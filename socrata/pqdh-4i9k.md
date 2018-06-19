# Performance Ranges By Building Type 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-ranges-by-building-type-2015) |
| Metadata | [Link](https://data.seattle.gov/api/views/pqdh-4i9k) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/pqdh-4i9k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/pqdh-4i9k/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | pqdh-4i9k |
| Name | Performance Ranges By Building Type 2015 |
| Attribution | Office of Sustainability & Environment |
| Tags | buildings, energy, eui, energy star, multifamily, commercial, electricity, natural gas |
| Created | 2017-01-28T00:30:03Z |
| Publication Date | 2017-02-07T00:15:01Z |

## Description

Summary energy and building characteristics by building type for non-residential and multifamily buildings 20,000 square feet or greater that benchmark energy data with the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | building_type                              | Building Type                              | text      | text        |
| Yes      | numeric metric | minimum_eui                                | Minimum EUI                                | number    | number      |
| Yes      | numeric metric | 25th_percentile_of_eui                     | 25th Percentile of EUI                     | number    | number      |
| Yes      | numeric metric | median_site_eui                            | Median Site EUI                            | number    | number      |
| Yes      | numeric metric | 75th_percentile_of_eui                     | 75th Percentile of EUI                     | number    | number      |
| Yes      | numeric metric | maximum_eui                                | Maximum EUI                                | number    | number      |
| Yes      | numeric metric | median_site_eui_weather_normalized         | Median Site EUI Weather Normalized         | number    | number      |
| Yes      | numeric metric | median_source_eui                          | Median Source EUI                          | number    | number      |
| Yes      | numeric metric | median_energy_star_score                   | Median ENERGY STAR Score                   | number    | number      |
| Yes      | numeric metric | number_of_buildings                        | Number of Buildings                        | number    | number      |
| Yes      | numeric metric | total_gross_floor_area                     | Total Gross Floor Area                     | number    | number      |
| Yes      | numeric metric | median_gross_floor_area                    | Median Gross Floor Area                    | number    | number      |
| Yes      | numeric metric | median_year_built                          | Median Year Built                          | number    | number      |
| Yes      | numeric metric | percent_electricity                        | Percent Electricity                        | percent   | percent     |
| Yes      | numeric metric | percent_gas                                | Percent Gas                                | percent   | percent     |
| Yes      | numeric metric | percent_steam                              | Percent Steam                              | percent   | percent     |
| Yes      | numeric metric | percent_other                              | Percent Other                              | percent   | percent     |
| Yes      | numeric metric | number_of_bulidings_with_energy_star_score | Number of Bulidings with ENERGY STAR Score | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pqdh-4i9k d:2015-01-01T00:00:00.000Z t:building_type="Low-rise Multifamily" m:75th_percentile_of_eui=36 m:median_site_eui_weather_normalized=31.9 m:median_site_eui=29.1 m:25th_percentile_of_eui=24.9 m:median_energy_star_score=77 m:percent_other=0.03 m:maximum_eui=87.1 m:percent_electricity=74.97 m:minimum_eui=17.4 m:number_of_bulidings_with_energy_star_score=829 m:median_gross_floor_area=31457 m:total_gross_floor_area=40355349 m:median_source_eui=82.5 m:percent_gas=24.88 m:number_of_buildings=946 m:percent_steam=0.13 m:median_year_built=1978

series e:pqdh-4i9k d:2015-01-01T00:00:00.000Z t:building_type="Mid-rise Multifamily" m:75th_percentile_of_eui=42 m:median_site_eui_weather_normalized=35.7 m:median_site_eui=32.9 m:25th_percentile_of_eui=27.4 m:median_energy_star_score=85 m:percent_other=0 m:maximum_eui=85.4 m:percent_electricity=68.36 m:minimum_eui=19.3 m:number_of_bulidings_with_energy_star_score=422 m:median_gross_floor_area=58333 m:total_gross_floor_area=45659262 m:median_source_eui=87.9 m:percent_gas=31.39 m:number_of_buildings=516 m:percent_steam=0.25 m:median_year_built=1998

series e:pqdh-4i9k d:2015-01-01T00:00:00.000Z t:building_type="High-rise Multifamily" m:75th_percentile_of_eui=56 m:median_site_eui_weather_normalized=51.2 m:median_site_eui=47.6 m:25th_percentile_of_eui=37.1 m:median_energy_star_score=49 m:percent_other=0 m:maximum_eui=114.3 m:percent_electricity=61.9 m:minimum_eui=26.4 m:number_of_bulidings_with_energy_star_score=89 m:median_gross_floor_area=170000 m:total_gross_floor_area=20131288 m:median_source_eui=109.3 m:percent_gas=35.47 m:number_of_buildings=99 m:percent_steam=2.63 m:median_year_built=1982
```

## Meta Commands

```ls
metric m:minimum_eui p:float l:"Minimum EUI" d:"Minimum non-normalized (for weather) site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:25th_percentile_of_eui p:float l:"25th Percentile of EUI" d:"25th Percentile non-normalized (for weather) site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:median_site_eui p:float l:"Median Site EUI" d:"Median non-normalized (for weather) site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:75th_percentile_of_eui p:float l:"75th Percentile of EUI" d:"75th non-normalized (for weather) site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:maximum_eui p:float l:"Maximum EUI" d:"Maximum non-normalized (for weather) site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:median_site_eui_weather_normalized p:float l:"Median Site EUI Weather Normalized" d:"Median weather-normalized site EUI (kBtu/sf). 1% outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:median_source_eui p:float l:"Median Source EUI" d:"Median non-normalized (for weather) source EUI (kBtu/sf). 1% site EUI outliers and other identified errors have been excluded." t:dataTypeName=number

metric m:median_energy_star_score p:integer l:"Median ENERGY STAR Score" d:"Median 1-100 ENERGY STAR Score." t:dataTypeName=number

metric m:number_of_buildings p:integer l:"Number of Buildings" d:"Number of buildings used to compute EUI metrics." t:dataTypeName=number

metric m:total_gross_floor_area p:integer l:"Total Gross Floor Area" d:"Total gross floor area (sf) reported by buildings used to compute EUI metrics." t:dataTypeName=number

metric m:median_gross_floor_area p:integer l:"Median Gross Floor Area" d:"Median building floor area of buildings used to compute EUI metrics." t:dataTypeName=number

metric m:median_year_built p:integer l:"Median Year Built" d:"Median year built of buildings used to compute EUI metrics." t:dataTypeName=number

metric m:percent_electricity p:float l:"Percent Electricity" d:"Electricity as a percent of total energy consumption. 1% site EUI outliers and other identified errors have been excluded." t:dataTypeName=percent

metric m:percent_gas p:float l:"Percent Gas" d:"Natural gas as a percent of total energy consumption. 1% site EUI outliers and other identified errors have been excluded." t:dataTypeName=percent

metric m:percent_steam p:float l:"Percent Steam" d:"Steam as a percent of total energy consumption. 1% site EUI outliers and other identified errors have been excluded." t:dataTypeName=percent

metric m:percent_other p:float l:"Percent Other" d:"Other energy consumption (e.g. fuel oil or chilled water) as a percent of total energy consumption. 1% site EUI outliers and other identified errors have been excluded." t:dataTypeName=percent

metric m:number_of_bulidings_with_energy_star_score p:integer l:"Number of Bulidings with ENERGY STAR Score" d:"Number of buildings with a valid ENERGY STAR score" t:dataTypeName=number

entity e:pqdh-4i9k l:"Performance Ranges By Building Type 2015" t:attribution="Office of Sustainability & Environment" t:url=https://data.seattle.gov/api/views/pqdh-4i9k

property e:pqdh-4i9k t:meta.view v:id=pqdh-4i9k v:averageRating=0 v:name="Performance Ranges By Building Type 2015" v:attribution="Office of Sustainability & Environment"

property e:pqdh-4i9k t:meta.view.owner v:id=9yyf-ecsx v:screenName="Sullivan, Terry" v:displayName="Sullivan, Terry"

property e:pqdh-4i9k t:meta.view.tableauthor v:id=9yyf-ecsx v:screenName="Sullivan, Terry" v:roleName=publisher v:displayName="Sullivan, Terry"
```

## Top Records

```ls
| building_type              | minimum_eui | 25th_percentile_of_eui | median_site_eui | 75th_percentile_of_eui | maximum_eui | median_site_eui_weather_normalized | median_source_eui | median_energy_star_score | number_of_buildings | total_gross_floor_area | median_gross_floor_area | median_year_built | percent_electricity | percent_gas | percent_steam | percent_other | number_of_bulidings_with_energy_star_score | 
| ========================== | =========== | ====================== | =============== | ====================== | =========== | ================================== | ================= | ======================== | =================== | ====================== | ======================= | ================= | =================== | =========== | ============= | ============= | ========================================== | 
| Low-rise Multifamily       | 17.4        | 24.9                   | 29.1            | 36.0                   | 87.1        | 31.9                               | 82.5              | 77                       | 946                 | 40355349               | 31457                   | 1978              | 74.97               | 24.88       | 0.13          | 0.03          | 829                                        | 
| Mid-rise Multifamily       | 19.3        | 27.4                   | 32.9            | 42.0                   | 85.4        | 35.7                               | 87.9              | 85                       | 516                 | 45659262               | 58333                   | 1998              | 68.36               | 31.39       | 0.25          | 0.00          | 422                                        | 
| High-rise Multifamily      | 26.4        | 37.1                   | 47.6            | 56.0                   | 114.3       | 51.2                               | 109.3             | 49                       | 99                  | 20131288               | 170000                  | 1982              | 61.90               | 35.47       | 2.63          | 0.00          | 89                                         | 
| Small- to Mid-sized Office | 20.1        | 38.5                   | 52.5            | 69.9                   | 173.0       | 54.6                               | 145.0             | 74                       | 274                 | 13117419               | 39940                   | 1961              | 82.54               | 15.77       | 1.68          | 0.00          | 228                                        | 
| Large Office               | 20.6        | 47.1                   | 56.1            | 70.8                   | 178.5       | 58.3                               | 164.9             | 83                       | 158                 | 57875174               | 242281                  | 1984              | 91.49               | 5.46        | 2.92          | 0.13          | 151                                        | 
| Non-Refrigerated Warehouse | 0.2         | 13.1                   | 25.2            | 44.9                   | 199.8       | 26.7                               | 60.7              | 57                       | 185                 | 10716928               | 40028                   | 1964              | 65.09               | 34.91       | 0.00          | 0.00          | 145                                        | 
| Mixed Use Property         | 5.6         | 39.6                   | 56.1            | 93.3                   | 800.6       | 60.8                               | 133.1             | 80                       | 128                 | 13203588               | 44566                   | 1968              | 75.01               | 21.77       | 3.45          | 0.00          | 39                                         | 
| K-12 School                | 0.6         | 31.7                   | 37.1            | 49.1                   | 107.0       | 45.6                               | 80.2              | 84                       | 127                 | 9719893                | 52924                   | 1963              | 51.64               | 48.16       | 0.19          | 0.00          | 126                                        | 
| Retail Store               | 14.9        | 37.8                   | 58.3            | 83.9                   | 197.8       | 60.3                               | 149.7             | 70                       | 89                  | 7805166                | 45271                   | 1965              | 78.13               | 21.87       | 0.00          | 0.00          | 81                                         | 
| Hotel                      | 28.7        | 60.2                   | 77.1            | 96.3                   | 196.7       | 80.9                               | 173.1             | 61                       | 66                  | 10802832               | 101100                  | 1976              | 53.24               | 32.28       | 14.47         | 0.00          | 63                                         | 
```