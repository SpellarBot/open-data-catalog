# COA INFO BY CLASS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-info-by-class) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jmuq-5usm) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jmuq-5usm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jmuq-5usm/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jmuq-5usm |
| Name | COA INFO BY CLASS |
| Created | 2015-06-29T16:05:34Z |
| Publication Date | 2017-01-11T11:00:48Z |

## Description

Information on vehicles by class type

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | management_class      | MANAGEMENT_CLASS      | text      | text        |
| Yes      | series tag     | class_desc            | CLASS_DESC            | text      | text        |
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
series e:jmuq-5usm d:2017-04-13T10:00:42.000Z t:class_desc="SEMI-TRAILER LIVE BOTTOM" t:management_class=K503 t:fuel_qty=No-DATA m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:maint_dollars=2882.541772 m:total_miles=0

series e:jmuq-5usm d:2017-03-21T10:00:41.000Z t:class_desc="SEMI-TRAILER, SLUDGE HAUL" t:management_class=K601 t:fuel_qty=No-DATA m:vehicle_count=1 m:avg_miles_per_vehicle=0 m:maint_dollars=614.169582 m:total_miles=0

series e:jmuq-5usm d:2017-04-13T10:00:42.000Z t:class_desc="TRAILER, OUTBOARD BOAT, S" t:management_class=L410 t:fuel_qty=No-DATA m:vehicle_count=23 m:avg_miles_per_vehicle=0 m:maint_dollars=13534.349993 m:total_miles=0
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:VEHICLE_COUNT t:dataTypeName=number

metric m:maint_dollars p:double l:MAINT_DOLLARS t:dataTypeName=number

metric m:avg_miles_per_vehicle p:decimal l:AVG_MILES_PER_VEHICLE t:dataTypeName=number

metric m:total_miles p:decimal l:TOTAL_MILES t:dataTypeName=number

entity e:jmuq-5usm l:"COA INFO BY CLASS" t:url=https://data.austintexas.gov/api/views/jmuq-5usm

property e:jmuq-5usm t:meta.view v:id=jmuq-5usm v:averageRating=0 v:name="COA INFO BY CLASS"

property e:jmuq-5usm t:meta.view.license v:name="Public Domain"

property e:jmuq-5usm t:meta.view.owner v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:displayName="Fleet Services"

property e:jmuq-5usm t:meta.view.tableauthor v:id=bcru-v2iw v:profileImageUrlMedium=/api/users/bcru-v2iw/profile_images/THUMB v:profileImageUrlLarge=/api/users/bcru-v2iw/profile_images/LARGE v:screenName="Fleet Services" v:profileImageUrlSmall=/api/users/bcru-v2iw/profile_images/TINY v:roleName=editor v:displayName="Fleet Services"
```

## Top Records

```ls
| :updated_at | management_class | class_desc                | vehicle_count | maint_dollars | fuel_qty | avg_miles_per_vehicle | total_miles | 
| =========== | ================ | ========================= | ============= | ============= | ======== | ===================== | =========== | 
| 1492077642  | K503             | SEMI-TRAILER LIVE BOTTOM  | 1             | 2882.541772   | No-DATA  | 0                     | 0           | 
| 1490090441  | K601             | SEMI-TRAILER, SLUDGE HAUL | 1             | 614.169582    | No-DATA  | 0                     | 0           | 
| 1492077642  | L410             | TRAILER, OUTBOARD BOAT, S | 23            | 13534.349993  | No-DATA  | 0                     | 0           | 
| 1484132441  | L420             | TRAILER, INBOARD BOAT, SI | 1             | 71.3241       | No-DATA  | 0                     | 0           | 
| 1484132441  | H509             | CHIPPER ATTACHMENT, BRUSH | 3             | 83.666655     | No-DATA  | 0                     | 0           | 
| 1484132441  | H511             | TWIN TURBINE TRLR MTD     | 1             | 1.137222      | No-DATA  | 0                     | 0           | 
| 1484132441  | J332             | WATER PMP 6" TRL GAS      | 1             | 61.364511     | No-DATA  | 0                     | 0           | 
| 1484132441  | K604             | SEMI-TRAILER, MATERIALS T | 1             |               | No-DATA  | 0                     | 0           | 
| 1484132441  | K106             | TRAILER, IMP., 30K, DUALA | 1             | 306.8453      | No-DATA  | 0                     | 0           | 
| 1484132441  | A731             | BUS 120 PASS DIESEL       | 2             | 0             | No-DATA  | 0                     | 0           | 
```