# 2014 Elections - Independent Expenditure Committees Financial Summaries (as of November 4, 2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-independent-expenditure-committees-financial-summaries-as-of-november-4-201) |
| Metadata | [Link](https://data.hawaii.gov/api/views/hip3-7qsn) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/hip3-7qsn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/hip3-7qsn/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | hip3-7qsn |
| Name | 2014 Elections - Independent Expenditure Committees Financial Summaries (as of November 4, 2014) |
| Attribution | Hawaii State Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending, candidates, campaign spending commission, elections |
| Created | 2015-02-17T21:45:28Z |
| Publication Date | 2015-02-18T23:44:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | independent_expenditure_committee | Independent Expenditure Committee | text      | text        |
| Yes      | numeric metric | total_receipts                    | Total Receipts                    | money     | money       |
| Yes      | numeric metric | total_disbursements               | Total Disbursements               | money     | money       |
| Yes      | numeric metric | closing_cash                      | Closing Cash                      | money     | money       |
| Yes      | numeric metric | unpaid_expenditures               | Unpaid Expenditures               | money     | money       |
| Yes      | numeric metric | surplus_deficit                   | Surplus/Deficit                   | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hip3-7qsn d:2014-01-01T00:00:00.000Z t:independent_expenditure_committee="Hawaii Building & Construction Trades Council" m:unpaid_expenditures=0 m:closing_cash=0 m:total_disbursements=20660.51 m:surplus_deficit=0 m:total_receipts=20660.51

series e:hip3-7qsn d:2014-01-01T00:00:00.000Z t:independent_expenditure_committee="NEA Advocacy Fund" m:unpaid_expenditures=0 m:closing_cash=0 m:total_disbursements=299233 m:surplus_deficit=0 m:total_receipts=299233

series e:hip3-7qsn d:2014-01-01T00:00:00.000Z t:independent_expenditure_committee="Ocean Resort Villas North PAC" m:unpaid_expenditures=0 m:closing_cash=0 m:total_disbursements=450000 m:surplus_deficit=0 m:total_receipts=450000
```

## Meta Commands

```ls
metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:closing_cash p:double l:"Closing Cash" t:dataTypeName=money

metric m:unpaid_expenditures p:double l:"Unpaid Expenditures" t:dataTypeName=money

metric m:surplus_deficit p:double l:Surplus/Deficit t:dataTypeName=money

entity e:hip3-7qsn l:"2014 Elections - Independent Expenditure Committees Financial Summaries (as of November 4, 2014)" t:attribution="Hawaii State Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/hip3-7qsn

property e:hip3-7qsn t:meta.view v:id=hip3-7qsn v:category=Community v:averageRating=0 v:name="2014 Elections - Independent Expenditure Committees Financial Summaries (as of November 4, 2014)" v:attribution="Hawaii State Campaign Spending Commission"

property e:hip3-7qsn t:meta.view.license v:name="Public Domain"

property e:hip3-7qsn t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:hip3-7qsn t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| independent_expenditure_committee             | total_receipts | total_disbursements | closing_cash | unpaid_expenditures | surplus_deficit | 
| ============================================= | ============== | =================== | ============ | =================== | =============== | 
| Hawaii Building & Construction Trades Council | 20660.51       | 20660.51            | 0            | 0                   | 0               | 
| NEA Advocacy Fund                             | 299233         | 299233              | 0            | 0                   | 0               | 
| Ocean Resort Villas North PAC                 | 450000         | 450000              | 0            | 0                   | 0               | 
| Ocean Resort Villas PAC                       | 450000         | 450000              | 0            | 0                   | 0               | 
| Planned Parenthood of Hawaii Action Network   | 5156.16        | 5726.67             | 93.17        | 0                   | 93.17           | 
| Save Our Aloha State                          | 171            | 171                 | 0            | 0                   | 0               | 
| SaveOurHonolulu.com                           | 0              | 2346.56             | 3245.71      | 0                   | 3245.71         | 
| Sierra Club Hawaii PAC                        | 26084.75       | 25841.04            | 13573.59     | 0                   | 13573.59        | 
| Workers for a Better Hawaii                   | 130000         | 120758.88           | 13454.33     | 0                   | 13454.33        | 
| Hawaii Solutions                              | 32532          | 29592.89            | 5221.51      | 1272                | 3949.51         | 
```