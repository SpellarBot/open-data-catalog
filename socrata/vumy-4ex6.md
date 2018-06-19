# Contracts: ESD: LBL: FY2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-lbl-fy2013-cdbdf) |
| Metadata | [Link](https://data.oregon.gov/api/views/vumy-4ex6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vumy-4ex6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vumy-4ex6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vumy-4ex6 |
| Name | Contracts: ESD: LBL: FY2013 |
| Category | Revenue & Expense |
| Tags | esd, contracts, esd contracts, lbl esd contracts, linn benton lincoln esd contracts |
| Created | 2013-12-02T22:27:08Z |
| Publication Date | 2013-12-02T22:31:18Z |

## Description

Summary of contracts for Linn, Benton, Lincoln ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | numeric metric | esd                                           | ESD #                                         | number    | number      |
| Yes      | series tag     | esd_name                                      | ESD NAME                                      | text      | text        |
| Yes      | numeric metric | award_number_w_amendments                     | Award Number w/Amendments                     | number    | number      |
| Yes      | series tag     | award_title                                   | Award Title                                   | text      | text        |
| Yes      | series tag     | award_type                                    | Award Type **                                 | text      | text        |
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
series e:vumy-4ex6 d:2013-01-01T00:00:00.000Z t:esd_name="Linn Benton Lincoln Education Service District" t:contractor_state=WA t:type_of_contract_subcontract=Professional t:contractor_city=Vancouver t:award_type="Price Agreement" t:award_title="Licensing Agreement" t:contractor_zip=98682 t:contractor_information="Andrew Scott LLC" m:amendment_value=42000 m:total_award_value_w_amendments=67200 m:esd=2098 m:original_award_value=25200

series e:vumy-4ex6 d:2013-01-01T00:00:00.000Z t:esd_name="Linn Benton Lincoln Education Service District" t:contractor_state=OR t:type_of_contract_subcontract="Personal Service" t:contractor_city=Corvallis t:award_type="Personal Service" t:award_title="Law Enforcement Services" t:contractor_zip=97330 t:contractor_information="Benton County" m:esd=2098

series e:vumy-4ex6 d:2013-01-01T00:00:00.000Z t:esd_name="Linn Benton Lincoln Education Service District" t:contractor_state=TX t:type_of_contract_subcontract=Professional t:contractor_city=Dallas t:award_type="Price Agreement" t:award_title="Licensing Agreement" t:contractor_zip=75320 t:contractor_information="Computer Software Associates" m:amendment_value=504000 m:total_award_value_w_amendments=5091158 m:esd=2098 m:original_award_value=4587158
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:award_number_w_amendments p:integer l:"Award Number w/Amendments" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:amendment_value p:double l:"Amendment Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:vumy-4ex6 l:"Contracts: ESD: LBL: FY2013" t:url=https://data.oregon.gov/api/views/vumy-4ex6

property e:vumy-4ex6 t:meta.view v:id=vumy-4ex6 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: LBL: FY2013"

property e:vumy-4ex6 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vumy-4ex6 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                       | award_number_w_amendments | award_title                | award_type        | type_of_contract_subcontract | contractor_information                        | contractor_address              | contractor_city | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ============================================== | ========================= | ========================== | ================= | ============================ | ============================================= | =============================== | =============== | ================ | ============== | ============================================= | ==================== | =============== | ============================== | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Licensing Agreement        | Price Agreement   | Professional                 | Andrew Scott LLC                              | PO Box 820205                   | Vancouver       | WA               | 98682          | 05/14/2012, 06/30/2013                        | 25200.00             | 42000.00        | 67200.00                       | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Law Enforcement Services   | Personal Service  | Personal Service             | Benton County                                 | 180 NW 5th Avenue               | Corvallis       | OR               | 97330          | 07/01/2009, 06/30/2013                        |                      |                 |                                | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Licensing Agreement        | Price Agreement   | Professional                 | Computer Software Associates                  | PO Box 203556                   | Dallas          | TX               | 75320          | 10/7/2007, 06/30/2012, 06/30/2013             | 4587158.00           | 504000.00       | 5091158.00                     | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Contract for Services      | Service Agreement | Professional                 | Corvallis Parks and Rec. Maple Lawn Preschool | 1310 SW Avery Park Drive        | Corvallis       | OR               | 97333          | 07/01/2012, 09/01/2012, 06/30/2013            | 19250.00             | 2800.00         | 22050.00                       | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Licensing Agreement        | Price Agreement   | Professional                 | Evisions                                      | 410 Exchange, Suite 250         | Irvine          | CA               | 92602          | 05/23/2013, 06/30/2016                        | 175500.00            | 0.00            | 175500.00                      | 
| 2098 | Linn Benton Lincoln Education Service District | 3601750                   | Master Agreement           | Price Agreement   | Professional                 | Follett Software Company                      | 14394 Collection Center Drive   | Chicago         | IL               | 60693          | 01/03/2011, 01/02/2014                        | 279825.00            | 0.00            | 279825.00                      | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Licensing Agreement        | Price Agreement   | Professional                 | Global Scholar                                | PO Box 93038                    | Chicago         | IL               | 60673          | 12/01/2012, 11/20/2013                        | 90000.00             | 0.00            | 90000.00                       | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Master Service Agreement   | Price Agreement   | Professional                 | Integra                                       | PO Box 2966                     | Milwaukie       | WI               | 53201          | 3/22/2011, 3/21/2014                          | 21416.28             | 0.00            | 21416.28                       | 
| 2098 | Linn Benton Lincoln Education Service District |                           | Master Service Agreement   | Price Agreement   | Professional                 | LS Networks                                   | 921 SW Washington St, Suite 370 | Portland        | OR               | 97205          | 3/21/2011, 3/20/2015                          | 146493.40            | 0.00            | 146493.40                      | 
| 2098 | Linn Benton Lincoln Education Service District |                           | HVAC Maintenance Agreement | Trade Service     | Professional and Materials   | MacDonald-Miller                              | PO Box 47983                    | Seattle         | WA               | 98146          | 07/01/2012, 06/30/2013                        | 36565.00             | 0.00            | 36565.00                       | 
```