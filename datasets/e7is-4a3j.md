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
| Rows Updated | 2017-02-03T02:20:57Z |

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
| Yes      | numeric metric | package_size                   | Package Size                   | number        | text          |
| Yes      | numeric metric | period_covered                 | Year                           | number        | text          |
| Yes      | numeric metric | quarter                        | Quarter                        | number        | text          |
| Yes      | series tag     | product_fda_list_name          | Product Name                   | text          | text          |
| Yes      | series tag     | suppression_used               | Suppression Used               | checkbox      | checkbox      |
| Yes      | numeric metric | units_reimbursed               | Units Reimbursed               | number        | number        |
| Yes      | numeric metric | number_of_prescriptions        | Number of Prescriptions        | number        | number        |
| Yes      | numeric metric | total_amount_reimbursed        | Total Amount Reimbursed        | number        | number        |
| Yes      | numeric metric | medicaid_amount_reimbursed     | Medicaid Amount Reimbursed     | number        | number        |
| Yes      | numeric metric | non_medicaid_amount_reimbursed | Non Medicaid Amount Reimbursed | number        | number        |
| Yes      | series tag     | quarter_begin                  | Quarter Begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | Latitude                       | number        | number        |
| No       |                | longitude                      | Longitude                      | number        | number        |
| Yes      | numeric metric | ndc                            | NDC                            | number        | text          |
```

## Time Field

```ls
Value = quarter_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:e7is-4a3j d:2006-10-01T00:00:00.000Z t:product_fda_list_name="AMOX TR-K" t:quarter_begin=10/1 t:state_code=MS t:labeler_code=66685 t:product_code=1012 t:suppression_used=false t:record_id=FFSU m:package_size=1 m:ndc=66685101201 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=21548.28 m:number_of_prescriptions=419 m:units_reimbursed=41950 m:period_covered=2006 m:non_medicaid_amount_reimbursed=0 m:quarter=4

series e:e7is-4a3j d:2006-04-01T00:00:00.000Z t:product_fda_list_name=PROCHLORPE t:quarter_begin=4/1 t:state_code=CA t:labeler_code=51285 t:product_code=0522 t:suppression_used=true t:record_id=FFSU m:package_size=2 m:ndc=51285052202 m:period_covered=2006 m:quarter=2

series e:e7is-4a3j d:2006-04-01T00:00:00.000Z t:product_fda_list_name=NITROFURAN t:quarter_begin=4/1 t:state_code=TN t:labeler_code=63304 t:product_code=0518 t:suppression_used=false t:record_id=FFSU m:package_size=1 m:ndc=63304051801 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2653.9 m:number_of_prescriptions=118 m:units_reimbursed=2100 m:period_covered=2006 m:non_medicaid_amount_reimbursed=0 m:quarter=2
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size" d:"Third segment of National Drug Code (NDC3) identifies package forms and sizes." t:dataTypeName=number

metric m:period_covered p:integer l:Year d:"Calendar year" t:dataTypeName=number

metric m:quarter p:integer l:Quarter d:"Quarter of year (1-4) 1 = January 1 ? March 31, 2 = April 1 ? June 30, 3 = July 1 ? September 30, 4 = October 1 ? December 31" t:dataTypeName=number

metric m:units_reimbursed l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:e7is-4a3j l:"State Drug Utilization Data 2006" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/e7is-4a3j

property e:e7is-4a3j t:meta.view v:id=e7is-4a3j v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2006" v:attribution="Centers for Medicare and Medicaid"

property e:e7is-4a3j t:meta.view.license v:name="Public Domain"

property e:e7is-4a3j t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:e7is-4a3j t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:e7is-4a3j t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```