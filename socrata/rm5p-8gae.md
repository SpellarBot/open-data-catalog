# Hospital Value-Based Purchasing (HVBP) ? Acute Myocardial Infarction Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-value-based-purchasing-hvbp-acute-myocardial-infarction-scores-7442a) |
| Metadata | [Link](https://data.medicare.gov/api/views/rm5p-8gae) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/rm5p-8gae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/rm5p-8gae/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | rm5p-8gae |
| Name | Hospital Value-Based Purchasing (HVBP) ? Acute Myocardial Infarction Scores |
| Category | Hospital Compare |
| Tags | hospital compare, hospital value-based purchasing, value-based purchasing, hvbp, ratings, quality, process of care, acute myocardial infarction, ami, heart attack, scores, rates, linking quality t... |
| Created | 2012-11-26T15:50:26Z |
| Publication Date | 2016-12-19T02:05:16Z |

## Description

A list of hospitals participating in the Hospital VBP Program and their performance rates and scores for the Clinical Process of Care AMI measures.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | provider_number               | Provider Number               | text      | text        |
| Yes      | series tag     | hospital_name                 | Hospital Name                 | text      | text        |
| No       |                | address                       | Address                       | text      | text        |
| Yes      | series tag     | city                          | City                          | text      | text        |
| Yes      | series tag     | state                         | State                         | text      | text        |
| Yes      | series tag     | zip_code                      | ZIP Code                      | text      | text        |
| Yes      | series tag     | county_name                   | County Name                   | text      | text        |
| Yes      | numeric metric | ami_7a_achievement_threshold  | AMI-7a Achievement Threshold  | number    | text        |
| Yes      | numeric metric | ami_7a_benchmark              | AMI-7a Benchmark              | number    | text        |
| Yes      | series tag     | ami_7a_baseline_rate          | AMI-7a Baseline Rate          | text      | text        |
| Yes      | series tag     | ami_7a_performance_rate       | AMI-7a Performance Rate       | text      | text        |
| Yes      | series tag     | ami_7a_achievement_points     | AMI-7a Achievement Points     | text      | text        |
| Yes      | series tag     | ami_7a_improvement_points     | AMI-7a Improvement Points     | text      | text        |
| Yes      | series tag     | ami_7a_measure_score          | AMI-7a Measure Score          | text      | text        |
| Yes      | numeric metric | ami_condition_procedure_score | AMI Condition/Procedure Score | number    | text        |
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
series e:rm5p-8gae d:2016-11-21T00:35:05.000Z t:ami_7a_measure_score="Not Available" t:ami_7a_performance_rate="Not Available" t:hospital_name="LAC/RANCHO LOS AMIGOS NATIONAL REHABILITATION  CTR" t:zip_code=90242 t:provider_number=050717 t:ami_7a_achievement_points="Not Available" t:state=CA t:ami_7a_improvement_points="Not Available" t:ami_7a_baseline_rate="Not Available" t:ami_condition_procedure_score="Not Available" t:county_name="LOS ANGELES" t:city=Downey m:ami_7a_achievement_threshold=0.954545 m:ami_7a_benchmark=1

series e:rm5p-8gae d:2016-11-21T00:35:05.000Z t:ami_7a_measure_score="Not Available" t:ami_7a_performance_rate="Not Available" t:hospital_name="TWIN CITIES HOSPITAL" t:zip_code=32578 t:provider_number=100054 t:ami_7a_achievement_points="Not Available" t:state=FL t:ami_7a_improvement_points="Not Available" t:ami_7a_baseline_rate="Not Available" t:ami_condition_procedure_score="Not Available" t:county_name=OKALOOSA t:city=Niceville m:ami_7a_achievement_threshold=0.954545 m:ami_7a_benchmark=1

series e:rm5p-8gae d:2016-11-21T00:35:05.000Z t:ami_7a_measure_score="Not Available" t:ami_7a_performance_rate="Not Available" t:hospital_name="ALTON MEMORIAL HOSPITAL" t:zip_code=62002 t:provider_number=140002 t:ami_7a_achievement_points="Not Available" t:state=IL t:ami_7a_improvement_points="Not Available" t:ami_7a_baseline_rate="Not Available" t:ami_condition_procedure_score="Not Available" t:county_name=MADISON t:city=Alton m:ami_7a_achievement_threshold=0.954545 m:ami_7a_benchmark=1
```

## Meta Commands

```ls
metric m:ami_7a_achievement_threshold p:float l:"AMI-7a Achievement Threshold" t:dataTypeName=number

metric m:ami_7a_benchmark p:float l:"AMI-7a Benchmark" t:dataTypeName=number

entity e:rm5p-8gae l:"Hospital Value-Based Purchasing (HVBP) ? Acute Myocardial Infarction Scores" t:url=https://data.medicare.gov/api/views/rm5p-8gae

property e:rm5p-8gae t:meta.view v:id=rm5p-8gae v:category="Hospital Compare" v:averageRating=0 v:name="Hospital Value-Based Purchasing (HVBP) ? Acute Myocardial Infarction Scores"

property e:rm5p-8gae t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:rm5p-8gae t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:rm5p-8gae t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | provider_number | hospital_name                                     | address                          | city          | state | zip_code | county_name    | ami_7a_achievement_threshold | ami_7a_benchmark | ami_7a_baseline_rate | ami_7a_performance_rate | ami_7a_achievement_points | ami_7a_improvement_points | ami_7a_measure_score | ami_condition_procedure_score | 
| =========== | =============== | ================================================= | ================================ | ============= | ===== | ======== | ============== | ============================ | ================ | ==================== | ======================= | ========================= | ========================= | ==================== | ============================= | 
| 1479688505  | 050717          | LAC/RANCHO LOS AMIGOS NATIONAL REHABILITATION CTR | 7601 EAST IMPERIAL HIGHWAY       | Downey        | CA    | 90242    | LOS ANGELES    | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 100054          | TWIN CITIES HOSPITAL                              | 2190 HWY 85 N                    | Niceville     | FL    | 32578    | OKALOOSA       | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 140002          | ALTON MEMORIAL HOSPITAL                           | ONE MEMORIAL DRIVE               | Alton         | IL    | 62002    | MADISON        | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 150069          | KING'S DAUGHTERS' HEALTH                          | 1373 EAST SR 62                  | Madison       | IN    | 47250    | JEFFERSON      | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 260032          | BARNES JEWISH HOSPITAL                            | ONE BARNES-JEWISH HOSPITAL PLAZA | Saint Louis   | MO    | 63110    | ST. LOUIS CITY | 0.954545                     | 1.000000         | 1.000000             | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 260141          | UNIVERSITY OF MISSOURI HEALTH CARE                | ONE HOSPITAL DRIVE               | Columbia      | MO    | 65201    | BOONE          | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 310038          | ROBERT WOOD JOHNSON UNIVERSITY HOSPITAL           | ONE ROBERT WOOD JOHNSON PLACE    | New Brunswick | NJ    | 08901    | MIDDLESEX      | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 310054          | HACKENSACK-UMC MOUNTAINSIDE                       | BAY AND HIGHLAND AVE             | Montclair     | NJ    | 07042    | ESSEX          | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 310110          | ROBERT WOOD JOHNSON UNIVERSITY HOSPITAL HAMILTON  | ONE HAMILTON HEALTH PLACE        | Hamilton      | NJ    | 08690    | MERCER         | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
| 1479688505  | 330386          | CATSKILL REGIONAL MEDICAL CENTER                  | 68 HARRIS BUSHVILLE ROAD         | Harris        | NY    | 12742    | SULLIVAN       | 0.954545                     | 1.000000         | Not Available        | Not Available           | Not Available             | Not Available             | Not Available        | Not Available                 | 
```