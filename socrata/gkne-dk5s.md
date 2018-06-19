# TLC Taxi Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-taxi-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gkne-dk5s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gkne-dk5s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gkne-dk5s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gkne-dk5s |
| Name | TLC Taxi Data |
| Created | 2015-06-03T06:28:44Z |
| Publication Date | 2016-02-18T23:44:23Z |

## Description

TLC Taxi Data

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | vendor_id          | vendor_id          | text          | text          |
| Yes      | time           | pickup_datetime    | pickup_datetime    | calendar_date | calendar_date |
| No       |                | dropoff_datetime   | dropoff_datetime   | calendar_date | calendar_date |
| Yes      | numeric metric | passenger_count    | passenger_count    | number        | number        |
| Yes      | numeric metric | trip_distance      | trip_distance      | number        | number        |
| No       |                | pickup_longitude   | pickup_longitude   | number        | number        |
| No       |                | pickup_latitude    | pickup_latitude    | number        | number        |
| Yes      | series tag     | store_and_fwd_flag | store_and_fwd_flag | text          | text          |
| No       |                | dropoff_longitude  | dropoff_longitude  | number        | number        |
| No       |                | dropoff_latitude   | dropoff_latitude   | number        | number        |
| Yes      | series tag     | payment_type       | payment_type       | text          | text          |
| Yes      | numeric metric | fare_amount        | fare_amount        | number        | number        |
| Yes      | numeric metric | mta_tax            | mta_tax            | number        | number        |
| Yes      | numeric metric | tip_amount         | tip_amount         | number        | number        |
| Yes      | numeric metric | tolls_amount       | tolls_amount       | number        | number        |
| Yes      | numeric metric | total_amount       | total_amount       | number        | number        |
| Yes      | numeric metric | imp_surcharge      | imp_surcharge      | number        | number        |
| Yes      | numeric metric | extra              | extra              | number        | number        |
| Yes      | series tag     | rate_code          | rate_code          | text          | text          |
```

## Time Field

```ls
Value = pickup_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dropoff_datetime,pickup_longitude,pickup_latitude,dropoff_longitude,dropoff_latitude
```

## Data Commands

```ls
series e:gkne-dk5s d:2014-05-19T13:51:00.000Z t:rate_code=1 t:vendor_id=VTS t:payment_type=CRD m:mta_tax=0.5 m:total_amount=6.5 m:fare_amount=5 m:passenger_count=6 m:trip_distance=0.82 m:tolls_amount=0 m:tip_amount=1 m:imp_surcharge=0

series e:gkne-dk5s d:2014-07-04T19:28:00.000Z t:rate_code=1 t:vendor_id=VTS t:payment_type=CRD m:mta_tax=0.5 m:total_amount=5.3 m:fare_amount=4 m:passenger_count=1 m:trip_distance=0.43 m:tolls_amount=0 m:tip_amount=0.8 m:imp_surcharge=0

series e:gkne-dk5s d:2014-12-06T05:24:00.000Z t:rate_code=1 t:vendor_id=VTS t:payment_type=CRD m:mta_tax=0.5 m:total_amount=11.5 m:fare_amount=10.5 m:passenger_count=2 m:trip_distance=2.58 m:tolls_amount=0 m:tip_amount=0 m:imp_surcharge=0.5
```

## Meta Commands

```ls
metric m:passenger_count p:long l:passenger_count d:"The number of passengers in the vehicle. This is a driver-entered value." t:dataTypeName=number

metric m:trip_distance p:long l:trip_distance d:"The elapsed trip distance in miles reported by the taximeter." t:dataTypeName=number

metric m:fare_amount p:long l:fare_amount d:"The time-and-distance fare calculated by the meter." t:dataTypeName=number

metric m:mta_tax p:long l:mta_tax d:"$0.50 MTA tax that is automatically triggered based on the metered rate in use." t:dataTypeName=number

metric m:tip_amount p:long l:tip_amount d:"Tip amount ? This field is automatically populated for credit card tips. Cash tips are not included." t:dataTypeName=number

metric m:tolls_amount p:long l:tolls_amount d:"Total amount of all tolls paid in trip." t:dataTypeName=number

metric m:total_amount p:long l:total_amount d:"The total amount charged to passengers. Does not include cash tips." t:dataTypeName=number

metric m:imp_surcharge p:long l:imp_surcharge d:"$0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015." t:dataTypeName=number

metric m:extra p:long l:extra d:"Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges." t:dataTypeName=number

entity e:gkne-dk5s l:"TLC Taxi Data" t:url=https://data.cityofnewyork.us/api/views/gkne-dk5s

property e:gkne-dk5s t:meta.view v:id=gkne-dk5s v:averageRating=0 v:name="TLC Taxi Data"

property e:gkne-dk5s t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gkne-dk5s t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| vendor_id | pickup_datetime     | dropoff_datetime    | passenger_count | trip_distance       | pickup_longitude    | pickup_latitude    | store_and_fwd_flag | dropoff_longitude   | dropoff_latitude   | payment_type | fare_amount | mta_tax | tip_amount          | tolls_amount       | total_amount       | imp_surcharge | extra | rate_code | 
| ========= | =================== | =================== | =============== | =================== | =================== | ================== | ================== | =================== | ================== | ============ | =========== | ======= | =================== | ================== | ================== | ============= | ===== | ========= | 
| VTS       | 2014-05-19T13:51:00 | 2014-05-19T13:56:00 | 6               | 0.81999999999999995 | -74.005457000000007 | 40.74586           |                    | -74.003832000000003 | 40.737997          | CRD          | 5           | 0.5     | 1                   | 0                  | 6.5                | 0             |       | 1         | 
| VTS       | 2014-07-04T19:28:00 | 2014-07-04T19:30:00 | 1               | 0.42999999999999999 | -73.984737999999993 | 40.728116999999997 |                    | -73.989796999999996 | 40.731074999999997 | CRD          | 4           | 0.5     | 0.80000000000000004 | 0                  | 5.2999999999999998 | 0             |       | 1         | 
| VTS       | 2014-12-06T05:24:00 | 2014-12-06T05:35:00 | 2               | 2.5800000000000001  | -73.906306999999998 | 40.773097999999997 |                    | -73.932500000000005 | 40.745507000000003 | CRD          | 10.5        | 0.5     | 0                   | 0                  | 11.5               | 0.5           |       | 1         | 
| VTS       | 2014-04-07T12:18:00 | 2014-04-07T12:30:00 | 1               | 1.3700000000000001  | -74.005302          | 40.740327000000001 |                    | -73.993700000000004 | 40.727336999999999 | CRD          | 9           | 0.5     | 2.25                | 0                  | 11.75              | 0             |       | 1         | 
| CMT       | 2014-04-29T01:16:46 | 2014-04-29T01:32:27 | 1               | 7.7000000000000002  | -73.979101          | 40.752353999999997 | Y                  | -73.871727000000007 | 40.740039000000003 | CRD          | 23          | 0.5     | 5.8600000000000003  | 5.3300000000000001 | 35.189999999999998 | 0.5           |       | 1         | 
| VTS       | 2014-12-07T08:42:00 | 2014-12-07T08:50:00 | 1               | 2.1000000000000001  | -73.976808000000005 | 40.762362000000003 |                    | -74.003337999999999 | 40.755572000000001 | CRD          | 9           | 0.5     | 1.8                 | 0                  | 11.300000000000001 | 0             |       | 1         | 
| CMT       | 2014-02-11T18:40:21 | 2014-02-11T18:57:11 | 1               | 2.2000000000000002  | -73.969425000000001 | 40.763584000000002 | N                  | -73.981014999999999 | 40.787759000000001 | CSH          | 12.5        | 0.5     | 0                   | 0                  | 14                 | 1             |       | 1         | 
| CMT       | 2014-06-12T09:52:56 | 2014-06-12T10:05:26 | 1               | 4.5                 | -73.982733999999994 | 40.727266999999998 | Y                  | -73.990582000000003 | 40.702959999999997 | CRD          | 15.5        | 0.5     | 2                   | 0                  | 18                 | 0             |       | 1         | 
| CMT       | 2014-05-10T15:59:51 | 2014-05-10T16:07:13 | 1               | 1.8                 | -73.970243999999994 | 40.794302000000002 | N                  | -73.951858000000001 | 40.814596000000002 | CRD          | 8           | 0.5     | 2.1200000000000001  | 0                  | 10.619999999999999 | 0             |       | 1         | 
| VTS       | 2014-07-15T01:10:00 | 2014-07-15T01:26:00 | 1               | 6.6600000000000001  | -73.942407000000003 | 40.794581999999998 |                    | -73.850656999999998 | 40.836500000000001 | CSH          | 20.5        | 0.5     | 0                   | 0                  | 21.5               | 0.5           |       | 1         | 
```