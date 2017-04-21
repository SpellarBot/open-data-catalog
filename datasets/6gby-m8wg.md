# Contracts: Lottery: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-lottery-fiscal-year-2013-4f55c) |
| Metadata | [Link](https://data.oregon.gov/api/views/6gby-m8wg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6gby-m8wg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6gby-m8wg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6gby-m8wg |
| Name | Contracts: Lottery: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | lottery contracts, lottery, oregon state lottery contracts |
| Created | 2013-12-03T17:55:05Z |
| Publication Date | 2013-12-03T18:06:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | contract_number            | Contract Number            | text          | number        |
| Yes      | series tag     | amendment_number           | Amendment Number           | text          | text          |
| Yes      | series tag     | contract_description       | Contract Description       | text          | text          |
| Yes      | series tag     | award_type                 | Award Type                 | text          | text          |
| Yes      | series tag     | contractor_name            | Contractor Name            | text          | text          |
| Yes      | series tag     | zipcode                    | Zipcode                    | text          | number        |
| Yes      | time           | contract_executed_datetime | Contract Executed DateTime | calendar_date | calendar_date |
| No       |                | contract_end_datetime      | Contract End DateTime      | calendar_date | calendar_date |
| Yes      | series tag     | original_contract_amount   | Original Contract Amount   | text          | text          |
| Yes      | numeric metric | amendment_amount           | Amendment Amount           | number        | number        |
| Yes      | series tag     | total_contract_amount      | Total Contract Amount      | text          | text          |
```

## Time Field

```ls
Value = contract_executed_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_datetime
```

## Data Commands

```ls
series e:6gby-m8wg d:2013-01-11T00:00:00.000Z t:total_contract_amount="* 11,560.00" t:original_contract_amount="* 5,780.00" t:contract_description="Business continuity planning software annual maint/support" t:contractor_name="eBRP SOLUTIONS NETWORK INC" t:contract_number=436 t:award_type=SERVICES m:amendment_amount=0

series e:6gby-m8wg d:2012-11-28T00:00:00.000Z t:total_contract_amount="* 117,624.00" t:original_contract_amount="* 117,624.00" t:contract_description="Scratch-it #983 Pure Crossword" t:contractor_name="POLLARD BANKNOTE LMTD PARTNERSHIP" t:contract_number=1833 t:award_type=GOODS m:amendment_amount=0

series e:6gby-m8wg d:2012-09-19T00:00:00.000Z t:total_contract_amount="* 106,271.00" t:original_contract_amount="* 106,271.00" t:contract_description="Scrtach-it  #981 Caveman Crossword" t:contractor_name="POLLARD BANKNOTE LMTD PARTNERSHIP" t:contract_number=1834 t:award_type=SERVICES m:amendment_amount=0
```

## Meta Commands

```ls
metric m:amendment_amount p:float l:"Amendment Amount" t:dataTypeName=number

entity e:6gby-m8wg l:"Contracts: Lottery: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/6gby-m8wg

property e:6gby-m8wg t:meta.view v:id=6gby-m8wg v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Lottery: Fiscal Year 2013"

property e:6gby-m8wg t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6gby-m8wg t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_number | amendment_number | contract_description                                                                   | award_type | contractor_name                   | zipcode | contract_executed_datetime | contract_end_datetime | original_contract_amount | amendment_amount | total_contract_amount | 
| =============== | ================ | ====================================================================================== | ========== | ================================= | ======= | ========================== | ===================== | ======================== | ================ | ===================== | 
| 436             |                  | Business continuity planning software annual maint/support                             | SERVICES   | eBRP SOLUTIONS NETWORK INC        |         | 2013-01-11T00:00:00        | 2014-01-07T00:00:00   | * 5,780.00               | 0.0              | * 11,560.00           | 
| 1641            | 001641(1)        | Amendment #1 to include 1,500 Trail Blazers coupons for Lottery promotional give-aways |            |                                   |         |                            |                       |                          |                  |                       | 
| 1833            |                  | Scratch-it #983 Pure Crossword                                                         | GOODS      | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2012-11-28T00:00:00        | 2014-04-30T00:00:00   | * 117,624.00             | 0.0              | * 117,624.00          | 
| 1834            |                  | Scrtach-it #981 Caveman Crossword                                                      | SERVICES   | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2012-09-19T00:00:00        | 2014-03-19T00:00:00   | * 106,271.00             | 0.0              | * 106,271.00          | 
| 1835            |                  | Scratch-it #980 Crossword Trail                                                        | SERVICES   | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2012-09-19T00:00:00        | 2014-03-19T00:00:00   | * 106,271.00             | 0.0              | * 106,271.00          | 
| 1836            |                  | Scratch-it #982 Cruisin Crossword                                                      | GOODS      | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2012-11-28T00:00:00        | 2014-05-07T00:00:00   | * 134,915.00             | 0.0              | * 134,915.00          | 
| 1859            |                  | Hash File costs for Scratch- it Games 847, 858, 861, 867, 937, 950, 951 and 953        | SERVICES   | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2012-11-14T00:00:00        | 2013-11-14T00:00:00   | * 60,000.00              | 0.0              | * 60,000.00           | 
| 1938            |                  | Inventory replenishment, VLT spare parts                                               | GOODS      | GAMESMAN LTD                      |         | 2012-12-26T00:00:00        |                       | * 5,194.25               | 0.0              | * 5,194.25            | 
| 1978            |                  | Scratch-it Tickets Game 987 Doubler Dollar Fortune                                     | GOODS      | POLLARD BANKNOTE LMTD PARTNERSHIP |         | 2013-01-09T00:00:00        |                       | * 92,974.00              | 0.0              | * 92,974.00           | 
| 2053            |                  | Spielo VLT spare parts                                                                 | GOODS      | SPIELO INTERNATIONAL CANADA ULC   |         | 2013-01-28T00:00:00        |                       | * 35,120.80              | 0.0              | * 35,120.80           | 
```