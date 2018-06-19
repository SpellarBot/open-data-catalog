# CCRB: Attribution of Complaints to Other Patrol Services Bureau Commands 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-other-patrol-services-bureau-commands-2005-2009-8861a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wudr-qbgm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wudr-qbgm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wudr-qbgm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wudr-qbgm |
| Name | CCRB: Attribution of Complaints to Other Patrol Services Bureau Commands 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:05:49Z |
| Publication Date | 2011-09-13T21:05:49Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | other_patrol_services_bureau_commands | Other Patrol Services Bureau Commands | text      | text        |
| Yes      | numeric metric | 2005                                  | 2005                                  | number    | number      |
| Yes      | numeric metric | 2006                                  | 2006                                  | number    | number      |
| Yes      | numeric metric | 2007                                  | 2007                                  | number    | number      |
| Yes      | numeric metric | 2008                                  | 2008                                  | number    | number      |
| Yes      | numeric metric | 2009                                  | 2009                                  | number    | number      |
| Yes      | numeric metric | total                                 | Total                                 | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wudr-qbgm d:2005-01-01T00:00:00.000Z t:other_patrol_services_bureau_commands="Chief's Office" m:2008=2 m:total=16 m:2009=3 m:2006=4 m:2007=5 m:2005=2

series e:wudr-qbgm d:2005-01-01T00:00:00.000Z t:other_patrol_services_bureau_commands="Other Patrol Services Bureau Commands Total" m:2008=2 m:total=16 m:2009=3 m:2006=4 m:2007=5 m:2005=2
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:wudr-qbgm l:"CCRB: Attribution of Complaints to Other Patrol Services Bureau Commands 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/wudr-qbgm

property e:wudr-qbgm t:meta.view v:id=wudr-qbgm v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Other Patrol Services Bureau Commands 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:wudr-qbgm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wudr-qbgm t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| other_patrol_services_bureau_commands       | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =========================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Chief's Office                              | 2    | 4    | 5    | 2    | 3    | 16    | 
| Other Patrol Services Bureau Commands Total | 2    | 4    | 5    | 2    | 3    | 16    | 
```