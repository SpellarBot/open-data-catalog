# Hospital Value-Based Purchasing (HVBP) ? Outcome Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-value-based-purchasing-hvbp-outcome-scores-29c85) |
| Metadata | [Link](https://data.medicare.gov/api/views/pudb-wetr) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/pudb-wetr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/pudb-wetr/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | pudb-wetr |
| Name | Hospital Value-Based Purchasing (HVBP) ? Outcome Scores |
| Category | Hospital Compare |
| Tags | hvbp, linking quality to payment, outcome |
| Created | 2013-10-15T18:04:03Z |
| Publication Date | 2016-12-19T02:07:11Z |

## Description

A list of hospitals participating in the Hospital VBP Program and their performance rates and scores for the outcome measures.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | provider_number                   | Provider Number                   | text      | text        |
| Yes      | series tag     | hospital_name                     | Hospital Name                     | text      | text        |
| No       |                | address                           | Address                           | text      | text        |
| Yes      | series tag     | city                              | City                              | text      | text        |
| Yes      | series tag     | state                             | State                             | text      | text        |
| Yes      | series tag     | zip_code                          | ZIP Code                          | text      | text        |
| Yes      | series tag     | county_name                       | County Name                       | text      | text        |
| Yes      | numeric metric | mort_30_ami_achievement_threshold | MORT-30-AMI Achievement Threshold | number    | text        |
| Yes      | numeric metric | mort_30_ami_benchmark             | MORT-30-AMI Benchmark             | number    | text        |
| Yes      | numeric metric | mort_30_ami_baseline_rate         | MORT-30-AMI Baseline Rate         | number    | text        |
| Yes      | numeric metric | mort_30_ami_performance_rate      | MORT-30-AMI Performance Rate      | number    | text        |
| Yes      | series tag     | mort_30_ami_achievement_points    | MORT-30-AMI Achievement Points    | text      | text        |
| Yes      | series tag     | mort_30_ami_improvement_points    | MORT-30-AMI Improvement Points    | text      | text        |
| Yes      | series tag     | mort_30_ami_measure_score         | MORT-30-AMI Measure Score         | text      | text        |
| Yes      | numeric metric | mort_30_hf_achievement_threshold  | MORT-30-HF Achievement Threshold  | number    | text        |
| Yes      | numeric metric | mort_30_hf_benchmark              | MORT-30-HF Benchmark              | number    | text        |
| Yes      | numeric metric | mort_30_hf_baseline_rate          | MORT-30-HF Baseline Rate          | number    | text        |
| Yes      | numeric metric | mort_30_hf_performance_rate       | MORT-30-HF Performance Rate       | number    | text        |
| Yes      | series tag     | mort_30_hf_achievement_points     | MORT-30-HF Achievement Points     | text      | text        |
| Yes      | series tag     | mort_30_hf_improvement_points     | MORT-30-HF Improvement Points     | text      | text        |
| Yes      | series tag     | mort_30_hf_measure_score          | MORT-30-HF Measure Score          | text      | text        |
| Yes      | numeric metric | mort_30_pn_achievement_threshold  | MORT-30-PN Achievement Threshold  | number    | text        |
| Yes      | numeric metric | mort_30_pn_benchmark              | MORT-30-PN Benchmark              | number    | text        |
| Yes      | numeric metric | mort_30_pn_baseline_rate          | MORT-30-PN Baseline Rate          | number    | text        |
| Yes      | numeric metric | mort_30_pn_performance_rate       | MORT-30-PN Performance Rate       | number    | text        |
| Yes      | series tag     | mort_30_pn_achievement_points     | MORT-30-PN Achievement Points     | text      | text        |
| Yes      | series tag     | mort_30_pn_improvement_points     | MORT-30-PN Improvement Points     | text      | text        |
| Yes      | series tag     | mort_30_pn_measure_score          | MORT-30-PN Measure Score          | text      | text        |
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
series e:pudb-wetr d:2016-11-16T15:57:35.000Z t:hospital_name="MARSHALL MEDICAL CENTER SOUTH" t:zip_code=35957 t:mort_30_hf_improvement_points="1 out of 9" t:provider_number=010005 t:mort_30_ami_improvement_points="Not Available" t:state=AL t:mort_30_hf_achievement_points="0 out of 10" t:city=Boaz t:mort_30_pn_measure_score="1 out of 10" t:mort_30_pn_improvement_points="1 out of 9" t:mort_30_ami_achievement_points="3 out of 10" t:mort_30_ami_measure_score="3 out of 10" t:county_name=MARSHALL t:mort_30_pn_achievement_points="0 out of 10" t:mort_30_hf_measure_score="1 out of 10" m:mort_30_ami_benchmark=0.871669 m:mort_30_pn_achievement_threshold=0.882986 m:mort_30_ami_performance_rate=0.857198 m:mort_30_hf_achievement_threshold=0.881794 m:mort_30_ami_baseline_rate=0.843034 m:mort_30_hf_baseline_rate=0.842804 m:mort_30_hf_benchmark=0.903985 m:mort_30_ami_achievement_threshold=0.851458 m:mort_30_pn_performance_rate=0.860678 m:mort_30_pn_baseline_rate=0.850177 m:mort_30_hf_performance_rate=0.851384 m:mort_30_pn_benchmark=0.908124

series e:pudb-wetr d:2016-11-16T15:57:35.000Z t:hospital_name="CRESTWOOD MEDICAL CENTER" t:zip_code=35801 t:mort_30_hf_improvement_points="0 out of 9" t:provider_number=010131 t:mort_30_ami_improvement_points="7 out of 9" t:state=AL t:mort_30_hf_achievement_points="0 out of 10" t:city=Huntsville t:mort_30_pn_measure_score="0 out of 10" t:mort_30_pn_improvement_points="0 out of 9" t:mort_30_ami_achievement_points="8 out of 10" t:mort_30_ami_measure_score="8 out of 10" t:county_name=MADISON t:mort_30_pn_achievement_points="0 out of 10" t:mort_30_hf_measure_score="0 out of 10" m:mort_30_ami_benchmark=0.871669 m:mort_30_pn_achievement_threshold=0.882986 m:mort_30_ami_performance_rate=0.867794 m:mort_30_hf_achievement_threshold=0.881794 m:mort_30_ami_baseline_rate=0.858001 m:mort_30_hf_baseline_rate=0.867205 m:mort_30_hf_benchmark=0.903985 m:mort_30_ami_achievement_threshold=0.851458 m:mort_30_pn_performance_rate=0.865677 m:mort_30_pn_baseline_rate=0.87965 m:mort_30_hf_performance_rate=0.867608 m:mort_30_pn_benchmark=0.908124

series e:pudb-wetr d:2016-11-16T15:57:35.000Z t:hospital_name="TUBA CITY REGIONAL HEALTH CARE CORPORATION" t:zip_code=86045 t:mort_30_hf_improvement_points="Not Available" t:provider_number=030073 t:mort_30_ami_improvement_points="Not Available" t:state=AZ t:mort_30_hf_achievement_points="Not Available" t:city="Tuba City" t:mort_30_pn_measure_score="4 out of 10" t:mort_30_pn_improvement_points="4 out of 9" t:mort_30_ami_achievement_points="Not Available" t:mort_30_ami_measure_score="Not Available" t:county_name=COCONINO t:mort_30_pn_achievement_points="4 out of 10" t:mort_30_hf_measure_score="Not Available" m:mort_30_ami_benchmark=0.871669 m:mort_30_pn_achievement_threshold=0.882986 m:mort_30_ami_performance_rate=0.86257 m:mort_30_hf_achievement_threshold=0.881794 m:mort_30_ami_baseline_rate=0.851611 m:mort_30_hf_baseline_rate=0.890927 m:mort_30_hf_benchmark=0.903985 m:mort_30_ami_achievement_threshold=0.851458 m:mort_30_pn_performance_rate=0.893985 m:mort_30_pn_baseline_rate=0.881268 m:mort_30_hf_performance_rate=0.889599 m:mort_30_pn_benchmark=0.908124
```

## Meta Commands

```ls
metric m:mort_30_ami_achievement_threshold p:float l:"MORT-30-AMI Achievement Threshold" t:dataTypeName=number

metric m:mort_30_ami_benchmark p:float l:"MORT-30-AMI Benchmark" t:dataTypeName=number

metric m:mort_30_hf_achievement_threshold p:float l:"MORT-30-HF Achievement Threshold" t:dataTypeName=number

metric m:mort_30_hf_benchmark p:float l:"MORT-30-HF Benchmark" t:dataTypeName=number

metric m:mort_30_pn_achievement_threshold p:float l:"MORT-30-PN Achievement Threshold" t:dataTypeName=number

metric m:mort_30_pn_benchmark p:float l:"MORT-30-PN Benchmark" t:dataTypeName=number

entity e:pudb-wetr l:"Hospital Value-Based Purchasing (HVBP) ? Outcome Scores" t:url=https://data.medicare.gov/api/views/pudb-wetr

property e:pudb-wetr t:meta.view v:id=pudb-wetr v:category="Hospital Compare" v:averageRating=0 v:name="Hospital Value-Based Purchasing (HVBP) ? Outcome Scores"

property e:pudb-wetr t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:pudb-wetr t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:pudb-wetr t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | provider_number | hospital_name                                      | address                           | city          | state | zip_code | county_name   | mort_30_ami_achievement_threshold | mort_30_ami_benchmark | mort_30_ami_baseline_rate | mort_30_ami_performance_rate | mort_30_ami_achievement_points | mort_30_ami_improvement_points | mort_30_ami_measure_score | mort_30_hf_achievement_threshold | mort_30_hf_benchmark | mort_30_hf_baseline_rate | mort_30_hf_performance_rate | mort_30_hf_achievement_points | mort_30_hf_improvement_points | mort_30_hf_measure_score | mort_30_pn_achievement_threshold | mort_30_pn_benchmark | mort_30_pn_baseline_rate | mort_30_pn_performance_rate | mort_30_pn_achievement_points | mort_30_pn_improvement_points | mort_30_pn_measure_score | 
| =========== | =============== | ================================================== | ================================= | ============= | ===== | ======== | ============= | ================================= | ===================== | ========================= | ============================ | ============================== | ============================== | ========================= | ================================ | ==================== | ======================== | =========================== | ============================= | ============================= | ======================== | ================================ | ==================== | ======================== | =========================== | ============================= | ============================= | ======================== | 
| 1479311855  | 010005          | MARSHALL MEDICAL CENTER SOUTH                      | 2505 U S HIGHWAY 431 NORTH        | Boaz          | AL    | 35957    | MARSHALL      | 0.851458                          | 0.871669              | 0.843034                  | 0.857198                     | 3 out of 10                    | Not Available                  | 3 out of 10               | 0.881794                         | 0.903985             | 0.842804                 | 0.851384                    | 0 out of 10                   | 1 out of 9                    | 1 out of 10              | 0.882986                         | 0.908124             | 0.850177                 | 0.860678                    | 0 out of 10                   | 1 out of 9                    | 1 out of 10              | 
| 1479311855  | 010131          | CRESTWOOD MEDICAL CENTER                           | ONE HOSPITAL DR SE                | Huntsville    | AL    | 35801    | MADISON       | 0.851458                          | 0.871669              | 0.858001                  | 0.867794                     | 8 out of 10                    | 7 out of 9                     | 8 out of 10               | 0.881794                         | 0.903985             | 0.867205                 | 0.867608                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 0.882986                         | 0.908124             | 0.879650                 | 0.865677                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 
| 1479311855  | 030073          | TUBA CITY REGIONAL HEALTH CARE CORPORATION         | PO BOX 600                        | Tuba City     | AZ    | 86045    | COCONINO      | 0.851458                          | 0.871669              | 0.851611                  | 0.862570                     | Not Available                  | Not Available                  | Not Available             | 0.881794                         | 0.903985             | 0.890927                 | 0.889599                    | Not Available                 | Not Available                 | Not Available            | 0.882986                         | 0.908124             | 0.881268                 | 0.893985                    | 4 out of 10                   | 4 out of 9                    | 4 out of 10              | 
| 1479311855  | 030084          | CHINLE COMPREHENSIVE HEALTH CARE FACILITY          | US HWY 191, HOSPITAL ROAD         | Chinle        | AZ    | 86503    | APACHE        | 0.851458                          | 0.871669              | 0.855292                  | 0.861115                     | Not Available                  | Not Available                  | Not Available             | 0.881794                         | 0.903985             | 0.878156                 | 0.880545                    | Not Available                 | Not Available                 | Not Available            | 0.882986                         | 0.908124             | 0.902543                 | 0.865468                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 
| 1479311855  | 040007          | CHI-ST VINCENT INFIRMARY                           | TWO ST VINCENT CIRCLE             | Little Rock   | AR    | 72205    | PULASKI       | 0.851458                          | 0.871669              | 0.838751                  | 0.852913                     | 1 out of 10                    | 4 out of 9                     | 4 out of 10               | 0.881794                         | 0.903985             | 0.875401                 | 0.855541                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 0.882986                         | 0.908124             | 0.860304                 | 0.864791                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 
| 1479311855  | 050054          | SAN GORGONIO MEMORIAL HOSPITAL                     | 600 NORTH HIGHLAND SPRINGS AVENUE | Banning       | CA    | 92220    | RIVERSIDE     | 0.851458                          | 0.871669              | 0.847464                  | 0.857281                     | 3 out of 10                    | 4 out of 9                     | 4 out of 10               | 0.881794                         | 0.903985             | 0.880322                 | 0.890600                    | 4 out of 10                   | 4 out of 9                    | 4 out of 10              | 0.882986                         | 0.908124             | 0.826917                 | 0.872957                    | 0 out of 10                   | 5 out of 9                    | 5 out of 10              | 
| 1479311855  | 050055          | CALIFORNIA PACIFIC MEDICAL CTR - ST. LUKE'S CAMPUS | 3555 CESAR CHAVEZ STREET          | San Francisco | CA    | 94110    | SAN FRANCISCO | 0.851458                          | 0.871669              | 0.847040                  | 0.868191                     | Not Available                  | Not Available                  | Not Available             | 0.881794                         | 0.903985             | 0.896554                 | 0.893642                    | 5 out of 10                   | 0 out of 9                    | 5 out of 10              | 0.882986                         | 0.908124             | 0.872327                 | 0.900708                    | 7 out of 10                   | 7 out of 9                    | 7 out of 10              | 
| 1479311855  | 050145          | COMMUNITY HOSPITAL OF THE MONTEREY PENINSULA       | 23625 W R HOLMAN HIGHWAY          | Monterey      | CA    | 93940    | MONTEREY      | 0.851458                          | 0.871669              | 0.856980                  | 0.866468                     | 7 out of 10                    | 6 out of 9                     | 7 out of 10               | 0.881794                         | 0.903985             | 0.881797                 | 0.889958                    | 4 out of 10                   | 3 out of 9                    | 4 out of 10              | 0.882986                         | 0.908124             | 0.867370                 | 0.897683                    | 6 out of 10                   | 7 out of 9                    | 7 out of 10              | 
| 1479311855  | 050224          | HOAG MEMORIAL HOSPITAL PRESBYTERIAN                | ONE HOAG DRIVE                    | Newport Beach | CA    | 92663    | ORANGE        | 0.851458                          | 0.871669              | 0.853537                  | 0.871879                     | 10 out of 10                   | 9 out of 9                     | 10 out of 10              | 0.881794                         | 0.903985             | 0.894412                 | 0.872068                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 0.882986                         | 0.908124             | 0.901827                 | 0.905343                    | 9 out of 10                   | 5 out of 9                    | 9 out of 10              | 
| 1479311855  | 050309          | SUTTER ROSEVILLE MEDICAL CENTER                    | ONE MEDICAL PLAZA                 | Roseville     | CA    | 95661    | PLACER        | 0.851458                          | 0.871669              | 0.861589                  | 0.868828                     | 8 out of 10                    | 7 out of 9                     | 8 out of 10               | 0.881794                         | 0.903985             | 0.886416                 | 0.860082                    | 0 out of 10                   | 0 out of 9                    | 0 out of 10              | 0.882986                         | 0.908124             | 0.878717                 | 0.904002                    | 8 out of 10                   | 8 out of 9                    | 8 out of 10              | 
```