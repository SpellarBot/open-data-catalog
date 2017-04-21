# Number Of Delayed Bills

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-delayed-bills-74147) |
| Metadata | [Link](https://data.lacity.org/api/views/f7se-beud) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/f7se-beud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/f7se-beud/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | f7se-beud |
| Name | Number Of Delayed Bills |
| Attribution | LADWP |
| Category | A Well Run City |
| Tags | delayed bills |
| Created | 2014-05-23T22:47:18Z |
| Publication Date | 2014-05-23T22:49:13Z |

## Description

Number of delayed LADWP bills and revenue in millions from delayed bills.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | jan_14      | Jan-14     | money     | money       |
| Yes      | numeric metric | feb_14      | Feb-14     | money     | money       |
| Yes      | numeric metric | mar_14      | Mar-14     | money     | money       |
| Yes      | numeric metric | apr_14      | Apr-14     | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f7se-beud d:2014-05-23T15:47:21.000Z t:month="No. of Delayed Bills" m:jan_14=74460

series e:f7se-beud d:2014-05-23T15:47:21.000Z t:month="Delayed Bill Revenue (Million)" m:feb_14=145 m:mar_14=71 m:apr_14=56 m:jan_14=160
```

## Meta Commands

```ls
metric m:jan_14 p:integer l:Jan-14 t:dataTypeName=money

metric m:feb_14 p:integer l:Feb-14 t:dataTypeName=money

metric m:mar_14 p:integer l:Mar-14 t:dataTypeName=money

metric m:apr_14 p:integer l:Apr-14 t:dataTypeName=money

entity e:f7se-beud l:"Number Of Delayed Bills" t:attribution=LADWP t:url=https://data.lacity.org/api/views/f7se-beud

property e:f7se-beud t:meta.view v:id=f7se-beud v:category="A Well Run City" v:averageRating=0 v:name="Number Of Delayed Bills" v:attribution=LADWP

property e:f7se-beud t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:f7se-beud t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:f7se-beud t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| :updated_at | month                          | jan_14 | feb_14 | mar_14 | apr_14 | 
| =========== | ============================== | ====== | ====== | ====== | ====== | 
| 1400860041  | No. of Delayed Bills           | 74460  |        |        |        | 
| 1400860041  | Delayed Bill Revenue (Million) | 160    | 145    | 71     | 56     | 
```