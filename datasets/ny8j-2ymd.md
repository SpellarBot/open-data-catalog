# State Drug Utilization Data 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2008) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ny8j-2ymd) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ny8j-2ymd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ny8j-2ymd/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ny8j-2ymd |
| Name | State Drug Utilization Data 2008 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-06-11T13:10:50Z |
| Publication Date | 2016-08-29T21:59:35Z |

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
series e:ny8j-2ymd d:2008-04-01T00:00:00.000Z t:product_fda_list_name=SERTRALINE t:ndc=68180035302 t:package_size=02 t:state_code=NC t:labeler_code=68180 t:product_code=0353 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=4284.4 m:total_amount_reimbursed=5445.4 m:number_of_prescriptions=516 m:units_reimbursed=20683 m:non_medicaid_amount_reimbursed=1161

series e:ny8j-2ymd d:2008-10-01T00:00:00.000Z t:product_fda_list_name=CARBAMAZEP t:ndc=00228214310 t:package_size=10 t:state_code=KY t:labeler_code=00228 t:product_code=2143 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=528.18 m:total_amount_reimbursed=528.18 m:number_of_prescriptions=43 m:units_reimbursed=4470 m:non_medicaid_amount_reimbursed=0

series e:ny8j-2ymd d:2008-07-01T00:00:00.000Z t:product_fda_list_name="BPM PSEUDO" t:ndc=64376054401 t:package_size=01 t:state_code=NC t:labeler_code=64376 t:product_code=0544 t:suppression_used=false t:record_id=FFSU m:medicaid_amount_reimbursed=1832.54 m:total_amount_reimbursed=2030.54 m:number_of_prescriptions=125 m:units_reimbursed=4457 m:non_medicaid_amount_reimbursed=198
```

## Meta Commands

```ls
metric m:units_reimbursed p:double l:"Units Reimbursed" d:"The total number of units (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions" d:"The number of prescriptions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed p:double l:"Total Amount Reimbursed" d:"The total amount reimbursed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed p:double l:"Medicaid Amount Reimbursed" d:"The amount reimbursed (by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed p:double l:"Non Medicaid Amount Reimbursed" d:"The amount reimbursed (by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

entity e:ny8j-2ymd l:"State Drug Utilization Data 2008" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ny8j-2ymd

property e:ny8j-2ymd t:meta.view v:id=ny8j-2ymd v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2008" v:attribution="Centers for Medicare and Medicaid"

property e:ny8j-2ymd t:meta.view.license v:name="Public Domain"

property e:ny8j-2ymd t:meta.view.owner v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ny8j-2ymd t:meta.view.tableauthor v:id=dqu3-3w2u v:profileImageUrlMedium=/api/users/dqu3-3w2u/profile_images/THUMB v:profileImageUrlLarge=/api/users/dqu3-3w2u/profile_images/LARGE v:screenName="Mark Silverberg" v:profileImageUrlSmall=/api/users/dqu3-3w2u/profile_images/TINY v:displayName="Mark Silverberg"

property e:ny8j-2ymd t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| record_id | state_code | labeler_code | product_code | package_size | period_covered | quarter | product_fda_list_name | units_reimbursed | suppression_used | number_of_prescriptions | total_amount_reimbursed | medicaid_amount_reimbursed | non_medicaid_amount_reimbursed | quarter_begin | quarter_begin_date  | latitude | longitude | ndc         | 
| ========= | ========== | ============ | ============ | ============ | ============== | ======= | ===================== | ================ | ================ | ======================= | ======================= | ========================== | ============================== | ============= | =================== | ======== | ========= | =========== | 
| FFSU      | NC         | 68180        | 0353         | 02           | 2008           | 2       | SERTRALINE            | 20683            | false            | 516                     | 5445.4                  | 4284.4                     | 1161                           | 4/1           | 2008-04-01T00:00:00 | 35.6411  | -79.8431  | 68180035302 | 
| FFSU      | KY         | 00228        | 2143         | 10           | 2008           | 4       | CARBAMAZEP            | 4470             | false            | 43                      | 528.18                  | 528.18                     | 0                              | 10/1          | 2008-10-01T00:00:00 | 37.669   | -84.6514  | 00228214310 | 
| FFSU      | ME         | 00025        | 1411         | 90           | 2008           | 3       | ARTHROTEC             |                  | true             |                         |                         |                            |                                | 7/1           | 2008-07-01T00:00:00 | 44.6074  | -69.3977  | 00025141190 | 
| FFSU      | NC         | 64376        | 0544         | 01           | 2008           | 3       | BPM PSEUDO            | 4457             | false            | 125                     | 2030.54                 | 1832.54                    | 198                            | 7/1           | 2008-07-01T00:00:00 | 35.6411  | -79.8431  | 64376054401 | 
| FFSU      | CT         | 00555        | 0833         | 05           | 2008           | 1       | WARFARIN S            | 3875             | false            | 184                     | 2641.38                 | 2614.22                    | 27.16                          | 1/1           | 2008-01-01T00:00:00 | 41.5834  | -72.7622  | 00555083305 | 
| FFSU      | SC         | 00555        | 0323         | 02           | 2008           | 2       | HYDROXYZIN            | 8161             | false            | 142                     | 897.49                  | 897.49                     | 0                              | 4/1           | 2008-04-01T00:00:00 | 33.8191  | -80.9066  | 00555032302 | 
| FFSU      | MN         | 00024        | 1535         | 08           | 2008           | 4       | PHISOHEX              |                  | true             |                         |                         |                            |                                | 10/1          | 2008-10-01T00:00:00 | 45.7326  | -93.9196  | 00024153508 | 
| FFSU      | OK         | 63323        | 0385         | 10           | 2008           | 3       | Cefotetan             |                  | true             |                         |                         |                            |                                | 7/1           | 2008-07-01T00:00:00 | 35.5376  | -96.9247  | 63323038510 | 
| FFSU      | CO         | 00378        | 4187         | 05           | 2008           | 4       | SERTRALINE            | 1238             | false            | 32                      | 346.54                  | 346.54                     | 0                              | 10/1          | 2008-10-01T00:00:00 | 39.0646  | -105.3272 | 00378418705 | 
| FFSU      | CT         | 10019        | 0210         | 02           | 2008           | 3       | LABETALOL             |                  | true             |                         |                         |                            |                                | 7/1           | 2008-07-01T00:00:00 | 41.5834  | -72.7622  | 10019021002 | 
```