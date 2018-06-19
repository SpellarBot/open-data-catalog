# Travis County Community-wide Greenhouse Gas Emissions Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/travis-county-community-wide-greenhouse-gas-emissions-inventory) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3maj-7ecz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3maj-7ecz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3maj-7ecz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3maj-7ecz |
| Name | Travis County Community-wide Greenhouse Gas Emissions Inventory |
| Category | Environmental |
| Tags | carbon footprint, greenhouse gas, emissions |
| Created | 2015-08-07T18:23:16Z |
| Publication Date | 2015-08-07T18:27:48Z |

## Description

Summary of Travis County community-wide greenhouse gas emissions inventory by source and year (MTCO2e)

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type | Render Type |
| ======== | ============== | =================================== | ===================================== | ========= | =========== |
| Yes      | time           | year                                | Year                                  | number    | number      |
| Yes      | numeric metric | materials_and_waste_management      | Materials and Waste Management        | number    | number      |
| Yes      | numeric metric | transportation_mobile_sources       | Transportation & Mobile Sources       | number    | number      |
| Yes      | numeric metric | water_wastewater                    | Water & Wastewater                    | number    | number      |
| Yes      | numeric metric | process_fugitive_emissions          | Process & Fugitive Emissions          | number    | number      |
| Yes      | numeric metric | industrial_electricity_natural_gas  | Industrial Electricity & Natural Gas  | number    | number      |
| Yes      | numeric metric | residential_electricity_natural_gas | Residential Electricity & Natural Gas | number    | number      |
| Yes      | numeric metric | commercial_electricity_natural_gas  | Commercial Electricity & Natural Gas  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3maj-7ecz d:2007-01-01T00:00:00.000Z m:transportation_mobile_sources=5191174 m:commercial_electricity_natural_gas=3302901 m:residential_electricity_natural_gas=3127768 m:industrial_electricity_natural_gas=1179814 m:water_wastewater=29791 m:materials_and_waste_management=206514

series e:3maj-7ecz d:2010-01-01T00:00:00.000Z m:transportation_mobile_sources=4851487 m:process_fugitive_emissions=1016859 m:commercial_electricity_natural_gas=3144043 m:residential_electricity_natural_gas=3482365 m:industrial_electricity_natural_gas=1090938 m:water_wastewater=30574 m:materials_and_waste_management=433902

series e:3maj-7ecz d:2013-01-01T00:00:00.000Z m:transportation_mobile_sources=4919066 m:process_fugitive_emissions=783038 m:commercial_electricity_natural_gas=2909966 m:residential_electricity_natural_gas=3020522 m:industrial_electricity_natural_gas=1446193 m:water_wastewater=10409 m:materials_and_waste_management=650223
```

## Meta Commands

```ls
metric m:materials_and_waste_management p:integer l:"Materials and Waste Management" t:dataTypeName=number

metric m:transportation_mobile_sources p:integer l:"Transportation & Mobile Sources" t:dataTypeName=number

metric m:water_wastewater p:integer l:"Water & Wastewater" t:dataTypeName=number

metric m:process_fugitive_emissions p:integer l:"Process & Fugitive Emissions" t:dataTypeName=number

metric m:industrial_electricity_natural_gas p:integer l:"Industrial Electricity & Natural Gas" t:dataTypeName=number

metric m:residential_electricity_natural_gas p:integer l:"Residential Electricity & Natural Gas" t:dataTypeName=number

metric m:commercial_electricity_natural_gas p:integer l:"Commercial Electricity & Natural Gas" t:dataTypeName=number

entity e:3maj-7ecz l:"Travis County Community-wide Greenhouse Gas Emissions Inventory" t:url=https://data.austintexas.gov/api/views/3maj-7ecz

property e:3maj-7ecz t:meta.view v:id=3maj-7ecz v:category=Environmental v:averageRating=0 v:name="Travis County Community-wide Greenhouse Gas Emissions Inventory"

property e:3maj-7ecz t:meta.view.owner v:id=e6tq-76jh v:screenName=jenellmoffett v:displayName=jenellmoffett

property e:3maj-7ecz t:meta.view.tableauthor v:id=e6tq-76jh v:screenName=jenellmoffett v:roleName=editor v:displayName=jenellmoffett
```

## Top Records

```ls
| year | materials_and_waste_management | transportation_mobile_sources | water_wastewater | process_fugitive_emissions | industrial_electricity_natural_gas | residential_electricity_natural_gas | commercial_electricity_natural_gas | 
| ==== | ============================== | ============================= | ================ | ========================== | ================================== | =================================== | ================================== | 
| 2007 | 206514                         | 5191174                       | 29791            |                            | 1179814                            | 3127768                             | 3302901                            | 
| 2010 | 433902                         | 4851487                       | 30574            | 1016859                    | 1090938                            | 3482365                             | 3144043                            | 
| 2013 | 650223                         | 4919066                       | 10409            | 783038                     | 1446193                            | 3020522                             | 2909966                            | 
```