# Payment and value of care - Hospital

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/payment-and-value-of-care-hospital) |
| Metadata | [Link](https://data.medicare.gov/api/views/c7us-v4mf) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/c7us-v4mf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/c7us-v4mf/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | c7us-v4mf |
| Name | Payment and value of care - Hospital |
| Category | Hospital Compare |
| Tags | hospital compare, medicare payment |
| Created | 2014-11-21T02:02:37Z |
| Publication Date | 2016-12-19T17:10:03Z |

## Description

Payment measures and value of care displays ? provider data. This data set includes provider data for the payment measures and value of care displays associated with a 30-day episode of care for heart attack, heart failure, and pneumonia patients.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | provider_id                | Provider ID                | text          | text          |
| Yes      | series tag     | hospital_name              | Hospital name              | text          | text          |
| No       |                | address                    | Address                    | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | state                      | State                      | text          | text          |
| Yes      | series tag     | zip_code                   | ZIP Code                   | text          | text          |
| Yes      | series tag     | county_name                | County name                | text          | text          |
| Yes      | series tag     | phone_number               | Phone number               | phone         | phone         |
| Yes      | series tag     | measure_name               | Payment measure name       | text          | text          |
| Yes      | series tag     | measure_id                 | Payment measure ID         | text          | text          |
| Yes      | series tag     | category                   | Payment category           | text          | text          |
| Yes      | numeric metric | denominator                | Denominator                | number        | text          |
| Yes      | numeric metric | payment                    | Payment                    | money         | text          |
| Yes      | numeric metric | lower_estimate             | Lower estimate             | money         | text          |
| Yes      | numeric metric | higher_estimate            | Higher estimate            | money         | text          |
| No       |                | payment_footnote           | Payment footnote           | text          | text          |
| Yes      | series tag     | value_of_care_display_name | Value of care display name | text          | text          |
| Yes      | series tag     | value_of_care_display_id   | Value of care display ID   | text          | text          |
| Yes      | series tag     | value_of_care_category     | Value of care category     | text          | text          |
| No       |                | value_of_care_footnote     | Value of care footnote     | text          | text          |
| Yes      | time           | measure_start_date         | Measure start date         | calendar_date | calendar_date |
| No       |                | measure_end_date           | Measure End Date           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,payment_footnote,value_of_care_footnote,measure_end_date
```

## Data Commands

```ls
series e:c7us-v4mf d:2012-07-01T00:00:00.000Z t:hospital_name="MARSHALL MEDICAL CENTER SOUTH" t:phone_number=2565938310 t:zip_code=35957 t:provider_id=010005 t:value_of_care_category="Average mortality and average payment" t:state=AL t:value_of_care_display_id=MORT_PAYM_30_AMI t:value_of_care_display_name="Value of Care Heart Attack measure" t:city=BOAZ t:category="No Different than the National Average Payment" t:measure_id=PAYM_30_AMI t:county_name=MARSHALL t:measure_name="Payment for heart attack patients" m:payment=23171 m:higher_estimate=26226 m:denominator=53 m:lower_estimate=20404

series e:c7us-v4mf d:2012-07-01T00:00:00.000Z t:hospital_name="MARSHALL MEDICAL CENTER SOUTH" t:phone_number=2565938310 t:zip_code=35957 t:provider_id=010005 t:value_of_care_category="Worse mortality and average payment" t:state=AL t:value_of_care_display_id=MORT_PAYM_30_HF t:value_of_care_display_name="Value of Care Heart Failure measure" t:city=BOAZ t:category="No Different than the National Average Payment" t:measure_id=PAYM_30_HF t:county_name=MARSHALL t:measure_name="Payment for heart failure patients" m:payment=16376 m:higher_estimate=17547 m:denominator=347 m:lower_estimate=15237

series e:c7us-v4mf d:2012-07-01T00:00:00.000Z t:hospital_name="MARSHALL MEDICAL CENTER SOUTH" t:phone_number=2565938310 t:zip_code=35957 t:provider_id=010005 t:value_of_care_category="Worse mortality and average payment" t:state=AL t:value_of_care_display_id=MORT_PAYM_30_PN t:value_of_care_display_name="Value of Care Pneumonia measure" t:city=BOAZ t:category="No Different than the National Average Payment" t:measure_id=PAYM_30_PN t:county_name=MARSHALL t:measure_name="Payment for pneumonia patients" m:payment=14384 m:higher_estimate=15118 m:denominator=646 m:lower_estimate=13642
```

## Meta Commands

```ls
entity e:c7us-v4mf l:"Payment and value of care - Hospital" t:url=https://data.medicare.gov/api/views/c7us-v4mf

property e:c7us-v4mf t:meta.view v:id=c7us-v4mf v:category="Hospital Compare" v:averageRating=0 v:name="Payment and value of care - Hospital"

property e:c7us-v4mf t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:c7us-v4mf t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:c7us-v4mf t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                  | address                    | city       | state | zip_code | county_name | phone_number       | measure_name                       | measure_id  | category                                       | denominator   | payment       | lower_estimate | higher_estimate | payment_footnote                                       | value_of_care_display_name          | value_of_care_display_id | value_of_care_category                | value_of_care_footnote                                       | measure_start_date  | measure_end_date    | 
| =========== | ============================== | ========================== | ========== | ===== | ======== | =========== | ================== | ================================== | =========== | ============================================== | ============= | ============= | ============== | =============== | ====================================================== | =================================== | ======================== | ===================================== | ============================================================ | =================== | =================== | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH  | 2505 U S HIGHWAY 431 NORTH | BOAZ       | AL    | 35957    | MARSHALL    | [2565938310, null] | Payment for heart attack patients  | PAYM_30_AMI | No Different than the National Average Payment | 53            | $23,171       | $20,404        | $26,226         |                                                        | Value of Care Heart Attack measure  | MORT_PAYM_30_AMI         | Average mortality and average payment |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH  | 2505 U S HIGHWAY 431 NORTH | BOAZ       | AL    | 35957    | MARSHALL    | [2565938310, null] | Payment for heart failure patients | PAYM_30_HF  | No Different than the National Average Payment | 347           | $16,376       | $15,237        | $17,547         |                                                        | Value of Care Heart Failure measure | MORT_PAYM_30_HF          | Worse mortality and average payment   |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTER SOUTH  | 2505 U S HIGHWAY 431 NORTH | BOAZ       | AL    | 35957    | MARSHALL    | [2565938310, null] | Payment for pneumonia patients     | PAYM_30_PN  | No Different than the National Average Payment | 646           | $14,384       | $13,642        | $15,118         |                                                        | Value of Care Pneumonia measure     | MORT_PAYM_30_PN          | Worse mortality and average payment   |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010012      | DEKALB REGIONAL MEDICAL CENTER | 200 MED CENTER DRIVE       | FORT PAYNE | AL    | 35968    | DE KALB     | [2568453150, null] | Payment for heart attack patients  | PAYM_30_AMI | No Different than the National Average Payment | 143           | $22,997       | $20,910        | $25,353         |                                                        | Value of Care Heart Attack measure  | MORT_PAYM_30_AMI         | Average mortality and average payment |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010012      | DEKALB REGIONAL MEDICAL CENTER | 200 MED CENTER DRIVE       | FORT PAYNE | AL    | 35968    | DE KALB     | [2568453150, null] | Payment for heart failure patients | PAYM_30_HF  | No Different than the National Average Payment | 145           | $16,722       | $15,113        | $18,491         |                                                        | Value of Care Heart Failure measure | MORT_PAYM_30_HF          | Average mortality and average payment |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010012      | DEKALB REGIONAL MEDICAL CENTER | 200 MED CENTER DRIVE       | FORT PAYNE | AL    | 35968    | DE KALB     | [2568453150, null] | Payment for pneumonia patients     | PAYM_30_PN  | No Different than the National Average Payment | 193           | $15,449       | $14,119        | $16,795         |                                                        | Value of Care Pneumonia measure     | MORT_PAYM_30_PN          | Worse mortality and average payment   |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010032      | WEDOWEE HOSPITAL               | 209 NORTH MAIN STREET      | WEDOWEE    | AL    | 36278    | RANDOLPH    | [2563572111, null] | Payment for heart attack patients  | PAYM_30_AMI | Number of Cases Too Small                      | Not Available | Not Available | Not Available  | Not Available   | 1 - The number of cases/patients is too few to report. | Value of Care Heart Attack measure  | MORT_PAYM_30_AMI         | Not Available                         | 13 - Results cannot be calculated for this reporting period. | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010032      | WEDOWEE HOSPITAL               | 209 NORTH MAIN STREET      | WEDOWEE    | AL    | 36278    | RANDOLPH    | [2563572111, null] | Payment for heart failure patients | PAYM_30_HF  | No Different than the National Average Payment | 45            | $16,649       | $14,390        | $19,228         |                                                        | Value of Care Heart Failure measure | MORT_PAYM_30_HF          | Average mortality and average payment |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010032      | WEDOWEE HOSPITAL               | 209 NORTH MAIN STREET      | WEDOWEE    | AL    | 36278    | RANDOLPH    | [2563572111, null] | Payment for pneumonia patients     | PAYM_30_PN  | No Different than the National Average Payment | 70            | $13,168       | $11,474        | $14,876         |                                                        | Value of Care Pneumonia measure     | MORT_PAYM_30_PN          | Average mortality and average payment |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
| 010131      | CRESTWOOD MEDICAL CENTER       | ONE HOSPITAL DR SE         | HUNTSVILLE | AL    | 35801    | MADISON     | [2568823100, null] | Payment for heart attack patients  | PAYM_30_AMI | Less than the National Average Payment         | 186           | $20,007       | $18,418        | $21,732         |                                                        | Value of Care Heart Attack measure  | MORT_PAYM_30_AMI         | Average mortality and lower payment   |                                                              | 2012-07-01T00:00:00 | 2015-06-30T00:00:00 | 
```