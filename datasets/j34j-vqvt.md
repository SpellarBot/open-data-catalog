# FDNY Monthly Response Times

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-monthly-response-times-91c61) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j34j-vqvt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j34j-vqvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j34j-vqvt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j34j-vqvt |
| Name | FDNY Monthly Response Times |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Social Services |
| Tags | safety, fire, health, medical, response, emergency, emergencies, time |
| Created | 2011-08-29T18:48:44Z |
| Publication Date | 2013-06-26T17:18:22Z |

## Description

Average response times to incidents by Year, Month, Incident classification and borough.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | numeric metric | yearmonth              | YEARMONTH              | number    | number      |
| Yes      | series tag     | incidentclassification | INCIDENTCLASSIFICATION | text      | text        |
| Yes      | series tag     | incidentborough        | INCIDENTBOROUGH        | text      | text        |
| Yes      | numeric metric | incidentcount          | INCIDENTCOUNT          | number    | number      |
| Yes      | series tag     | averageresponsetime    | AVERAGERESPONSETIME    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j34j-vqvt d:2011-08-29T11:48:45.000Z t:incidentborough=Citywide t:averageresponsetime=3:54 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=1947

series e:j34j-vqvt d:2011-08-29T11:48:45.000Z t:incidentborough=Manhattan t:averageresponsetime=4:00 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=435

series e:j34j-vqvt d:2011-08-29T11:48:45.000Z t:incidentborough=Bronx t:averageresponsetime=3:59 t:incidentclassification="Structural Fires" m:yearmonth=200907 m:incidentcount=432
```

## Meta Commands

```ls
metric m:yearmonth p:integer l:YEARMONTH t:dataTypeName=number

metric m:incidentcount p:integer l:INCIDENTCOUNT t:dataTypeName=number

entity e:j34j-vqvt l:"FDNY Monthly Response Times" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/j34j-vqvt

property e:j34j-vqvt t:meta.view v:id=j34j-vqvt v:category="Social Services" v:averageRating=0 v:name="FDNY Monthly Response Times" v:attribution="Fire Department of New York City (FDNY)"

property e:j34j-vqvt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j34j-vqvt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | yearmonth | incidentclassification | incidentborough | incidentcount | averageresponsetime | 
| =========== | ========= | ====================== | =============== | ============= | =================== | 
| 1314618525  |           | INCIDENTCLASSIFICATION | INCIDENTBOROUGH |               | AVERAGERESPONSETIME | 
| 1314618525  | 200907    | Structural Fires       | Citywide        | 1947          | 3:54                | 
| 1314618525  | 200907    | Structural Fires       | Manhattan       | 435           | 4:00                | 
| 1314618525  | 200907    | Structural Fires       | Bronx           | 432           | 3:59                | 
| 1314618525  | 200907    | Structural Fires       | Staten Island   | 90            | 4:34                | 
| 1314618525  | 200907    | Structural Fires       | Brooklyn        | 652           | 3:29                | 
| 1314618525  | 200907    | Structural Fires       | Queens          | 338           | 4:17                | 
| 1314618525  | 200907    | Non Structural Fires   | Citywide        | 1495          | 4:19                | 
| 1314618525  | 200907    | Non Structural Fires   | Manhattan       | 349           | 4:16                | 
| 1314618525  | 200907    | Non Structural Fires   | Bronx           | 296           | 4:32                | 
```