# Contracts: Lottery: Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-lottery-fiscal-year-2011-9f46c) |
| Metadata | [Link](https://data.oregon.gov/api/views/dwi6-thje) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dwi6-thje/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dwi6-thje/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dwi6-thje |
| Name | Contracts: Lottery: Fiscal Year 2011 |
| Created | 2011-12-18T22:50:02Z |
| Publication Date | 2011-12-18T22:51:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | agency_number        | Agency Number        | text      | number      |
| Yes      | series tag     | agency_name          | Agency Name          | text      | text        |
| Yes      | series tag     | contract_description | Contract Description | text      | text        |
| Yes      | series tag     | contractor           | Contractor           | text      | text        |
| Yes      | time           | date_executed        | Date Executed        | date      | date        |
| Yes      | numeric metric | dollar_amount        | Dollar amount        | money     | money       |
```

## Time Field

```ls
Value = date_executed
Format & Zone = seconds
```

## Data Commands

```ls
series e:dwi6-thje d:2010-07-01T07:00:00.000Z t:contract_description="Use of a State Price Agreement to purchase 3 Chevrolet AWD vans." t:contractor="Hubbard            Chevrolet" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:dollar_amount=74277

series e:dwi6-thje d:2010-07-01T07:00:00.000Z t:contract_description="Use of a State Price Agreement to purchase 7 Ford cargo service vans." t:contractor="Northside            Ford" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:dollar_amount=137751

series e:dwi6-thje d:2010-07-01T07:00:00.000Z t:contract_description="Purchase of bins and racks for new 2011 model year vans." t:contractor="Pacific Truck         Colors" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:dollar_amount=26255
```

## Meta Commands

```ls
metric m:dollar_amount p:integer l:"Dollar amount" t:dataTypeName=money

entity e:dwi6-thje l:"Contracts: Lottery: Fiscal Year 2011" t:url=https://data.oregon.gov/api/views/dwi6-thje

property e:dwi6-thje t:meta.view v:id=dwi6-thje v:averageRating=0 v:name="Contracts: Lottery: Fiscal Year 2011"

property e:dwi6-thje t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:dwi6-thje t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name          | contract_description                                                                                             | contractor                        | date_executed | dollar_amount | 
| ============= | ==================== | ================================================================================================================ | ================================= | ============= | ============= | 
| 177000        | Oregon State Lottery | Use of a State Price Agreement to purchase 3 Chevrolet AWD vans.                                                 | Hubbard Chevrolet                 | 1277967600    | 74277         | 
| 177000        | Oregon State Lottery | Use of a State Price Agreement to purchase 7 Ford cargo service vans.                                            | Northside Ford                    | 1277967600    | 137751        | 
| 177000        | Oregon State Lottery | Purchase of bins and racks for new 2011 model year vans.                                                         | Pacific Truck Colors              | 1277967600    | 26255         | 
| 177000        | Oregon State Lottery | Work Order Contract 8391-96 Annual Strategic Planning Services                                                   | Borders Perrin & Norrander Inc.   | 1277967600    | 96000         | 
| 177000        | Oregon State Lottery | Purchase of 50 LCD monitors for IGT Trimline? and Game King? Video LotterySM Terminals.                          | International Gaming Technologies | 1278054000    | 65050         | 
| 177000        | Oregon State Lottery | Contract for a Biennial Security Review of the Lottery as required by Oregon Statute.                            | Delahanty Consulting              | 1278054000    | 185000        | 
| 177000        | Oregon State Lottery | Contract renewal for Megabucks? Jackpot outdoor bulletin space located on Hwy 217 in Tigard for a 3-year period. | LaMar                             | 1278745200    | 263432        | 
| 177000        | Oregon State Lottery | Contract for Advertising displays at the Portland Airport for a 1 year period.                                   | Alliance Airport Advertising      | 1279609200    | 123660        | 
| 177000        | Oregon State Lottery | Work Order Contract 8391-97 for Advertising Services for Oregon Wins Fall Campaign - Project #1                  | Borders Perrin & Norrander Inc.   | 1279609200    | 710105        | 
| 177000        | Oregon State Lottery | Work Order Contract 8391-95 for Annual Talent Renewal Fees                                                       | Borders Perrin & Norrander Inc.   | 1279782000    | 80000         | 
```