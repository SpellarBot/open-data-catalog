# FY15 MMR Agency Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mmr-agency-resources) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/erts-eyf6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/erts-eyf6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/erts-eyf6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | erts-eyf6 |
| Name | FY15 MMR Agency Resources |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Tags | mmr, management, report, key performance indicators, kpi, metrics |
| Created | 2015-11-25T15:23:50Z |
| Publication Date | 2015-11-25T15:32:59Z |

## Description

NYC agency resources from the Mayor's Management Report (MMR), including expenditures, personnel, revenue and paid overtime

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                                | Data Type | Render Type |
| ======== | =========== | ================================= | =================================== | ========= | =========== |
| No       | time        | :updated_at                       | updated_at                          | meta_data | meta_data   |
| Yes      | series tag  | agencies                          | Agencies                            | text      | text        |
| Yes      | series tag  | resource_indicators               | Resource Indicators                 | text      | text        |
| Yes      | series tag  | fy11_actual                       | FY11 Actual                         | text      | text        |
| Yes      | series tag  | fy12_actual                       | FY12 Actual                         | text      | text        |
| Yes      | series tag  | fy13_actual                       | FY13 Actual                         | text      | text        |
| Yes      | series tag  | fy14_actual                       | FY14 Actual                         | text      | text        |
| Yes      | series tag  | fy15_actual                       | FY15 Actual                         | text      | text        |
| Yes      | series tag  | fy15_plan_authorized_budget_level | FY15 Plan (Authorized Budget Level) | text      | text        |
| Yes      | series tag  | fy16_plan_authorized_budget_level | FY16 Plan (Authorized Budget Level) | text      | text        |
| Yes      | series tag  | 5yr_trend                         | 5yr Trend                           | text      | text        |
| Yes      | series tag  | includes_all_funds                | Includes all Funds                  | text      | text        |
| Yes      | series tag  | notes                             | Notes                               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:erts-eyf6 d:2015-11-25T07:23:55.000Z t:includes_all_funds=Y t:fy14_actual=$38.3 t:fy11_actual=$45.0 t:5yr_trend=Neutral t:fy12_actual=$42.1 t:agencies=311 t:resource_indicators="Expenditures ($000,000)" t:notes="The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report." t:fy16_plan_authorized_budget_level=$42.6 t:fy13_actual=$39.6 t:fy15_actual=$47.5 t:fy15_plan_authorized_budget_level=$46.0 m:row_number.erts-eyf6=1

series e:erts-eyf6 d:2015-11-25T07:23:55.000Z t:fy14_actual=308 t:fy11_actual=347 t:5yr_trend=Neutral t:fy12_actual=280 t:agencies=311 t:resource_indicators=Personnel t:notes="The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report." t:fy16_plan_authorized_budget_level=405 t:fy13_actual=276 t:fy15_actual=337 t:fy15_plan_authorized_budget_level=366 m:row_number.erts-eyf6=2

series e:erts-eyf6 d:2015-11-25T07:23:55.000Z t:fy14_actual=$248 t:fy11_actual=$297 t:5yr_trend=Down t:fy12_actual=$297 t:agencies=311 t:resource_indicators="Overtime Paid ($000)" t:notes="The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report." t:fy16_plan_authorized_budget_level=$239 t:fy13_actual=$239 t:fy15_actual=$239 t:fy15_plan_authorized_budget_level=$239 m:row_number.erts-eyf6=3
```

## Meta Commands

```ls
metric m:row_number.erts-eyf6 p:long l:"Row Number"

entity e:erts-eyf6 l:"FY15 MMR Agency Resources" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/erts-eyf6

property e:erts-eyf6 t:meta.view v:id=erts-eyf6 v:category="City Government" v:averageRating=0 v:name="FY15 MMR Agency Resources" v:attribution="Mayor's Office of Operations (OPS)"

property e:erts-eyf6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:erts-eyf6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agencies | resource_indicators                                 | fy11_actual | fy12_actual | fy13_actual | fy14_actual | fy15_actual | fy15_plan_authorized_budget_level | fy16_plan_authorized_budget_level | 5yr_trend | includes_all_funds | notes                                                                                                                                                                         | 
| =========== | ======== | =================================================== | =========== | =========== | =========== | =========== | =========== | ================================= | ================================= | ========= | ================== | ============================================================================================================================================================================= | 
| 1448436235  | 311      | Expenditures ($000,000)                             | $45.0       | $42.1       | $39.6       | $38.3       | $47.5       | $46.0                             | $42.6                             | Neutral   | Y                  | The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report. | 
| 1448436235  | 311      | Personnel                                           | 347         | 280         | 276         | 308         | 337         | 366                               | 405                               | Neutral   |                    | The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report. | 
| 1448436235  | 311      | Overtime Paid ($000)                                | $297        | $297        | $239        | $248        | $239        | $239                              | $239                              | Down      |                    | The figures shown in the table above are subtotals of the Department of Information Technology and Telecommunications totals that appear in the DOITT chapter of this Report. | 
| 1448436235  | ACS      | Expenditures ($000,000)                             | $2,964.2    | $2,854.5    | $2,805.0    | $2,785.5    | $2,885.0    | $2,951.7                          | $2,948.9                          | Neutral   | Y                  |                                                                                                                                                                               | 
| 1448436235  | ACS      | Revenues ($000,000)                                 | $2.8        | 3.8         | $3.4        | $3.1        | $3.9        | $3.4                              | $3.4                              | Up        |                    |                                                                                                                                                                               | 
| 1448436235  | ACS      | Personnel                                           | 6,213       | 6,196       | 6,082       | 5,923       | 5,972       | 6,722                             | 7,302                             | Neutral   |                    |                                                                                                                                                                               | 
| 1448436235  | ACS      | Overtime Paid ($000,000)                            | $20.8       | $21.2       | $20.6       | $25.2       | $17.4       | $17.4                             | $17.4                             | Neutral   |                    |                                                                                                                                                                               | 
| 1448436235  | ACS      | Capital Commitments ($000,000)                      | $10.1       | $13.5       | $11.1       | $10.2       | $5.8        | $38.7                             | $26.9                             | Down      |                    |                                                                                                                                                                               | 
| 1448436235  | ACS      | Human Services Contract Budget ($000,000)           | $1,614.7    | $1,568.9    | $1,630.0    | $1,629.5    | $1,682.8    | $1,684.2                          | $1,693.6                          | Neutral   |                    |                                                                                                                                                                               | 
| 1448436235  | ACS      | Work Experience Program (WEP) Participants Assigned | 143         | 96          | 73          | 110         | 30          | *                                 | *                                 | Down      |                    |                                                                                                                                                                               | 
```