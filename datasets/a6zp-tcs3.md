# FY 2017 PMMR Data Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-2017-pmmr-data-extract) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a6zp-tcs3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a6zp-tcs3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a6zp-tcs3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a6zp-tcs3 |
| Name | FY 2017 PMMR Data Extract |
| Category | City Government |
| Created | 2017-02-03T18:43:48Z |
| Publication Date | 2017-02-09T20:29:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | agency                | Agency                | text      | text        |
| Yes      | series tag     | pmmr_goal             | PMMR Goal             | text      | text        |
| Yes      | numeric metric | critical              | Critical              | number    | number      |
| Yes      | series tag     | performance_indicator | Performance Indicator | text      | text        |
| Yes      | series tag     | actual_fy14           | Actual FY14           | text      | text        |
| Yes      | series tag     | actual_fy15           | Actual FY15           | text      | text        |
| Yes      | series tag     | actual_fy16           | Actual FY16           | text      | text        |
| Yes      | series tag     | target_fy17           | Target FY17           | text      | text        |
| Yes      | series tag     | target_fy18           | Target FY18           | text      | text        |
| Yes      | series tag     | 4_month_actual_fy16   | 4-Month Actual FY16   | text      | text        |
| Yes      | series tag     | 4_month_actual_fy17   | 4-Month Actual FY17   | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a6zp-tcs3 d:2017-01-01T00:00:00.000Z t:4_month_actual_fy17=6,199 t:target_fy17=* t:actual_fy14=21,346 t:target_fy18=* t:actual_fy15=21,079 t:performance_indicator="311 calls (000)" t:actual_fy16=18,799 t:pmmr_goal=1a t:agency=3-1-1 t:4_month_actual_fy16=6,089 m:critical=1

series e:a6zp-tcs3 d:2017-01-01T00:00:00.000Z t:4_month_actual_fy17=5,449 t:target_fy17=? t:actual_fy14=5,248 t:target_fy18=? t:actual_fy15=9,656 t:performance_indicator="311 Online site visits (000)" t:actual_fy16=13,018 t:pmmr_goal=1a t:agency=3-1-1 t:4_month_actual_fy16=3,985 m:critical=1

series e:a6zp-tcs3 d:2017-01-01T00:00:00.000Z t:4_month_actual_fy17=357 t:target_fy17=* t:actual_fy14=NA t:target_fy18=* t:actual_fy15=705 t:performance_indicator="311 mobile app contacts (000)" t:actual_fy16=1,010 t:pmmr_goal=1a t:agency=3-1-1 t:4_month_actual_fy16=302 m:critical=0
```

## Meta Commands

```ls
metric m:critical p:integer l:Critical t:dataTypeName=number

entity e:a6zp-tcs3 l:"FY 2017 PMMR Data Extract" t:url=https://data.cityofnewyork.us/api/views/a6zp-tcs3

property e:a6zp-tcs3 t:meta.view v:id=a6zp-tcs3 v:category="City Government" v:averageRating=0 v:name="FY 2017 PMMR Data Extract"

property e:a6zp-tcs3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a6zp-tcs3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency | pmmr_goal | critical | performance_indicator                                                   | actual_fy14 | actual_fy15 | actual_fy16 | target_fy17 | target_fy18 | 4_month_actual_fy16 | 4_month_actual_fy17 | 
| ====== | ========= | ======== | ======================================================================= | =========== | =========== | =========== | =========== | =========== | =================== | =================== | 
| 3-1-1  | 1a        | 1        | 311 calls (000)                                                         | 21,346      | 21,079      | 18,799      | *           | *           | 6,089               | 6,199               | 
| 3-1-1  | 1a        | 1        | 311 Online site visits (000)                                            | 5,248       | 9,656       | 13,018      | ?           | ?           | 3,985               | 5,449               | 
| 3-1-1  | 1a        | 0        | 311 mobile app contacts (000)                                           | NA          | 705         | 1,010       | *           | *           | 302                 | 357                 | 
| 3-1-1  | 1a        | 0        | 311-NYC (text) contacts (000)                                           | 234         | 175         | 156         | *           | *           | 46                  | 42                  | 
| 3-1-1  | 1a        | 0        | Calls handled in languages other than English (%)                       | 1.8%        | 2.5%        | 3.0%        | *           | *           | 3.2%                | 3.0%                | 
| 3-1-1  | 1a        | 1        | Average wait time (tier 1 calls) (minutes:seconds)                      | 0:23        | 0:23        | 0:16        | 0:30        | 0:30        | 0:14                | 0:16                | 
| 3-1-1  | 1a        | 0        | Average wait time (tier 2 agency legacy system calls) (minutes:seconds) | 2:06        | 0:44        | 0:10        | *           | *           | 0:15                | 0:09                | 
| 3-1-1  | 1a        | 1        | Calls answered in 30 seconds (%)                                        | 83%         | 84%         | 89%         | 80%         | 80%         | 90%                 | 85%                 | 
| 3-1-1  | 1a        | 0        | Maximum answer delay (minutes:seconds)                                  | 116:20      | 33:45       | 62:58       | *           | *           | 33:21               | 16:39               | 
| 3-1-1  | 1a        | 0        | Call takers time occupied (%)                                           | 79%         | 77%         | 74%         | *           | *           | 76%                 | 74%                 | 
```