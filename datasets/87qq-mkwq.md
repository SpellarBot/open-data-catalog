# Austin Water Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-statistics) |
| Metadata | [Link](https://data.austintexas.gov/api/views/87qq-mkwq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/87qq-mkwq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/87qq-mkwq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 87qq-mkwq |
| Name | Austin Water Statistics |
| Attribution | Austin Water |
| Category | Utility |
| Tags | water, wastewater, statistics, key facts, gis, customers, capacity |
| Created | 2015-12-16T20:23:58Z |
| Publication Date | 2016-05-05T17:02:42Z |

## Description

Austin Water updates the following set of key facts and statistics quarterly based on customer and GIS data.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                         | Data Type | Render Type |
| ======== | ============== | ====================== | ============================ | ========= | =========== |
| No       | time           | :updated_at            | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | austin_water_key_facts | 2016 Austin Water Statistics | text      | text        |
| Yes      | numeric metric | total_total_average    | Oct-Dec                      | number    | number      |
| Yes      | numeric metric | jan_apr                | Jan-Apr                      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:87qq-mkwq d:2016-05-05T09:59:48.000Z t:austin_water_key_facts="City-Maintained Fire Hydrants (silver)" m:jan_apr=27578 m:total_total_average=27405

series e:87qq-mkwq d:2016-05-05T09:59:51.000Z t:austin_water_key_facts="City-Maintained Lift Stations (Wastewater)" m:jan_apr=135 m:total_total_average=134

series e:87qq-mkwq d:2016-05-05T10:00:01.000Z t:austin_water_key_facts="City-Maintained Manholes (Wastewater)" m:jan_apr=52221 m:total_total_average=51798
```

## Meta Commands

```ls
metric m:total_total_average p:integer l:Oct-Dec d:"2016 First Quarter Statistics for Austin Water" t:dataTypeName=number

metric m:jan_apr p:integer l:Jan-Apr d:"2016 Second Quarter Statistics for Austin Water" t:dataTypeName=number

entity e:87qq-mkwq l:"Austin Water Statistics" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/87qq-mkwq

property e:87qq-mkwq t:meta.view v:id=87qq-mkwq v:category=Utility v:attributionLink=http://www.AustinWater.org v:averageRating=0 v:name="Austin Water Statistics" v:attribution="Austin Water"

property e:87qq-mkwq t:meta.view.owner v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:displayName="Austin Water"

property e:87qq-mkwq t:meta.view.tableauthor v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"
```

## Top Records

```ls
| :updated_at | austin_water_key_facts                          | total_total_average | jan_apr | 
| =========== | =============================================== | =================== | ======= | 
| 1462442388  | City-Maintained Fire Hydrants (silver)          | 27405               | 27578   | 
| 1462442391  | City-Maintained Lift Stations (Wastewater)      | 134                 | 135     | 
| 1462442401  | City-Maintained Manholes (Wastewater)           | 51798               | 52221   | 
| 1462442407  | City-Maintained Pump Stations (Water)           | 40                  | 40      | 
| 1462442409  | Ciy-Maintained Reservoirs (Water)               | 40                  | 41      | 
| 1462442416  | Miles of City-Maintained Sewer Mains (pipeline) | 2776                | 2789    | 
| 1462442426  | Miles of City-Maintained Water Mains (pipeline) | 3807                | 3823    | 
| 1462442431  | Private-Maintained Fire Hydrants (red)          | 10099               | 10303   | 
| 1462442437  | Private-Maintained Manholes (Wastewater)        | 5040                | 5059    | 
| 1462442443  | Retail Customers                                | 921013              | 948441  | 
```