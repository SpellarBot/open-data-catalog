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
series e:gi8d-wdg5 d:2015-02-04T18:32:35.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=7.3 m:fare_amount=5.5 m:passenger_count=1 m:extra=1 m:trip_distance=0.76 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-02-15T17:00:48.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=8.76 m:fare_amount=6.5 m:passenger_count=1 m:extra=0 m:trip_distance=1.36 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=1.46

series e:gi8d-wdg5 d:2015-02-24T19:05:11.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=8.8 m:fare_amount=7 m:passenger_count=1 m:extra=1 m:trip_distance=1.33 m:tolls_amount=0 m:improvement_surcharge=0.3 m:tip_amount=0
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
| 2        | 2015-02-04T18:32:35  | 2015-02-04T18:38:06   | N                  | 1          | -73.925483703613281 | 40.827888488769531 | -73.926124572753906 | 40.833690643310547 | 1               | 0.76          | 5.5         | 1     | 0.5     | 0          | 0            |           | 0.3                   | 7.3          | 2            | 1         | 
| 2        | 2015-02-15T17:00:48  | 2015-02-15T17:06:03   | N                  | 1          | -73.950607299804687 | 40.666759490966797 | -73.953804016113281 | 40.683231353759766 | 1               | 1.36          | 6.5         | 0     | 0.5     | 1.46       | 0            |           | 0.3                   | 8.76         | 1            | 1         | 
| 2        | 2015-02-24T19:05:11  | 2015-02-24T19:11:54   | N                  | 1          | -73.952392578125    | 40.810981750488281 | -73.94189453125     | 40.826408386230469 | 1               | 1.33          | 7           | 1     | 0.5     | 0          | 0            |           | 0.3                   | 8.8          | 2            | 1         | 
| 1        | 2015-02-15T22:46:04  | 2015-02-15T22:57:52   | N                  | 5          | -73.882484436035156 | 40.750133514404297 | -73.852043151855469 | 40.741252899169922 | 2               | 2.1           | 0           | 0     | 0       | 0          | 0            |           | 0                     | 0            | 2            | 2         | 
| 2        | 2015-02-04T06:43:40  | 2015-02-04T06:46:32   | N                  | 1          | -73.992988586425781 | 40.701103210449219 | -73.99688720703125  | 40.697425842285156 | 1               | 0.66          | 4.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 5.3          | 2            | 1         | 
| 1        | 2015-02-23T14:25:38  | 2015-02-23T14:34:06   | N                  | 1          | -73.999862670898438 | 40.693393707275391 | -73.991424560546875 | 40.700824737548828 | 1               | 1             | 7.5         | 0     | 0.5     | 1.65       | 0            |           | 0.3                   | 9.95         | 1            | 1         | 
| 2        | 2015-02-04T01:27:59  | 2015-02-04T01:31:13   | N                  | 5          | -73.938522338867188 | 40.684654235839844 | -73.938941955566406 | 40.680850982666016 | 1               | 0.5           | 7           | 0     | 0       | 0          | 0            |           | 0                     | 7            | 2            | 2         | 
| 2        | 2015-02-12T06:56:53  | 2015-02-12T07:02:33   | N                  | 1          | -73.946563720703125 | 40.800746917724609 | -73.953582763671875 | 40.816207885742188 | 1               | 1.52          | 7           | 0     | 0.5     | 1.56       | 0            |           | 0.3                   | 9.36         | 1            | 1         | 
| 2        | 2015-02-06T03:09:21  | 2015-02-06T03:17:56   | N                  | 1          | -73.919670104980469 | 40.75921630859375  | -73.907554626464844 | 40.736862182617188 | 1               | 2.07          | 8.5         | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 9.8          | 2            | 1         | 
| 2        | 2015-02-15T14:02:28  | 2015-02-15T14:06:32   | N                  | 1          | -73.958282470703125 | 40.710411071777344 | -73.962104797363281 | 40.717792510986328 | 1               | 0.69          | 4.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 5.3          | 1            | 1         | 
```