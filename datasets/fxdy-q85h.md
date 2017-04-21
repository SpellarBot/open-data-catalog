# FY15 MMR Agency Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mmr-agency-performance-indicators) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fxdy-q85h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fxdy-q85h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fxdy-q85h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fxdy-q85h |
| Name | FY15 MMR Agency Performance Indicators |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Tags | mmr, management, report, key performance indicators, kpi, metrics |
| Created | 2015-11-25T15:09:32Z |
| Publication Date | 2017-03-28T15:58:48Z |

## Description

NYC agency performance indicators from the Mayor's Management Report (MMR)

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | mmr_goal              | MMR Goal              | text      | text        |
| Yes      | series tag  | critical              | Critical              | text      | text        |
| Yes      | series tag  | performance_indicator | Performance Indicator | text      | text        |
| Yes      | series tag  | fy11                  | FY11                  | text      | text        |
| Yes      | series tag  | fy12                  | FY12                  | text      | text        |
| Yes      | series tag  | fy13                  | FY13                  | text      | text        |
| Yes      | series tag  | fy14                  | FY14                  | text      | text        |
| Yes      | series tag  | fy15                  | FY15                  | text      | text        |
| Yes      | series tag  | tgt15                 | TGT15                 | text      | text        |
| Yes      | series tag  | tgt16                 | TGT16                 | text      | text        |
| Yes      | series tag  | desired_direction     | Desired direction     | text      | text        |
| Yes      | series tag  | 5_yr_trend            | 5 yr trend            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fxdy-q85h d:2017-03-28T15:57:49.000Z t:critical=TRUE t:fy11=21,730 t:fy12=18,957 t:fy13=19,917 t:desired_direction=Neutral t:fy14=21,346 t:fy15=21,079 t:tgt15=* t:performance_indicator="311 calls (000)" t:agency="3 1 1" t:mmr_goal=1a t:tgt16=* t:5_yr_trend=Neutral m:row_number.fxdy-q85h=1

series e:fxdy-q85h d:2017-03-28T15:57:49.000Z t:critical=TRUE t:fy11=1,329 t:fy12=2,117 t:fy13=3,998 t:desired_direction=Up t:fy14=5,248 t:fy15=9,656 t:tgt15=Up t:performance_indicator="311 Online site visits (000)" t:agency="3 1 1" t:mmr_goal=1a t:tgt16=Up t:5_yr_trend=Up m:row_number.fxdy-q85h=2

series e:fxdy-q85h d:2017-03-28T15:57:49.000Z t:critical=FALSE t:fy11=2.70% t:fy12=2.20% t:fy13=2.10% t:desired_direction=Neutral t:fy14=1.80% t:fy15=2.50% t:tgt15=* t:performance_indicator="Calls handled in languages other than English (%)" t:agency="3 1 1" t:mmr_goal=1a t:tgt16=* t:5_yr_trend=Down m:row_number.fxdy-q85h=3
```

## Meta Commands

```ls
metric m:row_number.fxdy-q85h p:long l:"Row Number"

entity e:fxdy-q85h l:"FY15 MMR Agency Performance Indicators" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/fxdy-q85h

property e:fxdy-q85h t:meta.view v:id=fxdy-q85h v:category="City Government" v:averageRating=0 v:name="FY15 MMR Agency Performance Indicators" v:attribution="Mayor's Office of Operations (OPS)"

property e:fxdy-q85h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fxdy-q85h t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | mmr_goal | critical | performance_indicator                              | fy11    | fy12    | fy13    | fy14    | fy15    | tgt15 | tgt16 | desired_direction | 5_yr_trend | 
| =========== | ====== | ======== | ======== | ================================================== | ======= | ======= | ======= | ======= | ======= | ===== | ===== | ================= | ========== | 
| 1490716669  | 3 1 1  | 1a       | TRUE     | 311 calls (000)                                    | 21,730  | 18,957  | 19,917  | 21,346  | 21,079  | *     | *     | Neutral           | Neutral    | 
| 1490716669  | 3 1 1  | 1a       | TRUE     | 311 Online site visits (000)                       | 1,329   | 2,117   | 3,998   | 5,248   | 9,656   | Up    | Up    | Up                | Up         | 
| 1490716669  | 3 1 1  | 1a       | FALSE    | Calls handled in languages other than English (%)  | 2.70%   | 2.20%   | 2.10%   | 1.80%   | 2.50%   | *     | *     | Neutral           | Down       | 
| 1490716669  | 3 1 1  | 1a       | TRUE     | Average wait time (tier 1 calls) (minutes:seconds) | 0:31    | 0:45    | 0:38    | 0:23    | 0:23    | 0:30  | 0:30  | Down              | Down       | 
| 1490716669  | 3 1 1  | 1a       | TRUE     | Calls answered in 30 seconds (%)                   | 78%     | 71%     | 81%     | 83%     | 84%     | 80%   | 80%   | Up                | Up         | 
| 1490716669  | 3 1 1  | 1a       | FALSE    | Call takers time occupied (%)                      | 80%     | 80%     | 78%     | 79%     | 77%     | *     | *     | Up                | Neutral    | 
| 1490716669  | 3 1 1  | 1a       | FALSE    | Complaints about 311 per million calls             | 24.9    | 30      | 26      | 23      | 26      | *     | *     | Down              | Neutral    | 
| 1490716669  | 3 1 1  | 2a       | FALSE    | Completed requests for interpretation              | 595,101 | 425,157 | 421,839 | 392,759 | 531,194 | *     | *     | Neutral           | Down       | 
| 1490716669  | 3 1 1  | 2a       | FALSE    | Letters responded to in 14 days (%)                | 96%     | 100%    | 100%    | NA      | NA      | *     | *     | Neutral           | NA         | 
| 1490716669  | 3 1 1  | 2a       | FALSE    | E-mails responded to in 14 days (%)                | 100%    | 100%    | 100%    | 100%    | 100%    | *     | *     | Neutral           | Neutral    | 
```