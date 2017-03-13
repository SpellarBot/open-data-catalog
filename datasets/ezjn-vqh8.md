# State Drug Utilization Data 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2005) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ezjn-vqh8) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ezjn-vqh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ezjn-vqh8/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ezjn-vqh8 |
| Name | State Drug Utilization Data 2005 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:23:15Z |
| Publication Date | 2016-08-29T22:58:27Z |
| Rows Updated | 2017-02-03T02:30:37Z |

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
| No       |                | quarter                        | Quarter                        | number        | text          |
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
Excluded Fields = latitude,longitude,quarter
```

## Data Commands

```ls
series e:ezjn-vqh8 d:2005-04-01T00:00:00.000Z t:product_fda_list_name=INTAL t:quarter_begin=4/1 t:state_code=MO t:labeler_code=60793 t:product_code=0011 t:suppression_used=false t:record_id=FFSU m:package_size=8 m:ndc=60793001108 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2953.32 m:number_of_prescriptions=38 m:units_reimbursed=364.5 m:period_covered=2005 m:non_medicaid_amount_reimbursed=0

series e:ezjn-vqh8 d:2005-01-01T00:00:00.000Z t:product_fda_list_name=LACTULOSE t:quarter_begin=1/1 t:state_code=VA t:labeler_code=50383 t:product_code=0795 t:suppression_used=false t:record_id=FFSU m:package_size=16 m:ndc=50383079516 m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=6713.48 m:number_of_prescriptions=432 m:units_reimbursed=255853 m:period_covered=2005 m:non_medicaid_amount_reimbursed=0

series e:ezjn-vqh8 d:2005-01-01T00:00:00.000Z t:product_fda_list_name="ESTRING VA" t:quarter_begin=1/1 t:state_code=NE t:labeler_code=00013 t:product_code=2150 t:suppression_used=true t:record_id=FFSU m:package_size=36 m:ndc=13215036 m:period_covered=2005
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size" d:"Third segment of National Drug Code (NDC3) identifies package forms and sizes." t:dataTypeName=number

metric m:period_covered p:integer l:Year d:"Calendar year" t:dataTypeName=number

metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:ezjn-vqh8 l:"State Drug Utilization Data 2005" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ezjn-vqh8

property e:ezjn-vqh8 t:meta.view v:id=ezjn-vqh8 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2005" v:attribution="Centers for Medicare and Medicaid"

property e:ezjn-vqh8 t:meta.view.license v:name="Public Domain"

property e:ezjn-vqh8 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ezjn-vqh8 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```