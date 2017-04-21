# Choose Maryland: Compare Counties - Quality Of Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-quality-of-life) |
| Metadata | [Link](https://data.maryland.gov/api/views/dyym-bjv4) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/dyym-bjv4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/dyym-bjv4/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | dyym-bjv4 |
| Name | Choose Maryland: Compare Counties - Quality Of Life |
| Attribution | Maryland Department of Commerce |
| Category | Housing |
| Tags | maryland, county, compare, cost of living, housing, price |
| Created | 2013-08-23T18:26:57Z |
| Publication Date | 2017-02-01T20:19:57Z |

## Description

Key quality of life indicators - cost index, housing.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                                     | Data Type | Render Type |
| ======== | ============== | ====================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at                               | meta_data | meta_data   |
| Yes      | series tag     | county                 | County                                   | text      | text        |
| Yes      | numeric metric | cost_of_living_index   | Cost of Living Index                     | number    | number      |
| Yes      | numeric metric | avg_sale_price_home    | Average Sale Price of a Home ($ Dollars) | money     | money       |
| Yes      | numeric metric | median_sale_price_home | Median Sale Price of a Home ($ Dollars)  | money     | money       |
| Yes      | numeric metric | housing_units_sold     | Number of Housing Units Sold             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dyym-bjv4 d:2017-02-01T20:18:58.000Z t:county="Allegany County" m:median_sale_price_home=80543 m:housing_units_sold=575 m:avg_sale_price_home=93500 m:cost_of_living_index=86.7

series e:dyym-bjv4 d:2017-02-01T20:18:58.000Z t:county="Anne Arundel County" m:median_sale_price_home=308382 m:housing_units_sold=8770 m:avg_sale_price_home=361780 m:cost_of_living_index=117.7

series e:dyym-bjv4 d:2017-02-01T20:18:58.000Z t:county="Baltimore City" m:median_sale_price_home=127413 m:housing_units_sold=8252 m:avg_sale_price_home=166545 m:cost_of_living_index=99
```

## Meta Commands

```ls
metric m:cost_of_living_index p:float l:"Cost of Living Index" t:dataTypeName=number

metric m:avg_sale_price_home p:integer l:"Average Sale Price of a Home ($ Dollars)" t:dataTypeName=money

metric m:median_sale_price_home p:integer l:"Median Sale Price of a Home ($ Dollars)" t:dataTypeName=money

metric m:housing_units_sold p:integer l:"Number of Housing Units Sold" t:dataTypeName=number

entity e:dyym-bjv4 l:"Choose Maryland:  Compare Counties - Quality Of Life" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/dyym-bjv4

property e:dyym-bjv4 t:meta.view v:id=dyym-bjv4 v:category=Housing v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Quality Of Life" v:attribution="Maryland Department of Commerce"

property e:dyym-bjv4 t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:dyym-bjv4 t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | cost_of_living_index | avg_sale_price_home | median_sale_price_home | housing_units_sold | 
| =========== | =================== | ==================== | =================== | ====================== | ================== | 
| 1485980338  | Allegany County     | 86.7                 | 93500               | 80543                  | 575                | 
| 1485980338  | Anne Arundel County | 117.7                | 361780              | 308382                 | 8770               | 
| 1485980338  | Baltimore City      | 99.0                 | 166545              | 127413                 | 8252               | 
| 1485980338  | Baltimore County    | 110.9                | 258558              | 217721                 | 10413              | 
| 1485980338  | Calvert County      | 112.4                | 311480              | 286800                 | 1600               | 
| 1485980338  | Caroline County     | 104.2                | 178588              | 165703                 | 388                | 
| 1485980338  | Carroll County      | 107.9                | 305394              | 291161                 | 2510               | 
| 1485980338  | Cecil County        | 103.0                | 212546              | 194765                 | 1324               | 
| 1485980338  | Charles County      | 110.3                | 274000              | 261508                 | 2499               | 
| 1485980338  | Dorchester County   | 97.2                 | 172845              | 139516                 | 459                | 
```