# Rate At Which The CCRB Made Findings On The Merits 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rate-at-which-the-ccrb-made-findings-on-the-merits-2005-2009-1f981) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6wkw-kjx4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6wkw-kjx4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6wkw-kjx4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6wkw-kjx4 |
| Name | Rate At Which The CCRB Made Findings On The Merits 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:17:46Z |
| Publication Date | 2011-09-29T19:19:22Z |

## Description

CCRB: Rate at Which the CCRB Made Findings on the Merits 2005 - 2009

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type | Render Type |
| ======== | =========== | ========== | ======== | ========= | =========== |
| Yes      | series tag  | category   | Category | text      | text        |
| No       |             | _1         | 2005     | percent   | percent     |
| No       |             | _2         | 2006     | percent   | percent     |
| No       |             | _3         | 2007     | percent   | percent     |
| No       |             | _4         | 2008     | percent   | percent     |
| No       |             | _5         | 2009     | percent   | percent     |
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
series e:6wkw-kjx4 d:2005-01-01T00:00:00.000Z t:category="Findings on the Merits" m:row_number.6wkw-kjx4=1

series e:6wkw-kjx4 d:2005-01-01T00:00:00.000Z t:category="No Findings on the Merits" m:row_number.6wkw-kjx4=2

series e:6wkw-kjx4 d:2005-01-01T00:00:00.000Z t:category="Total Allegations Closed After" m:row_number.6wkw-kjx4=3
```

## Meta Commands

```ls
metric m:row_number.6wkw-kjx4 p:long l:"Row Number"

entity e:6wkw-kjx4 l:"Rate At Which The CCRB Made Findings On The Merits  2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/6wkw-kjx4

property e:6wkw-kjx4 t:meta.view v:id=6wkw-kjx4 v:category="Public Safety" v:averageRating=0 v:name="Rate At Which The CCRB Made Findings On The Merits  2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:6wkw-kjx4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6wkw-kjx4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| category                       | _1    | _2    | _3    | _4    | _5    | 
| ============================== | ===== | ===== | ===== | ===== | ===== | 
| Findings on the Merits         | 6544  | 6683  | 7174  | 4658  | 5355  | 
| No Findings on the Merits      | 3597  | 3989  | 4315  | 4922  | 4789  | 
| Total Allegations Closed After | 10141 | 10672 | 11489 | 9580  | 10144 | 
| Full Investigation             |       |       |       |       |       | 
| Rate at Which the CCRB         | 64.50 | 62.60 | 62.40 | 48.60 | 52.80 | 
| Made Findings on the Merits    |       |       |       |       |       | 
```