# Expenditures: ESD: Northwest Regional: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-northwest-regional-fiscal-year-2013-fd744) |
| Metadata | [Link](https://data.oregon.gov/api/views/gbtj-rjg2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/gbtj-rjg2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/gbtj-rjg2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | gbtj-rjg2 |
| Name | Expenditures: ESD: Northwest Regional: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, northwest regional, nw regional, fiscal year 2013 |
| Created | 2013-11-04T20:20:09Z |
| Publication Date | 2013-11-04T20:23:24Z |

## Description

Expenditures for Northwest Regional ESD for Fiscal Year 2013

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
| Yes      | series tag     | cash_expense    | CASH_EXPENSE    | text      | text        |
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
series e:gbtj-rjg2 d:2013-01-01T00:00:00.000Z t:vendor_city=ASTORIA t:fund_name="GENERAL FUNDS" t:vendor_zip_code=97103 t:vendor_state=OR t:esd_name="NW REGIONAL ESD" t:cash_expense="* 65.50" t:compt_obj_title="REPAIR & MAINTENANCE SVCS" t:vendor_name="A COASTAL LOCK-N-KEY" m:compt_obj=322 m:esd=2240

series e:gbtj-rjg2 d:2013-01-01T00:00:00.000Z t:vendor_city=ASTORIA t:fund_name="GENERAL FUNDS" t:vendor_zip_code=97103 t:vendor_state=OR t:esd_name="NW REGIONAL ESD" t:cash_expense="* 139.95" t:compt_obj_title="REPAIR & MAINTENANCE SVCS" t:vendor_name="A COASTAL LOCK-N-KEY" m:compt_obj=322 m:esd=2240

series e:gbtj-rjg2 d:2013-01-01T00:00:00.000Z t:vendor_city=PORTLAND t:fund_name="TUITION REIMBURSEMENT" t:vendor_zip_code=97214 t:vendor_state=OR t:esd_name="NW REGIONAL ESD" t:cash_expense="* 15.00" t:compt_obj_title="OTH EMPLOYEE BENEFIT - LICENSED" t:vendor_name="ABBENHAUS, MARK" m:compt_obj=247 m:esd=2240
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

entity e:gbtj-rjg2 l:"Expenditures: ESD: Northwest Regional: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/gbtj-rjg2

property e:gbtj-rjg2 t:meta.view v:id=gbtj-rjg2 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Northwest Regional: Fiscal Year 2013"

property e:gbtj-rjg2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:gbtj-rjg2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name        | fund_name                 | compt_obj | compt_obj_title                 | vendor_name                        | vendor_address  | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | =============== | ========================= | ========= | =============================== | ================================== | =============== | =========== | ============ | =============== | ============ | 
| 2240 | NW REGIONAL ESD | GENERAL FUNDS             | 322       | REPAIR & MAINTENANCE SVCS       | A COASTAL LOCK-N-KEY               | 49 7TH STREET   | ASTORIA     | OR           | 97103           | * 65.50      | 
| 2240 | NW REGIONAL ESD | GENERAL FUNDS             | 322       | REPAIR & MAINTENANCE SVCS       | A COASTAL LOCK-N-KEY               | 49 7TH STREET   | ASTORIA     | OR           | 97103           | * 139.95     | 
| 2240 | NW REGIONAL ESD | TUITION REIMBURSEMENT     | 247       | OTH EMPLOYEE BENEFIT - LICENSED | ABBENHAUS, MARK                    | 403 SE 30TH AVE | PORTLAND    | OR           | 97214           | * 15.00      | 
| 2240 | NW REGIONAL ESD | GENERAL FUNDS             | 344       | CONFERENCE REGISTR FEES         | ABC FOR LIFE TRAINING CENTER       | 51704 SE 4TH ST | SCAPPOOSE   | OR           | 97056           | * 225.00     | 
| 2240 | NW REGIONAL ESD | GENERAL FUNDS             | 310       | INSTR PROF TECH SVCS            | ABC FOR LIFE TRAINING CENTER       | 51704 SE 4TH ST | SCAPPOOSE   | OR           | 97056           | * 225.00     | 
| 2240 | NW REGIONAL ESD | EARLY INTERVENTION        | 310       | INSTR PROF TECH SVCS            | A-BEST APPLIANCE INC               | 127 SE BASELINE | HILLSBORO   | OR           | 97123           | * (25.00)    | 
| 2240 | NW REGIONAL ESD | EARLY INTERVENTION        | 310       | INSTR PROF TECH SVCS            | A-BEST APPLIANCE INC               | 127 SE BASELINE | HILLSBORO   | OR           | 97123           | * 25.00      | 
| 2240 | NW REGIONAL ESD | CONTRACTED MOTOR SERVICES | 410       | CONSUMABLE MATER/SUPPLIES       | ABILITATIONS/SCHOOL SPECIALTY INC. | MB UNIT 67-3106 | CHICAGO     | IL           | 60695-3106      | * 27.59      | 
| 2240 | NW REGIONAL ESD | CONTRACTED MOTOR SERVICES | 410       | CONSUMABLE MATER/SUPPLIES       | ABILITATIONS/SCHOOL SPECIALTY INC. | MB UNIT 67-3106 | CHICAGO     | IL           | 60695-3106      | * 27.59      | 
| 2240 | NW REGIONAL ESD | EARLY INTERVENTION        | 410       | CONSUMABLE MATER/SUPPLIES       | ABILITATIONS/SCHOOL SPECIALTY INC. | MB UNIT 67-3106 | CHICAGO     | IL           | 60695-3106      | * (9.84)     | 
```