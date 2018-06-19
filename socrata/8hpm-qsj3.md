# MDOT Performance Dashboard - Annual Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdot-performance-dashboard-annual-data) |
| Metadata | [Link](https://data.maryland.gov/api/views/8hpm-qsj3) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8hpm-qsj3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8hpm-qsj3/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8hpm-qsj3 |
| Name | MDOT Performance Dashboard - Annual Data |
| Attribution | Maryland Department of Transportation |
| Category | Transportation |
| Created | 2016-07-22T20:24:24Z |
| Publication Date | 2016-10-25T19:43:31Z |

## Description

Set of annual MDOT perfromance data including port, transit, bridge and highway condition, and MVA branch office wait time data.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                      | Name                                                                                                              | Data Type     | Render Type   |
| ======== | ============== | =============================================================================================================== | ================================================================================================================= | ============= | ============= |
| Yes      | time           | date                                                                                                            | Date for Fiscal Year                                                                                              | calendar_date | calendar_date |
| Yes      | series tag     | year                                                                                                            | Year                                                                                                              | text          | text          |
| Yes      | numeric metric | md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year                                      | MD Port Administration Total General Cargo Tonnage (millions) (by Fiscal Year)                                    | number        | number        |
| Yes      | numeric metric | cargo_tonnage_forecast                                                                                          | Cargo Tonnage Forecast (millions)                                                                                 | number        | number        |
| Yes      | numeric metric | mta_core_bus_ridership_fy                                                                                       | MTA - Core Bus Ridership (FY)                                                                                     | number        | number        |
| Yes      | numeric metric | mta_baltimore_metro_ridership_fy                                                                                | MTA - Baltimore Metro Ridership (FY)                                                                              | number        | number        |
| Yes      | numeric metric | mta_light_rail_ridership_fy                                                                                     | MTA - Light Rail Ridership (FY)                                                                                   | number        | number        |
| Yes      | numeric metric | mta_mobility_paratransit_ridership_fy                                                                           | MTA - Mobility Paratransit Ridership (FY)                                                                         | number        | number        |
| Yes      | numeric metric | mta_call_a_ride_ridership_formerly_taxi_access_fy                                                               | MTA - Call a Ride Ridership (formerly Taxi Access) (FY)                                                           | number        | number        |
| Yes      | numeric metric | mta_marc_ridership_fy                                                                                           | MTA - MARC Ridership (FY)                                                                                         | number        | number        |
| Yes      | numeric metric | mta_commuter_bus_ridership_contracted_to_balt_wash_fy                                                           | MTA - Commuter Bus Ridership (Contracted to Balt & Wash) (FY)                                                     | number        | number        |
| Yes      | numeric metric | total_mta_ridership_fy                                                                                          | Total MTA Ridership (FY)                                                                                          | number        | number        |
| Yes      | numeric metric | locally_owned_transit_systems_lots_ridership_fy                                                                 | Locally Owned Transit Systems (LOTS) Ridership (FY)                                                               | number        | number        |
| Yes      | numeric metric | washington_metropolitan_area_transit_authority_ridership_maryland_only_fy                                       | Washington Metropolitan Area Transit Authority Ridership (Maryland Only) (FY)                                     | number        | number        |
| Yes      | numeric metric | total_maryland_transit_ridership_mta_lots_wmata_fy                                                              | Total Maryland Transit Ridership (MTA, LOTS & WMATA) (FY)                                                         | number        | number        |
| Yes      | numeric metric | average_mva_branch_office_customer_wait_time_in_minutes_fy                                                      | Average MVA Branch Office Customer Wait Time (in minutes) (FY)                                                    | number        | number        |
| Yes      | numeric metric | percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy | Percentage of the MD State Highway Administration Highway Network in overall preferred maintenance condition (CY) | percent       | percent       |
| Yes      | numeric metric | percentage_of_state_bridges_that_are_structurally_deficient_cy                                                  | Percentage of State Bridges that are Structurally Deficient (CY)                                                  | percent       | percent       |
| No       |                | date_for_calendar_year                                                                                          | Date for Calendar Year                                                                                            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_for_calendar_year
```

## Data Commands

```ls
series e:8hpm-qsj3 d:2011-06-30T00:00:00.000Z t:year=2011 m:total_maryland_transit_ridership_mta_lots_wmata_fy=279042589 m:md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year=8.69 m:locally_owned_transit_systems_lots_ridership_fy=40243273 m:mta_marc_ridership_fy=8232729 m:total_mta_ridership_fy=115622316 m:percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy=82.2 m:mta_mobility_paratransit_ridership_fy=1351065 m:percentage_of_state_bridges_that_are_structurally_deficient_cy=3.9 m:average_mva_branch_office_customer_wait_time_in_minutes_fy=22 m:washington_metropolitan_area_transit_authority_ridership_maryland_only_fy=123177000 m:mta_call_a_ride_ridership_formerly_taxi_access_fy=308662 m:mta_commuter_bus_ridership_contracted_to_balt_wash_fy=4096562 m:mta_baltimore_metro_ridership_fy=14587930 m:mta_light_rail_ridership_fy=8655209 m:mta_core_bus_ridership_fy=78390159

series e:8hpm-qsj3 d:2012-06-30T00:00:00.000Z t:year=2012 m:total_maryland_transit_ridership_mta_lots_wmata_fy=285785639 m:md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year=9.33 m:locally_owned_transit_systems_lots_ridership_fy=40907881 m:mta_marc_ridership_fy=8451695 m:total_mta_ridership_fy=118080758 m:percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy=85.1 m:mta_mobility_paratransit_ridership_fy=1554592 m:percentage_of_state_bridges_that_are_structurally_deficient_cy=3.5 m:average_mva_branch_office_customer_wait_time_in_minutes_fy=19.9 m:washington_metropolitan_area_transit_authority_ridership_maryland_only_fy=126797000 m:mta_call_a_ride_ridership_formerly_taxi_access_fy=345469 m:mta_commuter_bus_ridership_contracted_to_balt_wash_fy=4289775 m:mta_baltimore_metro_ridership_fy=15364164 m:mta_light_rail_ridership_fy=8539996 m:mta_core_bus_ridership_fy=79535067

series e:8hpm-qsj3 d:2013-06-30T00:00:00.000Z t:year=2013 m:total_maryland_transit_ridership_mta_lots_wmata_fy=282817369 m:md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year=9.55 m:locally_owned_transit_systems_lots_ridership_fy=40280758 m:mta_marc_ridership_fy=9062254 m:total_mta_ridership_fy=119259611 m:percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy=83.4 m:mta_mobility_paratransit_ridership_fy=1651198 m:percentage_of_state_bridges_that_are_structurally_deficient_cy=3 m:average_mva_branch_office_customer_wait_time_in_minutes_fy=25.2 m:washington_metropolitan_area_transit_authority_ridership_maryland_only_fy=123277000 m:mta_call_a_ride_ridership_formerly_taxi_access_fy=432534 m:mta_commuter_bus_ridership_contracted_to_balt_wash_fy=4187141 m:mta_baltimore_metro_ridership_fy=15208352 m:mta_light_rail_ridership_fy=8647381 m:mta_core_bus_ridership_fy=80070751
```

## Meta Commands

```ls
metric m:md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year p:float l:"MD Port Administration Total General Cargo Tonnage (millions) (by Fiscal Year)" t:dataTypeName=number

metric m:cargo_tonnage_forecast p:float l:"Cargo Tonnage Forecast (millions)" t:dataTypeName=number

metric m:mta_core_bus_ridership_fy p:double l:"MTA - Core Bus Ridership (FY)" t:dataTypeName=number

metric m:mta_baltimore_metro_ridership_fy p:float l:"MTA - Baltimore Metro Ridership (FY)" t:dataTypeName=number

metric m:mta_light_rail_ridership_fy p:float l:"MTA - Light Rail Ridership (FY)" t:dataTypeName=number

metric m:mta_mobility_paratransit_ridership_fy p:double l:"MTA - Mobility Paratransit Ridership (FY)" t:dataTypeName=number

metric m:mta_call_a_ride_ridership_formerly_taxi_access_fy p:float l:"MTA - Call a Ride Ridership (formerly Taxi Access) (FY)" t:dataTypeName=number

metric m:mta_marc_ridership_fy p:float l:"MTA - MARC Ridership (FY)" t:dataTypeName=number

metric m:mta_commuter_bus_ridership_contracted_to_balt_wash_fy p:float l:"MTA - Commuter Bus Ridership (Contracted to Balt & Wash) (FY)" t:dataTypeName=number

metric m:total_mta_ridership_fy p:double l:"Total MTA Ridership (FY)" t:dataTypeName=number

metric m:locally_owned_transit_systems_lots_ridership_fy p:float l:"Locally Owned Transit Systems (LOTS) Ridership (FY)" t:dataTypeName=number

metric m:washington_metropolitan_area_transit_authority_ridership_maryland_only_fy p:float l:"Washington Metropolitan Area Transit Authority Ridership (Maryland Only) (FY)" t:dataTypeName=number

metric m:total_maryland_transit_ridership_mta_lots_wmata_fy p:double l:"Total Maryland Transit Ridership (MTA, LOTS & WMATA) (FY)" t:dataTypeName=number

metric m:average_mva_branch_office_customer_wait_time_in_minutes_fy p:float l:"Average MVA Branch Office Customer Wait Time (in minutes) (FY)" t:dataTypeName=number

metric m:percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy p:float l:"Percentage of the MD State Highway Administration Highway Network in overall preferred maintenance condition (CY)" t:dataTypeName=percent

metric m:percentage_of_state_bridges_that_are_structurally_deficient_cy p:float l:"Percentage of State Bridges that are Structurally Deficient (CY)" t:dataTypeName=percent

entity e:8hpm-qsj3 l:"MDOT Performance Dashboard - Annual Data" t:attribution="Maryland Department of Transportation" t:url=https://data.maryland.gov/api/views/8hpm-qsj3

property e:8hpm-qsj3 t:meta.view v:id=8hpm-qsj3 v:category=Transportation v:averageRating=0 v:name="MDOT Performance Dashboard - Annual Data" v:attribution="Maryland Department of Transportation"

property e:8hpm-qsj3 t:meta.view.license v:name="Public Domain"

property e:8hpm-qsj3 t:meta.view.owner v:id=w3wv-wxfw v:screenName="Mike Haley" v:displayName="Mike Haley"

property e:8hpm-qsj3 t:meta.view.tableauthor v:id=w3wv-wxfw v:screenName="Mike Haley" v:roleName=editor v:displayName="Mike Haley"
```

## Top Records

```ls
| date                | year          | md_port_administration_total_general_cargo_tonnage_millions_by_fiscal_year | cargo_tonnage_forecast | mta_core_bus_ridership_fy | mta_baltimore_metro_ridership_fy | mta_light_rail_ridership_fy | mta_mobility_paratransit_ridership_fy | mta_call_a_ride_ridership_formerly_taxi_access_fy | mta_marc_ridership_fy | mta_commuter_bus_ridership_contracted_to_balt_wash_fy | total_mta_ridership_fy | locally_owned_transit_systems_lots_ridership_fy | washington_metropolitan_area_transit_authority_ridership_maryland_only_fy | total_maryland_transit_ridership_mta_lots_wmata_fy | average_mva_branch_office_customer_wait_time_in_minutes_fy | percentage_of_the_md_state_highway_administration_highway_network_in_overall_preferred_maintenance_condition_cy | percentage_of_state_bridges_that_are_structurally_deficient_cy | date_for_calendar_year | 
| =================== | ============= | ========================================================================== | ====================== | ========================= | ================================ | =========================== | ===================================== | ================================================= | ===================== | ===================================================== | ====================== | =============================================== | ========================================================================= | ================================================== | ========================================================== | =============================================================================================================== | ============================================================== | ====================== | 
| 2011-06-30T00:00:00 | 2011          | 8.69                                                                       |                        | 78390159.00               | 14587930.00                      | 8655209.00                  | 1351065.00                            | 308662.00                                         | 8232729.00            | 4096562.00                                            | 115622316.00           | 40243273.00                                     | 123177000.00                                                              | 279042589.00                                       | 22                                                         | 82.2                                                                                                            | 3.9                                                            | 2011-12-31T00:00:00    | 
| 2012-06-30T00:00:00 | 2012          | 9.33                                                                       |                        | 79535067.00               | 15364164.00                      | 8539996.00                  | 1554592.00                            | 345469.00                                         | 8451695.00            | 4289775.00                                            | 118080758.00           | 40907881.00                                     | 126797000.00                                                              | 285785639.00                                       | 19.9                                                       | 85.1                                                                                                            | 3.5                                                            | 2012-12-31T00:00:00    | 
| 2013-06-30T00:00:00 | 2013          | 9.55                                                                       |                        | 80070751.00               | 15208352.00                      | 8647381.00                  | 1651198.00                            | 432534.00                                         | 9062254.00            | 4187141.00                                            | 119259611.00           | 40280758.00                                     | 123277000.00                                                              | 282817369.00                                       | 25.2                                                       | 83.4                                                                                                            | 3.0                                                            | 2013-12-31T00:00:00    | 
| 2014-06-30T00:00:00 | 2014          | 9.60                                                                       |                        | 75780350.00               | 14632430.00                      | 8105743.00                  | 1781084.00                            | 507718.00                                         | 9167935.00            | 4017089.00                                            | 113992349.00           | 42500000.00                                     | 121243000.00                                                              | 277735349.00                                       | 28.1                                                       | 83.4                                                                                                            | 2.8                                                            | 2014-12-31T00:00:00    | 
| 2015-06-30T00:00:00 | 2015          | 9.74                                                                       |                        | 78697164.00               | 13900813.00                      | 7657256.00                  | 1892901.00                            | 601578.00                                         | 9245588.00            | 4034248.00                                            | 116029548.00           | 39440669.00                                     | 122800000.00                                                              | 278270217.00                                       | 21.6                                                       | 78.8                                                                                                            | 2.4                                                            | 2015-12-31T00:00:00    | 
| 2017-06-30T00:00:00 | 2017 Forecast |                                                                            | 9.8                    |                           |                                  |                             |                                       |                                                   |                       |                                                       |                        |                                                 |                                                                           |                                                    |                                                            |                                                                                                                 |                                                                | 2017-12-31T00:00:00    | 
| 2016-06-30T00:00:00 | 2016          | 9.8                                                                        |                        | 75901000                  | 12222000                         | 7475000                     | 1981000                               | 574000                                            | 8962000               | 3928000                                               | 111043000              | 38476000                                        | 114252000                                                                 | 263771000                                          | 24                                                         | 84                                                                                                              | 2.4                                                            | 2016-12-31T00:00:00    | 
```