# Code Enforcement All Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/code-enforcement-all-inspections) |
| Metadata | [Link](https://data.nola.gov/api/views/uh5a-f7uw) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/uh5a-f7uw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/uh5a-f7uw/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | uh5a-f7uw |
| Name | Code Enforcement All Inspections |
| Category | Housing, Land Use, and Blight |
| Tags | blightstatus, inspection |
| Created | 2013-09-30T06:21:05Z |
| Publication Date | 2014-01-22T08:45:30Z |

## Description

Code Enforcement All Inspections. Connected to http://blightstatus.nola.gov/.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | caseid           | CaseID           | text          | number        |
| Yes      | series tag  | caseno           | CaseNo           | text          | text          |
| Yes      | series tag  | location         | Location         | text          | text          |
| Yes      | time        | inspectiondate   | InspectionDate   | calendar_date | calendar_date |
| Yes      | series tag  | inspectiontype   | InspectionType   | text          | text          |
| Yes      | series tag  | inspectionresult | InspectionResult | text          | text          |
| Yes      | series tag  | inspector        | Inspector        | text          | text          |
| Yes      | series tag  | check            | Check            | text          | number        |
| Yes      | series tag  | hashid           | HashID           | text          | text          |
| No       |             | lastupload       | LastUpload       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = inspectiondate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lastupload
```

## Data Commands

```ls
series e:uh5a-f7uw d:2013-03-01T00:00:00.000Z t:inspectiontype=Inspection t:check=1 t:inspector="Alexander Smith" t:location="6218-6220 Wainwright Dr" t:inspectionresult="Violation: No WIP" t:hashid=8ba929dd44211bb0eebfc54ae9ec5747 t:caseno=09-002855 t:caseid=171833 m:row_number.uh5a-f7uw=1

series e:uh5a-f7uw d:2004-03-31T00:00:00.000Z t:inspectiontype="Posted Hearing Notice (CE)" t:check=1 t:inspector="Mark Smyth" t:location="1121 Charbonnet St" t:inspectionresult="Violation Exists" t:hashid=7f5aae04dcb79ac9d5506547b6cfae63 t:caseno=12-06545-BLGHT t:caseid=166455 m:row_number.uh5a-f7uw=2

series e:uh5a-f7uw d:2012-06-21T17:00:00.000Z t:inspectiontype=Inspection t:check=1 t:inspector="Karl Seyler" t:location="1121 Charbonnet St" t:inspectionresult="No Violations Found" t:hashid=cfa96f8343ce81b15487c47d64aec711 t:caseno=12-06545-BLGHT t:caseid=166455 m:row_number.uh5a-f7uw=3
```

## Meta Commands

```ls
metric m:row_number.uh5a-f7uw p:long l:"Row Number"

entity e:uh5a-f7uw l:"Code Enforcement All Inspections" t:url=https://data.nola.gov/api/views/uh5a-f7uw

property e:uh5a-f7uw t:meta.view v:id=uh5a-f7uw v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Code Enforcement All Inspections"

property e:uh5a-f7uw t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uh5a-f7uw t:meta.view.owner v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:displayName="Socrata Service Account"

property e:uh5a-f7uw t:meta.view.tableauthor v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:roleName=editor v:displayName="Socrata Service Account"

property e:uh5a-f7uw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| caseid | caseno          | location                | inspectiondate      | inspectiontype             | inspectionresult    | inspector       | check | hashid                           | lastupload          | 
| ====== | =============== | ======================= | =================== | ========================== | =================== | =============== | ===== | ================================ | =================== | 
| 171833 | 09-002855       | 6218-6220 Wainwright Dr | 2013-03-01T00:00:00 | Inspection                 | Violation: No WIP   | Alexander Smith | 1     | 8ba929dd44211bb0eebfc54ae9ec5747 | 2014-01-22T02:36:52 | 
| 166455 | 12-06545-BLGHT  | 1121 Charbonnet St      | 2004-03-31T00:00:00 | Posted Hearing Notice (CE) | Violation Exists    | Mark Smyth      | 1     | 7f5aae04dcb79ac9d5506547b6cfae63 | 2014-01-22T02:36:52 | 
| 166455 | 12-06545-BLGHT  | 1121 Charbonnet St      | 2012-06-21T17:00:00 | Inspection                 | No Violations Found | Karl Seyler     | 1     | cfa96f8343ce81b15487c47d64aec711 | 2014-01-22T02:36:52 | 
| 166462 | 12-06552-PRELIM | 5904 Annunciation St    | 2012-06-22T08:45:00 | Inspection                 | No Violations Found | Robert Heim     | 1     | 33eb22b597919912ac990b48941e974d | 2014-01-22T02:36:52 | 
| 166468 | 12-06558-PNBL   | 600 Ursulines Ave       | 2004-03-31T11:00:00 | Posted Judgment (CE)       | No Violation        |                 | 1     | 4e360e2caf2a0bfbafd785de54a0f25e | 2014-01-22T02:36:52 | 
| 166468 | 12-06558-PNBL   | 600 Ursulines Ave       | 2004-04-01T00:00:00 | Posted Hearing Notice (CE) | Violation Exists    | Mark Smyth      | 1     | 696e620b2a91618e9d56cc404f130ba9 | 2014-01-22T02:36:52 | 
| 166468 | 12-06558-PNBL   | 600 Ursulines Ave       | 2012-06-23T09:30:00 | Inspection                 | No Violations Found | Anthony Manalla | 1     | a6351969bdc38cdb25d73db43501ee39 | 2014-01-22T02:36:52 | 
| 166469 | 12-06559-PNBL   | 1013 Royal St           | 2012-06-23T10:00:00 | Inspection                 | Violation: No WIP   | Alton Sartin    | 1     | 1afa514882e77edd4caf88fa794a07e5 | 2014-01-22T02:36:52 | 
| 166470 | 12-06560-PNBL   | 927 Bourbon St          | 2012-06-23T11:00:00 | Inspection                 | No Violations Found | Angela Pender   | 1     | 75b8324cfae990b2c7543b4251215fd9 | 2014-01-22T02:36:52 | 
| 166471 | 12-06561-PNBL   | 919 Bourbon St          | 2012-06-23T11:30:00 | Inspection                 | No Violations Found | Amanda Beaulieu | 1     | d49abdc1c8492b205a16c407e2da9a55 | 2014-01-22T02:36:52 | 
```