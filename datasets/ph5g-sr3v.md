# Projected Population 2010-2040 - Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-population-2010-2040-summary-5298f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ph5g-sr3v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ph5g-sr3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ph5g-sr3v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ph5g-sr3v |
| Name | Projected Population 2010-2040 - Summary |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 2010-2040 - summary, dcp, population, 2010, 2040 |
| Created | 2011-10-25T18:05:51Z |
| Publication Date | 2014-04-22T20:29:32Z |

## Description

Projected New York City population numbers and percentage changes from 2010 through 2040 by Borough, including school-age, 65 and Over, and total population.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================ | ==================================== | ========= | =========== |
| Yes      | series tag     | age_group                        | Age Group                            | text      | text        |
| Yes      | series tag     | borough                          | Borough                              | text      | text        |
| No       |                | _1                               | 2010                                 | number    | number      |
| Yes      | numeric metric | of_total_borough_population_2000 | % of Total Borough Population - 2010 | percent   | percent     |
| No       |                | _2                               | 2020                                 | number    | number      |
| Yes      | numeric metric | of_total_borough_population_2010 | % of Total Borough Population - 2020 | percent   | percent     |
| No       |                | _3                               | 2030                                 | number    | number      |
| Yes      | numeric metric | of_total_borough_population_2020 | % of Total Borough Population - 2030 | percent   | percent     |
| No       |                | _4                               | 2040                                 | number    | number      |
| Yes      | numeric metric | of_total_borough_population_2030 | % of Total Borough Population - 2040 | percent   | percent     |
| Yes      | numeric metric | change_in_number_2000_2010       | Change in Number - 2010-2020         | number    | number      |
| Yes      | numeric metric | change_in_percent_2000_2010      | Change in Percent - 2010-2020        | percent   | percent     |
| Yes      | numeric metric | change_in_number_2010_2020_      | Change in Number - 2020-2030         | number    | number      |
| Yes      | numeric metric | change_in_percent_2010_2020      | Change in Percent - 2020-2030        | percent   | percent     |
| Yes      | numeric metric | change_in_number_2020_2030_      | Change in Number - 2030-2040         | number    | number      |
| Yes      | numeric metric | change_in_percent_2020_2030      | Change in Percent - 2030-2040        | percent   | percent     |
| Yes      | numeric metric | change_in_number_2000_2030_      | Change in Number - 2010-2040         | number    | number      |
| Yes      | numeric metric | change_in_percent_2000_2030      | Change in Percent - 2010-2040        | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4
```

## Data Commands

```ls
series e:ph5g-sr3v d:2010-01-01T00:00:00.000Z t:age_group=Total t:borough="New York City" m:change_in_number_2000_2030_=782521 m:of_total_borough_population_2020=100 m:change_in_percent_2020_2030=2.31 m:change_in_percent_2000_2030=9.49 m:change_in_percent_2000_2010=3.74 m:change_in_number_2010_2020_=270056 m:of_total_borough_population_2030=100 m:change_in_percent_2010_2020=3.16 m:change_in_number_2000_2010=308347 m:change_in_number_2020_2030_=204118 m:of_total_borough_population_2010=100 m:of_total_borough_population_2000=100

series e:ph5g-sr3v d:2010-01-01T00:00:00.000Z t:age_group=Total t:borough=Bronx m:change_in_number_2000_2030_=194137 m:of_total_borough_population_2020=100 m:change_in_percent_2020_2030=3.97 m:change_in_percent_2000_2030=14.02 m:change_in_percent_2000_2010=4.45 m:change_in_number_2010_2020_=72210 m:of_total_borough_population_2030=100 m:change_in_percent_2010_2020=4.99 m:change_in_number_2000_2010=61680 m:change_in_number_2020_2030_=60247 m:of_total_borough_population_2010=100 m:of_total_borough_population_2000=100

series e:ph5g-sr3v d:2010-01-01T00:00:00.000Z t:age_group=Total t:borough=Brooklyn m:change_in_number_2000_2030_=287614 m:of_total_borough_population_2020=100 m:change_in_percent_2020_2030=3.14 m:change_in_percent_2000_2030=11.27 m:change_in_percent_2000_2010=3.74 m:change_in_number_2010_2020_=105557 m:of_total_borough_population_2030=100 m:change_in_percent_2010_2020=3.99 m:change_in_number_2000_2010=95541 m:change_in_number_2020_2030_=86516 m:of_total_borough_population_2010=100 m:of_total_borough_population_2000=100
```

## Meta Commands

```ls
metric m:of_total_borough_population_2000 p:float l:"% of Total Borough Population - 2010" t:dataTypeName=percent

metric m:of_total_borough_population_2010 p:float l:"% of Total Borough Population - 2020" t:dataTypeName=percent

metric m:of_total_borough_population_2020 p:float l:"% of Total Borough Population - 2030" t:dataTypeName=percent

metric m:of_total_borough_population_2030 p:float l:"% of Total Borough Population - 2040" t:dataTypeName=percent

metric m:change_in_number_2000_2010 p:integer l:"Change in Number - 2010-2020" t:dataTypeName=number

metric m:change_in_percent_2000_2010 p:float l:"Change in Percent - 2010-2020" t:dataTypeName=percent

metric m:change_in_number_2010_2020_ p:integer l:"Change in Number - 2020-2030" t:dataTypeName=number

metric m:change_in_percent_2010_2020 p:float l:"Change in Percent - 2020-2030" t:dataTypeName=percent

metric m:change_in_number_2020_2030_ p:integer l:"Change in Number - 2030-2040" t:dataTypeName=number

metric m:change_in_percent_2020_2030 p:float l:"Change in Percent - 2030-2040" t:dataTypeName=percent

metric m:change_in_number_2000_2030_ p:integer l:"Change in Number - 2010-2040" t:dataTypeName=number

metric m:change_in_percent_2000_2030 p:float l:"Change in Percent - 2010-2040" t:dataTypeName=percent

entity e:ph5g-sr3v l:"Projected Population 2010-2040 - Summary" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/ph5g-sr3v

property e:ph5g-sr3v t:meta.view v:id=ph5g-sr3v v:category="City Government" v:averageRating=0 v:name="Projected Population 2010-2040 - Summary" v:attribution="Department of City Planning (DCP)"

property e:ph5g-sr3v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ph5g-sr3v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| age_group           | borough       | _1      | of_total_borough_population_2000 | _2      | of_total_borough_population_2010 | _3      | of_total_borough_population_2020 | _4      | of_total_borough_population_2030 | change_in_number_2000_2010 | change_in_percent_2000_2010 | change_in_number_2010_2020_ | change_in_percent_2010_2020 | change_in_number_2020_2030_ | change_in_percent_2020_2030 | change_in_number_2000_2030_ | change_in_percent_2000_2030 | 
| =================== | ============= | ======= | ================================ | ======= | ================================ | ======= | ================================ | ======= | ================================ | ========================== | =========================== | =========================== | =========================== | =========================== | =========================== | =========================== | =========================== | 
| Total               | New York City | 8242624 | 100.00                           | 8550971 | 100.00                           | 8821027 | 100.00                           | 9025145 | 100.00                           | 308347                     | 3.74                        | 270056                      | 3.16                        | 204118                      | 2.31                        | 782521                      | 9.49                        | 
| Total               | Bronx         | 1385108 | 100.00                           | 1446788 | 100.00                           | 1518998 | 100.00                           | 1579245 | 100.00                           | 61680                      | 4.45                        | 72210                       | 4.99                        | 60247                       | 3.97                        | 194137                      | 14.02                       | 
| Total               | Brooklyn      | 2552911 | 100.00                           | 2648452 | 100.00                           | 2754009 | 100.00                           | 2840525 | 100.00                           | 95541                      | 3.74                        | 105557                      | 3.99                        | 86516                       | 3.14                        | 287614                      | 11.27                       | 
| Total               | Manhattan     | 1585873 | 100.00                           | 1638281 | 100.00                           | 1676720 | 100.00                           | 1691617 | 100.00                           | 52408                      | 3.30                        | 38439                       | 2                           | 14897                       | 0.89                        | 105744                      | 6.67                        | 
| Total               | Queens        | 2250002 | 100.00                           | 2330295 | 100.00                           | 2373551 | 100.00                           | 2412649 | 100.00                           | 80293                      | 3.57                        | 43256                       | 1.86                        | 39098                       | 2                           | 162647                      | 7.23                        | 
| Total               | Staten Island | 468730  | 100.00                           | 487155  | 100.00                           | 497749  | 100.00                           | 501109  | 100.00                           | 18425                      | 3.93                        | 10594                       | 2.17                        | 3360                        | 0.68                        | 32379                       | 6.91                        | 
| School-Age (5 to17) | New York City | 1260400 | 15.29                            | 1282814 | 15.00                            | 1347036 | 15.27                            | 1342097 | 14.87                            | 22415                      | 1.78                        | 64222                       | 5.01                        | -4939                       | -0.37                       | 81697                       | 6.48                        | 
| School-Age (5 to17) | Bronx         | 265052  | 19.14                            | 259013  | 17.90                            | 277830  | 18.29                            | 281688  | 17.84                            | -6039                      | -2.28                       | 18817                       | 7.26                        | 3858                        | 1.39                        | 16636                       | 6.28                        | 
| School-Age (5 to17) | Brooklyn      | 424704  | 16.64                            | 441049  | 16.65                            | 461688  | 16.76                            | 454949  | 16.02                            | 16345                      | 3.85                        | 20639                       | 4.68                        | -6739                       | -1.46                       | 30245                       | 7.12                        | 
| School-Age (5 to17) | Manhattan     | 157856  | 9.95                             | 162931  | 9.95                             | 177440  | 10.58                            | 170114  | 10.06                            | 5075                       | 3.21                        | 14509                       | 8.90                        | -7326                       | -4.13                       | 12258                       | 7.77                        | 
```