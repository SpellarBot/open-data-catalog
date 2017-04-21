# Performance Metrics - 311 Call Center

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-311-call-center-63dc7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kj88-xnxq) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kj88-xnxq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kj88-xnxq/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kj88-xnxq |
| Name | Performance Metrics - 311 Call Center |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery |
| Created | 2011-09-26T20:36:39Z |
| Publication Date | 2016-08-09T14:11:17Z |

## Description

To make 311 effective for residents, visitors, and business owners, 311 representatives must respond to calls in a timely and accurate manner.

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                   | Data Type | Render Type |
| ======== | ============== | =================================================== | ====================================================== | ========= | =========== |
| No       | time           | :updated_at                                         | updated_at                                             | meta_data | meta_data   |
| Yes      | numeric metric | sort                                                | Sort                                                   | number    | number      |
| Yes      | series tag     | dates                                               | Dates                                                  | text      | text        |
| Yes      | numeric metric | average_number_of_operators_mon_fri_7_00am_3_00pm_  | Average Number of Operators, Mon-Fri, (7:00AM-3:00PM)  | number    | number      |
| Yes      | numeric metric | average_number_of_operators_mon_fri_3_00pm_11_00pm_ | Average Number of Operators, Mon-Fri, (3:00PM-11:00PM) | number    | number      |
| Yes      | numeric metric | average_number_of_operators_mon_fri_11_00pm_7_00am_ | Average Number of Operators, Mon-Fri, (11:00PM-7:00AM) | number    | number      |
| Yes      | numeric metric | average_number_of_operators_sat_sun_7_00am_3_00pm_  | Average Number of Operators, Sat-Sun, (7:00AM-3:00PM)  | number    | number      |
| Yes      | numeric metric | average_number_of_operators_sat_sun_3_00pm_11_00pm_ | Average Number of Operators, Sat-Sun, (3:00PM-11:00PM) | number    | number      |
| Yes      | numeric metric | average_number_of_operators_sat_sun_11_00pm_7_00am_ | Average Number of Operators, Sat-Sun, (11:00PM-7:00AM) | number    | number      |
| Yes      | numeric metric | call_volume_7_00am_3_00pm_                          | Call Volume (7:00AM-3:00PM)                            | number    | number      |
| Yes      | numeric metric | call_volume_3_00pm_11_00pm_                         | Call Volume (3:00PM-11:00PM)                           | number    | number      |
| Yes      | numeric metric | call_volume_11_00pm_7_00am_                         | Call Volume (11:00PM-7:00AM)                           | number    | number      |
| Yes      | numeric metric | efficiency_7_00am_3_00pm_                           | Efficiency (7:00AM-3:00PM)                             | percent   | percent     |
| Yes      | numeric metric | efficiency_3_00pm_11_00pm_                          | Efficiency (3:00PM-11:00PM)                            | percent   | percent     |
| Yes      | numeric metric | efficiency_11_00pm_7_00am_                          | Efficiency (11:00PM-7:00AM)                            | percent   | percent     |
| Yes      | numeric metric | utilization_7_00am_3_00pm_                          | Utilization (7:00AM-3:00PM)                            | percent   | percent     |
| Yes      | numeric metric | utilization_3_00pm_11_00pm_                         | Utilization (3:00PM-11:00PM)                           | percent   | percent     |
| Yes      | numeric metric | utilization_11_00pm_7_00am_                         | Utilization (11:00PM-7:00AM)                           | percent   | percent     |
| Yes      | numeric metric | abandoned_7_00am_3_00pm_                            | Abandoned (7:00AM-3:00PM)                              | percent   | percent     |
| Yes      | numeric metric | abandoned_3_00pm_11_00pm_                           | Abandoned (3:00PM-11:00PM)                             | percent   | percent     |
| Yes      | numeric metric | abandoned_11_00pm_7_00am_                           | Abandoned (11:00PM-7:00AM)                             | percent   | percent     |
| Yes      | numeric metric | average_wait_time_seconds_7_00am_3_00pm             | Average Wait Time (seconds): 7:00AM-3:00PM             | number    | number      |
| Yes      | numeric metric | average_wait_time_seconds_3_00pm_11_00pm            | Average Wait Time (seconds): 3:00PM-11:00PM            | number    | number      |
| Yes      | numeric metric | average_wait_time_seconds_11_00pm_7_00am            | Average Wait Time (seconds): 11:00PM-7:00AM            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kj88-xnxq d:2016-08-09T07:08:28.000Z t:dates=4/10/11-4/16/11 m:sort=1 m:efficiency_7_00am_3_00pm_=92 m:average_number_of_operators_mon_fri_3_00pm_11_00pm_=25 m:call_volume_11_00pm_7_00am_=18113 m:abandoned_7_00am_3_00pm_=9 m:average_wait_time_seconds_11_00pm_7_00am=67 m:efficiency_3_00pm_11_00pm_=89 m:abandoned_3_00pm_11_00pm_=11 m:average_wait_time_seconds_7_00am_3_00pm=14 m:average_number_of_operators_mon_fri_7_00am_3_00pm_=2 m:average_number_of_operators_sat_sun_3_00pm_11_00pm_=16 m:abandoned_11_00pm_7_00am_=17 m:average_wait_time_seconds_3_00pm_11_00pm=53 m:call_volume_7_00am_3_00pm_=3905 m:efficiency_11_00pm_7_00am_=82 m:average_number_of_operators_sat_sun_11_00pm_7_00am_=7 m:average_number_of_operators_mon_fri_11_00pm_7_00am_=8 m:utilization_11_00pm_7_00am_=69 m:average_number_of_operators_sat_sun_7_00am_3_00pm_=2 m:utilization_7_00am_3_00pm_=43 m:call_volume_3_00pm_11_00pm_=27090 m:utilization_3_00pm_11_00pm_=74

series e:kj88-xnxq d:2016-08-09T07:08:28.000Z t:dates=4/17/11-4/23/11 m:sort=2 m:efficiency_7_00am_3_00pm_=94 m:average_number_of_operators_mon_fri_3_00pm_11_00pm_=24 m:call_volume_11_00pm_7_00am_=16865 m:abandoned_7_00am_3_00pm_=6 m:average_wait_time_seconds_11_00pm_7_00am=72 m:efficiency_3_00pm_11_00pm_=89 m:abandoned_3_00pm_11_00pm_=12 m:average_wait_time_seconds_7_00am_3_00pm=8 m:average_number_of_operators_mon_fri_7_00am_3_00pm_=2 m:average_number_of_operators_sat_sun_3_00pm_11_00pm_=15 m:abandoned_11_00pm_7_00am_=16 m:average_wait_time_seconds_3_00pm_11_00pm=12 m:call_volume_7_00am_3_00pm_=3892 m:efficiency_11_00pm_7_00am_=81 m:average_number_of_operators_sat_sun_11_00pm_7_00am_=7 m:average_number_of_operators_mon_fri_11_00pm_7_00am_=7 m:utilization_11_00pm_7_00am_=71 m:average_number_of_operators_sat_sun_7_00am_3_00pm_=1 m:utilization_7_00am_3_00pm_=41 m:call_volume_3_00pm_11_00pm_=27021 m:utilization_3_00pm_11_00pm_=75

series e:kj88-xnxq d:2016-08-09T07:08:28.000Z t:dates=4/24/11-4/30/11 m:sort=3 m:efficiency_7_00am_3_00pm_=93 m:average_number_of_operators_mon_fri_3_00pm_11_00pm_=25 m:call_volume_11_00pm_7_00am_=18266 m:abandoned_7_00am_3_00pm_=8 m:average_wait_time_seconds_11_00pm_7_00am=51 m:efficiency_3_00pm_11_00pm_=92 m:abandoned_3_00pm_11_00pm_=9 m:average_wait_time_seconds_7_00am_3_00pm=10 m:average_number_of_operators_mon_fri_7_00am_3_00pm_=2 m:average_number_of_operators_sat_sun_3_00pm_11_00pm_=15 m:abandoned_11_00pm_7_00am_=14 m:average_wait_time_seconds_3_00pm_11_00pm=41 m:call_volume_7_00am_3_00pm_=3748 m:efficiency_11_00pm_7_00am_=86 m:average_number_of_operators_sat_sun_11_00pm_7_00am_=8 m:average_number_of_operators_mon_fri_11_00pm_7_00am_=10 m:utilization_11_00pm_7_00am_=69 m:average_number_of_operators_sat_sun_7_00am_3_00pm_=2 m:utilization_7_00am_3_00pm_=43 m:call_volume_3_00pm_11_00pm_=26995 m:utilization_3_00pm_11_00pm_=73
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort d:"Column to sort by" t:dataTypeName=number

metric m:average_number_of_operators_mon_fri_7_00am_3_00pm_ p:integer l:"Average Number of Operators, Mon-Fri, (7:00AM-3:00PM)" t:dataTypeName=number

metric m:average_number_of_operators_mon_fri_3_00pm_11_00pm_ p:integer l:"Average Number of Operators, Mon-Fri, (3:00PM-11:00PM)" t:dataTypeName=number

metric m:average_number_of_operators_mon_fri_11_00pm_7_00am_ p:integer l:"Average Number of Operators, Mon-Fri, (11:00PM-7:00AM)" t:dataTypeName=number

metric m:average_number_of_operators_sat_sun_7_00am_3_00pm_ p:integer l:"Average Number of Operators, Sat-Sun, (7:00AM-3:00PM)" t:dataTypeName=number

metric m:average_number_of_operators_sat_sun_3_00pm_11_00pm_ p:integer l:"Average Number of Operators, Sat-Sun, (3:00PM-11:00PM)" t:dataTypeName=number

metric m:average_number_of_operators_sat_sun_11_00pm_7_00am_ p:integer l:"Average Number of Operators, Sat-Sun, (11:00PM-7:00AM)" t:dataTypeName=number

metric m:call_volume_7_00am_3_00pm_ p:integer l:"Call Volume (7:00AM-3:00PM)" t:dataTypeName=number

metric m:call_volume_3_00pm_11_00pm_ p:integer l:"Call Volume (3:00PM-11:00PM)" t:dataTypeName=number

metric m:call_volume_11_00pm_7_00am_ p:integer l:"Call Volume (11:00PM-7:00AM)" t:dataTypeName=number

metric m:efficiency_7_00am_3_00pm_ p:integer l:"Efficiency (7:00AM-3:00PM)" t:dataTypeName=percent

metric m:efficiency_3_00pm_11_00pm_ p:integer l:"Efficiency (3:00PM-11:00PM)" t:dataTypeName=percent

metric m:efficiency_11_00pm_7_00am_ p:integer l:"Efficiency (11:00PM-7:00AM)" t:dataTypeName=percent

metric m:utilization_7_00am_3_00pm_ p:integer l:"Utilization (7:00AM-3:00PM)" t:dataTypeName=percent

metric m:utilization_3_00pm_11_00pm_ p:integer l:"Utilization (3:00PM-11:00PM)" t:dataTypeName=percent

metric m:utilization_11_00pm_7_00am_ p:integer l:"Utilization (11:00PM-7:00AM)" t:dataTypeName=percent

metric m:abandoned_7_00am_3_00pm_ p:integer l:"Abandoned (7:00AM-3:00PM)" t:dataTypeName=percent

metric m:abandoned_3_00pm_11_00pm_ p:integer l:"Abandoned (3:00PM-11:00PM)" t:dataTypeName=percent

metric m:abandoned_11_00pm_7_00am_ p:double l:"Abandoned (11:00PM-7:00AM)" t:dataTypeName=percent

metric m:average_wait_time_seconds_7_00am_3_00pm p:integer l:"Average Wait Time (seconds): 7:00AM-3:00PM" t:dataTypeName=number

metric m:average_wait_time_seconds_3_00pm_11_00pm p:integer l:"Average Wait Time (seconds): 3:00PM-11:00PM" t:dataTypeName=number

metric m:average_wait_time_seconds_11_00pm_7_00am p:integer l:"Average Wait Time (seconds): 11:00PM-7:00AM" t:dataTypeName=number

entity e:kj88-xnxq l:"Performance Metrics - 311 Call Center" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kj88-xnxq

property e:kj88-xnxq t:meta.view v:id=kj88-xnxq v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - 311 Call Center" v:attribution="City of Chicago"

property e:kj88-xnxq t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:kj88-xnxq t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | sort | dates            | average_number_of_operators_mon_fri_7_00am_3_00pm_ | average_number_of_operators_mon_fri_3_00pm_11_00pm_ | average_number_of_operators_mon_fri_11_00pm_7_00am_ | average_number_of_operators_sat_sun_7_00am_3_00pm_ | average_number_of_operators_sat_sun_3_00pm_11_00pm_ | average_number_of_operators_sat_sun_11_00pm_7_00am_ | call_volume_7_00am_3_00pm_ | call_volume_3_00pm_11_00pm_ | call_volume_11_00pm_7_00am_ | efficiency_7_00am_3_00pm_ | efficiency_3_00pm_11_00pm_ | efficiency_11_00pm_7_00am_ | utilization_7_00am_3_00pm_ | utilization_3_00pm_11_00pm_ | utilization_11_00pm_7_00am_ | abandoned_7_00am_3_00pm_ | abandoned_3_00pm_11_00pm_ | abandoned_11_00pm_7_00am_ | average_wait_time_seconds_7_00am_3_00pm | average_wait_time_seconds_3_00pm_11_00pm | average_wait_time_seconds_11_00pm_7_00am | 
| =========== | ==== | ================ | ================================================== | =================================================== | =================================================== | ================================================== | =================================================== | =================================================== | ========================== | =========================== | =========================== | ========================= | ========================== | ========================== | ========================== | =========================== | =========================== | ======================== | ========================= | ========================= | ======================================= | ======================================== | ======================================== | 
| 1470726508  | 1    | 4/10/11-4/16/11  | 2                                                  | 25                                                  | 8                                                   | 2                                                  | 16                                                  | 7                                                   | 3905                       | 27090                       | 18113                       | 92                        | 89                         | 82                         | 43                         | 74                          | 69                          | 9                        | 11                        | 17                        | 14                                      | 53                                       | 67                                       | 
| 1470726508  | 2    | 4/17/11-4/23/11  | 2                                                  | 24                                                  | 7                                                   | 1                                                  | 15                                                  | 7                                                   | 3892                       | 27021                       | 16865                       | 94                        | 89                         | 81                         | 41                         | 75                          | 71                          | 6                        | 12                        | 16                        | 8                                       | 12                                       | 72                                       | 
| 1470726508  | 3    | 4/24/11-4/30/11  | 2                                                  | 25                                                  | 10                                                  | 2                                                  | 15                                                  | 8                                                   | 3748                       | 26995                       | 18266                       | 93                        | 92                         | 86                         | 43                         | 73                          | 69                          | 8                        | 9                         | 14                        | 10                                      | 41                                       | 51                                       | 
| 1470726508  | 4    | 5/1/11-5/7/11    | 2                                                  | 22                                                  | 10                                                  | 2                                                  | 15                                                  | 9                                                   | 4167                       | 26105                       | 18029                       | 93                        | 86                         | 85                         | 44                         | 74                          | 66                          | 8                        | 12                        | 13                        | 11                                      | 63                                       | 51                                       | 
| 1470726508  | 5    | 5/8/11-5/14/11   | 2                                                  | 22                                                  | 9                                                   | 2                                                  | 12                                                  | 9                                                   | 4385                       | 24762                       | 18171                       | 91                        | 77                         | 82                         | 50                         | 76                          | 71                          | 10                       | 17                        | 17                        | 13                                      | 105                                      | 69                                       | 
| 1470726508  | 6    | 5/15/11-5/21/11  | 2                                                  | 24                                                  | 9                                                   | 1                                                  | 14                                                  | 8                                                   | 4203                       | 26465                       | 18318                       | 91                        | 76                         | 83                         | 50                         | 75                          | 75                          | 10                       | 16                        | 17                        | 16                                      | 103                                      | 74                                       | 
| 1470726508  | 7    | 5/22/11-5/28/11  | 1                                                  | 22                                                  | 10                                                  | 2                                                  | 13                                                  | 7                                                   | 4621                       | 26869                       | 19434                       | 93                        | 67                         | 82                         | 51                         | 76                          | 72                          | 8                        | 18                        | 16                        | 13                                      | 130                                      | 78                                       | 
| 1470726508  | 8    | 5/30/11-6/5/11   | 23                                                 | 7                                                   | 2                                                   | 15                                                 | 9                                                   | 2                                                   | 26223                      | 19814                       | 5417                        | 59                        | 66                         | 92                         | 71                         | 72                          | 53                          | 21                       | 19                        | 10                        | 144                                     | 127                                      | 17                                       | 
| 1470726508  | 9    | 6/06/11-6/12/11  | 22                                                 | 9                                                   | 2                                                   | 14                                                 | 7                                                   | 1                                                   | 39150                      | 33462                       | 6494                        | 53                        | 54                         | 90                         | 76                         | 75                          | 58                          | 27                       | 28                        | 10                        | 173                                     | 166                                      | 25                                       | 
| 1470726508  | 10   | 6/13/11- 6/19/11 | 21                                                 | 8                                                   | 1                                                   | 14                                                 | 7                                                   | 1                                                   | 26368                      | 18625                       | 4851                        | 57                        | 57                         | 89                         | 76                         | 75                          | 55                          | 22                       | 25                        | 12                        | 163                                     | 163                                      | 25                                       | 
```