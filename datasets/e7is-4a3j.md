# State Drug Utilization Data 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2006) |
| Metadata | [Link](https://data.medicaid.gov/api/views/e7is-4a3j) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/e7is-4a3j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/e7is-4a3j/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | e7is-4a3j |
| Name | State Drug Utilization Data 2006 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:13:04Z |
| Publication Date | 2016-08-29T22:11:40Z |

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
series e:e7is-4a3j d:2006-10-01T00:00:00.000Z t:product_fda_list_name="AMOX TR-K" t:ndc=66685101201 t:package_size=01 t:state_code=MS t:labeler_code=66685 t:product_code=1012 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=21548.28 m:number_of_prescriptions=419 m:units_reimbursed=41950 m:non_medicaid_amount_reimbursed=0

series e:e7is-4a3j d:2006-04-01T00:00:00.000Z t:product_fda_list_name=NITROFURAN t:ndc=63304051801 t:package_size=01 t:state_code=TN t:labeler_code=63304 t:product_code=0518 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2653.9 m:number_of_prescriptions=118 m:units_reimbursed=2100 m:non_medicaid_amount_reimbursed=0

series e:e7is-4a3j d:2006-01-01T00:00:00.000Z t:product_fda_list_name="KERATOL 40" t:ndc=51991026819 t:package_size=19 t:state_code=MO t:labeler_code=51991 t:product_code=0268 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=879.94 m:number_of_prescriptions=18 m:units_reimbursed=1615 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:e7is-4a3j l:"State Drug Utilization Data 2006" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/e7is-4a3j

property e:e7is-4a3j t:meta.view v:id=e7is-4a3j v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2006" v:attribution="Centers for Medicare and Medicaid"

property e:e7is-4a3j t:meta.view.license v:name="Public Domain"

property e:e7is-4a3j t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:e7is-4a3j t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:e7is-4a3j t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MS         | 66685        | 1012         | 01           | 2006           | 4       | AMOX TR-K             | false            | 41950            | 419                     | 21548.28                | 0                          | 0                              | 10/1          | 2006-10-01T00:00:00 | 32.7673  | -89.6812  | 66685101201 | 
| FFSU      | CA         | 51285        | 0522         | 02           | 2006           | 2       | PROCHLORPE            | true             |                  |                         |                         |                            |                                | 4/1           | 2006-04-01T00:00:00 | 36.17    | -119.7462 | 51285052202 | 
| FFSU      | TN         | 63304        | 0518         | 01           | 2006           | 2       | NITROFURAN            | false            | 2100             | 118                     | 2653.9                  | 0                          | 0                              | 4/1           | 2006-04-01T00:00:00 | 35.7449  | -86.7489  | 63304051801 | 
| FFSU      | MO         | 00904        | 7914         | 61           | 2006           | 2       | IBUPROFEN             | true             |                  |                         |                         |                            |                                | 4/1           | 2006-04-01T00:00:00 | 38.4623  | -92.302   | 00904791461 | 
| FFSU      | VT         | 00007        | 4892         | 20           | 2006           | 2       | REQUIP(ROP            | true             |                  |                         |                         |                            |                                | 4/1           | 2006-04-01T00:00:00 | 44.0407  | -72.7093  | 00007489220 | 
| FFSU      | MO         | 51991        | 0268         | 19           | 2006           | 1       | KERATOL 40            | false            | 1615             | 18                      | 879.94                  | 0                          | 0                              | 1/1           | 2006-01-01T00:00:00 | 38.4623  | -92.302   | 51991026819 | 
| FFSU      | WA         | 00085        | 0567         | 01           | 2006           | 3       | ELOCON CRE            | false            | 90               | 730000                  | 400000                  | 0                          | 0                              | 7/1           | 2006-07-01T00:00:00 | 47.3917  | -121.5708 | 00085056701 | 
| FFSU      | OR         | 50458        | 0302         | 06           | 2006           | 2       | RISPERDAL             | false            | 84986            | 1649                    | 292241.16               | 271034.16                  | 21207                          | 4/1           | 2006-04-01T00:00:00 | 44.5672  | -122.1269 | 50458030206 | 
| FFSU      | WY         | 57664        | 0506         | 18           | 2006           | 2       | METOPROLOL            | true             |                  |                         |                         |                            |                                | 4/1           | 2006-04-01T00:00:00 | 42.7475  | -107.2085 | 57664050618 | 
| FFSU      | SC         | 62037        | 0699         | 90           | 2006           | 2       | TAZTIA XT             | true             |                  |                         |                         |                            |                                | 4/1           | 2006-04-01T00:00:00 | 33.8191  | -80.9066  | 62037069990 | 
```