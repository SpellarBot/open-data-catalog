# New York City Population By Neighborhood Tabulation Areas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-population-by-neighborhood-tabulation-areas-f2447) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/swpk-hqdp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/swpk-hqdp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/swpk-hqdp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | swpk-hqdp |
| Name | New York City Population By Neighborhood Tabulation Areas |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, nta, neighborhood, tabulation |
| Created | 2013-03-03T16:54:56Z |
| Publication Date | 2013-06-26T17:16:18Z |

## Description

Population Numbers By New York City Neighborhood Tabulation Areas

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | borough          | Borough          | text      | text        |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | series tag     | fips_county_code | FIPS County Code | text      | text        |
| Yes      | series tag     | nta_code         | NTA Code         | text      | text        |
| Yes      | series tag     | nta_name         | NTA Name         | text      | text        |
| Yes      | numeric metric | population       | Population       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:swpk-hqdp d:2000-01-01T00:00:00.000Z t:nta_name=Claremont-Bathgate t:fips_county_code=005 t:nta_code=BX01 t:borough=Bronx m:population=28149

series e:swpk-hqdp d:2000-01-01T00:00:00.000Z t:nta_name=Eastchester-Edenwald-Baychester t:fips_county_code=005 t:nta_code=BX03 t:borough=Bronx m:population=35422

series e:swpk-hqdp d:2000-01-01T00:00:00.000Z t:nta_name="Bedford Park-Fordham North" t:fips_county_code=005 t:nta_code=BX05 t:borough=Bronx m:population=55329
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:swpk-hqdp l:"New York City Population By Neighborhood Tabulation Areas" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/swpk-hqdp

property e:swpk-hqdp t:meta.view v:id=swpk-hqdp v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/html/census/demo_tables_2010.shtml v:averageRating=0 v:name="New York City Population By Neighborhood Tabulation Areas" v:attribution="Department of City Planning (DCP)"

property e:swpk-hqdp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:swpk-hqdp t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| borough | year | fips_county_code | nta_code | nta_name                                        | population | 
| ======= | ==== | ================ | ======== | =============================================== | ========== | 
| Bronx   | 2000 | 005              | BX01     | Claremont-Bathgate                              | 28149      | 
| Bronx   | 2000 | 005              | BX03     | Eastchester-Edenwald-Baychester                 | 35422      | 
| Bronx   | 2000 | 005              | BX05     | Bedford Park-Fordham North                      | 55329      | 
| Bronx   | 2000 | 005              | BX06     | Belmont                                         | 25967      | 
| Bronx   | 2000 | 005              | BX07     | Bronxdale                                       | 34309      | 
| Bronx   | 2000 | 005              | BX08     | West Farms-Bronx River                          | 34542      | 
| Bronx   | 2000 | 005              | BX09     | Soundview-Castle Hill-Clason Point-Harding Park | 50753      | 
| Bronx   | 2000 | 005              | BX10     | Pelham Bay-Country Club-City Island             | 27140      | 
| Bronx   | 2000 | 005              | BX13     | Co-Op City                                      | 40676      | 
| Bronx   | 2000 | 005              | BX14     | East Concourse-Concourse Village                | 58961      | 
```