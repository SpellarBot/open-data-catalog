# FY16 PMMR Agency Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy16-pmmr-agency-resources) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7ceq-6nwu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7ceq-6nwu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7ceq-6nwu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7ceq-6nwu |
| Name | FY16 PMMR Agency Resources |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | City Government |
| Tags | pmmr, mmr, indicators, metrics, performance, ops, 2016, management, report, fy16, operations |
| Created | 2016-02-05T22:41:17Z |
| Publication Date | 2016-02-05T22:43:34Z |

## Description

NYC agency resources from the FY16 Preliminary Mayor's Management Report (PMMR), including expenditures (includes all funds), personnel, revenue and paid overtime

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                            | Data Type | Render Type |
| ======== | ============== | ============================================== | =============================================== | ========= | =========== |
| No       | time           | :updated_at                                    | updated_at                                      | meta_data | meta_data   |
| Yes      | series tag     | agency                                         | Agency                                          | text      | text        |
| Yes      | series tag     | resource_indicators                            | Resource Indicators                             | text      | text        |
| Yes      | numeric metric | fy13_actual                                    | FY13 Actual                                     | money     | text        |
| Yes      | numeric metric | fy14_actual                                    | FY14 Actual                                     | money     | text        |
| Yes      | numeric metric | fy15_actual                                    | FY15 Actual                                     | money     | text        |
| Yes      | numeric metric | fy16_sept_2015_mmr_plan                        | FY16 (Sept. 2015 MMR Plan)                      | money     | text        |
| Yes      | numeric metric | fy16_updated_plan_from_jan_2016_financial_plan | FY16 Updated Plan from Jan. 2016 Financial Plan | money     | text        |
| Yes      | numeric metric | fy17_plan_from_jan_2016_financial_plan         | FY17 Plan from Jan. 2016 Financial Plan         | money     | text        |
| Yes      | series tag     | fy15_4_month_actual                            | FY15 4-Month Actual                             | text      | text        |
| Yes      | series tag     | fy16_4_month_actual                            | FY16 4-Month Actual                             | text      | text        |
| Yes      | series tag     | notes                                          | Notes                                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7ceq-6nwu d:2016-02-05T14:41:21.000Z t:fy16_4_month_actual=$21.2 t:fy15_4_month_actual=$17.6 t:agency=311 t:resource_indicators="Expenditures ($000,000)" t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." m:fy14_actual=38.3 m:fy16_sept_2015_mmr_plan=42.6 m:fy17_plan_from_jan_2016_financial_plan=41.9 m:fy16_updated_plan_from_jan_2016_financial_plan=41.9 m:fy13_actual=39.6 m:fy15_actual=44.1

series e:7ceq-6nwu d:2016-02-05T14:41:21.000Z t:fy16_4_month_actual=342 t:fy15_4_month_actual=303 t:agency=311 t:resource_indicators=Personnel t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." m:fy14_actual=308 m:fy16_sept_2015_mmr_plan=405 m:fy17_plan_from_jan_2016_financial_plan=405 m:fy16_updated_plan_from_jan_2016_financial_plan=405 m:fy13_actual=276 m:fy15_actual=337

series e:7ceq-6nwu d:2016-02-05T14:41:21.000Z t:fy16_4_month_actual=$68 t:fy15_4_month_actual=$45 t:agency=311 t:resource_indicators="Overtime paid ($000)" t:notes="This is a subtotal of the Department of Information Technology and Telecommunications total." m:fy14_actual=248 m:fy16_sept_2015_mmr_plan=239 m:fy17_plan_from_jan_2016_financial_plan=239 m:fy16_updated_plan_from_jan_2016_financial_plan=239 m:fy13_actual=239 m:fy15_actual=224
```

## Meta Commands

```ls
metric m:fy13_actual p:integer l:"FY13 Actual" t:dataTypeName=money

metric m:fy14_actual p:long l:"FY14 Actual" t:dataTypeName=money

metric m:fy15_actual p:long l:"FY15 Actual" t:dataTypeName=money

entity e:7ceq-6nwu l:"FY16 PMMR Agency Resources" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/7ceq-6nwu

property e:7ceq-6nwu t:meta.view v:id=7ceq-6nwu v:category="City Government" v:averageRating=0 v:name="FY16 PMMR Agency Resources" v:attribution="Mayor's Office of Operations (OPS)"

property e:7ceq-6nwu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7ceq-6nwu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | resource_indicators                                 | fy13_actual | fy14_actual | fy15_actual | fy16_sept_2015_mmr_plan | fy16_updated_plan_from_jan_2016_financial_plan | fy17_plan_from_jan_2016_financial_plan | fy15_4_month_actual | fy16_4_month_actual | notes                                                                                        | 
| =========== | ====== | =================================================== | =========== | =========== | =========== | ======================= | ============================================== | ====================================== | =================== | =================== | ============================================================================================ | 
| 1454683281  | 311    | Expenditures ($000,000)                             | $39.6       | $38.3       | $44.1       | $42.6                   | $41.9                                          | $41.9                                  | $17.6               | $21.2               | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1454683281  | 311    | Personnel                                           | 276         | 308         | 337         | 405                     | 405                                            | 405                                    | 303                 | 342                 | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1454683281  | 311    | Overtime paid ($000)                                | $239        | $248        | $224        | $239                    | $239                                           | $239                                   | $45                 | $68                 | This is a subtotal of the Department of Information Technology and Telecommunications total. | 
| 1454683281  | ACS    | Expenditures ($000,000)                             | $2,805.0    | $2,785.5    | $2,826.7    | $2,948.9                | $2,996.3                                       | $2,968.8                               | $1,537.1            | $1,504.9            |                                                                                              | 
| 1454683281  | ACS    | Revenues ($000,000)                                 | $3.4        | $3.1        | $3.9        | $3.4                    | $3.4                                           | $3.4                                   | $0.8                | $0.9                |                                                                                              | 
| 1454683281  | ACS    | Personnel                                           | 6,082       | 5,923       | 5,972       | 7,302                   | 7,293                                          | 7,355                                  | 5,925               | 5,882               |                                                                                              | 
| 1454683281  | ACS    | Overtime paid ($000,000)                            | $20.6       | $25.2       | $30.1       | $17.4                   | $17.4                                          | $17.5                                  | $7.4                | $9.4                |                                                                                              | 
| 1454683281  | ACS    | Capital commitments ($000,000)                      | $11.1       | $10.2       | $5.8        | $26.9                   | $37.7                                          | $40.8                                  | $3.3                | $2.7                |                                                                                              | 
| 1454683281  | ACS    | Human services contract budget ($000,000)           | $1,630.0    | $1,629.5    | $1,647.8    | $1,693.6                | $1,729.6                                       | $1,708.2                               | $564.0              | $554.4              |                                                                                              | 
| 1454683281  | ACS    | Work Experience Program (WEP) participants assigned | 73          | 110         | 30          | *                       | *                                              | *                                      | 68                  | 64                  |                                                                                              | 
```