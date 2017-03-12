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
| Rows Updated | 2017-02-03T08:51:25Z |

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
| Yes      | series tag     | quarter_begin                  | Quarter begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | _latitude                      | number        | number        |
| No       |                | longitude                      | _longitude                     | number        | number        |
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
series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=1/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:utilization_type=FFSU t:suppression_used=true m:package_size=1 m:ndc=2445301 m:period_covered=2016 m:quarter=1

series e:3v6v-qk5s d:2016-04-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=4/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:utilization_type=FFSU t:suppression_used=true m:package_size=1 m:ndc=2445301 m:period_covered=2016 m:quarter=2

series e:3v6v-qk5s d:2016-01-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=1/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:utilization_type=FFSU t:suppression_used=true m:package_size=85 m:ndc=2445385 m:period_covered=2016 m:quarter=1
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size" t:dataTypeName=number

metric m:period_covered p:integer l:Year t:dataTypeName=number

metric m:quarter p:integer l:Quarter t:dataTypeName=number

metric m:units_reimbursed l:"Units Reimbursed" t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" t:dataTypeName=number

metric m:total_amount_reimbursed l:"Total Amount Reimbursed" t:dataTypeName=number

metric m:medicaid_amount_reimbursed l:"Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed l:"Non Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:3v6v-qk5s l:"State Drug Utilization Data 2016" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/3v6v-qk5s

property e:3v6v-qk5s t:meta.view v:id=3v6v-qk5s v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2016" v:attribution="Centers for Medicare and Medicaid"

property e:3v6v-qk5s t:meta.view.license v:name="Public Domain"

property e:3v6v-qk5s t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:3v6v-qk5s t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```