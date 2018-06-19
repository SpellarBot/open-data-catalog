# CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Detective Bureau 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-detective-bureau-2-e9cb8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jdmi-whyn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jdmi-whyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jdmi-whyn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jdmi-whyn |
| Name | CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Detective Bureau 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T16:35:39Z |
| Publication Date | 2011-09-13T16:35:39Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | detective_bureau | Detective Bureau | text      | text        |
| Yes      | numeric metric | 2005             | 2005             | percent   | percent     |
| Yes      | numeric metric | 2006             | 2006             | percent   | percent     |
| Yes      | numeric metric | 2007             | 2007             | percent   | percent     |
| Yes      | numeric metric | 2008             | 2008             | percent   | percent     |
| Yes      | numeric metric | 2009             | 2009             | percent   | percent     |
| Yes      | numeric metric | total            | Total            | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jdmi-whyn d:2005-01-01T00:00:00.000Z t:detective_bureau="Manhattan Units" m:2008=2 m:total=5 m:2009=1 m:2006=0 m:2007=1 m:2005=1

series e:jdmi-whyn d:2005-01-01T00:00:00.000Z t:detective_bureau="Bronx Units" m:2008=5 m:total=22 m:2009=0 m:2006=7 m:2007=4 m:2005=6

series e:jdmi-whyn d:2005-01-01T00:00:00.000Z t:detective_bureau="Brooklyn Units" m:2008=4 m:total=17 m:2009=0 m:2006=6 m:2007=4 m:2005=3
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:jdmi-whyn l:"CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Detective Bureau 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/jdmi-whyn

property e:jdmi-whyn t:meta.view v:id=jdmi-whyn v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Detective Bureau 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:jdmi-whyn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jdmi-whyn t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| detective_bureau       | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ====================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Manhattan Units        | 1    | 0    | 1    | 2    | 1    | 5     | 
| Bronx Units            | 6    | 7    | 4    | 5    | 0    | 22    | 
| Brooklyn Units         | 3    | 6    | 4    | 4    | 0    | 17    | 
| Queens Units           | 3    | 3    | 0    | 0    | 1    | 7     | 
| Staten Island Units    | 0    | 1    | 0    | 0    | 0    | 1     | 
| Central Robbery        | 0    | 0    | 0    | 0    | 0    | 0     | 
| Special Investigations | 0    | 0    | 0    | 1    | 0    | 1     | 
| Career Criminals       | 0    | 0    | 0    | 0    | 0    | 0     | 
| Missing Person         | 0    | 0    | 0    | 0    | 0    | 0     | 
| Special Victims        | 0    | 2    | 0    | 0    | 0    | 2     | 
```