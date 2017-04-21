# Where Incidents That Led To A Substantiated Complaint Took Place - Bronx 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-substantiated-complaint-took-place-bronx-2005-2009-2537e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k4u8-p5ux) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k4u8-p5ux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k4u8-p5ux/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k4u8-p5ux |
| Name | Where Incidents That Led To A Substantiated Complaint Took Place - Bronx 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:56:10Z |
| Publication Date | 2011-09-29T20:57:47Z |

## Description

Where Incidents that Led to a Substantiated Complaint Took Place - Bronx 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | bronx      | Bronx | text      | text        |
| No       |                | _1         | 2005  | percent   | percent     |
| No       |                | _2         | 2006  | percent   | percent     |
| No       |                | _3         | 2007  | percent   | percent     |
| No       |                | _4         | 2008  | percent   | percent     |
| No       |                | _5         | 2009  | percent   | percent     |
| Yes      | numeric metric | total      | Total | percent   | percent     |
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
series e:k4u8-p5ux d:2005-01-01T00:00:00.000Z t:bronx="40th Precinct" m:total=29

series e:k4u8-p5ux d:2005-01-01T00:00:00.000Z t:bronx="41st Precinct" m:total=16

series e:k4u8-p5ux d:2005-01-01T00:00:00.000Z t:bronx="42nd Precinct" m:total=19
```

## Meta Commands

```ls
metric m:total p:double l:Total t:dataTypeName=percent

entity e:k4u8-p5ux l:"Where Incidents That Led To A Substantiated Complaint Took Place - Bronx 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/k4u8-p5ux

property e:k4u8-p5ux t:meta.view v:id=k4u8-p5ux v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Substantiated Complaint Took Place - Bronx 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:k4u8-p5ux t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k4u8-p5ux t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| bronx         | _1 | _2 | _3 | _4 | _5 | total | 
| ============= | == | == | == | == | == | ===== | 
| 40th Precinct | 7  | 6  | 12 | 2  | 2  | 29    | 
| 41st Precinct | 4  | 3  | 3  | 3  | 3  | 16    | 
| 42nd Precinct | 3  | 4  | 6  | 3  | 3  | 19    | 
| 43rd Precinct | 10 | 6  | 8  | 2  | 8  | 34    | 
| 44th Precinct | 5  | 7  | 7  | 8  | 7  | 34    | 
| 45th Precinct | 3  | 2  | 0  | 2  | 3  | 10    | 
| 46th Precinct | 3  | 3  | 3  | 7  | 12 | 28    | 
| 47th Precicnt | 3  | 9  | 2  | 3  | 7  | 24    | 
| 48th Precinct | 8  | 1  | 2  | 6  | 7  | 24    | 
| 49th Precinct | 5  | 2  | 1  | 2  | 4  | 14    | 
```