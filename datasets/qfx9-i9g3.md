# Expenditures: Agencies: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-agencies-fiscal-year-2012-65ee5) |
| Metadata | [Link](https://data.oregon.gov/api/views/qfx9-i9g3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qfx9-i9g3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qfx9-i9g3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qfx9-i9g3 |
| Name | Expenditures: Agencies: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-13T17:48:52Z |
| Publication Date | 2012-12-13T19:11:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | agency          | AGENCY          | text      | text        |
| Yes      | series tag     | agency_title    | AGENCY_TITLE    | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | text        |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qfx9-i9g3 d:2012-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="DEPARTMENT OF ADMINISTRATIVE SERVICES" m:compt_obj=3111 m:cash_expense=148231.35

series e:qfx9-i9g3 d:2012-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="OREGON HEALTH AUTHORITY" m:compt_obj=3111 m:cash_expense=3477420.21

series e:qfx9-i9g3 d:2012-01-01T00:00:00.000Z t:vendor_state=OR t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency=100 t:compt_obj_title="REGULAR EMPLOYEES" t:vendor_name="OREGON HEALTHY AUTHORITY (FMIP)" m:compt_obj=3111 m:cash_expense=4530.52
```

## Meta Commands

```ls
metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:qfx9-i9g3 l:"Expenditures: Agencies: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/qfx9-i9g3

property e:qfx9-i9g3 t:meta.view v:id=qfx9-i9g3 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: Agencies: Fiscal Year 2012"

property e:qfx9-i9g3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:qfx9-i9g3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                 | compt_obj | compt_obj_title        | vendor_state | vendor_name                               | cash_expense | 
| ====== | ============================ | ========= | ====================== | ============ | ========================================= | ============ | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | DEPARTMENT OF ADMINISTRATIVE SERVICES     | 148231.35    | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | OREGON HEALTH AUTHORITY                   | 3477420.21   | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | OREGON HEALTHY AUTHORITY (FMIP)           | 4530.52      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | OREGON MILITARY DEPARTMENT                | 50718.75     | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | STATE OF OREGON DEPARTMENT OF CORRECTIONS | 10180.27     | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3111      | REGULAR EMPLOYEES      | OR           | STATE OF OREGON SECRETARY OF STATE        | 1548.17      | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3121      | TEMPORARY EMPLOYEES    | OR           | OREGON HEALTH AUTHORITY                   | 102690.98    | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3171      | OVERTIME PAYMENTS      | OR           | OREGON HEALTH AUTHORITY                   | 58716.21     | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3181      | SHIFT DIFFERENTIAL     | OR           | OREGON HEALTH AUTHORITY                   | 54.03        | 
| 100    | DEPARTMENT OF HUMAN SERVICES | 3190      | ALL OTHER DIFFERENTIAL | OR           | OREGON HEALTH AUTHORITY                   | 3407.21      | 
```