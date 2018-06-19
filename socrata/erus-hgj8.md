# Expenditures: ESD: Multnomah County: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-multnomah-county-fiscal-year-2014-300be) |
| Metadata | [Link](https://data.oregon.gov/api/views/erus-hgj8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/erus-hgj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/erus-hgj8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | erus-hgj8 |
| Name | Expenditures: ESD: Multnomah County: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, expenditures, esd expenditures, multnomah esd expenditures, 2014 |
| Created | 2014-12-05T01:06:54Z |
| Publication Date | 2014-12-29T05:46:38Z |

## Description

Expenditures for Multnomah County ESD for Fiscal Year 2014

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
series e:erus-hgj8 d:2014-01-01T00:00:00.000Z t:vendor_city=REDMOND t:fund_name=Operating t:vendor_zip_code=97756 t:vendor_state=OR t:esd_name="Multnomah Education Service District" t:compt_obj_title=Travel t:vendor_name="SILVERLEAF CAFE" m:compt_obj=340 m:esd=2148 m:cash_expense=12.24

series e:erus-hgj8 d:2014-01-01T00:00:00.000Z t:vendor_city=REDMOND t:fund_name="Agency Pass-Through" t:vendor_zip_code=97756 t:vendor_state=OR t:esd_name="Multnomah Education Service District" t:compt_obj_title=Travel t:vendor_name="EAGLE CREST INC" m:compt_obj=340 m:esd=2148 m:cash_expense=19506.54

series e:erus-hgj8 d:2014-01-01T00:00:00.000Z t:vendor_city="SAN ANTONIO" t:fund_name="Agency Pass-Through" t:vendor_zip_code=78261 t:vendor_state=TX t:esd_name="Multnomah Education Service District" t:compt_obj_title=Travel t:vendor_name="JW MARRIOTT SAN ANTONIO" m:compt_obj=340 m:esd=2148 m:cash_expense=753.03
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:double l:CASH_EXPENSE t:dataTypeName=money

entity e:erus-hgj8 l:"Expenditures: ESD: Multnomah County: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/erus-hgj8

property e:erus-hgj8 t:meta.view v:id=erus-hgj8 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Multnomah County: Fiscal Year 2014"

property e:erus-hgj8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:erus-hgj8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                             | fund_name           | compt_obj | compt_obj_title             | vendor_name              | vendor_address            | vendor_city | vendor_state | vendor_zip_code | cash_expense | 
| ==== | ==================================== | =================== | ========= | =========================== | ======================== | ========================= | =========== | ============ | =============== | ============ | 
| 2148 | Multnomah Education Service District | Operating           | 340       | Travel                      | SILVERLEAF CAFE          | 7535 FALCON CREST DR      | REDMOND     | OR           | 97756           | 12.24        | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | EAGLE CREST INC          | EAGLE CREST RESORT        | REDMOND     | OR           | 97756           | 19506.54     | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | JW MARRIOTT SAN ANTONIO  | Hill Country Resort & Spa | SAN ANTONIO | TX           | 78261           | 753.03       | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | MABBOTT, JAMES           | 11611 NE AINSWORTH CIRCLE | PORTLAND    | OR           | 97220           | 5294.57      | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | MARRIOTT CORPORATION     | 1401 SW Naito Parkway     | PORTLAND    | OR           | 97201           | 7051.88      | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | NW REGIONAL ESD          | 5825 NE RAY CIRCLE        | HILLSBORO   | OR           |                 | 854.29       | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | TRAVEL INSURANCE POLICY  | 2805 NORTH PARHAM ROAD    | RICHMOND    | VA           | 23286           | 18.48        | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 340       | Travel                      | US AIRWAYS INC           | 4000 E SKY HARBOR BLVD    | PHOENIX     | AZ           |                 | 402.60       | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 350       | Communication               | WILLAMETTE ESD           | 2611 PRINGLE ROAD SE      | SALEM       | OR           | 97302           | 157.50       | 
| 2148 | Multnomah Education Service District | Agency Pass-Through | 380       | Non-Instructional Prof/Tech | HOLLER JR, RICHARD LOUIS | 18540 McSwain Drive       | SISTERS     | OR           | 97759           | 300.00       | 
```