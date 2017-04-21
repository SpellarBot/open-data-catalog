# New York Power Authority (NYPA) Electric Supply Rates - Governmental Entities: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-power-authority-nypa-electric-supply-rates-governmental-entities-beginning-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/tj6m-a24c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tj6m-a24c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tj6m-a24c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tj6m-a24c |
| Name | New York Power Authority (NYPA) Electric Supply Rates - Governmental Entities: Beginning 2012 |
| Attribution | Electric, supply, rates, utility |
| Category | Energy & Environment |
| Tags | power, government, electric supply rates |
| Created | 2014-10-14T17:07:37Z |
| Publication Date | 2017-01-31T23:01:47Z |

## Description

The New York Power Authority provides low-cost power to help support jobs statewide while reducing public-sector costs. The Authority?s customer base includes large and small businesses, not-for-profit organizations, community-owned electric systems and rural electric cooperatives and government entities. This data includes the electric supply rates that the Authority offers to its Governmental Customers.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                        | Data Type     | Render Type   |
| ======== | ============== | ========================================= | =========================================== | ============= | ============= |
| Yes      | series tag     | govermental_entity                        | Govermental Entity                          | text          | text          |
| Yes      | series tag     | service_classification                    | Service Classification                      | text          | text          |
| Yes      | series tag     | ratetype                                  | RateType                                    | text          | text          |
| Yes      | series tag     | period                                    | Period                                      | text          | text          |
| Yes      | numeric metric | production_demand_price_kw                | Production Demand Rate ($/kW)               | number        | number        |
| Yes      | numeric metric | production_energy_price_mills_kwh         | Production Energy Rate (mills/kWh)          | number        | number        |
| Yes      | numeric metric | production_on_peak_energy_price_mills_kwh | Production On-Peak Energy Rate (mills/kWh)  | number        | number        |
| Yes      | numeric metric | production_offpeak_energy_price_mills_kwh | Production Off-Peak Energy Rate (mills/kWh) | number        | number        |
| Yes      | time           | data_as_of                                | Data as of                                  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tj6m-a24c d:2013-04-30T00:00:00.000Z t:govermental_entity="NYC Customers" t:ratetype=Conventional t:service_classification="SC 62 - General Small" t:period=Summer m:production_energy_price_mills_kwh=77.46 m:production_demand_price_kw=0

series e:tj6m-a24c d:2013-04-30T00:00:00.000Z t:govermental_entity="NYC Customers" t:ratetype=Conventional t:service_classification="SC 62 - General Small" t:period=Winter m:production_energy_price_mills_kwh=72.67 m:production_demand_price_kw=0

series e:tj6m-a24c d:2013-04-30T00:00:00.000Z t:govermental_entity="NYC Customers" t:ratetype=Conventional t:service_classification="SC 65 - Electric Traction Systems and Platform Lighting" t:period=Summer m:production_energy_price_mills_kwh=60.51 m:production_demand_price_kw=8.15
```

## Meta Commands

```ls
metric m:production_demand_price_kw p:float l:"Production Demand Rate ($/kW)" d:"Lists demand rate expressed in dollars per kilowatt per month, usually applied to the monthly max metered demand kW." t:dataTypeName=number

metric m:production_energy_price_mills_kwh p:float l:"Production Energy Rate (mills/kWh)" d:"Lists monthly energy rate expressed in mills per kilowatt-hour (0.1 cents/kWh), usually applied to the monthly energy kWh usage." t:dataTypeName=number

metric m:production_on_peak_energy_price_mills_kwh p:float l:"Production On-Peak Energy Rate (mills/kWh)" d:"Lists on-peak (8:00 AM to 10 PM weekdays, including holidays)energy rate for TOD service classifications expressed in mills per kilowatt-hour (0.1 cents/kWh)." t:dataTypeName=number

metric m:production_offpeak_energy_price_mills_kwh p:float l:"Production Off-Peak Energy Rate (mills/kWh)" d:"Lists off-peak (10 PM to 8 AM weekdays, including holidays, and all day on weekends) energy rate for TOD service classifications expressed in mills per kilowatt-hour (0.1 cents/kWh)." t:dataTypeName=number

entity e:tj6m-a24c l:"New York Power Authority (NYPA) Electric Supply Rates - Governmental Entities: Beginning 2012" t:attribution="Electric, supply, rates, utility" t:url=https://data.ny.gov/api/views/tj6m-a24c

property e:tj6m-a24c t:meta.view v:id=tj6m-a24c v:category="Energy & Environment" v:averageRating=0 v:name="New York Power Authority (NYPA) Electric Supply Rates - Governmental Entities: Beginning 2012" v:attribution="Electric, supply, rates, utility"

property e:tj6m-a24c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tj6m-a24c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tj6m-a24c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| govermental_entity | service_classification                                                       | ratetype     | period | production_demand_price_kw | production_energy_price_mills_kwh | production_on_peak_energy_price_mills_kwh | production_offpeak_energy_price_mills_kwh | data_as_of          | 
| ================== | ============================================================================ | ============ | ====== | ========================== | ================================= | ========================================= | ========================================= | =================== | 
| NYC Customers      | SC 62 - General Small                                                        | Conventional | Summer | 0                          | 77.459999999999994                |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 62 - General Small                                                        | Conventional | Winter | 0                          | 72.67                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 65 - Electric Traction Systems and Platform Lighting                      | Conventional | Summer | 8.15                       | 60.51                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 65 - Electric Traction Systems and Platform Lighting                      | Conventional | Winter | 8.15                       | 55.81                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 66 - NYC Public Street Lighting (Except for service provided under SC 80) | Conventional | Summer | 0                          | 59.37                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 66 - NYC Public Street Lighting (Except for service provided under SC 80) | Conventional | Winter | 0                          | 59.37                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 68 - Multiple Dwellings-Redistribution                                    | Conventional | Summer | 17.559999999999999         | 56.37                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 68 - Multiple Dwellings-Redistribution                                    | Conventional | Winter | 17.559999999999999         | 51.58                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 69 - General Large                                                        | Conventional | Summer | 12.5                       | 58.69                             |                                           |                                           | 2013-04-30T00:00:00 | 
| NYC Customers      | SC 69 - General Large                                                        | Conventional | Winter | 12.5                       | 53.91                             |                                           |                                           | 2013-04-30T00:00:00 | 
```