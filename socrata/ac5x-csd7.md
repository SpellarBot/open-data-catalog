# Austin Resource Recovery Telework Pilot

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-resource-recovery-telework-pilot) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ac5x-csd7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ac5x-csd7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ac5x-csd7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ac5x-csd7 |
| Name | Austin Resource Recovery Telework Pilot |
| Tags | arr, austin resource recovery, telework, telecommute |
| Created | 2016-08-29T19:31:12Z |
| Publication Date | 2016-08-29T19:34:29Z |

## Description

During the City's Employee Commute Reduction Program, Austin Resource Recovery partnered with the non-profit Movability Austin to create a Mobility Plan for the department in order to further reduce on peak commutes and emissions caused by single occupancy vehicles.  One major strategy to achieve this goal was to implement a telework pilot.  ARR developed a telework policy and provided training to all participating employees and their managers.  The telework pilot ran from February 8, 2016, to May 6, 2016.  During this time, measures were taken regarding employees' schedules and commute habits as well as miles driven and estimated MPG of their cars in order to calculate emissions.  Surveys were also taken to gauge employee satisfaction and productivity associated with teleworking.  After reviewing the data and results from the pilot, ARR Director Bob Gedert approved the telework pilot to make it an official departmental program in July, 2016.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================= | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                    | meta_data | meta_data   |
| Yes      | series tag     | data_collection_dates                        | Data Collection Dates                         | text      | text        |
| Yes      | numeric metric | number_of_employees                          | Number of Employees                           | number    | number      |
| Yes      | numeric metric | miles_travelled_to_and_from_work             | Miles travelled to and from Work              | number    | number      |
| Yes      | numeric metric | weekly_emissions_grams_of_co2                | Weekly Emissions (grams of CO2)               | number    | number      |
| Yes      | numeric metric | drive_alone_miles_avoided                    | Drive-Alone Miles Avoided                     | number    | number      |
| Yes      | numeric metric | emissions_saved_pounds_of_co2                | Emissions saved (pounds of CO2)               | number    | number      |
| Yes      | numeric metric | est_weekly_savings                           | Est. Weekly Savings                           | money     | money       |
| Yes      | numeric metric | total_possible_commutes                      | Total Possible Commutes                       | number    | number      |
| Yes      | numeric metric | off_peak_am_trips                            | Off Peak AM Trips                             | number    | number      |
| Yes      | numeric metric | off_peak_pm_trips                            | Off Peak PM Trips                             | number    | number      |
| Yes      | numeric metric | on_peak_am_trips                             | On Peak AM Trips                              | number    | number      |
| Yes      | numeric metric | on_peak_pm_trips                             | On Peak PM Trips                              | number    | number      |
| Yes      | numeric metric | trips_by_alternative_transportation          | Trips by alternative transportation           | number    | number      |
| Yes      | numeric metric | trips_saved_by_alternative_schedule_telework | Trips saved by Alternative Schedule/ Telework | number    | number      |
| Yes      | numeric metric | total_on_peak_trips_reduced                  | Total On Peak Trips Reduced                   | number    | number      |
| Yes      | numeric metric | percent_reduction_of_on_peak_commutes        | Percent Reduction of On Peak commutes         | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ac5x-csd7 d:2016-08-29T19:31:18.000Z t:data_collection_dates="February Baseline" m:emissions_saved_pounds_of_co2=787 m:drive_alone_miles_avoided=1185 m:on_peak_pm_trips=372 m:trips_by_alternative_transportation=92 m:trips_saved_by_alternative_schedule_telework=56 m:percent_reduction_of_on_peak_commutes=46.25 m:on_peak_am_trips=279 m:total_possible_commutes=1040 m:off_peak_pm_trips=114 m:est_weekly_savings=690.35 m:number_of_employees=52 m:miles_travelled_to_and_from_work=1490 m:weekly_emissions_grams_of_co2=2502651 m:off_peak_am_trips=219 m:total_on_peak_trips_reduced=481

series e:ac5x-csd7 d:2016-08-29T19:31:18.000Z t:data_collection_dates="March Projected Totals" m:emissions_saved_pounds_of_co2=1485 m:drive_alone_miles_avoided=2031 m:on_peak_pm_trips=282 m:trips_by_alternative_transportation=74 m:trips_saved_by_alternative_schedule_telework=192 m:percent_reduction_of_on_peak_commutes=59.33 m:on_peak_am_trips=215 m:total_possible_commutes=1040 m:off_peak_pm_trips=135 m:est_weekly_savings=1167.62 m:number_of_employees=52 m:miles_travelled_to_and_from_work=1498 m:weekly_emissions_grams_of_co2=2155013 m:off_peak_am_trips=216 m:total_on_peak_trips_reduced=617

series e:ac5x-csd7 d:2016-08-29T19:31:18.000Z t:data_collection_dates="April Actual Totals" m:emissions_saved_pounds_of_co2=1294 m:drive_alone_miles_avoided=1687 m:on_peak_pm_trips=271 m:trips_by_alternative_transportation=46 m:trips_saved_by_alternative_schedule_telework=182 m:percent_reduction_of_on_peak_commutes=55.92 m:on_peak_am_trips=207 m:total_possible_commutes=980 m:off_peak_pm_trips=138 m:est_weekly_savings=969.82 m:number_of_employees=49 m:miles_travelled_to_and_from_work=1416 m:weekly_emissions_grams_of_co2=2103671 m:off_peak_am_trips=182 m:total_on_peak_trips_reduced=548
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:miles_travelled_to_and_from_work p:integer l:"Miles travelled to and from Work" t:dataTypeName=number

metric m:weekly_emissions_grams_of_co2 p:integer l:"Weekly Emissions (grams of CO2)" t:dataTypeName=number

metric m:drive_alone_miles_avoided p:integer l:"Drive-Alone Miles Avoided" t:dataTypeName=number

metric m:emissions_saved_pounds_of_co2 p:integer l:"Emissions saved (pounds of CO2)" t:dataTypeName=number

metric m:est_weekly_savings p:double l:"Est. Weekly Savings" t:dataTypeName=money

metric m:total_possible_commutes p:integer l:"Total Possible Commutes" t:dataTypeName=number

metric m:off_peak_am_trips p:integer l:"Off Peak AM Trips" t:dataTypeName=number

metric m:off_peak_pm_trips p:integer l:"Off Peak PM Trips" t:dataTypeName=number

metric m:on_peak_am_trips p:integer l:"On Peak AM Trips" t:dataTypeName=number

metric m:on_peak_pm_trips p:integer l:"On Peak PM Trips" t:dataTypeName=number

metric m:trips_by_alternative_transportation p:integer l:"Trips by alternative transportation" t:dataTypeName=number

metric m:trips_saved_by_alternative_schedule_telework p:integer l:"Trips saved by Alternative Schedule/ Telework" t:dataTypeName=number

metric m:total_on_peak_trips_reduced p:integer l:"Total On Peak Trips Reduced" t:dataTypeName=number

metric m:percent_reduction_of_on_peak_commutes p:float l:"Percent Reduction of On Peak commutes" t:dataTypeName=percent

entity e:ac5x-csd7 l:"Austin Resource Recovery Telework Pilot" t:url=https://data.austintexas.gov/api/views/ac5x-csd7

property e:ac5x-csd7 t:meta.view v:id=ac5x-csd7 v:averageRating=0 v:name="Austin Resource Recovery Telework Pilot"

property e:ac5x-csd7 t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:ac5x-csd7 t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | data_collection_dates  | number_of_employees | miles_travelled_to_and_from_work | weekly_emissions_grams_of_co2 | drive_alone_miles_avoided | emissions_saved_pounds_of_co2 | est_weekly_savings | total_possible_commutes | off_peak_am_trips | off_peak_pm_trips | on_peak_am_trips | on_peak_pm_trips | trips_by_alternative_transportation | trips_saved_by_alternative_schedule_telework | total_on_peak_trips_reduced | percent_reduction_of_on_peak_commutes | 
| =========== | ====================== | =================== | ================================ | ============================= | ========================= | ============================= | ================== | ======================= | ================= | ================= | ================ | ================ | =================================== | ============================================ | =========================== | ===================================== | 
| 1472499078  | February Baseline      | 52                  | 1490                             | 2502651                       | 1185                      | 787                           | 690.35             | 1040                    | 219               | 114               | 279              | 372              | 92                                  | 56                                           | 481                         | 46.25                                 | 
| 1472499078  | March Projected Totals | 52                  | 1498                             | 2155013                       | 2031                      | 1485                          | 1167.62            | 1040                    | 216               | 135               | 215              | 282              | 74                                  | 192                                          | 617                         | 59.33                                 | 
| 1472499078  | April Actual Totals    | 49                  | 1416                             | 2103671                       | 1687                      | 1294                          | 969.82             | 980                     | 182               | 138               | 207              | 271              | 46                                  | 182                                          | 548                         | 55.92                                 | 
```