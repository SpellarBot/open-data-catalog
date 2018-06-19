# Choose Maryland: Compare States - Economy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-economy) |
| Metadata | [Link](https://data.maryland.gov/api/views/gv8w-7mdg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/gv8w-7mdg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/gv8w-7mdg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | gv8w-7mdg |
| Name | Choose Maryland: Compare States - Economy |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, state, compare, economy, gdp, gross, domestic, product |
| Created | 2013-11-18T16:24:11Z |
| Publication Date | 2017-01-11T14:23:59Z |

## Description

Economic production - Gross Domestic Product.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                          | Data Type | Render Type |
| ======== | ============== | ================================= | ============================================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                                    | meta_data | meta_data   |
| Yes      | series tag     | state                             | State                                         | text      | text        |
| Yes      | numeric metric | gross_domestic_product_millions   | Gross Domestic Product ($ Millions)           | money     | money       |
| Yes      | numeric metric | gross_domestic_product_per_capita | Gross Domestic Product per Capita ($ Dollars) | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gv8w-7mdg d:2017-01-11T14:23:41.000Z t:state=Alabama m:gross_domestic_product_millions=199656 m:gross_domestic_product_per_capita=36750

series e:gv8w-7mdg d:2017-01-11T14:23:41.000Z t:state=Alaska m:gross_domestic_product_millions=52747 m:gross_domestic_product_per_capita=66835

series e:gv8w-7mdg d:2017-01-11T14:23:41.000Z t:state=Arizona m:gross_domestic_product_millions=290903 m:gross_domestic_product_per_capita=38276
```

## Meta Commands

```ls
metric m:gross_domestic_product_millions p:integer l:"Gross Domestic Product ($ Millions)" t:dataTypeName=money

metric m:gross_domestic_product_per_capita p:integer l:"Gross Domestic Product per Capita ($ Dollars)" t:dataTypeName=money

entity e:gv8w-7mdg l:"Choose Maryland:  Compare States - Economy" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/gv8w-7mdg

property e:gv8w-7mdg t:meta.view v:id=gv8w-7mdg v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Economy" v:attribution="Maryland Department of Commerce"

property e:gv8w-7mdg t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:gv8w-7mdg t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | gross_domestic_product_millions | gross_domestic_product_per_capita | 
| =========== | =========== | =============================== | ================================= | 
| 1484144621  | Alabama     | 199656                          | 36750                             | 
| 1484144621  | Alaska      | 52747                           | 66835                             | 
| 1484144621  | Arizona     | 290903                          | 38276                             | 
| 1484144621  | Arkansas    | 118907                          | 36259                             | 
| 1484144621  | California  | 2481348                         | 56851                             | 
| 1484144621  | Colorado    | 313748                          | 52558                             | 
| 1484144621  | Connecticut | 252930                          | 62800                             | 
| 1484144621  | Delaware    | 68724                           | 63783                             | 
| 1484144621  | Florida     | 888087                          | 39218                             | 
| 1484144621  | Georgia     | 497944                          | 43555                             | 
```