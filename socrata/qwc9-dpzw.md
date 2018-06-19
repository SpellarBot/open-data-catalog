# SDOT Bike Racks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-racks) |
| Metadata | [Link](https://data.seattle.gov/api/views/qwc9-dpzw) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qwc9-dpzw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qwc9-dpzw/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qwc9-dpzw |
| Name | SDOT Bike Racks |
| Category | Transportation |
| Tags | bikes, bicycles, racks, streets, seattle, parking, sdot asset status and condition report, assets |
| Created | 2015-03-19T15:23:17Z |
| Publication Date | 2015-03-19T15:27:55Z |

## Description

Displays the location and attributes of bike racks in the City of Seattle including the type of rack facility, type of mount, style of rack and color of the bike rack.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | compkey                   | COMPKEY                   | number    | number      |
| Yes      | series tag     | comptype                  | COMPTYPE                  | text      | number      |
| Yes      | numeric metric | segkey                    | SEGKEY                    | number    | number      |
| Yes      | numeric metric | distance                  | DISTANCE                  | number    | number      |
| Yes      | numeric metric | width                     | WIDTH                     | number    | number      |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | unittype                  | UNITTYPE                  | text      | text        |
| Yes      | series tag     | unitdesc                  | UNITDESC                  | text      | text        |
| Yes      | series tag     | bike_facility             | BIKE_FACILITY             | text      | text        |
| Yes      | numeric metric | rack_capacity             | RACK_CAPACITY             | number    | number      |
| Yes      | series tag     | delineator_posts          | DELINEATOR_POSTS          | text      | text        |
| Yes      | series tag     | finish_type               | FINISH_TYPE               | text      | text        |
| Yes      | series tag     | surface_type              | SURFACE_TYPE              | text      | text        |
| No       |                | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | mount_type                | MOUNT_TYPE                | text      | text        |
| Yes      | series tag     | color                     | COLOR                     | text      | text        |
| Yes      | series tag     | manufacturer              | MANUFACTURER              | text      | text        |
| Yes      | series tag     | model_type                | MODEL_TYPE                | text      | text        |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| Yes      | time           | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | side                      | SIDE                      | text      | text        |
| Yes      | series tag     | ownership                 | OWNERSHIP                 | text      | text        |
| Yes      | series tag     | current_status            | CURRENT_STATUS            | text      | text        |
| Yes      | series tag     | primarydistrictcd         | PRIMARYDISTRICTCD         | text      | text        |
| Yes      | series tag     | secondarydistrictcd       | SECONDARYDISTRICTCD       | text      | text        |
| Yes      | series tag     | overrideyn                | OVERRIDEYN                | text      | text        |
| Yes      | series tag     | overridecomment           | OVERRIDECOMMENT           | text      | text        |
```

## Time Field

```ls
Value = condition_assessment_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date
```

## Data Commands

```ls
series e:qwc9-dpzw d:2009-08-19T00:00:00.000Z t:delineator_posts=N t:condition=GOOD t:comptype=16 t:current_status=INSVC t:unitdesc="EASTLAKE AVE E 0320 BLOCK NW SIDE ( 101) 101 FT NE/O HARVARD AVE E" t:ownership=SDOT t:unitid=BKR-265 t:color=NONE t:side=NW t:finish_type=GALV t:manufacturer=BKR-CRMTL t:overrideyn=N t:primarydistrictcd=DISTRICT3 t:model_type=BKR-RLRCK t:objectid=1 t:surface_type=PCC t:unittype=BKR t:mount_type=SUFMT t:bike_facility=SGL m:distance=101 m:segkey=10184 m:rack_capacity=2 m:width=34 m:compkey=517101

series e:qwc9-dpzw d:2009-08-17T00:00:00.000Z t:delineator_posts=N t:condition=GOOD t:comptype=16 t:current_status=INSVC t:unitdesc="35TH AVE SW 0730 BLOCK E SIDE ( 501) 119 FT N/O SW WEBSTER ST" t:ownership=SDOT t:unitid=BKR-2646 t:color=NONE t:side=E t:finish_type=GALV t:manufacturer=BKR-CRMTL t:overrideyn=N t:primarydistrictcd=DISTRICT1 t:model_type=BKR-RLRCK t:objectid=2 t:surface_type=PCC t:unittype=BKR t:mount_type=SUFMT t:bike_facility=SGL m:distance=524 m:segkey=5466 m:rack_capacity=2 m:width=31 m:compkey=518581

series e:qwc9-dpzw d:2017-04-21T08:13:46.873Z t:delineator_posts=N t:comptype=16 t:unitdesc="4TH AVE NE 0400 BLOCK E SIDE ( 335) 335 FT N/O NE 40 UPPER ST" t:unitid=BKR-3357 t:ownership=SDOT t:side=E t:finish_type=GALV t:primarydistrictcd=DISTRICT4 t:overrideyn=N t:objectid=3 t:surface_type=PCC t:unittype=BKR t:bike_facility=SGL m:distance=348 m:segkey=6173 m:rack_capacity=10 m:width=-17 m:compkey=614105
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:decimal l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:integer l:WIDTH d:WIDTH t:dataTypeName=number

metric m:rack_capacity p:integer l:RACK_CAPACITY d:RACK_CAPACITY t:dataTypeName=number

entity e:qwc9-dpzw l:"SDOT Bike Racks" t:url=https://data.seattle.gov/api/views/qwc9-dpzw

property e:qwc9-dpzw t:meta.view v:id=qwc9-dpzw v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Bike Racks"

property e:qwc9-dpzw t:meta.view.license v:name="Public Domain"

property e:qwc9-dpzw t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:qwc9-dpzw t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | distance | width | unitid   | unittype | unitdesc                                                           | bike_facility | rack_capacity | delineator_posts | finish_type | surface_type | install_date | mount_type | color | manufacturer | model_type | condition | condition_assessment_date | side | ownership | current_status | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | 
| ======== | ======= | ======== | ====== | ======== | ===== | ======== | ======== | ================================================================== | ============= | ============= | ================ | =========== | ============ | ============ | ========== | ===== | ============ | ========== | ========= | ========================= | ==== | ========= | ============== | ================= | =================== | ========== | =============== | 
| 1        | 517101  | 16       | 10184  | 101      | 34    | BKR-265  | BKR      | EASTLAKE AVE E 0320 BLOCK NW SIDE ( 101) 101 FT NE/O HARVARD AVE E | SGL           | 2             | N                | GALV        | PCC          | 1132704000   | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1250640000                | NW   | SDOT      | INSVC          | DISTRICT3         |                     | N          |                 | 
| 2        | 518581  | 16       | 5466   | 524      | 31    | BKR-2646 | BKR      | 35TH AVE SW 0730 BLOCK E SIDE ( 501) 119 FT N/O SW WEBSTER ST      | SGL           | 2             | N                | GALV        | PCC          |              | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1250467200                | E    | SDOT      | INSVC          | DISTRICT1         |                     | N          |                 | 
| 3        | 614105  | 16       | 6173   | 348      | -17   | BKR-3357 | BKR      | 4TH AVE NE 0400 BLOCK E SIDE ( 335) 335 FT N/O NE 40 UPPER ST      | SGL           | 10            | N                | GALV        | PCC          | 1396742400   |            |       |              |            |           |                           | E    | SDOT      |                | DISTRICT4         |                     | N          |                 | 
| 4        | 606481  | 16       | 4972   | 484      | 17    | BKR-3320 | BKR      | 32ND AVE NE 1400 BLOCK W SIDE ( 471) 170 FT S/O NE 143RD ST        | SGL           | 2             | N                | GALV        | PCC          | 1383264000   |            |       |              |            |           |                           | W    | SDOT      |                | DISTRICT5         |                     | N          |                 | 
| 5        | 516697  | 16       | 2929   | 45       | 17    | BKR-1415 | BKR      | 20TH AVE 0010 BLOCK W SIDE ( 32) 32 FT N/O E YESLER WAY            | SGL           | 2             | N                | GALV        | PCC          |              | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1248307200                | W    | SDOT      | INSVC          | DISTRICT3         |                     | N          |                 | 
| 6        | 516721  | 16       | 3232   | 130      | -17   | BKR-342  | BKR      | 22ND AVE 0140 BLOCK E SIDE ( 117) 117 FT N/O E UNION ST            | SGL           | 2             | N                | GALV        | PCC          | 1076976000   | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1248220800                | E    | SDOT      | INSVC          | DISTRICT3         |                     | N          |                 | 
| 7        | 517099  | 16       | 10184  | 139      | -34   | BKR-2514 | BKR      | EASTLAKE AVE E 0320 BLOCK SE SIDE ( 139) 139 FT NE/O HARVARD AVE E | SGL           | 2             | N                | GALV        | PCC          |              | SUFMT      | NONE  | BKR-ARCRE    | BKR-RLRCK  | GOOD      | 1250640000                | SE   | SDOT      | INSVC          | DISTRICT3         |                     | N          |                 | 
| 8        | 517291  | 16       | 12131  | 36       | -26   | BKR-828  | BKR      | PHINNEY AVE N 0350 BLOCK E SIDE ( 12) 12 FT N/O N 35TH ST          | SGL           | 2             | N                | PAINT       | PCC-PAD      | 1249257600   | SUFMT      | GRN   | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1248825600                | E    | SDOT      | INSVC          | DISTRICT6         |                     | N          |                 | 
| 9        | 518518  | 16       | 4987   | 215      | -24   | BKR-2474 | BKR      | 32ND AVE NW 0640 BLOCK E SIDE ( 185) 0 FT S/O NW 65TH ST           | SGL           | 2             | N                | GALV        | PCC          |              | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1249257600                | E    | SDOT      | INSVC          | DISTRICT6         |                     | N          |                 | 
| 10       | 517241  | 16       | 6143   | 207      | 34    | BKR-1216 | BKR      | 4TH AVE 0260 BLOCK SW SIDE ( 181) 79 FT SE/O CEDAR ST              | SGL           | 2             | N                | GALV        | PCC          |              | SUFMT      | NONE  | BKR-CRMTL    | BKR-RLRCK  | GOOD      | 1247788800                | SW   | SDOT      | INSVC          | DISTRICT7         |                     | N          |                 | 
```