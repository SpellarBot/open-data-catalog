# 1995 Street Tree Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/1995-street-tree-census) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kyad-zm4j) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kyad-zm4j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kyad-zm4j/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kyad-zm4j |
| Name | 1995 Street Tree Census |
| Attribution | Department of Parks and Recreation |
| Category | Environment |
| Tags | parks, trees, census, recreation, volunteers, inventory |
| Created | 2015-08-20T19:24:11Z |
| Publication Date | 2015-08-20T20:49:07Z |

## Description

Citywide street tree data from the 1995 Street Tree Census, conducted by volunteers organized by NYC Parks & Recreation.  Trees were inventoried by address, and were collected from 1995-1996.  Data collected includes tree species, diameter, condition.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | recordid           | RecordId           | text      | number      |
| No       |                | address            | Address            | text      | text        |
| Yes      | series tag     | house_number       | House_Number       | text      | number      |
| Yes      | series tag     | street             | Street             | text      | text        |
| Yes      | series tag     | zip_original       | Zip_Original       | text      | number      |
| Yes      | numeric metric | cb_original        | CB_Original        | number    | number      |
| Yes      | series tag     | site               | Site               | text      | text        |
| Yes      | series tag     | species            | Species            | text      | text        |
| Yes      | numeric metric | diameter           | Diameter           | number    | number      |
| Yes      | series tag     | condition          | Condition          | text      | text        |
| Yes      | series tag     | wires              | Wires              | text      | text        |
| Yes      | series tag     | sidewalk_condition | Sidewalk_Condition | text      | text        |
| Yes      | series tag     | support_structure  | Support_Structure  | text      | text        |
| Yes      | series tag     | borough            | Borough            | text      | text        |
| No       |                | x                  | X                  | number    | number      |
| No       |                | y                  | Y                  | number    | number      |
| No       |                | longitude          | Longitude          | number    | number      |
| No       |                | latitude           | Latitude           | number    | number      |
| Yes      | numeric metric | cb_new             | CB_New             | number    | number      |
| Yes      | series tag     | zip_new            | Zip_New            | text      | number      |
| Yes      | numeric metric | censustract_2010   | CensusTract_2010   | number    | number      |
| Yes      | numeric metric | censusblock_2010   | CensusBlock_2010   | number    | number      |
| Yes      | series tag     | nta_2010           | NTA_2010           | text      | text        |
| Yes      | series tag     | segmentid          | SegmentID          | text      | number      |
| Yes      | series tag     | spc_common         | Spc_Common         | text      | text        |
| Yes      | series tag     | spc_latin          | Spc_Latin          | text      | text        |
```

## Time Field

```ls
Value = 1995
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,x,y,longitude,latitude
```

## Data Commands

```ls
series e:kyad-zm4j d:1995-01-01T00:00:00.000Z t:site=Front t:species=PLAC t:sidewalk_condition=NA t:condition=Unknown t:wires=None t:street="E 17 ST" t:borough=Manhattan t:zip_new=10003 t:support_structure=None t:house_number=245 t:nta_2010=MN21 t:zip_original=10003 t:spc_common="LONDON PLANETREE" t:spc_latin="PLATANUS ACERIFOLIA" t:recordid=1 t:segmentid=33134 m:diameter=8 m:cb_original=106 m:censustract_2010=48 m:censusblock_2010=2000 m:cb_new=106

series e:kyad-zm4j d:1995-01-01T00:00:00.000Z t:site=Side t:species=ACPL t:sidewalk_condition=Good t:condition=Good t:wires=None t:street="N MOORE ST" t:borough=Manhattan t:zip_new=10013 t:support_structure=None t:house_number=80 t:nta_2010=MN24 t:zip_original=10013 t:spc_common="MAPLE, NORWAY" t:spc_latin="ACER PLATANOIDES" t:recordid=2 t:segmentid=31567 m:diameter=7 m:cb_original=101 m:censustract_2010=39 m:censusblock_2010=2001 m:cb_new=101

series e:kyad-zm4j d:1995-01-01T00:00:00.000Z t:site=Side t:species=ACPL t:sidewalk_condition=Good t:condition=Good t:wires=None t:street="N MOORE ST" t:borough=Manhattan t:zip_new=10013 t:support_structure=None t:house_number=80 t:nta_2010=MN24 t:zip_original=10013 t:spc_common="MAPLE, NORWAY" t:spc_latin="ACER PLATANOIDES" t:recordid=3 t:segmentid=31567 m:diameter=6 m:cb_original=101 m:censustract_2010=39 m:censusblock_2010=2001 m:cb_new=101
```

## Meta Commands

```ls
metric m:cb_original p:integer l:CB_Original d:"The community board originally geocoded to the address using LION 02A" t:dataTypeName=number

metric m:diameter p:integer l:Diameter d:"Diameter of the tree as measured at approximately 4.5 feet from the ground." t:dataTypeName=number

metric m:cb_new p:integer l:CB_New d:"Community Board geocoded to the address using Geosupport 11.4" t:dataTypeName=number

metric m:censustract_2010 p:integer l:CensusTract_2010 d:"2010 Census Tract geocoded to the address using Geosupport 11.4" t:dataTypeName=number

metric m:censusblock_2010 p:integer l:CensusBlock_2010 d:"2010 Census Block geocoded to the address using Geosupport 11.4" t:dataTypeName=number

entity e:kyad-zm4j l:"1995 Street Tree Census" t:attribution="Department of Parks and Recreation" t:url=https://data.cityofnewyork.us/api/views/kyad-zm4j

property e:kyad-zm4j t:meta.view v:id=kyad-zm4j v:category=Environment v:averageRating=0 v:name="1995 Street Tree Census" v:attribution="Department of Parks and Recreation"

property e:kyad-zm4j t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kyad-zm4j t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| recordid | address       | house_number | street     | zip_original | cb_original | site  | species | diameter | condition | wires | sidewalk_condition | support_structure | borough   | x           | y           | longitude  | latitude  | cb_new | zip_new | censustract_2010 | censusblock_2010 | nta_2010 | segmentid | spc_common           | spc_latin           | 
| ======== | ============= | ============ | ========== | ============ | =========== | ===== | ======= | ======== | ========= | ===== | ================== | ================= | ========= | =========== | =========== | ========== | ========= | ====== | ======= | ================ | ================ | ======== | ========= | ==================== | =================== | 
| 1        | 245 E 17 ST   | 245          | E 17 ST    | 10003        | 106         | Front | PLAC    | 8        | Unknown   | None  | NA                 | None              | Manhattan | 988618.9688 | 206893.764  | -73.984235 | 40.734551 | 106    | 10003   | 48               | 2000             | MN21     | 33134     | LONDON PLANETREE     | PLATANUS ACERIFOLIA | 
| 2        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 7        | Good      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 3        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 6        | Good      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 4        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 7        | Excellent | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 5        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 6        | Good      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 6        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | SOJA    | 6        | Good      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | JAPANESE PAGODA TREE | SOPHORA JAPONICA    | 
| 7        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 7        | Excellent | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 8        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 7        | Poor      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
| 9        | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | SOJA    | 4        | Poor      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | JAPANESE PAGODA TREE | SOPHORA JAPONICA    | 
| 10       | 80 N MOORE ST | 80           | N MOORE ST | 10013        | 101         | Side  | ACPL    | 7        | Poor      | None  | Good               | None              | Manhattan | 981330.4271 | 201649.9518 | -74.010532 | 40.720159 | 101    | 10013   | 39               | 2001             | MN24     | 31567     | MAPLE, NORWAY        | ACER PLATANOIDES    | 
```