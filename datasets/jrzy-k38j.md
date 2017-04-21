# ARR Employee Commute Reduction Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arr-employee-commute-reduction-program) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jrzy-k38j) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jrzy-k38j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jrzy-k38j/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jrzy-k38j |
| Name | ARR Employee Commute Reduction Program |
| Tags | arr, austin resource recovery, commute, reduction, carpool, vanpool, telecommute, transportation |
| Created | 2016-08-29T19:24:44Z |
| Publication Date | 2016-08-29T19:27:36Z |

## Description

In April, 2015, City Manager Marc Ott implemented the Employee Commute Reduction Program by directing all City of Austin departments to reduce employee commuting during peak periods by 20 percent.  This can be accomplished by teleworking, working alternative hours, working condensed schedules, and reducing single occupancy trips during peak hours.  By collecting baseline data regarding employees' schedules and commute habits, it was determined that nearly 74% of ARR's possible on peak commutes were already reduced by travelling off peak periods, using alternative schedules, teleworking, or by utilizing alternative transportation.  Austin Resource Recovery wanted to do even more and responded to the City Manager's initiative by implementing alternative work schedules for its administrative employees and encouraging reduction of single occupancy trips by utilizing public transportation, carpooling, and the vanpool program.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================== | ================================================== | ========= | =========== |
| No       | time           | :updated_at                                        | updated_at                                         | meta_data | meta_data   |
| Yes      | series tag     | data_collection_dates                              | Data Collection Dates                              | text      | text        |
| Yes      | numeric metric | total_employees                                    | Total Employees                                    | number    | number      |
| Yes      | numeric metric | possible_commutes                                  | Possible Commutes                                  | number    | number      |
| Yes      | numeric metric | total_commutes                                     | Total Commutes                                     | number    | number      |
| Yes      | numeric metric | on_peak_am                                         | On Peak AM                                         | number    | number      |
| Yes      | numeric metric | off_peak_am                                        | Off Peak AM                                        | number    | number      |
| Yes      | numeric metric | on_peak_pm                                         | On Peak PM                                         | number    | number      |
| Yes      | numeric metric | off_peak_pm                                        | Off Peak PM                                        | number    | number      |
| Yes      | numeric metric | trips_saved_by_alternative_schedule                | Trips Saved by alternative schedule                | number    | number      |
| Yes      | numeric metric | trips_saved_by_telework                            | Trips saved by Telework                            | number    | number      |
| Yes      | numeric metric | trips_taken_by_train                               | Trips taken by Train                               | number    | number      |
| Yes      | numeric metric | trips_taken_by_bus                                 | Trips taken by Bus                                 | number    | number      |
| Yes      | numeric metric | trips_taken_by_walking                             | Trips taken by Walking                             | number    | number      |
| Yes      | numeric metric | trips_taken_by_bike                                | Trips taken by Bike                                | number    | number      |
| Yes      | numeric metric | trips_taken_by_vanpool                             | Trips taken by Vanpool                             | number    | number      |
| Yes      | numeric metric | trips_taken_by_carpool                             | Trips taken by Carpool                             | number    | number      |
| Yes      | numeric metric | trips_saved_by_alternative_transportation_telework | Trips Saved by alternative transportation/Telework | number    | number      |
| Yes      | numeric metric | total_on_peak_trips_reduced                        | Total On Peak trips Reduced                        | number    | number      |
| Yes      | numeric metric | percent_reduction                                  | Percent Reduction                                  | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jrzy-k38j d:2016-08-29T19:24:54.000Z t:data_collection_dates="May Baseline" m:trips_taken_by_walking=0 m:trips_taken_by_bike=0 m:total_commutes=8140 m:on_peak_pm=1830 m:off_peak_am=3370 m:on_peak_am=700 m:possible_commutes=8140 m:trips_taken_by_vanpool=16.5 m:trips_saved_by_alternative_transportation_telework=35 m:percent_reduction=73.8 m:total_employees=407 m:trips_taken_by_carpool=4 m:trips_taken_by_train=3 m:trips_taken_by_bus=2 m:trips_saved_by_telework=9.5 m:total_on_peak_trips_reduced=6007 m:off_peak_pm=2240 m:trips_saved_by_alternative_schedule=362

series e:jrzy-k38j d:2016-08-29T19:24:54.000Z t:data_collection_dates="July Total" m:trips_taken_by_walking=0 m:trips_taken_by_bike=0 m:total_commutes=7596 m:on_peak_pm=1542 m:off_peak_am=3263 m:on_peak_am=486 m:possible_commutes=8240 m:trips_taken_by_vanpool=12 m:trips_saved_by_alternative_transportation_telework=44 m:percent_reduction=74.73 m:total_employees=412 m:trips_taken_by_carpool=18 m:trips_taken_by_train=0 m:trips_taken_by_bus=4 m:trips_saved_by_telework=10 m:total_on_peak_trips_reduced=6158 m:off_peak_pm=2207 m:trips_saved_by_alternative_schedule=644

series e:jrzy-k38j d:2016-08-29T19:24:54.000Z t:data_collection_dates="Sept. Total" m:trips_taken_by_walking=0 m:trips_taken_by_bike=0 m:total_commutes=7774 m:on_peak_pm=1610 m:off_peak_am=3397 m:on_peak_am=540 m:possible_commutes=8300 m:trips_taken_by_vanpool=24 m:trips_saved_by_alternative_transportation_telework=50 m:percent_reduction=75.88 m:total_employees=415 m:trips_taken_by_carpool=12 m:trips_taken_by_train=0 m:trips_taken_by_bus=4 m:trips_saved_by_telework=10 m:total_on_peak_trips_reduced=6298 m:off_peak_pm=2325 m:trips_saved_by_alternative_schedule=526
```

## Meta Commands

```ls
metric m:total_employees p:integer l:"Total Employees" t:dataTypeName=number

metric m:possible_commutes p:integer l:"Possible Commutes" t:dataTypeName=number

metric m:total_commutes p:integer l:"Total Commutes" t:dataTypeName=number

metric m:on_peak_am p:integer l:"On Peak AM" t:dataTypeName=number

metric m:off_peak_am p:integer l:"Off Peak AM" t:dataTypeName=number

metric m:on_peak_pm p:integer l:"On Peak PM" t:dataTypeName=number

metric m:off_peak_pm p:integer l:"Off Peak PM" t:dataTypeName=number

metric m:trips_saved_by_alternative_schedule p:integer l:"Trips Saved by alternative schedule" t:dataTypeName=number

metric m:trips_saved_by_telework p:double l:"Trips saved by Telework" t:dataTypeName=number

metric m:trips_taken_by_train p:integer l:"Trips taken by Train" t:dataTypeName=number

metric m:trips_taken_by_bus p:integer l:"Trips taken by Bus" t:dataTypeName=number

metric m:trips_taken_by_walking p:integer l:"Trips taken by Walking" t:dataTypeName=number

metric m:trips_taken_by_bike p:integer l:"Trips taken by Bike" t:dataTypeName=number

metric m:trips_taken_by_vanpool p:double l:"Trips taken by Vanpool" t:dataTypeName=number

metric m:trips_taken_by_carpool p:integer l:"Trips taken by Carpool" t:dataTypeName=number

metric m:trips_saved_by_alternative_transportation_telework p:integer l:"Trips Saved by alternative transportation/Telework" t:dataTypeName=number

metric m:total_on_peak_trips_reduced p:integer l:"Total On Peak trips Reduced" t:dataTypeName=number

metric m:percent_reduction p:float l:"Percent Reduction" t:dataTypeName=percent

entity e:jrzy-k38j l:"ARR Employee Commute Reduction Program" t:url=https://data.austintexas.gov/api/views/jrzy-k38j

property e:jrzy-k38j t:meta.view v:id=jrzy-k38j v:averageRating=0 v:name="ARR Employee Commute Reduction Program"

property e:jrzy-k38j t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:jrzy-k38j t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | data_collection_dates | total_employees | possible_commutes | total_commutes | on_peak_am | off_peak_am | on_peak_pm | off_peak_pm | trips_saved_by_alternative_schedule | trips_saved_by_telework | trips_taken_by_train | trips_taken_by_bus | trips_taken_by_walking | trips_taken_by_bike | trips_taken_by_vanpool | trips_taken_by_carpool | trips_saved_by_alternative_transportation_telework | total_on_peak_trips_reduced | percent_reduction | 
| =========== | ===================== | =============== | ================= | ============== | ========== | =========== | ========== | =========== | =================================== | ======================= | ==================== | ================== | ====================== | =================== | ====================== | ====================== | ================================================== | =========================== | ================= | 
| 1472498694  | May Baseline          | 407             | 8140              | 8140           | 700        | 3370        | 1830       | 2240        | 362                                 | 9.5                     | 3                    | 2                  | 0                      | 0                   | 16.5                   | 4                      | 35                                                 | 6007                        | 73.80             | 
| 1472498694  | July Total            | 412             | 8240              | 7596           | 486        | 3263        | 1542       | 2207        | 644                                 | 10                      | 0                    | 4                  | 0                      | 0                   | 12                     | 18                     | 44                                                 | 6158                        | 74.73             | 
| 1472498694  | Sept. Total           | 415             | 8300              | 7774           | 540        | 3397        | 1610       | 2325        | 526                                 | 10                      | 0                    | 4                  | 0                      | 0                   | 24                     | 12                     | 50                                                 | 6298                        | 75.88             | 
```