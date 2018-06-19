# Code Violation Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/code-violation-cases-332c9) |
| Metadata | [Link](https://data.seattle.gov/api/views/dk8m-pdjf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/dk8m-pdjf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/dk8m-pdjf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | dk8m-pdjf |
| Name | Code Violation Cases |
| Attribution | Seattle Department of Planning and Development |
| Category | Community |
| Tags | dpd, code violation, code enforcement |
| Created | 2010-08-11T21:48:57Z |
| Publication Date | 2017-01-23T16:57:15Z |

## Description

Current and historical information about complaints received that have become cases for further investigation.

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag  | case_number                     | Case Number                     | text          | text          |
| Yes      | series tag  | case_type                       | Case Type                       | text          | text          |
| No       |             | address                         | Address                         | text          | text          |
| Yes      | series tag  | description                     | Description                     | text          | text          |
| Yes      | series tag  | case_group                      | Case Group                      | text          | text          |
| Yes      | time        | date_case_created               | Date Case Created               | calendar_date | calendar_date |
| No       |             | last_inspection_date            | Last Inspection Date            | calendar_date | calendar_date |
| Yes      | series tag  | last_inspection_result          | Last Inspection Result          | text          | text          |
| Yes      | series tag  | status                          | Status                          | text          | text          |
| Yes      | series tag  | permit_and_complaint_status_url | Permit and Complaint Status URL | url           | url           |
| No       |             | latitude                        | Latitude                        | number        | number        |
| No       |             | longitude                       | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = date_case_created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,last_inspection_date,latitude,longitude
```

## Data Commands

```ls
series e:dk8m-pdjf d:2017-01-20T00:00:00.000Z t:case_number=1039286 t:status="ADMINISTRATIVE CLOSURE" t:description="Issuance of Owner's Certification of No Displacement." t:case_type="TENANT RELOCATION ORDINANCE" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039286" t:case_group="TENANT RELOCATION ASSIST ORD" m:row_number.dk8m-pdjf=1

series e:dk8m-pdjf d:2017-01-19T00:00:00.000Z t:last_inspection_result=FAILED t:case_number=1039276 t:status=OPEN t:description="01/19/17 DW OBSERVED BOAT ON TRAILER WITH FLAT TIRES." t:case_type=CITATION t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039276" t:case_group=ZONING m:row_number.dk8m-pdjf=2

series e:dk8m-pdjf d:2017-01-19T00:00:00.000Z t:case_number=1039274 t:status="ADMINISTRATIVE CLOSURE" t:description="Issuance of Certification of No Displacement." t:case_type="TENANT RELOCATION ORDINANCE" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039274" t:case_group="TENANT RELOCATION ASSIST ORD" m:row_number.dk8m-pdjf=3
```

## Meta Commands

```ls
metric m:row_number.dk8m-pdjf p:long l:"Row Number"

entity e:dk8m-pdjf l:"Code Violation Cases" t:attribution="Seattle Department of Planning and Development" t:url=https://data.seattle.gov/api/views/dk8m-pdjf

property e:dk8m-pdjf t:meta.view v:id=dk8m-pdjf v:category=Community v:attributionLink=http://www.seattle.gov/dpd v:averageRating=0 v:name="Code Violation Cases" v:attribution="Seattle Department of Planning and Development"

property e:dk8m-pdjf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:dk8m-pdjf t:meta.view.owner v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:displayName="Department of Planning and Development"

property e:dk8m-pdjf t:meta.view.tableauthor v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:roleName=publisher v:displayName="Department of Planning and Development"
```

## Top Records

```ls
| case_number | case_type                   | address                | description                                                                                                        | case_group                   | date_case_created   | last_inspection_date | last_inspection_result | status                 | permit_and_complaint_status_url                                          | latitude    | longitude     | 
| =========== | =========================== | ====================== | ================================================================================================================== | ============================ | =================== | ==================== | ====================== | ====================== | ======================================================================== | =========== | ============= | 
| 1039286     | TENANT RELOCATION ORDINANCE | 1724 11TH AVE          | Issuance of Owner's Certification of No Displacement.                                                              | TENANT RELOCATION ASSIST ORD | 2017-01-20T00:00:00 |                      |                        | ADMINISTRATIVE CLOSURE | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039286, null] | 47.61718246 | -122.31782678 | 
| 1039276     | CITATION                    | 1026 S DONOVAN ST      | 01/19/17 DW OBSERVED BOAT ON TRAILER WITH FLAT TIRES.                                                              | ZONING                       | 2017-01-19T00:00:00 | 2017-01-19T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039276, null] | 47.52577959 | -122.31918851 | 
| 1039274     | TENANT RELOCATION ORDINANCE | 2027 S WASHINGTON ST   | Issuance of Certification of No Displacement.                                                                      | TENANT RELOCATION ASSIST ORD | 2017-01-19T00:00:00 |                      |                        | ADMINISTRATIVE CLOSURE | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039274, null] | 47.60063701 | -122.30515026 | 
| 1039267     | HOUSING / ZONING            | 4840 CALIFORNIA AVE SW | 1/17/17 rf Observed subject property to have extensive water intrusion and water damage from leaking roof.         | HOUSING                      | 2017-01-18T00:00:00 | 2017-01-17T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039267, null] | 47.55801855 | -122.38652805 | 
| 1039263     | HOUSING / ZONING            | 1414 S COLUMBIAN WAY   | 01/18/2017 ED- Several HBMC violation. Smoke det missing, leaking ceilings etc.                                    | HOUSING                      | 2017-01-18T00:00:00 | 2017-01-18T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039263, null] | 47.57199355 | -122.31429705 | 
| 1039262     | HOUSING / ZONING            | 706 S KING ST          | Land Use Code Violation - changes to exterior without permit in special review district                            | ZONING                       | 2017-01-17T00:00:00 | 2016-11-03T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039262, null] | 47.59852978 | -122.32322478 | 
| 1039257     | CITATION                    | 5009 35TH AVE SW       | 1/11/17 rf observed subject property to have overgrown vegetation encroaching onto the right of way.               | WEEDS AND VEGETATION         | 2017-01-17T00:00:00 | 2017-01-11T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039257, null] | 47.55707297 | -122.37668696 | 
| 1039256     | HOUSING / ZONING            | 13341 15TH AVE NE      | Alleged HBMC Violation: Complaint alleges moldy surfaces resulting from leaking bathroom fixtures (sink & toilet). | HOUSING                      | 2017-01-13T00:00:00 | 2017-01-13T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039256, null] | 47.72646065 | -122.31311357 | 
| 1039254     | HOUSING / ZONING            | 2410 E LYNN ST         | 1/13/17- Observed no heat in the unit, temp. is at 54 degrees.                                                     | HOUSING                      | 2017-01-13T00:00:00 | 2017-01-18T00:00:00  | PASSED                 | VOLUNTARY COMPLIANCE   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039254, null] | 47.63982828 | -122.30182736 | 
| 1039253     | CITATION                    | 7424 RAINIER AVE S     | Bradrick 1.13.17 Outdoor junk storage in the back yard.                                                            | ZONING                       | 2017-01-13T00:00:00 | 2017-01-13T00:00:00  | FAILED                 | OPEN                   | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=1039253, null] | 47.5351643  | -122.26972947 | 
```