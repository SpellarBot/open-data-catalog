# NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: October 2014 - December 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-points-for-all-vehicles-1-hour-intervals-october-2014-2) |
| Metadata | [Link](https://data.ny.gov/api/views/i57x-udiw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/i57x-udiw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/i57x-udiw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | i57x-udiw |
| Name | NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: October 2014 - December 2014 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2015-12-07T16:48:47Z |
| Publication Date | 2016-03-18T21:06:52Z |

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
series e:i57x-udiw d:2014-10-01T00:00:00.000Z t:vehicle_class=2H t:payment_type=CASH t:exit=17 t:entrance=15 m:vehicle_count=1

series e:i57x-udiw d:2014-11-08T00:00:00.000Z t:vehicle_class=2L t:payment_type=E-ZPass t:exit=15 t:entrance=35 m:vehicle_count=1

series e:i57x-udiw d:2014-10-10T00:00:00.000Z t:vehicle_class=2L t:payment_type=CASH t:exit=57 t:entrance=56 m:vehicle_count=2
```

## Meta Commands

```ls
metric m:vehicle_count p:integer l:"Vehicle Count" d:"The number of vehicles reported" t:dataTypeName=number

entity e:i57x-udiw l:"NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: October 2014 - December 2014" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/i57x-udiw

property e:i57x-udiw t:meta.view v:id=i57x-udiw v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination Points for All Vehicles - 1 Hour Intervals: October 2014 - December 2014" v:attribution="New York State Thruway Authority"

property e:i57x-udiw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:i57x-udiw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| date                | entrance | exit | beginning_time | vehicle_class | vehicle_count | payment_type | 
| =================== | ======== | ==== | ============== | ============= | ============= | ============ | 
| 2014-10-01T00:00:00 | 15       | 17   | 00             | 2H            | 1             | CASH         | 
| 2014-11-08T00:00:00 | 35       | 15   | 15             | 2L            | 1             | E-ZPass      | 
| 2014-10-10T00:00:00 | 56       | 57   | 08             | 2L            | 2             | CASH         | 
| 2014-12-01T00:00:00 | 19       | 34A  | 16             | 2L            | 2             | E-ZPass      | 
| 2014-10-05T00:00:00 | 38       | 50   | 16             | 2L            | 5             | CASH         | 
| 2014-12-26T00:00:00 | 43       | 40   | 02             | 2L            | 1             | E-ZPass      | 
| 2014-11-22T00:00:00 | 15       | 25A  | 20             | 2L            | 2             | E-ZPass      | 
| 2014-12-31T00:00:00 | 28       | 25A  | 16             | 5H            | 1             | E-ZPass      | 
| 2014-10-24T00:00:00 | 23       | 24   | 22             | 2L            | 19            | E-ZPass      | 
| 2014-11-07T00:00:00 | 57A      | 55   | 18             | 2H            | 1             | E-ZPass      | 
```