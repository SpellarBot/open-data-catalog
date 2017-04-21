# County Spending

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-spending-f463a) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/vpf9-6irq) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/vpf9-6irq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/vpf9-6irq/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | vpf9-6irq |
| Name | County Spending |
| Category | Finance/Tax/Property |
| Tags | spending, checks, invoices, vendors, suppliers, purchase order |
| Created | 2014-12-05T19:34:38Z |
| Publication Date | 2015-05-07T15:44:40Z |

## Description

This dataset includes County spending data for Montgomery County government. It does not include agency spending. Data considered sensitive or confidential and will be encrypted before it is posted.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | numeric metric | fiscal_year_period        | Fiscal Year Period        | number        | number        |
| No       |                | fiscal_year               | Fiscal Year               | number        | number        |
| Yes      | series tag     | service                   | Service                   | text          | text          |
| Yes      | series tag     | department                | Department                | text          | text          |
| Yes      | series tag     | program                   | Program                   | text          | text          |
| Yes      | series tag     | fund                      | Fund                      | text          | text          |
| Yes      | series tag     | category                  | Category                  | text          | text          |
| Yes      | series tag     | expense_category          | Expense Category          | text          | text          |
| Yes      | series tag     | account_code              | Account Code              | text          | text          |
| Yes      | series tag     | description               | Invoice Description       | text          | text          |
| Yes      | series tag     | vendor                    | Vendor                    | text          | text          |
| Yes      | series tag     | vendor_id                 | Vendor Number             | text          | text          |
| Yes      | series tag     | vendor_zip                | Zip                       | text          | text          |
| Yes      | series tag     | contract_num              | Contract Number           | text          | text          |
| Yes      | series tag     | po_num                    | PO Number                 | text          | text          |
| Yes      | numeric metric | po_line                   | PO Line                   | number        | text          |
| Yes      | series tag     | invoice_id                | Invoice Number            | text          | text          |
| Yes      | numeric metric | invoice_line              | Invoice Line              | number        | text          |
| Yes      | numeric metric | invoice_distribution_line | Invoice Distribution Line | number        | text          |
| Yes      | numeric metric | amount                    | Amount                    | number        | number        |
| No       |                | inv_date                  | Invoice Date              | calendar_date | calendar_date |
| Yes      | series tag     | payment_method            | Payment Method            | text          | text          |
| Yes      | time           | payment_date              | Payment Date              | calendar_date | calendar_date |
| Yes      | series tag     | payment_id                | Payment Number            | text          | number        |
| Yes      | series tag     | payment_status            | Payment Status            | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = inv_date,fiscal_year
```

## Data Commands

```ls
series e:vpf9-6irq d:2016-10-10T00:00:00.000Z t:department="Liquor Control" t:vendor="P-CARD PURCHASES (JP MORGAN CHASE)" t:account_code=63634 t:expense_category="Phones/Telecommunication Services" t:vendor_id=50766 t:payment_status=RECONCILED t:vendor_zip=60197-4471 t:category="Operating Expenses" t:description="Other Communication Services" t:program="Retail Sales Operations" t:service="General Government" t:payment_id=452450 t:invoice_id=2243394385001 t:fund=Liquor t:payment_method=EFT m:amount=214.85 m:invoice_line=1 m:fiscal_year_period=4 m:invoice_distribution_line=1

series e:vpf9-6irq d:2013-12-20T00:00:00.000Z t:department="Human Resources" t:vendor="GROUP HOSPITALIZATION AND MEDICAL SERVICES INC" t:account_code=65624 t:expense_category="Insurance (Non-Fringe Benefits)" t:vendor_id=10759 t:po_num=1037952 t:payment_status=RECONCILED t:vendor_zip=21117 t:category="Operating Expenses" t:description="Actives - Claims" t:program="Health & Employee Welfare" t:service="General Government" t:payment_id=368883 t:invoice_id=121613PG52 t:fund="Employee Health Self Insurance" t:payment_method=EFT m:amount=1576281.42 m:invoice_line=1 m:po_line=1 m:fiscal_year_period=6 m:invoice_distribution_line=1

series e:vpf9-6irq d:2016-11-22T00:00:00.000Z t:department="Housing and Community Affairs" t:vendor=4258210579 t:account_code=65132 t:expense_category="Public Assistance" t:vendor_id=60508852 t:po_num=12751057 t:payment_status=RECONCILED t:vendor_zip=20850 t:category="Operating Expenses" t:description="Other Rental Assistance Program Benefits" t:program="Multi-Family Housing Programs" t:service="Housing and Community Development" t:payment_id=3198504552 t:invoice_id=2380687041 t:fund="Montgomery Housing Initiative" t:payment_method=CHECK t:contract_num=60508852 m:amount=200 m:invoice_line=10 m:fiscal_year_period=5 m:invoice_distribution_line=1
```

## Meta Commands

```ls
metric m:fiscal_year_period p:integer l:"Fiscal Year Period" d:"Our fiscal year runs July 1st through June 30th. A period is equal to one month (Example: period 1 is July, period 2 is August, period 3 is September, etc.)" t:dataTypeName=number

metric m:po_line p:float l:"PO Line" d:"The line number for a specific item or service that is being purchased on the Purchase Order (PO). (For example, if five different items are purchased, then there will be five PO lines.)" t:dataTypeName=number

metric m:invoice_line p:float l:"Invoice Line" d:"A line number from a supplier invoice, for the County?s purchase of a good or a service." t:dataTypeName=number

metric m:invoice_distribution_line p:float l:"Invoice Distribution Line" d:"The line number indicating which Department(s) or Program(s) the invoice is charged to. (For example, if five different departments are being charged for an item, then there will be five distribution lines.)" t:dataTypeName=number

metric m:amount p:double l:Amount d:"The dollar amount associated with an invoice distribution line." t:dataTypeName=number

entity e:vpf9-6irq l:"County Spending" t:url=https://data.montgomerycountymd.gov/api/views/vpf9-6irq

property e:vpf9-6irq t:meta.view v:id=vpf9-6irq v:category=Finance/Tax/Property v:averageRating=0 v:name="County Spending"

property e:vpf9-6irq t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:vpf9-6irq t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| fiscal_year_period | fiscal_year | service                           | department                    | program                                       | fund                           | category           | expense_category                   | account_code | description                              | vendor                                         | vendor_id | vendor_zip | contract_num | po_num   | po_line | invoice_id    | invoice_line | invoice_distribution_line | amount     | inv_date            | payment_method | payment_date        | payment_id | payment_status | 
| ================== | =========== | ================================= | ============================= | ============================================= | ============================== | ================== | ================================== | ============ | ======================================== | ============================================== | ========= | ========== | ============ | ======== | ======= | ============= | ============ | ========================= | ========== | =================== | ============== | =================== | ========== | ============== | 
| 4                  | 2017        | General Government                | Liquor Control                | Retail Sales Operations                       | Liquor                         | Operating Expenses | Phones/Telecommunication Services  | 63634        | Other Communication Services             | P-CARD PURCHASES (JP MORGAN CHASE)             | 50766     | 60197-4471 |              |          |         | 2243394385001 | 1.0          | 1.0                       | 214.85     | 2016-08-31T00:00:00 | EFT            | 2016-10-10T00:00:00 | 452450     | RECONCILED     | 
| 6                  | 2014        | General Government                | Human Resources               | Health & Employee Welfare                     | Employee Health Self Insurance | Operating Expenses | Insurance (Non-Fringe Benefits)    | 65624        | Actives - Claims                         | GROUP HOSPITALIZATION AND MEDICAL SERVICES INC | 10759     | 21117      |              | 1037952  | 1.0     | 121613PG52    | 1.0          | 1.0                       | 1576281.42 | 2013-12-16T00:00:00 | EFT            | 2013-12-20T00:00:00 | 368883     | RECONCILED     | 
| 5                  | 2017        | Housing and Community Development | Housing and Community Affairs | Multi-Family Housing Programs                 | Montgomery Housing Initiative  | Operating Expenses | Public Assistance                  | 65132        | Other Rental Assistance Program Benefits | 4258210579                                     | 60508852  | 20850      | 60508852     | 12751057 |         | 2380687041    | 10.0         | 1.0                       | 200        | 2016-11-21T00:00:00 | CHECK          | 2016-11-22T00:00:00 | 3198504552 | RECONCILED     | 
| 7                  | 2016        | Culture and Recreation            | Public Libraries              | Collection Management                         | General Fund                   | Operating Expenses | Books/Videos/Subscriptions         | 62710        | Book Processing                          | BAKER & TAYLOR INC                             | 26730     | 30384-7930 |              | 1061042  | 2.0     | 3020606277    | 1.0          | 1.0                       | 23.76      | 2015-10-27T00:00:00 | MCG_JPM_SUA    | 2016-01-07T00:00:00 | 6009471    | RECONCILED     | 
| 9                  | 2016        | Public Safety                     | Fire and Rescue Service       | Operations                                    | Fire                           | Operating Expenses | Other Supplies/Materials/Equipment | 62816        | Cleaning Supplies                        | MONTGOMERY COUNTY PUBLIC SCHOOLS               | 1431      | 20850-9999 |              | 1056374  | 1.0     | 6039741       | 1.0          | 1.0                       | 103.54     | 2016-01-27T00:00:00 | EFT            | 2016-03-15T00:00:00 | 434615     | RECONCILED     | 
| 8                  | 2014        | Public Safety                     | Fire and Rescue Service       | Operations                                    | Fire                           | Operating Expenses | Motor Vehicle Supplies/Equipment   | 62400        | Engine Parts & Supplies                  | SPARTAN CHASSIS INC DBA SPARTAN MOTORS USA INC | 25742     | 48277-0340 |              |          |         | IN00571387    | 1.0          | 1.0                       | 149.65     | 2014-02-05T00:00:00 | CHECK          | 2014-02-25T00:00:00 | 2022834    | RECONCILED     | 
| 5                  | 2017        | Transportation                    | Transportation                | Administration                                | General Fund                   | Operating Expenses | Contract and Services              | 60168        | Temporary Office Clerical                | 1ST CHOICE STAFFING LLC                        | 25676     | 30343      |              |          |         | 2104-6470     | 1.0          | 1.0                       | 878        | 2016-10-22T00:00:00 | EFT            | 2016-12-01T00:00:00 | 457405     | RECONCILED     | 
| 5                  | 2017        | General Government                | Liquor Control                | Warehouse Operations                          | Liquor                         | Not Defined        | Liquor Purchases (DLC)             | 14750        | Liquor and Wine Inventory                | DIAGEO NORTH AMERICA INC                       | 13874     | 06610      |              | 129578   | 1.0     | 9219559421    | 1.0          | 1.0                       | 198459.06  | 2016-11-25T00:00:00 | EFT            | 2016-12-14T00:00:00 | 89731      | RECONCILED     | 
| 6                  | 2017        | Health and Human Services         | Health and Human Services     | Outpatient Behavioral Health Services - Adult | General Fund                   | Operating Expenses | Travel                             | 64010        | Metropolitan Area Travel                 | McAlpine-Eig, Catherine                        | 38545     |            |              |          |         | 1258397       | 2.0          | 1.0                       | 169.02     | 2016-07-05T00:00:00 | EFT            | 2016-12-19T00:00:00 | 458886     | RECONCILED     | 
| 11                 | 2015        | General Government                | General Services              | Facilities Management                         | General Fund                   | Not Defined        | Contract and Services              | 14201        | DGS Facilities - Inventory               | LIBERTY LOCK & SECURITY INC                    | 34568     | 20850      |              | 1033891  | 2.0     | S77514-IN     | 1.0          | 1.0                       | 16.78      | 2015-04-15T00:00:00 | MCG_JPM_SUA    | 2015-05-28T00:00:00 | 6007602    | RECONCILED     | 
```