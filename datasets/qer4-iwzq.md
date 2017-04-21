# SSMMA Sales Tax

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-sales-tax-07aef) |
| Metadata | [Link](https://data.illinois.gov/api/views/qer4-iwzq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qer4-iwzq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qer4-iwzq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qer4-iwzq |
| Name | SSMMA Sales Tax |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Created | 2012-11-27T18:00:37Z |
| Publication Date | 2012-11-27T19:08:29Z |

## Description

This dataset outlines the sales tax rates for Chicago Southland communities in 2012.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | type        | TYPE       | text      | text        |
| Yes      | numeric metric | salestax    | SalesTax   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qer4-iwzq d:2012-11-27T10:00:38.000Z t:name="Chicago Heights" t:type=city t:objectid=1 m:salestax=9.25

series e:qer4-iwzq d:2012-11-27T10:00:38.000Z t:name="Clarendon Hills" t:type=village t:objectid=2 m:salestax=7.25

series e:qer4-iwzq d:2012-11-27T10:00:38.000Z t:name=Bolingbrook t:type=village t:objectid=14 m:salestax=8.5
```

## Meta Commands

```ls
metric m:salestax p:float l:SalesTax t:dataTypeName=number

entity e:qer4-iwzq l:"SSMMA Sales Tax" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/qer4-iwzq

property e:qer4-iwzq t:meta.view v:id=qer4-iwzq v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Sales Tax" v:attribution="South Suburban Mayors and Managers Association"

property e:qer4-iwzq t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qer4-iwzq t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:qer4-iwzq t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | name            | type    | salestax | 
| =========== | ======== | =============== | ======= | ======== | 
| 1354010438  | 1        | Chicago Heights | city    | 9.25     | 
| 1354010438  | 2        | Clarendon Hills | village | 7.25     | 
| 1354010438  | 14       | Bolingbrook     | village | 8.5      | 
| 1354010438  | 71       | North Riverside | village | 9.25     | 
| 1354010438  | 72       | La Grange Park  | village | 8.25     | 
| 1354010438  | 73       | Riverside       | village | 9.25     | 
| 1354010438  | 74       | Brookfield      | village | 9.25     | 
| 1354010438  | 75       | Stickney        | village | 9.25     | 
| 1354010438  | 76       | Lyons           | village | 8.25     | 
| 1354010438  | 77       | Western Springs | village | 8.25     | 
```