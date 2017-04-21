# FDNY Community Board Incident Count

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-community-board-incident-count-fc5ae) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rtc6-e7ff) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rtc6-e7ff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rtc6-e7ff/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rtc6-e7ff |
| Name | FDNY Community Board Incident Count |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fire department, fdny, fd, fires, community board, station, fire station, fire house, emergency, 911 |
| Created | 2011-08-30T20:16:34Z |
| Publication Date | 2011-08-30T20:16:34Z |

## Description

Provides incident counts by Year, Month, Incident classification, borough and community board.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | numeric metric | yearmonth              | YEARMONTH              | number    | number      |
| Yes      | series tag     | incidentclassification | INCIDENTCLASSIFICATION | text      | text        |
| Yes      | series tag     | incidentborough        | INCIDENTBOROUGH        | text      | text        |
| Yes      | series tag     | communityboardcode     | COMMUNITYBOARDCODE     | text      | number      |
| Yes      | numeric metric | incidentcount          | INCIDENTCOUNT          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rtc6-e7ff d:2011-08-30T13:16:38.000Z t:incidentborough=Manhattan t:communityboardcode=1 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=20

series e:rtc6-e7ff d:2011-08-30T13:16:38.000Z t:incidentborough=Manhattan t:communityboardcode=2 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=35

series e:rtc6-e7ff d:2011-08-30T13:16:38.000Z t:incidentborough=Manhattan t:communityboardcode=3 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=42
```

## Meta Commands

```ls
metric m:yearmonth p:integer l:YEARMONTH t:dataTypeName=number

metric m:incidentcount p:integer l:INCIDENTCOUNT t:dataTypeName=number

entity e:rtc6-e7ff l:"FDNY Community Board Incident Count" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/rtc6-e7ff

property e:rtc6-e7ff t:meta.view v:id=rtc6-e7ff v:category="Public Safety" v:averageRating=0 v:name="FDNY Community Board Incident Count" v:attribution="Fire Department of New York City (FDNY)"

property e:rtc6-e7ff t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rtc6-e7ff t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | yearmonth | incidentclassification | incidentborough | communityboardcode | incidentcount | 
| =========== | ========= | ====================== | =============== | ================== | ============= | 
| 1314710198  |           | INCIDENTCLASSIFICATION | INCIDENTBOROUGH |                    |               | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 1                  | 20            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 2                  | 35            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 3                  | 42            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 4                  | 21            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 5                  | 39            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 6                  | 32            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 7                  | 37            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 8                  | 31            | 
| 1314710198  | 200907    | Structural Fires       | Manhattan       | 9                  | 39            | 
```