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
series e:3v6v-qk5s d:2016-10-01T00:00:00.000Z t:package_size=96 t:product_fda_list_name=ACYCLOVIR t:labeler_code=65162 t:suppression_used=false t:product_code=0835 t:ndc=65162083596 t:state_code=FL t:utilization_type=MCOU m:total_amount_reimbursed=180412.58 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=13200 m:medicaid_amount_reimbursed=180412.58 m:number_of_prescriptions=435

series e:3v6v-qk5s d:2016-04-01T00:00:00.000Z t:package_size=11 t:product_fda_list_name=Gemcitabin t:labeler_code=16729 t:suppression_used=false t:product_code=0117 t:ndc=16729011711 t:state_code=RI t:utilization_type=MCOU m:total_amount_reimbursed=12717.64 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=64 m:medicaid_amount_reimbursed=12717.64 m:number_of_prescriptions=32

series e:3v6v-qk5s d:2016-10-01T00:00:00.000Z t:package_size=05 t:product_fda_list_name=ISOSORBIDE t:labeler_code=68382 t:suppression_used=false t:product_code=0650 t:ndc=68382065005 t:state_code=FL t:utilization_type=FFSU m:total_amount_reimbursed=345.88 m:non_medicaid_amount_reimbursed=0 m:units_reimbursed=1245 m:medicaid_amount_reimbursed=345.88 m:number_of_prescriptions=34
```

## Meta Commands

```ls
metric m:units_reimbursed p:integer l:"Units Reimbursed" t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" t:dataTypeName=number

entity e:3v6v-qk5s l:"State Drug Utilization Data 2016" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/3v6v-qk5s

property e:3v6v-qk5s t:meta.view d:2017-09-25T07:24:26.873Z v:averageRating=0 v:name="State Drug Utilization Data 2016" v:attribution="Centers for Medicare and Medicaid" v:attributionLink=https://medicaid.gov v:id=3v6v-qk5s v:category="State Drug Utilization"

property e:3v6v-qk5s t:meta.view.license d:2017-09-25T07:24:26.873Z v:name="Public Domain"

property e:3v6v-qk5s t:meta.view.owner d:2017-09-25T07:24:26.873Z v:displayName=Medicaid.gov v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:id=di3h-9ddn v:screenName=Medicaid.gov v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB

property e:3v6v-qk5s t:meta.view.tableauthor d:2017-09-25T07:24:26.873Z v:displayName=Medicaid.gov v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:id=di3h-9ddn v:screenName=Medicaid.gov v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB

property e:3v6v-qk5s t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:24:26.873Z v:Program_Code=009:076 v:Bureau_Code=009:00
```

## Top Records

```ls
| utilization_type | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ================ | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| MCOU             | FL         | 65162        | 0835         | 96           | 2016           | 4       | ACYCLOVIR             | false            | 13200            | 435                     | 180412.58               | 180412.58                  | 0                              | 10/1          | 2016-10-01T00:00:00 | 27.8333  | -81.717   | 65162083596 | 
| MCOU             | RI         | 16729        | 0117         | 11           | 2016           | 2       | Gemcitabin            | false            | 64               | 32                      | 12717.64                | 12717.64                   | 0                              | 4/1           | 2016-04-01T00:00:00 | 41.6772  | -71.5101  | 16729011711 | 
| FFSU             | FL         | 68382        | 0650         | 05           | 2016           | 4       | ISOSORBIDE            | false            | 1245             | 34                      | 345.88                  | 345.88                     | 0                              | 10/1          | 2016-10-01T00:00:00 | 27.8333  | -81.717   | 68382065005 | 
| FFSU             | KY         | 00536        | 4544         | 10           | 2016           | 3       | SODIUM BIC            | false            | 1580             | 23                      | 122.86                  | 122.86                     | 0                              | 7/1           | 2016-07-01T00:00:00 | 37.669   | -84.6514  | 00536454410 | 
| FFSU             | AR         | 43598        | 0208         | 52           | 2016           | 4       | AMOXICILLI            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 34.9513  | -92.3809  | 43598020852 | 
| MCOU             | SC         | 16729        | 0019         | 01           | 2016           | 3       | MYCOPHENOL            | false            | 4050             | 42                      | 4634.98                 | 4634.98                    | 0                              | 7/1           | 2016-07-01T00:00:00 | 33.8191  | -80.9066  | 16729001901 | 
| FFSU             | UT         | 68134        | 0201         | 16           | 2016           | 4       | Naproxen O            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 40.1135  | -111.8535 | 68134020116 | 
| FFSU             | ND         | 24208        | 0463         | 25           | 2016           | 4       | LATANOPROS            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 47.5362  | -99.793   | 24208046325 | 
| MCOU             | VA         | 57237        | 0002         | 05           | 2016           | 4       | Hydrochlor            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 37.768   | -78.2057  | 57237000205 | 
| MCOU             | XX         | 00093        | 7810         | 56           | 2016           | 3       | AMLODIPINE            | false            | 2760             | 92                      | 10581.58                | 10563.58                   | 18                             | 7/1           | 2016-07-01T00:00:00 |          |           | 00093781056 | 
```