# Where Incidents That Led To A Complaint Took Place By Precinct - Staten Island 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-complaint-took-place-by-precinct-staten-island-2005-2009-b0108) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/axmw-6kmf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/axmw-6kmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/axmw-6kmf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | axmw-6kmf |
| Name | Where Incidents That Led To A Complaint Took Place By Precinct - Staten Island 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:54:15Z |
| Publication Date | 2011-09-29T20:55:12Z |

## Description

CCRB: Where Incidents that Led to a Complaint Took Place by Precinct - Staten Island 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | staten_island | Staten Island | text      | text        |
| No       |                | _1            | 2005          | number    | number      |
| No       |                | _2            | 2006          | number    | number      |
| No       |                | _3            | 2007          | number    | number      |
| No       |                | _4            | 2008          | number    | number      |
| No       |                | _5            | 2009          | number    | number      |
| Yes      | numeric metric | total         | Total         | number    | number      |
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
series e:axmw-6kmf d:2005-01-01T00:00:00.000Z t:staten_island="120th Precinct" m:total=855

series e:axmw-6kmf d:2005-01-01T00:00:00.000Z t:staten_island="122nd Precinct" m:total=349

series e:axmw-6kmf d:2005-01-01T00:00:00.000Z t:staten_island="123rd Precinct" m:total=121
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:axmw-6kmf l:"Where Incidents That Led To A Complaint Took Place By Precinct - Staten Island 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/axmw-6kmf

property e:axmw-6kmf t:meta.view v:id=axmw-6kmf v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Complaint Took Place By Precinct - Staten Island 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:axmw-6kmf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:axmw-6kmf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| staten_island              | _1  | _2  | _3  | _4  | _5  | total | 
| ========================== | === | === | === | === | === | ===== | 
| 120th Precinct             | 138 | 170 | 163 | 164 | 220 | 855   | 
| 122nd Precinct             | 63  | 72  | 55  | 87  | 72  | 349   | 
| 123rd Precinct             | 21  | 28  | 21  | 27  | 24  | 121   | 
| Staten Island Total        | 222 | 270 | 239 | 278 | 316 | 1325  | 
| Outside City/ Unidentified | 109 | 89  | 104 | 112 | 100 | 514   | 
```