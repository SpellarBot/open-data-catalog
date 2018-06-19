# SDOT Parklets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-parklets) |
| Metadata | [Link](https://data.seattle.gov/api/views/m4k5-ua7m) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/m4k5-ua7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/m4k5-ua7m/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | m4k5-ua7m |
| Name | SDOT Parklets |
| Category | Transportation |
| Tags | parklet, public, parking, space, street use, street, sdot asset status and condition report, assets |
| Created | 2016-04-21T15:40:53Z |
| Publication Date | 2016-04-21T16:30:05Z |

## Description

Displays the location of Parklets in the City of Seattle

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | objectid    | OBJECTID    | text      | number      |
| No       |                | id          | ID          | text      | number      |
| Yes      | series tag     | host        | HOST        | text      | text        |
| Yes      | series tag     | built       | BUILT       | text      | text        |
| Yes      | series tag     | nhood       | NHOOD       | text      | text        |
| Yes      | time           | year        | YEAR        | number    | number      |
| Yes      | numeric metric | num_parksp  | NUM_PARKSP  | number    | number      |
| No       |                | address     | ADDRESS     | text      | text        |
| Yes      | series tag     | permit_num  | PERMIT_NUM  | text      | number      |
| Yes      | series tag     | amenities   | AMENITIES   | text      | text        |
| Yes      | series tag     | imageurl    | IMAGEURL    | text      | text        |
| Yes      | series tag     | status      | STATUS      | text      | text        |
| Yes      | series tag     | unitidsort  | UNITIDSORT  | text      | text        |
| Yes      | series tag     | blockid     | BLOCKID     | text      | text        |
| Yes      | series tag     | zip         | ZIP         | text      | text        |
| Yes      | series tag     | permit_desc | PERMIT_DESC | text      | text        |
| Yes      | series tag     | imgname     | IMGNAME     | text      | text        |
| Yes      | series tag     | type        | TYPE        | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id,address
```

## Data Commands

```ls
series e:m4k5-ua7m d:2015-01-01T00:00:00.000Z t:zip=98107 t:blockid=NWMT-17 t:nhood=Ballard t:host="Mighty-O Donuts" t:amenities="seating, planters, bike parking, play area" t:status=Proposed t:imgname=17.png t:permit_num=0 t:objectid=1 t:imageurl=http://www.seattle.gov/transportation/images/parklets/map/17.png t:type=Parklet t:built=N m:num_parksp=2

series e:m4k5-ua7m d:2015-01-01T00:00:00.000Z t:zip=98112 t:nhood="Captiol Hill" t:host="Sugar Plum" t:amenities="seating, tables, planters, bike parking" t:status=Proposed t:imgname=18.png t:permit_num=0 t:objectid=2 t:imageurl=http://www.seattle.gov/transportation/images/parklets/map/18.png t:type=Parklet t:built=N m:num_parksp=1

series e:m4k5-ua7m d:2015-01-01T00:00:00.000Z t:zip=98107 t:blockid=NWBL-52 t:nhood=Ballard t:host=Stoneburner t:amenities="seating, tables, planters, bike parking" t:status=Proposed t:imgname=19.png t:permit_num=0 t:objectid=3 t:imageurl=http://www.seattle.gov/transportation/images/parklets/map/19.png t:type=Streatery t:built=N m:num_parksp=2
```

## Meta Commands

```ls
metric m:num_parksp p:double l:NUM_PARKSP d:Num_ParkSp t:dataTypeName=number

entity e:m4k5-ua7m l:"SDOT Parklets" t:url=https://data.seattle.gov/api/views/m4k5-ua7m

property e:m4k5-ua7m t:meta.view v:id=m4k5-ua7m v:category=Transportation v:averageRating=0 v:name="SDOT Parklets"

property e:m4k5-ua7m t:meta.view.license v:name="Public Domain"

property e:m4k5-ua7m t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:m4k5-ua7m t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | id | host                                   | built | nhood            | year | num_parksp | address                | permit_num | amenities                                                         | imageurl                                                         | status   | unitidsort           | blockid        | zip   | permit_desc                                             | imgname | type      | 
| ======== | == | ====================================== | ===== | ================ | ==== | ========== | ====================== | ========== | ================================================================= | ================================================================ | ======== | ==================== | ============== | ===== | ======================================================= | ======= | ========= | 
| 1        | 17 | Mighty-O Donuts                        | N     | Ballard          | 2015 | 2          | 1555 NW Market St      | 0          | seating, planters, bike parking, play area                        | http://www.seattle.gov/transportation/images/parklets/map/17.png | Proposed |                      | NWMT-17        | 98107 |                                                         | 17.png  | Parklet   | 
| 2        | 18 | Sugar Plum                             | N     | Captiol Hill     | 2015 | 1          | 324 15th Ave E         | 0          | seating, tables, planters, bike parking                           | http://www.seattle.gov/transportation/images/parklets/map/18.png | Proposed |                      |                | 98112 |                                                         | 18.png  | Parklet   | 
| 3        | 19 | Stoneburner                            | N     | Ballard          | 2015 | 2          | 5214 Ballard Ave NW    | 0          | seating, tables, planters, bike parking                           | http://www.seattle.gov/transportation/images/parklets/map/19.png | Proposed |                      | NWBL-52        | 98107 |                                                         | 19.png  | Streatery | 
| 4        | 11 | Cortona Cafe                           | Y     | Central District | 2014 | 1          | 2425 E Union St        | 236944     | Seating, planters, games                                          | http://www.seattle.gov/transportation/images/parklets/map/11.png | Approved | 116500240            |                | 98122 | Construction Use Permit 243586                          | 11.png  | Parklet   | 
| 5        | 5  | Seattle Children's Research Institute  | Y     | Denny Triangle   | 2014 | 12         | 1915 Terry Ave         | 236623     | Seating, planters, bike parking, bike parking                     | http://www.seattle.gov/transportation/images/parklets/map/5.png  | Approved | 100400190            | TY-19          | 98101 | Parklet adjacent to 1915 Terry Ave | Related SIP 223285 | 5.png   | Parklet   | 
| 6        | 1  | Delancey                               | N     | Ballard          | 2014 | 2          | 1415 NW 70th St        | 0          |                                                                   | http://www.seattle.gov/transportation/images/parklets/map/1.png  | Proposed | 147100143            |                | 98117 |                                                         | 1.png   | Parklet   | 
| 7        | 7  | Montana Bar                            | Y     | Capitol Hill     | 2013 | 1.5        | 1506 E Olive Way       | 211304     | Table/railing, bike parking, planters, sidewalk cafe              | http://www.seattle.gov/transportation/images/parklets/map/7.png  | Approved | 114350150            |                | 98122 |                                                         | 7.png   | Streatery | 
| 8        | 13 | Chinatown/ID Business Improvement Area | Y     | Chinatown/ID     | 2013 | 0          | 519 6th Ave S          | 229381     | Seating, tables, planters, bike parking                           | http://www.seattle.gov/transportation/images/parklets/map/13.png | Approved | 044550050            | S06-05         | 98104 |                                                         | 13.png  | Parklet   | 
| 9        | 9  | Lost Lake Lounge/Comet Tavern          | N     | Capitol Hill     | 2014 | 5          | 10th Ave and E Pike St | 0          |                                                                   | http://www.seattle.gov/transportation/images/parklets/map/9.png  | Proposed | 114650090; 001450150 | E15-09; E10-15 | 98122 |                                                         | 9.png   | Streatery | 
| 10       | 4  | Uptown Alliance/SIFF Cinema            | Y     | Uptown           | 2014 | 1          | 511 Queen Anne Ave N   | 244172     | Seating, tables, planter, bike parking, little library, waste bin | http://www.seattle.gov/transportation/images/parklets/map/4.png  | Approved | 093150050            | NQA-05         | 98109 | Parklet adjacent to SIFF Cinema                         | 4.png   | Parklet   | 
```