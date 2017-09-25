# Directory of NYCHA Community Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-nycha-community-facilities-f87c8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/crns-fw6u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/crns-fw6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/crns-fw6u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | crns-fw6u |
| Name | Directory of NYCHA Community Facilities |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Social Services |
| Tags | nycha, nyc housing, community center, community facility, senior center, lunch program, day care, head start, health clinic |
| Created | 2013-03-28T21:01:03Z |
| Publication Date | 2017-09-16T21:23:10Z |

## Description

Community Facilities (Centers) that are on NYCHA property with programs either sponsored by NYCHA or by a non-NYCHA entity. All programs are open to the public. The file contains development name, address, city, state, zipcode, telephone #, sponsoring organization and contact person. 

This file is updated on a need basis.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | type             | TYPE             | text      | text        |
| Yes      | series tag     | funding_agency   | FUNDING AGENCY   | text      | text        |
| Yes      | series tag     | borough          | BOROUGH          | text      | text        |
| Yes      | series tag     | program_type     | PROGRAM TYPE     | text      | text        |
| Yes      | series tag     | count_as         | COUNT AS         | text      | text        |
| Yes      | series tag     | development      | DEVELOPMENT      | text      | text        |
| No       |                | address          | ADDRESS          | text      | text        |
| Yes      | series tag     | city             | CITY             | text      | text        |
| Yes      | series tag     | state            | STATE            | text      | text        |
| Yes      | series tag     | zip              | Postcode         | text      | text        |
| Yes      | series tag     | telephone        | TELEPHONE        | text      | text        |
| Yes      | series tag     | sponsor          | SPONSOR          | text      | text        |
| Yes      | series tag     | director         | DIRECTOR         | text      | text        |
| No       |                | month            | MONTH            | text      | text        |
| No       |                | year             | YEAR             | number    | text        |
| No       |                | latitude         | Latitude         | number    | number      |
| No       |                | longitude        | Longitude        | number    | number      |
| Yes      | numeric metric | community_board  | Community Board  | number    | number      |
| Yes      | series tag     | council_district | Council District | text      | number      |
| Yes      | numeric metric | census_tract     | Census Tract     | number    | number      |
| Yes      | numeric metric | bin              | BIN              | number    | number      |
| Yes      | numeric metric | bbl              | BBL              | number    | number      |
| Yes      | series tag     | nta              | NTA              | text      | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude,year,month
```

## Data Commands

```ls
series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:zip=10456 t:sponsor=NYCHA t:program_type=Closed t:count_as=Pending t:development="1162-1176 'Washington Ave." t:city=Bronx t:nta=Claremont-Bathgate t:borough=Bronx t:state=NY t:type=NYCHA t:council_district=16 m:bin=2001312 m:community_board=3 m:bbl=2023720001 m:census_tract=145

series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:zip=10455 t:sponsor=NYCHA t:program_type=Closed t:count_as=Vacant t:development=Adams t:city=Bronx t:nta="Melrose South-Mott Haven North" t:borough=Bronx t:state=NY t:type=NYCHA t:council_district=17 m:bin=2091979 m:community_board=1 m:bbl=2026540002 m:census_tract=79

series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:zip=10472 t:sponsor=NYCHA t:program_type=Closed t:count_as=Vacant t:development="Bronx River" t:city=Bronx t:nta="West Farms-Bronx River" t:borough=Bronx t:state=NY t:type=NYCHA t:council_district=18 m:bin=2092902 m:community_board=9 m:bbl=2038860002 m:census_tract=62
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:crns-fw6u l:"Directory of NYCHA Community Facilities" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/crns-fw6u

property e:crns-fw6u t:meta.view d:2017-09-25T07:31:51.521Z v:averageRating=0 v:name="Directory of NYCHA Community Facilities" v:attribution="New York City Housing Authority (NYCHA)" v:attributionLink=http://www.nyc.gov/html/nycha/html/ccschtml/communitycenters.shtml v:id=crns-fw6u v:category="Social Services"

property e:crns-fw6u t:meta.view.owner d:2017-09-25T07:31:51.521Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:crns-fw6u t:meta.view.tableauthor d:2017-09-25T07:31:51.521Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| type  | funding_agency | borough | program_type | count_as | development                | address                | city  | state | zip   | telephone | sponsor | director | month    | year | latitude  | longitude  | community_board | council_district | census_tract | bin     | bbl        | nta                             | 
| ===== | ============== | ======= | ============ | ======== | ========================== | ====================== | ===== | ===== | ===== | ========= | ======= | ======== | ======== | ==== | ========= | ========== | =============== | ================ | ============ | ======= | ========== | =============================== | 
| NYCHA |                | Bronx   | Closed       | Pending  | 1162-1176 'Washington Ave. | 1162 Washington Avenue | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 40.82986  | -73.90769  | 3               | 16               | 145          | 2001312 | 2023720001 | Claremont-Bathgate              | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Adams                      | 755 East 152nd Street  | Bronx | NY    | 10455 |           | NYCHA   |          | February | 2013 | 40.815818 | -73.90699  | 1               | 17               | 79           | 2091979 | 2026540002 | Melrose South-Mott Haven North  | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Bronx River                | 1625 East 174th Street | Bronx | NY    | 10472 |           | NYCHA   |          | February | 2013 | 40.834024 | -73.875601 | 9               | 18               | 62           | 2092902 | 2038860002 | West Farms-Bronx River          | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Bronx River Add            | 1350 Manor Avenue      | Bronx | NY    | 10472 |           | NYCHA   |          | February | 2013 | 40.833016 | -73.877331 | 9               | 18               | 56           | 2027475 | 2038660031 | West Farms-Bronx River          | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Butler                     | 1450 Webster Avenue    | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 40.837646 | -73.906504 | 3               | 16               | 14702        | 2092076 | 2028950001 | Claremont-Bathgate              | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Edenwald                   | 1135 229th Dr South    | Bronx | NY    | 10466 |           | NYCHA   |          | February | 2013 | 40.885849 | -73.845823 | 12              | 12               | 458          | 2094157 | 2049050001 | Eastchester-Edenwald-Baychester | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Edenwald                   | 1141 East 229th Street | Bronx | NY    | 10466 |           | NYCHA   |          | February | 2013 | 40.886304 | -73.845367 | 12              | 12               | 458          | 2094151 | 2049050001 | Eastchester-Edenwald-Baychester | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Forest                     | 1005 Tinton Avenue     | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 40.824078 | -73.902585 | 3               | 16               | 133          | 2091962 | 2026390001 | Morrisania-Melrose              | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Gun Hill                   | 744 Gunhill Road       | Bronx | NY    | 10467 |           | NYCHA   |          | February | 2013 | 40.876876 | -73.864868 | 12              | 12               | 374          | 2093515 | 2046290050 | Williamsbridge-Olinville        | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Gun Hill                   | 3450 White Plains Road | Bronx | NY    | 10467 |           | NYCHA   |          | February | 2013 | 40.876214 | -73.866978 | 12              | 12               | 374          | 2093518 | 2046290050 | Williamsbridge-Olinville        | 
```