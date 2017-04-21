# CCRB: Attribution of Complaints to Patrol Boroughs and Other Commands 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-boroughs-and-other-commands-2005-2009-37e2c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/egiq-kmr5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/egiq-kmr5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/egiq-kmr5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | egiq-kmr5 |
| Name | CCRB: Attribution of Complaints to Patrol Boroughs and Other Commands 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T19:49:42Z |
| Publication Date | 2011-09-14T19:49:42Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

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
series e:egiq-kmr5 d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Manhattan South" m:2008=290 m:total=1539 m:2009=261 m:2006=352 m:2007=341 m:2005=295

series e:egiq-kmr5 d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Manhattan North" m:2008=379 m:total=1926 m:2009=357 m:2006=389 m:2007=386 m:2005=415

series e:egiq-kmr5 d:2005-01-01T00:00:00.000Z t:patrol_services_bureau="Patrol Borough Bronx" m:2008=750 m:total=3489 m:2009=735 m:2006=640 m:2007=748 m:2005=616
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:egiq-kmr5 l:"CCRB: Attribution of Complaints to Patrol Boroughs and Other Commands 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/egiq-kmr5

property e:egiq-kmr5 t:meta.view v:id=egiq-kmr5 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Boroughs and Other Commands 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:egiq-kmr5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:egiq-kmr5 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| patrol_services_bureau                | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ===================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Patrol Borough Manhattan South        | 295  | 352  | 341  | 290  | 261  | 1539  | 
| Patrol Borough Manhattan North        | 415  | 389  | 386  | 379  | 357  | 1926  | 
| Patrol Borough Bronx                  | 616  | 640  | 748  | 750  | 735  | 3489  | 
| Patrol Borough Brooklyn South         | 531  | 545  | 500  | 445  | 401  | 2422  | 
| Patrol Borough Brooklyn North         | 550  | 558  | 556  | 521  | 556  | 2741  | 
| Patrol Borough Queens South           | 324  | 341  | 331  | 264  | 249  | 1509  | 
| Patrol Borough Queens North           | 250  | 203  | 170  | 185  | 170  | 978   | 
| Patrol Borough Staten Island          | 100  | 136  | 118  | 90   | 110  | 554   | 
| Special Operations Division           | 39   | 45   | 40   | 21   | 15   | 160   | 
| Other Patrol Services Bureau Commands | 2    | 4    | 5    | 2    | 3    | 16    | 
```