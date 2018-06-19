# ResultsNOLA (2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/resultsnola-2015) |
| Metadata | [Link](https://data.nola.gov/api/views/yh4i-gtfv) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/yh4i-gtfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/yh4i-gtfv/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | yh4i-gtfv |
| Name | ResultsNOLA (2015) |
| Tags | resultsnola |
| Created | 2017-01-04T22:28:12Z |
| Publication Date | 2017-01-04T22:32:10Z |

## Description

This data includes all of the key performance indicators for the ResultsNOLA (the City's performance management report) from 2015.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | indicatorid        | IndicatorID        | text          | number        |
| Yes      | series tag     | strategyid         | StrategyID         | text          | text          |
| Yes      | series tag     | organization       | Organization       | text          | text          |
| Yes      | series tag     | name               | Name               | text          | text          |
| Yes      | series tag     | type               | Type               | text          | text          |
| Yes      | series tag     | target             | Target             | text          | text          |
| Yes      | series tag     | seasonality        | Seasonality        | text          | text          |
| Yes      | series tag     | direction          | Direction          | text          | text          |
| Yes      | numeric metric | value              | value              | number        | number        |
| Yes      | series tag     | rowid              | RowID              | text          | text          |
| Yes      | time           | date               | Date               | calendar_date | calendar_date |
| No       |                | year               | Year               | number        | number        |
| No       |                | quarter            | Quarter            | number        | number        |
| No       |                | datelabel          | DateLabel          | text          | text          |
| Yes      | series tag     | total              | Total              | text          | text          |
| Yes      | numeric metric | percent            | Percent            | percent       | percent       |
| Yes      | numeric metric | ytd                | YTD                | number        | number        |
| Yes      | series tag     | action_aggregation | Action_Aggregation | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter,datelabel,year
```

## Data Commands

```ls
series e:yh4i-gtfv d:2015-03-31T00:00:00.000Z t:total=0.92 t:strategyid=20103 t:organization=Budget t:indicatorid=101 t:action_aggregation="Maintain Below" t:direction=Under t:name="Avg. days to approve requisitions for the purchase of goods or services" t:target=1 t:seasonality="Not Seasonal" t:type=Average t:rowid="Avg. days to approve requisitions for the purchase of goods or services_2015-03-31" m:ytd=0.92 m:value=0.92

series e:yh4i-gtfv d:2015-03-31T00:00:00.000Z t:total=NA t:strategyid=40103 t:organization="Capital Projects" t:indicatorid=201 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of projects delivered on schedule" t:target=80% t:seasonality="Not Seasonal" t:type="Average Percent" t:rowid="Percent of projects delivered on schedule_2015-03-31" m:percent=85 m:ytd=0.85 m:value=85

series e:yh4i-gtfv d:2015-03-31T00:00:00.000Z t:total=NA t:strategyid=20103 t:organization="Capital Projects" t:indicatorid=202 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of invoices paid within 30 days for bonds, 45 days for revolver funds, and 60 days for DCDBG funds" t:target=80% t:seasonality="Not Seasonal" t:type="Average Percent" t:rowid="Percent of invoices paid within 30 days for bonds, 45 days for revolver funds, and 60 days for DCDBG funds_2015-03-31" m:percent=73 m:ytd=0.73 m:value=73
```

## Meta Commands

```ls
metric m:value p:double l:value t:dataTypeName=number

metric m:percent p:double l:Percent t:dataTypeName=percent

metric m:ytd p:double l:YTD t:dataTypeName=number

entity e:yh4i-gtfv l:"ResultsNOLA (2015)" t:url=https://data.nola.gov/api/views/yh4i-gtfv

property e:yh4i-gtfv t:meta.view v:id=yh4i-gtfv v:averageRating=0 v:name="ResultsNOLA (2015)"

property e:yh4i-gtfv t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:yh4i-gtfv t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:yh4i-gtfv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=maschigoda@nola.gov
```

## Top Records

```ls
| indicatorid | strategyid | organization              | name                                                                                                             | type            | target | seasonality  | direction | value | rowid                                                                                                                       | date                | year | quarter | datelabel | total | percent | ytd   | action_aggregation | 
| =========== | ========== | ========================= | ================================================================================================================ | =============== | ====== | ============ | ========= | ===== | =========================================================================================================================== | =================== | ==== | ======= | ========= | ===== | ======= | ===== | ================== | 
| 101         | 20103      | Budget                    | Avg. days to approve requisitions for the purchase of goods or services                                          | Average         | 1      | Not Seasonal | Under     | 0.92  | Avg. days to approve requisitions for the purchase of goods or services_2015-03-31                                          | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | 0.92  |         | 0.92  | Maintain Below     | 
| 201         | 40103      | Capital Projects          | Percent of projects delivered on schedule                                                                        | Average Percent | 80%    | Not Seasonal | Over      | 85    | Percent of projects delivered on schedule_2015-03-31                                                                        | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | NA    | 85      | 0.85  | Maintain Above     | 
| 202         | 20103      | Capital Projects          | Percent of invoices paid within 30 days for bonds, 45 days for revolver funds, and 60 days for DCDBG funds       | Average Percent | 80%    | Not Seasonal | Over      | 73    | Percent of invoices paid within 30 days for bonds, 45 days for revolver funds, and 60 days for DCDBG funds_2015-03-31       | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | NA    | 73      | 0.73  | Maintain Above     | 
| 301         | 40205      | City Planning Commission  | Avg. days to docket a Board of Zoning Adjustment variance application for public hearing                         | Average         | 10     | Not Seasonal | Under     | 9.25  | Avg. days to docket a Board of Zoning Adjustment variance application for public hearing_2015-03-31                         | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | 9.25  |         | 9.25  | Maintain Below     | 
| 302         | 40205      | City Planning Commission  | Avg. days to docket a completed subdivision application                                                          | Average         | 13     | Not Seasonal | Under     | 22    | Avg. days to docket a completed subdivision application_2015-03-31                                                          | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | 22    |         | 22    | Maintain Below     | 
| 303         | 40205      | City Planning Commission  | Avg. days to schedule a completed zoning docket application for a public hearing before the CPC                  | Average         | 6      | Not Seasonal | Under     | 15.58 | Avg. days to schedule a completed zoning docket application for a public hearing before the CPC_2015-03-31                  | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | 15.58 |         | 15.58 | Maintain Below     | 
| 401         | 20203      | Civil Service             | Percent of internal customers who agree that training was useful to their position                               | Average Percent | 95%    | Not Seasonal | Over      | 96    | Percent of internal customers who agree that training was useful to their position_2015-03-31                               | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | NA    | 96      | 0.96  | Maintain Above     | 
| 402         | 20201      | Civil Service             | Percent of eligible lists established within 60 days of the job announcement closing                             | Average Percent | 80%    | Not Seasonal | Over      | 94    | Percent of eligible lists established within 60 days of the job announcement closing_2015-03-31                             | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | NA    | 94      | 0.94  | Maintain Above     | 
| 404         | 20201      | Civil Service             | Percent of employees selected from eligible lists who satisfactorily complete their initial probationary periods | Average Percent | 90%    | Not Seasonal | Over      | 84    | Percent of employees selected from eligible lists who satisfactorily complete their initial probationary periods_2015-03-31 | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | NA    | 84      | 0.84  | Maintain Above     | 
| 501         | 40302      | Coastal and Environmental | Number of participants in coastal sustainability and other resilience focused events                             | Count           | 200    | Not Seasonal | Over      | 102   | Number of participants in coastal sustainability and other resilience focused events_2015-03-31                             | 2015-03-31T00:00:00 | 2015 | 1       | 2015, Q1  | 102   |         | 102   | Increase to        | 
```