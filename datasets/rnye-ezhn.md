# SDOT Radar Speed Signs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-radar-speed-signs) |
| Metadata | [Link](https://data.seattle.gov/api/views/rnye-ezhn) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/rnye-ezhn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/rnye-ezhn/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | rnye-ezhn |
| Name | SDOT Radar Speed Signs |
| Category | Transportation |
| Tags | sdot asset status and condition report, assets |
| Created | 2016-04-20T15:13:09Z |
| Publication Date | 2016-04-22T15:37:56Z |

## Description

Displays the location of radar speed signs within the City of Seattle that are owned by SDOT.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | objectid                   | OBJECTID                   | text      | number      |
| Yes      | numeric metric | compkey                    | COMPKEY                    | number    | number      |
| Yes      | series tag     | comptype                   | COMPTYPE                   | text      | number      |
| Yes      | numeric metric | segkey                     | SEGKEY                     | number    | number      |
| Yes      | numeric metric | distance                   | DISTANCE                   | number    | number      |
| Yes      | numeric metric | width                      | WIDTH                      | number    | number      |
| Yes      | series tag     | unitid                     | UNITID                     | text      | text        |
| Yes      | series tag     | unittype                   | UNITTYPE                   | text      | text        |
| Yes      | series tag     | unitdesc                   | UNITDESC                   | text      | text        |
| Yes      | series tag     | blue_tooth_enabled         | BLUE_TOOTH_ENABLED         | text      | text        |
| Yes      | series tag     | data_collection_capability | DATA_COLLECTION_CAPABILITY | text      | text        |
| Yes      | series tag     | service_point              | SERVICE_POINT              | text      | text        |
| Yes      | series tag     | solar_operated             | SOLAR_OPERATED             | text      | text        |
| Yes      | series tag     | side                       | SIDE                       | text      | text        |
| Yes      | series tag     | current_status             | CURRENT_STATUS             | text      | text        |
| Yes      | series tag     | ownership                  | OWNERSHIP                  | text      | text        |
| Yes      | series tag     | condition                  | CONDITION                  | text      | text        |
| Yes      | series tag     | primarydistrictcd          | PRIMARYDISTRICTCD          | text      | text        |
| Yes      | series tag     | secondarydistrictcd        | SECONDARYDISTRICTCD        | text      | text        |
| Yes      | series tag     | overrideyn                 | OVERRIDEYN                 | text      | text        |
| Yes      | series tag     | overridecomment            | OVERRIDECOMMENT            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rnye-ezhn d:2016-04-20T15:13:09.000Z t:solar_operated=Y t:condition=GOOD t:comptype=16 t:current_status=INSVC t:unitdesc="35TH AVE SW 0990 BLOCK W SIDE ( 318) 0 FT N/O SW 100TH ST" t:unitid=RSS-17 t:ownership=SDOT t:side=W t:data_collection_capability=N t:primarydistrictcd=DISTRICT1 t:overrideyn=N t:objectid=1 t:unittype=RSS t:blue_tooth_enabled=N m:segkey=5488 m:distance=331 m:width=-13 m:compkey=535341

series e:rnye-ezhn d:2016-04-20T15:13:09.000Z t:solar_operated=Y t:condition=GOOD t:comptype=16 t:current_status=INSVC t:unitdesc="NE 83RD ST 0250 BLOCK N SIDE ( 673) 310 FT W/O 28TH AVE NE" t:unitid=RSS-38 t:ownership=SDOT t:side=N t:data_collection_capability=Y t:primarydistrictcd=DISTRICT5 t:secondarydistrictcd=DISTRICT4 t:overrideyn=N t:objectid=2 t:unittype=RSS t:blue_tooth_enabled=Y m:segkey=17694 m:distance=686 m:width=17 m:compkey=605876

series e:rnye-ezhn d:2016-04-20T15:13:09.000Z t:solar_operated=N t:condition=GOOD t:service_point="SCL pole 1331072" t:comptype=16 t:current_status=INSVC t:unitdesc="RAINIER AVE S 0352 BLOCK SW SIDE ( 360) 360 FT SE/O S COURT ST" t:unitid=RSS-3 t:ownership=SDOT t:side=SW t:data_collection_capability=N t:primarydistrictcd=DISTRICT2 t:overrideyn=N t:objectid=3 t:unittype=RSS t:blue_tooth_enabled=N m:segkey=12375 m:distance=383 m:width=-29 m:compkey=510549
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:double l:WIDTH d:WIDTH t:dataTypeName=number

entity e:rnye-ezhn l:"SDOT Radar Speed Signs" t:url=https://data.seattle.gov/api/views/rnye-ezhn

property e:rnye-ezhn t:meta.view v:id=rnye-ezhn v:category=Transportation v:averageRating=0 v:name="SDOT Radar Speed Signs"

property e:rnye-ezhn t:meta.view.license v:name="Public Domain"

property e:rnye-ezhn t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:rnye-ezhn t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | compkey | comptype | segkey | distance | width | unitid | unittype | unitdesc                                                              | blue_tooth_enabled | data_collection_capability | service_point    | solar_operated | side | current_status | ownership | condition | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | 
| =========== | ======== | ======= | ======== | ====== | ======== | ===== | ====== | ======== | ===================================================================== | ================== | ========================== | ================ | ============== | ==== | ============== | ========= | ========= | ================= | =================== | ========== | =============== | 
| 0           | 1        | 535341  | 16       | 5488   | 331      | -13   | RSS-17 | RSS      | 35TH AVE SW 0990 BLOCK W SIDE ( 318) 0 FT N/O SW 100TH ST             | N                  | N                          |                  | Y              | W    | INSVC          | SDOT      | GOOD      | DISTRICT1         |                     | N          |                 | 
| 0           | 2        | 605876  | 16       | 17694  | 686      | 17    | RSS-38 | RSS      | NE 83RD ST 0250 BLOCK N SIDE ( 673) 310 FT W/O 28TH AVE NE            | Y                  | Y                          |                  | Y              | N    | INSVC          | SDOT      | GOOD      | DISTRICT5         | DISTRICT4           | N          |                 | 
| 0           | 3        | 510549  | 16       | 12375  | 383      | -29   | RSS-3  | RSS      | RAINIER AVE S 0352 BLOCK SW SIDE ( 360) 360 FT SE/O S COURT ST        | N                  | N                          | SCL pole 1331072 | N              | SW   | INSVC          | SDOT      | GOOD      | DISTRICT2         |                     | N          |                 | 
| 0           | 4        | 510566  | 16       | 12418  | 63       | -32   | RSS-4  | RSS      | RAINIER AVE S 0840 BLOCK W SIDE ( 40) 40 FT S/O S THISTLE ST          | N                  | N                          |                  | N              | W    | INSVC          | SDOT      | GOOD      | DISTRICT2         |                     | N          |                 | 
| 0           | 5        | 573710  | 16       | 13151  | 116      | -24   | RSS-26 | RSS      | THORNDYKE AVE W 0190 BLOCK SE SIDE ( 103) 0 FT SW/O W PLYMOUTH ST     | Y                  | Y                          |                  | Y              | SE   |                |           |           | DISTRICT7         |                     | N          |                 | 
| 0           | 6        | 535585  | 16       | 2072   | 13       | 14    | RSS-20 | RSS      | 15TH AVE NE 0980 BLOCK W SIDE ( 0) 0 FT /O NE 100TH ST                | Y                  | Y                          |                  | Y              | W    | PLANNED        | SDOT      | GOOD      | DISTRICT5         |                     | N          |                 | 
| 0           | 7        | 573709  | 16       | 13161  | 626      | 22    | RSS-25 | RSS      | THORNDYKE AVE W 0280 BLOCK NW SIDE ( 613) 100 FT SW/O 20TH AVE W      | Y                  | Y                          |                  | Y              | NW   |                |           |           | DISTRICT7         |                     | N          |                 | 
| 0           | 8        | 581471  | 16       | 8909   | 23       | -41   | RSS-28 | RSS      | AURORA AVE N 0110 BLOCK E SIDE ( 0) 0 FT /O HIGHLAND DR               | Y                  | Y                          |                  | Y              | E    |                |           |           | DISTRICT7         |                     | N          |                 | 
| 0           | 9        | 510586  | 16       | 3544   | 163      | -27   | RSS-9  | RSS      | 24TH AVE E 0120 BLOCK E SIDE ( 140) 140 FT N/O E HIGHLAND DR          | N                  | N                          |                  | N              | E    | INSVC          | SDOT      | GOOD      | DISTRICT3         |                     | N          |                 | 
| 0           | 10       | 510595  | 16       | 10408  | 240      | 29    | RSS-11 | RSS      | FAUNTLEROY WAY SW 0730 BLOCK E SIDE ( 227) 20 FT N/O BAINBRIDGE PL SW | N                  | N                          |                  | N              | E    | INSVC          | SDOT      | GOOD      | DISTRICT1         |                     | N          |                 | 
```