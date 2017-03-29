# Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/greenhouse-gas-emissions-from-fuel-combustion-million-metric-tons-beginning-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/djfn-trk4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/djfn-trk4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/djfn-trk4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | djfn-trk4 |
| Name | Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | greenhouse gas, fuel combustion, co2, energy |
| Created | 2013-02-22T16:48:37Z |
| Publication Date | 2016-11-04T22:00:51Z |

## Description

The Greenhouse Gas Emissions Inventory details the estimated New York State emissions releases from fuel combustion.  The dataset includes emissions for each year from 1990 through the present (currently 2010), broken down by the sector (Residential/Commercial/Industrial, Electricity generation, and Transportation).  The dataset also includes a fuel type breakdown, also by sector, for the current year.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | numeric metric | residential_total          | Residential Total          | number    | number      |
| Yes      | numeric metric | commercial_total           | Commercial Total           | number    | number      |
| Yes      | numeric metric | industrial_total           | Industrial Total           | number    | number      |
| Yes      | numeric metric | transportation_total       | Transportation Total       | number    | number      |
| Yes      | numeric metric | electric_generation_total  | Electric Generation Total  | number    | number      |
| Yes      | numeric metric | net_imports_of_electricity | Net Imports of Electricity | number    | number      |
| Yes      | numeric metric | yeartotal                  | Year Total                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:djfn-trk4 d:2014-01-01T00:00:00.000Z m:yeartotal=181 m:commercial_total=22 m:residential_total=35.5 m:transportation_total=74 m:industrial_total=11 m:net_imports_of_electricity=8 m:electric_generation_total=30.4

series e:djfn-trk4 d:2013-01-01T00:00:00.000Z m:yeartotal=177 m:commercial_total=22.4 m:residential_total=32.3 m:transportation_total=72.6 m:industrial_total=10.4 m:net_imports_of_electricity=9.3 m:electric_generation_total=29.9

series e:djfn-trk4 d:2012-01-01T00:00:00.000Z m:yeartotal=175.9 m:commercial_total=20.9 m:residential_total=30.4 m:transportation_total=72.2 m:industrial_total=10.7 m:net_imports_of_electricity=9.5 m:electric_generation_total=32.2
```

## Meta Commands

```ls
metric m:residential_total p:float l:"Residential Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:commercial_total p:float l:"Commercial Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:industrial_total p:float l:"Industrial Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:transportation_total p:float l:"Transportation Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:electric_generation_total p:float l:"Electric Generation Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:net_imports_of_electricity p:float l:"Net Imports of Electricity" d:"Million Metric Tons" t:dataTypeName=number

metric m:yeartotal p:float l:"Year Total" d:"Million Metric tons" t:dataTypeName=number

entity e:djfn-trk4 l:"Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/djfn-trk4

property e:djfn-trk4 t:meta.view v:id=djfn-trk4 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990" v:attribution="New York State Energy Research and Development Authority"

property e:djfn-trk4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:djfn-trk4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:djfn-trk4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | residential_total | commercial_total | industrial_total | transportation_total | electric_generation_total | net_imports_of_electricity | yeartotal | 
| ==== | ================= | ================ | ================ | ==================== | ========================= | ========================== | ========= | 
| 2014 | 35.5              | 22.0             | 11.0             | 74.0                 | 30.4                      | 8.0                        | 181.0     | 
| 2013 | 32.3              | 22.4             | 10.4             | 72.6                 | 29.9                      | 9.3                        | 177.0     | 
| 2012 | 30.4              | 20.9             | 10.7             | 72.2                 | 32.2                      | 9.5                        | 175.9     | 
| 2011 | 31.1              | 24.2             | 11.1             | 70.1                 | 33.4                      | 9.1                        | 178.9     | 
| 2010 | 31.7              | 24.2             | 10.3             | 74.9                 | 37.3                      | 9.6                        | 187.9     | 
| 2009 | 32.9              | 25.1             | 11.5             | 77.7                 | 34.0                      | 9.0                        | 190.2     | 
| 2008 | 35.6              | 25.9             | 13.8             | 80.3                 | 42.5                      | 8.6                        | 206.7     | 
| 2007 | 36.9              | 26.7             | 14.1             | 82.9                 | 48.8                      | 7.5                        | 216.8     | 
| 2006 | 33.1              | 25.4             | 14.6             | 84.8                 | 45.9                      | 6.7                        | 210.6     | 
| 2005 | 39.8              | 28.6             | 15.0             | 83.7                 | 53.6                      | 6.6                        | 227.3     | 
```