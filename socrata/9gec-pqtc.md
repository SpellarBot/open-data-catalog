# Expenditures: ESD: South Coast: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-south-coast-fiscal-year-2014-48976) |
| Metadata | [Link](https://data.oregon.gov/api/views/9gec-pqtc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9gec-pqtc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9gec-pqtc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9gec-pqtc |
| Name | Expenditures: ESD: South Coast: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, south coast, fiscal year 2014 |
| Created | 2014-12-11T22:35:16Z |
| Publication Date | 2014-12-29T05:50:33Z |

## Description

Expenditures for South Coast ESD for Fiscal Year 2014

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
| Yes      | numeric metric | invamt     | INVAMT | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9gec-pqtc d:2014-01-01T00:00:00.000Z t:odeid=1949 t:texto=ADVERTISING t:vndnam=ASHA t:dname="SOUTH COAST ESD REGION #7" t:textf="SPECIAL FUNDS" m:invamt=236 m:obj=354

series e:9gec-pqtc d:2014-01-01T00:00:00.000Z t:odeid=1949 t:texto=ADVERTISING t:vndnam=ASHA t:dname="SOUTH COAST ESD REGION #7" t:textf="SPECIAL FUNDS" m:invamt=236 m:obj=354

series e:9gec-pqtc d:2014-01-01T00:00:00.000Z t:odeid=1949 t:texto="TRAVEL, OUT OF DISTRICT" t:vndnam="BROWN, GREG" t:dname="SOUTH COAST ESD REGION #7" t:textf="GENERAL FUND" m:invamt=19 m:obj=342
```

## Meta Commands

```ls
metric m:obj p:integer l:OBJ t:dataTypeName=number

metric m:invamt p:double l:INVAMT t:dataTypeName=money

entity e:9gec-pqtc l:"Expenditures: ESD: South Coast: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/9gec-pqtc

property e:9gec-pqtc t:meta.view v:id=9gec-pqtc v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: South Coast: Fiscal Year 2014"

property e:9gec-pqtc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:9gec-pqtc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| odeid | dname                     | textf         | obj | texto                               | vndnam                      | invamt   | 
| ===== | ========================= | ============= | === | =================================== | =========================== | ======== | 
| 1949  | SOUTH COAST ESD REGION #7 | SPECIAL FUNDS | 354 | ADVERTISING                         | ASHA                        | 236.00   | 
| 1949  | SOUTH COAST ESD REGION #7 | SPECIAL FUNDS | 354 | ADVERTISING                         | ASHA                        | 236.00   | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 342 | TRAVEL, OUT OF DISTRICT             | BROWN, GREG                 | 19.00    | 
| 1949  | SOUTH COAST ESD REGION #7 | SPECIAL FUNDS | 310 | CONTRACTED SERVICES (INST/PROF/TECH | LAWSON, NANCY               | 550.00   | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 313 | STUDENT SERVICES                    | OREGON COMMUNITY FOUNDATION | 40000.00 | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 353 | POSTAGE                             | PITNEY BOWES                | 9.80     | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 341 | TRAVEL, IN DISTRICT                 | HASELDEN, AMY               | 274.25   | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 460 | NON-CONSUMABLE SUPPLIES             | PRO-BUILD COMPANY LLC       | 200.70   | 
| 1949  | SOUTH COAST ESD REGION #7 | SPECIAL FUNDS | 410 | CONSUMABLE SUPPLIES                 | VISA                        | 173.47   | 
| 1949  | SOUTH COAST ESD REGION #7 | GENERAL FUND  | 353 | POSTAGE                             | PITNEY BOWES                | 2.03     | 
```