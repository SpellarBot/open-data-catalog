# Transportation Department Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-department-permits) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pubx-yq2d) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pubx-yq2d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pubx-yq2d/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pubx-yq2d |
| Name | Transportation Department Permits |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | permits, transportation, streets |
| Created | 2015-07-13T16:15:18Z |
| Publication Date | 2016-09-15T16:55:09Z |

## Description

Applications to the Chicago Department of Transportation for permits under its jurisdiction, which typically are permits to block or otherwise affect public streets in some way.  Because all permits start as applications, this dataset also serves as a list of permits granted.  See more information about CDOT permits at http://www.cityofchicago.org/city/en/depts/cdot/provdrs/construction_information/svcs/online-permit-portal.html.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | numeric metric | uniquekey                    | UNIQUEKEY                    | number        | text          |
| Yes      | series tag     | applicationnumber            | APPLICATIONNUMBER            | text          | text          |
| Yes      | series tag     | applicationtype              | APPLICATIONTYPE              | text          | text          |
| Yes      | series tag     | applicationdescription       | APPLICATIONDESCRIPTION       | text          | text          |
| Yes      | series tag     | worktype                     | WORKTYPE                     | text          | text          |
| Yes      | series tag     | worktypedescription          | WORKTYPEDESCRIPTION          | text          | text          |
| Yes      | series tag     | applicationstatus            | APPLICATIONSTATUS            | text          | text          |
| Yes      | series tag     | currentmilestone             | CURRENTMILESTONE             | text          | text          |
| No       |                | applicationstartdate         | APPLICATIONSTARTDATE         | calendar_date | calendar_date |
| Yes      | time           | applicationenddate           | APPLICATIONENDDATE           | calendar_date | calendar_date |
| No       |                | applicationprocesseddate     | APPLICATIONPROCESSEDDATE     | calendar_date | calendar_date |
| No       |                | applicationissueddate        | APPLICATIONISSUEDDATE        | calendar_date | calendar_date |
| No       |                | applicationfinalizeddate     | APPLICATIONFINALIZEDDATE     | calendar_date | calendar_date |
| No       |                | applicationexpiredate        | APPLICATIONEXPIREDATE        | calendar_date | calendar_date |
| Yes      | series tag     | applicationname              | APPLICATIONNAME              | text          | text          |
| Yes      | series tag     | comments                     | COMMENTS                     | text          | text          |
| Yes      | numeric metric | totalfees                    | TOTALFEES                    | money         | money         |
| Yes      | numeric metric | waivedfees                   | WAIVEDFEES                   | money         | money         |
| Yes      | series tag     | primarycontactlast           | PRIMARYCONTACTLAST           | text          | text          |
| Yes      | series tag     | primarycontactfirst          | PRIMARYCONTACTFIRST          | text          | text          |
| Yes      | series tag     | primarycontactmiddle         | PRIMARYCONTACTMIDDLE         | text          | text          |
| Yes      | series tag     | primarycontactstreet         | PRIMARYCONTACTSTREET         | text          | text          |
| Yes      | series tag     | primarycontactstreet2        | PRIMARYCONTACTSTREET2        | text          | text          |
| Yes      | series tag     | primarycontactcity           | PRIMARYCONTACTCITY           | text          | text          |
| Yes      | series tag     | primarycontactstate          | PRIMARYCONTACTSTATE          | text          | text          |
| Yes      | series tag     | primarycontactzip            | PRIMARYCONTACTZIP            | text          | text          |
| Yes      | series tag     | emergencycontactname         | EMERGENCYCONTACTNAME         | text          | text          |
| Yes      | series tag     | lastinspectionnumber         | LASTINSPECTIONNUMBER         | text          | number        |
| Yes      | series tag     | lastinspectiontype           | LASTINSPECTIONTYPE           | text          | text          |
| Yes      | series tag     | lastinsptypedescr            | LASTINSPTYPEDESCR            | text          | text          |
| No       |                | lastinspectiondate           | LASTINSPECTIONDATE           | calendar_date | calendar_date |
| Yes      | series tag     | lastinspectionresult         | LASTINSPECTIONRESULT         | text          | text          |
| Yes      | series tag     | streetnumberfrom             | STREETNUMBERFROM             | text          | number        |
| Yes      | series tag     | streetnumberto               | STREETNUMBERTO               | text          | number        |
| Yes      | series tag     | direction                    | DIRECTION                    | text          | text          |
| Yes      | series tag     | streetname                   | STREETNAME                   | text          | text          |
| Yes      | series tag     | suffix                       | SUFFIX                       | text          | text          |
| Yes      | series tag     | placement                    | PLACEMENT                    | text          | text          |
| Yes      | series tag     | streetclosure                | STREETCLOSURE                | text          | text          |
| Yes      | series tag     | detail                       | DETAIL                       | text          | text          |
| Yes      | series tag     | parkingmeterpostingorbagging | PARKINGMETERPOSTINGORBAGGING | text          | text          |
| Yes      | numeric metric | xcoordinate                  | XCOORDINATE                  | number        | number        |
| Yes      | numeric metric | ycoordinate                  | YCOORDINATE                  | number        | number        |
| No       |                | latitude                     | LATITUDE                     | number        | number        |
| No       |                | longitude                    | LONGITUDE                    | number        | number        |
```

## Time Field

```ls
Value = applicationenddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applicationstartdate,applicationprocesseddate,applicationissueddate,applicationfinalizeddate,applicationexpiredate,lastinspectiondate,latitude,longitude
```

## Data Commands

```ls
series e:pubx-yq2d d:2014-08-30T00:00:00.000Z t:primarycontactstate=IL t:detail="MILLION FATHER MARCH PARADE;;ASSEMBLY AREA;   4400 SOUTH COTTAGE GROVE AVENUE;;PROPOSED ROUTE;   PROCEED SOUTHBOUND ON COTTAGE GROVE FROM 4400 TO 5100 SOUTH COTTAGE GROVE AVENUE.  DISBAND AS NEEDED.;;CURBLANE" t:streetclosure=NA t:primarycontactzip=60653 t:primarycontactlast="THE BLACKSTAR PROJECT" t:direction=S t:worktypedescription=Parade t:primarycontactstreet="3509 S. KING DRIVE - SUITE 2B" t:suffix=AVE t:applicationstatus=Closed t:applicationtype=DOT_SE t:applicationdescription="DOT Special Event Permit" t:currentmilestone=Complete t:applicationname=472599223 t:emergencycontactname="PHILLIP JACKSON" t:worktype=Parade t:streetnumberfrom=4400 t:primarycontactcity=CHICAGO t:streetnumberto=4400 t:applicationnumber=DOT411477 t:streetname="COTTAGE GROVE" m:xcoordinate=1182295 m:ycoordinate=1875979 m:uniquekey=45453013470

series e:pubx-yq2d d:2014-07-09T00:00:00.000Z t:primarycontactstate=IL t:streetclosure=NA t:primarycontactzip=60609 t:primarycontactlast="SEVEN-D CONSTRUCTION CO" t:direction=S t:worktypedescription="Opening in the Public Way" t:primarycontactstreet="2000 W 43rd St" t:suffix=AVE t:applicationstatus=Closed t:applicationtype=DOT_PWO t:applicationdescription="DOT Public Way Opening" t:currentmilestone=Complete t:applicationname=466061202 t:emergencycontactname="MAURO GAVILANES" t:worktype=GenOpening t:streetnumberfrom=4439 t:primarycontactcity=CHICAGO t:comments="APS 1" t:streetnumberto=4439 t:applicationnumber=DOT305988 t:streetname=KOMENSKY m:xcoordinate=1150136 m:ycoordinate=1874736 m:uniquekey=349038115859

series e:pubx-yq2d d:2016-06-26T23:59:59.000Z t:primarycontactstate=IL t:placement=CURBLANE t:primarycontactzip=60804 t:primarycontactlast="CITY WIDE DISPOSAL INC" t:direction=N t:primarycontactstreet="5001 W 40th St" t:lastinspectionresult=Completed t:lastinspectiontype=DOT_DMPSTR t:suffix=AVE t:lastinsptypedescr="DOT Dumpster Inspection" t:applicationstatus=Closed t:lastinspectionnumber=883131 t:applicationtype=DOT_DMPSTR t:applicationdescription="DOT Dumpster Permit" t:currentmilestone=Complete t:emergencycontactname=Liz t:streetnumberfrom=6724 t:primarycontactcity=CICERO t:comments="construction dumpster per customer" t:streetnumberto=6724 t:applicationnumber=DOT655797 t:streetname=AVONDALE m:xcoordinate=1123978 m:ycoordinate=1943987 m:uniquekey=700871104898 m:totalfees=50
```

## Meta Commands

```ls
metric m:uniquekey p:long l:UNIQUEKEY d:"A unique identifier for each record." t:dataTypeName=number

metric m:totalfees p:integer l:TOTALFEES d:"Total permit fees for this permit calculated based on the work being carried out and location. See fee schedule for further information, available on the CDOT permit portal, http://www.cityofchicago.org/city/en/depts/cdot/provdrs/construction_information/svcs/online-permit-portal.html." t:dataTypeName=money

metric m:waivedfees p:integer l:WAIVEDFEES d:"If any fees were waived for this permit, the amount waived will be here. Possible reasons for waived fees include city contracts, city departments, ordinances, and franchise agreements with the City." t:dataTypeName=money

metric m:xcoordinate p:integer l:XCOORDINATE d:"X coordinate of the start of the address range in State Plane Illinois East NAD 1983 projection." t:dataTypeName=number

metric m:ycoordinate p:integer l:YCOORDINATE d:"Y coordinate of the start of the address range in State Plane Illinois East NAD 1983 projection." t:dataTypeName=number

entity e:pubx-yq2d l:"Transportation Department Permits" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/pubx-yq2d

property e:pubx-yq2d t:meta.view v:id=pubx-yq2d v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Transportation Department Permits" v:attribution="City of Chicago"

property e:pubx-yq2d t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:pubx-yq2d t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| uniquekey    | applicationnumber | applicationtype | applicationdescription         | worktype   | worktypedescription                                                 | applicationstatus | currentmilestone | applicationstartdate | applicationenddate  | applicationprocesseddate | applicationissueddate | applicationfinalizeddate | applicationexpiredate | applicationname | comments                                                                                                                                | totalfees | waivedfees | primarycontactlast          | primarycontactfirst | primarycontactmiddle | primarycontactstreet          | primarycontactstreet2 | primarycontactcity | primarycontactstate | primarycontactzip | emergencycontactname | lastinspectionnumber | lastinspectiontype | lastinsptypedescr                  | lastinspectiondate  | lastinspectionresult | streetnumberfrom | streetnumberto | direction | streetname    | suffix | placement | streetclosure | detail                                                                                                                                                                                                      | parkingmeterpostingorbagging | xcoordinate | ycoordinate | latitude     | longitude     | 
| ============ | ================= | =============== | ============================== | ========== | =================================================================== | ================= | ================ | ==================== | =================== | ======================== | ===================== | ======================== | ===================== | =============== | ======================================================================================================================================= | ========= | ========== | =========================== | =================== | ==================== | ============================= | ===================== | ================== | =================== | ================= | ==================== | ==================== | ================== | ================================== | =================== | ==================== | ================ | ============== | ========= | ============= | ====== | ========= | ============= | =========================================================================================================================================================================================================== | ============================ | =========== | =========== | ============ | ============= | 
| 45453013470  | DOT411477         | DOT_SE          | DOT Special Event Permit       | Parade     | Parade                                                              | Closed            | Complete         | 2014-08-30T00:00:00  | 2014-08-30T00:00:00 | 2014-08-13T00:00:00      | 2014-08-13T12:53:43   | 2014-08-31T00:01:56      | 2014-08-30T00:00:00   | 472599223       |                                                                                                                                         |           |            | THE BLACKSTAR PROJECT       |                     |                      | 3509 S. KING DRIVE - SUITE 2B |                       | CHICAGO            | IL                  | 60653             | PHILLIP JACKSON      |                      |                    |                                    |                     |                      | 4400             | 4400           | S         | COTTAGE GROVE | AVE    |           | NA            | MILLION FATHER MARCH PARADE;;ASSEMBLY AREA; 4400 SOUTH COTTAGE GROVE AVENUE;;PROPOSED ROUTE; PROCEED SOUTHBOUND ON COTTAGE GROVE FROM 4400 TO 5100 SOUTH COTTAGE GROVE AVENUE. DISBAND AS NEEDED.;;CURBLANE |                              | 1182295     | 1875979     | 41.814903924 | -87.606827264 | 
| 349038115859 | DOT305988         | DOT_PWO         | DOT Public Way Opening         | GenOpening | Opening in the Public Way                                           | Closed            | Complete         | 2014-06-09T00:00:00  | 2014-07-09T00:00:00 | 2014-06-09T00:00:00      | 2014-06-09T12:32:58   | 2014-07-10T00:01:44      | 2014-07-09T00:00:00   | 466061202       | APS 1                                                                                                                                   |           |            | SEVEN-D CONSTRUCTION CO     |                     |                      | 2000 W 43rd St                |                       | CHICAGO            | IL                  | 60609             | MAURO GAVILANES      |                      |                    |                                    |                     |                      | 4439             | 4439           | S         | KOMENSKY      | AVE    |           | NA            |                                                                                                                                                                                                             |                              | 1150136     | 1874736     | 41.812181124 | -87.724823955 | 
| 700871104898 | DOT655797         | DOT_DMPSTR      | DOT Dumpster Permit            |            |                                                                     | Closed            | Complete         | 2016-06-24T00:00:00  | 2016-06-26T23:59:59 | 2016-06-24T15:05:51      | 2016-06-24T15:06:00   | 2016-07-05T10:24:08      | 2016-06-26T23:59:59   |                 | construction dumpster per customer                                                                                                      | 50        |            | CITY WIDE DISPOSAL INC      |                     |                      | 5001 W 40th St                |                       | CICERO             | IL                  | 60804             | Liz                  | 883131               | DOT_DMPSTR         | DOT Dumpster Inspection            | 2016-07-05T10:23:00 | Completed            | 6724             | 6724           | N         | AVONDALE      | AVE    | CURBLANE  |               |                                                                                                                                                                                                             |                              | 1123978     | 1943987     | 42.002682559 | -87.819250885 | 
| 5531808449   | DOT510127         | DOT_OCC         | DOT Occupy the Pub. ROW Permit | GenOccupy  | Work Vehicles, Temporary Driveways, Barricades, Operating Equipment | Closed            | Complete         | 2013-04-30T00:00:00  | 2013-05-30T00:00:00 | 2013-04-29T00:00:00      | 2013-04-29T15:12:14   | 2013-05-31T00:01:59      | 2013-05-30T00:00:00   | 361977144       |                                                                                                                                         |           |            | ComED North                 |                     |                      | 3 Lincoln Center              |                       | Oakbrook           | IL                  |                   | JIM TORRES           | 787792               | DOT_OCC            | DOT Occupy the Pub. ROW Inspection | 2013-10-03T00:00:00 | Completed            | 2400             | 2900           | S         | HILLOCK       | AVE    |           | NA            |                                                                                                                                                                                                             |                              |             |             |              |               | 
| 53951073149  | DOT496457         | DOT_DMPSTR      | DOT Dumpster Permit            |            |                                                                     | Closed            | Complete         | 2015-10-14T00:00:00  | 2015-10-14T00:00:00 | 2015-10-12T00:00:00      | 2015-10-12T09:04:49   | 2015-10-15T00:02:09      | 2015-10-14T00:00:00   | 578595347       |                                                                                                                                         | 50        |            | BOLT SCAVENGER SERVICES INC |                     |                      | 5819 W Ogden Ave              |                       | CICERO             | IL                  | 60804             | peter bolt           |                      |                    |                                    |                     |                      | 6212             | 6222           | S         | MCVICKER      | AVE    | CURBLANE  |               |                                                                                                                                                                                                             |                              | 1137104     | 1862644     | 41.779239273 | -87.772915509 | 
| 398510186528 | DOT355460         | DOT_PWO         | DOT Public Way Opening         | GenOpening | Opening in the Public Way                                           | Closed            | Complete         | 2015-04-22T00:00:00  | 2015-05-22T00:00:00 | 2015-04-22T00:00:00      | 2015-04-22T10:21:28   | 2015-05-23T00:02:44      | 2015-05-22T00:00:00   | 561280985       | - SR Input By: A. BROWN                                                                                                                 |           |            | DWM                         |                     |                      | 1000 E OHIO ST                |                       | CHICAGO            | IL                  | 60611-3416        | ALFRED BROWN         |                      |                    |                                    |                     |                      | 1648             | 1648           | S         | HARDING       | AVE    |           | NA            | Subcontractor: Williams Concrete                                                                                                                                                                            |                              | 1150294     | 1891227     | 41.857431252 | -87.723816364 | 
| 352695120753 | DOT309645         | DOT_PWO         | DOT Public Way Opening         | GenOpening | Opening in the Public Way                                           | Closed            | Complete         | 2014-06-30T00:00:00  | 2014-07-30T00:00:00 | 2014-06-30T00:00:00      | 2014-06-30T10:32:49   | 2014-07-31T00:01:36      | 2014-07-30T00:00:00   | 468153817       | - SR Input By: B. MCKENNIE                                                                                                              |           |            | DWM                         |                     |                      | 1000 E OHIO ST                |                       | CHICAGO            | IL                  | 60611-3416        | BARBARA MCKENNIE     |                      |                    |                                    |                     |                      | 8629             | 8629           | S         | CHAPPEL       | AVE    |           | NA            |                                                                                                                                                                                                             |                              | 1191387     | 1848036     | 41.738011606 | -87.57438346  | 
| 30004750999  | DOT256997         | DOT_PWO         | DOT Public Way Opening         | GenOpening | Opening in the Public Way                                           | Closed            | Complete         | 2013-08-12T00:00:00  | 2013-10-12T00:00:00 | 2013-08-07T00:00:00      | 2013-08-07T16:44:08   | 2013-10-13T00:01:33      | 2013-10-12T00:00:00   | 371997287       | MQ AS A SUB CONTRACTOR.                                                                                                                 |           |            | SEVEN-D CONSTRUCTION CO     |                     |                      | 2000 W 43rd St                |                       | CHICAGO            | IL                  | 60609             | PAT                  |                      |                    |                                    |                     |                      | 4548             | 4548           | N         | CLAREMONT     | AVE    |           | NA            |                                                                                                                                                                                                             |                              | 1159835     | 1930343     | 41.96457758  | -87.687713785 | 
| 2445101      | DOT201460         | DOT_TRUCK       | DOT Truck Routing Permits      | OWeight    | Overweight Vehicle                                                  | Closed            | Complete         | 2014-03-05T00:00:00  | 2014-03-19T00:00:00 | 2014-03-03T00:00:00      | 2014-03-04T11:56:24   | 2014-03-20T00:01:42      | 2014-03-19T00:00:00   | 456292021       |                                                                                                                                         | 150       |            | Andersen Concrete Pumping   |                     |                      | 60 E Taft Dr                  |                       | SOUTH HOLLAND      | IL                  | 60473             | Monica Dorsett       |                      |                    |                                    |                     |                      |                  |                |           |               |        |           |               |                                                                                                                                                                                                             |                              |             |             |              |               | 
| 48179714485  | DOT438744         | DOT_DMPSTR      | DOT Dumpster Permit            |            |                                                                     | Closed            | Complete         | 2013-07-25T00:00:00  | 2013-08-23T00:00:00 | 2013-07-25T00:00:00      | 2013-07-26T15:16:55   | 2013-08-24T00:03:13      | 2013-08-23T00:00:00   | 370688065       | AUTO-ISSUE PROCESS - The applicant has specified a City Contract Number - T889087108-1. A specified Location falls within a Moratorium. | 0         |            | NATIONAL WASTE SERVICE INC  |                     |                      | 2608 S Damen Ave              |                       | CHICAGO            | IL                  | 60608             | Petra                | 773145               | DOT_DMPSTR         | DOT Dumpster Inspection            | 2014-05-23T00:00:00 | Completed            | 5100             | 5100           | S         | WOODLAWN      | AVE    | CURBLANE  |               |                                                                                                                                                                                                             |                              | 1185054     | 1871406     | 41.802292773 | -87.596852689 | 
```