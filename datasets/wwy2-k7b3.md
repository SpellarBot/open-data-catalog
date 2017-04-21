# Parks - Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-locations-10f58) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/wwy2-k7b3) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/wwy2-k7b3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/wwy2-k7b3/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | wwy2-k7b3 |
| Name | Parks - Locations |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | gis, parks, sustainability |
| Created | 2012-02-08T21:07:07Z |
| Publication Date | 2012-02-08T21:41:00Z |

## Description

Parks managed by the Chicago Park District. Dataset includes park facilities and features information. For Shapefiles, go to https://data.cityofchicago.org/Parks-Recreation/Parks-Shapefiles/5msb-wbxn. For KML files, go to https://data.cityofchicago.org/Parks-Recreation/Parks-KML/hmfy-xsta.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | park_number                       | PARK NUMBER                       | text      | number      |
| Yes      | series tag     | park_name                         | PARK NAME                         | text      | text        |
| Yes      | series tag     | street_address                    | STREET ADDRESS                    | text      | text        |
| Yes      | series tag     | zip                               | ZIP                               | text      | number      |
| Yes      | numeric metric | acres                             | ACRES                             | number    | number      |
| Yes      | series tag     | ward                              | WARD                              | text      | number      |
| Yes      | series tag     | park_class                        | PARK CLASS                        | text      | text        |
| Yes      | series tag     | label                             | LABEL                             | text      | text        |
| Yes      | numeric metric | wheelchair_accessible_ball_fields | WHEELCHAIR ACCESSIBLE BALL FIELDS | number    | number      |
| Yes      | numeric metric | alfred_caldwell_lily_pond         | ALFRED CALDWELL LILY POND         | number    | number      |
| Yes      | numeric metric | archery_range                     | ARCHERY RANGE                     | number    | number      |
| Yes      | numeric metric | artificial_turf_fields            | ARTIFICIAL TURF FIELDS            | number    | number      |
| Yes      | numeric metric | band_shell                        | BAND SHELL                        | number    | number      |
| Yes      | numeric metric | baseball_batting_cages            | BASEBALL BATTING CAGES            | number    | number      |
| Yes      | numeric metric | basketball_backboards             | BASKETBALL BACKBOARDS             | number    | number      |
| Yes      | numeric metric | basketball_courts                 | BASKETBALL COURTS                 | number    | number      |
| Yes      | numeric metric | beach                             | BEACH                             | number    | number      |
| Yes      | numeric metric | boat_launch_motorized             | BOAT LAUNCH (MOTORIZED)           | number    | number      |
| Yes      | numeric metric | boat_launch_non_motorized         | BOAT LAUNCH (NON-MOTORIZED)       | number    | number      |
| Yes      | numeric metric | boat_slips                        | BOAT SLIPS                        | number    | number      |
| Yes      | numeric metric | bocce_court                       | BOCCE COURT                       | number    | number      |
| Yes      | numeric metric | bowling_green                     | BOWLING GREEN                     | number    | number      |
| Yes      | numeric metric | casting_area                      | CASTING AREA                      | number    | number      |
| Yes      | numeric metric | chess_pavillion                   | CHESS PAVILLION                   | number    | number      |
| Yes      | numeric metric | football_soccer_combo             | FOOTBALL SOCCER COMBO             | number    | number      |
| Yes      | numeric metric | community_garden                  | COMMUNITY GARDEN                  | number    | number      |
| Yes      | numeric metric | conservatory                      | CONSERVATORY                      | number    | number      |
| Yes      | numeric metric | cultural_center                   | CULTURAL CENTER                   | number    | number      |
| Yes      | numeric metric | dog_friendly                      | DOG-FRIENDLY                      | number    | number      |
| Yes      | numeric metric | fitness_center                    | FITNESS CENTER                    | number    | number      |
| Yes      | numeric metric | fitness_courses                   | FITNESS COURSES                   | number    | number      |
| Yes      | numeric metric | gallery                           | GALLERY                           | number    | number      |
| Yes      | numeric metric | garden                            | GARDEN                            | number    | number      |
| Yes      | numeric metric | golf_course                       | GOLF COURSE                       | number    | number      |
| Yes      | numeric metric | golf_driving_range                | GOLF DRIVING RANGE                | number    | number      |
| Yes      | numeric metric | golf_putting_greens               | GOLF PUTTING GREENS               | number    | number      |
| Yes      | numeric metric | gymnasium                         | GYMNASIUM                         | number    | number      |
| Yes      | numeric metric | gymnastic_centers                 | GYMNASTIC CENTERS                 | number    | number      |
| Yes      | numeric metric | handball_raquetball_court         | HANDBALL/RAQUETBALL COURT         | number    | number      |
| Yes      | numeric metric | handball                          | HANDBALL                          | number    | number      |
| Yes      | numeric metric | horseshoe_courts                  | HORSESHOE COURTS                  | number    | number      |
| Yes      | numeric metric | ice_skating                       | ICE SKATING                       | number    | number      |
| Yes      | numeric metric | pool_indoor                       | POOL INDOOR                       | number    | number      |
| Yes      | numeric metric | baseball_jr_softball_t_ball       | BASEBALL JR/SOFTBALL/T-BALL       | number    | number      |
| Yes      | numeric metric | mountain_bike_trail               | MOUNTAIN BIKE TRAIL               | number    | number      |
| Yes      | numeric metric | nature_center                     | NATURE CENTER                     | number    | number      |
| Yes      | numeric metric | pool_outdoor                      | POOL OUTDOOR                      | number    | number      |
| Yes      | numeric metric | pavillion                         | PAVILLION                         | number    | number      |
| Yes      | numeric metric | zoo                               | ZOO                               | number    | number      |
| Yes      | numeric metric | playground                        | PLAYGROUND                        | number    | number      |
| Yes      | numeric metric | playground_park                   | PLAYGROUND PARK                   | number    | number      |
| Yes      | numeric metric | rowing_club                       | ROWING CLUB                       | number    | number      |
| Yes      | numeric metric | volleyball                        | VOLLEYBALL                        | number    | number      |
| Yes      | numeric metric | senior_center                     | SENIOR CENTER                     | number    | number      |
| Yes      | numeric metric | shuffleboard                      | SHUFFLEBOARD                      | number    | number      |
| Yes      | numeric metric | skate_park                        | SKATE PARK                        | number    | number      |
| Yes      | numeric metric | sled_hill                         | SLED HILL                         | number    | number      |
| Yes      | numeric metric | sport_roller_courts               | SPORT ROLLER COURTS               | number    | number      |
| Yes      | numeric metric | spray_feature                     | SPRAY FEATURE                     | number    | number      |
| Yes      | numeric metric | baseball_sr                       | BASEBALL SR                       | number    | number      |
| Yes      | numeric metric | tennis_courts                     | TENNIS COURTS                     | number    | number      |
| Yes      | numeric metric | track                             | TRACK                             | number    | number      |
| Yes      | numeric metric | volleyball_sand                   | VOLLEYBALL SAND                   | number    | number      |
| Yes      | numeric metric | water_playground                  | WATER PLAYGROUND                  | number    | number      |
| Yes      | numeric metric | water_slide                       | WATER SLIDE                       | number    | number      |
| Yes      | numeric metric | boxing_center                     | BOXING CENTER                     | number    | number      |
| Yes      | numeric metric | wetland_area                      | WETLAND AREA                      | number    | number      |
| Yes      | numeric metric | lagoon                            | LAGOON                            | number    | number      |
| Yes      | numeric metric | carousel                          | CAROUSEL                          | number    | text        |
| Yes      | numeric metric | croquet                           | CROQUET                           | number    | text        |
| Yes      | numeric metric | golf_course_miniature             | GOLF COURSE MINIATURE             | number    | text        |
| Yes      | numeric metric | model_train_display               | MODEL TRAIN DISPLAY               | number    | text        |
| Yes      | numeric metric | model_yacht_basin                 | MODEL YACHT BASIN                 | number    | text        |
| Yes      | numeric metric | cricket_field                     | CRICKET FIELD                     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wwy2-k7b3 d:2012-02-08T13:34:25.000Z t:zip=60627 t:park_class="COMMUNITY PARK" t:ward=9 t:park_name="GOLDEN GATE" t:park_number=288 t:label="Golden Gate" t:street_address="500 E 130TH ST" m:skate_park=0 m:conservatory=0 m:wetland_area=0 m:football_soccer_combo=0 m:sled_hill=0 m:basketball_backboards=4 m:golf_putting_greens=0 m:beach=0 m:zoo=0 m:alfred_caldwell_lily_pond=0 m:water_playground=0 m:shuffleboard=0 m:baseball_sr=1 m:model_yacht_basin=0 m:boat_slips=0 m:spray_feature=1 m:bowling_green=0 m:golf_driving_range=0 m:casting_area=0 m:water_slide=0 m:boat_launch_motorized=0 m:wheelchair_accessible_ball_fields=0 m:band_shell=0 m:lagoon=0 m:playground_park=0 m:volleyball=0 m:dog_friendly=0 m:boat_launch_non_motorized=0 m:gymnastic_centers=0 m:fitness_courses=0 m:golf_course=0 m:baseball_batting_cages=0 m:rowing_club=0 m:fitness_center=0 m:cricket_field=0 m:boxing_center=0 m:baseball_jr_softball_t_ball=1 m:bocce_court=0 m:ice_skating=0 m:pool_outdoor=0 m:nature_center=0 m:horseshoe_courts=0 m:chess_pavillion=0 m:carousel=0 m:handball=0 m:cultural_center=0 m:volleyball_sand=0 m:acres=5.2 m:senior_center=0 m:mountain_bike_trail=0 m:playground=1 m:handball_raquetball_court=0 m:gallery=0 m:artificial_turf_fields=0 m:track=0 m:gymnasium=0 m:model_train_display=0 m:basketball_courts=1 m:sport_roller_courts=0 m:archery_range=0 m:pavillion=0 m:golf_course_miniature=0 m:community_garden=0 m:pool_indoor=0 m:garden=0 m:croquet=0 m:tennis_courts=0

series e:wwy2-k7b3 d:2012-02-08T13:34:25.000Z t:park_class="COMMUNITY PARK" t:ward=0 t:park_name="MAJOR TAYLOR BIKE TRAIL" t:park_number=548 t:label="Major Taylor Bike Trail" m:skate_park=0 m:conservatory=0 m:wetland_area=0 m:football_soccer_combo=0 m:sled_hill=0 m:basketball_backboards=0 m:golf_putting_greens=0 m:beach=0 m:zoo=0 m:alfred_caldwell_lily_pond=0 m:water_playground=0 m:shuffleboard=0 m:baseball_sr=0 m:model_yacht_basin=0 m:boat_slips=0 m:spray_feature=0 m:bowling_green=0 m:golf_driving_range=0 m:casting_area=0 m:water_slide=0 m:boat_launch_motorized=0 m:wheelchair_accessible_ball_fields=0 m:band_shell=0 m:lagoon=0 m:playground_park=0 m:volleyball=0 m:dog_friendly=0 m:boat_launch_non_motorized=0 m:gymnastic_centers=0 m:fitness_courses=0 m:golf_course=0 m:baseball_batting_cages=0 m:rowing_club=0 m:fitness_center=0 m:cricket_field=0 m:boxing_center=0 m:baseball_jr_softball_t_ball=0 m:bocce_court=0 m:ice_skating=0 m:pool_outdoor=0 m:nature_center=0 m:horseshoe_courts=0 m:chess_pavillion=0 m:carousel=0 m:handball=0 m:cultural_center=0 m:volleyball_sand=0 m:acres=31.24 m:senior_center=0 m:mountain_bike_trail=0 m:playground=0 m:handball_raquetball_court=0 m:gallery=0 m:artificial_turf_fields=0 m:track=0 m:gymnasium=0 m:model_train_display=0 m:basketball_courts=0 m:sport_roller_courts=0 m:archery_range=0 m:pavillion=0 m:golf_course_miniature=0 m:community_garden=0 m:pool_indoor=0 m:garden=0 m:croquet=0 m:tennis_courts=0

series e:wwy2-k7b3 d:2012-02-08T13:34:25.000Z t:zip=60627 t:park_class="REGIONAL PARK" t:ward=9 t:park_name="CARVER (GEORGE WASHINGTON)" t:park_number=255 t:label=Carver t:street_address="939 E 132ND ST" m:skate_park=0 m:conservatory=0 m:wetland_area=0 m:football_soccer_combo=2 m:sled_hill=0 m:basketball_backboards=4 m:golf_putting_greens=0 m:beach=0 m:zoo=0 m:alfred_caldwell_lily_pond=0 m:water_playground=0 m:shuffleboard=0 m:baseball_sr=2 m:model_yacht_basin=0 m:boat_slips=0 m:spray_feature=0 m:bowling_green=0 m:golf_driving_range=0 m:casting_area=0 m:water_slide=0 m:boat_launch_motorized=0 m:wheelchair_accessible_ball_fields=0 m:band_shell=0 m:lagoon=0 m:playground_park=0 m:volleyball=1 m:dog_friendly=0 m:boat_launch_non_motorized=0 m:gymnastic_centers=0 m:fitness_courses=0 m:golf_course=0 m:baseball_batting_cages=0 m:rowing_club=0 m:fitness_center=1 m:cricket_field=0 m:boxing_center=0 m:baseball_jr_softball_t_ball=2 m:bocce_court=0 m:ice_skating=0 m:pool_outdoor=0 m:nature_center=0 m:horseshoe_courts=0 m:chess_pavillion=0 m:carousel=0 m:handball=0 m:cultural_center=0 m:volleyball_sand=0 m:acres=19.42 m:senior_center=0 m:mountain_bike_trail=0 m:playground=2 m:handball_raquetball_court=0 m:gallery=0 m:artificial_turf_fields=0 m:track=0 m:gymnasium=1 m:model_train_display=0 m:basketball_courts=2 m:sport_roller_courts=0 m:archery_range=0 m:pavillion=0 m:golf_course_miniature=0 m:community_garden=0 m:pool_indoor=1 m:garden=0 m:croquet=0 m:tennis_courts=0
```

## Meta Commands

```ls
metric m:acres p:float l:ACRES t:dataTypeName=number

metric m:wheelchair_accessible_ball_fields p:integer l:"WHEELCHAIR ACCESSIBLE BALL FIELDS" t:dataTypeName=number

metric m:alfred_caldwell_lily_pond p:integer l:"ALFRED CALDWELL LILY POND" t:dataTypeName=number

metric m:archery_range p:integer l:"ARCHERY RANGE" t:dataTypeName=number

metric m:artificial_turf_fields p:integer l:"ARTIFICIAL TURF FIELDS" t:dataTypeName=number

metric m:band_shell p:integer l:"BAND SHELL" t:dataTypeName=number

metric m:baseball_batting_cages p:integer l:"BASEBALL BATTING CAGES" t:dataTypeName=number

metric m:basketball_backboards p:integer l:"BASKETBALL BACKBOARDS" t:dataTypeName=number

metric m:basketball_courts p:integer l:"BASKETBALL COURTS" t:dataTypeName=number

metric m:beach p:integer l:BEACH t:dataTypeName=number

metric m:boat_launch_motorized p:integer l:"BOAT LAUNCH (MOTORIZED)" t:dataTypeName=number

metric m:boat_launch_non_motorized p:integer l:"BOAT LAUNCH (NON-MOTORIZED)" t:dataTypeName=number

metric m:boat_slips p:integer l:"BOAT SLIPS" t:dataTypeName=number

metric m:bocce_court p:integer l:"BOCCE COURT" t:dataTypeName=number

metric m:bowling_green p:integer l:"BOWLING GREEN" t:dataTypeName=number

metric m:casting_area p:integer l:"CASTING AREA" t:dataTypeName=number

metric m:chess_pavillion p:integer l:"CHESS PAVILLION" t:dataTypeName=number

metric m:football_soccer_combo p:integer l:"FOOTBALL SOCCER COMBO" t:dataTypeName=number

metric m:community_garden p:integer l:"COMMUNITY GARDEN" t:dataTypeName=number

metric m:conservatory p:integer l:CONSERVATORY t:dataTypeName=number

metric m:cultural_center p:integer l:"CULTURAL CENTER" t:dataTypeName=number

metric m:dog_friendly p:integer l:DOG-FRIENDLY t:dataTypeName=number

metric m:fitness_center p:integer l:"FITNESS CENTER" t:dataTypeName=number

metric m:fitness_courses p:integer l:"FITNESS COURSES" t:dataTypeName=number

metric m:gallery p:integer l:GALLERY t:dataTypeName=number

metric m:garden p:integer l:GARDEN t:dataTypeName=number

metric m:golf_course p:integer l:"GOLF COURSE" t:dataTypeName=number

metric m:golf_driving_range p:integer l:"GOLF DRIVING RANGE" t:dataTypeName=number

metric m:golf_putting_greens p:integer l:"GOLF PUTTING GREENS" t:dataTypeName=number

metric m:gymnasium p:integer l:GYMNASIUM t:dataTypeName=number

metric m:gymnastic_centers p:integer l:"GYMNASTIC CENTERS" t:dataTypeName=number

metric m:handball_raquetball_court p:integer l:"HANDBALL/RAQUETBALL COURT" t:dataTypeName=number

metric m:handball p:integer l:HANDBALL t:dataTypeName=number

metric m:horseshoe_courts p:integer l:"HORSESHOE COURTS" t:dataTypeName=number

metric m:ice_skating p:integer l:"ICE SKATING" t:dataTypeName=number

metric m:pool_indoor p:integer l:"POOL INDOOR" t:dataTypeName=number

metric m:baseball_jr_softball_t_ball p:integer l:"BASEBALL JR/SOFTBALL/T-BALL" t:dataTypeName=number

metric m:mountain_bike_trail p:integer l:"MOUNTAIN BIKE TRAIL" t:dataTypeName=number

metric m:nature_center p:integer l:"NATURE CENTER" t:dataTypeName=number

metric m:pool_outdoor p:integer l:"POOL OUTDOOR" t:dataTypeName=number

metric m:pavillion p:integer l:PAVILLION t:dataTypeName=number

metric m:zoo p:integer l:ZOO t:dataTypeName=number

metric m:playground p:integer l:PLAYGROUND t:dataTypeName=number

metric m:playground_park p:integer l:"PLAYGROUND PARK" t:dataTypeName=number

metric m:rowing_club p:integer l:"ROWING CLUB" t:dataTypeName=number

metric m:volleyball p:integer l:VOLLEYBALL t:dataTypeName=number

metric m:senior_center p:integer l:"SENIOR CENTER" t:dataTypeName=number

metric m:shuffleboard p:integer l:SHUFFLEBOARD t:dataTypeName=number

metric m:skate_park p:integer l:"SKATE PARK" t:dataTypeName=number

metric m:sled_hill p:integer l:"SLED HILL" t:dataTypeName=number

metric m:sport_roller_courts p:integer l:"SPORT ROLLER COURTS" t:dataTypeName=number

metric m:spray_feature p:integer l:"SPRAY FEATURE" t:dataTypeName=number

metric m:baseball_sr p:integer l:"BASEBALL SR" t:dataTypeName=number

metric m:tennis_courts p:integer l:"TENNIS COURTS" t:dataTypeName=number

metric m:track p:integer l:TRACK t:dataTypeName=number

metric m:volleyball_sand p:integer l:"VOLLEYBALL SAND" t:dataTypeName=number

metric m:water_playground p:integer l:"WATER PLAYGROUND" t:dataTypeName=number

metric m:water_slide p:integer l:"WATER SLIDE" t:dataTypeName=number

metric m:boxing_center p:integer l:"BOXING CENTER" t:dataTypeName=number

metric m:wetland_area p:integer l:"WETLAND AREA" t:dataTypeName=number

metric m:lagoon p:integer l:LAGOON t:dataTypeName=number

metric m:carousel p:integer l:CAROUSEL t:dataTypeName=number

metric m:croquet p:integer l:CROQUET t:dataTypeName=number

metric m:golf_course_miniature p:integer l:"GOLF COURSE MINIATURE" t:dataTypeName=number

metric m:model_train_display p:integer l:"MODEL TRAIN DISPLAY" t:dataTypeName=number

metric m:model_yacht_basin p:integer l:"MODEL YACHT BASIN" t:dataTypeName=number

metric m:cricket_field p:integer l:"CRICKET FIELD" t:dataTypeName=number

entity e:wwy2-k7b3 l:"Parks - Locations" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/wwy2-k7b3

property e:wwy2-k7b3 t:meta.view v:id=wwy2-k7b3 v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/parks/search/ v:averageRating=0 v:name="Parks - Locations" v:attribution="Chicago Park District"

property e:wwy2-k7b3 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:wwy2-k7b3 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | park_number | park_name                    | street_address       | zip   | acres | ward | park_class        | label                   | wheelchair_accessible_ball_fields | alfred_caldwell_lily_pond | archery_range | artificial_turf_fields | band_shell | baseball_batting_cages | basketball_backboards | basketball_courts | beach | boat_launch_motorized | boat_launch_non_motorized | boat_slips | bocce_court | bowling_green | casting_area | chess_pavillion | football_soccer_combo | community_garden | conservatory | cultural_center | dog_friendly | fitness_center | fitness_courses | gallery | garden | golf_course | golf_driving_range | golf_putting_greens | gymnasium | gymnastic_centers | handball_raquetball_court | handball | horseshoe_courts | ice_skating | pool_indoor | baseball_jr_softball_t_ball | mountain_bike_trail | nature_center | pool_outdoor | pavillion | zoo | playground | playground_park | rowing_club | volleyball | senior_center | shuffleboard | skate_park | sled_hill | sport_roller_courts | spray_feature | baseball_sr | tennis_courts | track | volleyball_sand | water_playground | water_slide | boxing_center | wetland_area | lagoon | carousel | croquet | golf_course_miniature | model_train_display | model_yacht_basin | cricket_field | 
| =========== | =========== | ============================ | ==================== | ===== | ===== | ==== | ================= | ======================= | ================================= | ========================= | ============= | ====================== | ========== | ====================== | ===================== | ================= | ===== | ===================== | ========================= | ========== | =========== | ============= | ============ | =============== | ===================== | ================ | ============ | =============== | ============ | ============== | =============== | ======= | ====== | =========== | ================== | =================== | ========= | ================= | ========================= | ======== | ================ | =========== | =========== | =========================== | =================== | ============= | ============ | ========= | === | ========== | =============== | =========== | ========== | ============= | ============ | ========== | ========= | =================== | ============= | =========== | ============= | ===== | =============== | ================ | =========== | ============= | ============ | ====== | ======== | ======= | ===================== | =================== | ================= | ============= | 
| 1328708065  | 288         | GOLDEN GATE                  | 500 E 130TH ST       | 60627 | 5.2   | 9    | COMMUNITY PARK    | Golden Gate             | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 4                     | 1                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 1                           | 0                   | 0             | 0            | 0         | 0   | 1          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 1             | 1           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708065  | 548         | MAJOR TAYLOR BIKE TRAIL      |                      |       | 31.24 | 0    | COMMUNITY PARK    | Major Taylor Bike Trail | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 0          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708065  | 255         | CARVER (GEORGE WASHINGTON)   | 939 E 132ND ST       | 60627 | 19.42 | 9    | REGIONAL PARK     | Carver                  | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 4                     | 2                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 2                     | 0                | 0            | 0               | 0            | 1              | 0               | 0       | 0      | 0           | 0                  | 0                   | 1         | 0                 | 0                         | 0        | 0                | 0           | 1           | 2                           | 0                   | 0             | 0            | 0         | 0   | 2          | 0               | 0           | 1          | 0             | 0            | 0          | 0         | 0                   | 0             | 2           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708065  | 127         | RUTHERFORD SAYRE             | 6871 W BELDEN AVE    | 60635 | 12.33 | 36   | COMMUNITY PARK    | Rutherford Sayre        | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 1                     | 0                | 0            | 0               | 0            | 1              | 0               | 0       | 1      | 0           | 0                  | 0                   | 1         | 0                 | 0                         | 0        | 0                | 0           | 0           | 2                           | 0                   | 0             | 0            | 0         | 0   | 1          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 1                   | 1             | 0           | 2             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708361  | 1256        | HOWARD (URE) BEACH           | 1300 W HOWARD ST     | 60626 | 0.89  | 49   | NEIGHBORHOOD PARK | Howard Beach            | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 1     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 1          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708362  | 373         | BLACKWELDER (I.S., GERTRUDE) | 1800 W 115TH ST      | 60643 | 5.05  | 19   | COMMUNITY PARK    | Blackwelder             | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 4                     | 1                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 1                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 1                           | 0                   | 0             | 0            | 0         | 0   | 1          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708362  | 34          | NORTHERLY ISLAND             | 1400 S LYNN WHITE DR | 60605 | 91.2  | 1    | MAGNET PARK       | Northerly Island        | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 1     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 0          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708362  | 1278        | WALNUT                       | 3801 W 45TH ST       | 60632 | 0.53  | 12   | NEIGHBORHOOD PARK | Walnut                  | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 1          | 0               | 0           | 0          | 0             | 0            | 0          | 0         | 1                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708362  | 343         | ASTER                        | 4639 N KENMORE AVE   | 60640 | 0.16  | 46   | MINI-PARK         | Aster                   | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 0          | 1               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
| 1328708362  | 424         | SPIKINGS FARM                | 4706 N PULASKI RD    | 60630 | 0.14  | 39   | MINI-PARK         | Spikings Farm           | 0                                 | 0                         | 0             | 0                      | 0          | 0                      | 0                     | 0                 | 0     | 0                     | 0                         | 0          | 0           | 0             | 0            | 0               | 0                     | 0                | 0            | 0               | 0            | 0              | 0               | 0       | 0      | 0           | 0                  | 0                   | 0         | 0                 | 0                         | 0        | 0                | 0           | 0           | 0                           | 0                   | 0             | 0            | 0         | 0   | 0          | 1               | 0           | 0          | 0             | 0            | 0          | 0         | 0                   | 0             | 0           | 0             | 0     | 0               | 0                | 0           | 0             | 0            | 0      | 0        | 0       | 0                     | 0                   | 0                 | 0             | 
```