# 2015-Contracts: Lottery: Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-contracts-lottery-fiscal-year-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/bb5m-capg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bb5m-capg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bb5m-capg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bb5m-capg |
| Name | 2015-Contracts: Lottery: Fiscal Year 2015 |
| Category | Revenue & Expense |
| Tags | lottery contracts, lottery, oregon state lottery contracts 2014, 2014 |
| Created | 2016-01-01T04:13:08Z |
| Publication Date | 2016-01-01T04:18:55Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx#Lottery_Commission_-_Contract_Activity

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ============================================ | ============= | ============= |
| No       |                | fiscal_year                                | Fiscal Year                                  | number        | number        |
| Yes      | numeric metric | purchase_order                             | Purchase order                               | number        | number        |
| Yes      | series tag     | amendment_no                               | Amendment No                                 | text          | number        |
| Yes      | series tag     | detailed_contract_information_by_line_item | Detailed Contract Information (by line item) | text          | text          |
| No       |                | contract_executed                          | Contract executed                            | calendar_date | calendar_date |
| No       |                | contract_end                               | Contract end                                 | calendar_date | calendar_date |
| Yes      | time           | purchase_date                              | Purchase Date                                | calendar_date | calendar_date |
| Yes      | series tag     | type                                       | Type                                         | text          | text          |
| Yes      | series tag     | vendor                                     | Vendor                                       | text          | text          |
| Yes      | numeric metric | total_amount                               | Total Amount                                 | money         | money         |
```

## Time Field

```ls
Value = purchase_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_executed,contract_end,fiscal_year
```

## Data Commands

```ls
series e:bb5m-capg d:2015-12-31T20:13:10.000Z t:vendor="USF REDDAWAY TRUCKLINE" t:detailed_contract_information_by_line_item="Misc Shipping Projects - FY16" t:type=BLGD m:total_amount=10000 m:purchase_order=4315

series e:bb5m-capg d:2015-12-31T20:13:10.000Z t:vendor="MARSHALL SUNSHINE INC." t:detailed_contract_information_by_line_item="Blanket PO FY16" t:type=BLSV m:total_amount=1500 m:purchase_order=194

series e:bb5m-capg d:2015-12-31T20:13:10.000Z t:vendor="MARSHALL SUNSHINE INC." t:detailed_contract_information_by_line_item="Vehicle Maintenance & Repairs" t:type=BLSV m:total_amount=2500
```

## Meta Commands

```ls
metric m:purchase_order p:integer l:"Purchase order" t:dataTypeName=number

metric m:total_amount p:double l:"Total Amount" t:dataTypeName=money

entity e:bb5m-capg l:"2015-Contracts: Lottery: Fiscal Year 2015" t:url=https://data.oregon.gov/api/views/bb5m-capg

property e:bb5m-capg t:meta.view v:id=bb5m-capg v:category="Revenue & Expense" v:averageRating=0 v:name="2015-Contracts: Lottery: Fiscal Year 2015"

property e:bb5m-capg t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:bb5m-capg t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | purchase_order | amendment_no | detailed_contract_information_by_line_item             | contract_executed   | contract_end        | purchase_date       | type | vendor                 | total_amount | 
| =========== | ============== | ============ | ====================================================== | =================== | =================== | =================== | ==== | ====================== | ============ | 
| 2015        |                |              |                                                        |                     |                     |                     |      |                        |              | 
| 2015        | 4315           |              | Misc Shipping Projects - FY16                          | 2015-06-25T00:00:00 | 2016-06-30T00:00:00 |                     | BLGD | USF REDDAWAY TRUCKLINE | 10000.00     | 
| 2015        | 194            |              | Blanket PO FY16                                        | 2015-06-24T00:00:00 | 2016-06-30T00:00:00 |                     | BLSV | MARSHALL SUNSHINE INC. | 1500.00      | 
| 2015        |                |              | Vehicle Maintenance & Repairs                          | 2014-07-22T00:00:00 | 2015-06-30T00:00:00 |                     | BLSV | MARSHALL SUNSHINE INC. | 2500.00      | 
| 2015        | 4456           |              | Verizon Mobile Device Services for FY15                | 2014-07-23T00:00:00 | 2015-06-30T00:00:00 |                     | BLSV | VERIZON WIRELESS       | 174000.00    | 
| 2015        | 14838          |              | Blanket PO FY16                                        | 2015-06-30T00:00:00 | 2016-06-30T00:00:00 |                     | BLSV | LES SCHWAB TIRE CENTER | 50000.00     | 
| 2015        |                |              | Vehicle Maintenance & Repair                           | 2014-07-10T00:00:00 | 2015-06-30T00:00:00 |                     | BLSV | LES SCHWAB TIRE CENTER | 75000.00     | 
| 2015        | 14845          |              | Blanket PO FY16                                        | 2015-06-24T00:00:00 | 2016-06-30T00:00:00 |                     | BLSV | WET WILLY'S CAR WASH   | 500.00       | 
| 2015        |                |              | Vehicle Maintenance                                    | 2014-07-10T00:00:00 | 2015-06-30T00:00:00 |                     | BLSV | WET WILLY'S CAR WASH   | 1500.00      | 
| 2015        | 5675           |              | April Invoice for IRS - IVES - Tax Account Transcripts |                     |                     | 2015-05-18T00:00:00 | BLSV | IRS - IVES TRANSCRIPTS | 1068.00      | 
```