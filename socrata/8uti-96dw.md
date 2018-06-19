# State Drug Utilization Data 1994

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1994) |
| Metadata | [Link](https://data.medicaid.gov/api/views/8uti-96dw) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/8uti-96dw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/8uti-96dw/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 8uti-96dw |
| Name | State Drug Utilization Data 1994 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:21:05Z |
| Publication Date | 2016-08-29T19:40:10Z |

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
series e:8uti-96dw d:1994-07-01T00:00:00.000Z t:product_fda_list_name=DORAL t:ndc=00037900201 t:package_size=01 t:state_code=VA t:labeler_code=00037 t:product_code=9002 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=3114.45 m:number_of_prescriptions=145 m:units_reimbursed=3725 m:non_medicaid_amount_reimbursed=0

series e:8uti-96dw d:1994-10-01T00:00:00.000Z t:product_fda_list_name="THEO-24 30" t:ndc=50474285206 t:package_size=06 t:state_code=ND t:labeler_code=50474 t:product_code=2852 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=355.89 m:number_of_prescriptions=16 m:units_reimbursed=902 m:non_medicaid_amount_reimbursed=0

series e:8uti-96dw d:1994-07-01T00:00:00.000Z t:product_fda_list_name=Spironolac t:ndc=00364051201 t:package_size=01 t:state_code=LA t:labeler_code=00364 t:product_code=0512 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=119.6 m:number_of_prescriptions=13 m:units_reimbursed=1050 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:float l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:8uti-96dw l:"State Drug Utilization Data 1994" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/8uti-96dw

property e:8uti-96dw t:meta.view v:id=8uti-96dw v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1994" v:attribution="Centers for Medicare and Medicaid"

property e:8uti-96dw t:meta.view.license v:name="Public Domain"

property e:8uti-96dw t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:8uti-96dw t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:8uti-96dw t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | VT         | 00998        | 0637         | 10           | 1994           | 1       | ECONOPRED             | true             |                  |                         |                         |                            |                                | 1/1           | 1994-01-01T00:00:00 | 44.0407  | -72.7093  | 00998063710 | 
| FFSU      | VA         | 00037        | 9002         | 01           | 1994           | 3       | DORAL                 | false            | 3725             | 145                     | 3114.45                 | 0                          | 0                              | 7/1           | 1994-07-01T00:00:00 | 37.768   | -78.2057  | 00037900201 | 
| FFSU      | OH         | 00143        | 1202         | 10           | 1994           | 2       | CORTISONE             | true             |                  |                         |                         |                            |                                | 4/1           | 1994-04-01T00:00:00 | 40.3736  | -82.7755  | 00143120210 | 
| FFSU      | OH         | 00006        | 0712         | 98           | 1994           | 1       | VASOTEC               | true             |                  |                         |                         |                            |                                | 1/1           | 1994-01-01T00:00:00 | 40.3736  | -82.7755  | 00006071298 | 
| FFSU      | ND         | 50474        | 2852         | 06           | 1994           | 4       | THEO-24 30            | false            | 902              | 16                      | 355.89                  | 0                          | 0                              | 10/1          | 1994-10-01T00:00:00 | 47.5362  | -99.793   | 50474285206 | 
| FFSU      | LA         | 00364        | 0512         | 01           | 1994           | 3       | Spironolac            | false            | 1050             | 13                      | 119.6                   | 0                          | 0                              | 7/1           | 1994-07-01T00:00:00 | 31.1801  | -91.8749  | 00364051201 | 
| FFSU      | ME         | 00006        | 0694         | 68           | 1994           | 4       | ALDORIL D3            | true             |                  |                         |                         |                            |                                | 10/1          | 1994-10-01T00:00:00 | 44.6074  | -69.3977  | 00006069468 | 
| FFSU      | VA         | 00182        | 0678         | 40           | 1994           | 2       | TETRACYCLI            | true             |                  |                         |                         |                            |                                | 4/1           | 1994-04-01T00:00:00 | 37.768   | -78.2057  | 00182067840 | 
| FFSU      | VT         | 00062        | 1185         | 01           | 1994           | 2       | ERYCETTE 6            | true             |                  |                         |                         |                            |                                | 4/1           | 1994-04-01T00:00:00 | 44.0407  | -72.7093  | 00062118501 | 
| FFSU      | XX         | 51285        | 0323         | 09           | 1994           | 1       | PROPRANOLO            | true             |                  |                         |                         |                            |                                | 1/1           | 1994-01-01T00:00:00 |          |           | 51285032309 | 
```