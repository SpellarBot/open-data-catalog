# State Drug Utilization Data 1996

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1996) |
| Metadata | [Link](https://data.medicaid.gov/api/views/jqjw-uby8) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/jqjw-uby8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/jqjw-uby8/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | jqjw-uby8 |
| Name | State Drug Utilization Data 1996 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:22:39Z |
| Publication Date | 2016-08-29T22:36:58Z |

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
series e:jqjw-uby8 d:1996-01-01T00:00:00.000Z t:record_id=FFSU t:package_size=63 t:product_fda_list_name=PROMETHAZI t:labeler_code=00182 t:suppression_used=false t:product_code=0501 t:ndc=00182050163 t:state_code=CO m:total_amount_reimbursed=1171.42 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=990 m:medicaid_amount_reimbursed=0 m:number_of_prescriptions=63

series e:jqjw-uby8 d:1996-10-01T00:00:00.000Z t:record_id=FFSU t:package_size=04 t:product_fda_list_name="INTRON A P" t:labeler_code=00085 t:suppression_used=false t:product_code=0647 t:ndc=00085064704 t:state_code=MT m:total_amount_reimbursed=3934.23 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=134 m:medicaid_amount_reimbursed=0 m:number_of_prescriptions=14

series e:jqjw-uby8 d:1996-07-01T00:00:00.000Z t:record_id=FFSU t:package_size=60 t:product_fda_list_name="BACLOFEN T" t:labeler_code=00172 t:suppression_used=false t:product_code=4096 t:ndc=00172409660 t:state_code=VA m:total_amount_reimbursed=13779.52 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=95748 m:medicaid_amount_reimbursed=0 m:number_of_prescriptions=803
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:float l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:jqjw-uby8 l:"State Drug Utilization Data 1996" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/jqjw-uby8

property e:jqjw-uby8 t:meta.view d:2017-09-25T07:27:28.664Z v:averageRating=0 v:name="State Drug Utilization Data 1996" v:attribution="Centers for Medicare and Medicaid" v:attributionLink=https://medicaid.gov v:id=jqjw-uby8 v:category="State Drug Utilization"

property e:jqjw-uby8 t:meta.view.license d:2017-09-25T07:27:28.664Z v:name="Public Domain"

property e:jqjw-uby8 t:meta.view.owner d:2017-09-25T07:27:28.664Z v:displayName=Medicaid.gov v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:id=di3h-9ddn v:screenName=Medicaid.gov v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB

property e:jqjw-uby8 t:meta.view.tableauthor d:2017-09-25T07:27:28.664Z v:displayName=Medicaid.gov v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:id=di3h-9ddn v:screenName=Medicaid.gov v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB

property e:jqjw-uby8 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:27:28.664Z v:Program_Code=009:076 v:Bureau_Code=009:00
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MA         | 00062        | 5450         | 00           | 1996           | 4       | ORTHO DIEN            | true             |                  |                         |                         |                            |                                | 10/1          | 1996-10-01T00:00:00 | 42.2373  | -71.5314  | 00062545000 | 
| FFSU      | AK         | 00008        | 0036         | 05           | 1996           | 2       | PEN-VEE K             | true             |                  |                         |                         |                            |                                | 4/1           | 1996-04-01T00:00:00 | 61.385   | -152.2683 | 00008003605 | 
| FFSU      | CO         | 00182        | 0501         | 63           | 1996           | 1       | PROMETHAZI            | false            | 990              | 63                      | 1171.42                 | 0                          | 0                              | 1/1           | 1996-01-01T00:00:00 | 39.0646  | -105.3272 | 00182050163 | 
| FFSU      | MT         | 00085        | 0647         | 04           | 1996           | 4       | INTRON A P            | false            | 134              | 14                      | 3934.23                 | 0                          | 0                              | 10/1          | 1996-10-01T00:00:00 | 46.9048  | -110.3261 | 00085064704 | 
| FFSU      | AL         | 00008        | 0602         | 50           | 1996           | 4       | MEPERIDINE            | true             |                  |                         |                         |                            |                                | 10/1          | 1996-10-01T00:00:00 | 32.799   | -86.8073  | 00008060250 | 
| FFSU      | VA         | 00172        | 4096         | 60           | 1996           | 3       | BACLOFEN T            | false            | 95748            | 803                     | 13779.52                | 0                          | 0                              | 7/1           | 1996-07-01T00:00:00 | 37.768   | -78.2057  | 00172409660 | 
| FFSU      | CO         | 00677        | 0565         | 01           | 1996           | 3       | METHYL PRE            | true             |                  |                         |                         |                            |                                | 7/1           | 1996-07-01T00:00:00 | 39.0646  | -105.3272 | 00677056501 | 
| FFSU      | DC         | 00364        | 7318         | 16           | 1996           | 4       | Cardec DM             | false            | 6070             | 39                      | 276.28                  | 0                          | 0                              | 10/1          | 1996-10-01T00:00:00 | 38.8964  | -77.0262  | 00364731816 | 
| FFSU      | UT         | 00904        | 2463         | 16           | 1996           | 1       | ERYTHROMYC            | true             |                  |                         |                         |                            |                                | 1/1           | 1996-01-01T00:00:00 | 40.1135  | -111.8535 | 00904246316 | 
| FFSU      | SC         | 00228        | 2502         | 10           | 1996           | 4       | PRAZOSIN H            | true             |                  |                         |                         |                            |                                | 10/1          | 1996-10-01T00:00:00 | 33.8191  | -80.9066  | 00228250210 | 
```