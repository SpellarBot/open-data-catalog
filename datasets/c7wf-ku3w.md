# State Drug Utilization Data 1997

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1997) |
| Metadata | [Link](https://data.medicaid.gov/api/views/c7wf-ku3w) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/c7wf-ku3w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/c7wf-ku3w/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | c7wf-ku3w |
| Name | State Drug Utilization Data 1997 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:22:17Z |
| Publication Date | 2016-08-29T18:54:20Z |

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
series e:c7wf-ku3w d:1997-04-01T00:00:00.000Z t:product_fda_list_name=EC-NAPROSY t:ndc=18393025542 t:package_size=42 t:state_code=LA t:labeler_code=18393 t:product_code=0255 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=28435.08 m:number_of_prescriptions=633 m:units_reimbursed=26792 m:non_medicaid_amount_reimbursed=0

series e:c7wf-ku3w d:1997-10-01T00:00:00.000Z t:product_fda_list_name=DARVOCET-N t:ndc=00002036303 t:package_size=03 t:state_code=WI t:labeler_code=00002 t:product_code=0363 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=3274.66 m:number_of_prescriptions=104 m:units_reimbursed=6883 m:non_medicaid_amount_reimbursed=0

series e:c7wf-ku3w d:1997-10-01T00:00:00.000Z t:product_fda_list_name="SINEMET CR" t:ndc=00056060168 t:package_size=68 t:state_code=KY t:labeler_code=00056 t:product_code=0601 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=13623.52 m:number_of_prescriptions=256 m:units_reimbursed=18165 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:c7wf-ku3w l:"State Drug Utilization Data 1997" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/c7wf-ku3w

property e:c7wf-ku3w t:meta.view v:id=c7wf-ku3w v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1997" v:attribution="Centers for Medicare and Medicaid"

property e:c7wf-ku3w t:meta.view.license v:name="Public Domain"

property e:c7wf-ku3w t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:c7wf-ku3w t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:c7wf-ku3w t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | LA         | 18393        | 0255         | 42           | 1997           | 2       | EC-NAPROSY            | false            | 26792            | 633                     | 28435.08                | 0                          | 0                              | 4/1           | 1997-04-01T00:00:00 | 31.1801  | -91.8749  | 18393025542 | 
| FFSU      | PA         | 00054        | 3545         | 63           | 1997           | 4       | MEPERID 50            | true             |                  |                         |                         |                            |                                | 10/1          | 1997-10-01T00:00:00 | 40.5773  | -77.264   | 00054354563 | 
| FFSU      | NV         | 00536        | 4959         | 05           | 1997           | 4       | BACLOFEN U            | true             |                  |                         |                         |                            |                                | 10/1          | 1997-10-01T00:00:00 | 38.4199  | -117.1219 | 00536495905 | 
| FFSU      | XX         | 54092        | 0010         | 01           | 1997           | 2       | P-A-C TABL            | true             |                  |                         |                         |                            |                                | 4/1           | 1997-04-01T00:00:00 |          |           | 54092001001 | 
| FFSU      | VA         | 59743        | 0061         | 01           | 1997           | 3       | PSEUBROM-P            | true             |                  |                         |                         |                            |                                | 7/1           | 1997-07-01T00:00:00 | 37.768   | -78.2057  | 59743006101 | 
| FFSU      | XX         | 00781        | 1815         | 10           | 1997           | 3       | ISONIAZID             | true             |                  |                         |                         |                            |                                | 7/1           | 1997-07-01T00:00:00 |          |           | 00781181510 | 
| FFSU      | VA         | 00677        | 0443         | 01           | 1997           | 3       | PROPOXYPHE            | true             |                  |                         |                         |                            |                                | 7/1           | 1997-07-01T00:00:00 | 37.768   | -78.2057  | 00677044301 | 
| FFSU      | ME         | 00026        | 8554         | 63           | 1997           | 4       | CIPROFLOXA            | true             |                  |                         |                         |                            |                                | 10/1          | 1997-10-01T00:00:00 | 44.6074  | -69.3977  | 00026855463 | 
| FFSU      | WV         | 51079        | 0107         | 20           | 1997           | 3       | AMITRIPTYL            | true             |                  |                         |                         |                            |                                | 7/1           | 1997-07-01T00:00:00 | 38.468   | -80.9696  | 51079010720 | 
| FFSU      | RI         | 00364        | 2233         | 01           | 1997           | 1       | Acetohexam            | true             |                  |                         |                         |                            |                                | 1/1           | 1997-01-01T00:00:00 | 41.6772  | -71.5101  | 00364223301 | 
```