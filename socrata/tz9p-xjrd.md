# Belleville Population By Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/belleville-population-by-age-90edb) |
| Metadata | [Link](https://data.illinois.gov/api/views/tz9p-xjrd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tz9p-xjrd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tz9p-xjrd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tz9p-xjrd |
| Name | Belleville Population By Age |
| Attribution | US Census Bureau |
| Category | Reference |
| Tags | population |
| Created | 2013-02-01T18:47:38Z |
| Publication Date | 2013-02-01T18:50:54Z |

## Description

The age demographic of Belleville according to the 2010 Census

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | category_id | Category ID | text      | number      |
| Yes      | series tag     | category    | Category    | text      | text        |
| Yes      | numeric metric | population  | Population  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tz9p-xjrd d:2013-02-01T10:47:39.000Z t:category="Under 5 years" t:category_id=1 m:population=3002

series e:tz9p-xjrd d:2013-02-01T10:47:39.000Z t:category="5 to 9 years" t:category_id=2 m:population=2771

series e:tz9p-xjrd d:2013-02-01T10:47:39.000Z t:category="10 to 14 years" t:category_id=3 m:population=2795
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:tz9p-xjrd l:"Belleville Population By Age" t:attribution="US Census Bureau" t:url=https://data.illinois.gov/api/views/tz9p-xjrd

property e:tz9p-xjrd t:meta.view v:id=tz9p-xjrd v:category=Reference v:attributionLink="http://factfinder2.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_10_DP_DPDP1" v:averageRating=0 v:name="Belleville Population By Age" v:attribution="US Census Bureau"

property e:tz9p-xjrd t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:tz9p-xjrd t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | category_id | category       | population | 
| =========== | =========== | ============== | ========== | 
| 1359715659  | 1           | Under 5 years  | 3002       | 
| 1359715659  | 2           | 5 to 9 years   | 2771       | 
| 1359715659  | 3           | 10 to 14 years | 2795       | 
| 1359715659  | 4           | 15 to 19 years | 2931       | 
| 1359715659  | 5           | 20 to 24 years | 2993       | 
| 1359715659  | 6           | 25 to 29 years | 3571       | 
| 1359715659  | 7           | 30 to 34 years | 3308       | 
| 1359715659  | 8           | 35 to 39 years | 2950       | 
| 1359715659  | 9           | 40 to 44 years | 2854       | 
| 1359715659  | 10          | 45 to 49 years | 3363       | 
```