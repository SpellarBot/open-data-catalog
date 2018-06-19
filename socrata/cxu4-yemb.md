# Energy Prices Per Physical Unit By Sector: Beginning 1970

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-prices-per-physical-unit-by-sector-beginning-1970) |
| Metadata | [Link](https://data.ny.gov/api/views/cxu4-yemb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cxu4-yemb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cxu4-yemb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cxu4-yemb |
| Name | Energy Prices Per Physical Unit By Sector: Beginning 1970 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | energy prices, prices by sector, nominal prices, real prices |
| Created | 2013-03-04T15:54:15Z |
| Publication Date | 2016-11-04T22:05:19Z |

## Description

New York Energy Prices presents retail energy price data. Energy prices are provided by fuel type in nominal dollars per specified physical unit for the residential, commercial, industrial, and transportation sectors. This section includes a column in the price table displaying gross domestic product (GDP) price deflators for converting nominal (current year) dollars to constant (real) dollars. To convert nominal to constant dollars, divide the nominal energy price by the GDP price deflator for that particular year. Historical petroleum, electricity, coal, and natural gas prices were compiled primarily from the Energy Information Administration.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                          | Data Type | Render Type |
| ======== | ============== | =========================== | ============================= | ========= | =========== |
| Yes      | time           | year                        | Year                          | number    | number      |
| Yes      | numeric metric | gdp_deflator                | GDP Deflator                  | number    | number      |
| Yes      | series tag     | sector                      | Sector                        | text      | text        |
| Yes      | numeric metric | coal_ton                    | Coal ($/Ton)                  | money     | money       |
| Yes      | numeric metric | distillate_cents_gallon     | Distillate (cents/gallon)     | number    | number      |
| Yes      | numeric metric | residual_barrel             | Residual ($/barrel)           | money     | money       |
| Yes      | numeric metric | kerosene_cents_gallon       | Kerosene (cents/gallon)       | number    | number      |
| Yes      | numeric metric | propane_cents_gallon        | Propane (cents/gallon)        | number    | number      |
| Yes      | numeric metric | natural_gas_mcf             | Natural Gas ($/Mcf)           | money     | money       |
| Yes      | numeric metric | electricity_cents_kwh       | Electricity (cents/kWh)       | number    | number      |
| Yes      | numeric metric | wood_cord                   | Wood ($/Cord)                 | money     | money       |
| Yes      | numeric metric | motor_gasoline_cents_gallon | Motor Gasoline (cents/gallon) | number    | number      |
| Yes      | numeric metric | jet_fuel_cents_gallon       | Jet Fuel (cents/gallon)       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cxu4-yemb d:2014-01-01T00:00:00.000Z t:sector=Commercial m:kerosene_cents_gallon=402.84 m:propane_cents_gallon=228.97 m:gdp_deflator=1 m:electricity_cents_kwh=16.12 m:residual_barrel=92.73 m:natural_gas_mcf=8.31 m:distillate_cents_gallon=299.08

series e:cxu4-yemb d:2014-01-01T00:00:00.000Z t:sector=Industrial m:kerosene_cents_gallon=332.64 m:coal_ton=81.79 m:propane_cents_gallon=283.5 m:gdp_deflator=1 m:electricity_cents_kwh=6.58 m:residual_barrel=92.73 m:natural_gas_mcf=8.13 m:distillate_cents_gallon=312.4

series e:cxu4-yemb d:2014-01-01T00:00:00.000Z t:sector=Residential m:kerosene_cents_gallon=402.84 m:wood_cord=194.2 m:propane_cents_gallon=338.02 m:gdp_deflator=1 m:electricity_cents_kwh=20.07 m:natural_gas_mcf=12.54 m:distillate_cents_gallon=378.35
```

## Meta Commands

```ls
metric m:gdp_deflator p:double l:"GDP Deflator" t:dataTypeName=number

metric m:coal_ton p:double l:"Coal ($/Ton)" t:dataTypeName=money

metric m:distillate_cents_gallon p:float l:"Distillate (cents/gallon)" t:dataTypeName=number

metric m:residual_barrel p:double l:"Residual ($/barrel)" t:dataTypeName=money

metric m:kerosene_cents_gallon p:float l:"Kerosene (cents/gallon)" t:dataTypeName=number

metric m:propane_cents_gallon p:float l:"Propane (cents/gallon)" t:dataTypeName=number

metric m:natural_gas_mcf p:double l:"Natural Gas ($/Mcf)" t:dataTypeName=money

metric m:electricity_cents_kwh p:float l:"Electricity (cents/kWh)" t:dataTypeName=number

metric m:wood_cord p:double l:"Wood ($/Cord)" t:dataTypeName=money

metric m:motor_gasoline_cents_gallon p:float l:"Motor Gasoline (cents/gallon)" t:dataTypeName=number

metric m:jet_fuel_cents_gallon p:float l:"Jet Fuel (cents/gallon)" t:dataTypeName=number

entity e:cxu4-yemb l:"Energy Prices Per Physical Unit By Sector: Beginning 1970" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/cxu4-yemb

property e:cxu4-yemb t:meta.view v:id=cxu4-yemb v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Energy Prices Per Physical Unit By Sector: Beginning 1970" v:attribution="New York State Energy Research and Development Authority"

property e:cxu4-yemb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cxu4-yemb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cxu4-yemb t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | gdp_deflator | sector         | coal_ton | distillate_cents_gallon | residual_barrel | kerosene_cents_gallon | propane_cents_gallon | natural_gas_mcf | electricity_cents_kwh | wood_cord | motor_gasoline_cents_gallon | jet_fuel_cents_gallon | 
| ==== | ============ | ============== | ======== | ======================= | =============== | ===================== | ==================== | =============== | ===================== | ========= | =========================== | ===================== | 
| 2014 | 1            | Commercial     |          | 299.08                  | 92.73           | 402.84                | 228.97               | 8.31            | 16.12                 |           |                             |                       | 
| 2014 | 1            | Industrial     | 81.79    | 312.40                  | 92.73           | 332.64                | 283.50               | 8.13            | 6.58                  |           |                             |                       | 
| 2014 | 1            | Residential    |          | 378.35                  |                 | 402.84                | 338.02               | 12.54           | 20.07                 | 194.20    |                             |                       | 
| 2014 | 1            | Transportation |          | 369.97                  | 82.93           |                       |                      |                 | 13.82                 |           | 341.67                      | 278.24                | 
| 2013 | 0.9840       | Commercial     |          | 343.83                  | 105.87          | 400.68                | 217.28               | 7.95            | 15.35                 |           |                             |                       | 
| 2013 | 0.9840       | Industrial     | 83.79    | 332.01                  | 105.87          | 351.41                | 267.88               | 7.39            | 6.59                  |           |                             |                       | 
| 2013 | 0.9840       | Residential    |          | 387.96                  |                 | 400.68                | 318.39               | 12.41           | 18.79                 | 199.20    |                             |                       | 
| 2013 | 0.9840       | Transportation |          | 389.88                  | 97.57           |                       |                      |                 | 13.65                 |           | 354.58                      | 299.03                | 
| 2012 | 0.9698       | Commercial     |          | 354.28                  | 115.43          | 399.87                | 220.48               | 7.79            | 15.06                 |           |                             |                       | 
| 2012 | 0.9698       | Industrial     | 90.87    | 341.77                  | 115.43          | 346.55                | 273.09               | 6.87            | 6.69                  |           |                             |                       | 
```