# Vehicle Classification Counts (2012-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicle-classification-counts-2012-2013-b609e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ae5u-upr6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ae5u-upr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ae5u-upr6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ae5u-upr6 |
| Name | Vehicle Classification Counts (2012-2013) |
| Attribution | Department of Transportation - DOT |
| Category | NYC BigApps |
| Tags | vehicle class, dot, bigapps, transportation |
| Created | 2014-05-08T15:58:43Z |
| Publication Date | 2014-06-17T19:29:45Z |

## Description

Vehicle classification counts collected by DOT for New York Metropolitan Transportation Council (NYMTC) to validate the New York Best Practice Model (NYBPM). For NYBPM screenline locations where data has been collected within the last three years are not considered for data collection for the present year. DOT collects data on at least 10% of the total NYBPM screenline locations.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| No       |                | id             | ID             | text          | number        |
| Yes      | series tag     | gis_id         | Segment ID     | text          | number        |
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
series e:ae5u-upr6 d:2012-10-24T00:00:00.000Z t:veh_class_type=Auto t:direction=EB t:gis_id=30344.00 t:from="Grand Ave" t:roadway_name="Flushing Ave" m:8_00_9_00pm=249 m:2_00_3_00pm=265 m:9_00_10_00pm=133 m:4_00_5_00pm=295 m:1_00_2_00pm=260 m:11_00_12_00am=117 m:10_00_11_00pm=145 m:12_00_1_00pm=220 m:6_00_7_00pm=260 m:3_00_4_00pm=270 m:5_00_6_00pm=292 m:7_00_8_00pm=329

series e:ae5u-upr6 d:2012-10-24T00:00:00.000Z t:veh_class_type=Taxis t:direction=EB t:gis_id=30344.00 t:from="Grand Ave" t:roadway_name="Flushing Ave" m:8_00_9_00pm=14 m:2_00_3_00pm=13 m:9_00_10_00pm=11 m:4_00_5_00pm=6 m:1_00_2_00pm=8 m:11_00_12_00am=14 m:10_00_11_00pm=14 m:12_00_1_00pm=7 m:6_00_7_00pm=7 m:3_00_4_00pm=14 m:5_00_6_00pm=13 m:7_00_8_00pm=19

series e:ae5u-upr6 d:2012-10-24T00:00:00.000Z t:veh_class_type=Commercial t:direction=EB t:gis_id=30344.00 t:from="Grand Ave" t:roadway_name="Flushing Ave" m:8_00_9_00pm=2 m:2_00_3_00pm=21 m:9_00_10_00pm=5 m:4_00_5_00pm=22 m:1_00_2_00pm=26 m:11_00_12_00am=3 m:10_00_11_00pm=3 m:12_00_1_00pm=22 m:6_00_7_00pm=10 m:3_00_4_00pm=17 m:5_00_6_00pm=12 m:7_00_8_00pm=12
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

entity e:ae5u-upr6 l:"Vehicle Classification Counts (2012-2013)" t:attribution="Department of Transportation -  DOT" t:url=https://data.cityofnewyork.us/api/views/ae5u-upr6

property e:ae5u-upr6 t:meta.view v:id=ae5u-upr6 v:category="NYC BigApps" v:averageRating=0 v:name="Vehicle Classification Counts (2012-2013)" v:attribution="Department of Transportation -  DOT"

property e:ae5u-upr6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ae5u-upr6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| id   | gis_id   | roadway_name | from      | to         | direction | date                | veh_class_type | 12_00_1_00_am | 1_00_2_00am | 2_00_3_00am | 3_00_4_00am | 4_00_5_00am | 5_00_6_00am | 6_00_7_00am | 7_00_8_00am | 8_00_9_00am | 9_00_10_00am | 10_00_11_00am | 11_00_12_00pm | 12_00_1_00pm | 1_00_2_00pm | 2_00_3_00pm | 3_00_4_00pm | 4_00_5_00pm | 5_00_6_00pm | 6_00_7_00pm | 7_00_8_00pm | 8_00_9_00pm | 9_00_10_00pm | 10_00_11_00pm | 11_00_12_00am | 
| ==== | ======== | ============ | ========= | ========== | ========= | =================== | ============== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | ============ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Auto           |               |             |             |             |             |             |             |             |             |              |               |               | 220.00       | 260.00      | 265.00      | 270.00      | 295.00      | 292.00      | 260.00      | 329.00      | 249.00      | 133.00       | 145.00        | 117.00        | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Taxis          |               |             |             |             |             |             |             |             |             |              |               |               | 7.00         | 8.00        | 13.00       | 14.00       | 6.00        | 13.00       | 7.00        | 19.00       | 14.00       | 11.00        | 14.00         | 14.00         | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Commercial     |               |             |             |             |             |             |             |             |             |              |               |               | 22.00        | 26.00       | 21.00       | 17.00       | 22.00       | 12.00       | 10.00       | 12.00       | 2.00        | 5.00         | 3.00          | 3.00          | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Medium Truck   |               |             |             |             |             |             |             |             |             |              |               |               | 44.00        | 50.00       | 50.00       | 40.00       | 22.00       | 22.00       | 15.00       | 18.00       | 9.00        | 7.00         | 7.00          | 8.00          | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Heavy Truck    |               |             |             |             |             |             |             |             |             |              |               |               | 5.00         | 9.00        | 4.00        | 8.00        | 10.00       | 8.00        | 2.00        | 3.00        | 4.00        | 1.00         | 1.00          | 1.00          | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | School Bus     |               |             |             |             |             |             |             |             |             |              |               |               | 1.00         | 2.00        | 6.00        | 5.00        | 8.00        | 3.00        | 0.00        | 7.00        | 1.00        | 0.00         | 0.00          | 0.00          | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-24T00:00:00 | Other Bus      |               |             |             |             |             |             |             |             |             |              |               |               | 5.00         | 3.00        | 7.00        | 3.00        | 7.00        | 6.00        | 4.00        | 5.00        | 3.00        | 2.00         | 3.00          | 3.00          | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-25T00:00:00 | Auto           | 83.00         | 38.00       | 13.00       | 20.00       | 23.00       | 45.00       | 87.00       | 149.00      | 184.00      | 200.00       | 232.00        | 244.00        |              |             |             |             |             |             |             |             |             |              |               |               | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-25T00:00:00 | Taxis          | 13.00         | 12.00       | 4.00        | 2.00        | 5.00        | 6.00        | 16.00       | 17.00       | 12.00       | 14.00        | 14.00         | 22.00         |              |             |             |             |             |             |             |             |             |              |               |               | 
| 1.00 | 30344.00 | Flushing Ave | Grand Ave | Ryerson St | EB        | 2012-10-25T00:00:00 | Commercial     | 2.00          | 1.00        | 1.00        | 3.00        | 2.00        | 7.00        | 7.00        | 23.00       | 27.00       | 24.00        | 29.00         | 26.00         |              |             |             |             |             |             |             |             |             |              |               |               | 
```