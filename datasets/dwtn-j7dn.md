# Expenditures: ESD: Inter Mountain: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-inter-mountain-fiscal-year-2014-026a7) |
| Metadata | [Link](https://data.oregon.gov/api/views/dwtn-j7dn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dwtn-j7dn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dwtn-j7dn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dwtn-j7dn |
| Name | Expenditures: ESD: Inter Mountain: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, intermountain, fiscal year 2014 |
| Created | 2014-12-16T18:07:46Z |
| Publication Date | 2014-12-30T02:57:37Z |

## Description

Expenditures for Inter Mountain ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP_CODE | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:dwtn-j7dn d:2014-01-01T00:00:00.000Z t:vendor_city=MILTON-FREEWATER t:fund_name="ADMIN SPECIAL FUND" t:vendor_zip_code=97862 t:vendor_state=OR t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:compt_obj_title="REPAIR & MAINT" t:vendor_name="HUMBERT SEPTIC SERVICE" m:compt_obj=322 m:esd=2200 m:cash_expense=910

series e:dwtn-j7dn d:2014-01-01T00:00:00.000Z t:vendor_city=MILTON-FREEWATER t:fund_name="ADMIN SPECIAL FUND" t:vendor_zip_code=97862 t:vendor_state=OR t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:compt_obj_title="REPAIR & MAINT" t:vendor_name="HUMBERT SEPTIC SERVICE" m:compt_obj=322 m:esd=2200 m:cash_expense=719

series e:dwtn-j7dn d:2014-01-01T00:00:00.000Z t:vendor_city=OMAHA t:fund_name="ADMIN SPECIAL FUND" t:vendor_zip_code=68103-2818 t:vendor_state=NE t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:compt_obj_title="REPAIR & MAINT" t:vendor_name="FIRST BANKCARD" m:compt_obj=322 m:esd=2200 m:cash_expense=80.42
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:dwtn-j7dn l:"Expenditures: ESD: Inter Mountain: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/dwtn-j7dn

property e:dwtn-j7dn t:meta.view v:id=dwtn-j7dn v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Inter Mountain: Fiscal Year 2014"

property e:dwtn-j7dn t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:dwtn-j7dn t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                 | fund_name          | compt_obj | compt_obj_title           | vendor_name                         | vendor_address                      | vendor_city          | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ======================================== | ================== | ========= | ========================= | =================================== | =================================== | ==================== | ============ | =============== | ============ | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 322       | REPAIR & MAINT            | HUMBERT SEPTIC SERVICE              | PO BOX 139                          | MILTON-FREEWATER     | OR           | 97862           | 910.00       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 322       | REPAIR & MAINT            | HUMBERT SEPTIC SERVICE              | PO BOX 139                          | MILTON-FREEWATER     | OR           | 97862           | 719.00       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 322       | REPAIR & MAINT            | FIRST BANKCARD                      | PO BOX 2818                         | OMAHA                | NE           | 68103-2818      | 80.42        | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 165.52       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 146.92       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 134.67       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 115.19       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 102.30       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 99.43        | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ADMIN SPECIAL FUND | 325       | ELECTRICITY               | UMATILLA ELECTRIC COOPERATIVE       | PO BOX 1148                         | HERMISTON            | OR           | 97838-1148      | 83.84        | 
```