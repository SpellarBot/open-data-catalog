# Expenditures: ESD: Wallowa: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-wallowa-fiscal-year-2014-db643) |
| Metadata | [Link](https://data.oregon.gov/api/views/kaad-v7tu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kaad-v7tu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kaad-v7tu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kaad-v7tu |
| Name | Expenditures: ESD: Wallowa: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, wallowa, fiscal year 2014 |
| Created | 2014-12-15T02:44:55Z |
| Publication Date | 2014-12-29T05:54:09Z |

## Description

Expenditures for Wallowa ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | esd          | ESD #        | text      | text        |
| Yes      | series tag     | esd_name     | ESD NAME     | text      | text        |
| Yes      | series tag     | fund_name    | FUND NAME    | text      | text        |
| Yes      | series tag     | compt_obj    | COMPT_OBJ    | text      | text        |
| Yes      | series tag     | vendor_state | VENDOR_STATE | text      | text        |
| Yes      | series tag     | vendor_name  | VENDOR_NAME  | text      | text        |
| Yes      | numeric metric | cash_expense | CASH_EXPENSE | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kaad-v7tu d:2014-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="JOSEPH SD #6" m:cash_expense=473025

series e:kaad-v7tu d:2014-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="WALLOWA SD #12" m:cash_expense=406787

series e:kaad-v7tu d:2014-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="ENTERPRISE SD #21" m:cash_expense=634727
```

## Meta Commands

```ls
metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:kaad-v7tu l:"Expenditures: ESD: Wallowa: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/kaad-v7tu

property e:kaad-v7tu t:meta.view v:id=kaad-v7tu v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Wallowa: Fiscal Year 2014"

property e:kaad-v7tu t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kaad-v7tu t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name           | fund_name        | compt_obj | vendor_state | vendor_name               | cash_expense | 
| ======= | ================== | ================ | ========= | ============ | ========================= | ============ | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | JOSEPH SD #6              | 473025.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | WALLOWA SD #12            | 406787.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | ENTERPRISE SD #21         | 634727.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | TROY SD #54               | 31571.00     | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-310  | OR           | FLINT STEARNS             | 4455.00      | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-310  | OR           | Wallowa Memorial Hospital | 755.82       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | KIM COGGINS               | 253.03       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | MELANY CRENSHAW           | 197.28       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | DONNA KIIRKMAN            | 364.79       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | LYNDA WINGO               | 292.86       | 
```