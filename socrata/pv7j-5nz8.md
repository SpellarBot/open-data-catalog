# Electricity Sales By Sector, GWh: Beginning 1980

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electricity-sales-by-sector-gwh-beginning-1980) |
| Metadata | [Link](https://data.ny.gov/api/views/pv7j-5nz8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pv7j-5nz8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pv7j-5nz8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pv7j-5nz8 |
| Name | Electricity Sales By Sector, GWh: Beginning 1980 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | electricity, electric generation, electricity sales, renewable |
| Created | 2013-02-21T14:40:50Z |
| Publication Date | 2016-11-04T22:02:29Z |

## Description

New York Electricity Sales dataset provides data on total electricity requirements for New York State.  Electricity sales to ultimate consumers are provided and are broken down by sector (Residential/Commercial/Industrial/Transportation) in GWh.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | numeric metric | residential    | Residential    | number    | number      |
| Yes      | numeric metric | commercial     | Commercial     | number    | number      |
| Yes      | numeric metric | industrial     | Industrial     | number    | number      |
| Yes      | numeric metric | transportation | Transportation | number    | number      |
| Yes      | numeric metric | total          | Total          | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pv7j-5nz8 d:2014-01-01T00:00:00.000Z m:total=147372 m:industrial=18003 m:residential=49975 m:transportation=2853 m:commercial=76541

series e:pv7j-5nz8 d:2013-01-01T00:00:00.000Z m:total=147895 m:industrial=17911 m:residential=50778 m:transportation=2864 m:commercial=76342

series e:pv7j-5nz8 d:2012-01-01T00:00:00.000Z m:total=143163 m:industrial=13705 m:residential=50692 m:transportation=2748 m:commercial=76018
```

## Meta Commands

```ls
metric m:residential p:integer l:Residential d:GWh t:dataTypeName=number

metric m:commercial p:integer l:Commercial d:GWh t:dataTypeName=number

metric m:industrial p:integer l:Industrial d:GWh t:dataTypeName=number

metric m:transportation p:integer l:Transportation d:GWh t:dataTypeName=number

metric m:total p:integer l:Total d:GWh t:dataTypeName=number

entity e:pv7j-5nz8 l:"Electricity Sales By Sector, GWh: Beginning 1980" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/pv7j-5nz8

property e:pv7j-5nz8 t:meta.view v:id=pv7j-5nz8 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-statistics.aspx v:averageRating=0 v:name="Electricity Sales By Sector, GWh: Beginning 1980" v:attribution="New York State Energy Research and Development Authority"

property e:pv7j-5nz8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pv7j-5nz8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pv7j-5nz8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | residential | commercial | industrial | transportation | total  | 
| ==== | =========== | ========== | ========== | ============== | ====== | 
| 2014 | 49975       | 76541      | 18003      | 2853           | 147372 | 
| 2013 | 50778       | 76342      | 17911      | 2864           | 147895 | 
| 2012 | 50692       | 76018      | 13705      | 2748           | 143163 | 
| 2011 | 51240       | 76406      | 13420      | 2981           | 144047 | 
| 2010 | 50946       | 77276      | 13480      | 2922           | 144624 | 
| 2009 | 48246       | 75347      | 13417      | 3025           | 140034 | 
| 2008 | 49034       | 77416      | 14685      | 2918           | 144053 | 
| 2007 | 50241       | 74326      | 20213      | 3397           | 148178 | 
| 2006 | 48427       | 76029      | 14976      | 2806           | 142238 | 
| 2005 | 50533       | 76822      | 19947      | 2846           | 150148 | 
```