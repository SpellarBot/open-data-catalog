# State Drug Utilization Data 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1999) |
| Metadata | [Link](https://data.medicaid.gov/api/views/vhg8-v7wa) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/vhg8-v7wa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/vhg8-v7wa/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | vhg8-v7wa |
| Name | State Drug Utilization Data 1999 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:20:33Z |
| Publication Date | 2016-08-29T22:48:07Z |

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
series e:vhg8-v7wa d:1999-07-01T00:00:00.000Z t:product_fda_list_name=CHLORPROMA t:ndc=00832030000 t:package_size=00 t:state_code=MO t:labeler_code=00832 t:product_code=0300 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=296.08 m:number_of_prescriptions=18 m:units_reimbursed=960 m:non_medicaid_amount_reimbursed=0

series e:vhg8-v7wa d:1999-01-01T00:00:00.000Z t:product_fda_list_name=ALPRAZOLAM t:ndc=59762372003 t:package_size=03 t:state_code=AK t:labeler_code=59762 t:product_code=3720 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=812.13 m:number_of_prescriptions=75 m:units_reimbursed=3536 m:non_medicaid_amount_reimbursed=0

series e:vhg8-v7wa d:1999-10-01T00:00:00.000Z t:product_fda_list_name="RESTORIL 1" t:ndc=00078009808 t:package_size=08 t:state_code=XX t:labeler_code=00078 t:product_code=0098 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=721.29 m:number_of_prescriptions=28 m:units_reimbursed=871 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:float l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:vhg8-v7wa l:"State Drug Utilization Data 1999" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/vhg8-v7wa

property e:vhg8-v7wa t:meta.view v:id=vhg8-v7wa v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1999" v:attribution="Centers for Medicare and Medicaid"

property e:vhg8-v7wa t:meta.view.license v:name="Public Domain"

property e:vhg8-v7wa t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:vhg8-v7wa t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:vhg8-v7wa t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MN         | 00009        | 0725         | 03           | 1999           | 1       | MOTRIN                |                  | true             |                         |                         |                            |                                | 1/1           | 1999-01-01T00:00:00 | 45.7326  | -93.9196  | 00009072503 | 
| FFSU      | MO         | 00832        | 0300         | 00           | 1999           | 3       | CHLORPROMA            | 960              | false            | 18                      | 296.08                  | 0                          | 0                              | 7/1           | 1999-07-01T00:00:00 | 38.4623  | -92.302   | 00832030000 | 
| FFSU      | AK         | 59762        | 3720         | 03           | 1999           | 1       | ALPRAZOLAM            | 3536             | false            | 75                      | 812.13                  | 0                          | 0                              | 1/1           | 1999-01-01T00:00:00 | 61.385   | -152.2683 | 59762372003 | 
| FFSU      | IN         | 00088        | 1771         | 47           | 1999           | 4       | CARDIZEM 3            |                  | true             |                         |                         |                            |                                | 10/1          | 1999-10-01T00:00:00 | 39.8647  | -86.2604  | 00088177147 | 
| FFSU      | XX         | 00078        | 0098         | 08           | 1999           | 4       | RESTORIL 1            | 871              | false            | 28                      | 721.29                  | 0                          | 0                              | 10/1          | 1999-10-01T00:00:00 |          |           | 00078009808 | 
| FFSU      | FL         | 00182        | 5094         | 60           | 1999           | 4       | CLOTRIMAZO            |                  | true             |                         |                         |                            |                                | 10/1          | 1999-10-01T00:00:00 | 27.8333  | -81.717   | 00182509460 | 
| FFSU      | DC         | 00008        | 4191         | 01           | 1999           | 1       | SYNALGOS-D            |                  | true             |                         |                         |                            |                                | 1/1           | 1999-01-01T00:00:00 | 38.8964  | -77.0262  | 00008419101 | 
| FFSU      | MA         | 00143        | 1227         | 10           | 1999           | 1       | DICYCLOMIN            | 2152             | false            | 33                      | 170.6                   | 0                          | 0                              | 1/1           | 1999-01-01T00:00:00 | 42.2373  | -71.5314  | 00143122710 | 
| FFSU      | IN         | 00469        | 0280         | 25           | 1999           | 2       | FUROSEMIDE            |                  | true             |                         |                         |                            |                                | 4/1           | 1999-04-01T00:00:00 | 39.8647  | -86.2604  | 00469028025 | 
| FFSU      | SC         | 60758        | 0801         | 10           | 1999           | 2       | TIMOLOL MA            |                  | true             |                         |                         |                            |                                | 4/1           | 1999-04-01T00:00:00 | 33.8191  | -80.9066  | 60758080110 | 
```