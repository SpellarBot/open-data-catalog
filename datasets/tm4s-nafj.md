# SDOT Storm Response Last 3 Hours

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-storm-response-last-3-hours) |
| Metadata | [Link](https://data.seattle.gov/api/views/tm4s-nafj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/tm4s-nafj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/tm4s-nafj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | tm4s-nafj |
| Name | SDOT Storm Response Last 3 Hours |
| Tags | storm response |
| Created | 2016-12-09T18:00:43Z |
| Publication Date | 2016-12-14T16:27:18Z |

## Description

During a winter storm, SDOT sends out a fleet of vehicles equipped with GPS tracking systems. Some vehicles have a plow blade; others have de-icing or spreader equipment. This dataset shows the recent path of vehicles that have been dispatched to respond to the winter weather event within the last 3 hours.

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
series e:tm4s-nafj d:2017-04-20T14:29:42.000Z t:shape.longitude=-122.34227899999996 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=17 t:plow_state=U t:subtype="Plow Truck With Salt Spreader" t:shape.latitude=47.722863000000075 t:objectid=1699848 t:loadts="2017-04-20 14:29:45.515481-07" t:assettype=Standard t:heading=S m:fleet=32305 m:speedmph=0 m:odometer=13184.1 m:reasons=512 m:distancetraveled=0.2

series e:tm4s-nafj d:2017-04-20T14:29:43.000Z t:shape.longitude=-122.34228199999995 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=17 t:plow_state=U t:subtype="Plow Truck With Salt Spreader" t:shape.latitude=47.72239200000007 t:objectid=1699849 t:loadts="2017-04-20 14:29:47.718231-07" t:assettype=Standard t:heading=S m:fleet=32305 m:speedmph=5.8 m:odometer=13184.1 m:reasons=1024 m:distancetraveled=0.2

series e:tm4s-nafj d:2017-04-20T14:29:48.000Z t:shape.longitude=-122.34228199999995 t:spreader_on=N t:shape.needs_recoding=false t:subtypeid=17 t:plow_state=U t:subtype="Plow Truck With Salt Spreader" t:shape.latitude=47.72237100000007 t:objectid=1699850 t:loadts="2017-04-20 14:29:48.996271-07" t:assettype=Standard t:heading=S m:fleet=32305 m:speedmph=0 m:odometer=13184.1 m:reasons=512 m:distancetraveled=0.2
```

## Meta Commands

```ls
metric m:fleet p:integer l:FLEET d:FLEET t:dataTypeName=number

metric m:speedmph p:float l:SPEEDMPH d:SPEEDMPH t:dataTypeName=number

metric m:reasons p:integer l:REASONS d:REASONS t:dataTypeName=number

metric m:distancetraveled p:float l:DISTANCETRAVELED d:DISTANCETRAVELED t:dataTypeName=number

metric m:odometer p:float l:ODOMETER d:ODOMETER t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

entity e:tm4s-nafj l:"SDOT Storm Response Last 3 Hours" t:url=https://data.seattle.gov/api/views/tm4s-nafj

property e:tm4s-nafj t:meta.view v:id=tm4s-nafj v:averageRating=0 v:name="SDOT Storm Response Last 3 Hours"

property e:tm4s-nafj t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:tm4s-nafj t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | fleet | id  | assettype | subtype                       | subtypeid | datetimestamp | speedmph                                              | heading | reasons | distancetraveled                                         | odometer                                      | loadts                        | spreader_on | plow_state | shape                                                                                                                                                         | shape_len | 
| ======== | ===== | === | ========= | ============================= | ========= | ============= | ===================================================== | ======= | ======= | ======================================================== | ============================================= | ============================= | =========== | ========== | ============================================================================================================================================================= | ========= | 
| 1699848  | 32305 | 98  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698582    | 0                                                     | S       | 512     | 0.200000000000000011102230246251565404236316680908203125 | 13184.100000000000363797880709171295166015625 | 2017-04-20 14:29:45.515481-07 | N           | U          | [null, 47.722863000000075, -122.34227899999996, null, false, {paths=[[[-122.34227899999996, 47.722863000000075], [-122.34228199999995, 47.72239200000007]]]}] |           | 
| 1699849  | 32305 | 98  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698583    | 5.79999999999999982236431605997495353221893310546875  | S       | 1024    | 0.200000000000000011102230246251565404236316680908203125 | 13184.100000000000363797880709171295166015625 | 2017-04-20 14:29:47.718231-07 | N           | U          | [null, 47.72239200000007, -122.34228199999995, null, false, {paths=[[[-122.34228199999995, 47.72239200000007], [-122.34228199999995, 47.72237100000007]]]}]   |           | 
| 1699850  | 32305 | 98  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698588    | 0                                                     | S       | 512     | 0.200000000000000011102230246251565404236316680908203125 | 13184.100000000000363797880709171295166015625 | 2017-04-20 14:29:48.996271-07 | N           | U          | [null, 47.72237100000007, -122.34228199999995, null, false, {paths=[[[-122.34228199999995, 47.72237100000007], [-122.34227599999997, 47.72229900000008]]]}]   |           | 
| 1699851  | 32305 | 98  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698590    | 8.5999999999999996447286321199499070644378662109375   | S       | 1024    | 0.200000000000000011102230246251565404236316680908203125 | 13184.100000000000363797880709171295166015625 | 2017-04-20 14:29:51.571946-07 | N           | U          | [null, 47.72229900000008, -122.34227599999997, null, false, {paths=[[[-122.34227599999997, 47.72229900000008], [-122.34227899999996, 47.72225400000008]]]}]   |           | 
| 1699859  | 33664 | 143 | Standard  | Plow Truck With Salt Spreader | 17        | 1492698587    | 18.400000000000002131628207280300557613372802734375   | N       | 2048    | 0.5                                                      | 17525.9000000000014551915228366851806640625   | 2017-04-20 14:30:06.835821-07 | N           | U          | [null, 47.65818100000007, -122.32085599999999, null, false, {paths=[[[-122.32085599999999, 47.65818100000007], [-122.32083799999998, 47.66009200000008]]]}]   |           | 
| 1699860  | 33664 | 143 | Standard  | Plow Truck With Salt Spreader | 17        | 1492698596    | 11.7000000000000010658141036401502788066864013671875  | N       | 2048    | 0.5                                                      | 17526                                         | 2017-04-20 14:30:06.835821-07 | N           | U          | [null, 47.66009200000008, -122.32083799999998, null, false, {paths=[[[-122.32083799999998, 47.66009200000008], [-122.32079299999998, 47.66076700000008]]]}]   |           | 
| 1699861  | 33664 | 143 | Standard  | Plow Truck With Salt Spreader | 17        | 1492698604    | 0                                                     | NNW     | 512     | 0.5                                                      | 17526                                         | 2017-04-20 14:30:06.835821-07 | N           | U          | [null, 47.66076700000008, -122.32079299999998, null, false, {paths=[[[-122.32079299999998, 47.66076700000008], [-122.32078699999994, 47.66097400000007]]]}]   |           | 
| 1699862  | 33664 | 143 | Standard  | Plow Truck With Salt Spreader | 17        | 1492698624    | 6.60000000000000053290705182007513940334320068359375  | N       | 1024    | 0.5                                                      | 17526                                         | 2017-04-20 14:30:27.270975-07 | N           | U          | [null, 47.66097400000007, -122.32078699999994, null, false, {paths=[[[-122.32078699999994, 47.66097400000007], [-122.32079199999998, 47.66101500000008]]]}]   |           | 
| 1699882  | 25573 | 23  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698591    | 3.899999999999999911182158029987476766109466552734375 | SSE     | 1024    | 0                                                        | 3369.8000000000001818989403545856475830078125 | 2017-04-20 14:29:54.175507-07 | N           | U          | [null, 47.690278000000035, -122.40195799999998, null, false, {paths=[[[-122.40195799999998, 47.690278000000035], [-122.40187499999996, 47.69026100000008]]]}] |           | 
| 1699883  | 25573 | 23  | Standard  | Plow Truck With Salt Spreader | 17        | 1492698606    | 0                                                     | NNW     | 512     | 0                                                        | 3369.8000000000001818989403545856475830078125 | 2017-04-20 14:30:07.557125-07 | N           | U          | [null, 47.69026100000008, -122.40187499999996, null, false, {paths=[[[-122.40187499999996, 47.69026100000008], [-122.401862, 47.690462000000025]]]}]          |           | 
```