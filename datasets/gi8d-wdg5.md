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
| Rows Updated | 2016-12-14T03:36:41Z |

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
| Yes      | numeric metric | ratecodeid            | rate_code             | number        | number        |
| Yes      | numeric metric | pickup_longitude      | Pickup_longitude      | number        | number        |
| Yes      | numeric metric | pickup_latitude       | Pickup_latitude       | number        | number        |
| Yes      | numeric metric | dropoff_longitude     | Dropoff_longitude     | number        | number        |
| Yes      | numeric metric | dropoff_latitude      | Dropoff_latitude      | number        | number        |
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
Excluded Fields = lpep_dropoff_datetime
```

## Data Commands

```ls
series e:gi8d-wdg5 d:2015-02-17T17:51:35.000Z t:store_and_fwd_flag=N t:vendorid=1 t:trip_type=2 t:payment_type=2 m:mta_tax=0 m:total_amount=7 m:ratecodeid=5 m:extra=0 m:pickup_longitude=-73.92123 m:trip_distance=1.8 m:tolls_amount=0 m:fare_amount=7 m:passenger_count=0 m:dropoff_longitude=-73.9064 m:pickup_latitude=40.83398 m:improvement_surcharge=0 m:dropoff_latitude=40.85239 m:tip_amount=0

series e:gi8d-wdg5 d:2015-02-06T16:39:02.000Z t:store_and_fwd_flag=N t:vendorid=2 t:trip_type=1 t:payment_type=2 m:mta_tax=0.5 m:total_amount=10.3 m:ratecodeid=1 m:extra=1 m:pickup_longitude=-73.88423 m:trip_distance=1.33 m:tolls_amount=0 m:fare_amount=8.5 m:passenger_count=2 m:dropoff_longitude=-73.9009 m:pickup_latitude=40.74755 m:improvement_surcharge=0.3 m:dropoff_latitude=40.74328 m:tip_amount=0

series e:gi8d-wdg5 d:2015-02-14T19:06:47.000Z t:store_and_fwd_flag=N t:vendorid=2 t:trip_type=1 t:payment_type=1 m:mta_tax=0.5 m:total_amount=20.16 m:ratecodeid=1 m:extra=0 m:pickup_longitude=-73.94138 m:trip_distance=4.7 m:tolls_amount=0 m:fare_amount=16 m:passenger_count=1 m:dropoff_longitude=-73.97112 m:pickup_latitude=40.84192 m:improvement_surcharge=0.3 m:dropoff_latitude=40.79348 m:tip_amount=3.36
```

## Meta Commands

```ls
metric m:ratecodeid p:integer l:rate_code d:"The final rate code in effect at the end of the trip. 1= Standard rate 2=JFK 3=Newark 4=Nassau or Westchester 5=Negotiated fare 6=Group ride" t:dataTypeName=number

metric m:pickup_longitude p:double l:Pickup_longitude d:"Longitude where the meter was engaged." t:dataTypeName=number

metric m:pickup_latitude p:decimal l:Pickup_latitude d:"Latitude where the meter was engaged." t:dataTypeName=number

metric m:dropoff_longitude p:double l:Dropoff_longitude d:"Longitude where the meter was disengaged." t:dataTypeName=number

metric m:dropoff_latitude p:decimal l:Dropoff_latitude d:"Latitude where the meter was disengaged." t:dataTypeName=number

metric m:passenger_count p:integer l:Passenger_count d:"The number of passengers in the vehicle. This is a driver-entered value." t:dataTypeName=number

metric m:trip_distance p:float l:Trip_distance d:"The elapsed trip distance in miles reported by the taximeter." t:dataTypeName=number

metric m:fare_amount p:float l:Fare_amount d:"The time-and-distance fare calculated by the meter. Extra Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges." t:dataTypeName=number

metric m:extra p:double l:Extra t:dataTypeName=number

metric m:mta_tax p:float l:MTA_tax d:"$0.50 MTA tax that is automatically triggered based on the metered rate in use." t:dataTypeName=number

metric m:tip_amount p:float l:Tip_amount d:"Tip amount ? This field is automatically populated for credit card tips. Cash tips are not included." t:dataTypeName=number

metric m:tolls_amount p:float l:Tolls_amount d:"Total amount of all tolls paid in trip." t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:improvement_surcharge p:float l:Improvement_surcharge d:"$0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015." t:dataTypeName=number

metric m:total_amount p:double l:Total_amount d:"The total amount charged to passengers. Does not include cash tips." t:dataTypeName=number

entity e:gi8d-wdg5 l:"2015 Green Taxi Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/gi8d-wdg5

property e:gi8d-wdg5 t:meta.view v:id=gi8d-wdg5 v:category=Transportation v:averageRating=0 v:name="2015 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:gi8d-wdg5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:gi8d-wdg5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```