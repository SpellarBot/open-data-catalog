# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Bronx 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-br--f30d0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/scqk-i7ht) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/scqk-i7ht/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/scqk-i7ht/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | scqk-i7ht |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Bronx 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T19:39:38Z |
| Publication Date | 2011-09-13T19:39:38Z |

## Description

CCRB complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | bronx      | Bronx | text      | text        |
| Yes      | numeric metric | 2005       | 2005  | percent   | percent     |
| Yes      | numeric metric | 2006       | 2006  | percent   | percent     |
| Yes      | numeric metric | 2007       | 2007  | percent   | percent     |
| Yes      | numeric metric | 2008       | 2008  | percent   | percent     |
| Yes      | numeric metric | 2009       | 2009  | percent   | percent     |
| Yes      | numeric metric | total      | Total | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:scqk-i7ht d:2005-01-01T00:00:00.000Z t:bronx="40th Precinct" m:2008=1 m:total=19 m:2009=0 m:2006=5 m:2007=10 m:2005=3

series e:scqk-i7ht d:2005-01-01T00:00:00.000Z t:bronx="41st Precinct" m:2008=1 m:total=13 m:2009=2 m:2006=2 m:2007=2 m:2005=6

series e:scqk-i7ht d:2005-01-01T00:00:00.000Z t:bronx="42nd Precinct" m:2008=0 m:total=17 m:2009=5 m:2006=3 m:2007=5 m:2005=4
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:scqk-i7ht l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Bronx 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/scqk-i7ht

property e:scqk-i7ht t:meta.view v:id=scqk-i7ht v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Bronx 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:scqk-i7ht t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:scqk-i7ht t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| bronx         | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============= | ==== | ==== | ==== | ==== | ==== | ===== | 
| 40th Precinct | 3    | 5    | 10   | 1    | 0    | 19    | 
| 41st Precinct | 6    | 2    | 2    | 1    | 2    | 13    | 
| 42nd Precinct | 4    | 3    | 5    | 0    | 5    | 17    | 
| 43rd Precinct | 8    | 5    | 4    | 2    | 8    | 27    | 
| 44th Precinct | 4    | 6    | 14   | 9    | 11   | 44    | 
| 45h Precinct  | 2    | 2    | 0    | 2    | 1    | 7     | 
| 46th Precinct | 2    | 4    | 5    | 4    | 23   | 38    | 
| 47th Precicnt | 6    | 7    | 2    | 3    | 9    | 27    | 
| 48th Precinct | 8    | 0    | 4    | 4    | 9    | 25    | 
| 49th Precinct | 3    | 1    | 0    | 2    | 2    | 8     | 
```