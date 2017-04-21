# Table 17.03 CONSUMPTION OF ENERGY BY END- USE SECTOR 1960 TO 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-17-03-consumption-of-energy-by-end-use-sector-1960-to-2011) |
| Metadata | [Link](https://data.hawaii.gov/api/views/usfi-mive) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/usfi-mive/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/usfi-mive/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | usfi-mive |
| Name | Table 17.03 CONSUMPTION OF ENERGY BY END- USE SECTOR 1960 TO 2012 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | energy |
| Created | 2012-08-27T23:49:29Z |
| Publication Date | 2015-10-21T19:26:47Z |

## Description

(Trillion btu)
* There is a discontinuity between 1988 and 1989 due to the expanded coverage of renewable energy sources?beginning?in?1989.										
* Beginning?in?1980,?adjusted?for?the?double-counting?of?supplemental?gaseous?fuels,?which?are included?in?both?natural?gas?and?the?other?fossil?fuels?from?which?they?are?mostly?derived,?but?should?be counted?only?once?in?net?energy?and?total.										
* Small amouts of solar thermal and photovoltaic energy consumed in the commercial sector cannot be separately identified and are included in residential consumption.  										
* From?1981?through?1992,?includes?fuel?ethanol?blended?into?motor gasoline?that?is?not?included?in?the?motor?gasoline?column.??										
* Beginning?in?1980,?adjusted?for?the?double-counting?of supplemental?gaseous?fuels,?which?are?included?in?both?natural?gas?and?the?other?fossil?fuels?from?which?they?are?mostly derived,?but?should?be counted?only?once?in?net?energy?and?total.										
     Source:  U.S. Department of Energy, Energy Information Administration, State Energy Data System (SEDS)										
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | numeric metric | residential    | Residential    | number    | number      |
| Yes      | numeric metric | commercial     | Commercial     | number    | number      |
| Yes      | numeric metric | industrial     | Industrial     | number    | number      |
| Yes      | numeric metric | transportation | Transportation | number    | number      |
| Yes      | numeric metric | electric_power | Electric power | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:usfi-mive d:1960-01-01T00:00:00.000Z m:industrial=20.6 m:residential=7.1 m:transportation=61.8 m:commercial=5.3 m:electric_power=17.6

series e:usfi-mive d:1961-01-01T00:00:00.000Z m:industrial=26.8 m:residential=7.3 m:transportation=74 m:commercial=5.6 m:electric_power=19.4

series e:usfi-mive d:1962-01-01T00:00:00.000Z m:industrial=28.7 m:residential=7.7 m:transportation=66.1 m:commercial=5.7 m:electric_power=21.4
```

## Meta Commands

```ls
metric m:residential p:float l:Residential t:dataTypeName=number

metric m:commercial p:float l:Commercial t:dataTypeName=number

metric m:industrial p:float l:Industrial t:dataTypeName=number

metric m:transportation p:float l:Transportation t:dataTypeName=number

metric m:electric_power p:float l:"Electric power" t:dataTypeName=number

entity e:usfi-mive l:"Table 17.03 CONSUMPTION OF ENERGY BY END- USE SECTOR 1960 TO 2012" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/usfi-mive

property e:usfi-mive t:meta.view v:id=usfi-mive v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook, v:averageRating=0 v:name="Table 17.03 CONSUMPTION OF ENERGY BY END- USE SECTOR 1960 TO 2012" v:attribution="Department of Economic Development and Tourism"

property e:usfi-mive t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:usfi-mive t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:usfi-mive t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | residential | commercial | industrial | transportation | electric_power | 
| ==== | =========== | ========== | ========== | ============== | ============== | 
| 1960 | 7.1         | 5.3        | 20.6       | 61.8           | 17.6           | 
| 1961 | 7.3         | 5.6        | 26.8       | 74.0           | 19.4           | 
| 1962 | 7.7         | 5.7        | 28.7       | 66.1           | 21.4           | 
| 1963 | 8.7         | 6.2        | 29.9       | 69.5           | 24.2           | 
| 1964 | 9.4         | 6.9        | 32.4       | 74.8           | 26.7           | 
| 1965 | 9.9         | 7.0        | 34.7       | 79.0           | 27.6           | 
| 1966 | 10.5        | 7.7        | 35.8       | 91.5           | 29.7           | 
| 1967 | 11.7        | 8.4        | 38.7       | 105.1          | 31.3           | 
| 1968 | 12.6        | 9.2        | 38.9       | 122.0          | 35.0           | 
| 1969 | 14.1        | 10.7       | 41.0       | 125.1          | 38.7           | 
```