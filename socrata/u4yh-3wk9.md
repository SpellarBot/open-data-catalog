# Census - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-2010) |
| Metadata | [Link](https://data.nola.gov/api/views/u4yh-3wk9) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/u4yh-3wk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/u4yh-3wk9/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | u4yh-3wk9 |
| Name | Census - 2010 |
| Created | 2015-05-08T04:56:56Z |
| Publication Date | 2015-05-08T04:57:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type    | Render Type  |
| ======== | ============== | ================= | ================== | ============ | ============ |
| Yes      | series tag     | feature_id        | _feature_id        | text         | number       |
| Yes      | series tag     | feature_id_string | _feature_id_string | text         | text         |
| No       |                | the_geom          | the_geom           | multipolygon | multipolygon |
| Yes      | series tag     | statefp10         | statefp10          | text         | text         |
| Yes      | series tag     | countyfp10        | countyfp10         | text         | text         |
| Yes      | series tag     | tractce10         | tractce10          | text         | text         |
| Yes      | series tag     | blockce10         | blockce10          | text         | text         |
| Yes      | series tag     | geoid10           | geoid10            | text         | text         |
| Yes      | series tag     | name10            | name10             | text         | text         |
| Yes      | series tag     | mtfcc10           | mtfcc10            | text         | text         |
| Yes      | series tag     | ur10              | ur10               | text         | text         |
| Yes      | series tag     | uace10            | uace10             | text         | text         |
| Yes      | series tag     | funcstat10        | funcstat10         | text         | text         |
| Yes      | numeric metric | aland10           | aland10            | number       | number       |
| Yes      | numeric metric | awater10          | awater10           | number       | number       |
| Yes      | series tag     | intptlat10        | intptlat10         | text         | text         |
| Yes      | series tag     | intptlon10        | intptlon10         | text         | text         |
| Yes      | numeric metric | oid_              | oid_               | number       | number       |
| Yes      | series tag     | geoid10_1         | geoid10_1          | text         | text         |
| Yes      | numeric metric | total_pop         | total_pop          | number       | number       |
| Yes      | numeric metric | white             | white              | number       | number       |
| Yes      | numeric metric | black             | black              | number       | number       |
| Yes      | numeric metric | amer_ind          | amer_ind           | number       | number       |
| Yes      | numeric metric | asian             | asian              | number       | number       |
| Yes      | numeric metric | pac_islndr        | pac_islndr         | number       | number       |
| Yes      | numeric metric | other_race        | other_race         | number       | number       |
| Yes      | numeric metric | multi_race        | multi_race         | number       | number       |
| Yes      | numeric metric | hispanic          | hispanic           | number       | number       |
| Yes      | numeric metric | non_hisp          | non_hisp           | number       | number       |
| Yes      | numeric metric | total_hu          | total_hu           | number       | number       |
| Yes      | numeric metric | occ_hu            | occ_hu             | number       | number       |
| Yes      | numeric metric | vacant_hu         | vacant_hu          | number       | number       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = the_geom
```

## Data Commands

```ls
series e:u4yh-3wk9 d:2010-01-01T00:00:00.000Z t:countyfp10=071 t:tractce10=002401 t:funcstat10=S t:name10="Block 1011" t:geoid10=220710024011011 t:mtfcc10=G5040 t:feature_id_string=orl_census2010_block_pl.1 t:statefp10=22 t:feature_id=1 t:blockce10=1011 t:intptlat10=+29.9944976 t:geoid10_1=220710024011011 t:intptlon10=-090.0532519 m:occ_hu=28 m:white=0 m:pac_islndr=0 m:total_hu=36 m:oid_=6308 m:aland10=18350 m:other_race=0 m:hispanic=0 m:awater10=0 m:asian=0 m:vacant_hu=8 m:non_hisp=77 m:amer_ind=0 m:total_pop=77 m:multi_race=0 m:black=77

series e:u4yh-3wk9 d:2010-01-01T00:00:00.000Z t:countyfp10=071 t:tractce10=012000 t:funcstat10=S t:name10="Block 1037" t:geoid10=220710120001037 t:mtfcc10=G5040 t:feature_id_string=orl_census2010_block_pl.2 t:statefp10=22 t:feature_id=2 t:blockce10=1037 t:intptlat10=+29.9259469 t:geoid10_1=220710120001037 t:intptlon10=-090.1345273 m:occ_hu=0 m:white=0 m:pac_islndr=0 m:total_hu=0 m:oid_=9569 m:aland10=58092 m:other_race=0 m:hispanic=0 m:awater10=0 m:asian=0 m:vacant_hu=0 m:non_hisp=0 m:amer_ind=0 m:total_pop=0 m:multi_race=0 m:black=0

series e:u4yh-3wk9 d:2010-01-01T00:00:00.000Z t:countyfp10=071 t:tractce10=012200 t:funcstat10=S t:name10="Block 2034" t:geoid10=220710122002034 t:mtfcc10=G5040 t:feature_id_string=orl_census2010_block_pl.3 t:statefp10=22 t:feature_id=3 t:blockce10=2034 t:intptlat10=+29.9435142 t:geoid10_1=220710122002034 t:intptlon10=-090.1126884 m:occ_hu=0 m:white=0 m:pac_islndr=0 m:total_hu=0 m:oid_=9771 m:aland10=5735 m:other_race=0 m:hispanic=0 m:awater10=0 m:asian=0 m:vacant_hu=0 m:non_hisp=0 m:amer_ind=0 m:total_pop=0 m:multi_race=0 m:black=0
```

## Meta Commands

```ls
metric m:aland10 p:long l:aland10 t:dataTypeName=number

metric m:awater10 p:long l:awater10 t:dataTypeName=number

metric m:oid_ p:long l:oid_ t:dataTypeName=number

metric m:total_pop p:long l:total_pop t:dataTypeName=number

metric m:white p:long l:white t:dataTypeName=number

metric m:black p:long l:black t:dataTypeName=number

metric m:amer_ind p:long l:amer_ind t:dataTypeName=number

metric m:asian p:long l:asian t:dataTypeName=number

metric m:pac_islndr p:long l:pac_islndr t:dataTypeName=number

metric m:other_race p:long l:other_race t:dataTypeName=number

metric m:multi_race p:long l:multi_race t:dataTypeName=number

metric m:hispanic p:long l:hispanic t:dataTypeName=number

metric m:non_hisp p:long l:non_hisp t:dataTypeName=number

metric m:total_hu p:long l:total_hu t:dataTypeName=number

metric m:occ_hu p:long l:occ_hu t:dataTypeName=number

metric m:vacant_hu p:long l:vacant_hu t:dataTypeName=number

entity e:u4yh-3wk9 l:"Census - 2010" t:url=https://data.nola.gov/api/views/u4yh-3wk9

property e:u4yh-3wk9 t:meta.view v:id=u4yh-3wk9 v:averageRating=0 v:name="Census - 2010"

property e:u4yh-3wk9 t:meta.view.owner v:id=y4bj-k9rq v:screenName="Alejandro Escobar" v:displayName="Alejandro Escobar"

property e:u4yh-3wk9 t:meta.view.tableauthor v:id=y4bj-k9rq v:screenName="Alejandro Escobar" v:displayName="Alejandro Escobar"

property e:u4yh-3wk9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| feature_id | feature_id_string          | the_geom                                                                                                                                                                                                                                                                                                                                                                                                                    | statefp10 | countyfp10 | tractce10 | blockce10 | geoid10         | name10     | mtfcc10 | ur10 | uace10 | funcstat10 | aland10 | awater10 | intptlat10  | intptlon10   | oid_  | geoid10_1       | total_pop | white | black | amer_ind | asian | pac_islndr | other_race | multi_race | hispanic | non_hisp | total_hu | occ_hu | vacant_hu | 
| ========== | ========================== | =========================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | ========== | ========= | ========= | =============== | ========== | ======= | ==== | ====== | ========== | ======= | ======== | =========== | ============ | ===== | =============== | ========= | ===== | ===== | ======== | ===== | ========== | ========== | ========== | ======== | ======== | ======== | ====== | ========= | 
| 1          | orl_census2010_block_pl.1  | MULTIPOLYGON (((-90.053122 29.99348499918256, -90.054181 29.995113999182532, -90.053372 29.995501999182526, -90.052328 29.993887999182547, -90.053122 29.99348499918256)))                                                                                                                                                                                                                                                  | 22        | 071        | 002401    | 1011      | 220710024011011 | Block 1011 | G5040   |      |        | S          | 18350   | 0        | +29.9944976 | -090.0532519 | 6308  | 220710024011011 | 77.0      | 0.0   | 77.0  | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 77.0     | 36.0     | 28.0   | 8.0       | 
| 2          | orl_census2010_block_pl.2  | MULTIPOLYGON (((-90.13511899999997 29.923583999183712, -90.13520899999999 29.922290999183733, -90.13542699999999 29.925035999183688, -90.135285 29.925590999183672, -90.135481 29.925737999183678, -90.13554299999998 29.926104999183668, -90.13358300000002 29.928702999183628, -90.133591 29.92585399918368, -90.13435399999999 29.924912999183697, -90.134548 29.9243369991837, -90.13511899999997 29.923583999183712))) | 22        | 071        | 012000    | 1037      | 220710120001037 | Block 1037 | G5040   |      |        | S          | 58092   | 0        | +29.9259469 | -090.1345273 | 9569  | 220710120001037 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 0.0      | 0.0    | 0.0       | 
| 3          | orl_census2010_block_pl.3  | MULTIPOLYGON (((-90.111944 29.942999999183396, -90.112045 29.942748999183397, -90.11294699999999 29.943463999183383, -90.11322299999998 29.94404099918337, -90.11300700000001 29.944465999183368, -90.11254699999999 29.943450999183387, -90.111944 29.942999999183396)))                                                                                                                                                   | 22        | 071        | 012200    | 2034      | 220710122002034 | Block 2034 | G5040   |      |        | S          | 5735    | 0        | +29.9435142 | -090.1126884 | 9771  | 220710122002034 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 0.0      | 0.0    | 0.0       | 
| 4          | orl_census2010_block_pl.4  | MULTIPOLYGON (((-90.11246399999999 29.938286999183468, -90.11276199999999 29.93729899918349, -90.112971 29.937350999183483, -90.11251600000001 29.93830099918347, -90.11246399999999 29.938286999183468)))                                                                                                                                                                                                                  | 22        | 071        | 011900    | 2009      | 220710119002009 | Block 2009 | G5040   |      |        | S          | 1407    | 0        | +29.9377104 | -090.1127129 | 9688  | 220710119002009 | 4.0       | 4.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 4.0      | 2.0      | 1.0    | 1.0       | 
| 5          | orl_census2010_block_pl.5  | MULTIPOLYGON (((-90.11131499999998 29.942696999183397, -90.11139100000001 29.942364999183404, -90.112045 29.942748999183397, -90.111944 29.942999999183396, -90.11131499999998 29.942696999183397)))                                                                                                                                                                                                                        | 22        | 071        | 012200    | 2035      | 220710122002035 | Block 2035 | G5040   |      |        | S          | 2373    | 0        | +29.9426913 | -090.1116651 | 9772  | 220710122002035 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 1.0      | 0.0    | 1.0       | 
| 6          | orl_census2010_block_pl.6  | MULTIPOLYGON (((-90.11251600000001 29.93830099918347, -90.11352099999999 29.93856299918346, -90.113213 29.93943099918345, -90.11223499999998 29.939159999183452, -90.11251600000001 29.93830099918347)))                                                                                                                                                                                                                    | 22        | 071        | 011900    | 2000      | 220710119002000 | Block 2000 | G5040   |      |        | S          | 10263   | 0        | +29.9388555 | -090.1128614 | 9679  | 220710119002000 | 51.0      | 38.0  | 3.0   | 0.0      | 5.0   | 0.0        | 5.0        | 0.0        | 5.0      | 46.0     | 27.0     | 22.0   | 5.0       | 
| 7          | orl_census2010_block_pl.7  | MULTIPOLYGON (((-90.12360599999998 29.934876999183523, -90.12382 29.935035999183526, -90.12369399999999 29.935172999183518, -90.123488 29.93501399918352, -90.12360599999998 29.934876999183523)))                                                                                                                                                                                                                          | 22        | 071        | 012102    | 2010      | 220710121022010 | Block 2010 | G5040   |      |        | S          | 516     | 0        | +29.9350251 | -090.1236527 | 12860 | 220710121022010 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 0.0      | 0.0    | 0.0       | 
| 8          | orl_census2010_block_pl.8  | MULTIPOLYGON (((-90.12306300000002 29.93470099918353, -90.123189 29.93457799918353, -90.12360599999998 29.934876999183523, -90.123488 29.93501399918352, -90.12306300000002 29.93470099918353)))                                                                                                                                                                                                                            | 22        | 071        | 012102    | 2011      | 220710121022011 | Block 2011 | G5040   |      |        | S          | 985     | 0        | +29.9347938 | -090.1233375 | 12861 | 220710121022011 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 0.0      | 0.0    | 0.0       | 
| 9          | orl_census2010_block_pl.9  | MULTIPOLYGON (((-90.122457 29.934248999183534, -90.12225699999999 29.934106999183534, -90.121754 29.933751999183542, -90.12183800000001 29.933652999183547, -90.12255899999998 29.93414099918354, -90.122457 29.934248999183534)))                                                                                                                                                                                          | 22        | 071        | 012102    | 2007      | 220710121022007 | Block 2007 | G5040   |      |        | S          | 1278    | 0        | +29.9339538 | -090.1221595 | 12857 | 220710121022007 | 0.0       | 0.0   | 0.0   | 0.0      | 0.0   | 0.0        | 0.0        | 0.0        | 0.0      | 0.0      | 0.0      | 0.0    | 0.0       | 
| 10         | orl_census2010_block_pl.10 | MULTIPOLYGON (((-90.11866100000002 29.934322999183536, -90.11967399999999 29.934803999183526, -90.119249 29.935533999183512, -90.118213 29.935189999183525, -90.11866100000002 29.934322999183536)))                                                                                                                                                                                                                        | 22        | 071        | 011700    | 4015      | 220710117004015 | Block 4015 | G5040   |      |        | S          | 10682   | 0        | +29.9349548 | -090.1189379 | 9636  | 220710117004015 | 30.0      | 29.0  | 0.0   | 0.0      | 0.0   | 0.0        | 1.0        | 0.0        | 1.0      | 29.0     | 12.0     | 12.0   | 0.0       | 
```