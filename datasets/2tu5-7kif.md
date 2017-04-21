# Baton Rouge Traffic Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baton-rouge-traffic-incidents) |
| Metadata | [Link](https://data.brla.gov/api/views/2tu5-7kif) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/2tu5-7kif/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/2tu5-7kif/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 2tu5-7kif |
| Name | Baton Rouge Traffic Incidents |
| Attribution | Baton Rouge Police Department |
| Category | Transportation and Infrastructure |
| Tags | traffic, accident, crash, police, brpd |
| Created | 2015-01-16T15:14:38Z |
| Publication Date | 2017-02-04T03:01:32Z |

## Description

Traffic incident reports handled by Baton Rouge City Police

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | file_number         | FILE#               | text          | text          |
| No       |                | crash_date          | CRASH DATE          | calendar_date | calendar_date |
| No       |                | crash_time          | CRASH TIME          | text          | text          |
| Yes      | numeric metric | tot_veh             | TOT VEH             | number        | number        |
| Yes      | series tag     | district            | DISTRICT            | text          | text          |
| Yes      | series tag     | zone                | ZONE                | text          | text          |
| Yes      | series tag     | subzone             | SUBZONE             | text          | text          |
| Yes      | series tag     | st_number           | STREET#             | text          | number        |
| Yes      | series tag     | st_direction        | STREET DIRECTION    | text          | text          |
| Yes      | series tag     | st_name             | STREET NAME         | text          | text          |
| Yes      | series tag     | st_type             | STREET TYPE         | text          | text          |
| Yes      | series tag     | formattedstreet     | FORMATTED STREET    | text          | text          |
| Yes      | series tag     | occured_on          | OCCURED ON          | text          | text          |
| Yes      | series tag     | hit_run             | HIT&RUN             | text          | text          |
| Yes      | series tag     | train_involved      | TRAIN INVOLVED      | text          | text          |
| Yes      | series tag     | fatality            | FATALITY            | text          | text          |
| Yes      | series tag     | injury              | INJURY              | text          | text          |
| Yes      | series tag     | pedestrian          | PEDESTRIAN          | text          | text          |
| Yes      | series tag     | at_intersection     | AT INTERSECTION     | text          | text          |
| Yes      | series tag     | closest_street      | CLOSEST STREET      | text          | text          |
| Yes      | series tag     | manner_of_collision | MANNER OF COLLISION | text          | text          |
| Yes      | series tag     | surface_cond        | SURFACE CONDITION   | text          | text          |
| Yes      | series tag     | surface_type        | SURFACE TYPE        | text          | text          |
| Yes      | series tag     | road_condition      | ROAD CONDITION      | text          | text          |
| Yes      | series tag     | road_type           | ROAD TYPE           | text          | text          |
| Yes      | series tag     | alignment           | ALIGNMENT           | text          | text          |
| Yes      | series tag     | primary_factor      | PRIMARY FACTOR      | text          | text          |
| Yes      | series tag     | second_factor       | SECOND FACTOR       | text          | text          |
| Yes      | series tag     | weather             | WEATHER             | text          | text          |
| Yes      | series tag     | location_kind       | LOCATION KIND       | text          | text          |
| Yes      | series tag     | relation_roadway    | RELATION ROADWAY    | text          | text          |
| Yes      | series tag     | access_control      | ACCESS CONTROL      | text          | text          |
| Yes      | series tag     | lighting            | LIGHTING            | text          | text          |
```

## Time Field

```ls
Value = crash_date-crash_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-hh:mm a
```

## Series Fields

```ls
Excluded Fields = crash_time,crash_date
```

## Data Commands

```ls
series e:2tu5-7kif d:2015-06-07T22:14:00.000Z t:alignment=STRAIGHT-LEVEL t:subzone=3 t:file_number=15-00007788 t:relation_roadway="ON ROADWAY" t:occured_on="CITY STREET" t:st_number=1800 t:second_factor="CONDITION OF DRIVER" t:st_name=BRIGHTSIDE t:lighting="DARK - CONTINUOUS STREET" t:closest_street="BRIGHTSIDE VIEW DR" t:location_kind="BUSINESS, MIXED RESIDENTIAL" t:surface_cond=WET t:manner_of_collision="REAR END" t:injury=X t:st_type=DR t:weather=CLOUDY t:access_control="NO CONTROL (UNLIMITED ACCESS TO ROADWAY)" t:primary_factor=VIOLATIONS t:surface_type=CONCRETE t:district=2 t:road_type="TWO-WAY ROAD WITH NO PHYSICAL SEPARATION" t:formattedstreet="1800  BRIGHTSIDE DR" t:zone=C t:road_condition="NO ABNORMALITIES" m:tot_veh=3

series e:2tu5-7kif d:2010-06-18T20:35:00.000Z t:alignment=STRAIGHT-LEVEL t:subzone=2 t:file_number=10-00003768 t:relation_roadway="ON ROADWAY" t:occured_on="U.S. HWY" t:st_number=11301 t:second_factor="MOVEMENT PRIOR TO CRASH" t:st_name=FLORIDA t:lighting=DAYLIGHT t:at_intersection=X t:closest_street="N SHERWOOD FOREST  BL" t:location_kind="BUSINESS, MIXED RESIDENTIAL" t:surface_cond=DRY t:manner_of_collision="RIGHT ANGLE" t:st_type=BL t:weather=CLEAR t:access_control="NO CONTROL (UNLIMITED ACCESS TO ROADWAY)" t:primary_factor=VIOLATIONS t:surface_type=CONCRETE t:district=3 t:road_type="TOW-WAY ROAD WITH A PHYSICAL SEPARATION" t:formattedstreet="11301  FLORIDA BL" t:zone=D t:road_condition="NO ABNORMALITIES" m:tot_veh=2

series e:2tu5-7kif d:2013-11-20T17:08:00.000Z t:alignment=STRAIGHT-LEVEL t:st_direction=E t:subzone=2 t:file_number=13-00014160 t:relation_roadway="ON ROADWAY" t:occured_on=INTERSTATE t:st_number=700 t:st_name=I10 t:lighting="DARK - CONTINUOUS STREET" t:at_intersection=X t:closest_street=PERKINS t:location_kind=OTHER t:surface_cond=DRY t:manner_of_collision="REAR END" t:weather=CLEAR t:access_control="FULL CONTROL (ONLY RAMP ENTRANCE and EXIT)" t:primary_factor="MOVEMENT PRIOR TO CRASH" t:surface_type=CONCRETE t:district=2 t:road_type="ONE-WAY ROAD" t:formattedstreet="700 E I10" t:zone=B t:road_condition="NO ABNORMALITIES" m:tot_veh=2
```

## Meta Commands

```ls
metric m:tot_veh p:integer l:"TOT VEH" d:"Number of vehicles involved in crash" t:dataTypeName=number

entity e:2tu5-7kif l:"Baton Rouge Traffic Incidents" t:attribution="Baton Rouge Police Department" t:url=https://data.brla.gov/api/views/2tu5-7kif

property e:2tu5-7kif t:meta.view v:id=2tu5-7kif v:category="Transportation and Infrastructure" v:attributionLink=http://brgov.com/dept/brpd v:averageRating=0 v:name="Baton Rouge Traffic Incidents" v:attribution="Baton Rouge Police Department"

property e:2tu5-7kif t:meta.view.license v:name="Public Domain"

property e:2tu5-7kif t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:2tu5-7kif t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| file_number | crash_date          | crash_time | tot_veh | district | zone | subzone | st_number | st_direction | st_name           | st_type | formattedstreet           | occured_on  | hit_run | train_involved | fatality | injury | pedestrian | at_intersection | closest_street       | manner_of_collision | surface_cond | surface_type | road_condition   | road_type                                | alignment      | primary_factor          | second_factor           | weather | location_kind               | relation_roadway | access_control                             | lighting                 | 
| =========== | =================== | ========== | ======= | ======== | ==== | ======= | ========= | ============ | ================= | ======= | ========================= | =========== | ======= | ============== | ======== | ====== | ========== | =============== | ==================== | =================== | ============ | ============ | ================ | ======================================== | ============== | ======================= | ======================= | ======= | =========================== | ================ | ========================================== | ======================== | 
| 15-00007788 | 2015-06-07T00:00:00 | 10:14 PM   | 3       | 2        | C    | 3       | 1800      |              | BRIGHTSIDE        | DR      | 1800 BRIGHTSIDE DR        | CITY STREET |         |                |          | X      |            |                 | BRIGHTSIDE VIEW DR   | REAR END            | WET          | CONCRETE     | NO ABNORMALITIES | TWO-WAY ROAD WITH NO PHYSICAL SEPARATION | STRAIGHT-LEVEL | VIOLATIONS              | CONDITION OF DRIVER     | CLOUDY  | BUSINESS, MIXED RESIDENTIAL | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DARK - CONTINUOUS STREET | 
| 10-00003768 | 2010-06-18T00:00:00 | 08:35 PM   | 2       | 3        | D    | 2       | 11301     |              | FLORIDA           | BL      | 11301 FLORIDA BL          | U.S. HWY    |         |                |          |        |            | X               | N SHERWOOD FOREST BL | RIGHT ANGLE         | DRY          | CONCRETE     | NO ABNORMALITIES | TOW-WAY ROAD WITH A PHYSICAL SEPARATION  | STRAIGHT-LEVEL | VIOLATIONS              | MOVEMENT PRIOR TO CRASH | CLEAR   | BUSINESS, MIXED RESIDENTIAL | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
| 13-00014160 | 2013-11-20T00:00:00 | 05:08 PM   | 2       | 2        | B    | 2       | 700       | E            | I10               |         | 700 E I10                 | INTERSTATE  |         |                |          |        |            | X               | PERKINS              | REAR END            | DRY          | CONCRETE     | NO ABNORMALITIES | ONE-WAY ROAD                             | STRAIGHT-LEVEL | MOVEMENT PRIOR TO CRASH |                         | CLEAR   | OTHER                       | ON ROADWAY       | FULL CONTROL (ONLY RAMP ENTRANCE and EXIT) | DARK - CONTINUOUS STREET | 
| 11-00003204 | 2011-03-14T00:00:00 | 12:23 PM   | 2       | 2        | B    | 2       | 2600      |              | COLLEGE           | DR      | 2600 COLLEGE DR           | CITY STREET |         |                |          |        |            |                 | I-10                 | SIDESWIPE SAME      | DRY          | CONCRETE     | NO ABNORMALITIES | TOW-WAY ROAD WITH A PHYSICAL SEPARATION  | STRAIGHT-LEVEL | VIOLATIONS              |                         | CLEAR   | BUSINESS CONTINUOUS         | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
| 15-00014887 | 2015-10-25T00:00:00 | 12:27 AM   | 2       | 1        | A    | 2       | 1500      |              | SCENIC            | HW      | 1500 SCENIC HW            | STATE HWY   |         |                |          |        |            | X               | ELLERSLIE            | REAR END            | WET          | BLACK TOP    | NO ABNORMALITIES | TWO-WAY ROAD WITH NO PHYSICAL SEPARATION | STRAIGHT-LEVEL | MOVEMENT PRIOR TO CRASH |                         | RAIN    | BUSINESS, MIXED RESIDENTIAL | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DARK - CONTINUOUS STREET | 
| 15-00008587 | 2015-06-23T00:00:00 | 05:38 PM   | 2       | 3        | F    | 2       | 2800      | S            | SHERWOOD FOREST   | BL      | 2800 S SHERWOOD FOREST BL | CITY STREET |         |                |          |        |            |                 | I12 HW               | REAR END            | WET          | CONCRETE     | NO ABNORMALITIES | TOW-WAY ROAD WITH A PHYSICAL SEPARATION  | STRAIGHT-LEVEL | VIOLATIONS              |                         | RAIN    | BUSINESS, MIXED RESIDENTIAL | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
| 16-00005412 | 2016-04-13T00:00:00 | 04:29 PM   | 2       | 4        | B    | 2       | 9200      |              | VETERANS MEMORIAL |         | 9200 VETERANS MEMORIAL    | CITY STREET | X       |                |          |        |            | X               | SALLY RIDE           | SIDESWIPE SAME      | DRY          | CONCRETE     | NO ABNORMALITIES | TOW-WAY ROAD WITH A PHYSICAL SEPARATION  | STRAIGHT-LEVEL | VIOLATIONS              |                         | CLEAR   | BUSINESS, MIXED RESIDENTIAL | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
| 16-00010428 | 2016-07-28T00:00:00 | 04:12 PM   | 2       | 4        | D    | 2       | 5000      |              | GLEN OAKS         | DR      | 5000 GLEN OAKS DR         | CITY STREET |         |                |          |        |            | X               | FOSTER               | REAR END            | WET          | BLACK TOP    | NO ABNORMALITIES | TWO-WAY ROAD WITH NO PHYSICAL SEPARATION | STRAIGHT-LEVEL | VIOLATIONS              |                         | RAIN    | RESIDENTIAL DISTRICT        | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
| 15-00001060 | 2015-01-26T00:00:00 | 08:49 PM   | 2       | 2        | B    | 5       | 1000      | E            | I10               |         | 1000 E I10                | INTERSTATE  |         |                |          | X      |            |                 | COLLEGE              | SIDESWIPE SAME      | DRY          | CONCRETE     | NO ABNORMALITIES | TOW-WAY ROAD WITH A PHYSICAL SEPARATION  | STRAIGHT-LEVEL | VIOLATIONS              |                         | CLEAR   | OPEN COUNTRY                | ON ROADWAY       | FULL CONTROL (ONLY RAMP ENTRANCE and EXIT) | DARK - CONTINUOUS STREET | 
| 12-00014661 | 2012-12-07T00:00:00 | 12:29 PM   | 2       | 2        | E    | 3       | 5000      |              | HENNESSY          | BL      | 5000 HENNESSY BL          | CITY STREET |         |                |          |        |            |                 | BRITTANY             | RIGHT TURN          | DRY          | CONCRETE     | NO ABNORMALITIES | TWO-WAY ROAD WITH NO PHYSICAL SEPARATION | STRAIGHT-LEVEL | VIOLATIONS              | MOVEMENT PRIOR TO CRASH | CLEAR   | BUSINESS CONTINUOUS         | ON ROADWAY       | NO CONTROL (UNLIMITED ACCESS TO ROADWAY)   | DAYLIGHT                 | 
```