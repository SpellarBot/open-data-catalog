# Race Of Victims Whose Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/race-of-victims-whose-allegations-were-substantiated-2005-2009-a391d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x8rc-3utf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x8rc-3utf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x8rc-3utf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x8rc-3utf |
| Name | Race Of Victims Whose Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:04:45Z |
| Publication Date | 2011-09-29T19:08:14Z |

## Description

CCRB: Race of Officers against Whom Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type | Render Type |
| ======== | ============== | ====================== | ======================== | ========= | =========== |
| Yes      | series tag     | race                   | Race                     | text      | text        |
| Yes      | series tag     | number_1               | 2005 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_1     | 2005 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_2               | 2006 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_2     | 2006 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_3               | 2007 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_3     | 2007 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_4               | 2008 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_4     | 2008 Percent of Total    | percent   | percent     |
| Yes      | series tag     | number_5               | 2009 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_5     | 2009 Percent of Total    | percent   | percent     |
| Yes      | series tag     | yr_number              | 5 yr Number              | text      | percent     |
| Yes      | numeric metric | yr_percent_of_subtotal | 5 yr Percent of Subtotal | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x8rc-3utf d:2005-01-01T00:00:00.000Z t:number_1=51 t:number_3=39 t:number_2=70 t:race=White t:number_5=41 t:yr_number=35.10 t:number_4=38 m:percent_of_total_3=10.3 m:percent_of_total_4=13.1 m:percent_of_total_1=11.9 m:percent_of_total_2=17.9 m:yr_percent_of_subtotal=239 m:percent_of_total_5=12.6

series e:x8rc-3utf d:2005-01-01T00:00:00.000Z t:number_1=244 t:number_3=232 t:number_2=206 t:race=Black t:number_5=172 t:yr_number=23.40 t:number_4=148 m:percent_of_total_3=61.2 m:percent_of_total_4=50.9 m:percent_of_total_1=57.1 m:percent_of_total_2=52.7 m:yr_percent_of_subtotal=1002 m:percent_of_total_5=52.9

series e:x8rc-3utf d:2005-01-01T00:00:00.000Z t:number_1=86 t:number_3=93 t:number_2=95 t:race=Latino t:number_5=97 t:yr_number=27.50 t:number_4=96 m:percent_of_total_3=24.5 m:percent_of_total_4=33 m:percent_of_total_1=20.1 m:percent_of_total_2=24.3 m:yr_percent_of_subtotal=467 m:percent_of_total_5=29.8
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

metric m:yr_percent_of_subtotal p:integer l:"5 yr Percent of Subtotal" t:dataTypeName=number

entity e:x8rc-3utf l:"Race Of Victims Whose Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/x8rc-3utf

property e:x8rc-3utf t:meta.view v:id=x8rc-3utf v:category="Public Safety" v:averageRating=0 v:name="Race Of Victims Whose Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:x8rc-3utf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x8rc-3utf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| race     | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | yr_number | yr_percent_of_subtotal | 
| ======== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ========= | ====================== | 
| White    | 51       | 11.90              | 70       | 17.90              | 39       | 10.30              | 38       | 13.10              | 41       | 12.60              | 35.10     | 239                    | 
| Black    | 244      | 57.10              | 206      | 52.70              | 232      | 61.20              | 148      | 50.90              | 172      | 52.90              | 23.40     | 1002                   | 
| Latino   | 86       | 20.10              | 95       | 24.30              | 93       | 24.50              | 96       | 33.00              | 97       | 29.80              | 27.50     | 467                    | 
| Asian    | 12       | 2.80               | 7        | 1.80               | 6        | 1.60               | 3        | 1.00               | 7        | 2.20               | 11.70     | 35                     | 
| Other    | 34       | 8.00               | 13       | 3.30               | 9        | 2.40               | 6        | 2.10               | 8        | 2.50               | 2.30      | 70                     | 
| Subtotal | 427      | 100.00             | 391      | 100.00             | 379      | 100.00             | 291      | 100.00             | 325      | 100.00             | 100.00    | 1813                   | 
| Unknown  | 26       |                    | 56       |                    | 62       |                    | 52       |                    | 47       |                    |           | 243                    | 
| Total    | 453      |                    | 447      |                    | 441      |                    | 343      |                    | 372      |                    |           | 2056                   | 
```