# Electricity Sales By Sector, TBtu: Beginning 1980

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electricity-sales-by-sector-tbtu-beginning-1980) |
| Metadata | [Link](https://data.ny.gov/api/views/8m9z-nvih) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/8m9z-nvih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/8m9z-nvih/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 8m9z-nvih |
| Name | Electricity Sales By Sector, TBtu: Beginning 1980 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | electricity, electric generation, electricity sales, renewable |
| Created | 2013-02-21T14:36:13Z |
| Publication Date | 2016-11-04T22:01:48Z |

## Description

New York Electricity Sales dataset provides data on total electricity requirements for New York State.  Electricity sales to ultimate consumers are provided and are broken down by sector (Residential/Commercial/Industrial/Transportation) in TBtu.

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
series e:8m9z-nvih d:2014-01-01T00:00:00.000Z m:total=502.8 m:industrial=61.4 m:residential=170.5 m:transportation=9.7 m:commercial=261.2

series e:8m9z-nvih d:2013-01-01T00:00:00.000Z m:total=504.6 m:industrial=61.1 m:residential=173.3 m:transportation=9.8 m:commercial=260.5

series e:8m9z-nvih d:2012-01-01T00:00:00.000Z m:total=488.5 m:industrial=46.8 m:residential=173 m:transportation=9.4 m:commercial=259.4
```

## Meta Commands

```ls
metric m:residential p:float l:Residential d:TBtu t:dataTypeName=number

metric m:commercial p:float l:Commercial d:TBtu t:dataTypeName=number

metric m:industrial p:float l:Industrial d:TBtu t:dataTypeName=number

metric m:transportation p:float l:Transportation d:TBtu t:dataTypeName=number

metric m:total p:float l:Total d:TBtu t:dataTypeName=number

entity e:8m9z-nvih l:"Electricity Sales By Sector, TBtu: Beginning 1980" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/8m9z-nvih

property e:8m9z-nvih t:meta.view v:id=8m9z-nvih v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Electricity Sales By Sector, TBtu: Beginning 1980" v:attribution="New York State Energy Research and Development Authority"

property e:8m9z-nvih t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:8m9z-nvih t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:8m9z-nvih t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | residential | commercial | industrial | transportation | total | 
| ==== | =========== | ========== | ========== | ============== | ===== | 
| 2014 | 170.5       | 261.2      | 61.4       | 9.7            | 502.8 | 
| 2013 | 173.3       | 260.5      | 61.1       | 9.8            | 504.6 | 
| 2012 | 173.0       | 259.4      | 46.8       | 9.4            | 488.5 | 
| 2011 | 174.8       | 260.7      | 45.8       | 10.2           | 491.5 | 
| 2010 | 173.8       | 263.7      | 46.0       | 10.0           | 493.5 | 
| 2009 | 164.6       | 257.1      | 45.8       | 10.3           | 477.8 | 
| 2008 | 167.3       | 264.1      | 50.1       | 10.0           | 491.5 | 
| 2007 | 171.4       | 253.6      | 69.0       | 11.6           | 505.6 | 
| 2006 | 165.2       | 259.4      | 51.1       | 9.6            | 485.3 | 
| 2005 | 172.4       | 262.1      | 68.1       | 9.7            | 512.3 | 
```