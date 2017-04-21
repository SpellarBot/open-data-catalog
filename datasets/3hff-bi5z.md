# SDOT Storm Response Last Hour

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-storm-response-last-hour) |
| Metadata | [Link](https://data.seattle.gov/api/views/3hff-bi5z) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3hff-bi5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3hff-bi5z/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3hff-bi5z |
| Name | SDOT Storm Response Last Hour |
| Tags | storm response |
| Created | 2016-12-08T23:52:11Z |
| Publication Date | 2016-12-14T18:14:02Z |

## Description

During a winter storm, SDOT sends out a fleet of vehicles equipped with GPS tracking systems. Some vehicles have a plow blade; others have de-icing or spreader equipment. This dataset shows the recent path of vehicles that have been dispatched to respond to the winter weather event within the last hour.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type  | Render Type |
| ======== | ============== | ================ | ================ | ========== | =========== |
| Yes      | series tag     | objectid         | OBJECTID         | text       | number      |
| Yes      | numeric metric | fleet            | FLEET            | number     | text        |
| No       |                | id               | ID               | text       | text        |
| Yes      | series tag     | assettype        | ASSETTYPE        | text       | text        |
| Yes      | series tag     | subtype          | SUBTYPE          | text       | text        |
| Yes      | series tag     | subtypeid        | SUBTYPEID        | text       | text        |
| Yes      | time           | datetimestamp    | DATETIMESTAMP    | date       | date        |
| Yes      | numeric metric | speedmph         | SPEEDMPH         | number     | number      |
| Yes      | series tag     | heading          | HEADING          | text       | text        |
| Yes      | numeric metric | reasons          | REASONS          | number     | text        |
| Yes      | numeric metric | distancetraveled | DISTANCETRAVELED | number     | number      |
| Yes      | numeric metric | odometer         | ODOMETER         | number     | number      |
| Yes      | series tag     | loadts           | LOADTS           | text       | text        |
| Yes      | series tag     | spreader_on      | SPREADER_ON      | text       | text        |
| Yes      | series tag     | plow_state       | PLOW_STATE       | text       | text        |
| No       |                | shape            | SHAPE            | geospatial | geospatial  |
| Yes      | numeric metric | shape_len        | SHAPE.LEN        | number     | number      |
```

## Time Field

```ls
Value = datetimestamp
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,shape
```

## Data Commands

```ls
series e:3hff-bi5z d:2017-04-20T23:37:41.000Z t:shape.longitude=-122.32368099999997 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=13 t:plow_state=U t:subtype="Liquid Deicer Truck" t:shape.latitude=47.57158300000003 t:objectid=1703448 t:loadts="2017-04-20 23:37:45.046087-07" t:assettype=Standard t:heading=NW m:fleet=85707 m:speedmph=2.9 m:odometer=6790.7 m:reasons=1024 m:distancetraveled=0

series e:3hff-bi5z d:2017-04-20T23:37:43.000Z t:shape.longitude=-122.32379799999995 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=13 t:plow_state=U t:subtype="Liquid Deicer Truck" t:shape.latitude=47.57163900000006 t:objectid=1703449 t:loadts="2017-04-20 23:37:46.375551-07" t:assettype=Standard t:heading=NW m:fleet=85707 m:speedmph=0 m:odometer=6790.7 m:reasons=512 m:distancetraveled=0

series e:3hff-bi5z d:2017-04-20T23:38:05.000Z t:shape.longitude=-122.32386299999996 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=13 t:plow_state=U t:subtype="Liquid Deicer Truck" t:shape.latitude=47.571660000000065 t:objectid=1703450 t:loadts="2017-04-20 23:38:08.567897-07" t:assettype=Standard t:heading=NE m:fleet=85707 m:speedmph=6.4 m:odometer=6790.8 m:reasons=1024 m:distancetraveled=0
```

## Meta Commands

```ls
metric m:fleet p:integer l:FLEET d:FLEET t:dataTypeName=number

metric m:speedmph p:float l:SPEEDMPH d:SPEEDMPH t:dataTypeName=number

metric m:reasons p:integer l:REASONS d:REASONS t:dataTypeName=number

metric m:distancetraveled p:float l:DISTANCETRAVELED d:DISTANCETRAVELED t:dataTypeName=number

metric m:odometer p:float l:ODOMETER d:ODOMETER t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

entity e:3hff-bi5z l:"SDOT Storm Response Last Hour" t:url=https://data.seattle.gov/api/views/3hff-bi5z

property e:3hff-bi5z t:meta.view v:id=3hff-bi5z v:averageRating=0 v:name="SDOT Storm Response Last Hour"

property e:3hff-bi5z t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:3hff-bi5z t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | fleet | id | assettype | subtype             | subtypeid | datetimestamp | speedmph                                              | heading | reasons | distancetraveled                                          | odometer                                      | loadts                        | spreader_on | plow_state | shape                                                                                                                                                         | shape_len | 
| ======== | ===== | == | ========= | =================== | ========= | ============= | ===================================================== | ======= | ======= | ========================================================= | ============================================= | ============================= | =========== | ========== | ============================================================================================================================================================= | ========= | 
| 1703448  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731461    | 2.899999999999999911182158029987476766109466552734375 | NW      | 1024    | 0                                                         | 6790.6999999999998181010596454143524169921875 | 2017-04-20 23:37:45.046087-07 | N           | U          | [null, 47.57158300000003, -122.32368099999997, null, false, {paths=[[[-122.32368099999997, 47.57158300000003], [-122.32379799999995, 47.57163900000006]]]}]   |           | 
| 1703449  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731463    | 0                                                     | NW      | 512     | 0                                                         | 6790.6999999999998181010596454143524169921875 | 2017-04-20 23:37:46.375551-07 | N           | U          | [null, 47.57163900000006, -122.32379799999995, null, false, {paths=[[[-122.32379799999995, 47.57163900000006], [-122.32386299999996, 47.571660000000065]]]}]  |           | 
| 1703450  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731485    | 6.4000000000000003552713678800500929355621337890625   | NE      | 1024    | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:38:08.567897-07 | N           | U          | [null, 47.571660000000065, -122.32386299999996, null, false, {paths=[[[-122.32386299999996, 47.571660000000065], [-122.32385899999997, 47.57177600000006]]]}] |           | 
| 1703451  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731502    | 0                                                     | S       | 512     | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:38:22.894884-07 | N           | U          | [null, 47.57177600000006, -122.32385899999997, null, false, {paths=[[[-122.32385899999997, 47.57177600000006], [-122.32356999999996, 47.57183100000003]]]}]   |           | 
| 1703452  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731526    | 4.29999999999999982236431605997495353221893310546875  | SE      | 1024    | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:38:49.205257-07 | N           | U          | [null, 47.57183100000003, -122.32356999999996, null, false, {paths=[[[-122.32356999999996, 47.57183100000003], [-122.32349099999999, 47.571785000000034]]]}]  |           | 
| 1703453  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731558    | 0                                                     | SWW     | 512     | 0.1000000000000000055511151231257827021181583404541015625 | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:39:21.449573-07 | N           | U          | [null, 47.571785000000034, -122.32349099999999, null, false, {paths=[[[-122.32349099999999, 47.571785000000034], [-122.32325199999997, 47.57174800000007]]]}] |           | 
| 1703454  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731644    | 3.5                                                   | W       | 1024    | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:40:47.695383-07 | N           | U          | [null, 47.57174800000007, -122.32325199999997, null, false, {paths=[[[-122.32325199999997, 47.57174800000007], [-122.32347999999996, 47.57183300000003]]]}]   |           | 
| 1703455  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731647    | 0                                                     | SWW     | 512     | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:40:48.815927-07 | N           | U          | [null, 47.57183300000003, -122.32347999999996, null, false, {paths=[[[-122.32347999999996, 47.57183300000003], [-122.32353899999998, 47.57184200000006]]]}]   |           | 
| 1703456  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492731679    | 0                                                     | SWW     | 128     | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:41:22.454915-07 | N           | U          | [null, 47.57184200000006, -122.32353899999998, null, false, {paths=[[[-122.32353899999998, 47.57184200000006], [-122.32363299999997, 47.57185700000008]]]}]   |           | 
| 1703457  | 85707 | 14 | Standard  | Liquid Deicer Truck | 13        | 1492732292    | 4                                                     | W       | 1024    | 0                                                         | 6790.8000000000001818989403545856475830078125 | 2017-04-20 23:51:35.49974-07  | N           | U          | [null, 47.57185700000008, -122.32363299999997, null, false, {paths=[[[-122.32363299999997, 47.57185700000008], [-122.32379999999995, 47.571912000000054]]]}]  |           | 
```