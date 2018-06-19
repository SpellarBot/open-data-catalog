# Renewable Energy Generated In Maryland

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/renewable-energy-generated-in-maryland-8f51e) |
| Metadata | [Link](https://data.maryland.gov/api/views/79zg-5xwz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/79zg-5xwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/79zg-5xwz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 79zg-5xwz |
| Name | Renewable Energy Generated In Maryland |
| Attribution | StateStat |
| Category | Energy and Environment |
| Tags | energy, renewable, wind, solar |
| Created | 2013-02-20T22:28:18Z |
| Publication Date | 2015-09-09T13:37:41Z |

## Description

This data set describes the amount of energy generated annually by renewable sources in Maryland in megawatt hours (MWh).  In addition, there is a column which describes the percent of all energy generated in Maryland that came from renewable sources each year.

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                                | Data Type | Render Type |
| ======== | ============== | ============================================== | =================================================== | ========= | =========== |
| Yes      | time           | year                                           | Year                                                | number    | text        |
| Yes      | numeric metric | landfill_gas                                   | Landfill Gas                                        | number    | number      |
| Yes      | numeric metric | black_liquor                                   | Black Liquor                                        | number    | number      |
| Yes      | numeric metric | blast_furnace_gas                              | Blast Furnace Gas                                   | number    | number      |
| Yes      | numeric metric | hydro                                          | Hydro                                               | number    | number      |
| Yes      | numeric metric | waste_to_energy                                | Waste to Energy                                     | number    | number      |
| Yes      | numeric metric | land_based_wind                                | Land-Based Wind                                     | number    | number      |
| Yes      | numeric metric | solar                                          | Solar                                               | number    | number      |
| Yes      | numeric metric | animal_litter                                  | Animal Litter                                       | number    | number      |
| Yes      | numeric metric | offshore_wind                                  | Offshore Wind                                       | number    | number      |
| Yes      | numeric metric | percent_generation                             | Percent Generation                                  | percent   | percent     |
| Yes      | numeric metric | total_electricity_generation_renewable_sources | Electricity Generation from Renewable Sources (MWh) | number    | number      |
| Yes      | numeric metric | total_electricity_generation_all_sources       | Electricity Generation from All Sources (MWh)       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:79zg-5xwz d:2008-01-01T00:00:00.000Z m:land_based_wind=0 m:waste_to_energy=713035 m:offshore_wind=0 m:animal_litter=0 m:total_electricity_generation_renewable_sources=3111947 m:landfill_gas=32534 m:black_liquor=151297 m:blast_furnace_gas=337823 m:total_electricity_generation_all_sources=47360953 m:solar=281 m:percent_generation=6.6 m:hydro=1876977

series e:79zg-5xwz d:2007-01-01T00:00:00.000Z m:land_based_wind=0 m:waste_to_energy=697167 m:offshore_wind=0 m:animal_litter=0 m:total_electricity_generation_renewable_sources=2923693 m:landfill_gas=44213 m:black_liquor=146016 m:blast_furnace_gas=377560 m:total_electricity_generation_all_sources=50197924 m:solar=320 m:percent_generation=5.8 m:hydro=1658417

series e:79zg-5xwz d:2009-01-01T00:00:00.000Z m:land_based_wind=2 m:waste_to_energy=639306 m:offshore_wind=0 m:animal_litter=0 m:total_electricity_generation_renewable_sources=2960011 m:landfill_gas=50876 m:black_liquor=128806 m:blast_furnace_gas=269182 m:total_electricity_generation_all_sources=43774832 m:solar=3524 m:percent_generation=6.8 m:hydro=1868315
```

## Meta Commands

```ls
metric m:landfill_gas p:integer l:"Landfill Gas" t:dataTypeName=number

metric m:black_liquor p:integer l:"Black Liquor" t:dataTypeName=number

metric m:blast_furnace_gas p:integer l:"Blast Furnace Gas" t:dataTypeName=number

metric m:hydro p:integer l:Hydro t:dataTypeName=number

metric m:waste_to_energy p:integer l:"Waste to Energy" t:dataTypeName=number

metric m:land_based_wind p:integer l:"Land-Based Wind" t:dataTypeName=number

metric m:solar p:integer l:Solar t:dataTypeName=number

metric m:animal_litter p:integer l:"Animal Litter" t:dataTypeName=number

metric m:offshore_wind p:integer l:"Offshore Wind" t:dataTypeName=number

metric m:percent_generation p:float l:"Percent Generation" t:dataTypeName=percent

metric m:total_electricity_generation_renewable_sources p:integer l:"Electricity Generation from Renewable Sources (MWh)" t:dataTypeName=number

metric m:total_electricity_generation_all_sources p:integer l:"Electricity Generation from All Sources (MWh)" t:dataTypeName=number

entity e:79zg-5xwz l:"Renewable Energy Generated In Maryland" t:attribution=StateStat t:url=https://data.maryland.gov/api/views/79zg-5xwz

property e:79zg-5xwz t:meta.view v:id=79zg-5xwz v:category="Energy and Environment" v:attributionLink=http://www.statestat.maryland.gov/ v:averageRating=0 v:name="Renewable Energy Generated In Maryland" v:attribution=StateStat

property e:79zg-5xwz t:meta.view.license v:name="Public Domain"

property e:79zg-5xwz t:meta.view.owner v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:displayName="Kristen Ahearn"

property e:79zg-5xwz t:meta.view.tableauthor v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:roleName=publisher v:displayName="Kristen Ahearn"
```

## Top Records

```ls
| year | landfill_gas | black_liquor | blast_furnace_gas | hydro   | waste_to_energy | land_based_wind | solar  | animal_litter | offshore_wind | percent_generation | total_electricity_generation_renewable_sources | total_electricity_generation_all_sources | 
| ==== | ============ | ============ | ================= | ======= | =============== | =============== | ====== | ============= | ============= | ================== | ============================================== | ======================================== | 
| 2008 | 32534        | 151297       | 337823            | 1876977 | 713035          | 0               | 281    | 0             | 0             | 6.6                | 3111947                                        | 47360953                                 | 
| 2007 | 44213        | 146016       | 377560            | 1658417 | 697167          | 0               | 320    | 0             | 0             | 5.8                | 2923693                                        | 50197924                                 | 
| 2009 | 50876        | 128806       | 269182            | 1868315 | 639306          | 2               | 3524   | 0             | 0             | 6.8                | 2960011                                        | 43774832                                 | 
| 2010 | 48926        | 137402       | 214727            | 1667971 | 674401          | 14927           | 12336  | 0             | 0             | 6.4                | 2770690                                        | 43607264                                 | 
| 2011 | 63419        | 128371       | 154641            | 2553489 | 663920          | 311774          | 34459  | 0             | 0             | 9.3                | 3910073                                        | 41913287                                 | 
| 2012 | 57453        | 119556       | 110444            | 1656935 | 662596          | 299525          | 83567  | 0             | 0             | 7.9                | 2990076                                        | 37809743                                 | 
| 2013 | 102600       | 104499       | 0                 | 1531000 | 677530          | 322971          | 190469 | 0             | 0             | 8.3                | 2929069                                        | 35487000                                 | 
| 2014 | 96336        | 113508       | 0                 | 1665868 | 700539          | 320380          | 241831 | 0             | 0             | 8.3                | 3138462                                        | 38015159                                 | 
```