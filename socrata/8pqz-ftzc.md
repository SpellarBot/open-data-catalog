# Code Enforcement Active Pipeline

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/code-enforcement-active-pipeline) |
| Metadata | [Link](https://data.nola.gov/api/views/8pqz-ftzc) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/8pqz-ftzc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/8pqz-ftzc/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 8pqz-ftzc |
| Name | Code Enforcement Active Pipeline |
| Category | Housing, Land Use, and Blight |
| Tags | blightstatus, active, case, violation |
| Created | 2013-09-30T05:18:13Z |
| Publication Date | 2013-10-03T21:27:14Z |

## Description

Code Enforcement Active Pipeline. Connected to http://blightstatus.nola.gov/.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | o_c               | O/C               | text          | text          |
| Yes      | series tag     | caseno            | CaseNo            | text          | text          |
| Yes      | series tag     | location          | Location          | text          | text          |
| Yes      | series tag     | stage             | Stage             | text          | text          |
| Yes      | series tag     | keystatus         | KeyStatus         | text          | text          |
| Yes      | time           | statdate          | StatDate          | calendar_date | calendar_date |
| No       |                | casefiled         | CaseFiled         | calendar_date | calendar_date |
| No       |                | initinspection    | InitInspection    | calendar_date | calendar_date |
| Yes      | series tag     | initinspresult    | InitInspResult    | text          | text          |
| No       |                | prevhearingdate   | PrevHearingDate   | text          | text          |
| Yes      | series tag     | prevhearingresult | PrevHearingResult | text          | text          |
| No       |                | nexthearingdate   | NextHearingDate   | text          | text          |
| Yes      | series tag     | lastpermit        | LastPermit        | text          | text          |
| No       |                | permitfiling      | PermitFiling      | calendar_date | calendar_date |
| Yes      | series tag     | permittype        | PermitType        | text          | text          |
| Yes      | series tag     | permitstatus      | PermitStatus      | text          | text          |
| No       |                | geoaddress        | GeoAddress        | text          | text          |
| Yes      | series tag     | city              | City              | text          | text          |
| Yes      | series tag     | state             | State             | text          | text          |
| Yes      | series tag     | zipcode           | Zipcode           | text          | text          |
| Yes      | numeric metric | geopin            | GeoPIN            | number        | number        |
| Yes      | numeric metric | xpos              | XPos              | number        | number        |
| Yes      | numeric metric | ypos              | YPos              | number        | number        |
| Yes      | series tag     | caseid            | CaseID            | text          | number        |
| No       |                | lastupload        | LastUpload        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = statdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = casefiled,initinspection,prevhearingdate,nexthearingdate,permitfiling,geoaddress,lastupload
```

## Data Commands

```ls
series e:8pqz-ftzc d:2017-03-20T15:25:05.000Z t:lastpermit=07BLD-04097 t:keystatus="The case was filed on 03/20/2017 and the property is awaiting inspection to proceed further." t:location="1917 Caffin Ave" t:permittype=Demolition t:zipcode=70117 t:o_c=Open t:state=LA t:permitstatus="Application Acceptance - Approved No Review" t:stage="1 - Inspection" t:caseno=17-02530-MPM t:caseid=224268 t:city="New Orleans" m:geopin=41124137 m:xpos=3698976.7713 m:ypos=536916.36468

series e:8pqz-ftzc d:2017-03-20T15:08:30.000Z t:lastpermit=12BLD-03763 t:keystatus="The case was filed on 03/20/2017 and the property is awaiting inspection to proceed further." t:location="8639 Colapissa St" t:permittype=Demolition t:zipcode=70118 t:o_c=Open t:state=LA t:permitstatus="Certificate of Occupancy" t:stage="1 - Inspection" t:caseno=17-02527-MPM t:caseid=224265 t:city="New Orleans" m:geopin=41029041 m:xpos=3665019.13991 m:ypos=534833.28775

series e:8pqz-ftzc d:2015-02-03T15:48:43.000Z t:lastpermit=06ELC-42086 t:keystatus="The case was filed on 02/03/2015 and the property is awaiting inspection to proceed further." t:location="3919 Baldwin Woods Rd" t:permittype="Electrical Repair / Replacement / Addition" t:zipcode=70131 t:o_c=Open t:state=LA t:permitstatus="Application Acceptance - Approved" t:stage="1 - Inspection" t:caseno=15-00721-MPM t:caseid=196925 t:city="New Orleans" m:geopin=41207112 m:xpos=3697730.13644 m:ypos=514000.86356
```

## Meta Commands

```ls
metric m:geopin p:integer l:GeoPIN t:dataTypeName=number

metric m:xpos p:double l:XPos t:dataTypeName=number

metric m:ypos p:double l:YPos t:dataTypeName=number

entity e:8pqz-ftzc l:"Code Enforcement Active Pipeline" t:url=https://data.nola.gov/api/views/8pqz-ftzc

property e:8pqz-ftzc t:meta.view v:id=8pqz-ftzc v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Code Enforcement Active Pipeline"

property e:8pqz-ftzc t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8pqz-ftzc t:meta.view.owner v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:displayName="Socrata Service Account"

property e:8pqz-ftzc t:meta.view.tableauthor v:id=7kk9-bewq v:screenName="J.B. Raasch" v:roleName=administrator v:displayName="J.B. Raasch"

property e:8pqz-ftzc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| o_c  | caseno       | location                     | stage              | keystatus                                                                                                                                                   | statdate            | casefiled           | initinspection      | initinspresult    | prevhearingdate | prevhearingresult | nexthearingdate     | lastpermit    | permitfiling        | permittype                                 | permitstatus                                | geoaddress               | city        | state | zipcode | geopin   | xpos          | ypos         | caseid | lastupload          | 
| ==== | ============ | ============================ | ================== | =========================================================================================================================================================== | =================== | =================== | =================== | ================= | =============== | ================= | =================== | ============= | =================== | ========================================== | =========================================== | ======================== | =========== | ===== | ======= | ======== | ============= | ============ | ====== | =================== | 
| Open | 17-02530-MPM | 1917 Caffin Ave              | 1 - Inspection     | The case was filed on 03/20/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-20T15:25:05 | 2017-03-20T15:25:05 |                     |                   |                 |                   |                     | 07BLD-04097   | 2007-05-18T00:00:00 | Demolition                                 | Application Acceptance - Approved No Review | 1917 Caffin Ave          | New Orleans | LA    | 70117   | 41124137 | 3698976.7713  | 536916.36468 | 224268 | 2017-03-20T23:00:15 | 
| Open | 17-02527-MPM | 8639 Colapissa St            | 1 - Inspection     | The case was filed on 03/20/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-20T15:08:30 | 2017-03-20T15:08:30 |                     |                   |                 |                   |                     | 12BLD-03763   | 2012-06-14T00:00:00 | Demolition                                 | Certificate of Occupancy                    | 8639 Colapissa St        | New Orleans | LA    | 70118   | 41029041 | 3665019.13991 | 534833.28775 | 224265 | 2017-03-20T23:00:15 | 
| Open | 15-00721-MPM | 3919 Baldwin Woods Rd        | 1 - Inspection     | The case was filed on 02/03/2015 and the property is awaiting inspection to proceed further.                                                                | 2015-02-03T15:48:43 | 2015-02-03T15:48:43 |                     |                   |                 |                   |                     | 06ELC-42086   | 2007-01-14T00:00:00 | Electrical Repair / Replacement / Addition | Application Acceptance - Approved           | 3919 Baldwin Woods Rd    | New Orleans | LA    | 70131   | 41207112 | 3697730.13644 | 514000.86356 | 196925 | 2015-02-03T23:00:22 | 
| Open | 15-00723-MPM | 2921-2925 Chippewa St        | 1 - Inspection     | The case was filed on 02/03/2015 and the property is awaiting inspection to proceed further.                                                                | 2015-02-03T16:00:44 | 2015-02-03T16:00:44 |                     |                   |                 |                   |                     | 14-36722-HDLC | 2014-11-24T14:52:12 | HDLC COA                                   | Permit Issued                               | 2921 Chippewa St         | New Orleans | LA    | 70115   | 41042296 | 3677277.45655 | 519205.23518 | 196927 | 2015-02-03T23:00:22 | 
| Open | 17-02526-MPM | 2218 S Robertson St          | 1 - Inspection     | The case was filed on 03/20/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-20T15:06:28 | 2017-03-20T15:06:28 |                     |                   |                 |                   |                     | 17-03350-ERPR | 2017-01-30T15:45:54 | Electrical Repair / Replacement / Addition | Meter Release                               | 2218 S Robertson St      | New Orleans | LA    | 70113   | 41039270 | 3675341.65697 | 526389.65056 | 224264 | 2017-03-20T23:00:15 | 
| Open | 17-02638-MPM | 1433-1435 Elysian Fields Ave | 1 - Inspection     | The case was filed on 03/23/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-23T09:16:30 | 2017-03-23T09:16:30 |                     |                   |                 |                   |                     | 14-10044-EVAC | 2014-03-31T00:00:00 | Electrical Vacancy                         | Permit Issued                               | 1435 Elysian Fields Ave  | New Orleans | LA    | 70117   | 41064941 | 3685044.14825 | 537706.10145 | 224376 | 2017-03-23T23:00:28 | 
| Open | 17-02652-MPM | 1509 General Collins Ave     | 1 - Inspection     | The case was filed on 03/23/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-23T13:10:15 | 2017-03-23T13:10:15 |                     |                   |                 |                   |                     |               |                     |                                            |                                             | 1509 General Collins Ave | New Orleans | LA    | 70114   | 41006526 | 3698435.50807 | 525640.15321 | 224390 | 2017-03-23T23:00:28 | 
| Open | 17-02643-MPM | 701 Charbonnet St            | 2 - Title Research | The property was inspected on 04/10/2017 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2017-04-10T00:00:00 | 2017-03-23T10:41:15 | 2017-04-10T00:00:00 | Violation: No WIP |                 |                   |                     | 11ELC-10372   | 2011-10-03T00:00:00 | Electrical Service / Circuit / Feeder      | Permit Issuance - Active                    | 701 Charbonnet St        | New Orleans | LA    | 70117   | 41125934 | 3698280.78655 | 532152.60108 | 224381 | 2017-04-10T23:00:16 | 
| Open | 17-02642-MPM | 707 Charbonnet St            | 2 - Title Research | The property was inspected on 04/10/2017 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2017-04-10T00:00:00 | 2017-03-23T10:37:20 | 2017-04-10T00:00:00 | Violation: No WIP |                 |                   |                     | 11ELC-10371   | 2011-10-03T00:00:00 | Electrical Service / Circuit / Feeder      | Permit Issuance - Active                    | 707 Charbonnet St        | New Orleans | LA    | 70117   | 41126032 | 3698293.52068 | 532216.2717  | 224380 | 2017-04-10T23:00:16 | 
| Open | 17-02524-MPM | 1912 Josephine St            | 3 - Hearing        | Notice has been sent of an upcoming hearing on 05/16/2017.                                                                                                  | 2017-04-20T08:51:00 | 2017-03-20T14:53:01 | 2017-04-12T00:00:00 | Violation: No WIP |                 |                   | 2017-05-16T09:15:00 | B01004771     | 2001-10-03T00:00:00 | Building - SPIN                            | Permit Issued                               | 1912 Josephine St        | New Orleans | LA    | 70113   | 41038700 | 3677017.98363 | 525048.41721 | 224262 | 2017-04-20T23:00:17 | 
```