# NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-points-for-all-vehicles-15-minute-intervals-2016-q3) |
| Metadata | [Link](https://data.ny.gov/api/views/ib6f-ap6m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ib6f-ap6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ib6f-ap6m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ib6f-ap6m |
| Name | NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q3 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2016-10-06T20:42:51Z |
| Publication Date | 2016-10-28T17:20:51Z |

## Description

This file contains data on the number and types of vehicles that entered from each entry point on the tolled section of the Thruway with their exit points.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============================== | ============= | ============= |
| Yes      | time           | date           | Date                           | calendar_date | calendar_date |
| Yes      | series tag     | entrance       | Entrance                       | text          | text          |
| Yes      | series tag     | exit           | Exit                           | text          | text          |
| No       |                | beginning_time | Interval Beginning Time        | text          | text          |
| Yes      | series tag     | vehicle_class  | Vehicle Class                  | text          | text          |
| Yes      | numeric metric | vehicle_count  | Vehicle Count                  | number        | number        |
| Yes      | series tag     | payment_type   | Payment Type (Cash or E-ZPass) | text          | text          |
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
series e:ib6f-ap6m d:2016-08-06T00:00:00.000Z t:vehicle_class=2L t:payment_type=E-ZPass t:exit=47 t:entrance=48A m:vehicle_count=3

series e:ib6f-ap6m d:2016-07-11T00:00:00.000Z t:vehicle_class=4L t:payment_type=CASH t:exit=17 t:entrance=15 m:vehicle_count=2

series e:ib6f-ap6m d:2016-09-12T00:00:00.000Z t:vehicle_class=5H t:payment_type=E-ZPass t:exit=47 t:entrance=50 m:vehicle_count=3
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:"Vehicle Count" d:"The number of vehicles reported" t:dataTypeName=number

entity e:ib6f-ap6m l:"NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q3" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/ib6f-ap6m

property e:ib6f-ap6m t:meta.view v:id=ib6f-ap6m v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination Points for All Vehicles - 15 Minute Intervals: 2016 Q3" v:attribution="New York State Thruway Authority"

property e:ib6f-ap6m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ib6f-ap6m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | entrance | exit | beginning_time | vehicle_class | vehicle_count | payment_type | 
| =================== | ======== | ==== | ============== | ============= | ============= | ============ | 
| 2016-08-06T00:00:00 | 48A      | 47   | 2115           | 2L            | 3             | E-ZPass      | 
| 2016-07-11T00:00:00 | 15       | 17   | 1145           | 4L            | 2             | CASH         | 
| 2016-09-12T00:00:00 | 50       | 47   | 0715           | 5H            | 3             | E-ZPass      | 
| 2016-09-16T00:00:00 | 16       | 23   | 1830           | 2L            | 2             | CASH         | 
| 2016-08-05T00:00:00 | 28       | 47   | 1430           | 5S            | 1             | E-ZPass      | 
| 2016-08-30T00:00:00 | 38       | 35   | 0545           | 2L            | 13            | E-ZPass      | 
| 2016-09-18T00:00:00 | 58       | 57   | 1545           | 2L            | 3             | E-ZPass      | 
| 2016-09-22T00:00:00 | 46       | 41   | 1500           | 5S            | 1             | E-ZPass      | 
| 2016-07-01T00:00:00 | 34       | 37   | 0745           | 2L            | 8             | E-ZPass      | 
| 2016-08-11T00:00:00 | 45       | 36   | 1100           | 2L            | 4             | CASH         | 
```