# Hydrants [arcgis_rest_services_general_hydrants_MapServer_0]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-county-fire-hydrants) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/d7i2-mvrw) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/d7i2-mvrw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/d7i2-mvrw/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | d7i2-mvrw |
| Name | Hydrants [arcgis_rest_services_general_hydrants_MapServer_0] |
| Category | Public Safety |
| Tags | technology, map, geographic, public safety, fire hydrant |
| Created | 2014-12-30T15:41:28Z |
| Publication Date | 2014-12-30T15:41:46Z |

## Description

https://gis3.montgomerycountymd.gov/arcgis/rest/services/general/hydrants/MapServer/0

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | hyd_id      | HYD_ID      | text      | number      |
| Yes      | series tag     | g_key_co_1  | G_KEY_CO_1  | text      | text        |
| Yes      | series tag     | private     | PRIVATE     | text      | text        |
| Yes      | series tag     | st_num      | ST_NUM      | text      | text        |
| Yes      | series tag     | st_name     | ST_NAME     | text      | text        |
| Yes      | time           | edit_date   | EDIT_DATE   | date      | date        |
| No       |                | imprt_date  | IMPRT_DATE  | date      | date        |
| Yes      | series tag     | own         | OWN         | text      | text        |
| Yes      | series tag     | oth_id      | OTH_ID      | text      | text        |
| Yes      | numeric metric | main        | MAIN        | number    | text        |
| Yes      | series tag     | st_type     | ST_TYPE     | text      | text        |
| Yes      | series tag     | st_prefix   | ST_PREFIX   | text      | text        |
| Yes      | series tag     | st_suffix   | ST_SUFFIX   | text      | text        |
| No       |                | x           | X           | number    | number      |
| No       |                | y           | Y           | number    | number      |
| Yes      | series tag     | city        | CITY        | text      | text        |
| Yes      | series tag     | zip         | ZIP         | text      | text        |
| Yes      | series tag     | label       | LABEL       | text      | text        |
| Yes      | series tag     | ooc         | OOC         | text      | text        |
| Yes      | numeric metric | station     | STATION     | number    | text        |
| Yes      | series tag     | objectid_1  | OBJECTID_1  | text      | number      |
| Yes      | series tag     | verified    | VERIFIED    | text      | text        |
| Yes      | series tag     | f_polygonid | F_POLYGONID | text      | number      |
| Yes      | numeric metric | f_scale     | F_SCALE     | number    | number      |
| Yes      | numeric metric | f_angle     | F_ANGLE     | number    | number      |
```

## Time Field

```ls
Value = edit_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = imprt_date,x,y
```

## Data Commands

```ls
series e:d7i2-mvrw d:2015-06-05T00:00:00.000Z t:zip=20872 t:g_key_co_1=FH40D10004 t:st_num=28607 t:hyd_id=1 t:objectid_1=1 t:st_name=KEMPTOWN t:st_type=RD t:label=28607 t:f_polygonid=0 t:city=Damascus m:station=13 m:f_scale=1 m:f_angle=1 m:main=12

series e:d7i2-mvrw d:2015-06-05T00:00:00.000Z t:zip=20872 t:g_key_co_1=FH40D10003 t:st_num=10101 t:hyd_id=2 t:objectid_1=2 t:st_name=JOHNS t:st_type=DR t:label=10101 t:f_polygonid=0 t:city=Damascus m:station=13 m:f_scale=1 m:f_angle=1 m:main=8

series e:d7i2-mvrw d:2015-06-05T00:00:00.000Z t:zip=20872 t:g_key_co_1=FH40D10010 t:st_num=28407 t:hyd_id=3 t:objectid_1=3 t:st_name=KEMPTOWN t:st_type=RD t:label=28407 t:f_polygonid=0 t:city=Damascus m:station=13 m:f_scale=1 m:f_angle=1 m:main=0
```

## Meta Commands

```ls
metric m:main p:long l:MAIN d:MAIN t:dataTypeName=number

metric m:station p:integer l:STATION d:STATION t:dataTypeName=number

metric m:f_scale p:integer l:F_SCALE d:F_SCALE t:dataTypeName=number

metric m:f_angle p:integer l:F_ANGLE d:F_ANGLE t:dataTypeName=number

entity e:d7i2-mvrw l:"Hydrants [arcgis_rest_services_general_hydrants_MapServer_0]" t:url=https://data.montgomerycountymd.gov/api/views/d7i2-mvrw

property e:d7i2-mvrw t:meta.view v:id=d7i2-mvrw v:category="Public Safety" v:averageRating=0 v:name="Hydrants [arcgis_rest_services_general_hydrants_MapServer_0]"

property e:d7i2-mvrw t:meta.view.owner v:id=hesx-43k8 v:screenName=Dan v:displayName=Dan

property e:d7i2-mvrw t:meta.view.tableauthor v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```

## Top Records

```ls
| hyd_id | g_key_co_1 | private | st_num | st_name   | edit_date  | imprt_date | own | oth_id | main | st_type | st_prefix | st_suffix | x                                                  | y                                                  | city     | zip   | label | ooc | station | objectid_1 | verified | f_polygonid | f_scale | f_angle | 
| ====== | ========== | ======= | ====== | ========= | ========== | ========== | === | ====== | ==== | ======= | ========= | ========= | ================================================== | ================================================== | ======== | ===== | ===== | === | ======= | ========== | ======== | =========== | ======= | ======= | 
| 1      | FH40D10004 |         | 28607  | KEMPTOWN  | 1433462400 | 972432000  |     |        | 12   | RD      |           |           | -77.208134209999997210616129450500011444091796875  | 39.32554748999999816305717104114592075347900390625 | Damascus | 20872 | 28607 |     | 13      | 1          |          | 0           | 1       | 1       | 
| 2      | FH40D10003 |         | 10101  | JOHNS     | 1433462400 | 972432000  |     |        | 8    | DR      |           |           | -77.208534339999999929204932413995265960693359375  | 39.323741339999997990162228234112262725830078125   | Damascus | 20872 | 10101 |     | 13      | 2          |          | 0           | 1       | 1       | 
| 3      | FH40D10010 |         | 28407  | KEMPTOWN  | 1433462400 | 972432000  |     |        | 0    | RD      |           |           | -77.2033971599999944146475172601640224456787109375 | 39.322632400000003372042556293308734893798828125   | Damascus | 20872 | 28407 |     | 13      | 3          |          | 0           | 1       | 1       | 
| 4      | FH40D10009 |         | 9900   | MOXLEY    | 1433462400 | 972432000  |     |        | 10   | RD      |           |           | -77.205668610000003582172212190926074981689453125  | 39.32257793000000134497895487584173679351806640625 | Damascus | 20872 | 9900  |     | 13      | 4          |          | 0           | 1       | 1       | 
| 5      | FH40D10006 |         | 10213  | FOX RIDGE | 1433462400 | 972432000  |     |        | 8    | DR      |           |           | -77.2117954999999938081600703299045562744140625    | 39.3223782900000031759191188029944896697998046875  | Damascus | 20872 | 10213 |     | 13      | 5          |          | 0           | 1       | 1       | 
| 6      | FH40D10007 |         | 10201  | FOX RIDGE | 1433462400 | 972432000  |     |        | 8    | DR      |           |           | -77.2101489899999933186336420476436614990234375    | 39.322300630000000865038600750267505645751953125   | Damascus | 20872 | 10201 |     | 13      | 6          |          | 0           | 1       | 1       | 
| 7      | FH40D10008 |         | 9937   | MOXLEY    | 1433462400 | 972432000  |     |        | 10   | RD      |           |           | -77.206486060000003135428414680063724517822265625  | 39.3210753999999980123902787454426288604736328125  | Damascus | 20872 | 9937  |     | 13      | 7          |          | 0           | 1       | 1       | 
| 8      | FH40D09001 |         | 28201  | KEMPTOWN  | 1433462400 | 972432000  |     |        | 12   | RD      |           |           | -77.19871636999999964245944283902645111083984375   | 39.31838364000000041187377064488828182220458984375 | Damascus | 20872 | 28201 |     | 13      | 8          |          | 0           | 1       | 1       | 
| 9      | FH39D09001 |         | 28000  | RIDGE     | 1433462400 | 972432000  |     |        | 12   | RD      |           |           | -77.1981960300000054076008382253348827362060546875 | 39.316820890000002464148565195500850677490234375   | Damascus | 20872 | 28000 |     | 13      | 9          |          | 0           | 1       | 1       | 
| 10     | FH39D09002 |         | 27912  | RIDGE     | 1433462400 | 972432000  |     |        | 12   | RD      |           |           | -77.1982022600000021839150576852262020111083984375 | 39.31505333999999862726326682604849338531494140625 | Damascus | 20872 | 27912 |     | 13      | 10         |          | 0           | 1       | 1       | 
```