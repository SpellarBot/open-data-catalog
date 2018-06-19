# Expenditures: ESD: Willamette: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-willamette-fiscal-year-2013-18e30) |
| Metadata | [Link](https://data.oregon.gov/api/views/wnky-6kuz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wnky-6kuz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wnky-6kuz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wnky-6kuz |
| Name | Expenditures: ESD: Willamette: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, willamette, fiscal year 2013 |
| Created | 2013-10-30T20:31:09Z |
| Publication Date | 2013-10-30T20:34:43Z |

## Description

Expenditures for Willamette ESD for Fiscal Year 2013

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
| Yes      | numeric metric | cash_expense    | CASH EXPENSE    | number    | number      |
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
series e:wnky-6kuz d:2013-01-01T00:00:00.000Z t:vendor_city=CHICAGO t:fund_name="YCEP OLDER YOUTH-OYA" t:vendor_zip_code=60675-2698 t:vendor_state=IL t:esd_name="Willamette ESD" t:compt_obj_title="CONSUMB SUP MAT" t:vendor_name="OFFICEMAX INC" m:compt_obj=410 m:esd=2117 m:cash_expense=19.28

series e:wnky-6kuz d:2013-01-01T00:00:00.000Z t:vendor_city=CHICAGO t:fund_name="YCEP OLDER YOUTH-OYA" t:vendor_zip_code=60675-2698 t:vendor_state=IL t:esd_name="Willamette ESD" t:compt_obj_title="CONSUMB SUP MAT" t:vendor_name="OFFICEMAX INC" m:compt_obj=410 m:esd=2117 m:cash_expense=10.14

series e:wnky-6kuz d:2013-01-01T00:00:00.000Z t:vendor_city=CHICAGO t:fund_name="YCEP OLDER YOUTH-OYA" t:vendor_zip_code=60675-2698 t:vendor_state=IL t:esd_name="Willamette ESD" t:compt_obj_title="CONSUMB SUP MAT" t:vendor_name="OFFICEMAX INC" m:compt_obj=410 m:esd=2117 m:cash_expense=19.44
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:"CASH EXPENSE" t:dataTypeName=number

entity e:wnky-6kuz l:"Expenditures: ESD: Willamette: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/wnky-6kuz

property e:wnky-6kuz t:meta.view v:id=wnky-6kuz v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Willamette: Fiscal Year 2013"

property e:wnky-6kuz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:wnky-6kuz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name       | fund_name            | compt_obj | compt_obj_title | vendor_name   | vendor_address         | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ============== | ==================== | ========= | =============== | ============= | ====================== | =========== | ============ | =============== | ============ | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 19.28        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 10.14        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 19.44        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 2.68         | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 10.62        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 10.62        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 21.37        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 21.10        | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 3.44         | 
| 2117 | Willamette ESD | YCEP OLDER YOUTH-OYA | 410       | CONSUMB SUP MAT | OFFICEMAX INC | 75 REMITTANCE DR #2698 | CHICAGO     | IL           | 60675-2698      | 3.64         | 
```