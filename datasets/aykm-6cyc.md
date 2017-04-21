# SDOT Marked Crosswalks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/marked-crosswalks) |
| Metadata | [Link](https://data.seattle.gov/api/views/aykm-6cyc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/aykm-6cyc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/aykm-6cyc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | aykm-6cyc |
| Name | SDOT Marked Crosswalks |
| Category | Transportation |
| Tags | marked, crosswalks, pedestrians, seattle, crossing, sdot asset status and condition report, assets |
| Created | 2015-03-19T15:30:58Z |
| Publication Date | 2015-03-19T15:40:31Z |

## Description

Shows the location and displays some attributes of marked crosswalks in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | distance                  | DISTANCE                  | number    | number      |
| Yes      | numeric metric | width                     | WIDTH                     | number    | number      |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | unitdesc                  | UNITDESC                  | text      | text        |
| Yes      | series tag     | approach                  | APPROACH                  | text      | text        |
| Yes      | series tag     | marking_type              | MARKING_TYPE              | text      | text        |
| Yes      | series tag     | school                    | SCHOOL                    | text      | text        |
| Yes      | series tag     | midblock_crosswalk        | MIDBLOCK_CROSSWALK        | text      | text        |
| Yes      | time           | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | color                     | COLOR                     | text      | text        |
| Yes      | series tag     | comments                  | COMMENTS                  | text      | text        |
| Yes      | series tag     | category                  | CATEGORY                  | text      | text        |
| No       |                | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | city_sector               | CITY_SECTOR               | text      | text        |
| Yes      | series tag     | nbrhood_district          | NBRHOOD_DISTRICT          | text      | text        |
| Yes      | series tag     | maint_district            | MAINT_DISTRICT            | text      | text        |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| Yes      | series tag     | primarydistrictcd         | PRIMARYDISTRICTCD         | text      | text        |
| Yes      | series tag     | secondarydistrictcd       | SECONDARYDISTRICTCD       | text      | text        |
| Yes      | series tag     | overrideyn                | OVERRIDEYN                | text      | text        |
| Yes      | series tag     | overridecomment           | OVERRIDECOMMENT           | text      | text        |
```

## Time Field

```ls
Value = install_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = condition_assessment_date
```

## Data Commands

```ls
series e:aykm-6cyc d:2017-04-21T09:15:10.009Z t:condition=GOOD t:marking_type=LADER t:unitdesc="WESTERN AVE 0250 BLOCK C SIDE (  32) 32 FT NW/O WALL ST" t:category=THRPL t:school=N t:unitid=XWK-4142 t:color=WHT t:nbrhood_district=DWNTN t:approach=NW t:primarydistrictcd=DISTRICT7 t:overrideyn=N t:maint_district=CENTRAL t:objectid=1 t:midblock_crosswalk=N t:comments="WI #15922 10/27/98 <br>WESTERN AVE & WALL ST, N" t:city_sector=W m:distance=32 m:width=0

series e:aykm-6cyc d:2017-04-21T09:15:10.009Z t:condition=POOR t:marking_type=LADER t:unitdesc="LAKEVIEW BLVD E 0100 BLOCK C SIDE (  20) 20 FT NE/O BELMONT AVE E" t:category=THRPL t:school=N t:unitid=XWK-3753 t:color=WHT t:nbrhood_district=E t:approach=NE t:primarydistrictcd=DISTRICT3 t:overrideyn=N t:maint_district=CENTRAL t:objectid=2 t:midblock_crosswalk=N t:comments="VISUAL ASSESSMENT AR <br>LAKEVIEW BLVD & BELMONT AVE E, NE" t:city_sector=E m:distance=20 m:width=0

series e:aykm-6cyc d:2013-08-01T00:00:00.000Z t:unitdesc="WEST GREEN LAKE WAY N 0565 BLOCK C SIDE ( 123) 35 FT SE/O GREEN LAKE TURN RD" t:school=N t:unitid=XWK-5336 t:nbrhood_district=LKUN-NW t:condition=GOOD t:marking_type=LADER t:overrideyn=N t:primarydistrictcd=DISTRICT6 t:approach=SE t:maint_district=NORTH t:objectid=3 t:midblock_crosswalk=N t:comments="This crosswalk is an existing crosswalk installed as a part of pedestrian and bicycle improvements in July 2008" t:city_sector=NW m:distance=123 m:width=0
```

## Meta Commands

```ls
metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:integer l:WIDTH d:WIDTH t:dataTypeName=number

entity e:aykm-6cyc l:"SDOT Marked Crosswalks" t:url=https://data.seattle.gov/api/views/aykm-6cyc

property e:aykm-6cyc t:meta.view v:id=aykm-6cyc v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Marked Crosswalks"

property e:aykm-6cyc t:meta.view.license v:name="Public Domain"

property e:aykm-6cyc t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:aykm-6cyc t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | distance                                        | width | unitid   | unitdesc                                                                     | approach | marking_type | school | midblock_crosswalk | install_date | color | comments                                                                                                        | category | condition_assessment_date | city_sector | nbrhood_district | maint_district | condition | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | 
| ======== | =============================================== | ===== | ======== | ============================================================================ | ======== | ============ | ====== | ================== | ============ | ===== | =============================================================================================================== | ======== | ========================= | =========== | ================ | ============== | ========= | ================= | =================== | ========== | =============== | 
| 1        | 32                                              | 0     | XWK-4142 | WESTERN AVE 0250 BLOCK C SIDE ( 32) 32 FT NW/O WALL ST                       | NW       | LADER        | N      | N                  |              | WHT   | WI #15922 10/27/98
WESTERN AVE & WALL ST, N                                                                     | THRPL    | 1404172800                | W           | DWNTN            | CENTRAL        | GOOD      | DISTRICT7         |                     | N          |                 | 
| 2        | 20                                              | 0     | XWK-3753 | LAKEVIEW BLVD E 0100 BLOCK C SIDE ( 20) 20 FT NE/O BELMONT AVE E             | NE       | LADER        | N      | N                  |              | WHT   | VISUAL ASSESSMENT AR
LAKEVIEW BLVD & BELMONT AVE E, NE                                                          | THRPL    | 1407715200                | E           | E                | CENTRAL        | POOR      | DISTRICT3         |                     | N          |                 | 
| 3        | 123                                             | 0     | XWK-5336 | WEST GREEN LAKE WAY N 0565 BLOCK C SIDE ( 123) 35 FT SE/O GREEN LAKE TURN RD | SE       | LADER        | N      | N                  | 1375315200   |       | This crosswalk is an existing crosswalk installed as a part of pedestrian and bicycle improvements in July 2008 |          | 1404259200                | NW          | LKUN-NW          | NORTH          | GOOD      | DISTRICT6         |                     | N          |                 | 
| 4        | 623                                             | 0     | XWK-2346 | 35TH AVE SW 0940 BLOCK C SIDE ( 623) 30 FT N/O SW ROXBURY ST                 | N        | LADER        | N      | N                  |              | WHT   | 35 AVE SW & SW ROXBURY ST, N                                                                                    | THRPL    | 1405555200                | SW          | SW               | SOUTH          | GOOD      | DISTRICT1         |                     | N          |                 | 
| 5        | 28                                              | 0     | XWK-3375 | EASTLAKE AVE E 0260 BLOCK C SIDE ( 28) 28 FT N/O E ROANOKE ST                | N        | LADER        | N      | N                  |              | WHT   | WI #14228
EASTLAKE AVE & E ROANOKE ST, N                                                                        | THRPL    | 1407715200                | W           | LKUN             | CENTRAL        | FAIR      | DISTRICT4         |                     | N          |                 | 
| 6        | 229                                             | 0     | XWK-1411 | 11TH AVE NW 0470 BLOCK C SIDE ( 229) 37 FT S/O NW LEARY WAY                  | S        | LADER        | N      | N                  |              | WHT   | WI #18482
not visible
LEARY WAY NW & NW 48 ST, S                                                                | THRPL    | 1403740800                | NW          | BLRD             | NORTH          | GOOD      | DISTRICT6         |                     | N          |                 | 
| 7        | 1058.738770539999904940486885607242584228515625 | 0     | XWK-5674 | BURKE GILMAN TRL 0590 BLOCK C SIDE (1058) 0 FT W/O ADAMS LN NE               | C        | LADER        | N      | N                  |              |       |                                                                                                                 |          |                           | NE          | NE               | NORTH          |           | DISTRICT4         |                     | N          |                 | 
| 8        | 292                                             | 0     | XWK-4176 | CEDAR ST 0006 BLOCK C SIDE ( 292) 30 FT SW/O WESTERN AVE                     | SW       | LADER        | N      | N                  |              | WHT   | WI #15922 10/27/98
WESTERN AVE & CEDAR ST, W                                                                    | THRPL    | 1404172800                | W           | DWNTN            | CENTRAL        | GOOD      | DISTRICT7         |                     | N          |                 | 
| 9        | 184                                             | 0     | XWK-5354 | WESTERN AVE W 0020 BLOCK C SIDE ( 184) 40 FT SE/O ELLIOTT ER AVE W           | S        | LADER        | N      | N                  |              | WHT   | Asset added to inventory 10-23-13                                                                               | THRPL    | 1407196800                | W           | MGNL-QA          | CENTRAL        | POOR      | DISTRICT7         |                     | N          |                 | 
| 10       | 289                                             | 0     | XWK-1214 | BELL ST 0030 BLOCK C SIDE ( 289) 33 FT SW/O 4TH AVE                          | SW       | PARSL        | N      | N                  |              | WHT   | 4 AVE & BELL ST, W                                                                                              | RASED    | 1450310400                | W           | DWNTN            | CENTRAL        | GOOD      | DISTRICT7         |                     | N          |                 | 
```