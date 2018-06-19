# Expenditures: ESD: Malheur: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-malheur-fiscal-year-2014-c4996) |
| Metadata | [Link](https://data.oregon.gov/api/views/9qsb-krjy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9qsb-krjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9qsb-krjy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9qsb-krjy |
| Name | Expenditures: ESD: Malheur: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, malheur esd, malheur esd expenditures, malheur educational service district |
| Created | 2014-12-15T08:24:13Z |
| Publication Date | 2014-12-29T05:57:41Z |

## Description

A list of expenditures for Malheur Educational Service District for Fiscal Year 2014

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
| Yes      | series tag     | vendor_zip      | VENDOR_ZIP      | text      | number      |
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
series e:9qsb-krjy d:2014-01-01T00:00:00.000Z t:vendor_city=MIDDLETON t:fund_name="SPECIAL REVENUE FUNDS" t:vendor_state=ID t:esd_name="MALHEUR ESD RGN 14" t:vendor_zip=83644 t:compt_obj_title="PURCHASED SERVICES" t:vendor_name="SPA COMMUNICATION LLC" m:compt_obj=310 m:esd=2106 m:cash_expense=3450

series e:9qsb-krjy d:2014-01-01T00:00:00.000Z t:vendor_city=MIDDLETON t:fund_name="GENERAL FUND" t:vendor_state=ID t:esd_name="MALHEUR ESD RGN 14" t:vendor_zip=83644 t:compt_obj_title="PURCHASED SERVICES" t:vendor_name="SPA COMMUNICATION LLC" m:compt_obj=310 m:esd=2106 m:cash_expense=2100

series e:9qsb-krjy d:2014-01-01T00:00:00.000Z t:vendor_city=MIDDLETON t:fund_name="GENERAL FUND" t:vendor_state=ID t:esd_name="MALHEUR ESD RGN 14" t:vendor_zip=83644 t:compt_obj_title="PURCHASED SERVICES" t:vendor_name="SPA COMMUNICATION LLC" m:compt_obj=310 m:esd=2106 m:cash_expense=1575
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:9qsb-krjy l:"Expenditures: ESD: Malheur: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/9qsb-krjy

property e:9qsb-krjy t:meta.view v:id=9qsb-krjy v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Malheur: Fiscal Year 2014"

property e:9qsb-krjy t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:9qsb-krjy t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name           | fund_name             | compt_obj | compt_obj_title    | vendor_name           | vendor_address    | vendor_city | vendor_state | vendor_zip | cash_expense | 
| ==== | ================== | ===================== | ========= | ================== | ===================== | ================= | =========== | ============ | ========== | ============ | 
| 2106 | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 3450.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 2100.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 1575.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 1725.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 1050.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 2250.00      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 1762.50      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 3937.50      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 5437.50      | 
| 2106 | MALHEUR ESD RGN 14 | GENERAL FUND          | 310       | PURCHASED SERVICES | SPA COMMUNICATION LLC | 23 E 1ST STREET N | MIDDLETON   | ID           | 83644      | 3975.00      | 
```