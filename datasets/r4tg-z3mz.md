# NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-points-for-all-vehicles-1-hour-intervals-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/r4tg-z3mz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/r4tg-z3mz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/r4tg-z3mz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | r4tg-z3mz |
| Name | NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: 2017 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2016-12-27T16:57:30Z |
| Publication Date | 2017-04-20T22:17:22Z |

## Description

This file contains data on the number and types of vehicles that entered from each entry point on the tolled section of the Thruway with their exit points.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                    | Data Type     | Render Type   |
| ======== | ============== | ============== | ======================= | ============= | ============= |
| Yes      | time           | date           | Date                    | calendar_date | calendar_date |
| Yes      | series tag     | entrance       | Entrance                | text          | text          |
| Yes      | series tag     | exit           | Exit                    | text          | text          |
| No       |                | beginning_time | Interval Beginning Time | text          | text          |
| Yes      | series tag     | vehicle_class  | Vehicle Class           | text          | text          |
| Yes      | numeric metric | vehicle_count  | Vehicle Count           | number        | number        |
| Yes      | series tag     | payment_type   | Payment Type            | text          | text          |
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
series e:r4tg-z3mz d:2017-01-01T00:00:00.000Z t:vehicle_class=2L t:payment_type=CASH t:exit=17 t:entrance=15 m:vehicle_count=14

series e:r4tg-z3mz d:2017-01-01T00:00:00.000Z t:vehicle_class=5H t:payment_type=CASH t:exit=17 t:entrance=15 m:vehicle_count=1

series e:r4tg-z3mz d:2017-01-01T00:00:00.000Z t:vehicle_class=2L t:payment_type=CASH t:exit=17 t:entrance=15 m:vehicle_count=33
```

## Meta Commands

```ls
metric m:vehicle_count p:long l:"Vehicle Count" d:"The number of vehicles reported" t:dataTypeName=number

entity e:r4tg-z3mz l:"NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: 2017" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/r4tg-z3mz

property e:r4tg-z3mz t:meta.view v:id=r4tg-z3mz v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: 2017" v:attribution="New York State Thruway Authority"

property e:r4tg-z3mz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:r4tg-z3mz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | entrance | exit | beginning_time | vehicle_class | vehicle_count | payment_type | 
| =================== | ======== | ==== | ============== | ============= | ============= | ============ | 
| 2017-01-01T00:00:00 | 15       | 17   | 00             | 2L            | 14            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 00             | 5H            | 1             | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 01             | 2L            | 33            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 02             | 2L            | 32            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 03             | 2L            | 34            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 04             | 2L            | 28            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 04             | 5H            | 1             | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 05             | 2L            | 20            | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 05             | 5H            | 2             | CASH         | 
| 2017-01-01T00:00:00 | 15       | 17   | 06             | 2L            | 16            | CASH         | 
```