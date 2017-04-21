# State Drug Utilization Data 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2012) |
| Metadata | [Link](https://data.medicaid.gov/api/views/yi2j-kk5z) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/yi2j-kk5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/yi2j-kk5z/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | yi2j-kk5z |
| Name | State Drug Utilization Data 2012 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T12:33:26Z |
| Publication Date | 2016-11-01T15:30:55Z |

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
series e:yi2j-kk5z d:2012-01-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=13182.72 m:total_amount_reimbursed=15282.23 m:number_of_prescriptions=61 m:units_reimbursed=2389 m:non_medicaid_amount_reimbursed=2099.51

series e:yi2j-kk5z d:2012-04-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=11543.56 m:total_amount_reimbursed=14372.38 m:number_of_prescriptions=54 m:units_reimbursed=2271 m:non_medicaid_amount_reimbursed=2828.82

series e:yi2j-kk5z d:2012-07-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=9044.29 m:total_amount_reimbursed=11406.33 m:number_of_prescriptions=41 m:units_reimbursed=1800 m:non_medicaid_amount_reimbursed=2362.04
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:yi2j-kk5z l:"State Drug Utilization Data 2012" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/yi2j-kk5z

property e:yi2j-kk5z t:meta.view v:id=yi2j-kk5z v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2012" v:attribution="Centers for Medicare and Medicaid"

property e:yi2j-kk5z t:meta.view.license v:name="Public Domain"

property e:yi2j-kk5z t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:yi2j-kk5z t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:yi2j-kk5z t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2012           | 1       | STRATTERA             | false            | 2389.000         | 61                      | 15282.23                | 13182.72                   | 2099.51                        | 1/1           | 2012-01-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2012           | 2       | STRATTERA             | false            | 2271.000         | 54                      | 14372.38                | 11543.56                   | 2828.82                        | 4/1           | 2012-04-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2012           | 3       | STRATTERA             | false            | 1800.000         | 41                      | 11406.33                | 9044.29                    | 2362.04                        | 7/1           | 2012-07-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2012           | 4       | STRATTERA             | false            | 2078.000         | 56                      | 14424.38                | 12064.92                   | 2359.46                        | 10/1          | 2012-10-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2012           | 1       | STRATTERA             | false            | 4776.000         | 119                     | 30609.50                | 26726.11                   | 3883.39                        | 1/1           | 2012-01-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2012           | 2       | STRATTERA             | false            | 4382.000         | 109                     | 27887.15                | 24741.57                   | 3145.58                        | 4/1           | 2012-04-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2012           | 3       | STRATTERA             | false            | 4337.000         | 103                     | 27774.05                | 24070.44                   | 3703.61                        | 7/1           | 2012-07-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2012           | 4       | STRATTERA             | false            | 4854.000         | 127                     | 33685.19                | 30875.26                   | 2809.93                        | 10/1          | 2012-10-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3229         | 30           | 2012           | 1       | STRATTERA             | false            | 5984.000         | 208                     | 41144.55                | 37307.29                   | 3837.26                        | 1/1           | 2012-01-01T00:00:00 | 61.3850  | -152.2683 | 00002322930 | 
| FFSU      | AK         | 00002        | 3229         | 30           | 2012           | 2       | STRATTERA             | false            | 5794.000         | 196                     | 40152.99                | 35530.34                   | 4622.65                        | 4/1           | 2012-04-01T00:00:00 | 61.3850  | -152.2683 | 00002322930 | 
```