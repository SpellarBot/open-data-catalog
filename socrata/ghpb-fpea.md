# 2013 Green Taxi Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-green-taxi-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ghpb-fpea) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ghpb-fpea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ghpb-fpea/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ghpb-fpea |
| Name | 2013 Green Taxi Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2015-10-09T00:05:02Z |
| Publication Date | 2015-10-15T18:32:25Z |

## Description

This dataset includes trip records from all trips completed in green taxis in NYC in 2013. Records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Livery Passenger Enhancement Program (LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name               | Data Type     | Render Type   |
| ======== | ============== | ===================== | ================== | ============= | ============= |
| Yes      | time           | lpep_pickup_datetime  | pickup_datetime    | calendar_date | calendar_date |
| No       |                | lpep_dropoff_datetime | dropoff_datetime   | calendar_date | calendar_date |
| Yes      | series tag     | store_and_fwd_flag    | Store_and_fwd_flag | text          | text          |
| Yes      | series tag     | ratecodeid            | rate_code          | text          | number        |
| No       |                | dropoff_latitude      | Dropoff_latitude   | number        | number        |
| Yes      | numeric metric | passenger_count       | Passenger_count    | number        | number        |
| Yes      | numeric metric | trip_distance         | Trip_distance      | number        | number        |
| Yes      | numeric metric | fare_amount           | Fare_amount        | number        | number        |
| Yes      | numeric metric | extra                 | Extra              | number        | number        |
| Yes      | numeric metric | mta_tax               | MTA_tax            | number        | number        |
| Yes      | numeric metric | tip_amount            | Tip_amount         | number        | number        |
| Yes      | numeric metric | tolls_amount          | Tolls_amount       | number        | number        |
| Yes      | numeric metric | ehail_fee             | Ehail_fee          | number        | number        |
| Yes      | numeric metric | total_amount          | Total_amount       | number        | number        |
| Yes      | series tag     | payment_type          | Payment_type       | text          | number        |
| Yes      | series tag     | trip_type             | Trip_type          | text          | number        |
| No       |                | pickup_longitude      | Pickup_longitude   | number        | number        |
| No       |                | pickup_latitude       | Pickup_latitude    | number        | number        |
| No       |                | dropoff_longitude     | Dropoff_longitude  | number        | number        |
| Yes      | series tag     | vendorid              | vendor_id          | text          | text          |
```

## Time Field

```ls
Value = lpep_pickup_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lpep_dropoff_datetime,dropoff_latitude,pickup_longitude,pickup_latitude,dropoff_longitude
```

## Data Commands

```ls
series e:ghpb-fpea d:2013-12-06T12:11:05.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=4.5 m:fare_amount=4 m:passenger_count=1 m:extra=0 m:tolls_amount=0 m:trip_distance=0.5 m:tip_amount=0

series e:ghpb-fpea d:2013-11-23T01:31:07.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:payment_type=1 m:mta_tax=0.5 m:total_amount=53.5 m:fare_amount=52.5 m:passenger_count=5 m:extra=0.5 m:tolls_amount=0 m:trip_distance=14.16 m:tip_amount=0

series e:ghpb-fpea d:2013-12-13T10:26:02.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=5.5 m:fare_amount=5 m:passenger_count=1 m:extra=0 m:tolls_amount=0 m:trip_distance=0.6 m:tip_amount=0
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_count t:dataTypeName=number

metric m:trip_distance p:double l:Trip_distance t:dataTypeName=number

metric m:fare_amount p:float l:Fare_amount t:dataTypeName=number

metric m:extra p:float l:Extra t:dataTypeName=number

metric m:mta_tax p:double l:MTA_tax t:dataTypeName=number

metric m:tip_amount p:double l:Tip_amount t:dataTypeName=number

metric m:tolls_amount p:double l:Tolls_amount t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:total_amount p:float l:Total_amount t:dataTypeName=number

entity e:ghpb-fpea l:"2013 Green Taxi Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/ghpb-fpea

property e:ghpb-fpea t:meta.view v:id=ghpb-fpea v:category=Transportation v:averageRating=0 v:name="2013 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:ghpb-fpea t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ghpb-fpea t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | total_amount | payment_type | trip_type | pickup_longitude    | pickup_latitude    | dropoff_longitude   | vendorid | 
| ==================== | ===================== | ================== | ========== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ============ | ============ | ========= | =================== | ================== | =================== | ======== | 
| 2013-12-06T12:11:05  | 2013-12-06T12:14:06   | N                  | 1          | 40.811981201171875 | 1               | 0.5           | 4           | 0     | 0.5     | 0          | 0            |           | 4.5          | 2            |           | -73.965065002441406 | 40.806140899658203 | -73.962234497070312 | 1        | 
| 2013-11-23T01:31:07  | 2013-11-23T02:36:01   | N                  | 1          | 40.591175079345703 | 5               | 14.16         | 52.5        | 0.5   | 0.5     | 0          | 0            |           | 53.5         | 1            |           | -73.958465576171875 | 40.719093322753906 | -73.965423583984375 | 2        | 
| 2013-12-13T10:26:02  | 2013-12-13T10:30:26   | N                  | 1          | 40.807601928710937 | 1               | 0.6           | 5           | 0     | 0.5     | 0          | 0            |           | 5.5          | 2            |           | -73.923065185546875 | 40.813323974609375 | -73.924156188964844 | 1        | 
| 2013-10-05T11:19:04  | 2013-10-05T11:29:47   | N                  | 1          | 40.804969787597656 | 1               | 1.84          | 9.5         | 0     | 0.5     | 2          | 0            |           | 12           | 1            | 1         | -73.964912414550781 | 40.806842803955078 | -73.939010620117188 | 2        | 
| 2013-12-12T13:33:58  | 2013-12-12T13:42:23   | N                  | 1          | 40.835029602050781 | 1               | 1.69          | 8.5         | 0     | 0.5     | 0          | 0            |           | 9            | 2            |           | -73.902473449707031 | 40.838836669921875 | -73.926017761230469 | 2        | 
| 2013-11-24T03:46:53  | 2013-11-24T04:12:53   | N                  | 1          | 40.779762268066406 | 5               | 6.71          | 24.5        | 0.5   | 0.5     | 6.25       | 0            |           | 31.75        | 1            |           | -73.951698303222656 | 40.714801788330078 | -73.978286743164063 | 2        | 
| 2013-11-24T10:08:48  | 2013-11-24T10:30:45   | N                  | 1          | 40.750179290771484 | 1               | 5.3           | 19.5        | 0     | 0.5     | 4          | 0            |           | 24           | 1            |           | -73.959953308105469 | 40.808113098144531 | -73.973030090332031 | 1        | 
| 2013-10-31T23:44:01  | 2013-10-31T23:46:20   | N                  | 1          | 40.773761749267578 | 1               | 0.5           | 4           | 0.5   | 0.5     | 0          | 0            |           | 5            | 2            |           | -73.918075561523438 | 40.770259857177734 | -73.924652099609375 | 2        | 
| 2013-10-29T03:28:11  | 2013-10-29T03:31:18   | N                  | 1          | 40.807548522949219 | 1               | 0.59          | 4.5         | 0.5   | 0.5     | 0          | 0            |           | 5.5          | 2            |           | -73.945472717285156 | 40.807971954345703 | -73.95086669921875  | 2        | 
| 2013-11-22T21:03:19  | 2013-11-22T21:13:58   | N                  | 1          | 40.734340667724609 | 1               | 2.32          | 10          | 0.5   | 0.5     | 0          | 0            |           | 11           | 2            |           | -73.853248596191406 | 40.727012634277344 | -73.824226379394531 | 2        | 
```