# Adopted FY17 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adopted-fy17-budget) |
| Metadata | [Link](https://data.honolulu.gov/api/views/fpu3-7m4z) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/fpu3-7m4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/fpu3-7m4z/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | fpu3-7m4z |
| Name | Adopted FY17 Budget |
| Category | Finance |
| Tags | adopted, fiscal year 2017, fy17, budget |
| Created | 2016-07-01T18:20:03Z |
| Publication Date | 2016-07-01T18:24:25Z |

## Description

Adopted Fiscal Year 2017 Budget

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | text        |
| Yes      | numeric metric | fy_2014_actual           | FY 2014 Actual           | money     | money       |
| Yes      | numeric metric | fy_2015_actual           | FY 2015 Actual           | money     | money       |
| Yes      | numeric metric | fy_2016_budget           | FY 2016 Budget           | money     | money       |
| Yes      | numeric metric | fy_2017_current_services | FY 2017 Current Services | money     | money       |
| Yes      | numeric metric | fy_2017_budget_issues    | FY 2017 Budget Issues    | money     | money       |
| Yes      | numeric metric | fy_2017_final_budget     | FY 2017 Final Budget     | money     | money       |
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
series e:fpu3-7m4z d:2016-07-01T11:20:09.000Z t:fund_name="General Fund" t:division=BFS0381 t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Advertising & Publication of Notices" t:division_name="Real Property" t:object_code=3252 m:fy_2015_actual=2759 m:fy_2017_current_services=3000 m:fy_2017_budget_issues=0 m:fund=110 m:fy_2014_actual=2069 m:fy_2016_budget=2500 m:fy_2017_final_budget=3000

series e:fpu3-7m4z d:2016-07-01T11:20:09.000Z t:fund_name="General Fund" t:division=BFS0381 t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Parking Fees" t:division_name="Real Property" t:object_code=3822 m:fy_2015_actual=3656 m:fy_2017_current_services=3750 m:fy_2017_budget_issues=0 m:fund=110 m:fy_2014_actual=3715 m:fy_2016_budget=2250 m:fy_2017_final_budget=3750

series e:fpu3-7m4z d:2016-07-01T11:20:09.000Z t:fund_name="General Fund" t:division=BFS0361C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name="Purchasing and General Services" t:object_code=1101 m:fy_2015_actual=1593384 m:fy_2017_current_services=1832064 m:fy_2017_budget_issues=0 m:fund=110 m:fy_2014_actual=1472555 m:fy_2016_budget=1739634 m:fy_2017_final_budget=1832064
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2014_actual p:integer l:"FY 2014 Actual" t:dataTypeName=money

metric m:fy_2015_actual p:integer l:"FY 2015 Actual" t:dataTypeName=money

metric m:fy_2016_budget p:double l:"FY 2016 Budget" t:dataTypeName=money

metric m:fy_2017_current_services p:integer l:"FY 2017 Current Services" t:dataTypeName=money

metric m:fy_2017_budget_issues p:integer l:"FY 2017 Budget Issues" t:dataTypeName=money

metric m:fy_2017_final_budget p:integer l:"FY 2017 Final Budget" t:dataTypeName=money

entity e:fpu3-7m4z l:"Adopted FY17 Budget" t:url=https://data.honolulu.gov/api/views/fpu3-7m4z

property e:fpu3-7m4z t:meta.view v:id=fpu3-7m4z v:category=Finance v:averageRating=0 v:name="Adopted FY17 Budget"

property e:fpu3-7m4z t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:fpu3-7m4z t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2014_actual | fy_2015_actual | fy_2016_budget | fy_2017_current_services | fy_2017_budget_issues | fy_2017_final_budget | department_name            | division_name                   | fund_name    | object_code_name                                | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ==================== | ========================== | =============================== | ============ | =============================================== | 
| 1467372009  | OP_BFS     | BFS0381  | 110  | 3252        | 2069           | 2759           | 2500           | 3000                     | 0                     | 3000                 | Budget and Fiscal Services | Real Property                   | General Fund | Advertising & Publication of Notices            | 
| 1467372009  | OP_BFS     | BFS0381  | 110  | 3822        | 3715           | 3656           | 2250           | 3750                     | 0                     | 3750                 | Budget and Fiscal Services | Real Property                   | General Fund | Parking Fees                                    | 
| 1467372009  | OP_BFS     | BFS0361C | 110  | 1101        | 1472555        | 1593384        | 1739634        | 1832064                  | 0                     | 1832064              | Budget and Fiscal Services | Purchasing and General Services | General Fund | Regular Pay                                     | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 3990        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Treasury                        | General Fund | Other Fixed Charges                             | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 3014        | 78147          | 96362          | 80000          | 354000                   | 0                     | 354000               | Budget and Fiscal Services | Treasury                        | General Fund | Management Fees                                 | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 1701        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Treasury                        | General Fund | Health Fund                                     | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 3811        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Treasury                        | General Fund | Pcard Charges (Default)                         | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 1125        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Treasury                        | General Fund | Personal Svcs-Contract Positions                | 
| 1467372009  | OP_BFS     | BFS0371C | 110  | 3021        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Treasury                        | General Fund | Sub Recipient Grants                            | 
| 1467372009  | OP_BFS     | BFS0361C | 110  | 2755        | 0              | 0              | 0              | 0                        | 0                     | 0                    | Budget and Fiscal Services | Purchasing and General Services | General Fund | Parts & Accessories-Equipment (Other Equipment) | 
```