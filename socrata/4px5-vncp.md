# CCRB: Attribution of Complaints to Patrol Borough Manhattan South 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-manhattan-south-2005-2009-9c979) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4px5-vncp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4px5-vncp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4px5-vncp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4px5-vncp |
| Name | CCRB: Attribution of Complaints to Patrol Borough Manhattan South 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:46:11Z |
| Publication Date | 2011-09-13T21:46:11Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manhattan_south | Manhattan South | text      | text        |
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
series e:4px5-vncp d:2005-01-01T00:00:00.000Z t:manhattan_south="1st Precinct" m:2008=16 m:total=77 m:2009=10 m:2006=16 m:2007=25 m:2005=10

series e:4px5-vncp d:2005-01-01T00:00:00.000Z t:manhattan_south="5th Precinct" m:2008=14 m:total=94 m:2009=18 m:2006=22 m:2007=18 m:2005=22

series e:4px5-vncp d:2005-01-01T00:00:00.000Z t:manhattan_south="6th Precinct" m:2008=27 m:total=164 m:2009=31 m:2006=35 m:2007=45 m:2005=26
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:4px5-vncp l:"CCRB: Attribution of Complaints to Patrol Borough Manhattan South 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/4px5-vncp

property e:4px5-vncp t:meta.view v:id=4px5-vncp v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Manhattan South 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:4px5-vncp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4px5-vncp t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| manhattan_south | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 1st Precinct    | 10   | 16   | 25   | 16   | 10   | 77    | 
| 5th Precinct    | 22   | 22   | 18   | 14   | 18   | 94    | 
| 6th Precinct    | 26   | 35   | 45   | 27   | 31   | 164   | 
| 7th Precinct    | 18   | 14   | 20   | 20   | 31   | 103   | 
| 9th Precinct    | 23   | 28   | 36   | 31   | 27   | 145   | 
| 10th Precinct   | 19   | 32   | 28   | 29   | 20   | 128   | 
| 13th Precinct   | 22   | 28   | 25   | 22   | 19   | 116   | 
| Midtown South   | 69   | 80   | 61   | 60   | 37   | 307   | 
| 17th Precinct   | 21   | 23   | 19   | 14   | 18   | 95    | 
| Midtown North   | 36   | 45   | 45   | 33   | 28   | 187   | 
```