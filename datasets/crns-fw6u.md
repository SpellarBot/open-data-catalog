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
| Publication Date | 2013-03-29T13:19:07Z |

## Description

Community Facilities (Centers) that are on NYCHA property with programs either sponsored by NYCHA or by a non-NYCHA entity. All programs are open to the public. The file contains development name, address, city, state, zipcode, telephone #, sponsoring organization and contact person. 

This file is updated on a need basis.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | type           | TYPE           | text      | text        |
| Yes      | series tag  | funding_agency | FUNDING AGENCY | text      | text        |
| Yes      | series tag  | borough        | BOROUGH        | text      | text        |
| Yes      | series tag  | program_type   | PROGRAM TYPE   | text      | text        |
| Yes      | series tag  | count_as       | COUNT AS       | text      | text        |
| Yes      | series tag  | development    | DEVELOPMENT    | text      | text        |
| No       |             | address        | ADDRESS        | text      | text        |
| Yes      | series tag  | city           | CITY           | text      | text        |
| Yes      | series tag  | state          | STATE          | text      | text        |
| Yes      | series tag  | zip            | ZIP            | text      | text        |
| Yes      | series tag  | telephone      | TELEPHONE      | text      | text        |
| Yes      | series tag  | sponsor        | SPONSOR        | text      | text        |
| Yes      | series tag  | director       | DIRECTOR       | text      | text        |
| No       |             | month          | MONTH          | text      | text        |
| No       |             | year           | YEAR           | number    | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = address,year,month
```

## Data Commands

```ls
series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:program_type=Closed t:zip=10456 t:count_as=Pending t:development="1162-1176 'Washington Ave." t:state=NY t:borough=Bronx t:type=NYCHA t:sponsor=NYCHA t:city=Bronx m:row_number.crns-fw6u=1

series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:program_type=Closed t:zip=10455 t:count_as=Vacant t:development=Adams t:state=NY t:borough=Bronx t:type=NYCHA t:sponsor=NYCHA t:city=Bronx m:row_number.crns-fw6u=2

series e:crns-fw6u d:2013-02-01T00:00:00.000Z t:program_type=Closed t:zip=10472 t:count_as=Vacant t:development="Bronx River" t:state=NY t:borough=Bronx t:type=NYCHA t:sponsor=NYCHA t:city=Bronx m:row_number.crns-fw6u=3
```

## Meta Commands

```ls
metric m:row_number.crns-fw6u p:long l:"Row Number"

entity e:crns-fw6u l:"Directory of NYCHA Community Facilities" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/crns-fw6u

property e:crns-fw6u t:meta.view v:id=crns-fw6u v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/nycha/html/ccschtml/communitycenters.shtml v:averageRating=0 v:name="Directory of NYCHA Community Facilities" v:attribution="New York City Housing Authority (NYCHA)"

property e:crns-fw6u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:crns-fw6u t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| type  | funding_agency | borough | program_type | count_as | development                | address                | city  | state | zip   | telephone | sponsor | director | month    | year | 
| ===== | ============== | ======= | ============ | ======== | ========================== | ====================== | ===== | ===== | ===== | ========= | ======= | ======== | ======== | ==== | 
| NYCHA |                | Bronx   | Closed       | Pending  | 1162-1176 'Washington Ave. | 1162 Washington Avenue | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Adams                      | 755 East 152nd Street  | Bronx | NY    | 10455 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Bronx River                | 1625 East 174th Street | Bronx | NY    | 10472 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Bronx River Add            | 1350 Manor Avenue      | Bronx | NY    | 10472 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Butler                     | 1450 Webster Avenue    | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Edenwald                   | 1135 229th Dr South    | Bronx | NY    | 10466 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Edenwald                   | 1141 East 229th Street | Bronx | NY    | 10466 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Forest                     | 1005 Tinton Avenue     | Bronx | NY    | 10456 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Gun Hill                   | 744 Gunhill Road       | Bronx | NY    | 10467 |           | NYCHA   |          | February | 2013 | 
| NYCHA |                | Bronx   | Closed       | Vacant   | Gun Hill                   | 3450 White Plains Road | Bronx | NY    | 10467 |           | NYCHA   |          | February | 2013 | 
```