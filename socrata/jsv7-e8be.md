# SSMMA Pointsof Interests10292012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-pointsof-interests10292012-9b5d7) |
| Metadata | [Link](https://data.illinois.gov/api/views/jsv7-e8be) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/jsv7-e8be/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/jsv7-e8be/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | jsv7-e8be |
| Name | SSMMA Pointsof Interests10292012 |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | social service, shopping, economic development, planning, municipal |
| Created | 2012-11-27T17:54:05Z |
| Publication Date | 2012-11-27T17:55:22Z |

## Description

This dataset details points of interest in the Chicago Southland. This may include Libraries, City Hall, Shopping Centers, Parks, Post Offices, and Social Service Agencies.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | type         | Type         | text      | text        |
| Yes      | series tag  | municipality | Municipality | text      | text        |
| Yes      | series tag  | county       | County       | text      | text        |
| Yes      | series tag  | website      | Website      | text      | text        |
| Yes      | series tag  | location_1   | Location 1   | text      | text        |
| Yes      | series tag  | location_2   | Location 2   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jsv7-e8be d:2012-11-27T09:54:06.000Z t:location_2="1900 West 119th Street, Blue Island, Illinois" t:website=http://metrarail.com/metra/en/home/maps_schedules/metra_system_map/ri/station.119TH-BEV.html t:county=Cook t:name="Blue Island 119th Street  MetraStation" t:municipality="Blue Island" t:location_1="1900 West 119th Street" t:type="Train Station" m:row_number.jsv7-e8be=1

series e:jsv7-e8be d:2012-11-27T09:54:06.000Z t:location_2="2237 120th Street, Blue Island, Illinois" t:website=https://ecchurchbi.org t:county=Cook t:name="Evangelical Community Church" t:municipality="Blue Island" t:location_1="2237 120th Street" t:type=Church m:row_number.jsv7-e8be=2

series e:jsv7-e8be d:2012-11-27T09:54:06.000Z t:location_2="2500 121st Street, Blue Island, Illinois" t:website=http://chicago.citysearch.com/profile/36660495/blue_island_il/st_philip_lutheran_church.html t:county=Cook t:name="St Philip Lutheran Church" t:municipality="Blue Island" t:location_1="2500 121st Street" t:type=Church m:row_number.jsv7-e8be=3
```

## Meta Commands

```ls
metric m:row_number.jsv7-e8be p:long l:"Row Number"

entity e:jsv7-e8be l:"SSMMA Pointsof Interests10292012" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/jsv7-e8be

property e:jsv7-e8be t:meta.view v:id=jsv7-e8be v:category=Municipality v:averageRating=0 v:name="SSMMA Pointsof Interests10292012" v:attribution="South Suburban Mayors and Managers Association"

property e:jsv7-e8be t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:jsv7-e8be t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | name                                  | type              | municipality | county | website                                                                                      | location_1             | location_2                                    | 
| =========== | ===================================== | ================= | ============ | ====== | ============================================================================================ | ====================== | ============================================= | 
| 1354010046  | Blue Island 119th Street MetraStation | Train Station     | Blue Island  | Cook   | http://metrarail.com/metra/en/home/maps_schedules/metra_system_map/ri/station.119TH-BEV.html | 1900 West 119th Street | 1900 West 119th Street, Blue Island, Illinois | 
| 1354010046  | Evangelical Community Church          | Church            | Blue Island  | Cook   | https://ecchurchbi.org                                                                       | 2237 120th Street      | 2237 120th Street, Blue Island, Illinois      | 
| 1354010046  | St Philip Lutheran Church             | Church            | Blue Island  | Cook   | http://chicago.citysearch.com/profile/36660495/blue_island_il/st_philip_lutheran_church.html | 2500 121st Street      | 2500 121st Street, Blue Island, Illinois      | 
| 1354010046  | Iowa Interstate Intermodal Facility   | Railroad Yard     | Blue Island  | Cook   |                                                                                              | 1620 121st Street      | 1600 121st Street, Blue Island, Illinois      | 
| 1354010046  | Blue Island Water Tower #1            | Water Tower       | Blue Island  | Cook   |                                                                                              | 12161 Highland Avenue  | 12161 Highland Ave, Blue Island, Illinois     | 
| 1354010046  | Metra 123rd Street Station            | Train Station     | Blue Island  | Cook   | http://metrarail.com/metra/en/home/maps_schedules/metra_system_map/ri/station.123RD-BEV.html | 2120 123rd Street      | 2120 123rd Street, Blue Island, Illinois      | 
| 1354010046  | Hart Park                             | Park              | Blue Island  | Cook   | http://blueislandparks.org/parks/                                                            | 12300 Western Ave      | 12300 Western Ave, Blue Island, Illinois      | 
| 1354010046  | Paul Revere Intermediate School       | Elementary School | Blue Island  | Cook   | http://www.district130.org/our_schools/paul_revere_intermediate/default.aspx                 | 12331 Gregory Ave      | 12331 Gregory Ave, Blue Island, Illinois      | 
| 1354010046  | Veterans Memorial Middle School       | Elementary School | Blue Island  | Cook   | http://www.district130.org/our_schools/veterans_memorial/default.aspx                        | 12320 Greenwood Ave    | 12320 Greenwood Ave, Blue Island, Illinois    | 
| 1354010046  | The Meadows Golf Course               | Golf Course       | Blue Island  | Cook   | http://www.meadowsgc.com/Contact_Us.html                                                     | 2802 123rd Street      | 2802 123rd Street, Blue Island, Illinois      | 
```