# Where Incidents That Led To A Complaint Took Place By Precinct - Bronx 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-complaint-took-place-by-precinct-bronx-2005-2009-b9a79) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yanz-4hj5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yanz-4hj5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yanz-4hj5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yanz-4hj5 |
| Name | Where Incidents That Led To A Complaint Took Place By Precinct - Bronx 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Social Services |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:40:25Z |
| Publication Date | 2011-09-29T20:41:21Z |

## Description

CCRB: Where Incidents that Led to a Complaint Took Place by Precinct - Bronx 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | bronx      | Bronx | text      | text        |
| No       |                | _1         | 2005  | number    | number      |
| No       |                | _2         | 2006  | number    | number      |
| No       |                | _3         | 2007  | number    | number      |
| No       |                | _4         | 2008  | number    | number      |
| No       |                | _5         | 2009  | number    | number      |
| Yes      | numeric metric | total      | Total | number    | number      |
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
series e:yanz-4hj5 d:2005-01-01T00:00:00.000Z t:bronx="40th Precinct" m:total=894

series e:yanz-4hj5 d:2005-01-01T00:00:00.000Z t:bronx="41st Precinct" m:total=411

series e:yanz-4hj5 d:2005-01-01T00:00:00.000Z t:bronx="42nd Precinct" m:total=549
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:yanz-4hj5 l:"Where Incidents That Led To A Complaint Took Place By Precinct - Bronx 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/yanz-4hj5

property e:yanz-4hj5 t:meta.view v:id=yanz-4hj5 v:category="Social Services" v:averageRating=0 v:name="Where Incidents That Led To A Complaint Took Place By Precinct - Bronx 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:yanz-4hj5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yanz-4hj5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| bronx         | _1  | _2  | _3  | _4  | _5  | total | 
| ============= | === | === | === | === | === | ===== | 
| 40th Precinct | 176 | 208 | 161 | 166 | 183 | 894   | 
| 41st Precinct | 68  | 58  | 85  | 82  | 118 | 411   | 
| 42nd Precinct | 67  | 95  | 106 | 127 | 154 | 549   | 
| 43rd Precinct | 199 | 194 | 199 | 180 | 149 | 921   | 
| 44th Precinct | 203 | 255 | 244 | 236 | 226 | 1164  | 
| 45th Precinct | 71  | 51  | 72  | 75  | 83  | 352   | 
| 46th Precinct | 162 | 169 | 199 | 209 | 238 | 977   | 
| 47th Precinct | 141 | 140 | 197 | 226 | 235 | 939   | 
| 48th Precinct | 76  | 94  | 153 | 145 | 130 | 598   | 
| 49th Precinct | 82  | 62  | 73  | 69  | 72  | 358   | 
```