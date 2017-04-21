# CCRB: Attribution of Complaints to Patrol Borough Manhattan North 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-manhattan-north-2005-2009-2098d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xpcf-tg2m) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xpcf-tg2m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xpcf-tg2m/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xpcf-tg2m |
| Name | CCRB: Attribution of Complaints to Patrol Borough Manhattan North 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:42:03Z |
| Publication Date | 2011-09-13T21:42:03Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manhattan_north | Manhattan North | text      | text        |
| Yes      | numeric metric | 2005            | 2005            | number    | number      |
| Yes      | numeric metric | 2006            | 2006            | number    | number      |
| Yes      | numeric metric | 2007            | 2007            | number    | number      |
| Yes      | numeric metric | 2008            | 2008            | number    | number      |
| Yes      | numeric metric | 2009            | 2009            | number    | number      |
| Yes      | numeric metric | total           | Total           | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xpcf-tg2m d:2005-01-01T00:00:00.000Z t:manhattan_north="19th Precinct" m:2008=17 m:total=131 m:2009=20 m:2006=33 m:2007=24 m:2005=37

series e:xpcf-tg2m d:2005-01-01T00:00:00.000Z t:manhattan_north="20th Precinct" m:2008=19 m:total=83 m:2009=15 m:2006=21 m:2007=11 m:2005=17

series e:xpcf-tg2m d:2005-01-01T00:00:00.000Z t:manhattan_north="23rd Precinct" m:2008=34 m:total=179 m:2009=34 m:2006=39 m:2007=38 m:2005=34
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:xpcf-tg2m l:"CCRB: Attribution of Complaints to Patrol Borough Manhattan North 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/xpcf-tg2m

property e:xpcf-tg2m t:meta.view v:id=xpcf-tg2m v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Manhattan North 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:xpcf-tg2m t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xpcf-tg2m t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| manhattan_north | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 19th Precinct   | 37   | 33   | 24   | 17   | 20   | 131   | 
| 20th Precinct   | 17   | 21   | 11   | 19   | 15   | 83    | 
| 23rd Precinct   | 34   | 39   | 38   | 34   | 34   | 179   | 
| 24th Precinct   | 21   | 17   | 20   | 24   | 26   | 108   | 
| 25th Precinct   | 45   | 30   | 46   | 27   | 21   | 169   | 
| 26th Precinct   | 18   | 25   | 18   | 17   | 18   | 96    | 
| Central Park    | 12   | 6    | 5    | 5    | 5    | 33    | 
| 28th Precinct   | 40   | 43   | 37   | 27   | 38   | 185   | 
| 30th Precinct   | 34   | 22   | 19   | 24   | 22   | 121   | 
| 32nd Precinct   | 57   | 64   | 52   | 76   | 62   | 311   | 
```