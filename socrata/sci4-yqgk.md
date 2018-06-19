# Daily Report Of Single Adult And Family Intake

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/daily-report-of-single-adult-and-family-intake-b932a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sci4-yqgk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sci4-yqgk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sci4-yqgk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sci4-yqgk |
| Name | Daily Report Of Single Adult And Family Intake |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, family, adult, intake, daily, report |
| Created | 2013-01-31T15:08:28Z |
| Publication Date | 2013-01-31T15:16:21Z |

## Description

Daily report of how many Single Adults and Families are served

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | date         | Date         | text      | text        |
| Yes      | series tag     | daily_report | Daily Report | text      | text        |
| Yes      | numeric metric | number       | Number       | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yyyy
```

## Data Commands

```ls
series e:sci4-yqgk d:2013-01-28T00:00:00.000Z t:daily_report="Single Adults - Drop-in Center Clients Served" m:number=610

series e:sci4-yqgk d:2013-01-28T00:00:00.000Z t:daily_report="Single Adults - Drop-in Center Overnight Census" m:number=175

series e:sci4-yqgk d:2013-01-28T00:00:00.000Z t:daily_report="Single Adults - Faith Bed Census" m:number=254
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:sci4-yqgk l:"Daily Report Of Single Adult And Family Intake" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/sci4-yqgk

property e:sci4-yqgk t:meta.view v:id=sci4-yqgk v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/dailyreport.pdf v:averageRating=0 v:name="Daily Report Of Single Adult And Family Intake" v:attribution="Department of Homeless Services (DHS)"

property e:sci4-yqgk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sci4-yqgk t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| date       | daily_report                                                        | number | 
| ========== | =================================================================== | ====== | 
| 01/28/2013 | Single Adults - Drop-in Center Clients Served                       | 610    | 
| 01/28/2013 | Single Adults - Drop-in Center Overnight Census                     | 175    | 
| 01/28/2013 | Single Adults - Faith Bed Census                                    | 254    | 
| 01/28/2013 | Single Adults - Outreach Contacts                                   | 253    | 
| 01/28/2013 | Single Adults - Outreach Placements                                 | 11     | 
| 01/28/2013 | Single Adults - Safe Haven Utilization                              | 537    | 
| 01/28/2013 | Single Adults - Veterans In Short-term Housing                      | 376    | 
| 01/28/2013 | Family Intake - Families Requesting Temporary Housing at PATH       | 115    | 
| 01/28/2013 | Family Intake - Adult Families Requesting Temporary Housing at AFIC | 13     | 
| 01/28/2013 | Family Intake - Families Placed in Overnight Accommodations         | 0      | 
```