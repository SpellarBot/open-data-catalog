# Expenditures: ESD: Southern Oregon: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-southern-oregon-fy-2014-c9ac2) |
| Metadata | [Link](https://data.oregon.gov/api/views/g2k8-huf8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/g2k8-huf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/g2k8-huf8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | g2k8-huf8 |
| Name | Expenditures: ESD: Southern Oregon: FY 2014 |
| Category | Revenue & Expense |
| Tags | soesd, soesd expenditures, southern oregon esd expenditures, southern oregon expenditures |
| Created | 2014-12-15T02:56:15Z |
| Publication Date | 2014-12-29T05:55:46Z |

## Description

Summary of expenditures for Southern Oregon ESD for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD Name        | text      | text        |
| Yes      | series tag     | fund_name       | Fund Name       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| No       |                | vendor_address  | VENDOR_ADDRESS  | text      | text        |
| Yes      | series tag     | vendor_city     | VENDOR_CITY     | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_zip_code | VENDOR_ZIP CODE | text      | number      |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | money     | money       |
| Yes      | numeric metric | none            | (none)          | number    | number      |
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
series e:g2k8-huf8 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN JUAN CAPISTRANO" t:fund_name="SPECIAL REVENUE-FEDERAL" t:vendor_zip_code=92675 t:vendor_state=CA t:esd_name="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:compt_obj_title="PROF/TECH SERVICES" t:vendor_name="EL ACHIEVE" m:compt_obj=310 m:esd=2025 m:cash_expense=3600

series e:g2k8-huf8 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN JUAN CAPISTRANO" t:fund_name="SPECIAL REVENUE-FEDERAL" t:vendor_zip_code=92675 t:vendor_state=CA t:esd_name="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:compt_obj_title="PROF/TECH SERVICES" t:vendor_name="EL ACHIEVE" m:compt_obj=310 m:esd=2025 m:cash_expense=3600

series e:g2k8-huf8 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN JUAN CAPISTRANO" t:fund_name="SPECIAL REVENUE-FEDERAL" t:vendor_zip_code=92675 t:vendor_state=CA t:esd_name="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:compt_obj_title="PROF/TECH SERVICES" t:vendor_name="EL ACHIEVE" m:compt_obj=310 m:esd=2025 m:cash_expense=2760
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

metric m:none p:long l:(none) t:dataTypeName=number

entity e:g2k8-huf8 l:"Expenditures: ESD: Southern Oregon: FY 2014" t:url=https://data.oregon.gov/api/views/g2k8-huf8

property e:g2k8-huf8 t:meta.view v:id=g2k8-huf8 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Southern Oregon: FY 2014"

property e:g2k8-huf8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:g2k8-huf8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                   | fund_name               | compt_obj | compt_obj_title    | vendor_name                        | vendor_address                  | vendor_city         | vendor_state | vendor_zip_code | cash_expense | none | 
| ==== | ========================================== | ======================= | ========= | ================== | ================================== | =============================== | =================== | ============ | =============== | ============ | ==== | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | EL ACHIEVE                         | 27132-A PASEO ESPADA, SUITE 401 | SAN JUAN CAPISTRANO | CA           | 92675           | 3600.00      |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | EL ACHIEVE                         | 27132-A PASEO ESPADA, SUITE 401 | SAN JUAN CAPISTRANO | CA           | 92675           | 3600.00      |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | EL ACHIEVE                         | 27132-A PASEO ESPADA, SUITE 401 | SAN JUAN CAPISTRANO | CA           | 92675           | 2760.00      |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | GENERAL FUND            | 310       | PROF/TECH SERVICES | BANK OF AMERICA                    | PO BOX 15796                    | WILMINGTON          | DE           | 19886           | 796.95       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 975.00       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 520.00       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 455.00       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 130.00       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 260.00       |      | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 310       | PROF/TECH SERVICES | LANGUAGE TESTING INTERNATIONAL INC | 445 HAMILTON AVE #1104          | WHITE PLAINS        | NY           | 10601           | 130.00       |      | 
```