# FY03 ? FY12 MMR Agency Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mayors-management-report-mmr-values-2003-to-2012-93d9d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jhjm-vsp8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jhjm-vsp8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jhjm-vsp8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jhjm-vsp8 |
| Name | FY03 ? FY12 MMR Agency Performance Indicators |
| Attribution | Mayor's Office of Operations (Ops) |
| Category | City Government |
| Tags | mayor's management report (mmr) values, mmr, stats, statistics, ops, operations, data |
| Created | 2013-01-02T16:26:53Z |
| Publication Date | 2013-06-21T19:50:54Z |

## Description

Annual NYC agency reporting statistics taken from the Mayor's Management Report.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | agency         | Agency         | text      | text        |
| Yes      | series tag  | indicator_name | Indicator Name | text      | text        |
| No       |             | _1             | 2003           | text      | text        |
| No       |             | _2             | 2004           | text      | text        |
| No       |             | _3             | 2005           | text      | text        |
| No       |             | _4             | 2006           | text      | text        |
| No       |             | _5             | 2007           | money     | text        |
| No       |             | _6             | 2008           | text      | text        |
| No       |             | _7             | 2009           | money     | text        |
| No       |             | _8             | 2010           | money     | text        |
| No       |             | _9             | 2011           | text      | text        |
| Yes      | series tag  | _10            | 2012           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:jhjm-vsp8 d:2013-01-04T08:07:51.000Z t:indicator_name="311 Online site visits (000)" t:_10=2,117.10 t:agency=311 m:row_number.jhjm-vsp8=1

series e:jhjm-vsp8 d:2013-01-04T08:07:51.000Z t:indicator_name="311 calls (000)" t:_10=18,957.50 t:agency=311 m:row_number.jhjm-vsp8=2

series e:jhjm-vsp8 d:2013-01-04T08:07:51.000Z t:indicator_name="Average wait time (tier 1 calls) (minutes:seconds)" t:_10=0:45 t:agency=311 m:row_number.jhjm-vsp8=3
```

## Meta Commands

```ls
metric m:row_number.jhjm-vsp8 p:long l:"Row Number"

entity e:jhjm-vsp8 l:"FY03 ? FY12 MMR Agency Performance Indicators" t:attribution="Mayor's Office of Operations (Ops)" t:url=https://data.cityofnewyork.us/api/views/jhjm-vsp8

property e:jhjm-vsp8 t:meta.view v:id=jhjm-vsp8 v:category="City Government" v:averageRating=0 v:name="FY03 ? FY12 MMR Agency Performance Indicators" v:attribution="Mayor's Office of Operations (Ops)"

property e:jhjm-vsp8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jhjm-vsp8 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | agency | indicator_name                                                          | _1 | _2       | _3        | _4        | _5        | _6        | _7        | _8        | _9        | _10       | 
| =========== | ====== | ======================================================================= | == | ======== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| 1357286871  | 311    | 311 Online site visits (000)                                            |    |          |           |           |           |           |           | 740.5     | 1,328.80  | 2,117.10  | 
| 1357286871  | 311    | 311 calls (000)                                                         |    | 8,140.90 | 12,503.20 | 14,245.40 | 14,314.70 | 15,212.90 | 18,363.10 | 18,642.60 | 21,730.00 | 18,957.50 | 
| 1357286871  | 311    | Average wait time (tier 1 calls) (minutes:seconds)                      |    |          |           |           | 0:05      | 0:07      | 0:12      | 0:22      | 0:31      | 0:45      | 
| 1357286871  | 311    | Average wait time (tier 2 agency legacy system calls) (minutes:seconds) |    |          |           |           | 0:09      | 0:14      | 0:25      | 1:04      | 2:03      | 1:43      | 
| 1357286871  | 311    | Call takers time occupied (%)                                           |    | 56%      | 73%       | 67%       | 65%       | 63%       | 69%       | 78%       | 80%       | 80%       | 
| 1357286871  | 311    | Calls answered in 30 seconds or less (%)                                |    | 90%      | 63%       | 88%       | 96%       | 97%       | 88%       | 82%       | 78%       | 71%       | 
| 1357286871  | 311    | Calls handled in languages other than English (%)                       |    | 1.30%    | 1.30%     | 1.90%     | 2.40%     | 1.90%     | 3.60%     | 3.40%     | 2.70%     | 2.20%     | 
| 1357286871  | 311    | Calls resolved at 311 without transfer to agency for resolution (%)     |    |          |           | 79%       | 77%       | 80%       | 84%       | 86%       | 89%       | 90%       | 
| 1357286871  | 311    | Complaints about 311 per million calls                                  |    |          |           |           | 46        | 36.5      | 32.7      | 29.2      | 24.9      | 30        | 
| 1357286871  | 311    | Maximum answer delay (minutes:seconds)                                  |    |          |           | 17:43     | 20:15     | 42:28:00  | 68:76     | 69:36:00  | 86:25:00  | 94:16:00  | 
```