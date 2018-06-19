# Historical Coal Mines (point locations)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-coal-mines-point-locations) |
| Metadata | [Link](https://data.iowa.gov/api/views/ir7d-ze53) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ir7d-ze53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ir7d-ze53/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ir7d-ze53 |
| Name | Historical Coal Mines (point locations) |
| Attribution | Iowa Department of Natural Resources |
| Category | Environment |
| Tags | coal mines |
| Created | 2016-03-01T19:10:38Z |
| Publication Date | 2016-03-01T19:20:27Z |

## Description

Historic coal mines with known locations, but no available map extents.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | objectid     | OBJECTID     | text      | number      |
| Yes      | series tag     | siteid       | SITEID       | text      | number      |
| Yes      | series tag     | mine_name    | MINE_NAME    | text      | text        |
| Yes      | series tag     | co_name      | CO_NAME      | text      | text        |
| Yes      | series tag     | name_caps    | NAME_CAPS    | text      | text        |
| Yes      | numeric metric | opstart      | OPSTART      | number    | number      |
| Yes      | numeric metric | opend        | OPEND        | number    | number      |
| Yes      | numeric metric | norecs       | NORECS       | number    | number      |
| Yes      | series tag     | datatype     | DATATYPE     | text      | text        |
| Yes      | series tag     | mine_mthd    | MINE_MTHD    | text      | text        |
| Yes      | series tag     | enttype      | ENTTYPE      | text      | text        |
| Yes      | numeric metric | shaft_dpth   | SHAFT_DPTH   | number    | number      |
| Yes      | series tag     | coal_bed     | COAL_BED     | text      | text        |
| Yes      | numeric metric | ave_thk      | AVE_THK      | number    | number      |
| Yes      | numeric metric | coal_elv     | COAL_ELV     | number    | number      |
| Yes      | series tag     | data_class   | DATA_CLASS   | text      | text        |
| Yes      | series tag     | comments     | COMMENTS     | text      | text        |
| Yes      | numeric metric | surface_elv  | SURFACE_ELV  | number    | number      |
| Yes      | series tag     | trs_centroid | TRS_CENTROID | text      | text        |
| Yes      | numeric metric | utm_x        | UTM_X        | number    | number      |
| Yes      | numeric metric | utm_y        | UTM_Y        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ir7d-ze53 d:2016-03-01T19:10:38.000Z t:enttype=shaft t:mine_mthd=longwall t:trs_centroid="Sec. 19, T71N, R35W" t:name_caps="JOE ANKENY COAL COMPANY" t:siteid=2010 t:mine_name="Joe Ankeny Coal Company" t:datatype="Point location, w/in section" t:objectid=1 t:comments="(Mine Inspectors' files) This mine was connected underground to the nearby Farland mine; located one mile west of Nodaway.  A new shaft was sunk in 1941.  (NCRDS ADA-24:  SW NE 19 T071N R35W)  1.3 feet of Nodaway coal at  977 feet." t:coal_bed=nodaway t:data_class=smine t:co_name=ADAMS m:opstart=1938 m:utm_x=338258.61685669393 m:utm_y=4533390.821535013 m:shaft_dpth=95 m:opend=1942 m:norecs=1

series e:ir7d-ze53 d:2016-03-01T19:10:38.000Z t:enttype=shaft t:mine_mthd=unknown t:trs_centroid="Sec. 12, T72N, R35W" t:name_caps="JACOB ARMON MINE" t:siteid=2011 t:mine_name="Jacob Armon Mine" t:datatype="Point location, w/in section" t:objectid=2 t:comments="(Mine Inspectors' Reports 1891) Small mine, local sales, located at Carlson, Iowa. (NCRDS ADA-14  SE SE 12 T072N R35W)  1.3' Nodaway at 1045'." t:coal_bed=nodaway t:data_class=smine t:co_name=ADAMS m:utm_x=346939.79412911733 m:utm_y=4545394.536143461 m:opend=1891 m:norecs=1

series e:ir7d-ze53 d:2016-03-01T19:10:38.000Z t:enttype=shaft t:mine_mthd=longwall t:trs_centroid="Sec. 12, T72N, R35W" t:name_caps="BELL MINE" t:siteid=2014 t:mine_name="Bell Mine" t:datatype="Point location, w/in section" t:objectid=3 t:comments="(Mine Inspectors' files: ) Known dates 1881-85.  Two shafts at this mine 42 ft. apart.  Inconsistent name data:  may have also been known as  Bell No. 1.  (NCRDS ADA-14)" t:coal_bed=nodaway t:data_class=smine t:co_name=ADAMS m:ave_thk=5 m:utm_x=346601.769995362 m:utm_y=4546109.261207009 m:norecs=1
```

## Meta Commands

```ls
metric m:opstart p:integer l:OPSTART d:"Starting Date" t:dataTypeName=number

metric m:opend p:integer l:OPEND d:"Ending Date" t:dataTypeName=number

metric m:norecs p:integer l:NORECS d:"Number Records" t:dataTypeName=number

metric m:shaft_dpth p:integer l:SHAFT_DPTH d:"Shaft Depth" t:dataTypeName=number

metric m:ave_thk p:float l:AVE_THK d:"Coal Thickness" t:dataTypeName=number

metric m:coal_elv p:integer l:COAL_ELV d:"Coal Bed Elv_" t:dataTypeName=number

metric m:surface_elv p:integer l:SURFACE_ELV d:"Surface Elv" t:dataTypeName=number

metric m:utm_x p:decimal l:UTM_X d:UTM_X t:dataTypeName=number

metric m:utm_y p:decimal l:UTM_Y d:UTM_Y t:dataTypeName=number

entity e:ir7d-ze53 l:"Historical Coal Mines (point locations)" t:attribution="Iowa Department of Natural Resources" t:url=https://data.iowa.gov/api/views/ir7d-ze53

property e:ir7d-ze53 t:meta.view v:id=ir7d-ze53 v:category=Environment v:attributionLink=https://programs.iowadnr.gov/geospatial/rest/services/Geology/CoalMines/MapServer/1 v:averageRating=0 v:name="Historical Coal Mines (point locations)" v:attribution="Iowa Department of Natural Resources"

property e:ir7d-ze53 t:meta.view.owner v:id=wf9z-sj5u v:profileImageUrlMedium=/api/users/wf9z-sj5u/profile_images/THUMB v:profileImageUrlLarge=/api/users/wf9z-sj5u/profile_images/LARGE v:screenName="Iowa Department of Natural Resources" v:profileImageUrlSmall=/api/users/wf9z-sj5u/profile_images/TINY v:displayName="Iowa Department of Natural Resources"

property e:ir7d-ze53 t:meta.view.tableauthor v:id=wf9z-sj5u v:profileImageUrlMedium=/api/users/wf9z-sj5u/profile_images/THUMB v:profileImageUrlLarge=/api/users/wf9z-sj5u/profile_images/LARGE v:screenName="Iowa Department of Natural Resources" v:profileImageUrlSmall=/api/users/wf9z-sj5u/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Natural Resources"
```

## Top Records

```ls
| :updated_at | objectid | siteid | mine_name                         | co_name | name_caps                         | opstart | opend | norecs | datatype                     | mine_mthd | enttype | shaft_dpth | coal_bed | ave_thk | coal_elv | data_class | comments                                                                                                                                                                                                                           | surface_elv | trs_centroid        | utm_x                                     | utm_y                                  | 
| =========== | ======== | ====== | ================================= | ======= | ================================= | ======= | ===== | ====== | ============================ | ========= | ======= | ========== | ======== | ======= | ======== | ========== | ================================================================================================================================================================================================================================== | =========== | =================== | ========================================= | ====================================== | 
| 0           | 1        | 2010   | Joe Ankeny Coal Company           | ADAMS   | JOE ANKENY COAL COMPANY           | 1938    | 1942  | 1      | Point location, w/in section | longwall  | shaft   | 95         | nodaway  |         |          | smine      | (Mine Inspectors' files) This mine was connected underground to the nearby Farland mine; located one mile west of Nodaway. A new shaft was sunk in 1941. (NCRDS ADA-24: SW NE 19 T071N R35W) 1.3 feet of Nodaway coal at 977 feet. |             | Sec. 19, T71N, R35W | 338258.6168566939304582774639129638671875 | 4533390.821535012684762477874755859375 | 
| 0           | 2        | 2011   | Jacob Armon Mine                  | ADAMS   | JACOB ARMON MINE                  |         | 1891  | 1      | Point location, w/in section | unknown   | shaft   |            | nodaway  |         |          | smine      | (Mine Inspectors' Reports 1891) Small mine, local sales, located at Carlson, Iowa. (NCRDS ADA-14 SE SE 12 T072N R35W) 1.3' Nodaway at 1045'.                                                                                       |             | Sec. 12, T72N, R35W | 346939.7941291173337958753108978271484375 | 4545394.53614346124231815338134765625  | 
| 0           | 3        | 2014   | Bell Mine                         | ADAMS   | BELL MINE                         |         |       | 1      | Point location, w/in section | longwall  | shaft   |            | nodaway  | 5.0     |          | smine      | (Mine Inspectors' files: ) Known dates 1881-85. Two shafts at this mine 42 ft. apart. Inconsistent name data: may have also been known as Bell No. 1. (NCRDS ADA-14)                                                               |             | Sec. 12, T72N, R35W | 346601.7699953619739972054958343505859375 | 4546109.26120700873434543609619140625  | 
| 0           | 4        | 2017   | Bontrager Coal Company            | ADAMS   | BONTRAGER COAL COMPANY            |         |       | 1      | Point location, w/in section | longwall  | shaft   |            | nodaway  |         |          | smine      | (MMDF#3) Only date 1936. Mine located 4 miles east of Villisca on the county line. (NCRDS ADA-24)                                                                                                                                  |             | Sec. 19, T71N, R35W | 338232.0149391943705268204212188720703125 | 4534013.145898423157632350921630859375 | 
| 0           | 5        | 2018   | Joseph Briscoe Mine               | ADAMS   | JOSEPH BRISCOE MINE               |         |       | 1      | Point location, w/in section | longwall  | shaft   |            | nodaway  |         |          | smine      | (Mine Inspectors' Reports 1893) Only date 1893.                                                                                                                                                                                    |             | Sec. 3, T73N, R35W  | 343200.679906279663555324077606201171875  | 4557129.959503903053700923919677734375 | 
| 0           | 6        | 2019   | Richard Briscoe Coal Company      | ADAMS   | RICHARD BRISCOE COAL COMPANY      | 1886    | 1891  | 1      | Point location, w/in section | longwall  | shaft   | 86         | nodaway  | 1.5     |          | smine      | Local sales only, small mine.                                                                                                                                                                                                      |             | Sec. 3, T73N, R35W  | 344185.187394854030571877956390380859375  | 4556747.737897044979035854339599609375 | 
| 0           | 7        | 2022   | Bullock Coal Company              | ADAMS   | BULLOCK COAL COMPANY              | 1943    | 1947  | 2      | Point location, w/in section | longwall  | shaft   | 132        | nodaway  |         |          | smine      | (Mine Inspectors' files: ) Successors to Cozad Mine. This mine was located 1 mile north and 1 mile west of Nodaway, Iowa. An escape shaft was located 120 feet deep adn 75 feet north of main shaft.                               |             | Sec. 8, T71N, R35W  | 340016.9149796746787615120410919189453125 | 4536768.922039934433996677398681640625 | 
| 0           | 8        | 2023   | Bunker Hill Coal Company          | ADAMS   | BUNKER HILL COAL COMPANY          | 1940    | 1941  | 1      | Point location, w/in section | longwall  | shaft   | 50         | nodaway  | 1.5     |          | smine      | (Mine Inspectors' files: ) Mine located 2 miles west and 1 mile south of Carbon. (NCRDS ADA-17: 15 T072N R35W) 1.3' Nodaway at 1083'.                                                                                              |             | Sec. 15, T72N, R35W | 343187.7319005948374979197978973388671875 | 4544608.051149439997971057891845703125 | 
| 0           | 9        | 2024   | Carbon Coal Company               | ADAMS   | CARBON COAL COMPANY               | 1889    | 1893  | 1      | Point location, w/in section | longwall  | shaft   | 60         | nodaway  | 1.5     |          | smine      | (Mine Inspectors' Reports 1889) Small mine, local sales. (NCRDS ADA-14: NE NE 13 T072N R35W) 1.3' Nodaway coal at 1045'.                                                                                                           |             | Sec. 12, T72N, R35W | 346479.021119219833053648471832275390625  | 4546063.011181931011378765106201171875 | 
| 0           | 10       | 2025   | Carbon Cooperative Coal Co. No. 1 | ADAMS   | CARBON COOPERATIVE COAL CO. NO. 1 |         |       | 1      | Point location, w/in section | longwall  | shaft   | 50         | nodaway  | 1.5     |          | smine      | Coal sold for local trade. Known dates 1886-1889. (NCRDS ADA-14: NE NE 13 T072N R35W) 1.3' Nodaway at 1045'.                                                                                                                       |             | Sec. 12, T72N, R35W | 346199.7753437624196521937847137451171875 | 4545592.2383873350918292999267578125   | 
```