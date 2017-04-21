# CCRB: Attribution of Complaints to Patrol Borough Bronx 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-bronx-2005-2009-54ae8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m7m9-uyrn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m7m9-uyrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m7m9-uyrn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m7m9-uyrn |
| Name | CCRB: Attribution of Complaints to Patrol Borough Bronx 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:10:53Z |
| Publication Date | 2011-09-13T21:10:53Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | bronx      | Bronx | text      | text        |
| Yes      | numeric metric | 2005       | 2005  | number    | number      |
| Yes      | numeric metric | 2006       | 2006  | number    | number      |
| Yes      | numeric metric | 2007       | 2007  | number    | number      |
| Yes      | numeric metric | 2008       | 2008  | number    | number      |
| Yes      | numeric metric | 2009       | 2009  | number    | number      |
| Yes      | numeric metric | total      | Total | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m7m9-uyrn d:2005-01-01T00:00:00.000Z t:bronx="40th Precinct" m:2008=35 m:total=279 m:2009=53 m:2006=68 m:2007=59 m:2005=64

series e:m7m9-uyrn d:2005-01-01T00:00:00.000Z t:bronx="41st Precinct" m:2008=43 m:total=165 m:2009=51 m:2006=19 m:2007=29 m:2005=23

series e:m7m9-uyrn d:2005-01-01T00:00:00.000Z t:bronx="42nd Precinct" m:2008=46 m:total=171 m:2009=35 m:2006=38 m:2007=33 m:2005=19
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:m7m9-uyrn l:"CCRB: Attribution of Complaints to Patrol Borough Bronx 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/m7m9-uyrn

property e:m7m9-uyrn t:meta.view v:id=m7m9-uyrn v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Bronx 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:m7m9-uyrn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m7m9-uyrn t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| bronx         | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============= | ==== | ==== | ==== | ==== | ==== | ===== | 
| 40th Precinct | 64   | 68   | 59   | 35   | 53   | 279   | 
| 41st Precinct | 23   | 19   | 29   | 43   | 51   | 165   | 
| 42nd Precinct | 19   | 38   | 33   | 46   | 35   | 171   | 
| 43rd Precinct | 88   | 57   | 84   | 64   | 61   | 354   | 
| 44th Precinct | 79   | 117  | 129  | 121  | 94   | 540   | 
| 45th Precinct | 23   | 25   | 20   | 29   | 23   | 120   | 
| 46th Precinct | 83   | 76   | 90   | 84   | 99   | 432   | 
| 47th Precinct | 47   | 59   | 82   | 106  | 96   | 390   | 
| 48th Precinct | 31   | 28   | 58   | 43   | 55   | 215   | 
| 49th Precinct | 44   | 29   | 26   | 35   | 30   | 164   | 
```