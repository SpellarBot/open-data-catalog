# Hawaii Renewable Energy Generation By Resource (Source: Hawaii Public Utilities Commission)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-renewable-energy-generation-by-resource-source-hawaii-public-utilities-commission-d758f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ezj8-myxp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ezj8-myxp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ezj8-myxp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ezj8-myxp |
| Name | Hawaii Renewable Energy Generation By Resource (Source: Hawaii Public Utilities Commission) |
| Created | 2012-11-20T19:40:31Z |
| Publication Date | 2016-04-11T20:53:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | biomass          | Biomass          | number    | number      |
| Yes      | numeric metric | geothermal       | Geothermal       | number    | number      |
| Yes      | numeric metric | commercial_solar | Commercial Solar | number    | number      |
| Yes      | numeric metric | hydro            | Hydro            | number    | number      |
| Yes      | numeric metric | wind             | Wind             | number    | number      |
| Yes      | numeric metric | biofuels         | Biofuels         | number    | number      |
| Yes      | numeric metric | distributed_pv   | Distributed PV   | number    | number      |
| Yes      | numeric metric | total            | Total Renewables | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ezj8-myxp d:2009-01-01T00:00:00.000Z m:total=964600 m:wind=250355 m:biomass=402303 m:commercial_solar=1390 m:geothermal=167591 m:biofuels=4877 m:hydro=103065 m:distributed_pv=35020

series e:ezj8-myxp d:2010-01-01T00:00:00.000Z m:total=950741 m:wind=261206 m:biomass=358852 m:commercial_solar=1787 m:geothermal=201587 m:biofuels=3160 m:hydro=69809 m:distributed_pv=54339

series e:ezj8-myxp d:2011-01-01T00:00:00.000Z m:total=1186007 m:wind=344376 m:biomass=365266 m:commercial_solar=3637 m:geothermal=232906 m:biofuels=59254 m:hydro=90423 m:distributed_pv=90144
```

## Meta Commands

```ls
metric m:biomass p:integer l:Biomass t:dataTypeName=number

metric m:geothermal p:integer l:Geothermal t:dataTypeName=number

metric m:commercial_solar p:integer l:"Commercial Solar" t:dataTypeName=number

metric m:hydro p:integer l:Hydro t:dataTypeName=number

metric m:wind p:integer l:Wind t:dataTypeName=number

metric m:biofuels p:integer l:Biofuels t:dataTypeName=number

metric m:distributed_pv p:integer l:"Distributed PV" t:dataTypeName=number

metric m:total p:integer l:"Total Renewables" t:dataTypeName=number

entity e:ezj8-myxp l:"Hawaii Renewable Energy Generation By Resource (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/ezj8-myxp

property e:ezj8-myxp t:meta.view v:id=ezj8-myxp v:averageRating=0 v:name="Hawaii Renewable Energy Generation By Resource (Source: Hawaii Public Utilities Commission)"

property e:ezj8-myxp t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:ezj8-myxp t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| year | biomass | geothermal | commercial_solar | hydro  | wind   | biofuels | distributed_pv | total   | 
| ==== | ======= | ========== | ================ | ====== | ====== | ======== | ============== | ======= | 
| 2009 | 402303  | 167591     | 1390             | 103065 | 250355 | 4877     | 35020          | 964600  | 
| 2010 | 358852  | 201587     | 1787             | 69809  | 261206 | 3160     | 54339          | 950741  | 
| 2011 | 365266  | 232906     | 3637             | 90423  | 344376 | 59254    | 90144          | 1186007 | 
| 2012 | 341790  | 266234     | 11524            | 103978 | 388256 | 22607    | 189563         | 1323953 | 
| 2013 | 415691  | 281417     | 35752            | 86002  | 503548 | 29789    | 355636         | 1707836 | 
| 2014 | 433164  | 255027     | 68356            | 85446  | 577867 | 37093    | 531810         | 1988764 | 
| 2015 | 422181  | 230495     | 91842            | 106764 | 612782 | 53412    | 681325         | 2198801 | 
```