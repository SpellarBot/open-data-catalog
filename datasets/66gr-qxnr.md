# State Drug Utilization Data 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2003) |
| Metadata | [Link](https://data.medicaid.gov/api/views/66gr-qxnr) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/66gr-qxnr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/66gr-qxnr/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 66gr-qxnr |
| Name | State Drug Utilization Data 2003 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:24:06Z |
| Publication Date | 2016-08-29T18:05:55Z |

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
series e:66gr-qxnr d:2003-10-01T00:00:00.000Z t:product_fda_list_name=BUTALBITAL t:ndc=00591048501 t:package_size=01 t:state_code=MI t:labeler_code=00591 t:product_code=0485 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=248.67 m:total_amount_reimbursed=268.57 m:number_of_prescriptions=15 m:units_reimbursed=801 m:non_medicaid_amount_reimbursed=19.9

series e:66gr-qxnr d:2003-01-01T00:00:00.000Z t:product_fda_list_name=HYDROCORTI t:ndc=51672129006 t:package_size=06 t:state_code=WI t:labeler_code=51672 t:product_code=1290 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=1599.99 m:number_of_prescriptions=60 m:units_reimbursed=2701 m:non_medicaid_amount_reimbursed=0

series e:66gr-qxnr d:2003-04-01T00:00:00.000Z t:product_fda_list_name=PERPHENAZI t:ndc=00378044205 t:package_size=05 t:state_code=NJ t:labeler_code=00378 t:product_code=0442 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=196.68 m:number_of_prescriptions=15 m:units_reimbursed=1570 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:66gr-qxnr l:"State Drug Utilization Data 2003" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/66gr-qxnr

property e:66gr-qxnr t:meta.view v:id=66gr-qxnr v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2003" v:attribution="Centers for Medicare and Medicaid"

property e:66gr-qxnr t:meta.view.license v:name="Public Domain"

property e:66gr-qxnr t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:66gr-qxnr t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:66gr-qxnr t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | ND         | 00172        | 2416         | 60           | 2003           | 4       | TETRACYCLI            | true             |                  |                         |                         |                            |                                | 10/1          | 2003-10-01T00:00:00 | 47.5362  | -99.793   | 00172241660 | 
| FFSU      | MI         | 00591        | 0485         | 01           | 2003           | 4       | BUTALBITAL            | false            | 801              | 15                      | 268.57                  | 248.67                     | 19.9                           | 10/1          | 2003-10-01T00:00:00 | 43.3504  | -84.5603  | 00591048501 | 
| FFSU      | WI         | 51672        | 1290         | 06           | 2003           | 1       | HYDROCORTI            | false            | 2701             | 60                      | 1599.99                 | 0                          | 0                              | 1/1           | 2003-01-01T00:00:00 | 44.2563  | -89.6385  | 51672129006 | 
| FFSU      | PA         | 00378        | 0733         | 01           | 2003           | 4       | NAPROXEN S            | true             |                  |                         |                         |                            |                                | 10/1          | 2003-10-01T00:00:00 | 40.5773  | -77.264   | 00378073301 | 
| FFSU      | PA         | 00062        | 5426         | 02           | 2003           | 1       | MONISTAT C            | true             |                  |                         |                         |                            |                                | 1/1           | 2003-01-01T00:00:00 | 40.5773  | -77.264   | 00062542602 | 
| FFSU      | AL         | 60951        | 0675         | 70           | 2003           | 1       | BUTALBITAL            | true             |                  |                         |                         |                            |                                | 1/1           | 2003-01-01T00:00:00 | 32.799   | -86.8073  | 60951067570 | 
| FFSU      | NJ         | 00378        | 0442         | 05           | 2003           | 2       | PERPHENAZI            | false            | 1570             | 15                      | 196.68                  | 0                          | 0                              | 4/1           | 2003-04-01T00:00:00 | 40.314   | -74.5089  | 00378044205 | 
| FFSU      | XX         | 00364        | 6644         | 54           | 2003           | 3       | PYRIDOXINE            | true             |                  |                         |                         |                            |                                | 7/1           | 2003-07-01T00:00:00 |          |           | 00364664454 | 
| FFSU      | NE         | 49348        | 0571         | 41           | 2003           | 1       | PEDIATRIC             | false            | 370658           | 137                     | 1445.57                 | 0                          | 0                              | 1/1           | 2003-01-01T00:00:00 | 41.1289  | -98.2883  | 49348057141 | 
| FFSU      | GA         | 00185        | 4350         | 30           | 2003           | 3       | ISONIAZID             | false            | 517              | 17                      | 106.61                  | 0                          | 0                              | 7/1           | 2003-07-01T00:00:00 | 32.9866  | -83.6487  | 00185435030 | 
```