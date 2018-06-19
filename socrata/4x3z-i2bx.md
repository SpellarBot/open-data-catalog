# Contracts: ESD: Northwest Regional: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-northwest-regional-fiscal-year-2013-28d5b) |
| Metadata | [Link](https://data.oregon.gov/api/views/4x3z-i2bx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4x3z-i2bx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4x3z-i2bx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4x3z-i2bx |
| Name | Contracts: ESD: Northwest Regional: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, esd, northwest regional, nw regional, fiscal year 2013 |
| Created | 2013-11-04T20:09:38Z |
| Publication Date | 2013-11-04T20:15:02Z |

## Description

Contracts for Northwest Regional ESD for Fiscal Yeear 2013

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
| Yes      | series tag     | contractor_zip                                | Contractor Zip                                | text      | text        |
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
Excluded Fields = contractor_address,original_start_amendment_date_expiration_date
```

## Data Commands

```ls
series e:4x3z-i2bx d:2013-01-01T00:00:00.000Z t:esd_name="Northwest Regional Education Service District" t:contractor_state=MD t:type_of_contract_subcontract="Professional Services" t:total_award_value_w_amendments="* 5,000.00" t:contractor_city=ROCKVILLE t:award_type="Price Agreement" t:award_title="Training Presenter" t:contractor_zip=20853-2626 t:contractor_information="Cafiero Communications; Joanne M. Cafiero" t:original_award_value="* 5,000.00" m:award_number_w_amendments=133937 m:esd=2230

series e:4x3z-i2bx d:2013-01-01T00:00:00.000Z t:esd_name="Northwest Regional Education Service District" t:contractor_state=OR t:type_of_contract_subcontract="Professional Services" t:total_award_value_w_amendments="* 3,200.00" t:contractor_city="FOREST GROVE" t:award_type="Price Agreement" t:award_title="EI/ECSE Program Services" t:contractor_zip=97116-0000 t:contractor_information="Pacific University/Early Learning Community" t:original_award_value="* 3,200.00" m:award_number_w_amendments=130974 m:esd=2230

series e:4x3z-i2bx d:2013-01-01T00:00:00.000Z t:esd_name="Northwest Regional Education Service District" t:contractor_state=OR t:type_of_contract_subcontract="Professional Services" t:total_award_value_w_amendments="* 337.50" t:contractor_city=WARRENTON t:award_type="Price Agreement" t:award_title=Rental t:contractor_zip=97146-9711 t:contractor_information="Oregon Dept. of Military; c/o Camp Rilea" t:original_award_value="* 337.50" m:award_number_w_amendments=132208 m:esd=2230
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:award_number_w_amendments p:integer l:"Award Number w/Amendments" t:dataTypeName=number

entity e:4x3z-i2bx l:"Contracts: ESD: Northwest Regional: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/4x3z-i2bx

property e:4x3z-i2bx t:meta.view v:id=4x3z-i2bx v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Northwest Regional: Fiscal Year 2013"

property e:4x3z-i2bx t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:4x3z-i2bx t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                      | award_number_w_amendments | award_title                        | award_type      | type_of_contract_subcontract | contractor_information                                  | contractor_address   | contractor_city | contractor_state | contractor_zip | original_start_amendment_date_expiration_date | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | ============================================= | ========================= | ================================== | =============== | ============================ | ======================================================= | ==================== | =============== | ================ | ============== | ============================================= | ==================== | =============== | ============================== | 
| 2230 | Northwest Regional Education Service District | 133937                    | Training Presenter                 | Price Agreement | Professional Services        | Cafiero Communications; Joanne M. Cafiero               | 14112 CASTAWAY DRIVE | ROCKVILLE       | MD               | 20853-2626     | 3/1/2013 / 00/00/0000 / 3/30/2013             | * 5,000.00           |                 | * 5,000.00                     | 
| 2230 | Northwest Regional Education Service District | 130974                    | EI/ECSE Program Services           | Price Agreement | Professional Services        | Pacific University/Early Learning Community             | 2043 COLLEGE WAY     | FOREST GROVE    | OR               | 97116-0000     | 07/01/12 / 00/00/0000 / 6/30/2013             | * 3,200.00           |                 | * 3,200.00                     | 
| 2230 | Northwest Regional Education Service District | 132208                    | Rental                             | Price Agreement | Professional Services        | Oregon Dept. of Military; c/o Camp Rilea                | 33168 PATRIOT WAY    | WARRENTON       | OR               | 97146-9711     | 10/25/12 / 00/00/0000 / 10/25/2012            | * 337.50             |                 | * 337.50                       | 
| 2230 | Northwest Regional Education Service District | 133867                    | BVIS Reimbursement                 | Price Agreement | Professional Services        | Portland Public Schools                                 | 501 N. DIXON ST.     | PORTLAND        | OR               | 97227-1804     | 07/01/12 / 00/00/0000 / 6/30/2013             | * 40,000.00          |                 | * 40,000.00                    | 
| 2230 | Northwest Regional Education Service District | 132813                    | Agreement #108-13 - Matching Grant | Price Agreement | Professional Services        | State of Oregon Commission for the Blind - PAID IN FULL | 535 SE 12TH AVENUE   | PORTLAND        | OR               | 97214          | 11/01/12 / 00/00/0000 / 1/31/2013             | * 27,500.00          |                 | * 27,500.00                    | 
| 2230 | Northwest Regional Education Service District | 125510                    | SWEP 2012                          | Price Agreement | Professional Services        | State of Oregon Commission for the Blind - PAID IN FULL | 535 SE 12TH AVENUE   | PORTLAND        | OR               | 97214          | 06/01/12 / 00/00/0000 / 8/1/2012              | * 90,000.00          |                 | * 90,000.00                    | 
| 2230 | Northwest Regional Education Service District | 500005                    | SWEP 2013                          | Price Agreement | Professional Services        | State of Oregon Commission for the Blind - PAID IN FULL | 535 SE 12TH AVENUE   | PORTLAND        | OR               | 97214          | 06/01/13 / 00/00/0000 / 9/1/2013              | * 123,800.00         |                 | * 123,800.00                   | 
| 2230 | Northwest Regional Education Service District | 133503                    | Translation Services               | Price Agreement | Professional Services        | Northcoast Translation Services                         | 969 8TH ST           | ASTORIA         | OR               | 97103          | 01/15/13 / 00/00/0000 / 6/30/2013             | * 2,000.00           |                 | * 2,000.00                     | 
| 2230 | Northwest Regional Education Service District | 130459                    | Carpet cleaning for WSC            | Price Agreement | Professional Services        | Northwest Commerical Carpet & Floor Cleaning, Inc.      | P.O. BOX 104         | CLACKAMAS       | OR               | 97015          | 07/01/12 / 00/00/0000 / 6/30/2013             | * 6,700.00           |                 | * 6,700.00                     | 
| 2230 | Northwest Regional Education Service District | 132946                    | Training Presenter                 | Price Agreement | Professional Services        | Clear Perspective                                       | PO BOX 1404          | MCMINNVILLE     | OR               | 97128          | 12/03/12 / 00/00/0000 / 1/24/2013             | * 17,498.95          |                 | * 17,498.95                    | 
```