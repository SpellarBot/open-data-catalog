# Traffic Volume Counts (2012-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-volume-counts-2012-2013-c8b1e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p424-amsu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p424-amsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p424-amsu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p424-amsu |
| Name | Traffic Volume Counts (2012-2013) |
| Attribution | DOT |
| Category | NYC BigApps |
| Tags | traffic, dot, bigapps, transportation |
| Created | 2014-05-08T15:46:07Z |
| Publication Date | 2014-06-17T19:22:45Z |

## Description

Traffic volume counts collected by DOT for New York Metropolitan Transportation Council (NYMTC) to validate the New York Best Practice Model (NYBPM). For NYBPM screenline locations where data has been collected within the last three years are not considered for data collection for the present year. DOT collects data on at least 30% of the total NYBPM screenline locations.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| No       |                | id            | ID            | text          | number        |
| Yes      | series tag     | segment_id    | Segment ID    | text          | number        |
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
series e:p424-amsu d:2013-02-02T00:00:00.000Z t:segment_id=2153.00 t:direction=NB t:from="WOODROW RD" t:roadway_name="HUGUENOT AVE" m:5_00_6_00am=45 m:9_00_10_00am=278 m:10_00_11_00am=387 m:4_00_5_00pm=324 m:8_00_9_00am=213 m:11_00_12_00pm=335 m:1_00_2_00am=74 m:6_00_7_00pm=379 m:5_00_6_00pm=394 m:3_00_4_00pm=398 m:8_00_9_00pm=249 m:2_00_3_00pm=371 m:9_00_10_00pm=197 m:7_00_8_00am=145 m:4_00_5_00am=29 m:2_00_3_00am=45 m:11_00_12_00am=169 m:1_00_2_00pm=411 m:10_00_11_00pm=187 m:12_00_1_00pm=406 m:12_00_1_00_am=106 m:6_00_7_00am=71 m:3_00_4_00am=29 m:7_00_8_00pm=329

series e:p424-amsu d:2013-02-03T00:00:00.000Z t:segment_id=2153.00 t:direction=NB t:from="WOODROW RD" t:roadway_name="HUGUENOT AVE" m:5_00_6_00am=25 m:9_00_10_00am=204 m:10_00_11_00am=249 m:4_00_5_00pm=313 m:8_00_9_00am=111 m:11_00_12_00pm=351 m:1_00_2_00am=74 m:6_00_7_00pm=242 m:5_00_6_00pm=253 m:3_00_4_00pm=291 m:8_00_9_00pm=210 m:2_00_3_00pm=308 m:9_00_10_00pm=144 m:7_00_8_00am=74 m:4_00_5_00am=26 m:2_00_3_00am=55 m:11_00_12_00am=79 m:1_00_2_00pm=350 m:10_00_11_00pm=125 m:12_00_1_00pm=374 m:12_00_1_00_am=109 m:6_00_7_00am=47 m:3_00_4_00am=37 m:7_00_8_00pm=217

series e:p424-amsu d:2013-02-04T00:00:00.000Z t:segment_id=2153.00 t:direction=NB t:from="WOODROW RD" t:roadway_name="HUGUENOT AVE" m:5_00_6_00am=108 m:9_00_10_00am=263 m:10_00_11_00am=282 m:4_00_5_00pm=419 m:8_00_9_00am=493 m:11_00_12_00pm=307 m:1_00_2_00am=28 m:6_00_7_00pm=425 m:5_00_6_00pm=469 m:3_00_4_00pm=425 m:8_00_9_00pm=224 m:2_00_3_00pm=426 m:9_00_10_00pm=185 m:7_00_8_00am=418 m:4_00_5_00am=32 m:2_00_3_00am=11 m:11_00_12_00am=74 m:1_00_2_00pm=328 m:10_00_11_00pm=132 m:12_00_1_00pm=304 m:12_00_1_00_am=36 m:6_00_7_00am=168 m:3_00_4_00am=16 m:7_00_8_00pm=358
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

entity e:p424-amsu l:"Traffic Volume Counts (2012-2013)" t:attribution=DOT t:url=https://data.cityofnewyork.us/api/views/p424-amsu

property e:p424-amsu t:meta.view v:id=p424-amsu v:category="NYC BigApps" v:averageRating=0 v:name="Traffic Volume Counts (2012-2013)" v:attribution=DOT

property e:p424-amsu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p424-amsu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| id   | segment_id | roadway_name | from       | to           | direction | date                | 12_00_1_00_am | 1_00_2_00am | 2_00_3_00am | 3_00_4_00am | 4_00_5_00am | 5_00_6_00am | 6_00_7_00am | 7_00_8_00am | 8_00_9_00am | 9_00_10_00am | 10_00_11_00am | 11_00_12_00pm | 12_00_1_00pm | 1_00_2_00pm | 2_00_3_00pm | 3_00_4_00pm | 4_00_5_00pm | 5_00_6_00pm | 6_00_7_00pm | 7_00_8_00pm | 8_00_9_00pm | 9_00_10_00pm | 10_00_11_00pm | 11_00_12_00am | 
| ==== | ========== | ============ | ========== | ============ | ========= | =================== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | ============ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ============= | ============= | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-02T00:00:00 | 106.00        | 74.00       | 45.00       | 29.00       | 29.00       | 45.00       | 71.00       | 145.00      | 213.00      | 278.00       | 387.00        | 335.00        | 406.00       | 411.00      | 371.00      | 398.00      | 324.00      | 394.00      | 379.00      | 329.00      | 249.00      | 197.00       | 187.00        | 169.00        | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-03T00:00:00 | 109.00        | 74.00       | 55.00       | 37.00       | 26.00       | 25.00       | 47.00       | 74.00       | 111.00      | 204.00       | 249.00        | 351.00        | 374.00       | 350.00      | 308.00      | 291.00      | 313.00      | 253.00      | 242.00      | 217.00      | 210.00      | 144.00       | 125.00        | 79.00         | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-04T00:00:00 | 36.00         | 28.00       | 11.00       | 16.00       | 32.00       | 108.00      | 168.00      | 418.00      | 493.00      | 263.00       | 282.00        | 307.00        | 304.00       | 328.00      | 426.00      | 425.00      | 419.00      | 469.00      | 425.00      | 358.00      | 224.00      | 185.00       | 132.00        | 74.00         | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-05T00:00:00 | 42.00         | 28.00       | 16.00       | 12.00       | 34.00       | 109.00      | 193.00      | 397.00      | 499.00      | 241.00       | 255.00        | 294.00        | 310.00       | 382.00      | 393.00      | 479.00      | 441.00      | 476.00      | 446.00      | 424.00      | 305.00      | 219.00       | 171.00        | 76.00         | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-06T00:00:00 | 35.00         | 38.00       | 12.00       | 14.00       | 31.00       | 98.00       | 195.00      | 372.00      | 490.00      | 297.00       | 260.00        | 283.00        | 334.00       | 324.00      | 383.00      | 384.00      | 391.00      | 369.00      | 401.00      | 338.00      | 236.00      | 186.00       | 123.00        | 76.00         | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-07T00:00:00 | 33.00         | 26.00       | 14.00       | 22.00       | 31.00       | 100.00      | 171.00      | 382.00      | 460.00      | 273.00       | 215.00        | 263.00        | 254.00       | 303.00      | 151.00      | 409.00      | 422.00      | 364.00      | 356.00      | 339.00      | 275.00      | 225.00       | 169.00        | 104.00        | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-08T00:00:00 | 35.00         | 28.00       | 18.00       | 14.00       | 34.00       | 89.00       | 202.00      | 306.00      | 440.00      | 290.00       | 236.00        | 282.00        | 343.00       | 353.00      | 430.00      | 518.00      | 461.00      | 485.00      | 531.00      | 393.00      | 351.00      | 276.00       | 242.00        | 154.00        | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-09T00:00:00 | 110.00        | 73.00       | 46.00       | 32.00       | 29.00       | 44.00       | 73.00       | 150.00      | 217.00      | 283.00       | 395.00        | 342.00        | 414.00       | 419.00      | 379.00      | 406.00      | 330.00      | 402.00      | 387.00      | 336.00      | 254.00      | 201.00       | 191.00        | 174.00        | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-10T00:00:00 | 114.00        | 77.00       | 58.00       | 40.00       | 28.00       | 27.00       | 48.00       | 77.00       | 127.00      | 208.00       | 238.00        | 359.00        | 382.00       | 356.00      | 315.00      | 297.00      | 320.00      | 257.00      | 246.00      | 221.00      | 214.00      | 147.00       | 121.00        | 85.00         | 
| 1.00 | 2153.00    | HUGUENOT AVE | WOODROW RD | STAFFORD AVE | NB        | 2013-02-11T00:00:00 | 38.00         | 30.00       | 15.00       | 19.00       | 34.00       | 112.00      | 172.00      | 427.00      | 502.00      | 268.00       | 287.00        | 313.00        | 310.00       | 321.00      | 434.00      | 433.00      | 438.00      | 478.00      | 433.00      | 365.00      | 228.00      | 189.00       | 136.00        | 75.00         | 
```