# CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Organized Crime Control Bureau 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-organized-crime-c--08197) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xt3u-h44z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xt3u-h44z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xt3u-h44z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xt3u-h44z |
| Name | CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Organized Crime Control Bureau 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T16:29:53Z |
| Publication Date | 2011-09-13T16:29:53Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | organized_crime_control_bureau | Organized Crime Control Bureau | text      | text        |
| Yes      | numeric metric | 2005                           | 2005                           | percent   | percent     |
| Yes      | numeric metric | 2006                           | 2006                           | percent   | percent     |
| Yes      | numeric metric | 2007                           | 2007                           | percent   | percent     |
| Yes      | numeric metric | 2008                           | 2008                           | percent   | percent     |
| Yes      | numeric metric | 2009                           | 2009                           | percent   | percent     |
| Yes      | numeric metric | total                          | Total                          | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xt3u-h44z d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Queens Narcotics" m:2008=11 m:total=25 m:2009=6 m:2006=1 m:2007=2 m:2005=5

series e:xt3u-h44z d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Manhattan North Narcotics" m:2008=4 m:total=21 m:2009=0 m:2006=3 m:2007=2 m:2005=12

series e:xt3u-h44z d:2005-01-01T00:00:00.000Z t:organized_crime_control_bureau="Manhattan South Narcotics" m:2008=0 m:total=5 m:2009=0 m:2006=1 m:2007=2 m:2005=2
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:xt3u-h44z l:"CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Organized Crime Control Bureau 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/xt3u-h44z

property e:xt3u-h44z t:meta.view v:id=xt3u-h44z v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment Of Officers Against Whom Allegations Were Substantiated - Organized Crime Control Bureau 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:xt3u-h44z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xt3u-h44z t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| organized_crime_control_bureau | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Queens Narcotics               | 5    | 1    | 2    | 11   | 6    | 25    | 
| Manhattan North Narcotics      | 12   | 3    | 2    | 4    | 0    | 21    | 
| Manhattan South Narcotics      | 2    | 1    | 2    | 0    | 0    | 5     | 
| Bronx Narcotics                | 5    | 4    | 3    | 10   | 10   | 32    | 
| Staten Island Narcotics        | 0    | 2    | 2    | 0    | 2    | 6     | 
| Brooklyn South Narcotics       | 9    | 2    | 6    | 3    | 5    | 25    | 
| Brooklyn North Narcotics       | 8    | 6    | 9    | 8    | 2    | 33    | 
| Narcotics Headquarters         | 0    | 0    | 0    | 0    | 0    | 0     | 
| Auto Crime                     | 0    | 0    | 1    | 0    | 0    | 1     | 
| Vice Enforcement               | 1    | 2    | 0    | 1    | 1    | 5     | 
```