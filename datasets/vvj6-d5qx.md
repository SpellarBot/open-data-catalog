# NYC Municipal Building Energy Benchmarking Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-nyc-municipal-building-energy-benchmarking-results-6d21a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vvj6-d5qx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vvj6-d5qx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vvj6-d5qx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vvj6-d5qx |
| Name | NYC Municipal Building Energy Benchmarking Results |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | nyc, nyc municipal building energy benchmarking results, benchmark, energy, energy intensity, emissions, municipal building, block, lot, dcas, department of citywide administrative services (dcas) |
| Created | 2012-02-14T16:29:21Z |
| Publication Date | 2015-04-09T20:05:10Z |

## Description

This is a list of New York City municipal buildings over 10,000 square feet by borough, block, lot, and agency, identifying each building?s energy intensity (kBtu/sq. ft.), Portfolio Manager benchmarking rating, where available, and the total GHG emissions for the calendar years 2010 - 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                        | Data Type | Render Type |
| ======== | ============== | ========================================== | =========================================== | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                  | meta_data | meta_data   |
| Yes      | numeric metric | borough                                    | Borough                                     | number    | number      |
| Yes      | series tag     | block                                      | Block                                       | text      | number      |
| Yes      | series tag     | lot                                        | Lot                                         | text      | number      |
| Yes      | numeric metric | bin                                        | BIN                                         | number    | number      |
| Yes      | series tag     | agency                                     | Building                                    | text      | text        |
| Yes      | series tag     | building                                   | Agency                                      | text      | text        |
| Yes      | series tag     | rating                                     | 2010 Rating *                               | text      | text        |
| Yes      | series tag     | current_source_energy_intensity_kbtu_sq_ft | 2010 Source EUI (kBtu/sq.ft.)               | text      | text        |
| Yes      | numeric metric | current_total_ghg_emissions_mtco2e         | 2010 GHG Emissions Intensity (kgCO2e/ft?) ? | number    | number      |
| Yes      | series tag     | rating_2                                   | 2011 Rating *                               | text      | text        |
| Yes      | numeric metric | source_energy_intensity_kbtu_sq_ft         | 2011 Source EUI (kBtu/sq.ft.)               | number    | number      |
| Yes      | numeric metric | total_ghg_emissions_mtco2e                 | 2011 GHG Emissions Intensity (kgCO2e/ft?) ? | number    | number      |
| No       |                | address                                    | 2012 Rating *                               | text      | text        |
| Yes      | series tag     | city                                       | 2012 Source EUI (kBtu/sq.ft.)               | text      | text        |
| Yes      | series tag     | state                                      | 2012 GHG Emissions Intensity (kgCO2e/ft?) ? | text      | text        |
| Yes      | series tag     | zip                                        | 2013 Rating *                               | text      | number      |
| Yes      | numeric metric | gross_sq_ft                                | 2013 Source EUI (kBtu/sq.ft.)               | number    | number      |
| Yes      | numeric metric | year_built                                 | 2013 GHG Emissions Intensity (kgCO2e/ft?) ? | number    | number      |
| Yes      | series tag     | epapmbenchmarkedas                         | EPAPMBenchmarkedAs                          | text      | text        |
| Yes      | series tag     | campus_name                                | Campus Name                                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:vvj6-d5qx d:2015-04-09T13:04:16.000Z t:building=ACS t:current_source_energy_intensity_kbtu_sq_ft=180.6 t:epapmbenchmarkedas="Individual building" t:rating_2=N/A t:state=4.3 t:lot=12 t:block=2383 t:agency="1332 Fulton Ave D C C Inc" t:rating=N/A t:city=157.7 m:current_total_ghg_emissions_mtco2e=4.9 m:year_built=4.5 m:borough=2 m:total_ghg_emissions_mtco2e=4.3 m:bin=2001505 m:source_energy_intensity_kbtu_sq_ft=155.9 m:gross_sq_ft=164.8

series e:vvj6-d5qx d:2015-04-09T13:04:16.000Z t:zip=64 t:building=ACS t:current_source_energy_intensity_kbtu_sq_ft=239.0 t:epapmbenchmarkedas="Individual building" t:rating_2=55 t:state=5.9 t:lot=1 t:block=93 t:agency="ACS Administrative Site" t:rating=57 t:city=228.3 m:current_total_ghg_emissions_mtco2e=6.2 m:year_built=5.6 m:borough=1 m:total_ghg_emissions_mtco2e=6.3 m:bin=1062652 m:source_energy_intensity_kbtu_sq_ft=242.1 m:gross_sq_ft=217.9

series e:vvj6-d5qx d:2015-04-09T13:04:16.000Z t:zip=24 t:building=ACS t:current_source_energy_intensity_kbtu_sq_ft=286.6 t:epapmbenchmarkedas="Space within building" t:rating_2=19 t:state=7.6 t:lot=13 t:block=4484 t:agency="ACS Administrative Site" t:rating=16 t:city=258.6 m:current_total_ghg_emissions_mtco2e=8.6 m:year_built=7.5 m:borough=3 m:total_ghg_emissions_mtco2e=7.9 m:bin=3098733 m:source_energy_intensity_kbtu_sq_ft=268.3 m:gross_sq_ft=252.1
```

## Meta Commands

```ls
metric m:borough p:integer l:Borough t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:current_total_ghg_emissions_mtco2e p:float l:"2010 GHG Emissions Intensity (kgCO2e/ft?) ?" t:dataTypeName=number

metric m:source_energy_intensity_kbtu_sq_ft p:float l:"2011 Source EUI (kBtu/sq.ft.)" t:dataTypeName=number

metric m:total_ghg_emissions_mtco2e p:float l:"2011 GHG Emissions Intensity (kgCO2e/ft?) ?" t:dataTypeName=number

metric m:gross_sq_ft p:float l:"2013 Source EUI (kBtu/sq.ft.)" t:dataTypeName=number

metric m:year_built p:float l:"2013 GHG Emissions Intensity (kgCO2e/ft?) ?" t:dataTypeName=number

entity e:vvj6-d5qx l:"NYC Municipal Building Energy Benchmarking Results" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/vvj6-d5qx

property e:vvj6-d5qx t:meta.view v:id=vvj6-d5qx v:category="City Government" v:averageRating=0 v:name="NYC Municipal Building Energy Benchmarking Results" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:vvj6-d5qx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vvj6-d5qx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough | block | lot | bin     | agency                                       | building | rating | current_source_energy_intensity_kbtu_sq_ft | current_total_ghg_emissions_mtco2e | rating_2 | source_energy_intensity_kbtu_sq_ft | total_ghg_emissions_mtco2e | address | city  | state | zip | gross_sq_ft | year_built | epapmbenchmarkedas    | campus_name | 
| =========== | ======= | ===== | === | ======= | ============================================ | ======== | ====== | ========================================== | ================================== | ======== | ================================== | ========================== | ======= | ===== | ===== | === | =========== | ========== | ===================== | =========== | 
| 1428584656  | 2       | 2383  | 12  | 2001505 | 1332 Fulton Ave D C C Inc                    | ACS      | N/A    | 180.6                                      | 4.9                                | N/A      | 155.9                              | 4.3                        | N/A     | 157.7 | 4.3   |     | 164.8       | 4.5        | Individual building   |             | 
| 1428584656  | 1       | 93    | 1   | 1062652 | ACS Administrative Site                      | ACS      | 57     | 239.0                                      | 6.2                                | 55       | 242.1                              | 6.3                        | 59      | 228.3 | 5.9   | 64  | 217.9       | 5.6        | Individual building   |             | 
| 1428584656  | 3       | 4484  | 13  | 3098733 | ACS Administrative Site                      | ACS      | 16     | 286.6                                      | 8.6                                | 19       | 268.3                              | 7.9                        | 20      | 258.6 | 7.6   | 24  | 252.1       | 7.5        | Space within building |             | 
| 1428584656  | 2       | 4101  | 1   | 2044743 | ACS Bronx Field Office                       | ACS      | 7      | 316.2                                      | 8.9                                | 14       | 269.6                              | 7.2                        | 12      | 273.0 | 7.4   | 12  | 282.8       | 7.9        | Individual building   |             | 
| 1428584656  | 3       | 2022  | 18  | 3057913 | Administration Site                          | ACS      | 21     | 313.6                                      | 9.8                                | 31       | 272.4                              | 8.4                        | 35      | 257.9 | 7.5   | 37  | 256.1       | 7.6        | Individual building   |             | 
| 1428584656  | 3       | 1230  | 44  | 3031082 | Albany Day Care and Senior Center            | ACS      | N/A    | 137.8                                      | 4.0                                | N/A      | 143.0                              | 4.1                        | N/A     | 131.5 | 3.7   |     | 158.6       | 4.5        | Individual building   |             | 
| 1428584656  | 3       | 1420  | 51  | 3038317 | All My Children Daycare and Nursery School   | ACS      | N/A    | 177.2                                      | 4.6                                | N/A      | 218.7                              | 5.7                        | N/A     | 170.4 | 4.4   |     | 161.7       | 4.2        | Individual building   |             | 
| 1428584656  | 4       | 12022 | 20  | 4260903 | All My Children Daycare and Nursery School   | ACS      | N/A    | 192.1                                      | 5.2                                | N/A      | 201.3                              | 5.4                        | N/A     | 205.7 | 5.5   |     | 196.3       | 5.2        | Individual building   |             | 
| 1428584656  | 4       | 10193 | 1   | 4216947 | All My Children Daycare and Nursery School   | ACS      | N/A    | 136.0                                      | 3.7                                | N/A      | 128.0                              | 3.4                        | N/A     | 151.1 | 4.1   |     | 133.4       | 3.6        | Individual building   |             | 
| 1428584656  | 4       | 12062 | 51  | 4261925 | Alpha Kappa Alpha Sorority Child Care Center | ACS      | N/A    | 144.5                                      | 3.7                                | N/A      | 128.4                              | 3.3                        | N/A     | 120.9 | 3.1   |     | 135.6       | 3.5        | Individual building   |             | 
```