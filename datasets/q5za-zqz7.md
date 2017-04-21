# FY16 PMMR Agency Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy16-pmmr-agency-performance-indicators) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q5za-zqz7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q5za-zqz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q5za-zqz7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q5za-zqz7 |
| Name | FY16 PMMR Agency Performance Indicators |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Tags | pmmr, mmr, indicators, metrics, performance, ops, 2016, management, report, fy16, operations |
| Created | 2016-02-05T22:41:12Z |
| Publication Date | 2016-02-05T22:43:36Z |

## Description

NYC agency performance indicators from the FY16 Preliminary Mayor's Management Report (PMMR)

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | pmmr_goal             | PMMR Goal             | text      | text        |
| Yes      | series tag  | critical              | Critical              | text      | text        |
| Yes      | series tag  | performance_indicator | Performance Indicator | text      | text        |
| Yes      | series tag  | fy13                  | FY13                  | text      | text        |
| Yes      | series tag  | fy14                  | FY14                  | text      | text        |
| Yes      | series tag  | fy15                  | FY15                  | text      | text        |
| Yes      | series tag  | tgt16                 | TGT16                 | text      | text        |
| Yes      | series tag  | tgt17                 | TGT17                 | text      | text        |
| Yes      | series tag  | 4_month_actual_fy15   | 4-Month Actual FY15   | text      | text        |
| Yes      | series tag  | 4_month_actual_fy16   | 4-Month Actual FY16   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q5za-zqz7 d:2016-02-05T14:41:18.000Z t:critical=TRUE t:fy13=19,917 t:fy14=21,346 t:fy15=21,079 t:performance_indicator="311 calls (000)" t:pmmr_goal=1a t:agency=311 t:tgt17=* t:tgt16=* t:4_month_actual_fy16=6,089 t:4_month_actual_fy15=5,836 m:row_number.q5za-zqz7=1

series e:q5za-zqz7 d:2016-02-05T14:41:18.000Z t:critical=TRUE t:fy13=3,998 t:fy14=5,248 t:fy15=9,656 t:performance_indicator="311 Online site visits (000)" t:pmmr_goal=1a t:agency=311 t:tgt17=UP t:tgt16=UP t:4_month_actual_fy16=3,985 t:4_month_actual_fy15=2,431 m:row_number.q5za-zqz7=2

series e:q5za-zqz7 d:2016-02-05T14:41:18.000Z t:critical=FALSE t:fy13=2.10% t:fy14=1.80% t:fy15=2.50% t:performance_indicator="Calls handled in languages other than English (%)" t:pmmr_goal=1a t:agency=311 t:tgt17=* t:tgt16=* t:4_month_actual_fy16=3.20% t:4_month_actual_fy15=2.30% m:row_number.q5za-zqz7=3
```

## Meta Commands

```ls
metric m:row_number.q5za-zqz7 p:long l:"Row Number"

entity e:q5za-zqz7 l:"FY16 PMMR Agency Performance Indicators" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/q5za-zqz7

property e:q5za-zqz7 t:meta.view v:id=q5za-zqz7 v:category="City Government" v:averageRating=0 v:name="FY16 PMMR Agency Performance Indicators" v:attribution="Mayor's Office of Operations (OPS)"

property e:q5za-zqz7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q5za-zqz7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | pmmr_goal | critical | performance_indicator                                               | fy13    | fy14    | fy15    | tgt16 | tgt17 | 4_month_actual_fy15 | 4_month_actual_fy16 | 
| =========== | ====== | ========= | ======== | =================================================================== | ======= | ======= | ======= | ===== | ===== | =================== | =================== | 
| 1454683278  | 311    | 1a        | TRUE     | 311 calls (000)                                                     | 19,917  | 21,346  | 21,079  | *     | *     | 5,836               | 6,089               | 
| 1454683278  | 311    | 1a        | TRUE     | 311 Online site visits (000)                                        | 3,998   | 5,248   | 9,656   | UP    | UP    | 2,431               | 3,985               | 
| 1454683278  | 311    | 1a        | FALSE    | Calls handled in languages other than English (%)                   | 2.10%   | 1.80%   | 2.50%   | *     | *     | 2.30%               | 3.20%               | 
| 1454683278  | 311    | 1a        | TRUE     | Average wait time (tier 1 calls) (minutes:seconds)                  | 0:38    | 0:23    | 0:23    | 0:30  | 0:30  | 0:13                | 0:14                | 
| 1454683278  | 311    | 1a        | TRUE     | Calls answered in 30 seconds (%)                                    | 81%     | 83%     | 84%     | 80%   | 80%   | 91%                 | 90%                 | 
| 1454683278  | 311    | 1a        | FALSE    | Call takers time occupied (%)                                       | 78%     | 79%     | 77%     | *     | *     | 75%                 | 76%                 | 
| 1454683278  | 311    | 1a        | FALSE    | Calls resolved at 311 without transfer to agency for resolution (%) | 91%     | 93%     | 94%     | *     | *     | 92%                 | 92%                 | 
| 1454683278  | 311    | 1a        | FALSE    | Complaints about 311 per million calls                              | 26      | 23      | 26      | *     | *     | 30                  | 34                  | 
| 1454683278  | 311    | 2a        | FALSE    | Completed requests for interpretation                               | 421,839 | 392,759 | 531,194 | *     | *     | 132,791             | 191,959             | 
| 1454683278  | 311    | 2a        | FALSE    | Letters responded to in 14 days (%)                                 | 100%    | NA      | NA      | *     | *     | NA                  | NA                  | 
```