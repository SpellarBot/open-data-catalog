# State Drug Utilization Data 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2016) |
| Metadata | [Link](https://data.medicaid.gov/api/views/3v6v-qk5s) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/3v6v-qk5s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/3v6v-qk5s/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 3v6v-qk5s |
| Name | State Drug Utilization Data 2016 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2016-08-01T19:24:51Z |
| Publication Date | 2016-11-01T15:23:45Z |

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | utilization_type               | Utilization Type               | text          | text          |
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
| No       |                | quarter_begin                  | Quarter begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | _latitude                      | number        | number        |
| No       |                | longitude                      | _longitude                     | number        | number        |
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
series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="GLUCAGON E" t:ndc=00002803101 t:package_size=01 t:state_code=AK t:labeler_code=00002 t:product_code=8031 t:utilization_type=FFSU t:suppression_used=false m:medicaid_amount_reimbursed=14265.5 m:total_amount_reimbursed=15987.86 m:number_of_prescriptions=49 m:units_reimbursed=69.4 m:non_medicaid_amount_reimbursed=1722.36

series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="HUMULIN 70" t:ndc=00002871501 t:package_size=01 t:state_code=AK t:labeler_code=00002 t:product_code=8715 t:utilization_type=FFSU t:suppression_used=false m:medicaid_amount_reimbursed=8248.51 m:total_amount_reimbursed=8248.51 m:number_of_prescriptions=14 m:units_reimbursed=650 m:non_medicaid_amount_reimbursed=0

series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="HUMALOG KW" t:ndc=00002879959 t:package_size=59 t:state_code=AK t:labeler_code=00002 t:product_code=8799 t:utilization_type=FFSU t:suppression_used=false m:medicaid_amount_reimbursed=183302.84 m:total_amount_reimbursed=187541.53 m:number_of_prescriptions=392 m:units_reimbursed=6267 m:non_medicaid_amount_reimbursed=4238.69
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" t:dataTypeName=number

entity e:3v6v-qk5s l:"State Drug Utilization Data 2016" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/3v6v-qk5s

property e:3v6v-qk5s t:meta.view v:id=3v6v-qk5s v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2016" v:attribution="Centers for Medicare and Medicaid"

property e:3v6v-qk5s t:meta.view.license v:name="Public Domain"

property e:3v6v-qk5s t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| utilization_type | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ================ | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU             | AK         | 00002        | 4453         | 01           | 2016           | 1       | ZYPREXA ZY            | true             |                  |                         |                         |                            |                                | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002445301 | 
| FFSU             | AK         | 00002        | 4453         | 01           | 2016           | 2       | ZYPREXA ZY            | true             |                  |                         |                         |                            |                                | 4/1           | 2016-04-01T00:00:00 | 61.3850  | -152.2683 | 00002445301 | 
| FFSU             | AK         | 00002        | 4453         | 85           | 2016           | 1       | ZYPREXA ZY            | true             |                  |                         |                         |                            |                                | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002445385 | 
| FFSU             | AK         | 00002        | 4453         | 85           | 2016           | 2       | ZYPREXA ZY            | true             |                  |                         |                         |                            |                                | 4/1           | 2016-04-01T00:00:00 | 61.3850  | -152.2683 | 00002445385 | 
| FFSU             | AK         | 00002        | 7511         | 01           | 2016           | 1       | HUMALOG MI            | true             |                  |                         |                         |                            |                                | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002751101 | 
| FFSU             | AK         | 00002        | 7512         | 01           | 2016           | 2       | HUMALOG MI            | true             |                  |                         |                         |                            |                                | 4/1           | 2016-04-01T00:00:00 | 61.3850  | -152.2683 | 00002751201 | 
| FFSU             | AK         | 00002        | 7712         | 27           | 2016           | 1       | HUMALOG KW            | true             |                  |                         |                         |                            |                                | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002771227 | 
| FFSU             | AK         | 00002        | 7712         | 27           | 2016           | 2       | HUMALOG KW            | true             |                  |                         |                         |                            |                                | 4/1           | 2016-04-01T00:00:00 | 61.3850  | -152.2683 | 00002771227 | 
| FFSU             | AK         | 00002        | 8031         | 01           | 2016           | 1       | GLUCAGON E            | false            | 69.400           | 49                      | 15987.86                | 14265.50                   | 1722.36                        | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002803101 | 
| FFSU             | AK         | 00002        | 8715         | 01           | 2016           | 1       | HUMULIN 70            | false            | 650.000          | 14                      | 8248.51                 | 8248.51                    | 0.00                           | 1/1           | 2016-01-01T00:00:00 | 61.3850  | -152.2683 | 00002871501 | 
```