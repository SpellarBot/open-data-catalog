# Expenditures: ESD: Malheur: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-malheur-fiscal-year-2013-2e25b) |
| Metadata | [Link](https://data.oregon.gov/api/views/4y5x-hw8j) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4y5x-hw8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4y5x-hw8j/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4y5x-hw8j |
| Name | Expenditures: ESD: Malheur: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | esd, malheur esd, malheur esd contracts, malheur educational service district |
| Created | 2013-12-20T00:05:35Z |
| Publication Date | 2013-12-20T00:09:05Z |

## Description

A list of expenditures for Malheur Educational Service District for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | odeid      | ODEID# | text      | number      |
| Yes      | series tag     | dname      | DNAME  | text      | text        |
| Yes      | series tag     | textf      | TEXTF  | text      | text        |
| Yes      | numeric metric | obj        | OBJ    | number    | number      |
| Yes      | series tag     | texto      | TEXTO  | text      | text        |
| Yes      | series tag     | vndnam     | VNDNAM | text      | text        |
| Yes      | numeric metric | invamt     | INVAMT | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4y5x-hw8j d:2013-01-01T00:00:00.000Z t:odeid=2106 t:texto="PURCHASED SERVICES" t:vndnam="ADRIAN SCHOOL DISTRICT 61" t:dname="MALHEUR ESD RGN 14" t:textf="SPECIAL REVENUE FUNDS" m:invamt=265 m:obj=310

series e:4y5x-hw8j d:2013-01-01T00:00:00.000Z t:odeid=2106 t:texto="PURCHASED SERVICES" t:vndnam="ADRIAN SCHOOL DISTRICT 61" t:dname="MALHEUR ESD RGN 14" t:textf="SPECIAL REVENUE FUNDS" m:invamt=1315 m:obj=310

series e:4y5x-hw8j d:2013-01-01T00:00:00.000Z t:odeid=2106 t:texto="PROF SERVICES" t:vndnam="ADRIAN SCHOOL DISTRICT 61" t:dname="MALHEUR ESD RGN 14" t:textf="GENERAL FUND" m:invamt=530.21 m:obj=390
```

## Meta Commands

```ls
metric m:obj p:integer l:OBJ t:dataTypeName=number

metric m:invamt p:double l:INVAMT t:dataTypeName=number

entity e:4y5x-hw8j l:"Expenditures: ESD: Malheur: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/4y5x-hw8j

property e:4y5x-hw8j t:meta.view v:id=4y5x-hw8j v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Malheur: Fiscal Year 2013"

property e:4y5x-hw8j t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:4y5x-hw8j t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| odeid | dname              | textf                 | obj | texto              | vndnam                         | invamt | 
| ===== | ================== | ===================== | === | ================== | ============================== | ====== | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ADRIAN SCHOOL DISTRICT 61      | 265    | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ADRIAN SCHOOL DISTRICT 61      | 1315   | 
| 2106  | MALHEUR ESD RGN 14 | GENERAL FUND          | 390 | PROF SERVICES      | ADRIAN SCHOOL DISTRICT 61      | 530.21 | 
| 2106  | MALHEUR ESD RGN 14 | GENERAL FUND          | 390 | PROF SERVICES      | ADRIAN SCHOOL DISTRICT 61      | 141.25 | 
| 2106  | MALHEUR ESD RGN 14 | GENERAL FUND          | 310 | PURCHASED SERVICES | AFFORDABLE DOCUMENT MANAGEMENT | 760    | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ALLIED BUSINESS SOLUTIONS      | 59.9   | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ALLIED BUSINESS SOLUTIONS      | 29.6   | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ALLIED BUSINESS SOLUTIONS      | 59.9   | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ALLIED BUSINESS SOLUTIONS      | 112.43 | 
| 2106  | MALHEUR ESD RGN 14 | SPECIAL REVENUE FUNDS | 310 | PURCHASED SERVICES | ALLIED BUSINESS SOLUTIONS      | 59.9   | 
```