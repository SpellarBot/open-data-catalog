# RWIS Data - Traffic Speeds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rwis-data-traffic-speeds) |
| Metadata | [Link](https://data.iowa.gov/api/views/am2d-jc37) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/am2d-jc37/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/am2d-jc37/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | am2d-jc37 |
| Name | RWIS Data - Traffic Speeds |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | operations, asset, inventory, rwis, weather, roadway, traffic, speed, iowa dot, iowa department of transportation |
| Created | 2016-06-09T06:38:24Z |
| Publication Date | 2016-06-09T06:39:39Z |

## Description

Live Roadway Weather Information System (RWIS) data feed- current traffic speeds at RWIS stations.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | rwisid       | RWISID       | text      | number      |
| Yes      | series tag     | currentid    | CURRENTID    | text      | number      |
| Yes      | series tag     | siteid       | SITEID       | text      | number      |
| Yes      | series tag     | sitename     | SITENAME     | text      | text        |
| Yes      | time           | timestamp    | TIMESTAMP    | date      | date        |
| Yes      | numeric metric | avgspeed     | AVGSPEED     | number    | number      |
| Yes      | numeric metric | normalvolume | NORMALVOLUME | number    | number      |
| Yes      | numeric metric | longvolume   | LONGVOLUME   | number    | number      |
| Yes      | numeric metric | avgvolume    | AVGVOLUME    | number    | number      |
| Yes      | numeric metric | occupancy    | OCCUPANCY    | number    | number      |
| Yes      | series tag     | name         | NAME         | text      | text        |
```

## Time Field

```ls
Value = timestamp
Format & Zone = seconds
```

## Data Commands

```ls
series e:am2d-jc37 d:2015-11-12T14:00:23.000Z t:currentid=99411422 t:rwisid=2 t:sitename=Alton t:name="IA-18 EB" t:siteid=309 m:avgspeed=69.59344 m:normalvolume=9999 m:longvolume=9999 m:occupancy=9998 m:avgvolume=0

series e:am2d-jc37 d:2017-04-21T04:19:44.000Z t:currentid=99411425 t:rwisid=3 t:sitename="Altoona (I-80/US 65)" t:name="IA-10 EB" t:siteid=310 m:avgspeed=60.894259999999996 m:normalvolume=9999 m:longvolume=9999 m:occupancy=9998 m:avgvolume=0

series e:am2d-jc37 d:2017-04-21T04:20:23.000Z t:currentid=99411430 t:rwisid=7 t:sitename="Burlington (US 34)" t:name="I-80 EB Driving" t:siteid=314 m:avgspeed=86.9918 m:normalvolume=9999 m:longvolume=9999 m:occupancy=9998 m:avgvolume=0
```

## Meta Commands

```ls
metric m:avgspeed p:decimal l:AVGSPEED d:"Average Speed" t:dataTypeName=number

metric m:normalvolume p:integer l:NORMALVOLUME d:"Passenger Vehicle Volume" t:dataTypeName=number

metric m:longvolume p:integer l:LONGVOLUME d:"Long Vehicle Volume" t:dataTypeName=number

metric m:avgvolume p:integer l:AVGVOLUME d:"Average Volume" t:dataTypeName=number

metric m:occupancy p:integer l:OCCUPANCY d:Occupancy t:dataTypeName=number

entity e:am2d-jc37 l:"RWIS Data - Traffic Speeds" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/am2d-jc37

property e:am2d-jc37 t:meta.view v:id=am2d-jc37 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/RWIS_Live/MapServer/1 v:averageRating=0 v:name="RWIS Data - Traffic Speeds" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:am2d-jc37 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:am2d-jc37 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| rwisid | currentid | siteid | sitename             | timestamp  | avgspeed                                           | normalvolume | longvolume | avgvolume | occupancy | name            | 
| ====== | ========= | ====== | ==================== | ========== | ================================================== | ============ | ========== | ========= | ========= | =============== | 
| 2      | 99411422  | 309    | Alton                | 1447336823 | 69.5934400000000010777512216009199619293212890625  | 9999         | 9999       | 0         | 9998      | IA-18 EB        | 
| 3      | 99411425  | 310    | Altoona (I-80/US 65) | 1492748384 | 60.89425999999999561396180070005357265472412109375 | 9999         | 9999       | 0         | 9998      | IA-10 EB        | 
| 7      | 99411430  | 314    | Burlington (US 34)   | 1492748423 | 86.9917999999999977944753482006490230560302734375  | 9999         | 9999       | 0         | 9998      | I-80 EB Driving | 
```