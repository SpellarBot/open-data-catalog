# Oregon Prod Invest Fund ( OPIF) Auction Results ? Composite Report ( FY 2017 - 2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-prod-invest-fund-opif-auction-results-composite-report-fy-2017-2013) |
| Metadata | [Link](https://data.oregon.gov/api/views/kijp-9nsu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kijp-9nsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kijp-9nsu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kijp-9nsu |
| Name | Oregon Prod Invest Fund ( OPIF) Auction Results ? Composite Report ( FY 2017 - 2013) |
| Category | Revenue & Expense |
| Tags | oregon production investment fund, opif, investment fund, oregon investment fund; film and television; governor's office of film and television, composite report, fy 2017-2013 |
| Created | 2016-12-01T04:57:23Z |
| Publication Date | 2016-12-01T06:21:05Z |

## Description

For more information on this program and economic development go to: http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | fiscal_year          | Fiscal Year          | text      | text        |
| Yes      | series tag     | business_name        | Business Name        | text      | text        |
| Yes      | series tag     | first_name           | First Name           | text      | text        |
| Yes      | series tag     | last_name            | Last Name            | text      | text        |
| No       |                | address              | Address              | text      | text        |
| Yes      | series tag     | city                 | City                 | text      | text        |
| Yes      | series tag     | state                | State                | text      | text        |
| Yes      | series tag     | zip_code             | Zip Code             | text      | text        |
| Yes      | numeric metric | amt_paid             | Amt Paid             | money     | money       |
| Yes      | numeric metric | credit_amt           | Credit Amt           | money     | money       |
| Yes      | series tag     | outcomes             | Outcomes             | text      | text        |
| Yes      | series tag     | taxpayer_requirement | Taxpayer requirement | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:kijp-9nsu d:2017-01-01T00:00:00.000Z t:business_name="Excel Finishing" t:fiscal_year=2016-2017 t:outcomes="Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production." t:first_name=Joe t:zip_code=97045 t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Robinson t:city="Oregon City" m:amt_paid=15480 m:credit_amt=15000

series e:kijp-9nsu d:2017-01-01T00:00:00.000Z t:business_name="Jason Waxberg P.C." t:fiscal_year=2016-2017 t:outcomes="Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production." t:first_name=Jason t:zip_code=97215 t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Waxberg t:city=Portland m:amt_paid=20400 m:credit_amt=20000

series e:kijp-9nsu d:2017-01-01T00:00:00.000Z t:business_name="Stein Oil Company Inc." t:fiscal_year=2016-2017 t:outcomes="Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production." t:first_name=George t:zip_code=97035 t:taxpayer_requirement="Taxpayer filled out application and submitted application for credit." t:state=OR t:last_name=Hughes t:city="Lake Oswego" m:amt_paid=309600 m:credit_amt=300000
```

## Meta Commands

```ls
metric m:amt_paid p:double l:"Amt Paid" t:dataTypeName=money

metric m:credit_amt p:double l:"Credit Amt" t:dataTypeName=money

entity e:kijp-9nsu l:"Oregon Prod Invest Fund ( OPIF) Auction Results ? Composite Report ( FY 2017 - 2013)" t:url=https://data.oregon.gov/api/views/kijp-9nsu

property e:kijp-9nsu t:meta.view v:id=kijp-9nsu v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon Prod Invest Fund ( OPIF) Auction Results ? Composite Report ( FY 2017 - 2013)"

property e:kijp-9nsu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kijp-9nsu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | business_name          | first_name | last_name | address                     | city         | state | zip_code | amt_paid | credit_amt | outcomes                                                                                                                                   | taxpayer_requirement                                                  | 
| =========== | ====================== | ========== | ========= | =========================== | ============ | ===== | ======== | ======== | ========== | ========================================================================================================================================== | ===================================================================== | 
| 2016-2017   | Excel Finishing        | Joe        | Robinson  | 1765 Red Soils Ct, Ste. 105 | Oregon City  | OR    | 97045    | 15480    | 15000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   | Jason Waxberg P.C.     | Jason      | Waxberg   | 1715 SE 51st Ave            | Portland     | OR    | 97215    | 20400    | 20000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   | Stein Oil Company Inc. | George     | Hughes    | 4900 Meadows Rd, Suite 200  | Lake Oswego  | OR    | 97035    | 309600   | 300000.00  | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | Natalie    | Crenshaw  | 4900 Meadows Rd - Suite 200 | Lake Oswego  | OR    | 97035    | 8240     | 8000.00    | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | Mark       | Ace       | 1314 NW Irving St Apt 607   | Portland     | OR    | 97209    | 5200     | 5000.00    | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | Jason      | Adams     | 11414 NE Norwood Loop       | Happy Valley | OR    | 97086    | 25250    | 25000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | Andrew     | Aebi      | 15845 SW Cardinal Loop      | Beaverton    | OR    | 97007    | 26468    | 26000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | James      | Alder     | 13883 NW Hartung Ct         | Portland     | OR    | 97229    | 10540    | 10000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | James      | Alder     | 43883 NW Hartung Ct         | Portland     | OR    | 97229    | 10420    | 10000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
| 2016-2017   |                        | Mark       | Allen     | 17195 SW Arbutus Drive      | Beaverton    | OR    | 97007    | 15750    | 15000.00   | Taxpayer received an Oregon state credit and enough money was raised in OPIF to recruit a record amount of film and television production. | Taxpayer filled out application and submitted application for credit. | 
```