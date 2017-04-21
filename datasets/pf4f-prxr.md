# RACVB 2013 Events Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/racvb-2013-events-calendar-21396) |
| Metadata | [Link](https://data.illinois.gov/api/views/pf4f-prxr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pf4f-prxr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pf4f-prxr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pf4f-prxr |
| Name | RACVB 2013 Events Calendar |
| Attribution | Rockford Area Convention & Visitors Bureau |
| Category | Recreation |
| Created | 2013-11-15T22:11:56Z |
| Publication Date | 2013-11-15T22:16:29Z |

## Description

RACVB 2013 Events Calendar

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | series tag     | sponser       | Sponser       | text          | text          |
| Yes      | series tag     | name_of_event | Name of Event | text          | text          |
| Yes      | time           | start_date    | Start Date    | calendar_date | calendar_date |
| No       |                | end_date      | End Date      | calendar_date | calendar_date |
| Yes      | series tag     | event_site    | Event Site    | text          | text          |
| No       |                | event_address | Event Address | text          | text          |
| Yes      | numeric metric | room_nights   | Room Nights   | number        | number        |
| Yes      | numeric metric | attendance    | Attendance    | number        | number        |
| Yes      | series tag     | hq_hotel      | HQ Hotel      | text          | text          |
| No       |                | hotel_address | Hotel Address | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,event_address,hotel_address
```

## Data Commands

```ls
series e:pf4f-prxr d:2013-11-15T00:00:00.000Z t:hq_hotel=Multiple t:name_of_event="2013 NPC Natural Mid States Muscle Classic XXVI" t:sponser="Kevin Noble Presents" t:event_site="Jefferson High School" m:attendance=1200 m:room_nights=150

series e:pf4f-prxr d:2013-11-15T00:00:00.000Z t:hq_hotel=Multiple t:name_of_event="Fall Pre-Thanksgiving Tournament" t:sponser="Rockford Ambassadors" t:event_site="Jefferson High School" m:attendance=800 m:room_nights=200

series e:pf4f-prxr d:2013-11-15T00:00:00.000Z t:hq_hotel=Multiple t:name_of_event="2013 Chariots Basketball Regional" t:sponser="Chariots Wheelchair Athletic Association" t:event_site="Harlem High School" m:attendance=400 m:room_nights=100
```

## Meta Commands

```ls
metric m:room_nights p:integer l:"Room Nights" t:dataTypeName=number

metric m:attendance p:integer l:Attendance t:dataTypeName=number

entity e:pf4f-prxr l:"RACVB 2013 Events Calendar" t:attribution="Rockford Area Convention & Visitors Bureau" t:url=https://data.illinois.gov/api/views/pf4f-prxr

property e:pf4f-prxr t:meta.view v:id=pf4f-prxr v:category=Recreation v:averageRating=0 v:name="RACVB 2013 Events Calendar" v:attribution="Rockford Area Convention & Visitors Bureau"

property e:pf4f-prxr t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:pf4f-prxr t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| sponser                                  | name_of_event                                   | start_date          | end_date            | event_site                        | event_address                                   | room_nights | attendance | hq_hotel                               | hotel_address                                   | 
| ======================================== | =============================================== | =================== | =================== | ================================= | =============================================== | =========== | ========== | ====================================== | =============================================== | 
| Kevin Noble Presents                     | 2013 NPC Natural Mid States Muscle Classic XXVI | 2013-11-15T00:00:00 | 2013-11-17T00:00:00 | Jefferson High School             | 4145 Samuelson Rd, Rockford, IL 61109           | 150         | 1200       | Multiple                               | Multiple                                        | 
| Rockford Ambassadors                     | Fall Pre-Thanksgiving Tournament                | 2013-11-15T00:00:00 | 2013-11-17T00:00:00 | Jefferson High School             | 4145 Samuelson Rd, Rockford, IL 61109           | 200         | 800        | Multiple                               | Multiple                                        | 
| Chariots Wheelchair Athletic Association | 2013 Chariots Basketball Regional               | 2013-11-15T00:00:00 | 2013-11-17T00:00:00 | Harlem High School                | 1 Huskie Cir, Machesney Park, IL 61115          | 100         | 400        | Multiple                               | Multiple                                        | 
| Forest City Tennis Center                | Midwest National Level 5 Doubles                | 2013-11-16T00:00:00 | 2013-11-19T00:00:00 | Forest City Tennis                | 7801 E State St, Rockford, IL 61108             | 120         | 300        | Multiple                               | Multiple                                        | 
| University of Illinois Tax School        | 2013 Fall Tax School                            | 2013-11-24T00:00:00 | 2013-11-27T00:00:00 | Radisson Conference Center        | 200 S Bell School Rd, Rockford, IL 61108        | 110         | 115        | Radisson Hotel & Conference Center     | 200 S Bell School Rd, Rockford, IL 61108        | 
| Youth and Young Adult Baptist Convention | 2013 Youth and Young Adult Convention           | 2013-11-29T00:00:00 | 2013-12-01T00:00:00 | Clock Tower                       | 7801 East State Street Rockford, Illinois 61108 | 200         | 250        | Clock Tower Resort & Conference Center | 7801 East State Street Rockford, Illinois 61108 | 
| Chariots Wheelchair Athletic Association | 2013 Jr Chariots Tournament                     | 2013-12-06T00:00:00 | 2013-12-08T00:00:00 | Harlem High School                | 1 Huskie Cir, Machesney Park, IL 61115          | 100         | 700        | Multiple                               | Multiple                                        | 
| Patriots' Gateway Community Center       | 2013 Illinois Silver Gloves Boxing Championship | 2013-12-13T00:00:00 | 2013-12-15T00:00:00 | Patriots Gateway Community Center | 615 S 5th St, Rockford, IL 61104                | 150         | 600        | Multiple                               | Multiple                                        | 
| Boys & Girls Club of Rockford            | 11th Annual Holiday Classic                     | 2013-12-13T00:00:00 | 2013-12-15T00:00:00 | Flodin Boys Club                  | 988 S Lyford Rd, Rockford, IL 61108             | 30          | 4000       | Multiple                               | Multiple                                        | 
| Rockford Volleyball Club                 | 2013/14 Rockford Challenge 1&2                  | 2013-12-13T00:00:00 | 2013-12-15T00:00:00 | ISC                               | 8800 E Riverside Blvd, Loves Park, IL 61111     | 40          | 400        | Multiple                               | Multiple                                        | 
```