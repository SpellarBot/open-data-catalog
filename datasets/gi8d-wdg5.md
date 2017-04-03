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
series e:gi8d-wdg5 d:2015-11-20T08:28:04.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=8.55 m:fare_amount=6.5 m:passenger_count=1 m:extra=0 m:trip_distance=0.99 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=1.25

series e:gi8d-wdg5 d:2015-09-04T02:53:29.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=20.8 m:fare_amount=19.5 m:passenger_count=1 m:extra=0.5 m:trip_distance=5.26 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-09-02T20:56:15.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=9.96 m:fare_amount=7 m:passenger_count=1 m:extra=0.5 m:trip_distance=1.33 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=1.66
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

property e:gi8d-wdg5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:gi8d-wdg5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude    | pickup_latitude    | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | improvement_surcharge | total_amount | payment_type | trip_type | 
| ======== | ==================== | ===================== | ================== | ========== | =================== | ================== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ===================== | ============ | ============ | ========= | 
| 2        | 2015-11-20T08:28:04  | 2015-11-20T08:35:27   | N                  | 1          | -73.902915954589844 | 40.751548767089844 | -73.886398315429687 | 40.744441986083984 | 1               | 0.99          | 6.5         | 0     | 0.5     | 1.25       | 0            |           | 0.3                   | 8.55         | 1            | 1         | 
| 2        | 2015-09-04T02:53:29  | 2015-09-04T03:15:35   | N                  | 1          | -73.958808898925781 | 40.722202301025391 | -73.924156188964844 | 40.768226623535156 | 1               | 5.26          | 19.5        | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 20.8         | 2            | 1         | 
| 2        | 2015-09-02T20:56:15  | 2015-09-02T21:03:46   | N                  | 1          | -73.988075256347656 | 40.690013885498047 | -73.9716796875      | 40.697349548339844 | 1               | 1.33          | 7           | 0.5   | 0.5     | 1.66       | 0            |           | 0.3                   | 9.96         | 1            | 1         | 
| 2        | 2015-11-26T00:23:47  | 2015-11-27T00:15:31   | N                  | 1          | -73.919349670410156 | 40.7559814453125   | -73.922393798828125 | 40.754871368408203 | 1               | 0.25          | 4           | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 5.3          | 2            | 1         | 
| 2        | 2015-06-08T03:38:45  | 2015-06-08T03:57:53   | N                  | 1          | -73.932235717773438 | 40.698329925537109 | -73.949745178222656 | 40.762264251708984 | 1               | 5.63          | 19          | 0.5   | 0.5     | 1          | 0            |           | 0.3                   | 21.3         | 1            | 1         | 
| 2        | 2015-07-27T23:20:48  | 2015-07-27T23:37:20   | N                  | 1          | -73.991607666015625 | 40.685031890869141 | -73.984649658203125 | 40.720226287841797 | 2               | 3.31          | 14.5        | 0.5   | 0.5     | 3.16       | 0            |           | 0.3                   | 18.96        | 1            | 1         | 
| 2        | 2015-05-19T11:54:55  | 2015-05-19T11:57:46   | N                  | 1          | -73.98162841796875  | 40.688091278076172 | -73.977928161621094 | 40.684215545654297 | 1               | 0.34          | 4           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 4.8          | 2            | 1         | 
| 1        | 2015-03-07T20:19:02  | 2015-03-07T20:24:18   | N                  | 1          | -73.892631530761719 | 40.868053436279297 | -73.881500244140625 | 40.874679565429687 | 1               | 1             | 5.5         | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 6.8          | 2            | 1         | 
| 2        | 2015-07-01T19:13:19  | 2015-07-01T19:49:36   | N                  | 1          | -73.921958923339844 | 40.689563751220703 | -73.924095153808594 | 40.690708160400391 | 1               | 6.78          | 26          | 1     | 0.5     | 0          | 0            |           | 0.3                   | 27.8         | 2            | 1         | 
| 2        | 2015-05-24T13:50:32  | 2015-05-24T13:56:43   | N                  | 1          | -73.871200561523438 | 40.734046936035156 | -73.86749267578125  | 40.742538452148438 | 5               | 0.87          | 6           | 0     | 0.5     | 0          | 0            |           | 0.3                   | 6.8          | 2            | 1         | 
```