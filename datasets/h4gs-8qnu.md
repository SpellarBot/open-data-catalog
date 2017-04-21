# Electric Generation By Fuel Type, GWh: Beginning 1960

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electric-generation-by-fuel-type-gwh-beginning-1960) |
| Metadata | [Link](https://data.ny.gov/api/views/h4gs-8qnu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/h4gs-8qnu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/h4gs-8qnu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | h4gs-8qnu |
| Name | Electric Generation By Fuel Type, GWh: Beginning 1960 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | electricity, electric generation, renewable |
| Created | 2013-02-21T14:43:19Z |
| Publication Date | 2016-11-04T22:03:48Z |

## Description

New York Electric Generation By Fuel Type, GWh dataset provides data on total electricity requirements and in-state generation for New York State in giga-watt hours. Sources of electricity include coal, natural gas, petroleum products, hydro, nuclear, waste, landfill gas, wood, wind, solar, and net imports of electricity.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | coal        | Coal        | number    | number      |
| Yes      | numeric metric | natural_gas | Natural Gas | number    | number      |
| Yes      | numeric metric | petroleum   | Petroleum   | number    | number      |
| Yes      | numeric metric | conv_hydro  | Conv. Hydro | number    | number      |
| Yes      | numeric metric | ps_hydro    | PS Hydro    | number    | number      |
| Yes      | numeric metric | nuclear     | Nuclear     | number    | number      |
| Yes      | numeric metric | net_imports | Net Imports | number    | number      |
| Yes      | numeric metric | other       | Other       | number    | number      |
| Yes      | numeric metric | waste       | Waste       | number    | number      |
| Yes      | numeric metric | lfg         | LFG         | number    | number      |
| Yes      | numeric metric | wood        | Wood        | number    | number      |
| Yes      | numeric metric | wind        | Wind        | number    | number      |
| Yes      | numeric metric | solar       | Solar       | number    | number      |
| Yes      | numeric metric | total       | Total       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h4gs-8qnu d:2014-01-01T00:00:00.000Z m:total=160059 m:waste=1866 m:wind=3986 m:other=3194 m:wood=539 m:petroleum=2136 m:solar=71 m:natural_gas=54380 m:lfg=789 m:net_imports=22103 m:nuclear=43041 m:conv_hydro=25974 m:coal=4325 m:ps_hydro=849

series e:h4gs-8qnu d:2013-01-01T00:00:00.000Z m:total=163514 m:waste=1799 m:wind=3539 m:other=3003 m:wood=377 m:petroleum=1007 m:solar=67 m:natural_gas=54354 m:lfg=828 m:net_imports=25694 m:nuclear=44756 m:conv_hydro=25631 m:coal=4697 m:ps_hydro=766

series e:h4gs-8qnu d:2012-01-01T00:00:00.000Z m:total=162840 m:waste=1897 m:wind=2992 m:other=2945 m:wood=311 m:petroleum=580 m:solar=53 m:natural_gas=59462 m:lfg=736 m:net_imports=26180 m:nuclear=40775 m:conv_hydro=24572 m:coal=4551 m:ps_hydro=731
```

## Meta Commands

```ls
metric m:coal p:integer l:Coal d:GWh t:dataTypeName=number

metric m:natural_gas p:integer l:"Natural Gas" d:GWh t:dataTypeName=number

metric m:petroleum p:integer l:Petroleum d:GWh t:dataTypeName=number

metric m:conv_hydro p:integer l:"Conv. Hydro" d:GWh t:dataTypeName=number

metric m:ps_hydro p:integer l:"PS Hydro" d:GWh t:dataTypeName=number

metric m:nuclear p:integer l:Nuclear d:GWh t:dataTypeName=number

metric m:net_imports p:integer l:"Net Imports" d:GWh t:dataTypeName=number

metric m:other p:integer l:Other d:GWh t:dataTypeName=number

metric m:waste p:integer l:Waste d:GWh t:dataTypeName=number

metric m:lfg p:integer l:LFG d:GWh t:dataTypeName=number

metric m:wood p:integer l:Wood d:GWh t:dataTypeName=number

metric m:wind p:integer l:Wind d:GWh t:dataTypeName=number

metric m:solar p:integer l:Solar d:GWh t:dataTypeName=number

metric m:total p:integer l:Total d:GWh t:dataTypeName=number

entity e:h4gs-8qnu l:"Electric Generation By Fuel Type, GWh: Beginning 1960" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/h4gs-8qnu

property e:h4gs-8qnu t:meta.view v:id=h4gs-8qnu v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/BusinessAreas/Energy-Data-and-Prices-Planning-and-Policy/Energy-Prices-Data-and-Reports/Energy-Statistics-and-Weather-Data/Energy-Statistics.aspx v:averageRating=0 v:name="Electric Generation By Fuel Type, GWh: Beginning 1960" v:attribution="New York State Energy Research and Development Authority"

property e:h4gs-8qnu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:h4gs-8qnu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:h4gs-8qnu t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | coal  | natural_gas | petroleum | conv_hydro | ps_hydro | nuclear | net_imports | other | waste | lfg | wood | wind | solar | total  | 
| ==== | ===== | =========== | ========= | ========== | ======== | ======= | =========== | ===== | ===== | === | ==== | ==== | ===== | ====== | 
| 2014 | 4325  | 54380       | 2136      | 25974      | 849      | 43041   | 22103       | 3194  | 1866  | 789 | 539  | 3986 | 71    | 160059 | 
| 2013 | 4697  | 54354       | 1007      | 25631      | 766      | 44756   | 25694       | 3003  | 1799  | 828 | 377  | 3539 | 67    | 163514 | 
| 2012 | 4551  | 59462       | 580       | 24572      | 731      | 40775   | 26180       | 2945  | 1897  | 736 | 311  | 2992 | 53    | 162840 | 
| 2011 | 9426  | 50805       | 1189      | 27634      | 721      | 42695   | 25201       | 2823  | 1878  | 735 | 210  | 2828 | 7     | 163329 | 
| 2010 | 13583 | 48916       | 2005      | 24214      | 889      | 41870   | 26517       | 2916  | 1893  | 708 | 315  | 2596 |       | 163505 | 
| 2009 | 12759 | 41780       | 2648      | 26420      | 1525     | 43485   | 25009       | 2888  | 1900  | 648 | 340  | 2266 |       | 158780 | 
| 2008 | 19154 | 43856       | 3745      | 25711      | 1790     | 43209   | 23899       | 2996  | 1903  | 533 | 560  | 1251 |       | 165612 | 
| 2007 | 21406 | 45634       | 8195      | 24184      | 1373     | 42453   | 20708       | 2555  | 1902  | 397 | 256  | 833  |       | 167341 | 
| 2006 | 20968 | 42134       | 6778      | 27110      | 1312     | 42224   | 18569       | 2488  | 1902  | 326 | 260  | 655  |       | 162238 | 
| 2005 | 20598 | 31873       | 24013     | 26204      | 1379     | 42443   | 18115       | 2481  | 1899  | 329 | 253  | 103  |       | 167208 | 
```