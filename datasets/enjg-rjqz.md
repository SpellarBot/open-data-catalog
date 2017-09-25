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
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | maryland, state, compare, spending, obligations, research, development, awards, contracts, patents |
| Created | 2013-08-20T17:52:53Z |
| Publication Date | 2017-08-16T17:50:47Z |

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
series e:enjg-rjqz d:2017-08-16T17:50:21.000Z t:state=Alabama m:patents_per_100k=10.1 m:nih_rd_awards=25399511 m:sbir_awards_per_capita=4.57 m:federal_rd_spending_obligations=4537952

series e:enjg-rjqz d:2017-08-16T17:50:21.000Z t:state=Alaska m:patents_per_100k=7.3 m:nih_rd_awards=0 m:sbir_awards_per_capita=0.26 m:federal_rd_spending_obligations=208043.9

series e:enjg-rjqz d:2017-08-16T17:50:21.000Z t:state=Arizona m:patents_per_100k=39.2 m:nih_rd_awards=3186536 m:sbir_awards_per_capita=3.33 m:federal_rd_spending_obligations=1643746.2
```

## Meta Commands

```ls
metric m:federal_rd_spending_obligations p:double l:"Federal R&D Spending/Obligations ($ Thousands)" t:dataTypeName=money

metric m:nih_rd_awards p:double l:"National Institutes of Health R&D Contract Awards ($ Dollars)" t:dataTypeName=money

metric m:sbir_awards_per_capita p:double l:"SBIR Awards, Value Per Capita ($ Dollars)" t:dataTypeName=money

metric m:patents_per_100k p:float l:"Number of Patents Issued per 100,000 Population" t:dataTypeName=number

entity e:enjg-rjqz l:"Choose Maryland:  Compare States - Technology" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/enjg-rjqz

property e:enjg-rjqz t:meta.view d:2017-09-25T07:22:29.236Z v:averageRating=0 v:name="Choose Maryland:  Compare States - Technology" v:attribution="Maryland Department of Commerce" v:attributionLink=http://commerce.maryland.gov v:id=enjg-rjqz v:category="Business and Economy"

property e:enjg-rjqz t:meta.view.owner d:2017-09-25T07:22:29.236Z v:displayName="Mike Grandel" v:id=m2gt-bxeg v:screenName="Mike Grandel"

property e:enjg-rjqz t:meta.view.tableauthor d:2017-09-25T07:22:29.236Z v:displayName="Mike Grandel" v:roleName=editor v:id=m2gt-bxeg v:screenName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | federal_rd_spending_obligations | nih_rd_awards | sbir_awards_per_capita | patents_per_100k | 
| =========== | =========== | =============================== | ============= | ====================== | ================ | 
| 1502905821  | Alabama     | 4537952.00                      | 25399511.00   | 4.57                   | 10.1             | 
| 1502905821  | Alaska      | 208043.90                       | 0.00          | 0.26                   | 7.3              | 
| 1502905821  | Arizona     | 1643746.20                      | 3186536.00    | 3.33                   | 39.2             | 
| 1502905821  | Arkansas    | 105595.50                       | 1758464.00    | 1.52                   | 8.1              | 
| 1502905821  | California  | 15280643.10                     | 91438716.00   | 9.99                   | 104.0            | 
| 1502905821  | Colorado    | 3506387.50                      | 6547016.00    | 14.17                  | 54.8             | 
| 1502905821  | Connecticut | 2292751.10                      | 3533404.00    | 8.61                   | 64.8             | 
| 1502905821  | Delaware    | 108102.90                       | 0.00          | 13.41                  | 33.8             | 
| 1502905821  | Florida     | 2932695.70                      | 3501386.00    | 2.10                   | 20.6             | 
| 1502905821  | Georgia     | 1182449.50                      | 21414017.00   | 1.88                   | 24.1             | 
```