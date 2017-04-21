# Unincorporated King County Population, 2000 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unincorporated-king-county-population-2000-2010-7ff7c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/t7m5-d3dx) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/t7m5-d3dx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/t7m5-d3dx/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | t7m5-d3dx |
| Name | Unincorporated King County Population, 2000 - 2010 |
| Attribution | King County |
| Category | Census |
| Tags | population, growth, change, census |
| Created | 2011-03-24T18:43:31Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Unincorporated King County Population, 2010 U.S. Census; Source: US Census 2010, PL94-171 redistricting file, February 2011

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
series e:t7m5-d3dx d:2000-01-01T00:00:00.000Z t:demographic="Total Population" m:population_2010=325002 m:population_2000=352764 m:change=-27762 m:percent_change=-7.9

series e:t7m5-d3dx d:2000-01-01T00:00:00.000Z t:demographic="Non-Hispanic total" m:population_2010=299607 m:population_2000=337511 m:change=-37904 m:percent_change=-11.2 m:2010_percent=92.2

series e:t7m5-d3dx d:2000-01-01T00:00:00.000Z t:demographic="Non-Hispanic white" m:population_2010=228392 m:population_2000=279593 m:change=-51201 m:percent_change=-18.3 m:2010_percent=70.3
```

## Meta Commands

```ls
metric m:population_2000 p:integer l:"Population 2000" t:dataTypeName=number

metric m:population_2010 p:integer l:"Population 2010" t:dataTypeName=number

metric m:change p:integer l:Change t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

metric m:2010_percent p:float l:"2010 Percent" t:dataTypeName=percent

entity e:t7m5-d3dx l:"Unincorporated King County Population, 2000 - 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/t7m5-d3dx

property e:t7m5-d3dx t:meta.view v:id=t7m5-d3dx v:category=Census v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="Unincorporated King County Population, 2000 - 2010" v:attribution="King County"

property e:t7m5-d3dx t:meta.view.license v:name="Public Domain"

property e:t7m5-d3dx t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:t7m5-d3dx t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| demographic                   | population_2000 | population_2010 | change | percent_change | 2010_percent | 
| ============================= | =============== | =============== | ====== | ============== | ============ | 
| Total Population              | 352764          | 325002          | -27762 | -7.9           |              | 
| Non-Hispanic total            | 337511          | 299607          | -37904 | -11.2          | 92.2         | 
| Non-Hispanic white            | 279593          | 228392          | -51201 | -18.3          | 70.3         | 
| Non-Hispanic African-American | 12052           | 14851           | 2799   | 23.2           | 4.6          | 
| Non-Hispanic Asian            | 29239           | 38813           | 9574   | 32.7           | 11.9         | 
| Non-Hispanic Pacific Islander | 1595            | 1986            | 391    | 24.5           | 0.6          | 
| Non-Hispanic Native American  | 3275            | 2717            | -558   | -17.0          | 0.8          | 
| Non-Hispanic Other            | 893             | 696             | -197   | -22.1          | 0.2          | 
| Hispanic/Latino               | 15253           | 25395           | 10142  | 66.5           | 7.8          | 
| Two or more race              | 10864           | 12152           | 1288   | 11.9           | 3.7          | 
```