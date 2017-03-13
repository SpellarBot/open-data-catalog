# Operations And Maintenance Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/operations-and-maintenance-expenditures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/q3b3-ezki) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/q3b3-ezki/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/q3b3-ezki/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | q3b3-ezki |
| Name | Operations And Maintenance Expenditures |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | operations and maintenance, o&m, expenditures, energy, budget |
| Created | 2016-08-01T14:33:01Z |
| Publication Date | 2016-10-31T13:55:05Z |
| Rows Updated | 2016-10-31T13:54:49Z |

## Description

Austin Energy's operating budget includes Operations & Maintenance; fuel costs; debt service payments; and cash transfers to the Capital Improvements Project fund.   
Please note: Operations and Maintenance with Fuel does not include debt service and transfers

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| Yes      | time           | fiscal_year                    | Fiscal Year                      | number    | number      |
| Yes      | numeric metric | fuel                           | Fuel                             | money     | money       |
| Yes      | numeric metric | power_supply_market_operations | Power Supply & Market Operations | money     | money       |
| Yes      | numeric metric | electric_service_delivery      | Electric Service Delivery        | money     | money       |
| Yes      | numeric metric | distributed_energy_services    | Distributed Energy Services      | money     | money       |
| Yes      | numeric metric | customer_care                  | Customer Care                    | money     | money       |
| Yes      | numeric metric | administrative_and_general     | Administrative and General       | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q3b3-ezki d:2007-01-01T00:00:00.000Z m:electric_service_delivery=103947739 m:fuel=368759133 m:distributed_energy_services=26394706 m:administrative_and_general=78289887 m:power_supply_market_operations=129980185 m:customer_care=23690882

series e:q3b3-ezki d:2008-01-01T00:00:00.000Z m:electric_service_delivery=112627646 m:fuel=480998900 m:distributed_energy_services=28758771 m:administrative_and_general=79860010 m:power_supply_market_operations=123595487 m:customer_care=24120110

series e:q3b3-ezki d:2009-01-01T00:00:00.000Z m:electric_service_delivery=128031667 m:fuel=442789384 m:distributed_energy_services=34208249 m:administrative_and_general=93614766 m:power_supply_market_operations=124978787 m:customer_care=28670858
```

## Meta Commands

```ls
metric m:fuel p:integer l:Fuel t:dataTypeName=money

metric m:power_supply_market_operations p:double l:"Power Supply & Market Operations" t:dataTypeName=money

metric m:electric_service_delivery p:integer l:"Electric Service Delivery" t:dataTypeName=money

metric m:distributed_energy_services p:integer l:"Distributed Energy Services" t:dataTypeName=money

metric m:customer_care p:integer l:"Customer Care" t:dataTypeName=money

metric m:administrative_and_general p:integer l:"Administrative and General" t:dataTypeName=money

entity e:q3b3-ezki l:"Operations And Maintenance Expenditures" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/q3b3-ezki

property e:q3b3-ezki t:meta.view v:id=q3b3-ezki v:category=Utility v:averageRating=0 v:name="Operations And Maintenance Expenditures" v:attribution="Austin Energy"

property e:q3b3-ezki t:meta.view.license v:name="Public Domain"

property e:q3b3-ezki t:meta.view.owner v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"

property e:q3b3-ezki t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```