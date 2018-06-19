# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens South 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-qu--13ee5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c2v8-zzjq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c2v8-zzjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c2v8-zzjq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c2v8-zzjq |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens South 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident, report, substantiation, substantiated, victim, ccrb, officer, assignmen... |
| Created | 2011-09-13T20:31:45Z |
| Publication Date | 2011-09-13T20:31:45Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | queens_south | Queens South | text      | text        |
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
series e:c2v8-zzjq d:2005-01-01T00:00:00.000Z t:queens_south="100th Precinct" m:2008=0 m:total=4 m:2009=1 m:2006=1 m:2007=0 m:2005=2

series e:c2v8-zzjq d:2005-01-01T00:00:00.000Z t:queens_south="101st Precinct" m:2008=6 m:total=36 m:2009=6 m:2006=10 m:2007=6 m:2005=8

series e:c2v8-zzjq d:2005-01-01T00:00:00.000Z t:queens_south="102nd Precinct" m:2008=0 m:total=6 m:2009=0 m:2006=4 m:2007=0 m:2005=2
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:c2v8-zzjq l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens South 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/c2v8-zzjq

property e:c2v8-zzjq t:meta.view v:id=c2v8-zzjq v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Queens South 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:c2v8-zzjq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c2v8-zzjq t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| queens_south    | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 100th Precinct  | 2    | 1    | 0    | 0    | 1    | 4     | 
| 101st Precinct  | 8    | 10   | 6    | 6    | 6    | 36    | 
| 102nd Precinct  | 2    | 4    | 0    | 0    | 0    | 6     | 
| 103nd Precinct  | 0    | 5    | 5    | 4    | 4    | 18    | 
| 105th Precinct  | 4    | 3    | 7    | 0    | 0    | 14    | 
| 106th Precinct  | 2    | 0    | 0    | 0    | 1    | 3     | 
| 107th Precinct  | 0    | 2    | 1    | 1    | 3    | 7     | 
| 113th Precinct  | 7    | 1    | 0    | 0    | 3    | 11    | 
| Precincts Total | 25   | 26   | 19   | 11   | 18   | 99    | 
| Task Force      | 0    | 0    | 2    | 0    | 0    | 2     | 
```