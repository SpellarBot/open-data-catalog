# Salaries: ESD: Malheur: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-malheur-fiscal-year-2013-89a8c) |
| Metadata | [Link](https://data.oregon.gov/api/views/ghk3-vcke) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ghk3-vcke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ghk3-vcke/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ghk3-vcke |
| Name | Salaries: ESD: Malheur: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd salaries, educational service districts, malheur esd, malheur esd salaries |
| Created | 2013-12-20T00:14:03Z |
| Publication Date | 2013-12-20T00:16:21Z |

## Description

Salaries as reported by Malheur Educational Service District for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | odeid      | ODEID# | text      | number      |
| Yes      | series tag     | dname      | DNAME  | text      | text        |
| Yes      | series tag     | jobdes     | JOBDES | text      | text        |
| Yes      | series tag     | jobtyp     | JOBTYP | text      | text        |
| Yes      | series tag     | fullt      | FULLT  | text      | text        |
| Yes      | numeric metric | annrat     | ANNRAT | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ghk3-vcke d:2013-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="SERVICE PROGRAM COORDINATOR" m:annrat=36663

series e:ghk3-vcke d:2013-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CLASSIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="TRANSITION SPECIALIST" m:annrat=19063.8

series e:ghk3-vcke d:2013-01-01T00:00:00.000Z t:odeid=2106 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="MALHEUR ESD RGN 14" t:jobdes="BEHAVIOR SPECIALIST/COUNSELOR" m:annrat=32877
```

## Meta Commands

```ls
metric m:annrat p:double l:ANNRAT t:dataTypeName=number

entity e:ghk3-vcke l:"Salaries: ESD: Malheur: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/ghk3-vcke

property e:ghk3-vcke t:meta.view v:id=ghk3-vcke v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Malheur: Fiscal Year 2013"

property e:ghk3-vcke t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ghk3-vcke t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| odeid | dname              | jobdes                         | jobtyp     | fullt | annrat  | 
| ===== | ================== | ============================== | ========== | ===== | ======= | 
| 2106  | MALHEUR ESD RGN 14 | SERVICE PROGRAM COORDINATOR    | CERTIFIED  | FULL  | 36663   | 
| 2106  | MALHEUR ESD RGN 14 | TRANSITION SPECIALIST          | CLASSIFIED | FULL  | 19063.8 | 
| 2106  | MALHEUR ESD RGN 14 | BEHAVIOR SPECIALIST/COUNSELOR  | CERTIFIED  | FULL  | 32877   | 
| 2106  | MALHEUR ESD RGN 14 | DIRECTOR,CURRICULUM & INSTRUCT | CERTIFIED  | FULL  | 75000   | 
| 2106  | MALHEUR ESD RGN 14 | DIAGNOSTICIAN/CONSULTING TCHR  | CERTIFIED  | PART  | 38272.5 | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CLASSIFIED | FULL  | 32940   | 
| 2106  | MALHEUR ESD RGN 14 | DIAGNOSTICIAN/CONSULTING TCHR  | CERTIFIED  | FULL  | 63105   | 
| 2106  | MALHEUR ESD RGN 14 | SUPERINTENDENT                 | CERTIFIED  | FULL  | 94940   | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | FULL  | 32877   | 
| 2106  | MALHEUR ESD RGN 14 | SPCH-LANG PATHOLOGIST          | CERTIFIED  | FULL  | 63105   | 
```