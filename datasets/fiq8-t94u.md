# Expenditures: State Agencies: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-state-agencies-fiscal-year-2014) |
| Metadata | [Link](https://data.oregon.gov/api/views/fiq8-t94u) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fiq8-t94u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fiq8-t94u/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fiq8-t94u |
| Name | Expenditures: State Agencies: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | agency expenditures, all agency expenditures, state agency expenditures 2014, 2014 |
| Created | 2014-12-26T18:14:29Z |
| Publication Date | 2014-12-26T18:28:41Z |

## Description

A list of expenditures for state agencies for Fiscal Year 2014. Sorted by Agency Number.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                            | Data Type | Render Type |
| ======== | ============== | ============================ | =============================== | ========= | =========== |
| Yes      | series tag     | agency_number                | AGENCY_NUMBER                   | text      | number      |
| Yes      | series tag     | agency_title                 | AGENCY_TITLE                    | text      | text        |
| Yes      | series tag     | compt_obj_account_number     | COMPT_OBJ_ (Account Number)     | text      | number      |
| Yes      | series tag     | compt_obj_title_account_name | COMPT_OBJ_TITLE_ (Account Name) | text      | text        |
| Yes      | series tag     | vendor_state                 | VENDOR_STATE                    | text      | text        |
| Yes      | series tag     | vendor_name                  | VENDOR_NAME                     | text      | text        |
| Yes      | numeric metric | cash_expense                 | CASH_EXPENSE                    | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fiq8-t94u d:2014-01-01T00:00:00.000Z t:vendor_state=OR t:compt_obj_account_number=4101 t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency_number=100 t:vendor_name="ACACIA MCGUIRE ANDERSON" t:compt_obj_title_account_name="INSTATE MEALS WITH OVERNIGHT STAY" m:cash_expense=542.5

series e:fiq8-t94u d:2014-01-01T00:00:00.000Z t:vendor_state=OR t:compt_obj_account_number=4101 t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency_number=100 t:vendor_name="ADELAIDA SOLIS TORRES" t:compt_obj_title_account_name="INSTATE MEALS WITH OVERNIGHT STAY" m:cash_expense=195.5

series e:fiq8-t94u d:2014-01-01T00:00:00.000Z t:vendor_state=WA t:compt_obj_account_number=4101 t:agency_title="DEPARTMENT OF HUMAN SERVICES" t:agency_number=100 t:vendor_name="ADELAIDA SOLIS TORRES" t:compt_obj_title_account_name="INSTATE MEALS WITH OVERNIGHT STAY" m:cash_expense=80.5
```

## Meta Commands

```ls
metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=number

entity e:fiq8-t94u l:"Expenditures: State Agencies: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/fiq8-t94u

property e:fiq8-t94u t:meta.view v:id=fiq8-t94u v:category="Revenue & Expense" v:averageRating=100 v:name="Expenditures: State Agencies: Fiscal Year 2014"

property e:fiq8-t94u t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:fiq8-t94u t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_title                 | compt_obj_account_number | compt_obj_title_account_name      | vendor_state | vendor_name             | cash_expense | 
| ============= | ============================ | ======================== | ================================= | ============ | ======================= | ============ | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ACACIA MCGUIRE ANDERSON | 542.5        | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ADELAIDA SOLIS TORRES   | 195.5        | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | WA           | ADELAIDA SOLIS TORRES   | 80.5         | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ADELAIDE L TURNER       | 650.25       | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ADREA KORTHASE          | 150.25       | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ADRIENNE BINAM          | 1948.75      | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | AIMEE DICKSON           | 126.5        | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ALBA MARROQUIN          | 69           | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ALEC ESQUIVEL           | 135          | 
| 100           | DEPARTMENT OF HUMAN SERVICES | 4101                     | INSTATE MEALS WITH OVERNIGHT STAY | OR           | ALEX T SIMS             | 69           | 
```