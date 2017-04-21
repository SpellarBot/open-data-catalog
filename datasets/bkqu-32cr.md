# Santa Rosa Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/santa-rosa-operating-budget) |
| Metadata | [Link](https://data.srcity.org/api/views/bkqu-32cr) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/bkqu-32cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/bkqu-32cr/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | bkqu-32cr |
| Name | Santa Rosa Operating Budget |
| Created | 2015-11-05T22:32:48Z |
| Publication Date | 2016-07-01T22:19:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscal_year        | Fiscal Year        | number    | number      |
| Yes      | series tag     | service            | Service            | text      | text        |
| Yes      | series tag     | department         | Department         | text      | text        |
| Yes      | series tag     | program            | Program            | text      | text        |
| Yes      | series tag     | expense_category   | Expense Category   | text      | text        |
| Yes      | numeric metric | recommended_amount | Recommended Amount | money     | money       |
| Yes      | numeric metric | approved_amount    | Approved Amount    | number    | number      |
| Yes      | series tag     | fund               | Fund               | text      | text        |
| Yes      | series tag     | fund_type          | Fund Type          | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | series tag     | expense_type       | Expense Type       | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bkqu-32cr d:2015-01-01T00:00:00.000Z t:expense_type="Operating Expenses" t:program=Elections t:department="City Council" t:service="City Council" t:expense_category="Professional Services" t:fund="General Fund" m:approved_amount=230000

series e:bkqu-32cr d:2015-01-01T00:00:00.000Z t:expense_type="Operating Expenses" t:program=Elections t:department="City Council" t:service="City Council" t:expense_category="Other Miscellaneous" t:fund="General Fund" m:approved_amount=25000

series e:bkqu-32cr d:2015-01-01T00:00:00.000Z t:expense_type="Personnel Costs" t:program=Administration t:department="City Council" t:service="City Council" t:expense_category=Salaries t:fund="General Fund" m:approved_amount=72000
```

## Meta Commands

```ls
metric m:recommended_amount p:double l:"Recommended Amount" t:dataTypeName=money

metric m:approved_amount p:integer l:"Approved Amount" t:dataTypeName=number

entity e:bkqu-32cr l:"Santa Rosa Operating Budget" t:url=https://data.srcity.org/api/views/bkqu-32cr

property e:bkqu-32cr t:meta.view v:id=bkqu-32cr v:averageRating=0 v:name="Santa Rosa Operating Budget"

property e:bkqu-32cr t:meta.view.owner v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"

property e:bkqu-32cr t:meta.view.tableauthor v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"
```

## Top Records

```ls
| fiscal_year | service      | department   | program        | expense_category       | recommended_amount | approved_amount | fund         | fund_type | description | expense_type       | 
| =========== | ============ | ============ | ============== | ====================== | ================== | =============== | ============ | ========= | =========== | ================== | 
| 2015        | City Council | City Council | Elections      | Professional Services  |                    | 230000          | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Elections      | Other Miscellaneous    |                    | 25000           | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Salaries               |                    | 72000           | General Fund |           |             | Personnel Costs    | 
| 2015        | City Council | City Council | Administration | Benefits               |                    | 134818          | General Fund |           |             | Personnel Costs    | 
| 2015        | City Council | City Council | Administration | Professional Services  |                    | 91000           | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Vehicle Expenses       |                    | 1000            | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Utilities              |                    | 6500            | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Operational Supplies   |                    | 10598           | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Information Technology |                    | 24781           | General Fund |           |             | Operating Expenses | 
| 2015        | City Council | City Council | Administration | Other Miscellaneous    |                    | 96800           | General Fund |           |             | Operating Expenses | 
```