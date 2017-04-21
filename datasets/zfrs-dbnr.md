# Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Collectors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bureau-of-sanitation-unscheduled-absences-by-day-of-week-for-refuse-collectors-a08b3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/zfrs-dbnr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/zfrs-dbnr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/zfrs-dbnr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | zfrs-dbnr |
| Name | Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Collectors |
| Category | Sanitation |
| Created | 2011-09-27T21:51:52Z |
| Publication Date | 2011-09-27T21:52:03Z |

## Description

Number of call outs by day of the week from August 2010 - August 2011 for Refuse Laborers in Streets & Sanitation Department

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                              | Data Type | Render Type |
| ======== | ============== | ================================================================= | ================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                       | updated_at                                                        | meta_data | meta_data   |
| No       |                | day_of_the_week                                                   | Day of the Week                                                   | text      | text        |
| Yes      | numeric metric | average_unscheduled_absences_by_day_of_week_for_refuse_collectors | Average Unscheduled Absences by Day of Week for Refuse Collectors | number    | number      |
| Yes      | numeric metric | unscheduled_absence                                               | Unscheduled Absences (Yearly Total)                               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = day_of_the_week
```

## Data Commands

```ls
series e:zfrs-dbnr d:2011-09-26T19:32:00.000Z m:average_unscheduled_absences_by_day_of_week_for_refuse_collectors=40 m:unscheduled_absence=2011

series e:zfrs-dbnr d:2011-09-26T19:32:02.000Z m:average_unscheduled_absences_by_day_of_week_for_refuse_collectors=30 m:unscheduled_absence=1683

series e:zfrs-dbnr d:2011-09-26T19:32:05.000Z m:average_unscheduled_absences_by_day_of_week_for_refuse_collectors=28 m:unscheduled_absence=1612
```

## Meta Commands

```ls
metric m:average_unscheduled_absences_by_day_of_week_for_refuse_collectors p:integer l:"Average Unscheduled Absences by Day of Week for Refuse Collectors" t:dataTypeName=number

metric m:unscheduled_absence p:integer l:"Unscheduled Absences (Yearly Total)" t:dataTypeName=number

entity e:zfrs-dbnr l:"Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Collectors" t:url=https://data.cityofchicago.org/api/views/zfrs-dbnr

property e:zfrs-dbnr t:meta.view v:id=zfrs-dbnr v:category=Sanitation v:averageRating=0 v:name="Bureau of Sanitation - Unscheduled Absences by Day of Week for Refuse Collectors"

property e:zfrs-dbnr t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:zfrs-dbnr t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| :updated_at | day_of_the_week | average_unscheduled_absences_by_day_of_week_for_refuse_collectors | unscheduled_absence | 
| =========== | =============== | ================================================================= | =================== | 
| 1317065520  | Monday          | 40                                                                | 2011                | 
| 1317065522  | Tuesday         | 30                                                                | 1683                | 
| 1317065525  | Wednesday       | 28                                                                | 1612                | 
| 1317065528  | Thursday        | 27                                                                | 1473                | 
| 1317135120  | Friday          | 31                                                                | 1658                | 
```