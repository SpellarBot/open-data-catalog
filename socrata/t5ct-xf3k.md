# State Drug Utilization Data 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2001) |
| Metadata | [Link](https://data.medicaid.gov/api/views/t5ct-xf3k) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/t5ct-xf3k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/t5ct-xf3k/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | t5ct-xf3k |
| Name | State Drug Utilization Data 2001 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:25:23Z |
| Publication Date | 2016-08-29T20:08:56Z |

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
| Yes      | series tag     | suppression_used               | Suppression Used               | checkbox      | checkbox      |
| Yes      | numeric metric | units_reimbursed               | Units Reimbursed               | number        | number        |
| Yes      | numeric metric | number_of_prescriptions        | Number of Prescriptions        | number        | number        |
| Yes      | numeric metric | total_amount_reimbursed        | Total Amount Reimbursed        | number        | number        |
| Yes      | numeric metric | medicaid_amount_reimbursed     | Medicaid Amount Reimbursed     | number        | number        |
| Yes      | numeric metric | non_medicaid_amount_reimbursed | Non Medicaid Amount Reimbursed | number        | number        |
| No       |                | quarter_begin                  | Quarter Begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | Latitude                       | number        | number        |
| No       |                | longitude                      | Longitude                      | number        | number        |
| Yes      | series tag     | ndc                            | NDC                            | text          | text          |
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
series e:t5ct-xf3k d:2001-01-01T00:00:00.000Z t:ndc=55953013240 t:package_size=40 t:state_code=OH t:labeler_code=55953 t:product_code=0132 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=78.11 m:number_of_prescriptions=14 m:units_reimbursed=797 m:non_medicaid_amount_reimbursed=0

series e:t5ct-xf3k d:2001-07-01T00:00:00.000Z t:product_fda_list_name="FERROUS SU" t:ndc=00677007110 t:package_size=10 t:state_code=OR t:labeler_code=00677 t:product_code=0071 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=540.78 m:number_of_prescriptions=133 m:units_reimbursed=7012 m:non_medicaid_amount_reimbursed=0

series e:t5ct-xf3k d:2001-04-01T00:00:00.000Z t:product_fda_list_name=DIPIVEFRIN t:ndc=00364304054 t:package_size=54 t:state_code=XX t:labeler_code=00364 t:product_code=3040 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2170.51 m:number_of_prescriptions=207 m:units_reimbursed=1975 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:t5ct-xf3k l:"State Drug Utilization Data 2001" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/t5ct-xf3k

property e:t5ct-xf3k t:meta.view v:id=t5ct-xf3k v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2001" v:attribution="Centers for Medicare and Medicaid"

property e:t5ct-xf3k t:meta.view.license v:name="Public Domain"

property e:t5ct-xf3k t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:t5ct-xf3k t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:t5ct-xf3k t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | OH         | 55953        | 0132         | 40           | 2001           | 1       |                       | false            | 797              | 14                      | 78.11                   | 0                          | 0                              | 1/1           | 2001-01-01T00:00:00 | 40.3736  | -82.7755  | 55953013240 | 
| FFSU      | NH         | 24208        | 0347         | 20           | 2001           | 4       | ALBUTEROL             | true             |                  |                         |                         |                            |                                | 10/1          | 2001-10-01T00:00:00 | 43.4108  | -71.5653  | 24208034720 | 
| FFSU      | OR         | 00677        | 0071         | 10           | 2001           | 3       | FERROUS SU            | false            | 7012             | 133                     | 540.78                  | 0                          | 0                              | 7/1           | 2001-07-01T00:00:00 | 44.5672  | -122.1269 | 00677007110 | 
| FFSU      | WY         | 00781        | 6570         | 16           | 2001           | 1       | HYDROXYZIN            | true             |                  |                         |                         |                            |                                | 1/1           | 2001-01-01T00:00:00 | 42.7475  | -107.2085 | 00781657016 | 
| FFSU      | AK         | 00074        | 6057         | 13           | 2001           | 2       | CYLERT TAB            | true             |                  |                         |                         |                            |                                | 4/1           | 2001-04-01T00:00:00 | 61.385   | -152.2683 | 00074605713 | 
| FFSU      | XX         | 00364        | 3040         | 54           | 2001           | 2       | DIPIVEFRIN            | false            | 1975             | 207                     | 2170.51                 | 0                          | 0                              | 4/1           | 2001-04-01T00:00:00 |          |           | 00364304054 | 
| FFSU      | IL         | 00603        | 5022         | 21           | 2001           | 2       | PANASE CAP            | true             |                  |                         |                         |                            |                                | 4/1           | 2001-04-01T00:00:00 | 40.3363  | -89.0022  | 00603502221 | 
| FFSU      | UT         | 00026        | 8512         | 51           | 2001           | 3       | CIPRO                 | false            | 5314             | 355                     | 19904.37                | 0                          | 0                              | 7/1           | 2001-07-01T00:00:00 | 40.1135  | -111.8535 | 00026851251 | 
| FFSU      | OH         | 00008        | 0653         | 50           | 2001           | 1       | MORPHINE S            | true             |                  |                         |                         |                            |                                | 1/1           | 2001-01-01T00:00:00 | 40.3736  | -82.7755  | 00008065350 | 
| FFSU      | OH         | 00054        | 8744         | 25           | 2001           | 3       | PSEUDOEPHE            | false            | 2361             | 69                      | 290.3                   | 0                          | 0                              | 7/1           | 2001-07-01T00:00:00 | 40.3736  | -82.7755  | 00054874425 | 
```