# Distribution of Abuse of Authority Allegations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/distribution-of-abuse-of-authority-allegations-02593) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bfiu-cc7d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bfiu-cc7d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bfiu-cc7d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bfiu-cc7d |
| Name | Distribution of Abuse of Authority Allegations |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, assignment, abuse, substantiated, allegations |
| Created | 2013-02-26T21:42:21Z |
| Publication Date | 2013-06-21T20:08:16Z |

## Description

This table represents the distribution of abuse of authority allegations

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | series tag     | abuse_type  | Abuse Type  | text      | text        |
| Yes      | numeric metric | abuse_count | Abuse Count | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bfiu-cc7d d:2009-01-01T00:00:00.000Z t:abuse_type="Failure to show search warrant" m:abuse_count=75

series e:bfiu-cc7d d:2009-01-01T00:00:00.000Z t:abuse_type=Frisk m:abuse_count=727

series e:bfiu-cc7d d:2009-01-01T00:00:00.000Z t:abuse_type="Gun drawn" m:abuse_count=155
```

## Meta Commands

```ls
metric m:abuse_count p:integer l:"Abuse Count" t:dataTypeName=number

entity e:bfiu-cc7d l:"Distribution of Abuse of Authority Allegations" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/bfiu-cc7d

property e:bfiu-cc7d t:meta.view v:id=bfiu-cc7d v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Distribution of Abuse of Authority Allegations" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:bfiu-cc7d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bfiu-cc7d t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | abuse_type                             | abuse_count | 
| ==== | ====================================== | =========== | 
| 2009 | Failure to show search warrant         | 75          | 
| 2009 | Frisk                                  | 727         | 
| 2009 | Gun drawn                              | 155         | 
| 2009 | Improper dissemination of medical info | 2           | 
| 2009 | Premises entered and/or searched       | 880         | 
| 2009 | Property damaged                       | 297         | 
| 2009 | Question                               | 385         | 
| 2009 | Refusal to obtain medical treatment    | 168         | 
| 2009 | Refusal to process civilian complaint  | 118         | 
| 2009 | Refusal to provide name/shield number  | 1009        | 
```