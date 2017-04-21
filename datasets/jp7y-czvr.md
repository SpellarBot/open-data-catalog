# Types Of Allegations In Complaints Received 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/types-of-allegations-in-complaints-received-2005-2009-00d86) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jp7y-czvr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jp7y-czvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jp7y-czvr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jp7y-czvr |
| Name | Types Of Allegations In Complaints Received 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Social Services |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T20:33:07Z |
| Publication Date | 2011-09-29T20:33:53Z |

## Description

CCRB: Types of Allegations in Complaints Received 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                  | Data Type | Render Type |
| ======== | ============== | ================== | ===================== | ========= | =========== |
| Yes      | series tag     | category           | Category              | text      | text        |
| Yes      | series tag     | number_1           | 2005 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_1 | 2005 Percent of Total | number    | text        |
| Yes      | series tag     | number_2           | 2006 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_2 | 2006 Percent of Total | number    | text        |
| Yes      | series tag     | number_3           | 2007 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_3 | 2007 Percent of Total | number    | text        |
| Yes      | series tag     | number_4           | 2008 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_4 | 2008 Percent of Total | number    | text        |
| Yes      | series tag     | number_5           | 2009 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_5 | 2009 Percent of Total | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jp7y-czvr d:2005-01-01T00:00:00.000Z t:category="Force (F)" t:number_1=3337 t:number_3=4115 t:number_2=4090 t:number_5=4060 t:number_4=4088 m:percent_of_total_3=54.5 m:percent_of_total_4=55.29999923706055 m:percent_of_total_1=49.20000076293945 m:percent_of_total_2=53.400001525878906 m:percent_of_total_5=53

series e:jp7y-czvr d:2005-01-01T00:00:00.000Z t:category="Abuse of Authority (A)" t:number_1=4627 t:number_3=5196 t:number_2=5286 t:number_5=4930 t:number_4=4878 m:percent_of_total_3=68.80000305175781 m:percent_of_total_4=66 m:percent_of_total_1=68.19999694824219 m:percent_of_total_2=69 m:percent_of_total_5=64.30000305175781

series e:jp7y-czvr d:2005-01-01T00:00:00.000Z t:category="Discourtesy (D)" t:number_1=2838 t:number_3=2998 t:number_2=2980 t:number_5=3184 t:number_4=3006 m:percent_of_total_3=39.70000076293945 m:percent_of_total_4=40.599998474121094 m:percent_of_total_1=41.79999923706055 m:percent_of_total_2=38.900001525878906 m:percent_of_total_5=41.5
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=number

entity e:jp7y-czvr l:"Types Of Allegations In Complaints Received 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/jp7y-czvr

property e:jp7y-czvr t:meta.view v:id=jp7y-czvr v:category="Social Services" v:averageRating=0 v:name="Types Of Allegations In Complaints Received 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:jp7y-czvr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jp7y-czvr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| category               | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ====================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| Force (F)              | 3337     | 49.20%             | 4090     | 53.40%             | 4115     | 54.50%             | 4088     | 55.30%             | 4060     | 53.00%             | 
| Abuse of Authority (A) | 4627     | 68.20%             | 5286     | 69.00%             | 5196     | 68.80%             | 4878     | 66.00%             | 4930     | 64.30%             | 
| Discourtesy (D)        | 2838     | 41.80%             | 2980     | 38.90%             | 2998     | 39.70%             | 3006     | 40.60%             | 3184     | 41.50%             | 
| Offensive Language (O) | 496      | 7.30%              | 576      | 7.50%              | 600      | 7.90%              | 586      | 7.90%              | 574      | 7.50%              | 
| Total Complaints       | 6786     |                    | 7663     |                    | 7549     |                    | 7395     |                    | 7664     |                    | 
```