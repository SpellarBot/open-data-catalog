# New York City Population By Boroughs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-population-by-boroughs-fd2c0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9mhd-na2n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9mhd-na2n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9mhd-na2n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9mhd-na2n |
| Name | New York City Population By Boroughs |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, borough |
| Created | 2013-02-20T16:43:44Z |
| Publication Date | 2013-06-26T17:15:38Z |

## Description

New York City Population By Boroughs

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | borough         | Borough         | text      | text        |
| Yes      | numeric metric | 2000_population | 2000 Population | number    | number      |
| Yes      | numeric metric | 2010_population | 2010 Population | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9mhd-na2n d:2013-02-20T08:43:45.000Z t:borough=Bronx m:2000_population=1332650 m:2010_population=1385108

series e:9mhd-na2n d:2013-02-20T08:43:45.000Z t:borough=Brooklyn m:2000_population=2465326 m:2010_population=2504700

series e:9mhd-na2n d:2013-02-20T08:43:45.000Z t:borough=Manhattan m:2000_population=1537195 m:2010_population=1585873
```

## Meta Commands

```ls
metric m:2000_population p:integer l:"2000 Population" t:dataTypeName=number

metric m:2010_population p:integer l:"2010 Population" t:dataTypeName=number

entity e:9mhd-na2n l:"New York City Population By Boroughs" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/9mhd-na2n

property e:9mhd-na2n t:meta.view v:id=9mhd-na2n v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/html/census/demo_tables_2010.shtml v:averageRating=0 v:name="New York City Population By Boroughs" v:attribution="Department of City Planning (DCP)"

property e:9mhd-na2n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9mhd-na2n t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough       | 2000_population | 2010_population | 
| =========== | ============= | =============== | =============== | 
| 1361349825  | Bronx         | 1332650         | 1385108         | 
| 1361349825  | Brooklyn      | 2465326         | 2504700         | 
| 1361349825  | Manhattan     | 1537195         | 1585873         | 
| 1361349825  | Queens        | 2229379         | 2230722         | 
| 1361349825  | Staten Island | 443728          | 468730          | 
```