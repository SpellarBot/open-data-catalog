# Where Incidents That Led To A Substantiated Complaint Took Place - Brooklyn 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-substantiated-complaint-took-place-brooklyn-2005-2009-241fa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/u4uz-edhr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/u4uz-edhr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/u4uz-edhr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | u4uz-edhr |
| Name | Where Incidents That Led To A Substantiated Complaint Took Place - Brooklyn 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T21:03:40Z |
| Publication Date | 2011-09-29T21:04:46Z |

## Description

Where Incidents that Led to a Substantiated Complaint Took Place - Brooklyn 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | brooklyn_south | Brooklyn South | text      | text        |
| No       |                | _1             | 2005           | percent   | percent     |
| No       |                | _2             | 2006           | percent   | percent     |
| No       |                | _3             | 2007           | percent   | percent     |
| No       |                | _4             | 2008           | percent   | percent     |
| No       |                | _5             | 2009           | percent   | percent     |
| Yes      | numeric metric | total          | Total          | percent   | percent     |
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
series e:u4uz-edhr d:2005-01-01T00:00:00.000Z t:brooklyn_south="60th Precinct" m:total=13

series e:u4uz-edhr d:2005-01-01T00:00:00.000Z t:brooklyn_south="61st Precinct" m:total=9

series e:u4uz-edhr d:2005-01-01T00:00:00.000Z t:brooklyn_south="62nd Precinct" m:total=3
```

## Meta Commands

```ls
metric m:total p:double l:Total t:dataTypeName=percent

entity e:u4uz-edhr l:"Where Incidents That Led To A Substantiated Complaint Took Place - Brooklyn 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/u4uz-edhr

property e:u4uz-edhr t:meta.view v:id=u4uz-edhr v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Substantiated Complaint Took Place - Brooklyn 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:u4uz-edhr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:u4uz-edhr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| brooklyn_south | _1   | _2   | _3   | _4   | _5   | total | 
| ============== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Brooklyn South | 2005 | 2006 | 2007 | 2008 | 2009 |       | 
| 60th Precinct  | 3    | 5    | 0    | 3    | 2    | 13    | 
| 61st Precinct  | 1    | 3    | 2    | 3    | 0    | 9     | 
| 62nd Precinct  | 0    | 1    | 0    | 0    | 2    | 3     | 
| 63rd Precinct  | 1    | 3    | 2    | 0    | 2    | 8     | 
| 66th Precinct  | 0    | 2    | 1    | 0    | 1    | 4     | 
| 67th Precinct  | 10   | 8    | 5    | 4    | 3    | 30    | 
| 68th Precinct  | 1    | 0    | 1    | 2    | 2    | 6     | 
| 69th Precinct  | 3    | 2    | 1    | 0    | 3    | 9     | 
| 70th Precinct  | 5    | 7    | 8    | 2    | 4    | 26    | 
```