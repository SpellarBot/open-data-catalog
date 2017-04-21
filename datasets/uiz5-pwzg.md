# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn North 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-br--f2701) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uiz5-pwzg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uiz5-pwzg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uiz5-pwzg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uiz5-pwzg |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn North 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T19:46:37Z |
| Publication Date | 2011-09-13T19:46:37Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | brooklyn_north | Brooklyn North | text      | text        |
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
series e:uiz5-pwzg d:2005-01-01T00:00:00.000Z t:brooklyn_north="73rd Precinct" m:2008=5 m:total=28 m:2009=5 m:2006=2 m:2007=10 m:2005=6

series e:uiz5-pwzg d:2005-01-01T00:00:00.000Z t:brooklyn_north="75th Precinct" m:2008=8 m:total=41 m:2009=5 m:2006=15 m:2007=5 m:2005=8

series e:uiz5-pwzg d:2005-01-01T00:00:00.000Z t:brooklyn_north="77th Precinct" m:2008=3 m:total=24 m:2009=3 m:2006=8 m:2007=7 m:2005=3
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:uiz5-pwzg l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn North 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/uiz5-pwzg

property e:uiz5-pwzg t:meta.view v:id=uiz5-pwzg v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Brooklyn North 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:uiz5-pwzg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uiz5-pwzg t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| brooklyn_north | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 73rd Precinct  | 6    | 2    | 10   | 5    | 5    | 28    | 
| 75th Precinct  | 8    | 15   | 5    | 8    | 5    | 41    | 
| 77th Precinct  | 3    | 8    | 7    | 3    | 3    | 24    | 
| 79th Precinct  | 7    | 4    | 6    | 3    | 1    | 21    | 
| 81st Precinct  | 4    | 3    | 6    | 0    | 0    | 13    | 
| 83rd Precinct  | 4    | 5    | 5    | 5    | 2    | 21    | 
| 84th Precinct  | 4    | 0    | 0    | 0    | 0    | 4     | 
| 88th Precinct  | 1    | 6    | 0    | 2    | 0    | 9     | 
| 90th Precinct  | 3    | 1    | 2    | 6    | 2    | 14    | 
| 94th Precinct  | 1    | 1    | 2    | 1    | 0    | 5     | 
```