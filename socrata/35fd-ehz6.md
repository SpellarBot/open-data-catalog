# CCRB: Attribution of Complaints to Traffic Control Division 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-traffic-control-division-2005-2009-d9157) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/35fd-ehz6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/35fd-ehz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/35fd-ehz6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 35fd-ehz6 |
| Name | CCRB: Attribution of Complaints to Traffic Control Division 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint activity, statistics |
| Created | 2011-09-14T22:39:25Z |
| Publication Date | 2011-09-14T22:39:25Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | traffic_control_division | Traffic Control Division | text      | text        |
| Yes      | numeric metric | 2005                     | 2005                     | number    | number      |
| Yes      | numeric metric | 2006                     | 2006                     | number    | number      |
| Yes      | numeric metric | 2007                     | 2007                     | number    | number      |
| Yes      | numeric metric | 2008                     | 2008                     | number    | number      |
| Yes      | numeric metric | 2009                     | 2009                     | number    | number      |
| Yes      | numeric metric | total                    | Total                    | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:35fd-ehz6 d:2005-01-01T00:00:00.000Z t:traffic_control_division="Headquarters Command" m:2008=1 m:total=5 m:2009=0 m:2006=1 m:2007=3 m:2005=0

series e:35fd-ehz6 d:2005-01-01T00:00:00.000Z t:traffic_control_division="Manhattan Task Force" m:2008=29 m:total=144 m:2009=19 m:2006=35 m:2007=31 m:2005=30

series e:35fd-ehz6 d:2005-01-01T00:00:00.000Z t:traffic_control_division="Brooklyn Task Force" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:35fd-ehz6 l:"CCRB: Attribution of Complaints to Traffic Control Division 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/35fd-ehz6

property e:35fd-ehz6 t:meta.view v:id=35fd-ehz6 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Traffic Control Division 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:35fd-ehz6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:35fd-ehz6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| traffic_control_division     | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ============================ | ==== | ==== | ==== | ==== | ==== | ===== | 
| Headquarters Command         | 0    | 1    | 3    | 1    | 0    | 5     | 
| Manhattan Task Force         | 30   | 35   | 31   | 29   | 19   | 144   | 
| Brooklyn Task Force          | 0    | 0    | 0    | 0    | 0    | 0     | 
| Bronx Task Force             | 0    | 0    | 0    | 0    | 0    | 0     | 
| Queens Task Force            | 0    | 0    | 0    | 0    | 0    | 0     | 
| Surface Transportation       | 9    | 6    | 5    | 6    | 2    |       | 
| Enforcement Division         | 0    | 4    | 5    | 4    | 3    | 28    | 
| Bus                          | 0    | 4    | 5    | 4    | 3    | 16    | 
| Parking Enforcement District | 0    | 0    | 3    | 0    | 0    | 3     | 
| Tow Units                    | 0    | 0    | 0    | 0    | 0    | 0     | 
```