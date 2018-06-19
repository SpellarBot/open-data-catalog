# Expenditures: ESD: Multnomah: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-multnomah-fy-2013-b3ef6) |
| Metadata | [Link](https://data.oregon.gov/api/views/cv4t-9rai) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cv4t-9rai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cv4t-9rai/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cv4t-9rai |
| Name | Expenditures: ESD: Multnomah: FY 2013 |
| Category | Revenue & Expense |
| Tags | esd, expenditures, esd expenditures, multnomah esd expenditures |
| Created | 2013-11-21T17:03:20Z |
| Publication Date | 2013-11-21T17:06:53Z |

## Description

Summary of expenditures for Multnomah ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD #           | number    | number      |
| Yes      | series tag     | esd_name        | ESD Name        | text      | text        |
| Yes      | series tag     | fund_name       | Fund Name       | text      | text        |
| Yes      | numeric metric | compt_obj       | COMPT_OBJ       | number    | number      |
| Yes      | series tag     | compt_obj_title | COMPT_OBJ_TITLE | text      | text        |
| Yes      | series tag     | vendor_state    | VENDOR_STATE    | text      | text        |
| Yes      | series tag     | vendor_name     | VENDOR_NAME     | text      | text        |
| Yes      | numeric metric | cash_expense    | CASH_EXPENSE    | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cv4t-9rai d:2013-01-01T00:00:00.000Z t:fund_name="Board of Education" t:vendor_state=NY t:esd_name="Multnomah Education Service District" t:compt_obj_title="Property Services" t:vendor_name="IRON MOUNTAIN INFORMATION MANA" m:compt_obj=320 m:esd=2148 m:cash_expense=92.09

series e:cv4t-9rai d:2013-01-01T00:00:00.000Z t:fund_name="Board of Education" t:vendor_state=OR t:esd_name="Multnomah Education Service District" t:compt_obj_title=Travel t:vendor_name=COSA m:compt_obj=340 m:esd=2148 m:cash_expense=294

series e:cv4t-9rai d:2013-01-01T00:00:00.000Z t:fund_name="Board of Education" t:vendor_state=OR t:esd_name="Multnomah Education Service District" t:compt_obj_title=Travel t:vendor_name="OREGON SCHOOL BOARDS ASSOC" m:compt_obj=340 m:esd=2148 m:cash_expense=1502
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:compt_obj p:integer l:COMPT_OBJ t:dataTypeName=number

metric m:cash_expense p:float l:CASH_EXPENSE t:dataTypeName=number

entity e:cv4t-9rai l:"Expenditures: ESD: Multnomah: FY 2013" t:url=https://data.oregon.gov/api/views/cv4t-9rai

property e:cv4t-9rai t:meta.view v:id=cv4t-9rai v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Multnomah: FY 2013"

property e:cv4t-9rai t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cv4t-9rai t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                             | fund_name          | compt_obj | compt_obj_title   | vendor_state | vendor_name                    | cash_expense       | 
| ==== | ==================================== | ================== | ========= | ================= | ============ | ============================== | ================== | 
| 2148 | Multnomah Education Service District | Board of Education | 320       | Property Services | NY           | IRON MOUNTAIN INFORMATION MANA | 92.09              | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | COSA                           | 294                | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | OREGON SCHOOL BOARDS ASSOC     | 1502.00            | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | OREGON SCHOOL BOARDS ASSOC     | 505                | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | NW REGIONAL ESD                | 225                | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | HALISKI, JEAN                  | 4.5199999999999996 | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | HALISKI, JEAN                  | 9.0399999999999991 | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | HALISKI, JEAN                  | 9.0399999999999991 | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | HALISKI, JEAN                  | 13.32              | 
| 2148 | Multnomah Education Service District | Board of Education | 340       | Travel            | OR           | HALISKI, JEAN                  | 18.079999999999998 | 
```