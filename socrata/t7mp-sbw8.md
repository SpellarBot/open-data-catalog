# 2016 - State Agencies Expenditures Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-state-agencies-expenditures-report) |
| Metadata | [Link](https://data.oregon.gov/api/views/t7mp-sbw8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/t7mp-sbw8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/t7mp-sbw8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | t7mp-sbw8 |
| Name | 2016 - State Agencies Expenditures Report |
| Category | Revenue & Expense |
| Tags | 2016, agency expenditures, all agency expenditures, state agency expenditures |
| Created | 2016-12-05T21:03:24Z |
| Publication Date | 2016-12-05T21:20:03Z |

## Description

This is a list of expenditures for state agencies for Fiscal Year 2016, sorted by Agency Number. For more information go to: http://www.oregon.gov/transparency/Pages/expenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | agency          | AGENCY          | text      | number      |
| Yes      | series tag     | agency_title    | AGENCY_TITLE    | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t7mp-sbw8 d:2016-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="BOARD OF ACCOUNTANCY" m:compt_obj=3111 m:cash_expense=19736.02

series e:t7mp-sbw8 d:2016-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPARTMENT OF ADMINISTRATIVE SERVICES" m:compt_obj=3111 m:cash_expense=141492.33

series e:t7mp-sbw8 d:2016-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPT OF HUMAN SERVICES" m:compt_obj=3111 m:cash_expense=3752.65
```

## Meta Commands

```ls
metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:t7mp-sbw8 l:"2016 - State Agencies Expenditures Report" t:url=https://data.oregon.gov/api/views/t7mp-sbw8

property e:t7mp-sbw8 t:meta.view v:id=t7mp-sbw8 v:category="Revenue & Expense" v:averageRating=0 v:name="2016 - State Agencies Expenditures Report"

property e:t7mp-sbw8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:t7mp-sbw8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                 | compt_obj | compt_obj_title     | vendor_state | vendor_name                               | cash_expense | 
| ====== | ============================ | ========= | =================== | ============ | ========================================= | ============ | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | BOARD OF ACCOUNTANCY                      | 19736.02     | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | DEPARTMENT OF ADMINISTRATIVE SERVICES     | 141492.33    | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | DEPT OF HUMAN SERVICES                    | 3752.65      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | EMPLOYMENT DEPARTMENT                     | 3862.89      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | OREGON HEALTH AUTHORITY                   | 598334.54    | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | OREGON PUBLIC EMPLOYEES RETIREMENT SYSTEM | 2481.60      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | STATE OF OREGON DEPARTMENT OF CORRECTIONS | 2302.57      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3121      | TEMPORARY EMPLOYEES | OR           | OREGON HEALTH AUTHORITY                   | 7007.35      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3171      | OVERTIME PAYMENTS   | OR           | OREGON HEALTH AUTHORITY                   | 253.59       | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3181      | SHIFT DIFFERENTIAL  | OR           | OREGON HEALTH AUTHORITY                   | 2.03         | 
```