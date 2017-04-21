# Mobile Telecommunication Franchise Poletop Installation Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mobile-telecommunication-franchise-poletop-installation-locations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tbgj-tdd6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tbgj-tdd6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tbgj-tdd6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tbgj-tdd6 |
| Name | Mobile Telecommunication Franchise Poletop Installation Locations |
| Attribution | Department of Information Technology and Telecommunications (DOITT) |
| Category | City Government |
| Tags | poletop, telecommunications, equipment |
| Created | 2016-07-19T19:02:38Z |
| Publication Date | 2017-01-31T23:49:53Z |

## Description

Locations of street light poles, traffic light poles and utility poles approved for the potential installation of?mobile telecommunications equipment by?companies authorized by the New York City Department of Information Technology and Telecommunications.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| No       |                | id                 | Id                 | text      | number      |
| Yes      | numeric metric | x_coord            | X Coord.           | number    | number      |
| Yes      | numeric metric | y_coord            | Y Coord.           | number    | number      |
| Yes      | series tag     | zone               | Zone               | text      | text        |
| Yes      | series tag     | on_street          | On street          | text      | text        |
| Yes      | series tag     | cross_street_1     | Cross street 1     | text      | text        |
| Yes      | series tag     | cross_street_2     | Cross street 2     | text      | text        |
| Yes      | series tag     | borough            | Borough            | text      | text        |
| Yes      | series tag     | pole_type          | Pole type          | text      | text        |
| Yes      | series tag     | bid_advisory       | BID Advisory       | text      | text        |
| Yes      | series tag     | historic_advisory  | Historic Advisory  | text      | text        |
| Yes      | series tag     | nysdot_advisory    | NYSDOT Advisory    | text      | text        |
| Yes      | series tag     | park_advisory      | Park Advisory      | text      | text        |
| Yes      | series tag     | port_auth_advisory | Port Auth Advisory | text      | text        |
| Yes      | series tag     | school_advisory    | School Advisory    | text      | text        |
| No       |                | submission_date    | Submission date    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,submission_date
```

## Data Commands

```ls
series e:tbgj-tdd6 d:2017-01-31T23:49:38.000Z t:historic_advisory="This pole is located within the following historic area: Upper West Side/Central Park West Historic District" t:borough=Manhattan t:pole_type="Streetlight Pole" t:zone=A t:on_street="CENTRAL PK W" t:cross_street_2="W 69 ST" t:cross_street_1="W 68 ST" m:y_coord=221185 m:x_coord=990378

series e:tbgj-tdd6 d:2017-01-31T23:49:38.000Z t:historic_advisory="This pole is located within the following historic area: Central Park" t:borough=Manhattan t:pole_type="Mixed Traffic And Street Pole" t:zone=A t:on_street="CENTRAL PK W" t:cross_street_2="W 71 ST" t:cross_street_1="TERRACE DR" m:y_coord=222025 m:x_coord=990920

series e:tbgj-tdd6 d:2017-01-31T23:49:38.000Z t:historic_advisory="This pole is located within the following historic area: Upper West Side/Central Park West Historic District" t:borough=Manhattan t:pole_type="Streetlight Pole" t:zone=A t:on_street="Central Park West" t:cross_street_2="81st Street" t:cross_street_1="77th Street" m:y_coord=223321 m:x_coord=991563
```

## Meta Commands

```ls
metric m:x_coord p:integer l:"X Coord." d:"X Coordinate" t:dataTypeName=number

metric m:y_coord p:integer l:"Y Coord." d:"Y Coordinate" t:dataTypeName=number

entity e:tbgj-tdd6 l:"Mobile Telecommunication Franchise Poletop Installation Locations" t:attribution="Department of Information Technology and Telecommunications (DOITT)" t:url=https://data.cityofnewyork.us/api/views/tbgj-tdd6

property e:tbgj-tdd6 t:meta.view v:id=tbgj-tdd6 v:category="City Government" v:averageRating=0 v:name="Mobile Telecommunication Franchise Poletop Installation Locations" v:attribution="Department of Information Technology and Telecommunications (DOITT)"

property e:tbgj-tdd6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tbgj-tdd6 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | id   | x_coord | y_coord | zone | on_street         | cross_street_1  | cross_street_2 | borough   | pole_type                     | bid_advisory | historic_advisory                                                                                            | nysdot_advisory | park_advisory | port_auth_advisory | school_advisory                                                                            | submission_date | 
| =========== | ==== | ======= | ======= | ==== | ================= | =============== | ============== | ========= | ============================= | ============ | ============================================================================================================ | =============== | ============= | ================== | ========================================================================================== | =============== | 
| 1485906578  | 2040 | 990378  | 221185  | A    | CENTRAL PK W      | W 68 ST         | W 69 ST        | Manhattan | Streetlight Pole              |              | This pole is located within the following historic area: Upper West Side/Central Park West Historic District |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2041 | 990920  | 222025  | A    | CENTRAL PK W      | TERRACE DR      | W 71 ST        | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Central Park                                        |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2042 | 991563  | 223321  | A    | Central Park West | 77th Street     | 81st Street    | Manhattan | Streetlight Pole              |              | This pole is located within the following historic area: Upper West Side/Central Park West Historic District |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2043 | 992114  | 224172  | A    | CENTRAL PK W      | TRANSVERSE RD 2 | W 82 St        | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Central Park                                        |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2044 | 992730  | 225433  | A    | Central Park West | 86th Street     | 87th Street    | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Upper West Side/Central Park West Historic District |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2047 | 993249  | 220420  | A    | 5th Avenue        | 71st Street     | 70th Street    | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Upper East Side Historic District                   |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2048 | 992744  | 219509  | A    | 5th Avenue        | 67th Street     | 66th Street    | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Upper East Side Historic District                   |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2049 | 992493  | 219051  | A    | 5th Avenue        | 65th Street     | 64th Street    | Manhattan | Mixed Traffic And Street Pole |              | This pole is located within the following historic area: Upper East Side Historic District                   |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2064 | 987699  | 221769  | A    | West End Avenue   | 65th Street     | 66th Street    | Manhattan | Mixed Traffic And Street Pole |              |                                                                                                              |                 |               |                    |                                                                                            | Jun-16-2005     | 
| 1485906578  | 2066 | 986690  | 219928  | A    | 11th Avenue       | 57th Street     | 58th Street    | Manhattan | Mixed Traffic And Street Pole |              |                                                                                                              |                 |               |                    | This pole is located within 20 feet of the following school: JOHN JAY COLLEGE BMW BUILDING | Jun-16-2005     | 
```