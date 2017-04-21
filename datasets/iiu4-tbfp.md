# 2013 Retail Sales By Town ALL NAICS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-retail-sales-by-town-all-naics) |
| Metadata | [Link](https://data.ct.gov/api/views/iiu4-tbfp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/iiu4-tbfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/iiu4-tbfp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | iiu4-tbfp |
| Name | 2013 Retail Sales By Town ALL NAICS |
| Attribution | Department of Revenue Services |
| Category | Business |
| Tags | sales tax, retail, sales, tax |
| Created | 2015-06-19T14:16:18Z |
| Publication Date | 2015-06-19T14:32:56Z |

## Description

Retail Sales by Town for all NAICS Retail Sectors * Please note that retailers with more than one establishment usually report all of their sales and use taxes from their primary location; therefore the amounts for various towns may not reflect actual business activity ** Total Tax Due includes some tax amounts at the 6% rate from returns filed on cash basis. Sales and Use tax data at the 9.35% rate applicable to short-term rentals or leasing of motor vehicles are not included to comply with disclosure requirements

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iiu4-tbfp d:2013-01-01T00:00:00.000Z t:municipality="ANDOVER (001)" m:tax_due_at_6_35=471171 m:total_tax_due_excluding_tax_at_9_35_rate=471171 m:tax_due_at_7=0 m:number_of_taxpayers=135 m:total_retail_sales_of_goods=6288391

series e:iiu4-tbfp d:2013-01-01T00:00:00.000Z t:municipality="ANSONIA (002)" m:tax_due_at_6_35=4096856 m:total_tax_due_excluding_tax_at_9_35_rate=4101341 m:tax_due_at_7=4485 m:number_of_taxpayers=430 m:total_retail_sales_of_goods=95989113

series e:iiu4-tbfp d:2013-01-01T00:00:00.000Z t:municipality="ASHFORD (003)" m:tax_due_at_6_35=701875 m:total_tax_due_excluding_tax_at_9_35_rate=701988 m:tax_due_at_7=113 m:number_of_taxpayers=183 m:total_retail_sales_of_goods=14484094
```

## Meta Commands

```ls
metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

metric m:total_retail_sales_of_goods p:long l:"Total Retail Sales of Goods" t:dataTypeName=money

metric m:total_tax_due_excluding_tax_at_9_35_rate p:long l:"Total Tax Due **(Excluding Tax at 9.35% Rate)" t:dataTypeName=money

metric m:tax_due_at_6_35 p:long l:"Tax Due At 6.35%" t:dataTypeName=money

metric m:tax_due_at_7 p:integer l:"Tax Due at 7%" t:dataTypeName=money

entity e:iiu4-tbfp l:"2013 Retail Sales By Town ALL NAICS" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/iiu4-tbfp

property e:iiu4-tbfp t:meta.view v:id=iiu4-tbfp v:category=Business v:attributionLink="http://www.ct.gov/drs/cwp/view.asp?a=1448&q=318442" v:averageRating=0 v:name="2013 Retail Sales By Town ALL NAICS" v:attribution="Department of Revenue Services"

property e:iiu4-tbfp t:meta.view.license v:name="Public Domain"

property e:iiu4-tbfp t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:iiu4-tbfp t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality       | number_of_taxpayers | total_retail_sales_of_goods | total_tax_due_excluding_tax_at_9_35_rate | tax_due_at_6_35 | tax_due_at_7 | 
| ================== | =================== | =========================== | ======================================== | =============== | ============ | 
| ANDOVER (001)      | 135                 | 6288391                     | 471171                                   | 471171          | 0            | 
| ANSONIA (002)      | 430                 | 95989113                    | 4101341                                  | 4096856         | 4485         | 
| ASHFORD (003)      | 183                 | 14484094                    | 701988                                   | 701875          | 113          | 
| AVON (004)         | 795                 | 191577625                   | 9794246                                  | 9684935         | 109311       | 
| BARKHAMSTED (005)  | 186                 | 19730315                    | 711695                                   | 711695          | 0            | 
| BEACON FALLS (006) | 205                 | 36325590                    | 1239856                                  | 1239856         | 0            | 
| BERLIN (007)       | 1007                | 1022358574                  | 60430929                                 | 60348459        | 82469        | 
| BETHANY (008)      | 258                 | 29836686                    | 1049692                                  | 1049673         | 19           | 
| BETHEL (009)       | 863                 | 352355278                   | 9396696                                  | 9359106         | 37590        | 
| BETHLEHEM (010)    | 249                 | 21891068                    | 1044001                                  | 1044001         | 0            | 
```