# 2015 State Budget Restrictions As of March 31, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-state-budget-restrictions-as-of-march-31-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/49v8-zgwp) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/49v8-zgwp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/49v8-zgwp/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 49v8-zgwp |
| Name | 2015 State Budget Restrictions As of March 31, 2015 |
| Category | Government Administration |
| Created | 2015-04-06T13:44:59Z |
| Publication Date | 2015-04-06T13:45:53Z |

## Description

The data provided here details the State of Missouri's Budget Restrictions as of March 31, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | budget_fiscal_year | Budget Fiscal Year | number    | text        |
| Yes      | series tag     | agency_name        | Agency Name        | text      | text        |
| Yes      | series tag     | fund_name          | Fund Name          | text      | text        |
| Yes      | numeric metric | restricted_amount  | Restricted Amount  | number    | number      |
| Yes      | numeric metric | released_amount    | Released Amount    | number    | number      |
```

## Time Field

```ls
Value = budget_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:49v8-zgwp d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE BUSINESS DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=39 m:restricted_amount=39

series e:49v8-zgwp d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=343 m:restricted_amount=343

series e:49v8-zgwp d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE PROTECTION" t:agency_name=AGRICULTURE m:released_amount=2364 m:restricted_amount=46330
```

## Meta Commands

```ls
metric m:restricted_amount p:integer l:"Restricted Amount" t:dataTypeName=number

metric m:released_amount p:integer l:"Released Amount" t:dataTypeName=number

entity e:49v8-zgwp l:"2015 State Budget Restrictions As of March 31, 2015" t:url=https://data.mo.gov/api/views/49v8-zgwp

property e:49v8-zgwp t:meta.view v:id=49v8-zgwp v:category="Government Administration" v:averageRating=0 v:name="2015 State Budget Restrictions As of March 31, 2015"

property e:49v8-zgwp t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:49v8-zgwp t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```