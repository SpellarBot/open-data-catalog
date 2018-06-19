# Salaries: ESD: Malheur: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-malheur-fiscal-year-2014-dbfb6) |
| Metadata | [Link](https://data.oregon.gov/api/views/8hfq-8nxj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8hfq-8nxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8hfq-8nxj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8hfq-8nxj |
| Name | Salaries: ESD: Malheur: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd salaries, educational service districts, malheur esd, malheur esd salaries |
| Created | 2014-12-15T08:28:03Z |
| Publication Date | 2014-12-29T05:58:04Z |

## Description

Salaries as reported by Malheur Educational Service District for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | odeid      | ODEID# | text      | number      |
| Yes      | series tag     | dname      | DNAME  | text      | text        |
| Yes      | series tag     | jobdes     | JOBDES | text      | text        |
| Yes      | series tag     | jobtyp     | JOBTYP | text      | text        |
| Yes      | series tag     | fullt      | FULLT  | text      | text        |
| Yes      | numeric metric | annrat     | ANNRAT | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8hfq-8nxj d:2014-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="SERVICE PROGRAM COORDINATOR" m:annrat=38779

series e:8hfq-8nxj d:2014-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CLASSIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="TRANSITION SPECIALIST" m:annrat=19447.32

series e:8hfq-8nxj d:2014-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="DIRECTOR,CURRICULUM & INSTRUCT" m:annrat=76500
```

## Meta Commands

```ls
metric m:annrat p:double l:ANNRAT t:dataTypeName=money

entity e:8hfq-8nxj l:"Salaries: ESD: Malheur: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/8hfq-8nxj

property e:8hfq-8nxj t:meta.view v:id=8hfq-8nxj v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Malheur: Fiscal Year 2014"

property e:8hfq-8nxj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:8hfq-8nxj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| odeid | dname              | jobdes                         | jobtyp     | fullt | annrat   | 
| ===== | ================== | ============================== | ========== | ===== | ======== | 
| 2106  | MALHEUR ESD RGN 14 | SERVICE PROGRAM COORDINATOR    | CERTIFIED  | FULL  | 38779.00 | 
| 2106  | MALHEUR ESD RGN 14 | TRANSITION SPECIALIST          | CLASSIFIED | FULL  | 19447.32 | 
| 2106  | MALHEUR ESD RGN 14 | DIRECTOR,CURRICULUM & INSTRUCT | CERTIFIED  | FULL  | 76500.00 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CLASSIFIED | FULL  | 34842.00 | 
| 2106  | MALHEUR ESD RGN 14 | DIAGNOSTICIAN/CONSULTING TCHR  | CERTIFIED  | FULL  | 64367.00 | 
| 2106  | MALHEUR ESD RGN 14 | SUPERINTENDENT                 | CERTIFIED  | FULL  | 96839.00 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | FULL  | 64367.00 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | FULL  | 62071.00 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | PART  | 22307.60 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | FULL  | 55769.00 | 
```