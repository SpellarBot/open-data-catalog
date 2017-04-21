# Noise Exceedance Rating

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/noise-exceedance-rating) |
| Metadata | [Link](https://data.sfgov.org/api/views/5m6g-bqm4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5m6g-bqm4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5m6g-bqm4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5m6g-bqm4 |
| Name | Noise Exceedance Rating |
| Attribution | San Francisco International Airport |
| Category | Transportation |
| Tags | aircraft, noise, sfo, airport, airlines |
| Created | 2016-04-08T21:43:47Z |
| Publication Date | 2016-04-08T23:07:47Z |

## Description

Counts of airline operations that incur noise exceeding threshold by airline and by month. The Aircraft Noise Abatement Office collects this data using an Airport Noise and Operations Management System. It is collected using remote noise monitor sites in the communities surrounding SFO. This data is collected to monitor and grade airlines' performance as part of SFO's Fly Quiet Program.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| No       |                | year                                  | Year                                  | number    | number      |
| No       |                | month                                 | Month                                 | text      | text        |
| Yes      | series tag     | airline_code                          | Airline Code                          | text      | text        |
| Yes      | series tag     | airline                               | Airline                               | text      | text        |
| Yes      | numeric metric | total_noise_exceedances               | Total Noise Exceedances               | number    | number      |
| Yes      | numeric metric | total_operations_per_month            | Total Operations per Month            | number    | number      |
| Yes      | numeric metric | exceedances_per_1000_operations       | Exceedances per 1000 Operations       | number    | number      |
| Yes      | numeric metric | noise_exceedance_quality_rating_score | Noise Exceedance Quality Rating Score | number    | number      |
| Yes      | series tag     | noise_exceedance_rating               | Noise Exceedance Rating               | html      | html        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:5m6g-bqm4 d:2014-01-01T00:00:00.000Z t:airline_code=CPZ t:airline="COMPASS AIRLINES" m:noise_exceedance_quality_rating_score=9.99 m:total_noise_exceedances=1 m:exceedances_per_1000_operations=1 m:total_operations_per_month=828

series e:5m6g-bqm4 d:2014-01-01T00:00:00.000Z t:airline_code=SKW t:airline=SKYWEST m:noise_exceedance_quality_rating_score=9.99 m:total_noise_exceedances=18 m:exceedances_per_1000_operations=2 m:total_operations_per_month=8279

series e:5m6g-bqm4 d:2014-01-01T00:00:00.000Z t:airline_code=DAL t:airline="DELTA AIRLINES" m:noise_exceedance_quality_rating_score=9.97 m:total_noise_exceedances=7 m:exceedances_per_1000_operations=6 m:total_operations_per_month=1265
```

## Meta Commands

```ls
metric m:total_noise_exceedances p:integer l:"Total Noise Exceedances" t:dataTypeName=number

metric m:total_operations_per_month p:integer l:"Total Operations per Month" t:dataTypeName=number

metric m:exceedances_per_1000_operations p:integer l:"Exceedances per 1000 Operations" t:dataTypeName=number

metric m:noise_exceedance_quality_rating_score p:float l:"Noise Exceedance Quality Rating Score" t:dataTypeName=number

entity e:5m6g-bqm4 l:"Noise Exceedance Rating" t:attribution="San Francisco International Airport" t:url=https://data.sfgov.org/api/views/5m6g-bqm4

property e:5m6g-bqm4 t:meta.view v:id=5m6g-bqm4 v:category=Transportation v:attributionLink=http://www.flysfo.com v:averageRating=0 v:name="Noise Exceedance Rating" v:attribution="San Francisco International Airport"

property e:5m6g-bqm4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5m6g-bqm4 t:meta.view.owner v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:displayName=NoiseAbatementOffice@flysfo.com

property e:5m6g-bqm4 t:meta.view.tableauthor v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:roleName=editor v:displayName=NoiseAbatementOffice@flysfo.com
```

## Top Records

```ls
| year | month   | airline_code | airline           | total_noise_exceedances | total_operations_per_month | exceedances_per_1000_operations | noise_exceedance_quality_rating_score | noise_exceedance_rating | 
| ==== | ======= | ============ | ================= | ======================= | ========================== | =============================== | ===================================== | ======================= | 
| 2014 | January | CPZ          | COMPASS AIRLINES  | 1                       | 828                        | 1                               | 9.99                                  |                         | 
| 2014 | January | SKW          | SKYWEST           | 18                      | 8279                       | 2                               | 9.99                                  |                         | 
| 2014 | January | DAL          | DELTA AIRLINES    | 7                       | 1265                       | 6                               | 9.97                                  |                         | 
| 2014 | January | ASA          | ALASKA AIRLINES   | 7                       | 802                        | 9                               | 9.95                                  |                         | 
| 2014 | January | DLH          | LUFTHANSA         | 1                       | 114                        | 9                               | 9.95                                  |                         | 
| 2014 | January | AAL          | AMERICAN AIRLINES | 16                      | 1697                       | 9                               | 9.95                                  |                         | 
| 2014 | January | AWE          | US AIRWAYS        | 9                       | 838                        | 11                              | 9.94                                  |                         | 
| 2014 | January | VRD          | VIRGIN AMERICA    | 36                      | 2894                       | 12                              | 9.93                                  |                         | 
| 2014 | January | FFT          | FRONTIER AIRLINES | 3                       | 218                        | 14                              | 9.93                                  |                         | 
| 2014 | January | ANZ          | AIR NEW ZEALAND   | 1                       | 62                         | 16                              | 9.91                                  |                         | 
```