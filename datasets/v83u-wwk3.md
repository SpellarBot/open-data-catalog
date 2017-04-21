# State Drug Utilization Data 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1995) |
| Metadata | [Link](https://data.medicaid.gov/api/views/v83u-wwk3) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/v83u-wwk3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/v83u-wwk3/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | v83u-wwk3 |
| Name | State Drug Utilization Data 1995 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:19:51Z |
| Publication Date | 2016-08-29T19:08:08Z |

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
series e:v83u-wwk3 d:1995-07-01T00:00:00.000Z t:product_fda_list_name=TOFRANIL-P t:ndc=00028004026 t:package_size=26 t:state_code=MD t:labeler_code=00028 t:product_code=0040 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=925.62 m:number_of_prescriptions=21 m:units_reimbursed=662 m:non_medicaid_amount_reimbursed=0

series e:v83u-wwk3 d:1995-10-01T00:00:00.000Z t:product_fda_list_name=NITROFURAN t:ndc=00781250101 t:package_size=01 t:state_code=WI t:labeler_code=00781 t:product_code=2501 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=460.96 m:number_of_prescriptions=23 m:units_reimbursed=1069 m:non_medicaid_amount_reimbursed=0

series e:v83u-wwk3 d:1995-04-01T00:00:00.000Z t:product_fda_list_name="TOLMETIN S" t:ndc=00378520001 t:package_size=01 t:state_code=MS t:labeler_code=00378 t:product_code=5200 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=1119.15 m:number_of_prescriptions=33 m:units_reimbursed=3045 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:float l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:v83u-wwk3 l:"State Drug Utilization Data 1995" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/v83u-wwk3

property e:v83u-wwk3 t:meta.view v:id=v83u-wwk3 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1995" v:attribution="Centers for Medicare and Medicaid"

property e:v83u-wwk3 t:meta.view.license v:name="Public Domain"

property e:v83u-wwk3 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:v83u-wwk3 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:v83u-wwk3 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MD         | 00028        | 0040         | 26           | 1995           | 3       | TOFRANIL-P            | 662              | false            | 21                      | 925.62                  | 0                          | 0                              | 7/1           | 1995-07-01T00:00:00 | 39.0724  | -76.7902  | 00028004026 | 
| FFSU      | WI         | 00781        | 2501         | 01           | 1995           | 4       | NITROFURAN            | 1069             | false            | 23                      | 460.96                  | 0                          | 0                              | 10/1          | 1995-10-01T00:00:00 | 44.2563  | -89.6385  | 00781250101 | 
| FFSU      | MS         | 00378        | 5200         | 01           | 1995           | 2       | TOLMETIN S            | 3045             | false            | 33                      | 1119.15                 | 0                          | 0                              | 4/1           | 1995-04-01T00:00:00 | 32.7673  | -89.6812  | 00378520001 | 
| FFSU      | IL         | 00781        | 1405         | 01           | 1995           | 2       | LORAZEPAM             | 4492             | false            | 111                     | 495.87                  | 0                          | 0                              | 4/1           | 1995-04-01T00:00:00 | 40.3363  | -89.0022  | 00781140501 | 
| FFSU      | IN         | 00182        | 0507         | 89           | 1995           | 3       | FOLIC ACID            | 18268            | false            | 506                     | 4548.18                 | 0                          | 0                              | 7/1           | 1995-07-01T00:00:00 | 39.8647  | -86.2604  | 00182050789 | 
| FFSU      | XX         | 17714        | 0021         | 01           | 1995           | 4       | DIPHENHYDR            | 20489            | false            | 535                     | 2204.38                 | 0                          | 0                              | 10/1          | 1995-10-01T00:00:00 |          |           | 17714002101 | 
| FFSU      | MS         | 00904        | 1227         | 28           | 1995           | 1       | BENAPHEN              | 73720            | false            | 432                     | 2307.57                 | 0                          | 0                              | 1/1           | 1995-01-01T00:00:00 | 32.7673  | -89.6812  | 00904122728 | 
| FFSU      | XX         | 00364        | 2145         | 50           | 1995           | 1       | IBUPROFEN             | 10556            | false            | 163                     | 809.77                  | 3.89                       | 0                              | 1/1           | 1995-01-01T00:00:00 |          |           | 00364214550 | 
| FFSU      | KY         | 00021        | 0450         | 50           | 1995           | 1       | PHAZYME-12            | 2127             | false            | 31                      | 613.41                  | 0                          | 0                              | 1/1           | 1995-01-01T00:00:00 | 37.669   | -84.6514  | 00021045050 | 
| FFSU      | IL         | 00074        | 3210         | 01           | 1995           | 3       | DIAZEPAM 2            |                  | true             |                         |                         |                            |                                | 7/1           | 1995-07-01T00:00:00 | 40.3363  | -89.0022  | 00074321001 | 
```