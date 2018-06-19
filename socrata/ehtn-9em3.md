# Expenditures: ESD: Jefferson County: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-jefferson-county-fiscal-year-2014-a137c) |
| Metadata | [Link](https://data.oregon.gov/api/views/ehtn-9em3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ehtn-9em3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ehtn-9em3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ehtn-9em3 |
| Name | Expenditures: ESD: Jefferson County: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | jefferson esd, jefferson county esd, jefferson esd expenditures, jefferson county esd expenditures, 2014 |
| Created | 2014-12-16T21:15:23Z |
| Publication Date | 2014-12-29T06:13:24Z |

## Description

This is a summary of expenditures by Jefferson County ESD for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       |                | id           | ID           | text      | number      |
| Yes      | series tag     | district     | District     | text      | text        |
| Yes      | series tag     | fund_name    | Fund Name    | text      | text        |
| Yes      | numeric metric | object       | Object       | number    | number      |
| Yes      | series tag     | object_title | Object Title | text      | text        |
| Yes      | series tag     | vendor_state | Vendor State | text      | text        |
| Yes      | series tag     | vendor_name  | Vendor Name  | text      | text        |
| Yes      | numeric metric | expense      | Expense      | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:ehtn-9em3 d:2014-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:vendor_state=OR t:object_title="INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES" t:district="Jefferson Co. Ed. Svc. District" t:vendor_name="SUE TAYLOR" m:expense=1000 m:object=310

series e:ehtn-9em3 d:2014-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:vendor_state=OR t:object_title="INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES" t:district="Jefferson Co. Ed. Svc. District" t:vendor_name="JEFFERSON COUNTY SCHOOL DISTRICT 509-J" m:expense=618.63 m:object=310

series e:ehtn-9em3 d:2014-01-01T00:00:00.000Z t:fund_name="GENERAL FUND" t:vendor_state=OR t:object_title="INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES" t:district="Jefferson Co. Ed. Svc. District" t:vendor_name="JEFFERSON COUNTY SCHOOL DISTRICT 509-J" m:expense=349.02 m:object=310
```

## Meta Commands

```ls
metric m:object p:integer l:Object t:dataTypeName=number

metric m:expense p:double l:Expense t:dataTypeName=money

entity e:ehtn-9em3 l:"Expenditures: ESD: Jefferson County: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/ehtn-9em3

property e:ehtn-9em3 t:meta.view v:id=ehtn-9em3 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Jefferson County: Fiscal Year 2014"

property e:ehtn-9em3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ehtn-9em3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| id   | district                        | fund_name    | object | object_title                                       | vendor_state | vendor_name                            | expense | 
| ==== | =============================== | ============ | ====== | ================================================== | ============ | ====================================== | ======= | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | SUE TAYLOR                             | 1000.00 | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | JEFFERSON COUNTY SCHOOL DISTRICT 509-J | 618.63  | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | JEFFERSON COUNTY SCHOOL DISTRICT 509-J | 349.02  | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | DATA DELETE OF OREGON LLC              | 70.00   | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | KEILA MONROY                           | 118.75  | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | JESSE RODRIGUEZ                        | 520.00  | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | SUEDY BORJA                            | 350.75  | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | DATA DELETE OF OREGON LLC              | 36.00   | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | JESSE RODRIGUEZ                        | 72.50   | 
| 2049 | Jefferson Co. Ed. Svc. District | GENERAL FUND | 310    | INSTRUCTIONAL, PROFESSIONAL AND TECHNICAL SERVICES | OR           | KEILA MONROY                           | 166.75  | 
```