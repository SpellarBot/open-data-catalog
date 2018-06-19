# Farebox Recovery Ratio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/farebox-recovery-ratio) |
| Metadata | [Link](https://data.maryland.gov/api/views/6hpa-vs46) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6hpa-vs46/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6hpa-vs46/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6hpa-vs46 |
| Name | Farebox Recovery Ratio |
| Attribution | Maryland Transit Administration |
| Category | Transportation |
| Tags | transportation, mta, maryland transit administration, revenue. |
| Created | 2016-06-09T15:30:52Z |
| Publication Date | 2016-09-07T17:52:44Z |

## Description

Farebox Recovery Ratio on a fiscal basis for Maryland Transit Administration services; Local Bus, Light Rail, Metro Rail, and MARC.

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ==================================================== | ====================================================== | ============= | ============= |
| Yes      | time           | date                                                 | Date                                                   | calendar_date | calendar_date |
| Yes      | series tag     | fiscal_year                                          | Fiscal Year                                            | text          | text          |
| Yes      | numeric metric | core_bus                                             | Core Bus                                               | percent       | percent       |
| Yes      | numeric metric | metro                                                | Metro                                                  | percent       | percent       |
| Yes      | numeric metric | light_rail                                           | Light Rail                                             | percent       | percent       |
| Yes      | numeric metric | marc                                                 | MARC                                                   | percent       | percent       |
| Yes      | numeric metric | baltimore_area_services_without_mobility_paratransit | Baltimore Area Services (Without Mobility paratransit) | percent       | percent       |
| Yes      | numeric metric | contracted_commuter_bus_washington                   | Contracted Commuter Bus Washington                     | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6hpa-vs46 d:2010-07-01T00:00:00.000Z t:fiscal_year="FY 2011" m:core_bus=30 m:marc=50 m:baltimore_area_services_without_mobility_paratransit=28 m:metro=26 m:light_rail=17

series e:6hpa-vs46 d:2011-07-01T00:00:00.000Z t:fiscal_year="FY 2012" m:core_bus=29 m:marc=56 m:baltimore_area_services_without_mobility_paratransit=27 m:metro=28 m:contracted_commuter_bus_washington=28 m:light_rail=16

series e:6hpa-vs46 d:2012-07-01T00:00:00.000Z t:fiscal_year="FY 2013" m:core_bus=30 m:marc=55 m:baltimore_area_services_without_mobility_paratransit=27 m:metro=26 m:contracted_commuter_bus_washington=25 m:light_rail=16
```

## Meta Commands

```ls
metric m:core_bus p:integer l:"Core Bus" t:dataTypeName=percent

metric m:metro p:integer l:Metro t:dataTypeName=percent

metric m:light_rail p:integer l:"Light Rail" t:dataTypeName=percent

metric m:marc p:integer l:MARC t:dataTypeName=percent

metric m:baltimore_area_services_without_mobility_paratransit p:integer l:"Baltimore Area Services (Without Mobility paratransit)" t:dataTypeName=percent

metric m:contracted_commuter_bus_washington p:integer l:"Contracted Commuter Bus Washington" t:dataTypeName=percent

entity e:6hpa-vs46 l:"Farebox Recovery Ratio" t:attribution="Maryland Transit Administration" t:url=https://data.maryland.gov/api/views/6hpa-vs46

property e:6hpa-vs46 t:meta.view v:id=6hpa-vs46 v:category=Transportation v:attributionLink=https://mta.maryland.gov/ v:averageRating=0 v:name="Farebox Recovery Ratio" v:attribution="Maryland Transit Administration"

property e:6hpa-vs46 t:meta.view.license v:name="Public Domain"

property e:6hpa-vs46 t:meta.view.owner v:id=28y5-7nmz v:screenName=bsmalls1 v:displayName=bsmalls1

property e:6hpa-vs46 t:meta.view.tableauthor v:id=28y5-7nmz v:screenName=bsmalls1 v:roleName=editor v:displayName=bsmalls1
```

## Top Records

```ls
| date                | fiscal_year | core_bus | metro | light_rail | marc | baltimore_area_services_without_mobility_paratransit | contracted_commuter_bus_washington | 
| =================== | =========== | ======== | ===== | ========== | ==== | ==================================================== | ================================== | 
| 2010-07-01T00:00:00 | FY 2011     | 30       | 26    | 17         | 50   | 28                                                   |                                    | 
| 2011-07-01T00:00:00 | FY 2012     | 29       | 28    | 16         | 56   | 27                                                   | 28                                 | 
| 2012-07-01T00:00:00 | FY 2013     | 30       | 26    | 16         | 55   | 27                                                   | 25                                 | 
| 2013-07-01T00:00:00 | FY 2014     | 28       | 24    | 16         | 50   | 28                                                   | 33                                 | 
| 2014-07-01T00:00:00 | FY 2015     | 28       | 21    | 16         | 44   | 25                                                   | 30                                 | 
```