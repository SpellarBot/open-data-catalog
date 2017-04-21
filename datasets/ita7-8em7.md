# Tenure Of Officers Against Whom Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tenure-of-officers-against-whom-allegations-were-substantiated-2005-2009-9758f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ita7-8em7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ita7-8em7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ita7-8em7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ita7-8em7 |
| Name | Tenure Of Officers Against Whom Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:49:25Z |
| Publication Date | 2011-09-29T19:50:49Z |

## Description

CCRB: Tenure of Officers against Whom Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type | Field Name | Name   | Data Type | Render Type |
| ======== | =========== | ========== | ====== | ========= | =========== |
| Yes      | series tag  | tenure     | Tenure | text      | text        |
| No       |             | _1         | 2005   | percent   | percent     |
| No       |             | _2         | 2006   | percent   | percent     |
| No       |             | _3         | 2007   | percent   | percent     |
| No       |             | _4         | 2008   | percent   | percent     |
| No       |             | _5         | 2009   | percent   | percent     |
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
series e:ita7-8em7 d:2005-01-01T00:00:00.000Z t:tenure="Less than 1 year" m:row_number.ita7-8em7=1

series e:ita7-8em7 d:2005-01-01T00:00:00.000Z t:tenure="1 year" m:row_number.ita7-8em7=2

series e:ita7-8em7 d:2005-01-01T00:00:00.000Z t:tenure="2 years" m:row_number.ita7-8em7=3
```

## Meta Commands

```ls
metric m:row_number.ita7-8em7 p:long l:"Row Number"

entity e:ita7-8em7 l:"Tenure Of Officers Against Whom Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ita7-8em7

property e:ita7-8em7 t:meta.view v:id=ita7-8em7 v:category="Public Safety" v:averageRating=0 v:name="Tenure Of Officers Against Whom Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ita7-8em7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ita7-8em7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| tenure            | _1  | _2  | _3  | _4  | _5  | 
| ================= | === | === | === | === | === | 
| Less than 1 year  | 7   | 10  | 18  | 6   | 13  | 
| 1 year            | 26  | 39  | 36  | 20  | 33  | 
| 2 years           | 27  | 29  | 22  | 26  | 35  | 
| 3 years           | 30  | 33  | 14  | 17  | 31  | 
| 4 years           | 24  | 20  | 25  | 14  | 20  | 
| 5 to 7 years      | 71  | 66  | 49  | 39  | 46  | 
| 8 to 11 years     | 86  | 51  | 51  | 33  | 28  | 
| 12 to 15 years    | 56  | 69  | 62  | 40  | 35  | 
| 16 years and over | 42  | 30  | 22  | 24  | 34  | 
| Subtotal          | 369 | 347 | 299 | 219 | 275 | 
```