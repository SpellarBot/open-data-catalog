# State Drug Utilization Data 1993

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-1993) |
| Metadata | [Link](https://data.medicaid.gov/api/views/iu8s-z84j) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/iu8s-z84j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/iu8s-z84j/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | iu8s-z84j |
| Name | State Drug Utilization Data 1993 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T14:27:17Z |
| Publication Date | 2016-08-29T21:36:03Z |

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
| Yes      | series tag     | ndc                            | ndc                            | text          | text          |
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
series e:iu8s-z84j d:1993-10-01T00:00:00.000Z t:product_fda_list_name=CEPHALEXIN t:ndc=00047093930 t:package_size=30 t:state_code=VA t:labeler_code=00047 t:product_code=0939 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=719.37 m:number_of_prescriptions=74 m:units_reimbursed=1983 m:non_medicaid_amount_reimbursed=0

series e:iu8s-z84j d:1993-01-01T00:00:00.000Z t:product_fda_list_name=SULFAMETHO t:ndc=58345080265 t:package_size=65 t:state_code=XX t:labeler_code=58345 t:product_code=0802 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=3840.7 m:number_of_prescriptions=559 m:units_reimbursed=10183 m:non_medicaid_amount_reimbursed=0

series e:iu8s-z84j d:1993-01-01T00:00:00.000Z t:product_fda_list_name=CREON t:ndc=00032120007 t:package_size=07 t:state_code=WA t:labeler_code=00032 t:product_code=1200 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=0 m:total_amount_reimbursed=2368.37 m:number_of_prescriptions=27 m:units_reimbursed=6970 m:non_medicaid_amount_reimbursed=0
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:integer l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:iu8s-z84j l:"State Drug Utilization Data 1993" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/iu8s-z84j

property e:iu8s-z84j t:meta.view v:id=iu8s-z84j v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 1993" v:attribution="Centers for Medicare and Medicaid"

property e:iu8s-z84j t:meta.view.license v:name="Public Domain"

property e:iu8s-z84j t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:iu8s-z84j t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:iu8s-z84j t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | suppression_used | units_reimbursed | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | NH         | 00641        | 2800         | 41           | 1993           | 4       | BACTERIOST            | true             |                  |                         |                         |                            |                                | 10/1          | 1993-10-01T00:00:00 | 43.4108  | -71.5653  | 00641280041 | 
| FFSU      | VA         | 00047        | 0939         | 30           | 1993           | 4       | CEPHALEXIN            | false            | 1983             | 74                      | 719.37                  | 0                          | 0                              | 10/1          | 1993-10-01T00:00:00 | 37.768   | -78.2057  | 00047093930 | 
| FFSU      | XX         | 58345        | 0802         | 65           | 1993           | 1       | SULFAMETHO            | false            | 10183            | 559                     | 3840.7                  | 0                          | 0                              | 1/1           | 1993-01-01T00:00:00 |          |           | 58345080265 | 
| FFSU      | WA         | 00032        | 1200         | 07           | 1993           | 1       | CREON                 | false            | 6970             | 27                      | 2368.37                 | 0                          | 0                              | 1/1           | 1993-01-01T00:00:00 | 47.3917  | -121.5708 | 00032120007 | 
| FFSU      | KS         | 00228        | 2530         | 30           | 1993           | 3       | NIFEDIPINE            | false            | 2966             | 33                      | 1683.99                 | 0                          | 0                              | 7/1           | 1993-07-01T00:00:00 | 38.5111  | -96.8005  | 00228253030 | 
| FFSU      | MI         | 00402        | 0749         | 15           | 1993           | 3       | GENTAMICIN            | true             |                  |                         |                         |                            |                                | 7/1           | 1993-07-01T00:00:00 | 43.3504  | -84.5603  | 00402074915 | 
| FFSU      | KY         | 00062        | 1780         | 22           | 1993           | 2       | ORTHO NOVU            | true             |                  |                         |                         |                            |                                | 4/1           | 1993-04-01T00:00:00 | 37.669   | -84.6514  | 00062178022 | 
| FFSU      | OH         | 00172        | 3626         | 48           | 1993           | 2       | DOXYCYCLIN            | false            | 808              | 41                      | 218.7                   | 0                          | 0                              | 4/1           | 1993-04-01T00:00:00 | 40.3736  | -82.7755  | 00172362648 | 
| FFSU      | CO         | 58887        | 0027         | 30           | 1993           | 1       | TEGRETOL (            | false            | 262796           | 2161                    | 72931.08                | 0                          | 0                              | 1/1           | 1993-01-01T00:00:00 | 39.0646  | -105.3272 | 58887002730 | 
| FFSU      | OH         | 00536        | 4077         | 01           | 1993           | 2       | NIACIN                | true             |                  |                         |                         |                            |                                | 4/1           | 1993-04-01T00:00:00 | 40.3736  | -82.7755  | 00536407701 | 
```