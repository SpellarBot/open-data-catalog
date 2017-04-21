# Energy Benchmarking, San Francisco Municipal Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-benchmarking-san-francisco-municipal-buildings) |
| Metadata | [Link](https://data.sfgov.org/api/views/eg8h-pgn3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/eg8h-pgn3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/eg8h-pgn3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | eg8h-pgn3 |
| Name | Energy Benchmarking, San Francisco Municipal Buildings |
| Category | Energy and Environment |
| Tags | environment, climate change, energy, sustainability |
| Created | 2016-02-12T17:40:18Z |
| Publication Date | 2016-02-16T18:51:51Z |

## Description

Updated October 2014: This report details the calendar year 2013 energy performance of over 470 San Francisco public buildings across 30 facility types. Includes ENERGY STAR ratings, where applicable. Accompanying dataset includes 2013 results in spreadsheet form. (Previous reports from 2011 and 2012 available on website.) You can read the 2013 report at http://bit.ly/sfbenchmark2013

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                         | Data Type | Render Type |
| ======== | ============== | ========================= | ============================ | ========= | =========== |
| Yes      | series tag     | sfpuc_code                | SFPUC Code                   | text      | text        |
| Yes      | series tag     | facility                  | Facility                     | text      | text        |
| Yes      | series tag     | notes                     | Notes                        | text      | text        |
| Yes      | series tag     | dpt                       | Dpt.                         | text      | text        |
| Yes      | series tag     | general_building_category | General Building Category    | text      | text        |
| Yes      | series tag     | facility_type             | Facility Type                | text      | text        |
| Yes      | series tag     | energy_star_bldg_type     | ENERGY STAR Bldg Type        | text      | text        |
| Yes      | time           | year_built                | Year Built                   | number    | number      |
| No       |                | year_renov                | Year Renov.                  | number    | number      |
| Yes      | numeric metric | 2013_building_area_sq_ft  | 2013 Building Area (sq. ft.) | number    | number      |
| Yes      | numeric metric | 2013_site_eui_kbtu_sq_ft  | 2013 Site EUI (kBtu/sq.ft.)  | number    | number      |
| Yes      | series tag     | 2013_energy_star_rating   | 2013 ENERGY STAR rating      | text      | text        |
```

## Time Field

```ls
Value = year_built
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = year_renov
```

## Data Commands

```ls
series e:eg8h-pgn3 d:2002-01-01T00:00:00.000Z t:general_building_category="Convention Centers" t:facility="Moscone Center West" t:2013_energy_star_rating=N/A t:facility_type="convention facility" t:energy_star_bldg_type=Other t:dpt=CFD t:sfpuc_code=1684 m:2013_site_eui_kbtu_sq_ft=74.3 m:2013_building_area_sq_ft=775000

series e:eg8h-pgn3 d:1981-01-01T00:00:00.000Z t:general_building_category="Convention Centers" t:facility="Moscone Center North & South" t:2013_energy_star_rating=N/A t:facility_type="convention facility" t:energy_star_bldg_type=Other t:notes="Adjacent facilities combined for benchmarking, due to shared mechanical systems." t:dpt=CFD t:sfpuc_code=XXX m:2013_site_eui_kbtu_sq_ft=58.3 m:2013_building_area_sq_ft=1296000

series e:eg8h-pgn3 d:1915-01-01T00:00:00.000Z t:general_building_category="Performance Halls" t:facility="Bill Graham Civic Auditorium" t:2013_energy_star_rating=N/A t:facility_type="performance hall" t:energy_star_bldg_type=Other t:notes="(2) Bill Graham Civic Auditorium and DPH Central Office receive steam from the Civic Center steam loop that is unmetered at individual facility level. For purposes of this report, the metered use at the steam loop is apportioned based on each building?s square footage, but may be over reported here due to leaks and other losses in the steam loop itself. A steam meter was installed at City Hall at the beginning of 2012." t:dpt=RED t:sfpuc_code=102 m:2013_site_eui_kbtu_sq_ft=67.8 m:2013_building_area_sq_ft=302250
```

## Meta Commands

```ls
metric m:2013_building_area_sq_ft p:integer l:"2013 Building Area (sq. ft.)" t:dataTypeName=number

metric m:2013_site_eui_kbtu_sq_ft p:float l:"2013 Site EUI (kBtu/sq.ft.)" t:dataTypeName=number

entity e:eg8h-pgn3 l:"Energy Benchmarking, San Francisco Municipal Buildings" t:url=https://data.sfgov.org/api/views/eg8h-pgn3

property e:eg8h-pgn3 t:meta.view v:id=eg8h-pgn3 v:category="Energy and Environment" v:averageRating=0 v:name="Energy Benchmarking, San Francisco Municipal Buildings"

property e:eg8h-pgn3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:eg8h-pgn3 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:eg8h-pgn3 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| sfpuc_code | facility                                         | notes                                                                                                                                                                                                                                                                                                                                                                                                                                  | dpt   | general_building_category | facility_type       | energy_star_bldg_type | year_built | year_renov | 2013_building_area_sq_ft | 2013_site_eui_kbtu_sq_ft | 2013_energy_star_rating | 
| ========== | ================================================ | ====================================================================================================================================================================================================================================================================================================================================================================================================================================== | ===== | ========================= | =================== | ===================== | ========== | ========== | ======================== | ======================== | ======================= | 
| 1684       | Moscone Center West                              |                                                                                                                                                                                                                                                                                                                                                                                                                                        | CFD   | Convention Centers        | convention facility | Other                 | 2002       |            | 775000                   | 74.3                     | N/A                     | 
| XXX        | Moscone Center North & South                     | Adjacent facilities combined for benchmarking, due to shared mechanical systems.                                                                                                                                                                                                                                                                                                                                                       | CFD   | Convention Centers        | convention facility | Other                 | 1981       | 1992       | 1296000                  | 58.3                     | N/A                     | 
| 102        | Bill Graham Civic Auditorium                     | (2) Bill Graham Civic Auditorium and DPH Central Office receive steam from the Civic Center steam loop that is unmetered at individual facility level. For purposes of this report, the metered use at the steam loop is apportioned based on each building?s square footage, but may be over reported here due to leaks and other losses in the steam loop itself. A steam meter was installed at City Hall at the beginning of 2012. | RED   | Performance Halls         | performance hall    | Other                 | 1915       | 1989       | 302250                   | 67.8                     | N/A                     | 
| XXX        | War Memorial Veterans Building & Opera House     | This location was under construction or vacant for an extended period of time during a portion of calendar years 2012 or 2013.                                                                                                                                                                                                                                                                                                         | WMPAC | Performance Halls         | performance hall    | Other                 | 1932       |            | 529700                   | 67.1                     | N/A                     | 
| 468        | Davies Symphony Hall / Zellerbach Rehearsal Hall | Adjacent facilities combined for benchmarking, due to shared mechanical systems.                                                                                                                                                                                                                                                                                                                                                       | WMPAC | Performance Halls         | performance hall    | Other                 | 1980       |            | 229500                   | 55.9                     | N/A                     | 
| 317        | GGP -- Sharon Arts Studio                        |                                                                                                                                                                                                                                                                                                                                                                                                                                        | RPD   | Museums and Art           | art/cultural center | Other                 | 1888       | 1992       | 11376                    | 77.1                     | N/A                     | 
| 378        | Randall Museum                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                        | RPD   | Museums and Art           | art/cultural center | Other                 | 1951       |            | 32030                    | 72.3                     | N/A                     | 
| 3          | SOMArts Cultural Center                          |                                                                                                                                                                                                                                                                                                                                                                                                                                        | SFAC  | Museums and Art           | art/cultural center | Other                 | 1906       |            | 17844                    | 32.2                     | N/A                     | 
| 302        | Harvey Milk Center for the Arts                  |                                                                                                                                                                                                                                                                                                                                                                                                                                        | RPD   | Museums and Art           | art/cultural center | Other                 | 1950       | 2009       | 23125                    | 28.9                     | N/A                     | 
| 4          | Mission Cultural Center for Latino Arts          |                                                                                                                                                                                                                                                                                                                                                                                                                                        | SFAC  | Museums and Art           | art/cultural center | Other                 | 1948       |            | 32230                    | 28.3                     | N/A                     | 
```