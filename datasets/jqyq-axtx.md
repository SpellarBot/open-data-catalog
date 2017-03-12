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
| Rows Updated | 2016-09-13T14:17:18Z |

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
| Yes      | numeric metric | quarter            | Quarter            | number        | number        |
| Yes      | series tag     | datelabel          | DateLabel          | text          | text          |
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
Excluded Fields = quarter_label,year
```

## Data Commands

```ls
series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=20103 t:organization=Budget t:indicatorid=101 t:action_aggregation="Maintain Below" t:direction=Under t:name="Avg. days to approve requisitions for the purchase of goods or services" t:target=1 t:seasonality="Not Seasonal" t:datelabel="2016, Q1" t:type=Average t:rowid="Avg. days to approve requisitions for the purchase of goods or services_2016-03-31" t:note="6,973 requisitions approved in 2016." m:total=0.63 m:ytd=0.63498 m:value=0.63 m:quarter=1

series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=40103 t:organization="Capital Projects" t:indicatorid=201 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of projects delivered on schedule" t:target=80% t:seasonality="Not Seasonal" t:datelabel="2016, Q1" t:type="Average Percent" t:rowid="Percent of projects delivered on schedule_2016-03-31" t:note="111 of 140 project milestones delivered on schedule in 2016." m:percent=82.4 m:value=82.4 m:quarter=1

series e:jqyq-axtx d:2016-03-31T00:00:00.000Z t:strategyid=20103 t:organization="Capital Projects" t:indicatorid=203 t:action_aggregation="Maintain Above" t:direction=Over t:name="Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds" t:target=80% t:seasonality="Not Seasonal" t:datelabel="2016, Q1" t:type="Average Percent" t:rowid="Percent of invoices paid within 30 days for bonds, 60 days for revolver funds, and 60 days for DCDBG funds_2016-03-31" t:note="387 of 451 invoices paid within respective time periods in 2016." m:percent=82.1 m:value=82.1 m:quarter=1
```

## Meta Commands

```ls
metric m:value p:integer l:value t:dataTypeName=number

metric m:quarter p:integer l:Quarter t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

metric m:percent p:integer l:Percent t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:jqyq-axtx l:"ResultsNOLA (historic)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/jqyq-axtx

property e:jqyq-axtx t:meta.view v:id=jqyq-axtx v:category="City Administration" v:averageRating=0 v:name="ResultsNOLA (historic)" v:attribution="City of New Orleans"

property e:jqyq-axtx t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```