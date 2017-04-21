# Expenditures: State Agencies: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-state-agencies-fiscal-year-2013-48e21) |
| Metadata | [Link](https://data.oregon.gov/api/views/ktg5-vsgq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ktg5-vsgq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ktg5-vsgq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ktg5-vsgq |
| Name | Expenditures: State Agencies: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | agency expenditures, all agency expenditures, state agency expenditures |
| Created | 2013-12-24T01:09:54Z |
| Publication Date | 2014-02-07T16:29:42Z |

## Description

A list of expenditures for state agencies for Fiscal Year 2013. Sorted by Agency Number.

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
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ktg5-vsgq d:2013-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPARTMENT OF ADMINISTRATIVE SERVICES" m:compt_obj=3111 m:cash_expense=130275.85

series e:ktg5-vsgq d:2013-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPARTMENT OF HOUSING & COMMUNITY SERVICES" m:compt_obj=3111 m:cash_expense=1681.14

series e:ktg5-vsgq d:2013-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPT OF HUMAN SERVICES" m:compt_obj=3111 m:cash_expense=91532
```

## Meta Commands

```ls
metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=number

entity e:ktg5-vsgq l:"Expenditures: State Agencies: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/ktg5-vsgq

property e:ktg5-vsgq t:meta.view v:id=ktg5-vsgq v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: State Agencies: Fiscal Year 2013"

property e:ktg5-vsgq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ktg5-vsgq t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                 | compt_obj | compt_obj_title     | vendor_state | vendor_name                                     | cash_expense | 
| ====== | ============================ | ========= | =================== | ============ | =============================================== | ============ | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | DEPARTMENT OF ADMINISTRATIVE SERVICES           | 130275.85    | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | DEPARTMENT OF HOUSING & COMMUNITY SERVICES      | 1681.14      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | DEPT OF HUMAN SERVICES                          | 91532        | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | OREGON COMMISSION ON CHILDREN AND FAMILIES      | 6899.65      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | OREGON HEALTH AUTHORITY                         | 3144997.59   | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | OREGON HEALTH AUTHORITY PUBLIC HEALTH FINANCIAL | 41398.36     | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES   | OR           | STATE OF OREGON DEPARTMENT OF CORRECTIONS       | 5256.69      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3121      | TEMPORARY EMPLOYEES | OR           | DEPARTMENT OF HOUSING & COMMUNITY SERVICES      | 5755.05      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3121      | TEMPORARY EMPLOYEES | OR           | OREGON HEALTH AUTHORITY                         | 50116.7      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3171      | OVERTIME PAYMENTS   | OR           | OREGON HEALTH AUTHORITY                         | 10646.22     | 
```