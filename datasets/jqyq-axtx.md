# ResultsNOLA (historic)

## Dataset

* [Dataset URL](https://data.nola.gov/api/views/jqyq-axtx/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/resultsnola)
* [Metadata URL](https://data.nola.gov/api/views/jqyq-axtx)
* Id = jqyq-axtx
* Name = ResultsNOLA (historic)
* Attribution = City of New Orleans
* Category = City Administration
* Tags = [resultsnola]
* Created = 2015-11-10T14:28:12Z
* Publication Date = 2016-09-13T14:20:34Z
* Rows Updated = 2016-09-13T14:17:18Z

## Description

This data includes all of the key performance indicators for ResultsNOLA, the City's performance management report. It is connected to the graphs showing data for past years on the goal pages on results.nola.gov.

## Columns

```ls
| Name               | Field Name         | Data Type     | Render Type   | Schema Type    | Included | 
| ================== | ================== | ============= | ============= | ============== | ======== | 
| IndicatorID        | indicatorid        | text          | number        | series tag     | Yes      | 
| StrategyID         | strategyid         | text          | number        | series tag     | Yes      | 
| Organization       | organization       | text          | text          | series tag     | Yes      | 
| Name               | name               | text          | text          | series tag     | Yes      | 
| Type               | type               | text          | text          | series tag     | Yes      | 
| Target             | target             | text          | text          | series tag     | Yes      | 
| Seasonality        | seasonality        | text          | text          | series tag     | Yes      | 
| Direction          | direction          | text          | text          | series tag     | Yes      | 
| value              | value              | number        | number        | numeric metric | Yes      | 
| RowID              | rowid              | text          | text          | series tag     | Yes      | 
| Date               | date               | calendar_date | calendar_date | time           | Yes      | 
| Year               | year               | number        | number        |                | No       | 
| Quarter            | quarter            | number        | number        | numeric metric | Yes      | 
| DateLabel          | datelabel          | text          | text          | series tag     | Yes      | 
| Total              | total              | number        | number        | numeric metric | Yes      | 
| Percent            | percent            | number        | number        | numeric metric | Yes      | 
| YTD                | ytd                | number        | number        | numeric metric | Yes      | 
| Quarter_Label      | quarter_label      | text          | text          |                | No       | 
| Action_Aggregation | action_aggregation | text          | text          | series tag     | Yes      | 
| Note               | note               | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = quarter_label,year
Annotation Fields = 
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

property e:jqyq-axtx t:meta.view d:2017-03-08T00:15:31.886Z v:id=jqyq-axtx v:category="City Administration" v:averageRating=0 v:name="ResultsNOLA (historic)" v:attribution="City of New Orleans"

property e:jqyq-axtx t:meta.view.owner d:2017-03-08T00:15:31.886Z v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.tableauthor d:2017-03-08T00:15:31.886Z v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:jqyq-axtx t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:15:31.886Z v:Contact_Email=data@nola.gov
```