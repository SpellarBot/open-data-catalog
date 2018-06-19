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
| Category | Utilities and City Services |
| Tags | operations and maintenance, o&m, expenditures, energy, budget |
| Created | 2016-08-01T14:33:01Z |
| Publication Date | 2016-10-31T13:55:05Z |

## Description

Austin Energy's operating budget includes Operations & Maintenance; fuel costs; debt service payments; and cash transfers to the Capital Improvements Project fund. Please note: Operations and Maintenance with Fuel does not include debt service and transfers. Find more information at http://austinenergy.com/go/reports.

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
series e:q3b3-ezki d:2007-01-01T00:00:00.000Z m:customer_care=23690882 m:fuel=368759133 m:electric_service_delivery=103947739 m:power_supply_market_operations=129980185 m:distributed_energy_services=26394706 m:administrative_and_general=78289887

series e:q3b3-ezki d:2008-01-01T00:00:00.000Z m:customer_care=24120110 m:fuel=480998900 m:electric_service_delivery=112627646 m:power_supply_market_operations=123595487 m:distributed_energy_services=28758771 m:administrative_and_general=79860010

series e:q3b3-ezki d:2009-01-01T00:00:00.000Z m:customer_care=28670858 m:fuel=442789384 m:electric_service_delivery=128031667 m:power_supply_market_operations=124978787 m:distributed_energy_services=34208249 m:administrative_and_general=93614766
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

property e:q3b3-ezki t:meta.view d:2017-09-25T07:28:09.814Z v:averageRating=0 v:name="Operations And Maintenance Expenditures" v:attribution="Austin Energy" v:id=q3b3-ezki v:category="Utilities and City Services"

property e:q3b3-ezki t:meta.view.license d:2017-09-25T07:28:09.814Z v:name="Public Domain"

property e:q3b3-ezki t:meta.view.owner d:2017-09-25T07:28:09.814Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB

property e:q3b3-ezki t:meta.view.tableauthor d:2017-09-25T07:28:09.814Z v:displayName="Elaine Lee" v:roleName=editor v:id=3qbr-w2gj v:screenName="Elaine Lee"
```

## Top Records

```ls
| fiscal_year | fuel      | power_supply_market_operations | electric_service_delivery | distributed_energy_services | customer_care | administrative_and_general | 
| =========== | ========= | ============================== | ========================= | =========================== | ============= | ========================== | 
| 2007        | 368759133 | 129980185                      | 103947739                 | 26394706                    | 23690882      | 78289887                   | 
| 2008        | 480998900 | 123595487                      | 112627646                 | 28758771                    | 24120110      | 79860010                   | 
| 2009        | 442789384 | 124978787                      | 128031667                 | 34208249                    | 28670858      | 93614766                   | 
| 2010        | 438286450 | 135838491.72999999             | 131416061                 | 30590851                    | 25712622      | 107934153                  | 
| 2011        | 471788888 | 144230284                      | 128814600                 | 30184082                    | 31202456      | 106645672                  | 
| 2012        | 425895800 | 140538765                      | 137923078                 | 32015121                    | 26248955      | 107262926                  | 
| 2013        | 455275095 | 156755183                      | 150565104                 | 36367754                    | 43939583      | 104837164                  | 
| 2014        | 501593156 | 162976155                      | 180494394                 | 40465464                    | 49373814      | 77124154                   | 
| 2015        | 443535156 | 138317501                      | 192051588                 | 44496023                    | 43829112      | 105252630                  | 
```