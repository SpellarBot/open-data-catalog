# Contracts: ESD: Willamette: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-willamette-fiscal-year-2013-a2d3e) |
| Metadata | [Link](https://data.oregon.gov/api/views/eeru-6mkv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/eeru-6mkv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/eeru-6mkv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | eeru-6mkv |
| Name | Contracts: ESD: Willamette: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, willamette, fiscal year 2013 |
| Created | 2013-10-30T20:14:54Z |
| Publication Date | 2013-10-30T20:30:01Z |

## Description

Contracts for Willamette ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | numeric metric | esd                                           | ESD #                                         | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD NAME                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments                     | Award Number w/Amendments                     | text      | text        |
| Yes      | series tag     | award_title                                   | Award Title                                   | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type                                    | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract                  | Type of Contract/Subcontract                  | text      | text        |
| Yes      | series tag     | contractor_information                        | Contractor Information                        | text      | text        |
| No       |                | contractor_address                            | Contractor Address                            | text      | text        |
| Yes      | series tag     | contractor_city                               | Contractor City                               | text      | text        |
| No       |                | st                                            | St                                            | text      | text        |
| Yes      | series tag     | zip_cd                                        | Zip Cd                                        | text      | number      |
| No       |                | original_start_amendment_date_expiration_date | Original Start/Amendment Date/Expiration Date | text      | text        |
| Yes      | series tag     | original_award_value                          | Original Award Value                          | text      | text        |
| Yes      | series tag     | amendment_value                               | Amendment Value                               | text      | text        |
| Yes      | series tag     | total_award_value_w_amendments                | Total Award Value w/Amendments                | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,st,original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:eeru-6mkv d:2013-01-01T00:00:00.000Z t:esd_name="Willamette Educational Service District" t:award_number_w_amendments=104345 t:type_of_contract_subcontract=Professional t:total_award_value_w_amendments="* 95,000.00" t:contractor_city=Charlotte t:zip_cd=28273 t:award_type="Price Agreement" t:award_title="Speech and Language Pathologist Services" t:contractor_information="Cumberland Therapy Services, LLC" t:original_award_value="* 95,000.00" m:esd=2117

series e:eeru-6mkv d:2013-01-01T00:00:00.000Z t:esd_name="Willamette Educational Service District" t:award_number_w_amendments=107043 t:type_of_contract_subcontract=Professional t:total_award_value_w_amendments="* 30,000.00" t:contractor_city=Salem t:zip_cd=97302 t:award_type="Price Agreement" t:award_title=Consulting t:contractor_information="Dixon, Bill and Pat" t:original_award_value="* 30,000.00" m:esd=2117

series e:eeru-6mkv d:2013-01-01T00:00:00.000Z t:esd_name="Willamette Educational Service District" t:amendment_value=$400,000.00 t:award_number_w_amendments=101015 t:type_of_contract_subcontract=Professional t:total_award_value_w_amendments="* 1,100,000.00" t:contractor_city="West Chester" t:zip_cd=19382 t:award_type="Price Agreement" t:award_title="Speech and Language Pathologist Services" t:contractor_information="Educational Based Services" t:original_award_value="* 700,000.00" m:esd=2117
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

entity e:eeru-6mkv l:"Contracts: ESD: Willamette: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/eeru-6mkv

property e:eeru-6mkv t:meta.view v:id=eeru-6mkv v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Willamette: Fiscal Year 2013"

property e:eeru-6mkv t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:eeru-6mkv t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                | award_number_w_amendments | award_title                              | award_type        | type_of_contract_subcontract | contractor_information           | contractor_address            | contractor_city | st | zip_cd | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ======================================= | ========================= | ======================================== | ================= | ============================ | ================================ | ============================= | =============== | == | ====== | ============================================= | ==================== | =============== | ============================== | 
| 2117 | Willamette Educational Service District | 104345                    | Speech and Language Pathologist Services | Price Agreement   | Professional                 | Cumberland Therapy Services, LLC | 9140 Arrowpoint Blvd          | Charlotte       | NC | 28273  | July 1, 2012 - June 30, 2013                  | * 95,000.00          |                 | * 95,000.00                    | 
| 2117 | Willamette Educational Service District | 107043                    | Consulting                               | Price Agreement   | Professional                 | Dixon, Bill and Pat              | 608 Salem Heights Ave S       | Salem           | OR | 97302  | July 1, 2012 - June 30, 2013                  | * 30,000.00          |                 | * 30,000.00                    | 
| 2117 | Willamette Educational Service District | 101015                    | Speech and Language Pathologist Services | Price Agreement   | Professional                 | Educational Based Services       | 200 Skiles Blvd, 2nd Floor    | West Chester    | PA | 19382  | August 08, 2012 - July 1, 2013                | * 700,000.00         | $400,000.00     | * 1,100,000.00                 | 
| 2117 | Willamette Educational Service District | 106575                    | Speech Therapy                           | Price Agreement   | Professional                 | Elevation Healthcare             | 1480 Harborsun Dr             | Charlston       | NC | 29412  | July 3, 2012 - July 1, 2013                   | * 100,000.00         |                 | * 100,000.00                   | 
| 2117 | Willamette Educational Service District | 105404                    | Occupational Therpy                      | Price Agreement   | Professional                 | Fertig, Elizabeth                | 7150 Corvallis Rd             | Independence    | OR | 97351  | October 10, 2012 - June 30, 2013              | * 7,000.00           |                 | * 7,000.00                     | 
| 2117 | Willamette Educational Service District | 107553                    | Janitorial Services                      | Price Agreement   | Professional                 | Freeman NW Inc. DBA Janiking     | 8338 NE Alderwood Rd, Ste 130 | Portland        | OR | 97220  | September 4, 2012 - December 31, 2012         | * 7,955.75           |                 | * 7,955.75                     | 
| 2117 | Willamette Educational Service District | 107569                    | Professional Development - Training      | One Time Contract | Professional                 | Guskey, Thomas R                 | 2108 Shelton Rd               | Lexington       | KY | 40515  | March 7, 2013 - September 30, 2013            | * 10,000.00          |                 | * 10,000.00                    | 
| 2117 | Willamette Educational Service District | 104582                    | Professional Services                    | One Time Contract | Material                     | FastSigns 285                    | 2290 Commercial St, SE #101   | Salem           | OR | 97302  | September 28, 2012 - September 18, 2013       | * 5,000.00           |                 | * 5,000.00                     | 
| 2117 | Willamette Educational Service District | 104683                    | Engineering Services                     | Price Agreement   | Professional                 | Schoolboy Engineering            | 7421 Liberty Rd S             | Salem           | OR | 97306  | February 19, 2013 - June 30, 2013             | * 25,000.00          |                 | * 25,000.00                    | 
| 2117 | Willamette Educational Service District | 107446                    | Art Therapy                              | Price Agreement   | Professional                 | Jorgensen, Julie D               | 4524 SW Illinois St           | Portland        | OR | 97221  | August 29, 2012 - June 30, 2013               | * 30,000.00          |                 | * 30,000.00                    | 
```