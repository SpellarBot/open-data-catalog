# New York Power Authority (NYPA) Electric Supply Rates - Business Customers: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-power-authority-nypa-electric-supply-rates-business-customers-beginning-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/2x8p-pewm) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2x8p-pewm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2x8p-pewm/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2x8p-pewm |
| Name | New York Power Authority (NYPA) Electric Supply Rates - Business Customers: Beginning 2012 |
| Attribution | New York Power Authority |
| Category | Energy & Environment |
| Tags | power, business, electric supply rates |
| Created | 2014-10-14T16:46:07Z |
| Publication Date | 2017-01-31T23:01:04Z |

## Description

The New York Power Authority provides low-cost power to help support jobs statewide while reducing public-sector costs. The Authority?s customer base includes large and small businesses, not-for-profit organizations, community-owned electric systems and rural electric cooperatives and government entities. This data includes the electric supply rates that the Authority offers to its Business Customers under different power programs.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | customer_type                | Customer Type                  | text          | text          |
| Yes      | series tag     | nyiso_zone                   | NYISO Zone                     | text          | text          |
| Yes      | numeric metric | demand_price_kw              | Demand Rate ($/kW)             | number        | number        |
| Yes      | numeric metric | energy_price_mills_kwh       | Energy Rate (mills/kWh)        | number        | number        |
| Yes      | numeric metric | composite_price_load_factor_ | Composite Rate Load Factor (%) | percent       | percent       |
| Yes      | numeric metric | composite_price_mills_kwh    | Composite Rate (mills/kWh)     | number        | number        |
| Yes      | time           | data_as_of                   | Data as of                     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2x8p-pewm d:2012-12-31T00:00:00.000Z t:customer_type="Utilities, Municipal and Cooperative Systems and Public Entities" m:demand_price_kw=3.57 m:energy_price_mills_kwh=4.92 m:composite_price_load_factor_=70 m:composite_price_mills_kwh=11.91

series e:2x8p-pewm d:2012-12-31T00:00:00.000Z t:customer_type="Replacement Power" m:demand_price_kw=5.81 m:energy_price_mills_kwh=9.95 m:composite_price_load_factor_=80 m:composite_price_mills_kwh=19.9

series e:2x8p-pewm d:2012-12-31T00:00:00.000Z t:customer_type="Expansion Power" m:demand_price_kw=5.81 m:energy_price_mills_kwh=9.95 m:composite_price_load_factor_=80 m:composite_price_mills_kwh=19.9
```

## Meta Commands

```ls
metric m:demand_price_kw p:float l:"Demand Rate ($/kW)" d:"Lists demand rate expressed in dollars per kilowatt per month, usually applied to the monthly max metered demand kW." t:dataTypeName=number

metric m:energy_price_mills_kwh p:float l:"Energy Rate (mills/kWh)" d:"Lists monthly energy rate expressed in mills per kilowatt-hour (0.1 cents/kWh), usually applied to the monthly energy kWh usage." t:dataTypeName=number

metric m:composite_price_load_factor_ p:integer l:"Composite Rate Load Factor (%)" d:"Lists assumed percentage load factor (the ratio of the average load to peak load during a specified time interval) for the Customer Type." t:dataTypeName=percent

metric m:composite_price_mills_kwh p:float l:"Composite Rate (mills/kWh)" d:"All-in rate including both demand and energy charges at the assumed load factor. The formula for the composite rate can be found in the attached data dictionary." t:dataTypeName=number

entity e:2x8p-pewm l:"New York Power Authority (NYPA) Electric Supply Rates - Business Customers: Beginning 2012" t:attribution="New York Power Authority" t:url=https://data.ny.gov/api/views/2x8p-pewm

property e:2x8p-pewm t:meta.view v:id=2x8p-pewm v:category="Energy & Environment" v:attributionLink=http://www.nypa.gov/about/documents.htm v:averageRating=0 v:name="New York Power Authority (NYPA) Electric Supply Rates - Business Customers: Beginning 2012" v:attribution="New York Power Authority"

property e:2x8p-pewm t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2x8p-pewm t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2x8p-pewm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| customer_type                                                                                                        | nyiso_zone | demand_price_kw | energy_price_mills_kwh | composite_price_load_factor_ | composite_price_mills_kwh | data_as_of          | 
| ==================================================================================================================== | ========== | =============== | ====================== | ============================ | ========================= | =================== | 
| Utilities, Municipal and Cooperative Systems and Public Entities                                                     |            | 3.57            | 4.92                   | 70                           | 11.91                     | 2012-12-31T00:00:00 | 
| Replacement Power                                                                                                    |            | 5.81            | 9.95                   | 80                           | 19.9                      | 2012-12-31T00:00:00 | 
| Expansion Power                                                                                                      |            | 5.81            | 9.95                   | 80                           | 19.9                      | 2012-12-31T00:00:00 | 
| Aluminum Company of America                                                                                          |            | 4.48            | 8.86                   | 95                           | 15.32                     | 2012-12-31T00:00:00 | 
| Reynolds Metals Company                                                                                              |            | 4.56            | 9.01                   | 95                           | 15.59                     | 2012-12-31T00:00:00 | 
| St. Lawrence Seaway Development Corporation and New York State Office of Parks, Recreation and Historic Preservation |            |                 | 10                     |                              |                           | 2012-12-31T00:00:00 | 
| Preservation Power                                                                                                   |            | 7.32            | 12.52                  | 70                           | 26.84                     | 2012-12-31T00:00:00 | 
| Direct Sale ReCharge New York - Hydro Power                                                                          | A-E        | 7.32            | 15.81                  | 70                           | 30.13                     | 2012-12-31T00:00:00 | 
| Direct Sale ReCharge New York - Hydro Power                                                                          | F-I        | 7.32            | 23.89                  | 70                           | 38.21                     | 2012-12-31T00:00:00 | 
| Direct Sale ReCharge New York - Hydro Power                                                                          | J          | 7.32            | 36.44                  | 70                           | 50.76                     | 2012-12-31T00:00:00 | 
```