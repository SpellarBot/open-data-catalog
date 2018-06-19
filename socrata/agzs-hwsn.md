# State Drug Utilization Data 1992

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1992) |
| Metadata | [Link](https://data.medicaid.gov/api/views/agzs-hwsn) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/agzs-hwsn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/agzs-hwsn/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | agzs-hwsn |
| Name | State Drug Utilization Data 1992 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:25:57Z |
| Publication Date | 2016-08-29T17:34:41Z |

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
series e:agzs-hwsn d:1992-01-01T00:00:00.000Z t:product_fda_list_name=FLUOCINONI t:ndc=00093026292 t:package_size=92 t:state_code=DC t:labeler_code=00093 t:product_code=0262 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=577.43 m:number_of_prescriptions=34 m:units_reimbursed=2130 m:non_medicaid_amount_reimbursed=0

series e:agzs-hwsn d:1992-10-01T00:00:00.000Z t:product_fda_list_name=SELDANE-D t:ndc=00068072261 t:package_size=61 t:state_code=MO t:labeler_code=00068 t:product_code=0722 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=85272.23 m:number_of_prescriptions=2645 m:units_reimbursed=87489 m:non_medicaid_amount_reimbursed=0

series e:agzs-hwsn d:1992-01-01T00:00:00.000Z t:product_fda_list_name=ISOSORBIDE t:ndc=00555018605 t:package_size=05 t:state_code=WI t:labeler_code=00555 t:product_code=0186 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=1700.26 m:number_of_prescriptions=281 m:units_reimbursed=31044 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:integer l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:agzs-hwsn l:"State Drug Utilization Data 1992" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/agzs-hwsn

property e:agzs-hwsn t:meta.view v:id=agzs-hwsn v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1992" v:attribution="Centers for Medicare and Medicaid"

property e:agzs-hwsn t:meta.view.license v:name="Public Domain"

property e:agzs-hwsn t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:agzs-hwsn t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:agzs-hwsn t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | NY         | 00349        | 8398         | 01           | 1992           | 1       | NO DESCRIP            | true             |                  |                         |                         |                            |                                | 1/1           | 1992-01-01T00:00:00 | 42.1497  | -74.9384  | 00349839801 | 
| FFSU      | DC         | 00093        | 0262         | 92           | 1992           | 1       | FLUOCINONI            | false            | 2130             | 34                      | 577.43                  | 0                          | 0                              | 1/1           | 1992-01-01T00:00:00 | 38.8964  | -77.0262  | 00093026292 | 
| FFSU      | MO         | 00068        | 0722         | 61           | 1992           | 4       | SELDANE-D             | false            | 87489            | 2645                    | 85272.23                | 0                          | 0                              | 10/1          | 1992-10-01T00:00:00 | 38.4623  | -92.302   | 00068072261 | 
| FFSU      | WI         | 00555        | 0186         | 05           | 1992           | 1       | ISOSORBIDE            | false            | 31044            | 281                     | 1700.26                 | 0                          | 0                              | 1/1           | 1992-01-01T00:00:00 | 44.2563  | -89.6385  | 00555018605 | 
| FFSU      | NY         | 00839        | 6659         | 43           | 1992           | 4       | TRIPLE ANT            | false            | 241              | 59                      | 118.81                  | 0                          | 0                              | 10/1          | 1992-10-01T00:00:00 | 42.1497  | -74.9384  | 00839665943 | 
| FFSU      | MN         | 00024        | 1075         | 01           | 1992           | 2       | KAYEXALATE            | false            | 16706            | 52                      | 4066.33                 | 0                          | 0                              | 4/1           | 1992-04-01T00:00:00 | 45.7326  | -93.9196  | 00024107501 | 
| FFSU      | NY         | 00781        | 1865         | 05           | 1992           | 4       | CLORAZEPAT            | true             |                  |                         |                         |                            |                                | 10/1          | 1992-10-01T00:00:00 | 42.1497  | -74.9384  | 00781186505 | 
| FFSU      | MT         | 00074        | 6320         | 11           | 1992           | 3       | ERY-TAB 33            | true             |                  |                         |                         |                            |                                | 7/1           | 1992-07-01T00:00:00 | 46.9048  | -110.3261 | 00074632011 | 
| FFSU      | FL         | 52446        | 0250         | 21           | 1992           | 1       | IMIPRAMINE            | false            | 1505             | 23                      | 117.54                  | 0                          | 0                              | 1/1           | 1992-01-01T00:00:00 | 27.8333  | -81.717   | 52446025021 | 
| FFSU      | PA         | 00555        | 0487         | 02           | 1992           | 4       | TEMAZEPAM             | false            | 550              | 15                      | 70.25                   | 0                          | 0                              | 10/1          | 1992-10-01T00:00:00 | 40.5773  | -77.264   | 00555048702 | 
```