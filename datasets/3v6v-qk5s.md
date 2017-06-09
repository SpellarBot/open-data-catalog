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
series e:3v6v-qk5s d:2016-10-01T00:00:00.000Z t:product_fda_list_name=ACYCLOVIR t:ndc=65162083596 t:package_size=96 t:state_code=FL t:labeler_code=65162 t:product_code=0835 t:utilization_type=MCOU t:suppression_used=false m:medicaid_amount_reimbursed=180412.58 m:total_amount_reimbursed=180412.58 m:number_of_prescriptions=435 m:units_reimbursed=13200 m:non_medicaid_amount_reimbursed=0

series e:3v6v-qk5s d:2016-04-01T00:00:00.000Z t:product_fda_list_name=Gemcitabin t:ndc=16729011711 t:package_size=11 t:state_code=RI t:labeler_code=16729 t:product_code=0117 t:utilization_type=MCOU t:suppression_used=false m:medicaid_amount_reimbursed=12717.64 m:total_amount_reimbursed=12717.64 m:number_of_prescriptions=32 m:units_reimbursed=64 m:non_medicaid_amount_reimbursed=0

series e:3v6v-qk5s d:2016-10-01T00:00:00.000Z t:product_fda_list_name=BUTALBITAL t:ndc=00143178701 t:package_size=01 t:state_code=WA t:labeler_code=00143 t:product_code=1787 t:utilization_type=MCOU t:suppression_used=false m:medicaid_amount_reimbursed=4202.08 m:total_amount_reimbursed=4202.08 m:number_of_prescriptions=153 m:units_reimbursed=5594 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" t:dataTypeName=number

entity e:3v6v-qk5s l:"State Drug Utilization Data 2016" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/3v6v-qk5s

property e:3v6v-qk5s t:meta.view d:2017-06-09T13:53:06.532Z v:id=3v6v-qk5s v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2016" v:attribution="Centers for Medicare and Medicaid"

property e:3v6v-qk5s t:meta.view.license d:2017-06-09T13:53:06.532Z v:name="Public Domain"

property e:3v6v-qk5s t:meta.view.owner d:2017-06-09T13:53:06.532Z v:id=di3h-9ddn v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:screenName=Medicaid.gov v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:displayName=Medicaid.gov

property e:3v6v-qk5s t:meta.view.tableauthor d:2017-06-09T13:53:06.532Z v:id=di3h-9ddn v:profileImageUrlMedium=/api/users/di3h-9ddn/profile_images/THUMB v:profileImageUrlLarge=/api/users/di3h-9ddn/profile_images/LARGE v:screenName=Medicaid.gov v:profileImageUrlSmall=/api/users/di3h-9ddn/profile_images/TINY v:roleName=administrator v:displayName=Medicaid.gov

property e:3v6v-qk5s t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:53:06.532Z v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| utilization_type | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ================ | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| MCOU             | FL         | 65162        | 0835         | 96           | 2016           | 4       | ACYCLOVIR             | false            | 13200            | 435                     | 180412.58               | 180412.58                  | 0                              | 10/1          | 2016-10-01T00:00:00 | 27.8333  | -81.717   | 65162083596 | 
| MCOU             | RI         | 16729        | 0117         | 11           | 2016           | 2       | Gemcitabin            | false            | 64               | 32                      | 12717.64                | 12717.64                   | 0                              | 4/1           | 2016-04-01T00:00:00 | 41.6772  | -71.5101  | 16729011711 | 
| MCOU             | WA         | 00143        | 1787         | 01           | 2016           | 4       | BUTALBITAL            | false            | 5594             | 153                     | 4202.08                 | 4202.08                    | 0                              | 10/1          | 2016-10-01T00:00:00 | 47.3917  | -121.5708 | 00143178701 | 
| FFSU             | FL         | 68382        | 0650         | 05           | 2016           | 4       | ISOSORBIDE            | false            | 1245             | 34                      | 345.88                  | 345.88                     | 0                              | 10/1          | 2016-10-01T00:00:00 | 27.8333  | -81.717   | 68382065005 | 
| FFSU             | KY         | 00536        | 4544         | 10           | 2016           | 3       | SODIUM BIC            | false            | 1580             | 23                      | 122.86                  | 122.86                     | 0                              | 7/1           | 2016-07-01T00:00:00 | 37.669   | -84.6514  | 00536454410 | 
| MCOU             | IA         | 00186        | 4050         | 01           | 2016           | 4       | Nexium For            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 42.0046  | -93.214   | 00186405001 | 
| FFSU             | AR         | 43598        | 0208         | 52           | 2016           | 4       | AMOXICILLI            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 34.9513  | -92.3809  | 43598020852 | 
| MCOU             | NJ         | 00409        | 4332         | 01           | 2016           | 4       | VANCOMYCIN            | false            | 465.69           | 70                      | 3333.27                 | 2165.36                    | 1167.91                        | 10/1          | 2016-10-01T00:00:00 | 40.314   | -74.5089  | 00409433201 | 
| MCOU             | SC         | 16729        | 0019         | 01           | 2016           | 3       | MYCOPHENOL            | false            | 4050             | 42                      | 4634.98                 | 4634.98                    | 0                              | 7/1           | 2016-07-01T00:00:00 | 33.8191  | -80.9066  | 16729001901 | 
| FFSU             | UT         | 68134        | 0201         | 16           | 2016           | 4       | Naproxen O            | true             |                  |                         |                         |                            |                                | 10/1          | 2016-10-01T00:00:00 | 40.1135  | -111.8535 | 68134020116 | 
```