# Motor Vehicle Crash Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crash-reports-ec91d) |
| Metadata | [Link](https://data.somervillema.gov/api/views/d5qn-yy3v) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/d5qn-yy3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/d5qn-yy3v/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | d5qn-yy3v |
| Name | Motor Vehicle Crash Reports |
| Category | Public Safety |
| Tags | public safety, bicycle, pedestrian |
| Created | 2016-08-25T13:04:27Z |
| Publication Date | 2016-08-25T13:06:15Z |

## Description

Motor vehicle crash report data from the Somerville Police for roads maintained by the City.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| No       |                | id                               | id                               | text          | number        |
| Yes      | time           | date_time                        | date_time                        | calendar_date | calendar_date |
| No       |                | address                          | address                          | text          | text          |
| Yes      | numeric metric | lon                              | lon                              | number        | number        |
| No       |                | lat                              | lat                              | number        | number        |
| Yes      | numeric metric | weather                          | Weather                          | number        | number        |
| Yes      | numeric metric | road_surface                     | road_surface                     | number        | number        |
| Yes      | numeric metric | traffic_control_device           | traffic_control_device           | number        | number        |
| Yes      | series tag     | intersection_type                | intersection_type                | text          | number        |
| Yes      | numeric metric | traffic_way_desc                 | traffic_way_desc                 | number        | number        |
| Yes      | numeric metric | collision_manner                 | collision_manner                 | number        | number        |
| Yes      | numeric metric | num_involved_vehicles            | num_involved_vehicles            | number        | number        |
| Yes      | numeric metric | vehicle1_configuration           | vehicle1_configuration           | number        | number        |
| Yes      | numeric metric | driver1_contrib1                 | driver1_contrib1                 | number        | number        |
| Yes      | numeric metric | driver1_contrib2                 | driver1_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle2_configuration           | vehicle2_configuration           | number        | number        |
| Yes      | numeric metric | driver2_contrib1                 | driver2_contrib1                 | number        | number        |
| Yes      | numeric metric | driver2_contrib2                 | driver2_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle3_configuration           | vehicle3_configuration           | number        | number        |
| Yes      | numeric metric | driver3_contrib1                 | driver3_contrib1                 | number        | number        |
| Yes      | numeric metric | driver3_contrib2                 | driver3_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle4_configuration           | vehicle4_configuration           | number        | number        |
| Yes      | numeric metric | driver4_contrib1                 | driver4_contrib1                 | number        | number        |
| Yes      | numeric metric | driver4_contrib2                 | driver4_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle5_configuration           | vehicle5_configuration           | number        | number        |
| Yes      | numeric metric | driver5_contrib1                 | driver5_contrib1                 | number        | number        |
| Yes      | numeric metric | driver5_contrib2                 | driver5_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle6_configuration           | vehicle6_configuration           | number        | number        |
| Yes      | numeric metric | driver6_contrib1                 | driver6_contrib1                 | number        | number        |
| Yes      | numeric metric | driver6_contrib2                 | driver6_contrib2                 | number        | number        |
| Yes      | numeric metric | vehicle7_configuration           | vehicle7_configuration           | number        | number        |
| Yes      | numeric metric | driver7_contrib1                 | driver7_contrib1                 | number        | number        |
| Yes      | numeric metric | driver7_contrib2                 | driver7_contrib2                 | number        | number        |
| Yes      | numeric metric | bicycle                          | Bicycle                          | number        | number        |
| Yes      | numeric metric | pedestrian                       | Pedestrian                       | number        | number        |
| Yes      | numeric metric | non_mv                           | non_mv                           | number        | number        |
| Yes      | numeric metric | non_motorist_location            | non_motorist_location            | number        | number        |
| Yes      | numeric metric | non_motorist_action              | non_motorist_action              | number        | number        |
| Yes      | series tag     | non_motorist_type                | non_motorist_type                | text          | number        |
| Yes      | numeric metric | manner_of_non_motorist_collision | manner_of_non_motorist_collision | number        | number        |
| Yes      | numeric metric | injury                           | Injury                           | number        | number        |
| Yes      | numeric metric | multiple                         | Multiple                         | number        | number        |
| Yes      | numeric metric | gender1                          | Gender1                          | number        | number        |
| Yes      | numeric metric | age1                             | Age1                             | number        | number        |
| Yes      | numeric metric | severity1                        | Severity1                        | number        | number        |
| Yes      | numeric metric | hospital1                        | Hospital1                        | number        | number        |
| Yes      | numeric metric | gender2                          | Gender2                          | number        | number        |
| Yes      | numeric metric | age2                             | Age2                             | number        | number        |
| Yes      | numeric metric | severity2                        | Severity2                        | number        | number        |
| Yes      | numeric metric | hospital2                        | Hospital2                        | number        | number        |
| Yes      | numeric metric | gender3                          | Gender3                          | number        | number        |
| Yes      | numeric metric | age3                             | Age3                             | number        | number        |
| Yes      | numeric metric | severity3                        | Severity3                        | number        | number        |
| Yes      | numeric metric | hospital3                        | Hospital3                        | number        | number        |
| Yes      | numeric metric | gender4                          | Gender4                          | number        | number        |
| Yes      | numeric metric | age4                             | Age4                             | number        | number        |
| Yes      | numeric metric | severity4                        | Severity4                        | number        | number        |
| Yes      | numeric metric | hospital4                        | Hospital4                        | number        | number        |
| Yes      | numeric metric | gender5                          | Gender5                          | number        | number        |
| Yes      | numeric metric | age5                             | Age5                             | number        | number        |
| Yes      | numeric metric | severity5                        | Severity5                        | number        | number        |
| Yes      | numeric metric | hospital5                        | Hospital5                        | number        | number        |
| Yes      | numeric metric | city_vehicle                     | city_vehicle                     | number        | number        |
| Yes      | series tag     | notes                            | Notes                            | text          | text          |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,lat
```

## Data Commands

```ls
series e:d5qn-yy3v d:2010-01-02T22:21:00.000Z m:lon=-71.0867525 m:pedestrian=0 m:injury=0 m:city_vehicle=0 m:non_mv=0 m:bicycle=0

series e:d5qn-yy3v d:2010-01-03T14:45:00.000Z m:lon=-71.0960659 m:pedestrian=0 m:injury=0 m:city_vehicle=0 m:non_mv=0 m:bicycle=0

series e:d5qn-yy3v d:2010-01-05T11:24:00.000Z m:lon=-71.1143386 m:pedestrian=0 m:injury=0 m:city_vehicle=0 m:non_mv=0 m:bicycle=0
```

## Meta Commands

```ls
metric m:lon p:float l:lon t:dataTypeName=number

metric m:weather p:integer l:Weather t:dataTypeName=number

metric m:road_surface p:integer l:road_surface t:dataTypeName=number

metric m:traffic_control_device p:integer l:traffic_control_device t:dataTypeName=number

metric m:traffic_way_desc p:integer l:traffic_way_desc t:dataTypeName=number

metric m:collision_manner p:integer l:collision_manner t:dataTypeName=number

metric m:num_involved_vehicles p:integer l:num_involved_vehicles t:dataTypeName=number

metric m:vehicle1_configuration p:integer l:vehicle1_configuration t:dataTypeName=number

metric m:driver1_contrib1 p:integer l:driver1_contrib1 t:dataTypeName=number

metric m:driver1_contrib2 p:integer l:driver1_contrib2 t:dataTypeName=number

metric m:vehicle2_configuration p:integer l:vehicle2_configuration t:dataTypeName=number

metric m:driver2_contrib1 p:integer l:driver2_contrib1 t:dataTypeName=number

metric m:driver2_contrib2 p:integer l:driver2_contrib2 t:dataTypeName=number

metric m:vehicle3_configuration p:integer l:vehicle3_configuration t:dataTypeName=number

metric m:driver3_contrib1 p:integer l:driver3_contrib1 t:dataTypeName=number

metric m:driver3_contrib2 p:integer l:driver3_contrib2 t:dataTypeName=number

metric m:vehicle4_configuration p:integer l:vehicle4_configuration t:dataTypeName=number

metric m:driver4_contrib1 p:integer l:driver4_contrib1 t:dataTypeName=number

metric m:driver4_contrib2 p:integer l:driver4_contrib2 t:dataTypeName=number

metric m:vehicle5_configuration p:integer l:vehicle5_configuration t:dataTypeName=number

metric m:driver5_contrib1 p:integer l:driver5_contrib1 t:dataTypeName=number

metric m:driver5_contrib2 p:integer l:driver5_contrib2 t:dataTypeName=number

metric m:vehicle6_configuration p:integer l:vehicle6_configuration t:dataTypeName=number

metric m:driver6_contrib1 p:integer l:driver6_contrib1 t:dataTypeName=number

metric m:driver6_contrib2 p:long l:driver6_contrib2 t:dataTypeName=number

metric m:vehicle7_configuration p:integer l:vehicle7_configuration t:dataTypeName=number

metric m:driver7_contrib1 p:long l:driver7_contrib1 t:dataTypeName=number

metric m:driver7_contrib2 p:long l:driver7_contrib2 t:dataTypeName=number

metric m:bicycle p:integer l:Bicycle t:dataTypeName=number

metric m:pedestrian p:integer l:Pedestrian t:dataTypeName=number

metric m:non_mv p:integer l:non_mv t:dataTypeName=number

metric m:non_motorist_location p:integer l:non_motorist_location t:dataTypeName=number

metric m:non_motorist_action p:integer l:non_motorist_action t:dataTypeName=number

metric m:manner_of_non_motorist_collision p:integer l:manner_of_non_motorist_collision t:dataTypeName=number

metric m:injury p:integer l:Injury t:dataTypeName=number

metric m:multiple p:integer l:Multiple t:dataTypeName=number

metric m:gender1 p:integer l:Gender1 t:dataTypeName=number

metric m:age1 p:integer l:Age1 t:dataTypeName=number

metric m:severity1 p:integer l:Severity1 t:dataTypeName=number

metric m:hospital1 p:integer l:Hospital1 t:dataTypeName=number

metric m:gender2 p:integer l:Gender2 t:dataTypeName=number

metric m:age2 p:integer l:Age2 t:dataTypeName=number

metric m:severity2 p:integer l:Severity2 t:dataTypeName=number

metric m:hospital2 p:integer l:Hospital2 t:dataTypeName=number

metric m:gender3 p:integer l:Gender3 t:dataTypeName=number

metric m:age3 p:integer l:Age3 t:dataTypeName=number

metric m:severity3 p:integer l:Severity3 t:dataTypeName=number

metric m:hospital3 p:integer l:Hospital3 t:dataTypeName=number

metric m:gender4 p:integer l:Gender4 t:dataTypeName=number

metric m:age4 p:integer l:Age4 t:dataTypeName=number

metric m:severity4 p:integer l:Severity4 t:dataTypeName=number

metric m:hospital4 p:integer l:Hospital4 t:dataTypeName=number

metric m:gender5 p:integer l:Gender5 t:dataTypeName=number

metric m:age5 p:integer l:Age5 t:dataTypeName=number

metric m:severity5 p:integer l:Severity5 t:dataTypeName=number

metric m:hospital5 p:integer l:Hospital5 t:dataTypeName=number

metric m:city_vehicle p:integer l:city_vehicle t:dataTypeName=number

entity e:d5qn-yy3v l:"Motor Vehicle Crash Reports" t:url=https://data.somervillema.gov/api/views/d5qn-yy3v

property e:d5qn-yy3v t:meta.view v:id=d5qn-yy3v v:category="Public Safety" v:averageRating=0 v:name="Motor Vehicle Crash Reports"

property e:d5qn-yy3v t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:d5qn-yy3v t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:d5qn-yy3v t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| id | date_time           | address                                                          | lon         | lat        | weather | road_surface | traffic_control_device | intersection_type | traffic_way_desc | collision_manner | num_involved_vehicles | vehicle1_configuration | driver1_contrib1 | driver1_contrib2 | vehicle2_configuration | driver2_contrib1 | driver2_contrib2 | vehicle3_configuration | driver3_contrib1 | driver3_contrib2 | vehicle4_configuration | driver4_contrib1 | driver4_contrib2 | vehicle5_configuration | driver5_contrib1 | driver5_contrib2 | vehicle6_configuration | driver6_contrib1 | driver6_contrib2 | vehicle7_configuration | driver7_contrib1 | driver7_contrib2 | bicycle | pedestrian | non_mv | non_motorist_location | non_motorist_action | non_motorist_type | manner_of_non_motorist_collision | injury | multiple | gender1 | age1 | severity1 | hospital1 | gender2 | age2 | severity2 | hospital2 | gender3 | age3 | severity3 | hospital3 | gender4 | age4 | severity4 | hospital4 | gender5 | age5 | severity5 | hospital5 | city_vehicle | notes | 
| == | =================== | ================================================================ | =========== | ========== | ======= | ============ | ====================== | ================= | ================ | ================ | ===================== | ====================== | ================ | ================ | ====================== | ================ | ================ | ====================== | ================ | ================ | ====================== | ================ | ================ | ====================== | ================ | ================ | ====================== | ================ | ================ | ====================== | ================ | ================ | ======= | ========== | ====== | ===================== | =================== | ================= | ================================ | ====== | ======== | ======= | ==== | ========= | ========= | ======= | ==== | ========= | ========= | ======= | ==== | ========= | ========= | ======= | ==== | ========= | ========= | ======= | ==== | ========= | ========= | ============ | ===== | 
| 1  | 2010-01-02T22:21:00 | BROADWAY and GARFIELD AVENUE, Somerville, MA                     | -71.0867525 | 42.3889844 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 2  | 2010-01-03T14:45:00 | BROADWAY and FENWICK STREET, Somerville, MA                      | -71.0960659 | 42.3939409 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 3  | 2010-01-05T11:24:00 | POWDER HOUSE SQUARE and BROADWAY, Somerville, MA                 | -71.1143386 | 42.4006346 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 4  | 2010-01-06T16:10:00 | BOW STREET and WARREN AVENUE, Somerville, MA                     | -71.0967461 | 42.3803419 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 5  | 2010-01-06T16:19:00 | HIGHLAND AVENUE and TOWER STREET, Somerville, MA                 | -71.108706  | 42.3905439 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 6  | 2010-01-07T05:00:00 | WASHINGTON STREET and BEACON STREET, Somerville, MA              | -71.106382  | 42.3782892 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 7  | 2010-01-07T08:40:00 | 308 MCGRATH HIGHWAY, Somerville, MA                              | -71.0899388 | 42.3791845 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 0      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 8  | 2010-01-07T17:37:00 | HOLLAND STREET and CAMERON AVENUE, Somerville, MA                | -71.126181  | 42.401052  |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 0          | 0      |                       |                     |                   |                                  | 1      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 9  | 2010-01-07T07:27:00 | 1360 BROADWAY, Somerville, MA                                    | -71.1330505 | 42.4066392 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 0       | 1          | 0      |                       |                     |                   |                                  | 1      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
| 10 | 2010-01-07T17:27:00 | COLLEGE AVENUE and CHAPEL STREET and HALL AVENUE, Somerville, MA | -71.1189719 | 42.3979833 |         |              |                        |                   |                  |                  |                       |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  |                        |                  |                  | 1       | 0          | 0      |                       |                     |                   |                                  | 1      |          |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           |         |      |           |           | 0            |       | 
```