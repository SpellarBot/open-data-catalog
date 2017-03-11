# Operations And Maintenance Expenditures

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/q3b3-ezki/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/operations-and-maintenance-expenditures)
* [Metadata URL](https://data.austintexas.gov/api/views/q3b3-ezki)
* Id = q3b3-ezki
* Name = Operations And Maintenance Expenditures
* Attribution = Austin Energy
* Category = Utility
* Tags = [operations and maintenance, o&m, expenditures, energy, budget]
* Created = 2016-08-01T14:33:01Z
* Publication Date = 2016-10-31T13:55:05Z
* Rows Updated = 2016-10-31T13:54:49Z

## Description

Austin Energy's operating budget includes Operations & Maintenance; fuel costs; debt service payments; and cash transfers to the Capital Improvements Project fund.   
Please note: Operations and Maintenance with Fuel does not include debt service and transfers

## Columns

```ls
| Name                             | Field Name                     | Data Type | Render Type | Schema Type    | Included | 
| ================================ | ============================== | ========= | =========== | ============== | ======== | 
| Fiscal Year                      | fiscal_year                    | number    | number      | time           | Yes      | 
| Fuel                             | fuel                           | money     | money       | numeric metric | Yes      | 
| Power Supply & Market Operations | power_supply_market_operations | money     | money       | numeric metric | Yes      | 
| Electric Service Delivery        | electric_service_delivery      | money     | money       | numeric metric | Yes      | 
| Distributed Energy Services      | distributed_energy_services    | money     | money       | numeric metric | Yes      | 
| Customer Care                    | customer_care                  | money     | money       | numeric metric | Yes      | 
| Administrative and General       | administrative_and_general     | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
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
series e:q3b3-ezki d:2007-01-01T00:00:00.000Z m:electric_service_delivery=103947739 m:fuel=368759133 m:distributed_energy_services=26394706 m:administrative_and_general=78289887 m:power_supply_market_operations=129980185 m:customer_care=23690882

series e:q3b3-ezki d:2008-01-01T00:00:00.000Z m:electric_service_delivery=112627646 m:fuel=480998900 m:distributed_energy_services=28758771 m:administrative_and_general=79860010 m:power_supply_market_operations=123595487 m:customer_care=24120110

series e:q3b3-ezki d:2009-01-01T00:00:00.000Z m:electric_service_delivery=128031667 m:fuel=442789384 m:distributed_energy_services=34208249 m:administrative_and_general=93614766 m:power_supply_market_operations=124978787 m:customer_care=28670858
```

## Meta Commands

```ls
entity e:q3b3-ezki l:"Operations And Maintenance Expenditures" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/q3b3-ezki

property e:q3b3-ezki t:meta.view d:2017-03-07T22:56:48.454Z v:id=q3b3-ezki v:category=Utility v:averageRating=0 v:name="Operations And Maintenance Expenditures" v:attribution="Austin Energy"

property e:q3b3-ezki t:meta.view.license d:2017-03-07T22:56:48.454Z v:name="Public Domain"

property e:q3b3-ezki t:meta.view.owner d:2017-03-07T22:56:48.454Z v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"

property e:q3b3-ezki t:meta.view.tableauthor d:2017-03-07T22:56:48.454Z v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```