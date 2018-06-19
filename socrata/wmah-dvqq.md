# Salaries: ESD: South Coast: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-south-coast-fiscal-year-2013-c078f) |
| Metadata | [Link](https://data.oregon.gov/api/views/wmah-dvqq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wmah-dvqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wmah-dvqq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wmah-dvqq |
| Name | Salaries: ESD: South Coast: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, south coast, fiscal year 2013 |
| Created | 2013-10-31T19:47:42Z |
| Publication Date | 2013-10-31T19:49:53Z |

## Description

Salaries for South Coast ESD for Fiscal Yer 2013

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
series e:wmah-dvqq d:2013-01-01T00:00:00.000Z t:odeid=1949 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="SOUTH COAST ESD REGION #7" t:jobdes="AUTISM SPECIALIST" m:annrat=51452

series e:wmah-dvqq d:2013-01-01T00:00:00.000Z t:odeid=1949 t:fullt=FULL t:jobtyp=CERTIFIED t:dname="SOUTH COAST ESD REGION #7" t:jobdes="SPEECH/LANGUAGE PATHOLOGIST" m:annrat=59909

series e:wmah-dvqq d:2013-01-01T00:00:00.000Z t:odeid=1949 t:fullt=PART t:jobtyp=CERTIFIED t:dname="SOUTH COAST ESD REGION #7" t:jobdes="SPEECH/LANGUAGE PATHOLOGIST" m:annrat=58597.2
```

## Meta Commands

```ls
metric m:annrat p:double l:ANNRAT t:dataTypeName=number

entity e:wmah-dvqq l:"Salaries: ESD: South Coast: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/wmah-dvqq

property e:wmah-dvqq t:meta.view v:id=wmah-dvqq v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: South Coast: Fiscal Year 2013"

property e:wmah-dvqq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:wmah-dvqq t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| odeid | dname                     | jobdes                         | jobtyp       | fullt | annrat   | 
| ===== | ========================= | ============================== | ============ | ===== | ======== | 
| 1949  | SOUTH COAST ESD REGION #7 | AUTISM SPECIALIST              | CERTIFIED    | FULL  | 51452    | 
| 1949  | SOUTH COAST ESD REGION #7 | SPEECH/LANGUAGE PATHOLOGIST    | CERTIFIED    | FULL  | 59909    | 
| 1949  | SOUTH COAST ESD REGION #7 | SPEECH/LANGUAGE PATHOLOGIST    | CERTIFIED    | PART  | 58597.2  | 
| 1949  | SOUTH COAST ESD REGION #7 | INSTRUCTIONAL ASSISTANT        | CLASSIFIED   | PART  | 12422.4  | 
| 1949  | SOUTH COAST ESD REGION #7 | INSTRUCTIONAL ASSISTANT        | CLASSIFIED   | FULL  | 20270.83 | 
| 1949  | SOUTH COAST ESD REGION #7 | TEACHER                        | CERTIFIED    | FULL  | 59909    | 
| 1949  | SOUTH COAST ESD REGION #7 | VISION TEACHER                 | CERTIFIED    | FULL  | 65108    | 
| 1949  | SOUTH COAST ESD REGION #7 | PSYCHOLOGIST                   | CERTIFIED    | FULL  | 65108    | 
| 1949  | SOUTH COAST ESD REGION #7 | REGIONAL PROGRAM ADMINISTRATOR | ADMINISTRATN | FULL  | 75221    | 
| 1949  | SOUTH COAST ESD REGION #7 | SPEECH/LANGUAGE PATHOLOGIST    | CERTIFIED    | FULL  | 65108    | 
```