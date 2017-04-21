# New York City?s School-Age and 65 and Over Populations by Borough, 1950 ? 2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-citys-school-age-and-65-and-over-populations-by-borough-1950-2040-b6c1d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xgse-vmv6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xgse-vmv6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xgse-vmv6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xgse-vmv6 |
| Name | New York City?s School-Age and 65 and Over Populations by Borough, 1950 ? 2040 |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 1950-2040 -?? school- age-- elderly-- total by borough, dcp, 2000, 2040 |
| Created | 2014-04-29T14:30:15Z |
| Publication Date | 2014-04-29T14:35:15Z |

## Description

Unadjusted decennial census data from 1950-2000 and projected figures from 2010-2040: summary table of New York City population numbers and percentage share by Borough, including school-age (5 to 17), 65 and Over, and total population.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag     | age_group                                | Age Group                                  | text      | text        |
| Yes      | series tag     | borough                                  | Borough                                    | text      | text        |
| Yes      | numeric metric | 1950                                     | 1950                                       | number    | number      |
| Yes      | numeric metric | 1950_percent_of_total_population_by_boro | 1950 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 1960                                     | 1960                                       | number    | number      |
| Yes      | numeric metric | 1960_percent_of_total_population_by_boro | 1960 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 1970                                     | 1970                                       | number    | number      |
| Yes      | numeric metric | 1970_percent_of_total_population_by_boro | 1970 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 1980                                     | 1980                                       | number    | number      |
| Yes      | numeric metric | 1980_percent_of_total_population_by_boro | 1980 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 1990                                     | 1990                                       | number    | number      |
| Yes      | numeric metric | 1990_percent_of_total_population_by_boro | 1990 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 2000                                     | 2000                                       | number    | number      |
| Yes      | numeric metric | 2000_percent_of_total_population_by_boro | 2000 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 2010                                     | 2010                                       | number    | number      |
| Yes      | numeric metric | 2010_percent_of_total_population_by_boro | 2010 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 2020                                     | 2020                                       | number    | number      |
| Yes      | numeric metric | 2020_percent_of_total_population_by_boro | 2020 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 2030                                     | 2030                                       | number    | number      |
| Yes      | numeric metric | 2030_percent_of_total_population_by_boro | 2030 - Percent of Total Population by Boro | percent   | percent     |
| Yes      | numeric metric | 2040                                     | 2040                                       | number    | number      |
| Yes      | numeric metric | 2040_percent_of_total_population_by_boro | 2040 - Percent of Total Population by Boro | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xgse-vmv6 d:2014-04-29T07:30:19.000Z t:age_group="School-Age (5 to 17)" t:borough="NYC Total" m:2030_percent_of_total_population_by_boro=15.27 m:2040=1342096.684 m:2000_percent_of_total_population_by_boro=17.54 m:2030=1347035.911 m:1980_percent_of_total_population_by_boro=18.27 m:2010_percent_of_total_population_by_boro=15.29 m:2040_percent_of_total_population_by_boro=14.87 m:1990=1190021 m:1950=1258877 m:1950_percent_of_total_population_by_boro=15.95 m:1960=1463279 m:1970=1617310 m:1980=1291705 m:2020_percent_of_total_population_by_boro=15 m:1960_percent_of_total_population_by_boro=18.8 m:2020=1282814.167 m:2010=1260400 m:1990_percent_of_total_population_by_boro=16.25 m:1970_percent_of_total_population_by_boro=20.49 m:2000=1404316

series e:xgse-vmv6 d:2014-04-29T07:30:19.000Z t:age_group="School-Age (5 to 17)" t:borough=Bronx m:2030_percent_of_total_population_by_boro=18.29 m:2040=281688 m:2000_percent_of_total_population_by_boro=21.63 m:2030=277830 m:1980_percent_of_total_population_by_boro=21.5 m:2010_percent_of_total_population_by_boro=19.14 m:2040_percent_of_total_population_by_boro=17.84 m:1990=231489 m:1950=251210 m:1950_percent_of_total_population_by_boro=17.31 m:1960=275325 m:1970=331588 m:1980=251366 m:2020_percent_of_total_population_by_boro=17.9 m:1960_percent_of_total_population_by_boro=19.32 m:2020=259013 m:2010=265052 m:1990_percent_of_total_population_by_boro=19.23 m:1970_percent_of_total_population_by_boro=22.53 m:2000=288308

series e:xgse-vmv6 d:2014-04-29T07:30:19.000Z t:age_group="School-Age (5 to 17)" t:borough=Brooklyn m:2030_percent_of_total_population_by_boro=16.76 m:2040=454949 m:2000_percent_of_total_population_by_boro=19.43 m:2030=461688 m:1980_percent_of_total_population_by_boro=20.31 m:2010_percent_of_total_population_by_boro=16.64 m:2040_percent_of_total_population_by_boro=16.02 m:1990=429418 m:1950=471479 m:1950_percent_of_total_population_by_boro=17.22 m:1960=527360 m:1970=588273 m:1980=453116 m:2020_percent_of_total_population_by_boro=16.65 m:1960_percent_of_total_population_by_boro=20.07 m:2020=441049 m:2010=424704 m:1990_percent_of_total_population_by_boro=18.66 m:1970_percent_of_total_population_by_boro=22.61 m:2000=478912
```

## Meta Commands

```ls
metric m:1950 p:integer l:1950 t:dataTypeName=number

metric m:1950_percent_of_total_population_by_boro p:float l:"1950 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:1960 p:integer l:1960 t:dataTypeName=number

metric m:1960_percent_of_total_population_by_boro p:float l:"1960 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:1970 p:integer l:1970 t:dataTypeName=number

metric m:1970_percent_of_total_population_by_boro p:float l:"1970 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:1980 p:integer l:1980 t:dataTypeName=number

metric m:1980_percent_of_total_population_by_boro p:float l:"1980 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:1990 p:integer l:1990 t:dataTypeName=number

metric m:1990_percent_of_total_population_by_boro p:float l:"1990 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2000_percent_of_total_population_by_boro p:float l:"2000 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2010_percent_of_total_population_by_boro p:float l:"2010 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:2020 p:double l:2020 t:dataTypeName=number

metric m:2020_percent_of_total_population_by_boro p:float l:"2020 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:2030 p:double l:2030 t:dataTypeName=number

metric m:2030_percent_of_total_population_by_boro p:float l:"2030 - Percent of Total Population by Boro" t:dataTypeName=percent

metric m:2040 p:double l:2040 t:dataTypeName=number

metric m:2040_percent_of_total_population_by_boro p:float l:"2040 - Percent of Total Population by Boro" t:dataTypeName=percent

entity e:xgse-vmv6 l:"New York City?s School-Age and 65 and Over Populations by Borough, 1950 ? 2040" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/xgse-vmv6

property e:xgse-vmv6 t:meta.view v:id=xgse-vmv6 v:category="City Government" v:averageRating=0 v:name="New York City?s School-Age and 65 and Over Populations by Borough, 1950 ? 2040" v:attribution="Department of City Planning (DCP)"

property e:xgse-vmv6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xgse-vmv6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | age_group            | borough       | 1950    | 1950_percent_of_total_population_by_boro | 1960    | 1960_percent_of_total_population_by_boro | 1970    | 1970_percent_of_total_population_by_boro | 1980    | 1980_percent_of_total_population_by_boro | 1990    | 1990_percent_of_total_population_by_boro | 2000    | 2000_percent_of_total_population_by_boro | 2010    | 2010_percent_of_total_population_by_boro | 2020        | 2020_percent_of_total_population_by_boro | 2030        | 2030_percent_of_total_population_by_boro | 2040        | 2040_percent_of_total_population_by_boro | 
| =========== | ==================== | ============= | ======= | ======================================== | ======= | ======================================== | ======= | ======================================== | ======= | ======================================== | ======= | ======================================== | ======= | ======================================== | ======= | ======================================== | =========== | ======================================== | =========== | ======================================== | =========== | ======================================== | 
| 1398756619  | School-Age (5 to 17) | NYC Total     | 1258877 | 15.95                                    | 1463279 | 18.80                                    | 1617310 | 20.49                                    | 1291705 | 18.27                                    | 1190021 | 16.25                                    | 1404316 | 17.54                                    | 1260400 | 15.29                                    | 1282814.167 | 15.00                                    | 1347035.911 | 15.27                                    | 1342096.684 | 14.87                                    | 
| 1398756619  | School-Age (5 to 17) | Bronx         | 251210  | 17.31                                    | 275325  | 19.32                                    | 331588  | 22.53                                    | 251366  | 21.50                                    | 231489  | 19.23                                    | 288308  | 21.63                                    | 265052  | 19.14                                    | 259013      | 17.90                                    | 277830      | 18.29                                    | 281688      | 17.84                                    | 
| 1398756619  | School-Age (5 to 17) | Brooklyn      | 471479  | 17.22                                    | 527360  | 20.07                                    | 588273  | 22.61                                    | 453116  | 20.31                                    | 429418  | 18.66                                    | 478912  | 19.43                                    | 424704  | 16.64                                    | 441049      | 16.65                                    | 461688      | 16.76                                    | 454949      | 16.02                                    | 
| 1398756619  | School-Age (5 to 17) | Manhattan     | 247520  | 12.63                                    | 258476  | 15.22                                    | 243423  | 15.81                                    | 186389  | 13.05                                    | 173437  | 11.66                                    | 187758  | 12.21                                    | 157856  | 9.95                                     | 162931.0279 | 9.95                                     | 177440      | 10.58                                    | 170114      | 10.06                                    | 
| 1398756619  | School-Age (5 to 17) | Queens        | 254277  | 16.40                                    | 348996  | 19.29                                    | 379369  | 19.10                                    | 323532  | 17.11                                    | 289639  | 14.84                                    | 366604  | 16.44                                    | 331926  | 14.75                                    | 341062.3    | 14.64                                    | 350544      | 14.77                                    | 355340      | 14.73                                    | 
| 1398756619  | School-Age (5 to 17) | Staten Island | 34390   | 17.95                                    | 53121   | 23.93                                    | 74657   | 25.27                                    | 77302   | 21.96                                    | 66037   | 17.43                                    | 82734   | 18.65                                    | 80862   | 17.25                                    | 78758.8     | 16.17                                    | 79535       | 15.98                                    | 80005       | 15.97                                    | 
| 1398756619  | 65 and over          | NYC Total     | 605235  | 7.67                                     | 813827  | 10.46                                    | 947878  | 12.01                                    | 951732  | 13.46                                    | 953317  | 13.02                                    | 937857  | 11.71                                    | 1002208 | 12.16                                    | 1177215     | 13.77                                    | 1364178     | 15.47                                    | 1409708     | 15.62                                    | 
| 1398756619  | 65 and over          | Bronx         | 105862  | 7.29                                     | 152403  | 10.70                                    | 170920  | 11.61                                    | 151298  | 12.94                                    | 140220  | 11.65                                    | 133948  | 10.05                                    | 145882  | 10.53                                    | 171856      | 11.88                                    | 212334      | 13.98                                    | 228476      | 14.47                                    | 
| 1398756619  | 65 and over          | Brooklyn      | 202838  | 7.41                                     | 259158  | 9.86                                     | 289077  | 11.11                                    | 279544  | 12.53                                    | 285057  | 12.39                                    | 282658  | 11.47                                    | 294610  | 11.54                                    | 351609      | 13.28                                    | 408424      | 14.83                                    | 428845      | 15.10                                    | 
| 1398756619  | 65 and over          | Manhattan     | 171323  | 8.74                                     | 207700  | 12.23                                    | 214973  | 13.97                                    | 204437  | 14.31                                    | 197384  | 13.27                                    | 186776  | 12.15                                    | 214153  | 13.50                                    | 250806      | 15.31                                    | 278043      | 16.58                                    | 277444      | 16.40                                    | 
```