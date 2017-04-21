# Where Incidents That Led To A Complaint Took Place By Precinct - Manhattan 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-incidents-that-led-to-a-complaint-took-place-by-precinct-manhattan-2005-2009-93b55) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fics-ewaq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fics-ewaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fics-ewaq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fics-ewaq |
| Name | Where Incidents That Led To A Complaint Took Place By Precinct - Manhattan 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:45:01Z |
| Publication Date | 2011-09-29T20:45:56Z |

## Description

CCRB: Where Incidents that Led to a Complaint Took Place by Precinct - Manhattan 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manhattan_south | Manhattan South | text      | text        |
| No       |                | _1              | 2005            | number    | number      |
| No       |                | _2              | 2006            | number    | number      |
| No       |                | _3              | 2007            | number    | number      |
| No       |                | _4              | 2008            | number    | number      |
| No       |                | _5              | 2009            | number    | number      |
| Yes      | numeric metric | total           | Total           | number    | number      |
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
series e:fics-ewaq d:2005-01-01T00:00:00.000Z t:manhattan_south="1st Precinct" m:total=331

series e:fics-ewaq d:2005-01-01T00:00:00.000Z t:manhattan_south="5th Precinct" m:total=280

series e:fics-ewaq d:2005-01-01T00:00:00.000Z t:manhattan_south="6th Precinct" m:total=405
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:fics-ewaq l:"Where Incidents That Led To A Complaint Took Place By Precinct - Manhattan 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/fics-ewaq

property e:fics-ewaq t:meta.view v:id=fics-ewaq v:category="Public Safety" v:averageRating=0 v:name="Where Incidents That Led To A Complaint Took Place By Precinct - Manhattan 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:fics-ewaq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fics-ewaq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| manhattan_south | _1  | _2  | _3  | _4  | _5  | total | 
| =============== | === | === | === | === | === | ===== | 
| 1st Precinct    | 57  | 83  | 73  | 58  | 60  | 331   | 
| 5th Precinct    | 50  | 54  | 62  | 52  | 62  | 280   | 
| 6th Precinct    | 69  | 83  | 103 | 77  | 73  | 405   | 
| 7th Precinct    | 39  | 40  | 54  | 67  | 79  | 279   | 
| 9th Precinct    | 70  | 83  | 69  | 78  | 76  | 376   | 
| 10th Precinct   | 65  | 100 | 80  | 75  | 64  | 384   | 
| 13th Precinct   | 72  | 70  | 90  | 76  | 67  | 375   | 
| Midtown South   | 180 | 192 | 159 | 159 | 143 | 833   | 
| 17th Precinct   | 40  | 51  | 47  | 35  | 33  | 206   | 
| Midtown North   | 96  | 117 | 117 | 111 | 92  | 533   | 
```