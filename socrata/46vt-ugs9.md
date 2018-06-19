# Where Incidents That Led To A Complaint Took Place By Precinct - Queens 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-complaint-took-place-by-precinct-queens-2005-2009-99f94) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/46vt-ugs9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/46vt-ugs9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/46vt-ugs9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 46vt-ugs9 |
| Name | Where Incidents That Led To A Complaint Took Place By Precinct - Queens 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:46:58Z |
| Publication Date | 2011-09-29T20:47:46Z |

## Description

CCRB: Where Incidents that Led to a Complaint Took Place by Precinct - Manhattan 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | queens_south | Queens South | text      | text        |
| No       |                | _1           | 2005         | number    | number      |
| No       |                | _2           | 2006         | number    | number      |
| No       |                | _3           | 2007         | number    | number      |
| No       |                | _4           | 2008         | number    | number      |
| No       |                | _5           | 2009         | number    | number      |
| Yes      | numeric metric | total        | Total        | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5
```

## Data Commands

```ls
series e:46vt-ugs9 d:2005-01-01T00:00:00.000Z t:queens_south="100th Precinct" m:total=182

series e:46vt-ugs9 d:2005-01-01T00:00:00.000Z t:queens_south="101st Precinct" m:total=447

series e:46vt-ugs9 d:2005-01-01T00:00:00.000Z t:queens_south="102nd Precinct" m:total=340
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:46vt-ugs9 l:"Where Incidents That Led To A Complaint Took Place By Precinct - Queens 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/46vt-ugs9

property e:46vt-ugs9 t:meta.view v:id=46vt-ugs9 v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Complaint Took Place By Precinct - Queens 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:46vt-ugs9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:46vt-ugs9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| queens_south       | _1  | _2  | _3  | _4  | _5  | total | 
| ================== | === | === | === | === | === | ===== | 
| 100th Precinct     | 28  | 33  | 44  | 37  | 40  | 182   | 
| 101st Precinct     | 78  | 101 | 104 | 87  | 77  | 447   | 
| 102nd Precinct     | 70  | 74  | 83  | 69  | 44  | 340   | 
| 103rd Precinct     | 160 | 178 | 171 | 150 | 106 | 765   | 
| 105th Precinct     | 86  | 112 | 85  | 53  | 90  | 426   | 
| 106th Precinct     | 53  | 63  | 67  | 81  | 73  | 337   | 
| 107th Precinct     | 55  | 58  | 42  | 50  | 55  | 260   | 
| 113th Precinct     | 77  | 109 | 88  | 94  | 107 | 475   | 
| Queens South Total | 607 | 728 | 684 | 621 | 592 | 3232  | 
| Queens North       |     |     |     |     |     |       | 
```