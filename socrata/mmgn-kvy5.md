# State Drug Utilization Data 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2010) |
| Metadata | [Link](https://data.medicaid.gov/api/views/mmgn-kvy5) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/mmgn-kvy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/mmgn-kvy5/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | mmgn-kvy5 |
| Name | State Drug Utilization Data 2010 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T12:35:21Z |
| Publication Date | 2016-08-29T18:38:17Z |

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
| Yes      | numeric metric | units_reimbursed               | Units Reimbursed               | number        | number        |
| Yes      | series tag     | suppression_used               | Suppression Used               | checkbox      | checkbox      |
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
series e:mmgn-kvy5 d:2010-04-01T00:00:00.000Z t:product_fda_list_name="ASMANEX TW" t:ndc=00085134101 t:package_size=01 t:state_code=NC t:labeler_code=00085 t:product_code=1341 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=21518.63 m:total_amount_reimbursed=22263.73 m:number_of_prescriptions=111 m:units_reimbursed=26.64 m:non_medicaid_amount_reimbursed=745.1

series e:mmgn-kvy5 d:2010-01-01T00:00:00.000Z t:product_fda_list_name=FAMCICLOVI t:ndc=00093811956 t:package_size=56 t:state_code=OK t:labeler_code=00093 t:product_code=8119 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=17811.52 m:total_amount_reimbursed=17811.52 m:number_of_prescriptions=83 m:units_reimbursed=2440 m:non_medicaid_amount_reimbursed=0

series e:mmgn-kvy5 d:2010-10-01T00:00:00.000Z t:product_fda_list_name=HYDROCODON t:ndc=00603388728 t:package_size=28 t:state_code=FL t:labeler_code=00603 t:product_code=3887 t:suppression_used=false t:record_id=MCOU m:medicaid_amount_reimbursed=27654.09 m:total_amount_reimbursed=27715.14 m:number_of_prescriptions=1144 m:units_reimbursed=105566 m:non_medicaid_amount_reimbursed=61.05
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:mmgn-kvy5 l:"State Drug Utilization Data 2010" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/mmgn-kvy5

property e:mmgn-kvy5 t:meta.view v:id=mmgn-kvy5 v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2010" v:attribution="Centers for Medicare and Medicaid"

property e:mmgn-kvy5 t:meta.view.license v:name="Public Domain"

property e:mmgn-kvy5 t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:mmgn-kvy5 t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:mmgn-kvy5 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | NC         | 00085        | 1341         | 01           | 2010           | 2       | ASMANEX TW            | 26.64            | false            | 111                     | 22263.73                | 21518.63                   | 745.1                          | 4/1           | 2010-04-01T00:00:00 | 35.6411  | -79.8431  | 00085134101 | 
| FFSU      | IN         | 00169        | 5174         | 01           | 2010           | 3       | ACTIVELLA             |                  | true             |                         |                         |                            |                                | 7/1           | 2010-07-01T00:00:00 | 39.8647  | -86.2604  | 00169517401 | 
| FFSU      | OK         | 00093        | 8119         | 56           | 2010           | 1       | FAMCICLOVI            | 2440             | false            | 83                      | 17811.52                | 17811.52                   | 0                              | 1/1           | 2010-01-01T00:00:00 | 35.5376  | -96.9247  | 00093811956 | 
| FFSU      | WV         | 00054        | 4582         | 25           | 2010           | 4       | MORPHINE S            |                  | true             |                         |                         |                            |                                | 10/1          | 2010-10-01T00:00:00 | 38.468   | -80.9696  | 00054458225 | 
| MCOU      | FL         | 00603        | 3887         | 28           | 2010           | 4       | HYDROCODON            | 105566           | false            | 1144                    | 27715.14                | 27654.09                   | 61.05                          | 10/1          | 2010-10-01T00:00:00 | 27.8333  | -81.717   | 00603388728 | 
| FFSU      | ME         | 60258        | 0006         | 01           | 2010           | 3       | PHOS-NAK P            |                  | true             |                         |                         |                            |                                | 7/1           | 2010-07-01T00:00:00 | 44.6074  | -69.3977  | 60258000601 | 
| FFSU      | DE         | 00093        | 0150         | 01           | 2010           | 2       | ACETAMINOP            | 570              | false            | 16                      | 101.16                  | 95.16                      | 6                              | 4/1           | 2010-04-01T00:00:00 | 39.3498  | -75.5148  | 00093015001 | 
| FFSU      | MT         | 67767        | 0122         | 18           | 2010           | 3       | FENTANYL 7            |                  | true             |                         |                         |                            |                                | 7/1           | 2010-07-01T00:00:00 | 46.9048  | -110.3261 | 67767012218 | 
| FFSU      | MA         | 00121        | 0722         | 08           | 2010           | 1       | SENNA SYRU            |                  | true             |                         |                         |                            |                                | 1/1           | 2010-01-01T00:00:00 | 42.2373  | -71.5314  | 00121072208 | 
| FFSU      | MI         | 59762        | 4801         | 01           | 2010           | 4       | CITALOPRAM            | 4102             | false            | 128                     | 417.75                  | 417.75                     | 0                              | 10/1          | 2010-10-01T00:00:00 | 43.3504  | -84.5603  | 59762480101 | 
```