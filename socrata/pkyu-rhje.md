# SSMMA Vacant Lots

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-vacant-lots-5bfc3) |
| Metadata | [Link](https://data.illinois.gov/api/views/pkyu-rhje) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pkyu-rhje/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pkyu-rhje/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pkyu-rhje |
| Name | SSMMA Vacant Lots |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | land use, planning, economic development |
| Created | 2012-11-27T18:02:05Z |
| Publication Date | 2012-11-27T19:08:10Z |

## Description

This dataset details vacant lots across the Chicago Southland. These lots are suspected vacant by South Suburban Atlas staff.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | numeric metric | pin14       | PIN14      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pkyu-rhje d:2012-11-27T10:02:07.000Z t:objectid=1 m:pin14=24272020190000

series e:pkyu-rhje d:2012-11-27T10:02:07.000Z t:objectid=2 m:pin14=24272020190000

series e:pkyu-rhje d:2012-11-27T10:02:07.000Z t:objectid=3 m:pin14=24272030120000
```

## Meta Commands

```ls
metric m:pin14 p:long l:PIN14 t:dataTypeName=number

entity e:pkyu-rhje l:"SSMMA Vacant Lots" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/pkyu-rhje

property e:pkyu-rhje t:meta.view v:id=pkyu-rhje v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Vacant Lots" v:attribution="South Suburban Mayors and Managers Association"

property e:pkyu-rhje t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pkyu-rhje t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:pkyu-rhje t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | pin14          | 
| =========== | ======== | ============== | 
| 1354010527  | 1        | 24272020190000 | 
| 1354010527  | 2        | 24272020190000 | 
| 1354010527  | 3        | 24272030120000 | 
| 1354010527  | 4        | 24272030130000 | 
| 1354010527  | 5        | 24272030140000 | 
| 1354010527  | 6        | 24252290220000 | 
| 1354010527  | 7        | 24252290240000 | 
| 1354010527  | 8        | 24252290280000 | 
| 1354010527  | 9        | 24252290350000 | 
| 1354010527  | 10       | 24252290200000 | 
```