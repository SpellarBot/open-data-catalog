# CCRB: Attribution of Complaints to Patrol Borough Brooklyn South 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-brooklyn-south-2005-2009-348b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c5mf-k73g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c5mf-k73g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c5mf-k73g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c5mf-k73g |
| Name | CCRB: Attribution of Complaints to Patrol Borough Brooklyn South 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:20:11Z |
| Publication Date | 2011-09-13T21:20:11Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009.. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | brooklyn_south | Brooklyn South | text      | text        |
| Yes      | numeric metric | 2005           | 2005           | number    | number      |
| Yes      | numeric metric | 2006           | 2006           | number    | number      |
| Yes      | numeric metric | 2007           | 2007           | number    | number      |
| Yes      | numeric metric | 2008           | 2008           | number    | number      |
| Yes      | numeric metric | 2009           | 2009           | number    | number      |
| Yes      | numeric metric | total          | Total          | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c5mf-k73g d:2005-01-01T00:00:00.000Z t:brooklyn_south="60th Precinct" m:2008=24 m:total=140 m:2009=22 m:2006=36 m:2007=28 m:2005=30

series e:c5mf-k73g d:2005-01-01T00:00:00.000Z t:brooklyn_south="61st Precinct" m:2008=30 m:total=160 m:2009=26 m:2006=31 m:2007=40 m:2005=33

series e:c5mf-k73g d:2005-01-01T00:00:00.000Z t:brooklyn_south="62nd Precinct" m:2008=28 m:total=107 m:2009=13 m:2006=25 m:2007=21 m:2005=20
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:c5mf-k73g l:"CCRB: Attribution of Complaints to Patrol Borough Brooklyn South 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/c5mf-k73g

property e:c5mf-k73g t:meta.view v:id=c5mf-k73g v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Brooklyn South 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:c5mf-k73g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c5mf-k73g t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| brooklyn_south | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 60th Precinct  | 30   | 36   | 28   | 24   | 22   | 140   | 
| 61st Precinct  | 33   | 31   | 40   | 30   | 26   | 160   | 
| 62nd Precinct  | 20   | 25   | 21   | 28   | 13   | 107   | 
| 63rd Precinct  | 27   | 30   | 40   | 25   | 23   | 145   | 
| 66th Precinct  | 24   | 14   | 15   | 22   | 18   | 93    | 
| 67th Precinct  | 94   | 90   | 72   | 51   | 60   | 367   | 
| 68th Precinct  | 28   | 28   | 18   | 19   | 14   | 107   | 
| 69th Precinct  | 51   | 45   | 46   | 35   | 34   | 211   | 
| 70th Precinct  | 76   | 108  | 70   | 87   | 81   | 422   | 
| 71st Precinct  | 69   | 68   | 70   | 53   | 39   | 299   | 
```