# 2015 Composite All ESD Contracts SB250v2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-composite-all-esd-contracts-sb250v2) |
| Metadata | [Link](https://data.oregon.gov/api/views/6kp9-eip2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6kp9-eip2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6kp9-eip2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6kp9-eip2 |
| Name | 2015 Composite All ESD Contracts SB250v2 |
| Category | Revenue & Expense |
| Tags | 2015; contracts; esd, fiscal year 2015: esd contracts |
| Created | 2016-02-13T19:45:17Z |
| Publication Date | 2016-11-09T10:10:09Z |

## Description

This is a composite listing of contract data from all ESD's per SB250 for Fiscal Year 2015. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | time           | fiscal_year                                   | FISCAL YEAR                                   | number    | number      |
| Yes      | numeric metric | esd                                           | ESD #                                         | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD Name                                      | text      | text        |
| Yes      | series tag     | award_number_w_amendments_po_no               | Award Number w/Amendments                     | text      | text        |
| Yes      | series tag     | award_title                                   | Award Title                                   | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type                                    | text      | text        |
| Yes      | series tag     | type_of_contract_subcontract                  | Type of Contract/Subcontract                  | text      | text        |
| Yes      | series tag     | contractor_information                        | Contractor Information                        | text      | text        |
| No       |                | contractor_address                            | Contractor Address                            | text      | text        |
| Yes      | series tag     | contractor_city_state_zip                     | Contractor City/State/Zip                     | text      | text        |
| Yes      | series tag     | contractor_state                              | Contractor_State                              | text      | text        |
| Yes      | series tag     | contractor_zip                                | Contractor_Zip                                | text      | text        |
| No       |                | original_start_amendment_date_expiration_date | Original Start/Amendment Date/Expiration Date | text      | text        |
| Yes      | numeric metric | original_award_value                          | Original Award Value                          | money     | money       |
| Yes      | numeric metric | amendment_value                               | Amendment Value                               | money     | money       |
| Yes      | numeric metric | total_award_value_w_amendments                | Total Award Value w/Amendments                | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contractor_address,original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:6kp9-eip2 d:2015-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:type_of_contract_subcontract="Contracts 2014-15" t:award_title=Auxilary t:contractor_city_state_zip="Vancouver,WA 98687-2830" t:contractor_information="Alpha Ecological" t:award_number_w_amendments_po_no=150316 m:amendment_value=0 m:total_award_value_w_amendments=129 m:esd=1902 m:original_award_value=129

series e:6kp9-eip2 d:2015-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:type_of_contract_subcontract="Contracts 2014-15" t:award_title=Auxilary t:contractor_city_state_zip="Vancouver,WA 98687-2830" t:contractor_information="Alpha Ecological" t:award_number_w_amendments_po_no=150014 m:amendment_value=0 m:total_award_value_w_amendments=476 m:esd=1902 m:original_award_value=476

series e:6kp9-eip2 d:2015-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:type_of_contract_subcontract="Contracts 2014-15" t:award_title=Auxilary t:contractor_city_state_zip="Portland,OR 97202" t:contractor_information="American Security Alarms Co." t:award_number_w_amendments_po_no=150015 m:amendment_value=0 m:total_award_value_w_amendments=598.8 m:esd=1902 m:original_award_value=598.8
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:6kp9-eip2 l:"2015 Composite All ESD Contracts SB250v2" t:url=https://data.oregon.gov/api/views/6kp9-eip2

property e:6kp9-eip2 t:meta.view v:id=6kp9-eip2 v:category="Revenue & Expense" v:averageRating=0 v:name="2015 Composite All ESD Contracts SB250v2"

property e:6kp9-eip2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6kp9-eip2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd  | esd_name      | award_number_w_amendments_po_no | award_title                  | award_type | type_of_contract_subcontract | contractor_information       | contractor_address          | contractor_city_state_zip | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| =========== | ==== | ============= | =============================== | ============================ | ========== | ============================ | ============================ | =========================== | ========================= | ================ | ============== | ============================================= | ==================== | =============== | ============================== | 
| 2015        | 1902 | Clackamas ESD | 150316                          | Auxilary                     |            | Contracts 2014-15            | Alpha Ecological             | PO Box 872830               | Vancouver,WA 98687-2830   |                  |                | 9/5/2014                                      | 129.00               | 0.00            | 129.00                         | 
| 2015        | 1902 | Clackamas ESD | 150014                          | Auxilary                     |            | Contracts 2014-15            | Alpha Ecological             | PO Box 872830               | Vancouver,WA 98687-2830   |                  |                | 6/25/2014                                     | 476.00               | 0.00            | 476.00                         | 
| 2015        | 1902 | Clackamas ESD | 150015                          | Auxilary                     |            | Contracts 2014-15            | American Security Alarms Co. | 5411 S.E. Mc Loughlin Blvd. | Portland,OR 97202         |                  |                | 6/24/2014                                     | 598.80               | 0.00            | 598.80                         | 
| 2015        | 1902 | Clackamas ESD | 150109                          | Auxilary                     |            | Contracts 2014-15            | American Security Alarms Co. | 5411 S.E. Mc Loughlin Blvd. | Portland,OR 97202         |                  |                | 7/14/2014                                     | 360.00               | -0.60           | 359.40                         | 
| 2015        | 1902 | Clackamas ESD | 151317                          | Network Info Services        |            | Contracts 2014-15            | Aronson Security Group       | 8089 SW Cirrus Dr.          | Beaverton,OR 97008-5989   |                  |                | 6/26/2015                                     | 380.00               | 0.00            | 380.00                         | 
| 2015        | 1902 | Clackamas ESD | 151266                          | WIA                          |            | Contracts 2014-15            | Bitclone, LLC                | 1109 N. Buffalo St.         | Portland,OR 97217         |                  |                | 6/9/2015                                      | 3350.00              | 0.00            | 3350.00                        | 
| 2015        | 1902 | Clackamas ESD | 150572                          | School Improvement           |            | Contracts 2014-15            | Bonita L. Staebler           | 438 Crystal Springs Lane N. | Keizer,OR 97303           |                  |                | 10/29/2014                                    | 5000.00              | -1700.00        | 3300.00                        | 
| 2015        | 1902 | Clackamas ESD | 150001                          | Human Resources              |            | Contracts 2014-15            | Boyle EMS HazMat Education   | 12365 SW King George Dr.    | King City,OR 97224        |                  |                | 6/16/2014                                     | 3500.00              | -875.00         | 2625.00                        | 
| 2015        | 1902 | Clackamas ESD | 150545                          | Human Resources              |            | Contracts 2014-15            | Boyle Safety Training, LLC   | 12365 SW King George Dr.    | King City,OR 97224        |                  |                | 10/27/2014                                    | 875.00               | -70.00          | 805.00                         | 
| 2015        | 1902 | Clackamas ESD | 150103                          | Child Care Resource/Referral |            | Contracts 2014-15            | Boyle Safety Training, LLC   | 12365 SW King George Dr.    | King City,OR 97224        |                  |                | 7/7/2014                                      | 17000.00             | -4780.00        | 12220.00                       | 
```