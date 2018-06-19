# Chicago Energy Benchmarking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-energy-benchmarking) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/xq83-jr8c) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/xq83-jr8c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/xq83-jr8c/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | xq83-jr8c |
| Name | Chicago Energy Benchmarking |
| Attribution | City of Chicago |
| Category | Environment & Sustainable Development |
| Tags | 2014, 2015, buildings, energy, sustainability, benchmarks |
| Created | 2015-12-03T23:02:34Z |
| Publication Date | 2016-12-02T16:00:04Z |

## Description

The Chicago Building Energy Use Benchmarking Ordinance calls on existing municipal, commercial, and residential buildings larger than 50,000 square feet to track whole-building energy use, report to the City annually, and verify data accuracy every three years. The law, which phases in from 2014-2017, covers less than 1% of Chicago?s buildings, which account for approximately 20% of total energy used by all buildings. For more details, including ordinance text, rules and regulations, and timing, please visit www.CityofChicago.org/EnergyBenchmarking

The ordinance authorizes the City to share property-specific information with the public, beginning with the second year in which a building is required to comply. 

The dataset represents self-reported and publicly-available property information by calendar year. Currently, the data includes calendar year 2014 information for 243 properties, as well as calendar year 2015 information for over 1,500 properties. In future years, the City will continue to release additional building data, as-authorized by the ordinance. 

The "Data Year" column and filtered views under "More Views" can be used to isolate specific years.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| Yes      | time           | data_year                                | Data Year                                  | number    | number      |
| No       |                | id                                       | ID                                         | text      | number      |
| Yes      | series tag     | property_name                            | Property Name                              | text      | text        |
| No       |                | address                                  | Address                                    | text      | text        |
| Yes      | series tag     | zip_code                                 | ZIP Code                                   | text      | text        |
| Yes      | series tag     | community_area                           | Community Area                             | text      | text        |
| Yes      | series tag     | primary_property_type                    | Primary Property Type                      | text      | text        |
| Yes      | numeric metric | gross_floor_area_buildings_sq_ft         | Gross Floor Area - Buildings (sq ft)       | number    | number      |
| No       |                | year_built                               | Year Built                                 | number    | number      |
| Yes      | numeric metric | of_buildings                             | # of Buildings                             | number    | number      |
| Yes      | numeric metric | energy_star_score                        | ENERGY STAR Score                          | number    | number      |
| Yes      | numeric metric | electricity_use_kbtu                     | Electricity Use (kBtu)                     | number    | number      |
| Yes      | numeric metric | natural_gas_use_kbtu                     | Natural Gas Use (kBtu)                     | number    | number      |
| Yes      | series tag     | district_steam_use_kbtu                  | District Steam Use (kBtu)                  | text      | number      |
| Yes      | series tag     | district_chilled_water_use_kbtu          | District Chilled Water Use (kBtu)          | text      | number      |
| Yes      | numeric metric | all_other_fuel_use_kbtu                  | All Other Fuel Use (kBtu)                  | number    | number      |
| Yes      | numeric metric | site_eui_kbtu_sq_ft                      | Site EUI (kBtu/sq ft)                      | number    | number      |
| Yes      | numeric metric | source_eui_kbtu_sq_ft                    | Source EUI (kBtu/sq ft)                    | number    | number      |
| Yes      | numeric metric | weather_normalized_site_eui_kbtu_sq_ft   | Weather Normalized Site EUI (kBtu/sq ft)   | number    | number      |
| Yes      | numeric metric | weather_normalized_source_eui_kbtu_sq_ft | Weather Normalized Source EUI (kBtu/sq ft) | number    | number      |
| Yes      | numeric metric | total_ghg_emissions_metric_tons_co2e     | Total GHG Emissions (Metric Tons CO2e)     | number    | number      |
| Yes      | numeric metric | ghg_intensity_kg_co2e_sq_ft              | GHG Intensity (kg CO2e/sq ft)              | number    | number      |
| No       |                | latitude                                 | Latitude                                   | number    | number      |
| No       |                | longitude                                | Longitude                                  | number    | number      |
```

## Time Field

```ls
Value = data_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id,address,year_built,latitude,longitude
```

## Data Commands

```ls
series e:xq83-jr8c d:2014-01-01T00:00:00.000Z t:zip_code=60625 t:property_name="Roosevelt Hi-CPS" t:primary_property_type="K-12 School" t:community_area="ALBANY PARK" m:of_buildings=1 m:weather_normalized_source_eui_kbtu_sq_ft=122 m:source_eui_kbtu_sq_ft=129 m:weather_normalized_site_eui_kbtu_sq_ft=75 m:total_ghg_emissions_metric_tons_co2e=2379 m:site_eui_kbtu_sq_ft=80 m:gross_floor_area_buildings_sq_ft=319900 m:natural_gas_use_kbtu=18731796 m:energy_star_score=71 m:electricity_use_kbtu=6889272 m:ghg_intensity_kg_co2e_sq_ft=7.44

series e:xq83-jr8c d:2014-01-01T00:00:00.000Z t:zip_code=60632 t:property_name="Curie Metrop-CPS" t:primary_property_type="K-12 School" t:community_area="ARCHER HEIGHTS" m:of_buildings=1 m:weather_normalized_source_eui_kbtu_sq_ft=261 m:source_eui_kbtu_sq_ft=268 m:weather_normalized_site_eui_kbtu_sq_ft=93 m:total_ghg_emissions_metric_tons_co2e=7573 m:site_eui_kbtu_sq_ft=96 m:gross_floor_area_buildings_sq_ft=447330 m:natural_gas_use_kbtu=7180231 m:energy_star_score=19 m:electricity_use_kbtu=35792767 m:ghg_intensity_kg_co2e_sq_ft=16.93

series e:xq83-jr8c d:2014-01-01T00:00:00.000Z t:zip_code=60616 t:property_name="METROPOLITIAN PIER AND EXPOSITION AUTHORITY" t:primary_property_type="Convention Center" t:community_area="ARMOUR SQUARE" m:of_buildings=8 m:weather_normalized_source_eui_kbtu_sq_ft=200 m:source_eui_kbtu_sq_ft=204 m:weather_normalized_site_eui_kbtu_sq_ft=86 m:total_ghg_emissions_metric_tons_co2e=115833 m:site_eui_kbtu_sq_ft=90 m:gross_floor_area_buildings_sq_ft=9245333 m:natural_gas_use_kbtu=344178866 m:electricity_use_kbtu=485542954 m:ghg_intensity_kg_co2e_sq_ft=12.53
```

## Meta Commands

```ls
metric m:gross_floor_area_buildings_sq_ft p:integer l:"Gross Floor Area - Buildings (sq ft)" d:"Total interior floor space in square feet between the outside surfaces of a building?s enclosing walls, with the exception of any interior space used for parking. This includes tenant space, common areas, stairwells, basements, and storage, but does not include any interior parking areas. This is the Property Gross Floor Area - EPA Calculated (Buildings) field from Portfolio Manager." t:dataTypeName=number

metric m:of_buildings p:integer l:"# of Buildings" d:"Number of buildings included in the property's report. In cases where a property is reporting as a campus, multiple buildings may be included in one report." t:dataTypeName=number

metric m:energy_star_score p:integer l:"ENERGY STAR Score" d:"1-100 rating that assesses a property?s overall energy performance, based on national data to control for differences among climate, building uses, and operations. A score of 50 represents the national median." t:dataTypeName=number

metric m:electricity_use_kbtu p:integer l:"Electricity Use (kBtu)" d:"The annual amount of electricity consumed by the property on-site, including electricity purchased from the grid and generated by onsite renewable systems, measured in thousands of British thermal units (kBtu)." t:dataTypeName=number

metric m:natural_gas_use_kbtu p:integer l:"Natural Gas Use (kBtu)" d:"The annual amount of utility-supplied natural gas consumed by the property, measured in thousands of British thermal units (kBtu)." t:dataTypeName=number

metric m:all_other_fuel_use_kbtu p:integer l:"All Other Fuel Use (kBtu)" d:"The annual amount of fuel use other than electricity, natural gas, district chilled water, or district steam consumed by the property on-site, measured in thousands of British thermal units (kBtu)." t:dataTypeName=number

metric m:site_eui_kbtu_sq_ft p:float l:"Site EUI (kBtu/sq ft)" d:"Site Energy Use Intensity (EUI) is a property's Site Energy Use divided by its gross floor area. Site Energy Use is the annual amount of all the energy consumed by the property on-site, as reported on utility bills. Site EUI is measured in thousands of British thermal units (kBtu) per square foot." t:dataTypeName=number

metric m:source_eui_kbtu_sq_ft p:double l:"Source EUI (kBtu/sq ft)" d:"Source Energy Use Intensity (EUI) is a property's Source Energy Use divided by its gross floor area. Source Energy Use is the annual energy used to operate the property, including losses from generation, transmission, & distribution. Source EUI is measured in thousands of British thermal units (kBtu) per square foot." t:dataTypeName=number

metric m:weather_normalized_site_eui_kbtu_sq_ft p:float l:"Weather Normalized Site EUI (kBtu/sq ft)" d:"Weather Normalized (WN) Site Energy Use Intensity (EUI) is a property's WN Site Energy divided by its gross floor area (in square feet). WN Site Energy is the Site Energy Use the property would have consumed during 30-year average weather conditions. WN Site EUI is measured in measured in thousands of British thermal units (kBtu) per square foot." t:dataTypeName=number

metric m:weather_normalized_source_eui_kbtu_sq_ft p:float l:"Weather Normalized Source EUI (kBtu/sq ft)" d:"Weather Normalized (WN) Source Energy Use Intensity (EUI) is a property's WN Source Energy divided by its gross floor area. WN Source Energy is the Source Energy Use the property would have consumed during 30-year average weather conditions. WN Source EUI is measured in measured in thousands of British thermal units (kBtu) per square foot." t:dataTypeName=number

metric m:total_ghg_emissions_metric_tons_co2e p:integer l:"Total GHG Emissions (Metric Tons CO2e)" d:"The total amount of greenhouse gas emissions, including carbon dioxide, methane, and nitrous oxide gases released into the atmosphere as a result of energy consumption at the property, measured in metric tons of carbon dioxide equivalent." t:dataTypeName=number

metric m:ghg_intensity_kg_co2e_sq_ft p:float l:"GHG Intensity (kg CO2e/sq ft)" d:"Total Greenhouse Gas Emissions divided by property's gross floor area, measured in kilograms of carbon dioxide equivalent per square foot." t:dataTypeName=number

entity e:xq83-jr8c l:"Chicago Energy Benchmarking" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/xq83-jr8c

property e:xq83-jr8c t:meta.view v:id=xq83-jr8c v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Chicago Energy Benchmarking" v:attribution="City of Chicago"

property e:xq83-jr8c t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:xq83-jr8c t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| data_year | id     | property_name                               | address                   | zip_code | community_area  | primary_property_type                 | gross_floor_area_buildings_sq_ft | year_built | of_buildings | energy_star_score | electricity_use_kbtu | natural_gas_use_kbtu | district_steam_use_kbtu | district_chilled_water_use_kbtu | all_other_fuel_use_kbtu | site_eui_kbtu_sq_ft | source_eui_kbtu_sq_ft | weather_normalized_site_eui_kbtu_sq_ft | weather_normalized_source_eui_kbtu_sq_ft | total_ghg_emissions_metric_tons_co2e | ghg_intensity_kg_co2e_sq_ft | latitude    | longitude    | 
| ========= | ====== | =========================================== | ========================= | ======== | =============== | ===================================== | ================================ | ========== | ============ | ================= | ==================== | ==================== | ======================= | =============================== | ======================= | =================== | ===================== | ====================================== | ======================================== | ==================================== | =========================== | =========== | ============ | 
| 2014      | 157767 | Roosevelt Hi-CPS                            | 3436 W WILSON AVE         | 60625    | ALBANY PARK     | K-12 School                           | 319900                           | 1927       | 1            | 71                | 6889272              | 18731796             |                         |                                 |                         | 80                  | 129                   | 75                                     | 122                                      | 2379                                 | 7.44                        | 41.96501325 | -87.71451268 | 
| 2014      | 100256 | Curie Metrop-CPS                            | 4975 S Archer             | 60632    | ARCHER HEIGHTS  | K-12 School                           | 447330                           | 1990       | 1            | 19                | 35792767             | 7180231              |                         |                                 |                         | 96                  | 268                   | 93                                     | 261                                      | 7573                                 | 16.93                       | 41.802759   | -87.722671   | 
| 2014      | 101551 | METROPOLITIAN PIER AND EXPOSITION AUTHORITY | 301 Cermak Road           | 60616    | ARMOUR SQUARE   | Convention Center                     | 9245333                          | 1971       | 8            |                   | 485542954            | 344178866            |                         |                                 |                         | 90                  | 204                   | 86                                     | 200                                      | 115833                               | 12.53                       | 41.85284    | -87.634931   | 
| 2014      | 100396 | St. Rita of Cascia High School              | 7740 South Western Avenue | 60620    | ASHBURN         | K-12 School                           | 250000                           | 1960       | 1            | 68                | 6027551              | 15042857             |                         |                                 |                         | 84                  | 139                   | 80                                     | 135                                      | 2010                                 | 8.04                        | 41.7520028  | -87.68463714 | 
| 2014      | 250052 | Steinmetz Ac-CPS                            | 3030 N MOBILE AVE         | 60634    | BELMONT CRAGIN  | K-12 School                           | 323400                           | 1934       | 1            | 66                | 8184634              | 19187703             |                         |                                 |                         | 85                  | 142                   | 80                                     | 136                                      | 2664                                 | 8.24                        | 41.93560335 | -87.7843396  | 
| 2014      | 168174 | Kelly High S-CPS                            | 4136 S California Ave     | 60632    | BRIGHTON PARK   | K-12 School                           | 298432                           | 1928       | 1            | 54                | 8949806              | 17533370             |                         |                                 |                         | 89                  | 156                   | 79                                     | 146                                      | 2729                                 | 9.15                        | 41.818909   | -87.694567   | 
| 2014      | 102532 | Advocate Trinity Hospital                   | 2320 E. 93rd. Street      | 60617    | CALUMET HEIGHTS | Hospital (General Medical & Surgical) | 369087                           | 1960       | 1            | 57                | 31138936             | 60536647             |                         |                                 |                         | 248                 | 437                   | 245                                    | 433                                      | 9472                                 | 25.66                       | 41.72673518 | -87.56695195 | 
| 2014      | 250051 | Simeon Caree-CPS                            | 8235 S VINCENNES AVE      | 60620    | CHATHAM         | K-12 School                           | 284691                           | 2003       | 1            | 19                | 13609687             | 21476024             |                         |                                 |                         | 123                 | 229                   | 117                                    | 222                                      | 3875                                 | 13.61                       | 41.744236   | -87.635863   | 
| 2014      | 112188 | Dunbar Vocat-CPS                            | 3000 S King Dr            | 60616    | DOUGLAS         | K-12 School                           | 319937                           | 1955       | 1            | 15                | 5044007              | 26713862             |                         |                                 |                         | 99                  | 137                   | 97                                     | 135                                      | 2432                                 | 7.60                        | 41.83978929 | -87.61953177 | 
| 2014      | 111290 | IIT Research Tower                          | 10 West 35th Street       | 60616    | DOUGLAS         | College/University                    | 392894                           | 1964       | 1            |                   | 19183561             | 623800               |                         |                                 |                         | 50                  | 155                   |                                        |                                          | 3887                                 | 9.89                        | 41.83139755 | -87.62723022 | 
```