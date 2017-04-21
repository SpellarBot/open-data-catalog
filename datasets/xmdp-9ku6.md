# Total MTA Public Transit Ridership by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-ridership-by-fiscal-year-1fa44) |
| Metadata | [Link](https://data.maryland.gov/api/views/xmdp-9ku6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xmdp-9ku6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xmdp-9ku6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xmdp-9ku6 |
| Name | Total MTA Public Transit Ridership by Fiscal Year |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | transit, mta, maryland transit administration, governor's office of performance improvement, bus, metro, marc, rail, mobility, paratransit, ridership |
| Created | 2012-11-09T22:36:43Z |
| Publication Date | 2014-08-28T19:59:35Z |

## Description

In FY2014, the MTA also upgraded its bus ridership counting system to enhance its service planning and scheduling functions. This new Automatic Passenger Count (APC) system uses computerized sensors to count passengers as they board and leave the vehicle. The APCs provide the most accurate estimates of bus ridership to date and the most robust data for ridership on particular routes, which will help drive planning decisions. In order to maintain the integrity of historical comparisons for the Transit Ridership Goal, the MTA used ridership estimate differences between the new APC system and previous counting estimates for its Bus Service to allow for apples-to-apples comparisons between fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                     | Data Type | Render Type |
| ======== | ============== | ====================================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at                            | updated_at                               | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                            | Fiscal Year                              | text      | text        |
| Yes      | numeric metric | total_transit_trips_by_mode_bus        | Total Transit Trips by Mode - Bus        | number    | number      |
| Yes      | numeric metric | total_transit_trips_by_mode_metro      | Total Transit Trips by Mode - Metro      | number    | number      |
| Yes      | numeric metric | total_transit_trips_by_mode_light_rail | Total Transit Trips by Mode - Light Rail | number    | number      |
| Yes      | numeric metric | total_transit_trips_by_mode_marc       | Total Transit Trips by Mode - MARC       | number    | number      |
| Yes      | numeric metric | total_transit_trips_mobility           | Total Transit Trips-Mobility             | number    | number      |
| Yes      | numeric metric | total_transit_trips_call_a_ride        | Total Transit Trips-Call-A-Ride          | number    | number      |
| Yes      | numeric metric | total_transit_trips_commuter_bus       | Total Transit Trips-Commuter Bus         | number    | number      |
| Yes      | numeric metric | total_transit_trips                    | Total Transit Trips                      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xmdp-9ku6 d:2014-08-28T12:52:36.000Z t:fiscal_year=FY06 m:total_transit_trips_by_mode_bus=68667994 m:total_transit_trips=98420026 m:total_transit_trips_by_mode_metro=12919000 m:total_transit_trips_by_mode_light_rail=5401000 m:total_transit_trips_commuter_bus=3192629 m:total_transit_trips_call_a_ride=311666 m:total_transit_trips_mobility=653000 m:total_transit_trips_by_mode_marc=7274737

series e:xmdp-9ku6 d:2014-08-28T12:52:36.000Z t:fiscal_year=FY07 m:total_transit_trips_by_mode_bus=69474012 m:total_transit_trips=101934062 m:total_transit_trips_by_mode_metro=13225753 m:total_transit_trips_by_mode_light_rail=7122036 m:total_transit_trips_commuter_bus=3367027 m:total_transit_trips_call_a_ride=365690 m:total_transit_trips_mobility=874318 m:total_transit_trips_by_mode_marc=7505226

series e:xmdp-9ku6 d:2014-08-28T12:52:36.000Z t:fiscal_year=FY08 m:total_transit_trips_by_mode_bus=72103723 m:total_transit_trips=107022245 m:total_transit_trips_by_mode_metro=13955325 m:total_transit_trips_by_mode_light_rail=7962979 m:total_transit_trips_commuter_bus=3715563 m:total_transit_trips_call_a_ride=406669 m:total_transit_trips_mobility=980384 m:total_transit_trips_by_mode_marc=7897602
```

## Meta Commands

```ls
metric m:total_transit_trips_by_mode_bus p:integer l:"Total Transit Trips by Mode - Bus" t:dataTypeName=number

metric m:total_transit_trips_by_mode_metro p:integer l:"Total Transit Trips by Mode - Metro" t:dataTypeName=number

metric m:total_transit_trips_by_mode_light_rail p:integer l:"Total Transit Trips by Mode - Light Rail" t:dataTypeName=number

metric m:total_transit_trips_by_mode_marc p:integer l:"Total Transit Trips by Mode - MARC" t:dataTypeName=number

metric m:total_transit_trips_mobility p:integer l:"Total Transit Trips-Mobility" t:dataTypeName=number

metric m:total_transit_trips_call_a_ride p:integer l:"Total Transit Trips-Call-A-Ride" t:dataTypeName=number

metric m:total_transit_trips_commuter_bus p:integer l:"Total Transit Trips-Commuter Bus" t:dataTypeName=number

metric m:total_transit_trips p:integer l:"Total Transit Trips" t:dataTypeName=number

entity e:xmdp-9ku6 l:"Total MTA Public Transit Ridership by Fiscal Year" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/xmdp-9ku6

property e:xmdp-9ku6 t:meta.view v:id=xmdp-9ku6 v:category=Transportation v:attributionLink=http://mta.maryland.gov/ v:averageRating=0 v:name="Total MTA Public Transit Ridership by Fiscal Year" v:attribution="Maryland Transit Administration"

property e:xmdp-9ku6 t:meta.view.license v:name="Public Domain"

property e:xmdp-9ku6 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:xmdp-9ku6 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | fiscal_year | total_transit_trips_by_mode_bus | total_transit_trips_by_mode_metro | total_transit_trips_by_mode_light_rail | total_transit_trips_by_mode_marc | total_transit_trips_mobility | total_transit_trips_call_a_ride | total_transit_trips_commuter_bus | total_transit_trips | 
| =========== | =========== | =============================== | ================================= | ====================================== | ================================ | ============================ | =============================== | ================================ | =================== | 
| 1409230356  | FY06        | 68667994                        | 12919000                          | 5401000                                | 7274737                          | 653000                       | 311666                          | 3192629                          | 98420026            | 
| 1409230356  | FY07        | 69474012                        | 13225753                          | 7122036                                | 7505226                          | 874318                       | 365690                          | 3367027                          | 101934062           | 
| 1409230356  | FY08        | 72103723                        | 13955325                          | 7962979                                | 7897602                          | 980384                       | 406669                          | 3715563                          | 107022245           | 
| 1409230356  | FY09        | 75693961                        | 13566823                          | 8644099                                | 8021155                          | 1094437                      | 355310                          | 3973510                          | 111349295           | 
| 1409230356  | FY10        | 74925842                        | 13363903                          | 8158442                                | 8095577                          | 1209274                      | 271857                          | 3858783                          | 109883678           | 
| 1409230356  | FY11        | 78390159                        | 14587930                          | 8655209                                | 8232729                          | 1351065                      | 308662                          | 4096562                          | 115622316           | 
| 1409230356  | FY12        | 79535067                        | 15364164                          | 8539996                                | 8451695                          | 1554592                      | 345469                          | 4289775                          | 118080758           | 
| 1409230356  | FY13        | 80070751                        | 15208352                          | 8647381                                | 9062254                          | 1651198                      | 432534                          | 4187141                          | 119259611           | 
| 1409230356  | FY14        | 75780350                        | 14632430                          | 8105743                                | 8979468                          | 1781084                      | 507718                          | 4017089                          | 113803882           | 
```