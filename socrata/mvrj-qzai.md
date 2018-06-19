# Performance Metrics - Housing & Economic Development - Single Family Homes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-housing-economic-development-single-family-homes-0950b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/mvrj-qzai) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/mvrj-qzai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/mvrj-qzai/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | mvrj-qzai |
| Name | Performance Metrics - Housing & Economic Development - Single Family Homes |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, housing |
| Created | 2011-08-16T16:16:07Z |
| Publication Date | 2012-09-19T11:07:15Z |

## Description

Single family programs that support repairs or improvements to existing affordable single family units.  Units are counted when projects are approved for payment by HED.  Unit totals are adjusted to account for units receiving benefits from multiple HED programs.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                     | Data Type | Render Type |
| ======== | ============== | ====================================================== | ======================== | ========= | =========== |
| No       | time           | :updated_at                                            | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | month                                                  | Month                    | text      | text        |
| Yes      | series tag     | year                                                   | Year                     | text      | text        |
| Yes      | series tag     | single_family_home_repairs_units_improved_total_number | Repaired/Improve Homes   | text      | number      |
| Yes      | numeric metric | total_spending                                         | Total Spending           | money     | money       |
| Yes      | numeric metric | target_homes                                           | Target Homes             | number    | number      |
| Yes      | numeric metric | progress_to_target_homes                               | Progress to Target Homes | percent   | percent     |
| Yes      | numeric metric | spending_target                                        | Spending Target          | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mvrj-qzai d:2012-09-19T04:07:10.000Z t:single_family_home_repairs_units_improved_total_number=234 t:month=March t:year=2011 m:target_homes=1960 m:progress_to_target_homes=12 m:spending_target=16042832 m:total_spending=1640951

series e:mvrj-qzai d:2012-09-19T04:07:10.000Z t:single_family_home_repairs_units_improved_total_number=433 t:month=June t:year=2011 m:target_homes=1960 m:progress_to_target_homes=34 m:spending_target=16042832 m:total_spending=3536947

series e:mvrj-qzai d:2012-09-19T04:07:10.000Z t:single_family_home_repairs_units_improved_total_number=829 t:month=September t:year=2011 m:target_homes=1960 m:progress_to_target_homes=76 m:spending_target=16042832 m:total_spending=4422583
```

## Meta Commands

```ls
metric m:total_spending p:double l:"Total Spending" t:dataTypeName=money

metric m:target_homes p:integer l:"Target Homes" t:dataTypeName=number

metric m:progress_to_target_homes p:integer l:"Progress to Target Homes" t:dataTypeName=percent

metric m:spending_target p:double l:"Spending Target" t:dataTypeName=money

entity e:mvrj-qzai l:"Performance Metrics - Housing & Economic Development - Single Family Homes" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/mvrj-qzai

property e:mvrj-qzai t:meta.view v:id=mvrj-qzai v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Performance Metrics - Housing & Economic Development - Single Family Homes" v:attribution="City of Chicago"

property e:mvrj-qzai t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:mvrj-qzai t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | month     | year | single_family_home_repairs_units_improved_total_number | total_spending | target_homes | progress_to_target_homes | spending_target | 
| =========== | ========= | ==== | ====================================================== | ============== | ============ | ======================== | =============== | 
| 1348027630  | Month     | Year |                                                        |                |              |                          |                 | 
| 1348027630  | March     | 2011 | 234                                                    | 1640951.00     | 1960         | 12                       | 16042832.00     | 
| 1348027630  | June      | 2011 | 433                                                    | 3536947.00     | 1960         | 34                       | 16042832.00     | 
| 1348027630  | September | 2011 | 829                                                    | 4422583.00     | 1960         | 76                       | 16042832.00     | 
| 1348027630  | December  | 2011 | 601                                                    | 4604558.00     | 1960         | 107                      | 16042832.00     | 
| 1348027630  | March     | 2012 | 283                                                    | 2440319.00     | 2280         | 12                       | 19217882.00     | 
| 1348027630  | June      | 2012 | 479                                                    | 4374535.00     | 2280         | 33                       | 19217882.00     | 
```