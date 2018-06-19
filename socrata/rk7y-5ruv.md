# Adopted FY16 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adopted-fy16-budget) |
| Metadata | [Link](https://data.honolulu.gov/api/views/rk7y-5ruv) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/rk7y-5ruv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/rk7y-5ruv/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | rk7y-5ruv |
| Name | Adopted FY16 Budget |
| Category | Finance |
| Created | 2015-06-17T16:51:47Z |
| Publication Date | 2015-06-17T16:53:41Z |

## Description

Adopted Fiscal Year 2016 Budget

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type   |
| ======== | ============== | ======================== | ======================== | ========= | ============= |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data     |
| Yes      | series tag     | department               | Department               | text      | text          |
| Yes      | series tag     | division                 | Division                 | text      | text          |
| Yes      | numeric metric | fund                     | Fund                     | number    | number        |
| Yes      | series tag     | object_code              | Object Code              | text      | calendar_date |
| Yes      | numeric metric | fy_2013_actual           | FY 2013 Actual           | money     | money         |
| Yes      | numeric metric | fy_2014_actual           | FY 2014 Actual           | money     | money         |
| Yes      | numeric metric | fy_2015_budget           | FY 2015 Budget           | money     | money         |
| Yes      | numeric metric | fy_2016_current_services | FY 2016 Current Services | money     | money         |
| Yes      | numeric metric | fy_2016_budget_issues    | FY 2016 Budget Issues    | money     | money         |
| Yes      | numeric metric | fy_2016_final_budget     | FY 2016 Final Budget     | money     | money         |
| Yes      | series tag     | department_name          | Department Name          | text      | text          |
| Yes      | series tag     | division_name            | Division Name            | text      | text          |
| Yes      | series tag     | fund_name                | Fund Name                | text      | text          |
| Yes      | series tag     | object_code_name         | Object Code Name         | text      | text          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rk7y-5ruv d:2015-06-17T09:51:54.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name=Administration t:object_code=1101-01-01T00:00:00 m:fy_2013_actual=648445 m:fy_2015_budget=854868 m:fy_2016_final_budget=896328 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=749381 m:fy_2016_current_services=896328

series e:rk7y-5ruv d:2015-06-17T09:51:54.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Adjustment for Deactivated Positions" t:division_name=Administration m:fy_2013_actual=0 m:fy_2015_budget=0 m:fy_2016_final_budget=0 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=0 m:fy_2016_current_services=0

series e:rk7y-5ruv d:2015-06-17T09:51:54.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Transfer to Prov for Vacant Positions" t:division_name=Administration t:object_code=1101-01-01T00:00:00 m:fy_2013_actual=0 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=0
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2013_actual p:double l:"FY 2013 Actual" t:dataTypeName=money

metric m:fy_2014_actual p:double l:"FY 2014 Actual" t:dataTypeName=money

metric m:fy_2015_budget p:double l:"FY 2015 Budget" t:dataTypeName=money

metric m:fy_2016_current_services p:double l:"FY 2016 Current Services" t:dataTypeName=money

metric m:fy_2016_budget_issues p:double l:"FY 2016 Budget Issues" t:dataTypeName=money

metric m:fy_2016_final_budget p:double l:"FY 2016 Final Budget" t:dataTypeName=money

entity e:rk7y-5ruv l:"Adopted FY16 Budget" t:url=https://data.honolulu.gov/api/views/rk7y-5ruv

property e:rk7y-5ruv t:meta.view v:id=rk7y-5ruv v:category=Finance v:averageRating=0 v:name="Adopted FY16 Budget"

property e:rk7y-5ruv t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:rk7y-5ruv t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code         | fy_2013_actual | fy_2014_actual | fy_2015_budget | fy_2016_current_services | fy_2016_budget_issues | fy_2016_final_budget | department_name            | division_name  | fund_name    | object_code_name                        | 
| =========== | ========== | ======== | ==== | =================== | ============== | ============== | ============== | ======================== | ===================== | ==================== | ========================== | ============== | ============ | ======================================= | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1101-01-01T00:00:00 | 648445.00      | 749381.00      | 854868.00      | 896328.00                | 0.0                   | 896328.00            | Budget and Fiscal Services | Administration | General Fund | Regular Pay                             | 
| 1434534714  | OP_BFS     | BFS0300C | 110  |                     | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Adjustment for Deactivated Positions    | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1101-01-01T00:00:00 | 0.0            | 0.0            |                |                          | 0.0                   |                      | Budget and Fiscal Services | Administration | General Fund | Transfer to Prov for Vacant Positions   | 
| 1434534714  | OP_BFS     | BFS0300C | 110  |                     | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Vacancy Cutback                         | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1102-01-01T00:00:00 | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Non-Holiday Overtime Pay                | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1106-01-01T00:00:00 | 19243.00       | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Accumulated Vacation Pay (Lump-Sum Pay) | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1107-01-01T00:00:00 | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Holiday Overtime Pay                    | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1109-01-01T00:00:00 | 15010.00       | 4289.00        | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Temporary Assignment Pay                | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1118-01-01T00:00:00 | 0.0            | 0.0            | 3460.00        | 3460.00                  | 0.0                   | 3460.00              | Budget and Fiscal Services | Administration | General Fund | Misc Salary Adjustment                  | 
| 1434534714  | OP_BFS     | BFS0300C | 110  | 1125-01-01T00:00:00 | 0.0            | 0.0            | 0.0            | 0.0                      | 0.0                   | 0.0                  | Budget and Fiscal Services | Administration | General Fund | Personal Svcs-Contract Positions        | 
```