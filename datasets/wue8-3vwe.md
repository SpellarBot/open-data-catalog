# Ambulatory Surgical Measures - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ambulatory-surgical-measures-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/wue8-3vwe) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/wue8-3vwe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/wue8-3vwe/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | wue8-3vwe |
| Name | Ambulatory Surgical Measures - National |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care |
| Created | 2015-07-28T14:35:28Z |
| Publication Date | 2016-12-19T02:01:59Z |

## Description

The Ambulatory Surgical Center Quality Reporting (ASCQR) Program seeks to make care safer and more efficient through quality reporting. ASCs eligible for this program may have their Medicare payments reduced if they do not report data for these measures.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | asc1_measure_nat_rate       | ASC1_Measure_Nat_Rate       | number    | text        |
| Yes      | numeric metric | asc2_measure_nat_rate       | ASC2_Measure_Nat_Rate       | number    | text        |
| Yes      | numeric metric | asc3_measure_nat_rate       | ASC3_Measure_Nat_Rate       | number    | text        |
| Yes      | numeric metric | asc4_measure_nat_rate       | ASC4_Measure_Nat_Rate       | number    | text        |
| Yes      | numeric metric | asc5_measure_nat_rate       | ASC5_Measure_Nat_Rate       | number    | text        |
| Yes      | numeric metric | asc_6_nat_pct               | ASC_6_Nat_PCT               | number    | text        |
| Yes      | numeric metric | avg_asc_7_nat               | Avg_ASC_7_Nat               | number    | text        |
| Yes      | numeric metric | avg_gastrointestinal_nat    | Avg_Gastrointestinal_Nat    | number    | text        |
| Yes      | numeric metric | avg_eye_nat                 | Avg_Eye_Nat                 | number    | text        |
| Yes      | numeric metric | avg_genitourinary_nat       | Avg_Genitourinary_Nat       | number    | text        |
| Yes      | numeric metric | avg_multi_system_nat        | Avg_Multi_System_Nat        | number    | text        |
| Yes      | numeric metric | avg_musculoskeletal_nat     | Avg_Musculoskeletal_Nat     | number    | text        |
| Yes      | numeric metric | avg_nervous_system_nat      | Avg_Nervous_System_Nat      | number    | text        |
| Yes      | numeric metric | avg_respiratory_nat         | Avg_Respiratory_Nat         | number    | text        |
| Yes      | numeric metric | avg_skin_nat                | Avg_Skin_Nat                | number    | text        |
| Yes      | numeric metric | avg_asc_8_nat_rate          | Avg_ASC_8_Nat_Rate          | number    | text        |
| Yes      | numeric metric | avg_asc_9_nat_rate          | Avg_ASC_9_Nat_Rate          | number    | text        |
| Yes      | numeric metric | avg_asc_10_nat_rate         | Avg_ASC_10_Nat_Rate         | number    | text        |
| Yes      | numeric metric | avg_asc_11_nat_rate         | Avg_ASC_11_Nat_Rate         | number    | text        |
| Yes      | numeric metric | median_asc_7_nat            | Median_ASC_7_Nat            | number    | text        |
| Yes      | numeric metric | median_gastrointestinal_nat | Median_Gastrointestinal_Nat | number    | text        |
| Yes      | numeric metric | median_eye_nat              | Median_Eye_Nat              | number    | text        |
| Yes      | numeric metric | median_genitourinary_nat    | Median_Genitourinary_Nat    | number    | text        |
| Yes      | numeric metric | median_multi_system_nat     | Median_Multi_System_Nat     | number    | text        |
| Yes      | numeric metric | median_musculoskeletal_nat  | Median_Musculoskeletal_Nat  | number    | text        |
| Yes      | numeric metric | median_nervous_system_nat   | Median_Nervous_System_Nat   | number    | text        |
| Yes      | numeric metric | median_respiratory_nat      | Median_Respiratory_Nat      | number    | text        |
| Yes      | numeric metric | median_skin_nat             | Median_Skin_Nat             | number    | text        |
| Yes      | numeric metric | median_asc_8_nat_rate       | Median_ASC_8_Nat_Rate       | number    | text        |
| Yes      | numeric metric | median_asc_9_nat_rate       | Median_ASC_9_Nat_Rate       | number    | text        |
| Yes      | numeric metric | median_asc_10_nat_rate      | Median_ASC_10_Nat_Rate      | number    | text        |
| Yes      | numeric metric | median_asc_11_nat_rate      | Median_ASC_11_Nat_Rate      | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wue8-3vwe d:2015-01-01T00:00:00.000Z m:median_nervous_system_nat=824 m:median_asc_11_nat_rate=100 m:avg_asc_9_nat_rate=80.98 m:asc3_measure_nat_rate=0.022 m:asc4_measure_nat_rate=0.41 m:avg_respiratory_nat=206 m:median_multi_system_nat=30 m:avg_multi_system_nat=274 m:avg_asc_7_nat=4149 m:asc5_measure_nat_rate=956.44 m:median_asc_8_nat_rate=81.82 m:median_asc_7_nat=3146 m:median_musculoskeletal_nat=460 m:avg_gastrointestinal_nat=3552 m:median_asc_10_nat_rate=91.57 m:avg_skin_nat=146 m:avg_eye_nat=1745 m:avg_asc_11_nat_rate=96.54 m:median_skin_nat=33 m:median_gastrointestinal_nat=2261 m:asc_6_nat_pct=99.81 m:avg_nervous_system_nat=1751 m:asc1_measure_nat_rate=0.181 m:avg_genitourinary_nat=452 m:median_respiratory_nat=96 m:median_genitourinary_nat=96 m:asc2_measure_nat_rate=0.095 m:median_eye_nat=1132 m:avg_asc_10_nat_rate=79.9 m:median_asc_9_nat_rate=91.93 m:avg_asc_8_nat_rate=76.13 m:avg_musculoskeletal_nat=816
```

## Meta Commands

```ls
metric m:asc1_measure_nat_rate p:float l:ASC1_Measure_Nat_Rate t:dataTypeName=number

metric m:asc2_measure_nat_rate p:float l:ASC2_Measure_Nat_Rate t:dataTypeName=number

metric m:asc3_measure_nat_rate p:float l:ASC3_Measure_Nat_Rate t:dataTypeName=number

metric m:asc4_measure_nat_rate p:float l:ASC4_Measure_Nat_Rate t:dataTypeName=number

metric m:asc5_measure_nat_rate p:float l:ASC5_Measure_Nat_Rate t:dataTypeName=number

metric m:asc_6_nat_pct p:float l:ASC_6_Nat_PCT t:dataTypeName=number

metric m:avg_asc_7_nat p:integer l:Avg_ASC_7_Nat t:dataTypeName=number

metric m:avg_gastrointestinal_nat p:integer l:Avg_Gastrointestinal_Nat t:dataTypeName=number

metric m:avg_eye_nat p:integer l:Avg_Eye_Nat t:dataTypeName=number

metric m:avg_genitourinary_nat p:integer l:Avg_Genitourinary_Nat t:dataTypeName=number

metric m:avg_multi_system_nat p:integer l:Avg_Multi_System_Nat t:dataTypeName=number

metric m:avg_musculoskeletal_nat p:integer l:Avg_Musculoskeletal_Nat t:dataTypeName=number

metric m:avg_nervous_system_nat p:integer l:Avg_Nervous_System_Nat t:dataTypeName=number

metric m:avg_respiratory_nat p:integer l:Avg_Respiratory_Nat t:dataTypeName=number

metric m:avg_skin_nat p:integer l:Avg_Skin_Nat t:dataTypeName=number

metric m:avg_asc_8_nat_rate p:float l:Avg_ASC_8_Nat_Rate t:dataTypeName=number

metric m:avg_asc_9_nat_rate p:float l:Avg_ASC_9_Nat_Rate t:dataTypeName=number

metric m:avg_asc_10_nat_rate p:float l:Avg_ASC_10_Nat_Rate t:dataTypeName=number

metric m:avg_asc_11_nat_rate p:float l:Avg_ASC_11_Nat_Rate t:dataTypeName=number

metric m:median_asc_7_nat p:integer l:Median_ASC_7_Nat t:dataTypeName=number

metric m:median_gastrointestinal_nat p:integer l:Median_Gastrointestinal_Nat t:dataTypeName=number

metric m:median_eye_nat p:integer l:Median_Eye_Nat t:dataTypeName=number

metric m:median_genitourinary_nat p:integer l:Median_Genitourinary_Nat t:dataTypeName=number

metric m:median_multi_system_nat p:integer l:Median_Multi_System_Nat t:dataTypeName=number

metric m:median_musculoskeletal_nat p:integer l:Median_Musculoskeletal_Nat t:dataTypeName=number

metric m:median_nervous_system_nat p:integer l:Median_Nervous_System_Nat t:dataTypeName=number

metric m:median_respiratory_nat p:integer l:Median_Respiratory_Nat t:dataTypeName=number

metric m:median_skin_nat p:integer l:Median_Skin_Nat t:dataTypeName=number

metric m:median_asc_8_nat_rate p:float l:Median_ASC_8_Nat_Rate t:dataTypeName=number

metric m:median_asc_9_nat_rate p:float l:Median_ASC_9_Nat_Rate t:dataTypeName=number

metric m:median_asc_10_nat_rate p:float l:Median_ASC_10_Nat_Rate t:dataTypeName=number

metric m:median_asc_11_nat_rate p:integer l:Median_ASC_11_Nat_Rate t:dataTypeName=number

entity e:wue8-3vwe l:"Ambulatory Surgical Measures - National" t:url=https://data.medicare.gov/api/views/wue8-3vwe

property e:wue8-3vwe t:meta.view v:id=wue8-3vwe v:category="Hospital Compare" v:averageRating=0 v:name="Ambulatory Surgical Measures - National"

property e:wue8-3vwe t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:wue8-3vwe t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:wue8-3vwe t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| year | asc1_measure_nat_rate | asc2_measure_nat_rate | asc3_measure_nat_rate | asc4_measure_nat_rate | asc5_measure_nat_rate | asc_6_nat_pct | avg_asc_7_nat | avg_gastrointestinal_nat | avg_eye_nat | avg_genitourinary_nat | avg_multi_system_nat | avg_musculoskeletal_nat | avg_nervous_system_nat | avg_respiratory_nat | avg_skin_nat | avg_asc_8_nat_rate | avg_asc_9_nat_rate | avg_asc_10_nat_rate | avg_asc_11_nat_rate | median_asc_7_nat | median_gastrointestinal_nat | median_eye_nat | median_genitourinary_nat | median_multi_system_nat | median_musculoskeletal_nat | median_nervous_system_nat | median_respiratory_nat | median_skin_nat | median_asc_8_nat_rate | median_asc_9_nat_rate | median_asc_10_nat_rate | median_asc_11_nat_rate | 
| ==== | ===================== | ===================== | ===================== | ===================== | ===================== | ============= | ============= | ======================== | =========== | ===================== | ==================== | ======================= | ====================== | =================== | ============ | ================== | ================== | =================== | =================== | ================ | =========================== | ============== | ======================== | ======================= | ========================== | ========================= | ====================== | =============== | ===================== | ===================== | ====================== | ====================== | 
| 2015 | 0.181                 | 0.095                 | 0.022                 | 0.41                  | 956.44                | 99.81         | 4149          | 3552                     | 1745        | 452                   | 274                  | 816                     | 1751                   | 206                 | 146          | 76.13              | 80.98              | 79.9                | 96.54               | 3146             | 2261                        | 1132           | 96                       | 30                      | 460                        | 824                       | 96                     | 33              | 81.82                 | 91.93                 | 91.57                  | 100                    | 
```