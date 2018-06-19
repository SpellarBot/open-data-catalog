# Operating Cost Per Passenger Trip

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/operating-cost-per-passenger-trip) |
| Metadata | [Link](https://data.maryland.gov/api/views/ntnu-s899) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ntnu-s899/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ntnu-s899/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ntnu-s899 |
| Name | Operating Cost Per Passenger Trip |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | cost, maryland transit administration, passenger |
| Created | 2016-05-20T18:49:26Z |
| Publication Date | 2016-09-07T17:55:15Z |

## Description

Operating Cost Per Passenger Trip on an annual basis for Maryland Transit Administration services; Local Bus, Light Rail, Metro Rail, Mobility and MARC.

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
series e:ntnu-s899 d:2010-07-01T00:00:00.000Z m:core_bus=4.01 m:marc=11.28 m:metro=4.02 m:contracted_commuter_bus_to_baltimore_and_washington=6.35 m:taxi_access=19.88 m:mobility_paratransit=42.96 m:light_rail=4.48

series e:ntnu-s899 d:2011-07-01T00:00:00.000Z m:core_bus=4.05 m:marc=11.37 m:metro=3.52 m:contracted_commuter_bus_to_baltimore_and_washington=7.9 m:taxi_access=21.14 m:mobility_paratransit=42.3 m:light_rail=4.93

series e:ntnu-s899 d:2012-07-01T00:00:00.000Z m:core_bus=3.48 m:marc=13.42 m:metro=3.4 m:contracted_commuter_bus_to_baltimore_and_washington=12.76 m:taxi_access=22.88 m:mobility_paratransit=51.1 m:light_rail=4.37
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

entity e:ntnu-s899 l:"Operating Cost Per Passenger Trip" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/ntnu-s899

property e:ntnu-s899 t:meta.view v:id=ntnu-s899 v:category=Transportation v:attributionLink=https://mta.maryland.gov/ v:averageRating=0 v:name="Operating Cost Per Passenger Trip" v:attribution="Maryland Transit Administration"

property e:ntnu-s899 t:meta.view.license v:name="Public Domain"

property e:ntnu-s899 t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:ntnu-s899 t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| date                | fiscal_year | core_bus | metro | light_rail | mobility_paratransit | marc  | contracted_commuter_bus_to_baltimore_and_washington | taxi_access | 
| =================== | =========== | ======== | ===== | ========== | ==================== | ===== | =================================================== | =========== | 
| 2010-07-01T00:00:00 | 2011        | 4.01     | 4.02  | 4.48       | 42.96                | 11.28 | 6.35                                                | 19.88       | 
| 2011-07-01T00:00:00 | 2012        | 4.05     | 3.52  | 4.93       | 42.30                | 11.37 | 7.90                                                | 21.14       | 
| 2012-07-01T00:00:00 | 2013        | 3.48     | 3.40  | 4.37       | 51.10                | 13.42 | 12.76                                               | 22.88       | 
| 2013-07-01T00:00:00 | 2014        | 3.52     | 3.86  | 5.32       | 42.57                | 15.57 | 13.49                                               | 21.25       | 
| 2014-07-01T00:00:00 | 2015        | 3.48     | 4.06  | 5.85       | 42.61                | 15.39 | 13.65                                               | 24.65       | 
```