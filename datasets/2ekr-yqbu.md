# Charitable Games Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/charitable-games-statistics) |
| Metadata | [Link](https://data.ct.gov/api/views/2ekr-yqbu) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2ekr-yqbu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2ekr-yqbu/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2ekr-yqbu |
| Name | Charitable Games Statistics |
| Attribution | CT Dept. of Consumer Protection |
| Category | Government |
| Tags | charitable games, bingo, sealed tickets, raffles and bazaars |
| Created | 2014-10-20T16:11:20Z |
| Publication Date | 2014-10-20T16:15:33Z |

## Description

Charitable Games Statistics

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                  | Data Type | Render Type |
| ======== | ============== | ===================================================== | ===================================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                           | Fiscal Year                                           | number    | text        |
| Yes      | numeric metric | bingo_gross_receipts                                  | Bingo Gross Receipts                                  | money     | money       |
| Yes      | numeric metric | bingo_net_profit_to_the_organization                  | Bingo Net Profit to the Organization                  | money     | money       |
| Yes      | numeric metric | bingo_general_fund_transfers                          | Bingo General Fund Transfers                          | money     | money       |
| Yes      | numeric metric | sealed_tickets_number_of_tickets                      | Sealed Tickets Number of tickets                      | number    | number      |
| Yes      | numeric metric | sealed_tickets_retail_value                           | Sealed Tickets Retail Value                           | money     | money       |
| Yes      | numeric metric | sealed_tickets_profit_to_organization                 | Sealed Tickets Profit to Organization                 | money     | money       |
| Yes      | numeric metric | sealed_tickets_general_fund_transfers                 | Sealed Tickets General Fund Transfers                 | money     | money       |
| Yes      | numeric metric | raffles_and_bazaars_gross_receipts                    | Raffles and Bazaars Gross Receipts                    | money     | money       |
| Yes      | numeric metric | raffles_and_bazaars_net_profit_to_the_organization    | Raffles and Bazaars Net Profit to the Organization    | money     | money       |
| Yes      | numeric metric | sheet_ticket_revenue                                  | SHEET TICKET REVENUE                                  | money     | money       |
| Yes      | numeric metric | las_vegas_nights_gross_receipts                       | Las Vegas Nights Gross Receipts                       | money     | money       |
| Yes      | numeric metric | las_vegas_nights_net_profit_to_the_organization       | Las Vegas Nights Net Profit to the Organization       | money     | money       |
| Yes      | numeric metric | total_charitable_games_gross_receipts                 | Total Charitable Games Gross Receipts                 | money     | money       |
| Yes      | numeric metric | total_charitable_games_net_profit_to_the_organization | Total Charitable Games Net Profit to the Organization | money     | money       |
| Yes      | numeric metric | total_charitable_games_general_fund_transfers         | Total Charitable Games General Fund Transfers         | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2ekr-yqbu d:1988-01-01T00:00:00.000Z m:sealed_tickets_number_of_tickets=12676800 m:raffles_and_bazaars_net_profit_to_the_organization=1872637 m:sealed_tickets_profit_to_organization=1638670 m:bingo_net_profit_to_the_organization=3000490 m:total_charitable_games_net_profit_to_the_organization=6561717 m:sealed_tickets_general_fund_transfers=450209 m:las_vegas_nights_net_profit_to_the_organization=49920 m:raffles_and_bazaars_gross_receipts=3319643 m:las_vegas_nights_gross_receipts=96686 m:total_charitable_games_general_fund_transfers=983337 m:bingo_gross_receipts=15255063 m:total_charitable_games_gross_receipts=23173936 m:bingo_general_fund_transfers=533128 m:sealed_tickets_retail_value=4502544

series e:2ekr-yqbu d:1989-01-01T00:00:00.000Z m:sealed_tickets_number_of_tickets=17439264 m:raffles_and_bazaars_net_profit_to_the_organization=8390785 m:sealed_tickets_profit_to_organization=1767779 m:bingo_net_profit_to_the_organization=6072923 m:total_charitable_games_net_profit_to_the_organization=16518512 m:sealed_tickets_general_fund_transfers=663252 m:las_vegas_nights_net_profit_to_the_organization=287025 m:raffles_and_bazaars_gross_receipts=15479428 m:las_vegas_nights_gross_receipts=575659 m:total_charitable_games_general_fund_transfers=1129305 m:bingo_gross_receipts=23999311 m:total_charitable_games_gross_receipts=46686918 m:bingo_general_fund_transfers=466053 m:sealed_tickets_retail_value=6632520

series e:2ekr-yqbu d:1990-01-01T00:00:00.000Z m:sealed_tickets_number_of_tickets=16405056 m:raffles_and_bazaars_net_profit_to_the_organization=10174288 m:sealed_tickets_profit_to_organization=1643934 m:bingo_net_profit_to_the_organization=6643093 m:total_charitable_games_net_profit_to_the_organization=18544934 m:sealed_tickets_general_fund_transfers=653813 m:las_vegas_nights_net_profit_to_the_organization=83619 m:raffles_and_bazaars_gross_receipts=18418354 m:las_vegas_nights_gross_receipts=287557 m:total_charitable_games_general_fund_transfers=1048127 m:bingo_gross_receipts=26364086 m:total_charitable_games_gross_receipts=51608125 m:bingo_general_fund_transfers=394314 m:sealed_tickets_retail_value=6538128
```

## Meta Commands

```ls
metric m:bingo_gross_receipts p:integer l:"Bingo Gross Receipts" t:dataTypeName=money

metric m:bingo_net_profit_to_the_organization p:integer l:"Bingo Net Profit to the Organization" t:dataTypeName=money

metric m:bingo_general_fund_transfers p:integer l:"Bingo General Fund Transfers" t:dataTypeName=money

metric m:sealed_tickets_number_of_tickets p:integer l:"Sealed Tickets Number of tickets" t:dataTypeName=number

metric m:sealed_tickets_retail_value p:integer l:"Sealed Tickets Retail Value" t:dataTypeName=money

metric m:sealed_tickets_profit_to_organization p:integer l:"Sealed Tickets Profit to Organization" t:dataTypeName=money

metric m:sealed_tickets_general_fund_transfers p:integer l:"Sealed Tickets General Fund Transfers" t:dataTypeName=money

metric m:raffles_and_bazaars_gross_receipts p:integer l:"Raffles and Bazaars Gross Receipts" t:dataTypeName=money

metric m:raffles_and_bazaars_net_profit_to_the_organization p:integer l:"Raffles and Bazaars Net Profit to the Organization" t:dataTypeName=money

metric m:sheet_ticket_revenue p:integer l:"SHEET TICKET REVENUE" t:dataTypeName=money

metric m:las_vegas_nights_gross_receipts p:integer l:"Las Vegas Nights Gross Receipts" t:dataTypeName=money

metric m:las_vegas_nights_net_profit_to_the_organization p:integer l:"Las Vegas Nights Net Profit to the Organization" t:dataTypeName=money

metric m:total_charitable_games_gross_receipts p:integer l:"Total Charitable Games Gross Receipts" t:dataTypeName=money

metric m:total_charitable_games_net_profit_to_the_organization p:integer l:"Total Charitable Games Net Profit to the Organization" t:dataTypeName=money

metric m:total_charitable_games_general_fund_transfers p:integer l:"Total Charitable Games General Fund Transfers" t:dataTypeName=money

entity e:2ekr-yqbu l:"Charitable Games Statistics" t:attribution="CT Dept. of Consumer Protection" t:url=https://data.ct.gov/api/views/2ekr-yqbu

property e:2ekr-yqbu t:meta.view v:id=2ekr-yqbu v:category=Government v:attributionLink=http://www.ct.gov/dcp/lib/dcp/pdf/gaming/charitable_games_stats.pdf v:averageRating=0 v:name="Charitable Games Statistics" v:attribution="CT Dept. of Consumer Protection"

property e:2ekr-yqbu t:meta.view.license v:name="Public Domain"

property e:2ekr-yqbu t:meta.view.owner v:id=ewkk-db5a v:screenName=WilliamR v:displayName=WilliamR

property e:2ekr-yqbu t:meta.view.tableauthor v:id=ewkk-db5a v:screenName=WilliamR v:roleName=editor v:displayName=WilliamR
```

## Top Records

```ls
| fiscal_year | bingo_gross_receipts | bingo_net_profit_to_the_organization | bingo_general_fund_transfers | sealed_tickets_number_of_tickets | sealed_tickets_retail_value | sealed_tickets_profit_to_organization | sealed_tickets_general_fund_transfers | raffles_and_bazaars_gross_receipts | raffles_and_bazaars_net_profit_to_the_organization | sheet_ticket_revenue | las_vegas_nights_gross_receipts | las_vegas_nights_net_profit_to_the_organization | total_charitable_games_gross_receipts | total_charitable_games_net_profit_to_the_organization | total_charitable_games_general_fund_transfers | 
| =========== | ==================== | ==================================== | ============================ | ================================ | =========================== | ===================================== | ===================================== | ================================== | ================================================== | ==================== | =============================== | =============================================== | ===================================== | ===================================================== | ============================================= | 
| 1988        | 15255063             | 3000490                              | 533128                       | 12676800                         | 4502544                     | 1638670                               | 450209                                | 3319643                            | 1872637                                            |                      | 96686                           | 49920                                           | 23173936                              | 6561717                                               | 983337                                        | 
| 1989        | 23999311             | 6072923                              | 466053                       | 17439264                         | 6632520                     | 1767779                               | 663252                                | 15479428                           | 8390785                                            |                      | 575659                          | 287025                                          | 46686918                              | 16518512                                              | 1129305                                       | 
| 1990        | 26364086             | 6643093                              | 394314                       | 16405056                         | 6538128                     | 1643934                               | 653813                                | 18418354                           | 10174288                                           |                      | 287557                          | 83619                                           | 51608125                              | 18544934                                              | 1048127                                       | 
| 1991        | 27933508             | 6687854                              | 397225                       | 19386929                         | 9296477                     | 2409137                               | 929656                                | 14725574                           | 8183805                                            |                      | 388561                          | 152062                                          | 52344120                              | 17432858                                              | 1326881                                       | 
| 1992        | 30490671             | 7359116                              | 434176                       | 19801146                         | 10658352                    | 2822482                               | 1065859                               | 16448454                           | 9582122                                            |                      | 438579                          | 191344                                          | 58036056                              | 19955064                                              | 1500035                                       | 
| 1993        | 32140787             | 7396394                              | 449963                       | 22494918                         | 12855959                    | 3306489                               | 1285968                               | 15166362                           | 9180821                                            |                      | 325086                          | 163614                                          | 60488194                              | 20047318                                              | 1735931                                       | 
| 1994        | 32674269             | 7175268                              | 445907                       | 21954199                         | 13598809                    | 3425952                               | 1359893                               | 13593120                           | 8840097                                            |                      | 319564                          | 175423                                          | 60185762                              | 19616740                                              | 1805800                                       | 
| 1995        | 34611016             | 7350321                              | 463400                       | 20626728                         | 12852430                    | 3254049                               | 1285257                               | 13683322                           | 8618901                                            |                      | 368734                          | 149167                                          | 61515502                              | 19372438                                              | 1748657                                       | 
| 1996        | 32577392             | 6543880                              | 421319                       | 19170155                         | 13023225                    | 3327542                               | 1302330                               | 12927635                           | 8234590                                            |                      | 298979                          | 168786                                          | 59333490                              | 18274798                                              | 1723649                                       | 
| 1997        | 32601305             | 6405709                              | 414018                       | 16516608                         | 10777485                    | 2815867                               | 1077754                               | 14837149                           | 9437659                                            |                      | 397946                          | 201000                                          | 58613885                              | 18328621                                              | 1491772                                       | 
```