# Choose Maryland: Compare States - Technology

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-technology) |
| Metadata | [Link](https://data.maryland.gov/api/views/enjg-rjqz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/enjg-rjqz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/enjg-rjqz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | enjg-rjqz |
| Name | Choose Maryland: Compare States - Technology |
| Attribution | Maryland Department of Business and Economic Development |
| Category | Business and Economy |
| Tags | maryland, state, compare, spending, obligations, research, development, awards, contracts, patents |
| Created | 2013-08-20T17:52:53Z |
| Publication Date | 2017-03-22T19:52:56Z |

## Description

Innovation - R&D funding, research awards, and patents.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                                          | Data Type | Render Type |
| ======== | ============== | =============================== | ============================================================= | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                                                    | meta_data | meta_data   |
| Yes      | series tag     | state                           | State                                                         | text      | text        |
| Yes      | numeric metric | federal_rd_spending_obligations | Federal R&D Spending/Obligations ($ Thousands)                | money     | money       |
| Yes      | numeric metric | nih_rd_awards                   | National Institutes of Health R&D Contract Awards ($ Dollars) | money     | money       |
| Yes      | numeric metric | sbir_awards_per_capita          | SBIR Awards, Value Per Capita ($ Dollars)                     | money     | money       |
| Yes      | numeric metric | patents_per_100k                | Number of Patents Issued per 100,000 Population               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:enjg-rjqz d:2017-03-22T19:52:37.000Z t:state=Alabama m:federal_rd_spending_obligations=4537952 m:nih_rd_awards=25399511 m:sbir_awards_per_capita=7.03 m:patents_per_100k=9.7

series e:enjg-rjqz d:2017-03-22T19:52:37.000Z t:state=Alaska m:federal_rd_spending_obligations=208043.9 m:nih_rd_awards=0 m:sbir_awards_per_capita=0.2 m:patents_per_100k=5.4

series e:enjg-rjqz d:2017-03-22T19:52:37.000Z t:state=Arizona m:federal_rd_spending_obligations=1643746.2 m:nih_rd_awards=3186536 m:sbir_awards_per_capita=2.83 m:patents_per_100k=37.2
```

## Meta Commands

```ls
metric m:federal_rd_spending_obligations p:double l:"Federal R&D Spending/Obligations ($ Thousands)" t:dataTypeName=money

metric m:nih_rd_awards p:integer l:"National Institutes of Health R&D Contract Awards ($ Dollars)" t:dataTypeName=money

metric m:sbir_awards_per_capita p:double l:"SBIR Awards, Value Per Capita ($ Dollars)" t:dataTypeName=money

metric m:patents_per_100k p:float l:"Number of Patents Issued per 100,000 Population" t:dataTypeName=number

entity e:enjg-rjqz l:"Choose Maryland:  Compare States - Technology" t:attribution="Maryland Department of Business and Economic Development" t:url=https://data.maryland.gov/api/views/enjg-rjqz

property e:enjg-rjqz t:meta.view v:id=enjg-rjqz v:category="Business and Economy" v:attributionLink=http://www.choosemaryland.org v:averageRating=0 v:name="Choose Maryland:  Compare States - Technology" v:attribution="Maryland Department of Business and Economic Development"

property e:enjg-rjqz t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:enjg-rjqz t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | federal_rd_spending_obligations | nih_rd_awards | sbir_awards_per_capita | patents_per_100k | 
| =========== | =========== | =============================== | ============= | ====================== | ================ | 
| 1490212357  | Alabama     | 4537952.0                       | 25399511      | 7.03                   | 9.7              | 
| 1490212357  | Alaska      | 208043.9                        | 0             | 0.20                   | 5.4              | 
| 1490212357  | Arizona     | 1643746.2                       | 3186536       | 2.83                   | 37.2             | 
| 1490212357  | Arkansas    | 105595.5                        | 1758464       | 2.48                   | 7.8              | 
| 1490212357  | California  | 15280643.1                      | 91438716      | 8.49                   | 102.7            | 
| 1490212357  | Colorado    | 3506387.5                       | 6547016       | 15.04                  | 55.8             | 
| 1490212357  | Connecticut | 2292751.1                       | 3533404       | 6.89                   | 60.1             | 
| 1490212357  | Delaware    | 108102.9                        | 0             | 9.55                   | 38.2             | 
| 1490212357  | Florida     | 2932695.7                       | 3501386       | 2.33                   | 20.0             | 
| 1490212357  | Georgia     | 1182449.5                       | 21414017      | 1.36                   | 24.1             | 
```