# Passenger Trips Per Revenue Vehicle Mile

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/passenger-trips-per-revenue-vehicle-mile) |
| Metadata | [Link](https://data.maryland.gov/api/views/vu4x-y4sr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/vu4x-y4sr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/vu4x-y4sr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | vu4x-y4sr |
| Name | Passenger Trips Per Revenue Vehicle Mile |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | revenue, transit, mta, maryland transit administration, transportation |
| Created | 2016-06-08T18:46:35Z |
| Publication Date | 2016-09-07T17:53:38Z |

## Description

Passenger Trips Per Revenue Vehicle Mile on an annual basis for Maryland Transit Administration services; Local Bus, Light Rail, Metro Rail, and MARC

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type     | Render Type   |
| ======== | ============== | =================================================== | =================================================== | ============= | ============= |
| Yes      | time           | date                                                | Date                                                | calendar_date | calendar_date |
| No       |                | fiscal_year                                         | Fiscal Year                                         | number        | text          |
| Yes      | numeric metric | core_bus                                            | Core Bus                                            | number        | number        |
| Yes      | numeric metric | metro                                               | Metro                                               | number        | number        |
| Yes      | numeric metric | light_rail                                          | Light Rail                                          | number        | number        |
| Yes      | numeric metric | marc                                                | MARC                                                | number        | number        |
| Yes      | numeric metric | contracted_commuter_bus_to_baltimore_and_washington | Contracted Commuter Bus to Baltimore and Washington | number        | number        |
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
series e:vu4x-y4sr d:2010-07-01T00:00:00.000Z m:core_bus=3.55 m:marc=1.5 m:metro=2.97 m:contracted_commuter_bus_to_baltimore_and_washington=0.9 m:light_rail=2.76

series e:vu4x-y4sr d:2011-07-01T00:00:00.000Z m:core_bus=3.86 m:marc=1.47 m:metro=3.28 m:contracted_commuter_bus_to_baltimore_and_washington=0.82 m:light_rail=2.84

series e:vu4x-y4sr d:2012-07-01T00:00:00.000Z m:core_bus=3.4 m:marc=1.31 m:metro=2.98 m:contracted_commuter_bus_to_baltimore_and_washington=0.78 m:light_rail=2.66
```

## Meta Commands

```ls
metric m:core_bus p:float l:"Core Bus" t:dataTypeName=number

metric m:metro p:float l:Metro t:dataTypeName=number

metric m:light_rail p:float l:"Light Rail" t:dataTypeName=number

metric m:marc p:float l:MARC t:dataTypeName=number

metric m:contracted_commuter_bus_to_baltimore_and_washington p:float l:"Contracted Commuter Bus to Baltimore and Washington" t:dataTypeName=number

entity e:vu4x-y4sr l:"Passenger Trips Per Revenue Vehicle Mile" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/vu4x-y4sr

property e:vu4x-y4sr t:meta.view v:id=vu4x-y4sr v:category=Transportation v:attributionLink=https://mta.maryland.gov/ v:averageRating=0 v:name="Passenger Trips Per Revenue Vehicle Mile" v:attribution="Maryland Transit Administration"

property e:vu4x-y4sr t:meta.view.license v:name="Public Domain"

property e:vu4x-y4sr t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:vu4x-y4sr t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| date                | fiscal_year | core_bus | metro | light_rail | marc | contracted_commuter_bus_to_baltimore_and_washington | 
| =================== | =========== | ======== | ===== | ========== | ==== | =================================================== | 
| 2010-07-01T00:00:00 | 2011        | 3.55     | 2.97  | 2.76       | 1.50 | 0.90                                                | 
| 2011-07-01T00:00:00 | 2012        | 3.86     | 3.28  | 2.84       | 1.47 | 0.82                                                | 
| 2012-07-01T00:00:00 | 2013        | 3.40     | 2.98  | 2.66       | 1.31 | 0.78                                                | 
| 2013-07-01T00:00:00 | 2014        | 3.78     | 2.90  | 2.44       | 1.43 | 0.74                                                | 
| 2014-07-01T00:00:00 | 2015        | 3.92     | 2.77  | 2.59       | 1.47 | 0.68                                                | 
```