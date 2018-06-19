# Code Enforcement All Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/code-enforcement-all-cases) |
| Metadata | [Link](https://data.nola.gov/api/views/u6yx-v2tw) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/u6yx-v2tw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/u6yx-v2tw/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | u6yx-v2tw |
| Name | Code Enforcement All Cases |
| Category | Housing, Land Use, and Blight |
| Tags | blightstatus, case, violation |
| Created | 2013-09-30T05:52:28Z |
| Publication Date | 2013-12-11T15:13:40Z |

## Description

Code Enforcement All Cases. Connected to http://blightstatus.nola.gov/.

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
| No       |                | titleresearch     | TitleResearch     | calendar_date | calendar_date |
| No       |                | recordationdate   | RecordationDate   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = statdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = casefiled,initinspection,prevhearingdate,nexthearingdate,permitfiling,geoaddress,lastupload,titleresearch,recordationdate
```

## Data Commands

```ls
series e:u6yx-v2tw d:2016-09-27T00:00:00.000Z t:keystatus="The property was inspected on 09/27/2016 with a finding of ""Violation: No WIP"". The file is now awaiting title research before it can be set for a hearing." t:location="1645 Charbonnet St" t:zipcode=70117 t:initinspresult="Violation: No WIP" t:o_c=Open t:state=LA t:stage="2 - Title Research" t:caseno=16-09594-MPM t:caseid=216955 t:city="New Orleans" m:geopin=41121090 m:xpos=3699297.38553 m:ypos=535780.9872

series e:u6yx-v2tw d:2017-03-04T00:00:00.000Z t:keystatus="The property was inspected on 03/04/2017 with a finding of ""No Violation"". The file was subsequently closed." t:location="48580 Piety St" t:zipcode=70117 t:initinspresult="No Violation" t:o_c=Closed t:state=LA t:stage="6 - Case Closed" t:caseno=17-00948-MPM t:caseid=221684 t:city="New Orleans" m:geopin=41071460 m:xpos=3690827.4871 m:ypos=539902.96153

series e:u6yx-v2tw d:2017-03-06T00:00:00.000Z t:keystatus="The property was inspected on 03/06/2017 with a finding of ""Violation: No WIP"". The file is now awaiting title research before it can be set for a hearing." t:location="13 N Rampart St" t:initinspresult="Violation: No WIP" t:o_c=Open t:stage="2 - Title Research" t:caseno=17-00940-MPM t:caseid=221676 m:xpos=3694612.83338 m:ypos=534184.25853
```

## Meta Commands

```ls
metric m:geopin p:integer l:GeoPIN t:dataTypeName=number

metric m:xpos p:double l:XPos t:dataTypeName=number

metric m:ypos p:double l:YPos t:dataTypeName=number

entity e:u6yx-v2tw l:"Code Enforcement All Cases" t:url=https://data.nola.gov/api/views/u6yx-v2tw

property e:u6yx-v2tw t:meta.view v:id=u6yx-v2tw v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Code Enforcement All Cases"

property e:u6yx-v2tw t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:u6yx-v2tw t:meta.view.owner v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:displayName="Socrata Service Account"

property e:u6yx-v2tw t:meta.view.tableauthor v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:roleName=editor v:displayName="Socrata Service Account"

property e:u6yx-v2tw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| o_c    | caseno       | location                     | stage              | keystatus                                                                                                                                                   | statdate            | casefiled           | initinspection      | initinspresult    | prevhearingdate | prevhearingresult | nexthearingdate | lastpermit    | permitfiling        | permittype                                 | permitstatus             | geoaddress               | city        | state | zipcode | geopin   | xpos          | ypos         | caseid | lastupload          | titleresearch | recordationdate | 
| ====== | ============ | ============================ | ================== | =========================================================================================================================================================== | =================== | =================== | =================== | ================= | =============== | ================= | =============== | ============= | =================== | ========================================== | ======================== | ======================== | =========== | ===== | ======= | ======== | ============= | ============ | ====== | =================== | ============= | =============== | 
| Open   | 16-09594-MPM | 1645 Charbonnet St           | 2 - Title Research | The property was inspected on 09/27/2016 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2016-09-27T00:00:00 | 2016-09-06T16:51:18 | 2016-09-27T00:00:00 | Violation: No WIP |                 |                   |                 |               |                     |                                            |                          | 1645 Charbonnet St       | New Orleans | LA    | 70117   | 41121090 | 3699297.38553 | 535780.9872  | 216955 | 2017-03-22T23:10:00 |               |                 | 
| Closed | 17-00948-MPM | 48580 Piety St               | 6 - Case Closed    | The property was inspected on 03/04/2017 with a finding of "No Violation". The file was subsequently closed.                                                | 2017-03-04T00:00:00 | 2017-02-07T13:54:47 | 2017-03-04T00:00:00 | No Violation      |                 |                   |                 |               |                     |                                            |                          | 2142 Piety St            | New Orleans | LA    | 70117   | 41071460 | 3690827.4871  | 539902.96153 | 221684 | 2017-03-22T23:10:00 |               |                 | 
| Open   | 17-00940-MPM | 13 N Rampart St              | 2 - Title Research | The property was inspected on 03/06/2017 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2017-03-06T00:00:00 | 2017-02-07T11:31:16 | 2017-03-06T00:00:00 | Violation: No WIP |                 |                   |                 |               |                     |                                            |                          |                          |             |       |         |          | 3694612.83338 | 534184.25853 | 221676 | 2017-03-07T23:08:52 |               |                 | 
| Open   | 17-02638-MPM | 1433-1435 Elysian Fields Ave | 1 - Inspection     | The case was filed on 03/23/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-23T09:16:30 | 2017-03-23T09:16:30 |                     |                   |                 |                   |                 | 14-10044-EVAC | 2014-03-31T00:00:00 | Electrical Vacancy                         | Permit Issued            | 1435 Elysian Fields Ave  | New Orleans | LA    | 70117   | 41064941 | 3685044.14825 | 537706.10145 | 224376 | 2017-03-23T23:08:59 |               |                 | 
| Open   | 17-02652-MPM | 1509 General Collins Ave     | 1 - Inspection     | The case was filed on 03/23/2017 and the property is awaiting inspection to proceed further.                                                                | 2017-03-23T13:10:15 | 2017-03-23T13:10:15 |                     |                   |                 |                   |                 |               |                     |                                            |                          | 1509 General Collins Ave | New Orleans | LA    | 70114   | 41006526 | 3698435.50807 | 525640.15321 | 224390 | 2017-03-23T23:08:59 |               |                 | 
| Open   | 17-02643-MPM | 701 Charbonnet St            | 2 - Title Research | The property was inspected on 04/10/2017 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2017-04-10T00:00:00 | 2017-03-23T10:41:15 | 2017-04-10T00:00:00 | Violation: No WIP |                 |                   |                 | 11ELC-10372   | 2011-10-03T00:00:00 | Electrical Service / Circuit / Feeder      | Permit Issuance - Active | 701 Charbonnet St        | New Orleans | LA    | 70117   | 41125934 | 3698280.78655 | 532152.60108 | 224381 | 2017-04-10T23:09:04 |               |                 | 
| Closed | 16-09002-MPM | 39639 Brevard Ave            | 6 - Case Closed    | The case was filed on 08/29/2016 but has since been closed without further action.                                                                          | 2016-08-29T10:01:46 | 2016-08-29T10:01:46 |                     |                   |                 |                   |                 |               |                     |                                            |                          |                          |             |       |         |          | 3705730.24858 | 564460.64704 | 216363 | 2016-10-03T23:08:45 |               |                 | 
| Closed | 16-09587-MPM | 2322 Camp St                 | 6 - Case Closed    | The property was inspected on 10/03/2016 with a finding of "No Violation". The file was subsequently closed.                                                | 2016-10-03T00:00:00 | 2016-09-06T16:23:31 | 2016-10-03T00:00:00 | No Violation      |                 |                   |                 | 15-21425-RNVN | 2015-07-17T11:47:01 | Renovation (Non-Structural)                | Permit Issued            | 2322 Camp St             | New Orleans | LA    | 70130   | 41042930 | 3678178.37538 | 521993.7399  | 216948 | 2016-10-03T23:08:45 |               |                 | 
| Open   | 16-09593-MPM | 2635 Dante St                | 2 - Title Research | The property was inspected on 10/05/2016 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2016-10-05T00:00:00 | 2016-09-06T16:44:44 | 2016-10-05T00:00:00 | Violation: No WIP |                 |                   |                 | 10ELC-08330   | 2010-08-16T00:00:00 | Electrical Repair / Replacement / Addition | Permit Issuance - Active | 2635 Dante St            | New Orleans | LA    | 70118   | 41029248 | 3665035.15284 | 532771.06663 | 216954 | 2016-10-06T23:18:32 |               |                 | 
| Open   | 16-09595-MPM | 5745101 Chef Menteur Hwy     | 2 - Title Research | The property was inspected on 10/06/2016 with a finding of "Violation: No WIP". The file is now awaiting title research before it can be set for a hearing. | 2016-10-06T00:00:00 | 2016-09-06T16:55:40 | 2016-10-06T00:00:00 | Violation: No WIP |                 |                   |                 |               |                     |                                            |                          |                          |             |       |         |          | 3689294.26844 | 548772.06371 | 216956 | 2016-10-07T23:29:00 |               |                 | 
```