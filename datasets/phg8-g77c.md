# BREC Parks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brec-parks) |
| Metadata | [Link](https://data.brla.gov/api/views/phg8-g77c) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/phg8-g77c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/phg8-g77c/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | phg8-g77c |
| Name | BREC Parks |
| Attribution | BREC |
| Category | Culture and Recreation |
| Tags | brec, parks, recreation |
| Created | 2015-01-06T02:13:53Z |
| Publication Date | 2015-07-12T01:09:15Z |

## Description

This dataset displays all facilities and properties operated by the East Baton Rouge Parish Recreation and Park Commission (BREC).  This includes all parks, public golf courses, community centers, and special purpose recreational facilities (such as the Baton Rouge Zoo).

The amenity columns (Tennis Courts, Fishing Lakes, etc)  show how many of that amenity exist at each park.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | numeric metric | parkid                | PARK ID               | number    | number      |
| Yes      | series tag     | park_name             | PARK NAME             | text      | text        |
| Yes      | series tag     | classification        | CLASSIFICATION        | text      | text        |
| No       |                | full_address          | FULL ADDRESS          | text      | text        |
| Yes      | series tag     | city                  | CITY                  | text      | text        |
| Yes      | series tag     | zip                   | ZIP                   | text      | number      |
| Yes      | numeric metric | rec_center            | RECREATION CENTER     | number    | number      |
| Yes      | numeric metric | fitness_center        | FITNESS CENTER        | number    | number      |
| Yes      | numeric metric | stadium               | STADIUM               | number    | number      |
| Yes      | numeric metric | adult_leisure_program | ADULT LEISURE PROGRAM | number    | number      |
| Yes      | numeric metric | playgound             | PLAYGOUND             | number    | number      |
| Yes      | numeric metric | restroom              | RESTROOM              | number    | number      |
| Yes      | numeric metric | swimming_pool         | SWIMMING POOL         | number    | number      |
| Yes      | numeric metric | spray_pad             | SPRAY PAD             | number    | number      |
| Yes      | numeric metric | aquatic_center        | AQUATIC CENTER        | number    | number      |
| Yes      | numeric metric | indoor_basketball     | INDOOR BASKETBALL     | number    | number      |
| Yes      | numeric metric | outdoor_basketball    | OUTDOOR BASKETBALL    | number    | number      |
| Yes      | numeric metric | baseball_unlighted    | BASEBALL UNLIGHTED    | number    | number      |
| Yes      | numeric metric | baseball_lighted      | BASEBALL LIGHTED      | number    | number      |
| Yes      | numeric metric | soccer_field          | SOCCER FIELD          | number    | number      |
| Yes      | numeric metric | rugby_field           | RUGBY FIELD           | number    | number      |
| Yes      | numeric metric | indoor_tennis_court   | INDOOR TENNIS COURT   | number    | number      |
| Yes      | numeric metric | tennis_unlighted      | TENNIS UNLIGHTED      | number    | number      |
| Yes      | numeric metric | tennis_lighted        | TENNIS LIGHTED        | number    | number      |
| Yes      | numeric metric | golf_course_9_hole    | GOLF COURSE 9 HOLE    | number    | number      |
| Yes      | numeric metric | golf_course_18_hole   | GOLF COURSE 18 HOLE   | number    | number      |
| Yes      | numeric metric | disc_golf             | DISC GOLF             | number    | number      |
| Yes      | numeric metric | bocce_ball            | BOCCE BALL            | number    | number      |
| Yes      | numeric metric | croquet               | CROQUET               | number    | number      |
| Yes      | numeric metric | fishing_lake          | FISHING LAKE          | number    | number      |
| Yes      | numeric metric | dog_park              | DOG PARK              | number    | number      |
| Yes      | numeric metric | skate_park            | SKATE PARK            | number    | number      |
| Yes      | numeric metric | cycling_velodrome     | CYCLING VELODROME     | number    | number      |
| Yes      | numeric metric | bmx_track             | BMX TRACK             | number    | number      |
| Yes      | numeric metric | mountain_bike_trail   | MOUNTAIN BIKE TRAIL   | number    | number      |
| Yes      | numeric metric | walking_path_surfaced | WALKING PATH SURFACED | number    | number      |
| Yes      | numeric metric | walking_loop          | WALKING LOOP          | number    | number      |
| Yes      | numeric metric | equestrian            | EQUESTRIAN            | number    | number      |
| Yes      | numeric metric | archery_range         | ARCHERY RANGE         | number    | number      |
| Yes      | numeric metric | airgun_range          | AIRGUN RANGE          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = full_address
```

## Data Commands

```ls
series e:phg8-g77c d:2015-01-29T17:22:55.000Z t:zip=70807 t:classification=G t:park_name="J.S. CLARK PARK AND GOLF COURSE" t:city="BATON ROUGE" m:golf_course_9_hole=1 m:soccer_field=2 m:parkid=84 m:playgound=1

series e:phg8-g77c d:2015-01-29T17:22:55.000Z t:zip=70802 t:classification=N t:park_name="NORTH 18TH STREET PARK" t:city="BATON ROUGE" m:outdoor_basketball=2 m:parkid=127 m:playgound=1

series e:phg8-g77c d:2015-01-29T17:22:55.000Z t:zip=70817 t:classification=N t:park_name="LEO AND MURLIN WILLIE PARK" t:city="BATON ROUGE" m:parkid=103
```

## Meta Commands

```ls
metric m:parkid p:integer l:"PARK ID" d:"Unique identification number for each park" t:dataTypeName=number

metric m:rec_center p:integer l:"RECREATION CENTER" d:"Recreation Centers provide facilities for indoor programs; some include gymansiums" t:dataTypeName=number

metric m:fitness_center p:integer l:"FITNESS CENTER" d:"Facilities with fitness equipment and programs" t:dataTypeName=number

metric m:stadium p:integer l:STADIUM d:"Olympia Field, Memorial Stadium, Goldsby Stadium" t:dataTypeName=number

metric m:adult_leisure_program p:integer l:"ADULT LEISURE PROGRAM" d:"States whether a facility provides adult programs" t:dataTypeName=number

metric m:playgound p:integer l:PLAYGOUND d:"Playgrounds and play features included in that particular playgound" t:dataTypeName=number

metric m:restroom p:integer l:RESTROOM d:"Outdoor restrooms" t:dataTypeName=number

metric m:swimming_pool p:integer l:"SWIMMING POOL" d:"Outdoor swimming pools" t:dataTypeName=number

metric m:spray_pad p:integer l:"SPRAY PAD" d:"Outdoor spray pads" t:dataTypeName=number

metric m:aquatic_center p:integer l:"AQUATIC CENTER" d:"Liberty Lagoon" t:dataTypeName=number

metric m:indoor_basketball p:integer l:"INDOOR BASKETBALL" d:"Basketball courts in gymnasiums" t:dataTypeName=number

metric m:outdoor_basketball p:integer l:"OUTDOOR BASKETBALL" d:"Outdoor basketball courts including half courts or full courts" t:dataTypeName=number

metric m:baseball_unlighted p:integer l:"BASEBALL UNLIGHTED" d:"Unlighted baseball fields" t:dataTypeName=number

metric m:baseball_lighted p:integer l:"BASEBALL LIGHTED" d:"Lighted baseball fields" t:dataTypeName=number

metric m:soccer_field p:integer l:"SOCCER FIELD" d:"Outdoor soccer fields" t:dataTypeName=number

metric m:rugby_field p:integer l:"RUGBY FIELD" d:"Outdoor rugby fields" t:dataTypeName=number

metric m:indoor_tennis_court p:integer l:"INDOOR TENNIS COURT" d:"Indoor tennis courts" t:dataTypeName=number

metric m:tennis_unlighted p:integer l:"TENNIS UNLIGHTED" d:"Unlighted outdoor tennis courts" t:dataTypeName=number

metric m:tennis_lighted p:integer l:"TENNIS LIGHTED" d:"Lighted outdoor tennis courts" t:dataTypeName=number

metric m:golf_course_9_hole p:integer l:"GOLF COURSE 9 HOLE" d:"9-Hole golf courses" t:dataTypeName=number

metric m:golf_course_18_hole p:integer l:"GOLF COURSE 18 HOLE" d:"18-Hole golf courses" t:dataTypeName=number

metric m:disc_golf p:integer l:"DISC GOLF" d:"18-Hole outdoor disc golf courses" t:dataTypeName=number

metric m:bocce_ball p:integer l:"BOCCE BALL" d:"Outdoor bocce courts" t:dataTypeName=number

metric m:croquet p:integer l:CROQUET d:"Outdoor croquet courts" t:dataTypeName=number

metric m:fishing_lake p:integer l:"FISHING LAKE" d:"Outdoor fishing lakes" t:dataTypeName=number

metric m:dog_park p:integer l:"DOG PARK" d:"Outdoor dog parks" t:dataTypeName=number

metric m:skate_park p:integer l:"SKATE PARK" d:"Outdoor skate parks" t:dataTypeName=number

metric m:cycling_velodrome p:integer l:"CYCLING VELODROME" d:"Outdoor cycling velodromes" t:dataTypeName=number

metric m:bmx_track p:integer l:"BMX TRACK" d:"Outdoor BMX tracks" t:dataTypeName=number

metric m:mountain_bike_trail p:integer l:"MOUNTAIN BIKE TRAIL" d:"Outdoor mountain bike trails" t:dataTypeName=number

metric m:walking_path_surfaced p:integer l:"WALKING PATH SURFACED" d:"Paved walking paths" t:dataTypeName=number

metric m:walking_loop p:integer l:"WALKING LOOP" d:"Paved walking path loops" t:dataTypeName=number

metric m:equestrian p:integer l:EQUESTRIAN d:"Equestrian facilities including courses, stables, indoor horse events, pastures, horse trails" t:dataTypeName=number

metric m:archery_range p:integer l:"ARCHERY RANGE" d:"Outdoor archery ranges" t:dataTypeName=number

metric m:airgun_range p:integer l:"AIRGUN RANGE" d:"Outdoor airgun ranges" t:dataTypeName=number

entity e:phg8-g77c l:"BREC Parks" t:attribution=BREC t:url=https://data.brla.gov/api/views/phg8-g77c

property e:phg8-g77c t:meta.view v:id=phg8-g77c v:category="Culture and Recreation" v:attributionLink=http://brec.org v:averageRating=0 v:name="BREC Parks" v:attribution=BREC

property e:phg8-g77c t:meta.view.license v:name="Public Domain"

property e:phg8-g77c t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:phg8-g77c t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | parkid | park_name                       | classification | full_address              | city        | zip   | rec_center | fitness_center | stadium | adult_leisure_program | playgound | restroom | swimming_pool | spray_pad | aquatic_center | indoor_basketball | outdoor_basketball | baseball_unlighted | baseball_lighted | soccer_field | rugby_field | indoor_tennis_court | tennis_unlighted | tennis_lighted | golf_course_9_hole | golf_course_18_hole | disc_golf | bocce_ball | croquet | fishing_lake | dog_park | skate_park | cycling_velodrome | bmx_track | mountain_bike_trail | walking_path_surfaced | walking_loop | equestrian | archery_range | airgun_range | 
| =========== | ====== | =============================== | ============== | ========================= | =========== | ===== | ========== | ============== | ======= | ===================== | ========= | ======== | ============= | ========= | ============== | ================= | ================== | ================== | ================ | ============ | =========== | =================== | ================ | ============== | ================== | =================== | ========= | ========== | ======= | ============ | ======== | ========== | ================= | ========= | =================== | ===================== | ============ | ========== | ============= | ============ | 
| 1422552175  | 84     | J.S. CLARK PARK AND GOLF COURSE | G              | 2301 THOMAS RD            | BATON ROUGE | 70807 |            |                |         |                       | 1         |          |               |           |                |                   |                    |                    |                  | 2            |             |                     |                  |                | 1                  |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 127    | NORTH 18TH STREET PARK          | N              | 1801 GAYOSA ST            | BATON ROUGE | 70802 |            |                |         |                       | 1         |          |               |           |                |                   | 2                  |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 103    | LEO AND MURLIN WILLIE PARK      | N              | (3600-3900) STUMBERG LN   | BATON ROUGE | 70817 |            |                |         |                       |           |          |               |           |                |                   |                    |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 118    | MEADOW PARK                     | N              | 8300 MEADOW PARK AVE      | BATON ROUGE | 70810 |            |                |         |                       | 1         |          |               |           |                |                   | 1                  |                    |                  |              |             |                     | 1                |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 45     | CUNARD AVENUE PARK              | N              | 2290 CUNARD AVE           | BATON ROUGE | 70807 |            |                |         |                       | 1         |          |               |           |                |                   | 1                  |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 150    | RUE LEBOUEF PARK                | N              | (11600-11700) RUE LEBOUEF | BATON ROUGE | 70810 |            |                |         |                       | 1         |          |               |           |                |                   |                    | 1                  |                  |              |             |                     | 1                |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 164    | STARWOOD COURT PARK             | N              | 7900 STARWOOD CT          | BATON ROUGE | 70820 |            |                |         |                       | 1         |          |               |           |                |                   |                    |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 116    | MARY RUTH PARK                  | N              | 8808 MARY RUTH AVE        | BATON ROUGE | 70810 |            |                |         |                       |           |          |               |           |                |                   |                    |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 4      | ALEXANDER STREET PARK           | N              | 6000 ALEXANDER AVE        | BATON ROUGE | 70805 |            |                |         |                       |           |          |               |           |                |                   |                    |                    |                  |              |             |                     |                  |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
| 1422552175  | 105    | LITTLE FARMS PARK               | N              | 3754 LITTLE FARMS DR      | ZACHARY     | 70791 |            |                |         |                       | 1         | 1        |               |           |                |                   |                    |                    |                  |              |             |                     | 1                |                |                    |                     |           |            |         |              |          |            |                   |           |                     |                       |              |            |               |              | 
```