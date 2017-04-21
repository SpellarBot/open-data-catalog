# New York City Population By Census Tracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-population-by-census-tracts-af944) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/37cg-gxjd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/37cg-gxjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/37cg-gxjd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 37cg-gxjd |
| Name | New York City Population By Census Tracts |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, census, tract |
| Created | 2013-03-03T16:36:03Z |
| Publication Date | 2013-06-26T17:15:58Z |

## Description

Population Numbers in New York City by Census Tracts

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | borough          | Borough          | text      | text        |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | series tag     | fips_county_code | FIPS County Code | text      | text        |
| Yes      | series tag     | dcp_borough_code | DCP Borough Code | text      | text        |
| Yes      | series tag     | census_tract     | Census Tract     | text      | text        |
| Yes      | numeric metric | population       | Population       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:37cg-gxjd d:2000-01-01T00:00:00.000Z t:fips_county_code=005 t:borough=Bronx t:census_tract=000100 t:dcp_borough_code=2 m:population=12780

series e:37cg-gxjd d:2000-01-01T00:00:00.000Z t:fips_county_code=005 t:borough=Bronx t:census_tract=000200 t:dcp_borough_code=2 m:population=3545

series e:37cg-gxjd d:2000-01-01T00:00:00.000Z t:fips_county_code=005 t:borough=Bronx t:census_tract=000400 t:dcp_borough_code=2 m:population=3314
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:37cg-gxjd l:"New York City Population By Census Tracts" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/37cg-gxjd

property e:37cg-gxjd t:meta.view v:id=37cg-gxjd v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/html/census/demo_tables_2010.shtml v:averageRating=0 v:name="New York City Population By Census Tracts" v:attribution="Department of City Planning (DCP)"

property e:37cg-gxjd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:37cg-gxjd t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| borough | year | fips_county_code | dcp_borough_code | census_tract | population | 
| ======= | ==== | ================ | ================ | ============ | ========== | 
| Bronx   | 2000 | 005              | 2                | 000100       | 12780      | 
| Bronx   | 2000 | 005              | 2                | 000200       | 3545       | 
| Bronx   | 2000 | 005              | 2                | 000400       | 3314       | 
| Bronx   | 2000 | 005              | 2                | 001600       | 5237       | 
| Bronx   | 2000 | 005              | 2                | 001900       | 1584       | 
| Bronx   | 2000 | 005              | 2                | 002000       | 9068       | 
| Bronx   | 2000 | 005              | 2                | 002300       | 4338       | 
| Bronx   | 2000 | 005              | 2                | 002400       | 0          | 
| Bronx   | 2000 | 005              | 2                | 002500       | 5109       | 
| Bronx   | 2000 | 005              | 2                | 002701       | 3033       | 
```