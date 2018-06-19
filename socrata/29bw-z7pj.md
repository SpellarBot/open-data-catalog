# 2005 Street Tree Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2005-street-tree-census) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/29bw-z7pj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/29bw-z7pj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/29bw-z7pj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 29bw-z7pj |
| Name | 2005 Street Tree Census |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Environment |
| Tags | dpr, parks, recreation, trees, census |
| Created | 2016-06-01T20:34:53Z |
| Publication Date | 2016-06-02T14:12:33Z |

## Description

Citywide street tree data from the 2005 Street Tree Census, conducted partly by volunteers organized by NYC Parks & Recreation. Trees were inventoried by address, and were collected from 2005-2006. Data collected includes tree species, diameter, condition.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| Yes      | numeric metric | cen_year   | cen_year   | number    | number      |
| Yes      | numeric metric | tree_dbh   | tree_dbh   | number    | number      |
| Yes      | series tag     | tree_loc   | tree_loc   | text      | text        |
| Yes      | series tag     | pit_type   | pit_type   | text      | text        |
| Yes      | series tag     | soil_lvl   | soil_lvl   | text      | text        |
| Yes      | series tag     | status     | status     | text      | text        |
| Yes      | series tag     | spc_latin  | spc_latin  | text      | text        |
| Yes      | series tag     | spc_common | spc_common | text      | text        |
| Yes      | series tag     | vert_other | vert_other | text      | text        |
| Yes      | series tag     | vert_pgrd  | vert_pgrd  | text      | text        |
| Yes      | series tag     | vert_tgrd  | vert_tgrd  | text      | text        |
| Yes      | series tag     | vert_wall  | vert_wall  | text      | text        |
| Yes      | series tag     | horz_blck  | horz_blck  | text      | text        |
| Yes      | series tag     | horz_grate | horz_grate | text      | text        |
| Yes      | series tag     | horz_plant | horz_plant | text      | text        |
| Yes      | series tag     | horz_other | horz_other | text      | text        |
| Yes      | series tag     | sidw_crack | sidw_crack | text      | text        |
| Yes      | series tag     | sidw_raise | sidw_raise | text      | text        |
| Yes      | series tag     | wire_htap  | wire_htap  | text      | text        |
| Yes      | series tag     | wire_prime | wire_prime | text      | text        |
| Yes      | series tag     | wire_2nd   | wire_2nd   | text      | text        |
| Yes      | series tag     | wire_other | wire_other | text      | text        |
| Yes      | series tag     | inf_canopy | inf_canopy | text      | text        |
| Yes      | series tag     | inf_guard  | inf_guard  | text      | text        |
| Yes      | series tag     | inf_wires  | inf_wires  | text      | text        |
| Yes      | series tag     | inf_paving | inf_paving | text      | text        |
| Yes      | series tag     | inf_outlet | inf_outlet | text      | text        |
| Yes      | series tag     | inf_shoes  | inf_shoes  | text      | text        |
| Yes      | series tag     | inf_lights | inf_lights | text      | text        |
| Yes      | series tag     | inf_other  | inf_other  | text      | text        |
| Yes      | series tag     | trunk_dmg  | trunk_dmg  | text      | text        |
| Yes      | series tag     | zipcode    | zipcode    | text      | text        |
| Yes      | series tag     | zip_city   | zip_city   | text      | text        |
| Yes      | series tag     | cb_num     | cb_num     | text      | number      |
| Yes      | series tag     | borocode   | borocode   | text      | number      |
| Yes      | series tag     | boroname   | boroname   | text      | text        |
| Yes      | numeric metric | cncldist   | cncldist   | number    | number      |
| Yes      | numeric metric | st_assem   | st_assem   | number    | number      |
| Yes      | numeric metric | st_senate  | st_senate  | number    | number      |
| Yes      | series tag     | nta        | nta        | text      | text        |
| Yes      | series tag     | nta_name   | nta_name   | text      | text        |
| Yes      | numeric metric | boro_ct    | boro_ct    | number    | number      |
| Yes      | numeric metric | x_sp       | x_sp       | number    | number      |
| Yes      | numeric metric | y_sp       | y_sp       | number    | number      |
| Yes      | series tag     | objectid_1 | objectid_1 | text      | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:29bw-z7pj d:2005-01-01T00:00:00.000Z t:borocode=3 t:horz_blck=No t:horz_grate=No t:inf_guard=No t:wire_htap=No t:horz_plant=Yes t:zip_city=Brooklyn t:inf_other=No t:inf_paving=No t:inf_wires=No t:inf_outlet=No t:vert_pgrd=No t:nta_name="Borough Park" t:boroname=Brooklyn t:objectid_1=0 t:wire_prime=Yes t:sidw_crack=No t:soil_lvl=Level t:nta=BK88 t:status=Good t:tree_loc=Front t:sidw_raise=No t:zipcode=11219 t:trunk_dmg=None t:inf_lights=No t:horz_other=No t:wire_2nd=No t:wire_other=No t:inf_shoes=No t:vert_wall=No t:inf_canopy=No t:vert_tgrd=No t:pit_type="Sidewalk Pit" t:cb_num=312 t:vert_other=No t:spc_common="PEAR, CALLERY" t:objectid=592373 t:spc_latin="PYRUS CALLERYANA" m:boro_ct=3021600 m:cen_year=2005 m:y_sp=169769 m:cncldist=44 m:st_senate=17 m:x_sp=984182 m:st_assem=48 m:tree_dbh=6

series e:29bw-z7pj d:2005-01-01T00:00:00.000Z t:borocode=3 t:horz_blck=No t:horz_grate=No t:inf_guard=No t:wire_htap=No t:horz_plant=No t:zip_city=Brooklyn t:inf_other=Yes t:inf_paving=No t:inf_wires=No t:inf_outlet=No t:vert_pgrd=No t:nta_name="Georgetown-Marine Park-Bergen Beach-Mill Basin" t:boroname=Brooklyn t:objectid_1=1 t:wire_prime=No t:sidw_crack=No t:soil_lvl=Level t:nta=BK45 t:status=Good t:tree_loc=Across t:sidw_raise=No t:zipcode=11234 t:trunk_dmg=None t:inf_lights=No t:horz_other=No t:wire_2nd=No t:wire_other=No t:inf_shoes=No t:vert_wall=No t:inf_canopy=No t:vert_tgrd=No t:pit_type="Sidewalk Pit" t:cb_num=318 t:vert_other=No t:spc_common="LONDON PLANETREE" t:objectid=592374 t:spc_latin="PLATANUS ACERIFOLIA" m:boro_ct=3070600 m:cen_year=2005 m:y_sp=165205 m:cncldist=46 m:st_senate=19 m:x_sp=1011608 m:st_assem=59 m:tree_dbh=6

series e:29bw-z7pj d:2005-01-01T00:00:00.000Z t:borocode=3 t:horz_blck=No t:horz_grate=No t:inf_guard=No t:wire_htap=Yes t:horz_plant=Yes t:zip_city=Brooklyn t:inf_other=Yes t:inf_paving=Yes t:inf_wires=No t:inf_outlet=No t:vert_pgrd=No t:nta_name="Georgetown-Marine Park-Bergen Beach-Mill Basin" t:boroname=Brooklyn t:objectid_1=2 t:wire_prime=Yes t:sidw_crack=No t:soil_lvl=Level t:nta=BK45 t:status=Good t:tree_loc=Front t:sidw_raise=No t:zipcode=11234 t:trunk_dmg=Cavity t:inf_lights=No t:horz_other=Yes t:wire_2nd=Yes t:wire_other=No t:inf_shoes=No t:vert_wall=No t:inf_canopy=No t:vert_tgrd=No t:pit_type="Continuous Pit" t:cb_num=318 t:vert_other=No t:spc_common="MAPLE, NORWAY-CR KNG" t:objectid=592375 t:spc_latin="ACER PLATANOIDES          CRIMSON KING" m:boro_ct=3070600 m:cen_year=2005 m:y_sp=164445 m:cncldist=46 m:st_senate=19 m:x_sp=1012259 m:st_assem=59 m:tree_dbh=13
```

## Meta Commands

```ls
metric m:cen_year p:integer l:cen_year t:dataTypeName=number

metric m:tree_dbh p:integer l:tree_dbh t:dataTypeName=number

metric m:cncldist p:integer l:cncldist t:dataTypeName=number

metric m:st_assem p:integer l:st_assem t:dataTypeName=number

metric m:st_senate p:integer l:st_senate t:dataTypeName=number

metric m:boro_ct p:integer l:boro_ct t:dataTypeName=number

metric m:x_sp p:float l:x_sp t:dataTypeName=number

metric m:y_sp p:float l:y_sp t:dataTypeName=number

entity e:29bw-z7pj l:"2005 Street Tree Census" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/29bw-z7pj

property e:29bw-z7pj t:meta.view v:id=29bw-z7pj v:category=Environment v:averageRating=0 v:name="2005 Street Tree Census" v:attribution="Department of Parks and Recreation (DPR)"

property e:29bw-z7pj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:29bw-z7pj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| objectid | cen_year | tree_dbh | tree_loc | pit_type       | soil_lvl | status    | spc_latin                     | spc_common           | vert_other | vert_pgrd | vert_tgrd | vert_wall | horz_blck | horz_grate | horz_plant | horz_other | sidw_crack | sidw_raise | wire_htap | wire_prime | wire_2nd | wire_other | inf_canopy | inf_guard | inf_wires | inf_paving | inf_outlet | inf_shoes | inf_lights | inf_other | trunk_dmg   | zipcode | zip_city | cb_num | borocode | boroname | cncldist | st_assem | st_senate | nta  | nta_name                                       | boro_ct | x_sp                    | y_sp                   | objectid_1 | 
| ======== | ======== | ======== | ======== | ============== | ======== | ========= | ============================= | ==================== | ========== | ========= | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========= | ========== | ======== | ========== | ========== | ========= | ========= | ========== | ========== | ========= | ========== | ========= | =========== | ======= | ======== | ====== | ======== | ======== | ======== | ======== | ========= | ==== | ============================================== | ======= | ======================= | ====================== | ========== | 
| 592373   | 2005     | 6        | Front    | Sidewalk Pit   | Level    | Good      | PYRUS CALLERYANA              | PEAR, CALLERY        | No         | No        | No        | No        | No        | No         | Yes        | No         | No         | No         | No        | Yes        | No       | No         | No         | No        | No        | No         | No         | No        | No         | No        | None        | 11219   | Brooklyn | 312    | 3        | Brooklyn | 44       | 48       | 17        | BK88 | Borough Park                                   | 3021600 | 984182.000000000000000  | 169769.000000000000000 | 0          | 
| 592374   | 2005     | 6        | Across   | Sidewalk Pit   | Level    | Good      | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | No         | No         | No         | No         | No        | No         | No       | No         | No         | No        | No        | No         | No         | No        | No         | Yes       | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1011608.000000000000000 | 165205.000000000000000 | 1          | 
| 592375   | 2005     | 13       | Front    | Continuous Pit | Level    | Good      | ACER PLATANOIDES CRIMSON KING | MAPLE, NORWAY-CR KNG | No         | No        | No        | No        | No        | No         | Yes        | Yes        | No         | No         | Yes       | Yes        | Yes      | No         | No         | No        | No        | Yes        | No         | No        | No         | Yes       | Cavity      | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1012259.000000000000000 | 164445.000000000000000 | 2          | 
| 592376   | 2005     | 13       | Across   | Sidewalk Pit   | Level    | Good      | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | Yes        | No         | No         | No         | No        | No         | No       | No         | No         | No        | No        | No         | No         | No        | No         | No        | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1011733.000000000000000 | 165063.000000000000000 | 3          | 
| 592377   | 2005     | 15       | Across   | Sidewalk Pit   | Level    | Good      | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | Yes        | No         | No         | No         | No        | No         | No       | No         | No         | No        | No        | No         | No         | No        | No         | Yes       | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1012160.000000000000000 | 164564.000000000000000 | 4          | 
| 592378   | 2005     | 21       | Front    | Sidewalk Pit   | Level    | Poor      | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | No         | No         | No         | No         | No        | No         | No       | No         | No         | No        | No        | Yes        | No         | No        | No         | No        | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1011447.000000000000000 | 163751.000000000000000 | 5          | 
| 592379   | 2005     | 19       | Front    | Continuous Pit | Level    | Good      | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | Yes        | No         | No         | No         | Yes       | No         | Yes      | No         | No         | No        | Yes       | Yes        | No         | No        | No         | Yes       | Trunk Wound | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3070600 | 1011341.000000000000000 | 163073.000000000000000 | 6          | 
| 592380   | 2005     | 11       | Front    | Lawn           | Level    | Excellent | PLATANUS ACERIFOLIA           | LONDON PLANETREE     | No         | No        | No        | No        | No        | No         | No         | No         | No         | No         | No        | Yes        | No       | No         | No         | No        | No        | No         | No         | No        | No         | No        | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3069800 | 1007598.000000000000000 | 164610.000000000000000 | 7          | 
| 592381   | 2005     | 14       | Front    | Lawn           | Level    | Excellent | ACER PLATANOIDES CRIMSON KING | MAPLE, NORWAY-CR KNG | No         | No        | No        | No        | No        | No         | No         | No         | No         | No         | No        | Yes        | No       | No         | No         | No        | No        | No         | No         | No        | No         | No        | None        | 11234   | Brooklyn | 318    | 3        | Brooklyn | 46       | 59       | 19        | BK45 | Georgetown-Marine Park-Bergen Beach-Mill Basin | 3069800 | 1007589.000000000000000 | 164620.000000000000000 | 8          | 
| 592382   | 2005     | 3        | Front    | Lawn           | Level    | Good      | CRATAEGUS SPECIES             | HAWTHORN, OTHER      | No         | Yes       | No        | No        | No        | No         | No         | No         | No         | No         | No        | Yes        | No       | No         | No         | No        | No        | No         | No         | No        | No         | No        | None        | 11219   | Brooklyn | 312    | 3        | Brooklyn | 44       | 48       | 17        | BK88 | Borough Park                                   | 3021600 | 984287.000000000000000  | 169685.000000000000000 | 9          | 
```