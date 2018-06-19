# NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-points-for-all-vehicles-15-minute-intervals-2016-q1) |
| Metadata | [Link](https://data.ny.gov/api/views/4n7x-kstx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4n7x-kstx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4n7x-kstx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4n7x-kstx |
| Name | NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q1 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2016-03-28T16:03:26Z |
| Publication Date | 2016-04-07T20:13:16Z |

## Description

This file contains data on the number and types of vehicles that entered from each entry point on the tolled section of the Thruway with their exit points.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | time           | date                         | Date                           | calendar_date | calendar_date |
| Yes      | series tag     | entrance                     | Entrance                       | text          | text          |
| Yes      | series tag     | exit                         | Exit                           | text          | text          |
| No       |                | beginning_time               | Interval Beginning Time        | text          | text          |
| Yes      | series tag     | vehicle_class                | Vehicle Class                  | text          | text          |
| Yes      | numeric metric | vehicle_count                | Vehicle Count                  | number        | number        |
| Yes      | series tag     | payment_type_cash_or_e_zpass | Payment Type (Cash or E-ZPass) | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = beginning_time
```

## Data Commands

```ls
series e:4n7x-kstx d:2016-01-14T00:00:00.000Z t:vehicle_class=2L t:payment_type_cash_or_e_zpass=CASH t:exit=34A t:entrance=36 m:vehicle_count=1

series e:4n7x-kstx d:2016-02-06T00:00:00.000Z t:vehicle_class=2L t:payment_type_cash_or_e_zpass=E-ZPass t:exit=34A t:entrance=24 m:vehicle_count=2

series e:4n7x-kstx d:2016-02-06T00:00:00.000Z t:vehicle_class=4H t:payment_type_cash_or_e_zpass=E-ZPass t:exit=17 t:entrance=19 m:vehicle_count=1
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:"Vehicle Count" d:"The number of vehicles reported" t:dataTypeName=number

entity e:4n7x-kstx l:"NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q1" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/4n7x-kstx

property e:4n7x-kstx t:meta.view v:id=4n7x-kstx v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q1" v:attribution="New York State Thruway Authority"

property e:4n7x-kstx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4n7x-kstx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | entrance | exit | beginning_time | vehicle_class | vehicle_count | payment_type_cash_or_e_zpass | 
| =================== | ======== | ==== | ============== | ============= | ============= | ============================ | 
| 2016-01-14T00:00:00 | 36       | 34A  | 1330           | 2L            | 1             | CASH                         | 
| 2016-02-06T00:00:00 | 24       | 34A  | 0815           | 2L            | 2             | E-ZPass                      | 
| 2016-02-06T00:00:00 | 19       | 17   | 0630           | 4H            | 1             | E-ZPass                      | 
| 2016-01-07T00:00:00 | 44       | 48   | 1415           | 2L            | 2             | CASH                         | 
| 2016-02-11T00:00:00 | 55       | 59   | 0900           | 5H            | 2             | CASH                         | 
| 2016-02-09T00:00:00 | 41       | 43   | 1700           | 2L            | 6             | E-ZPass                      | 
| 2016-01-27T00:00:00 | 28       | 34A  | 1815           | 2L            | 3             | E-ZPass                      | 
| 2016-03-03T00:00:00 | B2       | 28   | 2015           | 2L            | 1             | E-ZPass                      | 
| 2016-02-22T00:00:00 | 18       | 23   | 1015           | 2L            | 3             | CASH                         | 
| 2016-01-21T00:00:00 | 24       | 31   | 0645           | 2H            | 1             | CASH                         | 
```