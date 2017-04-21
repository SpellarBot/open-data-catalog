# Trees in the Public Right of Way Diameter >= 40"

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trees-in-the-public-right-of-way-diameter-40-3fcb3) |
| Metadata | [Link](https://data.seattle.gov/api/views/cqsd-e672) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/cqsd-e672/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/cqsd-e672/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | cqsd-e672 |
| Name | Trees in the Public Right of Way Diameter >= 40" |
| Attribution | Seattle GIS Program |
| Category | Transportation |
| Created | 2011-12-20T18:15:47Z |
| Publication Date | 2012-01-24T17:27:08Z |

## Description

Trees within public right of way with a diameter of 40" or greater.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | objectid      | OBJECTID      | text      | number      |
| Yes      | series tag     | comptype      | COMPTYPE      | text      | number      |
| Yes      | numeric metric | compkey       | COMPKEY       | number    | number      |
| Yes      | series tag     | unitid        | UNITID        | text      | text        |
| Yes      | series tag     | unitdesc      | UNITDESC      | text      | text        |
| Yes      | series tag     | botname       | BOTNAME       | text      | text        |
| Yes      | series tag     | ownershp      | OWNERSHP      | text      | text        |
| Yes      | series tag     | currentstatus | CURRENTSTATUS | text      | text        |
| Yes      | numeric metric | condrat       | CONDRAT       | number    | text        |
| Yes      | series tag     | spacetype     | SPACETYPE     | text      | text        |
| Yes      | numeric metric | growspace     | GROWSPACE     | number    | number      |
| Yes      | numeric metric | diam          | DIAM          | number    | number      |
| Yes      | series tag     | btgyn         | BTGYN         | text      | text        |
| Yes      | series tag     | exceptnal     | EXCEPTNAL     | text      | text        |
| Yes      | series tag     | heritage      | HERITAGE      | text      | text        |
| Yes      | series tag     | codereq       | CODEREQ       | text      | text        |
| Yes      | series tag     | wires         | WIRES         | text      | text        |
| Yes      | numeric metric | wateryr       | WATERYR       | number    | number      |
| Yes      | time           | instdate      | INSTDATE      | date      | date        |
| No       |                | lastverify    | LASTVERIFY    | date      | date        |
| No       |                | expdate       | EXPDATE       | date      | date        |
| Yes      | series tag     | descript      | DESCRIPT      | text      | text        |
| Yes      | series tag     | sciname       | SCINAME       | text      | text        |
| Yes      | numeric metric | diamclass     | DIAMCLASS     | number    | number      |
| Yes      | series tag     | ownerdiam     | OWNERDIAM     | text      | text        |
```

## Time Field

```ls
Value = instdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lastverify,expdate
```

## Data Commands

```ls
series e:cqsd-e672 d:1992-06-16T00:00:00.000Z t:wires=Y t:codereq=N t:descript="Black Locust" t:comptype=36 t:botname=LOCBLK t:heritage=N t:ownershp=PRIV t:currentstatus=INSVC t:spacetype=GRASS t:btgyn=N t:unitdesc="1204 NE 75TH ST" t:unitid=TRE-62535 t:ownerdiam=PRIV3 t:exceptnal=N t:objectid=144 t:sciname="Robinia pseudoacacia" m:growspace=9 m:diam=40 m:wateryr=0 m:compkey=230247

series e:cqsd-e672 d:1990-09-19T00:00:00.000Z t:wires=Y t:codereq=N t:descript="Bigleaf Maple" t:comptype=36 t:botname=MAPBLM t:heritage=N t:ownershp=PRIV t:currentstatus=INSVC t:spacetype=GRASS t:btgyn=N t:unitdesc="745 BROADWAY AVE E" t:unitid=TRE-43529 t:ownerdiam=PRIV3 t:exceptnal=N t:objectid=498 t:sciname="Acer macrophyllum" m:growspace=9 m:diam=42 m:wateryr=0 m:compkey=211241

series e:cqsd-e672 d:1991-08-13T00:00:00.000Z t:wires=Y t:codereq=N t:descript="Willow Oak" t:comptype=36 t:botname=OAKWIL t:heritage=N t:ownershp=SDOT t:currentstatus=INSVC t:spacetype=GRASS t:btgyn=N t:unitdesc="3871 RAINIER AV S" t:unitid=TRE-79225 t:ownerdiam=SDOT3 t:exceptnal=N t:objectid=640 t:sciname="Quercus phellos" m:growspace=4 m:diam=42 m:wateryr=0 m:compkey=246937
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:condrat p:integer l:CONDRAT d:CONDRAT t:dataTypeName=number

metric m:growspace p:integer l:GROWSPACE d:GROWSPACE t:dataTypeName=number

metric m:diam p:integer l:DIAM d:Diameter t:dataTypeName=number

metric m:wateryr p:integer l:WATERYR d:WATERYR t:dataTypeName=number

metric m:diamclass p:long l:DIAMCLASS d:DIAMCLASS t:dataTypeName=number

entity e:cqsd-e672 l:"Trees in the Public Right of Way  Diameter >= 40""" t:attribution="Seattle GIS Program" t:url=https://data.seattle.gov/api/views/cqsd-e672

property e:cqsd-e672 t:meta.view v:id=cqsd-e672 v:category=Transportation v:attributionLink=https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/37 v:averageRating=0 v:name="Trees in the Public Right of Way  Diameter >= 40""" v:attribution="Seattle GIS Program"

property e:cqsd-e672 t:meta.view.license v:name="Public Domain"

property e:cqsd-e672 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:cqsd-e672 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | comptype | compkey | unitid      | unitdesc             | botname | ownershp | currentstatus | condrat | spacetype | growspace | diam | btgyn | exceptnal | heritage | codereq | wires | wateryr | instdate  | lastverify | expdate | descript          | sciname                 | diamclass | ownerdiam | 
| ======== | ======== | ======= | =========== | ==================== | ======= | ======== | ============= | ======= | ========= | ========= | ==== | ===== | ========= | ======== | ======= | ===== | ======= | ========= | ========== | ======= | ================= | ======================= | ========= | ========= | 
| 144      | 36       | 230247  | TRE-62535   | 1204 NE 75TH ST      | LOCBLK  | PRIV     | INSVC         |         | GRASS     | 9         | 40   | N     | N         | N        | N       | Y     | 0       | 708652800 |            |         | Black Locust      | Robinia pseudoacacia    |           | PRIV3     | 
| 498      | 36       | 211241  | TRE-43529   | 745 BROADWAY AVE E   | MAPBLM  | PRIV     | INSVC         |         | GRASS     | 9         | 42   | N     | N         | N        | N       | Y     | 0       | 653702400 |            |         | Bigleaf Maple     | Acer macrophyllum       |           | PRIV3     | 
| 640      | 36       | 246937  | TRE-79225   | 3871 RAINIER AV S    | OAKWIL  | SDOT     | INSVC         |         | GRASS     | 4         | 42   | N     | N         | N        | N       | Y     | 0       | 682041600 | 1199059200 |         | Willow Oak        | Quercus phellos         |           | SDOT3     | 
| 1456     | 36       | 185528  | TRE-17816   | 13314 23RD AV NE     | POPLOM  | PRIV     | INSVC         |         | GRASS     | 99        | 44   | N     | N         | N        | N       | N     | 0       | 715305600 |            |         | Lombardy Poplar   | Populus nigra `Italica` |           | PRIV3     | 
| 1629     | 36       | 212521  | TRE-44809   | 763 BELMONT PL E     | MAPBLM  | PRIV     | INSVC         |         | GRASS     | 11        | 45   | N     | N         | N        | N       | N     | 0       | 654998400 |            |         | Bigleaf Maple     | Acer macrophyllum       |           | PRIV3     | 
| 1811     | 36       | 493281  | TRE-1043581 | 1800 NE RAVENNA BLVD | HORSEC  | PARK     | INSVC         |         |           | 30        | 42   | N     | N         | N        | N       | N     | 0       |           | 1230681600 |         | Horse Chestnut    | Aesculus hippocastanum  |           | PARK3     | 
| 2275     | 36       | 500664  | TRE-1037367 | 2600 34TH AV W       | LOCBLK  | SDOT     | INSVC         |         |           | 15        | 50   | N     | N         | N        | N       | N     | 0       |           | 1230681600 |         | Black Locust      | Robinia pseudoacacia    |           | SDOT3     | 
| 2741     | 36       | 175564  | TRE-7852    | 2304 N 55TH ST       | MAPBLM  | PRIV     | INSVC         |         | GRASS     | 9         | 54   | N     | N         | N        | N       | Y     | 0       | 709430400 |            |         | Bigleaf Maple     | Acer macrophyllum       |           | PRIV3     | 
| 3090     | 36       | 186449  | TRE-18737   | 11045 15TH AV NE     | MAPBLM  | PRIV     | INSVC         |         | OTHER     | 99        | 41   | N     | N         | N        | N       | N     | 0       | 716774400 |            |         | Bigleaf Maple     | Acer macrophyllum       |           | PRIV3     | 
| 3505     | 36       | 605839  | TRE-1054074 | 15 MCGRAW ST         | CEDWRD  | PRIV     | INSVC         | 3       |           | 8         | 42   | 0     |           | N        | N       | Y     |         | 662688000 | 1379548800 |         | Western Red Cedar | Thuja plicata           |           | PRIV3     | 
```