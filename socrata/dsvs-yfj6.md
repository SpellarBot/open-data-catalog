# Performance Metrics - Housing & Economic Development - Affordable Multi Family Homes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-housing-economic-development-affordable-multi-family-homes-1185f) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/dsvs-yfj6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/dsvs-yfj6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/dsvs-yfj6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | dsvs-yfj6 |
| Name | Performance Metrics - Housing & Economic Development - Affordable Multi Family Homes |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, housing |
| Created | 2011-08-16T15:23:38Z |
| Publication Date | 2012-09-19T11:07:38Z |

## Description

Multi-family programs that support the creation of new affordable multi-family housing units or the preservation of existing affordable units.  Units are counted when financial commitments are approved by the City Council.

## Columns

```ls
| Included | Schema Type    | Field Name                                                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                                                         | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | month                                                               | Month                                | text      | text        |
| Yes      | series tag     | year                                                                | Year                                 | text      | text        |
| Yes      | numeric metric | affordable_multi_family_housing_units_created_or_preserved_to_date_ | Created/Preserved Multi-Family Units | number    | number      |
| Yes      | numeric metric | target_homes                                                        | Target Homes                         | number    | number      |
| Yes      | numeric metric | progress_to_target_homes                                            | Progress to Target Homes             | percent   | percent     |
| Yes      | numeric metric | total_spending                                                      | Total Spending                       | money     | money       |
| Yes      | numeric metric | spending_target                                                     | Spending Target                      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dsvs-yfj6 d:2012-09-19T04:07:33.000Z t:month=March t:year=2011 m:target_homes=5662 m:affordable_multi_family_housing_units_created_or_preserved_to_date_=3426 m:progress_to_target_homes=60.51 m:spending_target=355442732 m:total_spending=37662400

series e:dsvs-yfj6 d:2012-09-19T04:07:33.000Z t:month=June t:year=2011 m:target_homes=5662 m:affordable_multi_family_housing_units_created_or_preserved_to_date_=476 m:progress_to_target_homes=68.92 m:spending_target=355442732 m:total_spending=88847694

series e:dsvs-yfj6 d:2012-09-19T04:07:33.000Z t:month=September t:year=2011 m:target_homes=5662 m:affordable_multi_family_housing_units_created_or_preserved_to_date_=418 m:progress_to_target_homes=76.3 m:spending_target=355442732 m:total_spending=64887443
```

## Meta Commands

```ls
metric m:affordable_multi_family_housing_units_created_or_preserved_to_date_ p:integer l:"Created/Preserved Multi-Family Units" t:dataTypeName=number

metric m:target_homes p:integer l:"Target Homes" t:dataTypeName=number

metric m:progress_to_target_homes p:float l:"Progress to Target Homes" t:dataTypeName=percent

metric m:total_spending p:double l:"Total Spending" t:dataTypeName=money

metric m:spending_target p:double l:"Spending Target" t:dataTypeName=money

entity e:dsvs-yfj6 l:"Performance Metrics - Housing & Economic Development - Affordable Multi Family Homes" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/dsvs-yfj6

property e:dsvs-yfj6 t:meta.view v:id=dsvs-yfj6 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Housing & Economic Development - Affordable Multi Family Homes" v:attribution="City of Chicago"

property e:dsvs-yfj6 t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:dsvs-yfj6 t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | month     | year | affordable_multi_family_housing_units_created_or_preserved_to_date_ | target_homes | progress_to_target_homes | total_spending | spending_target | 
| =========== | ========= | ==== | =================================================================== | ============ | ======================== | ============== | =============== | 
| 1348027653  | Month     | Year |                                                                     |              |                          |                |                 | 
| 1348027653  | March     | 2011 | 3426                                                                | 5662         | 60.51                    | 37662400.00    | 355442732.00    | 
| 1348027653  | June      | 2011 | 476                                                                 | 5662         | 68.92                    | 88847694.00    | 355442732.00    | 
| 1348027653  | September | 2011 | 418                                                                 | 5662         | 76.30                    | 64887443.00    | 355442732.00    | 
| 1348027653  | December  | 2011 | 996                                                                 | 5662         | 93.89                    | 41587116.00    | 355442732.00    | 
| 1348027653  | March     | 2012 | 3184                                                                | 6188         | 51.45                    | 41183661.00    | 288880552.00    | 
| 1348027653  | June      | 2012 | 403                                                                 | 6188         | 58.00                    | 22365165.00    | 288880552.00    | 
```