# SDOT Traffic Lanes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-traffic-lanes) |
| Metadata | [Link](https://data.seattle.gov/api/views/3ytq-9ntv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3ytq-9ntv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3ytq-9ntv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3ytq-9ntv |
| Name | SDOT Traffic Lanes |
| Attribution | Seattle Department of Transporation |
| Category | Transportation |
| Tags | traffic lane, lane, traffic, street, bike lane, bus lane, hov lane, shoulder, ramps, turn lane, vision zero, sdot asset status and condition report, assets |
| Created | 2015-03-18T22:26:56Z |
| Publication Date | 2015-03-18T22:50:26Z |

## Description

Displays the types of traffic lanes for street segments in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type  | Render Type |
| ======== | ============== | ============= | ============= | ========== | =========== |
| Yes      | series tag     | objectid      | OBJECTID      | text       | number      |
| No       |                | shape         | Shape         | geospatial | geospatial  |
| Yes      | numeric metric | lanekey       | LANEKEY       | number     | number      |
| Yes      | numeric metric | segkey        | SEGKEY        | number     | number      |
| Yes      | numeric metric | elmntkey      | ELMNTKEY      | number     | number      |
| Yes      | series tag     | unitid        | UNITID        | text       | text        |
| Yes      | series tag     | unitid2       | UNITID2       | text       | text        |
| Yes      | series tag     | unitdesc      | UNITDESC      | text       | text        |
| Yes      | series tag     | side          | SIDE          | text       | text        |
| Yes      | numeric metric | distance      | DISTANCE      | number     | number      |
| Yes      | numeric metric | enddistance   | ENDDISTANCE   | number     | number      |
| Yes      | numeric metric | width         | WIDTH         | number     | number      |
| Yes      | numeric metric | lanewidth     | LANEWIDTH     | number     | number      |
| Yes      | numeric metric | lanelength    | LANELENGTH    | number     | number      |
| Yes      | series tag     | laneid        | LANEID        | text       | text        |
| Yes      | series tag     | traffdir      | TRAFFDIR      | text       | text        |
| Yes      | numeric metric | lanelocation  | LANELOCATION  | number     | text        |
| Yes      | series tag     | lanetype      | LANETYPE      | text       | text        |
| Yes      | series tag     | addby         | ADDBY         | text       | text        |
| No       |                | adddttm       | ADDDTTM       | date       | date        |
| Yes      | series tag     | modby         | MODBY         | text       | text        |
| No       |                | moddttm       | MODDTTM       | date       | date        |
| Yes      | time           | operstartdate | OPERSTARTDATE | date       | date        |
| No       |                | operenddate   | OPERENDDATE   | date       | date        |
| Yes      | numeric metric | shape_length  | Shape_Length  | number     | number      |
```

## Time Field

```ls
Value = operstartdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape,adddttm,moddttm,operenddate
```

## Data Commands

```ls
series e:3ytq-9ntv d:2013-06-25T00:00:00.000Z t:traffdir=E t:shape.longitude=-122.31654073499999 t:lanetype=PK t:unitdesc="NE RAVENNA EB BV BETWEEN ROOSEVELT WAY NE AND 11TH AVE NE" t:unitid=14010 t:addby=PAYTONA t:side=S t:unitid2=0100 t:shape.needs_recoding=false t:laneid=1.4 t:shape.latitude=47.671773193000035 t:objectid=1 m:shape_length=98.72746777245247 m:enddistance=320 m:lanewidth=8 m:distance=221 m:segkey=18067 m:lanelocation=4 m:lanelength=99 m:width=-17 m:lanekey=28903 m:elmntkey=86046

series e:3ytq-9ntv d:2013-06-25T00:00:00.000Z t:traffdir=N t:shape.longitude=-122.31186896899999 t:lanetype=T1 t:unitdesc="15TH AVE NE BETWEEN NE 56TH ST AND NE RAVENNA EB BV" t:unitid=00555 t:addby=PAYTONA t:side=E t:unitid2=0560 t:shape.needs_recoding=false t:laneid=2.1 t:shape.latitude=47.669446022000045 t:objectid=2 m:shape_length=464.0348217143313 m:enddistance=465 m:lanewidth=9 m:distance=0 m:segkey=2040 m:lanelocation=12.5 m:lanelength=465 m:width=-4.5 m:lanekey=29008 m:elmntkey=47238

series e:3ytq-9ntv d:2013-06-25T00:00:00.000Z t:traffdir=S t:shape.longitude=-122.31199081699998 t:lanetype=PK t:unitdesc="15TH AVE NE BETWEEN NE 62ND ST AND NE 63RD ST" t:unitid=00555 t:addby=PAYTONA t:side=W t:unitid2=0620 t:shape.needs_recoding=false t:laneid=4.1 t:shape.latitude=47.67397825200004 t:objectid=3 m:shape_length=287.05088625590076 m:enddistance=288 m:lanewidth=8 m:distance=0 m:segkey=2046 m:lanelocation=40 m:lanelength=288 m:width=18 m:lanekey=29059 m:elmntkey=47241
```

## Meta Commands

```ls
metric m:lanekey p:integer l:LANEKEY d:LANEKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:elmntkey p:integer l:ELMNTKEY d:ELMNTKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:enddistance p:integer l:ENDDISTANCE d:ENDDISTANCE t:dataTypeName=number

metric m:width p:double l:WIDTH d:WIDTH t:dataTypeName=number

metric m:lanewidth p:integer l:LANEWIDTH d:LANEWIDTH t:dataTypeName=number

metric m:lanelength p:integer l:LANELENGTH d:LANELENGTH t:dataTypeName=number

metric m:lanelocation p:float l:LANELOCATION d:LANELOCATION t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:3ytq-9ntv l:"SDOT Traffic Lanes" t:attribution="Seattle Department of Transporation" t:url=https://data.seattle.gov/api/views/3ytq-9ntv

property e:3ytq-9ntv t:meta.view v:id=3ytq-9ntv v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Traffic Lanes" v:attribution="Seattle Department of Transporation"

property e:3ytq-9ntv t:meta.view.license v:name="Public Domain"

property e:3ytq-9ntv t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:3ytq-9ntv t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | shape                                                                                                                                                         | lanekey | segkey | elmntkey | unitid | unitid2 | unitdesc                                                  | side | distance | enddistance | width | lanewidth | lanelength | laneid | traffdir | lanelocation | lanetype | addby    | adddttm | modby    | moddttm    | operstartdate | operenddate | shape_length                                      | 
| ======== | ============================================================================================================================================================= | ======= | ====== | ======== | ====== | ======= | ========================================================= | ==== | ======== | =========== | ===== | ========= | ========== | ====== | ======== | ============ | ======== | ======== | ======= | ======== | ========== | ============= | =========== | ================================================= | 
| 1        | [null, 47.671773193000035, -122.31654073499999, null, false, {paths=[[[-122.31654073499999, 47.671773193000035], [-122.31616206399997, 47.67168465100008]]]}] | 28903   | 18067  | 86046    | 14010  | 0100    | NE RAVENNA EB BV BETWEEN ROOSEVELT WAY NE AND 11TH AVE NE | S    | 221      | 320         | -17   | 8         | 99         | 1.4    | E        | 4            | PK       | PAYTONA  |         |          |            | 1372118400    |             | 98.7274677724524707400632905773818492889404296875 | 
| 2        | [null, 47.669446022000045, -122.31186896899999, null, false, {paths=[[[-122.31186896899999, 47.669446022000045], [-122.31187754399997, 47.67071815400004]]]}] | 29008   | 2040   | 47238    | 00555  | 0560    | 15TH AVE NE BETWEEN NE 56TH ST AND NE RAVENNA EB BV       | E    | 0        | 465         | -4.5  | 9         | 465        | 2.1    | N        | 12.5         | T1       | PAYTONA  |         |          |            | 1372118400    |             | 464.0348217143313149790628813207149505615234375   | 
| 3        | [null, 47.67397825200004, -122.31199081699998, null, false, {paths=[[[-122.31199081699998, 47.67397825200004], [-122.31199495599998, 47.67476519200005]]]}]   | 29059   | 2046   | 47241    | 00555  | 0620    | 15TH AVE NE BETWEEN NE 62ND ST AND NE 63RD ST             | W    | 0        | 288         | 18    | 8         | 288        | 4.1    | S        | 40           | PK       | PAYTONA  |         |          |            | 1372118400    |             | 287.0508862559007638992625288665294647216796875   | 
| 4        | [null, 47.67120532700005, -122.31193325999999, null, false, {paths=[[[-122.31193325999999, 47.67120532700005], [-122.31193690099997, 47.67172822800006]]]}]   | 29039   | 2043   | 69965    | 00555  | 0570    | 15TH AVE NE BETWEEN NE RAVENNA WB N BV AND NE 58TH ST     | W    | 0        | 192         | 8.5   | 13        | 192        | 3.1    | S        | 25.5         | T1       | PAYTONA  |         |          |            | 1372118400    |             | 190.73847938243312682971009053289890289306640625  | 
| 5        | [null, 47.52644395100003, -122.32631903199996, null, false, {paths=[[[-122.32631903199996, 47.52644395100003], [-122.32559131699998, 47.52644174900007]]]}]   | 29001   | 19646  | 87658    | 15590  | 0050    | S CLOVERDALE ST BETWEEN 5TH AVE S AND 7TH AVE S           | S    | 465      | 645         | -11.5 | 15        | 180        | 3.1    | E        | 7.5          | T2       | MENDOZA1 |         | MENDOZA1 | 1372161550 | 1372118400    |             | 179.794356052711236770846880972385406494140625    | 
| 6        | [null, 47.67476800000003, -122.31195032099998, null, false, {paths=[[[-122.31195032099998, 47.67476800000003], [-122.31195811699996, 47.67578060400007]]]}]   | 29067   | 2047   | 47245    | 00555  | 0630    | 15TH AVE NE BETWEEN NE 63RD ST AND NE 65TH ST             | W    | 0        | 370         | 7     | 14        | 370        | 3.1    | S        | 29           | T1       | PAYTONA  |         | PAYTONA  | 1372166223 | 1372118400    |             | 369.368172994907354222959838807582855224609375    | 
| 7        | [null, 47.67397849500003, -122.31188934199997, null, false, {paths=[[[-122.31188934199997, 47.67397849500003], [-122.31189347999998, 47.67476543600003]]]}]   | 29057   | 2046   | 47242    | 00555  | 0620    | 15TH AVE NE BETWEEN NE 62ND ST AND NE 63RD ST             | E    | 0        | 288         | -7    | 14        | 288        | 2.1    | N        | 15           | T1       | PAYTONA  |         |          |            | 1372118400    |             | 287.0508862559007638992625288665294647216796875   | 
| 8        | [null, 47.65376974000003, -122.32457375999996, null, false, {paths=[[[-122.32457375999996, 47.65376974000003], [-122.32351959399995, 47.65393209100006]]]}]   | 29033   | 18032  | 86018    | 13940  | 0040    | NE NORTHLAKE WAY BETWEEN 4TH AVE NE AND 5TH AVE NE        | S    | 0        | 267         | -16   | 8         | 267        | 1.1    | E        | 4            | PK       | WINTERE  |         |          |            | 1372118400    |             | 266.4738555019220029862481169402599334716796875   | 
| 9        | [null, 47.672105653000074, -122.31186262899996, null, false, {paths=[[[-122.31186262899996, 47.672105653000074], [-122.31187511799999, 47.67397581900008]]]}] | 29051   | 2045   | 2094     | 00555  | 0590    | 15TH AVE NE BETWEEN COWEN PL NE AND NE 62ND ST            | E    | 0        | 683         | -10.5 | 21        | 683        | 1.1    | N        | 10.5         | T1       | PAYTONA  |         |          |            | 1372118400    |             | 682.17977650534567146678455173969268798828125     | 
| 10       | [null, 47.67476835700006, -122.31184884499999, null, false, {paths=[[[-122.31184884499999, 47.67476835700006], [-122.31185663899998, 47.675780960000054]]]}]  | 29065   | 2047   | 47246    | 00555  | 0630    | 15TH AVE NE BETWEEN NE 63RD ST AND NE 65TH ST             | E    | 0        | 370         | -18   | 8         | 370        | 1.1    | N        | 4            | PK       | PAYTONA  |         |          |            | 1372118400    |             | 369.368172994907354222959838807582855224609375    | 
```