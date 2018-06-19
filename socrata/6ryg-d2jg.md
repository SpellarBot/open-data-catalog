# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens North 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-qu--7c4c2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6ryg-d2jg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6ryg-d2jg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6ryg-d2jg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6ryg-d2jg |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens North 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:24:34Z |
| Publication Date | 2011-09-13T20:24:34Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | queens_north | Queens North | text      | text        |
| Yes      | numeric metric | 2005         | 2005         | percent   | percent     |
| Yes      | numeric metric | 2006         | 2006         | percent   | percent     |
| Yes      | numeric metric | 2007         | 2007         | percent   | percent     |
| Yes      | numeric metric | 2008         | 2008         | percent   | percent     |
| Yes      | numeric metric | 2009         | 2009         | percent   | percent     |
| Yes      | numeric metric | total        | Total        | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6ryg-d2jg d:2005-01-01T00:00:00.000Z t:queens_north="104th Precinct" m:2008=2 m:total=10 m:2009=3 m:2006=3 m:2007=0 m:2005=2

series e:6ryg-d2jg d:2005-01-01T00:00:00.000Z t:queens_north="108th Precinct" m:2008=0 m:total=7 m:2009=1 m:2006=6 m:2007=0 m:2005=0

series e:6ryg-d2jg d:2005-01-01T00:00:00.000Z t:queens_north="109th Precinct" m:2008=1 m:total=16 m:2009=2 m:2006=9 m:2007=2 m:2005=2
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:6ryg-d2jg l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens North 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/6ryg-d2jg

property e:6ryg-d2jg t:meta.view v:id=6ryg-d2jg v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens North 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:6ryg-d2jg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6ryg-d2jg t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| queens_north    | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 104th Precinct  | 2    | 3    | 0    | 2    | 3    | 10    | 
| 108th Precinct  | 0    | 6    | 0    | 0    | 1    | 7     | 
| 109th Precinct  | 2    | 9    | 2    | 1    | 2    | 16    | 
| 110th Precinct  | 0    | 0    | 0    | 4    | 1    | 5     | 
| 111th Precinct  | 0    | 2    | 0    | 0    | 0    | 2     | 
| 112th Precinct  | 0    | 0    | 0    | 3    | 2    | 5     | 
| 114th Precinct  | 4    | 1    | 2    | 0    | 1    | 8     | 
| 115th Precinct  | 1    | 4    | 2    | 0    | 0    | 7     | 
| Precincts Total | 9    | 25   | 6    | 10   | 10   | 60    | 
| Task Force      | 0    | 0    | 0    | 0    | 0    | 0     | 
```