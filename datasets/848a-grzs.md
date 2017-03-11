# Jackson Operating Expenses Budget

## Dataset

* [Dataset URL](https://data.jacksonms.gov/api/views/848a-grzs/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/jackson-operating-expenses-budget)
* Id = 848a-grzs
* Name = Jackson Operating Expenses Budget
* Attribution = City of Jackson, Department of Administration
* Attribution Link = http://www.jacksonms.gov/index.aspx?nid=114
* Category = Budget and Finance
* Tags = [budget, operating budget, expenditures, spending]
* Created = 2016-03-31T20:54:21Z
* Publication Date = 2016-12-20T20:51:59Z
* Rows Updated = 2016-12-20T20:51:37Z

## Description

This dataset shows the City of Jackson's FY2017 budget, amount spent to date, amount encumbered, and the balance available to spend. The data can be broken down by Department, Division, Fund, Fund Type, and Expense Type.

This data displays all general fund dollars and some sub-fund dollars that assist with the operation of certain departments. This data is updated the 15th day of each month. This is to provide time for close out of the previous month in all budgetary software systems.

## Columns

```ls
| Name                        | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| =========================== | ====================== | ========= | =========== | ============== | ======== | 
| Fiscal Year                 | fiscal_year            | number    | number      | time           | Yes      | 
| Dept Name                   | dept_name              | text      | text        | series tag     | Yes      | 
| Fund Name                   | fund_name              | text      | text        | series tag     | Yes      | 
| Fund Type                   | fund_type              | text      | text        | series tag     | Yes      | 
| Division Name               | division_name          | text      | text        | series tag     | Yes      | 
| Function Name               | function_name          | text      | text        | series tag     | Yes      | 
| Expense Type                | expense_type           | text      | text        | series tag     | Yes      | 
| Expense Description         | expense_description    | text      | text        | series tag     | Yes      | 
| 2017 Budget                 | budget                 | money     | money       | numeric metric | Yes      | 
| Current Period Expenditures | current_period_exp     | money     | money       | numeric metric | Yes      | 
| YTD Expenditures            | ytd_exp                | money     | money       | numeric metric | Yes      | 
| Encumbrances                | encumb                 | money     | money       | numeric metric | Yes      | 
| Bal Available to Spend      | bal_available_to_spend | money     | money       | numeric metric | Yes      | 
| % of Budget Spent           | of_budget_spent        | percent   | percent     | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description=SALARIES t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=147130 m:current_period_exp=10630.37 m:ytd_exp=21054.14 m:bal_available_to_spend=126075.86 m:of_budget_spent=14.3

series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description=OVERTIME t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=500 m:ytd_exp=4.95 m:bal_available_to_spend=495.05 m:of_budget_spent=1

series e:848a-grzs d:2017-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:fund_type="GENERAL FUND" t:expense_type="PERSONAL SERVICES" t:function_name="OFFICE OF PUBLICATIONS" t:expense_description="FICA TAXES" t:dept_name=ADMINISTRATION t:division_name="OFFICE OF PUBLICATIONS" m:budget=9122 m:current_period_exp=621.17 m:ytd_exp=937.49 m:bal_available_to_spend=8184.51 m:of_budget_spent=10.3
```

## Meta Commands

```ls
entity e:848a-grzs l:"Jackson Operating Expenses Budget" t:attribution="City of Jackson, Department of Administration" t:url=https://data.jacksonms.gov/api/views/848a-grzs

property e:848a-grzs t:meta.view d:2017-03-06T08:20:13.466Z v:id=848a-grzs v:category="Budget and Finance" v:attributionLink="http://www.jacksonms.gov/index.aspx?nid=114" v:averageRating=0 v:name="Jackson Operating Expenses Budget" v:attribution="City of Jackson, Department of Administration"

property e:848a-grzs t:meta.view.owner d:2017-03-06T08:20:13.466Z v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:roleName=publisher v:displayName="Tiffanee Jones"

property e:848a-grzs t:meta.view.tableauthor d:2017-03-06T08:20:13.466Z v:id=csn7-fh8q v:screenName="Tiffanee Jones" v:roleName=publisher v:displayName="Tiffanee Jones"
```