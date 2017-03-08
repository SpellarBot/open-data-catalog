# System Production Cost

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/d683-uqui/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/system-production-cost)
* [Metadata URL](https://data.austintexas.gov/api/views/d683-uqui)
* Id = d683-uqui
* Name = System Production Cost
* Attribution = Austin Energy
* Category = Utility
* Tags = [system production cost, average system production cost, energy production, cost, energy]
* Created = 2016-09-09T20:45:18Z
* Publication Date = 2016-09-30T19:21:51Z
* Rows Updated = 2016-09-30T19:21:07Z

## Description

The average system production cost is total operations and maintenance costs divided by total generation in kilowatt hours. View average annual system production cost data starting in 2006. Austin Energy's system annual average production cost is total operations and maintenance costs divided by total generation in kilowatt hours. 

System annual average production cost includes fuel plus operating and maintenance.

## Columns

```ls
| Name                                                  | Field Name                                          | Data Type     | Render Type   | Schema Type    | Included | 
| ===================================================== | =================================================== | ============= | ============= | ============== | ======== | 
| Fiscal Year                                           | fiscal_year_2                                       | calendar_date | calendar_date | time           | Yes      | 
| System annual average production cost (cents per kWh) | system_annual_average_production_cost_cents_per_kwh | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:d683-uqui d:2006-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=3.93

series e:d683-uqui d:2007-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=3.831

series e:d683-uqui d:2008-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=4.403
```

## Meta Commands

```ls
metric m:system_annual_average_production_cost_cents_per_kwh l:"System annual average production cost (cents per kWh)" t:dataTypeName=number

entity e:d683-uqui l:"System Production Cost" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/d683-uqui

property e:d683-uqui t:meta.view d:2017-03-07T19:18:31.723Z v:id=d683-uqui v:category=Utility v:averageRating=0 v:name="System Production Cost" v:attribution="Austin Energy"

property e:d683-uqui t:meta.view.license d:2017-03-07T19:18:31.723Z v:name="Public Domain"

property e:d683-uqui t:meta.view.owner d:2017-03-07T19:18:31.723Z v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"

property e:d683-uqui t:meta.view.tableauthor d:2017-03-07T19:18:31.723Z v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```