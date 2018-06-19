# Expenditures: ESD: Northwest Regional: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-northwest-regional-fiscal-year-2014-83b7d) |
| Metadata | [Link](https://data.oregon.gov/api/views/s4ki-sam2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/s4ki-sam2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/s4ki-sam2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | s4ki-sam2 |
| Name | Expenditures: ESD: Northwest Regional: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, northwest regional, nw regional, fiscal year 2014 |
| Created | 2014-12-16T21:45:59Z |
| Publication Date | 2014-12-29T06:14:59Z |

## Description

Expenditures for Northwest Regional ESD for Fiscal Year 2014

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
| Yes      | series tag     | vendor_state    | VENDOR-STATE    | text      | text        |
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
series e:s4ki-sam2 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN JOSE" t:fund_name="SPEECH PATHOLOGY" t:vendor_zip_code=95014 t:vendor_state=CA t:esd_name="NORTHWEST REGIONAL ESD" t:compt_obj_title="INSTR PROF TECH SVCS" t:vendor_name="360 DEGREE CUSTOMER INC" m:compt_obj=310 m:esd=2240 m:cash_expense=7800

series e:s4ki-sam2 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN JOSE" t:fund_name="SPEECH PATHOLOGY" t:vendor_zip_code=95014 t:vendor_state=CA t:esd_name="NORTHWEST REGIONAL ESD" t:compt_obj_title="INSTR PROF TECH SVCS" t:vendor_name="360 DEGREE CUSTOMER INC" m:compt_obj=310 m:esd=2240 m:cash_expense=11400

series e:s4ki-sam2 d:2014-01-01T00:00:00.000Z t:vendor_city=PORTLAND t:fund_name="EMOTIONALLY DISTURBED" t:vendor_zip_code=97215 t:vendor_state=OR t:esd_name="NORTHWEST REGIONAL ESD" t:compt_obj_title="STUDENT TRAVEL OUT/DIST" t:vendor_name="ABBENHAUS, MARK" m:compt_obj=343 m:esd=2240 m:cash_expense=7
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:s4ki-sam2 l:"Expenditures: ESD: Northwest Regional: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/s4ki-sam2

property e:s4ki-sam2 t:meta.view v:id=s4ki-sam2 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Northwest Regional: Fiscal Year 2014"

property e:s4ki-sam2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:s4ki-sam2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name               | fund_name               | compt_obj | compt_obj_title           | vendor_name                       | vendor_address     | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ====================== | ======================= | ========= | ========================= | ================================= | ================== | =========== | ============ | =============== | ============ | 
| 2240 | NORTHWEST REGIONAL ESD | SPEECH PATHOLOGY        | 310       | INSTR PROF TECH SVCS      | 360 DEGREE CUSTOMER INC           | 4423 FORTRAN DRIVE | SAN JOSE    | CA           | 95014           | 7800.00      | 
| 2240 | NORTHWEST REGIONAL ESD | SPEECH PATHOLOGY        | 310       | INSTR PROF TECH SVCS      | 360 DEGREE CUSTOMER INC           | 4423 FORTRAN DRIVE | SAN JOSE    | CA           | 95014           | 11400.00     | 
| 2240 | NORTHWEST REGIONAL ESD | EMOTIONALLY DISTURBED   | 343       | STUDENT TRAVEL OUT/DIST   | ABBENHAUS, MARK                   | 1932 SE 52nd AVE   | PORTLAND    | OR           | 97215           | 7.00         | 
| 2240 | NORTHWEST REGIONAL ESD | EMOTIONALLY DISTURBED   | 411       | CATERING & FOOD SUPPLIES  | ABBENHAUS, MARK                   | 1932 SE 52nd AVE   | PORTLAND    | OR           | 97215           | 27.97        | 
| 2240 | NORTHWEST REGIONAL ESD | EARLY INTERVENTION      | 460       | NONCONSUMABLE ITEMS       | ABLENET INC                       | 2625 PATTON ROAD   | ROSEVILLE   | MN           | 55113-0000      | 415.80       | 
| 2240 | NORTHWEST REGIONAL ESD | AC/AT CONTRACT SERVICES | 470       | COMPUTER SOFTWARE         | ABLENET INC                       | 2625 PATTON ROAD   | ROSEVILLE   | MN           | 55113-0000      | 179.00       | 
| 2240 | NORTHWEST REGIONAL ESD | AC/AT CONTRACT SERVICES | 470       | COMPUTER SOFTWARE         | ABLENET INC                       | 2625 PATTON ROAD   | ROSEVILLE   | MN           | 55113-0000      | 17.90        | 
| 2240 | NORTHWEST REGIONAL ESD | GENERAL FUNDS           | 341       | IN DISTRICT MTG/TRAVEL    | ABNEY, BRANDI M                   | 1313 CHERRY ST     | VERNONIA    | OR           | 97064           | 32.77        | 
| 2240 | NORTHWEST REGIONAL ESD | LOW INCIDENCE REGIONAL  | 410       | CONSUMABLE MATER/SUPPLIES | ACADEMIC THERAPY PUBLICATIONS INC | 20 COMMERCIAL BLVD | NOVATO      | CA           | 94949-6191      | 64.00        | 
| 2240 | NORTHWEST REGIONAL ESD | LOW INCIDENCE REGIONAL  | 410       | CONSUMABLE MATER/SUPPLIES | ACADEMIC THERAPY PUBLICATIONS INC | 20 COMMERCIAL BLVD | NOVATO      | CA           | 94949-6191      | 6.40         | 
```