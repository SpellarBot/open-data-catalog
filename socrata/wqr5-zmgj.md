# Where Civilian Complaints Were Reported 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/where-civilian-complaints-were-reported-2005-2009-52ec4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wqr5-zmgj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wqr5-zmgj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wqr5-zmgj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wqr5-zmgj |
| Name | Where Civilian Complaints Were Reported 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Social Services |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:35:25Z |
| Publication Date | 2011-09-29T20:37:59Z |

## Description

CCRB: Where Civilian Complaints Were Reported 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                  | Data Type | Render Type |
| ======== | ============== | ================== | ===================== | ========= | =========== |
| Yes      | series tag     | category           | Category              | text      | text        |
| Yes      | series tag     | number_1           | 2005 Number           | text      | text        |
| Yes      | numeric metric | percent_of_total_1 | 2005 Percent of Total | number    | text        |
| Yes      | series tag     | number_2           | 2006 Number           | text      | text        |
| Yes      | numeric metric | percent_of_total_2 | 2006 Percent of Total | number    | text        |
| Yes      | series tag     | number_3           | 2007 Number           | text      | text        |
| Yes      | numeric metric | percent_of_total_3 | 2007 Percent of Total | number    | text        |
| Yes      | series tag     | number_4           | 2008 Number           | text      | text        |
| Yes      | numeric metric | percent_of_total_4 | 2008 Percent of Total | number    | text        |
| Yes      | series tag     | number_5           | 2009 Number           | text      | text        |
| Yes      | numeric metric | percent_of_total_5 | 2009 Percent of Total | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wqr5-zmgj d:2005-01-01T00:00:00.000Z t:category=CCRB t:number_1=4,575 t:number_3=4,823 t:number_2=5,152 t:number_5=4,642 t:number_4=4,641 m:percent_of_total_3=63.900001525878906 m:percent_of_total_4=62.79999923706055 m:percent_of_total_1=67.4000015258789 m:percent_of_total_2=67.19999694824219 m:percent_of_total_5=60.599998474121094

series e:wqr5-zmgj d:2005-01-01T00:00:00.000Z t:category=NYPD t:number_1=2,189 t:number_3=2,713 t:number_2=2,499 t:number_5=3,009 t:number_4=2,744 m:percent_of_total_3=35.900001525878906 m:percent_of_total_4=37.099998474121094 m:percent_of_total_1=32.29999923706055 m:percent_of_total_2=32.599998474121094 m:percent_of_total_5=39.29999923706055

series e:wqr5-zmgj d:2005-01-01T00:00:00.000Z t:category=Other t:number_1=22 t:number_3=13 t:number_2=12 t:number_5=13 t:number_4=10 m:percent_of_total_3=0.20000000298023224 m:percent_of_total_4=0.10000000149011612 m:percent_of_total_1=0.30000001192092896 m:percent_of_total_2=0.20000000298023224 m:percent_of_total_5=0.20000000298023224
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=number

entity e:wqr5-zmgj l:"Where Civilian Complaints Were Reported 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/wqr5-zmgj

property e:wqr5-zmgj t:meta.view v:id=wqr5-zmgj v:category="Social Services" v:averageRating=0 v:name="Where Civilian Complaints Were Reported 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:wqr5-zmgj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wqr5-zmgj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| category | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ======== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| CCRB     | 4,575    | 67.40%             | 5,152    | 67.20%             | 4,823    | 63.90%             | 4,641    | 62.80%             | 4,642    | 60.60%             | 
| NYPD     | 2,189    | 32.30%             | 2,499    | 32.60%             | 2,713    | 35.90%             | 2,744    | 37.10%             | 3,009    | 39.30%             | 
| Other    | 22       | 0.30%              | 12       | 0.20%              | 13       | 0.20%              | 10       | 0.10%              | 13       | 0.20%              | 
| Total    | 6,786    | 100.00%            | 7,663    | 100.00%            | 7,549    | 100.00%            | 7,395    | 100.00%            | 7,664    | 100.00%            | 
```