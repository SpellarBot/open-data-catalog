# Contracts: ESD: Columbia Gorge: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-columbia-gorge-fiscal-year-2013-c3848) |
| Metadata | [Link](https://data.oregon.gov/api/views/i3bn-rwu4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i3bn-rwu4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i3bn-rwu4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i3bn-rwu4 |
| Name | Contracts: ESD: Columbia Gorge: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, columbia gorge, fiscal year 2013 |
| Created | 2013-10-22T15:30:42Z |
| Publication Date | 2013-10-23T23:26:49Z |

## Description

Columbia Gorge ESD Contracts for Fiscal year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | numeric metric | esd                                           | ESD #                                         | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD NAME                                      | text      | text        |
| Yes      | numeric metric | award_number_w_amendments                     | Award Number w/Amendments                     | number    | number      |
| Yes      | series tag     | award_title                                   | Award Title                                   | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type                                    | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract                  | Type of Contract/Subcontract                  | text      | text        |
| Yes      | series tag     | contractor_information                        | Contractor Information                        | text      | text        |
| No       |                | contractor_address                            | Contractor Address                            | text      | text        |
| Yes      | series tag     | contractor_city                               | Contractor City                               | text      | text        |
| Yes      | series tag     | contractor_state                              | Contractor State                              | text      | text        |
| Yes      | series tag     | contractor_zip                                | Contractor Zip                                | text      | number      |
| No       |                | original_start_amendment_date_expiration_date | Original Start/Amendment Date/Expiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                          | Original Award Value                          | money     | money       |
| Yes      | numeric metric | amendment_value                               | Amendment Value                               | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                | Total Award Value w/Amendments                | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:i3bn-rwu4 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:contractor_state=CA t:type_of_contract_subcontract=Material t:contractor_city="San Jose" t:award_type="Price Agreement" t:award_title="Technology Equipment" t:contractor_zip=95131 t:contractor_information=AdvanTel m:award_number_w_amendments=18 m:total_award_value_w_amendments=32456.92 m:esd=2223 m:original_award_value=32456.92

series e:i3bn-rwu4 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:contractor_state=OR t:type_of_contract_subcontract=Professional t:contractor_city=Tigard t:award_type="Price Agreement" t:award_title=Consulting t:contractor_zip=97224 t:contractor_information="Carruth Comliance Consulting, Inc." m:award_number_w_amendments=2 m:total_award_value_w_amendments=2640 m:esd=2223 m:original_award_value=2640

series e:i3bn-rwu4 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:contractor_state=OR t:type_of_contract_subcontract=Professional t:contractor_city="The Dalles" t:award_type="Price Agreement" t:award_title="Facilities Lease" t:contractor_zip=97058 t:contractor_information="Columbia Gorge Community College" m:award_number_w_amendments=1 m:total_award_value_w_amendments=55584 m:esd=2223 m:original_award_value=55584
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:award_number_w_amendments p:integer l:"Award Number w/Amendments" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:i3bn-rwu4 l:"Contracts: ESD: Columbia Gorge: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/i3bn-rwu4

property e:i3bn-rwu4 t:meta.view v:id=i3bn-rwu4 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Columbia Gorge: Fiscal Year 2013"

property e:i3bn-rwu4 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:i3bn-rwu4 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                  | award_number_w_amendments | award_title                   | award_type      | type_of_contract_subcontract | contractor_information             | contractor_address    | contractor_city | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ========================================= | ========================= | ============================= | =============== | ============================ | ================================== | ===================== | =============== | ================ | ============== | ============================================= | ==================== | =============== | ============================== | 
| 2223 | Columbia Gorge Education Service District | 18                        | Technology Equipment          | Price Agreement | Material                     | AdvanTel                           | 2222 Trade Zone Blvd. | San Jose        | CA               | 95131          | 03-07-12/ / 06-30-12                          | 32456.92             |                 | 32456.92                       | 
| 2223 | Columbia Gorge Education Service District | 2                         | Consulting                    | Price Agreement | Professional                 | Carruth Comliance Consulting, Inc. | 11515 SW Durham Road  | Tigard          | OR               | 97224          | 07-01-11/ 07-01-12 / 06-30-13                 | 2640.00              |                 | 2640.00                        | 
| 2223 | Columbia Gorge Education Service District | 1                         | Facilities Lease              | Price Agreement | Professional                 | Columbia Gorge Community College   | 400 East Scenic Drive | The Dalles      | OR               | 97058          | 10-01-10/ / 06-30-15                          | 55584.00             |                 | 55584.00                       | 
| 2223 | Columbia Gorge Education Service District | 31                        | Facilities Maintenance        | Price Agreement | Professional                 | Crowns 3 Janitorial                | 1217 Roberts Street   | The Dalles      | OR               | 97058          | 10-01-12/ / 09-30-13                          | 6655.50              |                 | 6655.50                        | 
| 2223 | Columbia Gorge Education Service District | 26                        | Superintendent Services       | Price Agreement | Professional                 | Gary Peterson                      | 2543 Jordan Street    | The Dalles      | OR               | 97058          | 07-01-12/ / 06-30-15                          | 103626.00            |                 | 103626.00                      | 
| 2223 | Columbia Gorge Education Service District | 32                        | Document Destruction Services | Price Agreement | Professional                 | Gorge Security Shred               | 2940 Thomsen Rd       | Hood River      | OR               | 97031          | 09-22-10/ / open                              |                      |                 |                                | 
| 2223 | Columbia Gorge Education Service District | 43                        | Instructional Services        | Price Agreement | Professional                 | Hood River County School District  | 1011 Eugene Street    | Hood River      | OR               | 97031          | 07-01-12/ / 06-30-13                          | 45500.00             |                 | 45500.00                       | 
| 2223 | Columbia Gorge Education Service District | 20                        | Telecommunication Services    | Trade Services  | Professional                 | Johnson Network                    | 312 Court Street      | The Dalles      | OR               | 97058          | 07-01-12/ 10-01-12 / 06-30-14                 | 14400.00             | 8400.00         | 22800.00                       | 
| 2223 | Columbia Gorge Education Service District | 21                        | Telecommunication Services    | Trade Services  | Professional                 | Johnson Network                    | 312 Court Street      | The Dalles      | OR               | 97058          | 07-01-12/ 10-01-12 / 06-30-14                 | 14400.00             | 8400.00         | 22800.00                       | 
| 2223 | Columbia Gorge Education Service District | 13                        | Physical Therapy Services     | Price Agreement | Professional                 | Kidsense                           | 315 Oak Street        | Hood River      | OR               | 97031          | 07-01-12/ / 06-30-13                          | 50400.00             |                 | 50400.00                       | 
```