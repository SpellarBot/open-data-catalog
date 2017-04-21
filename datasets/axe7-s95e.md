# Ambulatory Surgical Measures - State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ambulatory-surgical-measures-state) |
| Metadata | [Link](https://data.medicare.gov/api/views/axe7-s95e) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/axe7-s95e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/axe7-s95e/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | axe7-s95e |
| Name | Ambulatory Surgical Measures - State |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care |
| Created | 2015-07-28T14:38:04Z |
| Publication Date | 2016-12-19T02:02:04Z |

## Description

The Ambulatory Surgical Center Quality Reporting (ASCQR) Program seeks to make care safer and more efficient through quality reporting. ASCs eligible for this program may have their Medicare payments reduced if they do not report data for these measures.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | state                         | State                         | text      | text        |
| Yes      | time           | year                          | Year                          | number    | text        |
| Yes      | series tag     | asc1_measure_state_rate       | ASC1_Measure_State_Rate       | text      | text        |
| Yes      | series tag     | asc2_measure_state_rate       | ASC2_Measure_State_Rate       | text      | text        |
| Yes      | series tag     | asc3_measure_state_rate       | ASC3_Measure_State_Rate       | text      | text        |
| Yes      | series tag     | asc4_measure_state_rate       | ASC4_Measure_State_Rate       | text      | text        |
| Yes      | series tag     | asc5_measure_state_rate       | ASC5_Measure_State_Rate       | text      | text        |
| Yes      | numeric metric | asc_6_state_pct               | ASC_6_State_PCT               | number    | text        |
| Yes      | numeric metric | avg_asc_7_state               | Avg_ASC_7_State               | number    | text        |
| Yes      | numeric metric | avg_gastrointestinal_state    | Avg_Gastrointestinal_State    | number    | text        |
| Yes      | numeric metric | avg_eye_state                 | Avg_Eye_State                 | number    | text        |
| Yes      | numeric metric | avg_genitourinary_state       | Avg_Genitourinary_State       | number    | text        |
| Yes      | numeric metric | avg_multi_system_state        | Avg_Multi_System_State        | number    | text        |
| Yes      | numeric metric | avg_musculoskeletal_state     | Avg_Musculoskeletal_State     | number    | text        |
| Yes      | numeric metric | avg_nervous_system_state      | Avg_Nervous_System_State      | number    | text        |
| Yes      | numeric metric | avg_respiratory_state         | Avg_Respiratory_State         | number    | text        |
| Yes      | numeric metric | avg_skin_state                | Avg_Skin_State                | number    | text        |
| Yes      | series tag     | avg_asc_8_state_rate          | Avg_ASC_8_State_Rate          | text      | text        |
| Yes      | series tag     | avg_asc_9_state_rate          | Avg_ASC_9_State_Rate          | text      | text        |
| Yes      | series tag     | avg_asc_10_state_rate         | Avg_ASC_10_State_Rate         | text      | text        |
| Yes      | series tag     | avg_asc_11_state_rate         | Avg_ASC_11_State_Rate         | text      | text        |
| Yes      | numeric metric | median_asc_7_state            | Median_ASC_7_State            | number    | text        |
| Yes      | numeric metric | median_gastrointestinal_state | Median_Gastrointestinal_State | number    | text        |
| Yes      | numeric metric | median_eye_state              | Median_Eye_State              | number    | text        |
| Yes      | numeric metric | median_genitourinary_state    | Median_Genitourinary_State    | number    | text        |
| Yes      | numeric metric | median_multi_system_state     | Median_Multi_System_State     | number    | text        |
| Yes      | numeric metric | median_musculoskeletal_state  | Median_Musculoskeletal_State  | number    | text        |
| Yes      | numeric metric | median_nervous_system_state   | Median_Nervous_System_State   | number    | text        |
| Yes      | numeric metric | median_respiratory_state      | Median_Respiratory_State      | number    | text        |
| Yes      | numeric metric | median_skin_state             | Median_Skin_State             | number    | text        |
| Yes      | series tag     | median_asc_8_state_rate       | Median_ASC_8_State_Rate       | text      | text        |
| Yes      | series tag     | median_asc_9_state_rate       | Median_ASC_9_State_Rate       | text      | text        |
| Yes      | series tag     | median_asc_10_state_rate      | Median_ASC_10_State_Rate      | text      | text        |
| Yes      | series tag     | median_asc_11_state_rate      | Median_ASC_11_State_Rate      | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:axe7-s95e d:2015-01-01T00:00:00.000Z t:median_asc_11_state_rate=100 t:asc1_measure_state_rate=0.258 t:state=AK t:asc3_measure_state_rate=0.129 t:avg_asc_9_state_rate=90.87 t:asc2_measure_state_rate=0.387 t:median_asc_8_state_rate=70.52 t:median_asc_10_state_rate=87.98 t:asc4_measure_state_rate=1.42 t:avg_asc_10_state_rate=86.42 t:avg_asc_11_state_rate=100 t:asc5_measure_state_rate=978.09 t:median_asc_9_state_rate=93.05 t:avg_asc_8_state_rate=67.58 m:median_musculoskeletal_state=442 m:median_respiratory_state=234 m:median_multi_system_state=2 m:avg_nervous_system_state=1207 m:median_skin_state=34 m:avg_eye_state=632 m:median_gastrointestinal_state=1104 m:median_asc_7_state=2423 m:asc_6_state_pct=100 m:avg_gastrointestinal_state=1921 m:avg_musculoskeletal_state=611 m:avg_asc_7_state=2361 m:avg_multi_system_state=2 m:avg_skin_state=43 m:avg_respiratory_state=233 m:median_genitourinary_state=66 m:avg_genitourinary_state=103 m:median_nervous_system_state=540 m:median_eye_state=486

series e:axe7-s95e d:2015-01-01T00:00:00.000Z t:median_asc_11_state_rate=93.33 t:asc1_measure_state_rate=0.022 t:state=AL t:asc3_measure_state_rate=0.022 t:avg_asc_9_state_rate=67.88 t:asc2_measure_state_rate=0.146 t:median_asc_8_state_rate=69.94 t:median_asc_10_state_rate=89.63 t:asc4_measure_state_rate=0.472 t:avg_asc_10_state_rate=75.67 t:avg_asc_11_state_rate=93.33 t:asc5_measure_state_rate=986.38 t:median_asc_9_state_rate=72.34 t:avg_asc_8_state_rate=67.93 m:median_musculoskeletal_state=951 m:median_respiratory_state=221 m:median_multi_system_state=45 m:avg_nervous_system_state=3027 m:median_skin_state=56 m:avg_eye_state=2245 m:median_gastrointestinal_state=3048 m:median_asc_7_state=6977 m:asc_6_state_pct=100 m:avg_gastrointestinal_state=4292 m:avg_musculoskeletal_state=1344 m:avg_asc_7_state=8020 m:avg_multi_system_state=44 m:avg_skin_state=162 m:avg_respiratory_state=350 m:median_genitourinary_state=87 m:avg_genitourinary_state=79 m:median_nervous_system_state=2006 m:median_eye_state=1396

series e:axe7-s95e d:2015-01-01T00:00:00.000Z t:median_asc_11_state_rate=100 t:asc1_measure_state_rate=0.108 t:state=AR t:asc3_measure_state_rate=0 t:avg_asc_9_state_rate=63.71 t:asc2_measure_state_rate=0.585 t:median_asc_8_state_rate=83.5 t:median_asc_10_state_rate=91.1 t:asc4_measure_state_rate=0.277 t:avg_asc_10_state_rate=76.75 t:avg_asc_11_state_rate=100 t:asc5_measure_state_rate=890.92 t:median_asc_9_state_rate=77.78 t:avg_asc_8_state_rate=77.37 m:median_musculoskeletal_state=640 m:median_respiratory_state=55 m:median_multi_system_state=157 m:avg_nervous_system_state=1439 m:median_skin_state=35 m:avg_eye_state=1476 m:median_gastrointestinal_state=3193 m:median_asc_7_state=2667 m:asc_6_state_pct=100 m:avg_gastrointestinal_state=3856 m:avg_musculoskeletal_state=724 m:avg_asc_7_state=3461 m:avg_multi_system_state=1104 m:avg_skin_state=157 m:avg_respiratory_state=76 m:median_genitourinary_state=7 m:avg_genitourinary_state=151 m:median_nervous_system_state=301 m:median_eye_state=998
```

## Meta Commands

```ls
metric m:asc_6_state_pct p:integer l:ASC_6_State_PCT t:dataTypeName=number

metric m:avg_asc_7_state p:integer l:Avg_ASC_7_State t:dataTypeName=number

metric m:avg_gastrointestinal_state p:integer l:Avg_Gastrointestinal_State t:dataTypeName=number

metric m:avg_eye_state p:integer l:Avg_Eye_State t:dataTypeName=number

metric m:avg_genitourinary_state p:integer l:Avg_Genitourinary_State t:dataTypeName=number

metric m:avg_multi_system_state p:integer l:Avg_Multi_System_State t:dataTypeName=number

metric m:avg_musculoskeletal_state p:integer l:Avg_Musculoskeletal_State t:dataTypeName=number

metric m:avg_nervous_system_state p:integer l:Avg_Nervous_System_State t:dataTypeName=number

metric m:avg_respiratory_state p:integer l:Avg_Respiratory_State t:dataTypeName=number

metric m:avg_skin_state p:integer l:Avg_Skin_State t:dataTypeName=number

metric m:median_asc_7_state p:integer l:Median_ASC_7_State t:dataTypeName=number

metric m:median_gastrointestinal_state p:integer l:Median_Gastrointestinal_State t:dataTypeName=number

metric m:median_eye_state p:integer l:Median_Eye_State t:dataTypeName=number

metric m:median_genitourinary_state p:integer l:Median_Genitourinary_State t:dataTypeName=number

metric m:median_multi_system_state p:integer l:Median_Multi_System_State t:dataTypeName=number

metric m:median_musculoskeletal_state p:integer l:Median_Musculoskeletal_State t:dataTypeName=number

metric m:median_nervous_system_state p:integer l:Median_Nervous_System_State t:dataTypeName=number

metric m:median_respiratory_state p:integer l:Median_Respiratory_State t:dataTypeName=number

metric m:median_skin_state p:integer l:Median_Skin_State t:dataTypeName=number

entity e:axe7-s95e l:"Ambulatory Surgical Measures - State" t:url=https://data.medicare.gov/api/views/axe7-s95e

property e:axe7-s95e t:meta.view v:id=axe7-s95e v:category="Hospital Compare" v:averageRating=0 v:name="Ambulatory Surgical Measures - State"

property e:axe7-s95e t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:axe7-s95e t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:axe7-s95e t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| state | year | asc1_measure_state_rate | asc2_measure_state_rate | asc3_measure_state_rate | asc4_measure_state_rate | asc5_measure_state_rate | asc_6_state_pct | avg_asc_7_state | avg_gastrointestinal_state | avg_eye_state | avg_genitourinary_state | avg_multi_system_state | avg_musculoskeletal_state | avg_nervous_system_state | avg_respiratory_state | avg_skin_state | avg_asc_8_state_rate | avg_asc_9_state_rate | avg_asc_10_state_rate | avg_asc_11_state_rate | median_asc_7_state | median_gastrointestinal_state | median_eye_state | median_genitourinary_state | median_multi_system_state | median_musculoskeletal_state | median_nervous_system_state | median_respiratory_state | median_skin_state | median_asc_8_state_rate | median_asc_9_state_rate | median_asc_10_state_rate | median_asc_11_state_rate | 
| ===== | ==== | ======================= | ======================= | ======================= | ======================= | ======================= | =============== | =============== | ========================== | ============= | ======================= | ====================== | ========================= | ======================== | ===================== | ============== | ==================== | ==================== | ===================== | ===================== | ================== | ============================= | ================ | ========================== | ========================= | ============================ | =========================== | ======================== | ================= | ======================= | ======================= | ======================== | ======================== | 
| AK    | 2015 | 0.258                   | 0.387                   | 0.129                   | 1.42                    | 978.09                  | 100             | 2361            | 1921                       | 632           | 103                     | 2                      | 611                       | 1207                     | 233                   | 43             | 67.58                | 90.87                | 86.42                 | 100                   | 2423               | 1104                          | 486              | 66                         | 2                         | 442                          | 540                         | 234                      | 34                | 70.52                   | 93.05                   | 87.98                    | 100                      | 
| AL    | 2015 | 0.022                   | 0.146                   | 0.022                   | 0.472                   | 986.38                  | 100             | 8020            | 4292                       | 2245          | 79                      | 44                     | 1344                      | 3027                     | 350                   | 162            | 67.93                | 67.88                | 75.67                 | 93.33                 | 6977               | 3048                          | 1396             | 87                         | 45                        | 951                          | 2006                        | 221                      | 56                | 69.94                   | 72.34                   | 89.63                    | 93.33                    | 
| AR    | 2015 | 0.108                   | 0.585                   | 0                       | 0.277                   | 890.92                  | 100             | 3461            | 3856                       | 1476          | 151                     | 1104                   | 724                       | 1439                     | 76                    | 157            | 77.37                | 63.71                | 76.75                 | 100                   | 2667               | 3193                          | 998              | 7                          | 157                       | 640                          | 301                         | 55                       | 35                | 83.5                    | 77.78                   | 91.1                     | 100                      | 
| AZ    | 2015 | 0.148                   | 0.096                   | 0.066                   | 0.428                   | 968.12                  | 98.44           | 4289            | 4106                       | 1923          | 181                     | 32                     | 715                       | 3135                     | 462                   | 213            | 64.38                | 86.08                | 80.05                 | 100                   | 3437               | 2758                          | 1224             | 116                        | 14                        | 536                          | 670                         | 130                      | 42                | 67.57                   | 90.68                   | 93.82                    | 100                      | 
| CA    | 2015 | 0.183                   | 0.079                   | 0.011                   | 0.247                   | 961.11                  | 100             | 3560            | 2863                       | 1184          | 165                     | 324                    | 688                       | 1544                     | 183                   | 113            | 75.68                | 74.98                | 73.58                 | 94.07                 | 2646               | 1847                          | 822              | 51                         | 31                        | 413                          | 840                         | 84                       | 25                | 82.55                   | 84.93                   | 83.63                    | 100                      | 
| CO    | 2015 | 0.075                   | 0.075                   | 0.021                   | 0.428                   | 871.13                  | 100             | 4242            | 2819                       | 1468          | 336                     | 144                    | 867                       | 1921                     | 262                   | 76             | 95.12                | 91.33                | 80.98                 | N/A (5)               | 3664               | 1597                          | 503              | 50                         | 13                        | 569                          | 1425                        | 162                      | 14                | 96.33                   | 97.06                   | 93.23                    | N/A (5)                  | 
| CT    | 2015 | 0.123                   | 0.123                   | 0                       | 0.614                   | 987.38                  | 100             | 5050            | 4846                       | 2569          | 251                     | 1649                   | 1460                      | 1522                     | 402                   | 36             | 83.41                | 86.86                | 78.16                 | N/A (5)               | 4394               | 4735                          | 1863             | 204                        | 1649                      | 1159                         | 1751                        | 442                      | 12                | 85.57                   | 98.31                   | 94.56                    | N/A (5)                  | 
| DC    | 2015 | 0                       | 0.722                   | 0                       | 0                       | 916.67                  | 100             | 2789            | 2045                       | 204           | 70                      | 0                      | 109                       | 834                      | 0                     | 5              | 85.58                | 72.98                | 94.27                 | N/A (5)               | 3373               | 1568                          | 204              | 70                         | 0                         | 109                          | 834                         | 0                        | 5                 | 85.58                   | 96.88                   | 100                      | N/A (5)                  | 
| DE    | 2015 | 0.22                    | 0.138                   | 0.083                   | 0.55                    | 972.12                  | 100             | 4430            | 3106                       | 1575          | 495                     | 153                    | 814                       | 2244                     | 136                   | 228            | 72.89                | 79.23                | 89.36                 | N/A (5)               | 3313               | 1987                          | 1592             | 513                        | 123                       | 676                          | 1725                        | 91                       | 75                | 79.13                   | 93.13                   | 91.67                    | N/A (5)                  | 
| FL    | 2015 | 0.176                   | 0.092                   | 0.055                   | 0.395                   | 964.47                  | 100             | 5054            | 4150                       | 1860          | 400                     | 215                    | 829                       | 1818                     | 156                   | 145            | 58.89                | 78.96                | 83.09                 | 99.06                 | 3732               | 3020                          | 1004             | 108                        | 33                        | 459                          | 929                         | 88                       | 68                | 60.67                   | 89.29                   | 91.89                    | 100                      | 
```