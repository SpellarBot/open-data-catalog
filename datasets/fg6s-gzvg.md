# Divvy Trips

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/divvy-trips) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/fg6s-gzvg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/fg6s-gzvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/fg6s-gzvg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | fg6s-gzvg |
| Name | Divvy Trips |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | transportation, divvy, bike sharing |
| Created | 2016-06-02T19:10:40Z |
| Publication Date | 2016-09-02T22:08:14Z |

## Description

This lists individual Divvy bike sharing trips, including the origin, destination, and timestamps for each trip. Trips are included when there is an starting and end date. Trips using a subscriber pass will include some basic demographic data (gender and age) that is associated with the account. For more information see https://www.divvybikes.com/data

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                   | Data Type     | Render Type   |
| ======== | ============== | =========================== | ====================== | ============= | ============= |
| Yes      | series tag     | trip_id                     | TRIP ID                | text          | number        |
| Yes      | time           | start_time                  | START TIME             | calendar_date | calendar_date |
| No       |                | stop_time                   | STOP TIME              | calendar_date | calendar_date |
| Yes      | series tag     | bike_id                     | BIKE ID                | text          | text          |
| Yes      | numeric metric | trip_duration               | TRIP DURATION          | number        | number        |
| Yes      | series tag     | from_station_id             | FROM STATION ID        | text          | text          |
| Yes      | series tag     | from_station_name           | FROM STATION NAME      | text          | text          |
| Yes      | series tag     | to_station_id               | TO STATION ID          | text          | text          |
| Yes      | series tag     | to_station_name             | TO STATION NAME        | text          | text          |
| Yes      | series tag     | user_type                   | USER TYPE              | text          | text          |
| Yes      | series tag     | gender                      | GENDER                 | text          | text          |
| No       |                | birth_year                  | BIRTH YEAR             | number        | number        |
| No       |                | from_latitude               | FROM LATITUDE          | number        | number        |
| No       |                | from_longitude              | FROM LONGITUDE         | number        | number        |
| Yes      | series tag     | from_location               | FROM LOCATION          | point         | point         |
| No       |                | to_latitude                 | TO LATITUDE            | number        | number        |
| No       |                | to_longitude                | TO LONGITUDE           | number        | number        |
| Yes      | series tag     | to_location                 | TO LOCATION            | point         | point         |
| Yes      | numeric metric | :@computed_region_rpca_8um6 | Boundaries - ZIP Codes | number        | number        |
| Yes      | numeric metric | :@computed_region_6mkv_f3dw | Zip Codes              | number        | number        |
| Yes      | numeric metric | :@computed_region_vrxf_vc4k | Community Areas        | number        | number        |
| Yes      | numeric metric | :@computed_region_43wa_7qmu | Wards                  | number        | number        |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = stop_time,from_latitude,from_longitude,to_latitude,to_longitude,birth_year
```

## Data Commands

```ls
series e:fg6s-gzvg d:2016-12-31T23:57:00.000Z t:trip_id=12979228 t:from_location="POINT (-87.697899 41.926618)" t:bike_id=5076 t:user_type=Customer t:to_station_id=258 t:to_location="POINT (-87.685126 41.930584)" t:from_station_name="California Ave & Altgeld St" t:from_station_id=502 t:to_station_name="Logan Blvd & Elston Ave" m::@computed_region_vrxf_vc4k=23 m::@computed_region_rpca_8um6=1 m:trip_duration=532 m::@computed_region_6mkv_f3dw=22535 m::@computed_region_43wa_7qmu=41

series e:fg6s-gzvg d:2016-12-31T23:53:00.000Z t:trip_id=12979227 t:from_location="POINT (-87.619521 41.884728)" t:bike_id=5114 t:user_type=Customer t:to_station_id=25 t:to_location="POINT (-87.62351 41.89766)" t:from_station_name="Columbus Dr & Randolph St" t:from_station_id=195 t:to_station_name="Michigan Ave & Pearson St" m::@computed_region_vrxf_vc4k=38 m::@computed_region_rpca_8um6=42 m:trip_duration=895 m::@computed_region_6mkv_f3dw=14309 m::@computed_region_43wa_7qmu=36

series e:fg6s-gzvg d:2016-12-31T23:53:00.000Z t:trip_id=12979226 t:from_location="POINT (-87.619521 41.884728)" t:bike_id=1026 t:user_type=Customer t:to_station_id=25 t:to_location="POINT (-87.62351 41.89766)" t:from_station_name="Columbus Dr & Randolph St" t:from_station_id=195 t:to_station_name="Michigan Ave & Pearson St" m::@computed_region_vrxf_vc4k=38 m::@computed_region_rpca_8um6=42 m:trip_duration=931 m::@computed_region_6mkv_f3dw=14309 m::@computed_region_43wa_7qmu=36
```

## Meta Commands

```ls
metric m:trip_duration p:long l:"TRIP DURATION" d:"Duration of the trip in seconds." t:dataTypeName=number

metric m::@computed_region_rpca_8um6 p:long l:"Boundaries - ZIP Codes" t:dataTypeName=number

metric m::@computed_region_6mkv_f3dw p:long l:"Zip Codes" t:dataTypeName=number

metric m::@computed_region_vrxf_vc4k p:long l:"Community Areas" t:dataTypeName=number

metric m::@computed_region_43wa_7qmu p:long l:Wards t:dataTypeName=number

entity e:fg6s-gzvg l:"Divvy Trips" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/fg6s-gzvg

property e:fg6s-gzvg t:meta.view v:id=fg6s-gzvg v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Divvy Trips" v:attribution="City of Chicago"

property e:fg6s-gzvg t:meta.view.owner v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"

property e:fg6s-gzvg t:meta.view.tableauthor v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"
```

## Top Records

```ls
| trip_id  | start_time          | stop_time           | bike_id | trip_duration | from_station_id | from_station_name            | to_station_id | to_station_name             | user_type  | gender | birth_year | from_latitude | from_longitude | from_location                | to_latitude | to_longitude | to_location                  | :@computed_region_rpca_8um6 | :@computed_region_6mkv_f3dw | :@computed_region_vrxf_vc4k | :@computed_region_43wa_7qmu | 
| ======== | =================== | =================== | ======= | ============= | =============== | ============================ | ============= | =========================== | ========== | ====== | ========== | ============= | ============== | ============================ | =========== | ============ | ============================ | =========================== | =========================== | =========================== | =========================== | 
| 12979228 | 2016-12-31T23:57:00 | 2017-01-01T00:06:00 | 5076    | 532           | 502             | California Ave & Altgeld St  | 258           | Logan Blvd & Elston Ave     | Customer   |        |            | 41.926618     | -87.697899     | POINT (-87.697899 41.926618) | 41.930584   | -87.685126   | POINT (-87.685126 41.930584) | 1                           | 22535                       | 23                          | 41                          | 
| 12979227 | 2016-12-31T23:53:00 | 2017-01-01T00:08:00 | 5114    | 895           | 195             | Columbus Dr & Randolph St    | 25            | Michigan Ave & Pearson St   | Customer   |        |            | 41.884728     | -87.619521     | POINT (-87.619521 41.884728) | 41.89766    | -87.62351    | POINT (-87.62351 41.89766)   | 42                          | 14309                       | 38                          | 36                          | 
| 12979226 | 2016-12-31T23:53:00 | 2017-01-01T00:08:00 | 1026    | 931           | 195             | Columbus Dr & Randolph St    | 25            | Michigan Ave & Pearson St   | Customer   |        |            | 41.884728     | -87.619521     | POINT (-87.619521 41.884728) | 41.89766    | -87.62351    | POINT (-87.62351 41.89766)   | 42                          | 14309                       | 38                          | 36                          | 
| 12979225 | 2016-12-31T23:51:00 | 2017-01-01T00:07:00 | 504     | 970           | 199             | Wabash Ave & Grand Ave       | 35            | Streeter Dr & Grand Ave     | Subscriber | Male   | 1985       | 41.891738     | -87.626937     | POINT (-87.626937 41.891738) | 41.892278   | -87.612043   | POINT (-87.612043 41.892278) | 6                           | 21182                       | 37                          | 36                          | 
| 12979224 | 2016-12-31T23:51:00 | 2017-01-01T00:07:00 | 4451    | 980           | 199             | Wabash Ave & Grand Ave       | 35            | Streeter Dr & Grand Ave     | Subscriber | Female | 1985       | 41.891738     | -87.626937     | POINT (-87.626937 41.891738) | 41.892278   | -87.612043   | POINT (-87.612043 41.892278) | 6                           | 21182                       | 37                          | 36                          | 
| 12979221 | 2016-12-31T23:47:00 | 2017-01-01T00:18:00 | 2865    | 1867          | 177             | Theater on the Lake          | 140           | Dearborn Pkwy & Delaware Pl | Customer   |        |            | 41.926277     | -87.630834     | POINT (-87.630834 41.926277) | 41.898969   | -87.629912   | POINT (-87.629912 41.898969) | 16                          | 4449                        | 68                          | 34                          | 
| 12979223 | 2016-12-31T23:47:00 | 2016-12-31T23:50:00 | 5643    | 179           | 47              | State St & Kinzie St         | 125           | Rush St & Hubbard St        | Subscriber | Male   | 1970       | 41.88918      | -87.6277       | POINT (-87.6277 41.88918)    | 41.890011   | -87.626293   | POINT (-87.626293 41.890011) | 6                           | 21182                       | 37                          | 36                          | 
| 12979222 | 2016-12-31T23:47:00 | 2017-01-01T00:18:00 | 48      | 1863          | 177             | Theater on the Lake          | 140           | Dearborn Pkwy & Delaware Pl | Customer   |        |            | 41.926277     | -87.630834     | POINT (-87.630834 41.926277) | 41.898969   | -87.629912   | POINT (-87.629912 41.898969) | 16                          | 4449                        | 68                          | 34                          | 
| 12979220 | 2016-12-31T23:45:00 | 2017-01-01T00:13:00 | 1779    | 1656          | 195             | Columbus Dr & Randolph St    | 195           | Columbus Dr & Randolph St   | Customer   |        |            | 41.884728     | -87.619521     | POINT (-87.619521 41.884728) | 41.884728   | -87.619521   | POINT (-87.619521 41.884728) | 42                          | 14309                       | 38                          | 36                          | 
| 12979219 | 2016-12-31T23:44:00 | 2016-12-31T23:46:00 | 518     | 108           | 264             | Stetson Ave & South Water St | 52            | Michigan Ave & Lake St      | Subscriber | Male   | 1986       | 41.886835     | -87.62232      | POINT (-87.62232 41.886835)  | 41.886024   | -87.624117   | POINT (-87.624117 41.886024) | 42                          | 14309                       | 38                          | 36                          | 
```