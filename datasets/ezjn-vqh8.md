# State Drug Utilization Data 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2005) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ezjn-vqh8) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ezjn-vqh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ezjn-vqh8/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ezjn-vqh8 |
| Name | State Drug Utilization Data 2005 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:23:15Z |
| Publication Date | 2016-08-29T22:58:27Z |

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
series e:ezjn-vqh8 d:2005-04-01T00:00:00.000Z t:product_fda_list_name=INTAL t:ndc=60793001108 t:package_size=08 t:state_code=MO t:labeler_code=60793 t:product_code=0011 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2953.32 m:number_of_prescriptions=38 m:units_reimbursed=364.5 m:non_medicaid_amount_reimbursed=0

series e:ezjn-vqh8 d:2005-01-01T00:00:00.000Z t:product_fda_list_name=LACTULOSE t:ndc=50383079516 t:package_size=16 t:state_code=VA t:labeler_code=50383 t:product_code=0795 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=6713.48 m:number_of_prescriptions=432 m:units_reimbursed=255853 m:non_medicaid_amount_reimbursed=0

series e:ezjn-vqh8 d:2005-07-01T00:00:00.000Z t:product_fda_list_name="FERROUS SU" t:ndc=00182402801 t:package_size=01 t:state_code=RI t:labeler_code=00182 t:product_code=4028 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=438.76 m:number_of_prescriptions=181 m:units_reimbursed=11445 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:ezjn-vqh8 l:"State Drug Utilization Data 2005" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ezjn-vqh8

property e:ezjn-vqh8 t:meta.view v:id=ezjn-vqh8 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2005" v:attribution="Centers for Medicare and Medicaid"

property e:ezjn-vqh8 t:meta.view.license v:name="Public Domain"

property e:ezjn-vqh8 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MO         | 60793        | 0011         | 08           | 2005           | 2       | INTAL                 | false            | 364.5            | 38                      | 2953.32                 | 0                          | 0                              | 4/1           | 2005-04-01T00:00:00 | 38.4623  | -92.302   | 60793001108 | 
| FFSU      | VA         | 50383        | 0795         | 16           | 2005           | 1       | LACTULOSE             | false            | 255853           | 432                     | 6713.48                 | 0                          | 0                              | 1/1           | 2005-01-01T00:00:00 | 37.768   | -78.2057  | 50383079516 | 
| FFSU      | NE         | 00013        | 2150         | 36           | 2005           | 1       | ESTRING VA            | true             |                  |                         |                         |                            |                                | 1/1           | 2005-01-01T00:00:00 | 41.1289  | -98.2883  | 00013215036 | 
| FFSU      | ND         | 00378        | 0087         | 01           | 2005           | 3       | MAPROTILIN            | true             |                  |                         |                         |                            |                                | 7/1           | 2005-07-01T00:00:00 | 47.5362  | -99.793   | 00378008701 | 
| FFSU      | RI         | 00182        | 4028         | 01           | 2005           | 3       | FERROUS SU            | false            | 11445            | 181                     | 438.76                  | 0                          | 0                              | 7/1           | 2005-07-01T00:00:00 | 41.6772  | -71.5101  | 00182402801 | 
| FFSU      | MA         | 59148        | 0011         | 35           | 2005           | 3       | ABILIFY 30            | true             |                  |                         |                         |                            |                                | 7/1           | 2005-07-01T00:00:00 | 42.2373  | -71.5314  | 59148001135 | 
| FFSU      | CA         | 53746        | 0132         | 90           | 2005           | 2       | IBUPROFEN             | true             |                  |                         |                         |                            |                                | 4/1           | 2005-04-01T00:00:00 | 36.17    | -119.7462 | 53746013290 | 
| FFSU      | MI         | 50111        | 0394         | 01           | 2005           | 2       | BENZTROPIN            | false            | 163411           | 3159                    | 22342.18                | 22111.63                   | 230.55                         | 4/1           | 2005-04-01T00:00:00 | 43.3504  | -84.5603  | 50111039401 | 
| FFSU      | WV         | 00603        | 4711         | 21           | 2005           | 2       | MULTIVIT/F            | false            | 645              | 22                      | 164.91                  | 0                          | 0                              | 4/1           | 2005-04-01T00:00:00 | 38.468   | -80.9696  | 00603471121 | 
| FFSU      | WA         | 52152        | 0001         | 02           | 2005           | 2       | MULTIVITA             | false            | 4187             | 138                     | 861.46                  | 0                          | 0                              | 4/1           | 2005-04-01T00:00:00 | 47.3917  | -121.5708 | 52152000102 | 
```