# 2015 Street Tree Census - Tree Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-street-tree-census-tree-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uvpi-gqnh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uvpi-gqnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uvpi-gqnh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uvpi-gqnh |
| Name | 2015 Street Tree Census - Tree Data |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Environment |
| Tags | parks, trees, treescount, census, dpr, nycopendata |
| Created | 2016-06-03T12:14:58Z |
| Publication Date | 2017-02-16T22:29:41Z |

## Description

Street tree data from the TreesCount! 2015 Street Tree Census, conducted by volunteers and staff organized by NYC Parks & Recreation and partner organizations. Tree data collected includes tree species, diameter and perception of health. Accompanying blockface data is available indicating status of data collection and data release citywide.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | tree_id    | tree_id    | text          | number        |
| Yes      | series tag     | block_id   | block_id   | text          | number        |
| Yes      | time           | created_at | created_at | calendar_date | calendar_date |
| Yes      | numeric metric | tree_dbh   | tree_dbh   | number        | number        |
| Yes      | numeric metric | stump_diam | stump_diam | number        | number        |
| Yes      | series tag     | curb_loc   | curb_loc   | text          | text          |
| Yes      | series tag     | status     | status     | text          | text          |
| Yes      | series tag     | health     | health     | text          | text          |
| Yes      | series tag     | spc_latin  | spc_latin  | text          | text          |
| Yes      | series tag     | spc_common | spc_common | text          | text          |
| Yes      | series tag     | steward    | steward    | text          | text          |
| Yes      | series tag     | guards     | guards     | text          | text          |
| Yes      | series tag     | sidewalk   | sidewalk   | text          | text          |
| Yes      | series tag     | user_type  | user_type  | text          | text          |
| Yes      | series tag     | problems   | problems   | text          | text          |
| Yes      | series tag     | root_stone | root_stone | text          | text          |
| Yes      | series tag     | root_grate | root_grate | text          | text          |
| Yes      | series tag     | root_other | root_other | text          | text          |
| Yes      | series tag     | trunk_wire | trunk_wire | text          | text          |
| Yes      | series tag     | trnk_light | trnk_light | text          | text          |
| Yes      | series tag     | trnk_other | trnk_other | text          | text          |
| Yes      | series tag     | brch_light | brch_light | text          | text          |
| Yes      | series tag     | brch_shoe  | brch_shoe  | text          | text          |
| Yes      | series tag     | brch_other | brch_other | text          | text          |
| No       |                | address    | address    | text          | text          |
| Yes      | series tag     | zipcode    | zipcode    | text          | number        |
| Yes      | series tag     | zip_city   | zip_city   | text          | text          |
| Yes      | series tag     | cb_num     | cb_num     | text          | number        |
| Yes      | series tag     | borocode   | borocode   | text          | number        |
| Yes      | series tag     | boroname   | boroname   | text          | text          |
| Yes      | numeric metric | cncldist   | cncldist   | number        | number        |
| Yes      | numeric metric | st_assem   | st_assem   | number        | number        |
| Yes      | numeric metric | st_senate  | st_senate  | number        | number        |
| Yes      | series tag     | nta        | nta        | text          | text          |
| Yes      | series tag     | nta_name   | nta_name   | text          | text          |
| Yes      | numeric metric | boro_ct    | boro_ct    | number        | number        |
| Yes      | series tag     | state      | state      | text          | text          |
| No       |                | latitude   | latitude   | number        | number        |
| No       |                | longitude  | longitude  | number        | number        |
| Yes      | numeric metric | x_sp       | x_sp       | number        | number        |
| Yes      | numeric metric | y_sp       | y_sp       | number        | number        |
```

## Time Field

```ls
Value = created_at
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:uvpi-gqnh d:2015-08-27T00:00:00.000Z t:borocode=4 t:trnk_other=No t:trunk_wire=No t:steward=None t:root_other=No t:state="New York" t:zip_city="Forest Hills" t:brch_shoe=No t:brch_light=No t:nta_name="Forest Hills" t:boroname=Queens t:root_stone=No t:guards=None t:problems=None t:nta=QN17 t:user_type="TreesCount Staff" t:status=Alive t:trnk_light=No t:zipcode=11375 t:root_grate=No t:health=Fair t:tree_id=180683 t:curb_loc=OnCurb t:cb_num=406 t:brch_other=No t:spc_common="red maple" t:spc_latin="Acer rubrum" t:block_id=348711 t:sidewalk=NoDamage m:boro_ct=4073900 m:y_sp=202756.7687 m:stump_diam=0 m:cncldist=29 m:st_senate=16 m:x_sp=1027431.148 m:st_assem=28 m:tree_dbh=3

series e:uvpi-gqnh d:2015-09-03T00:00:00.000Z t:borocode=4 t:trnk_other=No t:trunk_wire=No t:steward=None t:root_other=No t:state="New York" t:zip_city=Whitestone t:brch_shoe=No t:brch_light=No t:nta_name=Whitestone t:boroname=Queens t:root_stone=Yes t:guards=None t:problems=Stones t:nta=QN49 t:user_type="TreesCount Staff" t:status=Alive t:trnk_light=No t:zipcode=11357 t:root_grate=No t:health=Fair t:tree_id=200540 t:curb_loc=OnCurb t:cb_num=407 t:brch_other=No t:spc_common="pin oak" t:spc_latin="Quercus palustris" t:block_id=315986 t:sidewalk=Damage m:boro_ct=4097300 m:y_sp=228644.8374 m:stump_diam=0 m:cncldist=19 m:st_senate=11 m:x_sp=1034455.701 m:st_assem=27 m:tree_dbh=21

series e:uvpi-gqnh d:2015-09-05T00:00:00.000Z t:borocode=3 t:trnk_other=No t:trunk_wire=No t:steward=1or2 t:root_other=No t:state="New York" t:zip_city=Brooklyn t:brch_shoe=No t:brch_light=No t:nta_name="East Williamsburg" t:boroname=Brooklyn t:root_stone=No t:guards=None t:problems=None t:nta=BK90 t:user_type=Volunteer t:status=Alive t:trnk_light=No t:zipcode=11211 t:root_grate=No t:health=Good t:tree_id=204026 t:curb_loc=OnCurb t:cb_num=301 t:brch_other=No t:spc_common=honeylocust t:spc_latin="Gleditsia triacanthos var. inermis" t:block_id=218365 t:sidewalk=Damage m:boro_ct=3044900 m:y_sp=200716.8913 m:stump_diam=0 m:cncldist=34 m:st_senate=18 m:x_sp=1001822.831 m:st_assem=50 m:tree_dbh=3
```

## Meta Commands

```ls
metric m:tree_dbh p:integer l:tree_dbh t:dataTypeName=number

metric m:stump_diam p:integer l:stump_diam t:dataTypeName=number

metric m:cncldist p:integer l:cncldist t:dataTypeName=number

metric m:st_assem p:integer l:st_assem t:dataTypeName=number

metric m:st_senate p:integer l:st_senate t:dataTypeName=number

metric m:boro_ct p:integer l:boro_ct t:dataTypeName=number

metric m:x_sp p:double l:x_sp t:dataTypeName=number

metric m:y_sp p:double l:y_sp t:dataTypeName=number

entity e:uvpi-gqnh l:"2015 Street Tree Census - Tree Data" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/uvpi-gqnh

property e:uvpi-gqnh t:meta.view v:id=uvpi-gqnh v:category=Environment v:averageRating=0 v:name="2015 Street Tree Census - Tree Data" v:attribution="Department of Parks and Recreation (DPR)"

property e:uvpi-gqnh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uvpi-gqnh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| tree_id | block_id | created_at          | tree_dbh | stump_diam | curb_loc       | status | health | spc_latin                          | spc_common       | steward | guards  | sidewalk | user_type        | problems    | root_stone | root_grate | root_other | trunk_wire | trnk_light | trnk_other | brch_light | brch_shoe | brch_other | address            | zipcode | zip_city      | cb_num | borocode | boroname      | cncldist | st_assem | st_senate | nta  | nta_name                        | boro_ct | state    | latitude    | longitude    | x_sp        | y_sp        | 
| ======= | ======== | =================== | ======== | ========== | ============== | ====== | ====== | ================================== | ================ | ======= | ======= | ======== | ================ | =========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========= | ========== | ================== | ======= | ============= | ====== | ======== | ============= | ======== | ======== | ========= | ==== | =============================== | ======= | ======== | =========== | ============ | =========== | =========== | 
| 180683  | 348711   | 2015-08-27T00:00:00 | 3        | 0          | OnCurb         | Alive  | Fair   | Acer rubrum                        | red maple        | None    | None    | NoDamage | TreesCount Staff | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 108-005 70 AVENUE  | 11375   | Forest Hills  | 406    | 4        | Queens        | 29       | 28       | 16        | QN17 | Forest Hills                    | 4073900 | New York | 40.72309177 | -73.84421522 | 1027431.148 | 202756.7687 | 
| 200540  | 315986   | 2015-09-03T00:00:00 | 21       | 0          | OnCurb         | Alive  | Fair   | Quercus palustris                  | pin oak          | None    | None    | Damage   | TreesCount Staff | Stones      | Yes        | No         | No         | No         | No         | No         | No         | No        | No         | 147-074 7 AVENUE   | 11357   | Whitestone    | 407    | 4        | Queens        | 19       | 27       | 11        | QN49 | Whitestone                      | 4097300 | New York | 40.79411067 | -73.81867946 | 1034455.701 | 228644.8374 | 
| 204026  | 218365   | 2015-09-05T00:00:00 | 3        | 0          | OnCurb         | Alive  | Good   | Gleditsia triacanthos var. inermis | honeylocust      | 1or2    | None    | Damage   | Volunteer        | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 390 MORGAN AVENUE  | 11211   | Brooklyn      | 301    | 3        | Brooklyn      | 34       | 50       | 18        | BK90 | East Williamsburg               | 3044900 | New York | 40.71758074 | -73.9366077  | 1001822.831 | 200716.8913 | 
| 204337  | 217969   | 2015-09-05T00:00:00 | 10       | 0          | OnCurb         | Alive  | Good   | Gleditsia triacanthos var. inermis | honeylocust      | None    | None    | Damage   | Volunteer        | Stones      | Yes        | No         | No         | No         | No         | No         | No         | No        | No         | 1027 GRAND STREET  | 11211   | Brooklyn      | 301    | 3        | Brooklyn      | 34       | 53       | 18        | BK90 | East Williamsburg               | 3044900 | New York | 40.71353749 | -73.93445616 | 1002420.358 | 199244.2531 | 
| 189565  | 223043   | 2015-08-30T00:00:00 | 21       | 0          | OnCurb         | Alive  | Good   | Tilia americana                    | American linden  | None    | None    | Damage   | Volunteer        | Stones      | Yes        | No         | No         | No         | No         | No         | No         | No        | No         | 603 6 STREET       | 11215   | Brooklyn      | 306    | 3        | Brooklyn      | 39       | 44       | 21        | BK37 | Park Slope-Gowanus              | 3016500 | New York | 40.66677776 | -73.97597938 | 990913.775  | 182202.426  | 
| 190422  | 106099   | 2015-08-30T00:00:00 | 11       | 0          | OnCurb         | Alive  | Good   | Gleditsia triacanthos var. inermis | honeylocust      | 1or2    | Helpful | NoDamage | Volunteer        | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 8 COLUMBUS AVENUE  | 10023   | New York      | 107    | 1        | Manhattan     | 3        | 67       | 27        | MN14 | Lincoln Square                  | 1014500 | New York | 40.77004563 | -73.98494997 | 988418.6997 | 219825.5227 | 
| 190426  | 106099   | 2015-08-30T00:00:00 | 11       | 0          | OnCurb         | Alive  | Good   | Gleditsia triacanthos var. inermis | honeylocust      | 1or2    | Helpful | NoDamage | Volunteer        | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 120 WEST 60 STREET | 10023   | New York      | 107    | 1        | Manhattan     | 3        | 67       | 27        | MN14 | Lincoln Square                  | 1014500 | New York | 40.77020969 | -73.98533807 | 988311.19   | 219885.2785 | 
| 208649  | 103940   | 2015-09-07T00:00:00 | 9        | 0          | OnCurb         | Alive  | Good   | Tilia americana                    | American linden  | None    | None    | NoDamage | Volunteer        | MetalGrates | No         | Yes        | No         | No         | No         | No         | No         | No        | No         | 311 WEST 50 STREET | 10019   | New York      | 104    | 1        | Manhattan     | 3        | 75       | 27        | MN15 | Clinton                         | 1012700 | New York | 40.76272385 | -73.98729652 | 987769.1163 | 217157.8561 | 
| 209610  | 407443   | 2015-09-08T00:00:00 | 6        | 0          | OnCurb         | Alive  | Good   | Gleditsia triacanthos var. inermis | honeylocust      | None    | None    | NoDamage | TreesCount Staff | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 65 JEROME AVENUE   | 10305   | Staten Island | 502    | 5        | Staten Island | 50       | 64       | 23        | SI14 | Grasmere-Arrochar-Ft. Wadsworth | 5006400 | New York | 40.59657931 | -74.07625483 | 963073.1998 | 156635.5542 | 
| 192755  | 207508   | 2015-08-31T00:00:00 | 21       | 0          | OffsetFromCurb | Alive  | Fair   | Platanus x acerifolia              | London planetree | None    | None    | NoDamage | TreesCount Staff | None        | No         | No         | No         | No         | No         | No         | No         | No        | No         | 638 AVENUE Z       | 11223   | Brooklyn      | 313    | 3        | Brooklyn      | 47       | 45       | 23        | BK26 | Gravesend                       | 3037402 | New York | 40.58635725 | -73.96974394 | 992653.7253 | 152903.6306 | 
```