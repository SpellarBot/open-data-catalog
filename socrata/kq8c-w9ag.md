# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Manhattan South 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-ma--a6c07) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kq8c-w9ag) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kq8c-w9ag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kq8c-w9ag/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kq8c-w9ag |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Manhattan South 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:18:45Z |
| Publication Date | 2011-09-13T20:18:45Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manhattan_south | Manhattan South | text      | text        |
| Yes      | numeric metric | 2005            | 2005            | percent   | percent     |
| Yes      | numeric metric | 2006            | 2006            | percent   | percent     |
| Yes      | numeric metric | 2007            | 2007            | percent   | percent     |
| Yes      | numeric metric | 2008            | 2008            | percent   | percent     |
| Yes      | numeric metric | 2009            | 2009            | percent   | percent     |
| Yes      | numeric metric | total           | Total           | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kq8c-w9ag d:2005-01-01T00:00:00.000Z t:manhattan_south="1st Precinct" m:2008=0 m:total=9 m:2009=1 m:2006=1 m:2007=1 m:2005=6

series e:kq8c-w9ag d:2005-01-01T00:00:00.000Z t:manhattan_south="5th Precinct" m:2008=0 m:total=6 m:2009=0 m:2006=0 m:2007=3 m:2005=3

series e:kq8c-w9ag d:2005-01-01T00:00:00.000Z t:manhattan_south="6th Precinct" m:2008=2 m:total=5 m:2009=0 m:2006=1 m:2007=0 m:2005=2
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:kq8c-w9ag l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Manhattan South 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/kq8c-w9ag

property e:kq8c-w9ag t:meta.view v:id=kq8c-w9ag v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Manhattan South 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:kq8c-w9ag t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kq8c-w9ag t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| manhattan_south | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 1st Precinct    | 6    | 1    | 1    | 0    | 1    | 9     | 
| 5th Precinct    | 3    | 0    | 3    | 0    | 0    | 6     | 
| 6th Precinct    | 2    | 1    | 0    | 2    | 0    | 5     | 
| 7th Precinct    | 1    | 2    | 1    | 1    | 1    | 6     | 
| 9th Precinct    | 0    | 3    | 4    | 2    | 2    | 11    | 
| 10th Precinct   | 2    | 2    | 1    | 1    | 0    | 6     | 
| 13th Precinct   | 3    | 0    | 1    | 1    | 1    | 6     | 
| Midtown South   | 3    | 1    | 1    | 3    | 1    | 9     | 
| 17th Precinct   | 1    | 2    | 0    | 1    | 0    | 4     | 
| Midtown North   | 4    | 3    | 0    | 1    | 1    | 9     | 
```