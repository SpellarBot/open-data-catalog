# Quality Of Life Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quality-of-life-indicators-a785e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8hkx-uppz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8hkx-uppz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8hkx-uppz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8hkx-uppz |
| Name | Quality Of Life Indicators |
| Attribution | Downtown Alliance |
| Category | City Government |
| Tags | life, quality, statistic, community |
| Created | 2011-08-30T22:14:23Z |
| Publication Date | 2013-06-26T17:12:44Z |

## Description

Statistics on NYC quality of life

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | indicator   | INDICATOR  | text      | text        |
| Yes      | numeric metric | q1_09       | Q1 09      | percent   | percent     |
| Yes      | numeric metric | q2_09       | Q2 09      | percent   | percent     |
| Yes      | numeric metric | q3_09       | Q3 09      | percent   | percent     |
| Yes      | numeric metric | q4_09       | Q4 09      | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8hkx-uppz d:2011-08-30T15:14:24.000Z t:indicator="Downtown Commercial Vacancy Rates" m:q3_09=9.9 m:q1_09=8.1 m:q2_09=8.7 m:q4_09=9.6

series e:8hkx-uppz d:2011-08-30T15:14:24.000Z t:indicator="Hotel Occupancy Rates*" m:q3_09=87.8 m:q1_09=68.61 m:q2_09=84.22 m:q4_09=86

series e:8hkx-uppz d:2011-08-30T15:14:24.000Z t:indicator="Operation Scorecard - Percentage of Acceptably Clean Streets" m:q3_09=97.8 m:q1_09=98.8 m:q2_09=97.5 m:q4_09=99.4
```

## Meta Commands

```ls
metric m:q1_09 p:double l:"Q1 09" t:dataTypeName=percent

metric m:q2_09 p:double l:"Q2 09" t:dataTypeName=percent

metric m:q3_09 p:double l:"Q3 09" t:dataTypeName=percent

metric m:q4_09 p:double l:"Q4 09" t:dataTypeName=percent

entity e:8hkx-uppz l:"Quality Of Life Indicators" t:attribution="Downtown Alliance" t:url=https://data.cityofnewyork.us/api/views/8hkx-uppz

property e:8hkx-uppz t:meta.view v:id=8hkx-uppz v:category="City Government" v:averageRating=0 v:name="Quality Of Life Indicators" v:attribution="Downtown Alliance"

property e:8hkx-uppz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8hkx-uppz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | indicator                                                      | q1_09  | q2_09   | q3_09   | q4_09   | 
| =========== | ============================================================== | ====== | ======= | ======= | ======= | 
| 1314717264  | Downtown Commercial Vacancy Rates                              | 8.1    | 8.7     | 9.9     | 9.60    | 
| 1314717264  | Hotel Occupancy Rates*                                         | 68.61  | 84.22   | 87.8    | 86      | 
| 1314717264  | Operation Scorecard - Percentage of Acceptably Clean Streets   | 98.8   | 97.5    | 97.8    | 99.40   | 
| 1314717264  | Operation Scorecard - Percentage of Acceptably Clean Sidewalks | 98.2   | 99.4    | 100.0   | 100     | 
| 1314717264  | Visitors to Downtown Attractions*                              | 704461 | 2272824 | 2650642 | 1228309 | 
| 1314717264  | Average # of Homeless Individuals Encountered in Weekly 1 Hour | 2.18   | 4.47    | 2.43    | 3.33    | 
| 1314717264  | Number of Homeless encountered by Outreach Workers             | 187    | 106     |         | 239     | 
| 1314717264  | Services Accepted                                              | 88     | 53      |         | 150     | 
| 1314717264  | Services Declined                                              | 99     | 53      |         | 195     | 
| 1314717264  | Public Contacts                                                | 164273 | 198670  | 217154  | 141836  | 
```