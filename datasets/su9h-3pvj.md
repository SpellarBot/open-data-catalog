# Hospital Value-Based Purchasing (HVBP) ? Efficiency Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-value-based-purchasing-hvbp-efficiency-scores-7b9f0) |
| Metadata | [Link](https://data.medicare.gov/api/views/su9h-3pvj) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/su9h-3pvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/su9h-3pvj/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | su9h-3pvj |
| Name | Hospital Value-Based Purchasing (HVBP) ? Efficiency Scores |
| Category | Hospital Compare |
| Tags | hospital, linking quality to payment |
| Created | 2014-10-22T18:58:03Z |
| Publication Date | 2016-12-19T02:05:11Z |

## Description

A list of hospitals participating in the Hospital VBP Program and their performance ratios and scores for the Efficiency Medicare Spending per Beneficiary (MSPB) measure.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | provider_number              | Provider_Number              | text      | text        |
| Yes      | series tag     | hospital_name                | Hospital_Name                | text      | text        |
| No       |                | address                      | Address                      | text      | text        |
| Yes      | series tag     | city                         | City                         | text      | text        |
| Yes      | series tag     | state                        | State                        | text      | text        |
| Yes      | series tag     | zip_code                     | ZIP_Code                     | text      | text        |
| Yes      | series tag     | county_name                  | County_Name                  | text      | text        |
| Yes      | numeric metric | mspb_1_achievement_threshold | MSPB-1 Achievement Threshold | number    | text        |
| Yes      | numeric metric | mspb_1_benchmark             | MSPB-1 Benchmark             | number    | text        |
| Yes      | numeric metric | mspb_1_baseline_rate         | MSPB-1 Baseline Rate         | number    | text        |
| Yes      | numeric metric | mspb_1_performance_rate      | MSPB-1 Performance Rate      | number    | text        |
| Yes      | series tag     | mspb_1_achievement_points    | MSPB-1 Achievement Points    | text      | text        |
| Yes      | series tag     | mspb_1_improvement_points    | MSPB-1 Improvement Points    | text      | text        |
| Yes      | series tag     | mspb_1_measure_score         | MSPB-1 Measure Score         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:su9h-3pvj d:2016-11-21T00:23:58.000Z t:mspb_1_measure_score="0 out of 10" t:hospital_name="LAWRENCE GENERAL HOSPITAL" t:mspb_1_achievement_points="0 out of 10" t:zip_code=01842 t:provider_number=220010 t:mspb_1_improvement_points="0 out of 9" t:state=MA t:county_name=ESSEX t:city=Lawrence m:mspb_1_performance_rate=1.06173 m:mspb_1_benchmark=0.829199 m:mspb_1_baseline_rate=1.078845 m:mspb_1_achievement_threshold=0.987666

series e:su9h-3pvj d:2016-11-21T00:23:58.000Z t:mspb_1_measure_score="6 out of 10" t:hospital_name="AROOSTOOK MEDICAL CENTER" t:mspb_1_achievement_points="6 out of 10" t:zip_code=04769 t:provider_number=200018 t:mspb_1_improvement_points="0 out of 9" t:state=ME t:county_name=AROOSTOOK t:city="Presque Isle" m:mspb_1_performance_rate=0.89207 m:mspb_1_benchmark=0.829199 m:mspb_1_baseline_rate=0.847671 m:mspb_1_achievement_threshold=0.987666

series e:su9h-3pvj d:2016-11-21T00:23:58.000Z t:mspb_1_measure_score="0 out of 10" t:hospital_name="HURON VALLEY-SINAI HOSPITAL" t:mspb_1_achievement_points="0 out of 10" t:zip_code=48382 t:provider_number=230277 t:mspb_1_improvement_points="0 out of 9" t:state=MI t:county_name=OAKLAND t:city=Commerce m:mspb_1_performance_rate=0.994563 m:mspb_1_benchmark=0.829199 m:mspb_1_baseline_rate=0.973267 m:mspb_1_achievement_threshold=0.987666
```

## Meta Commands

```ls
metric m:mspb_1_achievement_threshold p:float l:"MSPB-1 Achievement Threshold" t:dataTypeName=number

metric m:mspb_1_benchmark p:float l:"MSPB-1 Benchmark" t:dataTypeName=number

metric m:mspb_1_performance_rate p:float l:"MSPB-1 Performance Rate" t:dataTypeName=number

entity e:su9h-3pvj l:"Hospital Value-Based Purchasing (HVBP) ? Efficiency Scores" t:url=https://data.medicare.gov/api/views/su9h-3pvj

property e:su9h-3pvj t:meta.view v:id=su9h-3pvj v:category="Hospital Compare" v:averageRating=0 v:name="Hospital Value-Based Purchasing (HVBP) ? Efficiency Scores"

property e:su9h-3pvj t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:su9h-3pvj t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:su9h-3pvj t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | provider_number | hospital_name                              | address                     | city         | state | zip_code | county_name | mspb_1_achievement_threshold | mspb_1_benchmark | mspb_1_baseline_rate | mspb_1_performance_rate | mspb_1_achievement_points | mspb_1_improvement_points | mspb_1_measure_score | 
| =========== | =============== | ========================================== | =========================== | ============ | ===== | ======== | =========== | ============================ | ================ | ==================== | ======================= | ========================= | ========================= | ==================== | 
| 1479687838  | 220010          | LAWRENCE GENERAL HOSPITAL                  | ONE GENERAL STREET          | Lawrence     | MA    | 01842    | ESSEX       | 0.987666                     | 0.829199         | 1.078845             | 1.061730                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
| 1479687838  | 200018          | AROOSTOOK MEDICAL CENTER                   | PO BOX 151                  | Presque Isle | ME    | 04769    | AROOSTOOK   | 0.987666                     | 0.829199         | 0.847671             | 0.892070                | 6 out of 10               | 0 out of 9                | 6 out of 10          | 
| 1479687838  | 230277          | HURON VALLEY-SINAI HOSPITAL                | ONE WILLIAM CARLS DRIVE     | Commerce     | MI    | 48382    | OAKLAND     | 0.987666                     | 0.829199         | 0.973267             | 0.994563                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
| 1479687838  | 290045          | ST ROSE DOMINICAN HOSPITALS - SIENA CAMPUS | 3001 ST ROSE PARKWAY        | Henderson    | NV    | 89052    | CLARK       | 0.987666                     | 0.829199         | 1.126782             | 1.107985                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
| 1479687838  | 420015          | BAPTIST EASLEY HOSPITAL                    | PO BOX 2129                 | Easley       | SC    | 29641    | PICKENS     | 0.987666                     | 0.829199         | 0.988188             | 0.991301                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
| 1479687838  | 390093          | CLARION HOSPITAL                           | ONE HOSPITAL DRIVE          | Clarion      | PA    | 16214    | CLARION     | 0.987666                     | 0.829199         | 1.017094             | 1.025596                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
| 1479687838  | 390156          | MERCY FITZGERALD HOSPITAL                  | LANSDOWNE & BAILY RDS       | Darby        | PA    | 19023    | DELAWARE    | 0.987666                     | 0.829199         | 1.092765             | 1.026800                | 0 out of 10               | 2 out of 9                | 2 out of 10          | 
| 1479687838  | 330393          | UNIVERSITY HOSPITAL ( STONY BROOK )        | HEALTH SCIENCES CENTER SUNY | Stony Brook  | NY    | 11794    | SUFFOLK     | 0.987666                     | 0.829199         | 0.981879             | 0.983226                | 1 out of 10               | 0 out of 9                | 1 out of 10          | 
| 1479687838  | 470001          | CENTRAL VERMONT MEDICAL CENTER             | BOX 547                     | Barre        | VT    | 05641    | WASHINGTON  | 0.987666                     | 0.829199         | 0.974987             | 0.939273                | 3 out of 10               | 2 out of 9                | 3 out of 10          | 
| 1479687838  | 510001          | WEST VIRGINIA UNIVERSITY HOSPITALS         | MEDICAL CENTER DRIVE        | Morgantown   | WV    | 26506    | MONONGALIA  | 0.987666                     | 0.829199         | 1.001921             | 1.013473                | 0 out of 10               | 0 out of 9                | 0 out of 10          | 
```