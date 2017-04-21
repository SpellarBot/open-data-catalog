# Where Incidents That Led To A Substantiated Complaint Took Place - Staten Island 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-substantiated-complaint-took-place-staten-island-2005-2009-49be9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/89j6-bdde) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/89j6-bdde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/89j6-bdde/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 89j6-bdde |
| Name | Where Incidents That Led To A Substantiated Complaint Took Place - Staten Island 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-30T17:19:22Z |
| Publication Date | 2011-09-30T17:20:11Z |

## Description

CCRB: Where Incidents that Led to a Substantiated Complaint Took Place - Staten Island 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | staten_island | Staten Island | text      | text        |
| No       |                | _1            | 2005          | percent   | percent     |
| No       |                | _2            | 2006          | percent   | percent     |
| No       |                | _3            | 2007          | percent   | percent     |
| No       |                | _4            | 2008          | percent   | percent     |
| No       |                | _5            | 2009          | percent   | percent     |
| Yes      | numeric metric | total         | Total         | percent   | percent     |
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
series e:89j6-bdde d:2005-01-01T00:00:00.000Z t:staten_island="120th Precinct" m:total=17

series e:89j6-bdde d:2005-01-01T00:00:00.000Z t:staten_island="122nd Precinct" m:total=4

series e:89j6-bdde d:2005-01-01T00:00:00.000Z t:staten_island="123rd Precinct" m:total=3
```

## Meta Commands

```ls
metric m:total p:double l:Total t:dataTypeName=percent

entity e:89j6-bdde l:"Where Incidents That Led To A Substantiated Complaint Took Place - Staten Island 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/89j6-bdde

property e:89j6-bdde t:meta.view v:id=89j6-bdde v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Substantiated Complaint Took Place - Staten Island 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:89j6-bdde t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:89j6-bdde t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| staten_island                                   | _1   | _2   | _3   | _4   | _5   | total | 
| =============================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 120th Precinct                                  | 4    | 6    | 2    | 1    | 4    | 17    | 
| 122nd Precinct                                  | 1    | 0    | 0    | 2    | 1    | 4     | 
| 123rd Precinct                                  | 0    | 1    | 1    | 1    | 0    | 3     | 
| Staten Island Total                             | 5    | 7    | 3    | 4    | 5    | 24    | 
| Percentage of Citywide Substantiated Complaints | 1.90 | 2.70 | 1.40 | 2.50 | 2.50 | 2.20  | 
```