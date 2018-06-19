# SSMMA EPA Registered Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-epa-registered-facilities-4a2fe) |
| Metadata | [Link](https://data.illinois.gov/api/views/vuvb-x2d6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vuvb-x2d6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vuvb-x2d6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vuvb-x2d6 |
| Name | SSMMA EPA Registered Facilities |
| Attribution | South Suburban Mayors and Manager Association |
| Category | Municipality |
| Tags | environmental, planning, epa, ilepa |
| Created | 2012-11-27T17:51:52Z |
| Publication Date | 2012-11-27T19:11:22Z |

## Description

This dataset consists of epa registered facilities in the Chicago Southland region.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | loc_name   | Loc_name   | text          | text          |
| Yes      | series tag     | status     | Status     | text          | text          |
| Yes      | numeric metric | score      | Score      | number        | number        |
| Yes      | series tag     | match_type | Match_type | text          | text          |
| Yes      | series tag     | match_addr | Match_addr | text          | text          |
| Yes      | series tag     | side       | Side       | text          | text          |
| No       |                | x          | X          | number        | number        |
| No       |                | y          | Y          | number        | number        |
| Yes      | series tag     | frs_facili | FRS_FACILI | text          | text          |
| Yes      | numeric metric | registry_i | REGISTRY_I | number        | number        |
| Yes      | series tag     | primary_na | PRIMARY_NA | text          | text          |
| Yes      | series tag     | location_a | LOCATION_A | text          | text          |
| Yes      | series tag     | supplement | SUPPLEMENT | text          | text          |
| Yes      | series tag     | city_name  | CITY_NAME  | text          | text          |
| Yes      | series tag     | county_nam | COUNTY_NAM | text          | text          |
| Yes      | series tag     | fips_code  | FIPS_CODE  | text          | number        |
| Yes      | series tag     | state_code | STATE_CODE | text          | text          |
| Yes      | series tag     | state_name | STATE_NAME | text          | text          |
| Yes      | series tag     | postal_cod | POSTAL_COD | text          | text          |
| Yes      | numeric metric | congressio | CONGRESSIO | number        | number        |
| Yes      | series tag     | huc_code   | HUC_CODE   | text          | number        |
| Yes      | numeric metric | epa_region | EPA_REGION | number        | number        |
| Yes      | time           | create_dat | CREATE_DAT | calendar_date | calendar_date |
| No       |                | update_dat | UPDATE_DAT | calendar_date | calendar_date |
| Yes      | series tag     | conveyor   | CONVEYOR   | text          | text          |
| Yes      | series tag     | collect_de | COLLECT_DE | text          | text          |
| Yes      | series tag     | hdatum_des | HDATUM_DES | text          | text          |
| Yes      | series tag     | source_des | SOURCE_DES | text          | text          |
| No       |                | location_1 | Location 1 | text          | text          |
```

## Time Field

```ls
Value = create_dat
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x,y,update_dat,location_1
```

## Data Commands

```ls
series e:vuvb-x2d6 d:2000-03-01T00:00:00.000Z t:collect_de="ADDRESS MATCHING-HOUSE NUMBER" t:city_name=BEECHER t:state_code=IL t:match_type=A t:status=M t:match_addr="449 W Corning Rd, Beecher, IL, 60401" t:loc_name=US_Streets t:location_a="449 WEST CORNING ROAD" t:huc_code=7120001 t:state_name=ILLINOIS t:hdatum_des=NAD83 t:primary_na="BERNARD WELDING" t:frs_facili="http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432121" t:side=R t:postal_cod=60401-3127 t:conveyor=FRS t:objectid=1 t:fips_code=17197 t:county_nam=WILL m:registry_i=110000432000 m:epa_region=5 m:score=100 m:congressio=11

series e:vuvb-x2d6 d:2000-03-01T00:00:00.000Z t:collect_de="ADDRESS MATCHING-HOUSE NUMBER" t:city_name="BEECHER CITY" t:state_code=IL t:match_type=A t:status=M t:match_addr="30553 S Dixie Hwy, Beecher, IL, 60401" t:loc_name=US_Streets t:location_a="30553 S. DIXIE HWY." t:huc_code=7120001 t:state_name=ILLINOIS t:hdatum_des=NAD83 t:primary_na="TEGRANT DIVERSIFIED BRANDS INC" t:frs_facili="http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432130" t:side=R t:postal_cod=60401-3144 t:conveyor=FRS t:objectid=2 t:fips_code=17197 t:county_nam=WILL m:registry_i=110000432000 m:epa_region=5 m:score=97.46 m:congressio=11

series e:vuvb-x2d6 d:2000-03-01T00:00:00.000Z t:collect_de="ADDRESS MATCHING-HOUSE NUMBER" t:city_name=CHANNAHON t:state_code=IL t:match_type=A t:status=M t:match_addr="23247 W Eames St, Channahon, IL, 60410" t:loc_name=US_RoofTop t:location_a="23247 W.EAMES ST." t:huc_code=7120004 t:state_name=ILLINOIS t:hdatum_des=NAD83 t:primary_na="INTERSTATE CHEMICAL CO" t:frs_facili="http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432210" t:side=R t:postal_cod=60410 t:conveyor=FRS t:objectid=3 t:fips_code=17197 t:county_nam=WILL m:registry_i=110000432000 m:epa_region=5 m:score=100 m:congressio=11
```

## Meta Commands

```ls
metric m:score p:double l:Score t:dataTypeName=number

metric m:registry_i p:long l:REGISTRY_I t:dataTypeName=number

metric m:congressio p:integer l:CONGRESSIO t:dataTypeName=number

metric m:epa_region p:integer l:EPA_REGION t:dataTypeName=number

entity e:vuvb-x2d6 l:"SSMMA EPA Registered Facilities" t:attribution="South Suburban Mayors and Manager Association" t:url=https://data.illinois.gov/api/views/vuvb-x2d6

property e:vuvb-x2d6 t:meta.view v:id=vuvb-x2d6 v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA EPA Registered Facilities" v:attribution="South Suburban Mayors and Manager Association"

property e:vuvb-x2d6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vuvb-x2d6 t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:vuvb-x2d6 t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| objectid | loc_name   | status | score | match_type | match_addr                                         | side | x          | y         | frs_facili                                                                                     | registry_i   | primary_na                         | location_a                  | supplement | city_name    | county_nam | fips_code | state_code | state_name | postal_cod | congressio | huc_code | epa_region | create_dat          | update_dat          | conveyor | collect_de                    | hdatum_des | source_des | location_1                        | 
| ======== | ========== | ====== | ===== | ========== | ================================================== | ==== | ========== | ========= | ============================================================================================== | ============ | ================================== | =========================== | ========== | ============ | ========== | ========= | ========== | ========== | ========== | ========== | ======== | ========== | =================== | =================== | ======== | ============================= | ========== | ========== | ================================= | 
| 1        | US_Streets | M      | 100   | A          | 449 W Corning Rd, Beecher, IL, 60401               | R    | -87.617917 | 41.326173 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432121 | 110000432000 | BERNARD WELDING                    | 449 WEST CORNING ROAD       |            | BEECHER      | WILL       | 17197     | IL         | ILLINOIS   | 60401-3127 | 11         | 7120001  | 5          | 2000-03-01T00:00:00 | 2012-03-09T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.32622500000, -87.61810700000) | 
| 2        | US_Streets | M      | 97.46 | A          | 30553 S Dixie Hwy, Beecher, IL, 60401              | R    | -87.62125  | 41.334855 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432130 | 110000432000 | TEGRANT DIVERSIFIED BRANDS INC     | 30553 S. DIXIE HWY.         |            | BEECHER CITY | WILL       | 17197     | IL         | ILLINOIS   | 60401-3144 | 11         | 7120001  | 5          | 2000-03-01T00:00:00 | 2012-03-08T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.33491800000, -87.62132600000) | 
| 3        | US_RoofTop | M      | 100   | A          | 23247 W Eames St, Channahon, IL, 60410             | R    | -88.177845 | 41.466877 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432210 | 110000432000 | INTERSTATE CHEMICAL CO             | 23247 W.EAMES ST.           |            | CHANNAHON    | WILL       | 17197     | IL         | ILLINOIS   | 60410      | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2011-11-07T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.46666700000, -88.17819100000) | 
| 4        | US_Streets | M      | 87.35 | A          | 27711 S Frontage Rd, Channahon, IL, 60410          | R    | -88.194208 | 41.426149 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432238 | 110000432000 | HAGER WOOD PRESERVING INCORPORATED | 27711 SOUTH FRONTAGE ROAD   |            | CHANNAHON    | WILL       | 17197     | IL         | ILLINOIS   | 60410-9790 | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-01-26T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.42588500000, -88.19427200000) | 
| 5        | US_Streets | M      | 90.97 | A          | 24219 S Northern Illinois Dr, Channahon, IL, 60410 | R    | -88.202299 | 41.443506 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432256 | 110000432000 | METALSTAMP INC                     | 24219 NORTHERN ILLINOIS DR. |            | CHANNAHON    | WILL       | 17197     | IL         | ILLINOIS   | 60410-5114 | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-01-26T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.44351800000, -88.20237400000) | 
| 6        | US_Streets | M      | 100   | A          | 24708 W Durkee Rd, Channahon, IL, 60410            | R    | -88.207772 | 41.410056 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432265 | 110000432000 | LODERS CROKLAAN                    | 24708 W. DURKEE RD.         |            | CHANNAHON    | WILL       | 17197     | IL         | ILLINOIS   | 60410      | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-03-09T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.41010400000, -88.20797100000) | 
| 7        | US_Streets | M      | 100   | A          | 24420 W Durkee Rd, Channahon, IL, 60410            | R    | -88.197971 | 41.410297 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432274 | 110000432000 | IMTT ILLINOIS - JOLIET FACILITY    | 24420 W. DURKEE RD.         |            | CHANNAHON    | WILL       | 17197     | IL         | ILLINOIS   | 60410      | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-03-09T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.41034500000, -88.19809200000) | 
| 8        | US_Streets | M      | 87.35 | A          | 3400 W Exchange St, Crete, IL, 60417               | L    | -87.695663 | 41.44716  | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432452 | 110000432000 | AMERICAN LOCK CO                   | 3400 W. EXCHANGE RD.        |            | CRETE        | WILL       | 17197     | IL         | ILLINOIS   | 60417-2043 | 2          | 7120003  | 5          | 2000-03-01T00:00:00 | 2012-02-22T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.44710200000, -87.69567500000) | 
| 9        | US_RoofTop | M      | 100   | A          | 22500 W Millsdale Rd, Elwood, IL, 60421            | L    | -88.160054 | 41.435278 | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432504 | 110000433000 | STEPAN CO MILLSDALE ROAD           | 22500 WEST MILLSDALE ROAD   |            | ELWOOD       | WILL       | 17197     | IL         | ILLINOIS   | 60421-9646 | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-03-09T00:00:00 | FRS-US   |                               | NAD83      |            | (41.44166700000, -88.15972000000) | 
| 10       | US_RoofTop | M      | 100   | A          | 300 S Maple St, Frankfort, IL, 60423               | L    | -87.854669 | 41.49509  | http://iaspub.epa.gov/enviro/fii_query_detail.disp_program_facility?p_registry_id=110000432513 | 110000433000 | BORGWARNER TRANSMISSION SYSTEMS    | 300 SOUTH MAPLE STREET      |            | FRANKFORT    | WILL       | 17197     | IL         | ILLINOIS   | 60423-1652 | 11         | 7120004  | 5          | 2000-03-01T00:00:00 | 2012-03-09T00:00:00 | FRS      | ADDRESS MATCHING-HOUSE NUMBER | NAD83      |            | (41.49450600000, -87.85461000000) | 
```