# Adopted FY15 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adopted-fy15-budget) |
| Metadata | [Link](https://data.honolulu.gov/api/views/utqy-e8pg) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/utqy-e8pg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/utqy-e8pg/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | utqy-e8pg |
| Name | Adopted FY15 Budget |
| Category | Finance |
| Tags | adopted, fiscal year 2015, fy15, budget |
| Created | 2015-03-06T18:29:35Z |
| Publication Date | 2015-03-06T18:33:17Z |

## Description

Adopted Fiscal Year 2016 Budget

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | text        |
| Yes      | numeric metric | fy_2012_actual           | FY 2012 Actual           | money     | money       |
| Yes      | numeric metric | fy_2013_actual           | FY 2013 Actual           | money     | money       |
| Yes      | numeric metric | fy_2014_budget           | FY 2014 Budget           | money     | money       |
| Yes      | numeric metric | fy_2015_current_services | FY 2015 Current Services | money     | money       |
| Yes      | numeric metric | fy_2015_budget_issues    | FY 2015 Budget Issues    | money     | money       |
| Yes      | numeric metric | fy_2015_adopted_budget   | FY 2015 Adopted Budget   | money     | money       |
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
series e:utqy-e8pg d:2015-03-06T10:29:38.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name=Administration t:object_code=1101 m:fy_2013_actual=648445 m:fy_2015_adopted_budget=854868 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=652845 m:fy_2015_current_services=854868 m:fy_2014_budget=871188

series e:utqy-e8pg d:2015-03-06T10:29:38.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Non-Holiday Overtime Pay" t:division_name=Administration t:object_code=1102 m:fy_2013_actual=0 m:fy_2015_adopted_budget=0 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=0 m:fy_2015_current_services=0 m:fy_2014_budget=0

series e:utqy-e8pg d:2015-03-06T10:29:38.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Accumulated Vacation Pay (Lump-Sum Pay)" t:division_name=Administration t:object_code=1106 m:fy_2013_actual=19243 m:fy_2015_adopted_budget=0 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=14197 m:fy_2015_current_services=0 m:fy_2014_budget=0
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2012_actual p:double l:"FY 2012 Actual" t:dataTypeName=money

metric m:fy_2013_actual p:double l:"FY 2013 Actual" t:dataTypeName=money

metric m:fy_2014_budget p:double l:"FY 2014 Budget" t:dataTypeName=money

metric m:fy_2015_current_services p:double l:"FY 2015 Current Services" t:dataTypeName=money

metric m:fy_2015_budget_issues p:double l:"FY 2015 Budget Issues" t:dataTypeName=money

metric m:fy_2015_adopted_budget p:double l:"FY 2015 Adopted Budget" t:dataTypeName=money

entity e:utqy-e8pg l:"Adopted FY15 Budget" t:url=https://data.honolulu.gov/api/views/utqy-e8pg

property e:utqy-e8pg t:meta.view v:id=utqy-e8pg v:category=Finance v:averageRating=0 v:name="Adopted FY15 Budget"

property e:utqy-e8pg t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:utqy-e8pg t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2012_actual | fy_2013_actual | fy_2014_budget | fy_2015_current_services | fy_2015_budget_issues | fy_2015_adopted_budget | department_name            | division_name  | fund_name    | object_code_name                               | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ====================== | ========================== | ============== | ============ | ============================================== | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1101        | 652845.00      | 648445.00      | 871188.00      | 854868.00                | 0.0                   | 854868.00              | Budget and Fiscal Services | Administration | General Fund | Regular Pay                                    | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1102        | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Non-Holiday Overtime Pay                       | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1106        | 14197.00       | 19243.00       | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Accumulated Vacation Pay (Lump-Sum Pay)        | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1107        | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Holiday Overtime Pay                           | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1109        | 0.0            | 15010.00       | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Temporary Assignment Pay                       | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1118        | 0.0            | 0.0            | 0.0            | 3460.00                  | 0.0                   | 3460.00                | Budget and Fiscal Services | Administration | General Fund | Misc Salary Adjustment                         | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1120        | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Vacancy Cut-Back(Budget)                       | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1120C       | 0.0            | 0.0            |                |                          | 0.0                   |                        | Budget and Fiscal Services | Administration | General Fund | Transfer to the Provision for Vacant Positions | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1125        | 153554.00      | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Personal Svcs-Contract Positions               | 
| 1425637778  | OP_BFS     | BFS0300C | 110  | 1301        | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                    | Budget and Fiscal Services | Administration | General Fund | Unemployment Compensation                      | 
```