# Completed Percent for Art projects with artist information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/completed-percent-for-art-projects-with-artist-information-daac2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gzdv-qiga) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gzdv-qiga/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gzdv-qiga/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gzdv-qiga |
| Name | Completed Percent for Art projects with artist information |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | Recreation |
| Tags | dcla, cultural, culture, program, fund, funding, project, art, percent, percent for art, artist, cultural affairs |
| Created | 2013-03-01T20:26:47Z |
| Publication Date | 2016-02-26T20:54:10Z |

## Description

This data set contains the current listing of Department of Cultural Affairs completed Percent for Art projects.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | percent_project  | Percent Project  | text      | text        |
| Yes      | series tag  | artist           | Artist           | text      | text        |
| No       |             | address          | Address          | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | borough          | Borough          | text      | text        |
| Yes      | series tag  | council_district | Council District | text      | text        |
| Yes      | series tag  | community_board  | Community Board  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:gzdv-qiga d:2016-02-26T12:53:45.000Z t:percent_project="Van Arsdale High School" t:council_district="Brooklyn Council District #33" t:borough=Brooklyn t:artist="Crowe, Susan" t:community_board="Brooklyn Community Board #1" t:city=Brooklyn m:row_number.gzdv-qiga=1

series e:gzdv-qiga d:2016-02-26T12:53:45.000Z t:percent_project="Van Arsdale High School" t:council_district="Brooklyn Council District #33" t:borough=Brooklyn t:artist="Sanchez, Juan" t:community_board="Brooklyn Community Board #1" t:city=Brooklyn m:row_number.gzdv-qiga=2

series e:gzdv-qiga d:2016-02-26T12:53:45.000Z t:percent_project="Van Nest PS/IS" t:council_district="Bronx Council District #13" t:borough=Bronx t:artist="Oppenheimer, Sarah" t:community_board="Bronx Community Board #1" t:city=Bronx m:row_number.gzdv-qiga=3
```

## Meta Commands

```ls
metric m:row_number.gzdv-qiga p:long l:"Row Number"

entity e:gzdv-qiga l:"Completed Percent for Art projects with artist information" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/gzdv-qiga

property e:gzdv-qiga t:meta.view v:id=gzdv-qiga v:category=Recreation v:attributionLink=http://www.nyc.gov/html/dcla/html/panyc/projects.shtml v:averageRating=0 v:name="Completed Percent for Art projects with artist information" v:attribution="Department of Cultural Affairs (DCLA)"

property e:gzdv-qiga t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gzdv-qiga t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | percent_project                   | artist             | address                           | city     | borough   | council_district              | community_board              | 
| =========== | ================================= | ================== | ================================= | ======== | ========= | ============================= | ============================ | 
| 1456491225  | Van Arsdale High School           | Crowe, Susan       | 259 North 6th Street              | Brooklyn | Brooklyn  | Brooklyn Council District #33 | Brooklyn Community Board #1  | 
| 1456491225  | Van Arsdale High School           | Sanchez, Juan      | 258 North 6th Street              | Brooklyn | Brooklyn  | Brooklyn Council District #33 | Brooklyn Community Board #1  | 
| 1456491225  | Van Nest PS/IS                    | Oppenheimer, Sarah | 900 Van Nest Avenue               | Bronx    | Bronx     | Bronx Council District #13    | Bronx Community Board #1     | 
| 1456491225  | Wall Street Esplanade and Pier 11 | Cheng, Carl        | Maiden Lane and South Street      | New York | Manhattan | Manhattan Council District #1 | Manhattan Community Board #1 | 
| 1456491225  | Walton High School                | Fekner, John       | 2780 Reservoir Avenue             | Bronx    | Bronx     | Bronx Council District #11    | Bronx Community Board #7     | 
| 1456491225  | Walton High School                | Weems, Carrie Mae  | 2780 Reservoir Avenue             | Bronx    | Bronx     | Bronx Council District #11    | Bronx Community Board #7     | 
| 1456491225  | Walton High School                | Zweig, Janet       | 2780 Reservoir Avenue             | Bronx    | Bronx     | Bronx Council District #11    | Bronx Community Board #7     | 
| 1456491225  | Weeksville Heritage Center        | Booker, Chakaia    | 1698-1708 Bergen Street           | Brooklyn | Brooklyn  | Brooklyn Council District #41 | Brooklyn Community Board #8  | 
| 1456491225  | West Harlem Waterfront            | Ward, Nari         | 125th Street and the Hudson River | New York | Manhattan | Manhattan Council District #7 | Manhattan Community Board #9 | 
| 1456491225  | West Side High School             | Wexler, Allan      | 140 West 102nd Street             | New York | Manhattan | Manhattan Council District #8 | Manhattan Community Board #7 | 
```