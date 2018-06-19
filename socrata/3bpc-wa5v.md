# Gender Of Alleged Victims Compared To New York City Demographics 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gender-of-alleged-victims-compared-to-new-york-city-demographics-2005-2009-7955d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3bpc-wa5v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3bpc-wa5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3bpc-wa5v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3bpc-wa5v |
| Name | Gender Of Alleged Victims Compared To New York City Demographics 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Social Services |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T16:16:37Z |
| Publication Date | 2011-09-29T16:17:59Z |

## Description

CCRB: Gender of Alleged Victims Compared to New York City Demographics 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type | Render Type |
| ======== | ============== | ====================== | ======================== | ========= | =========== |
| Yes      | series tag     | gender                 | Gender                   | text      | text        |
| Yes      | series tag     | number_1               | 2005 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_1     | 2005 Percent of Total    | number    | text        |
| Yes      | series tag     | number_2               | 2006 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_2     | 2006 Percent of Total    | number    | text        |
| Yes      | series tag     | number_3               | 2007 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_3     | 2007 Percent of Total    | number    | text        |
| Yes      | series tag     | number_4               | 2008 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_4     | 2008 Percent of Total    | number    | text        |
| Yes      | series tag     | number_5               | 2009 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_5     | 2009 Percent of Total    | number    | text        |
| Yes      | series tag     | yr_number              | 5 yr Number              | text      | number      |
| Yes      | numeric metric | yr_percent_of_subtotal | 5 yr Percent of Subtotal | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bpc-wa5v d:2005-01-01T00:00:00.000Z t:gender=Male t:number_1=6428 t:number_3=8007 t:number_2=7743 t:number_5=7709 t:yr_number=37242 t:number_4=7355 m:percent_of_total_3=70.69999694824219 m:percent_of_total_4=70.19999694824219 m:percent_of_total_1=68.5 m:percent_of_total_2=69.69999694824219 m:yr_percent_of_subtotal=70 m:percent_of_total_5=70.5

series e:3bpc-wa5v d:2005-01-01T00:00:00.000Z t:gender=Female t:number_1=2958 t:number_3=3324 t:number_2=3360 t:number_5=3223 t:yr_number=15989 t:number_4=3124 m:percent_of_total_3=29.299999237060547 m:percent_of_total_4=29.799999237060547 m:percent_of_total_1=31.5 m:percent_of_total_2=30.299999237060547 m:yr_percent_of_subtotal=30 m:percent_of_total_5=29.5

series e:3bpc-wa5v d:2005-01-01T00:00:00.000Z t:gender=Subtotal t:number_1=9386 t:number_3=11331 t:number_2=11103 t:number_5=10932 t:yr_number=53231 t:number_4=10479 m:percent_of_total_3=100 m:percent_of_total_4=100 m:percent_of_total_1=100 m:percent_of_total_2=100 m:yr_percent_of_subtotal=100 m:percent_of_total_5=100
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=number

metric m:yr_percent_of_subtotal p:float l:"5 yr Percent of Subtotal" t:dataTypeName=number

entity e:3bpc-wa5v l:"Gender Of Alleged Victims Compared To New York City Demographics 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/3bpc-wa5v

property e:3bpc-wa5v t:meta.view v:id=3bpc-wa5v v:category="Social Services" v:averageRating=0 v:name="Gender Of Alleged Victims Compared To New York City Demographics 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:3bpc-wa5v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3bpc-wa5v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| gender   | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | yr_number | yr_percent_of_subtotal | 
| ======== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ========= | ====================== | 
| Male     | 6428     | 68.50%             | 7743     | 69.70%             | 8007     | 70.70%             | 7355     | 70.20%             | 7709     | 70.50%             | 37242     | 70.00%                 | 
| Female   | 2958     | 31.50%             | 3360     | 30.30%             | 3324     | 29.30%             | 3124     | 29.80%             | 3223     | 29.50%             | 15989     | 30.00%                 | 
| Subtotal | 9386     | 100.00%            | 11103    | 100.00%            | 11331    | 100.00%            | 10479    | 100.00%            | 10932    | 100.00%            | 53231     | 100.00%                | 
| Unknown  | 659      |                    | 863      |                    | 935      |                    | 865      |                    | 891      |                    | 4213      |                        | 
| Total    | 10045    |                    | 11966    |                    | 12266    |                    | 11344    |                    | 11823    |                    | 57444     |                        | 
```