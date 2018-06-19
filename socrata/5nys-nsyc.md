# EMS - Fleet Maintenance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-fleet-maintenance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5nys-nsyc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5nys-nsyc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5nys-nsyc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5nys-nsyc |
| Name | EMS - Fleet Maintenance |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, fleet |
| Created | 2015-12-10T19:49:31Z |
| Publication Date | 2015-12-10T22:52:49Z |

## Description

This table contains data on maintenance of the department response fleet ? ambulances, command trucks, and utility vehicles.  It includes the number of vehicles due for preventative maintenance each month, and the percentage that are serviced.  The data is broken out by the three vehicle types in addition to describing overall performance.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                              | Data Type     | Render Type   |
| ======== | ============== | =================================== | ================================= | ============= | ============= |
| Yes      | numeric metric | month_key                           | Month Key                         | number        | number        |
| Yes      | time           | month_start_date                    | Month-Year                        | calendar_date | calendar_date |
| Yes      | numeric metric | count_vehicles_due_all              | Total Vehicles Due                | number        | number        |
| Yes      | numeric metric | percent_vehicles_complete_all       | Percent of Vehicles Serviced      | percent       | percent       |
| Yes      | numeric metric | count_vehicles_due_ambulance        | Count Ambulances Due              | number        | number        |
| Yes      | numeric metric | percent_vehicles_complete_ambulance | Percent Ambulances Serviced       | percent       | percent       |
| Yes      | numeric metric | count_vehicles_due_command          | Count Command Vehicles Due        | number        | number        |
| Yes      | numeric metric | percent_vehicles_complete_command   | Percent Command Vehicles Serviced | percent       | percent       |
| Yes      | numeric metric | count_vehicles_due_utility          | Count Utility Vehicles Due        | number        | number        |
| Yes      | numeric metric | percent_vehicles_complete_utility   | Percent Utility Vehicles Serviced | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5nys-nsyc d:2012-10-01T00:00:00.000Z m:percent_vehicles_complete_command=100 m:count_vehicles_due_all=41 m:count_vehicles_due_ambulance=31 m:count_vehicles_due_command=4 m:percent_vehicles_complete_utility=100 m:count_vehicles_due_utility=6 m:percent_vehicles_complete_all=80.4878 m:percent_vehicles_complete_ambulance=74.1935 m:month_key=201210

series e:5nys-nsyc d:2012-11-01T00:00:00.000Z m:percent_vehicles_complete_command=100 m:count_vehicles_due_all=34 m:count_vehicles_due_ambulance=32 m:count_vehicles_due_command=2 m:percent_vehicles_complete_utility=100 m:count_vehicles_due_utility=0 m:percent_vehicles_complete_all=64.7058 m:percent_vehicles_complete_ambulance=62.5 m:month_key=201211

series e:5nys-nsyc d:2012-12-01T00:00:00.000Z m:percent_vehicles_complete_command=100 m:count_vehicles_due_all=31 m:count_vehicles_due_ambulance=23 m:count_vehicles_due_command=1 m:percent_vehicles_complete_utility=100 m:count_vehicles_due_utility=7 m:percent_vehicles_complete_all=83.8709 m:percent_vehicles_complete_ambulance=78.2608 m:month_key=201212
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Unique ID for record. Year and month in <yyyymm> format." t:dataTypeName=number

metric m:count_vehicles_due_all p:integer l:"Total Vehicles Due" d:"Count of all response vehicles due for service." t:dataTypeName=number

metric m:percent_vehicles_complete_all p:float l:"Percent of Vehicles Serviced" d:"Percentage of vehicles that received service by due date for the month." t:dataTypeName=percent

metric m:count_vehicles_due_ambulance p:integer l:"Count Ambulances Due" d:"Count of all ambulances due for service for the month." t:dataTypeName=number

metric m:percent_vehicles_complete_ambulance p:float l:"Percent Ambulances Serviced" d:"Percent of ambulances due for service in the month that received service by the due date." t:dataTypeName=percent

metric m:count_vehicles_due_command p:integer l:"Count Command Vehicles Due" d:"Count of command vehicles due for service in month." t:dataTypeName=number

metric m:percent_vehicles_complete_command p:float l:"Percent Command Vehicles Serviced" d:"Percent of command vehicles due for service in month that received service by due date." t:dataTypeName=percent

metric m:count_vehicles_due_utility p:integer l:"Count Utility Vehicles Due" d:"Count of all utility vehicles due for service in month." t:dataTypeName=number

metric m:percent_vehicles_complete_utility p:float l:"Percent Utility Vehicles Serviced" d:"Percent of utility vehicles due for service in month that received service by due date." t:dataTypeName=percent

entity e:5nys-nsyc l:"EMS - Fleet Maintenance" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/5nys-nsyc

property e:5nys-nsyc t:meta.view v:id=5nys-nsyc v:category="Public Safety" v:attributionLink=http://www.austintexas.gov/department/ems v:averageRating=0 v:name="EMS - Fleet Maintenance" v:attribution="Austin-Travis County EMS"

property e:5nys-nsyc t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:5nys-nsyc t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_vehicles_due_all | percent_vehicles_complete_all | count_vehicles_due_ambulance | percent_vehicles_complete_ambulance | count_vehicles_due_command | percent_vehicles_complete_command | count_vehicles_due_utility | percent_vehicles_complete_utility | 
| ========= | =================== | ====================== | ============================= | ============================ | =================================== | ========================== | ================================= | ========================== | ================================= | 
| 201210    | 2012-10-01T00:00:00 | 41                     | 80.487800                     | 31                           | 74.193500                           | 4                          | 100.000000                        | 6                          | 100.000000                        | 
| 201211    | 2012-11-01T00:00:00 | 34                     | 64.705800                     | 32                           | 62.500000                           | 2                          | 100.000000                        | 0                          | 100.000000                        | 
| 201212    | 2012-12-01T00:00:00 | 31                     | 83.870900                     | 23                           | 78.260800                           | 1                          | 100.000000                        | 7                          | 100.000000                        | 
| 201301    | 2013-01-01T00:00:00 | 29                     | 89.655100                     | 22                           | 90.909000                           | 4                          | 75.000000                         | 3                          | 100.000000                        | 
| 201302    | 2013-02-01T00:00:00 | 22                     | 86.363600                     | 20                           | 85.000000                           | 2                          | 100.000000                        | 0                          | 100.000000                        | 
| 201303    | 2013-03-01T00:00:00 | 32                     | 87.500000                     | 24                           | 83.333300                           | 3                          | 100.000000                        | 5                          | 100.000000                        | 
| 201304    | 2013-04-01T00:00:00 | 29                     | 75.862000                     | 24                           | 75.000000                           | 3                          | 66.666600                         | 2                          | 100.000000                        | 
| 201305    | 2013-05-01T00:00:00 | 39                     | 82.051200                     | 29                           | 82.758600                           | 3                          | 100.000000                        | 7                          | 71.428500                         | 
| 201306    | 2013-06-01T00:00:00 | 38                     | 68.421000                     | 34                           | 70.588200                           | 2                          | 50.000000                         | 2                          | 50.000000                         | 
| 201307    | 2013-07-01T00:00:00 | 38                     | 65.789400                     | 29                           | 62.068900                           | 4                          | 75.000000                         | 5                          | 80.000000                         | 
```