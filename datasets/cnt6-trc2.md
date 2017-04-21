# Budget 2012- CIP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-cip-9ffc5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/cnt6-trc2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/cnt6-trc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/cnt6-trc2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | cnt6-trc2 |
| Name | Budget 2012- CIP |
| Attribution | King County |
| Category | Budget |
| Tags | budget |
| Created | 2011-09-25T20:35:06Z |
| Publication Date | 2011-09-26T03:05:23Z |

## Description

Capital Improvements budget, 2012. More at http://www.kingcounty.gov/budget

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | program    | Program | text      | text        |
| Yes      | numeric metric | amount     | Amount  | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cnt6-trc2 d:2012-01-01T00:00:00.000Z t:program="General Government" m:amount=86700000

series e:cnt6-trc2 d:2012-01-01T00:00:00.000Z t:program=Roads m:amount=92300000

series e:cnt6-trc2 d:2012-01-01T00:00:00.000Z t:program="Wastewater Treatment" m:amount=211900000
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:cnt6-trc2 l:"Budget 2012- CIP" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/cnt6-trc2

property e:cnt6-trc2 t:meta.view v:id=cnt6-trc2 v:category=Budget v:attributionLink=http://kingcounty.gov v:averageRating=0 v:name="Budget 2012- CIP" v:attribution="King County"

property e:cnt6-trc2 t:meta.view.license v:name="Public Domain"

property e:cnt6-trc2 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:cnt6-trc2 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| program              | amount    | 
| ==================== | ========= | 
| General Government   | 86700000  | 
| Roads                | 92300000  | 
| Wastewater Treatment | 211900000 | 
| Transit              | 340900000 | 
| Housing Program      | 36700000  | 
| Parks and Open Space | 30900000  | 
| Other Infrastructure | 33300000  | 
```