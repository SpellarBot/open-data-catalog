# Expenditures: ESD: Willamette: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-willamette-fiscal-year-2014-81da3) |
| Metadata | [Link](https://data.oregon.gov/api/views/4pvu-rrgj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4pvu-rrgj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4pvu-rrgj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4pvu-rrgj |
| Name | Expenditures: ESD: Willamette: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, willamette, fiscal year 2014 |
| Created | 2014-12-16T17:30:58Z |
| Publication Date | 2014-12-29T06:00:58Z |

## Description

Expenditures for Willamette ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD NAME        | text      | text        |
| Yes      | series tag     | fund_name       | FUND NAME       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR ZIP CODE | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH EXPENSE    | money     | money       |
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
series e:4pvu-rrgj d:2014-01-01T00:00:00.000Z t:vendor_city=SALEM t:fund_name=OMESC t:vendor_zip_code=97306 t:vendor_state=OR t:esd_name="Willamette ESD" t:compt_obj_title="CONF/WRKSHPS/RELATED TRVL" t:vendor_name="CYE A FINK" m:compt_obj=340 m:esd=2117 m:cash_expense=33.9

series e:4pvu-rrgj d:2014-01-01T00:00:00.000Z t:vendor_city=SALEM t:fund_name=OMESC t:vendor_zip_code=97302 t:vendor_state=OR t:esd_name="Willamette ESD" t:compt_obj_title="INST/PROF/TECH SERVICES" t:vendor_name="XOCHITL MAURICIO ESCALANTE" m:compt_obj=310 m:esd=2117 m:cash_expense=-375

series e:4pvu-rrgj d:2014-01-01T00:00:00.000Z t:vendor_city=SALEM t:fund_name="YCEP OLDER YOUTH-OYA" t:vendor_zip_code=97301-3765 t:vendor_state=OR t:esd_name="Willamette ESD" t:compt_obj_title="CONSUMB SUP MAT" t:vendor_name="OREGON YOUTH AUTHORITY" m:compt_obj=410 m:esd=2117 m:cash_expense=5.33
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:"CASH EXPENSE" t:dataTypeName=money

entity e:4pvu-rrgj l:"Expenditures: ESD: Willamette: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/4pvu-rrgj

property e:4pvu-rrgj t:meta.view v:id=4pvu-rrgj v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Willamette: Fiscal Year 2014"

property e:4pvu-rrgj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:4pvu-rrgj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name       | fund_name            | compt_obj | compt_obj_title           | vendor_name                        | vendor_address           | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ============== | ==================== | ========= | ========================= | ================================== | ======================== | =========== | ============ | =============== | ============ | 
| 2117 | Willamette ESD | OMESC                | 340       | CONF/WRKSHPS/RELATED TRVL | CYE A FINK                         | 3250 SUMAC DR. S.        | SALEM       | OR           | 97306           | 33.90        | 
| 2117 | Willamette ESD | OMESC                | 310       | INST/PROF/TECH SERVICES   | XOCHITL MAURICIO ESCALANTE         | C/O OMESC                | SALEM       | OR           | 97302           | -375.00      | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT           | OREGON YOUTH AUTHORITY             | 530 CENTER ST NE STE 200 | SALEM       | OR           | 97301-3765      | 5.33         | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT           | OREGON YOUTH AUTHORITY             | 530 CENTER ST NE STE 200 | SALEM       | OR           | 97301-3765      | 113.18       | 
| 2117 | Willamette ESD | OMESC                | 349       | OTHER TRAVEL              | HIGH DESERT EDUCATION SERVICE DIST | 145 SE SALMON ST SUITE A | REDMOND     | OR           | 97756           | 166.72       | 
| 2117 | Willamette ESD | OMESC                | 349       | OTHER TRAVEL              | HIGH DESERT EDUCATION SERVICE DIST | 145 SE SALMON ST SUITE A | REDMOND     | OR           | 97756           | 166.72       | 
| 2117 | Willamette ESD | OMESC                | 349       | OTHER TRAVEL              | HIGH DESERT EDUCATION SERVICE DIST | 145 SE SALMON ST SUITE A | REDMOND     | OR           | 97756           | 183.39       | 
| 2117 | Willamette ESD | OMESC                | 355       | PRINTING BINDING          | XEROX CORPORATION                  | PO BOX 101235            | PASADENA    | CA           | 91189-0005      | 68.20        | 
| 2117 | Willamette ESD | OMESC                | 355       | PRINTING BINDING          | XEROX CORPORATION                  | PO BOX 101235            | PASADENA    | CA           | 91189-0005      | 25.19        | 
| 2117 | Willamette ESD | OMESC                | 355       | PRINTING BINDING          | XEROX CORPORATION                  | PO BOX 101235            | PASADENA    | CA           | 91189-0005      | 68.20        | 
```