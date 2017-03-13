# Jackson Operating Expenses Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-operating-expenses-budget) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/848a-grzs) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/848a-grzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/848a-grzs/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 848a-grzs |
| Name | Jackson Operating Expenses Budget |
| Attribution | City of Jackson, Department of Administration |
| Category | Budget and Finance |
| Tags | budget, operating budget, expenditures, spending |
| Created | 2016-03-31T20:54:21Z |
| Publication Date | 2017-03-10T20:59:57Z |
| Rows Updated | 2017-03-10T20:59:31Z |

## Description

This dataset shows the City of Jackson's FY2017 budget, amount spent to date, amount encumbered, and the balance available to spend. The data can be broken down by Department, Division, Fund, Fund Type, and Expense Type.

This data displays all general fund dollars and some sub-fund dollars that assist with the operation of certain departments. This data is updated the 15th day of each month. This is to provide time for close out of the previous month in all budgetary software systems.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                        | Data Type | Render Type |
| ======== | ============== | ====================== | =========================== | ========= | =========== |
| Yes      | time           | fiscal_year            | Fiscal Year                 | number    | number      |
| Yes      | series tag     | dept_name              | Dept Name                   | text      | text        |
| Yes      | series tag     | fund_name              | Fund Name                   | text      | text        |
| Yes      | series tag     | fund_type              | Fund Type                   | text      | text        |
| Yes      | series tag     | division_name          | Division Name               | text      | text        |
| Yes      | series tag     | function_name          | Function Name               | text      | text        |
| Yes      | series tag     | expense_type           | Expense Type                | text      | text        |
| Yes      | series tag     | expense_description    | Expense Description         | text      | text        |
| Yes      | numeric metric | budget                 | 2017 Budget                 | money     | money       |
| Yes      | numeric metric | current_period_exp     | Current Period Expenditures | money     | money       |
| Yes      | numeric metric | ytd_exp                | YTD Expenditures            | money     | money       |
| Yes      | numeric metric | encumb                 | Encumbrances                | money     | money       |
| Yes      | numeric metric | bal_available_to_spend | Bal Available to Spend      | money     | money       |
| Yes      | numeric metric | of_budget_spent        | % of Budget Spent           | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description=SALARIES t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=147130 m:current_period_exp=10592 m:ytd_exp=42092 m:bal_available_to_spend=105038 m:of_budget_spent=28.6 m:encumb=0

series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description=OVERTIME t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=500 m:current_period_exp=0 m:ytd_exp=10 m:bal_available_to_spend=490 m:of_budget_spent=2 m:encumb=0

series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description="FICA TAXES" t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=9122 m:current_period_exp=625 m:ytd_exp=2507 m:bal_available_to_spend=6615 m:of_budget_spent=27.5 m:encumb=0
```

## Meta Commands

```ls
metric m:budget p:integer l:"2017 Budget" t:dataTypeName=money

metric m:current_period_exp p:integer l:"Current Period Expenditures" t:dataTypeName=money

metric m:ytd_exp p:integer l:"YTD Expenditures" t:dataTypeName=money

metric m:encumb p:integer l:Encumbrances t:dataTypeName=money

metric m:bal_available_to_spend p:integer l:"Bal Available to Spend" t:dataTypeName=money

metric m:of_budget_spent p:float l:"% of Budget Spent" t:dataTypeName=percent

entity e:848a-grzs l:"Jackson Operating Expenses Budget" t:attribution="City of Jackson, Department of Administration" t:url=https://data.jacksonms.gov/api/views/848a-grzs

property e:848a-grzs t:meta.view v:id=848a-grzs v:category="Budget and Finance" v:attributionLink="http://www.jacksonms.gov/index.aspx?nid=114" v:averageRating=0 v:name="Jackson Operating Expenses Budget" v:attribution="City of Jackson, Department of Administration"

property e:848a-grzs t:meta.view.owner v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:roleName=publisher v:displayName="Tiffanee Jones"

property e:848a-grzs t:meta.view.tableauthor v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:roleName=publisher v:displayName="Tiffanee Jones"
```