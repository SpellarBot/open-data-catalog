# 2016 For Hire Vehicle Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-for-hire-vehicle-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yini-w76t) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yini-w76t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yini-w76t/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yini-w76t |
| Name | 2016 For Hire Vehicle Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2016-11-30T21:53:12Z |
| Publication Date | 2017-03-13T20:50:33Z |

## Description

The For-Hire Vehicle (?FHV?) trip records include fields capturing the dispatching base license number and the pick-up date, time, and taxi zone location ID (shape file below). These records are generated from the FHV Trip Record submissions made by bases. Note: The TLC publishes base trip record data as submitted by the bases, and we cannot guarantee or confirm their accuracy or completeness. Therefore, this may not represent the total amount of trips dispatched by all TLC-licensed bases. The TLC performs routine reviews of the records and takes enforcement actions when necessary to ensure, to the extent possible, complete and accurate information.

For trip record data including TLC taxi zone location IDs, location names and corresponding boroughs for each ID can be found <a href="https://s3.amazonaws.com/nyc-tlc/misc/taxi+_zone_lookup.csv">here</a>. A shapefile containing the boundaries for the taxi zones can be found <a href="https://s3.amazonaws.com/nyc-tlc/misc/taxi_zones.zip">here</a>.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | dispatching_base_num | Dispatching_base_num | text          | text          |
| Yes      | time        | pickup_date          | Pickup_date          | calendar_date | calendar_date |
| Yes      | series tag  | locationid           | locationID           | text          | text          |
```

## Time Field

```ls
Value = pickup_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:yini-w76t d:2016-12-15T22:09:33.000Z t:locationid=234 t:dispatching_base_num=B02617 m:row_number.yini-w76t=1

series e:yini-w76t d:2016-12-15T22:09:34.000Z t:locationid=114 t:dispatching_base_num=B02617 m:row_number.yini-w76t=2

series e:yini-w76t d:2016-12-15T22:09:38.000Z t:locationid=249 t:dispatching_base_num=B02617 m:row_number.yini-w76t=3
```

## Meta Commands

```ls
metric m:row_number.yini-w76t p:long l:"Row Number"

entity e:yini-w76t l:"2016 For Hire Vehicle Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/yini-w76t

property e:yini-w76t t:meta.view v:id=yini-w76t v:category=Transportation v:averageRating=0 v:name="2016 For Hire Vehicle Trip Data" v:attribution="Taxi and Limousine Commission (TLC)"

property e:yini-w76t t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yini-w76t t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dispatching_base_num | pickup_date         | locationid | 
| ==================== | =================== | ========== | 
| B02617               | 2016-12-15T22:09:33 | 234        | 
| B02617               | 2016-12-15T22:09:34 | 114        | 
| B02617               | 2016-12-15T22:09:38 | 249        | 
| B02617               | 2016-12-15T22:09:48 | 236        | 
| B02617               | 2016-12-15T22:09:56 | 158        | 
| B02617               | 2016-12-15T22:09:58 | 138        | 
| B02617               | 2016-12-15T22:10:07 | 48         | 
| B02617               | 2016-12-15T22:10:12 | 196        | 
| B02617               | 2016-12-15T22:10:17 | 237        | 
| B02617               | 2016-12-15T22:10:22 | 79         | 
```