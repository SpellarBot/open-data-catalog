# street_centerline [arcgis_rest_services_GDX_street_centerline_MapServer_0]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-county-street-centerlines) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qtz9-vukc) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qtz9-vukc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qtz9-vukc/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qtz9-vukc |
| Name | street_centerline [arcgis_rest_services_GDX_street_centerline_MapServer_0] |
| Category | Transportation |
| Tags | technology, map, geographic, street, centerlines |
| Created | 2014-12-30T20:21:04Z |
| Publication Date | 2014-12-30T20:21:27Z |

## Description

https://gis3.montgomerycountymd.gov/arcgis/rest/services/GDX/street_centerline/MapServer/0

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type  | Render Type |
| ======== | ============== | ============= | ============= | ========== | =========== |
| Yes      | series tag     | objectid      | OBJECTID      | text       | number      |
| Yes      | series tag     | census_id     | CENSUS_ID     | text       | number      |
| Yes      | series tag     | pre_dir       | PRE_DIR       | text       | text        |
| Yes      | series tag     | street_name   | STREET_NAME   | text       | text        |
| Yes      | series tag     | street_type   | STREET_TYPE   | text       | text        |
| Yes      | series tag     | suf_dir       | SUF_DIR       | text       | text        |
| Yes      | numeric metric | l_f_add       | L_F_ADD       | number     | number      |
| Yes      | numeric metric | l_t_add       | L_T_ADD       | number     | number      |
| Yes      | numeric metric | r_f_add       | R_F_ADD       | number     | number      |
| Yes      | numeric metric | r_t_add       | R_T_ADD       | number     | number      |
| Yes      | series tag     | istreet       | ISTREET       | text       | text        |
| Yes      | series tag     | l_zip         | L_ZIP         | text       | text        |
| Yes      | series tag     | r_zip         | R_ZIP         | text       | text        |
| Yes      | series tag     | l_muni        | L_MUNI        | text       | text        |
| Yes      | series tag     | r_muni        | R_MUNI        | text       | text        |
| Yes      | series tag     | route_number  | ROUTE_NUMBER  | text       | text        |
| Yes      | series tag     | cfcc          | CFCC          | text       | text        |
| Yes      | series tag     | snow_priority | SNOW_PRIORITY | text       | text        |
| Yes      | series tag     | carto         | CARTO         | text       | text        |
| No       |                | shape         | SHAPE         | geospatial | geospatial  |
| Yes      | numeric metric | shape_len     | SHAPE.LEN     | number     | number      |
| Yes      | numeric metric | st_class      | ST_CLASS      | number     | number      |
| Yes      | numeric metric | travel_direct | TRAVEL_DIRECT | number     | number      |
| Yes      | series tag     | oneway        | ONEWAY        | text       | text        |
| Yes      | numeric metric | speed         | SPEED         | number     | number      |
| Yes      | time           | create_date   | CREATE_DATE   | text       | number      |
| Yes      | numeric metric | updated       | UPDATED       | number     | number      |
| Yes      | numeric metric | psupdated     | PSUPDATED     | number     | number      |
```

## Time Field

```ls
Value = create_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:qtz9-vukc d:1996-01-01T00:00:00.000Z t:shape.longitude=-77.05047308699994 t:r_muni=MCG t:street_name="LONDON BRIDGE" t:carto=A50 t:census_id=119143 t:l_muni=MCG t:shape.needs_recoding=false t:l_zip=20906 t:r_zip=20906 t:istreet="LONDON BRIDGE CT" t:cfcc=A50 t:shape.latitude=39.101156812000056 t:objectid=5113412 t:street_type=CT m:r_t_add=99 m:updated=0 m:r_f_add=1 m:speed=25 m:l_f_add=2 m:travel_direct=2 m:l_t_add=98 m:st_class=5 m:psupdated=0

series e:qtz9-vukc d:1996-01-01T00:00:00.000Z t:shape.longitude=-77.04986291399996 t:r_muni=MCG t:street_name="LONDON BRIDGE" t:carto=A40 t:census_id=119140 t:l_muni=MCG t:shape.needs_recoding=false t:l_zip=20906 t:r_zip=20906 t:istreet="LONDON BRIDGE DR" t:cfcc=A40 t:shape.latitude=39.10097680400003 t:objectid=5113413 t:street_type=DR m:r_t_add=2375 m:updated=0 m:r_f_add=2355 m:speed=30 m:l_f_add=2354 m:travel_direct=2 m:l_t_add=2374 m:st_class=4 m:psupdated=0

series e:qtz9-vukc d:1996-01-01T00:00:00.000Z t:shape.longitude=-77.04854558499994 t:r_muni=MCG t:street_name="LONDON BRIDGE" t:carto=A40 t:census_id=119139 t:l_muni=MCG t:shape.needs_recoding=false t:l_zip=20906 t:r_zip=20906 t:istreet="LONDON BRIDGE DR" t:cfcc=A40 t:shape.latitude=39.101130513000044 t:objectid=5113414 t:street_type=DR m:r_t_add=2353 m:updated=0 m:r_f_add=2319 m:speed=30 m:l_f_add=2320 m:travel_direct=2 m:l_t_add=2352 m:st_class=4 m:psupdated=0
```

## Meta Commands

```ls
metric m:l_f_add p:integer l:L_F_ADD d:L_F_ADD t:dataTypeName=number

metric m:l_t_add p:integer l:L_T_ADD d:L_T_ADD t:dataTypeName=number

metric m:r_f_add p:integer l:R_F_ADD d:R_F_ADD t:dataTypeName=number

metric m:r_t_add p:integer l:R_T_ADD d:R_T_ADD t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

metric m:st_class p:integer l:ST_CLASS d:ST_CLASS t:dataTypeName=number

metric m:travel_direct p:integer l:TRAVEL_DIRECT d:TRAVEL_DIRECT t:dataTypeName=number

metric m:speed p:integer l:SPEED d:SPEED t:dataTypeName=number

metric m:updated p:integer l:UPDATED d:UPDATED t:dataTypeName=number

metric m:psupdated p:integer l:PSUPDATED d:PSUPDATED t:dataTypeName=number

entity e:qtz9-vukc l:"street_centerline [arcgis_rest_services_GDX_street_centerline_MapServer_0]" t:url=https://data.montgomerycountymd.gov/api/views/qtz9-vukc

property e:qtz9-vukc t:meta.view v:id=qtz9-vukc v:category=Transportation v:averageRating=0 v:name="street_centerline [arcgis_rest_services_GDX_street_centerline_MapServer_0]"

property e:qtz9-vukc t:meta.view.owner v:id=hesx-43k8 v:screenName=Dan v:displayName=Dan

property e:qtz9-vukc t:meta.view.tableauthor v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```

## Top Records

```ls
| objectid | census_id | pre_dir | street_name   | street_type | suf_dir | l_f_add | l_t_add | r_f_add | r_t_add | istreet          | l_zip | r_zip | l_muni | r_muni | route_number | cfcc | snow_priority | carto | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | shape_len | st_class | travel_direct | oneway | speed | create_date | updated | psupdated | 
| ======== | ========= | ======= | ============= | =========== | ======= | ======= | ======= | ======= | ======= | ================ | ===== | ===== | ====== | ====== | ============ | ==== | ============= | ===== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | ======== | ============= | ====== | ===== | =========== | ======= | ========= | 
| 5113412  | 119143    |         | LONDON BRIDGE | CT          |         | 2       | 98      | 1       | 99      | LONDON BRIDGE CT | 20906 | 20906 | MCG    | MCG    |              | A50  |               | A50   | [null, 39.101156812000056, -77.05047308699994, null, false, {paths=[[[-77.05047308699994, 39.101156812000056], [-77.05085914299997, 39.100829056000066]]]}]                                                                                                                                                                                                                                                                                                                                                                                    |           | 5        | 2             |        | 25    | 19960101    | 0       | 0         | 
| 5113413  | 119140    |         | LONDON BRIDGE | DR          |         | 2354    | 2374    | 2355    | 2375    | LONDON BRIDGE DR | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.10097680400003, -77.04986291399996, null, false, {paths=[[[-77.04986291399996, 39.10097680400003], [-77.04999197099994, 39.10097795100006], [-77.05004615199994, 39.10098136000005], [-77.05010561999995, 39.100989742000024], [-77.05014746999996, 39.100997275000054], [-77.05018755899994, 39.10100652400007], [-77.05022324399994, 39.101016634000075], [-77.05025364299996, 39.10102674500007], [-77.05030122599999, 39.101045258000056], [-77.05033912099998, 39.10106549000005], [-77.05047308699994, 39.101156812000056]]]}] |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
| 5113414  | 119139    |         | LONDON BRIDGE | DR          |         | 2320    | 2352    | 2319    | 2353    | LONDON BRIDGE DR | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.101130513000044, -77.04854558499994, null, false, {paths=[[[-77.04854558499994, 39.101130513000044], [-77.04872133199996, 39.10113198400006], [-77.04969555699995, 39.10100510500007], [-77.04986291399996, 39.10097680400003]]]}]                                                                                                                                                                                                                                                                                                   |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
| 5113415  | 120121    |         | WIMBLEDON     | CIR         |         | 2200    | 2212    | 2201    | 2213    | WIMBLEDON CIR    | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.099731131000055, -77.04762054799994, null, false, {paths=[[[-77.04762054799994, 39.099731131000055], [-77.04733723199996, 39.099580065000055], [-77.04703980199997, 39.09939742800003], [-77.04693449499996, 39.099338954000075], [-77.04689616599995, 39.09932541200004], [-77.04684374699997, 39.09931728300006], [-77.04669619899994, 39.09932497800003]]]}]                                                                                                                                                                      |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
| 5113416  | 120125    |         | DUNVEGAN      | CT          |         | 14900   | 14998   | 14901   | 14999   | DUNVEGAN CT      | 20906 | 20906 | MCG    | MCG    |              | A50  |               | A50   | [null, 39.09932497800003, -77.04669619899994, null, false, {paths=[[[-77.04669619899994, 39.09932497800003], [-77.04653969099996, 39.09910084100005], [-77.04653439599997, 39.09908591400006], [-77.04653262399995, 39.099070985000026], [-77.04653965899996, 39.099052020000045], [-77.04656210899998, 39.09903296300007], [-77.04660922399995, 39.09901123700007], [-77.04666426699998, 39.098989851000056]]]}]                                                                                                                              |           | 5        | 2             |        | 25    | 19960101    | 0       | 0         | 
| 5113417  | 120122    |         | WIMBLEDON     | CIR         |         | 2214    | 2228    | 2215    | 2229    | WIMBLEDON CIR    | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.09932497800003, -77.04669619899994, null, false, {paths=[[[-77.04669619899994, 39.09932497800003], [-77.04660108799999, 39.09936637200008], [-77.04654032999997, 39.099403977000065], [-77.04648310199997, 39.09945282000007], [-77.04642236199999, 39.09951976900004], [-77.04635415799999, 39.099621556000045], [-77.04630710399994, 39.09973706400007]]]}]                                                                                                                                                                        |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
| 5113418  | 120124    |         | WIMBLEDON     | CIR         |         | 2246    | 2298    | 2247    | 2299    | WIMBLEDON CIR    | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.100398451000046, -77.04666034599995, null, false, {paths=[[[-77.04666034599995, 39.100398451000046], [-77.04685501799997, 39.10037984000007], [-77.04744869199999, 39.10027629700005]]]}]                                                                                                                                                                                                                                                                                                                                            |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
| 5113419  | 120127    |         | TRAVERT       | WAY         |         | 15012   | 15098   | 15013   | 15099   | TRAVERT WAY      | 20906 | 20906 | MCG    | MCG    |              | A50  |               | A50   | [null, 39.09973946100007, -77.04610229299999, null, false, {paths=[[[-77.04610229299999, 39.09973946100007], [-77.04605658399998, 39.09989220500006], [-77.04603505199998, 39.09997029300007], [-77.04603861399994, 39.10002880700006], [-77.04614185299994, 39.10029286300005]]]}]                                                                                                                                                                                                                                                            |           | 5        | 2             |        | 25    | 19960101    | 0       | 0         | 
| 5113420  | 120120    |         | WIMBLEDON     | CT          |         | 2       | 98      | 1       | 99      | WIMBLEDON CT     | 20906 | 20906 | MCG    | MCG    |              | A50  |               | A50   | [null, 39.100398451000046, -77.04666034599995, null, false, {paths=[[[-77.04666034599995, 39.100398451000046], [-77.04665114399995, 39.10047198600006], [-77.04665468499996, 39.10049703800007], [-77.04668338799996, 39.10060856900003], [-77.04669397699996, 39.100636450000025], [-77.04671205299996, 39.10066158200004], [-77.04673320199998, 39.10067272800006], [-77.04675478899998, 39.10067829700006], [-77.04687633799995, 39.10065036300006], [-77.04691200099995, 39.10062864100007]]]}]                                            |           | 5        | 2             |        | 25    | 19960101    | 0       | 0         | 
| 5113421  | 120126    |         | TRAVERT       | WAY         |         | 15000   | 15010   | 15001   | 15011   | TRAVERT WAY      | 20906 | 20906 | MCG    | MCG    |              | A40  |               | A40   | [null, 39.09973706400007, -77.04630710399994, null, false, {paths=[[[-77.04630710399994, 39.09973706400007], [-77.04615996899997, 39.099702544000024], [-77.04612429699995, 39.09971088000003], [-77.04610229299999, 39.09973946100007]]]}]                                                                                                                                                                                                                                                                                                    |           | 4        | 2             |        | 30    | 19960101    | 0       | 0         | 
```