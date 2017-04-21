# SSMMA Property Tax

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-property-tax-29d46) |
| Metadata | [Link](https://data.illinois.gov/api/views/jjf8-mx47) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jjf8-mx47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jjf8-mx47/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jjf8-mx47 |
| Name | SSMMA Property Tax |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | government, economic development, housing, community development |
| Created | 2012-11-27T17:40:21Z |
| Publication Date | 2012-11-27T19:13:19Z |

## Description

This dataset provides a overview of property tax rates across Chicago Southland communities

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | type        | TYPE       | text      | text        |
| No       |                | st          | ST         | text      | text        |
| Yes      | series tag     | stfips      | STFIPS     | text      | number      |
| Yes      | series tag     | fips_place  | FIPS_PLACE | text      | number      |
| Yes      | numeric metric | propertyta  | PROPERTYTA | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:jjf8-mx47 d:2012-11-27T09:40:23.000Z t:name="Chicago Heights" t:stfips=17 t:type=city t:objectid=1 t:fips_place=14026 m:propertyta=15.04

series e:jjf8-mx47 d:2012-11-27T09:40:23.000Z t:name="Clarendon Hills" t:stfips=17 t:type=village t:objectid=2 t:fips_place=14572 m:propertyta=5.53

series e:jjf8-mx47 d:2012-11-27T09:40:23.000Z t:name=Bolingbrook t:stfips=17 t:type=village t:objectid=14 t:fips_place=7133 m:propertyta=8.62
```

## Meta Commands

```ls
metric m:propertyta p:float l:PROPERTYTA t:dataTypeName=number

entity e:jjf8-mx47 l:"SSMMA Property Tax" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/jjf8-mx47

property e:jjf8-mx47 t:meta.view v:id=jjf8-mx47 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Property Tax" v:attribution="South Suburban Mayors and Managers Association"

property e:jjf8-mx47 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jjf8-mx47 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:jjf8-mx47 t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | name            | type    | st | stfips | fips_place | propertyta     | 
| =========== | ======== | =============== | ======= | == | ====== | ========== | ============== | 
| 1354009223  | 1        | Chicago Heights | city    | IL | 17     | 14026      | 15.04000000000 | 
| 1354009223  | 2        | Clarendon Hills | village | IL | 17     | 14572      | 5.53000000000  | 
| 1354009223  | 14       | Bolingbrook     | village | IL | 17     | 7133       | 8.62000000000  | 
| 1354009223  | 71       | North Riverside | village | IL | 17     | 54144      | 8.74000000000  | 
| 1354009223  | 72       | La Grange Park  | village | IL | 17     | 40793      | 8.16000000000  | 
| 1354009223  | 73       | Riverside       | village | IL | 17     | 64421      | 9.85000000000  | 
| 1354009223  | 74       | Brookfield      | village | IL | 17     | 8576       | 10.46000000000 | 
| 1354009223  | 75       | Stickney        | village | IL | 17     | 72676      | 11.90000000000 | 
| 1354009223  | 76       | Lyons           | village | IL | 17     | 45434      | 10.57000000000 | 
| 1354009223  | 77       | Western Springs | village | IL | 17     | 80242      | 7.15000000000  | 
```