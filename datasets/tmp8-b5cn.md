# Operating Cost Per Revenue Vehicle Mile

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/operating-cost-per-revenue-vehicle-mile) |
| Metadata | [Link](https://data.maryland.gov/api/views/tmp8-b5cn) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tmp8-b5cn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tmp8-b5cn/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tmp8-b5cn |
| Name | Operating Cost Per Revenue Vehicle Mile |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | revenue, cost, transportation, maryland transit administration |
| Created | 2016-05-19T20:51:04Z |
| Publication Date | 2016-09-07T17:56:03Z |

## Description

Operating Cost Per Revenue Vehicle Mile on an annual basis for Maryland Transit Administration services; Local Bus, Light Rail, Metro Rail, Mobility, and MARC.

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type     | Render Type   |
| ======== | ============== | =================================================== | =================================================== | ============= | ============= |
| Yes      | time           | date                                                | Date                                                | calendar_date | calendar_date |
| No       |                | fiscal_year                                         | Fiscal Year                                         | number        | text          |
| Yes      | numeric metric | core_bus                                            | Core Bus                                            | money         | money         |
| Yes      | numeric metric | metro                                               | Metro                                               | money         | money         |
| Yes      | numeric metric | light_rail                                          | Light Rail                                          | money         | money         |
| Yes      | numeric metric | mobility_paratransit                                | Mobility Paratransit                                | money         | money         |
| Yes      | numeric metric | marc                                                | MARC                                                | money         | money         |
| Yes      | numeric metric | contracted_commuter_bus_to_baltimore_and_washington | Contracted Commuter Bus to Baltimore and Washington | money         | money         |
| Yes      | numeric metric | taxi_access                                         | Taxi Access                                         | money         | money         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:tmp8-b5cn d:2010-07-01T00:00:00.000Z m:core_bus=14.23 m:marc=17.21 m:metro=11.95 m:contracted_commuter_bus_to_baltimore_and_washington=5.83 m:taxi_access=4.57 m:mobility_paratransit=6.06 m:light_rail=12.37

series e:tmp8-b5cn d:2011-07-01T00:00:00.000Z m:core_bus=15.6 m:marc=16.67 m:metro=11.58 m:contracted_commuter_bus_to_baltimore_and_washington=6.51 m:taxi_access=4.82 m:mobility_paratransit=5.34 m:light_rail=14

series e:tmp8-b5cn d:2012-07-01T00:00:00.000Z m:core_bus=11.83 m:marc=17.56 m:metro=10.12 m:contracted_commuter_bus_to_baltimore_and_washington=9.95 m:taxi_access=5.37 m:mobility_paratransit=6.06 m:light_rail=11.6
```

## Meta Commands

```ls
metric m:core_bus p:double l:"Core Bus" t:dataTypeName=money

metric m:metro p:double l:Metro t:dataTypeName=money

metric m:light_rail p:double l:"Light Rail" t:dataTypeName=money

metric m:mobility_paratransit p:double l:"Mobility Paratransit" t:dataTypeName=money

metric m:marc p:double l:MARC t:dataTypeName=money

metric m:contracted_commuter_bus_to_baltimore_and_washington p:double l:"Contracted Commuter Bus to Baltimore and Washington" t:dataTypeName=money

metric m:taxi_access p:double l:"Taxi Access" t:dataTypeName=money

entity e:tmp8-b5cn l:"Operating Cost Per Revenue Vehicle Mile" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/tmp8-b5cn

property e:tmp8-b5cn t:meta.view v:id=tmp8-b5cn v:category=Transportation v:attributionLink=https://mta.maryland.gov/ v:averageRating=0 v:name="Operating Cost Per Revenue Vehicle Mile" v:attribution="Maryland Transit Administration"

property e:tmp8-b5cn t:meta.view.license v:name="Public Domain"

property e:tmp8-b5cn t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:tmp8-b5cn t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| date                | fiscal_year | core_bus | metro | light_rail | mobility_paratransit | marc  | contracted_commuter_bus_to_baltimore_and_washington | taxi_access | 
| =================== | =========== | ======== | ===== | ========== | ==================== | ===== | =================================================== | =========== | 
| 2010-07-01T00:00:00 | 2011        | 14.23    | 11.95 | 12.37      | 6.06                 | 17.21 | 5.83                                                | 4.57        | 
| 2011-07-01T00:00:00 | 2012        | 15.60    | 11.58 | 14.00      | 5.34                 | 16.67 | 6.51                                                | 4.82        | 
| 2012-07-01T00:00:00 | 2013        | 11.83    | 10.12 | 11.60      | 6.06                 | 17.56 | 9.95                                                | 5.37        | 
| 2013-07-01T00:00:00 | 2014        | 13.30    | 11.18 | 12.98      | 5.14                 | 22.30 | 10.02                                               | 5.27        | 
| 2014-07-01T00:00:00 | 2015        | 13.64    | 11.25 | 15.11      | 5.16                 | 22.70 | 9.32                                                | 6.05        | 
```