# City spending

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-spending-fd588) |
| Metadata | [Link](https://data.honolulu.gov/api/views/std8-yakc) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/std8-yakc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/std8-yakc/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | std8-yakc |
| Name | City spending |
| Category | Finance |
| Created | 2012-06-01T00:13:48Z |
| Publication Date | 2012-11-20T16:44:46Z |

## Description

Actual spending 2010&2011 Budget 2012 Proposed Budget 2013

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | text        |
| Yes      | series tag     | object_code              | Object Code              | text      | number      |
| Yes      | numeric metric | fy_2010_actual           | FY 2010 Actual           | number    | number      |
| Yes      | numeric metric | fy_2011_actual           | FY 2011 Actual           | number    | number      |
| Yes      | numeric metric | fy_2012_budget           | FY 2012 Budget           | number    | number      |
| Yes      | numeric metric | fy_2013_current_services | FY 2013 Current Services | number    | number      |
| Yes      | numeric metric | fy_2013_budget_issues    | FY 2013 Budget Issues    | number    | number      |
| Yes      | numeric metric | fy_2013_proposed_budget  | FY 2013 Proposed Budget  | number    | number      |
| Yes      | series tag     | department_name          | Department Name          | text      | text        |
| Yes      | series tag     | division_name            | Division Name            | text      | text        |
| Yes      | series tag     | fund_name                | Fund Name                | text      | text        |
| Yes      | series tag     | object_code_name         | Object Code Name         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:std8-yakc d:2012-11-20T08:43:19.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Supplies Not Classified" t:division_name=Administration t:object_code=2517 m:fy_2013_budget_issues=0 m:fy_2012_budget=200 m:fy_2013_proposed_budget=200 m:fy_2013_current_services=200 m:fund=110 m:fy_2010_actual=31 m:fy_2011_actual=0

series e:std8-yakc d:2012-11-20T08:43:19.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Rentals-Office Equipment" t:division_name=Administration t:object_code=3630 m:fy_2013_budget_issues=0 m:fy_2012_budget=6700 m:fy_2013_proposed_budget=6700 m:fy_2013_current_services=6700 m:fund=110 m:fy_2010_actual=5426 m:fy_2011_actual=5242

series e:std8-yakc d:2012-11-20T08:43:19.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Other Services - Not Classified" t:division_name=Administration t:object_code=3049 m:fy_2013_budget_issues=0 m:fy_2012_budget=0 m:fy_2013_proposed_budget=0 m:fy_2013_current_services=0 m:fund=110 m:fy_2010_actual=200 m:fy_2011_actual=0
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2010_actual p:integer l:"FY 2010 Actual" t:dataTypeName=number

metric m:fy_2011_actual p:integer l:"FY 2011 Actual" t:dataTypeName=number

metric m:fy_2012_budget p:integer l:"FY 2012 Budget" t:dataTypeName=number

metric m:fy_2013_current_services p:integer l:"FY 2013 Current Services" t:dataTypeName=number

metric m:fy_2013_budget_issues p:integer l:"FY 2013 Budget Issues" t:dataTypeName=number

metric m:fy_2013_proposed_budget p:integer l:"FY 2013 Proposed Budget" t:dataTypeName=number

entity e:std8-yakc l:"City spending" t:url=https://data.honolulu.gov/api/views/std8-yakc

property e:std8-yakc t:meta.view v:id=std8-yakc v:category=Finance v:averageRating=100 v:name="City spending"

property e:std8-yakc t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:std8-yakc t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2010_actual | fy_2011_actual | fy_2012_budget | fy_2013_current_services | fy_2013_budget_issues | fy_2013_proposed_budget | department_name            | division_name  | fund_name    | object_code_name                                    | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ======================= | ========================== | ============== | ============ | =================================================== | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 2517        | 31             | 0              | 200            | 200                      | 0                     | 200                     | Budget and Fiscal Services | Administration | General Fund | Supplies Not Classified                             | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 3630        | 5426           | 5242           | 6700           | 6700                     | 0                     | 6700                    | Budget and Fiscal Services | Administration | General Fund | Rentals-Office Equipment                            | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 3049        | 200            | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Other Services - Not Classified                     | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 1120        | 0              | 0              | -83244         | -63244                   | 0                     | -63244                  | Budget and Fiscal Services | Administration | General Fund | Vacancy Cut-Back(Budget)                            | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 1125        | 241003         | 184309         | 153636         | 153636                   | 0                     | 153636                  | Budget and Fiscal Services | Administration | General Fund | Personal Svcs-Contract Positions                    | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 3211        | 590            | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Travel Expense-Intrastate                           | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 1109        | 0              | 1383           | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Temporary Assignment Pay                            | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 1501        | 660            | 815            | 500            | 500                      | 0                     | 500                     | Budget and Fiscal Services | Administration | General Fund | Service, Merit Or Employee Suggestion Program Award | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 2331        | 437            | 316            | 350            | 350                      | 0                     | 350                     | Budget and Fiscal Services | Administration | General Fund | Computer Supplies                                   | 
| 1353400999  | OP_BFS     | BFS0300C | 110  | 3004        | 392            | 0              | 2395           | 2395                     | 0                     | 2395                    | Budget and Fiscal Services | Administration | General Fund | Consultant Services                                 | 
```