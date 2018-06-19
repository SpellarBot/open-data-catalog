# Expenditures: ESD: InterMountain: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-intermountain-fiscal-year-2013-eb5a0) |
| Metadata | [Link](https://data.oregon.gov/api/views/6tta-i2fd) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6tta-i2fd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6tta-i2fd/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6tta-i2fd |
| Name | Expenditures: ESD: InterMountain: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, intermountain, fiscal year 2013 |
| Created | 2013-10-31T18:24:47Z |
| Publication Date | 2013-10-31T18:29:58Z |

## Description

Expenditures for InterMountain ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | object          | OBJECT          | number    | number      |
| Yes      | series tag     | object_title    | OBJECT TITLE    | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP_CODE | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = vendor_address
```

## Data Commands

```ls
series e:6tta-i2fd d:2013-01-01T00:00:00.000Z t:vendor_city=CHICAGO t:fund_name="MIGRANT SPECIAL FUNDS" t:vendor_zip_code=60673-1253 t:vendor_state=IL t:object_title="CONSUM SUPPLIES" t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:vendor_name="4IMPRINT INC" m:esd=2200 m:object=410 m:cash_expense=1555.84

series e:6tta-i2fd d:2013-01-01T00:00:00.000Z t:vendor_city="WALLA WALLA" t:fund_name="CAPITAL PROJECTS" t:vendor_zip_code=99362 t:vendor_state=WA t:object_title="REPAIR & MAINT" t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:vendor_name="A QUALITY SEALCOATING, LLC" m:esd=2200 m:object=322 m:cash_expense=9743

series e:6tta-i2fd d:2013-01-01T00:00:00.000Z t:vendor_city=DALLAS t:fund_name="GENERAL FUND" t:vendor_zip_code=75267-7530 t:vendor_state=TX t:object_title="COMP SFTWRE" t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:vendor_name="ACCUVANT, INC." m:esd=2200 m:object=470 m:cash_expense=25200
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:object p:integer l:OBJECT t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:6tta-i2fd l:"Expenditures: ESD: InterMountain: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/6tta-i2fd

property e:6tta-i2fd t:meta.view v:id=6tta-i2fd v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: InterMountain: Fiscal Year 2013"

property e:6tta-i2fd t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6tta-i2fd t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                 | fund_name             | object | object_title              | vendor_name                         | vendor_address                      | vendor_city          | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ======================================== | ===================== | ====== | ========================= | =================================== | =================================== | ==================== | ============ | =============== | ============ | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | MIGRANT SPECIAL FUNDS | 410    | CONSUM SUPPLIES           | 4IMPRINT INC                        | 25303 NETWORK PLACE                 | CHICAGO              | IL           | 60673-1253      | 1555.84      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | CAPITAL PROJECTS      | 322    | REPAIR & MAINT            | A QUALITY SEALCOATING, LLC          | 2345 HOOD PLACE                     | WALLA WALLA          | WA           | 99362           | 9743.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | GENERAL FUND          | 470    | COMP SFTWRE               | ACCUVANT, INC.                      | PO BOX 677530                       | DALLAS               | TX           | 75267-7530      | 25200.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 290.07       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 234.27       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 159.27       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 116.50       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 113.00       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 111.02       | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | TITLE 1C CURRENT YR   | 341    | TRV IN-DIST               | ACENETH PALOMARES                   | 314 SW 14TH ST                      | PENDLETON            | OR           | 97801           | 107.35       | 
```