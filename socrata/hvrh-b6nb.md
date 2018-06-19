# 2016 Green Taxi Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-green-taxi-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hvrh-b6nb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hvrh-b6nb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hvrh-b6nb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hvrh-b6nb |
| Name | 2016 Green Taxi Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2016-11-30T16:35:06Z |
| Publication Date | 2017-03-15T13:57:48Z |

## Description

This dataset includes trip records from all trips completed in green taxis in NYC from January to June 2016. Records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Livery Passenger Enhancement Program (LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | vendorid              | VendorID              | text          | number        |
| Yes      | time           | lpep_pickup_datetime  | lpep_pickup_datetime  | calendar_date | calendar_date |
| No       |                | lpep_dropoff_datetime | Lpep_dropoff_datetime | calendar_date | calendar_date |
| Yes      | series tag     | store_and_fwd_flag    | Store_and_fwd_flag    | text          | text          |
| Yes      | series tag     | ratecodeid            | RateCodeID            | text          | number        |
| No       |                | pickup_longitude      | Pickup_longitude      | number        | number        |
| No       |                | pickup_latitude       | Pickup_latitude       | number        | number        |
| No       |                | dropoff_longitude     | Dropoff_longitude     | number        | number        |
| No       |                | dropoff_latitude      | Dropoff_latitude      | number        | number        |
| Yes      | numeric metric | passenger_count       | Passenger_count       | number        | number        |
| Yes      | numeric metric | trip_distance         | Trip_distance         | number        | number        |
| Yes      | numeric metric | fare_amount           | Fare_amount           | number        | number        |
| Yes      | numeric metric | extra                 | Extra                 | number        | number        |
| Yes      | numeric metric | mta_tax               | MTA_tax               | number        | number        |
| Yes      | numeric metric | tip_amount            | Tip_amount            | number        | number        |
| Yes      | numeric metric | tolls_amount          | Tolls_amount          | number        | number        |
| Yes      | numeric metric | ehail_fee             | Ehail_fee             | number        | number        |
| Yes      | numeric metric | improvement_surcharge | improvement_surcharge | number        | number        |
| Yes      | numeric metric | total_amount          | Total_amount          | number        | number        |
| Yes      | series tag     | payment_type          | Payment_type          | text          | number        |
| Yes      | series tag     | trip_type             | Trip_type             | text          | number        |
| Yes      | series tag     | pulocationid          | PULocationID          | text          | number        |
| Yes      | series tag     | dolocationid          | DOLocationID          | text          | number        |
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
series e:hvrh-b6nb d:2016-01-01T00:29:24.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=11.16 m:fare_amount=8 m:passenger_count=1 m:extra=0.5 m:trip_distance=1.46 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=1.86

series e:hvrh-b6nb d:2016-01-01T00:19:39.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=16.8 m:fare_amount=15.5 m:passenger_count=1 m:extra=0.5 m:trip_distance=3.56 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0

series e:hvrh-b6nb d:2016-01-01T00:19:33.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=22.25 m:fare_amount=16.5 m:passenger_count=1 m:extra=0.5 m:trip_distance=3.79 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=4.45
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_count t:dataTypeName=number

metric m:trip_distance p:float l:Trip_distance t:dataTypeName=number

metric m:fare_amount p:float l:Fare_amount t:dataTypeName=number

metric m:extra p:double l:Extra t:dataTypeName=number

metric m:mta_tax p:double l:MTA_tax t:dataTypeName=number

metric m:tip_amount p:double l:Tip_amount t:dataTypeName=number

metric m:tolls_amount p:float l:Tolls_amount t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:improvement_surcharge p:float l:improvement_surcharge t:dataTypeName=number

metric m:total_amount p:float l:Total_amount t:dataTypeName=number

entity e:hvrh-b6nb l:"2016 Green Taxi Trip Data" t:attribution="Taxi and Limousine  Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/hvrh-b6nb

property e:hvrh-b6nb t:meta.view v:id=hvrh-b6nb v:category=Transportation v:averageRating=0 v:name="2016 Green Taxi Trip Data" v:attribution="Taxi and Limousine  Commission (TLC)"

property e:hvrh-b6nb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hvrh-b6nb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude    | pickup_latitude    | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | improvement_surcharge | total_amount | payment_type | trip_type | pulocationid | dolocationid | 
| ======== | ==================== | ===================== | ================== | ========== | =================== | ================== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ===================== | ============ | ============ | ========= | ============ | ============ | 
| 2        | 2016-01-01T00:29:24  | 2016-01-01T00:39:36   | N                  | 1          | -73.928642272949219 | 40.680610656738281 | -73.924278259277344 | 40.698043823242188 | 1               | 1.46          | 8           | 0.5   | 0.5     | 1.86       | 0            |           | 0.3                   | 11.16        | 1            | 1         |              |              | 
| 2        | 2016-01-01T00:19:39  | 2016-01-01T00:39:18   | N                  | 1          | -73.952674865722656 | 40.723175048828125 | -73.923919677734375 | 40.761379241943359 | 1               | 3.56          | 15.5        | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 16.8         | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:19:33  | 2016-01-01T00:39:48   | N                  | 1          | -73.971611022949219 | 40.676105499267578 | -74.013160705566406 | 40.646072387695313 | 1               | 3.79          | 16.5        | 0.5   | 0.5     | 4.45       | 0            |           | 0.3                   | 22.25        | 1            | 1         |              |              | 
| 2        | 2016-01-01T00:22:12  | 2016-01-01T00:38:32   | N                  | 1          | -73.989501953125    | 40.669578552246094 | -74.000648498535156 | 40.689033508300781 | 1               | 3.01          | 13.5        | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 14.8         | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:24:01  | 2016-01-01T00:39:22   | N                  | 1          | -73.964729309082031 | 40.682853698730469 | -73.940719604492188 | 40.663013458251953 | 1               | 2.55          | 12          | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 13.3         | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:32:59  | 2016-01-01T00:39:35   | N                  | 1          | -73.891143798828125 | 40.746456146240234 | -73.867744445800781 | 40.742111206054688 | 1               | 1.37          | 7           | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 8.3          | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:34:42  | 2016-01-01T00:39:21   | N                  | 1          | -73.896675109863281 | 40.746196746826172 | -73.886192321777344 | 40.745689392089844 | 1               | 0.57          | 5           | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 6.3          | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:31:23  | 2016-01-01T00:39:36   | N                  | 1          | -73.953353881835937 | 40.803558349609375 | -73.949150085449219 | 40.794120788574219 | 1               | 1.01          | 7           | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 8.3          | 2            | 1         |              |              | 
| 2        | 2016-01-01T00:24:40  | 2016-01-01T00:39:52   | N                  | 1          | -73.994064331054688 | 40.702816009521484 | -73.971572875976562 | 40.679725646972656 | 1               | 2.46          | 12          | 0.5   | 0.5     | 2          | 0            |           | 0.3                   | 15.3         | 1            | 1         |              |              | 
| 2        | 2016-01-01T00:28:59  | 2016-01-01T00:39:23   | N                  | 1          | -73.914131164550781 | 40.756641387939453 | -73.917549133300781 | 40.739658355712891 | 1               | 1.61          | 9           | 0.5   | 0.5     | 1.6        | 0            |           | 0.3                   | 11.9         | 1            | 1         |              |              | 
```