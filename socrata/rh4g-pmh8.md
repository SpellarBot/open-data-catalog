# Watershed statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/watershed-statistics-11b03) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rh4g-pmh8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rh4g-pmh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rh4g-pmh8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rh4g-pmh8 |
| Name | Watershed statistics |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | department of environmental protection, dep, environment, water, reservoir, health, ecosystem, eco-system, agua, water system, water supply, nyc, tap, tap water, conservation, watershrd, healthy l... |
| Created | 2011-09-09T21:40:29Z |
| Publication Date | 2013-06-21T19:43:35Z |

## Description

NYC West-of-Hudson Watershed Impervious Surface Percentages by Basin

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                                   | Data Type | Render Type |
| ======== | ============== | ================================================= | ====================================================== | ========= | =========== |
| No       | time           | :updated_at                                       | updated_at                                             | meta_data | meta_data   |
| Yes      | series tag     | woh_basin                                         | WOH Basin                                              | text      | text        |
| Yes      | numeric metric | total_basin_area_acres                            | Total Basin Area (acres)                               | number    | number      |
| Yes      | numeric metric | total_reservoir_area_acres                        | Total Reservoir Area (acres)                           | number    | number      |
| Yes      | numeric metric | total_water_bodies_incl_reservoirs_acres          | Total Water Bodies** incl. Reservoirs (acres)          | number    | number      |
| Yes      | numeric metric | basin_area_minus_water_bodies_acres               | Basin Area minus Water Bodies (acres)                  | number    | number      |
| Yes      | numeric metric | total_impervious_surface_acres                    | Total Impervious Surface (acres)                       | number    | number      |
| Yes      | numeric metric | impervious_as_of_total_basin_area                 | Impervious as % of Total Basin Area                    | percent   | percent     |
| Yes      | numeric metric | impervious_as_of_basin_excluding_water_body_areas | Impervious as % of Basin Excluding Water Body Areas*** | percent   | percent     |
| Yes      | numeric metric | population_density_persons_sq_mi                  | Population Density**** (persons/ sq. mi)               | number    | number      |
| Yes      | series tag     | references                                        | References ****                                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rh4g-pmh8 d:2011-09-09T14:40:30.000Z t:woh_basin=Ashokan m:total_basin_area_acres=163405 m:total_water_bodies_incl_reservoirs_acres=8557 m:total_impervious_surface_acres=1549 m:population_density_persons_sq_mi=33 m:impervious_as_of_total_basin_area=0.9 m:impervious_as_of_basin_excluding_water_body_areas=1 m:basin_area_minus_water_bodies_acres=154849 m:total_reservoir_area_acres=8106

series e:rh4g-pmh8 d:2011-09-09T14:40:30.000Z t:woh_basin=Cannonsville m:total_basin_area_acres=291077 m:total_water_bodies_incl_reservoirs_acres=6144 m:total_impervious_surface_acres=4608 m:population_density_persons_sq_mi=39 m:impervious_as_of_total_basin_area=1.6 m:impervious_as_of_basin_excluding_water_body_areas=1.6 m:basin_area_minus_water_bodies_acres=284933 m:total_reservoir_area_acres=4713

series e:rh4g-pmh8 d:2011-09-09T14:40:30.000Z t:woh_basin=Neversink m:total_basin_area_acres=58902 m:total_water_bodies_incl_reservoirs_acres=1873 m:total_impervious_surface_acres=350 m:population_density_persons_sq_mi=13 m:impervious_as_of_total_basin_area=0.6 m:impervious_as_of_basin_excluding_water_body_areas=0.6 m:basin_area_minus_water_bodies_acres=57029 m:total_reservoir_area_acres=1493
```

## Meta Commands

```ls
metric m:total_basin_area_acres p:integer l:"Total Basin Area (acres)" t:dataTypeName=number

metric m:total_reservoir_area_acres p:integer l:"Total Reservoir Area (acres)" t:dataTypeName=number

metric m:total_water_bodies_incl_reservoirs_acres p:integer l:"Total Water Bodies** incl. Reservoirs (acres)" t:dataTypeName=number

metric m:basin_area_minus_water_bodies_acres p:integer l:"Basin Area minus Water Bodies (acres)" t:dataTypeName=number

metric m:total_impervious_surface_acres p:integer l:"Total Impervious Surface (acres)" t:dataTypeName=number

metric m:impervious_as_of_total_basin_area p:float l:"Impervious as % of Total Basin Area" t:dataTypeName=percent

metric m:impervious_as_of_basin_excluding_water_body_areas p:float l:"Impervious as % of Basin Excluding Water Body Areas***" t:dataTypeName=percent

metric m:population_density_persons_sq_mi p:integer l:"Population Density**** (persons/ sq. mi)" t:dataTypeName=number

entity e:rh4g-pmh8 l:"Watershed statistics" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/rh4g-pmh8

property e:rh4g-pmh8 t:meta.view v:id=rh4g-pmh8 v:category=Environment v:averageRating=0 v:name="Watershed statistics" v:attribution="Department of Environmental Protection (DEP)"

property e:rh4g-pmh8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rh4g-pmh8 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | woh_basin    | total_basin_area_acres | total_reservoir_area_acres | total_water_bodies_incl_reservoirs_acres | basin_area_minus_water_bodies_acres | total_impervious_surface_acres | impervious_as_of_total_basin_area | impervious_as_of_basin_excluding_water_body_areas | population_density_persons_sq_mi | references                                                                                                                                                                                                                                                                 | 
| =========== | ============ | ====================== | ========================== | ======================================== | =================================== | ============================== | ================================= | ================================================= | ================================ | ========================================================================================================================================================================================================================================================================== | 
| 1315579230  | Ashokan      | 163405                 | 8106                       | 8557                                     | 154849                              | 1549                           | 0.90                              | 1.00                                              | 33                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Cannonsville | 291077                 | 4713                       | 6144                                     | 284933                              | 4608                           | 1.60                              | 1.60                                              | 39                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Neversink    | 58902                  | 1493                       | 1873                                     | 57029                               | 350                            | 0.60                              | 0.60                                              | 13                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Pepacton     | 237472                 | 5194                       | 5822                                     | 231650                              | 2517                           | 1.10                              | 1.10                                              | 21                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Rondout      | 61039                  | 2038                       | 2160                                     | 58879                               | 605                            | 1.00                              | 1.00                                              | 32                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Schoharie    | 202040                 | 1145                       | 2021                                     | 200019                              | 2345                           | 1.20                              | 1.20                                              | 27                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  | Grand Total  | 1013936                | 22688                      | 26576                                    | 987360                              | 11975                          | 1.20                              | 1.20                                              | 29                               |                                                                                                                                                                                                                                                                            | 
| 1315579230  |              |                        |                            |                                          |                                     |                                |                                   |                                                   |                                  | * Impervious surface acreages are calculated from NYCDEP GIS data derived from Spring 2001 high resolution (0.3 m) NYS Ortho Imagery using pattern recognition software.                                                                                                   | 
| 1315579230  |              |                        |                            |                                          |                                     |                                |                                   |                                                   |                                  | ** Water Bodies (column D) include reservoirs, lakes, ponds, and rivers/major streams but exclude minor streams and wetlands.                                                                                                                                              | 
| 1315579230  |              |                        |                            |                                          |                                     |                                |                                   |                                                   |                                  | *** To analyze the portion of potentially developable land area that is already impervious, percentages in column H represent the total impervious acreage for each basin divided by the difference between the total basin area and the total water body area (i.e. F/E). | 
```