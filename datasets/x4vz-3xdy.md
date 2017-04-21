# Airport Annual Performance Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-annual-performance-measures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/x4vz-3xdy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/x4vz-3xdy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/x4vz-3xdy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | x4vz-3xdy |
| Name | Airport Annual Performance Measures |
| Attribution | Austin-Bergstrom International Airport |
| Tags | airport, performance, resources, wildlife, recycling, employees, staff, de-icing, carbon footprint, security, arff, revenue, costs, customers, injuries, diversity, finance |
| Created | 2015-07-06T19:10:09Z |
| Publication Date | 2015-08-11T16:18:10Z |

## Description

Annual Performance Measures from Austin-Bergstrom International Airport. Covers a broad spectrum of categories from our four Strategic Focus areas:  Customer and Community Value; Operational Excellence; Environmental Stewardship; and Economic Sustainability.

## Columns

```ls
| Included | Schema Type    | Field Name                                                          | Name                                                                  | Data Type | Render Type |
| ======== | ============== | =================================================================== | ===================================================================== | ========= | =========== |
| Yes      | time           | reporting_year                                                      | Reporting Year                                                        | number    | text        |
| Yes      | numeric metric | terminal_electricity_use_kwh                                        | Terminal Electricity Use: KWH                                         | number    | number      |
| Yes      | numeric metric | terminal_natural_gas_use_ccf                                        | Terminal Natural Gas Use: CCF                                         | number    | number      |
| Yes      | numeric metric | terminal_water_use_gallons                                          | Terminal Water Use: Gallons                                           | number    | number      |
| Yes      | numeric metric | terminal_wastewater_use_gallons                                     | Terminal Wastewater Use: Gallons                                      | number    | number      |
| Yes      | numeric metric | campus_electrity_use_kwh                                            | Campus Electrity Use: KWH                                             | number    | number      |
| Yes      | numeric metric | campus_natural_gas_use_ccf                                          | Campus Natural Gas Use: CCF                                           | number    | number      |
| Yes      | numeric metric | campus_water_use_gallons                                            | Campus Water Use: Gallons                                             | number    | number      |
| Yes      | numeric metric | campus_reclaimed_water_use_gallons                                  | Campus Reclaimed Water Use: Gallons                                   | number    | number      |
| Yes      | numeric metric | campus_waste_water_use_gallons                                      | Campus Waste Water Use: Gallons                                       | number    | number      |
| Yes      | numeric metric | percentage_green_choice_electricity                                 | Percentage Green Choice Electricity                                   | percent   | percent     |
| Yes      | numeric metric | de_icing_airport_operations_gallons                                 | De-Icing: Airport Operations: Gallons                                 | number    | number      |
| Yes      | numeric metric | de_icing_pavement_ground_operations_gallons                         | De-icing: Pavement/Ground Operations: Gallons                         | number    | number      |
| Yes      | numeric metric | de_icing_pavement_ground_operations_lbs                             | De-Icing: Pavement/Ground Operations: Lbs                             | number    | number      |
| Yes      | numeric metric | de_icing_pond_discharges_to_waste_water_gallons                     | De-Icing: Pond Discharges to Waste Water: Gallons                     | number    | number      |
| Yes      | numeric metric | de_icer_treated_at_waste_water_plant_lbs                            | De-Icer Treated at Waste Water Plant: Lbs                             | number    | number      |
| Yes      | numeric metric | terminal_waste_to_landfill_tons                                     | Terminal Waste to Landfill: Tons                                      | number    | number      |
| Yes      | numeric metric | terminal_waste_recycled_tons                                        | Terminal Waste Recycled: Tons                                         | number    | number      |
| Yes      | numeric metric | brush_composting_tons                                               | Brush Composting: Tons                                                | number    | number      |
| Yes      | numeric metric | light_bulb_recycling_lbs                                            | Light Bulb Recycling: Lbs                                             | number    | number      |
| Yes      | numeric metric | light_bulb_recycling_units                                          | Light Bulb Recycling: Units                                           | number    | number      |
| Yes      | numeric metric | alkaline_and_rechargeable_batteries_lbs                             | Alkaline and Rechargeable Batteries: Lbs                              | number    | number      |
| Yes      | numeric metric | electronic_waste_lbs                                                | Electronic Waste: Lbs                                                 | number    | number      |
| Yes      | numeric metric | vehicle_batteries_recycled                                          | Vehicle Batteries Recycled                                            | number    | number      |
| Yes      | numeric metric | tires_recycled                                                      | Tires Recycled                                                        | number    | number      |
| Yes      | numeric metric | oil_recycled_gallons                                                | Oil Recycled: Gallons                                                 | number    | number      |
| Yes      | numeric metric | demolition_recycling_tons                                           | Demolition Recycling: Tons                                            | number    | number      |
| Yes      | numeric metric | gasoline_use_gallons                                                | Gasoline Use: Gallons                                                 | number    | number      |
| Yes      | numeric metric | ethanol_e85_use_gallons                                             | Ethanol (E85) Use: Gallons                                            | number    | number      |
| Yes      | numeric metric | diesel_use_gallons                                                  | Diesel Use: Gallons                                                   | number    | number      |
| Yes      | numeric metric | propane_use_gallons                                                 | Propane Use: Gallons                                                  | number    | number      |
| Yes      | numeric metric | cng_gallons                                                         | CNG: Gallons                                                          | number    | number      |
| Yes      | numeric metric | alternative_fuel_mowers                                             | Alternative Fuel Mowers                                               | number    | number      |
| Yes      | numeric metric | alternative_fuel_off_road_units                                     | Alternative Fuel Off-Road Units                                       | number    | number      |
| Yes      | numeric metric | alternative_fuel_on_road_units                                      | Alternative Fuel On-Road Units                                        | number    | number      |
| Yes      | numeric metric | carbon_footprint_metric_tons                                        | Carbon Footprint: Metric Tons                                         | number    | number      |
| Yes      | numeric metric | carbon_footprint_reduction                                          | Carbon Footprint Reduction                                            | percent   | percent     |
| Yes      | numeric metric | annual_aircraft_operations                                          | Annual Aircraft Operations                                            | number    | number      |
| Yes      | numeric metric | fod_debris_removed_from_apron_lbs                                   | FOD (Debris) Removed from Apron: Lbs                                  | number    | number      |
| Yes      | numeric metric | wildlife_bird_strikes                                               | Wildlife/Bird Strikes                                                 | number    | number      |
| Yes      | numeric metric | deficiencies_noted_during_daily_139_inspections_internal_operations | Deficiencies Noted During Daily 139 Inspections (Internal Operations) | number    | number      |
| Yes      | numeric metric | deficiencies_noted_during_139_inspections_external_inspectors       | Deficiencies Noted During 139 Inspections (External Inspectors)       | number    | number      |
| Yes      | numeric metric | aoa_warnings_issued                                                 | AOA Warnings Issued                                                   | number    | number      |
| No       |                | percent_security_responses_within_established_time                  | Percent Security Responses within Established Time                    | percent   | percent     |
| Yes      | numeric metric | security_violations_issued                                          | Security Violations Issued                                            | number    | number      |
| Yes      | numeric metric | average_morning_wait_time_at_security_checkpoints_minutes           | Average Morning Wait Time at Security Checkpoints: Minutes            | number    | number      |
| Yes      | numeric metric | average_afternoon_wait_time_at_security_checkpoints_minutes         | Average Afternoon Wait Time at Security Checkpoints: Minutes          | number    | number      |
| Yes      | numeric metric | number_of_arff_responses                                            | Number of ARFF Responses                                              | number    | number      |
| Yes      | numeric metric | average_repair_time_call_to_completion_minutes                      | Average Repair Time Call to Completion: Minutes                       | number    | number      |
| Yes      | numeric metric | epax_per_gate_utilized                                              | EPAX per Gate Utilized                                                | number    | number      |
| Yes      | numeric metric | enplanements_change_over_prior_period                               | Enplanements: Change over Prior Period                                | percent   | percent     |
| Yes      | numeric metric | gate_utilization_turns_per_gate                                     | Gate Utilization (Turns per Gate)                                     | number    | number      |
| Yes      | numeric metric | passenger_boarding_bridge_annual_cost                               | Passenger Boarding Bridge: Annual Cost                                | number    | number      |
| Yes      | numeric metric | airfield_lighting_units                                             | Airfield Lighting Units                                               | number    | number      |
| Yes      | numeric metric | people_moving_systems                                               | People-Moving Systems                                                 | percent   | percent     |
| Yes      | numeric metric | bhs_conveying_systems                                               | BHS Conveying Systems                                                 | percent   | percent     |
| Yes      | numeric metric | pm_costs_to_total_maintenance_costs                                 | PM Costs to Total Maintenance Costs                                   | percent   | percent     |
| Yes      | numeric metric | productive_hours_to_labor_hours                                     | Productive Hours to Labor Hours                                       | percent   | percent     |
| Yes      | numeric metric | pms_performed_on_fleet_vehicles                                     | PMs Performed on Fleet Vehicles                                       | number    | text        |
| Yes      | numeric metric | cost_per_covered_parking_space                                      | Cost per Covered Parking Space                                        | money     | money       |
| Yes      | numeric metric | cost_per_parking_space_with_busing                                  | Cost per Parking Space with Busing                                    | money     | money       |
| Yes      | numeric metric | cost_per_parking_space_without_busing_or_cover                      | Cost per Parking Space without Busing or Cover                        | money     | money       |
| Yes      | numeric metric | overall_customer_satisfaction                                       | Overall Customer Satisfaction                                         | number    | number      |
| Yes      | numeric metric | customer_rating_cleanliness_of_terminal                             | Customer Rating: Cleanliness of Terminal                              | number    | number      |
| Yes      | numeric metric | customer_rating_cleanliness_of_restrooms                            | Customer Rating: Cleanliness of Restrooms                             | number    | number      |
| Yes      | numeric metric | customer_rating_helpfulness_of_staff                                | Customer Rating: Helpfulness of Staff                                 | number    | number      |
| Yes      | numeric metric | customer_rating_courtesy_of_security_staff                          | Customer Rating: Courtesy of Security Staff                           | number    | number      |
| Yes      | numeric metric | percent_mbw_wbe_purchases_under_5000                                | Percent MBW/WBE Purchases Under $5000                                 | percent   | percent     |
| Yes      | numeric metric | total_mbw_wbe_purchases                                             | Total MBW/WBE Purchases                                               | number    | number      |
| Yes      | numeric metric | total_passenger_flights                                             | Total Passenger Flights                                               | number    | number      |
| Yes      | numeric metric | number_of_direct_flights                                            | Number of Direct Flights                                              | number    | number      |
| Yes      | numeric metric | number_of_non_stop_destinations                                     | Number of Non-Stop Destinations                                       | number    | number      |
| Yes      | numeric metric | average_seats_per_flight                                            | Average Seats per Flight                                              | number    | number      |
| Yes      | numeric metric | total_annual_seats                                                  | Total Annual Seats                                                    | number    | number      |
| Yes      | numeric metric | total_annual_passengers                                             | Total Annual Passengers                                               | number    | number      |
| Yes      | numeric metric | total_aviation_ftes                                                 | Total Aviation FTEs                                                   | number    | number      |
| Yes      | numeric metric | lost_time_injury_rate                                               | Lost time Injury Rate                                                 | number    | number      |
| Yes      | numeric metric | injuries_reportable                                                 | Injuries Reportable                                                   | number    | number      |
| Yes      | numeric metric | injuries_with_medical                                               | Injuries with Medical                                                 | number    | number      |
| Yes      | numeric metric | injuries_without_medical                                            | Injuries without Medical                                              | number    | number      |
| Yes      | numeric metric | sick_hours_utilized                                                 | Sick Hours Utilized                                                   | number    | number      |
| Yes      | numeric metric | training_hours_per_fte                                              | Training Hours per FTE                                                | number    | number      |
| Yes      | numeric metric | employee_satisfaction_rating                                        | Employee Satisfaction Rating                                          | number    | number      |
| Yes      | numeric metric | percent_male_employees                                              | Percent Male Employees                                                | percent   | percent     |
| Yes      | numeric metric | percent_female_employees                                            | Percent Female Employees                                              | percent   | percent     |
| Yes      | numeric metric | percent_white_employees                                             | Percent White Employees                                               | percent   | percent     |
| Yes      | numeric metric | percent_hispanic_employees                                          | Percent Hispanic Employees                                            | percent   | percent     |
| Yes      | numeric metric | percent_black_employees                                             | Percent Black Employees                                               | percent   | percent     |
| Yes      | numeric metric | percent_asian_employees                                             | Percent Asian Employees                                               | percent   | percent     |
| Yes      | numeric metric | percent_employees_reporting_other                                   | Percent Employees Reporting Other                                     | percent   | percent     |
| Yes      | numeric metric | employee_turnover_rate_percent                                      | Employee Turnover Rate: Percent                                       | percent   | percent     |
| Yes      | numeric metric | passenger_airline_cost_per_enplanement                              | Passenger Airline Cost per Enplanement                                | money     | money       |
| Yes      | numeric metric | expenses_per_enplaned_passenger                                     | Expenses per Enplaned Passenger                                       | money     | money       |
| Yes      | numeric metric | revenue_per_enplanement                                             | Revenue per Enplanement                                               | money     | money       |
| Yes      | numeric metric | total_non_airline_revenue                                           | Total Non-Airline Revenue                                             | money     | money       |
| Yes      | numeric metric | non_airline_revenue_per_passenger                                   | Non-Airline Revenue per Passenger                                     | money     | money       |
| Yes      | numeric metric | non_airline_revenue_airline_revenue                                 | Non-Airline Revenue :: Airline Revenue                                | percent   | percent     |
| Yes      | numeric metric | concession_revenue_to_airport                                       | Concession Revenue to Airport                                         | money     | money       |
| Yes      | numeric metric | concession_gross_sales_per_square_foot                              | Concession Gross Sales per Square Foot                                | money     | money       |
| Yes      | numeric metric | security_cost                                                       | Security Cost                                                         | money     | money       |
| Yes      | numeric metric | security_cost_total_cost                                            | Security Cost :: Total Cost                                           | percent   | percent     |
| Yes      | numeric metric | repair_and_maintenance_cost                                         | Repair and Maintenance Cost                                           | money     | money       |
| Yes      | numeric metric | arff_cost                                                           | ARFF Cost                                                             | money     | money       |
| Yes      | numeric metric | arff_cost_total_cost                                                | ARFF Cost :: Total Cost                                               | percent   | percent     |
| Yes      | numeric metric | arff_cost_per_operation                                             | ARFF Cost per Operation                                               | money     | money       |
| Yes      | numeric metric | arff_salary_and_benefits_cost                                       | ARFF Salary and Benefits Cost                                         | money     | money       |
| Yes      | numeric metric | parking_revenue_per_enplaned_passenger                              | Parking Revenue per Enplaned Passenger                                | money     | money       |
| Yes      | numeric metric | parking_and_ground_transportation_total_revenue                     | Parking and Ground Transportation: Total Revenue                      | money     | money       |
| Yes      | numeric metric | parking_and_ground_transportation_off_airport_revenue               | Parking and Ground Transportation: Off-Airport Revenue                | money     | money       |
| Yes      | numeric metric | parking_and_ground_transportation_on_airport_revenue                | Parking and Ground Transportation: On-Airport Revenue                 | money     | money       |
| Yes      | numeric metric | personnel_expenses                                                  | Personnel Expenses                                                    | money     | money       |
| Yes      | numeric metric | total_operating_revenue                                             | Total Operating Revenue                                               | money     | money       |
| Yes      | numeric metric | total_landed_weight_lbs                                             | Total Landed Weight: Lbs                                              | number    | number      |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = percent_security_responses_within_established_time
```

## Data Commands

```ls
series e:x4vz-3xdy d:2012-01-01T00:00:00.000Z m:terminal_water_use_gallons=25303100 m:customer_rating_cleanliness_of_restrooms=4.26 m:security_violations_issued=41 m:average_seats_per_flight=121 m:alternative_fuel_off_road_units=17 m:injuries_reportable=58 m:deficiencies_noted_during_139_inspections_external_inspectors=3 m:non_airline_revenue_airline_revenue=53 m:terminal_electricity_use_kwh=22715146 m:pms_performed_on_fleet_vehicles=300 m:percent_employees_reporting_other=1 m:terminal_waste_recycled_tons=256 m:security_cost_total_cost=12.03 m:customer_rating_helpfulness_of_staff=4.32 m:expenses_per_enplaned_passenger=14.34 m:customer_rating_courtesy_of_security_staff=4.05 m:total_passenger_flights=97324 m:light_bulb_recycling_lbs=458 m:personnel_expenses=28689620 m:parking_and_ground_transportation_total_revenue=31372981 m:security_cost=8040133 m:campus_water_use_gallons=50877800 m:deficiencies_noted_during_daily_139_inspections_internal_operations=954 m:repair_and_maintenance_cost=2116316 m:bhs_conveying_systems=95 m:total_operating_revenue=95205000 m:number_of_direct_flights=84 m:wildlife_bird_strikes=111 m:non_airline_revenue_per_passenger=5.41 m:gate_utilization_turns_per_gate=5.5 m:percent_white_employees=41 m:diesel_use_gallons=1393 m:carbon_footprint_reduction=76 m:passenger_boarding_bridge_annual_cost=377714 m:productive_hours_to_labor_hours=41 m:terminal_natural_gas_use_ccf=99776 m:overall_customer_satisfaction=4.33 m:de_icer_treated_at_waste_water_plant_lbs=297 m:percent_female_employees=35 m:number_of_non_stop_destinations=40 m:injuries_with_medical=25 m:total_non_airline_revenue=50432342 m:terminal_wastewater_use_gallons=24962100 m:percent_hispanic_employees=29 m:percent_male_employees=65 m:arff_cost=5183126 m:de_icing_pond_discharges_to_waste_water_gallons=386512 m:sick_hours_utilized=25.84 m:terminal_waste_to_landfill_tons=2004 m:alternative_fuel_on_road_units=50 m:propane_use_gallons=103233 m:parking_and_ground_transportation_off_airport_revenue=1298692 m:gasoline_use_gallons=35510 m:cost_per_parking_space_without_busing_or_cover=737.87 m:light_bulb_recycling_units=282 m:de_icing_pavement_ground_operations_lbs=0 m:employee_turnover_rate_percent=7.6 m:average_repair_time_call_to_completion_minutes=17 m:total_annual_seats=11764648 m:pm_costs_to_total_maintenance_costs=21 m:arff_salary_and_benefits_cost=4670572 m:lost_time_injury_rate=0.32 m:arff_cost_total_cost=7.75 m:total_landed_weight_lbs=5815537 m:percentage_green_choice_electricity=100 m:ethanol_e85_use_gallons=1973 m:total_aviation_ftes=347 m:campus_electrity_use_kwh=30653904 m:oil_recycled_gallons=546 m:fod_debris_removed_from_apron_lbs=789 m:injuries_without_medical=33 m:campus_waste_water_use_gallons=37164700 m:epax_per_gate_utilized=186510 m:average_morning_wait_time_at_security_checkpoints_minutes=18 m:tires_recycled=301 m:arff_cost_per_operation=32.54 m:total_mbw_wbe_purchases=129623 m:de_icing_airport_operations_gallons=4305 m:percent_mbw_wbe_purchases_under_5000=5.48 m:average_afternoon_wait_time_at_security_checkpoints_minutes=11 m:percent_asian_employees=4 m:concession_gross_sales_per_square_foot=1047 m:people_moving_systems=94 m:vehicle_batteries_recycled=140 m:cost_per_parking_space_with_busing=515.46 m:alternative_fuel_mowers=13 m:carbon_footprint_metric_tons=2697 m:campus_reclaimed_water_use_gallons=11818400 m:percent_black_employees=25 m:cost_per_covered_parking_space=730.68 m:concession_revenue_to_airport=7794464 m:parking_revenue_per_enplaned_passenger=6.65 m:brush_composting_tons=144 m:customer_rating_cleanliness_of_terminal=4.44 m:annual_aircraft_operations=159269 m:campus_natural_gas_use_ccf=144421 m:number_of_arff_responses=683 m:electronic_waste_lbs=4241 m:cng_gallons=96933 m:demolition_recycling_tons=1759 m:employee_satisfaction_rating=32 m:training_hours_per_fte=54 m:enplanements_change_over_prior_period=3 m:passenger_airline_cost_per_enplanement=8.32 m:aoa_warnings_issued=2 m:parking_and_ground_transportation_on_airport_revenue=30074289 m:alkaline_and_rechargeable_batteries_lbs=947 m:revenue_per_enplanement=20.44 m:total_annual_passengers=9317561 m:airfield_lighting_units=612

series e:x4vz-3xdy d:2013-01-01T00:00:00.000Z m:terminal_water_use_gallons=26959168 m:customer_rating_cleanliness_of_restrooms=4.21 m:security_violations_issued=18 m:average_seats_per_flight=121 m:alternative_fuel_off_road_units=38 m:injuries_reportable=53 m:deficiencies_noted_during_139_inspections_external_inspectors=0 m:non_airline_revenue_airline_revenue=57 m:terminal_electricity_use_kwh=22278056 m:percent_employees_reporting_other=1 m:terminal_waste_recycled_tons=309.55 m:security_cost_total_cost=14.18 m:customer_rating_helpfulness_of_staff=4.3 m:expenses_per_enplaned_passenger=13.6 m:customer_rating_courtesy_of_security_staff=4.06 m:total_passenger_flights=101593 m:light_bulb_recycling_lbs=1032 m:personnel_expenses=27032670 m:parking_and_ground_transportation_total_revenue=32157713 m:security_cost=9510842 m:campus_water_use_gallons=44507900 m:deficiencies_noted_during_daily_139_inspections_internal_operations=614 m:repair_and_maintenance_cost=2997046 m:bhs_conveying_systems=95 m:total_operating_revenue=103514000 m:number_of_direct_flights=121 m:wildlife_bird_strikes=108 m:non_airline_revenue_per_passenger=5.99 m:gate_utilization_turns_per_gate=5.7 m:percent_white_employees=42 m:diesel_use_gallons=17304 m:carbon_footprint_reduction=0 m:passenger_boarding_bridge_annual_cost=391390 m:productive_hours_to_labor_hours=98 m:terminal_natural_gas_use_ccf=137272 m:overall_customer_satisfaction=4.28 m:de_icer_treated_at_waste_water_plant_lbs=4902 m:percent_female_employees=34 m:number_of_non_stop_destinations=41 m:injuries_with_medical=19 m:total_non_airline_revenue=59078609 m:terminal_wastewater_use_gallons=26722000 m:percent_hispanic_employees=29 m:percent_male_employees=66 m:arff_cost=5191211 m:de_icing_pond_discharges_to_waste_water_gallons=2284320 m:sick_hours_utilized=25.24 m:terminal_waste_to_landfill_tons=2053.65 m:alternative_fuel_on_road_units=36 m:propane_use_gallons=49332 m:parking_and_ground_transportation_off_airport_revenue=1403806 m:gasoline_use_gallons=35405 m:cost_per_parking_space_without_busing_or_cover=1429.09 m:light_bulb_recycling_units=1500 m:de_icing_pavement_ground_operations_lbs=0 m:employee_turnover_rate_percent=8.95 m:de_icing_pavement_ground_operations_gallons=300 m:average_repair_time_call_to_completion_minutes=38 m:total_annual_seats=12319953 m:pm_costs_to_total_maintenance_costs=50 m:arff_salary_and_benefits_cost=4799541 m:lost_time_injury_rate=0.95 m:arff_cost_total_cost=7.74 m:total_landed_weight_lbs=6122513 m:percentage_green_choice_electricity=100 m:ethanol_e85_use_gallons=2150 m:total_aviation_ftes=358 m:campus_electrity_use_kwh=29264294 m:oil_recycled_gallons=451 m:fod_debris_removed_from_apron_lbs=2725 m:injuries_without_medical=34 m:campus_waste_water_use_gallons=31649232 m:epax_per_gate_utilized=197159 m:average_morning_wait_time_at_security_checkpoints_minutes=18 m:tires_recycled=325 m:arff_cost_per_operation=31.26 m:total_mbw_wbe_purchases=159722 m:de_icing_airport_operations_gallons=9243 m:percent_mbw_wbe_purchases_under_5000=6.66 m:average_afternoon_wait_time_at_security_checkpoints_minutes=14 m:percent_asian_employees=3 m:concession_gross_sales_per_square_foot=1301 m:people_moving_systems=94 m:vehicle_batteries_recycled=28 m:cost_per_parking_space_with_busing=529.9 m:alternative_fuel_mowers=17 m:carbon_footprint_metric_tons=2695 m:campus_reclaimed_water_use_gallons=11531000 m:percent_black_employees=25 m:cost_per_covered_parking_space=828.51 m:concession_revenue_to_airport=8559586 m:parking_revenue_per_enplaned_passenger=6.52 m:brush_composting_tons=600.47 m:customer_rating_cleanliness_of_terminal=4.37 m:annual_aircraft_operations=174245 m:campus_natural_gas_use_ccf=187202 m:number_of_arff_responses=782 m:electronic_waste_lbs=16798 m:cng_gallons=141529 m:demolition_recycling_tons=18845 m:employee_satisfaction_rating=32 m:training_hours_per_fte=51 m:enplanements_change_over_prior_period=6 m:passenger_airline_cost_per_enplanement=8.86 m:aoa_warnings_issued=0 m:parking_and_ground_transportation_on_airport_revenue=30753907 m:alkaline_and_rechargeable_batteries_lbs=1188 m:revenue_per_enplanement=21.06 m:total_annual_passengers=10017958 m:airfield_lighting_units=547

series e:x4vz-3xdy d:2014-01-01T00:00:00.000Z m:terminal_water_use_gallons=28466050 m:customer_rating_cleanliness_of_restrooms=4.17 m:security_violations_issued=44 m:average_seats_per_flight=125 m:alternative_fuel_off_road_units=39 m:injuries_reportable=52 m:deficiencies_noted_during_139_inspections_external_inspectors=2 m:non_airline_revenue_airline_revenue=60 m:terminal_electricity_use_kwh=22836040 m:percent_employees_reporting_other=1 m:terminal_waste_recycled_tons=291.24 m:security_cost_total_cost=12.69 m:customer_rating_helpfulness_of_staff=4.35 m:expenses_per_enplaned_passenger=14.41 m:customer_rating_courtesy_of_security_staff=4.16 m:total_passenger_flights=104103 m:light_bulb_recycling_lbs=893 m:personnel_expenses=28905381 m:parking_and_ground_transportation_total_revenue=34181754 m:security_cost=9650825 m:campus_water_use_gallons=47865700 m:deficiencies_noted_during_daily_139_inspections_internal_operations=654 m:repair_and_maintenance_cost=2124287 m:bhs_conveying_systems=96 m:total_operating_revenue=108960498 m:number_of_direct_flights=78 m:wildlife_bird_strikes=126 m:non_airline_revenue_per_passenger=6.18 m:gate_utilization_turns_per_gate=5.92 m:percent_white_employees=40 m:diesel_use_gallons=23469 m:carbon_footprint_reduction=-6 m:passenger_boarding_bridge_annual_cost=335699 m:productive_hours_to_labor_hours=92 m:terminal_natural_gas_use_ccf=141207 m:overall_customer_satisfaction=4.34 m:de_icer_treated_at_waste_water_plant_lbs=27793 m:percent_female_employees=35 m:number_of_non_stop_destinations=41 m:injuries_with_medical=18 m:total_non_airline_revenue=66703521 m:terminal_wastewater_use_gallons=28466050 m:percent_hispanic_employees=28 m:percent_male_employees=65 m:arff_cost=4846183 m:de_icing_pond_discharges_to_waste_water_gallons=2532200 m:sick_hours_utilized=26.27 m:terminal_waste_to_landfill_tons=2148.09 m:alternative_fuel_on_road_units=35 m:propane_use_gallons=55961 m:parking_and_ground_transportation_off_airport_revenue=1626932 m:gasoline_use_gallons=34900 m:cost_per_parking_space_without_busing_or_cover=343.86 m:light_bulb_recycling_units=1673 m:de_icing_pavement_ground_operations_lbs=0 m:employee_turnover_rate_percent=9.44 m:de_icing_pavement_ground_operations_gallons=7179 m:average_repair_time_call_to_completion_minutes=16 m:total_annual_seats=13072485 m:pm_costs_to_total_maintenance_costs=57 m:arff_salary_and_benefits_cost=4711908 m:lost_time_injury_rate=0.31 m:arff_cost_total_cost=6.37 m:total_landed_weight_lbs=6392065 m:percentage_green_choice_electricity=100 m:ethanol_e85_use_gallons=3318 m:total_aviation_ftes=362 m:campus_electrity_use_kwh=29660980 m:oil_recycled_gallons=585 m:fod_debris_removed_from_apron_lbs=4080 m:injuries_without_medical=30 m:campus_waste_water_use_gallons=34484800 m:epax_per_gate_utilized=211019 m:average_morning_wait_time_at_security_checkpoints_minutes=12.36 m:tires_recycled=557 m:arff_cost_per_operation=28.9 m:total_mbw_wbe_purchases=157811 m:de_icing_airport_operations_gallons=36830 m:percent_mbw_wbe_purchases_under_5000=7.48 m:average_afternoon_wait_time_at_security_checkpoints_minutes=9.84 m:percent_asian_employees=4 m:concession_gross_sales_per_square_foot=1460 m:people_moving_systems=93 m:vehicle_batteries_recycled=150 m:cost_per_parking_space_with_busing=625.03 m:alternative_fuel_mowers=12 m:carbon_footprint_metric_tons=2861 m:campus_reclaimed_water_use_gallons=17150000 m:percent_black_employees=24 m:cost_per_covered_parking_space=679.6 m:concession_revenue_to_airport=9781041 m:parking_revenue_per_enplaned_passenger=6.39 m:brush_composting_tons=334.79 m:customer_rating_cleanliness_of_terminal=4.43 m:annual_aircraft_operations=179224 m:campus_natural_gas_use_ccf=197246 m:number_of_arff_responses=866 m:electronic_waste_lbs=13338 m:cng_gallons=154774 m:demolition_recycling_tons=3758 m:employee_satisfaction_rating=37 m:training_hours_per_fte=40 m:enplanements_change_over_prior_period=7 m:passenger_airline_cost_per_enplanement=8.01 m:aoa_warnings_issued=0 m:parking_and_ground_transportation_on_airport_revenue=32554823 m:alkaline_and_rechargeable_batteries_lbs=1398 m:revenue_per_enplanement=20.65 m:total_annual_passengers=10718854 m:airfield_lighting_units=285
```

## Meta Commands

```ls
metric m:terminal_electricity_use_kwh p:integer l:"Terminal Electricity Use: KWH" t:dataTypeName=number

metric m:terminal_natural_gas_use_ccf p:integer l:"Terminal Natural Gas Use: CCF" t:dataTypeName=number

metric m:terminal_water_use_gallons p:integer l:"Terminal Water Use: Gallons" t:dataTypeName=number

metric m:terminal_wastewater_use_gallons p:integer l:"Terminal Wastewater Use: Gallons" t:dataTypeName=number

metric m:campus_electrity_use_kwh p:integer l:"Campus Electrity Use: KWH" t:dataTypeName=number

metric m:campus_natural_gas_use_ccf p:integer l:"Campus Natural Gas Use: CCF" t:dataTypeName=number

metric m:campus_water_use_gallons p:integer l:"Campus Water Use: Gallons" t:dataTypeName=number

metric m:campus_reclaimed_water_use_gallons p:integer l:"Campus Reclaimed Water Use: Gallons" t:dataTypeName=number

metric m:campus_waste_water_use_gallons p:integer l:"Campus Waste Water Use: Gallons" t:dataTypeName=number

metric m:percentage_green_choice_electricity p:integer l:"Percentage Green Choice Electricity" t:dataTypeName=percent

metric m:de_icing_airport_operations_gallons p:integer l:"De-Icing: Airport Operations: Gallons" t:dataTypeName=number

metric m:de_icing_pavement_ground_operations_gallons p:integer l:"De-icing: Pavement/Ground Operations: Gallons" t:dataTypeName=number

metric m:de_icing_pavement_ground_operations_lbs p:integer l:"De-Icing: Pavement/Ground Operations: Lbs" t:dataTypeName=number

metric m:de_icing_pond_discharges_to_waste_water_gallons p:integer l:"De-Icing: Pond Discharges to Waste Water: Gallons" t:dataTypeName=number

metric m:de_icer_treated_at_waste_water_plant_lbs p:integer l:"De-Icer Treated at Waste Water Plant: Lbs" t:dataTypeName=number

metric m:terminal_waste_to_landfill_tons p:float l:"Terminal Waste to Landfill: Tons" t:dataTypeName=number

metric m:terminal_waste_recycled_tons p:float l:"Terminal Waste Recycled: Tons" t:dataTypeName=number

metric m:brush_composting_tons p:float l:"Brush Composting: Tons" t:dataTypeName=number

metric m:light_bulb_recycling_lbs p:integer l:"Light Bulb Recycling: Lbs" t:dataTypeName=number

metric m:light_bulb_recycling_units p:integer l:"Light Bulb Recycling: Units" t:dataTypeName=number

metric m:alkaline_and_rechargeable_batteries_lbs p:integer l:"Alkaline and Rechargeable Batteries: Lbs" t:dataTypeName=number

metric m:electronic_waste_lbs p:integer l:"Electronic Waste: Lbs" t:dataTypeName=number

metric m:vehicle_batteries_recycled p:integer l:"Vehicle Batteries Recycled" t:dataTypeName=number

metric m:tires_recycled p:integer l:"Tires Recycled" t:dataTypeName=number

metric m:oil_recycled_gallons p:integer l:"Oil Recycled: Gallons" t:dataTypeName=number

metric m:demolition_recycling_tons p:integer l:"Demolition Recycling: Tons" t:dataTypeName=number

metric m:gasoline_use_gallons p:integer l:"Gasoline Use: Gallons" t:dataTypeName=number

metric m:ethanol_e85_use_gallons p:integer l:"Ethanol (E85) Use: Gallons" t:dataTypeName=number

metric m:diesel_use_gallons p:integer l:"Diesel Use: Gallons" t:dataTypeName=number

metric m:propane_use_gallons p:integer l:"Propane Use: Gallons" t:dataTypeName=number

metric m:cng_gallons p:integer l:"CNG: Gallons" t:dataTypeName=number

metric m:alternative_fuel_mowers p:integer l:"Alternative Fuel Mowers" t:dataTypeName=number

metric m:alternative_fuel_off_road_units p:integer l:"Alternative Fuel Off-Road Units" t:dataTypeName=number

metric m:alternative_fuel_on_road_units p:integer l:"Alternative Fuel On-Road Units" t:dataTypeName=number

metric m:carbon_footprint_metric_tons p:integer l:"Carbon Footprint: Metric Tons" t:dataTypeName=number

metric m:carbon_footprint_reduction p:integer l:"Carbon Footprint Reduction" t:dataTypeName=percent

metric m:annual_aircraft_operations p:integer l:"Annual Aircraft Operations" t:dataTypeName=number

metric m:fod_debris_removed_from_apron_lbs p:integer l:"FOD (Debris) Removed from Apron: Lbs" t:dataTypeName=number

metric m:wildlife_bird_strikes p:integer l:"Wildlife/Bird Strikes" t:dataTypeName=number

metric m:deficiencies_noted_during_daily_139_inspections_internal_operations p:integer l:"Deficiencies Noted During Daily 139 Inspections (Internal Operations)" t:dataTypeName=number

metric m:deficiencies_noted_during_139_inspections_external_inspectors p:integer l:"Deficiencies Noted During 139 Inspections (External Inspectors)" t:dataTypeName=number

metric m:aoa_warnings_issued p:integer l:"AOA Warnings Issued" t:dataTypeName=number

metric m:security_violations_issued p:integer l:"Security Violations Issued" t:dataTypeName=number

metric m:average_morning_wait_time_at_security_checkpoints_minutes p:float l:"Average Morning Wait Time at Security Checkpoints: Minutes" t:dataTypeName=number

metric m:average_afternoon_wait_time_at_security_checkpoints_minutes p:float l:"Average Afternoon Wait Time at Security Checkpoints: Minutes" t:dataTypeName=number

metric m:number_of_arff_responses p:integer l:"Number of ARFF Responses" t:dataTypeName=number

metric m:average_repair_time_call_to_completion_minutes p:integer l:"Average Repair Time Call to Completion: Minutes" t:dataTypeName=number

metric m:epax_per_gate_utilized p:integer l:"EPAX per Gate Utilized" t:dataTypeName=number

metric m:enplanements_change_over_prior_period p:integer l:"Enplanements: Change over Prior Period" t:dataTypeName=percent

metric m:gate_utilization_turns_per_gate p:float l:"Gate Utilization (Turns per Gate)" t:dataTypeName=number

metric m:passenger_boarding_bridge_annual_cost p:integer l:"Passenger Boarding Bridge: Annual Cost" t:dataTypeName=number

metric m:airfield_lighting_units p:integer l:"Airfield Lighting Units" t:dataTypeName=number

metric m:people_moving_systems p:integer l:"People-Moving Systems" t:dataTypeName=percent

metric m:bhs_conveying_systems p:integer l:"BHS Conveying Systems" t:dataTypeName=percent

metric m:pm_costs_to_total_maintenance_costs p:integer l:"PM Costs to Total Maintenance Costs" t:dataTypeName=percent

metric m:productive_hours_to_labor_hours p:integer l:"Productive Hours to Labor Hours" t:dataTypeName=percent

metric m:pms_performed_on_fleet_vehicles p:integer l:"PMs Performed on Fleet Vehicles" t:dataTypeName=number

metric m:cost_per_covered_parking_space p:double l:"Cost per Covered Parking Space" t:dataTypeName=money

metric m:cost_per_parking_space_with_busing p:double l:"Cost per Parking Space with Busing" t:dataTypeName=money

metric m:cost_per_parking_space_without_busing_or_cover p:double l:"Cost per Parking Space without Busing or Cover" t:dataTypeName=money

metric m:overall_customer_satisfaction p:float l:"Overall Customer Satisfaction" t:dataTypeName=number

metric m:customer_rating_cleanliness_of_terminal p:float l:"Customer Rating: Cleanliness of Terminal" t:dataTypeName=number

metric m:customer_rating_cleanliness_of_restrooms p:float l:"Customer Rating: Cleanliness of Restrooms" t:dataTypeName=number

metric m:customer_rating_helpfulness_of_staff p:float l:"Customer Rating: Helpfulness of Staff" t:dataTypeName=number

metric m:customer_rating_courtesy_of_security_staff p:float l:"Customer Rating: Courtesy of Security Staff" t:dataTypeName=number

metric m:percent_mbw_wbe_purchases_under_5000 p:float l:"Percent MBW/WBE Purchases Under $5000" t:dataTypeName=percent

metric m:total_mbw_wbe_purchases p:integer l:"Total MBW/WBE Purchases" t:dataTypeName=number

metric m:total_passenger_flights p:integer l:"Total Passenger Flights" t:dataTypeName=number

metric m:number_of_direct_flights p:integer l:"Number of Direct Flights" t:dataTypeName=number

metric m:number_of_non_stop_destinations p:integer l:"Number of Non-Stop Destinations" t:dataTypeName=number

metric m:average_seats_per_flight p:integer l:"Average Seats per Flight" t:dataTypeName=number

metric m:total_annual_seats p:integer l:"Total Annual Seats" t:dataTypeName=number

metric m:total_annual_passengers p:integer l:"Total Annual Passengers" t:dataTypeName=number

metric m:total_aviation_ftes p:integer l:"Total Aviation FTEs" t:dataTypeName=number

metric m:lost_time_injury_rate p:float l:"Lost time Injury Rate" t:dataTypeName=number

metric m:injuries_reportable p:integer l:"Injuries Reportable" t:dataTypeName=number

metric m:injuries_with_medical p:integer l:"Injuries with Medical" t:dataTypeName=number

metric m:injuries_without_medical p:integer l:"Injuries without Medical" t:dataTypeName=number

metric m:sick_hours_utilized p:float l:"Sick Hours Utilized" t:dataTypeName=number

metric m:training_hours_per_fte p:integer l:"Training Hours per FTE" t:dataTypeName=number

metric m:employee_satisfaction_rating p:integer l:"Employee Satisfaction Rating" t:dataTypeName=number

metric m:percent_male_employees p:integer l:"Percent Male Employees" t:dataTypeName=percent

metric m:percent_female_employees p:integer l:"Percent Female Employees" t:dataTypeName=percent

metric m:percent_white_employees p:integer l:"Percent White Employees" t:dataTypeName=percent

metric m:percent_hispanic_employees p:integer l:"Percent Hispanic Employees" t:dataTypeName=percent

metric m:percent_black_employees p:integer l:"Percent Black Employees" t:dataTypeName=percent

metric m:percent_asian_employees p:integer l:"Percent Asian Employees" t:dataTypeName=percent

metric m:percent_employees_reporting_other p:integer l:"Percent Employees Reporting Other" t:dataTypeName=percent

metric m:employee_turnover_rate_percent p:float l:"Employee Turnover Rate: Percent" t:dataTypeName=percent

metric m:passenger_airline_cost_per_enplanement p:double l:"Passenger Airline Cost per Enplanement" t:dataTypeName=money

metric m:expenses_per_enplaned_passenger p:double l:"Expenses per Enplaned Passenger" t:dataTypeName=money

metric m:revenue_per_enplanement p:double l:"Revenue per Enplanement" t:dataTypeName=money

metric m:total_non_airline_revenue p:integer l:"Total Non-Airline Revenue" t:dataTypeName=money

metric m:non_airline_revenue_per_passenger p:double l:"Non-Airline Revenue per Passenger" t:dataTypeName=money

metric m:non_airline_revenue_airline_revenue p:integer l:"Non-Airline Revenue :: Airline Revenue" t:dataTypeName=percent

metric m:concession_revenue_to_airport p:integer l:"Concession Revenue to Airport" t:dataTypeName=money

metric m:concession_gross_sales_per_square_foot p:integer l:"Concession Gross Sales per Square Foot" t:dataTypeName=money

metric m:security_cost p:integer l:"Security Cost" t:dataTypeName=money

metric m:security_cost_total_cost p:float l:"Security Cost :: Total Cost" t:dataTypeName=percent

metric m:repair_and_maintenance_cost p:integer l:"Repair and Maintenance Cost" t:dataTypeName=money

metric m:arff_cost p:integer l:"ARFF Cost" t:dataTypeName=money

metric m:arff_cost_total_cost p:float l:"ARFF Cost :: Total Cost" t:dataTypeName=percent

metric m:arff_cost_per_operation p:double l:"ARFF Cost per Operation" t:dataTypeName=money

metric m:arff_salary_and_benefits_cost p:integer l:"ARFF Salary and Benefits Cost" t:dataTypeName=money

metric m:parking_revenue_per_enplaned_passenger p:double l:"Parking Revenue per Enplaned Passenger" t:dataTypeName=money

metric m:parking_and_ground_transportation_total_revenue p:integer l:"Parking and Ground Transportation: Total Revenue" t:dataTypeName=money

metric m:parking_and_ground_transportation_off_airport_revenue p:integer l:"Parking and Ground Transportation: Off-Airport Revenue" t:dataTypeName=money

metric m:parking_and_ground_transportation_on_airport_revenue p:integer l:"Parking and Ground Transportation: On-Airport Revenue" t:dataTypeName=money

metric m:personnel_expenses p:integer l:"Personnel Expenses" t:dataTypeName=money

metric m:total_operating_revenue p:integer l:"Total Operating Revenue" t:dataTypeName=money

metric m:total_landed_weight_lbs p:integer l:"Total Landed Weight: Lbs" t:dataTypeName=number

entity e:x4vz-3xdy l:"Airport Annual Performance Measures" t:attribution="Austin-Bergstrom International Airport" t:url=https://data.austintexas.gov/api/views/x4vz-3xdy

property e:x4vz-3xdy t:meta.view v:id=x4vz-3xdy v:averageRating=0 v:name="Airport Annual Performance Measures" v:attribution="Austin-Bergstrom International Airport"

property e:x4vz-3xdy t:meta.view.license v:name="Public Domain"

property e:x4vz-3xdy t:meta.view.owner v:id=ra8t-tbn2 v:screenName=Holly v:displayName=Holly

property e:x4vz-3xdy t:meta.view.tableauthor v:id=ra8t-tbn2 v:screenName=Holly v:roleName=editor v:displayName=Holly
```

## Top Records

```ls
| reporting_year | terminal_electricity_use_kwh | terminal_natural_gas_use_ccf | terminal_water_use_gallons | terminal_wastewater_use_gallons | campus_electrity_use_kwh | campus_natural_gas_use_ccf | campus_water_use_gallons | campus_reclaimed_water_use_gallons | campus_waste_water_use_gallons | percentage_green_choice_electricity | de_icing_airport_operations_gallons | de_icing_pavement_ground_operations_gallons | de_icing_pavement_ground_operations_lbs | de_icing_pond_discharges_to_waste_water_gallons | de_icer_treated_at_waste_water_plant_lbs | terminal_waste_to_landfill_tons | terminal_waste_recycled_tons | brush_composting_tons | light_bulb_recycling_lbs | light_bulb_recycling_units | alkaline_and_rechargeable_batteries_lbs | electronic_waste_lbs | vehicle_batteries_recycled | tires_recycled | oil_recycled_gallons | demolition_recycling_tons | gasoline_use_gallons | ethanol_e85_use_gallons | diesel_use_gallons | propane_use_gallons | cng_gallons | alternative_fuel_mowers | alternative_fuel_off_road_units | alternative_fuel_on_road_units | carbon_footprint_metric_tons | carbon_footprint_reduction | annual_aircraft_operations | fod_debris_removed_from_apron_lbs | wildlife_bird_strikes | deficiencies_noted_during_daily_139_inspections_internal_operations | deficiencies_noted_during_139_inspections_external_inspectors | aoa_warnings_issued | percent_security_responses_within_established_time | security_violations_issued | average_morning_wait_time_at_security_checkpoints_minutes | average_afternoon_wait_time_at_security_checkpoints_minutes | number_of_arff_responses | average_repair_time_call_to_completion_minutes | epax_per_gate_utilized | enplanements_change_over_prior_period | gate_utilization_turns_per_gate | passenger_boarding_bridge_annual_cost | airfield_lighting_units | people_moving_systems | bhs_conveying_systems | pm_costs_to_total_maintenance_costs | productive_hours_to_labor_hours | pms_performed_on_fleet_vehicles | cost_per_covered_parking_space | cost_per_parking_space_with_busing | cost_per_parking_space_without_busing_or_cover | overall_customer_satisfaction | customer_rating_cleanliness_of_terminal | customer_rating_cleanliness_of_restrooms | customer_rating_helpfulness_of_staff | customer_rating_courtesy_of_security_staff | percent_mbw_wbe_purchases_under_5000 | total_mbw_wbe_purchases | total_passenger_flights | number_of_direct_flights | number_of_non_stop_destinations | average_seats_per_flight | total_annual_seats | total_annual_passengers | total_aviation_ftes | lost_time_injury_rate | injuries_reportable | injuries_with_medical | injuries_without_medical | sick_hours_utilized | training_hours_per_fte | employee_satisfaction_rating | percent_male_employees | percent_female_employees | percent_white_employees | percent_hispanic_employees | percent_black_employees | percent_asian_employees | percent_employees_reporting_other | employee_turnover_rate_percent | passenger_airline_cost_per_enplanement | expenses_per_enplaned_passenger | revenue_per_enplanement | total_non_airline_revenue | non_airline_revenue_per_passenger | non_airline_revenue_airline_revenue | concession_revenue_to_airport | concession_gross_sales_per_square_foot | security_cost | security_cost_total_cost | repair_and_maintenance_cost | arff_cost | arff_cost_total_cost | arff_cost_per_operation | arff_salary_and_benefits_cost | parking_revenue_per_enplaned_passenger | parking_and_ground_transportation_total_revenue | parking_and_ground_transportation_off_airport_revenue | parking_and_ground_transportation_on_airport_revenue | personnel_expenses | total_operating_revenue | total_landed_weight_lbs | 
| ============== | ============================ | ============================ | ========================== | =============================== | ======================== | ========================== | ======================== | ================================== | ============================== | =================================== | =================================== | =========================================== | ======================================= | =============================================== | ======================================== | =============================== | ============================ | ===================== | ======================== | ========================== | ======================================= | ==================== | ========================== | ============== | ==================== | ========================= | ==================== | ======================= | ================== | =================== | =========== | ======================= | =============================== | ============================== | ============================ | ========================== | ========================== | ================================= | ===================== | =================================================================== | ============================================================= | =================== | ================================================== | ========================== | ========================================================= | =========================================================== | ======================== | ============================================== | ====================== | ===================================== | =============================== | ===================================== | ======================= | ===================== | ===================== | =================================== | =============================== | =============================== | ============================== | ================================== | ============================================== | ============================= | ======================================= | ======================================== | ==================================== | ========================================== | ==================================== | ======================= | ======================= | ======================== | =============================== | ======================== | ================== | ======================= | =================== | ===================== | =================== | ===================== | ======================== | =================== | ====================== | ============================ | ====================== | ======================== | ======================= | ========================== | ======================= | ======================= | ================================= | ============================== | ====================================== | =============================== | ======================= | ========================= | ================================= | =================================== | ============================= | ====================================== | ============= | ======================== | =========================== | ========= | ==================== | ======================= | ============================= | ====================================== | =============================================== | ===================================================== | ==================================================== | ================== | ======================= | ======================= | 
| 2012           | 22715146                     | 99776                        | 25303100                   | 24962100                        | 30653904                 | 144421                     | 50877800                 | 11818400                           | 37164700                       | 100                                 | 4305                                |                                             | 0                                       | 386512                                          | 297                                      | 2004.00                         | 256.00                       | 144.00                | 458                      | 282                        | 947                                     | 4241                 | 140                        | 301            | 546                  | 1759                      | 35510                | 1973                    | 1393               | 103233              | 96933       | 13                      | 17                              | 50                             | 2697                         | 76                         | 159269                     | 789                               | 111                   | 954                                                                 | 3                                                             | 2                   | 100                                                | 41                         | 18.00                                                     | 11.00                                                       | 683                      | 17                                             | 186510                 | 3                                     | 5.50                            | 377714                                | 612                     | 94                    | 95                    | 21                                  | 41                              | 300                             | 730.68                         | 515.46                             | 737.87                                         | 4.33                          | 4.44                                    | 4.26                                     | 4.32                                 | 4.05                                       | 5.48                                 | 129623                  | 97324                   | 84                       | 40                              | 121                      | 11764648           | 9317561                 | 347                 | 0.32                  | 58                  | 25                    | 33                       | 25.84               | 54                     | 32                           | 65                     | 35                       | 41                      | 29                         | 25                      | 4                       | 1                                 | 7.60                           | 8.32                                   | 14.34                           | 20.44                   | 50432342                  | 5.41                              | 53                                  | 7794464                       | 1047                                   | 8040133       | 12.03                    | 2116316                     | 5183126   | 7.75                 | 32.54                   | 4670572                       | 6.65                                   | 31372981                                        | 1298692                                               | 30074289                                             | 28689620           | 95205000                | 5815537                 | 
| 2013           | 22278056                     | 137272                       | 26959168                   | 26722000                        | 29264294                 | 187202                     | 44507900                 | 11531000                           | 31649232                       | 100                                 | 9243                                | 300                                         | 0                                       | 2284320                                         | 4902                                     | 2053.65                         | 309.55                       | 600.47                | 1032                     | 1500                       | 1188                                    | 16798                | 28                         | 325            | 451                  | 18845                     | 35405                | 2150                    | 17304              | 49332               | 141529      | 17                      | 38                              | 36                             | 2695                         | 0                          | 174245                     | 2725                              | 108                   | 614                                                                 | 0                                                             | 0                   | 100                                                | 18                         | 18.00                                                     | 14.00                                                       | 782                      | 38                                             | 197159                 | 6                                     | 5.70                            | 391390                                | 547                     | 94                    | 95                    | 50                                  | 98                              |                                 | 828.51                         | 529.90                             | 1429.09                                        | 4.28                          | 4.37                                    | 4.21                                     | 4.30                                 | 4.06                                       | 6.66                                 | 159722                  | 101593                  | 121                      | 41                              | 121                      | 12319953           | 10017958                | 358                 | 0.95                  | 53                  | 19                    | 34                       | 25.24               | 51                     | 32                           | 66                     | 34                       | 42                      | 29                         | 25                      | 3                       | 1                                 | 8.95                           | 8.86                                   | 13.60                           | 21.06                   | 59078609                  | 5.99                              | 57                                  | 8559586                       | 1301                                   | 9510842       | 14.18                    | 2997046                     | 5191211   | 7.74                 | 31.26                   | 4799541                       | 6.52                                   | 32157713                                        | 1403806                                               | 30753907                                             | 27032670           | 103514000               | 6122513                 | 
| 2014           | 22836040                     | 141207                       | 28466050                   | 28466050                        | 29660980                 | 197246                     | 47865700                 | 17150000                           | 34484800                       | 100                                 | 36830                               | 7179                                        | 0                                       | 2532200                                         | 27793                                    | 2148.09                         | 291.24                       | 334.79                | 893                      | 1673                       | 1398                                    | 13338                | 150                        | 557            | 585                  | 3758                      | 34900                | 3318                    | 23469              | 55961               | 154774      | 12                      | 39                              | 35                             | 2861                         | -6                         | 179224                     | 4080                              | 126                   | 654                                                                 | 2                                                             | 0                   | 100                                                | 44                         | 12.36                                                     | 9.84                                                        | 866                      | 16                                             | 211019                 | 7                                     | 5.92                            | 335699                                | 285                     | 93                    | 96                    | 57                                  | 92                              |                                 | 679.60                         | 625.03                             | 343.86                                         | 4.34                          | 4.43                                    | 4.17                                     | 4.35                                 | 4.16                                       | 7.48                                 | 157811                  | 104103                  | 78                       | 41                              | 125                      | 13072485           | 10718854                | 362                 | 0.31                  | 52                  | 18                    | 30                       | 26.27               | 40                     | 37                           | 65                     | 35                       | 40                      | 28                         | 24                      | 4                       | 1                                 | 9.44                           | 8.01                                   | 14.41                           | 20.65                   | 66703521                  | 6.18                              | 60                                  | 9781041                       | 1460                                   | 9650825       | 12.69                    | 2124287                     | 4846183   | 6.37                 | 28.90                   | 4711908                       | 6.39                                   | 34181754                                        | 1626932                                               | 32554823                                             | 28905381           | 108960498               | 6392065                 | 
```