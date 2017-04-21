# CCRB: Attribution of Complaints to the Detective Bureau 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-the-detective-bureau-2005-2009-d88e7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fgb7-3q7d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fgb7-3q7d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fgb7-3q7d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fgb7-3q7d |
| Name | CCRB: Attribution of Complaints to the Detective Bureau 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T19:56:59Z |
| Publication Date | 2011-09-14T19:56:59Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | detective_bureau | Detective Bureau | text      | text        |
| Yes      | numeric metric | 2005             | 2005             | number    | number      |
| Yes      | numeric metric | 2006             | 2006             | number    | number      |
| Yes      | numeric metric | 2007             | 2007             | number    | number      |
| Yes      | numeric metric | 2008             | 2008             | number    | number      |
| Yes      | numeric metric | 2009             | 2009             | number    | number      |
| Yes      | numeric metric | total            | Total            | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fgb7-3q7d d:2005-01-01T00:00:00.000Z t:detective_bureau="Detective Headquarters" m:2008=3 m:total=10 m:2009=1 m:2006=4 m:2007=2 m:2005=0

series e:fgb7-3q7d d:2005-01-01T00:00:00.000Z t:detective_bureau="Central Investigation and Resource Division" m:2008=0 m:total=1 m:2009=0 m:2006=0 m:2007=0 m:2005=1

series e:fgb7-3q7d d:2005-01-01T00:00:00.000Z t:detective_bureau="Special Investigations" m:2008=3 m:total=17 m:2009=3 m:2006=4 m:2007=4 m:2005=3
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:fgb7-3q7d l:"CCRB: Attribution of Complaints to the Detective Bureau 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/fgb7-3q7d

property e:fgb7-3q7d t:meta.view v:id=fgb7-3q7d v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to the Detective Bureau 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:fgb7-3q7d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fgb7-3q7d t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| detective_bureau                            | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =========================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Detective Headquarters                      | 0    | 4    | 2    | 3    | 1    | 10    | 
| Central Investigation and Resource Division | 1    | 0    | 0    | 0    | 0    | 1     | 
| Special Investigations                      | 3    | 4    | 4    | 3    | 3    | 17    | 
| Special Victims                             | 12   | 4    | 6    | 7    | 3    | 32    | 
| Forensic Investigations                     | 0    | 2    | 0    | 1    | 0    | 3     | 
| Fugitive Enforcement                        | 39   | 33   | 28   | 27   | 42   | 169   | 
| Gang Units                                  | 33   | 45   | 38   | 47   | 41   | 204   | 
| DB Manhattan Units                          | 43   | 31   | 26   | 24   | 20   | 144   | 
| DB Bronx Units                              | 39   | 28   | 28   | 19   | 29   | 143   | 
| DB Brooklyn Units                           | 67   | 74   | 49   | 44   | 40   | 274   | 
```