# Green Connections Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-connections-network-3fdfa) |
| Metadata | [Link](https://data.sfgov.org/api/views/q8g4-wqta) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/q8g4-wqta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/q8g4-wqta/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | q8g4-wqta |
| Name | Green Connections Network |
| Category | Energy and Environment |
| Tags | planning |
| Created | 2016-07-28T21:18:39Z |
| Publication Date | 2016-08-19T21:36:05Z |

## Description

Green Connections aims to increase access to parks, open spaces, and the waterfront by envisioning a network of green connectors -- city streets that will be upgraded incrementally over the next 20 years to make it safer and more pleasant to travel to parks by walking, biking, and other forms of active transportation. The dataset is a zipped GIS shapefile of the Green Connections Network which is shown in this map: http://www.sf-planning.org/ftp/files/Citywide/green_connections/GC_Final_Network_Map_03-2014.pdf.  Further information can be found on the Green Connections website: http://greenconnections.sfplanning.org

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | cnn         | cnn        | number    | number      |
| Yes      | series tag     | gc_rt_name  | gc_rt_name | text      | text        |
| Yes      | series tag     | gc_rt_nmbr  | gc_rt_nmbr | text      | text        |
| Yes      | numeric metric | lf_fadd     | lf_fadd    | number    | number      |
| Yes      | numeric metric | lf_toadd    | lf_toadd   | number    | number      |
| Yes      | series tag     | objectid    | objectid   | text      | number      |
| Yes      | numeric metric | rt_fadd     | rt_fadd    | number    | number      |
| Yes      | numeric metric | rt_toadd    | rt_toadd   | number    | number      |
| Yes      | series tag     | street      | street     | text      | text        |
| Yes      | series tag     | st_type     | st_type    | text      | text        |
| Yes      | series tag     | geometry    | geometry   | line      | line        |
| Yes      | series tag     | multigeom   | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:q8g4-wqta d:2016-08-19T04:00:50.000Z t:gc_rt_nmbr=14 t:gc_rt_name="Presidio to Park Merced" t:street=22ND t:multigeom=false t:st_type=AVE t:objectid=181899 t:geometry="LINESTRING (-122.48111286328042 37.77458337860856, -122.48097876563916 37.77271628309879)" m:lf_fadd=700 m:rt_toadd=799 m:lf_toadd=798 m:rt_fadd=701 m:cnn=1138000

series e:q8g4-wqta d:2016-08-19T04:00:50.000Z t:gc_rt_nmbr=2 t:gc_rt_name="China Beach to Bay" t:street=WASHINGTON t:multigeom=false t:st_type=ST t:objectid=168499 t:geometry="LINESTRING (-122.41053787168633 37.79463122541162, -122.41136404327203 37.794526652839004)" m:lf_fadd=1051 m:rt_toadd=1098 m:lf_toadd=1099 m:rt_fadd=1058 m:cnn=13423000

series e:q8g4-wqta d:2016-08-19T04:00:50.000Z t:gc_rt_nmbr=8/24 t:gc_rt_name="Noe Valley to Central Waterfront/Shoreline" t:street=ILLINOIS t:multigeom=false t:st_type=ST t:objectid=175410 t:geometry="LINESTRING (-122.38706585219497 37.75544622090616, -122.38693869664368 37.75416779649186)" m:lf_fadd=1301 m:rt_toadd=1398 m:lf_toadd=1399 m:rt_fadd=1300 m:cnn=7172000
```

## Meta Commands

```ls
metric m:cnn p:long l:cnn t:dataTypeName=number

metric m:lf_fadd p:long l:lf_fadd t:dataTypeName=number

metric m:lf_toadd p:long l:lf_toadd t:dataTypeName=number

metric m:rt_fadd p:long l:rt_fadd t:dataTypeName=number

metric m:rt_toadd p:long l:rt_toadd t:dataTypeName=number

entity e:q8g4-wqta l:"Green Connections Network" t:url=https://data.sfgov.org/api/views/q8g4-wqta

property e:q8g4-wqta t:meta.view v:id=q8g4-wqta v:category="Energy and Environment" v:averageRating=0 v:name="Green Connections Network"

property e:q8g4-wqta t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:q8g4-wqta t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:q8g4-wqta t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | cnn        | gc_rt_name                                 | gc_rt_nmbr | lf_fadd | lf_toadd | objectid | rt_fadd | rt_toadd | street     | st_type | geometry                                                                                                                                                                                                                                                                                   | multigeom | 
| =========== | ========== | ========================================== | ========== | ======= | ======== | ======== | ======= | ======== | ========== | ======= | ========================================================================================================================================================================================================================================================================================== | ========= | 
| 1471579250  | 1138000.0  | Presidio to Park Merced                    | 14         | 700.0   | 798.0    | 181899   | 701.0   | 799.0    | 22ND       | AVE     | LINESTRING (-122.48111286328042 37.77458337860856, -122.48097876563916 37.77271628309879)                                                                                                                                                                                                  | false     | 
| 1471579250  | 13423000.0 | China Beach to Bay                         | 2          | 1051.0  | 1099.0   | 168499   | 1058.0  | 1098.0   | WASHINGTON | ST      | LINESTRING (-122.41053787168633 37.79463122541162, -122.41136404327203 37.794526652839004)                                                                                                                                                                                                 | false     | 
| 1471579250  | 7172000.0  | Noe Valley to Central Waterfront/Shoreline | 8/24       | 1301.0  | 1399.0   | 175410   | 1300.0  | 1398.0   | ILLINOIS   | ST      | LINESTRING (-122.38706585219497 37.75544622090616, -122.38693869664368 37.75416779649186)                                                                                                                                                                                                  | false     | 
| 1471579250  | 10382000.0 | Crosstown Trail                            | 23         | 701.0   | 799.0    | 171793   | 700.0   | 798.0    | PERU       | AVE     | LINESTRING (-122.4241347788771 37.72594540801444, -122.42354330063168 37.72566302133307, -122.42332549523945 37.725138138378526)                                                                                                                                                           | false     | 
| 1471579250  | 5705000.0  | Folsom Street                              | 20         | 3299.0  | 3399.0   | 177036   | 3300.0  | 3398.0   | FOLSOM     | ST      | LINESTRING (-122.41337632273402 37.745149133538405, -122.413280063816 37.744150044881245)                                                                                                                                                                                                  | false     | 
| 1471579250  | 1188000.0  | Noe Valley to Central Waterfront           | 8          | 3051.0  | 3099.0   | 181857   | 3050.0  | 3098.0   | 22ND       | ST      | LINESTRING (-122.41547327494038 37.75563410833778, -122.41656664078371 37.75556827813656)                                                                                                                                                                                                  | false     | 
| 1471579250  | 3026201.0  | Crosstown Trail                            | 23         | 0.0     | 0.0      | 179905   | 500.0   | 598.0    | BOSWORTH   | ST      | LINESTRING (-122.43297411597455 37.73331082636995, -122.43320106219707 37.73343882604965, -122.4340207120184 37.73358796266472, -122.43414453633044 37.733550343266714)                                                                                                                    | false     | 
| 1471579250  | 3258000.0  | Lake Merced to Candlestick                 | 12         | 601.0   | 649.0    | 179625   | 600.0   | 648.0    | BRUNSWICK  | ST      | LINESTRING (-122.44550334417616 37.70981331484346, -122.44670507359385 37.70940240109001)                                                                                                                                                                                                  | false     | 
| 1471579250  | 3516000.0  | Market to Beach                            | 3          | 4801.0  | 4899.0   | 179361   | 4800.0  | 4898.0   | CABRILLO   | ST      | LINESTRING (-122.51003695605 37.7732594694463, -122.51014643498205 37.77314440739929, -122.51041858382143 37.77313191655599, -122.51054322242608 37.773230418334855, -122.51066621449738 37.773222453514855, -122.51093996180835 37.772957707958625, -122.5112821019844 37.77295994414043) | false     | 
| 1471579250  | 5654000.0  | Folsom Street                              | 20         | 353.0   | 399.0    | 177162   | 350.0   | 398.0    | FOLSOM     | ST      | LINESTRING (-122.39330569042441 37.78822645225682, -122.39359716393014 37.78799630950512)                                                                                                                                                                                                  | false     | 
```