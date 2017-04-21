# 2012 Retail Sales By Town ALL NAICS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-retail-sales-by-town-all-naics) |
| Metadata | [Link](https://data.ct.gov/api/views/hyim-e6nq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/hyim-e6nq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/hyim-e6nq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | hyim-e6nq |
| Name | 2012 Retail Sales By Town ALL NAICS |
| Attribution | Department of Revenue Services |
| Category | Business |
| Tags | sales tax, retail, sales, tax |
| Created | 2014-03-21T19:00:55Z |
| Publication Date | 2014-03-21T19:09:00Z |

## Description

Retail Sales by Town for all NAICS Retail Sectors
* Please note that retailers with more than one establishment usually report all of their sales and use taxes from their primary location; therefore the amounts for various towns may not reflect actual business activity

** Total Tax Due includes some tax amounts at the 6% rate from returns filed on cash basis. Sales and Use tax data at the 9.35% rate applicable to short-term rentals or leasing of motor vehicles are not included to comply with disclosure requirements.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                          | Data Type | Render Type |
| ======== | ============== | ======================================== | ============================================= | ========= | =========== |
| Yes      | series tag     | municipality                             | Municipality                                  | text      | text        |
| Yes      | numeric metric | number_of_taxpayers                      | Number of Taxpayers                           | number    | number      |
| Yes      | numeric metric | total_retail_sales_of_goods              | Total Retail Sales of Goods                   | money     | money       |
| Yes      | numeric metric | total_tax_due_excluding_tax_at_9_35_rate | Total Tax Due **(Excluding Tax at 9.35% Rate) | money     | money       |
| Yes      | numeric metric | tax_due_at_6_35                          | Tax Due At 6.35%                              | money     | money       |
| Yes      | numeric metric | tax_due_at_7                             | Tax Due at 7%                                 | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hyim-e6nq d:2012-01-01T00:00:00.000Z t:municipality="ANDOVER (001)" m:tax_due_at_6_35=427872 m:total_tax_due_excluding_tax_at_9_35_rate=428026 m:tax_due_at_7=59 m:number_of_taxpayers=127 m:total_retail_sales_of_goods=5529457

series e:hyim-e6nq d:2012-01-01T00:00:00.000Z t:municipality="ANSONIA (002)" m:tax_due_at_6_35=3813289 m:total_tax_due_excluding_tax_at_9_35_rate=3817640 m:tax_due_at_7=2042 m:number_of_taxpayers=402 m:total_retail_sales_of_goods=89228175

series e:hyim-e6nq d:2012-01-01T00:00:00.000Z t:municipality="ASHFORD (003)" m:tax_due_at_6_35=654175 m:total_tax_due_excluding_tax_at_9_35_rate=659952 m:tax_due_at_7=5653 m:number_of_taxpayers=166 m:total_retail_sales_of_goods=12598684
```

## Meta Commands

```ls
metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

metric m:total_retail_sales_of_goods p:long l:"Total Retail Sales of Goods" t:dataTypeName=money

metric m:total_tax_due_excluding_tax_at_9_35_rate p:long l:"Total Tax Due **(Excluding Tax at 9.35% Rate)" t:dataTypeName=money

metric m:tax_due_at_6_35 p:long l:"Tax Due At 6.35%" t:dataTypeName=money

metric m:tax_due_at_7 p:integer l:"Tax Due at 7%" t:dataTypeName=money

entity e:hyim-e6nq l:"2012 Retail Sales By Town ALL NAICS" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/hyim-e6nq

property e:hyim-e6nq t:meta.view v:id=hyim-e6nq v:category=Business v:averageRating=0 v:name="2012 Retail Sales By Town ALL NAICS" v:attribution="Department of Revenue Services"

property e:hyim-e6nq t:meta.view.license v:name="Public Domain"

property e:hyim-e6nq t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:hyim-e6nq t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality       | number_of_taxpayers | total_retail_sales_of_goods | total_tax_due_excluding_tax_at_9_35_rate | tax_due_at_6_35 | tax_due_at_7 | 
| ================== | =================== | =========================== | ======================================== | =============== | ============ | 
| ANDOVER (001)      | 127                 | 5529457                     | 428026                                   | 427872          | 59           | 
| ANSONIA (002)      | 402                 | 89228175                    | 3817640                                  | 3813289         | 2042         | 
| ASHFORD (003)      | 166                 | 12598684                    | 659952                                   | 654175          | 5653         | 
| AVON (004)         | 739                 | 205383841                   | 8690891                                  | 8575388         | 113441       | 
| BARKHAMSTED (005)  | 174                 | 30403443                    | 695373                                   | 694846          | 0            | 
| BEACON FALLS (006) | 185                 | 35260220                    | 1265745                                  | 1264891         | 0            | 
| BERLIN (007)       | 939                 | 985677506                   | 61155725                                 | 61085854        | 65998        | 
| BETHANY (008)      | 231                 | 27887623                    | 1049597                                  | 1048503         | 0            | 
| BETHEL (009)       | 787                 | 231170096                   | 8012791                                  | 7968305         | 36095        | 
| BETHLEHEM (010)    | 237                 | 29410346                    | 1131629                                  | 1130744         | 0            | 
```