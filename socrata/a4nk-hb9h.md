# Legal Subdivisions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/legal-subdivisions-1cbc2) |
| Metadata | [Link](https://data.seattle.gov/api/views/a4nk-hb9h) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/a4nk-hb9h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/a4nk-hb9h/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | a4nk-hb9h |
| Name | Legal Subdivisions |
| Attribution | Seattle GIS Program |
| Category | Land Base |
| Tags | subdivisions, legal description, land, lots, blocks |
| Created | 2011-12-14T21:09:23Z |
| Publication Date | 2011-12-28T16:34:17Z |

## Description

Legal divisions of land: lots, blocks

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type  | Render Type |
| ======== | ============== | ================ | ================ | ========== | =========== |
| Yes      | series tag     | objectid_12      | OBJECTID_12      | text       | number      |
| No       |                | shape            | Shape            | geospatial | geospatial  |
| Yes      | series tag     | l_id             | L_ID             | text       | number      |
| Yes      | numeric metric | l_area           | L_AREA           | number     | number      |
| Yes      | numeric metric | l_prmtr          | L_PRMTR          | number     | number      |
| Yes      | series tag     | plat_id          | PLAT_ID          | text       | text        |
| Yes      | series tag     | plat_sym         | PLAT_SYM         | text       | text        |
| Yes      | series tag     | block_id         | BLOCK_ID         | text       | text        |
| Yes      | series tag     | tract_id         | TRACT_ID         | text       | text        |
| Yes      | series tag     | lot_id           | LOT_ID           | text       | text        |
| Yes      | series tag     | unitlot_id       | UNITLOT_ID       | text       | text        |
| Yes      | series tag     | rw_id            | RW_ID            | text       | number      |
| Yes      | series tag     | rw_adjst_id      | RW_ADJST_ID      | text       | text        |
| Yes      | series tag     | deed_id          | DEED_ID          | text       | text        |
| Yes      | series tag     | court_id         | COURT_ID         | text       | text        |
| Yes      | numeric metric | l_fea_sym        | L_FEA_SYM        | number     | number      |
| Yes      | numeric metric | attr_acrcy       | ATTR_ACRCY       | number     | number      |
| Yes      | time           | l_edt_date       | L_EDT_DATE       | date       | date        |
| Yes      | series tag     | objectid         | OBJECTID         | text       | number      |
| Yes      | series tag     | rw_adjst_id_1    | RW_ADJST_ID_1    | text       | text        |
| Yes      | series tag     | la_vrt_ord       | LA_VRT_ORD       | text       | text        |
| Yes      | numeric metric | la_kcrecnum      | LA_KCRECNUM      | number     | number      |
| Yes      | series tag     | la_ord_juris     | LA_ORD_JURIS     | text       | text        |
| Yes      | series tag     | la_ord_type      | LA_ORD_TYPE      | text       | text        |
| Yes      | series tag     | la_cndmntn_map   | LA_CNDMNTN_MAP   | text       | text        |
| Yes      | series tag     | objectid_1       | OBJECTID_1       | text       | number      |
| Yes      | series tag     | plat_id_1        | PLAT_ID_1        | text       | text        |
| Yes      | series tag     | plat_sym_1       | PLAT_SYM_1       | text       | text        |
| Yes      | numeric metric | lp_kcrecnum      | LP_KCRECNUM      | number     | number      |
| Yes      | series tag     | lp_name          | LP_NAME          | text       | text        |
| Yes      | series tag     | lp_type          | LP_TYPE          | text       | text        |
| Yes      | series tag     | lp_mup           | LP_MUP           | text       | text        |
| Yes      | series tag     | lp_prnt_plat_id  | LP_PRNT_PLAT_ID  | text       | text        |
| Yes      | numeric metric | lp_prnt_kcrecnum | LP_PRNT_KCRECNUM | number     | number      |
| Yes      | series tag     | lp_prnt_type     | LP_PRNT_TYPE     | text       | text        |
| Yes      | numeric metric | shape_length     | Shape_Length     | number     | number      |
| Yes      | numeric metric | shape_area       | Shape_Area       | number     | number      |
```

## Time Field

```ls
Value = l_edt_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:a4nk-hb9h d:2006-11-25T20:20:10.000Z t:shape.longitude=-122.35753104599996 t:lp_type=STP t:plat_sym=FMY t:plat_id=55-33 t:rw_id=0 t:shape.needs_recoding=false t:lot_id=11 t:objectid_1=6171 t:objectid_12=1 t:lp_name=GLENMERE t:shape.latitude=47.76943169200007 t:plat_id_1=55-33 t:plat_sym_1=FMY t:l_id=6938 t:block_id=2 m:shape_area=0 m:l_prmtr=361.52572 m:shape_length=163.95776679007193 m:lp_kcrecnum=0 m:l_area=7784.99745 m:attr_acrcy=0 m:l_fea_sym=1

series e:a4nk-hb9h d:2006-11-25T20:20:10.000Z t:plat_id="106-56 57" t:shape.longitude=-122.28251565499994 t:rw_id=0 t:lp_type=STP t:lot_id=C t:shape.needs_recoding=false t:objectid_1=332 t:lp_name="SUNSET ESTATES" t:objectid_12=2 t:plat_id_1="106-56 57" t:shape.latitude=47.77034462300003 t:plat_sym_1=OOJ t:l_id=6939 t:plat_sym=OOJ m:shape_area=571.8801130090851 m:l_prmtr=211.41622999999998 m:shape_length=95.80434211875638 m:lp_kcrecnum=0 m:l_area=2755.82384 m:attr_acrcy=0 m:l_fea_sym=1

series e:a4nk-hb9h d:2006-11-25T20:20:10.000Z t:shape.longitude=-122.38875001599996 t:lp_type=STP t:plat_sym=MKA t:plat_id=16-48 t:rw_id=0 t:shape.needs_recoding=false t:lot_id=4 t:objectid_1=1409 t:objectid_12=3 t:lp_name="RICHMOND RESERVE" t:shape.latitude=47.76900679100004 t:plat_id_1=16-48 t:plat_sym_1=MKA t:l_id=6940 t:block_id=2 m:shape_area=0 m:l_prmtr=338.45902 m:shape_length=153.45357891053487 m:lp_kcrecnum=0 m:l_area=6775.095700000001 m:attr_acrcy=0 m:l_fea_sym=1
```

## Meta Commands

```ls
metric m:l_area p:long l:L_AREA d:CADASTRAL_LEGAL_PLGN_PV.L_AREA t:dataTypeName=number

metric m:l_prmtr p:long l:L_PRMTR d:CADASTRAL_LEGAL_PLGN_PV.L_PRMTR t:dataTypeName=number

metric m:l_fea_sym p:long l:L_FEA_SYM d:L_FEA_SYM t:dataTypeName=number

metric m:attr_acrcy p:long l:ATTR_ACRCY d:ATTR_ACRCY t:dataTypeName=number

metric m:la_kcrecnum p:long l:LA_KCRECNUM d:CADASTRAL_LEGAL_PLGN_PV.LA_KCRECNUM t:dataTypeName=number

metric m:lp_kcrecnum p:long l:LP_KCRECNUM d:CADASTRAL_LEGAL_PLGN_PV.LP_KCRECNUM t:dataTypeName=number

metric m:lp_prnt_kcrecnum p:long l:LP_PRNT_KCRECNUM d:CADASTRAL_LEGAL_PLGN_PV.LP_PRNT_KCRECNUM t:dataTypeName=number

metric m:shape_length p:long l:Shape_Length d:Shape_Length t:dataTypeName=number

metric m:shape_area p:long l:Shape_Area d:Shape_Area t:dataTypeName=number

entity e:a4nk-hb9h l:"Legal Subdivisions" t:attribution="Seattle GIS Program" t:url=https://data.seattle.gov/api/views/a4nk-hb9h

property e:a4nk-hb9h t:meta.view v:id=a4nk-hb9h v:category="Land Base" v:attributionLink=https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/3 v:averageRating=0 v:name="Legal Subdivisions" v:attribution="Seattle GIS Program"

property e:a4nk-hb9h t:meta.view.license v:name="Public Domain"

property e:a4nk-hb9h t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:a4nk-hb9h t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid_12 | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | l_id | l_area                                        | l_prmtr                                          | plat_id   | plat_sym | block_id | tract_id | lot_id | unitlot_id | rw_id   | rw_adjst_id | deed_id | court_id | l_fea_sym | attr_acrcy | l_edt_date | objectid | rw_adjst_id_1 | la_vrt_ord | la_kcrecnum | la_ord_juris | la_ord_type | la_cndmntn_map | objectid_1 | plat_id_1 | plat_sym_1 | lp_kcrecnum | lp_name           | lp_type | lp_mup | lp_prnt_plat_id | lp_prnt_kcrecnum | lp_prnt_type | shape_length                                      | shape_area                                      | 
| =========== | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ==== | ============================================= | ================================================ | ========= | ======== | ======== | ======== | ====== | ========== | ======= | =========== | ======= | ======== | ========= | ========== | ========== | ======== | ============= | ========== | =========== | ============ | =========== | ============== | ========== | ========= | ========== | =========== | ================= | ======= | ====== | =============== | ================ | ============ | ================================================= | =============================================== | 
| 1           | [null, 47.76943169200007, -122.35753104599996, null, false, {rings=[[[-122.35753104599996, 47.76943169200007], [-122.35724427799994, 47.76943020400006], [-122.35724793499998, 47.76912917200008], [-122.35753692299994, 47.76912980800006], [-122.35753104599996, 47.76943169200007]]]}]                                                                                                                                                                                                                                                                                                                                           | 6938 | 7784.9974499999998442945070564746856689453125 | 361.5257199999999784267856739461421966552734375  | 55-33     | FMY      | 2        |          | 11     |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6171       | 55-33     | FMY        | 0           | GLENMERE          | STP     |        |                 |                  |              | 163.957766790071929108307813294231891632080078125 | 0                                               | 
| 2           | [null, 47.77034462300003, -122.28251565499994, null, false, {rings=[[[-122.28251565499994, 47.77034462300003], [-122.28260531499996, 47.77023510500004], [-122.28280426799995, 47.77023339900006], [-122.28280787199998, 47.77028354400005], [-122.28264367999998, 47.77040521200007], [-122.28251565499994, 47.77034462300003]]]}]                                                                                                                                                                                                                                                                                                 | 6939 | 2755.8238400000000183354131877422332763671875 | 211.41622999999998455677996389567852020263671875 | 106-56 57 | OOJ      |          |          | C      |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 332        | 106-56 57 | OOJ        | 0           | SUNSET ESTATES    | STP     |        |                 |                  |              | 95.8043421187563808416598476469516754150390625    | 571.880113009085107478313148021697998046875     | 
| 3           | [null, 47.76900679100004, -122.38875001599996, null, false, {rings=[[[-122.38875001599996, 47.76900679100004], [-122.38856894699995, 47.76887762600006], [-122.38886369799997, 47.76867280100004], [-122.38904654999999, 47.76880323900008], [-122.38875001599996, 47.76900679100004]]]}]                                                                                                                                                                                                                                                                                                                                           | 6940 | 6775.0957000000007610651664435863494873046875 | 338.459020000000009531504474580287933349609375   | 16-48     | MKA      | 2        |          | 4      |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 1409       | 16-48     | MKA        | 0           | RICHMOND RESERVE  | STP     |        |                 |                  |              | 153.45357891053487264798604883253574371337890625  | 0                                               | 
| 4           | [null, 47.76991687100008, -122.32046233399996, null, false, {rings=[[[-122.32046233399996, 47.76991687100008], [-122.32019809899998, 47.76991225300003], [-122.32020904099994, 47.76962552300006], [-122.32047329499994, 47.76962971700004], [-122.32046233399996, 47.76991687100008]]]}]                                                                                                                                                                                                                                                                                                                                           | 6941 | 6805.6562199999998483690433204174041748046875 | 339.404279999999971551005728542804718017578125   | 55-43     | JZW      |          |          | 12     |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6172       | 55-43     | JZW        | 0           | METCALF ADD       | STP     |        |                 |                  |              | 153.93070972362949078160454519093036651611328125  | 1398.86568808533729679766111075878143310546875  | 
| 5           | [null, 47.76991225300003, -122.32019809899998, null, false, {rings=[[[-122.32019809899998, 47.76991225300003], [-122.31993385899995, 47.76990763800006], [-122.31994479099995, 47.76962132800003], [-122.32020904099994, 47.76962552300006], [-122.32019809899998, 47.76991225300003]]]}]                                                                                                                                                                                                                                                                                                                                           | 6945 | 6795.645080000000234576873481273651123046875  | 339.09692000000001144144334830343723297119140625 | 55-43     | JZW      |          |          | 11     |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6172       | 55-43     | JZW        | 0           | METCALF ADD       | STP     |        |                 |                  |              | 153.791262881090830205721431411802768707275390625 | 1396.816746946710054544382728636264801025390625 | 
| 6           | [null, 47.76962193600008, -122.34217876799994, null, false, {rings=[[[-122.34217876799994, 47.76962193600008], [-122.34117542699994, 47.76962525400006], [-122.341173589, 47.76954005700003], [-122.34145772599999, 47.76953915100006], [-122.34145280899997, 47.76931731900004], [-122.34153413799999, 47.76931709200005], [-122.341532315, 47.76923485800006], [-122.34181607399995, 47.769234065000035], [-122.34181616899997, 47.769165532000045], [-122.34243762299997, 47.769163795000054], [-122.34235646599996, 47.76939027000003], [-122.34229488199998, 47.769621554000025], [-122.34217876799994, 47.76962193600008]]]}] | 6946 | 36453.3899699999965378083288669586181640625   | 925.50106000000005224137566983699798583984375    | L93S0031  | OLWL     |          |          | 1      |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 11602      | L93S0031  | OLWL       | 0           |                   | SHP     |        |                 |                  |              | 419.398627225609743618406355381011962890625       | 7507.513867499757907353341579437255859375       | 
| 7           | [null, 47.769822360000035, -122.32694998599999, null, false, {rings=[[[-122.32694998599999, 47.769822360000035], [-122.32666843699997, 47.76981767500007], [-122.32666823599999, 47.76949635900007], [-122.32694396699998, 47.76950079800008], [-122.32694998599999, 47.769822360000035]]]}]                                                                                                                                                                                                                                                                                                                                        | 6947 | 8032.8044700000000375439412891864776611328125 | 371.591949999999997089616954326629638671875      | 53-10     | KGC      | C        |          | 1      |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6062       | 53-10     | KGC        | 0           | MORRISON ADD NO 3 | STP     |        |                 |                  |              | 168.535928848615156994128483347594738006591796875 | 0                                               | 
| 8           | [null, 47.770403599000076, -122.28139298599996, null, false, {rings=[[[-122.28139298599996, 47.770403599000076], [-122.28139171799995, 47.77033780900007], [-122.28218542899998, 47.77033381000007], [-122.28218588799996, 47.77037493000006], [-122.28199065099994, 47.770375914000056], [-122.28199169099997, 47.770400583000026], [-122.28139298599996, 47.770403599000076]]]}]                                                                                                                                                                                                                                                  | 6949 | 4251.54680999999982304871082305908203125      | 438.4296199999999998908606357872486114501953125  | 106-56 57 | OOJ      |          |          | A      |            | 4220040 |             |         |          | 2         | 0          | 1164486010 |          |               |            |             |              |             |                | 332        | 106-56 57 | OOJ        | 0           | SUNSET ESTATES    | STP     |        |                 |                  |              | 198.537711594102574963471852242946624755859375    | 0                                               | 
| 9           | [null, 47.76990763800006, -122.31993385899995, null, false, {rings=[[[-122.31993385899995, 47.76990763800006], [-122.31962896799996, 47.76990231000008], [-122.31963988299998, 47.769616488000054], [-122.31994479099995, 47.76962132800003], [-122.31993385899995, 47.76990763800006]]]}]                                                                                                                                                                                                                                                                                                                                          | 6952 | 7828.789539999999760766513645648956298828125  | 358.767200000000002546585164964199066162109375   | 55-43     | JZW      |          |          | 10     |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6172       | 55-43     | JZW        | 0           | METCALF ADD       | STP     |        |                 |                  |              | 162.6948335355906465338193811476230621337890625   | 1609.1636490057571791112422943115234375         | 
| 10          | [null, 47.76981767500007, -122.32666843699997, null, false, {rings=[[[-122.32666843699997, 47.76981767500007], [-122.32637576399998, 47.76981280200005], [-122.32638009899995, 47.769491724000034], [-122.32666823599999, 47.76949635900007], [-122.32666843699997, 47.76981767500007]]]}]                                                                                                                                                                                                                                                                                                                                          | 6953 | 8367.91445000000021536834537982940673828125   | 377.1993300000000317595549859106540679931640625  | 53-10     | KGC      | C        |          | 2      |            | 0       |             |         |          | 1         | 0          | 1164486010 |          |               |            |             |              |             |                | 6062       | 53-10     | KGC        | 0           | MORRISON ADD NO 3 | STP     |        |                 |                  |              | 171.0740748356830636112135834991931915283203125   | 1719.97218241058590137981809675693511962890625  | 
```