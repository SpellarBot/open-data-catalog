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
series e:gi8d-wdg5 d:2015-02-25T20:14:18.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=2 t:trip_type=1 t:payment_type=2 m:fare_amount=4.5 m:total_amount=5.8 m:mta_tax=0.5 m:passenger_count=1 m:extra=0.5 m:tolls_amount=0 m:trip_distance=0.61 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-02-20T10:14:56.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=1 t:trip_type=1 t:payment_type=2 m:fare_amount=11 m:total_amount=12.3 m:mta_tax=0.5 m:passenger_count=1 m:extra=0 m:tolls_amount=0.5 m:trip_distance=2.4 m:improvement_surcharge=0.3 m:tip_amount=0

series e:gi8d-wdg5 d:2015-02-15T16:33:26.000Z t:store_and_fwd_flag=N t:ratecodeid=1 t:vendorid=1 t:trip_type=1 t:payment_type=1 m:fare_amount=12 m:total_amount=15.35 m:mta_tax=0.5 m:passenger_count=1 m:extra=0 m:tolls_amount=0 m:trip_distance=2.6 m:improvement_surcharge=0.3 m:tip_amount=2.55
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

property e:gi8d-wdg5 t:meta.view d:2017-06-09T13:54:29.918Z v:id=gi8d-wdg5 v:category=Transportation v:averageRating=0 v:name="2015 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:gi8d-wdg5 t:meta.view.owner d:2017-06-09T13:54:29.918Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:gi8d-wdg5 t:meta.view.tableauthor d:2017-06-09T13:54:29.918Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude    | pickup_latitude    | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | improvement_surcharge | total_amount | payment_type | trip_type | 
| ======== | ==================== | ===================== | ================== | ========== | =================== | ================== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ===================== | ============ | ============ | ========= | 
| 2        | 2015-02-25T20:14:18  | 2015-02-25T20:17:19   | N                  | 1          | -73.982315063476563 | 40.665901184082031 | -73.988487243652344 | 40.6591796875      | 1               | 0.61          | 4.5         | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 5.8          | 2            | 1         | 
| 1        | 2015-02-20T10:14:56  | 2015-02-20T10:28:08   | N                  | 1          | -73.921356201171875 | 40.756118774414063 | -73.955711364746094 | 40.745487213134766 | 1               | 2.4           | 11          | 0     | 0.5     | 0          | 0.5          |           | 0.3                   | 12.3         | 2            | 1         | 
| 1        | 2015-02-15T16:33:26  | 2015-02-15T16:47:22   | N                  | 1          | -73.939949035644531 | 40.841033935546875 | -73.913230895996094 | 40.829429626464844 | 1               | 2.6           | 12          | 0     | 0.5     | 2.55       | 0            |           | 0.3                   | 15.35        | 1            | 1         | 
| 2        | 2015-02-13T23:28:23  | 2015-02-14T00:00:06   | N                  | 1          | -73.956924438476563 | 40.734970092773437 | -73.927192687988281 | 40.688472747802734 | 1               | 4.67          | 21          | 0.5   | 0.5     | 1          | 0            |           | 0.3                   | 23.3         | 1            | 1         | 
| 2        | 2015-02-24T12:08:14  | 2015-02-24T12:16:05   | N                  | 1          | -73.949211120605469 | 40.807796478271484 | -73.940040588378906 | 40.825237274169922 | 1               | 1.47          | 7.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 8.3          | 2            | 1         | 
| 2        | 2015-02-10T07:42:19  | 2015-02-10T07:49:05   | N                  | 1          | -73.950942993164063 | 40.785846710205078 | -73.948814392089844 | 40.777667999267578 | 1               | 1.13          | 6.5         | 0     | 0.5     | 1.46       | 0            |           | 0.3                   | 8.76         | 1            | 1         | 
| 1        | 2015-02-02T12:14:40  | 2015-02-02T12:17:41   | N                  | 1          | -73.912078857421875 | 40.775245666503906 | -73.92010498046875  | 40.768440246582031 | 2               | 0.6           | 4.5         | 0     | 0.5     | 0          | 0            |           | 0.3                   | 5.3          | 2            | 1         | 
| 2        | 2015-02-12T20:04:41  | 2015-02-12T20:19:22   | N                  | 1          | -73.993324279785156 | 40.694541931152344 | -73.9688720703125   | 40.689491271972656 | 1               | 2.06          | 10.5        | 0.5   | 0.5     | 0          | 0            |           | 0.3                   | 11.8         | 2            | 1         | 
| 1        | 2015-02-22T08:58:55  | 2015-02-22T09:10:40   | N                  | 1          | -73.923912048339844 | 40.842796325683594 | -73.896781921386719 | 40.867279052734375 | 1               | 2.7           | 11.5        | 0     | 0.5     | 1          | 0            |           | 0.3                   | 13.3         | 1            | 1         | 
| 2        | 2015-02-06T17:41:44  | 2015-02-06T18:03:10   | N                  | 1          | -73.941329956054687 | 40.813079833984375 | -73.948585510253906 | 40.82904052734375  | 1               | 1.61          | 14          | 1     | 0.5     | 0          | 0            |           | 0.3                   | 15.8         | 2            | 1         | 
```