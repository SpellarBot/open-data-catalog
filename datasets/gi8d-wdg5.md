# 2015 Green Taxi Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-green-taxi-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gi8d-wdg5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gi8d-wdg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gi8d-wdg5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gi8d-wdg5 |
| Name | 2015 Green Taxi Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2015-08-07T14:50:12Z |
| Publication Date | 2016-12-12T17:07:27Z |

## Description

This dataset includes trip records from all trips completed in green taxis in NYC in 2015. Records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Livery Passenger Enhancement Program (LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | vendorid              | vendorid              | text          | text          |
| Yes      | time           | lpep_pickup_datetime  | pickup_datetime       | calendar_date | calendar_date |
| No       |                | lpep_dropoff_datetime | dropoff_datetime      | calendar_date | calendar_date |
| Yes      | series tag     | store_and_fwd_flag    | Store_and_fwd_flag    | text          | text          |
| Yes      | series tag     | ratecodeid            | rate_code             | text          | number        |
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
| Yes      | numeric metric | improvement_surcharge | Improvement_surcharge | number        | number        |
| Yes      | numeric metric | total_amount          | Total_amount          | number        | number        |
| Yes      | series tag     | payment_type          | Payment_type          | text          | number        |
| Yes      | series tag     | trip_type             | Trip_type             | text          | number        |
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
series e:gi8d-wdg5 d:2015-01-23T15:53:56.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=4.8 m:fare_amount=4 m:passenger_count=1 m:extra=0 m:trip_distance=0.59 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-01-23T15:47:40.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=8.3 m:fare_amount=7.5 m:passenger_count=1 m:extra=0 m:trip_distance=1.33 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-01-23T15:45:47.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=9.8 m:fare_amount=9 m:passenger_count=1 m:extra=0 m:trip_distance=2.01 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_count d:"The number of passengers in the vehicle. This is a driver-entered value." t:dataTypeName=number

metric m:trip_distance p:float l:Trip_distance d:"The elapsed trip distance in miles reported by the taximeter." t:dataTypeName=number

metric m:fare_amount p:float l:Fare_amount d:"The time-and-distance fare calculated by the meter. Extra Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges." t:dataTypeName=number

metric m:extra p:double l:Extra t:dataTypeName=number

metric m:mta_tax p:float l:MTA_tax d:"$0.50 MTA tax that is automatically triggered based on the metered rate in use." t:dataTypeName=number

metric m:tip_amount p:float l:Tip_amount d:"Tip amount – This field is automatically populated for credit card tips. Cash tips are not included." t:dataTypeName=number

metric m:tolls_amount p:float l:Tolls_amount d:"Total amount of all tolls paid in trip." t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:improvement_surcharge p:float l:Improvement_surcharge d:"$0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015." t:dataTypeName=number

metric m:total_amount p:double l:Total_amount d:"The total amount charged to passengers. Does not include cash tips." t:dataTypeName=number

entity e:gi8d-wdg5 l:"2015 Green Taxi Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/gi8d-wdg5

property e:gi8d-wdg5 t:meta.view v:id=gi8d-wdg5 v:category=Transportation v:averageRating=0 v:name="2015 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:gi8d-wdg5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gi8d-wdg5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude    | pickup_latitude    | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | improvement_surcharge | total_amount | payment_type | trip_type | 
| ======== | ==================== | ===================== | ================== | ========== | =================== | ================== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ===================== | ============ | ============ | ========= | 
| 2        | 2015-01-23T15:53:56  | 2015-01-23T15:55:48   | N                  | 1          | -73.9547119140625   | 40.789318084716797 | -73.964210510253906 | 40.792385101318359 | 1               | 0.59          | 4           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 4.8          | 2            | 1         | 
| 2        | 2015-01-23T15:47:40  | 2015-01-23T15:55:38   | N                  | 1          | -73.953079223632812 | 40.788677215576172 | -73.939826965332031 | 40.80352783203125  | 1               | 1.33          | 7.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 8.3          | 2            | 1         | 
| 2        | 2015-01-23T15:45:47  | 2015-01-23T15:56:09   | N                  | 1          | -73.917625427246094 | 40.743747711181641 | -73.913246154785156 | 40.757972717285156 | 1               | 2.01          | 9           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 9.8          | 2            | 1         | 
| 2        | 2015-01-23T15:52:07  | 2015-01-23T15:56:12   | N                  | 1          | -73.966560363769531 | 40.8043212890625   | -73.959495544433594 | 40.809558868408203 | 1               | 0.63          | 5           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 5.8          | 2            | 1         | 
| 2        | 2015-01-23T15:48:09  | 2015-01-23T15:56:05   | N                  | 1          | -73.922103881835938 | 40.664237976074219 | -73.930206298828125 | 40.65997314453125  | 1               | 0.79          | 5.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 6.3          | 2            | 1         | 
| 2        | 2015-01-23T15:51:51  | 2015-01-23T15:55:14   | N                  | 1          | -73.957038879394531 | 40.812507629394531 | -73.9620361328125   | 40.804695129394531 | 5               | 0.64          | 4.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 5.3          | 2            | 1         | 
| 1        | 2015-01-23T15:37:16  | 2015-01-23T15:47:08   | N                  | 1          | -73.921928405761719 | 40.75531005859375  | -73.911544799804688 | 40.764133453369141 | 1               | 0.90          | 8           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 8.8          | 2            | 1         | 
| 1        | 2015-01-23T15:36:44  | 2015-01-23T16:02:23   | N                  | 1          | -73.964256286621094 | 40.807872772216797 | -73.978340148925781 | 40.764137268066406 | 1               | 3.40          | 18          | 0     | 0.5     | 2          | 0            |           | 0.3                   | 20.8         | 1            | 1         | 
| 1        | 2015-01-23T15:36:36  | 2015-01-23T15:51:03   | N                  | 1          | -73.954933166503906 | 40.789119720458984 | -73.984840393066406 | 40.769317626953125 | 1               | 2.70          | 12          | 0     | 0.5     | 3.2        | 0            |           | 0.3                   | 16           | 1            | 1         | 
| 1        | 2015-01-23T15:35:39  | 2015-01-23T15:55:59   | N                  | 1          | -73.884445190429688 | 40.747554779052734 | -73.830497741699219 | 40.764705657958984 | 1               | 3.60          | 16          | 0     | 0.5     | 0          | 0            |           | 0.3                   | 16.8         | 1            | 1         | 
```