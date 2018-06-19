# State Drug Utilization Data 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1998) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ykva-ug36) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ykva-ug36/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ykva-ug36/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ykva-ug36 |
| Name | State Drug Utilization Data 1998 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:20:49Z |
| Publication Date | 2016-08-29T22:24:52Z |

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
series e:ykva-ug36 d:1998-01-01T00:00:00.000Z t:product_fda_list_name="NORPACE CR" t:ndc=00025273231 t:package_size=31 t:state_code=MO t:labeler_code=00025 t:product_code=2732 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=4682.39 m:number_of_prescriptions=77 m:units_reimbursed=6570 m:non_medicaid_amount_reimbursed=0

series e:ykva-ug36 d:1998-07-01T00:00:00.000Z t:product_fda_list_name=BUTALBITAL t:ndc=00143178501 t:package_size=01 t:state_code=XX t:labeler_code=00143 t:product_code=1785 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=7250.35 m:number_of_prescriptions=1311 m:units_reimbursed=57942 m:non_medicaid_amount_reimbursed=0

series e:ykva-ug36 d:1998-01-01T00:00:00.000Z t:product_fda_list_name=METOCLOPRA t:ndc=00904107316 t:package_size=16 t:state_code=IL t:labeler_code=00904 t:product_code=1073 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=633.69 m:number_of_prescriptions=38 m:units_reimbursed=14102 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:float l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:ykva-ug36 l:"State Drug Utilization Data 1998" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ykva-ug36

property e:ykva-ug36 t:meta.view v:id=ykva-ug36 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1998" v:attribution="Centers for Medicare and Medicaid"

property e:ykva-ug36 t:meta.view.license v:name="Public Domain"

property e:ykva-ug36 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ykva-ug36 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ykva-ug36 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | WV         | 55513        | 0148         | 01           | 1998           | 3       | EPOGEN (EP            |                  | true             |                         |                         |                            |                                | 7/1           | 1998-07-01T00:00:00 | 38.468   | -80.9696  | 55513014801 | 
| FFSU      | NM         | 00536        | 1423         | 26           | 1998           | 1       | MICONAZOLE            |                  | true             |                         |                         |                            |                                | 1/1           | 1998-01-01T00:00:00 | 34.8375  | -106.2371 | 00536142326 | 
| FFSU      | WY         | 00074        | 6025         | 13           | 1998           | 1       | CYLERT TAB            |                  | true             |                         |                         |                            |                                | 1/1           | 1998-01-01T00:00:00 | 42.7475  | -107.2085 | 00074602513 | 
| FFSU      | MT         | 49884        | 0449         | 05           | 1998           | 2       | ALPRAZOLAM            |                  | true             |                         |                         |                            |                                | 4/1           | 1998-04-01T00:00:00 | 46.9048  | -110.3261 | 49884044905 | 
| FFSU      | MO         | 00025        | 2732         | 31           | 1998           | 1       | NORPACE CR            | 6570             | false            | 77                      | 4682.39                 | 0                          | 0                              | 1/1           | 1998-01-01T00:00:00 | 38.4623  | -92.302   | 00025273231 | 
| FFSU      | XX         | 00143        | 1785         | 01           | 1998           | 3       | BUTALBITAL            | 57942            | false            | 1311                    | 7250.35                 | 0                          | 0                              | 7/1           | 1998-07-01T00:00:00 |          |           | 00143178501 | 
| FFSU      | IL         | 00904        | 1073         | 16           | 1998           | 1       | METOCLOPRA            | 14102            | false            | 38                      | 633.69                  | 0                          | 0                              | 1/1           | 1998-01-01T00:00:00 | 40.3363  | -89.0022  | 00904107316 | 
| FFSU      | OK         | 00781        | 1373         | 01           | 1998           | 1       | GUANFACINE            |                  | true             |                         |                         |                            |                                | 1/1           | 1998-01-01T00:00:00 | 35.5376  | -96.9247  | 00781137301 | 
| FFSU      | CA         | 00781        | 1973         | 01           | 1998           | 2       | DESIPRAMIN            | 85487            | false            | 1020                    | 12186.08                | 0                          | 0                              | 4/1           | 1998-04-01T00:00:00 | 36.17    | -119.7462 | 00781197301 | 
| FFSU      | NV         | 49884        | 0043         | 01           | 1998           | 3       | CYPROHEPTA            |                  | true             |                         |                         |                            |                                | 7/1           | 1998-07-01T00:00:00 | 38.4199  | -117.1219 | 49884004301 | 
```