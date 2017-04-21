# HousingCodeViolations_01012011_Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housingcodeviolations-01012011-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/86ax-cfey) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/86ax-cfey/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/86ax-cfey/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 86ax-cfey |
| Name | HousingCodeViolations_01012011_Current |
| Attribution | City of Hartford |
| Category | Housing / Development |
| Tags | housing, code, housing code, violations, hartford, ct |
| Created | 2014-06-13T23:41:29Z |
| Publication Date | 2016-12-14T15:21:30Z |

## Description

Housing Code Violations 1/1/2011 to Current. Updated Nightly

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | case_number          | Case Number          | text          | text          |
| Yes      | series tag  | parcel_id            | Parcel ID            | text          | text          |
| Yes      | series tag  | location             | Location             | text          | text          |
| Yes      | series tag  | location_description | Location Description | text          | text          |
| Yes      | series tag  | title                | Title                | text          | text          |
| Yes      | series tag  | complaintviolation   | Complaint Violation  | text          | text          |
| Yes      | time        | reported             | Open Date            | calendar_date | calendar_date |
| No       |             | statusclosedate      | Closed Date          | calendar_date | calendar_date |
| Yes      | series tag  | department           | Global Entity Name   | text          | text          |
| Yes      | series tag  | zone                 | First Name           | text          | text          |
| Yes      | series tag  | ownername            | Last Name            | text          | text          |
| Yes      | series tag  | complianceinspector  | Inspector First Name | text          | text          |
| Yes      | series tag  | holdpermits          | Inspector Last Name  | text          | text          |
```

## Time Field

```ls
Value = reported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = statusclosedate
```

## Data Commands

```ls
series e:86ax-cfey d:2015-07-31T00:00:00.000Z t:parcel_id=239108038 t:title="Housing Code Inspector" t:case_number=56270 t:location="263 MARTIN ST" t:complaintviolation="Certificate of Apartment Occupancy" t:holdpermits=Sako t:zone="TIFFANY REALTY" t:complianceinspector=Albi m:row_number.86ax-cfey=1

series e:86ax-cfey d:2015-07-31T00:00:00.000Z t:parcel_id=240119103 t:title="Housing Code Inspector" t:case_number=56251 t:location="134 CLARK                          ST" t:complaintviolation="Certificate of Apartment Occupancy" t:location_description="APT # 2-NORTH" t:holdpermits=Sako t:zone="P B & D PROPERTIES LLC" t:complianceinspector=Albi m:row_number.86ax-cfey=2

series e:86ax-cfey d:2016-11-28T09:19:00.000Z t:parcel_id=200267155 t:title="Housing Code Inspector" t:case_number=HC-HCE-2016-000963 t:ownername=NIXON t:location="132 COLLINS ST, Apt # 209" t:complaintviolation="Housing Code Enforcement" t:holdpermits=Sako t:zone=CLARENCE t:complianceinspector=Albi m:row_number.86ax-cfey=3
```

## Meta Commands

```ls
metric m:row_number.86ax-cfey p:long l:"Row Number"

entity e:86ax-cfey l:HousingCodeViolations_01012011_Current t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/86ax-cfey

property e:86ax-cfey t:meta.view v:id=86ax-cfey v:category="Housing / Development" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name=HousingCodeViolations_01012011_Current v:attribution="City of Hartford"

property e:86ax-cfey t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:86ax-cfey t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:86ax-cfey t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| case_number        | parcel_id | location                  | location_description | title                  | complaintviolation                 | reported            | statusclosedate     | department | zone                            | ownername | complianceinspector | holdpermits | 
| ================== | ========= | ========================= | ==================== | ====================== | ================================== | =================== | =================== | ========== | =============================== | ========= | =================== | =========== | 
| 56270              | 239108038 | 263 MARTIN ST             |                      | Housing Code Inspector | Certificate of Apartment Occupancy | 2015-07-31T00:00:00 |                     |            | TIFFANY REALTY                  |           | Albi                | Sako        | 
| 56251              | 240119103 | 134 CLARK ST              | APT # 2-NORTH        | Housing Code Inspector | Certificate of Apartment Occupancy | 2015-07-31T00:00:00 | 2015-08-12T00:00:00 |            | P B & D PROPERTIES LLC          |           | Albi                | Sako        | 
| HC-HCE-2016-000963 | 200267155 | 132 COLLINS ST, Apt # 209 |                      | Housing Code Inspector | Housing Code Enforcement           | 2016-11-28T09:19:00 |                     |            | CLARENCE                        | NIXON     | Albi                | Sako        | 
| 49668              | 204534131 | 777 PARK ST               |                      | Housing Code Inspector | Housing Code Enforcement           | 2014-10-09T00:00:00 | 2014-12-02T00:00:00 |            | AS PELEUS LLC                   |           | Shawn               | Holloway    | 
| HC-HCE-2016-000955 | 179317077 | 60 NILES ST               |                      | Housing Code Inspector | Housing Code Enforcement           | 2016-11-22T15:32:00 |                     |            | JACQUELINE                      | BOOKER    | Elisha              | Barrows     | 
| HC-ES-2016-000014  | 164606226 | 496 BROADVIEW TER         |                      | Housing Code Inspector | Essential Services                 | 2016-06-14T12:08:00 | 2016-07-01T09:01:00 |            | WAYNE                           | FRANCIS   | Rochelle            | Little      | 
| 19467              | 187615060 | 439 HILLSIDE AV           |                      | Housing Code Inspector | Housing Code Enforcement           | 2011-02-14T00:00:00 |                     |            | FRANK                           | CINTINO   | Rochelle            | Little      | 
| 37539              | 240119103 | 132 CLARK ST              |                      | Housing Code Inspector | Housing Code Enforcement           | 2013-06-26T00:00:00 |                     |            | P B & D PROPERTIES LLC          |           | Tonja               | Nelson      | 
| 48338              | 204528152 | 342 JEFFERSON ST          |                      | Housing Code Inspector | Certificate of Apartment Occupancy | 2014-08-22T00:00:00 |                     |            | JEFFERSON LLC                   |           | Shawn               | Holloway    | 
| 58230              | 179318005 | 50 GILLETT ST             |                      | Housing Code Inspector | Certificate of Apartment Occupancy | 2015-10-20T00:00:00 | 2015-12-08T00:00:00 |            | ALL IN PROPERTY MANAGEMENT, LLC |           | Shawn               | Holloway    | 
```