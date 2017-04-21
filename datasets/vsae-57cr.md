# Bridging The Gap Accomplishments 2007 to 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bridging-the-gap-accomplishments-2007-to-2011-496d7) |
| Metadata | [Link](https://data.seattle.gov/api/views/vsae-57cr) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vsae-57cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vsae-57cr/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vsae-57cr |
| Name | Bridging The Gap Accomplishments 2007 to 2011 |
| Attribution | SDOT |
| Category | Transportation |
| Tags | street, street construction, sidewalks, bridges, stairways, crosswalks, pedestrian transit corridors, bicycle |
| Created | 2011-10-18T20:44:00Z |
| Publication Date | 2011-10-19T21:38:11Z |

## Description

In 2006, Seattle voters passed a nine-year, $365 million levy for transportation maintenance and improvements known as Bridging the Gap. The levy is complemented by a commercial parking tax. The levy funds programs to address the maintenance backlog for paving; sidewalk development and repairs; bridge repair, rehabilitation and seismic upgrades; tree pruning and planting; transit enhancements; and other much needed maintenance work. Funding also supports projects that implement the Bicycle and Pedestrian Master plans, create a Safe Routes to School Program, improve transit connections and help neighborhoods get larger projects built through the Neighborhood Street Fund large project program.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | numeric metric | histkey    | HISTKEY    | number        | number        |
| Yes      | numeric metric | compkey    | COMPKEY    | number        | number        |
| Yes      | series tag     | comptype   | COMPTYPE   | text          | number        |
| Yes      | numeric metric | actkey     | ACTKEY     | number        | number        |
| Yes      | series tag     | actcode    | ACTCODE    | text          | text          |
| Yes      | series tag     | project_id | PROJECT_ID | text          | text          |
| Yes      | series tag     | project_na | PROJECT_NA | text          | text          |
| Yes      | series tag     | program_na | PROGRAM_NA | text          | text          |
| Yes      | series tag     | division_n | DIVISION_N | text          | text          |
| Yes      | series tag     | btg_group  | BTG_GROUP  | text          | text          |
| Yes      | series tag     | long_desc  | LONG_DESC  | text          | text          |
| Yes      | numeric metric | qty        | QTY        | number        | number        |
| Yes      | series tag     | unit_of_me | UNIT_OF_ME | text          | text          |
| Yes      | time           | compdttm   | COMPDTTM   | calendar_date | calendar_date |
| No       |                | compyear   | COMPYEAR   | number        | number        |
| Yes      | series tag     | sector     | SECTOR     | text          | text          |
| Yes      | series tag     | location   | LOCATION   | text          | text          |
| Yes      | series tag     | groupname  | GROUPNAME  | text          | text          |
| Yes      | numeric metric | groupflag  | GROUPFLAG  | number        | number        |
| No       |                | run_date   | RUN_DATE   | calendar_date | calendar_date |
| Yes      | numeric metric | wono       | WONO       | number        | number        |
| Yes      | series tag     | cra_no     | CRA_NO     | text          | number        |
| Yes      | numeric metric | cra_grp    | CRA_GRP    | number        | number        |
| Yes      | series tag     | gen_alias  | GEN_ALIAS  | text          | text          |
| Yes      | series tag     | detl_names | DETL_NAMES | text          | text          |
| Yes      | series tag     | neighdist  | NEIGHDIST  | text          | text          |
| Yes      | series tag     | data_link  | Data Link  | dataset_link  | dataset_link  |
```

## Time Field

```ls
Value = compdttm
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = run_date,compyear
```

## Data Commands

```ls
series e:vsae-57cr d:2011-03-01T00:00:00.000Z t:sector=E t:long_desc="BTG Regulatory street signs replaced" t:location="LAKESIDE AVE S BETWEEN S JUDKINS ST AND S IRVING ST" t:actcode=B-SRRP t:project_na="Sign Replacement Program" t:detl_names="Mt. Baker, North Rainier, Atlantic" t:gen_alias="Mt. Baker/North Rainier" t:comptype=68 t:cra_no=4.4 t:btg_group="Signal and Sign Maintenance" t:neighdist=Southeast t:division_n="SDOT-TRAFFIC MANAGEMENT" t:unit_of_me=Count t:project_id=TG355330 t:program_na="Signs and Markings" m:histkey=55823 m:actkey=1026 m:wono=55823 m:groupflag=0 m:cra_grp=4 m:qty=1 m:compkey=11268

series e:vsae-57cr d:2011-03-23T00:00:00.000Z t:sector=NW t:long_desc="BTG Regulatory street signs replaced" t:location="NE 60TH ST BETWEEN LATONA AVE NE AND 4TH AVE NE" t:actcode=B-SRRP t:project_na="Sign Replacement Program" t:detl_names="Green Lake, Meridian, Roosevelt, Woodland Park" t:gen_alias="Green Lake" t:comptype=68 t:cra_no=9.4 t:btg_group="Signal and Sign Maintenance" t:neighdist=Northwest t:division_n="SDOT-TRAFFIC MANAGEMENT" t:unit_of_me=Count t:project_id=TG355330 t:program_na="Signs and Markings" m:histkey=59551 m:actkey=1026 m:wono=59551 m:groupflag=0 m:cra_grp=9 m:qty=1 m:compkey=17122

series e:vsae-57cr d:2011-03-16T00:00:00.000Z t:sector=NW t:long_desc="BTG Regulatory street signs replaced" t:location="N 112TH ST BETWEEN PHINNEY AVE N AND DAYTON AVE N" t:actcode=B-SRRP t:project_na="Sign Replacement Program" t:detl_names="Crown Hill, North Beach, Blue Ridge" t:gen_alias="North Beach/Blue Ridge" t:comptype=68 t:cra_no=10.1 t:btg_group="Signal and Sign Maintenance" t:neighdist=Ballard t:division_n="SDOT-TRAFFIC MANAGEMENT" t:unit_of_me=Count t:project_id=TG355330 t:program_na="Signs and Markings" m:histkey=58581 m:actkey=1026 m:wono=58581 m:groupflag=0 m:cra_grp=10 m:qty=1 m:compkey=15060
```

## Meta Commands

```ls
metric m:histkey p:integer l:HISTKEY t:dataTypeName=number

metric m:compkey p:integer l:COMPKEY t:dataTypeName=number

metric m:actkey p:integer l:ACTKEY t:dataTypeName=number

metric m:qty p:integer l:QTY t:dataTypeName=number

metric m:groupflag p:integer l:GROUPFLAG t:dataTypeName=number

metric m:wono p:integer l:WONO t:dataTypeName=number

metric m:cra_grp p:integer l:CRA_GRP t:dataTypeName=number

entity e:vsae-57cr l:"Bridging The Gap Accomplishments 2007 to 2011" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/vsae-57cr

property e:vsae-57cr t:meta.view v:id=vsae-57cr v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/BridgingtheGap.htm v:averageRating=0 v:name="Bridging The Gap Accomplishments 2007 to 2011" v:attribution=SDOT

property e:vsae-57cr t:meta.view.license v:name="Public Domain"

property e:vsae-57cr t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vsae-57cr t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| histkey | compkey | comptype | actkey | actcode | project_id | project_na                           | program_na         | division_n              | btg_group                   | long_desc                              | qty | unit_of_me | compdttm            | compyear | sector | location                                                             | groupname | groupflag | run_date            | wono  | cra_no | cra_grp | gen_alias               | detl_names                                                          | neighdist              | data_link | 
| ======= | ======= | ======== | ====== | ======= | ========== | ==================================== | ================== | ======================= | =========================== | ====================================== | === | ========== | =================== | ======== | ====== | ==================================================================== | ========= | ========= | =================== | ===== | ====== | ======= | ======================= | =================================================================== | ====================== | ========= | 
| 55823   | 11268   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-01T00:00:00 | 2011     | E      | LAKESIDE AVE S BETWEEN S JUDKINS ST AND S IRVING ST                  |           | 0         | 2011-10-14T00:00:00 | 55823 | 4.4    | 4       | Mt. Baker/North Rainier | Mt. Baker, North Rainier, Atlantic                                  | Southeast              |           | 
| 59551   | 17122   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-23T00:00:00 | 2011     | NW     | NE 60TH ST BETWEEN LATONA AVE NE AND 4TH AVE NE                      |           | 0         | 2011-10-14T00:00:00 | 59551 | 9.4    | 9       | Green Lake              | Green Lake, Meridian, Roosevelt, Woodland Park                      | Northwest              |           | 
| 58581   | 15060   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-16T00:00:00 | 2011     | NW     | N 112TH ST BETWEEN PHINNEY AVE N AND DAYTON AVE N                    |           | 0         | 2011-10-14T00:00:00 | 58581 | 10.1   | 10      | North Beach/Blue Ridge  | Crown Hill, North Beach, Blue Ridge                                 | Ballard                |           | 
| 58583   | 15060   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-16T00:00:00 | 2011     | NW     | N 112TH ST BETWEEN PHINNEY AVE N AND DAYTON AVE N                    |           | 0         | 2011-10-14T00:00:00 | 58583 | 10.1   | 10      | North Beach/Blue Ridge  | Crown Hill, North Beach, Blue Ridge                                 | Ballard                |           | 
| 59270   | 20317   | 68       | 1034   | B-TIEV  | TG356570   | Traffic Operations Spot Improvements | Commuter Mobility  | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Traffic control concerns evaluated | 1   | Count      | 2011-03-22T00:00:00 | 2011     | SW     | S HOLGATE ST BETWEEN OCCIDENTAL AVE S AND 3RD AVE S                  |           | 0         | 2011-10-14T00:00:00 | 59270 | 3.3    | 3       | Duwamish/SODO           | Duwamish, SODO, Pioneer Square                                      | Greater Duwamish       |           | 
| 59274   | 19644   | 68       | 1034   | B-TIEV  | TG356570   | Traffic Operations Spot Improvements | Commuter Mobility  | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Traffic control concerns evaluated | 1   | Count      | 2011-03-22T00:00:00 | 2011     | SW     | S CLOVERDALE ST BETWEEN 1ST AVE S AND S CLOVERDALE (OFF RP) ST       |           | 0         | 2011-10-14T00:00:00 | 59274 | 2.5    | 2       | Highland Park           | Highland Park, Westwood, White Center, South Delridge               | Delridge Neighborhoods |           | 
| 59276   | 14281   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-15T00:00:00 | 2011     | NE     | EAST LAURELHURST DR NE BETWEEN NE 31ST ST AND NE 33RD ST             |           | 0         | 2011-10-14T00:00:00 | 59276 | 7.5    | 7       | Laurelhurst/Sand Point  | Laurelhurst, Windermere, Sand Point, Hawthorne Hills, Magnuson Park | Northeast              |           | 
| 59280   | 16170   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-16T00:00:00 | 2011     | NE     | NE 100TH ST BETWEEN LAKE SHORE BLVD NE AND LAKE SHORE (E RD) BLVD NE |           | 0         | 2011-10-14T00:00:00 | 59280 | 8.3    | 8       | Cedar Park/Meadowbrook  | Cedar Park, Lake City, Meadowbrook, Matthews Beach                  | North                  |           | 
| 59285   | 16733   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-15T00:00:00 | 2011     | NE     | NE 40TH ST BETWEEN 7TH AVE NE AND UNIVERSITY (OFF RP) BR             |           | 0         | 2011-10-14T00:00:00 | 59285 | 7.2    | 7       | University District     | University District, Cowen Park, Ravenna                            | Northeast              |           | 
| 59452   | 13520   | 68       | 1026   | B-SRRP  | TG355330   | Sign Replacement Program             | Signs and Markings | SDOT-TRAFFIC MANAGEMENT | Signal and Sign Maintenance | BTG Regulatory street signs replaced   | 1   | Count      | 2011-03-21T00:00:00 | 2011     | W      | WESTERN AVE W BETWEEN 1ST AVE W AND 2ND AVE W                        |           | 0         | 2011-10-14T00:00:00 | 59452 | 12.3   | 12      | Queen Anne              | Queen Anne, Lower Queen Anne, Uptown, Seattle Center, Westlake      | Magnolia/Queen Anne    |           | 
```