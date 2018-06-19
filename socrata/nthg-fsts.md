# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn South 2005 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borou-2005--64290) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nthg-fsts) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nthg-fsts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nthg-fsts/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nthg-fsts |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn South 2005 ? 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:03:36Z |
| Publication Date | 2011-09-13T20:03:36Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | brooklyn_south | Brooklyn South | text      | text        |
| Yes      | numeric metric | 2005           | 2005           | percent   | percent     |
| Yes      | numeric metric | 2006           | 2006           | percent   | percent     |
| Yes      | numeric metric | 2007           | 2007           | percent   | percent     |
| Yes      | numeric metric | 2008           | 2008           | percent   | percent     |
| Yes      | numeric metric | 2009           | 2009           | percent   | percent     |
| Yes      | numeric metric | total          | Total          | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nthg-fsts d:2005-01-01T00:00:00.000Z t:brooklyn_south="60th Precinct" m:2008=2 m:total=8 m:2009=2 m:2006=4 m:2007=0 m:2005=0

series e:nthg-fsts d:2005-01-01T00:00:00.000Z t:brooklyn_south="61st Precinct" m:2008=3 m:total=8 m:2009=0 m:2006=1 m:2007=3 m:2005=1

series e:nthg-fsts d:2005-01-01T00:00:00.000Z t:brooklyn_south="62nd Precinct" m:2008=0 m:total=2 m:2009=1 m:2006=1 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:nthg-fsts l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn South 2005 ? 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/nthg-fsts

property e:nthg-fsts t:meta.view v:id=nthg-fsts v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn South 2005 ? 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:nthg-fsts t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nthg-fsts t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| brooklyn_south | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 60th Precinct  | 0    | 4    | 0    | 2    | 2    | 8     | 
| 61st Precinct  | 1    | 1    | 3    | 3    | 0    | 8     | 
| 62nd Precinct  | 0    | 1    | 0    | 0    | 1    | 2     | 
| 63rd Precinct  | 1    | 0    | 0    | 0    | 1    | 2     | 
| 66th Precinct  | 0    | 0    | 0    | 0    | 0    | 0     | 
| 67th Precinct  | 13   | 11   | 3    | 0    | 2    | 29    | 
| 68th Precinct  | 1    | 1    | 1    | 2    | 2    | 7     | 
| 69th Precinct  | 5    | 4    | 1    | 1    | 3    | 14    | 
| 70th Precinct  | 6    | 3    | 10   | 2    | 9    | 30    | 
| 71st Precinct  | 6    | 7    | 2    | 1    | 4    | 20    | 
```