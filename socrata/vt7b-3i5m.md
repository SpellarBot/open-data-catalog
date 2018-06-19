# LADOT Re Striping After Slurry Metrics FY 13 14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladot-re-striping-after-slurry-metrics-fy-13-14) |
| Metadata | [Link](https://data.lacity.org/api/views/vt7b-3i5m) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vt7b-3i5m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vt7b-3i5m/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vt7b-3i5m |
| Name | LADOT Re Striping After Slurry Metrics FY 13 14 |
| Attribution | LADOT |
| Category | A Well Run City |
| Created | 2014-08-07T22:29:50Z |
| Publication Date | 2015-12-04T21:31:11Z |

## Description

LADOT Re Striping After Slurry Metrics

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type     | Render Type   |
| ======== | ============== | =========================================== | =========================================== | ============= | ============= |
| No       |                | week                                        | Week #                                      | number        | number        |
| Yes      | time           | week_ending                                 | Week Ending                                 | calendar_date | calendar_date |
| Yes      | numeric metric | of_blocks_slurried                          | # of Blocks Slurried                        | number        | number        |
| No       |                | date_dot_notified_of_completion             | Date DOT Notified of Completion             | calendar_date | calendar_date |
| Yes      | numeric metric | days_from_slurry_completion_to_notification | Days from Slurry Completion to Notification | number        | number        |
| Yes      | numeric metric | average_days_to_completed_restriping        | Average Days to Completed Restriping        | number        | number        |
| Yes      | numeric metric | total_days_dark                             | Total Days Dark                             | number        | number        |
```

## Time Field

```ls
Value = week_ending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_dot_notified_of_completion,week
```

## Data Commands

```ls
series e:vt7b-3i5m d:2014-01-04T00:00:00.000Z m:of_blocks_slurried=0

series e:vt7b-3i5m d:2014-01-11T00:00:00.000Z m:of_blocks_slurried=23 m:total_days_dark=8 m:average_days_to_completed_restriping=6 m:days_from_slurry_completion_to_notification=2

series e:vt7b-3i5m d:2014-01-18T00:00:00.000Z m:of_blocks_slurried=43 m:total_days_dark=6 m:average_days_to_completed_restriping=3 m:days_from_slurry_completion_to_notification=3
```

## Meta Commands

```ls
metric m:of_blocks_slurried p:integer l:"# of Blocks Slurried" t:dataTypeName=number

metric m:days_from_slurry_completion_to_notification p:integer l:"Days from Slurry Completion to Notification" t:dataTypeName=number

metric m:average_days_to_completed_restriping p:integer l:"Average Days to Completed Restriping" t:dataTypeName=number

metric m:total_days_dark p:integer l:"Total Days Dark" t:dataTypeName=number

entity e:vt7b-3i5m l:"LADOT Re Striping After Slurry Metrics FY 13 14" t:attribution=LADOT t:url=https://data.lacity.org/api/views/vt7b-3i5m

property e:vt7b-3i5m t:meta.view v:id=vt7b-3i5m v:category="A Well Run City" v:averageRating=0 v:name="LADOT Re Striping After Slurry Metrics FY 13 14" v:attribution=LADOT

property e:vt7b-3i5m t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vt7b-3i5m t:meta.view.owner v:id=epkx-23qu v:screenName="Mike Shimokochi" v:displayName="Mike Shimokochi"

property e:vt7b-3i5m t:meta.view.tableauthor v:id=epkx-23qu v:screenName="Mike Shimokochi" v:roleName=publisher v:displayName="Mike Shimokochi"
```

## Top Records

```ls
| week | week_ending         | of_blocks_slurried | date_dot_notified_of_completion | days_from_slurry_completion_to_notification | average_days_to_completed_restriping | total_days_dark | 
| ==== | =================== | ================== | =============================== | =========================================== | ==================================== | =============== | 
| 27   | 2014-01-04T00:00:00 | 0                  |                                 |                                             |                                      |                 | 
| 28   | 2014-01-11T00:00:00 | 23                 | 2014-01-13T00:00:00             | 2                                           | 6                                    | 8               | 
| 29   | 2014-01-18T00:00:00 | 43                 | 2014-01-21T00:00:00             | 3                                           | 3                                    | 6               | 
| 30   | 2014-01-25T00:00:00 | 63                 | 2014-01-30T00:00:00             | 5                                           | 10                                   | 15              | 
| 31   | 2014-02-01T00:00:00 | 52                 | 2014-02-04T00:00:00             | 3                                           | 14                                   | 17              | 
| 32   | 2014-02-08T00:00:00 | 9                  | 2014-02-20T00:00:00             | 12                                          | 10                                   | 22              | 
| 33   | 2014-02-15T00:00:00 | 82                 | 2014-02-20T00:00:00             | 5                                           | 9                                    | 14              | 
| 34   | 2014-02-22T00:00:00 | 104                | 2014-03-03T00:00:00             | 9                                           | 9                                    | 18              | 
| 35   | 2014-03-01T00:00:00 | 35                 | 2014-03-03T00:00:00             | 2                                           | 13                                   | 15              | 
| 36   | 2014-03-08T00:00:00 | 91                 | 2014-03-12T00:00:00             | 4                                           | 18                                   | 22              | 
```