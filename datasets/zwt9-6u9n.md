# CCRB: Attribution of Complaints to Patrol Borough Brooklyn North 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-brooklyn-north-2005-2009-b362d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zwt9-6u9n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zwt9-6u9n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zwt9-6u9n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zwt9-6u9n |
| Name | CCRB: Attribution of Complaints to Patrol Borough Brooklyn North 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:15:15Z |
| Publication Date | 2011-09-13T21:15:15Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | patrol_borough_brooklyn_north | Patrol Borough Brooklyn North | text      | text        |
| Yes      | numeric metric | 2005                          | 2005                          | number    | number      |
| Yes      | numeric metric | 2006                          | 2006                          | number    | number      |
| Yes      | numeric metric | 2007                          | 2007                          | number    | number      |
| Yes      | numeric metric | 2008                          | 2008                          | number    | number      |
| Yes      | numeric metric | 2009                          | 2009                          | number    | number      |
| Yes      | numeric metric | total                         | Total                         | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zwt9-6u9n d:2005-01-01T00:00:00.000Z t:patrol_borough_brooklyn_north="73rd Precinct" m:2008=73 m:total=411 m:2009=95 m:2006=71 m:2007=89 m:2005=83

series e:zwt9-6u9n d:2005-01-01T00:00:00.000Z t:patrol_borough_brooklyn_north="75th Precinct" m:2008=142 m:total=657 m:2009=122 m:2006=130 m:2007=144 m:2005=119

series e:zwt9-6u9n d:2005-01-01T00:00:00.000Z t:patrol_borough_brooklyn_north="77th Precinct" m:2008=62 m:total=356 m:2009=68 m:2006=83 m:2007=61 m:2005=82
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:zwt9-6u9n l:"CCRB: Attribution of Complaints to Patrol Borough Brooklyn North 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/zwt9-6u9n

property e:zwt9-6u9n t:meta.view v:id=zwt9-6u9n v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Brooklyn North 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:zwt9-6u9n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zwt9-6u9n t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| patrol_borough_brooklyn_north | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============================= | ==== | ==== | ==== | ==== | ==== | ===== | 
| 73rd Precinct                 | 83   | 71   | 89   | 73   | 95   | 411   | 
| 75th Precinct                 | 119  | 130  | 144  | 142  | 122  | 657   | 
| 77th Precinct                 | 82   | 83   | 61   | 62   | 68   | 356   | 
| 79th Precinct                 | 62   | 59   | 53   | 48   | 64   | 286   | 
| 81st Precinct                 | 38   | 44   | 34   | 41   | 39   | 196   | 
| 83rd Precinct                 | 64   | 58   | 62   | 52   | 66   | 302   | 
| 84th Precinct                 | 18   | 22   | 15   | 13   | 10   | 78    | 
| 88th Precinct                 | 28   | 33   | 27   | 17   | 26   | 131   | 
| 90th Precinct                 | 25   | 21   | 39   | 36   | 34   | 155   | 
| 94th Precinct                 | 15   | 16   | 14   | 15   | 14   | 74    | 
```