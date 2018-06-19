# MTA Average Weekday Ridership - by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mta-average-weekday-ridership-by-month) |
| Metadata | [Link](https://data.maryland.gov/api/views/ub96-xxqw) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ub96-xxqw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ub96-xxqw/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ub96-xxqw |
| Name | MTA Average Weekday Ridership - by Month |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | public transit, mta, maryland transit administration, rail, bus, marc, subway, metro, taxi, mobility, ridership |
| Created | 2012-10-11T15:06:31Z |
| Publication Date | 2017-01-09T17:51:53Z |

## Description

The average weekday ridership is indicative of the number of transit patrons making a one-way trip on any mode per weekday. This number is estimated and excludes holidays.

In FY2014, the MTA  upgraded its bus ridership counting system to enhance its service planning and scheduling functions. This new Automatic Passenger Count (APC) system uses computerized sensors to count passengers as they board and leave the vehicle. The APCs provide the most accurate estimates of bus ridership to date and the most robust data for ridership on particular routes, which will help drive planning decisions. In order to maintain the integrity of historical comparisons for the Transit Ridership Goal, the MTA used ridership estimate differences between the new APC system and previous counting estimates for its Bus Service to allow for apples-to-apples comparisons between fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | average_weekday_ridership       | Month                           | text      | text        |
| Yes      | numeric metric | bus                             | Bus                             | number    | number      |
| Yes      | numeric metric | metro                           | Metro                           | number    | number      |
| Yes      | numeric metric | light_rail                      | Light Rail                      | number    | number      |
| Yes      | numeric metric | mobility                        | Mobility                        | number    | number      |
| Yes      | numeric metric | taxi_access                     | Taxi Access                     | number    | number      |
| Yes      | numeric metric | marc_average                    | MARC Total                      | number    | number      |
| Yes      | numeric metric | marc_brunswick                  | MARC - Brunswick                | number    | number      |
| Yes      | numeric metric | marc_camden                     | MARC - Camden                   | number    | number      |
| Yes      | numeric metric | marc_penn                       | MARC - Penn                     | number    | number      |
| Yes      | numeric metric | commuter_bus_total              | Commuter Bus Total              | number    | number      |
| Yes      | numeric metric | baltimore                       | CB - Baltimore                  | number    | number      |
| Yes      | numeric metric | washington                      | CB - Washington                 | number    | number      |
| Yes      | numeric metric | icc                             | CB - ICC                        | number    | number      |
| Yes      | numeric metric | total_average_weekday_ridership | Total Average Weekday Ridership | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ub96-xxqw d:2014-08-28T15:36:20.000Z t:average_weekday_ridership=Jul-06 m:total_average_weekday_ridership=275280 m:bus=205015 m:metro=43358 m:taxi_access=1072 m:mobility=2838 m:light_rail=22997

series e:ub96-xxqw d:2014-08-28T15:36:20.000Z t:average_weekday_ridership=Aug-06 m:total_average_weekday_ridership=286612 m:bus=215455 m:metro=44427 m:taxi_access=1162 m:mobility=2860 m:light_rail=22708

series e:ub96-xxqw d:2014-08-28T15:36:20.000Z t:average_weekday_ridership=Sep-06 m:total_average_weekday_ridership=324062 m:bus=251719 m:metro=44062 m:taxi_access=1211 m:mobility=2985 m:light_rail=24085
```

## Meta Commands

```ls
metric m:bus p:integer l:Bus t:dataTypeName=number

metric m:metro p:integer l:Metro t:dataTypeName=number

metric m:light_rail p:integer l:"Light Rail" t:dataTypeName=number

metric m:mobility p:integer l:Mobility t:dataTypeName=number

metric m:taxi_access p:integer l:"Taxi Access" t:dataTypeName=number

metric m:marc_average p:integer l:"MARC Total" t:dataTypeName=number

metric m:marc_brunswick p:integer l:"MARC - Brunswick" t:dataTypeName=number

metric m:marc_camden p:integer l:"MARC - Camden" t:dataTypeName=number

metric m:marc_penn p:integer l:"MARC - Penn" t:dataTypeName=number

metric m:commuter_bus_total p:integer l:"Commuter Bus Total" t:dataTypeName=number

metric m:baltimore p:integer l:"CB - Baltimore" t:dataTypeName=number

metric m:washington p:integer l:"CB - Washington" t:dataTypeName=number

metric m:icc p:integer l:"CB - ICC" t:dataTypeName=number

metric m:total_average_weekday_ridership p:integer l:"Total Average Weekday Ridership" t:dataTypeName=number

entity e:ub96-xxqw l:"MTA Average Weekday Ridership - by Month" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/ub96-xxqw

property e:ub96-xxqw t:meta.view v:id=ub96-xxqw v:category=Transportation v:averageRating=0 v:name="MTA Average Weekday Ridership - by Month" v:attribution="Maryland Transit Administration"

property e:ub96-xxqw t:meta.view.license v:name="Public Domain"

property e:ub96-xxqw t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:ub96-xxqw t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| :updated_at | average_weekday_ridership | bus    | metro | light_rail | mobility | taxi_access | marc_average | marc_brunswick | marc_camden | marc_penn | commuter_bus_total | baltimore | washington | icc | total_average_weekday_ridership | 
| =========== | ========================= | ====== | ===== | ========== | ======== | =========== | ============ | ============== | =========== | ========= | ================== | ========= | ========== | === | =============================== | 
| 1409240180  | Jul-06                    | 205015 | 43358 | 22997      | 2838     | 1072        |              |                |             |           |                    |           |            |     | 275280                          | 
| 1409240180  | Aug-06                    | 215455 | 44427 | 22708      | 2860     | 1162        |              |                |             |           |                    |           |            |     | 286612                          | 
| 1409240180  | Sep-06                    | 251719 | 44062 | 24085      | 2985     | 1211        |              |                |             |           |                    |           |            |     | 324062                          | 
| 1409240180  | Oct-06                    | 251749 | 45510 | 22773      | 3055     | 1184        |              |                |             |           |                    |           |            |     | 324271                          | 
| 1409240180  | Nov-06                    | 247152 | 43469 | 22846      | 2997     | 1192        |              |                |             |           |                    |           |            |     | 317656                          | 
| 1409240180  | Dec-06                    | 232413 | 42324 | 23656      | 2940     | 1191        |              |                |             |           |                    |           |            |     | 302524                          | 
| 1409240180  | Jan-07                    | 240932 | 44371 | 23185      | 2981     | 1168        |              |                |             |           |                    |           |            |     | 312637                          | 
| 1409240180  | Feb-07                    | 220090 | 43082 | 26062      | 2783     | 1040        |              |                |             |           |                    |           |            |     | 293057                          | 
| 1409240180  | Mar-07                    | 250161 | 46007 | 23342      | 3211     | 1005        |              |                |             |           |                    |           |            |     | 323726                          | 
| 1409240180  | Apr-07                    | 234176 | 45422 | 25403      | 3132     | 1177        |              |                |             |           |                    |           |            |     | 309310                          | 
```