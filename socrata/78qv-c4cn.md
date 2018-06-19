# State Drug Utilization Data 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2000) |
| Metadata | [Link](https://data.medicaid.gov/api/views/78qv-c4cn) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/78qv-c4cn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/78qv-c4cn/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 78qv-c4cn |
| Name | State Drug Utilization Data 2000 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:20:19Z |
| Publication Date | 2016-08-29T21:47:53Z |

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | record_id                      | Utilization Type               | text          | text          |
| Yes      | series tag     | state_code                     | State                          | text          | text          |
| Yes      | series tag     | labeler_code                   | Labeler Code                   | text          | text          |
| Yes      | series tag     | product_code                   | Product Code                   | text          | text          |
| Yes      | series tag     | package_size                   | Package Size                   | text          | text          |
| No       |                | period_covered                 | Year                           | number        | text          |
| No       |                | quarter                        | Quarter                        | number        | text          |
| Yes      | series tag     | product_fda_list_name          | Product Name                   | text          | text          |
| Yes      | numeric metric | units_reimbursed               | Units Reimbursed               | number        | number        |
| Yes      | series tag     | suppression_used               | Suppression Used               | checkbox      | checkbox      |
| Yes      | numeric metric | number_of_prescriptions        | Number of Prescriptions        | number        | number        |
| Yes      | numeric metric | total_amount_reimbursed        | Total Amount Reimbursed        | number        | number        |
| Yes      | numeric metric | medicaid_amount_reimbursed     | Medicaid Amount Reimbursed     | number        | number        |
| Yes      | numeric metric | non_medicaid_amount_reimbursed | Non Medicaid Amount Reimbursed | number        | number        |
| No       |                | quarter_begin                  | Quarter Begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | Latitude                       | number        | number        |
| No       |                | longitude                      | Longitude                      | number        | number        |
| Yes      | series tag     | ndc                            | ndc                            | text          | text          |
```

## Time Field

```ls
Value = quarter_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_begin,latitude,longitude,period_covered,quarter
```

## Data Commands

```ls
series e:78qv-c4cn d:2000-07-01T00:00:00.000Z t:product_fda_list_name=DICYCLOMIN t:ndc=60951061670 t:package_size=70 t:state_code=MA t:labeler_code=60951 t:product_code=0616 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=146.18 m:number_of_prescriptions=22 m:units_reimbursed=1673 m:non_medicaid_amount_reimbursed=0

series e:78qv-c4cn d:2000-04-01T00:00:00.000Z t:product_fda_list_name=AMIODARONE t:ndc=00185014460 t:package_size=60 t:state_code=CT t:labeler_code=00185 t:product_code=0144 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=6240.24 m:number_of_prescriptions=47 m:units_reimbursed=2679 m:non_medicaid_amount_reimbursed=0

series e:78qv-c4cn d:2000-01-01T00:00:00.000Z t:product_fda_list_name=ACIDULATED t:ndc=38245061607 t:package_size=07 t:state_code=ME t:labeler_code=38245 t:product_code=0616 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=142.41 m:number_of_prescriptions=15 m:units_reimbursed=7500 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:78qv-c4cn l:"State Drug Utilization Data 2000" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/78qv-c4cn

property e:78qv-c4cn t:meta.view v:id=78qv-c4cn v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2000" v:attribution="Centers for Medicare and Medicaid"

property e:78qv-c4cn t:meta.view.license v:name="Public Domain"

property e:78qv-c4cn t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:78qv-c4cn t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:78qv-c4cn t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | AR         | 00536        | 4036         | 01           | 2000           | 2       | METHYLPRED            |                  | true             |                         |                         |                            |                                | 4/1           | 2000-04-01T00:00:00 | 34.9513  | -92.3809  | 00536403601 | 
| FFSU      | MA         | 60951        | 0616         | 70           | 2000           | 3       | DICYCLOMIN            | 1673             | false            | 22                      | 146.18                  | 0                          | 0                              | 7/1           | 2000-07-01T00:00:00 | 42.2373  | -71.5314  | 60951061670 | 
| FFSU      | CT         | 00185        | 0144         | 60           | 2000           | 2       | AMIODARONE            | 2679             | false            | 47                      | 6240.24                 | 0                          | 0                              | 4/1           | 2000-04-01T00:00:00 | 41.5834  | -72.7622  | 00185014460 | 
| FFSU      | ME         | 38245        | 0616         | 07           | 2000           | 1       | ACIDULATED            | 7500             | false            | 15                      | 142.41                  | 0                          | 0                              | 1/1           | 2000-01-01T00:00:00 | 44.6074  | -69.3977  | 38245061607 | 
| FFSU      | RI         | 00378        | 1132         | 01           | 2000           | 4       | NADOLOL 80            | 1450             | false            | 23                      | 867.59                  | 0                          | 0                              | 10/1          | 2000-10-01T00:00:00 | 41.6772  | -71.5101  | 00378113201 | 
| FFSU      | XX         | 63801        | 0107         | 05           | 2000           | 1       | BENSAL HP             | 534              | false            | 13                      | 1592.57                 | 1592.57                    | 0                              | 1/1           | 2000-01-01T00:00:00 |          |           | 63801010705 | 
| FFSU      | LA         | 00378        | 0577         | 05           | 2000           | 3       | AMILORIDE             |                  | true             |                         |                         |                            |                                | 7/1           | 2000-07-01T00:00:00 | 31.1801  | -91.8749  | 00378057705 | 
| FFSU      | LA         | 59911        | 5860         | 01           | 2000           | 1       | SULF/TRIME            |                  | true             |                         |                         |                            |                                | 1/1           | 2000-01-01T00:00:00 | 31.1801  | -91.8749  | 59911586001 | 
| FFSU      | XX         | 00085        | 0847         | 05           | 2000           | 3       | OTOBIOTIC             | 11896            | false            | 790                     | 18767.14                | 0                          | 0                              | 7/1           | 2000-07-01T00:00:00 |          |           | 00085084705 | 
| FFSU      | XX         | 24208        | 0730         | 06           | 2000           | 2       | PROPRACAIN            | 900              | false            | 60                      | 661.54                  | 0                          | 0                              | 4/1           | 2000-04-01T00:00:00 |          |           | 24208073006 | 
```