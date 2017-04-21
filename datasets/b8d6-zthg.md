# 2014 Housing Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-housing-inventory) |
| Metadata | [Link](https://data.sfgov.org/api/views/b8d6-zthg) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/b8d6-zthg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/b8d6-zthg/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | b8d6-zthg |
| Name | 2014 Housing Inventory |
| Attribution | SF Planning |
| Category | Housing and Buildings |
| Tags | new housing construction, housing units, net new units, demolition, merger, conversion, alteration, housing stock, housing inventory, illegal units removed |
| Created | 2016-07-29T17:49:50Z |
| Publication Date | 2016-07-29T17:53:21Z |

## Description

This report is the 45th in the series and describes San Francisco??s housing supply. Housing Inventory data accounts for new housing construction, demolitions, and alterations in a consistent format for analysis of housing production trends. Net housing unit gains are reported citywide, by zoning classification, and by planning district. Other areas covered include affordable housing production, condominium conversions, and changes to the residential hotel stock. In addition, lists of major housing projects completed and approved for construction in 2014 are provided. A list of affordable housing projects in the pipeline (projects in various stages of review or pre-construction planning) is included to provide a picture of likely housing construction activity in the near future.
External Link

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | appl_no    | APPL_NO  | text      | number      |
| Yes      | series tag     | app_id     | APP_ID   | text      | number      |
| Yes      | numeric metric | form       | FORM     | number    | number      |
| Yes      | series tag     | st_num     | ST_NUM   | text      | number      |
| Yes      | series tag     | st_name    | ST_NAME  | text      | text        |
| Yes      | series tag     | st_type    | ST_TYPE  | text      | text        |
| Yes      | series tag     | prj_name   | PRJ_NAME | text      | text        |
| Yes      | series tag     | stdadd     | STDADD   | text      | text        |
| Yes      | series tag     | block      | BLOCK    | text      | number      |
| Yes      | series tag     | lot        | LOT      | text      | number      |
| Yes      | numeric metric | units      | UNITS    | number    | number      |
| Yes      | numeric metric | netunits   | NETUNITS | number    | number      |
| Yes      | numeric metric | affhsg     | AFFHSG   | number    | number      |
| Yes      | series tag     | target     | TARGET   | text      | text        |
| Yes      | series tag     | type       | TYPE     | text      | text        |
| Yes      | series tag     | descript   | DESCRIPT | text      | text        |
| Yes      | series tag     | existuse   | EXISTUSE | text      | text        |
| Yes      | series tag     | propuse    | PROPUSE  | text      | text        |
| Yes      | series tag     | action     | ACTION   | text      | text        |
| No       |                | actdate    | ACTDATE  | text      | text        |
| Yes      | series tag     | staff      | STAFF    | text      | text        |
| Yes      | numeric metric | blklot     | BLKLOT   | number    | number      |
| Yes      | series tag     | gen_zone   | GEN_ZONE | text      | text        |
| Yes      | series tag     | zoning     | ZONING   | text      | text        |
| No       |                | pd         | PD       | number    | number      |
| Yes      | series tag     | planarea   | PLANAREA | text      | text        |
| Yes      | series tag     | ana_nbhd   | ANA_NBHD | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = actdate,pd
```

## Data Commands

```ls
series e:b8d6-zthg d:2014-01-01T00:00:00.000Z t:appl_no=201105236553 t:st_num=1000 t:stdadd="1000 MASON ST" t:descript="Install auto fire sprinkler to protect addiitional units at lower and basement. REFERENCE TO APP#201008319983 TO ADD 3 RESIDENTIAL UNITS W/IN RESIDENCE." t:block=223 t:st_name=MASON t:propuse=APARTMENTS t:existuse=APARTMENTS t:action=COMPLETE t:lot=8 t:gen_zone="Residential, House and Mixed" t:st_type=ST t:app_id=748144 t:ana_nbhd="Nob Hill" t:zoning=RM-4 m:blklot=223008 m:form=8 m:affhsg=0 m:netunits=3 m:units=51

series e:b8d6-zthg d:2014-01-01T00:00:00.000Z t:appl_no=201406188814 t:st_num=1000 t:stdadd="1000 POWELL ST" t:descript="CORRECT RECORD TO INCORPORATE SUPERINTENDANTS UNIT ON 1ST FLOOR" t:block=211 t:st_name=POWELL t:propuse=APARTMENTS t:existuse=APARTMENTS t:action=COMPLETE t:lot=15 t:gen_zone=Commercial t:st_type=ST t:app_id=847144 t:ana_nbhd=Chinatown t:zoning=RC-4 m:blklot=211015 m:form=8 m:affhsg=0 m:netunits=1 m:units=48

series e:b8d6-zthg d:2014-01-01T00:00:00.000Z t:appl_no=201208288439 t:st_num=101 t:stdadd="101 DUBOCE AV" t:descript="4TH FLOOR VERTICAL ADDITION OF 2 DWELLING UNITS." t:st_name=DUBOCE t:block=3533 t:propuse=APARTMENTS t:type=Homeowner t:planarea="Market and Octavia" t:existuse=APARTMENTS t:staff=RSUCRE t:target=SEC t:action=COMPLETE t:lot=1 t:gen_zone="Neighborhood Commercial Transit" t:st_type=AV t:app_id=786469 t:ana_nbhd=Mission t:zoning=NCT-3 m:blklot=3533001 m:form=3 m:affhsg=2 m:netunits=2 m:units=7
```

## Meta Commands

```ls
metric m:form p:integer l:FORM t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:netunits p:integer l:NETUNITS t:dataTypeName=number

metric m:affhsg p:double l:AFFHSG t:dataTypeName=number

metric m:blklot p:integer l:BLKLOT t:dataTypeName=number

entity e:b8d6-zthg l:"2014 Housing Inventory" t:attribution="SF Planning" t:url=https://data.sfgov.org/api/views/b8d6-zthg

property e:b8d6-zthg t:meta.view v:id=b8d6-zthg v:category="Housing and Buildings" v:attributionLink="http://sf-planning.org/index.aspx?page=1663" v:averageRating=0 v:name="2014 Housing Inventory" v:attribution="SF Planning"

property e:b8d6-zthg t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:b8d6-zthg t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:b8d6-zthg t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| appl_no      | app_id | form | st_num | st_name      | st_type | prj_name | stdadd              | block | lot | units | netunits | affhsg | target | type      | descript                                                                                                                                                 | existuse          | propuse           | action     | actdate   | staff    | blklot  | gen_zone                        | zoning | pd | planarea                         | ana_nbhd                   | 
| ============ | ====== | ==== | ====== | ============ | ======= | ======== | =================== | ===== | === | ===== | ======== | ====== | ====== | ========= | ======================================================================================================================================================== | ================= | ================= | ========== | ========= | ======== | ======= | =============================== | ====== | == | ================================ | ========================== | 
| 201105236553 | 748144 | 8    | 1000   | MASON        | ST      |          | 1000 MASON ST       | 223   | 8   | 51    | 3        | 0.0    |        |           | Install auto fire sprinkler to protect addiitional units at lower and basement. REFERENCE TO APP#201008319983 TO ADD 3 RESIDENTIAL UNITS W/IN RESIDENCE. | APARTMENTS        | APARTMENTS        | COMPLETE   | 27-Mar-14 |          | 223008  | Residential, House and Mixed    | RM-4   | 3  |                                  | Nob Hill                   | 
| 201406188814 | 847144 | 8    | 1000   | POWELL       | ST      |          | 1000 POWELL ST      | 211   | 15  | 48    | 1        | 0.0    |        |           | CORRECT RECORD TO INCORPORATE SUPERINTENDANTS UNIT ON 1ST FLOOR                                                                                          | APARTMENTS        | APARTMENTS        | COMPLETE   | 24-Jun-14 |          | 211015  | Commercial                      | RC-4   | 3  |                                  | Chinatown                  | 
| 201208288439 | 786469 | 3    | 101    | DUBOCE       | AV      |          | 101 DUBOCE AV       | 3533  | 1   | 7     | 2        | 2      | SEC    | Homeowner | 4TH FLOOR VERTICAL ADDITION OF 2 DWELLING UNITS.                                                                                                         | APARTMENTS        | APARTMENTS        | COMPLETE   | 07-Aug-14 | RSUCRE   | 3533001 | Neighborhood Commercial Transit | NCT-3  | 8  | Market and Octavia               | Mission                    | 
| 201408143788 | 853085 | 8    | 1017   | CAPITOL      | AV      |          | 1017 CAPITOL AV     | 6985  | 10  | 1     | -1       | 0.0    |        |           | LEGALIZE ONE BEDROOM, ONE HOME OFFICE, FAMILY ROOM, REMOVE ILLEGAL KITCHEN, CONVERT FULL BATHROOM TO HALF BATHROOM. ALL WORK AT GROUND FLOOR.            | 1 FAMILY DWELLING | 1 FAMILY DWELLING | CFC ISSUED | 12-Sep-14 | MCORRETT | 6985010 | Residential, House and Mixed    | RH-1   | 13 |                                  | Oceanview/Merced/Ingleside | 
| 201404102974 | 840139 | 8    | 1028   | WISCONSIN    | ST      |          | 1028 WISCONSIN ST   | 4219  | 3   | 2     | 2        | 0.0    |        |           | TO OBTAIN FINAL INSPECTION FOR WORK APPROVED UNDER PA 201204037474; ALL WORK IS COMPLETE                                                                 |                   | 2 FAMILY DWELLING | CFC ISSUED | 06-Nov-14 |          | 4219003 | Residential, House and Mixed    | RH-2   | 9  | Eastern Neighborhoods w/Valencia | Potrero Hill               | 
| 201312305282 | 830937 | 8    | 1066   | JAMESTOWN    | AV      |          | 1066 JAMESTOWN AV   | 4969  | 21  | 1     | -1       | 0.0    |        |           | COMPLY WITH NOV #201342751 DATED 12/19/13 TO DEMOLISH KITCHEN STOVE AND SINK AT GROUND FLOOR AND BASEMENT LEVEL. LEGALIZE A BATH AT BASEMENT LEVEL.      | 1 FAMILY DWELLING | 1 FAMILY DWELLING | CFC ISSUED | 30-Jan-14 |          | 4969021 | Residential, House and Mixed    | RH-1   | 10 | Bayview Hunters Point            | Bayview Hunters Point      | 
| 201204168384 | 774457 | 1    | 1078   | HAMPSHIRE    | ST      |          | 1078 HAMPSHIRE ST   | 4152  | 46  | 2     | 2        | 0.0    |        |           | RECOMMERCEMENT AND CONCEPTION OF WORK APPROVED UNDER PA#200709193092                                                                                     |                   | 2 FAMILY DWELLING | COMPLETE   | 27-Jan-14 |          | 4152046 | Residential, House and Mixed    | RH-2   | 8  | Mission (EN)                     | Mission                    | 
| 200608290880 | 590959 | 1    | 1080   | SUTTER       | ST      | Blanc    | 1080 SUTTER ST      | 279   | 11  | 35    | 35       | 4      | MOD    | Homeowner | ERECT 11 STORIES, 35 DWELLING UNITS MIXED USE BUILDING.                                                                                                  |                   | APARTMENTS        | COMPLETE   | 02-Apr-14 | AHOLLIST | 279011  | Commercial                      | RC-4   | 4  |                                  | Nob Hill                   | 
| 201307222394 | 815371 | 6    | 110    | MIDDLE POINT | RD      |          | 110 MIDDLE POINT RD | 4624  | 31  | -4    | -4       | 0.0    |        |           | BLDG 22 - DEMOLISH 2-STORY, TYPE 5, RESIDENTIAL APARTMENT BUILDING.                                                                                      | APARTMENTS        |                   | COMPLETE   | 30-Apr-14 | MSNYDER  | 4624031 | Residential, House and Mixed    | RM-1   | 10 | Hunters View                     | Bayview Hunters Point      | 
| 201307222374 | 815349 | 6    | 112    | WEST POINT   | RD      |          | 112 WEST POINT RD   | 4624  | 31  | -4    | -4       | 0.0    |        |           | BLDG 12 - DEMOLISH 2-STORY, TYPE 5, RESIDENTIAL APARTMENT BUILDING.                                                                                      | APARTMENTS        |                   | COMPLETE   | 30-Apr-14 | MSNYDER  | 4624031 | Residential, House and Mixed    | RM-1   | 10 | Hunters View                     | Bayview Hunters Point      | 
```