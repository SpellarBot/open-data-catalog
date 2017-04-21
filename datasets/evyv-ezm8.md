# Choose Maryland: Compare Metros - Economy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-metros-economy) |
| Metadata | [Link](https://data.maryland.gov/api/views/evyv-ezm8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/evyv-ezm8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/evyv-ezm8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | evyv-ezm8 |
| Name | Choose Maryland: Compare Metros - Economy |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, baltimore, metro, compare, economy, gross domestic product, gdp |
| Created | 2013-08-22T15:24:51Z |
| Publication Date | 2016-09-21T18:03:43Z |

## Description

Economic production - GDP

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                          | Data Type | Render Type |
| ======== | ============== | ========================================= | ============================================= | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                    | meta_data | meta_data   |
| Yes      | series tag     | metro                                     | Metro                                         | text      | text        |
| Yes      | numeric metric | gdp                                       | Gross Domestic Product ($ Millions)           | money     | money       |
| Yes      | numeric metric | gross_domestic_product_per_capita_dollars | Gross Domestic Product per Capita ($ Dollars) | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:evyv-ezm8 d:2016-09-21T18:03:25.000Z t:metro="Atlanta metro" m:gross_domestic_product_per_capita_dollars=53216 m:gdp=339203

series e:evyv-ezm8 d:2016-09-21T18:03:25.000Z t:metro="Austin, TX metro" m:gross_domestic_product_per_capita_dollars=55323 m:gdp=119949

series e:evyv-ezm8 d:2016-09-21T18:03:25.000Z t:metro="Baltimore metro" m:gross_domestic_product_per_capita_dollars=58041 m:gdp=181419
```

## Meta Commands

```ls
metric m:gdp p:integer l:"Gross Domestic Product ($ Millions)" t:dataTypeName=money

metric m:gross_domestic_product_per_capita_dollars p:integer l:"Gross Domestic Product per Capita ($ Dollars)" t:dataTypeName=money

entity e:evyv-ezm8 l:"Choose Maryland:  Compare Metros - Economy" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/evyv-ezm8

property e:evyv-ezm8 t:meta.view v:id=evyv-ezm8 v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Metros - Economy" v:attribution="Maryland Department of Commerce"

property e:evyv-ezm8 t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:evyv-ezm8 t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | metro               | gdp    | gross_domestic_product_per_capita_dollars | 
| =========== | =================== | ====== | ========================================= | 
| 1474481005  | Atlanta metro       | 339203 | 53216                                     | 
| 1474481005  | Austin, TX metro    | 119949 | 55323                                     | 
| 1474481005  | Baltimore metro     | 181419 | 58041                                     | 
| 1474481005  | Birmingham metro    | 64083  | 50174                                     | 
| 1474481005  | Boston metro        | 396549 | 74545                                     | 
| 1474481005  | Buffalo metro       | 56456  | 44054                                     | 
| 1474481005  | Charlotte metro     | 152447 | 55610                                     | 
| 1474481005  | Chicago metro       | 640656 | 59688                                     | 
| 1474481005  | Cincinnati metro    | 127057 | 52649                                     | 
| 1474481005  | Cleveland, OH metro | 128448 | 56013                                     | 
```