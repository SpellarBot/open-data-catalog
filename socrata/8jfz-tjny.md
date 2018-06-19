# FY16 MMR Agency Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy16-mmr-performance-indicators-data-for-open-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8jfz-tjny) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8jfz-tjny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8jfz-tjny/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8jfz-tjny |
| Name | FY16 MMR Agency Performance Indicators |
| Category | City Government |
| Tags | 5 yr trend, 5 year trend, critical target, desired direction, goals, services, fiscal 2016, mmr fy16, fy16, pmmr, mmr, indicators, metrics, performance, ops, 2016, management, report, operations, ... |
| Created | 2016-09-26T19:18:54Z |
| Publication Date | 2016-09-26T19:24:49Z |

## Description

NYC agency performance indicators from the FY16 Mayor's Management Report (MMR).

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | mmr_goal              | MMR Goal              | text      | text        |
| Yes      | series tag  | critical              | Critical              | text      | text        |
| Yes      | series tag  | performance_indicator | Performance Indicator | text      | text        |
| Yes      | series tag  | fy12                  | FY12                  | text      | text        |
| Yes      | series tag  | fy13                  | FY13                  | text      | text        |
| Yes      | series tag  | fy14                  | FY14                  | text      | text        |
| Yes      | series tag  | fy15                  | FY15                  | text      | text        |
| Yes      | series tag  | fy16                  | FY16                  | text      | text        |
| Yes      | series tag  | tgt16                 | TGT16                 | text      | text        |
| Yes      | series tag  | tgt17                 | TGT17                 | text      | text        |
| Yes      | series tag  | desired_direction     | Desired direction     | text      | text        |
| Yes      | series tag  | 5yr_trend             | 5yr trend             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8jfz-tjny d:2016-09-26T19:18:56.000Z t:critical=TRUE t:fy12=18,957 t:fy13=19,917 t:desired_direction=Neutral t:fy14=21,346 t:fy15=21,079 t:5yr_trend=Neutral t:fy16=18,799 t:performance_indicator="311 calls (000)" t:agency=3-1-1 t:tgt17=* t:mmr_goal=1a t:tgt16=* m:row_number.8jfz-tjny=1

series e:8jfz-tjny d:2016-09-26T19:18:56.000Z t:critical=TRUE t:fy12=2,117 t:fy13=3,998 t:desired_direction=Up t:fy14=5,248 t:fy15=9,656 t:5yr_trend=Up t:fy16=13,018 t:performance_indicator="311 Online site visits (000)" t:agency=3-1-1 t:tgt17=Up t:mmr_goal=1a t:tgt16=Up m:row_number.8jfz-tjny=2

series e:8jfz-tjny d:2016-09-26T19:18:56.000Z t:critical=FALSE t:fy12=NA t:fy13=NA t:desired_direction=Up t:fy14=NA t:fy15=705 t:5yr_trend=NA t:fy16=1,010 t:performance_indicator="311 mobile app contacts (000)" t:agency=3-1-1 t:tgt17=* t:mmr_goal=1a t:tgt16=* m:row_number.8jfz-tjny=3
```

## Meta Commands

```ls
metric m:row_number.8jfz-tjny p:long l:"Row Number"

entity e:8jfz-tjny l:"FY16 MMR Agency Performance Indicators" t:url=https://data.cityofnewyork.us/api/views/8jfz-tjny

property e:8jfz-tjny t:meta.view v:id=8jfz-tjny v:category="City Government" v:averageRating=0 v:name="FY16 MMR Agency Performance Indicators"

property e:8jfz-tjny t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8jfz-tjny t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | mmr_goal | critical | performance_indicator                                               | fy12   | fy13   | fy14   | fy15   | fy16   | tgt16 | tgt17 | desired_direction | 5yr_trend | 
| =========== | ====== | ======== | ======== | =================================================================== | ====== | ====== | ====== | ====== | ====== | ===== | ===== | ================= | ========= | 
| 1474917536  | 3-1-1  | 1a       | TRUE     | 311 calls (000)                                                     | 18,957 | 19,917 | 21,346 | 21,079 | 18,799 | *     | *     | Neutral           | Neutral   | 
| 1474917536  | 3-1-1  | 1a       | TRUE     | 311 Online site visits (000)                                        | 2,117  | 3,998  | 5,248  | 9,656  | 13,018 | Up    | Up    | Up                | Up        | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | 311 mobile app contacts (000)                                       | NA     | NA     | NA     | 705    | 1,010  | *     | *     | Up                | NA        | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | 311-NYC (text) contacts (000)                                       | NA     | NA     | 234    | 175    | 156    | *     | *     | Neutral           | NA        | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | Calls handled in languages other than English (%)                   | 2.2%   | 2.1%   | 1.8%   | 2.5%   | 3.0%   | *     | *     | Neutral           | Up        | 
| 1474917536  | 3-1-1  | 1a       | TRUE     | Average wait time (tier 1 calls) (minutes:seconds)                  | 0:45   | 0:38   | 0:23   | 0:23   | 0:16   | 0:30  | 0:30  | Down              | Down      | 
| 1474917536  | 3-1-1  | 1a       | TRUE     | Calls answered in 30 seconds (%)                                    | 71%    | 81%    | 83%    | 84%    | 89%    | 80%   | 80%   | Up                | Up        | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | Call takers time occupied (%)                                       | 80%    | 78%    | 79%    | 77%    | 74%    | *     | *     | Up                | Neutral   | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | Calls resolved at 311 without transfer to agency for resolution (%) | 90%    | 91%    | 93%    | 94%    | 93%    | *     | *     | Up                | Neutral   | 
| 1474917536  | 3-1-1  | 1a       | FALSE    | Complaints about 311 per million calls                              | 30.0   | 26.0   | 23.0   | 26.0   | 32.0   | *     | *     | Down              | Neutral   | 
```