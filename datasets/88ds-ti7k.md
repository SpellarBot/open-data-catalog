# Police Department Disposition Of Substantiated Cases By Year Of CCRB Referral 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-department-disposition-of-substantiated-cases-by-year-of-ccrb-referral-2005-2009-9ce9f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/88ds-ti7k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/88ds-ti7k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/88ds-ti7k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 88ds-ti7k |
| Name | Police Department Disposition Of Substantiated Cases By Year Of CCRB Referral 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T17:48:02Z |
| Publication Date | 2011-09-29T17:49:33Z |

## Description

CCRB: Police Department Disposition of Substantiated Cases by Year of CCRB Referral 2005 - 2009

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag  | police_department_disposition | Police Department Disposition | text      | text        |
| No       |             | _1                            | 2005                          | percent   | percent     |
| No       |             | _2                            | 2006                          | percent   | percent     |
| No       |             | _3                            | 2007                          | percent   | percent     |
| No       |             | _4                            | 2008                          | percent   | percent     |
| No       |             | _5                            | 2009                          | percent   | percent     |
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
series e:88ds-ti7k d:2005-01-01T00:00:00.000Z t:police_department_disposition="Guilty after trial" m:row_number.88ds-ti7k=1

series e:88ds-ti7k d:2005-01-01T00:00:00.000Z t:police_department_disposition="Pleaded guilty" m:row_number.88ds-ti7k=2

series e:88ds-ti7k d:2005-01-01T00:00:00.000Z t:police_department_disposition="To charges and specifications" m:row_number.88ds-ti7k=3
```

## Meta Commands

```ls
metric m:row_number.88ds-ti7k p:long l:"Row Number"

entity e:88ds-ti7k l:"Police Department Disposition Of Substantiated Cases By Year Of CCRB Referral 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/88ds-ti7k

property e:88ds-ti7k t:meta.view v:id=88ds-ti7k v:category="Public Safety" v:averageRating=0 v:name="Police Department Disposition Of Substantiated Cases By Year Of CCRB Referral 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:88ds-ti7k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:88ds-ti7k t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| police_department_disposition    | _1  | _2  | _3  | _4 | _5 | 
| ================================ | === | === | === | == | == | 
| Guilty after trial               | 12  | 2   | 6   | 1  | 0  | 
| Pleaded guilty                   |     |     |     |    |    | 
| To charges and specifications    | 6   | 10  | 5   | 6  | 1  | 
| To charges and specifications    |     |     |     |    |    | 
| negotiated as command discipline | 0   | 3   | 2   | 1  | 0  | 
| To command discipline            | 52  | 68  | 68  | 43 | 35 | 
| Instructions                     | 225 | 160 | 67  | 42 | 44 | 
| Subtotal: Disciplinary Action    | 295 | 243 | 148 | 93 | 80 | 
| Not guilty after trial           | 25  | 13  | 8   | 6  | 0  | 
| Dismissed                        | 14  | 8   | 1   | 2  | 0  | 
```