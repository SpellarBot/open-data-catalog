# 2011 Retail Sales By Town All NAICS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-retail-sales-by-town-all-naics) |
| Metadata | [Link](https://data.ct.gov/api/views/i2kw-ntg2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/i2kw-ntg2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/i2kw-ntg2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | i2kw-ntg2 |
| Name | 2011 Retail Sales By Town All NAICS |
| Attribution | Department of Revenue Services |
| Category | Business |
| Tags | taxe, retail sales, revenue |
| Created | 2014-03-21T19:09:54Z |
| Publication Date | 2014-05-12T14:44:20Z |

## Description

Retail sales Town for all NAICS sectors, Calendar Year 2011

* Please note that retailers with more than one establishment usually report all of their sales and use taxes from their primary location; therefore the amounts for various towns may not reflect actual business activity.

** Total Tax Due includes some tax amounts at the 6% rate from returns filed on cash basis. Sales and Use tax data at the 9.35% rate applicable to short-term rentals or leasing of motor vehicles are not included to comply with disclosure requirements.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | municipality                             | Municipality                               | text      | text        |
| Yes      | numeric metric | number_of_taxpayers                      | Number of Taxpayers                        | number    | number      |
| Yes      | numeric metric | total_retail_sales_of_goods              | Total Retail Sales of Goods                | money     | money       |
| Yes      | numeric metric | total_tax_due_excluding_tax_at_9_35_rate | Total Tax Due(Excluding Tax at 9.35% Rate) | money     | money       |
| Yes      | numeric metric | tax_due_at_6                             | Tax Due At 6%                              | money     | money       |
| Yes      | numeric metric | tax_due_at_6_35                          | Tax Due At 6.35%                           | money     | money       |
| Yes      | numeric metric | tax_due_at_7                             | Tax Due at 7%                              | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i2kw-ntg2 d:2011-01-01T00:00:00.000Z t:municipality="ANDOVER (001)" m:tax_due_at_6_35=275623 m:total_tax_due_excluding_tax_at_9_35_rate=502250 m:tax_due_at_6=226620 m:tax_due_at_7=7 m:number_of_taxpayers=139 m:total_retail_sales_of_goods=6435052

series e:i2kw-ntg2 d:2011-01-01T00:00:00.000Z t:municipality="ANSONIA (002)" m:tax_due_at_6_35=1811516 m:total_tax_due_excluding_tax_at_9_35_rate=3434137 m:tax_due_at_6=1616908 m:tax_due_at_7=5712 m:number_of_taxpayers=440 m:total_retail_sales_of_goods=82252912

series e:i2kw-ntg2 d:2011-01-01T00:00:00.000Z t:municipality="ASHFORD (003)" m:tax_due_at_6_35=409071 m:total_tax_due_excluding_tax_at_9_35_rate=712079 m:tax_due_at_6=302853 m:tax_due_at_7=155 m:number_of_taxpayers=186 m:total_retail_sales_of_goods=12825806
```

## Meta Commands

```ls
metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

metric m:total_retail_sales_of_goods p:long l:"Total Retail Sales of Goods" t:dataTypeName=money

metric m:total_tax_due_excluding_tax_at_9_35_rate p:long l:"Total Tax Due(Excluding Tax at 9.35% Rate)" t:dataTypeName=money

metric m:tax_due_at_6 p:integer l:"Tax Due At 6%" t:dataTypeName=money

metric m:tax_due_at_6_35 p:integer l:"Tax Due At 6.35%" t:dataTypeName=money

metric m:tax_due_at_7 p:integer l:"Tax Due at 7%" t:dataTypeName=money

entity e:i2kw-ntg2 l:"2011 Retail Sales By Town All NAICS" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/i2kw-ntg2

property e:i2kw-ntg2 t:meta.view v:id=i2kw-ntg2 v:category=Business v:averageRating=0 v:name="2011 Retail Sales By Town All NAICS" v:attribution="Department of Revenue Services"

property e:i2kw-ntg2 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:i2kw-ntg2 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality       | number_of_taxpayers | total_retail_sales_of_goods | total_tax_due_excluding_tax_at_9_35_rate | tax_due_at_6 | tax_due_at_6_35 | tax_due_at_7 | 
| ================== | =================== | =========================== | ======================================== | ============ | =============== | ============ | 
| ANDOVER (001)      | 139                 | 6435052                     | 502250                                   | 226620       | 275623          | 7            | 
| ANSONIA (002)      | 440                 | 82252912                    | 3434137                                  | 1616908      | 1811516         | 5712         | 
| ASHFORD (003)      | 186                 | 12825806                    | 712079                                   | 302853       | 409071          | 155          | 
| AVON (004)         | 797                 | 190254403                   | 7972169                                  | 3738357      | 4182282         | 51530        | 
| BARKHAMSTED (005)  | 199                 | 25611177                    | 661448                                   | 288886       | 372559          | 3            | 
| BEACON FALLS (006) | 207                 | 37004739                    | 996706                                   | 455361       | 541337          | 7            | 
| BERLIN (007)       | 981                 | 1063047358                  | 62482700                                 | 30735233     | 31744409        | 3059         | 
| BETHANY (008)      | 259                 | 28478567                    | 959102                                   | 485975       | 473022          | 105          | 
| BETHEL (009)       | 858                 | 229410031                   | 7712726                                  | 3654087      | 4040299         | 18340        | 
| BETHLEHEM (010)    | 264                 | 21657031                    | 932307                                   | 435820       | 496487          | 0            | 
```