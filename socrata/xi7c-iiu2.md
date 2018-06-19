# New York City Population By Community Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-population-by-community-districts-6486e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xi7c-iiu2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xi7c-iiu2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xi7c-iiu2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xi7c-iiu2 |
| Name | New York City Population By Community Districts |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city, planning, population, growth, community, district |
| Created | 2013-02-20T17:29:38Z |
| Publication Date | 2013-06-26T17:15:48Z |

## Description

New York City Population By Community Districts

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | borough         | Borough         | text      | text        |
| Yes      | series tag     | cd_number       | CD Number       | text      | number      |
| Yes      | series tag     | cd_name         | CD Name         | text      | text        |
| Yes      | numeric metric | 1970_population | 1970 Population | number    | number      |
| Yes      | numeric metric | 1980_population | 1980 Population | number    | number      |
| Yes      | numeric metric | 1990_population | 1990 Population | number    | number      |
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
series e:xi7c-iiu2 d:2013-02-20T09:29:39.000Z t:cd_number=1 t:cd_name="Melrose, Mott Haven, Port Morris" t:borough=Bronx m:1990_population=77214 m:2000_population=82159 m:1980_population=78441 m:2010_population=91497 m:1970_population=138557

series e:xi7c-iiu2 d:2013-02-20T09:29:39.000Z t:cd_number=2 t:cd_name="Hunts Point, Longwood" t:borough=Bronx m:1990_population=39443 m:2000_population=46824 m:1980_population=34399 m:2010_population=52246 m:1970_population=99493

series e:xi7c-iiu2 d:2013-02-20T09:29:39.000Z t:cd_number=3 t:cd_name="Morrisania, Crotona Park East" t:borough=Bronx m:1990_population=57162 m:2000_population=68574 m:1980_population=53635 m:2010_population=79762 m:1970_population=150636
```

## Meta Commands

```ls
metric m:1970_population p:integer l:"1970 Population" t:dataTypeName=number

metric m:1980_population p:integer l:"1980 Population" t:dataTypeName=number

metric m:1990_population p:integer l:"1990 Population" t:dataTypeName=number

metric m:2000_population p:integer l:"2000 Population" t:dataTypeName=number

metric m:2010_population p:integer l:"2010 Population" t:dataTypeName=number

entity e:xi7c-iiu2 l:"New York City Population By Community Districts" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/xi7c-iiu2

property e:xi7c-iiu2 t:meta.view v:id=xi7c-iiu2 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/dcp/html/census/demo_tables_2010.shtml v:averageRating=0 v:name="New York City Population By Community Districts" v:attribution="Department of City Planning (DCP)"

property e:xi7c-iiu2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xi7c-iiu2 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough | cd_number | cd_name                             | 1970_population | 1980_population | 1990_population | 2000_population | 2010_population | 
| =========== | ======= | ========= | =================================== | =============== | =============== | =============== | =============== | =============== | 
| 1361352579  | Bronx   | 1         | Melrose, Mott Haven, Port Morris    | 138557          | 78441           | 77214           | 82159           | 91497           | 
| 1361352579  | Bronx   | 2         | Hunts Point, Longwood               | 99493           | 34399           | 39443           | 46824           | 52246           | 
| 1361352579  | Bronx   | 3         | Morrisania, Crotona Park East       | 150636          | 53635           | 57162           | 68574           | 79762           | 
| 1361352579  | Bronx   | 4         | Highbridge, Concourse Village       | 144207          | 114312          | 119962          | 139563          | 146441          | 
| 1361352579  | Bronx   | 5         | University Hts., Fordham, Mt. Hope  | 121807          | 107995          | 118435          | 128313          | 128200          | 
| 1361352579  | Bronx   | 6         | East Tremont, Belmont               | 114137          | 65016           | 68061           | 75688           | 83268           | 
| 1361352579  | Bronx   | 7         | Bedford Park, Norwood, Fordham      | 113764          | 116827          | 128588          | 141411          | 139286          | 
| 1361352579  | Bronx   | 8         | Riverdale, Kingsbridge, Marble Hill | 103543          | 98275           | 97030           | 101332          | 101731          | 
| 1361352579  | Bronx   | 9         | Soundview, Parkchester              | 166442          | 167627          | 155970          | 167859          | 172298          | 
| 1361352579  | Bronx   | 10        | Throgs Nk., Co-op City, Pelham Bay  | 84948           | 106516          | 108093          | 115948          | 120392          | 
```