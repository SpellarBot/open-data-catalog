# Where Incidents That Led To A Substantiated Complaint Took Place - Queens 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-substantiated-complaint-took-place-queens-2005-2009-81fa6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pc4g-yqvf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pc4g-yqvf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pc4g-yqvf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pc4g-yqvf |
| Name | Where Incidents That Led To A Substantiated Complaint Took Place - Queens 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-30T17:17:40Z |
| Publication Date | 2011-09-30T17:18:33Z |

## Description

CCRB: Where Incidents that Led to a Substantiated Complaint Took Place - Queens 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | queens_south | Queens South | text      | text        |
| No       |                | _1           | 2005         | percent   | percent     |
| No       |                | _2           | 2006         | percent   | percent     |
| No       |                | _3           | 2007         | percent   | percent     |
| No       |                | _4           | 2008         | percent   | percent     |
| No       |                | _5           | 2009         | percent   | percent     |
| Yes      | numeric metric | total        | Total        | percent   | percent     |
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
series e:pc4g-yqvf d:2005-01-01T00:00:00.000Z t:queens_south="100th Precinct" m:total=4

series e:pc4g-yqvf d:2005-01-01T00:00:00.000Z t:queens_south="101st Precinct" m:total=28

series e:pc4g-yqvf d:2005-01-01T00:00:00.000Z t:queens_south="102nd Precinct" m:total=9
```

## Meta Commands

```ls
metric m:total p:double l:Total t:dataTypeName=percent

entity e:pc4g-yqvf l:"Where Incidents That Led To A Substantiated Complaint Took Place - Queens 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/pc4g-yqvf

property e:pc4g-yqvf t:meta.view v:id=pc4g-yqvf v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Substantiated Complaint Took Place - Queens 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:pc4g-yqvf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pc4g-yqvf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| queens_south       | _1 | _2 | _3 | _4 | _5 | total | 
| ================== | == | == | == | == | == | ===== | 
| 100th Precinct     | 2  | 1  | 0  | 0  | 1  | 4     | 
| 101st Precinct     | 6  | 9  | 6  | 3  | 4  | 28    | 
| 102nd Precinct     | 1  | 4  | 3  | 1  | 0  | 9     | 
| 103nd Precinct     | 1  | 3  | 3  | 2  | 7  | 16    | 
| 105th Precinct     | 5  | 3  | 8  | 3  | 1  | 20    | 
| 106th Precinct     | 2  | 2  | 0  | 1  | 1  | 6     | 
| 107th Precinct     | 0  | 2  | 2  | 1  | 3  | 8     | 
| 113th Precinct     | 7  | 1  | 0  | 0  | 3  | 11    | 
| Queens South Total | 24 | 25 | 22 | 11 | 20 | 102   | 
| Queens North       |    |    |    |    |    |       | 
```