# Contracts: ESD: Grant: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-grant-fiscal-year-2014-941b6) |
| Metadata | [Link](https://data.oregon.gov/api/views/sznd-yvc9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/sznd-yvc9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/sznd-yvc9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | sznd-yvc9 |
| Name | Contracts: ESD: Grant: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, esd, grant, fiscal year 2014 |
| Created | 2014-12-16T19:27:08Z |
| Publication Date | 2014-12-29T06:09:30Z |

## Description

Contracts for the Grant ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                            | Data Type | Render Type |
| ======== | ============== | ============================================= | =============================================== | ========= | =========== |
| Yes      | numeric metric | esd                                           | ESD #                                           | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD Name                                        | text      | text        |
| Yes      | series tag     | award_number_w_amendments                     | Award Number w/Amendments                       | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type                                      | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract                  | Type of Contract/ Subcontract                   | text      | text        |
| Yes      | series tag     | contractor_information                        | Contractor Information                          | text      | text        |
| No       |                | contractor_address                            | Contractor Address                              | text      | text        |
| Yes      | series tag     | contractor_city                               | Contractor City                                 | text      | text        |
| Yes      | series tag     | contractor_state                              | Contractor State                                | text      | text        |
| Yes      | series tag     | contractor_zip                                | Contractor Zip                                  | text      | number      |
| No       |                | original_start_amendment_date_expiration_date | Original Start/ Amendment Date/ Expiration Date | text      | text        |
| Yes      | numeric metric | total_award_value_current_year                | Total Award Value Current Year                  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:sznd-yvc9 d:2014-01-01T00:00:00.000Z t:esd_name="Grant ESD" t:contractor_state=Oregon t:type_of_contract_subcontract=Professional t:award_number_w_amendments=NA t:contractor_city="John Day" t:award_type="Monthly Contract" t:contractor_zip=97845 t:contractor_information="Eastern Oregon Building Maintenance" m:total_award_value_current_year=5100 m:esd=2007

series e:sznd-yvc9 d:2014-01-01T00:00:00.000Z t:esd_name="Grant ESD" t:contractor_state=Oregon t:type_of_contract_subcontract=Professional t:award_number_w_amendments=NA t:contractor_city=Gladstone t:award_type="Price Agreement" t:contractor_zip=97027 t:contractor_information="The Hello Foundation" m:total_award_value_current_year=73550 m:esd=2007

series e:sznd-yvc9 d:2014-01-01T00:00:00.000Z t:esd_name="Grant ESD" t:contractor_state=Oregon t:type_of_contract_subcontract=Personal t:award_number_w_amendments=NA t:contractor_city=Condon t:award_type="Annual Rate" t:contractor_zip=97823 t:contractor_information="R. E. Myers & Associates, LLC" m:total_award_value_current_year=10000 m:esd=2007
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:total_award_value_current_year p:double l:"Total Award Value Current Year" t:dataTypeName=money

entity e:sznd-yvc9 l:"Contracts: ESD: Grant: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/sznd-yvc9

property e:sznd-yvc9 t:meta.view v:id=sznd-yvc9 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Grant: Fiscal Year 2014"

property e:sznd-yvc9 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:sznd-yvc9 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name  | award_number_w_amendments | award_type       | type_of_contract_subcontract | contractor_information              | contractor_address | contractor_city | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | total_award_value_current_year | 
| ==== | ========= | ========================= | ================ | ============================ | =================================== | ================== | =============== | ================ | ============== | ============================================= | ============================== | 
| 2007 | Grant ESD | NA                        | Monthly Contract | Professional                 | Eastern Oregon Building Maintenance | 350 Highland Place | John Day        | Oregon           | 97845          | 2001                                          | 5100.00                        | 
| 2007 | Grant ESD | NA                        | Price Agreement  | Professional                 | The Hello Foundation                | P. O. Box 623      | Gladstone       | Oregon           | 97027          | 40452                                         | 73550.00                       | 
| 2007 | Grant ESD | NA                        | Annual Rate      | Personal                     | R. E. Myers & Associates, LLC       | P. O. Box 17       | Condon          | Oregon           | 97823          | 12-1-2008/7-1-2010                            | 10000.00                       | 
| 2007 | Grant ESD | NA                        | Price Agreement  | Professional                 | Oster Professional Group            | 101 NE 1st Avenue  | John Day        | Oregon           | 97845          | 40360                                         | 8860.00                        | 
| 2007 | Grant ESD | NA                        | Price Agreement  | Material                     | Wells Fargo Financial Leasing       | 800 Walnut Street  | Des Moines      | Iowa             | 50309          | 41733                                         | 8608.00                        | 
```