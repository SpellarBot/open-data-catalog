# Race Of Alleged Victims Compared To New York City Demographics 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/race-of-alleged-victims-compared-to-new-york-city-demographics-2005-2009-b01fe) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pfbw-d97h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pfbw-d97h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pfbw-d97h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pfbw-d97h |
| Name | Race Of Alleged Victims Compared To New York City Demographics 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T18:01:56Z |
| Publication Date | 2011-09-29T18:03:47Z |

## Description

CCRB: Race of Alleged Victims Compared to New York City Demographics 2005 - 2009

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
| Yes      | series tag     | yr_number              | 5 yr Number              | text      | number      |
| Yes      | numeric metric | yr_percent_of_subtotal | 5 yr Percent of Subtotal | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pfbw-d97h d:2005-01-01T00:00:00.000Z t:number_1=1083 t:number_3=1094 t:number_2=1124 t:race=White t:number_5=891 t:yr_number=5173 t:number_4=981 m:percent_of_total_3=13.2 m:percent_of_total_4=13.4 m:percent_of_total_1=15 m:percent_of_total_2=13.5 m:yr_percent_of_subtotal=13.5 m:percent_of_total_5=12.3

series e:pfbw-d97h d:2005-01-01T00:00:00.000Z t:number_1=3928 t:number_3=4742 t:number_2=4855 t:race=Black t:number_5=4126 t:yr_number=21790 t:number_4=4139 m:percent_of_total_3=57.2 m:percent_of_total_4=56.4 m:percent_of_total_1=54.4 m:percent_of_total_2=58.4 m:yr_percent_of_subtotal=56.7 m:percent_of_total_5=56.9

series e:pfbw-d97h d:2005-01-01T00:00:00.000Z t:number_1=1833 t:number_3=2057 t:number_2=1909 t:race=Latino t:number_5=1921 t:yr_number=9543 t:number_4=1823 m:percent_of_total_3=24.8 m:percent_of_total_4=24.8 m:percent_of_total_1=25.4 m:percent_of_total_2=23 m:yr_percent_of_subtotal=24.8 m:percent_of_total_5=26.5
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

metric m:yr_percent_of_subtotal p:float l:"5 yr Percent of Subtotal" t:dataTypeName=percent

entity e:pfbw-d97h l:"Race Of Alleged Victims Compared To New York City Demographics 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/pfbw-d97h

property e:pfbw-d97h t:meta.view v:id=pfbw-d97h v:category="Public Safety" v:averageRating=0 v:name="Race Of Alleged Victims Compared To New York City Demographics 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:pfbw-d97h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pfbw-d97h t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| race     | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | yr_number | yr_percent_of_subtotal | 
| ======== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ========= | ====================== | 
| White    | 1083     | 15.00              | 1124     | 13.50              | 1094     | 13.20              | 981      | 13.40              | 891      | 12.30              | 5173      | 13.50                  | 
| Black    | 3928     | 54.40              | 4855     | 58.40              | 4742     | 57.20              | 4139     | 56.40              | 4126     | 56.90              | 21790     | 56.70                  | 
| Latino   | 1833     | 25.40              | 1909     | 23.00              | 2057     | 24.80              | 1823     | 24.80              | 1921     | 26.50              | 9543      | 24.80                  | 
| Asian    | 182      | 2.50               | 177      | 2.10               | 169      | 2.00               | 203      | 2.80               | 164      | 2.30               | 895       | 2.30                   | 
| Others   | 201      | 2.80               | 246      | 3.00               | 221      | 2.70               | 196      | 2.70               | 154      | 2.10               | 1018      | 2.60                   | 
| Subtotal | 7227     | 100.00             | 8311     | 100.00             | 8283     | 100.00             | 7342     | 100.00             | 7256     | 100.00             | 38419     | 100.00                 | 
| Unknown  | 2818     |                    | 3655     |                    | 3983     |                    | 4002     |                    | 4567     |                    | 19025     |                        | 
| Total    | 10045    |                    | 11966    |                    | 12266    |                    | 11344    |                    | 11823    |                    | 57444     |                        | 
```