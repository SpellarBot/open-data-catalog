# State Drug Utilization Data 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2009) |
| Metadata | [Link](https://data.medicaid.gov/api/views/fhmx-iqs3) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/fhmx-iqs3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/fhmx-iqs3/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | fhmx-iqs3 |
| Name | State Drug Utilization Data 2009 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:10:36Z |
| Publication Date | 2016-08-29T18:20:21Z |

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
series e:fhmx-iqs3 d:2009-07-01T00:00:00.000Z t:product_fda_list_name=CLARITHROM t:ndc=00093715806 t:package_size=06 t:state_code=MN t:labeler_code=00093 t:product_code=7158 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=866.04 m:total_amount_reimbursed=866.04 m:number_of_prescriptions=40 m:units_reimbursed=942 m:non_medicaid_amount_reimbursed=0

series e:fhmx-iqs3 d:2009-01-01T00:00:00.000Z t:product_fda_list_name=CITALOPRAM t:ndc=00591317705 t:package_size=05 t:state_code=IA t:labeler_code=00591 t:product_code=3177 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=98.61 m:total_amount_reimbursed=98.61 m:number_of_prescriptions=17 m:units_reimbursed=463 m:non_medicaid_amount_reimbursed=0

series e:fhmx-iqs3 d:2009-01-01T00:00:00.000Z t:product_fda_list_name=FLUOXETINE t:ndc=49884073501 t:package_size=01 t:state_code=MT t:labeler_code=49884 t:product_code=0735 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=2033.54 m:total_amount_reimbursed=2150.09 m:number_of_prescriptions=69 m:units_reimbursed=2988 m:non_medicaid_amount_reimbursed=116.55
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:fhmx-iqs3 l:"State Drug Utilization Data 2009" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/fhmx-iqs3

property e:fhmx-iqs3 t:meta.view v:id=fhmx-iqs3 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2009" v:attribution="Centers for Medicare and Medicaid"

property e:fhmx-iqs3 t:meta.view.license v:name="Public Domain"

property e:fhmx-iqs3 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:fhmx-iqs3 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:fhmx-iqs3 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | MN         | 00093        | 7158         | 06           | 2009           | 3       | CLARITHROM            | false            | 942              | 40                      | 866.04                  | 866.04                     | 0                              | 7/1           | 2009-07-01T00:00:00 | 45.7326  | -93.9196  | 00093715806 | 
| FFSU      | IA         | 00591        | 3177         | 05           | 2009           | 1       | CITALOPRAM            | false            | 463              | 17                      | 98.61                   | 98.61                      | 0                              | 1/1           | 2009-01-01T00:00:00 | 42.0046  | -93.214   | 00591317705 | 
| FFSU      | MT         | 49884        | 0735         | 01           | 2009           | 1       | FLUOXETINE            | false            | 2988             | 69                      | 2150.09                 | 2033.54                    | 116.55                         | 1/1           | 2009-01-01T00:00:00 | 46.9048  | -110.3261 | 49884073501 | 
| FFSU      | WA         | 00904        | 0761         | 60           | 2009           | 1       | THYROID 1G            | true             |                  |                         |                         |                            |                                | 1/1           | 2009-01-01T00:00:00 | 47.3917  | -121.5708 | 00904076160 | 
| FFSU      | IA         | 16714        | 0041         | 04           | 2009           | 1       | ALLOPURINO            | false            | 640              | 16                      | 90.31                   | 90.31                      | 0                              | 1/1           | 2009-01-01T00:00:00 | 42.0046  | -93.214   | 16714004104 | 
| FFSU      | MT         | 00168        | 0015         | 16           | 2009           | 2       | HYDROCORTI            | true             |                  |                         |                         |                            |                                | 4/1           | 2009-04-01T00:00:00 | 46.9048  | -110.3261 | 00168001516 | 
| FFSU      | MN         | 58177        | 0350         | 26           | 2009           | 3       | ADVANCED N            | true             |                  |                         |                         |                            |                                | 7/1           | 2009-07-01T00:00:00 | 45.7326  | -93.9196  | 58177035026 | 
| FFSU      | PA         | 50474        | 0597         | 66           | 2009           | 2       | KEPPRA 1,0            | false            | 31192            | 460                     | 204894.73               | 188286.43                  | 16608.3                        | 4/1           | 2009-04-01T00:00:00 | 40.5773  | -77.264   | 50474059766 | 
| FFSU      | XX         | 00409        | 7997         | 09           | 2009           | 2       | D5%-1/4NS-            | true             |                  |                         |                         |                            |                                | 4/1           | 2009-04-01T00:00:00 |          |           | 00409799709 | 
| FFSU      | GA         | 00228        | 2539         | 96           | 2009           | 3       | CARB/LEVO             | false            | 7525             | 94                      | 3344.72                 | 3048.84                    | 295.88                         | 7/1           | 2009-07-01T00:00:00 | 32.9866  | -83.6487  | 00228253996 | 
```