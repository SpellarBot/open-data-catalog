# State Drug Utilization Data 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2011) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ra84-ffhc) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ra84-ffhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ra84-ffhc/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ra84-ffhc |
| Name | State Drug Utilization Data 2011 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T12:34:21Z |
| Publication Date | 2016-08-29T17:52:25Z |

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
series e:ra84-ffhc d:2011-10-01T00:00:00.000Z t:product_fda_list_name=METFORMIN t:ndc=68462015905 t:package_size=05 t:state_code=MA t:labeler_code=68462 t:product_code=0159 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=211.63 m:total_amount_reimbursed=233.63 m:number_of_prescriptions=40 m:units_reimbursed=2580 m:non_medicaid_amount_reimbursed=22

series e:ra84-ffhc d:2011-07-01T00:00:00.000Z t:product_fda_list_name=ONDANSETRO t:ndc=52152053930 t:package_size=30 t:state_code=PA t:labeler_code=52152 t:product_code=0539 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=580.97 m:total_amount_reimbursed=645.68 m:number_of_prescriptions=82 m:units_reimbursed=1126 m:non_medicaid_amount_reimbursed=64.71

series e:ra84-ffhc d:2011-01-01T00:00:00.000Z t:product_fda_list_name="CRYSELLE T" t:ndc=00555904958 t:package_size=58 t:state_code=RI t:labeler_code=00555 t:product_code=9049 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=19.96 m:total_amount_reimbursed=45.74 m:number_of_prescriptions=22 m:units_reimbursed=616 m:non_medicaid_amount_reimbursed=25.78
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:ra84-ffhc l:"State Drug Utilization Data 2011" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ra84-ffhc

property e:ra84-ffhc t:meta.view v:id=ra84-ffhc v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2011" v:attribution="Centers for Medicare and Medicaid"

property e:ra84-ffhc t:meta.view.license v:name="Public Domain"

property e:ra84-ffhc t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ra84-ffhc t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ra84-ffhc t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | IL         | 00085        | 1254         | 01           | 2011           | 4       | INTRON A 1            | true             |                  |                         |                         |                            |                                | 10/1          | 2011-10-01T00:00:00 | 40.3363  | -89.0022  | 00085125401 | 
| FFSU      | KY         | 67618        | 0300         | 11           | 2011           | 4       | SENOKOT               | true             |                  |                         |                         |                            |                                | 10/1          | 2011-10-01T00:00:00 | 37.669   | -84.6514  | 67618030011 | 
| FFSU      | MA         | 68462        | 0159         | 05           | 2011           | 4       | METFORMIN             | false            | 2580             | 40                      | 233.63                  | 211.63                     | 22                             | 10/1          | 2011-10-01T00:00:00 | 42.2373  | -71.5314  | 68462015905 | 
| FFSU      | AL         | 00185        | 0177         | 01           | 2011           | 1       | SOTALOL HC            | true             |                  |                         |                         |                            |                                | 1/1           | 2011-01-01T00:00:00 | 32.799   | -86.8073  | 00185017701 | 
| FFSU      | WA         | 29033        | 0019         | 12           | 2011           | 2       | Carbamazep            | true             |                  |                         |                         |                            |                                | 4/1           | 2011-04-01T00:00:00 | 47.3917  | -121.5708 | 29033001912 | 
| FFSU      | PA         | 52152        | 0539         | 30           | 2011           | 3       | ONDANSETRO            | false            | 1126             | 82                      | 645.68                  | 580.97                     | 64.71                          | 7/1           | 2011-07-01T00:00:00 | 40.5773  | -77.264   | 52152053930 | 
| FFSU      | RI         | 00555        | 9049         | 58           | 2011           | 1       | CRYSELLE T            | false            | 616              | 22                      | 45.74                   | 19.96                      | 25.78                          | 1/1           | 2011-01-01T00:00:00 | 41.6772  | -71.5101  | 00555904958 | 
| MCOU      | MN         | 63868        | 0500         | 24           | 2011           | 2       | COMPLETE A            | true             |                  |                         |                         |                            |                                | 4/1           | 2011-04-01T00:00:00 | 45.7326  | -93.9196  | 63868050024 | 
| FFSU      | PA         | 50111        | 0309         | 03           | 2011           | 2       | HYDROXYZIN            | true             |                  |                         |                         |                            |                                | 4/1           | 2011-04-01T00:00:00 | 40.5773  | -77.264   | 50111030903 | 
| FFSU      | ND         | 00054        | 0224         | 63           | 2011           | 2       | LEVETIRACE            | false            | 31005            | 101                     | 5148.72                 | 4239.02                    | 909.7                          | 4/1           | 2011-04-01T00:00:00 | 47.5362  | -99.793   | 00054022463 | 
```