# CCRB: Attribution of Complaints to Patrol Borough Queens South 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-patrol-borough-queens-south-2005-2009-c26e0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8wpj-vk59) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8wpj-vk59/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8wpj-vk59/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8wpj-vk59 |
| Name | CCRB: Attribution of Complaints to Patrol Borough Queens South 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T19:42:29Z |
| Publication Date | 2011-09-14T19:42:29Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | queens_south | Queens South | text      | text        |
| Yes      | numeric metric | 2005         | 2005         | number    | number      |
| Yes      | numeric metric | 2006         | 2006         | number    | number      |
| Yes      | numeric metric | 2007         | 2007         | number    | number      |
| Yes      | numeric metric | 2008         | 2008         | number    | number      |
| Yes      | numeric metric | 2009         | 2009         | number    | number      |
| Yes      | numeric metric | total        | Total        | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8wpj-vk59 d:2005-01-01T00:00:00.000Z t:queens_south="100th Precinct" m:2008=17 m:total=103 m:2009=22 m:2006=16 m:2007=27 m:2005=21

series e:8wpj-vk59 d:2005-01-01T00:00:00.000Z t:queens_south="101st Precinct" m:2008=42 m:total=219 m:2009=24 m:2006=45 m:2007=63 m:2005=45

series e:8wpj-vk59 d:2005-01-01T00:00:00.000Z t:queens_south="102nd Precinct" m:2008=22 m:total=120 m:2009=13 m:2006=27 m:2007=26 m:2005=32
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:8wpj-vk59 l:"CCRB: Attribution of Complaints to Patrol Borough Queens South 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/8wpj-vk59

property e:8wpj-vk59 t:meta.view v:id=8wpj-vk59 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Patrol Borough Queens South 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:8wpj-vk59 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8wpj-vk59 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| queens_south    | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 100th Precinct  | 21   | 16   | 27   | 17   | 22   | 103   | 
| 101st Precinct  | 45   | 45   | 63   | 42   | 24   | 219   | 
| 102nd Precinct  | 32   | 27   | 26   | 22   | 13   | 120   | 
| 103rd Precinct  | 76   | 84   | 77   | 64   | 45   | 346   | 
| 105th Precinct  | 41   | 58   | 42   | 18   | 33   | 192   | 
| 106th Precinct  | 28   | 24   | 26   | 34   | 31   | 143   | 
| 107th Precinct  | 27   | 26   | 25   | 20   | 24   | 122   | 
| 113th Precinct  | 33   | 47   | 33   | 38   | 44   | 195   | 
| Precincts Total | 303  | 327  | 319  | 255  | 236  | 1440  | 
| Task Force      | 13   | 11   | 8    | 3    | 9    | 44    | 
```