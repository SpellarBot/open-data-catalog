# Expenditures: ESD: Hight Desert: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-hight-desert-fiscal-year-2014-05424) |
| Metadata | [Link](https://data.oregon.gov/api/views/kgvj-w4ce) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kgvj-w4ce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kgvj-w4ce/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kgvj-w4ce |
| Name | Expenditures: ESD: Hight Desert: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, high desert, fiscal year 2014 |
| Created | 2014-12-16T22:05:10Z |
| Publication Date | 2014-12-29T06:16:38Z |

## Description

Expenditures for High Desert ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | esd_number   | ESD Number   | text      | number      |
| Yes      | series tag     | esd_name     | ESD Name     | text      | text        |
| Yes      | numeric metric | fund         | Fund         | number    | number      |
| Yes      | series tag     | fund_name    | Fund Name    | text      | text        |
| Yes      | numeric metric | object       | Object       | number    | number      |
| Yes      | series tag     | object_name  | Object Name  | text      | text        |
| Yes      | series tag     | remitname    | RemitName    | text      | text        |
| Yes      | series tag     | remitstreet1 | RemitStreet1 | text      | text        |
| Yes      | series tag     | remitcity    | RemitCity    | text      | text        |
| Yes      | series tag     | remitstate   | RemitState   | text      | text        |
| Yes      | series tag     | remitzipcode | RemitZipCode | text      | number      |
| Yes      | numeric metric | totalcost    | TotalCost    | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kgvj-w4ce d:2014-01-01T00:00:00.000Z t:fund_name="BEHAVIOR PROGRAMS" t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=OR t:remitcity=WILSONVILLE t:object_name="INSTRUCTIONAL PROF TECH" t:remitzipcode=97070 t:remitstreet1="P.O. BOX 503" t:remitname="GODBEY, GRANT T.  MD/PC" m:totalcost=1980 m:fund=113 m:object=310

series e:kgvj-w4ce d:2014-01-01T00:00:00.000Z t:fund_name="BEHAVIOR PROGRAMS" t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=OR t:remitcity=WILSONVILLE t:object_name="INSTRUCTIONAL PROF TECH" t:remitzipcode=97070 t:remitstreet1="P.O. BOX 503" t:remitname="GODBEY, GRANT T.  MD/PC" m:totalcost=2145 m:fund=113 m:object=310

series e:kgvj-w4ce d:2014-01-01T00:00:00.000Z t:fund_name="SCHOOL IMPROVEMENT" t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=OR t:remitcity=HILLSBORO t:object_name="INSTRUCTIONAL CONTRACTED SVC" t:remitstreet1="5825 NE RAY CIRCLE" t:remitname="NORTHWEST REGIONAL ESD" m:totalcost=10396.2 m:fund=111 m:object=311
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:object p:integer l:Object t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:kgvj-w4ce l:"Expenditures: ESD: Hight Desert: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/kgvj-w4ce

property e:kgvj-w4ce t:meta.view v:id=kgvj-w4ce v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Hight Desert: Fiscal Year 2014"

property e:kgvj-w4ce t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kgvj-w4ce t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_number | esd_name        | fund | fund_name                 | object | object_name                  | remitname                        | remitstreet1       | remitcity   | remitstate | remitzipcode | totalcost | 
| ========== | =============== | ==== | ========================= | ====== | ============================ | ================================ | ================== | =========== | ========== | ============ | ========= | 
| 1975       | High Desert ESD | 113  | BEHAVIOR PROGRAMS         | 310    | INSTRUCTIONAL PROF TECH      | GODBEY, GRANT T.  MD/PC          | P.O. BOX 503       | WILSONVILLE | OR         | 97070        | 1980.00   | 
| 1975       | High Desert ESD | 113  | BEHAVIOR PROGRAMS         | 310    | INSTRUCTIONAL PROF TECH      | GODBEY, GRANT T.  MD/PC          | P.O. BOX 503       | WILSONVILLE | OR         | 97070        | 2145.00   | 
| 1975       | High Desert ESD | 111  | SCHOOL IMPROVEMENT        | 311    | INSTRUCTIONAL CONTRACTED SVC | NORTHWEST REGIONAL ESD           | 5825 NE RAY CIRCLE | HILLSBORO   | OR         |              | 10396.20  | 
| 1975       | High Desert ESD | 227  | OREGON MEXICO PARTNERSHIP | 311    | INSTRUCTIONAL CONTRACTED SVC | OREGON CHILD DEVELOPMENT COALI   | P.O. BOX 2780      | WILSONVILLE | OR         | 97070        | 4821.00   | 
| 1975       | High Desert ESD | 229  | MIGRANT EDUCATION         | 311    | INSTRUCTIONAL CONTRACTED SVC | OREGON CHILD DEVELOPMENT COALI   | P.O. BOX 2780      | WILSONVILLE | OR         | 97070        | 3434.00   | 
| 1975       | High Desert ESD | 230  | CARL PERKINS TITLE I      | 311    | INSTRUCTIONAL CONTRACTED SVC | BEND LAPINE SCHOOL DISTRICT      | 520 NW WALL STREET | BEND        | OR         | 97701        | 2002.38   | 
| 1975       | High Desert ESD | 230  | CARL PERKINS TITLE I      | 311    | INSTRUCTIONAL CONTRACTED SVC | CENTRAL OREGON COMMUNITY COLLEGE | LISA BLOYER        | BEND        | OR         | 97701        | 1918.84   | 
| 1975       | High Desert ESD | 230  | CARL PERKINS TITLE I      | 311    | INSTRUCTIONAL CONTRACTED SVC | HOSTEK.COM                       | PO BOX 701048      | TULSA       | OK         | 74170        | 159.90    | 
| 1975       | High Desert ESD | 230  | CARL PERKINS TITLE I      | 311    | INSTRUCTIONAL CONTRACTED SVC | BEND LAPINE SCHOOL DISTRICT      | 520 NW WALL STREET | BEND        | OR         | 97701        | 2002.38   | 
| 1975       | High Desert ESD | 230  | CARL PERKINS TITLE I      | 311    | INSTRUCTIONAL CONTRACTED SVC | BEND LAPINE SCHOOL DISTRICT      | 520 NW WALL STREET | BEND        | OR         | 97701        | 2002.38   | 
```