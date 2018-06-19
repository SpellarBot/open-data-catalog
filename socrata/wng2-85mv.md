# Traffic Volume Counts (2011-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-volume-counts-2011-2012-59a24) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wng2-85mv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wng2-85mv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wng2-85mv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wng2-85mv |
| Name | Traffic Volume Counts (2011-2012) |
| Attribution | DOT |
| Category | NYC BigApps |
| Tags | traffic, dot, bigapps, transportation |
| Created | 2014-05-08T14:53:41Z |
| Publication Date | 2014-06-17T19:26:10Z |

## Description

Traffic volume counts collected by DOT for New York Metropolitan Transportation Council (NYMTC) to validate the New York Best Practice Model (NYBPM). For NYBPM screenline locations where data has been collected within the last three years are not considered for data collection for the present year. DOT collects data on at least 30% of the total NYBPM screenline locations.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| No       |                | id            | ID            | text          | number        |
| Yes      | series tag     | gis_id        | GIS ID        | text          | text          |
| Yes      | series tag     | roadway_name  | Roadway Name  | text          | text          |
| Yes      | series tag     | from          | From          | text          | text          |
| No       |                | to            | To            | text          | text          |
| Yes      | series tag     | direction     | Direction     | text          | text          |
| Yes      | time           | date          | Date          | calendar_date | calendar_date |
| Yes      | numeric metric | 12_00_1_00_am | 12:00-1:00 AM | number        | number        |
| Yes      | numeric metric | 1_00_2_00am   | 1:00-2:00AM   | number        | number        |
| Yes      | numeric metric | 2_00_3_00am   | 2:00-3:00AM   | number        | number        |
| Yes      | numeric metric | 3_00_4_00am   | 3:00-4:00AM   | number        | number        |
| Yes      | numeric metric | 4_00_5_00am   | 4:00-5:00AM   | number        | number        |
| Yes      | numeric metric | 5_00_6_00am   | 5:00-6:00AM   | number        | number        |
| Yes      | numeric metric | 6_00_7_00am   | 6:00-7:00AM   | number        | number        |
| Yes      | numeric metric | 7_00_8_00am   | 7:00-8:00AM   | number        | number        |
| Yes      | numeric metric | 8_00_9_00am   | 8:00-9:00AM   | number        | number        |
| Yes      | numeric metric | 9_00_10_00am  | 9:00-10:00AM  | number        | number        |
| Yes      | numeric metric | 10_00_11_00am | 10:00-11:00AM | number        | number        |
| Yes      | numeric metric | 11_00_12_00pm | 11:00-12:00PM | number        | number        |
| Yes      | numeric metric | 12_00_1_00pm  | 12:00-1:00PM  | number        | number        |
| Yes      | numeric metric | 1_00_2_00pm   | 1:00-2:00PM   | number        | number        |
| Yes      | numeric metric | 2_00_3_00pm   | 2:00-3:00PM   | number        | number        |
| Yes      | numeric metric | 3_00_4_00pm   | 3:00-4:00PM   | number        | number        |
| Yes      | numeric metric | 4_00_5_00pm   | 4:00-5:00PM   | number        | number        |
| Yes      | numeric metric | 5_00_6_00pm   | 5:00-6:00PM   | number        | number        |
| Yes      | numeric metric | 6_00_7_00pm   | 6:00-7:00PM   | number        | number        |
| Yes      | numeric metric | 7_00_8_00pm   | 7:00-8:00PM   | number        | number        |
| Yes      | numeric metric | 8_00_9_00pm   | 8:00-9:00PM   | number        | number        |
| Yes      | numeric metric | 9_00_10_00pm  | 9:00-10:00PM  | number        | number        |
| Yes      | numeric metric | 10_00_11_00pm | 10:00-11:00PM | number        | number        |
| Yes      | numeric metric | 11_00_12_00am | 11:00-12:00AM | number        | number        |
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
series e:wng2-85mv d:2012-01-09T00:00:00.000Z t:direction=NB t:gis_id=15540 t:from="UNION PLACE" t:roadway_name="BEACH STREET" m:5_00_6_00am=20 m:9_00_10_00am=52 m:10_00_11_00am=68 m:4_00_5_00pm=147 m:8_00_9_00am=100 m:11_00_12_00pm=85 m:1_00_2_00am=10 m:6_00_7_00pm=91 m:5_00_6_00pm=120 m:3_00_4_00pm=105 m:8_00_9_00pm=74 m:2_00_3_00pm=104 m:9_00_10_00pm=49 m:7_00_8_00am=66 m:4_00_5_00am=13 m:2_00_3_00am=11 m:11_00_12_00am=42 m:1_00_2_00pm=94 m:10_00_11_00pm=42 m:12_00_1_00pm=85 m:12_00_1_00_am=20 m:6_00_7_00am=34 m:3_00_4_00am=14 m:7_00_8_00pm=83

series e:wng2-85mv d:2012-01-10T00:00:00.000Z t:direction=NB t:gis_id=15540 t:from="UNION PLACE" t:roadway_name="BEACH STREET" m:5_00_6_00am=13 m:9_00_10_00am=45 m:10_00_11_00am=57 m:4_00_5_00pm=133 m:8_00_9_00am=67 m:11_00_12_00pm=67 m:1_00_2_00am=16 m:6_00_7_00pm=95 m:5_00_6_00pm=131 m:3_00_4_00pm=98 m:8_00_9_00pm=70 m:2_00_3_00pm=102 m:9_00_10_00pm=63 m:7_00_8_00am=70 m:4_00_5_00am=13 m:2_00_3_00am=8 m:11_00_12_00am=35 m:1_00_2_00pm=95 m:10_00_11_00pm=42 m:12_00_1_00pm=73 m:12_00_1_00_am=21 m:6_00_7_00am=31 m:3_00_4_00am=6 m:7_00_8_00pm=73

series e:wng2-85mv d:2012-01-11T00:00:00.000Z t:direction=NB t:gis_id=15540 t:from="UNION PLACE" t:roadway_name="BEACH STREET" m:5_00_6_00am=16 m:9_00_10_00am=71 m:10_00_11_00am=67 m:4_00_5_00pm=130 m:8_00_9_00am=69 m:11_00_12_00pm=70 m:1_00_2_00am=14 m:6_00_7_00pm=106 m:5_00_6_00pm=143 m:3_00_4_00pm=115 m:8_00_9_00pm=68 m:2_00_3_00pm=115 m:9_00_10_00pm=64 m:7_00_8_00am=75 m:4_00_5_00am=12 m:2_00_3_00am=6 m:11_00_12_00am=43 m:1_00_2_00pm=89 m:10_00_11_00pm=56 m:12_00_1_00pm=90 m:12_00_1_00_am=27 m:6_00_7_00am=34 m:3_00_4_00am=5 m:7_00_8_00pm=89
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

entity e:wng2-85mv l:"Traffic Volume Counts (2011-2012)" t:attribution=DOT t:url=https://data.cityofnewyork.us/api/views/wng2-85mv

property e:wng2-85mv t:meta.view v:id=wng2-85mv v:category="NYC BigApps" v:averageRating=0 v:name="Traffic Volume Counts (2011-2012)" v:attribution=DOT

property e:wng2-85mv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wng2-85mv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| id | gis_id | roadway_name | from        | to               | direction | date                | 12_00_1_00_am | 1_00_2_00am | 2_00_3_00am | 3_00_4_00am | 4_00_5_00am | 5_00_6_00am | 6_00_7_00am | 7_00_8_00am | 8_00_9_00am | 9_00_10_00am | 10_00_11_00am | 11_00_12_00pm | 12_00_1_00pm | 1_00_2_00pm | 2_00_3_00pm | 3_00_4_00pm | 4_00_5_00pm | 5_00_6_00pm | 6_00_7_00pm | 7_00_8_00pm | 8_00_9_00pm | 9_00_10_00pm | 10_00_11_00pm | 11_00_12_00am | 
| == | ====== | ============ | =========== | ================ | ========= | =================== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | ============ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | 
| 1  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-09T00:00:00 | 20.00         | 10.00       | 11.00       | 14.00       | 13.00       | 20.00       | 34.00       | 66.00       | 100.00      | 52.00        | 68.00         | 85.00         | 85.00        | 94.00       | 104.00      | 105.00      | 147.00      | 120.00      | 91.00       | 83.00       | 74.00       | 49.00        | 42.00         | 42.00         | 
| 2  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-10T00:00:00 | 21.00         | 16.00       | 8.00        | 6.00        | 13.00       | 13.00       | 31.00       | 70.00       | 67.00       | 45.00        | 57.00         | 67.00         | 73.00        | 95.00       | 102.00      | 98.00       | 133.00      | 131.00      | 95.00       | 73.00       | 70.00       | 63.00        | 42.00         | 35.00         | 
| 3  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-11T00:00:00 | 27.00         | 14.00       | 6.00        | 5.00        | 12.00       | 16.00       | 34.00       | 75.00       | 69.00       | 71.00        | 67.00         | 70.00         | 90.00        | 89.00       | 115.00      | 115.00      | 130.00      | 143.00      | 106.00      | 89.00       | 68.00       | 64.00        | 56.00         | 43.00         | 
| 4  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-12T00:00:00 | 22.00         | 7.00        | 7.00        | 8.00        | 11.00       | 12.00       | 33.00       | 75.00       | 89.00       | 66.00        | 70.00         | 60.00         | 105.00       | 103.00      | 71.00       | 127.00      | 122.00      | 144.00      | 122.00      | 76.00       | 64.00       | 58.00        | 64.00         | 43.00         | 
| 5  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-13T00:00:00 | 31.00         | 17.00       | 7.00        | 5.00        | 13.00       | 28.00       | 29.00       | 68.00       | 84.00       | 64.00        | 83.00         | 89.00         | 88.00        | 113.00      | 113.00      | 126.00      | 133.00      | 135.00      | 102.00      | 106.00      | 58.00       | 58.00        | 55.00         | 54.00         | 
| 6  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | NB        | 2012-01-14T00:00:00 | 42.00         | 27.00       | 21.00       | 18.00       | 21.00       | 13.00       | 17.00       | 18.00       | 46.00       | 53.00        | 29.00         | 0.00          |              |             |             |             |             |             |             |             |             |              |               |               | 
| 7  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | SB        | 2012-01-09T00:00:00 | 27.00         | 12.00       | 12.00       | 4.00        | 22.00       | 27.00       | 66.00       | 154.00      | 155.00      | 138.00       | 105.00        | 124.00        | 140.00       | 120.00      | 165.00      | 197.00      | 152.00      | 174.00      | 128.00      | 95.00       | 87.00       | 73.00        | 57.00         | 42.00         | 
| 8  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | SB        | 2012-01-10T00:00:00 | 26.00         | 16.00       | 11.00       | 13.00       | 16.00       | 27.00       | 59.00       | 156.00      | 177.00      | 131.00       | 107.00        | 108.00        | 122.00       | 131.00      | 192.00      | 180.00      | 161.00      | 171.00      | 120.00      | 96.00       | 90.00       | 70.00        | 63.00         | 49.00         | 
| 9  | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | SB        | 2012-01-11T00:00:00 | 32.00         | 16.00       | 8.00        | 9.00        | 15.00       | 26.00       | 63.00       | 169.00      | 178.00      | 148.00       | 139.00        | 131.00        | 126.00       | 137.00      | 178.00      | 194.00      | 168.00      | 160.00      | 143.00      | 114.00      | 78.00       | 64.00        | 49.00         | 45.00         | 
| 10 | 15540  | BEACH STREET | UNION PLACE | VAN DUZER STREET | SB        | 2012-01-12T00:00:00 | 24.00         | 12.00       | 7.00        | 18.00       | 11.00       | 23.00       | 61.00       | 146.00      | 177.00      | 128.00       | 117.00        | 111.00        | 134.00       | 134.00      | 171.00      | 184.00      | 157.00      | 167.00      | 148.00      | 112.00      | 86.00       | 77.00        | 63.00         | 51.00         | 
```