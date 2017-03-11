# Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/djfn-trk4/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/greenhouse-gas-emissions-from-fuel-combustion-million-metric-tons-beginning-1990)
* [Metadata URL](https://data.ny.gov/api/views/djfn-trk4)
* Id = djfn-trk4
* Name = Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990
* Attribution = New York State Energy Research and Development Authority
* [Attribution Link](http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx)
* Category = Energy & Environment
* Tags = [greenhouse gas, fuel combustion, co2, energy]
* Created = 2013-02-22T16:48:37Z
* Publication Date = 2016-11-04T22:00:51Z
* Rows Updated = 2016-11-04T22:00:46Z

## Description

The Greenhouse Gas Emissions Inventory details the estimated New York State emissions releases from fuel combustion.  The dataset includes emissions for each year from 1990 through the present (currently 2010), broken down by the sector (Residential/Commercial/Industrial, Electricity generation, and Transportation).  The dataset also includes a fuel type breakdown, also by sector, for the current year.

## Columns

```ls
| Name                       | Field Name                 | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ========================== | ========= | =========== | ============== | ======== | 
| Year                       | year                       | number    | number      | time           | Yes      | 
| Residential Total          | residential_total          | number    | number      | numeric metric | Yes      | 
| Commercial Total           | commercial_total           | number    | number      | numeric metric | Yes      | 
| Industrial Total           | industrial_total           | number    | number      | numeric metric | Yes      | 
| Transportation Total       | transportation_total       | number    | number      | numeric metric | Yes      | 
| Electric Generation Total  | electric_generation_total  | number    | number      | numeric metric | Yes      | 
| Net Imports of Electricity | net_imports_of_electricity | number    | number      | numeric metric | Yes      | 
| Year Total                 | yeartotal                  | number    | number      |                | No       | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = yeartotal
Annotation Fields = 
```

## Data Commands

```ls
series e:djfn-trk4 d:2014-01-01T00:00:00.000Z m:commercial_total=22 m:residential_total=35.5 m:transportation_total=74 m:industrial_total=11 m:net_imports_of_electricity=8 m:electric_generation_total=30.4

series e:djfn-trk4 d:2013-01-01T00:00:00.000Z m:commercial_total=22.4 m:residential_total=32.3 m:transportation_total=72.6 m:industrial_total=10.4 m:net_imports_of_electricity=9.3 m:electric_generation_total=29.9

series e:djfn-trk4 d:2012-01-01T00:00:00.000Z m:commercial_total=20.9 m:residential_total=30.4 m:transportation_total=72.2 m:industrial_total=10.7 m:net_imports_of_electricity=9.5 m:electric_generation_total=32.2
```

## Meta Commands

```ls
metric m:residential_total l:"Residential Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:commercial_total l:"Commercial Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:industrial_total l:"Industrial Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:transportation_total l:"Transportation Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:electric_generation_total l:"Electric Generation Total" d:"Million Metric Tons" t:dataTypeName=number

metric m:net_imports_of_electricity l:"Net Imports of Electricity" d:"Million Metric Tons" t:dataTypeName=number

entity e:djfn-trk4 l:"Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/djfn-trk4

property e:djfn-trk4 t:meta.view d:2017-03-07T17:43:57.272Z v:id=djfn-trk4 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Greenhouse Gas Emissions From Fuel Combustion, Million Metric Tons: Beginning 1990" v:attribution="New York State Energy Research and Development Authority"

property e:djfn-trk4 t:meta.view.owner d:2017-03-07T17:43:57.272Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:djfn-trk4 t:meta.view.tableauthor d:2017-03-07T17:43:57.272Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:djfn-trk4 t:meta.view.metadata.custom_fields.common_core d:2017-03-07T17:43:57.272Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```