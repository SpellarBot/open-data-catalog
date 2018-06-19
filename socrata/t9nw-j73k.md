# Vehicle Classification Counts (2011-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicle-classification-counts-2011-2012-5fe45) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/t9nw-j73k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/t9nw-j73k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/t9nw-j73k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | t9nw-j73k |
| Name | Vehicle Classification Counts (2011-2012) |
| Attribution | Department of Transportation (DOT) |
| Category | NYC BigApps |
| Tags | vehicle class, dot, bigapps, transportation |
| Created | 2014-05-08T15:13:23Z |
| Publication Date | 2014-05-08T15:28:45Z |

## Description

Vehicle classification counts collected by DOT for New York Metropolitan Transportation Council (NYMTC) to validate the New York Best Practice Model (NYBPM). For NYBPM screenline locations where data has been collected within the last three years are not considered for data collection for the present year. DOT collects data on at least 10% of the total NYBPM screenline locations.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| No       |                | id             | ID             | text          | number        |
| Yes      | series tag     | gis_id         | GIS ID         | text          | text          |
| Yes      | series tag     | roadway_name   | Roadway Name   | text          | text          |
| Yes      | series tag     | from           | From           | text          | text          |
| No       |                | to             | To             | text          | text          |
| Yes      | series tag     | direction      | Direction      | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| Yes      | series tag     | veh_class_type | Veh Class Type | text          | text          |
| Yes      | numeric metric | 12_00_1_00_am  | 12:00-1:00 AM  | number        | number        |
| Yes      | numeric metric | 1_00_2_00am    | 1:00-2:00AM    | number        | number        |
| Yes      | numeric metric | 2_00_3_00am    | 2:00-3:00AM    | number        | number        |
| Yes      | numeric metric | 3_00_4_00am    | 3:00-4:00AM    | number        | number        |
| Yes      | numeric metric | 4_00_5_00am    | 4:00-5:00AM    | number        | number        |
| Yes      | numeric metric | 5_00_6_00am    | 5:00-6:00AM    | number        | number        |
| Yes      | numeric metric | 6_00_7_00am    | 6:00-7:00AM    | number        | number        |
| Yes      | numeric metric | 7_00_8_00am    | 7:00-8:00AM    | number        | number        |
| Yes      | numeric metric | 8_00_9_00am    | 8:00-9:00AM    | number        | number        |
| Yes      | numeric metric | 9_00_10_00am   | 9:00-10:00AM   | number        | number        |
| Yes      | numeric metric | 10_00_11_00am  | 10:00-11:00AM  | number        | number        |
| Yes      | numeric metric | 11_00_12_00pm  | 11:00-12:00PM  | number        | number        |
| Yes      | numeric metric | 12_00_1_00pm   | 12:00-1:00PM   | number        | number        |
| Yes      | numeric metric | 1_00_2_00pm    | 1:00-2:00PM    | number        | number        |
| Yes      | numeric metric | 2_00_3_00pm    | 2:00-3:00PM    | number        | number        |
| Yes      | numeric metric | 3_00_4_00pm    | 3:00-4:00PM    | number        | number        |
| Yes      | numeric metric | 4_00_5_00pm    | 4:00-5:00PM    | number        | number        |
| Yes      | numeric metric | 5_00_6_00pm    | 5:00-6:00PM    | number        | number        |
| Yes      | numeric metric | 6_00_7_00pm    | 6:00-7:00PM    | number        | number        |
| Yes      | numeric metric | 7_00_8_00pm    | 7:00-8:00PM    | number        | number        |
| Yes      | numeric metric | 8_00_9_00pm    | 8:00-9:00PM    | number        | number        |
| Yes      | numeric metric | 9_00_10_00pm   | 9:00-10:00PM   | number        | number        |
| Yes      | numeric metric | 10_00_11_00pm  | 10:00-11:00PM  | number        | number        |
| Yes      | numeric metric | 11_00_12_00am  | 11:00-12:00AM  | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,to
```

## Data Commands

```ls
series e:t9nw-j73k d:2012-01-10T00:00:00.000Z t:veh_class_type=Autos t:direction=NB t:gis_id=15540 t:from="Union Pl" t:roadway_name="Beach St" m:9_00_10_00am=37 m:10_00_11_00am=44 m:4_00_5_00pm=118 m:8_00_9_00am=47 m:11_00_12_00pm=49 m:6_00_7_00pm=79 m:5_00_6_00pm=115 m:3_00_4_00pm=88 m:8_00_9_00pm=58 m:2_00_3_00pm=74 m:9_00_10_00pm=58 m:7_00_8_00am=48 m:11_00_12_00am=28 m:1_00_2_00pm=77 m:10_00_11_00pm=39 m:12_00_1_00pm=52 m:12_00_1_00_am=0 m:7_00_8_00pm=65

series e:t9nw-j73k d:2012-01-10T00:00:00.000Z t:veh_class_type=Taxi t:direction=NB t:gis_id=15540 t:from="Union Pl" t:roadway_name="Beach St" m:9_00_10_00am=6 m:10_00_11_00am=3 m:4_00_5_00pm=3 m:8_00_9_00am=5 m:11_00_12_00pm=4 m:6_00_7_00pm=3 m:5_00_6_00pm=8 m:3_00_4_00pm=7 m:8_00_9_00pm=2 m:2_00_3_00pm=7 m:9_00_10_00pm=3 m:7_00_8_00am=10 m:11_00_12_00am=0 m:1_00_2_00pm=6 m:10_00_11_00pm=1 m:12_00_1_00pm=4 m:12_00_1_00_am=0 m:7_00_8_00pm=1

series e:t9nw-j73k d:2012-01-10T00:00:00.000Z t:veh_class_type=Commercial t:direction=NB t:gis_id=15540 t:from="Union Pl" t:roadway_name="Beach St" m:9_00_10_00am=2 m:10_00_11_00am=5 m:4_00_5_00pm=5 m:8_00_9_00am=6 m:11_00_12_00pm=6 m:6_00_7_00pm=3 m:5_00_6_00pm=4 m:3_00_4_00pm=5 m:8_00_9_00pm=4 m:2_00_3_00pm=7 m:9_00_10_00pm=2 m:7_00_8_00am=3 m:11_00_12_00am=3 m:1_00_2_00pm=4 m:10_00_11_00pm=2 m:12_00_1_00pm=6 m:12_00_1_00_am=0 m:7_00_8_00pm=4
```

## Meta Commands

```ls
metric m:12_00_1_00_am p:float l:"12:00-1:00 AM" t:dataTypeName=number

metric m:1_00_2_00am p:float l:1:00-2:00AM t:dataTypeName=number

metric m:2_00_3_00am p:float l:2:00-3:00AM t:dataTypeName=number

metric m:3_00_4_00am p:float l:3:00-4:00AM t:dataTypeName=number

metric m:4_00_5_00am p:float l:4:00-5:00AM t:dataTypeName=number

metric m:5_00_6_00am p:float l:5:00-6:00AM t:dataTypeName=number

metric m:6_00_7_00am p:float l:6:00-7:00AM t:dataTypeName=number

metric m:7_00_8_00am p:float l:7:00-8:00AM t:dataTypeName=number

metric m:8_00_9_00am p:float l:8:00-9:00AM t:dataTypeName=number

metric m:9_00_10_00am p:float l:9:00-10:00AM t:dataTypeName=number

metric m:10_00_11_00am p:float l:10:00-11:00AM t:dataTypeName=number

metric m:11_00_12_00pm p:float l:11:00-12:00PM t:dataTypeName=number

metric m:12_00_1_00pm p:float l:12:00-1:00PM t:dataTypeName=number

metric m:1_00_2_00pm p:float l:1:00-2:00PM t:dataTypeName=number

metric m:2_00_3_00pm p:float l:2:00-3:00PM t:dataTypeName=number

metric m:3_00_4_00pm p:float l:3:00-4:00PM t:dataTypeName=number

metric m:4_00_5_00pm p:float l:4:00-5:00PM t:dataTypeName=number

metric m:5_00_6_00pm p:float l:5:00-6:00PM t:dataTypeName=number

metric m:6_00_7_00pm p:float l:6:00-7:00PM t:dataTypeName=number

metric m:7_00_8_00pm p:float l:7:00-8:00PM t:dataTypeName=number

metric m:8_00_9_00pm p:float l:8:00-9:00PM t:dataTypeName=number

metric m:9_00_10_00pm p:float l:9:00-10:00PM t:dataTypeName=number

metric m:10_00_11_00pm p:float l:10:00-11:00PM t:dataTypeName=number

metric m:11_00_12_00am p:float l:11:00-12:00AM t:dataTypeName=number

entity e:t9nw-j73k l:"Vehicle Classification Counts (2011-2012)" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/t9nw-j73k

property e:t9nw-j73k t:meta.view v:id=t9nw-j73k v:category="NYC BigApps" v:averageRating=0 v:name="Vehicle Classification Counts (2011-2012)" v:attribution="Department of Transportation (DOT)"

property e:t9nw-j73k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:t9nw-j73k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| id | gis_id | roadway_name | from     | to            | direction | date                | veh_class_type | 12_00_1_00_am | 1_00_2_00am | 2_00_3_00am | 3_00_4_00am | 4_00_5_00am | 5_00_6_00am | 6_00_7_00am | 7_00_8_00am | 8_00_9_00am | 9_00_10_00am | 10_00_11_00am | 11_00_12_00pm | 12_00_1_00pm | 1_00_2_00pm | 2_00_3_00pm | 3_00_4_00pm | 4_00_5_00pm | 5_00_6_00pm | 6_00_7_00pm | 7_00_8_00pm | 8_00_9_00pm | 9_00_10_00pm | 10_00_11_00pm | 11_00_12_00am | 
| == | ====== | ============ | ======== | ============= | ========= | =================== | ============== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | ============ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | 
| 1  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-10T00:00:00 | Autos          | 0.00          |             |             |             |             |             |             | 48.00       | 47.00       | 37.00        | 44.00         | 49.00         | 52.00        | 77.00       | 74.00       | 88.00       | 118.00      | 115.00      | 79.00       | 65.00       | 58.00       | 58.00        | 39.00         | 28.00         | 
| 2  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-10T00:00:00 | Taxi           | 0.00          |             |             |             |             |             |             | 10.00       | 5.00        | 6.00         | 3.00          | 4.00          | 4.00         | 6.00        | 7.00        | 7.00        | 3.00        | 8.00        | 3.00        | 1.00        | 2.00        | 3.00         | 1.00          | 0.00          | 
| 3  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-10T00:00:00 | Commercial     | 0.00          |             |             |             |             |             |             | 3.00        | 6.00        | 2.00         | 5.00          | 6.00          | 6.00         | 4.00        | 7.00        | 5.00        | 5.00        | 4.00        | 3.00        | 4.00        | 4.00        | 2.00         | 2.00          | 3.00          | 
| 4  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-10T00:00:00 | Trucks         | 0.00          |             |             |             |             |             |             | 8.00        | 8.00        | 3.00         | 4.00          | 5.00          | 7.00         | 7.00        | 6.00        | 4.00        | 7.00        | 5.00        | 3.00        | 4.00        | 4.00        | 3.00         | 3.00          | 2.00          | 
| 5  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-11T00:00:00 | Autos          | 26.00         | 10.00       | 5.00        | 3.00        | 8.00        | 10.00       | 18.00       |             |             |              |               |               |              |             |             |             |             |             |             |             |             |              |               |               | 
| 6  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-11T00:00:00 | Taxi           | 1.00          | 2.00        | 2.00        | 2.00        | 1.00        | 1.00        | 5.00        |             |             |              |               |               |              |             |             |             |             |             |             |             |             |              |               |               | 
| 7  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-11T00:00:00 | Commercial     | 0.00          | 0.00        | 0.00        | 0.00        | 0.00        | 1.00        | 4.00        |             |             |              |               |               |              |             |             |             |             |             |             |             |             |              |               |               | 
| 8  | 15540  | Beach St     | Union Pl | Van Duzert St | NB        | 2012-01-11T00:00:00 | Trucks         | 2.00          | 1.00        | 0.00        | 0.00        | 1.00        | 3.00        | 4.00        |             |             |              |               |               |              |             |             |             |             |             |             |             |             |              |               |               | 
| 9  | 15540  | Beach St     | Union Pl | Van Duzert St | SB        | 2012-01-10T00:00:00 | Autos          | 0.00          |             |             |             |             |             |             | 117.00      | 127.00      | 107.00       | 84.00         | 83.00         | 88.00        | 105.00      | 176.00      | 154.00      | 149.00      | 155.00      | 104.00      | 81.00       | 72.00       | 68.00        | 59.00         | 38.00         | 
| 10 | 15540  | Beach St     | Union Pl | Van Duzert St | SB        | 2012-01-10T00:00:00 | Taxi           | 0.00          |             |             |             |             |             |             | 10.00       | 11.00       | 12.00        | 8.00          | 5.00          | 7.00         | 8.00        | 9.00        | 10.00       | 7.00        | 3.00        | 2.00        | 4.00        | 3.00        | 3.00         | 1.00          | 5.00          | 
```