# Unincorporated King County Housing, 2000 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unincorporated-king-county-housing-2000-2010-a1cac) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pdjp-r9nt) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pdjp-r9nt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pdjp-r9nt/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pdjp-r9nt |
| Name | Unincorporated King County Housing, 2000 - 2010 |
| Attribution | King County |
| Category | Housing & Development |
| Tags | census, population, housing |
| Created | 2011-03-24T18:46:32Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Unincorporated King County Housing, 2010 U.S. Census; Source: US Census 2010, PL94-171 redistricting file, February 2011

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | occupancy       | Occupancy       | text      | text        |
| Yes      | numeric metric | population_2000 | Population 2000 | number    | number      |
| Yes      | numeric metric | population_2010 | Population 2010 | number    | number      |
| Yes      | numeric metric | change          | Change          | number    | number      |
| Yes      | numeric metric | percent_change  | Percent Change  | percent   | percent     |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pdjp-r9nt d:2000-01-01T00:00:00.000Z t:occupancy="Housing units" m:population_2010=125921 m:population_2000=130622 m:change=-4701 m:percent_change=-3.6

series e:pdjp-r9nt d:2000-01-01T00:00:00.000Z t:occupancy="Occupied housing units" m:population_2010=118101 m:population_2000=125715 m:change=-7614 m:percent_change=-6.1
```

## Meta Commands

```ls
metric m:population_2000 p:integer l:"Population 2000" t:dataTypeName=number

metric m:population_2010 p:integer l:"Population 2010" t:dataTypeName=number

metric m:change p:integer l:Change t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" t:dataTypeName=percent

entity e:pdjp-r9nt l:"Unincorporated King County Housing, 2000 - 2010" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/pdjp-r9nt

property e:pdjp-r9nt t:meta.view v:id=pdjp-r9nt v:category="Housing & Development" v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="Unincorporated King County Housing, 2000 - 2010" v:attribution="King County"

property e:pdjp-r9nt t:meta.view.license v:name="Public Domain"

property e:pdjp-r9nt t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:pdjp-r9nt t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| occupancy              | population_2000 | population_2010 | change | percent_change | 
| ====================== | =============== | =============== | ====== | ============== | 
| Housing units          | 130622          | 125921          | -4701  | -3.6           | 
| Occupied housing units | 125715          | 118101          | -7614  | -6.1           | 
```