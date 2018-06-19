# Total King County Population, 2000 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-king-county-population-2000-2010-331a3) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/xa7q-is96) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/xa7q-is96/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/xa7q-is96/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | xa7q-is96 |
| Name | Total King County Population, 2000 - 2010 |
| Attribution | King County |
| Category | Census |
| Tags | population, growth, change, census |
| Created | 2011-03-24T18:25:46Z |
| Publication Date | 2014-02-15T01:02:19Z |

## Description

King County Population, 2010 U.S. Census; Source: US Census 2010, PL94-171 redistricting file, February 2011

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | demographic     | Demographic     | text      | text        |
| Yes      | numeric metric | population_2000 | Population 2000 | number    | number      |
| Yes      | numeric metric | population_2010 | Population 2010 | number    | number      |
| Yes      | numeric metric | change          | Change          | number    | number      |
| Yes      | numeric metric | percent_change  | Percent Change  | percent   | percent     |
| Yes      | numeric metric | 2010_percent    | 2010 Percent    | percent   | percent     |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xa7q-is96 d:2000-01-01T00:00:00.000Z t:demographic="Non-Hispanic total" m:population_2010=1758871 m:population_2000=1641792 m:change=117079 m:percent_change=7.1 m:2010_percent=91.1

series e:xa7q-is96 d:2000-01-01T00:00:00.000Z t:demographic="Non-Hispanic white" m:population_2010=1251300 m:population_2000=1275127 m:change=-23827 m:percent_change=-1.9 m:2010_percent=64.8

series e:xa7q-is96 d:2000-01-01T00:00:00.000Z t:demographic="Non-Hispanic African-American" m:population_2010=116326 m:population_2000=91798 m:change=24528 m:percent_change=26.7 m:2010_percent=6
```

## Meta Commands

```ls
metric m:population_2000 p:integer l:"Population 2000" t:dataTypeName=number

metric m:population_2010 p:integer l:"Population 2010" t:dataTypeName=number

metric m:change p:integer l:Change t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

metric m:2010_percent p:float l:"2010 Percent" t:dataTypeName=percent

entity e:xa7q-is96 l:"Total King County Population, 2000 - 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/xa7q-is96

property e:xa7q-is96 t:meta.view v:id=xa7q-is96 v:category=Census v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="Total King County Population, 2000 - 2010" v:attribution="King County"

property e:xa7q-is96 t:meta.view.license v:name="Public Domain"

property e:xa7q-is96 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:xa7q-is96 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| demographic                   | population_2000 | population_2010 | change | percent_change | 2010_percent | 
| ============================= | =============== | =============== | ====== | ============== | ============ | 
| Non-Hispanic total            | 1641792         | 1758871         | 117079 | 7.1            | 91.1         | 
| Non-Hispanic white            | 1275127         | 1251300         | -23827 | -1.9           | 64.8         | 
| Non-Hispanic African-American | 91798           | 116326          | 24528  | 26.7           | 6.0          | 
| Non-Hispanic Asian            | 186615          | 280029          | 93414  | 50.1           | 14.5         | 
| Non-Hispanic Pacific Islander | 8737            | 14068           | 5331   | 61.0           | 0.7          | 
| Non-Hispanic Native American  | 14278           | 12931           | -1347  | -9.4           | 0.7          | 
| Non-Hispanic Other            | 4577            | 4688            | 111    | 2.4            | 0.2          | 
| Hispanic                      | 95242           | 172378          | 77136  | 81.0           | 8.9          | 
| Two or more race              | 60660           | 79529           | 18869  | 31.1           | 4.1          | 
| Total Population              | 1737034         | 1931249         | 194215 | 11.2           | 100.0        | 
```