# CGDB.CONTOUR1993_LN

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cgdb-contour1993-ln-c0f02) |
| Metadata | [Link](https://data.seattle.gov/api/views/vsbp-6kht) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vsbp-6kht/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vsbp-6kht/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vsbp-6kht |
| Name | CGDB.CONTOUR1993_LN |
| Attribution | Seattle GIS Program |
| Category | Land Base |
| Tags | contour lines, topographical |
| Created | 2011-12-14T16:52:23Z |
| Publication Date | 2011-12-14T16:53:49Z |

## Description

2 foot contour lines

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type  | Render Type |
| ======== | ============== | ============ | ============ | ========== | =========== |
| Yes      | series tag     | objectid     | OBJECTID     | text       | number      |
| No       |                | shape        | Shape        | geospatial | geospatial  |
| Yes      | numeric metric | cl93_lngth   | CL93_LNGTH   | number     | number      |
| Yes      | series tag     | cl93_type    | CL93_TYPE    | text       | text        |
| Yes      | numeric metric | cl93_src     | CL93_SRC     | number     | number      |
| Yes      | numeric metric | cl93_elev    | CL93_ELEV    | number     | number      |
| Yes      | numeric metric | shape_length | Shape_Length | number     | number      |
```

## Time Field

```ls
Value = 1993
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:vsbp-6kht d:1993-01-01T00:00:00.000Z t:shape.longitude=-122.36238101599997 t:cl93_type=INT t:shape.needs_recoding=false t:shape.latitude=47.777765944000066 t:objectid=1 m:shape_length=8.642726665609008 m:cl93_lngth=19.19433 m:cl93_src=1 m:cl93_elev=406

series e:vsbp-6kht d:1993-01-01T00:00:00.000Z t:shape.longitude=-122.361761377 t:cl93_type=INT t:shape.needs_recoding=false t:shape.latitude=47.777767262000054 t:objectid=2 m:shape_length=4.558022746949069 m:cl93_lngth=10.09945 m:cl93_src=1 m:cl93_elev=398

series e:vsbp-6kht d:1993-01-01T00:00:00.000Z t:shape.longitude=-122.36184024799996 t:cl93_type=INT t:shape.needs_recoding=false t:shape.latitude=47.777692682000065 t:objectid=3 m:shape_length=46.46952491865414 m:cl93_lngth=103.08642 m:cl93_src=1 m:cl93_elev=408
```

## Meta Commands

```ls
metric m:cl93_lngth p:decimal l:CL93_LNGTH d:CL93_LNGTH t:dataTypeName=number

metric m:cl93_src p:integer l:CL93_SRC d:CL93_SRC t:dataTypeName=number

metric m:cl93_elev p:integer l:CL93_ELEV d:CL93_ELEV t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:vsbp-6kht l:CGDB.CONTOUR1993_LN t:attribution="Seattle GIS Program" t:url=https://data.seattle.gov/api/views/vsbp-6kht

property e:vsbp-6kht t:meta.view v:id=vsbp-6kht v:category="Land Base" v:attributionLink=https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/1 v:averageRating=0 v:name=CGDB.CONTOUR1993_LN v:attribution="Seattle GIS Program"

property e:vsbp-6kht t:meta.view.license v:name="Public Domain"

property e:vsbp-6kht t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vsbp-6kht t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | shape                                                                                                                                                                                                                                                                                      | cl93_lngth                                           | cl93_type | cl93_src | cl93_elev | shape_length                                        | 
| ======== | ========================================================================================================================================================================================================================================================================================== | ==================================================== | ========= | ======== | ========= | =================================================== | 
| 1        | [null, 47.777765944000066, -122.36238101599997, null, false, {paths=[[[-122.36238101599997, 47.777765944000066], [-122.36241700199997, 47.77775899200003], [-122.36245590499999, 47.77776578400005]]]}]                                                                                    | 19.19433000000000077989170677028596401214599609375   | INT       | 1        | 406       | 8.642726665609007596913215820677578449249267578125  | 
| 2        | [null, 47.777767262000054, -122.361761377, null, false, {paths=[[[-122.361761377, 47.777767262000054], [-122.36180232299995, 47.777767175000065]]]}]                                                                                                                                       | 10.0994499999999991501908880309201776981353759765625 | INT       | 1        | 398       | 4.5580227469490690594966508797369897365570068359375 | 
| 3        | [null, 47.777692682000065, -122.36184024799996, null, false, {paths=[[[-122.36184024799996, 47.777692682000065], [-122.36183142299996, 47.77769691200007], [-122.36175448799997, 47.77769520100003], [-122.36206651399999, 47.77776661400003]]]}]                                          | 103.086420000000003938112058676779270172119140625    | INT       | 1        | 408       | 46.46952491865413747973434510640799999237060546875  | 
| 4        | [null, 47.77768370900003, -122.36234644099994, null, false, {paths=[[[-122.36234644099994, 47.77768370900003], [-122.36241790699995, 47.77770688100003], [-122.36254581499998, 47.77771284600004], [-122.36263439199996, 47.77773688600007], [-122.36265678399997, 47.77776535600003]]]}]  | 86.6403499999999979763742885552346706390380859375    | INT       | 1        | 412       | 39.0745037335837679393080179579555988311767578125   | 
| 5        | [null, 47.77768512200004, -122.36172896999994, null, false, {paths=[[[-122.36172896999994, 47.77768512200004], [-122.36171781899998, 47.777693224000075], [-122.36172606499997, 47.77769695200004], [-122.36181560999995, 47.77771247900006], [-122.36204043299995, 47.77776666900007]]]}] | 88.0515899999999902547642705030739307403564453125    | INT       | 1        | 406       | 39.81736327483355353251681663095951080322265625     | 
| 6        | [null, 47.77767240500003, -122.36253526699994, null, false, {paths=[[[-122.36253526699994, 47.77767240500003], [-122.36255438499995, 47.77768613400008], [-122.36268238599996, 47.77772280600004], [-122.36271035299995, 47.777765241000054]]]}]                                           | 58.2774399999999985766407917253673076629638671875    | INT       | 1        | 414       | 26.29253498067964045503686065785586833953857421875  | 
| 7        | [null, 47.77766401800005, -122.36279292599994, null, false, {paths=[[[-122.36279292599994, 47.77766401800005], [-122.36285857499996, 47.77769686500005], [-122.36287634399997, 47.77774762800004], [-122.36289618499995, 47.777764844000046]]]}]                                           | 47.2700899999999961664798320271074771881103515625    | INT       | 1        | 422       | 21.356852348638657446144861751236021518707275390625 | 
| 8        | [null, 47.777657702000056, -122.36291640599995, null, false, {paths=[[[-122.36291640599995, 47.777657702000056], [-122.36294918199997, 47.77769318300005], [-122.36296409599998, 47.77774371000004], [-122.36298887099997, 47.77776464600004]]]}]                                          | 44.08030999999999721694621257483959197998046875      | INT       | 1        | 426       | 19.882004837069775504687640932388603687286376953125 | 
| 9        | [null, 47.77764876200007, -122.36313336999996, null, false, {paths=[[[-122.36313336999996, 47.77764876200007], [-122.36320210999997, 47.77767608400006], [-122.36321753499999, 47.77768876400006], [-122.36322234099998, 47.77774134600003], [-122.36327593499999, 47.77776403300004]]]}]  | 60.5236699999999956389729049988090991973876953125    | INT       | 1        | 436       | 27.381199137901152340646149241365492343902587890625 | 
| 10       | [null, 47.77764739000003, -122.36317441599999, null, false, {paths=[[[-122.36317441599999, 47.77764739000003], [-122.36324669399994, 47.77767055000004], [-122.36327363499998, 47.77768746400005], [-122.36328728099994, 47.77773636400008], [-122.36333702499996, 47.77776390300005]]]}]  | 62.918319999999994251993484795093536376953125        | INT       | 1        | 438       | 28.43421827889300601555078173987567424774169921875  | 
```