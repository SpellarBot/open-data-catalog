# Expenditures: ESD: Southern Oregon: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-southern-oregon-fy-2013-d5373) |
| Metadata | [Link](https://data.oregon.gov/api/views/czqt-ibbi) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/czqt-ibbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/czqt-ibbi/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | czqt-ibbi |
| Name | Expenditures: ESD: Southern Oregon: FY 2013 |
| Category | Revenue & Expense |
| Tags | soesd, soesd expenditures, southern oregon esd expenditures, southern oregon expenditures |
| Created | 2013-11-12T19:11:57Z |
| Publication Date | 2013-11-12T19:15:36Z |

## Description

Summary of exependitures for Southern Oregon ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | name_of_esd    | Name of ESD    | text      | text        |
| Yes      | series tag     | fund           | Fund           | text      | text        |
| Yes      | numeric metric | object         | Object         | number    | number      |
| Yes      | series tag     | object_title   | Object Title   | text      | text        |
| Yes      | series tag     | vendor_name    | Vendor Name    | text      | text        |
| No       |                | vendor_address | Vendor Address | text      | text        |
| Yes      | series tag     | vendor_city    | Vendor City    | text      | text        |
| Yes      | series tag     | vendor_state   | Vendor State   | text      | text        |
| Yes      | series tag     | vendor_zip     | Vendor Zip     | text      | number      |
| Yes      | numeric metric | cash_expense   | Cash Expense   | money     | money       |
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
series e:czqt-ibbi d:2013-01-01T00:00:00.000Z t:vendor_city="EL DORADO HILLS" t:vendor_state=CA t:object_title=POSTAGE t:vendor_zip=95762 t:fund="GENERAL FUND" t:name_of_esd="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:vendor_name="100% EDUCATIONAL VIDEOS" m:esd=2025 m:object=353 m:cash_expense=6.5

series e:czqt-ibbi d:2013-01-01T00:00:00.000Z t:vendor_city="EL DORADO HILLS" t:vendor_state=CA t:object_title="MEDIA FILES" t:vendor_zip=95762 t:fund="SPECIAL REVENUE-OTHER" t:name_of_esd="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:vendor_name="100% EDUCATIONAL VIDEOS" m:esd=2025 m:object=545 m:cash_expense=79.9

series e:czqt-ibbi d:2013-01-01T00:00:00.000Z t:vendor_city="OVERLAND PARK" t:vendor_state=KS t:object_title=SUPPLIES t:vendor_zip=66223 t:fund="GENERAL FUND" t:name_of_esd="SOUTHERN OREGON EDUCATION SERVICE DISTRICT" t:vendor_name=AAPC m:esd=2025 m:object=410 m:cash_expense=45.9
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:object p:integer l:Object t:dataTypeName=number

metric m:cash_expense p:double l:"Cash Expense" t:dataTypeName=money

entity e:czqt-ibbi l:"Expenditures: ESD: Southern Oregon: FY 2013" t:url=https://data.oregon.gov/api/views/czqt-ibbi

property e:czqt-ibbi t:meta.view v:id=czqt-ibbi v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Southern Oregon: FY 2013"

property e:czqt-ibbi t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:czqt-ibbi t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | name_of_esd                                | fund                    | object | object_title              | vendor_name                     | vendor_address        | vendor_city     | vendor_state | vendor_zip | cash_expense | 
| ==== | ========================================== | ======================= | ====== | ========================= | =============================== | ===================== | =============== | ============ | ========== | ============ | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | GENERAL FUND            | 353    | POSTAGE                   | 100% EDUCATIONAL VIDEOS         | 4921 ROBERT J MATHEWS | EL DORADO HILLS | CA           | 95762      | 6.50         | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-OTHER   | 545    | MEDIA FILES               | 100% EDUCATIONAL VIDEOS         | 4921 ROBERT J MATHEWS | EL DORADO HILLS | CA           | 95762      | 79.90        | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | GENERAL FUND            | 410    | SUPPLIES                  | AAPC                            | PO BOX 23173          | OVERLAND PARK   | KS           | 66223      | 45.90        | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | GENERAL FUND            | 440    | PERIODICALS/SUBSCRIPTIONS | ABC-CLIO SCHOOL LIBRARY MONTHLY | PO BOX 291846         | KETTERING       | OH           | 45429      | 55.00        | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-OTHER   | 390    | OTHER PURCHASED SERVICES  | ABSOLUTE COMFORT                | 9026 HWY 39           | KLAMATH FALLS   | OR           | 97603      | 300.00       | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 342    | OUT OF DISTRICT TRAVEL    | ACADEMIC INNOVATIONS            | 1386 RIO VIRGIN DR    | WASHINGTON      | UT           | 84780      | 396.00       | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 410    | SUPPLIES                  | ACADEMIC THERAPY PUBLICATIONS   | 20 COMMERCIAL BLVD    | NOVATO          | CA           | 94949      | 360.80       | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-FEDERAL | 312    | IN-SERVICE                | ACF OF SOUTHERN OREGON          | 41 ROSS COURT         | MEDFORD         | OR           | 97501      | 150.00       | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | SPECIAL REVENUE-OTHER   | 410    | SUPPLIES                  | ACHIEVEMENT PRODUCTS, INC.      | PO BOX 6013           | CAROL STREAM    | IL           | 60197      | 36.73        | 
| 2025 | SOUTHERN OREGON EDUCATION SERVICE DISTRICT | GENERAL FUND            | 341    | IN DISTRICT TRAVEL        | ACKLES, MARY K                  | 3052 LAZY CREEK DRIVE | MEDFORD         | OR           | 97504      | 36.08        | 
```