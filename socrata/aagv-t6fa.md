# FY17 PMMR Agency Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy17-pmmr-agency-resources) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/aagv-t6fa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/aagv-t6fa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/aagv-t6fa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | aagv-t6fa |
| Name | FY17 PMMR Agency Resources |
| Attribution | Mayor?s Office of Operations (OPS) |
| Category | City Government |
| Tags | agency resource indicators, expenditures, personnel, overtime, overtime paid, capital commitments, actual, human services, human services contract budget, work experience program, wep, fy16 plan, ... |
| Created | 2017-02-06T22:44:37Z |
| Publication Date | 2017-02-06T22:52:41Z |

## Description

NYC agency resources from the FY17 Preliminary Mayor's Management Report (PMMR), including expenditures (includes all funds), personnel, revenue and paid overtime

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                            | Data Type | Render Type |
| ======== | ============== | ============================================== | =============================================== | ========= | =========== |
| No       | time           | :updated_at                                    | updated_at                                      | meta_data | meta_data   |
| Yes      | series tag     | agency                                         | Agency                                          | text      | text        |
| Yes      | series tag     | resource_indicators                            | Resource Indicators                             | text      | text        |
| Yes      | series tag     | fy14_actual                                    | FY14 Actual                                     | text      | text        |
| Yes      | series tag     | fy15_actual                                    | FY15 Actual                                     | text      | text        |
| Yes      | numeric metric | fy16_actual                                    | FY16 Actual                                     | money     | text        |
| Yes      | numeric metric | fy17_sept_2016_mmr_plan                        | FY17 (Sept. 2016 MMR Plan)                      | money     | text        |
| Yes      | numeric metric | fy17_updated_plan_from_jan_2017_financial_plan | FY17 Updated Plan from Jan. 2017 Financial Plan | money     | text        |
| Yes      | numeric metric | fy18_plan_from_jan_2017_financial_plan         | FY18 Plan from Jan. 2017 Financial Plan         | money     | text        |
| Yes      | series tag     | fy16_4_month_actual                            | FY16 4-Month Actual                             | text      | text        |
| Yes      | series tag     | fy17_4_month_actual                            | FY17 4-Month Actual                             | text      | text        |
| Yes      | series tag     | includes_all_funds                             | Includes all Funds                              | text      | text        |
| Yes      | series tag     | notes                                          | Notes                                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:aagv-t6fa d:2017-02-06T22:44:40.000Z t:fy16_4_month_actual=$21.2 t:includes_all_funds=Y t:fy14_actual=$38.3 t:agency=311 t:fy17_4_month_actual=$20.4 t:resource_indicators="Expenditures ($000,000)" t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." t:fy15_actual=$44.1 m:fy18_plan_from_jan_2017_financial_plan=46.3 m:fy16_actual=43.8 m:fy17_sept_2016_mmr_plan=42.2 m:fy17_updated_plan_from_jan_2017_financial_plan=42

series e:aagv-t6fa d:2017-02-06T22:44:40.000Z t:fy16_4_month_actual=342 t:fy14_actual=308 t:agency=311 t:fy17_4_month_actual=355 t:resource_indicators=Personnel t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." t:fy15_actual=337 m:fy18_plan_from_jan_2017_financial_plan=405 m:fy16_actual=358 m:fy17_sept_2016_mmr_plan=405 m:fy17_updated_plan_from_jan_2017_financial_plan=405

series e:aagv-t6fa d:2017-02-06T22:44:40.000Z t:fy16_4_month_actual=$68 t:fy14_actual=$248 t:agency=311 t:fy17_4_month_actual=$69 t:resource_indicators="Overtime paid ($000)" t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." t:fy15_actual=$224 m:fy18_plan_from_jan_2017_financial_plan=239 m:fy16_actual=176 m:fy17_sept_2016_mmr_plan=239 m:fy17_updated_plan_from_jan_2017_financial_plan=239
```

## Meta Commands

```ls
metric m:fy16_actual p:long l:"FY16 Actual" d:"The fiscal year actual for 2016 (July 2015 through June 2016)" t:dataTypeName=money

entity e:aagv-t6fa l:"FY17 PMMR Agency Resources" t:attribution="Mayor?s Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/aagv-t6fa

property e:aagv-t6fa t:meta.view v:id=aagv-t6fa v:category="City Government" v:averageRating=0 v:name="FY17 PMMR Agency Resources" v:attribution="Mayor?s Office of Operations (OPS)"

property e:aagv-t6fa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:aagv-t6fa t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | resource_indicators                       | fy14_actual | fy15_actual | fy16_actual | fy17_sept_2016_mmr_plan | fy17_updated_plan_from_jan_2017_financial_plan | fy18_plan_from_jan_2017_financial_plan | fy16_4_month_actual | fy17_4_month_actual | includes_all_funds | notes                                                                                        | 
| =========== | ====== | ========================================= | =========== | =========== | =========== | ======================= | ============================================== | ====================================== | =================== | =================== | ================== | ============================================================================================ | 
| 1486421080  | 311    | Expenditures ($000,000)                   | $38.3       | $44.1       | $43.8       | $42.2                   | $42.0                                          | $46.3                                  | $21.2               | $20.4               | Y                  | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1486421080  | 311    | Personnel                                 | 308         | 337         | 358         | 405                     | 405                                            | 405                                    | 342                 | 355                 |                    | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1486421080  | 311    | Overtime paid ($000)                      | $248        | $224        | $176        | $239                    | $239                                           | $239                                   | $68                 | $69                 |                    | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1486421080  | ACS    | Expenditures ($000,000)                   | $2,785.5    | $2,826.7    | $2,875.1    | $2,977.9                | $3,030.9                                       | $3,033.6                               | $1,504.9            | $1,625.5            | Y                  |                                                                                              | 
| 1486421080  | ACS    | Revenues ($000,000)                       | $3.1        | $3.9        | $7.2        | $3.4                    | $3.4                                           | $3.4                                   | $0.9                | $1.4                |                    |                                                                                              | 
| 1486421080  | ACS    | Personnel                                 | 5,923       | 5,972       | 6,000       | 7,181                   | 7,178                                          | 7,174                                  | 5,882               | 6,208               |                    |                                                                                              | 
| 1486421080  | ACS    | Overtime paid ($000,000)                  | $25.2       | 30,1        | $33.9       | $17.5                   | $17.5                                          | $17.5                                  | 9,4                 | $10.7               |                    |                                                                                              | 
| 1486421080  | ACS    | Capital commitments ($000,000)            | $10.2       | $5.8        | $10.2       | $101.6                  | $120.3                                         | $102.8                                 | $2.7                | $6.5                |                    |                                                                                              | 
| 1486421080  | ACS    | Human services contract budget ($000,000) | $1,629.5    | $1,647.8    | $1,710.3    | $1,746.3                | $1,780.9                                       | $1,774.4                               | $554.4              | $565.2              |                    |                                                                                              | 
| 1486421080  | BIC    | Expenditures ($000,000)                   | $7.3        | $8.1        | $8.1        | $9.1                    | $10.3                                          | $8.5                                   | $3.8                | $4.2                | Y                  |                                                                                              | 
```