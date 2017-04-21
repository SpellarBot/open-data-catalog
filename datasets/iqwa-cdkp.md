# Plant Dealers (2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plant-dealers-2013-dbb89) |
| Metadata | [Link](https://data.maryland.gov/api/views/iqwa-cdkp) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iqwa-cdkp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iqwa-cdkp/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iqwa-cdkp |
| Name | Plant Dealers (2013) |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | plants, plant dealers, landscaping |
| Created | 2013-05-29T12:36:57Z |
| Publication Date | 2013-10-25T19:22:25Z |

## Description

Plant Dealers in Maryland

## Columns

```ls
| Included | Schema Type | Field Name | Name   | Data Type | Render Type |
| ======== | =========== | ========== | ====== | ========= | =========== |
| Yes      | series tag  | store      | STORE  | text      | text        |
| Yes      | series tag  | countydesc | COUNTY | text      | text        |
| Yes      | series tag  | phone1     | PHONE1 | phone     | phone       |
| Yes      | series tag  | phone2     | PHONE2 | phone     | phone       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iqwa-cdkp d:2013-01-01T00:00:00.000Z t:countydesc="ANNE ARUNDEL" t:phone_number=3018556999 t:store="A.C. BROOKE CLAGETT" m:row_number.iqwa-cdkp=1

series e:iqwa-cdkp d:2013-01-01T00:00:00.000Z t:countydesc=MONTGOMERY t:store="ACE HARDWARE - TAKOMA" m:row_number.iqwa-cdkp=2

series e:iqwa-cdkp d:2013-01-01T00:00:00.000Z t:countydesc=WORCESTER t:phone_number=4107230311 t:store="A & P CO./SUPER FRESH #874" m:row_number.iqwa-cdkp=3
```

## Meta Commands

```ls
metric m:row_number.iqwa-cdkp p:long l:"Row Number"

entity e:iqwa-cdkp l:"Plant Dealers (2013)" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/iqwa-cdkp

property e:iqwa-cdkp t:meta.view v:id=iqwa-cdkp v:category=Agriculture v:attributionLink=http://www.mda.maryland.gov v:averageRating=0 v:name="Plant Dealers (2013)" v:attribution="MD Department of Agriculture"

property e:iqwa-cdkp t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:iqwa-cdkp t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| store                                                          | countydesc   | phone1             | phone2             | 
| ============================================================== | ============ | ================== | ================== | 
| A.C. BROOKE CLAGETT                                            | ANNE ARUNDEL | [3018556999, null] | [null, null]       | 
| ACE HARDWARE - TAKOMA                                          | MONTGOMERY   | [null, null]       | [null, null]       | 
| A & P CO./SUPER FRESH #874                                     | WORCESTER    | [4107230311, null] | [null, null]       | 
| A+ LAWN & LANDSCAPING, INC.                                    | WICOMICO     | [4105465530, null] | [4432358877, null] | 
| ACME MARKETS, INC. #7820                                       | QUEEN ANNE'S | [4432629150, null] | [null, null]       | 
| AKEHURST LANDSCAPE SERVICE, INC.                               | HARFORD      | [4105384018, null] | [null, null]       | 
| A.W. LANDSCAPES, INC.                                          | MONTGOMERY   | [3013492605, null] | [3013492607, null] | 
| A.W. LANDSCAPES, INC.                                          | MONTGOMERY   | [3013492605, null] | [3013492607, null] | 
| ACME MARKETS, INC. #7849                                       | KENT         | [4107785641, null] | [null, null]       | 
| A. A. COUNTY DEPT. OF RECREATION & PARKS SOUTH RIVER FARM PARK | ANNE ARUNDEL | [4102226250, null] | [4102226128, null] | 
```