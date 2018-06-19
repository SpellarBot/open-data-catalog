# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Staten Island 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-patrol-borough-st--b09b2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gd6m-k9v9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gd6m-k9v9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gd6m-k9v9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gd6m-k9v9 |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Staten Island 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:36:37Z |
| Publication Date | 2011-09-13T20:36:37Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | staten_island | Staten Island | text      | text        |
| Yes      | numeric metric | 2005          | 2005          | percent   | percent     |
| Yes      | numeric metric | 2006          | 2006          | percent   | percent     |
| Yes      | numeric metric | 2007          | 2007          | percent   | percent     |
| Yes      | numeric metric | 2008          | 2008          | percent   | percent     |
| Yes      | numeric metric | 2009          | 2009          | percent   | percent     |
| Yes      | numeric metric | total         | Total         | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gd6m-k9v9 d:2005-01-01T00:00:00.000Z t:staten_island="120th Precinct" m:2008=1 m:total=11 m:2009=3 m:2006=3 m:2007=0 m:2005=4

series e:gd6m-k9v9 d:2005-01-01T00:00:00.000Z t:staten_island="122nd Precinct" m:2008=2 m:total=5 m:2009=0 m:2006=1 m:2007=0 m:2005=2

series e:gd6m-k9v9 d:2005-01-01T00:00:00.000Z t:staten_island="123rd Precinct" m:2008=1 m:total=3 m:2009=0 m:2006=2 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:gd6m-k9v9 l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Staten Island 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/gd6m-k9v9

property e:gd6m-k9v9 t:meta.view v:id=gd6m-k9v9 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Patrol Borough Staten Island 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:gd6m-k9v9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gd6m-k9v9 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| staten_island                      | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 120th Precinct                     | 4    | 3    | 0    | 1    | 3    | 11    | 
| 122nd Precinct                     | 2    | 1    | 0    | 2    | 0    | 5     | 
| 123rd Precinct                     | 0    | 2    | 0    | 1    | 0    | 3     | 
| Precincts Total                    | 6    | 6    | 0    | 4    | 3    | 19    | 
| Task Force                         | 0    | 1    | 0    | 0    | 0    | 1     | 
| Borough Headquarters               | 0    | 0    | 0    | 0    | 0    | 0     | 
| Anti-crime Unit                    | 0    | 0    | 2    | 0    | 0    | 2     | 
| Housing                            | 0    | 0    | 0    | 0    | 0    | 0     | 
| Court                              | 0    | 0    | 0    | 0    | 0    | 0     | 
| Patrol Borough Staten Island Total | 6    | 7    | 2    | 4    | 3    | 22    | 
```