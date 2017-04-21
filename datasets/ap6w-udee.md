# Expenditures: ESD: Columbia Gorge: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-columbia-gorge-fiscal-year-2014-b274b) |
| Metadata | [Link](https://data.oregon.gov/api/views/ap6w-udee) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ap6w-udee/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ap6w-udee/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ap6w-udee |
| Name | Expenditures: ESD: Columbia Gorge: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, columbia gorge, fiscal year 2014 |
| Created | 2014-12-16T19:14:49Z |
| Publication Date | 2014-12-29T06:08:23Z |

## Description

ESD Expenditures for Columbia Gorge during Fiscal Year 2014.

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
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP_CODE | text      | number      |
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
series e:ap6w-udee d:2014-01-01T00:00:00.000Z t:vendor_city="THE DALLES" t:fund_name="PUBLIC INFORMATION SERVICES" t:vendor_zip_code=97058 t:vendor_state=OR t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="CONSUMABLE SUPPLIES" t:vendor_name="AERO PRINT INC." m:compt_obj=410 m:esd=2223 m:cash_expense=89.95

series e:ap6w-udee d:2014-01-01T00:00:00.000Z t:vendor_city="THE DALLES" t:fund_name="RAINY DAY FUND" t:vendor_zip_code=97058 t:vendor_state=OR t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="CONSUMABLE SUPPLIES" t:vendor_name="AERO PRINT INC." m:compt_obj=410 m:esd=2223 m:cash_expense=220.5

series e:ap6w-udee d:2014-01-01T00:00:00.000Z t:vendor_city=PORTLAND t:fund_name="ALDER DATA QUALITY PROJECT" t:vendor_zip_code=97230 t:vendor_state=OR t:esd_name="COLUMBIA GORGE EDUCATION SERVICE DISTRICT" t:compt_obj_title="INSTRUCTIONAL PROGRAM IMPROVEMENT SERVICES" t:vendor_name="AMY MCQUEEN" m:compt_obj=312 m:esd=2223 m:cash_expense=1
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:ap6w-udee l:"Expenditures: ESD: Columbia Gorge: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/ap6w-udee

property e:ap6w-udee t:meta.view v:id=ap6w-udee v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Columbia Gorge: Fiscal Year 2014"

property e:ap6w-udee t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ap6w-udee t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                  | fund_name                               | compt_obj | compt_obj_title                            | vendor_name                     | vendor_address         | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ========================================= | ======================================= | ========= | ========================================== | =============================== | ====================== | =========== | ============ | =============== | ============ | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | PUBLIC INFORMATION SERVICES             | 410       | CONSUMABLE SUPPLIES                        | AERO PRINT INC.                 | 308 EAST SECOND STREET | THE DALLES  | OR           | 97058           | 89.95        | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | RAINY DAY FUND                          | 410       | CONSUMABLE SUPPLIES                        | AERO PRINT INC.                 | 308 EAST SECOND STREET | THE DALLES  | OR           | 97058           | 220.50       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | ALDER DATA QUALITY PROJECT              | 312       | INSTRUCTIONAL PROGRAM IMPROVEMENT SERVICES | AMY MCQUEEN                     | 3015 NE 122ND AVENUE   | PORTLAND    | OR           | 97230           | 1.00         | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | ACCOUNTS RECEIVABLE                     | 153       | ACCOUNTS RECEIVABLE                        | CAITLIN ANDERSEN                | 1004 WEST EIGHTH PLACE | THE DALLES  | OR           | 97058           | 205.66       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | ACCOUNTS RECEIVABLE                     | 153       | ACCOUNTS RECEIVABLE                        | ASBO INTERNATIONAL              | 39912 TREASURY CIRCLE  | CHICAGO     | IL           | 60694           | 1020.00      | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | MIGRANT EDUCATION-SUMMER SCHOOL PROGRAM | 410       | CONSUMABLE SUPPLIES                        | BANK OF AMERICA COMMERCIAL CARD | PO BOX 15731           | WILMINGTON  | DE           | 19886           | 164.87       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | HUMAN RESOURCES/STAFF SERVICES          | 410       | CONSUMABLE SUPPLIES                        | BANK OF AMERICA COMMERCIAL CARD | PO BOX 15731           | WILMINGTON  | DE           | 19886           | 412.50       | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | HUMAN RESOURCES/STAFF SERVICES          | 410       | CONSUMABLE SUPPLIES                        | BANK OF AMERICA COMMERCIAL CARD | PO BOX 15731           | WILMINGTON  | DE           | 19886           | 30.00        | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | HUMAN RESOURCES/STAFF SERVICES          | 410       | CONSUMABLE SUPPLIES                        | BANK OF AMERICA COMMERCIAL CARD | PO BOX 15731           | WILMINGTON  | DE           | 19886           | 8.17         | 
| 2223 | COLUMBIA GORGE EDUCATION SERVICE DISTRICT | NATIVE AMERICAN EDUCATION-TITLE VII/JOM | 410       | CONSUMABLE SUPPLIES                        | BANK OF AMERICA COMMERCIAL CARD | PO BOX 15731           | WILMINGTON  | DE           | 19886           | 38.50        | 
```