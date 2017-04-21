# COA INFO BY MAKE AND MODEL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-info-by-make-and-model) |
| Metadata | [Link](https://data.austintexas.gov/api/views/98zg-jkqu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/98zg-jkqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/98zg-jkqu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 98zg-jkqu |
| Name | COA INFO BY MAKE AND MODEL |
| Created | 2015-06-29T16:17:59Z |
| Publication Date | 2017-01-11T11:00:49Z |

## Description

Information on City of Austin vehicles organized by make and model

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | make                  | MAKE                  | text      | text        |
| Yes      | series tag     | model                 | MODEL                 | text      | text        |
| Yes      | numeric metric | vehicle_count         | VEHICLE_COUNT         | number    | number      |
| Yes      | numeric metric | maint_dollars         | MAINT_DOLLARS         | number    | number      |
| Yes      | series tag     | fuel_qty              | FUEL_QTY              | text      | text        |
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
series e:98zg-jkqu d:2017-01-11T11:00:43.000Z t:model="8000 1060" t:fuel_qty=No-DATA t:make="CLIFTON M." m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:maint_dollars=50.909372 m:total_miles=0

series e:98zg-jkqu d:2017-03-29T10:00:34.000Z t:model=UNKNOWN t:fuel_qty=No-DATA t:make="YOUNG TANK" m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:maint_dollars=588.164344 m:total_miles=0

series e:98zg-jkqu d:2017-01-11T11:00:43.000Z t:model="8FT LIL-TEX" t:fuel_qty=No-DATA t:make="BIG TEX" m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:total_miles=0
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:VEHICLE_COUNT t:dataTypeName=number

metric m:maint_dollars p:double l:MAINT_DOLLARS t:dataTypeName=number

metric m:avg_miles_per_vehicle p:decimal l:AVG_MILES_PER_VEHICLE t:dataTypeName=number

metric m:total_miles p:decimal l:TOTAL_MILES t:dataTypeName=number

entity e:98zg-jkqu l:"COA INFO BY MAKE AND MODEL" t:url=https://data.austintexas.gov/api/views/98zg-jkqu

property e:98zg-jkqu t:meta.view v:id=98zg-jkqu v:averageRating=0 v:name="COA INFO BY MAKE AND MODEL"

property e:98zg-jkqu t:meta.view.license v:name="Public Domain"

property e:98zg-jkqu t:meta.view.owner v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:displayName="Fleet Services"

property e:98zg-jkqu t:meta.view.tableauthor v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:roleName=editor v:displayName="Fleet Services"
```

## Top Records

```ls
| :updated_at | make       | model        | vehicle_count | maint_dollars | fuel_qty | avg_miles_per_vehicle | total_miles | 
| =========== | ========== | ============ | ============= | ============= | ======== | ===================== | =========== | 
| 1484132443  | CLIFTON M. | 8000 1060    | 1             | 50.909372     | No-DATA  | 0                     | 0           | 
| 1490781634  | YOUNG TANK | UNKNOWN      | 1             | 588.164344    | No-DATA  | 0                     | 0           | 
| 1484132443  | BIG TEX    | 8FT LIL-TEX  | 1             |               | No-DATA  | 0                     | 0           | 
| 1492164026  | WELLS CARG | CVG2625      | 1             | 501.334129    | 16.4     | 0                     | 0           | 
| 1490781634  | MISC       | N/A          | 4             | 4557.515506   | 19.5     | 0                     | 0           | 
| 1484132443  | COMMERCIAL | MAT10T       | 1             | 530.940706    | No-DATA  | 0                     | 0           | 
| 1484132443  | US CARGO   | USC620TA2    | 1             | 37.979272     | No-DATA  | 0                     | 0           | 
| 1484132443  | WEDLAKE, F | STANDARD     | 1             | 86.315167     | No-DATA  | 0                     | 0           | 
| 1484132443  | ALLMAND    | 2200/SE      | 1             | 142.393306    | No-DATA  | 0                     | 0           | 
| 1484132443  | INTELL     | W1-AG/WTT-AP | 2             | 196.580234    | No-DATA  | 0                     | 0           | 
```