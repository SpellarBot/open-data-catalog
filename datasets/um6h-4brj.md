# WAOFM - Congressional Districts - Table 1: Census 2010 Population and Housing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-congressional-districts-table-1-census-2010-population-and-housing-25085) |
| Metadata | [Link](https://data.wa.gov/api/views/um6h-4brj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/um6h-4brj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/um6h-4brj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | um6h-4brj |
| Name | WAOFM - Congressional Districts - Table 1: Census 2010 Population and Housing |
| Attribution | Washington State Office of Financial Management, Forecasting Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, congressional district, population, housing, redistricting |
| Created | 2012-02-23T18:46:37Z |
| Publication Date | 2012-02-23T19:03:40Z |

## Description

Census 2010 population and housing for 2012 congressional districts based on Washington State Redistricting Commission plan C-JOINTSUB_2-1 as amended by Engrossed House Concurrent Resolution 4409.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                            | Data Type | Render Type |
| ======== | ============== | =========================================== | =============================================== | ========= | =========== |
| Yes      | series tag     | congressional_district                      | Congressional District                          | text      | text        |
| Yes      | numeric metric | total_population_2010                       | Total Population 2010                           | number    | number      |
| Yes      | numeric metric | population_density_persons_square_mile_2010 | Population Density (Persons / Square Mile) 2010 | number    | number      |
| Yes      | numeric metric | total_housing_units_2010                    | Total Housing Units 2010                        | number    | number      |
| Yes      | numeric metric | occupied_housing_units_2010                 | Occupied Housing Units 2010                     | number    | number      |
| Yes      | numeric metric | vacant_housing_units_2010                   | Vacant Housing Units 2010                       | number    | number      |
| Yes      | numeric metric | occupancy_rate_2010                         | Occupancy Rate (%) 2010                         | number    | number      |
| Yes      | numeric metric | vacancy_rate_2010                           | Vacancy Rate (%) 2010                           | number    | number      |
| Yes      | numeric metric | land_area_square_miles_2010                 | Land Area (Square Miles) 2010                   | number    | number      |
| Yes      | numeric metric | total_area_square_miles_2010                | Total Area (Square Miles) 2010                  | number    | number      |
| Yes      | numeric metric | water_area_2010                             | Water Area (%) 2010                             | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:um6h-4brj d:2010-01-01T00:00:00.000Z t:congressional_district="Washington State" m:population_density_persons_square_mile_2010=101.19 m:total_housing_units_2010=2885677 m:vacancy_rate_2010=9.2 m:land_area_square_miles_2010=66455.52 m:occupied_housing_units_2010=2620076 m:vacant_housing_units_2010=265601 m:occupancy_rate_2010=90.8 m:water_area_2010=6.79 m:total_area_square_miles_2010=71297.95 m:total_population_2010=6724540

series e:um6h-4brj d:2010-01-01T00:00:00.000Z t:congressional_district=10 m:population_density_persons_square_mile_2010=813.45 m:total_housing_units_2010=276807 m:vacancy_rate_2010=7.17 m:land_area_square_miles_2010=826.67 m:occupied_housing_units_2010=256966 m:vacant_housing_units_2010=19841 m:occupancy_rate_2010=92.83 m:water_area_2010=9.83 m:total_area_square_miles_2010=916.82 m:total_population_2010=672455

series e:um6h-4brj d:2010-01-01T00:00:00.000Z t:congressional_district=01 m:population_density_persons_square_mile_2010=108.7 m:total_housing_units_2010=278816 m:vacancy_rate_2010=8.91 m:land_area_square_miles_2010=6186.47 m:occupied_housing_units_2010=253973 m:vacant_housing_units_2010=24843 m:occupancy_rate_2010=91.09 m:water_area_2010=6.4 m:total_area_square_miles_2010=6609.64 m:total_population_2010=672444
```

## Meta Commands

```ls
metric m:total_population_2010 p:integer l:"Total Population 2010" t:dataTypeName=number

metric m:population_density_persons_square_mile_2010 p:float l:"Population Density (Persons / Square Mile) 2010" t:dataTypeName=number

metric m:total_housing_units_2010 p:integer l:"Total Housing Units 2010" t:dataTypeName=number

metric m:occupied_housing_units_2010 p:integer l:"Occupied Housing Units 2010" t:dataTypeName=number

metric m:vacant_housing_units_2010 p:integer l:"Vacant Housing Units 2010" t:dataTypeName=number

metric m:occupancy_rate_2010 p:float l:"Occupancy Rate (%) 2010" t:dataTypeName=number

metric m:vacancy_rate_2010 p:float l:"Vacancy Rate (%) 2010" t:dataTypeName=number

metric m:land_area_square_miles_2010 p:float l:"Land Area (Square Miles) 2010" t:dataTypeName=number

metric m:total_area_square_miles_2010 p:float l:"Total Area (Square Miles) 2010" t:dataTypeName=number

metric m:water_area_2010 p:float l:"Water Area (%) 2010" t:dataTypeName=number

entity e:um6h-4brj l:"WAOFM - Congressional Districts - Table 1: Census 2010 Population and Housing" t:attribution="Washington State Office of Financial Management, Forecasting Division" t:url=https://data.wa.gov/api/views/um6h-4brj

property e:um6h-4brj t:meta.view v:id=um6h-4brj v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/census2010/default.asp v:averageRating=70 v:name="WAOFM - Congressional Districts - Table 1: Census 2010 Population and Housing" v:attribution="Washington State Office of Financial Management, Forecasting Division"

property e:um6h-4brj t:meta.view.license v:name="Public Domain"

property e:um6h-4brj t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:um6h-4brj t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| congressional_district | total_population_2010 | population_density_persons_square_mile_2010 | total_housing_units_2010 | occupied_housing_units_2010 | vacant_housing_units_2010 | occupancy_rate_2010 | vacancy_rate_2010 | land_area_square_miles_2010 | total_area_square_miles_2010 | water_area_2010 | 
| ====================== | ===================== | =========================================== | ======================== | =========================== | ========================= | =================== | ================= | =========================== | ============================ | =============== | 
| Washington State       | 6724540               | 101.19                                      | 2885677                  | 2620076                     | 265601                    | 90.80               | 9.20              | 66455.52                    | 71297.95                     | 6.79            | 
| 10                     | 672455                | 813.45                                      | 276807                   | 256966                      | 19841                     | 92.83               | 7.17              | 826.67                      | 916.82                       | 9.83            | 
| 01                     | 672444                | 108.70                                      | 278816                   | 253973                      | 24843                     | 91.09               | 8.91              | 6186.47                     | 6609.64                      | 6.40            | 
| 02                     | 672454                | 662.50                                      | 296894                   | 266994                      | 29900                     | 89.93               | 10.07             | 1015.02                     | 2053.46                      | 50.57           | 
| 03                     | 672448                | 73.78                                       | 283279                   | 256966                      | 26313                     | 90.71               | 9.29              | 9114.01                     | 9582.14                      | 4.89            | 
| 04                     | 672456                | 34.93                                       | 253235                   | 230788                      | 22447                     | 91.14               | 8.86              | 19250.22                    | 19562.08                     | 1.59            | 
| 05                     | 672455                | 43.46                                       | 294931                   | 267039                      | 27892                     | 90.54               | 9.46              | 15473.13                    | 15704.36                     | 1.47            | 
| 06                     | 672448                | 97.42                                       | 313243                   | 271815                      | 41428                     | 86.77               | 13.23             | 6902.73                     | 8868.34                      | 22.16           | 
| 07                     | 672457                | 4665.51                                     | 336875                   | 310595                      | 26280                     | 92.20               | 7.80              | 144.13                      | 275.56                       | 47.69           | 
| 08                     | 672463                | 91.37                                       | 270391                   | 244876                      | 25515                     | 90.56               | 9.44              | 7359.70                     | 7500.59                      | 1.88            | 
```