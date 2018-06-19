# Proposed FY15 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-fy15-budget-e04de) |
| Metadata | [Link](https://data.honolulu.gov/api/views/dw6j-5gaz) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/dw6j-5gaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/dw6j-5gaz/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | dw6j-5gaz |
| Name | Proposed FY15 Budget |
| Category | Finance |
| Tags | proposed, budget, fy2015 |
| Created | 2014-03-01T00:18:03Z |
| Publication Date | 2015-03-24T19:55:48Z |

## Description

Proposed City Budget for Fiscal Year 2015

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | number      |
| Yes      | numeric metric | fy_2012_actual           | FY 2012 Actual           | number    | number      |
| Yes      | numeric metric | fy_2013_actual           | FY 2013 Actual           | number    | number      |
| Yes      | numeric metric | fy_2014_budget           | FY 2014 Budget           | number    | number      |
| Yes      | numeric metric | fy_2015_current_services | FY 2015 Current Services | number    | number      |
| Yes      | numeric metric | fy_2015_budget_issues    | FY 2015 Budget Issues    | number    | number      |
| Yes      | numeric metric | fy_2015_proposed_budget  | FY 2015 Proposed Budget  | number    | number      |
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
series e:dw6j-5gaz d:2014-02-28T16:18:07.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name=Administration t:object_code=1101 m:fy_2013_actual=648445 m:fy_2015_proposed_budget=854868 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=652845 m:fy_2015_current_services=854868 m:fy_2014_budget=871188

series e:dw6j-5gaz d:2014-02-28T16:18:07.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Non-Holiday Overtime Pay" t:division_name=Administration t:object_code=1102 m:fy_2013_actual=0 m:fy_2015_proposed_budget=0 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=0 m:fy_2015_current_services=0 m:fy_2014_budget=0

series e:dw6j-5gaz d:2014-02-28T16:18:07.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Accumulated Vacation Pay (Lump-Sum Pay)" t:division_name=Administration t:object_code=1106 m:fy_2013_actual=19243 m:fy_2015_proposed_budget=0 m:fy_2015_budget_issues=0 m:fund=110 m:fy_2012_actual=14197 m:fy_2015_current_services=0 m:fy_2014_budget=0
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2012_actual p:integer l:"FY 2012 Actual" t:dataTypeName=number

metric m:fy_2013_actual p:integer l:"FY 2013 Actual" t:dataTypeName=number

metric m:fy_2014_budget p:integer l:"FY 2014 Budget" t:dataTypeName=number

metric m:fy_2015_current_services p:integer l:"FY 2015 Current Services" t:dataTypeName=number

metric m:fy_2015_budget_issues p:integer l:"FY 2015 Budget Issues" t:dataTypeName=number

metric m:fy_2015_proposed_budget p:integer l:"FY 2015 Proposed Budget" t:dataTypeName=number

entity e:dw6j-5gaz l:"Proposed FY15 Budget" t:url=https://data.honolulu.gov/api/views/dw6j-5gaz

property e:dw6j-5gaz t:meta.view v:id=dw6j-5gaz v:category=Finance v:averageRating=0 v:name="Proposed FY15 Budget"

property e:dw6j-5gaz t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:dw6j-5gaz t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2012_actual | fy_2013_actual | fy_2014_budget | fy_2015_current_services | fy_2015_budget_issues | fy_2015_proposed_budget | department_name            | division_name  | fund_name    | object_code_name                               | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ======================= | ========================== | ============== | ============ | ============================================== | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1101        | 652845         | 648445         | 871188         | 854868                   | 0                     | 854868                  | Budget and Fiscal Services | Administration | General Fund | Regular Pay                                    | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1102        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Non-Holiday Overtime Pay                       | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1106        | 14197          | 19243          | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Accumulated Vacation Pay (Lump-Sum Pay)        | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1107        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Holiday Overtime Pay                           | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1109        | 0              | 15010          | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Temporary Assignment Pay                       | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1118        | 0              | 0              | 0              | 3460                     | 0                     | 3460                    | Budget and Fiscal Services | Administration | General Fund | Misc Salary Adjustment                         | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1120        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Vacancy Cut-Back(Budget)                       | 
| 1393604287  | OP_BFS     | BFS0300C | 110  |             | 0              | 0              | -447648        | -77544                   | 0                     | -77544                  | Budget and Fiscal Services | Administration | General Fund | Transfer to the Provision for Vacant Positions | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1125        | 153554         | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Personal Svcs-Contract Positions               | 
| 1393604287  | OP_BFS     | BFS0300C | 110  | 1301        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Unemployment Compensation                      | 
```