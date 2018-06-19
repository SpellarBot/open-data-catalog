# Energy and Water Data Disclosure for Local Law 84 (2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-and-water-data-disclosure-for-local-law-84-2013) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rgfe-8y2z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rgfe-8y2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rgfe-8y2z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rgfe-8y2z |
| Name | Energy and Water Data Disclosure for Local Law 84 (2013) |
| Attribution | Mayor's Office of Long Term Planning and Sustainability (OLTPS) |
| Category | Environment |
| Tags | mayor's office of long term planning and sustainability (oltps), energy, water, benchmarking |
| Created | 2015-06-27T00:53:37Z |
| Publication Date | 2015-09-01T20:22:46Z |

## Description

In September 2014, New York City released the 2013 energy and water use data for all properties required to annually benchmark under Local Law 84.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                            | Data Type | Render Type |
| ======== | ============== | ========================================================== | =============================================================== | ========= | =========== |
| Yes      | series tag     | record_number                                              | Record Number                                                   | text      | number      |
| Yes      | numeric metric | nyc_borough_block_and_lot_bbl                              | NYC Borough, Block, and Lot (BBL)                               | number    | number      |
| Yes      | series tag     | co_reported_bbl_status                                     | Co-reported BBL Status                                          | text      | text        |
| Yes      | series tag     | bbls_co_reported                                           | BBLs Co-reported                                                | text      | text        |
| Yes      | series tag     | reported_nyc_building_identificaiton_numbers_bins          | Reported NYC Building Identificaiton Numbers (BINs)             | text      | text        |
| Yes      | series tag     | street_number                                              | Street Number                                                   | text      | text        |
| Yes      | series tag     | street_name                                                | Street Name                                                     | text      | text        |
| Yes      | series tag     | borough                                                    | Borough                                                         | text      | text        |
| Yes      | series tag     | zip_code                                                   | Zip Code                                                        | text      | number      |
| Yes      | series tag     | dof_benchmarking_submission_status                         | DOF Benchmarking Submission Status                              | text      | text        |
| Yes      | series tag     | site_eui_kbtu_ft2                                          | Site EUI(kBtu/ft2)                                              | text      | text        |
| Yes      | series tag     | weather_normalized_site_eui_kbtu_ft2                       | Weather Normalized Site EUI(kBtu/ft2)                           | text      | text        |
| Yes      | series tag     | source_eui_kbtu_ft2                                        | Source EUI(kBtu/ft2)                                            | text      | text        |
| Yes      | series tag     | weather_normalized_source_eui_kbtu_ft2                     | Weather Normalized Source EUI(kBtu/ft2)                         | text      | text        |
| Yes      | series tag     | municipally_supplied_potable_water_indoor_intensity_gal_ft | Municipally Supplied Potable Water - Indoor Intensity (gal/ft?) | text      | text        |
| Yes      | series tag     | automatic_water_benchmarking_eligible                      | Automatic Water Benchmarking Eligible                           | text      | text        |
| Yes      | series tag     | reported_water_method                                      | Reported Water Method                                           | text      | text        |
| Yes      | series tag     | energy_star_score                                          | ENERGY STAR Score                                               | text      | text        |
| Yes      | series tag     | total_ghg_emissions_mtco2e                                 | Total GHG Emissions(MtCO2e)                                     | text      | text        |
| Yes      | series tag     | direct_ghg_emissions_mtco2e                                | Direct GHG Emissions(MtCO2e)                                    | text      | text        |
| Yes      | series tag     | indirect_ghg_emissions_mtco2e                              | Indirect GHG Emissions(MtCO2e)                                  | text      | text        |
| Yes      | series tag     | reported_property_floor_area_building_s_ft                 | Reported Property Floor Area (Building(s)) (ft?)                | text      | text        |
| Yes      | numeric metric | dof_property_floor_area_buildngs_and_parking_ft2           | DOF Property Floor Area (Buildngs and Parking)(ft2)             | number    | number      |
| Yes      | series tag     | primary_property_type_self_selected                        | Primary Property Type - Self Selected                           | text      | text        |
| Yes      | numeric metric | dof_number_of_buildings                                    | DOF Number of Buildings                                         | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rgfe-8y2z d:2013-01-01T00:00:00.000Z t:reported_nyc_building_identificaiton_numbers_bins=1001007 t:weather_normalized_site_eui_kbtu_ft2="Not Available" t:municipally_supplied_potable_water_indoor_intensity_gal_ft="Not Available" t:reported_water_method=N/A t:reported_property_floor_area_building_s_ft=918919 t:dof_benchmarking_submission_status="BBL not valid" t:energy_star_score="Not Available" t:bbls_co_reported=1000410001 t:borough=Manhattan t:automatic_water_benchmarking_eligible=N/A t:weather_normalized_source_eui_kbtu_ft2="Not Available" t:primary_property_type_self_selected=Office t:record_number=12086 m:nyc_borough_block_and_lot_bbl=1000410001

series e:rgfe-8y2z d:2013-01-01T00:00:00.000Z t:zip_code=11375 t:reported_water_method=None t:reported_property_floor_area_building_s_ft=#N/A t:dof_benchmarking_submission_status="No Submission Matched to BBL" t:street_name="108 STREET" t:borough=Queens t:automatic_water_benchmarking_eligible=Yes t:street_number=63-10 t:record_number=14354 m:dof_number_of_buildings=1 m:dof_property_floor_area_buildngs_and_parking_ft2=82730 m:nyc_borough_block_and_lot_bbl=4021460028

series e:rgfe-8y2z d:2013-01-01T00:00:00.000Z t:reported_nyc_building_identificaiton_numbers_bins=2006460 t:weather_normalized_site_eui_kbtu_ft2="Not Available" t:municipally_supplied_potable_water_indoor_intensity_gal_ft="Not Available" t:reported_water_method=N/A t:reported_property_floor_area_building_s_ft=64200 t:dof_benchmarking_submission_status="BBL not valid" t:energy_star_score="Not Available" t:bbls_co_reported=2027620097 t:borough=Bronx t:automatic_water_benchmarking_eligible=N/A t:weather_normalized_source_eui_kbtu_ft2="Not Available" t:primary_property_type_self_selected="Multifamily Housing" t:record_number=12150 m:nyc_borough_block_and_lot_bbl=2027620097
```

## Meta Commands

```ls
metric m:nyc_borough_block_and_lot_bbl p:long l:"NYC Borough, Block, and Lot (BBL)" t:dataTypeName=number

metric m:dof_property_floor_area_buildngs_and_parking_ft2 p:integer l:"DOF Property Floor Area (Buildngs and Parking)(ft2)" t:dataTypeName=number

metric m:dof_number_of_buildings p:integer l:"DOF Number of Buildings" t:dataTypeName=number

entity e:rgfe-8y2z l:"Energy and Water Data Disclosure for Local Law 84 (2013)" t:attribution="Mayor's Office of Long Term Planning and Sustainability (OLTPS)" t:url=https://data.cityofnewyork.us/api/views/rgfe-8y2z

property e:rgfe-8y2z t:meta.view v:id=rgfe-8y2z v:category=Environment v:averageRating=0 v:name="Energy and Water Data Disclosure for Local Law 84 (2013)" v:attribution="Mayor's Office of Long Term Planning and Sustainability (OLTPS)"

property e:rgfe-8y2z t:meta.view.license v:name="Public Domain"

property e:rgfe-8y2z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rgfe-8y2z t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| record_number | nyc_borough_block_and_lot_bbl | co_reported_bbl_status | bbls_co_reported | reported_nyc_building_identificaiton_numbers_bins | street_number | street_name  | borough   | zip_code | dof_benchmarking_submission_status | site_eui_kbtu_ft2 | weather_normalized_site_eui_kbtu_ft2 | source_eui_kbtu_ft2 | weather_normalized_source_eui_kbtu_ft2 | municipally_supplied_potable_water_indoor_intensity_gal_ft | automatic_water_benchmarking_eligible | reported_water_method | energy_star_score | total_ghg_emissions_mtco2e | direct_ghg_emissions_mtco2e | indirect_ghg_emissions_mtco2e | reported_property_floor_area_building_s_ft | dof_property_floor_area_buildngs_and_parking_ft2 | primary_property_type_self_selected | dof_number_of_buildings | 
| ============= | ============================= | ====================== | ================ | ================================================= | ============= | ============ | ========= | ======== | ================================== | ================= | ==================================== | =================== | ====================================== | ========================================================== | ===================================== | ===================== | ================= | ========================== | =========================== | ============================= | ========================================== | ================================================ | =================================== | ======================= | 
| 12086         | 1000410001                    |                        | 1000410001       | 1001007                                           |               |              | Manhattan |          | BBL not valid                      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | N/A                   | Not Available     |                            |                             |                               | 918919                                     |                                                  | Office                              |                         | 
| 14354         | 4021460028                    |                        |                  |                                                   | 63-10         | 108 STREET   | Queens    | 11375    | No Submission Matched to BBL       |                   |                                      |                     |                                        |                                                            | Yes                                   | None                  |                   |                            |                             |                               | #N/A                                       | 82730                                            |                                     | 1                       | 
| 12150         | 2027620097                    |                        | 2027620097       | 2006460                                           |               |              | Bronx     |          | BBL not valid                      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | N/A                   | Not Available     |                            |                             |                               | 64200                                      |                                                  | Multifamily Housing                 |                         | 
| 12590         | 1006700001                    |                        |                  |                                                   | 201           | 11 AVENUE    | Manhattan | 10001    | No Submission Matched to BBL       |                   |                                      |                     |                                        |                                                            | No                                    | None                  |                   |                            |                             |                               | #N/A                                       | 440360                                           |                                     | 1                       | 
| 15591         | 2048300034                    |                        | 2048300034       | 2063117                                           |               |              | Bronx     |          | Not on Covered Buildings List      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | None                  | Not Available     |                            |                             |                               | 50000                                      |                                                  | Multifamily Housing                 |                         | 
| 12135         | 2006120205                    |                        | 2-00612-0205     | 3008876                                           |               |              | Bronx     |          | BBL not valid                      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | N/A                   | Not Available     |                            |                             |                               | 61800                                      |                                                  | Distribution Center                 |                         | 
| 8523          | 3050770001                    |                        | 3-05077-0001     | 3116471                                           | 1600          | CATON AVENUE | Brooklyn  | 11226    | Filed                              |                   | Not Available                        |                     | Not Available                          | Not Available                                              | No                                    | None                  | Not Available     |                            |                             |                               | 102198                                     | 102198                                           | Multifamily Housing                 | 1                       | 
| 15920         | 3065710023                    |                        | 3065710023       | 3173037                                           |               |              | Brooklyn  |          | Not on Covered Buildings List      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | None                  | Not Available     |                            | 174.6                       |                               | 46620                                      |                                                  | Multifamily Housing                 |                         | 
| 14241         | 4004490013                    |                        |                  |                                                   | 44-02         | 11 STREET    | Queens    | 11101    | No Submission Matched to BBL       |                   |                                      |                     |                                        |                                                            | Yes                                   | None                  |                   |                            |                             |                               | #N/A                                       | 120570                                           |                                     | 1                       | 
| 15925         | 3072240128                    |                        | 3072240128       | 3196035                                           |               |              | Brooklyn  |          | Not on Covered Buildings List      |                   | Not Available                        |                     | Not Available                          | Not Available                                              | N/A                                   | None                  | Not Available     |                            |                             |                               | 54029                                      |                                                  | Multifamily Housing                 |                         | 
```