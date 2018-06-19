# Daily Fire Incidents 01012012 Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/daily-fire-incidents-01012012-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/izai-dug8) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/izai-dug8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/izai-dug8/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | izai-dug8 |
| Name | Daily Fire Incidents 01012012 Current |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | fire, public safety, hartford, ct |
| Created | 2015-05-18T17:51:19Z |
| Publication Date | 2015-05-18T17:57:24Z |

## Description

This data set is being used by our HartStat website to display the summary of fire incidents per day. Updated nightly.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | time           | alarm_date            | Alarm Date            | calendar_date | calendar_date |
| Yes      | numeric metric | total_number_of_calls | Total Number of Calls | number        | number        |
| Yes      | numeric metric | fire_calls            | Fire Calls            | number        | number        |
| Yes      | numeric metric | ems_calls             | EMS Calls             | number        | number        |
| Yes      | numeric metric | all_other_calls       | All Other Calls       | number        | number        |
```

## Time Field

```ls
Value = alarm_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:izai-dug8 d:2014-10-16T00:00:00.000Z m:all_other_calls=15 m:total_number_of_calls=56 m:ems_calls=40 m:fire_calls=1

series e:izai-dug8 d:2015-01-07T00:00:00.000Z m:all_other_calls=14 m:total_number_of_calls=46 m:ems_calls=29 m:fire_calls=3

series e:izai-dug8 d:2014-06-06T00:00:00.000Z m:all_other_calls=8 m:total_number_of_calls=41 m:ems_calls=31 m:fire_calls=2
```

## Meta Commands

```ls
metric m:total_number_of_calls p:integer l:"Total Number of Calls" t:dataTypeName=number

metric m:fire_calls p:integer l:"Fire Calls" t:dataTypeName=number

metric m:ems_calls p:integer l:"EMS Calls" t:dataTypeName=number

metric m:all_other_calls p:integer l:"All Other Calls" t:dataTypeName=number

entity e:izai-dug8 l:"Daily Fire Incidents 01012012 Current" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/izai-dug8

property e:izai-dug8 t:meta.view v:id=izai-dug8 v:category="Public Safety" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Daily Fire Incidents 01012012 Current" v:attribution="City of Hartford"

property e:izai-dug8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:izai-dug8 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:izai-dug8 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| alarm_date          | total_number_of_calls | fire_calls | ems_calls | all_other_calls | 
| =================== | ===================== | ========== | ========= | =============== | 
| 2014-10-16T00:00:00 | 56                    | 1          | 40        | 15              | 
| 2015-01-07T00:00:00 | 46                    | 3          | 29        | 14              | 
| 2014-06-06T00:00:00 | 41                    | 2          | 31        | 8               | 
| 2015-04-08T00:00:00 | 63                    | 1          | 42        | 20              | 
| 2015-01-16T00:00:00 | 64                    | 3          | 35        | 26              | 
| 2015-02-28T00:00:00 | 58                    | 1          | 46        | 11              | 
| 2015-02-22T00:00:00 | 66                    | 2          | 41        | 23              | 
| 2014-06-25T00:00:00 | 72                    | 3          | 55        | 14              | 
| 2014-05-10T00:00:00 | 73                    | 3          | 44        | 26              | 
| 2015-01-10T00:00:00 | 46                    | 1          | 33        | 12              | 
```