# Anne Arundel County Crime Rate By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/anne-arundel-county-crime-rate-by-type-e5923) |
| Metadata | [Link](https://data.maryland.gov/api/views/3fys-ggpk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/3fys-ggpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/3fys-ggpk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 3fys-ggpk |
| Name | Anne Arundel County Crime Rate By Type |
| Attribution | MSAC |
| Category | Public Safety |
| Tags | anne arundel, crime, public safety, violent crime, property crime |
| Created | 2014-07-25T16:31:44Z |
| Publication Date | 2014-07-25T16:37:33Z |

## Description

Historical crime rates per 100,000 people, 1975 - present.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | year                               | YEAR                               | number    | number      |
| Yes      | numeric metric | population                         | POPULATION                         | number    | number      |
| Yes      | numeric metric | murder                             | MURDER                             | number    | number      |
| Yes      | numeric metric | rape                               | RAPE                               | number    | number      |
| Yes      | numeric metric | robbery                            | ROBBERY                            | number    | number      |
| Yes      | numeric metric | agg_assault                        | AGG. ASSAULT                       | number    | number      |
| Yes      | numeric metric | violent_crime_rate                 | VIOLENT CRIME RATE                 | number    | number      |
| Yes      | numeric metric | violent_crime_rate_percent_change  | VIOLENT CRIME RATE PERCENT CHANGE  | percent   | percent     |
| Yes      | numeric metric | b_e                                | B & E                              | number    | number      |
| Yes      | numeric metric | larceny_theft                      | LARCENY THEFT                      | number    | number      |
| Yes      | numeric metric | m_v_theft                          | M/V THEFT                          | number    | number      |
| Yes      | numeric metric | property_crime_rate                | PROPERTY CRIME RATE                | number    | number      |
| Yes      | numeric metric | property_crime_rate_percent_change | PROPERTY CRIME RATE PERCENT CHANGE | percent   | percent     |
| Yes      | numeric metric | total_crime_rate                   | TOTAL CRIME RATE                   | number    | number      |
| Yes      | numeric metric | total_crime_ratae_percent_change   | TOTAL CRIME RATE PERCENT CHANGE    | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3fys-ggpk d:1975-01-01T00:00:00.000Z m:property_crime_rate=6151.1 m:larceny_theft=3843.2 m:murder=4.8 m:robbery=124.6 m:total_crime_rate=6759.7 m:b_e=1708.6 m:agg_assault=456.9 m:m_v_theft=599.3 m:violent_crime_rate=608.6 m:rape=22.3 m:population=331390

series e:3fys-ggpk d:1976-01-01T00:00:00.000Z m:property_crime_rate=5203 m:larceny_theft=3389.2 m:murder=2.9 m:robbery=97 m:total_crime_rate=5507.4 m:total_crime_ratae_percent_change=-18.5 m:b_e=1367.1 m:violent_crime_rate_percent_change=-50 m:agg_assault=181.9 m:property_crime_rate_percent_change=-15.4 m:m_v_theft=446.6 m:violent_crime_rate=304.4 m:rape=22.6 m:population=340345

series e:3fys-ggpk d:1977-01-01T00:00:00.000Z m:property_crime_rate=4980.8 m:larceny_theft=3102.7 m:murder=4.6 m:robbery=113.9 m:total_crime_rate=5322 m:total_crime_ratae_percent_change=-3.4 m:b_e=1464.9 m:violent_crime_rate_percent_change=12.1 m:agg_assault=188.8 m:property_crime_rate_percent_change=-4.3 m:m_v_theft=413.2 m:violent_crime_rate=341.3 m:rape=34 m:population=347538
```

## Meta Commands

```ls
metric m:population p:integer l:POPULATION t:dataTypeName=number

metric m:murder p:float l:MURDER t:dataTypeName=number

metric m:rape p:float l:RAPE t:dataTypeName=number

metric m:robbery p:float l:ROBBERY t:dataTypeName=number

metric m:agg_assault p:float l:"AGG. ASSAULT" t:dataTypeName=number

metric m:violent_crime_rate p:float l:"VIOLENT CRIME RATE" t:dataTypeName=number

metric m:violent_crime_rate_percent_change p:float l:"VIOLENT CRIME RATE PERCENT CHANGE" t:dataTypeName=percent

metric m:b_e p:float l:"B & E" t:dataTypeName=number

metric m:larceny_theft p:float l:"LARCENY THEFT" t:dataTypeName=number

metric m:m_v_theft p:float l:"M/V THEFT" t:dataTypeName=number

metric m:property_crime_rate p:float l:"PROPERTY CRIME RATE" t:dataTypeName=number

metric m:property_crime_rate_percent_change p:float l:"PROPERTY CRIME RATE PERCENT CHANGE" t:dataTypeName=percent

metric m:total_crime_rate p:float l:"TOTAL CRIME RATE" t:dataTypeName=number

metric m:total_crime_ratae_percent_change p:float l:"TOTAL CRIME RATE PERCENT CHANGE" t:dataTypeName=percent

entity e:3fys-ggpk l:"Anne Arundel County Crime Rate By Type" t:attribution=MSAC t:url=https://data.maryland.gov/api/views/3fys-ggpk

property e:3fys-ggpk t:meta.view v:id=3fys-ggpk v:category="Public Safety" v:attributionLink="http://www.goccp.maryland.gov/msac/crime-statistics-county.php?id=18" v:averageRating=0 v:name="Anne Arundel County Crime Rate By Type" v:attribution=MSAC

property e:3fys-ggpk t:meta.view.license v:name="Public Domain"

property e:3fys-ggpk t:meta.view.owner v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:displayName="Scott Shaffer"

property e:3fys-ggpk t:meta.view.tableauthor v:id=wdx2-yd94 v:screenName="Scott Shaffer" v:roleName=editor v:displayName="Scott Shaffer"
```

## Top Records

```ls
| year | population | murder | rape | robbery | agg_assault | violent_crime_rate | violent_crime_rate_percent_change | b_e    | larceny_theft | m_v_theft | property_crime_rate | property_crime_rate_percent_change | total_crime_rate | total_crime_ratae_percent_change | 
| ==== | ========== | ====== | ==== | ======= | =========== | ================== | ================================= | ====== | ============= | ========= | =================== | ================================== | ================ | ================================ | 
| 1975 | 331390     | 4.8    | 22.3 | 124.6   | 456.9       | 608.6              |                                   | 1708.6 | 3843.2        | 599.3     | 6151.1              |                                    | 6759.7           |                                  | 
| 1976 | 340345     | 2.9    | 22.6 | 97.0    | 181.9       | 304.4              | -50.0                             | 1367.1 | 3389.2        | 446.6     | 5203.0              | -15.4                              | 5507.4           | -18.5                            | 
| 1977 | 347538     | 4.6    | 34.0 | 113.9   | 188.8       | 341.3              | 12.1                              | 1464.9 | 3102.7        | 413.2     | 4980.8              | -4.3                               | 5322.0           | -3.4                             | 
| 1978 | 363169     | 4.7    | 18.7 | 96.1    | 195.5       | 315.0              | -7.7                              | 1292.5 | 2786.6        | 319.7     | 4398.8              | -11.7                              | 4713.8           | -11.4                            | 
| 1979 | 361749     | 3.6    | 23.2 | 83.2    | 201.2       | 311.3              | -1.2                              | 1224.6 | 2939.3        | 349.4     | 4513.4              | 2.6                                | 4824.6           | 2.4                              | 
| 1980 | 370099     | 5.4    | 31.6 | 95.1    | 220.2       | 352.3              | 13.2                              | 1471.0 | 3300.5        | 365.6     | 5137.0              | 13.8                               | 5489.3           | 13.8                             | 
| 1981 | 376172     | 6.1    | 22.6 | 129.7   | 218.0       | 376.4              | 6.8                               | 1357.1 | 3359.6        | 339.2     | 5055.9              | -1.6                               | 5432.4           | -1.0                             | 
| 1982 | 376525     | 5.0    | 22.0 | 111.5   | 224.2       | 362.8              | -3.6                              | 1225.4 | 3098.6        | 299.6     | 4623.6              | -8.6                               | 4986.4           | -8.2                             | 
| 1983 | 379967     | 3.4    | 18.7 | 122.4   | 246.1       | 390.6              | 7.7                               | 1155.9 | 2649.4        | 250.3     | 4055.6              | -12.3                              | 4446.2           | -10.8                            | 
| 1984 | 388659     | 4.1    | 25.0 | 107.0   | 279.2       | 415.3              | 6.3                               | 1098.4 | 2606.7        | 242.1     | 3947.2              | -2.7                               | 4362.4           | -1.9                             | 
```