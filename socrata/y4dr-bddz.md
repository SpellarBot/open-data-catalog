# CADASTRAL.CONTROL_LN [ArcGIS_rest_services_ext_WM_CityGISLayers_MapServer_2]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cadastral-control-ln-arcgis-rest-services-ext-wm-citygislayers-mapserver-2-bb4d4) |
| Metadata | [Link](https://data.seattle.gov/api/views/y4dr-bddz) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/y4dr-bddz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/y4dr-bddz/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | y4dr-bddz |
| Name | CADASTRAL.CONTROL_LN [ArcGIS_rest_services_ext_WM_CityGISLayers_MapServer_2] |
| Attribution | Seattle GIS Program |
| Category | Land Base |
| Tags | cadastral, survey |
| Created | 2011-12-14T21:08:48Z |
| Publication Date | 2011-12-28T16:36:05Z |

## Description

Survey lines

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type  | Render Type |
| ======== | ============== | ============== | ============== | ========== | =========== |
| Yes      | series tag     | objectid       | OBJECTID       | text       | number      |
| No       |                | shape          | Shape          | geospatial | geospatial  |
| Yes      | series tag     | cl_id          | CL_ID          | text       | number      |
| Yes      | numeric metric | cl_lngth       | CL_LNGTH       | number     | number      |
| Yes      | series tag     | angle          | ANGLE          | text       | text        |
| Yes      | series tag     | distance       | DISTANCE       | text       | text        |
| Yes      | series tag     | radius         | RADIUS         | text       | text        |
| Yes      | series tag     | delta          | DELTA          | text       | text        |
| Yes      | series tag     | tangent        | TANGENT        | text       | text        |
| Yes      | series tag     | arclength      | ARCLENGTH      | text       | text        |
| Yes      | series tag     | side           | SIDE           | text       | text        |
| Yes      | series tag     | cl_type        | CL_TYPE        | text       | text        |
| Yes      | series tag     | dim_type       | DIM_TYPE       | text       | text        |
| Yes      | numeric metric | cl_agncy       | CL_AGNCY       | number     | number      |
| Yes      | numeric metric | cl_src_doc     | CL_SRC_DOC     | number     | number      |
| Yes      | series tag     | cl_fldbk       | CL_FLDBK       | text       | text        |
| Yes      | series tag     | cl_fldbk_pg    | CL_FLDBK_PG    | text       | text        |
| Yes      | numeric metric | cl_pstn_acrcy  | CL_PSTN_ACRCY  | number     | number      |
| Yes      | series tag     | from_cp_loc_id | FROM_CP_LOC_ID | text       | text        |
| Yes      | series tag     | to_cp_loc_id   | TO_CP_LOC_ID   | text       | text        |
| Yes      | time           | cl_edt_date    | CL_EDT_DATE    | date       | date        |
| Yes      | numeric metric | len            | LEN            | number     | number      |
| Yes      | numeric metric | shape_length   | Shape_Length   | number     | number      |
```

## Time Field

```ls
Value = cl_edt_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:y4dr-bddz d:2006-11-25T20:10:45.000Z t:shape.longitude=-122.36283938599996 t:distance=15 t:cl_type=CEN t:shape.needs_recoding=false t:shape.latitude=47.77696297400007 t:dim_type=S t:objectid=1 t:cl_id=1 m:shape_length=6.4314224333061505 m:cl_src_doc=39 m:cl_agncy=3 m:len=14.205211070549499 m:cl_pstn_acrcy=0 m:cl_lngth=14.205129999999999

series e:y4dr-bddz d:2006-11-25T20:10:45.000Z t:shape.longitude=-122.36283775199996 t:distance=114.33 t:cl_type=CEN t:shape.needs_recoding=false t:shape.latitude=47.77664344100003 t:dim_type=S t:objectid=2 t:angle=N00-28-40E t:cl_id=2 m:shape_length=52.930512561063665 m:cl_src_doc=39 m:cl_agncy=3 m:len=116.55588661972301 m:cl_pstn_acrcy=0 m:cl_lngth=116.55587

series e:y4dr-bddz d:2006-11-25T20:10:45.000Z t:shape.longitude=-122.36398622899998 t:distance=286.37 t:cl_type=CEN t:shape.needs_recoding=false t:shape.latitude=47.77664524100004 t:dim_type=S t:objectid=3 t:angle=N88-44-24W t:cl_id=3 m:shape_length=127.84824753731233 m:cl_src_doc=39 m:cl_agncy=3 m:len=282.386427514367 m:cl_pstn_acrcy=0 m:cl_lngth=282.38643
```

## Meta Commands

```ls
metric m:cl_lngth p:long l:CL_LNGTH d:CL_LNGTH t:dataTypeName=number

metric m:cl_agncy p:long l:CL_AGNCY d:CL_AGNCY t:dataTypeName=number

metric m:cl_src_doc p:long l:CL_SRC_DOC d:CL_SRC_DOC t:dataTypeName=number

metric m:cl_pstn_acrcy p:long l:CL_PSTN_ACRCY d:CL_PSTN_ACRCY t:dataTypeName=number

metric m:len p:long l:LEN d:LEN t:dataTypeName=number

metric m:shape_length p:long l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:y4dr-bddz l:"CADASTRAL.CONTROL_LN [ArcGIS_rest_services_ext_WM_CityGISLayers_MapServer_2]" t:attribution="Seattle GIS Program" t:url=https://data.seattle.gov/api/views/y4dr-bddz

property e:y4dr-bddz t:meta.view v:id=y4dr-bddz v:category="Land Base" v:attributionLink=https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/2 v:averageRating=0 v:name="CADASTRAL.CONTROL_LN [ArcGIS_rest_services_ext_WM_CityGISLayers_MapServer_2]" v:attribution="Seattle GIS Program"

property e:y4dr-bddz t:meta.view.license v:name="Public Domain"

property e:y4dr-bddz t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:y4dr-bddz t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | shape                                                                                                                                                                                                    | cl_id | cl_lngth                                             | angle      | distance | radius | delta | tangent | arclength | side | cl_type | dim_type | cl_agncy | cl_src_doc | cl_fldbk | cl_fldbk_pg | cl_pstn_acrcy | from_cp_loc_id | to_cp_loc_id | cl_edt_date | len                                                 | shape_length                                         | 
| ======== | ======================================================================================================================================================================================================== | ===== | ==================================================== | ========== | ======== | ====== | ===== | ======= | ========= | ==== | ======= | ======== | ======== | ========== | ======== | =========== | ============= | ============== | ============ | =========== | =================================================== | ==================================================== | 
| 1        | [null, 47.77696297400007, -122.36283938599996, null, false, {paths=[[[-122.36283938599996, 47.77696297400007], [-122.36289713099995, 47.77696172600008]]]}]                                              | 1     | 14.2051299999999987022647474077530205249786376953125 |            | 15       |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 14.205211070549498941772981197573244571685791015625 | 6.43142243330615048790832588565535843372344970703125 | 
| 2        | [null, 47.77664344100003, -122.36283775199996, null, false, {paths=[[[-122.36283775199996, 47.77664344100003], [-122.36283938599996, 47.77696297400007]]]}]                                              | 2     | 116.555869999999998753992258571088314056396484375    | N00-28-40E | 114.33   |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 116.5558866197230116767968866042792797088623046875  | 52.9305125610636650890228338539600372314453125       | 
| 3        | [null, 47.77664524100004, -122.36398622899998, null, false, {paths=[[[-122.36398622899998, 47.77664524100004], [-122.36283775199996, 47.77664344100003]]]}]                                              | 3     | 282.38643000000001848093234002590179443359375        | N88-44-24W | 286.37   |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 282.3864275143670283796382136642932891845703125     | 127.8482475373123321560342446900904178619384765625   | 
| 4        | [null, 47.77661543600004, -122.36129162099996, null, false, {paths=[[[-122.36129162099996, 47.77661543600004], [-122.36129202599994, 47.77664100100003]]]}]                                              | 4     | 9.3262499999999999289457264239899814128875732421875  |            |          |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 9.326218324417869354192589526064693927764892578125  | 4.235139083140570193108942476101219654083251953125   | 
| 5        | [null, 47.77596739000006, -122.36128270899997, null, false, {paths=[[[-122.36128270899997, 47.77596739000006], [-122.36129162099996, 47.77661543600004]]]}]                                              | 5     | 236.396490000000000009094947017729282379150390625    |            |          |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 236.3964746137550037019536830484867095947265625     | 107.35168438454439865381573326885700225830078125     | 
| 6        | [null, 47.77596542600003, -122.36160766899997, null, false, {paths=[[[-122.36160766899997, 47.77596542600003], [-122.36128270899997, 47.77596739000006]]]}]                                              | 6     | 79.9052300000000030877345125190913677215576171875    | N89-31-20W | 77.68    |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 79.905156818625897585661732591688632965087890625    | 36.1758617090481919831290724687278270721435546875    | 
| 7        | [null, 47.775923729000056, -122.36200632299995, null, false, {paths=[[[-122.36200632299995, 47.775923729000056], [-122.36180912499998, 47.775953849000075], [-122.36160766899997, 47.77596542600003]]]}] | 7     | 99.4894199999999955252860672771930694580078125       |            |          | 350.0  |       |         | 95.76     |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 99.4893290071671998475721920840442180633544921875   | 45.019581516787667396783945150673389434814453125     | 
| 8        | [null, 47.77589633100007, -122.36397205899999, null, false, {paths=[[[-122.36397205899999, 47.77589633100007], [-122.36240583999995, 47.77589293400007]]]}]                                              | 8     | 385.1071799999999711872078478336334228515625         | N88-34-41W | 389.77   |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 385.10700982722704566185711883008480072021484375    | 174.351608350574991845860495232045650482177734375    | 
| 9        | [null, 47.77589293400007, -122.36240583999995, null, false, {paths=[[[-122.36240583999995, 47.77589293400007], [-122.36220437499998, 47.77589828600003], [-122.36200632299995, 47.775923729000056]]]}]   | 9     | 99.2173700000000025056579033844172954559326171875    |            |          | 350.0  |       |         | 101.52    |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 99.2176212551151905927326879464089870452880859375   | 44.89073836862007738091051578521728515625            | 
| 10       | [null, 47.77589633100007, -122.36397205899999, null, false, {paths=[[[-122.36397205899999, 47.77589633100007], [-122.36396515199999, 47.77562398200007]]]}]                                              | 10    | 99.3588099999999911915438133291900157928466796875    | N00-41-21E |          |        |       |         |           |      | CEN     | S        | 3        | 39         |          |             | 0             |                |              | 1164485445  | 99.358853060780489840908558107912540435791015625    | 45.12005026156774789569681161083281040191650390625   | 
```