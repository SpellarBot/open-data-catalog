# Total Allegations And Total Complaints Received 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-allegations-and-total-complaints-received-2005-2009-09aea) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bbvw-ivc8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bbvw-ivc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bbvw-ivc8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bbvw-ivc8 |
| Name | Total Allegations And Total Complaints Received 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:53:30Z |
| Publication Date | 2011-09-29T20:00:32Z |

## Description

CCRB: Total Allegations and Total Complaints Received 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                  | Data Type | Render Type |
| ======== | ============== | ================== | ===================== | ========= | =========== |
| Yes      | series tag     | category           | Category              | text      | text        |
| Yes      | series tag     | number_1           | 2005 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_1 | 2005 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_2           | 2006 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_2 | 2006 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_3           | 2007 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_3 | 2007 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_4           | 2008 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_4 | 2008 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_5           | 2009 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_5 | 2009 Percent of Total | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bbvw-ivc8 d:2005-01-01T00:00:00.000Z t:category="Force (F)" t:number_1=6058 t:number_3=7367 t:number_2=7388 t:number_5=7479 t:number_4=6761 m:percent_of_total_3=30.2 m:percent_of_total_4=30.3 m:percent_of_total_1=29.6 m:percent_of_total_2=31 m:percent_of_total_5=30.3

series e:bbvw-ivc8 d:2005-01-01T00:00:00.000Z t:category="Abuse of Authority (A)" t:number_1=10406 t:number_3=12599 t:number_2=12120 t:number_5=12371 t:number_4=11141 m:percent_of_total_3=51.7 m:percent_of_total_4=50 m:percent_of_total_1=50.8 m:percent_of_total_2=50.8 m:percent_of_total_5=50.1

series e:bbvw-ivc8 d:2005-01-01T00:00:00.000Z t:category="Discourtesy (D)" t:number_1=3487 t:number_3=3757 t:number_2=3726 t:number_5=4147 t:number_4=3740 m:percent_of_total_3=15.4 m:percent_of_total_4=16.8 m:percent_of_total_1=17 m:percent_of_total_2=15.6 m:percent_of_total_5=16.8
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:double l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:double l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:double l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:double l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:double l:"2009 Percent of Total" t:dataTypeName=percent

entity e:bbvw-ivc8 l:"Total Allegations And Total Complaints Received 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/bbvw-ivc8

property e:bbvw-ivc8 t:meta.view v:id=bbvw-ivc8 v:category="Public Safety" v:averageRating=0 v:name="Total Allegations And Total Complaints Received 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:bbvw-ivc8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bbvw-ivc8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| category               | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ====================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| Force (F)              | 6058     | 29.60              | 7388     | 31.00              | 7367     | 30.20              | 6761     | 30.30              | 7479     | 30.30              | 
| Abuse of Authority (A) | 10406    | 50.80              | 12120    | 50.80              | 12599    | 51.70              | 11141    | 50.00              | 12371    | 50.10              | 
| Discourtesy (D)        | 3487     | 17.00              | 3726     | 15.60              | 3757     | 15.40              | 3740     | 16.80              | 4147     | 16.80              | 
| Offensive Language (O) | 544      | 2.70               | 630      | 2.60               | 658      | 2.70               | 646      | 2.90               | 683      | 2.80               | 
| Total Allegations      | 20495    | 100                | 23864    | 100                | 24381    | 100                | 22288    | 100                | 24680    | 100                | 
| Total Complaints       | 6786     |                    | 7663     |                    | 7549     |                    | 7395     |                    | 7664     |                    | 
```