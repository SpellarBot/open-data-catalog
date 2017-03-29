# ResultsNOLA (historic)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/resultsnola) |
| Metadata | [Link](https://data.nola.gov/api/views/jqyq-axtx) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/jqyq-axtx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/jqyq-axtx/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | jqyq-axtx |
| Name | ResultsNOLA (historic) |
| Attribution | City of New Orleans |
| Category | City Administration |
| Tags | resultsnola |
| Created | 2015-11-10T14:28:12Z |
| Publication Date | 2016-09-13T14:20:34Z |

## Description

This data includes all of the key performance indicators for ResultsNOLA, the City's performance management report. It is connected to the graphs showing data for past years on the goal pages on results.nola.gov.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | indicatorid        | IndicatorID        | text          | number        |
| Yes      | series tag     | strategyid         | StrategyID         | text          | number        |
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
| Yes      | numeric metric | total              | Total              | number        | number        |
| Yes      | numeric metric | percent            | Percent            | number        | number        |
| Yes      | numeric metric | ytd                | YTD                | number        | number        |
| No       |                | quarter_label      | Quarter_Label      | text          | text          |
| Yes      | series tag     | action_aggregation | Action_Aggregation | text          | text          |
| Yes      | series tag     | note               | Note               | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter,datelabel,quarter_label,year
```

## Data Commands

```ls
series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=20103 t:organization=Budget t:indicatorid=101 t:action_aggregation="Maintain Below" t:direction=Under t:name="Avg. days to approve requisitions for the purchase of goods or services" t:target=1 t:seasonality="Not Seasonal" t:type=Average t:rowid="Avg. days to approve requisitions for the purchase of goods or services_2016-03-31" t:note="6,973 requisitions approved in 2016." m:total=0.63 m:ytd=0.634975982 m:value=0.63

series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=40103 t:organization="Capital Projects" t:indicatorid=201 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of projects delivered on schedule" t:target=80% t:seasonality="Not Seasonal" t:type="Average Percent" t:rowid="Percent of projects delivered on schedule_2016-03-31" t:note="111 of 140 project milestones delivered on schedule in 2016." m:percent=82.4 m:value=82.4

series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=20103 t:organization="Capital Projects" t:indicatorid=203 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds" t:target=80% t:seasonality="Not Seasonal" t:type="Average Percent" t:rowid="Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds_2016-03-31" t:note="387 of 451 invoices paid within respective time periods in 2016." m:percent=82.1 m:value=82.1
```

## Meta Commands

```ls
metric m:value p:double l:value t:dataTypeName=number

metric m:total p:double l:Total t:dataTypeName=number

metric m:percent p:integer l:Percent t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:jqyq-axtx l:"ResultsNOLA (historic)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/jqyq-axtx

property e:jqyq-axtx t:meta.view v:id=jqyq-axtx v:category="City Administration" v:averageRating=0 v:name="ResultsNOLA (historic)" v:attribution="City of New Orleans"

property e:jqyq-axtx t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| indicatorid | strategyid | organization     | name                                                                                                             | type            | target | seasonality  | direction | value | rowid                                                                                                                       | date                | year | quarter | datelabel | total | percent | ytd         | quarter_label | action_aggregation | note                                                                                | 
| =========== | ========== | ================ | ================================================================================================================ | =============== | ====== | ============ | ========= | ===== | =========================================================================================================================== | =================== | ==== | ======= | ========= | ===== | ======= | =========== | ============= | ================== | =================================================================================== | 
| 101         | 20103      | Budget           | Avg. days to approve requisitions for the purchase of goods or services                                          | Average         | 1      | Not Seasonal | Under     | 0.63  | Avg. days to approve requisitions for the purchase of goods or services_2016-03-31                                          | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  | 0.63  |         | 0.634975982 | Q1            | Maintain Below     | 6,973 requisitions approved in 2016.                                                | 
| 201         | 40103      | Capital Projects | Percent of projects delivered on schedule                                                                        | Average Percent | 80%    | Not Seasonal | Over      | 82.4  | Percent of projects delivered on schedule_2016-03-31                                                                        | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 82.4    |             | Q1            | Maintain Above     | 111 of 140 project milestones delivered on schedule in 2016.                        | 
| 203         | 20103      | Capital Projects | Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds       | Average Percent | 80%    | Not Seasonal | Over      | 82.1  | Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds_2016-03-31       | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 82.1    |             | Q1            | Maintain Above     | 387 of 451 invoices paid within respective time periods in 2016.                    | 
| 401         | 20203      | Civil Service    | Percent of internal customers who agree that training was useful to their position                               | Average Percent | 95%    | Not Seasonal | Over      | 92    | Percent of internal customers who agree that training was useful to their position_2016-03-31                               | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 92      | 92.30769231 | Q1            | Maintain Above     | 527 of 568 internal customers agreed training was useful to their position in 2016. | 
| 402         | 20201      | Civil Service    | Percent of eligible lists established within 60 days of the job announcement closing                             | Average Percent | 90%    | Not Seasonal | Over      | 96    | Percent of eligible lists established within 60 days of the job announcement closing_2016-03-31                             | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 96      | 95.65217391 | Q1            | Maintain Above     | NA                                                                                  | 
| 404         | 20201      | Civil Service    | Percent of employees selected from eligible lists who satisfactorily complete their initial probationary periods | Average Percent | 90%    | Not Seasonal | Over      | 87    | Percent of employees selected from eligible lists who satisfactorily complete their initial probationary periods_2016-03-31 | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 87      | 87.36842105 | Q1            | Maintain Above     | 145 of 167 employees completed probationary periods in 2016.                        | 
| 602         | 40201      | Code Enforcement | Number of inspections                                                                                            | Count           | 15,000 | Not Seasonal | Over      | 2264  | Number of inspections_2016-03-31                                                                                            | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  | 2264  |         | 2264        | Q1            | Increase to        | NA                                                                                  | 
| 607         | 40201      | Code Enforcement | Number of blighted properties brought into compliance at hearing by property owners                              | Count           | 750    | Not Seasonal | Over      | 174   | Number of blighted properties brought into compliance at hearing by property owners_2016-03-31                              | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  | 174   |         | 210         | Q1            | Increase to        | NA                                                                                  | 
| 603         | 40201      | Code Enforcement | Number of properties brought to initial hearing                                                                  | Count           | 2,500  | Not Seasonal | Over      | 571   | Number of properties brought to initial hearing_2016-03-31                                                                  | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  | 571   |         | 573         | Q1            | Increase to        | NA                                                                                  | 
| 605         | 40201      | Code Enforcement | Percent of hearings reset due to failure to re-inspect the property                                              | Average Percent | 3%     | Not Seasonal | Under     | 3.2   | Percent of hearings reset due to failure to re-inspect the property_2016-03-31                                              | 2016-03-31T00:00:00 | 2016 | 1       | 2016, Q1  |       | 3.2     | 1.745200698 | Q1            | Maintain Below     |                                                                                     | 
```