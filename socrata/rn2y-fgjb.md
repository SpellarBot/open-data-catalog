# State Drug Utilization Data 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2004) |
| Metadata | [Link](https://data.medicaid.gov/api/views/rn2y-fgjb) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/rn2y-fgjb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/rn2y-fgjb/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | rn2y-fgjb |
| Name | State Drug Utilization Data 2004 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:23:37Z |
| Publication Date | 2016-08-29T19:25:07Z |

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
series e:rn2y-fgjb d:2004-04-01T00:00:00.000Z t:product_fda_list_name=ALPRAZOLAM t:ndc=00781107710 t:package_size=10 t:state_code=MT t:labeler_code=00781 t:product_code=1077 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=309.8 m:total_amount_reimbursed=338.8 m:number_of_prescriptions=36 m:units_reimbursed=2430 m:non_medicaid_amount_reimbursed=29

series e:rn2y-fgjb d:2004-01-01T00:00:00.000Z t:product_fda_list_name="DOVONEX 0." t:ndc=00072254006 t:package_size=06 t:state_code=MS t:labeler_code=00072 t:product_code=2540 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=9030.67 m:total_amount_reimbursed=9030.67 m:number_of_prescriptions=69 m:units_reimbursed=4605 m:non_medicaid_amount_reimbursed=0

series e:rn2y-fgjb d:2004-10-01T00:00:00.000Z t:product_fda_list_name=LEVOTHROID t:ndc=00456132101 t:package_size=01 t:state_code=CT t:labeler_code=00456 t:product_code=1321 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=3824.36 m:number_of_prescriptions=393 m:units_reimbursed=12228 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:rn2y-fgjb l:"State Drug Utilization Data 2004" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/rn2y-fgjb

property e:rn2y-fgjb t:meta.view v:id=rn2y-fgjb v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2004" v:attribution="Centers for Medicare and Medicaid"

property e:rn2y-fgjb t:meta.view.license v:name="Public Domain"

property e:rn2y-fgjb t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:rn2y-fgjb t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:rn2y-fgjb t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MT         | 00781        | 1077         | 10           | 2004           | 2       | ALPRAZOLAM            | false            | 2430             | 36                      | 338.8                   | 309.8                      | 29                             | 4/1           | 2004-04-01T00:00:00 | 46.9048  | -110.3261 | 00781107710 | 
| FFSU      | FL         | 61703        | 0332         | 18           | 2004           | 1       | BLEOMYCIN             | true             |                  |                         |                         |                            |                                | 1/1           | 2004-01-01T00:00:00 | 27.8333  | -81.717   | 61703033218 | 
| FFSU      | MS         | 00072        | 2540         | 06           | 2004           | 1       | DOVONEX 0.            | false            | 4605             | 69                      | 9030.67                 | 9030.67                    | 0                              | 1/1           | 2004-01-01T00:00:00 | 32.7673  | -89.6812  | 00072254006 | 
| FFSU      | MI         | 63323        | 0247         | 10           | 2004           | 1       | LEVOTHYROX            | true             |                  |                         |                         |                            |                                | 1/1           | 2004-01-01T00:00:00 | 43.3504  | -84.5603  | 63323024710 | 
| FFSU      | CT         | 00456        | 1321         | 01           | 2004           | 4       | LEVOTHROID            | false            | 12228            | 393                     | 3824.36                 | 0                          | 0                              | 10/1          | 2004-10-01T00:00:00 | 41.5834  | -72.7622  | 00456132101 | 
| FFSU      | OR         | 24385        | 0403         | 71           | 2004           | 2       | PAIN RELIE            | true             |                  |                         |                         |                            |                                | 4/1           | 2004-04-01T00:00:00 | 44.5672  | -122.1269 | 24385040371 | 
| FFSU      | NY         | 00378        | 0030         | 05           | 2004           | 2       | CLORAZEPAT            | true             |                  |                         |                         |                            |                                | 4/1           | 2004-04-01T00:00:00 | 42.1497  | -74.9384  | 00378003005 | 
| FFSU      | CA         | 00026        | 8889         | 50           | 2004           | 3       | CIPRO XR              | false            | 2655             | 849                     | 24420.16                | 24420.16                   | 0                              | 7/1           | 2004-07-01T00:00:00 | 36.17    | -119.7462 | 00026888950 | 
| FFSU      | NM         | 17478        | 0063         | 35           | 2004           | 4       | TEARS RENE            | true             |                  |                         |                         |                            |                                | 10/1          | 2004-10-01T00:00:00 | 34.8375  | -106.2371 | 17478006335 | 
| FFSU      | MI         | 00006        | 0952         | 31           | 2004           | 4       | COZAAR                | false            | 34435            | 866                     | 52402.55                | 51470.02                   | 932.53                         | 10/1          | 2004-10-01T00:00:00 | 43.3504  | -84.5603  | 00006095231 | 
```