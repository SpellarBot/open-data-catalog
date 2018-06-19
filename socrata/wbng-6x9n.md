# SDOT Street Blockfaces

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-street-blockfaces) |
| Metadata | [Link](https://data.seattle.gov/api/views/wbng-6x9n) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wbng-6x9n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wbng-6x9n/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wbng-6x9n |
| Name | SDOT Street Blockfaces |
| Category | Transportation |
| Tags | blockface, street, sdot, parking |
| Created | 2016-04-21T15:37:03Z |
| Publication Date | 2016-05-03T07:43:11Z |

## Description

Displays the location and attribute information for blockfaces in the City of Seattle. This includes information about parking along that blockface and is a super set of features from the Restricted Parking Zones dataset.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type  | Render Type |
| ======== | ============== | =================== | =================== | ========== | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data  | meta_data   |
| Yes      | series tag     | objectid            | OBJECTID            | text       | number      |
| Yes      | numeric metric | elmntkey            | ELMNTKEY            | number     | number      |
| Yes      | numeric metric | segkey              | SEGKEY              | number     | number      |
| Yes      | numeric metric | distance            | DISTANCE            | number     | number      |
| Yes      | numeric metric | blockface_length    | BLOCKFACE_LENGTH    | number     | number      |
| Yes      | numeric metric | end_distance        | END_DISTANCE        | number     | number      |
| Yes      | numeric metric | width               | WIDTH               | number     | number      |
| Yes      | series tag     | unitid              | UNITID              | text       | text        |
| Yes      | series tag     | unitid2             | UNITID2             | text       | text        |
| Yes      | series tag     | unitdesc            | UNITDESC            | text       | text        |
| Yes      | series tag     | side                | SIDE                | text       | text        |
| Yes      | series tag     | block_id            | BLOCK_ID            | text       | text        |
| Yes      | numeric metric | block_nbr           | BLOCK_NBR           | number     | number      |
| Yes      | series tag     | csm                 | CSM                 | text       | text        |
| Yes      | series tag     | parking_category    | PARKING_CATEGORY    | text       | text        |
| Yes      | numeric metric | total_spaces        | TOTAL_SPACES        | number     | number      |
| Yes      | numeric metric | paid_spaces         | PAID_SPACES         | number     | number      |
| Yes      | numeric metric | carpool_spaces      | CARPOOL_SPACES      | number     | number      |
| Yes      | numeric metric | rpz_spaces          | RPZ_SPACES          | number     | number      |
| Yes      | numeric metric | tl_spaces           | TL_SPACES           | number     | number      |
| Yes      | numeric metric | bus                 | BUS                 | number     | number      |
| Yes      | numeric metric | nopark              | NOPARK              | number     | number      |
| Yes      | numeric metric | nostop              | NOSTOP              | number     | number      |
| Yes      | numeric metric | total_nopark        | TOTAL_NOPARK        | number     | number      |
| Yes      | numeric metric | load                | LOAD                | number     | number      |
| Yes      | numeric metric | zone                | ZONE                | number     | number      |
| Yes      | numeric metric | total_zones         | TOTAL_ZONES         | number     | number      |
| Yes      | numeric metric | parking_spaces      | PARKING_SPACES      | number     | number      |
| Yes      | numeric metric | unrestricted        | UNRESTRICTED        | number     | number      |
| Yes      | numeric metric | tier                | TIER                | number     | number      |
| Yes      | numeric metric | wkd_rate1           | WKD_RATE1           | number     | number      |
| Yes      | numeric metric | wkd_start1          | WKD_START1          | number     | number      |
| Yes      | numeric metric | wkd_end1            | WKD_END1            | number     | number      |
| Yes      | numeric metric | wkd_rate2           | WKD_RATE2           | number     | number      |
| Yes      | numeric metric | wkd_start2          | WKD_START2          | number     | number      |
| Yes      | numeric metric | wkd_end2            | WKD_END2            | number     | number      |
| Yes      | numeric metric | wkd_rate3           | WKD_RATE3           | number     | number      |
| Yes      | numeric metric | wkd_start3          | WKD_START3          | number     | number      |
| Yes      | numeric metric | wkd_end3            | WKD_END3            | number     | number      |
| Yes      | numeric metric | sat_rate1           | SAT_RATE1           | number     | number      |
| Yes      | numeric metric | sat_start1          | SAT_START1          | number     | number      |
| Yes      | numeric metric | sat_end1            | SAT_END1            | number     | number      |
| Yes      | numeric metric | sat_rate2           | SAT_RATE2           | number     | number      |
| Yes      | numeric metric | sat_start2          | SAT_START2          | number     | number      |
| Yes      | numeric metric | sat_end2            | SAT_END2            | number     | number      |
| Yes      | numeric metric | sat_rate3           | SAT_RATE3           | number     | number      |
| Yes      | numeric metric | sat_start3          | SAT_START3          | number     | number      |
| Yes      | numeric metric | sat_end3            | SAT_END3            | number     | number      |
| Yes      | numeric metric | sun_rate1           | SUN_RATE1           | number     | number      |
| Yes      | numeric metric | sun_start1          | SUN_START1          | number     | number      |
| Yes      | numeric metric | sun_end1            | SUN_END1            | number     | number      |
| Yes      | numeric metric | sun_rate2           | SUN_RATE2           | number     | number      |
| Yes      | numeric metric | sun_start2          | SUN_START2          | number     | number      |
| Yes      | numeric metric | sun_end2            | SUN_END2            | number     | number      |
| Yes      | numeric metric | sun_rate3           | SUN_RATE3           | number     | number      |
| Yes      | numeric metric | sun_start3          | SUN_START3          | number     | number      |
| Yes      | numeric metric | sun_end3            | SUN_END3            | number     | number      |
| Yes      | series tag     | peak_hour           | PEAK_HOUR           | text       | text        |
| Yes      | series tag     | rpz_zone            | RPZ_ZONE            | text       | text        |
| Yes      | numeric metric | rpz_area            | RPZ_AREA            | number     | text        |
| Yes      | series tag     | paidarea            | PAIDAREA            | text       | text        |
| Yes      | numeric metric | parking_time_limit  | PARKING_TIME_LIMIT  | number     | number      |
| Yes      | series tag     | subarea             | SUBAREA             | text       | text        |
| Yes      | series tag     | start_time_wkd      | START_TIME_WKD      | text       | text        |
| Yes      | series tag     | end_time_wkd        | END_TIME_WKD        | text       | text        |
| Yes      | series tag     | start_time_sat      | START_TIME_SAT      | text       | text        |
| Yes      | series tag     | end_time_sat        | END_TIME_SAT        | text       | text        |
| Yes      | series tag     | start_time_sun      | START_TIME_SUN      | text       | text        |
| Yes      | series tag     | end_time_sun        | END_TIME_SUN        | text       | text        |
| No       |                | shape               | Shape               | geospatial | geospatial  |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text       | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text       | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text       | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text       | text        |
| Yes      | numeric metric | shape_length        | Shape_Length        | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:wbng-6x9n d:2016-04-21T15:37:03.000Z t:shape.longitude=-122.29142618999998 t:unitdesc="NE 45TH PL BETWEEN NE BLAKELEY ST AND UNIVERSITY VIEW PL NE" t:parking_category="Unrestricted Parking" t:unitid=13280 t:side=SE t:unitid2=0330 t:shape.needs_recoding=false t:csm=N t:overrideyn=N t:primarydistrictcd=DISTRICT4 t:shape.latitude=47.66194213000006 t:objectid=1 t:peak_hour=4-6PM m:bus=0 m:tier=0 m:nopark=0 m:paid_spaces=0 m:end_distance=251 m:wkd_rate2=0 m:wkd_rate1=0 m:total_spaces=10 m:wkd_start3=0 m:wkd_rate3=0 m:wkd_start2=0 m:wkd_start1=0 m:parking_spaces=8 m:width=-16 m:sat_start3=0 m:sat_start1=0 m:sat_start2=0 m:elmntkey=84738 m:total_nopark=0 m:sat_rate2=0 m:sat_rate1=0 m:shape_length=237.40991821818355 m:sat_rate3=0 m:carpool_spaces=0 m:sun_start3=0 m:sun_end1=0 m:load=0 m:sun_end2=0 m:sun_end3=0 m:total_zones=2 m:sun_start1=0 m:sun_start2=0 m:sat_end1=0 m:nostop=0 m:tl_spaces=0 m:distance=13 m:wkd_end1=0 m:wkd_end2=0 m:block_nbr=3300 m:wkd_end3=0 m:sun_rate3=0 m:sat_end3=0 m:sat_end2=0 m:unrestricted=8 m:segkey=16836 m:sun_rate1=0 m:sun_rate2=0 m:blockface_length=238 m:rpz_spaces=0 m:zone=2

series e:wbng-6x9n d:2016-04-21T15:37:03.000Z t:shape.longitude=-122.32140779299999 t:unitdesc="NE 43RD ST BETWEEN DEAD END 1 AND 7TH AVE NE" t:parking_category="Unrestricted Parking" t:unitid=13250 t:side=S t:unitid2=0060 t:shape.needs_recoding=false t:csm=N t:overrideyn=N t:primarydistrictcd=DISTRICT4 t:shape.latitude=47.65942198000005 t:objectid=2 m:bus=0 m:tier=0 m:nopark=4 m:paid_spaces=0 m:end_distance=141 m:wkd_rate2=0 m:wkd_rate1=0 m:total_spaces=5 m:wkd_start3=0 m:wkd_rate3=0 m:wkd_start2=0 m:wkd_start1=0 m:parking_spaces=1 m:width=-13 m:sat_start3=0 m:sat_start1=0 m:sat_start2=0 m:elmntkey=84714 m:total_nopark=4 m:sat_rate2=0 m:sat_rate1=0 m:shape_length=126.96855067202569 m:sat_rate3=0 m:carpool_spaces=0 m:sun_start3=0 m:sun_end1=0 m:load=0 m:sun_end2=0 m:sun_end3=0 m:total_zones=0 m:sun_start1=0 m:sun_start2=0 m:sat_end1=0 m:nostop=0 m:tl_spaces=0 m:distance=13 m:wkd_end1=0 m:wkd_end2=0 m:block_nbr=600 m:wkd_end3=0 m:sun_rate3=0 m:sat_end3=0 m:sat_end2=0 m:unrestricted=1 m:segkey=16805 m:sun_rate1=0 m:sun_rate2=0 m:blockface_length=128 m:rpz_spaces=0 m:zone=0

series e:wbng-6x9n d:2016-04-21T15:37:03.000Z t:shape.longitude=-122.32618059099997 t:unitdesc="NE 42ND ST BETWEEN THACKERAY PL NE AND LATONA W AVE NE" t:parking_category="Unrestricted Parking" t:unitid=13225 t:side=S t:unitid2=0025 t:shape.needs_recoding=false t:csm=N t:overrideyn=N t:primarydistrictcd=DISTRICT4 t:shape.latitude=47.65766066000003 t:objectid=3 m:bus=0 m:tier=0 m:nopark=4 m:paid_spaces=0 m:end_distance=128 m:wkd_rate2=0 m:wkd_rate1=0 m:total_spaces=5 m:wkd_start3=0 m:wkd_rate3=0 m:wkd_start2=0 m:wkd_start1=0 m:parking_spaces=1 m:width=-13 m:sat_start3=0 m:sat_start1=0 m:sat_start2=0 m:elmntkey=84678 m:total_nopark=4 m:sat_rate2=0 m:sat_rate1=0 m:shape_length=113.80880590103406 m:sat_rate3=0 m:carpool_spaces=0 m:sun_start3=0 m:sun_end1=0 m:load=0 m:sun_end2=0 m:sun_end3=0 m:total_zones=0 m:sun_start1=0 m:sun_start2=0 m:sat_end1=0 m:nostop=0 m:tl_spaces=0 m:distance=13 m:wkd_end1=0 m:wkd_end2=0 m:block_nbr=200 m:wkd_end3=0 m:sun_rate3=0 m:sat_end3=0 m:sat_end2=0 m:unrestricted=1 m:segkey=16778 m:sun_rate1=0 m:sun_rate2=0 m:blockface_length=115 m:rpz_spaces=0 m:zone=0
```

## Meta Commands

```ls
metric m:elmntkey p:integer l:ELMNTKEY d:ELMNTKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:blockface_length p:integer l:BLOCKFACE_LENGTH d:BLOCKFACE_LENGTH t:dataTypeName=number

metric m:end_distance p:integer l:END_DISTANCE d:END_DISTANCE t:dataTypeName=number

metric m:width p:integer l:WIDTH d:WIDTH t:dataTypeName=number

metric m:block_nbr p:integer l:BLOCK_NBR d:BLOCK_NBR t:dataTypeName=number

metric m:total_spaces p:integer l:TOTAL_SPACES d:TOTAL_SPACES t:dataTypeName=number

metric m:paid_spaces p:integer l:PAID_SPACES d:PAID_SPACES t:dataTypeName=number

metric m:carpool_spaces p:integer l:CARPOOL_SPACES d:CARPOOL_SPACES t:dataTypeName=number

metric m:rpz_spaces p:integer l:RPZ_SPACES d:RPZ_SPACES t:dataTypeName=number

metric m:tl_spaces p:integer l:TL_SPACES d:TL_SPACES t:dataTypeName=number

metric m:bus p:integer l:BUS d:BUS t:dataTypeName=number

metric m:nopark p:integer l:NOPARK d:NOPARK t:dataTypeName=number

metric m:nostop p:integer l:NOSTOP d:NOSTOP t:dataTypeName=number

metric m:total_nopark p:integer l:TOTAL_NOPARK d:TOTAL_NOPARK t:dataTypeName=number

metric m:load p:integer l:LOAD d:LOAD t:dataTypeName=number

metric m:zone p:integer l:ZONE d:ZONE t:dataTypeName=number

metric m:total_zones p:integer l:TOTAL_ZONES d:TOTAL_ZONES t:dataTypeName=number

metric m:parking_spaces p:integer l:PARKING_SPACES d:PARKING_SPACES t:dataTypeName=number

metric m:unrestricted p:integer l:UNRESTRICTED d:UNRESTRICTED t:dataTypeName=number

metric m:tier p:integer l:TIER d:TIER t:dataTypeName=number

metric m:wkd_rate1 p:double l:WKD_RATE1 d:WKD_RATE1 t:dataTypeName=number

metric m:wkd_start1 p:integer l:WKD_START1 d:WKD_START1 t:dataTypeName=number

metric m:wkd_end1 p:integer l:WKD_END1 d:WKD_END1 t:dataTypeName=number

metric m:wkd_rate2 p:double l:WKD_RATE2 d:WKD_RATE2 t:dataTypeName=number

metric m:wkd_start2 p:integer l:WKD_START2 d:WKD_START2 t:dataTypeName=number

metric m:wkd_end2 p:integer l:WKD_END2 d:WKD_END2 t:dataTypeName=number

metric m:wkd_rate3 p:double l:WKD_RATE3 d:WKD_RATE3 t:dataTypeName=number

metric m:wkd_start3 p:integer l:WKD_START3 d:WKD_START3 t:dataTypeName=number

metric m:wkd_end3 p:integer l:WKD_END3 d:WKD_END3 t:dataTypeName=number

metric m:sat_rate1 p:double l:SAT_RATE1 d:SAT_RATE1 t:dataTypeName=number

metric m:sat_start1 p:integer l:SAT_START1 d:SAT_START1 t:dataTypeName=number

metric m:sat_end1 p:integer l:SAT_END1 d:SAT_END1 t:dataTypeName=number

metric m:sat_rate2 p:double l:SAT_RATE2 d:SAT_RATE2 t:dataTypeName=number

metric m:sat_start2 p:integer l:SAT_START2 d:SAT_START2 t:dataTypeName=number

metric m:sat_end2 p:integer l:SAT_END2 d:SAT_END2 t:dataTypeName=number

metric m:sat_rate3 p:double l:SAT_RATE3 d:SAT_RATE3 t:dataTypeName=number

metric m:sat_start3 p:integer l:SAT_START3 d:SAT_START3 t:dataTypeName=number

metric m:sat_end3 p:integer l:SAT_END3 d:SAT_END3 t:dataTypeName=number

metric m:sun_rate1 p:integer l:SUN_RATE1 d:SUN_RATE1 t:dataTypeName=number

metric m:sun_start1 p:integer l:SUN_START1 d:SUN_START1 t:dataTypeName=number

metric m:sun_end1 p:integer l:SUN_END1 d:SUN_END1 t:dataTypeName=number

metric m:sun_rate2 p:integer l:SUN_RATE2 d:SUN_RATE2 t:dataTypeName=number

metric m:sun_start2 p:integer l:SUN_START2 d:SUN_START2 t:dataTypeName=number

metric m:sun_end2 p:integer l:SUN_END2 d:SUN_END2 t:dataTypeName=number

metric m:sun_rate3 p:integer l:SUN_RATE3 d:SUN_RATE3 t:dataTypeName=number

metric m:sun_start3 p:integer l:SUN_START3 d:SUN_START3 t:dataTypeName=number

metric m:sun_end3 p:integer l:SUN_END3 d:SUN_END3 t:dataTypeName=number

metric m:rpz_area p:integer l:RPZ_AREA d:RPZ_AREA t:dataTypeName=number

metric m:parking_time_limit p:integer l:PARKING_TIME_LIMIT d:PARKING_TIME_LIMIT t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:wbng-6x9n l:"SDOT Street Blockfaces" t:url=https://data.seattle.gov/api/views/wbng-6x9n

property e:wbng-6x9n t:meta.view v:id=wbng-6x9n v:category=Transportation v:averageRating=0 v:name="SDOT Street Blockfaces"

property e:wbng-6x9n t:meta.view.license v:name="Public Domain"

property e:wbng-6x9n t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:wbng-6x9n t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | elmntkey | segkey | distance | blockface_length | end_distance | width | unitid | unitid2 | unitdesc                                                    | side | block_id | block_nbr | csm | parking_category     | total_spaces | paid_spaces | carpool_spaces | rpz_spaces | tl_spaces | bus | nopark | nostop | total_nopark | load | zone | total_zones | parking_spaces | unrestricted | tier | wkd_rate1 | wkd_start1 | wkd_end1 | wkd_rate2 | wkd_start2 | wkd_end2 | wkd_rate3 | wkd_start3 | wkd_end3 | sat_rate1 | sat_start1 | sat_end1 | sat_rate2 | sat_start2 | sat_end2 | sat_rate3 | sat_start3 | sat_end3 | sun_rate1 | sun_start1 | sun_end1 | sun_rate2 | sun_start2 | sun_end2 | sun_rate3 | sun_start3 | sun_end3 | peak_hour | rpz_zone | rpz_area | paidarea | parking_time_limit | subarea | start_time_wkd | end_time_wkd | start_time_sat | end_time_sat | start_time_sun | end_time_sun | shape                                                                                                                                                         | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | shape_length                                       | 
| =========== | ======== | ======== | ====== | ======== | ================ | ============ | ===== | ====== | ======= | =========================================================== | ==== | ======== | ========= | === | ==================== | ============ | =========== | ============== | ========== | ========= | === | ====== | ====== | ============ | ==== | ==== | =========== | ============== | ============ | ==== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ========== | ======== | ========= | ======== | ======== | ======== | ================== | ======= | ============== | ============ | ============== | ============ | ============== | ============ | ============================================================================================================================================================= | ================= | =================== | ========== | =============== | ================================================== | 
| 0           | 1        | 84738    | 16836  | 13       | 238              | 251          | -16   | 13280  | 0330    | NE 45TH PL BETWEEN NE BLAKELEY ST AND UNIVERSITY VIEW PL NE | SE   |          | 3300      | N   | Unrestricted Parking | 10           | 0           | 0              | 0          | 0         | 0   | 0      | 0      | 0            | 0    | 2    | 2           | 8              | 8            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 4-6PM     |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.66194213000006, -122.29142618999998, null, false, {paths=[[[-122.29142618999998, 47.66194213000006], [-122.29066468999997, 47.662340835000066]]]}]  | DISTRICT4         |                     | N          |                 | 237.409918218183548788147163577377796173095703125  | 
| 0           | 2        | 84714    | 16805  | 13       | 128              | 141          | -13   | 13250  | 0060    | NE 43RD ST BETWEEN DEAD END 1 AND 7TH AVE NE                | S    |          | 600       | N   | Unrestricted Parking | 5            | 0           | 0              | 0          | 0         | 0   | 4      | 0      | 4            | 0    | 0    | 0           | 1              | 1            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.65942198000005, -122.32140779299999, null, false, {paths=[[[-122.32140779299999, 47.65942198000005], [-122.32089261299996, 47.659426480000036]]]}]  | DISTRICT4         |                     | N          |                 | 126.96855067202568534412421286106109619140625      | 
| 0           | 3        | 84678    | 16778  | 13       | 115              | 128          | -13   | 13225  | 0025    | NE 42ND ST BETWEEN THACKERAY PL NE AND LATONA W AVE NE      | S    |          | 200       | N   | Unrestricted Parking | 5            | 0           | 0              | 0          | 0         | 0   | 4      | 0      | 4            | 0    | 0    | 0           | 1              | 1            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.65766066000003, -122.32618059099997, null, false, {paths=[[[-122.32618059099997, 47.65766066000003], [-122.32571880199998, 47.65765791200005]]]}]   | DISTRICT4         |                     | N          |                 | 113.8088059010340629129132139496505260467529296875 | 
| 0           | 4        | 84401    | 16496  | 23       | 275              | 298          | 23    | 12975  | 0260    | NE 125TH ST BETWEEN 26TH AVE NE AND 27TH AVE NE             | N    |          | 2600      | N   | Unrestricted Parking | 11           | 0           | 0              | 0          | 0         | 0   | 8      | 0      | 8            | 0    | 0    | 0           | 3              | 3            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.71937083800003, -122.30029949899995, null, false, {paths=[[[-122.30029949899995, 47.71937083800003], [-122.29918577799998, 47.719364186000064]]]}]  | DISTRICT5         |                     | N          |                 | 274.1530892933777749931323342025279998779296875    | 
| 0           | 5        | 84230    | 16270  | 13       | 389              | 402          | -13   | 12845  | 0280    | NE 107TH ST BETWEEN 28TH AVE NE AND 30TH AVE NE             | S    |          | 2800      | N   | Unrestricted Parking | 16           | 0           | 0              | 0          | 0         | 0   | 4      | 0      | 4            | 0    | 5    | 5           | 7              | 7            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.70665546500004, -122.29786572299997, null, false, {paths=[[[-122.29786572299997, 47.70665546500004], [-122.29629028899996, 47.706651212000054]]]}]  | DISTRICT5         |                     | N          |                 | 387.891020412815350937307812273502349853515625     | 
| 0           | 6        | 84118    | 16185  | 13       | 322              | 335          | -28   | 12795  | 0020    | NE 103RD ST BETWEEN 2ND AVE NE AND 3RD AVE NE               | S    |          | 200       | N   | No Parking Allowed   | 13           | 0           | 0              | 0          | 0         | 10  | 8      | 0      | 18           | 0    | 0    | 0           | 0              | 0            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.70309352800007, -122.32720280699999, null, false, {paths=[[[-122.32720280699999, 47.70309352800007], [-122.32589909099994, 47.703083907000064]]]}]  | DISTRICT5         |                     | N          |                 | 321.02926592011289130823570303618907928466796875   | 
| 0           | 7        | 83734    | 15784  | 13       | 319              | 332          | -13   | 12330  | 0212    | N 64TH ST BETWEEN WOODLAWN AVE N AND CORLISS AVE N          | S    |          | 2100      | N   | Unrestricted Parking | 13           | 0           | 0              | 0          | 0         | 0   | 8      | 0      | 8            | 0    | 0    | 0           | 5              | 5            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.67517540500006, -122.33220633399998, null, false, {paths=[[[-122.33220633399998, 47.67517540500006], [-122.33091548399995, 47.67516132900005]]]}]   | DISTRICT6         |                     | N          |                 | 318.05436650031350609424407593905925750732421875   | 
| 0           | 8        | 83494    | 15570  | 13       | 284              | 297          | -13   | 12140  | 0170    | N 46TH ST BETWEEN DENSMORE AVE N AND WALLINGFORD AVE N      | S    |          | 1700      | N   | Unrestricted Parking | 11           | 0           | 0              | 0          | 0         | 0   | 8      | 0      | 8            | 0    | 0    | 0           | 3              | 3            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.66209154100005, -122.33763130699998, null, false, {paths=[[[-122.33763130699998, 47.66209154100005], [-122.33648261999997, 47.66209125200004]]]}]   | DISTRICT4         |                     | N          |                 | 283.06111628399366964004002511501312255859375      | 
| 0           | 9        | 83401    | 15470  | 13       | 279              | 292          | 13    | 12080  | 0120    | N 42ND ST BETWEEN MIDVALE AVE N AND STONE WAY N             | N    |          | 1200      | N   | No Parking Allowed   | 11           | 0           | 0              | 0          | 0         | 0   | 12     | 0      | 12           | 0    | 0    | 0           | 0              | 0            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.65805691800006, -122.34349804299995, null, false, {paths=[[[-122.34349804299995, 47.65805691800006], [-122.34237085399997, 47.658051896000075]]]}]  | DISTRICT4         |                     | N          |                 | 277.7910399780242869383073411881923675537109375    | 
| 0           | 10       | 83385    | 15453  | 13       | 52               | 65           | 13    | 12080  | 0010    | N 42ND ST BETWEEN 1ST W AVE NW AND 1ST E AVE NW             | N    |          | 100       | N   | No Parking Allowed   | 2            | 0           | 0              | 0          | 0         | 0   | 4      | 0      | 4            | 0    | 0    | 0           | 0              | 0            | 0    | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        | 0         | 0          | 0        |           |          |          |          |                    |         |                |              |                |              |                |              | [null, 47.657760960000076, -122.35752433399995, null, false, {paths=[[[-122.35752433399995, 47.657760960000076], [-122.35731729899999, 47.65776126500003]]]}] | DISTRICT6         |                     | N          |                 | 51.022251202424740768037736415863037109375         | 
```