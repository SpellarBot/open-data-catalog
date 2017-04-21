# Where Incidents That Led To A Complaint Took Place By Precinct - Brooklyn 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-complaint-took-place-by-precinct-brooklyn-2005-2009-f6c88) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bn89-icuy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bn89-icuy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bn89-icuy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bn89-icuy |
| Name | Where Incidents That Led To A Complaint Took Place By Precinct - Brooklyn 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:42:44Z |
| Publication Date | 2011-09-29T20:44:01Z |

## Description

CCRB: Where Incidents that Led to a Complaint Took Place by Precinct - Brooklyn 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | brooklyn_south | Brooklyn South | text      | text        |
| No       |                | _1             | 2005           | number    | number      |
| No       |                | _2             | 2006           | number    | number      |
| No       |                | _3             | 2007           | number    | number      |
| No       |                | _4             | 2008           | number    | number      |
| No       |                | _5             | 2009           | number    | number      |
| Yes      | numeric metric | total          | Total          | number    | number      |
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
series e:bn89-icuy d:2005-01-01T00:00:00.000Z t:brooklyn_south="60th Precinct" m:total=540

series e:bn89-icuy d:2005-01-01T00:00:00.000Z t:brooklyn_south="61st Precinct" m:total=356

series e:bn89-icuy d:2005-01-01T00:00:00.000Z t:brooklyn_south="62nd Precinct" m:total=239
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:bn89-icuy l:"Where Incidents That Led To A Complaint Took Place By Precinct - Brooklyn 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/bn89-icuy

property e:bn89-icuy t:meta.view v:id=bn89-icuy v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Complaint Took Place By Precinct - Brooklyn 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:bn89-icuy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bn89-icuy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| brooklyn_south | _1  | _2  | _3  | _4  | _5  | total | 
| ============== | === | === | === | === | === | ===== | 
| 60th Precinct  | 95  | 110 | 117 | 96  | 122 | 540   | 
| 61st Precinct  | 62  | 75  | 78  | 62  | 79  | 356   | 
| 62nd Precinct  | 37  | 51  | 58  | 56  | 37  | 239   | 
| 63rd Precinct  | 55  | 58  | 75  | 58  | 46  | 292   | 
| 66th Precinct  | 40  | 49  | 29  | 42  | 36  | 196   | 
| 67th Precinct  | 197 | 216 | 197 | 144 | 198 | 952   | 
| 68th Precinct  | 51  | 57  | 48  | 36  | 38  | 230   | 
| 69th Precinct  | 74  | 92  | 81  | 70  | 82  | 399   | 
| 70th Precinct  | 153 | 232 | 170 | 141 | 161 | 857   | 
| 71st Precinct  | 121 | 139 | 141 | 127 | 110 | 638   | 
```