# COA FUEL BY DEPARTMENT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-fuel-by-department) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5j2i-tq4k) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5j2i-tq4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5j2i-tq4k/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5j2i-tq4k |
| Name | COA FUEL BY DEPARTMENT |
| Category | Environmental |
| Created | 2015-06-29T16:01:09Z |
| Publication Date | 2017-01-11T11:01:20Z |

## Description

Breakdown of usage by Department and mileage per vehicle

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | dept_no               | DEPT_NO               | text      | number      |
| Yes      | series tag     | department            | DEPARTMENT            | text      | text        |
| Yes      | numeric metric | vehicle_count         | VEHICLE_COUNT         | number    | number      |
| Yes      | numeric metric | maint_dollars         | MAINT_DOLLARS         | number    | number      |
| Yes      | numeric metric | fuel_qty              | FUEL_QTY              | number    | number      |
| Yes      | numeric metric | avg_miles_per_vehicle | AVG_MILES_PER_VEHICLE | number    | number      |
| Yes      | numeric metric | total_miles           | TOTAL_MILES           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5j2i-tq4k d:2017-01-11T11:01:14.000Z t:department="PARD SUMMER FOOD PRO" t:dept_no=8630 m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:total_miles=0

series e:5j2i-tq4k d:2017-01-11T11:01:14.000Z t:department="PARKS & RECREATION" t:dept_no=8610 m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:total_miles=0

series e:5j2i-tq4k d:2017-04-06T10:00:26.000Z t:department="AVIATION CIP" t:dept_no=8180 m:vehicle_count=2 m:avg_miles_per_vehicle=0 m:maint_dollars=520.246667 m:total_miles=0
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:VEHICLE_COUNT t:dataTypeName=number

metric m:maint_dollars p:long l:MAINT_DOLLARS t:dataTypeName=number

metric m:fuel_qty p:float l:FUEL_QTY t:dataTypeName=number

metric m:avg_miles_per_vehicle p:decimal l:AVG_MILES_PER_VEHICLE t:dataTypeName=number

metric m:total_miles p:decimal l:TOTAL_MILES t:dataTypeName=number

entity e:5j2i-tq4k l:"COA FUEL BY DEPARTMENT" t:url=https://data.austintexas.gov/api/views/5j2i-tq4k

property e:5j2i-tq4k t:meta.view v:id=5j2i-tq4k v:category=Environmental v:averageRating=0 v:name="COA FUEL BY DEPARTMENT"

property e:5j2i-tq4k t:meta.view.license v:name="Public Domain"

property e:5j2i-tq4k t:meta.view.owner v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:displayName="Fleet Services"

property e:5j2i-tq4k t:meta.view.tableauthor v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:roleName=editor v:displayName="Fleet Services"
```

## Top Records

```ls
| :updated_at | dept_no | department                      | vehicle_count | maint_dollars  | fuel_qty | avg_miles_per_vehicle                     | total_miles                               | 
| =========== | ======= | =============================== | ============= | ============== | ======== | ========================================= | ========================================= | 
| 1484132474  | 8630    | PARD SUMMER FOOD PRO            | 1             |                |          | 0                                         | 0                                         | 
| 1484132474  | 8610    | PARKS & RECREATION              | 1             |                |          | 0                                         | 0                                         | 
| 1491472826  | 8180    | AVIATION CIP                    | 2             | 520.246667     |          | 0                                         | 0                                         | 
| 1492509637  | 9320    | TRAVIS COUNTY                   | 1             | 1470.925346    | 136.4    | 0                                         | 0                                         | 
| 1492682435  | 1107    | ELECTRIC - CIPS                 | 3             | 1445.227977    | 202      | 5362.434356194860560405471892032514754933 | 16087.3030685845816812164156760975442648  | 
| 1492682435  | 1100    | ELECTRIC OPERATING              | 823           | 2171622.895942 | 365638   | 4895.12699989673583422688855323173394158  | 4028689.52091501359156872927930971703392  | 
| 1492682435  | 1520    | LANDFILL CLOSURE/PRECLOSURE     | 9             | 32669.481658   | 6813.5   | 2628.941159292335745405709371979689281722 | 23660.4704336310217086513843478172035355  | 
| 1492682435  | 6030    | PUBLIC WORKS DEPT-CONST_ENG_PM  | 44            | 48438.536555   | 15864.9  | 6166.841790456463700463546851062211903986 | 271341.0387800844028203960614467373237754 | 
| 1492682435  | 4600    | MUNICIPAL COURT                 | 18            | 31359.966614   | 7021.6   | 5223.864566496309621353416244583836975356 | 94029.5621969335731843614924025090655564  | 
| 1492682435  | 6800    | PLANNING DEVELOPMENT AND REVIEW | 12            | 22191.666083   | 7120.2   | 7656.619188792021159441904510107250675533 | 91879.4302655042539133028541212870081064  | 
```