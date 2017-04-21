# CCRB: Assignment of Officers against Whom Allegations Were Substantiated 2005 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-2005-2009-c4343) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uggy-myiz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uggy-myiz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uggy-myiz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uggy-myiz |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated 2005 ? 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident, report, substantiation, substantiated, victim, ccrb, officer, assignmen... |
| Created | 2011-09-12T20:28:25Z |
| Publication Date | 2011-09-12T20:28:25Z |

## Description

A statistical breakdown, by year and bureau, of the Civilian Complaint Review Board (CCRB) assignments of officers against whom allegations were substantiated for the years 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | patrol_services_bureau | Patrol Services Bureau | text      | text        |
| Yes      | numeric metric | 2005                   | 2005                   | number    | number      |
| Yes      | numeric metric | 2006                   | 2006                   | number    | number      |
| Yes      | numeric metric | 2007                   | 2007                   | number    | number      |
| Yes      | numeric metric | 2008                   | 2008                   | number    | number      |
| Yes      | numeric metric | 2009                   | 2009                   | number    | number      |
| Yes      | numeric metric | total                  | Total                  | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uggy-myiz d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Manhattan South" m:2008=15 m:total=92 m:2009=10 m:2006=17 m:2007=13 m:2005=26

series e:uggy-myiz d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Manhattan North" m:2008=17 m:total=165 m:2009=34 m:2006=39 m:2007=41 m:2005=39

series e:uggy-myiz d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Bronx" m:2008=36 m:total=259 m:2009=82 m:2006=46 m:2007=54 m:2005=61
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:uggy-myiz l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated 2005 ? 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/uggy-myiz

property e:uggy-myiz t:meta.view v:id=uggy-myiz v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated 2005 ? 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:uggy-myiz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uggy-myiz t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| patrol_services_bureau                | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ===================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Patrol Borough Manhattan South        | 26   | 17   | 13   | 15   | 10   | 92    | 
| Patrol Borough Manhattan North        | 39   | 39   | 41   | 17   | 34   | 165   | 
| Patrol Borough Bronx                  | 61   | 46   | 54   | 36   | 82   | 259   | 
| Patrol Borough Brooklyn South         | 40   | 40   | 22   | 17   | 29   | 174   | 
| Patrol Borough Brooklyn North         | 47   | 48   | 50   | 33   | 19   | 218   | 
| Patrol Borough Queens South           | 27   | 26   | 24   | 11   | 18   | 112   | 
| Patrol Borough Queens North           | 10   | 26   | 8    | 10   | 13   | 62    | 
| Patrol Borough Staten Island          | 6    | 7    | 2    | 4    | 3    | 55    | 
| Special Operations Division           | 0    | 0    | 1    | 1    | 0    | 7     | 
| Other Patrol Services Bureau Commands | 0    | 0    | 0    | 0    | 0    | 1     | 
```