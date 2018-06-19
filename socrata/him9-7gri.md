# FY17 PMMR Agency Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy17-pmmr-agency-performance-indicators) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/him9-7gri) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/him9-7gri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/him9-7gri/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | him9-7gri |
| Name | FY17 PMMR Agency Performance Indicators |
| Attribution | Mayor?s Office of Operations (OPS) |
| Category | City Government |
| Tags | critical, target, desired direction, goals, services, fiscal 2017, fy17, pmmr, mmr, indicators, metrics, performance, ops, 2017, management, report, operations, pmmr goals, pmmr services, pmmr tar... |
| Created | 2017-02-06T22:43:50Z |
| Publication Date | 2017-02-09T17:33:49Z |

## Description

NYC agency performance indicators from the FY17 Preliminary Mayor's Management Report (PMMR)

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | pmmr_goal             | PMMR Goal             | text      | text        |
| Yes      | series tag  | critical              | Critical              | text      | text        |
| Yes      | series tag  | performance_indicator | Performance Indicator | text      | text        |
| Yes      | series tag  | fy14                  | FY14                  | text      | text        |
| Yes      | series tag  | fy15                  | FY15                  | text      | text        |
| Yes      | series tag  | fy16                  | FY16                  | text      | text        |
| Yes      | series tag  | tgt17                 | TGT17                 | text      | text        |
| Yes      | series tag  | tgt18                 | TGT18                 | text      | text        |
| Yes      | series tag  | fy16_4_month_actual   | FY16 4-Month Actual   | text      | text        |
| Yes      | series tag  | fy17_4_month_actual   | FY17 4-Month Actual   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:him9-7gri d:2017-02-09T17:33:25.000Z t:fy16_4_month_actual=6,089 t:critical=TRUE t:tgt18=* t:fy14=21,346 t:fy15=21,079 t:fy16=18,799 t:performance_indicator="311 calls (000)" t:pmmr_goal=1a t:agency=3-1-1 t:tgt17=* t:fy17_4_month_actual=6,199 m:row_number.him9-7gri=1

series e:him9-7gri d:2017-02-09T17:33:25.000Z t:fy16_4_month_actual=3,985 t:critical=TRUE t:tgt18=UP t:fy14=5,248 t:fy15=9,656 t:fy16=13,018 t:performance_indicator="311 Online site visits (000)" t:pmmr_goal=1a t:agency=3-1-1 t:tgt17=UP t:fy17_4_month_actual=5,449 m:row_number.him9-7gri=2

series e:him9-7gri d:2017-02-09T17:33:25.000Z t:fy16_4_month_actual=302 t:critical=FALSE t:tgt18=* t:fy14=NA t:fy15=705 t:fy16=1,010 t:performance_indicator="311 mobile app contacts (000)" t:pmmr_goal=1a t:agency=3-1-1 t:tgt17=* t:fy17_4_month_actual=357 m:row_number.him9-7gri=3
```

## Meta Commands

```ls
metric m:row_number.him9-7gri p:long l:"Row Number"

entity e:him9-7gri l:"FY17 PMMR Agency Performance Indicators" t:attribution="Mayor?s Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/him9-7gri

property e:him9-7gri t:meta.view v:id=him9-7gri v:category="City Government" v:averageRating=0 v:name="FY17 PMMR Agency Performance Indicators" v:attribution="Mayor?s Office of Operations (OPS)"

property e:him9-7gri t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:him9-7gri t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | pmmr_goal | critical | performance_indicator                                               | fy14   | fy15   | fy16   | tgt17 | tgt18 | fy16_4_month_actual | fy17_4_month_actual | 
| =========== | ====== | ========= | ======== | =================================================================== | ====== | ====== | ====== | ===== | ===== | =================== | =================== | 
| 1486661605  | 3-1-1  | 1a        | TRUE     | 311 calls (000)                                                     | 21,346 | 21,079 | 18,799 | *     | *     | 6,089               | 6,199               | 
| 1486661605  | 3-1-1  | 1a        | TRUE     | 311 Online site visits (000)                                        | 5,248  | 9,656  | 13,018 | UP    | UP    | 3,985               | 5,449               | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | 311 mobile app contacts (000)                                       | NA     | 705    | 1,010  | *     | *     | 302                 | 357                 | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | 311-NYC (text) contacts (000)                                       | 234    | 175    | 156    | *     | *     | 46                  | 42                  | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | Calls handled in languages other than English (%)                   | 1.8%   | 2.5%   | 3.0%   | *     | *     | 3.2%                | 3.0%                | 
| 1486661605  | 3-1-1  | 1a        | TRUE     | Average wait time (tier 1 calls) (minutes:seconds)                  | 0:23   | 0:23   | 0:16   | 0:30  | 0:30  | 0:14                | 0:16                | 
| 1486661605  | 3-1-1  | 1a        | TRUE     | Calls answered in 30 seconds (%)                                    | 83%    | 84%    | 89%    | 80%   | 80%   | 90%                 | 85%                 | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | Call takers time occupied (%)                                       | 79%    | 77%    | 74%    | *     | *     | 76%                 | 74%                 | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | Calls resolved at 311 without transfer to agency for resolution (%) | 93%    | 94%    | 93%    | *     | *     | 92%                 | 93%                 | 
| 1486661605  | 3-1-1  | 1a        | FALSE    | Complaints about 311 per million calls                              | 23.0   | 26.0   | 32.0   | *     | *     | 34.0                | 33.0                | 
```