# Lottery Contracts - FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lottery-contracts-fy-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/rkhh-35im) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rkhh-35im/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rkhh-35im/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rkhh-35im |
| Name | Lottery Contracts - FY 2016 |
| Category | Revenue & Expense |
| Tags | lottery contracts, lottery, oregon state lottery contracts 2016, 2016 |
| Created | 2016-12-06T06:59:02Z |
| Publication Date | 2016-12-06T07:05:39Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx#Lottery_Commission_-_Contract_Activity

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| No       |                | fiscal_year           | Fiscal Year           | number        | number        |
| Yes      | numeric metric | purchase_order        | Purchase order        | number        | number        |
| Yes      | series tag     | vendor                | Vendor                | text          | text          |
| No       |                | address_line          | Address line          | text          | text          |
| Yes      | series tag     | city                  | City                  | text          | text          |
| Yes      | series tag     | state                 | State                 | text          | text          |
| Yes      | series tag     | contract_description  | Contract Description  | text          | text          |
| Yes      | series tag     | line_no               | Line No               | text          | number        |
| Yes      | series tag     | line_item_description | Line Item Description | text          | text          |
| Yes      | time           | created               | Created               | calendar_date | calendar_date |
| Yes      | numeric metric | quantity              | Quantity              | number        | number        |
| Yes      | numeric metric | unit_price            | Unit price            | money         | money         |
| Yes      | numeric metric | net_amount            | Net Amount            | money         | money         |
```

## Time Field

```ls
Value = created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line,fiscal_year
```

## Data Commands

```ls
series e:rkhh-35im d:2016-06-01T00:00:00.000Z t:contract_description="Vehicle Car Wash" t:line_no=5 t:line_item_description="FY 17 Vehicle Washing & Detail" t:vendor="B & W CAR WASH" t:state=OR t:city=ONTARIO m:net_amount=250 m:quantity=250 m:unit_price=1 m:purchase_order=191

series e:rkhh-35im d:2016-06-01T00:00:00.000Z t:contract_description="Vehicle Maintenance & Repair" t:line_no=5 t:line_item_description="Truck Washing & Detail" t:vendor="MARSHALL SUNSHINE INC." t:state=OR t:city=AURORA m:net_amount=1000 m:quantity=1000 m:unit_price=1 m:purchase_order=194

series e:rkhh-35im d:2016-06-01T00:00:00.000Z t:contract_description="Vehicle Maintenance Repairs" t:line_no=6 t:line_item_description="Vehicle Maintenance & Repair" t:vendor="PENDLETON QUICKY LUBE" t:state=OR t:city=PENDLETON m:net_amount=1500 m:quantity=1500 m:unit_price=1 m:purchase_order=195
```

## Meta Commands

```ls
metric m:purchase_order p:integer l:"Purchase order" t:dataTypeName=number

metric m:quantity p:integer l:Quantity t:dataTypeName=number

metric m:unit_price p:double l:"Unit price" t:dataTypeName=money

metric m:net_amount p:double l:"Net Amount" t:dataTypeName=money

entity e:rkhh-35im l:"Lottery Contracts -  FY 2016" t:url=https://data.oregon.gov/api/views/rkhh-35im

property e:rkhh-35im t:meta.view v:id=rkhh-35im v:category="Revenue & Expense" v:averageRating=0 v:name="Lottery Contracts -  FY 2016"

property e:rkhh-35im t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rkhh-35im t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | purchase_order | vendor                        | address_line             | city        | state | contract_description                                    | line_no | line_item_description                                                                 | created             | quantity | unit_price | net_amount | 
| =========== | ============== | ============================= | ======================== | =========== | ===== | ======================================================= | ======= | ===================================================================================== | =================== | ======== | ========== | ========== | 
| 2016        | 191            | B & W CAR WASH                | 621 SW 4TH AVE           | ONTARIO     | OR    | Vehicle Car Wash                                        | 5       | FY 17 Vehicle Washing & Detail                                                        | 2016-06-01T00:00:00 | 250      | 1.00       | 250.00     | 
| 2016        | 194            | MARSHALL SUNSHINE INC.        | 12271 MELINDA LN NE      | AURORA      | OR    | Vehicle Maintenance & Repair                            | 5       | Truck Washing & Detail                                                                | 2016-06-01T00:00:00 | 1000     | 1.00       | 1000.00    | 
| 2016        | 195            | PENDLETON QUICKY LUBE         | 904 SW COURT AVE         | PENDLETON   | OR    | Vehicle Maintenance Repairs                             | 6       | Vehicle Maintenance & Repair                                                          | 2016-06-01T00:00:00 | 1500     | 1.00       | 1500.00    | 
| 2016        | 362            | MARION ENVIRONMENTAL SERVICES | PO BOX 9130              | Salem       | OR    | Removal and Disposal of Bio Hazard Waste, Blanket Order | 4       | FY 17 - PO 362 - Blanket PO For Bio Hazard Waste Removal for On-Call basis. NTE $200. | 2016-06-10T00:00:00 | 200      | 1.00       | 200.00     | 
| 2016        | 403            | GAELIC FLEET SYSTEMS INC      | 640 NW SILVERADO DR      | Beaverton   | OR    | E-Fleet On-Line Vehicle System                          | 7       | efleetbase 100 vehicles Usage Fee 12/1/2014 to 12/31/2015                             | 2015-10-06T00:00:00 | 2700     | 1.00       | 2700.00    | 
| 2016        | 403            | GAELIC FLEET SYSTEMS INC      | 640 NW SILVERADO DR      | Beaverton   | OR    | E-Fleet On-Line Vehicle System                          | 8       | efleetbase 100 vehicles Usage Fee 07/01/15-12/01/15                                   | 2016-01-29T00:00:00 | 1344     | 1.00       | 1344.00    | 
| 2016        | 465            | SAFELITE AUTO GLASS           | 4229 N RIVER RD          | KEIZER      | OR    | Vehicle Maintenance & Repair                            | 5       | Vehicle Glass Replacement & Repair                                                    | 2016-06-01T00:00:00 | 5000     | 1.00       | 5000.00    | 
| 2016        | 576            | ELITE CAR BATH                | 1863 PIONEER PKWY E #204 | SPRINGFIELD | OR    | Vehicle Maintenance & Repair                            | 5       | Vehicle Car Wash                                                                      | 2016-06-01T00:00:00 | 2000     | 1.00       | 2000.00    | 
| 2016        | 578            | POWER CHEVROLET               | 500 SW SUBLIMITY BLVD    | SUBLIMITY   | OR    | Vehicle Maintenance & Repairs                           | 5       | Vehicle Maintenance & Repair                                                          | 2016-06-01T00:00:00 | 5000     | 1.00       | 5000.00    | 
| 2016        | 580            | SKYLINE FORD                  | 2510 COMMERCIAL ST SE    | Salem       | OR    | Vehicle Repairs & Maintenance                           | 6       | Vehicle Maintenance & Repair                                                          | 2016-06-01T00:00:00 | 5000     | 1.00       | 5000.00    | 
```