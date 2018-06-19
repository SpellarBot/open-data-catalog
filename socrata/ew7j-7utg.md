# Pavement Raw Collection Data 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pavement-raw-collection-data-2012) |
| Metadata | [Link](https://data.iowa.gov/api/views/ew7j-7utg) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ew7j-7utg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ew7j-7utg/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ew7j-7utg |
| Name | Pavement Raw Collection Data 2012 |
| Attribution | Iowa Department of Transportation - Office of Analytics |
| Category | Transportation & Utilities |
| Tags | iowa, idot, raw, pavement management, pavement condition, iri, rutting, faulting, cracking, pci, pavement distress, 2012, asset, classification |
| Created | 2016-07-28T14:50:23Z |
| Publication Date | 2016-07-28T14:51:54Z |

## Description

RAW Pavement Management Information System data collection points for 2012. Pavement distress data collected on Iowa Primary and Interstate routes. The data is collected by a 3rd party vender using forward and downward facing imagery.  Data fields are subject to change in future REST services. Raw data collection points are only visible inside county wide scale.?

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | roadware_id | ROADWARE_ID | text      | number      |
| Yes      | series tag     | route       | ROUTE       | text      | number      |
| Yes      | series tag     | dir         | DIR         | text      | text        |
| Yes      | numeric metric | begin_mile  | BEGIN_MILE  | number    | number      |
| Yes      | numeric metric | end_mile    | END_MILE    | number    | number      |
| Yes      | series tag     | notes       | NOTES       | text      | text        |
| Yes      | series tag     | origkey     | ORIGKEY     | text      | text        |
| Yes      | series tag     | comments    | COMMENTS    | text      | text        |
| Yes      | series tag     | road_name   | ROAD_NAME   | text      | text        |
| Yes      | numeric metric | constru     | CONSTRU     | number    | number      |
| Yes      | time           | datec       | DATEC       | date      | date        |
| Yes      | series tag     | lane        | LANE        | text      | text        |
| Yes      | numeric metric | sealant     | SEALANT     | number    | number      |
| Yes      | numeric metric | rrx         | RRX         | number    | number      |
| Yes      | numeric metric | bridge      | BRIDGE      | number    | number      |
| Yes      | series tag     | pave_t      | PAVE_T      | text      | text        |
| Yes      | numeric metric | distance    | DISTANCE    | number    | number      |
| Yes      | numeric metric | calc_lgth   | CALC_LGTH   | number    | number      |
| Yes      | series tag     | type        | TYPE        | text      | text        |
| Yes      | numeric metric | allig_h     | ALLIG_H     | number    | number      |
| Yes      | numeric metric | allig_l     | ALLIG_L     | number    | number      |
| Yes      | numeric metric | allig_m     | ALLIG_M     | number    | number      |
| Yes      | numeric metric | dcrack_h    | DCRACK_H    | number    | number      |
| Yes      | numeric metric | dcrack_m    | DCRACK_M    | number    | number      |
| Yes      | numeric metric | jspall_h    | JSPALL_H    | number    | number      |
| Yes      | numeric metric | jspall_m    | JSPALL_M    | number    | number      |
| Yes      | numeric metric | liri        | LIRI        | number    | number      |
| Yes      | numeric metric | liri_org    | LIRI_ORG    | number    | number      |
| Yes      | numeric metric | riri        | RIRI        | number    | number      |
| Yes      | numeric metric | riri_org    | RIRI_ORG    | number    | number      |
| Yes      | numeric metric | lrut        | LRUT        | number    | number      |
| Yes      | numeric metric | lrut_org    | LRUT_ORG    | number    | number      |
| Yes      | numeric metric | rrut        | RRUT        | number    | number      |
| Yes      | numeric metric | rrut_org    | RRUT_ORG    | number    | number      |
| Yes      | numeric metric | long_h      | LONG_H      | number    | number      |
| Yes      | numeric metric | long_l      | LONG_L      | number    | number      |
| Yes      | numeric metric | long_m      | LONG_M      | number    | number      |
| Yes      | numeric metric | long_wp_h   | LONG_WP_H   | number    | number      |
| Yes      | numeric metric | long_wp_l   | LONG_WP_L   | number    | number      |
| Yes      | numeric metric | long_wp_m   | LONG_WP_M   | number    | number      |
| Yes      | numeric metric | lt_ft_sev1  | LT_FT_SEV1  | number    | number      |
| Yes      | numeric metric | lt_ft_sev2  | LT_FT_SEV2  | number    | number      |
| Yes      | numeric metric | lt_ft_sev3  | LT_FT_SEV3  | number    | number      |
| Yes      | numeric metric | lt_ft_sev4  | LT_FT_SEV4  | number    | number      |
| Yes      | numeric metric | rt_ft_sev1  | RT_FT_SEV1  | number    | number      |
| Yes      | numeric metric | rt_ft_sev2  | RT_FT_SEV2  | number    | number      |
| Yes      | numeric metric | rt_ft_sev3  | RT_FT_SEV3  | number    | number      |
| Yes      | numeric metric | rt_ft_sev4  | RT_FT_SEV4  | number    | number      |
| Yes      | numeric metric | trans_h     | TRANS_H     | number    | number      |
| Yes      | numeric metric | trans_l     | TRANS_L     | number    | number      |
| Yes      | numeric metric | trans_m     | TRANS_M     | number    | number      |
| Yes      | numeric metric | patch_b     | PATCH_B     | number    | number      |
| Yes      | numeric metric | patch_cnt   | PATCH_CNT   | number    | number      |
| Yes      | numeric metric | patch_g     | PATCH_G     | number    | number      |
| Yes      | numeric metric | pmisyr      | PMISYR      | number    | number      |
| Yes      | series tag     | pmis_id     | PMIS_ID     | text      | number      |
| Yes      | series tag     | road_id     | ROAD_ID     | text      | text        |
| Yes      | series tag     | city_id     | CITY_ID     | text      | text        |
| Yes      | series tag     | county_id   | COUNTY_ID   | text      | text        |
| Yes      | series tag     | mixpave     | MIXPAVE     | text      | text        |
| Yes      | series tag     | aran        | ARAN        | text      | text        |
| Yes      | series tag     | routing_no  | ROUTING_NO  | text      | text        |
| Yes      | series tag     | run_no      | RUN_NO      | text      | text        |
| Yes      | series tag     | src         | SRC         | text      | text        |
| Yes      | numeric metric | lanedev     | LANEDEV     | number    | number      |
| Yes      | series tag     | objectid    | OBJECTID    | text      | number      |
```

## Time Field

```ls
Value = datec
Format & Zone = seconds
```

## Data Commands

```ls
series e:ew7j-7utg d:2012-05-05T00:00:00.000Z t:pave_t=5/* t:run_no=1 t:aran=1732 t:lane=1 t:city_id=0000 t:routing_no=209960 t:mixpave=0 t:roadware_id=454254 t:dir=5 t:route=57 t:origkey="05731037 12040 1107" t:pmis_id=1919 t:county_id=07 t:road_name="IOWA 57" t:src=RW_2012_GCODE_PTS_OF_DIR1_RAW t:road_id=S t:objectid=1 t:comments=CORRECT m:jspall_m=0 m:calc_lgth=53 m:lt_ft_sev1=0 m:lt_ft_sev4=0 m:jspall_h=0 m:lt_ft_sev3=0 m:sealant=0 m:rrut_org=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=35 m:distance=4 m:long_wp_l=0 m:liri_org=35 m:long_wp_m=0 m:long_wp_h=0 m:trans_h=0 m:trans_l=0 m:trans_m=0 m:end_mile=1 m:pmisyr=2012 m:long_m=0 m:lrut_org=0 m:patch_b=0 m:constru=0 m:long_l=0 m:rrut=0 m:begin_mile=1 m:lanedev=0 m:long_h=0 m:dcrack_h=0 m:lrut=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=18 m:riri_org=18 m:allig_l=0 m:rt_ft_sev1=0 m:patch_g=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0

series e:ew7j-7utg d:2012-05-05T00:00:00.000Z t:pave_t=5/* t:run_no=1 t:aran=1732 t:lane=1 t:city_id=0000 t:routing_no=209960 t:mixpave=0 t:roadware_id=454209 t:dir=5 t:route=57 t:origkey="05731037 12040 1107" t:pmis_id=1919 t:county_id=07 t:road_name="IOWA 57" t:src=RW_2012_GCODE_PTS_OF_DIR1_RAW t:road_id=S t:objectid=2 t:comments=CORRECT m:jspall_m=0 m:calc_lgth=53 m:lt_ft_sev1=0 m:lt_ft_sev4=0 m:jspall_h=0 m:lt_ft_sev3=0 m:sealant=0 m:rrut_org=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=35 m:distance=4 m:long_wp_l=0 m:liri_org=35 m:long_wp_m=0 m:long_wp_h=0 m:trans_h=0 m:trans_l=3 m:trans_m=7 m:end_mile=0 m:pmisyr=2012 m:long_m=0 m:lrut_org=0 m:patch_b=0 m:constru=0 m:long_l=0 m:rrut=0 m:begin_mile=0 m:lanedev=0 m:long_h=0 m:dcrack_h=0 m:lrut=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=44 m:riri_org=44 m:allig_l=0 m:rt_ft_sev1=0 m:patch_g=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0

series e:ew7j-7utg d:2012-05-05T00:00:00.000Z t:pave_t=5/* t:run_no=1 t:aran=1732 t:lane=1 t:city_id=0000 t:routing_no=209960 t:mixpave=0 t:roadware_id=454210 t:dir=5 t:route=57 t:origkey="05731037 12040 1107" t:pmis_id=1919 t:county_id=07 t:road_name="IOWA 57" t:src=RW_2012_GCODE_PTS_OF_DIR1_RAW t:road_id=S t:objectid=3 t:comments=CORRECT m:jspall_m=0 m:calc_lgth=53 m:lt_ft_sev1=0 m:lt_ft_sev4=0 m:jspall_h=0 m:lt_ft_sev3=0 m:sealant=0 m:rrut_org=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=29 m:distance=4 m:long_wp_l=0 m:liri_org=29 m:long_wp_m=0 m:long_wp_h=0 m:trans_h=0 m:trans_l=0 m:trans_m=10 m:end_mile=0 m:pmisyr=2012 m:long_m=0 m:lrut_org=0 m:patch_b=0 m:constru=0 m:long_l=0 m:rrut=0 m:begin_mile=0 m:lanedev=0 m:long_h=0 m:dcrack_h=0 m:lrut=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=32 m:riri_org=32 m:allig_l=0 m:rt_ft_sev1=0 m:patch_g=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0
```

## Meta Commands

```ls
metric m:begin_mile p:long l:BEGIN_MILE d:"Beginning mile post" t:dataTypeName=number

metric m:end_mile p:long l:END_MILE d:"Ending mile post" t:dataTypeName=number

metric m:constru p:long l:CONSTRU d:Construction t:dataTypeName=number

metric m:sealant p:long l:SEALANT d:Sealant t:dataTypeName=number

metric m:rrx p:long l:RRX d:"Railroad crossing" t:dataTypeName=number

metric m:bridge p:long l:BRIDGE d:Bridge t:dataTypeName=number

metric m:distance p:long l:DISTANCE d:Distance t:dataTypeName=number

metric m:calc_lgth p:long l:CALC_LGTH d:Length t:dataTypeName=number

metric m:allig_h p:long l:ALLIG_H d:"Alligator cracking - High" t:dataTypeName=number

metric m:allig_l p:long l:ALLIG_L d:"Alligator cracking - Low" t:dataTypeName=number

metric m:allig_m p:long l:ALLIG_M d:"Alligator cracking - Medium" t:dataTypeName=number

metric m:dcrack_h p:long l:DCRACK_H d:"D-cracking - High" t:dataTypeName=number

metric m:dcrack_m p:long l:DCRACK_M d:"D-cracking - Medium" t:dataTypeName=number

metric m:jspall_h p:long l:JSPALL_H d:"Joint spalling - Medium" t:dataTypeName=number

metric m:jspall_m p:long l:JSPALL_M d:"Joint spalling - Medium" t:dataTypeName=number

metric m:liri p:long l:LIRI d:"Left wheel international roughness index" t:dataTypeName=number

metric m:liri_org p:long l:LIRI_ORG d:LIRI_ORG t:dataTypeName=number

metric m:riri p:long l:RIRI d:"Right wheel international roughness index" t:dataTypeName=number

metric m:riri_org p:long l:RIRI_ORG d:RIRI_ORG t:dataTypeName=number

metric m:lrut p:long l:LRUT d:"Left wheel rutting" t:dataTypeName=number

metric m:lrut_org p:long l:LRUT_ORG d:LRUT_ORG t:dataTypeName=number

metric m:rrut p:long l:RRUT d:"Right wheel rutting" t:dataTypeName=number

metric m:rrut_org p:long l:RRUT_ORG d:RRUT_ORG t:dataTypeName=number

metric m:long_h p:long l:LONG_H d:"Longitudinal cracking - High" t:dataTypeName=number

metric m:long_l p:long l:LONG_L d:"Longitudinal cracking - Low" t:dataTypeName=number

metric m:long_m p:long l:LONG_M d:"Longitudinal cracking - Medium" t:dataTypeName=number

metric m:long_wp_h p:long l:LONG_WP_H d:"Longitudinal wheelpath cracking - High" t:dataTypeName=number

metric m:long_wp_l p:long l:LONG_WP_L d:"Longitudinal wheelpath cracking - Low" t:dataTypeName=number

metric m:long_wp_m p:long l:LONG_WP_M d:"Longitudinal cracking - Medium" t:dataTypeName=number

metric m:lt_ft_sev1 p:long l:LT_FT_SEV1 d:"Left wheel faulting - Severity 1" t:dataTypeName=number

metric m:lt_ft_sev2 p:long l:LT_FT_SEV2 d:"Left wheel faulting - Severity 2" t:dataTypeName=number

metric m:lt_ft_sev3 p:long l:LT_FT_SEV3 d:"Left wheel faulting - Severity 3" t:dataTypeName=number

metric m:lt_ft_sev4 p:long l:LT_FT_SEV4 d:"Left wheel faulting - Severity 4" t:dataTypeName=number

metric m:rt_ft_sev1 p:long l:RT_FT_SEV1 d:"Right wheel faulting - Severity 1" t:dataTypeName=number

metric m:rt_ft_sev2 p:long l:RT_FT_SEV2 d:"Right wheel faulting - Severity 2" t:dataTypeName=number

metric m:rt_ft_sev3 p:long l:RT_FT_SEV3 d:"Right wheel faulting - Severity 3" t:dataTypeName=number

metric m:rt_ft_sev4 p:long l:RT_FT_SEV4 d:"Right wheel faulting - Severity 4" t:dataTypeName=number

metric m:trans_h p:long l:TRANS_H d:"Transverse cracking - High" t:dataTypeName=number

metric m:trans_l p:long l:TRANS_L d:"Transverse cracking - Low" t:dataTypeName=number

metric m:trans_m p:long l:TRANS_M d:"Transverse cracking - Medium" t:dataTypeName=number

metric m:patch_b p:long l:PATCH_B d:"Patches bad condition" t:dataTypeName=number

metric m:patch_cnt p:long l:PATCH_CNT d:"Patch count" t:dataTypeName=number

metric m:patch_g p:long l:PATCH_G d:"Patches good condition" t:dataTypeName=number

metric m:pmisyr p:long l:PMISYR d:"Pavement management year" t:dataTypeName=number

metric m:lanedev p:long l:LANEDEV d:"Lane deviation" t:dataTypeName=number

entity e:ew7j-7utg l:"Pavement Raw Collection Data 2012" t:attribution="Iowa Department of Transportation - Office of Analytics" t:url=https://data.iowa.gov/api/views/ew7j-7utg

property e:ew7j-7utg t:meta.view v:id=ew7j-7utg v:category="Transportation & Utilities" v:averageRating=0 v:name="Pavement Raw Collection Data 2012" v:attribution="Iowa Department of Transportation - Office of Analytics"

property e:ew7j-7utg t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:ew7j-7utg t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| roadware_id | route | dir | begin_mile | end_mile | notes | origkey             | comments | road_name | constru | datec      | lane | sealant | rrx | bridge | pave_t | distance | calc_lgth | type | allig_h | allig_l | allig_m | dcrack_h | dcrack_m | jspall_h | jspall_m | liri | liri_org | riri | riri_org | lrut | lrut_org | rrut | rrut_org | long_h | long_l | long_m | long_wp_h | long_wp_l | long_wp_m | lt_ft_sev1 | lt_ft_sev2 | lt_ft_sev3 | lt_ft_sev4 | rt_ft_sev1 | rt_ft_sev2 | rt_ft_sev3 | rt_ft_sev4 | trans_h | trans_l | trans_m | patch_b | patch_cnt | patch_g | pmisyr | pmis_id | road_id | city_id | county_id | mixpave | aran | routing_no | run_no | src                           | lanedev | objectid | 
| =========== | ===== | === | ========== | ======== | ===== | =================== | ======== | ========= | ======= | ========== | ==== | ======= | === | ====== | ====== | ======== | ========= | ==== | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ==== | ======== | ==== | ======== | ==== | ======== | ==== | ======== | ====== | ====== | ====== | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ======= | ======= | ======= | ======= | ========= | ======= | ====== | ======= | ======= | ======= | ========= | ======= | ==== | ========== | ====== | ============================= | ======= | ======== | 
| 454254      | 57    | 5   | 1          | 1        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 35   | 35       | 18   | 18       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 0       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 1        | 
| 454209      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 35   | 35       | 44   | 44       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 3       | 7       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 2        | 
| 454210      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 29   | 29       | 32   | 32       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 10      | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 3        | 
| 454211      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 39   | 39       | 41   | 41       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 0       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 4        | 
| 454212      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 37   | 37       | 49   | 49       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 3       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 5        | 
| 454214      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 65   | 65       | 52   | 52       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 2       | 8       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 6        | 
| 454215      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 3        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 66   | 66       | 58   | 58       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 2       | 0       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 7        | 
| 454216      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 69   | 69       | 54   | 54       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 0       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 8        | 
| 454219      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 56   | 56       | 56   | 56       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 0       | 0       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 9        | 
| 454220      | 57    | 5   | 0          | 0        |       | 05731037 12040 1107 | CORRECT  | IOWA 57   | 0       | 1336176000 | 1    | 0       | 0   | 0      | 5/*    | 4        | 53        |      | 0       | 0       | 0       | 0        | 0        | 0        | 0        | 64   | 64       | 50   | 50       | 0    | 0        | 0    | 0        | 0      | 0      | 0      | 0         | 0         | 0         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0       | 5       | 7       | 0       | 0         | 0       | 2012   | 1919    | S       | 0000    | 07        | 0       | 1732 | 209960     | 1      | RW_2012_GCODE_PTS_OF_DIR1_RAW | 0       | 10       | 
```