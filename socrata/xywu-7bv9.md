# New York City Population by Borough, 1950 - 2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-population-by-borough-1950-2040-d09f9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xywu-7bv9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xywu-7bv9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xywu-7bv9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xywu-7bv9 |
| Name | New York City Population by Borough, 1950 - 2040 |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | projected population 1950-2040 -?? school- age-- elderly-- total by borough, dcp, 2000, 2040 |
| Created | 2014-04-29T14:39:10Z |
| Publication Date | 2014-04-29T14:41:06Z |

## Description

Unadjusted decennial census data from 1950-2000 and projected figures from 2010-2040: summary table of New York City population numbers and percentage share by Borough, including school-age (5 to 17), 65 and Over, and total population.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | age_group                    | Age Group                      | text      | text        |
| Yes      | series tag     | borough                      | Borough                        | text      | text        |
| Yes      | numeric metric | 1950                         | 1950                           | number    | number      |
| Yes      | numeric metric | 1950_boro_share_of_nyc_total | 1950 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 1960                         | 1960                           | number    | number      |
| Yes      | numeric metric | 1960_boro_share_of_nyc_total | 1960 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 1970                         | 1970                           | number    | number      |
| Yes      | numeric metric | 1970_boro_share_of_nyc_total | 1970 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 1980                         | 1980                           | number    | number      |
| Yes      | numeric metric | 1980_boro_share_of_nyc_total | 1980 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 1990                         | 1990                           | number    | number      |
| Yes      | numeric metric | 1990_boro_share_of_nyc_total | 1990 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 2000                         | 2000                           | number    | number      |
| Yes      | numeric metric | 2000_boro_share_of_nyc_total | 2000 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 2010                         | 2010                           | number    | number      |
| Yes      | numeric metric | 2010_boro_share_of_nyc_total | 2010 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 2020                         | 2020                           | number    | number      |
| Yes      | numeric metric | 2020_boro_share_of_nyc_total | 2020 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 2030                         | 2030                           | number    | number      |
| Yes      | numeric metric | 2030_boro_share_of_nyc_total | 2030 - Boro share of NYC total | percent   | percent     |
| Yes      | numeric metric | 2040                         | 2040                           | number    | number      |
| Yes      | numeric metric | 2040_boro_share_of_nyc_total | 2040 - Boro share of NYC total | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xywu-7bv9 d:2014-04-29T07:39:14.000Z t:age_group="Total Population" t:borough="NYC Total" m:2000_boro_share_of_nyc_total=100 m:2040=9025145 m:1980_boro_share_of_nyc_total=100 m:2030=8821027 m:1960_boro_share_of_nyc_total=100 m:2010_boro_share_of_nyc_total=100 m:1970_boro_share_of_nyc_total=100 m:2040_boro_share_of_nyc_total=100 m:1990=7322564 m:1950=7891957 m:1960=7781984 m:1990_boro_share_of_nyc_total=100 m:1970=7894862 m:2020_boro_share_of_nyc_total=100 m:1980=7071639 m:2020=8550971 m:1950_boro_share_of_nyc_total=100 m:2010=8242624 m:2000=8008278 m:2030_boro_share_of_nyc_total=100

series e:xywu-7bv9 d:2014-04-29T07:39:14.000Z t:age_group="Total Population" t:borough=Bronx m:2000_boro_share_of_nyc_total=16.64 m:2040=1579245 m:1980_boro_share_of_nyc_total=16.53 m:2030=1518998 m:1960_boro_share_of_nyc_total=18.31 m:2010_boro_share_of_nyc_total=16.8 m:1970_boro_share_of_nyc_total=18.64 m:2040_boro_share_of_nyc_total=17.5 m:1990=1203789 m:1950=1451277 m:1960=1424815 m:1990_boro_share_of_nyc_total=16.44 m:1970=1471701 m:2020_boro_share_of_nyc_total=16.92 m:1980=1168972 m:2020=1446788 m:1950_boro_share_of_nyc_total=18.39 m:2010=1385108 m:2000=1332650 m:2030_boro_share_of_nyc_total=17.22

series e:xywu-7bv9 d:2014-04-29T07:39:14.000Z t:age_group="Total Population" t:borough=Brooklyn m:2000_boro_share_of_nyc_total=30.78 m:2040=2840525 m:1980_boro_share_of_nyc_total=31.55 m:2030=2754009 m:1960_boro_share_of_nyc_total=33.76 m:2010_boro_share_of_nyc_total=30.97 m:1970_boro_share_of_nyc_total=32.96 m:2040_boro_share_of_nyc_total=31.47 m:1990=2300664 m:1950=2738175 m:1960=2627319 m:1990_boro_share_of_nyc_total=31.42 m:1970=2602012 m:2020_boro_share_of_nyc_total=30.97 m:1980=2230936 m:2020=2648452 m:1950_boro_share_of_nyc_total=34.7 m:2010=2552911 m:2000=2465326 m:2030_boro_share_of_nyc_total=31.22
```

## Meta Commands

```ls
metric m:1950 p:integer l:1950 t:dataTypeName=number

metric m:1950_boro_share_of_nyc_total p:float l:"1950 - Boro share of NYC total" t:dataTypeName=percent

metric m:1960 p:integer l:1960 t:dataTypeName=number

metric m:1960_boro_share_of_nyc_total p:float l:"1960 - Boro share of NYC total" t:dataTypeName=percent

metric m:1970 p:integer l:1970 t:dataTypeName=number

metric m:1970_boro_share_of_nyc_total p:float l:"1970 - Boro share of NYC total" t:dataTypeName=percent

metric m:1980 p:integer l:1980 t:dataTypeName=number

metric m:1980_boro_share_of_nyc_total p:float l:"1980 - Boro share of NYC total" t:dataTypeName=percent

metric m:1990 p:integer l:1990 t:dataTypeName=number

metric m:1990_boro_share_of_nyc_total p:float l:"1990 - Boro share of NYC total" t:dataTypeName=percent

metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2000_boro_share_of_nyc_total p:float l:"2000 - Boro share of NYC total" t:dataTypeName=percent

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2010_boro_share_of_nyc_total p:float l:"2010 - Boro share of NYC total" t:dataTypeName=percent

metric m:2020 p:integer l:2020 t:dataTypeName=number

metric m:2020_boro_share_of_nyc_total p:float l:"2020 - Boro share of NYC total" t:dataTypeName=percent

metric m:2030 p:integer l:2030 t:dataTypeName=number

metric m:2030_boro_share_of_nyc_total p:float l:"2030 - Boro share of NYC total" t:dataTypeName=percent

metric m:2040 p:integer l:2040 t:dataTypeName=number

metric m:2040_boro_share_of_nyc_total p:float l:"2040 - Boro share of NYC total" t:dataTypeName=percent

entity e:xywu-7bv9 l:"New York City Population by Borough, 1950 - 2040" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/xywu-7bv9

property e:xywu-7bv9 t:meta.view v:id=xywu-7bv9 v:category="City Government" v:averageRating=0 v:name="New York City Population by Borough, 1950 - 2040" v:attribution="Department of City Planning (DCP)"

property e:xywu-7bv9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xywu-7bv9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | age_group        | borough       | 1950    | 1950_boro_share_of_nyc_total | 1960    | 1960_boro_share_of_nyc_total | 1970    | 1970_boro_share_of_nyc_total | 1980    | 1980_boro_share_of_nyc_total | 1990    | 1990_boro_share_of_nyc_total | 2000    | 2000_boro_share_of_nyc_total | 2010    | 2010_boro_share_of_nyc_total | 2020    | 2020_boro_share_of_nyc_total | 2030    | 2030_boro_share_of_nyc_total | 2040    | 2040_boro_share_of_nyc_total | 
| =========== | ================ | ============= | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | ======= | ============================ | 
| 1398757154  | Total Population | NYC Total     | 7891957 | 100.00                       | 7781984 | 100.00                       | 7894862 | 100.00                       | 7071639 | 100.00                       | 7322564 | 100.00                       | 8008278 | 100.00                       | 8242624 | 100.00                       | 8550971 | 100.00                       | 8821027 | 100.00                       | 9025145 | 100.00                       | 
| 1398757154  | Total Population | Bronx         | 1451277 | 18.39                        | 1424815 | 18.31                        | 1471701 | 18.64                        | 1168972 | 16.53                        | 1203789 | 16.44                        | 1332650 | 16.64                        | 1385108 | 16.80                        | 1446788 | 16.92                        | 1518998 | 17.22                        | 1579245 | 17.50                        | 
| 1398757154  | Total Population | Brooklyn      | 2738175 | 34.70                        | 2627319 | 33.76                        | 2602012 | 32.96                        | 2230936 | 31.55                        | 2300664 | 31.42                        | 2465326 | 30.78                        | 2552911 | 30.97                        | 2648452 | 30.97                        | 2754009 | 31.22                        | 2840525 | 31.47                        | 
| 1398757154  | Total Population | Manhattan     | 1960101 | 24.84                        | 1698281 | 21.82                        | 1539233 | 19.50                        | 1428285 | 20.20                        | 1487536 | 20.31                        | 1537195 | 19.20                        | 1585873 | 19.24                        | 1638281 | 19.16                        | 1676720 | 19.01                        | 1691617 | 18.74                        | 
| 1398757154  | Total Population | Queens        | 1550849 | 19.65                        | 1809578 | 23.25                        | 1986473 | 25.16                        | 1891325 | 26.75                        | 1951598 | 26.65                        | 2229379 | 27.84                        | 2250002 | 27.30                        | 2330295 | 27.25                        | 2373551 | 26.91                        | 2412649 | 26.73                        | 
| 1398757154  | Total Population | Staten Island | 191555  | 2.43                         | 221991  | 2.85                         | 295443  | 3.74                         | 352121  | 4.98                         | 378977  | 5.18                         | 443728  | 5.54                         | 468730  | 5.69                         | 487155  | 5.70                         | 497749  | 5.64                         | 501109  | 5.55                         | 
```