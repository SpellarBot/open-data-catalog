# 2014 Green Taxi Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-green-taxi-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2np7-5jsg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2np7-5jsg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2np7-5jsg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2np7-5jsg |
| Name | 2014 Green Taxi Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2015-08-03T15:50:14Z |
| Publication Date | 2016-12-06T19:17:27Z |

## Description

This dataset includes trip records from all trips completed in green taxis in NYC in 2014.  Records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Livery Passenger Enhancement Program (LPEP).  The  trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name               | Data Type     | Render Type   |
| ======== | ============== | ===================== | ================== | ============= | ============= |
| Yes      | series tag     | vendorid              | vendorid           | text          | text          |
| Yes      | time           | lpep_pickup_datetime  | pickup_datetime    | calendar_date | calendar_date |
| No       |                | lpep_dropoff_datetime | dropoff_datetime   | calendar_date | calendar_date |
| Yes      | series tag     | store_and_fwd_flag    | Store_and_fwd_flag | text          | text          |
| Yes      | series tag     | ratecodeid            | rate_code          | text          | number        |
| No       |                | pickup_longitude      | Pickup_longitude   | number        | number        |
| No       |                | pickup_latitude       | Pickup_latitude    | number        | number        |
| No       |                | dropoff_longitude     | Dropoff_longitude  | number        | number        |
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
```

## Time Field

```ls
Value = lpep_pickup_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lpep_dropoff_datetime,pickup_longitude,pickup_latitude,dropoff_longitude,dropoff_latitude
```

## Data Commands

```ls
series e:2np7-5jsg d:2014-01-01T00:00:00.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:payment_type=1 m:mta_tax=0.5 m:total_amount=21 m:fare_amount=20 m:passenger_count=1 m:extra=0.5 m:trip_distance=6.47 m:tolls_amount=0 m:tip_amount=0

series e:2np7-5jsg d:2014-01-01T00:00:00.000Z t:store_and_fwd_flag=N t:ratecodeid=2 t:vendorid=2 t:payment_type=1 m:mta_tax=0.5 m:total_amount=57.83 m:fare_amount=52 m:passenger_count=1 m:extra=0 m:trip_distance=20.12 m:tolls_amount=5.33 m:tip_amount=0

series e:2np7-5jsg d:2014-01-01T00:00:00.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:payment_type=1 m:mta_tax=0.5 m:total_amount=6 m:fare_amount=5 m:passenger_count=2 m:extra=0.5 m:trip_distance=0.81 m:tolls_amount=0 m:tip_amount=0
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_count d:"The number of passengers in the vehicle. This is a driver-entered value." t:dataTypeName=number

metric m:trip_distance p:float l:Trip_distance d:"The elapsed trip distance in miles reported by the taximeter." t:dataTypeName=number

metric m:fare_amount p:double l:Fare_amount d:"The time-and-distance fare calculated by the meter. Extra Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges." t:dataTypeName=number

metric m:extra p:float l:Extra t:dataTypeName=number

metric m:mta_tax p:float l:MTA_tax d:"$0.50 MTA tax that is automatically triggered based on the metered rate in use." t:dataTypeName=number

metric m:tip_amount p:float l:Tip_amount d:"Tip amount ? This field is automatically populated for credit card tips. Cash tips are not included." t:dataTypeName=number

metric m:tolls_amount p:float l:Tolls_amount d:"Total amount of all tolls paid in trip." t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:total_amount p:float l:Total_amount t:dataTypeName=number

entity e:2np7-5jsg l:"2014 Green Taxi Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/2np7-5jsg

property e:2np7-5jsg t:meta.view v:id=2np7-5jsg v:category=Transportation v:averageRating=0 v:name="2014 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:2np7-5jsg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2np7-5jsg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude | pickup_latitude | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | total_amount | payment_type | trip_type | 
| ======== | ==================== | ===================== | ================== | ========== | ================ | =============== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ============ | ============ | ========= | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T01:08:06   | N                  | 1          | 0                | 0               | -73.865043640136719 | 40.872306823730469 | 1               | 6.47          | 20          | 0.5   | 0.5     | 0          | 0            |           | 21           | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T06:03:57   | N                  | 2          | 0                | 0               | -73.7763671875      | 40.645488739013672 | 1               | 20.12         | 52          | 0     | 0.5     | 0          | 5.33         |           | 57.83        | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T18:22:44   | N                  | 1          | 0                | 0               | -73.932647705078125 | 40.852573394775391 | 2               | 0.81          | 5           | 0.5   | 0.5     | 0          | 0            |           | 6            | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T00:52:03   | N                  | 1          | 0                | 0               | -73.99407958984375  | 40.749092102050781 | 1               | 9.55          | 33.5        | 0.5   | 0.5     | 2.17       | 5.33         |           | 42           | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T00:49:25   | N                  | 1          | 0                | 0               | -73.936065673828125 | 40.734725952148437 | 1               | 1.22          | 7           | 0.5   | 0.5     | 2          | 0            |           | 10           | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T00:01:15   | N                  | 1          | 0                | 0               | -73.912155151367188 | 40.684059143066406 | 2               | 4.27          | 17          | 0.5   | 0.5     | 0          | 0            |           | 18           | 2            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T02:37:20   | N                  | 1          | 0                | 0               | -73.935317993164063 | 40.737010955810547 | 1               | 7.50          | 40          | 0.5   | 0.5     | 0          | 0            |           | 41           | 2            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T15:24:02   | N                  | 5          | 0                | 0               | -73.937469482421875 | 40.804195404052734 | 2               | 0.02          | 18          | 0     | 0.5     | 0          | 0            |           | 18.5         | 1            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T06:11:44   | N                  | 1          | 0                | 0               | 0                   | 0                  | 5               | 3.02          | 15          | 0.5   | 0.5     | 0          | 0            |           | 16           | 2            |           | 
| 2        | 2014-01-01T00:00:00  | 2014-01-01T01:17:43   | N                  | 1          | 0                | 0               | -73.915679931640625 | 40.77630615234375  | 1               | 1.41          | 9           | 0.5   | 0.5     | 2.38       | 0            |           | 12.38        | 1            |           | 
```