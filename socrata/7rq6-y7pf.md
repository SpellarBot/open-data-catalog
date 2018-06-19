# Table 17.05 PRIMARY ENERGY CONSUMPTION, BY SOURCE 1993 TO 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-17-05-primary-energy-consumption-by-source-1993-to-2012) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7rq6-y7pf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7rq6-y7pf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7rq6-y7pf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7rq6-y7pf |
| Name | Table 17.05 PRIMARY ENERGY CONSUMPTION, BY SOURCE 1993 TO 2013 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-27T23:56:27Z |
| Publication Date | 2015-10-21T19:22:12Z |

## Description

Source: Hawaii State Department of Business, Economic Development & Tourism, Strategic Industries Division, Energy Planning & Policy Branch, records.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | total       | Total       | number    | number      |
| Yes      | numeric metric | petroleum   | Petroleum   | number    | number      |
| Yes      | numeric metric | biomass     | Biomass     | number    | number      |
| Yes      | numeric metric | solar       | Solar       | number    | number      |
| Yes      | numeric metric | hydro       | Hydro       | number    | number      |
| Yes      | numeric metric | coal        | Coal        | number    | number      |
| Yes      | numeric metric | wind        | Wind        | number    | number      |
| Yes      | numeric metric | geothermal  | Geothermal  | number    | number      |
| Yes      | numeric metric | renewable   | Renewable   | number    | number      |
| Yes      | numeric metric | natural_gas | Natural Gas | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7rq6-y7pf d:1993-01-01T00:00:00.000Z m:total=283.089 m:wind=0.226 m:biomass=24.388 m:coal=15.575 m:geothermal=1.57 m:petroleum=239.665 m:renewable=27.85 m:solar=1.086 m:hydro=0.58 m:natural_gas=0

series e:7rq6-y7pf d:1994-01-01T00:00:00.000Z m:total=299.395 m:wind=0.21 m:biomass=20.724 m:coal=15.74 m:geothermal=1.912 m:petroleum=258.227 m:renewable=25.427 m:solar=1.143 m:hydro=1.438 m:natural_gas=0

series e:7rq6-y7pf d:1995-01-01T00:00:00.000Z m:total=297.066 m:wind=0.21 m:biomass=19.803 m:coal=19.914 m:geothermal=2.419 m:petroleum=252.516 m:renewable=24.637 m:solar=1.196 m:hydro=1.009 m:natural_gas=0
```

## Meta Commands

```ls
metric m:total p:float l:Total t:dataTypeName=number

metric m:petroleum p:float l:Petroleum t:dataTypeName=number

metric m:biomass p:float l:Biomass t:dataTypeName=number

metric m:solar p:float l:Solar t:dataTypeName=number

metric m:hydro p:float l:Hydro t:dataTypeName=number

metric m:coal p:float l:Coal t:dataTypeName=number

metric m:wind p:float l:Wind t:dataTypeName=number

metric m:geothermal p:float l:Geothermal t:dataTypeName=number

metric m:renewable p:float l:Renewable t:dataTypeName=number

metric m:natural_gas p:float l:"Natural Gas" t:dataTypeName=number

entity e:7rq6-y7pf l:"Table 17.05 PRIMARY ENERGY CONSUMPTION, BY SOURCE  1993 TO 2013" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/7rq6-y7pf

property e:7rq6-y7pf t:meta.view v:id=7rq6-y7pf v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/economic/databook v:averageRating=0 v:name="Table 17.05 PRIMARY ENERGY CONSUMPTION, BY SOURCE  1993 TO 2013" v:attribution="Department of Economic Development and Tourism"

property e:7rq6-y7pf t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:7rq6-y7pf t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:7rq6-y7pf t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | total    | petroleum | biomass | solar  | hydro  | coal    | wind   | geothermal | renewable | natural_gas | 
| ==== | ======== | ========= | ======= | ====== | ====== | ======= | ====== | ========== | ========= | =========== | 
| 1993 | 283.0890 | 239.6650  | 24.3880 | 1.0860 | 0.5800 | 15.5750 | 0.2260 | 1.5700     | 27.8500   | 0.0000      | 
| 1994 | 299.3950 | 258.2270  | 20.7240 | 1.1430 | 1.4380 | 15.7400 | 0.2100 | 1.9120     | 25.4270   | 0.0000      | 
| 1995 | 297.0660 | 252.5160  | 19.8030 | 1.1960 | 1.0090 | 19.9140 | 0.2100 | 2.4190     | 24.6370   | 0.0000      | 
| 1996 | 283.3010 | 238.8090  | 19.0660 | 1.2440 | 1.0760 | 20.3710 | 0.2330 | 2.5020     | 24.1210   | 0.0000      | 
| 1997 | 273.614  | 230.561   | 17.4330 | 1.2590 | 1.1780 | 20.5130 | 0.1640 | 2.5060     | 22.5400   | 0.0000      | 
| 1998 | 273.56   | 233.636   | 16.5480 | 1.3020 | 1.2370 | 18.2230 | 0.1970 | 2.4180     | 21.701    | 0.0000      | 
| 1999 | 269.502  | 229.99    | 16.9810 | 1.3350 | 1.1750 | 17.6910 | 0.1690 | 2.1620     | 21.821    | 0.0000      | 
| 2000 | 273.495  | 235.315   | 15.1940 | 1.3470 | 1.0550 | 17.6530 | 0.1730 | 2.6810     | 20.451    | 0.0760      | 
| 2001 | 270.325  | 239.948   | 7.9470  | 1.3160 | 1.0410 | 17.7740 | 0.0220 | 2.1430     | 12.469    | 0.1340      | 
| 2002 | 284.9    | 257.593   | 7.4800  | 1.3370 | 0.9670 | 16.6180 | 0.0160 | 0.7480     | 10.55     | 0.1400      | 
```