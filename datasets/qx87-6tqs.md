# Recreation Summer Camps 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-summer-camps-2016) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qx87-6tqs) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qx87-6tqs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qx87-6tqs/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qx87-6tqs |
| Name | Recreation Summer Camps 2016 |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | camps, programs, activities, swimming, pools, running, soccer, basketball |
| Created | 2016-02-23T23:02:50Z |
| Publication Date | 2016-03-14T17:01:05Z |

## Description

List of all Camps (Register here:https://apm.activecommunities.com/montgomerycounty/Home)  to include Aquatics, Basketball, Soccer, Special Interest, General Sports, Therapeutic and more.    Dates, Times, Age Requirements, and Locations included.
Update Frequency:  Annually

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | session            | Session            | text      | text        |
| Yes      | series tag     | primary_category   | Primary Category   | text      | text        |
| Yes      | series tag     | secondary_category | Secondary Category | text      | text        |
| Yes      | series tag     | activityname       | ActivityName       | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | series tag     | activitynumber     | ActivityNumber     | text      | text        |
| Yes      | series tag     | ages               | Ages               | text      | text        |
| Yes      | series tag     | location           | Location           | text      | text        |
| No       |                | address            | Address            | text      | text        |
| Yes      | series tag     | city               | City               | text      | text        |
| Yes      | series tag     | state              | State              | text      | text        |
| Yes      | series tag     | zip                | Zip                | text      | text        |
| Yes      | time           | start_date         | Start Date         | text      | text        |
| No       |                | end_date           | End Date           | text      | text        |
| No       |                | start_time         | Start Time         | text      | text        |
| No       |                | end_time           | End Time           | text      | text        |
| Yes      | numeric metric | sessions           | Sessions           | number    | text        |
| No       |                | days_of_week       | Days of the Week   | text      | text        |
| Yes      | numeric metric | cost               | Cost               | money     | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = address,end_date,end_time,days_of_week,start_time
```

## Data Commands

```ls
series e:qx87-6tqs d:2016-08-01T00:00:00.000Z t:zip=20832 t:primary_category=Camps t:session="Camp 2016" t:location="Olney Swim Center" t:description="This camp has it all-swimming, diving, trampoline, soccer, kickball, crafts and games!  Campers should be able to swim 25 yards and must be comfortable in the water that exceeds their height.  Campers must come equipped with shorts, T-shirt and tennis shoes or athletic-type shoes.  Campers should bring a non-perishable lunch, extra pair of athletic socks, swim suit, towel, cap, goggles and sunscreen.  A $15 material fee is due at the beginning of each session, payable to Tober Aqua Sports, Inc.  Extended Care is provided by the camp for morning and/or afternoon for participants only.  Campers must be 7 by the first day of camp.  Jr. Camps are for ages 7-11.  For more information, contact Mike Tober at 301-873-8411 or visit www.aquasportscamp.com." t:state=MD t:activityname="Aqua Sports Camp Jr" t:secondary_category="Aquatic Camps" t:activitynumber=11899 t:ages="At least 7 but less than 12" t:city=Olney m:sessions=5 m:cost=270

series e:qx87-6tqs d:2016-07-05T00:00:00.000Z t:zip=20832 t:primary_category=Camps t:session="Camp 2016" t:location="Olney Swim Center" t:description="This camp has it all-swimming, diving, trampoline, soccer, kickball, crafts and games!  Campers should be able to swim 25 yards and must be comfortable in the water that exceeds their height.  Campers must come equipped with shorts, T-shirt and tennis shoes or athletic-type shoes.  Campers should bring a non-perishable lunch, extra pair of athletic socks, swim suit, towel, cap, goggles and sunscreen.  A $15 material fee is due at the beginning of each session, payable to Tober Aqua Sports, Inc.  Extended Care is provided by the camp for morning and/or afternoon for participants only.  Campers must be 7 by the first day of camp.  Jr. Camps are for ages 7-11.  For more information, contact Mike Tober at 301-873-8411 or visit www.aquasportscamp.com." t:state=MD t:activityname="Aqua Sports Camp Jr" t:secondary_category="Aquatic Camps" t:activitynumber=11895 t:ages="At least 7 but less than 12" t:city=Olney m:sessions=4 m:cost=216

series e:qx87-6tqs d:2016-07-11T00:00:00.000Z t:zip=20854 t:primary_category=Camps t:session="Camp 2016" t:location="Potomac Elementary School" t:description="During the LEGO? Robotics Mission to Mars classes, students design and robots to explore an unknown planet, find safe shelter, and collect soil samples from the planet. Students use LEGO? Robotics and computers to learn principles of robotics, computer programming, and teamwork." t:state=MD t:activityname="Robotics: Mission to Mars" t:secondary_category="Special Interest" t:activitynumber=13010 t:ages="At least 8 but less than 14" t:city=Potomac m:sessions=5 m:cost=220
```

## Meta Commands

```ls
metric m:sessions p:integer l:Sessions d:Sessions t:dataTypeName=number

metric m:cost p:long l:Cost d:Cost t:dataTypeName=money

entity e:qx87-6tqs l:"Recreation Summer Camps 2016" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/qx87-6tqs

property e:qx87-6tqs t:meta.view v:id=qx87-6tqs v:category=Community/Recreation v:averageRating=0 v:name="Recreation Summer Camps 2016" v:attribution="Montgomery County, MD"

property e:qx87-6tqs t:meta.view.license v:name="Public Domain"

property e:qx87-6tqs t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:qx87-6tqs t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| session   | primary_category | secondary_category              | activityname                              | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | activitynumber | ages                         | location                                | address              | city          | state | zip   | start_date | end_date   | start_time | end_time | sessions | days_of_week | cost | 
| ========= | ================ | =============================== | ========================================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | ============== | ============================ | ======================================= | ==================== | ============= | ===== | ===== | ========== | ========== | ========== | ======== | ======== | ============ | ==== | 
| Camp 2016 | Camps            | Aquatic Camps                   | Aqua Sports Camp Jr                       | This camp has it all-swimming, diving, trampoline, soccer, kickball, crafts and games! Campers should be able to swim 25 yards and must be comfortable in the water that exceeds their height. Campers must come equipped with shorts, T-shirt and tennis shoes or athletic-type shoes. Campers should bring a non-perishable lunch, extra pair of athletic socks, swim suit, towel, cap, goggles and sunscreen. A $15 material fee is due at the beginning of each session, payable to Tober Aqua Sports, Inc. Extended Care is provided by the camp for morning and/or afternoon for participants only. Campers must be 7 by the first day of camp. Jr. Camps are for ages 7-11. For more information, contact Mike Tober at 301-873-8411 or visit www.aquasportscamp.com. | 11899          | At least 7 but less than 12  | Olney Swim Center                       | 16605 Georgia Avenue | Olney         | MD    | 20832 | 08/01/2016 | 08/05/2016 | 8:45 AM    | 4:00 PM  | 5        | M-F          | $270 | 
| Camp 2016 | Camps            | Aquatic Camps                   | Aqua Sports Camp Jr                       | This camp has it all-swimming, diving, trampoline, soccer, kickball, crafts and games! Campers should be able to swim 25 yards and must be comfortable in the water that exceeds their height. Campers must come equipped with shorts, T-shirt and tennis shoes or athletic-type shoes. Campers should bring a non-perishable lunch, extra pair of athletic socks, swim suit, towel, cap, goggles and sunscreen. A $15 material fee is due at the beginning of each session, payable to Tober Aqua Sports, Inc. Extended Care is provided by the camp for morning and/or afternoon for participants only. Campers must be 7 by the first day of camp. Jr. Camps are for ages 7-11. For more information, contact Mike Tober at 301-873-8411 or visit www.aquasportscamp.com. | 11895          | At least 7 but less than 12  | Olney Swim Center                       | 16605 Georgia Avenue | Olney         | MD    | 20832 | 07/05/2016 | 07/08/2016 | 8:45 AM    | 4:00 PM  | 4        | T-F          | $216 | 
| Camp 2016 | Camps            | Special Interest                | Robotics: Mission to Mars                 | During the LEGO? Robotics Mission to Mars classes, students design and robots to explore an unknown planet, find safe shelter, and collect soil samples from the planet. Students use LEGO? Robotics and computers to learn principles of robotics, computer programming, and teamwork.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 13010          | At least 8 but less than 14  | Potomac Elementary School               | 10311 River Road     | Potomac       | MD    | 20854 | 07/11/2016 | 07/15/2016 | 9:00 AM    | 12:00 PM | 5        | M-F          | $220 | 
| Camp 2016 | Camps            | Therapeutic Recreation Programs | Camp Chesapeake                           | High school teens with developmental disabilities. Daily travel camp to regional parks and recreation facilities, swimming, and canoeing. Each day is a new trip destination. Trips are designed for active, independent teens and involve a lot of walking and/or physical exercise. No personal care provided. Staff ratio: 1 staff/4 participants. TR Extended Camp option available at Wood MS.                                                                                                                                                                                                                                                                                                                                                                          | 12595          | At least 14 but less than 22 | Bauer Drive Community Recreation Center | 14625 Bauer Drive    | Rockville     | MD    | 20853 | 06/27/2016 | 07/01/2016 | 9:00 AM    | 3:30 PM  | 5        | M-F          | $125 | 
| Camp 2016 | Camps            | Special Interest                | Explorations in Science at Dufief ES      | Slime, eruption and gravity, oh my! In this hands-on camp campers will learn about the amazing science they can do with basic household materials. Each day will include science experiments, crafts, games and outdoor exploration. Campers swim twice a week and go on a field trip during the first three sessions. Each camper must bring a bag lunch. Onsite morning and afternoon extended care is available for an additional fee.                                                                                                                                                                                                                                                                                                                                    | 12514          | At least 5 but less than 10  | DuFief Elementary School                | 15001 DuFief Drive   | Gaithersburg  | MD    | 20878 | 07/25/2016 | 08/05/2016 | 9:00 AM    | 3:30 PM  | 30       | M-F          | $305 | 
| Camp 2016 | Camps            | Basketball                      | One-on-One Multi-Sport Camp               | Ages 6-12: This camp will be a mix of drills, contests, and games. Sports will include basketball, soccer, kickball, funball, capture the flag, and more. We love to include games that the campers want to play so come with some ideas as well. All campers will receive a camp t-shirt, and the chance to win great prizes.                                                                                                                                                                                                                                                                                                                                                                                                                                               | 12745          | At least 6 but less than 12  | Luxmanor Elementary School              | 6201 Tilden Lane     | Potomac       | MD    | 20852 | 06/27/2016 | 07/01/2016 | 9:00 AM    | 3:00 PM  | 5        | M-F          | $195 | 
| Camp 2016 | Camps            | General Sports                  | Endless Summer Extended Camp              | Ages 5-12: Children registered for Endless Summer are eligible to register for an extended day program for an additional fee. The extended program provides supervised informal recreational activities for participants before and after Endless Summer. Half day participants are eligible for AM sessions only.                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 13078          | At least 5 but less than 13  | Bauer Drive Community Recreation Center | 14625 Bauer Drive    | Rockville     | MD    | 20853 | 08/08/2016 | 08/12/2016 | 3:30 PM    | 6:00 PM  | 5        | M-F          | $49  | 
| Camp 2016 | Camps            | Arts                            | Abrakadoodle: Garden Art Safari - AM Only | What's in a garden? More than you think! From soil to bugs and blooms, each art activity will inspire individual creativity while developing a better understanding of garden environments. Children practice sketching, create a worm diorama, explore the impressionistic art of Claude Monet and learn about the father of botanical drawing Basilius Besler. We'll even use real garden organics to make small creature and interesting layered art! From mighty woodland to tiny pollinators, the garden provides a wonderful canvas for our artistic creations!                                                                                                                                                                                                        | 13211          | At least 6 but less than 13  | Sligo Creek Elementary School           | 500 Schuyler Road    | Silver Spring | MD    | 20910 | 06/27/2016 | 07/01/2016 | 9:00 AM    | 12:00 PM | 5        | M-F          | $180 | 
| Camp 2016 | Camps            | Soccer                          | UK Elite Soccer - Petite                  | A fun introduction to soccer utilizing maximum activity and participation and highly stimulating fantasy games. The focus is creating a fun learning environment in which children develop basic ball manipulation skills using their feet. Instruction is provided by professional British coaches and teachers. All participants receive a U.K. Elite t-shirt and certificate of attendance.                                                                                                                                                                                                                                                                                                                                                                               | 13354          | At least 2 but less than 5   | Maplewood-Alta Vista Local Park         | 5209 Alta Vista Road | Bethesda      | MD    | 20814 | 06/21/2016 | 06/24/2016 | 9:00 AM    | 9:45 AM  | 4        | T-F          | $80  | 
| Camp 2016 | Camps            | Soccer                          | UK Elite Soccer Half Day Clinic           | Ages 5-14: Half Day Camp. Welcome to a fun environment which stimulates learning, developing, practicing and polishing soccer skills. UK Elite Soccer's international STEP2Success curriculum provides children with age specific training based on the use of maximum activity and highly stimulating practices and games. Each day begins with the move of the day and ends with a mini-World Cup tournament! The focus is creation a fun learning environment in which children learn and improve their skills. Instruction is provided by professional British coaches and teachers. All participants receive a t-shirt an evaluation by a trainer. Participants are divided by ages for participation.                                                                  | 12493          | At least 5 but less than 15  | Maplewood-Alta Vista Local Park         | 5209 Alta Vista Road | Bethesda      | MD    | 20814 | 06/21/2016 | 06/24/2016 | 9:00 AM    | 12:00 PM | 4        | T-F          | $175 | 
```