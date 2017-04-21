# Expenditures: ESD: Wallowa: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-wallowa-fiscal-year-2013-3f57c) |
| Metadata | [Link](https://data.oregon.gov/api/views/t5rp-2s8a) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/t5rp-2s8a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/t5rp-2s8a/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | t5rp-2s8a |
| Name | Expenditures: ESD: Wallowa: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, wallowa, fiscal year 2013 |
| Created | 2013-10-31T18:53:13Z |
| Publication Date | 2013-10-31T18:56:53Z |

## Description

Expenditures for Wallowa ESD for Fiscal Year 2013

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t5rp-2s8a d:2013-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="JOSEPH SD #6" m:cash_expense=447673

series e:t5rp-2s8a d:2013-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="WALLOWA SD #12" m:cash_expense=393943

series e:t5rp-2s8a d:2013-01-01T00:00:00.000Z t:fund_name="100/General Fund" t:vendor_state=OR t:esd_name="Wallowa County ESD" t:compt_obj=1131-380 t:esd="ESD #18" t:vendor_name="ENTERPRISE SD #21" m:cash_expense=569842
```

## Meta Commands

```ls
metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:t5rp-2s8a l:"Expenditures: ESD: Wallowa: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/t5rp-2s8a

property e:t5rp-2s8a t:meta.view v:id=t5rp-2s8a v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Wallowa: Fiscal Year 2013"

property e:t5rp-2s8a t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:t5rp-2s8a t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name           | fund_name        | compt_obj | vendor_state | vendor_name       | cash_expense | 
| ======= | ================== | ================ | ========= | ============ | ================= | ============ | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | JOSEPH SD #6      | 447673.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | WALLOWA SD #12    | 393943.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | ENTERPRISE SD #21 | 569842.00    | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1131-380  | OR           | TROY SD #54       | 27937.00     | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-310  | OR           | FLINT STEARNS     | 4950.00      | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | KIM COGGINS       | 76.00        | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | HILTON HOTEL      | 262.99       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-342  | OR           | KRISTEN ALBEE     | 557.52       | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-390  | OR           | DEPT. HUMAN SERV. | 24668.25     | 
| ESD #18 | Wallowa County ESD | 100/General Fund | 1250-410  | OR           | CLOUD 9 BAKERY    | 64.75        | 
```