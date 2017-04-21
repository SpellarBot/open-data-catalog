# State Drug Utilization Data 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2013) |
| Metadata | [Link](https://data.medicaid.gov/api/views/rkct-3tm8) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/rkct-3tm8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/rkct-3tm8/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | rkct-3tm8 |
| Name | State Drug Utilization Data 2013 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T12:31:51Z |
| Publication Date | 2016-11-01T15:31:07Z |

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
series e:rkct-3tm8 d:2013-01-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=10843.62 m:total_amount_reimbursed=11357.58 m:number_of_prescriptions=47 m:units_reimbursed=1626 m:non_medicaid_amount_reimbursed=513.96

series e:rkct-3tm8 d:2013-04-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=10250.72 m:total_amount_reimbursed=10815.92 m:number_of_prescriptions=42 m:units_reimbursed=1492 m:non_medicaid_amount_reimbursed=565.2

series e:rkct-3tm8 d:2013-07-01T00:00:00.000Z t:product_fda_list_name=STRATTERA t:ndc=00002322730 t:package_size=30 t:state_code=AK t:labeler_code=00002 t:product_code=3227 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=9210.67 m:total_amount_reimbursed=9587.47 m:number_of_prescriptions=31 m:units_reimbursed=1269 m:non_medicaid_amount_reimbursed=376.8
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:rkct-3tm8 l:"State Drug Utilization Data 2013" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/rkct-3tm8

property e:rkct-3tm8 t:meta.view v:id=rkct-3tm8 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2013" v:attribution="Centers for Medicare and Medicaid"

property e:rkct-3tm8 t:meta.view.license v:name="Public Domain"

property e:rkct-3tm8 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:rkct-3tm8 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:rkct-3tm8 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | AK         | 00002        | 1975         | 90           | 2013           | 1       | AXIRON                | true             |                  |                         |                         |                            |                                | 1/1           | 2013-01-01T00:00:00 | 61.3850  | -152.2683 | 00002197590 | 
| FFSU      | AK         | 00002        | 1975         | 90           | 2013           | 2       | AXIRON                | true             |                  |                         |                         |                            |                                | 4/1           | 2013-04-01T00:00:00 | 61.3850  | -152.2683 | 00002197590 | 
| FFSU      | AK         | 00002        | 1975         | 90           | 2013           | 4       | AXIRON                | true             |                  |                         |                         |                            |                                | 10/1          | 2013-10-01T00:00:00 | 61.3850  | -152.2683 | 00002197590 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2013           | 1       | STRATTERA             | false            | 1626.000         | 47                      | 11357.58                | 10843.62                   | 513.96                         | 1/1           | 2013-01-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2013           | 2       | STRATTERA             | false            | 1492.000         | 42                      | 10815.92                | 10250.72                   | 565.20                         | 4/1           | 2013-04-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2013           | 3       | STRATTERA             | false            | 1269.000         | 31                      | 9587.47                 | 9210.67                    | 376.80                         | 7/1           | 2013-07-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3227         | 30           | 2013           | 4       | STRATTERA             | false            | 1295.000         | 48                      | 9764.94                 | 9011.34                    | 753.60                         | 10/1          | 2013-10-01T00:00:00 | 61.3850  | -152.2683 | 00002322730 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2013           | 1       | STRATTERA             | false            | 4037.000         | 103                     | 28116.81                | 26294.90                   | 1821.91                        | 1/1           | 2013-01-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2013           | 2       | STRATTERA             | false            | 3170.000         | 81                      | 22803.53                | 21360.65                   | 1442.88                        | 4/1           | 2013-04-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
| FFSU      | AK         | 00002        | 3228         | 30           | 2013           | 3       | STRATTERA             | false            | 3411.000         | 78                      | 25705.56                | 23327.96                   | 2377.60                        | 7/1           | 2013-07-01T00:00:00 | 61.3850  | -152.2683 | 00002322830 | 
```