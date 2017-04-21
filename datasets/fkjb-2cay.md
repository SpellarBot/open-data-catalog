# King County Budget 2015-2016, Capital Improvement Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-budget-2015-2016-capital-improvement-programs-95754) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fkjb-2cay) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fkjb-2cay/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fkjb-2cay/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fkjb-2cay |
| Name | King County Budget 2015-2016, Capital Improvement Programs |
| Attribution | King County Performance, Strategy and Budget |
| Category | Budget |
| Tags | budget, building, capital improvement, project |
| Created | 2014-09-20T00:25:42Z |
| Publication Date | 2014-09-20T02:34:18Z |

## Description

King County biennial budget, 2015-2016, capital improvement programs

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | capital_improvement_program | Capital Improvement Program | text      | text        |
| Yes      | numeric metric | fy15_16                     | FY15-16                     | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fkjb-2cay d:2015-01-01T00:00:00.000Z t:capital_improvement_program="3151 - Conservation Futures Levy Subfund" m:fy15_16=19158186

series e:fkjb-2cay d:2015-01-01T00:00:00.000Z t:capital_improvement_program="3160 - Parks, Recreation and Open Space_" m:fy15_16=11976692

series e:fkjb-2cay d:2015-01-01T00:00:00.000Z t:capital_improvement_program="3292 - SWM CIP Non-bond_" m:fy15_16=22430726
```

## Meta Commands

```ls
metric m:fy15_16 p:integer l:FY15-16 t:dataTypeName=money

entity e:fkjb-2cay l:"King County Budget 2015-2016, Capital Improvement Programs" t:attribution="King County Performance, Strategy and Budget" t:url=https://data.kingcounty.gov/api/views/fkjb-2cay

property e:fkjb-2cay t:meta.view v:id=fkjb-2cay v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="King County Budget 2015-2016, Capital Improvement Programs" v:attribution="King County Performance, Strategy and Budget"

property e:fkjb-2cay t:meta.view.license v:name="Public Domain"

property e:fkjb-2cay t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:fkjb-2cay t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| capital_improvement_program                   | fy15_16   | 
| ============================================= | ========= | 
| 3151 - Conservation Futures Levy Subfund      | 19158186  | 
| 3160 - Parks, Recreation and Open Space_      | 11976692  | 
| 3292 - SWM CIP Non-bond_                      | 22430726  | 
| 3310 - Long Term Lease                        | 97949600  | 
| 3350 - Youth Services Facilities Construction | 192964731 | 
| 3380 - Airport Construction                   | 4938997   | 
| 3421 - Major Maintenance Reserve Sub          | 11210502  | 
| 3461 - Regional Justice Center Projects       | 918190    | 
| 3473 - Radio Services CIP Fund_               | 721967    | 
| 3490 - Parks Facilities Rehab                 | 2330265   | 
```