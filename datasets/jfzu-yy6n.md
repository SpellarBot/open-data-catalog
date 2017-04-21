# Oil Boilers - Detailed Fuel Consumption and Building Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-boilers-detailed-fuel-consumption-and-building-data-6f506) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jfzu-yy6n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jfzu-yy6n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jfzu-yy6n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jfzu-yy6n |
| Name | Oil Boilers - Detailed Fuel Consumption and Building Data |
| Attribution | Mayor's Office of Long-Term Planning and Sustainability (OLTPS) |
| Category | Housing & Development |
| Tags | energy, power, environment, planning, construction, housing, property |
| Created | 2011-09-29T15:45:34Z |
| Publication Date | 2013-06-21T20:49:55Z |

## Description

Detailed data on NYC buildings with oil boilers, including fuel consumption, BBL, building owner/management info, deadline for complying with Audit and Retrocommissioning Law, building type and year constructed, number of floors and residential units, Condo/Coop status, and more.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                            | Name                                                                                     | Data Type | Render Type |
| ======== | ============== | ===================================================================================== | ======================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                           | updated_at                                                                               | meta_data | meta_data   |
| Yes      | series tag     | borough_block_and_lot_                                                                | Borough, Block and Lot #                                                                 | text      | text        |
| Yes      | series tag     | natural_gas_utility_con_edison_or_national_grid                                       | Natural Gas Utility (Con Edison or National Grid                                         | text      | text        |
| Yes      | series tag     | building_manager                                                                      | Building Manager                                                                         | text      | text        |
| Yes      | series tag     | owner                                                                                 | Owner                                                                                    | text      | text        |
| Yes      | series tag     | dep_boiler_application_                                                               | DEP Boiler Application #                                                                 | text      | text        |
| Yes      | series tag     | deadline_for_phasing_out_6_oil_i_e_data_of_next_dep_permit_renewal_after_july_1_2012_ | Deadline for phasing out #6 oil (i.e. data of next DEP permit renewal after July 1 2012) | text      | text        |
| Yes      | series tag     | boiler_model                                                                          | Boiler Model                                                                             | text      | text        |
| Yes      | numeric metric | number_of_identical_boilers                                                           | Number of identical boilers                                                              | number    | number      |
| Yes      | numeric metric | boiler_capacity_gross_btu_                                                            | Boiler capacity (Gross BTU)                                                              | number    | number      |
| No       |                | boiler_installation_date                                                              | Boiler Installation Date                                                                 | text      | text        |
| Yes      | numeric metric | estimated_retirement_date_of_boiler_assuming_35_year_average_useful_life_             | Estimated retirement date of boiler (assuming 35 year average useful life)               | number    | text        |
| Yes      | series tag     | is_boiler_dual_fuel_capable_                                                          | Is boiler dual fuel capable?                                                             | text      | text        |
| Yes      | series tag     | age_range_of_boiler                                                                   | Age range of boiler                                                                      | text      | text        |
| Yes      | series tag     | burner_model                                                                          | Burner Model                                                                             | text      | text        |
| Yes      | series tag     | primary_fuel                                                                          | Primary Fuel                                                                             | text      | text        |
| Yes      | numeric metric | total_estimated_cosumption_high_estimate_gallons_                                     | Total Estimated Cosumption - High Estimate (Gallons)                                     | number    | number      |
| Yes      | numeric metric | total_estimated_cosumption_low_estimate_gallons_                                      | Total Estimated Cosumption - Low Estimate (Gallons)                                      | number    | number      |
| Yes      | numeric metric | total_estimated_cosumption_high_estimate_mmbtus_                                      | Total Estimated Cosumption - High Estimate (MMBTUs)                                      | number    | number      |
| Yes      | numeric metric | total_estimated_cosumption_low_estimate_mmbtus_                                       | Total Estimated Cosumption - Low Estimate (MMBTUs)                                       | number    | number      |
| Yes      | series tag     | needs_to_comply_with_greener_greater_buildings_laws_                                  | Needs to comply with Greener Greater Buildings Laws?                                     | text      | text        |
| Yes      | numeric metric | deadline_for_complying_with_audit_and_retrocommissioning_law                          | Deadline for complying with Audit and Retrocommissioning Law                             | number    | text        |
| Yes      | series tag     | building_type                                                                         | Building Type                                                                            | text      | text        |
| Yes      | series tag     | city_council_district                                                                 | City Council District                                                                    | text      | number      |
| Yes      | numeric metric | total_area_of_buildings_on_lot                                                        | Total area of buildings on lot                                                           | number    | number      |
| Yes      | numeric metric | number_of_buildings_on_property_tax_lot_                                              | Number of buildings on property (tax lot)                                                | number    | number      |
| Yes      | numeric metric | number_of_floors                                                                      | Number of floors                                                                         | number    | number      |
| Yes      | numeric metric | number_of_residential_units                                                           | Number of residential units                                                              | number    | number      |
| Yes      | numeric metric | number_of_total_units                                                                 | Number of total units                                                                    | number    | number      |
| Yes      | numeric metric | year_constructed                                                                      | Year constructed                                                                         | number    | text        |
| Yes      | series tag     | condominium_housing_                                                                  | Condominium housing?                                                                     | text      | text        |
| Yes      | series tag     | cooperative_housing_                                                                  | Cooperative housing?                                                                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = boiler_installation_date
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:number_of_identical_boilers p:integer l:"Number of identical boilers" t:dataTypeName=number

metric m:boiler_capacity_gross_btu_ p:float l:"Boiler capacity (Gross BTU)" t:dataTypeName=number

metric m:estimated_retirement_date_of_boiler_assuming_35_year_average_useful_life_ p:integer l:"Estimated retirement date of boiler (assuming 35 year average useful life)" t:dataTypeName=number

metric m:total_estimated_cosumption_high_estimate_gallons_ p:double l:"Total Estimated Cosumption - High Estimate (Gallons)" t:dataTypeName=number

metric m:total_estimated_cosumption_low_estimate_gallons_ p:double l:"Total Estimated Cosumption - Low Estimate (Gallons)" t:dataTypeName=number

metric m:total_estimated_cosumption_high_estimate_mmbtus_ p:double l:"Total Estimated Cosumption - High Estimate (MMBTUs)" t:dataTypeName=number

metric m:total_estimated_cosumption_low_estimate_mmbtus_ p:double l:"Total Estimated Cosumption - Low Estimate (MMBTUs)" t:dataTypeName=number

metric m:deadline_for_complying_with_audit_and_retrocommissioning_law p:integer l:"Deadline for complying with Audit and Retrocommissioning Law" t:dataTypeName=number

metric m:total_area_of_buildings_on_lot p:integer l:"Total area of buildings on lot" t:dataTypeName=number

metric m:number_of_buildings_on_property_tax_lot_ p:integer l:"Number of buildings on property (tax lot)" t:dataTypeName=number

metric m:number_of_floors p:integer l:"Number of floors" t:dataTypeName=number

metric m:number_of_residential_units p:integer l:"Number of residential units" t:dataTypeName=number

metric m:number_of_total_units p:integer l:"Number of total units" t:dataTypeName=number

metric m:year_constructed p:integer l:"Year constructed" t:dataTypeName=number

entity e:jfzu-yy6n l:"Oil Boilers - Detailed Fuel Consumption and Building Data" t:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)" t:url=https://data.cityofnewyork.us/api/views/jfzu-yy6n

property e:jfzu-yy6n t:meta.view v:id=jfzu-yy6n v:category="Housing & Development" v:averageRating=0 v:name="Oil Boilers - Detailed Fuel Consumption and Building Data" v:attribution="Mayor's Office of Long-Term Planning and Sustainability (OLTPS)"

property e:jfzu-yy6n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jfzu-yy6n t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough_block_and_lot_ | natural_gas_utility_con_edison_or_national_grid | building_manager | owner | dep_boiler_application_ | deadline_for_phasing_out_6_oil_i_e_data_of_next_dep_permit_renewal_after_july_1_2012_ | boiler_model | number_of_identical_boilers | boiler_capacity_gross_btu_ | boiler_installation_date | estimated_retirement_date_of_boiler_assuming_35_year_average_useful_life_ | is_boiler_dual_fuel_capable_ | age_range_of_boiler | burner_model | primary_fuel | total_estimated_cosumption_high_estimate_gallons_ | total_estimated_cosumption_low_estimate_gallons_ | total_estimated_cosumption_high_estimate_mmbtus_ | total_estimated_cosumption_low_estimate_mmbtus_ | needs_to_comply_with_greener_greater_buildings_laws_ | deadline_for_complying_with_audit_and_retrocommissioning_law | building_type | city_council_district | total_area_of_buildings_on_lot | number_of_buildings_on_property_tax_lot_ | number_of_floors | number_of_residential_units | number_of_total_units | year_constructed | condominium_housing_ | cooperative_housing_ | 
| =========== | ====================== | =============================================== | ================ | ===== | ======================= | ===================================================================================== | ============ | =========================== | ========================== | ======================== | ========================================================================= | ============================ | =================== | ============ | ============ | ================================================= | ================================================ | ================================================ | =============================================== | ==================================================== | ============================================================ | ============= | ===================== | ============================== | ======================================== | ================ | =========================== | ===================== | ================ | ==================== | ==================== | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
| 1317285981  |                        |                                                 |                  |       |                         |                                                                                       |              |                             |                            |                          |                                                                           |                              |                     |              |              |                                                   |                                                  |                                                  |                                                 |                                                      |                                                              |               |                       |                                |                                          |                  |                             |                       |                  |                      |                      | 
```