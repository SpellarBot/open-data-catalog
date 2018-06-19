# Municipal Carbon Footprint

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-carbon-footprint) |
| Metadata | [Link](https://data.austintexas.gov/api/views/acyh-8suc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/acyh-8suc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/acyh-8suc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | acyh-8suc |
| Name | Municipal Carbon Footprint |
| Category | Environmental |
| Tags | carbon footprint, greenhouse gas, emissions |
| Created | 2015-08-07T18:17:26Z |
| Publication Date | 2015-08-07T18:19:45Z |

## Description

Summary of City of Austin's Utility & Municipal Operations Greenhouse Gas Emissions by source and year (MTCO2e)

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | time           | year                                | Year                                | number    | number      |
| Yes      | numeric metric | power_generation_delivery           | Power Generation & Delivery         | number    | number      |
| Yes      | numeric metric | wastewater_treatment                | Wastewater Treatment                | number    | number      |
| Yes      | numeric metric | fm_812_landfill                     | FM 812 Landfill                     | number    | number      |
| Yes      | numeric metric | natural_gas_use                     | Natural Gas Use                     | number    | number      |
| Yes      | numeric metric | diesel_use_for_back_up_generators   | Diesel Use for Back-up Generators   | number    | number      |
| Yes      | numeric metric | transportation_fuel_use             | Transportation Fuel Use             | number    | number      |
| Yes      | numeric metric | refrigerant_use                     | Refrigerant Use                     | number    | number      |
| Yes      | numeric metric | electricity_use_from_non_ae_sources | Electricity Use from Non-AE Sources | number    | number      |
| Yes      | numeric metric | chilled_water_energy                | Chilled Water Energy                | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:acyh-8suc d:2007-01-01T00:00:00.000Z m:power_generation_delivery=6082347 m:fm_812_landfill=206570 m:natural_gas_use=6733 m:refrigerant_use=7 m:chilled_water_energy=1428 m:transportation_fuel_use=53717 m:electricity_use_from_non_ae_sources=2550 m:diesel_use_for_back_up_generators=194 m:wastewater_treatment=16990

series e:acyh-8suc d:2008-01-01T00:00:00.000Z m:power_generation_delivery=5888310 m:fm_812_landfill=198186 m:natural_gas_use=5879 m:refrigerant_use=17 m:chilled_water_energy=1435 m:transportation_fuel_use=45001 m:electricity_use_from_non_ae_sources=3442 m:diesel_use_for_back_up_generators=478 m:wastewater_treatment=17148

series e:acyh-8suc d:2009-01-01T00:00:00.000Z m:power_generation_delivery=5503901 m:fm_812_landfill=188732 m:natural_gas_use=5984 m:refrigerant_use=15 m:chilled_water_energy=1409 m:transportation_fuel_use=44845 m:electricity_use_from_non_ae_sources=2643 m:diesel_use_for_back_up_generators=307 m:wastewater_treatment=17525
```

## Meta Commands

```ls
metric m:power_generation_delivery p:integer l:"Power Generation & Delivery" t:dataTypeName=number

metric m:wastewater_treatment p:integer l:"Wastewater Treatment" t:dataTypeName=number

metric m:fm_812_landfill p:integer l:"FM 812 Landfill" t:dataTypeName=number

metric m:natural_gas_use p:integer l:"Natural Gas Use" t:dataTypeName=number

metric m:diesel_use_for_back_up_generators p:integer l:"Diesel Use for Back-up Generators" t:dataTypeName=number

metric m:transportation_fuel_use p:integer l:"Transportation Fuel Use" t:dataTypeName=number

metric m:refrigerant_use p:integer l:"Refrigerant Use" t:dataTypeName=number

metric m:electricity_use_from_non_ae_sources p:integer l:"Electricity Use from Non-AE Sources" t:dataTypeName=number

metric m:chilled_water_energy p:integer l:"Chilled Water Energy" t:dataTypeName=number

entity e:acyh-8suc l:"Municipal Carbon Footprint" t:url=https://data.austintexas.gov/api/views/acyh-8suc

property e:acyh-8suc t:meta.view v:id=acyh-8suc v:category=Environmental v:averageRating=0 v:name="Municipal Carbon Footprint"

property e:acyh-8suc t:meta.view.owner v:id=e6tq-76jh v:screenName=jenellmoffett v:displayName=jenellmoffett

property e:acyh-8suc t:meta.view.tableauthor v:id=e6tq-76jh v:screenName=jenellmoffett v:roleName=editor v:displayName=jenellmoffett
```

## Top Records

```ls
| year | power_generation_delivery | wastewater_treatment | fm_812_landfill | natural_gas_use | diesel_use_for_back_up_generators | transportation_fuel_use | refrigerant_use | electricity_use_from_non_ae_sources | chilled_water_energy | 
| ==== | ========================= | ==================== | =============== | =============== | ================================= | ======================= | =============== | =================================== | ==================== | 
| 2007 | 6082347                   | 16990                | 206570          | 6733            | 194                               | 53717                   | 7               | 2550                                | 1428                 | 
| 2008 | 5888310                   | 17148                | 198186          | 5879            | 478                               | 45001                   | 17              | 3442                                | 1435                 | 
| 2009 | 5503901                   | 17525                | 188732          | 5984            | 307                               | 44845                   | 15              | 2643                                | 1409                 | 
| 2010 | 5113139                   | 17809                | 8711            | 7226            | 308                               | 41975                   | 20              | 2478                                | 1285                 | 
| 2011 | 5836305                   | 18097                | 17882           | 5422            | 329                               | 44006                   | 1846            | 2546                                | 1584                 | 
| 2012 | 4635866                   | 18468                | 25790           | 5538            | 330                               | 41326                   | 1878            | 3577                                | 2120                 | 
| 2013 | 4879710                   | 10418                | 53070           | 6899            | 330                               | 45101                   | 1976            | 3966                                | 2355                 | 
```