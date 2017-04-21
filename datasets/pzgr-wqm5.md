# Energy Prices, Dollars per Million Btu: Beginning 1970

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-prices-dollars-per-million-btu-beginning-1970) |
| Metadata | [Link](https://data.ny.gov/api/views/pzgr-wqm5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pzgr-wqm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pzgr-wqm5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pzgr-wqm5 |
| Name | Energy Prices, Dollars per Million Btu: Beginning 1970 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | energy prices, prices by sector, nominal prices, real prices |
| Created | 2013-03-01T06:04:40Z |
| Publication Date | 2016-11-04T22:06:23Z |

## Description

New York Energy Prices presents retail energy price data.  Energy prices are provided by fuel type in nominal dollars per million Btu for the residential, commercial, industrial, and transportation sectors.  This section includes a column in the price table displaying gross domestic product (GDP) price deflators for converting nominal (current year) dollars to constant (real) dollars.  To convert nominal to constant dollars, divide the nominal energy price by the GDP price deflator for that particular year.  Historical petroleum, electricity, coal, and natural gas prices were compiled primarily from the Energy Information Administration.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | numeric metric | gdp_deflator   | GDP Deflator   | number    | number      |
| Yes      | series tag     | sector         | Sector         | text      | text        |
| Yes      | numeric metric | coal           | Coal           | money     | money       |
| Yes      | numeric metric | distillate     | Distillate     | money     | money       |
| Yes      | numeric metric | residual       | Residual       | money     | money       |
| Yes      | numeric metric | kerosene       | Kerosene       | money     | money       |
| Yes      | numeric metric | propane        | Propane        | money     | money       |
| Yes      | numeric metric | natural_gas    | Natural Gas    | money     | money       |
| Yes      | numeric metric | electricity    | Electricity    | money     | money       |
| Yes      | numeric metric | wood           | Wood           | money     | money       |
| Yes      | numeric metric | motor_gasoline | Motor Gasoline | money     | money       |
| Yes      | numeric metric | jet_fuel       | Jet Fuel       | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pzgr-wqm5 d:2014-01-01T00:00:00.000Z t:sector=Commercial m:kerosene=29.84 m:propane=25.07 m:gdp_deflator=1 m:distillate=21.77 m:residual=14.75 m:electricity=47.25 m:natural_gas=8.05

series e:pzgr-wqm5 d:2014-01-01T00:00:00.000Z t:sector=Industrial m:kerosene=24.64 m:propane=31.04 m:coal=4.24 m:gdp_deflator=1 m:distillate=22.74 m:residual=14.75 m:electricity=19.28 m:natural_gas=7.88

series e:pzgr-wqm5 d:2014-01-01T00:00:00.000Z t:sector=Residential m:kerosene=29.84 m:wood=9.71 m:propane=37.01 m:gdp_deflator=1 m:distillate=27.54 m:electricity=58.83 m:natural_gas=12.15
```

## Meta Commands

```ls
metric m:gdp_deflator p:double l:"GDP Deflator" t:dataTypeName=number

metric m:coal p:double l:Coal d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:distillate p:double l:Distillate d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:residual p:double l:Residual d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:kerosene p:double l:Kerosene d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:propane p:double l:Propane d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:natural_gas p:double l:"Natural Gas" d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:electricity p:double l:Electricity d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:wood p:double l:Wood d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:motor_gasoline p:double l:"Motor Gasoline" d:"Dollars per million British thermal units" t:dataTypeName=money

metric m:jet_fuel p:double l:"Jet Fuel" d:"Dollars per million British thermal units" t:dataTypeName=money

entity e:pzgr-wqm5 l:"Energy Prices, Dollars per Million Btu: Beginning 1970" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/pzgr-wqm5

property e:pzgr-wqm5 t:meta.view v:id=pzgr-wqm5 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Energy Prices, Dollars per Million Btu: Beginning 1970" v:attribution="New York State Energy Research and Development Authority"

property e:pzgr-wqm5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pzgr-wqm5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pzgr-wqm5 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | gdp_deflator | sector         | coal | distillate | residual | kerosene | propane | natural_gas | electricity | wood | motor_gasoline | jet_fuel | 
| ==== | ============ | ============== | ==== | ========== | ======== | ======== | ======= | =========== | =========== | ==== | ============== | ======== | 
| 2014 | 1            | Commercial     |      | 21.77      | 14.75    | 29.84    | 25.07   | 8.05        | 47.25       |      |                |          | 
| 2014 | 1            | Industrial     | 4.24 | 22.74      | 14.75    | 24.64    | 31.04   | 7.88        | 19.28       |      |                |          | 
| 2014 | 1            | Residential    |      | 27.54      |          | 29.84    | 37.01   | 12.15       | 58.83       | 9.71 |                |          | 
| 2014 | 1            | Transportation |      | 26.93      | 13.19    |          |         |             | 40.49       |      | 28.36          | 20.61    | 
| 2013 | 0.9840       | Commercial     |      | 25.01      | 16.84    | 29.68    | 23.79   | 7.73        | 45.00       |      |                |          | 
| 2013 | 0.9840       | Industrial     | 4.37 | 24.15      | 16.84    | 26.03    | 29.33   | 7.19        | 19.30       |      |                |          | 
| 2013 | 0.9840       | Residential    |      | 28.22      |          | 29.68    | 34.86   | 12.07       | 55.08       | 9.96 |                |          | 
| 2013 | 0.9840       | Transportation |      | 28.36      | 15.52    |          |         |             | 40.01       |      | 29.42          | 22.15    | 
| 2012 | 0.9698       | Commercial     |      | 25.77      | 18.36    | 29.62    | 24.14   | 7.60        | 44.13       |      |                |          | 
| 2012 | 0.9698       | Industrial     | 4.73 | 24.86      | 18.36    | 25.67    | 29.90   | 6.70        | 19.62       |      |                |          | 
```