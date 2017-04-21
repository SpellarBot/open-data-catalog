# Pavement Raw Collection Data 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pavement-raw-collection-data-2014) |
| Metadata | [Link](https://data.iowa.gov/api/views/tyh9-jfm6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tyh9-jfm6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tyh9-jfm6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tyh9-jfm6 |
| Name | Pavement Raw Collection Data 2014 |
| Attribution | Iowa Department of Transportation - Office of Analytics |
| Category | Transportation & Utilities |
| Tags | iowa, idot, raw, pavement management, pavement condition, iri, rutting, faulting, cracking, pci, pavement distress, 2014, asset, classification |
| Created | 2016-07-28T14:43:41Z |
| Publication Date | 2016-07-28T14:46:17Z |

## Description

RAW Pavement Management Information System data collection points for 2015. Pavement distress data collected on Iowa Primary and Interstate routes. The data is collected by a 3rd party vender using forward and downward facing imagery.  Data fields are subject to change in future REST services. Raw data collection points are only visible inside county wide scale.?

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | roadware_id | ROADWARE_ID | text      | number      |
| Yes      | series tag     | route       | ROUTE       | text      | number      |
| Yes      | numeric metric | dir         | DIR         | number    | text        |
| Yes      | numeric metric | begin_mile  | BEGIN_MILE  | number    | number      |
| Yes      | numeric metric | end_mile    | END_MILE    | number    | number      |
| Yes      | series tag     | origkey     | ORIGKEY     | text      | text        |
| Yes      | series tag     | road_name   | ROAD_NAME   | text      | text        |
| Yes      | numeric metric | constru     | CONSTRU     | number    | number      |
| Yes      | numeric metric | lanedev     | LANEDEV     | number    | number      |
| Yes      | series tag     | city_id     | CITY_ID     | text      | text        |
| Yes      | series tag     | county_id   | COUNTY_ID   | text      | text        |
| Yes      | time           | datec       | DATEC       | date      | date        |
| Yes      | numeric metric | lane        | LANE        | number    | text        |
| Yes      | numeric metric | sealant     | SEALANT     | number    | number      |
| Yes      | numeric metric | rrx         | RRX         | number    | number      |
| Yes      | numeric metric | bridge      | BRIDGE      | number    | number      |
| Yes      | series tag     | pave_t      | PAVE_T      | text      | text        |
| Yes      | series tag     | type_       | TYPE_       | text      | text        |
| Yes      | numeric metric | allig_h     | ALLIG_H     | number    | number      |
| Yes      | numeric metric | allig_l     | ALLIG_L     | number    | number      |
| Yes      | numeric metric | allig_m     | ALLIG_M     | number    | number      |
| No       |                | long_h      | LONG_H      | number    | number      |
| No       |                | long_l      | LONG_L      | number    | number      |
| No       |                | long_m      | LONG_M      | number    | number      |
| No       |                | long_wp_h   | LONG_WP_H   | number    | number      |
| No       |                | long_wp_l   | LONG_WP_L   | number    | number      |
| No       |                | long_wp_m   | LONG_WP_M   | number    | number      |
| Yes      | numeric metric | trans_h     | TRANS_H     | number    | number      |
| Yes      | numeric metric | trans_l     | TRANS_L     | number    | number      |
| Yes      | numeric metric | trans_m     | TRANS_M     | number    | number      |
| Yes      | numeric metric | jspall_h    | JSPALL_H    | number    | number      |
| Yes      | numeric metric | jspall_m    | JSPALL_M    | number    | number      |
| Yes      | numeric metric | dcrack_h    | DCRACK_H    | number    | number      |
| Yes      | numeric metric | dcrack_m    | DCRACK_M    | number    | number      |
| Yes      | numeric metric | mixpave     | MIXPAVE     | number    | text        |
| Yes      | numeric metric | patch_b     | PATCH_B     | number    | number      |
| Yes      | numeric metric | patch_cnt   | PATCH_CNT   | number    | number      |
| Yes      | numeric metric | patch_g     | PATCH_G     | number    | number      |
| Yes      | numeric metric | liri        | LIRI        | number    | number      |
| Yes      | numeric metric | riri        | RIRI        | number    | number      |
| Yes      | numeric metric | lrut        | LRUT        | number    | number      |
| Yes      | numeric metric | rrut        | RRUT        | number    | number      |
| Yes      | numeric metric | curb        | CURB        | number    | number      |
| Yes      | numeric metric | dropoff     | DROPOFF     | number    | number      |
| Yes      | series tag     | routing_no  | ROUTING_NO  | text      | text        |
| Yes      | series tag     | run_no      | RUN_NO      | text      | text        |
| Yes      | series tag     | road_id     | ROAD_ID     | text      | text        |
| Yes      | numeric metric | aran        | ARAN        | number    | text        |
| Yes      | numeric metric | lt_ft_sev1  | LT_FT_SEV1  | number    | number      |
| Yes      | numeric metric | lt_ft_sev2  | LT_FT_SEV2  | number    | number      |
| Yes      | numeric metric | lt_ft_sev3  | LT_FT_SEV3  | number    | number      |
| Yes      | numeric metric | lt_ft_sev4  | LT_FT_SEV4  | number    | number      |
| Yes      | numeric metric | rt_ft_sev1  | RT_FT_SEV1  | number    | number      |
| Yes      | numeric metric | rt_ft_sev2  | RT_FT_SEV2  | number    | number      |
| Yes      | numeric metric | rt_ft_sev3  | RT_FT_SEV3  | number    | number      |
| Yes      | numeric metric | rt_ft_sev4  | RT_FT_SEV4  | number    | number      |
| Yes      | numeric metric | calc_lgth   | CALC_LGTH   | number    | number      |
| Yes      | numeric metric | distance    | DISTANCE    | number    | number      |
| Yes      | series tag     | comments    | COMMENTS    | text      | text        |
| Yes      | series tag     | notes       | NOTES       | text      | text        |
| Yes      | numeric metric | pmisyr      | PMISYR      | number    | number      |
| Yes      | series tag     | pmis_id     | PMIS_ID     | text      | number      |
| Yes      | series tag     | objectid    | OBJECTID    | text      | number      |
```

## Time Field

```ls
Value = datec
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = long_h,long_l,long_m,long_wp_h,long_wp_l,long_wp_m
```

## Data Commands

```ls
series e:tyh9-jfm6 d:2014-05-16T00:00:00.000Z t:city_id=0000 t:routing_no=100150 t:type_=FAE t:pave_t=ASP t:roadware_id=57 t:run_no=1 t:route=35 t:origkey="03511126 04130 6040" t:county_id=40 t:road_name="I 35" t:road_id=S t:objectid=1 m:jspall_m=0 m:calc_lgth=52.73715171 m:lt_ft_sev1=0 m:aran=1731 m:curb=0 m:lt_ft_sev4=0 m:jspall_h=0 m:sealant=53 m:lt_ft_sev3=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=36.29 m:lane=1 m:distance=5.0084765 m:dir=5 m:trans_h=0 m:trans_l=20.87 m:end_mile=0.79 m:trans_m=9.74 m:constru=0 m:patch_b=0 m:rrut=0.08 m:begin_mile=0.78 m:lanedev=0 m:dropoff=0 m:lrut=0.11 m:dcrack_h=0 m:mixpave=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=42.76 m:allig_l=0 m:patch_g=0 m:rt_ft_sev1=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0

series e:tyh9-jfm6 d:2014-05-16T00:00:00.000Z t:city_id=0000 t:routing_no=100150 t:type_=FAE t:pave_t=ASP t:roadware_id=61 t:run_no=1 t:route=35 t:origkey="03511126 04130 6040" t:county_id=40 t:road_name="I 35" t:road_id=S t:objectid=2 m:jspall_m=0 m:calc_lgth=52.73901391 m:lt_ft_sev1=0 m:aran=1731 m:curb=0 m:lt_ft_sev4=0 m:jspall_h=0 m:sealant=53 m:lt_ft_sev3=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=47.800000000000004 m:lane=1 m:distance=5.12362756 m:dir=5 m:trans_h=0 m:trans_l=36.97 m:end_mile=0.8300000000000001 m:trans_m=9.58 m:constru=0 m:patch_b=0 m:rrut=0.2 m:begin_mile=0.8200000000000001 m:lanedev=0 m:dropoff=0 m:lrut=0.17 m:dcrack_h=0 m:mixpave=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=67.15 m:allig_l=0 m:patch_g=0 m:rt_ft_sev1=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0

series e:tyh9-jfm6 d:2014-05-16T00:00:00.000Z t:city_id=0000 t:routing_no=100150 t:type_=FAE t:pave_t=ASP t:roadware_id=63 t:run_no=1 t:route=35 t:origkey="03511126 04130 6040" t:county_id=40 t:road_name="I 35" t:road_id=S t:objectid=3 m:jspall_m=0 m:calc_lgth=52.73165245 m:lt_ft_sev1=0 m:aran=1731 m:curb=0 m:lt_ft_sev4=0 m:jspall_h=0 m:sealant=53 m:lt_ft_sev3=0 m:lt_ft_sev2=0 m:dcrack_m=0 m:liri=24.59 m:lane=1 m:distance=5.04715203 m:dir=5 m:trans_h=0 m:trans_l=22.68 m:end_mile=0.85 m:trans_m=9.67 m:constru=0 m:patch_b=0 m:rrut=0.08 m:begin_mile=0.84 m:lanedev=0 m:dropoff=0 m:lrut=0.1 m:dcrack_h=0 m:mixpave=0 m:allig_h=0 m:rrx=0 m:allig_m=0 m:riri=41.95 m:allig_l=0 m:patch_g=0 m:rt_ft_sev1=0 m:rt_ft_sev3=0 m:bridge=0 m:rt_ft_sev2=0 m:rt_ft_sev4=0 m:patch_cnt=0
```

## Meta Commands

```ls
metric m:dir p:integer l:DIR d:Direction t:dataTypeName=number

metric m:begin_mile p:float l:BEGIN_MILE d:"Beginning mile post" t:dataTypeName=number

metric m:end_mile p:float l:END_MILE d:"Ending mile post" t:dataTypeName=number

metric m:constru p:integer l:CONSTRU d:Construction t:dataTypeName=number

metric m:lanedev p:integer l:LANEDEV d:"Lane deviation" t:dataTypeName=number

metric m:lane p:integer l:LANE d:"Lane identifier" t:dataTypeName=number

metric m:sealant p:integer l:SEALANT d:Sealant t:dataTypeName=number

metric m:rrx p:integer l:RRX d:"Railroad crossing" t:dataTypeName=number

metric m:bridge p:integer l:BRIDGE d:Bridge t:dataTypeName=number

metric m:allig_h p:float l:ALLIG_H d:"Alligator cracking - High" t:dataTypeName=number

metric m:allig_l p:float l:ALLIG_L d:"Alligator cracking - Low" t:dataTypeName=number

metric m:allig_m p:float l:ALLIG_M d:"Alligator cracking - Medium" t:dataTypeName=number

metric m:trans_h p:float l:TRANS_H d:"Transverse cracking - High" t:dataTypeName=number

metric m:trans_l p:float l:TRANS_L d:"Transverse cracking - Low" t:dataTypeName=number

metric m:trans_m p:decimal l:TRANS_M d:"Transverse cracking - Medium" t:dataTypeName=number

metric m:jspall_h p:integer l:JSPALL_H d:"Joint spalling - High" t:dataTypeName=number

metric m:jspall_m p:integer l:JSPALL_M d:"Joint spalling - Medium" t:dataTypeName=number

metric m:dcrack_h p:integer l:DCRACK_H d:"D-cracking - High" t:dataTypeName=number

metric m:dcrack_m p:integer l:DCRACK_M d:"D-cracking - Medium" t:dataTypeName=number

metric m:mixpave p:integer l:MIXPAVE d:"Multiple pavement type" t:dataTypeName=number

metric m:patch_b p:float l:PATCH_B d:"Patches bad condition" t:dataTypeName=number

metric m:patch_cnt p:integer l:PATCH_CNT d:"Patch count" t:dataTypeName=number

metric m:patch_g p:float l:PATCH_G d:"Patches good condition" t:dataTypeName=number

metric m:liri p:decimal l:LIRI d:"Left wheel international roughness index" t:dataTypeName=number

metric m:riri p:decimal l:RIRI d:"Right wheel international roughness index" t:dataTypeName=number

metric m:lrut p:float l:LRUT d:"Left wheel rutting" t:dataTypeName=number

metric m:rrut p:double l:RRUT d:"Right wheel rutting" t:dataTypeName=number

metric m:curb p:double l:CURB d:Curb t:dataTypeName=number

metric m:dropoff p:float l:DROPOFF d:Dropoff t:dataTypeName=number

metric m:aran p:integer l:ARAN d:"Vehicle number" t:dataTypeName=number

metric m:lt_ft_sev1 p:integer l:LT_FT_SEV1 d:"Left wheel faulting - Severity 1" t:dataTypeName=number

metric m:lt_ft_sev2 p:integer l:LT_FT_SEV2 d:"Left wheel faulting - Severity 2" t:dataTypeName=number

metric m:lt_ft_sev3 p:integer l:LT_FT_SEV3 d:"Left wheel faulting - Severity 3" t:dataTypeName=number

metric m:lt_ft_sev4 p:integer l:LT_FT_SEV4 d:"Left wheel faulting - Severity 4" t:dataTypeName=number

metric m:rt_ft_sev1 p:integer l:RT_FT_SEV1 d:"Right wheel faulting - Severity 1" t:dataTypeName=number

metric m:rt_ft_sev2 p:integer l:RT_FT_SEV2 d:"Right wheel faulting - Severity 2" t:dataTypeName=number

metric m:rt_ft_sev3 p:integer l:RT_FT_SEV3 d:"Right wheel faulting - Severity 3" t:dataTypeName=number

metric m:rt_ft_sev4 p:integer l:RT_FT_SEV4 d:"Right wheel faulting - Severity 4" t:dataTypeName=number

metric m:calc_lgth p:decimal l:CALC_LGTH d:Length t:dataTypeName=number

metric m:distance p:decimal l:DISTANCE d:Distance t:dataTypeName=number

metric m:pmisyr p:long l:PMISYR d:"Pavement management year" t:dataTypeName=number

entity e:tyh9-jfm6 l:"Pavement Raw Collection Data 2014" t:attribution="Iowa Department of Transportation - Office of Analytics" t:url=https://data.iowa.gov/api/views/tyh9-jfm6

property e:tyh9-jfm6 t:meta.view v:id=tyh9-jfm6 v:category="Transportation & Utilities" v:averageRating=0 v:name="Pavement Raw Collection Data 2014" v:attribution="Iowa Department of Transportation - Office of Analytics"

property e:tyh9-jfm6 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:tyh9-jfm6 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| roadware_id | route | dir | begin_mile                                              | end_mile                                                | origkey             | road_name | constru | lanedev | city_id | county_id | datec      | lane | sealant | rrx | bridge | pave_t | type_ | allig_h | allig_l | allig_m | long_h | long_l                                                | long_m | long_wp_h | long_wp_l                                             | long_wp_m | trans_h | trans_l                                               | trans_m                                             | jspall_h | jspall_m | dcrack_h | dcrack_m | mixpave | patch_b | patch_cnt | patch_g | liri                                                | riri                                               | lrut                                                       | rrut                                                        | curb | dropoff | routing_no | run_no | road_id | aran | lt_ft_sev1 | lt_ft_sev2 | lt_ft_sev3 | lt_ft_sev4 | rt_ft_sev1 | rt_ft_sev2 | rt_ft_sev3 | rt_ft_sev4 | calc_lgth                                          | distance                                              | comments | notes | pmisyr | pmis_id | objectid | 
| =========== | ===== | === | ======================================================= | ======================================================= | =================== | ========= | ======= | ======= | ======= | ========= | ========== | ==== | ======= | === | ====== | ====== | ===== | ======= | ======= | ======= | ====== | ===================================================== | ====== | ========= | ===================================================== | ========= | ======= | ===================================================== | =================================================== | ======== | ======== | ======== | ======== | ======= | ======= | ========= | ======= | =================================================== | ================================================== | ========================================================== | =========================================================== | ==== | ======= | ========== | ====== | ======= | ==== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ================================================== | ===================================================== | ======== | ===== | ====== | ======= | ======== | 
| 57          | 35    | 5   | 0.7800000000000000266453525910037569701671600341796875  | 0.79000000000000003552713678800500929355621337890625    | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 3.390000000000000124344978758017532527446746826171875 | 0      | 0         | 52.2300000000000039790393202565610408782958984375     | 0         | 0       | 20.870000000000000994759830064140260219573974609375   | 9.7400000000000002131628207280300557613372802734375 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 36.28999999999999914734871708787977695465087890625  | 42.75999999999999801048033987171947956085205078125 | 0.11000000000000000055511151231257827021181583404541015625 | 0.08000000000000000166533453693773481063544750213623046875  | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.73715170999999912737621343694627285003662109375 | 5.008476500000000442014425061643123626708984375       |          |       |        |         | 1        | 
| 61          | 35    | 5   | 0.8200000000000000621724893790087662637233734130859375  | 0.8300000000000000710542735760100185871124267578125     | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 37.28999999999999914734871708787977695465087890625    | 0      | 0         | 24.769999999999999573674358543939888477325439453125   | 0         | 0       | 36.969999999999998863131622783839702606201171875      | 9.5800000000000000710542735760100185871124267578125 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 47.80000000000000426325641456060111522674560546875  | 67.150000000000005684341886080801486968994140625   | 0.1700000000000000122124532708767219446599483489990234375  | 0.200000000000000011102230246251565404236316680908203125    | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.7390139099999970540011418052017688751220703125  | 5.12362756000000008071992851910181343555450439453125  |          |       |        |         | 2        | 
| 63          | 35    | 5   | 0.83999999999999996891375531049561686813831329345703125 | 0.84999999999999997779553950749686919152736663818359375 | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 14.8499999999999996447286321199499070644378662109375  | 0      | 0         | 50.46000000000000085265128291212022304534912109375    | 0         | 0       | 22.67999999999999971578290569595992565155029296875    | 9.6699999999999999289457264239899814128875732421875 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 24.589999999999999857891452847979962825775146484375 | 41.9500000000000028421709430404007434844970703125  | 0.1000000000000000055511151231257827021181583404541015625  | 0.08000000000000000166533453693773481063544750213623046875  | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.7316524499999985664544510655105113983154296875  | 5.04715203000000034450067687430419027805328369140625  |          |       |        |         | 3        | 
| 64          | 35    | 5   | 0.84999999999999997779553950749686919152736663818359375 | 0.85999999999999998667732370449812151491641998291015625 | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 15.8800000000000007815970093361102044582366943359375  | 0      | 0         | 51.75999999999999801048033987171947956085205078125    | 0         | 0       | 12.46000000000000085265128291212022304534912109375    | 9.800000000000000710542735760100185871124267578125  | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 31.6099999999999994315658113919198513031005859375   | 42.93999999999999772626324556767940521240234375    | 0.1000000000000000055511151231257827021181583404541015625  | 0.070000000000000006661338147750939242541790008544921875    | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.72611841999999882091287872754037380218505859375 | 4.93021508999999991118556863511912524700164794921875  |          |       |        |         | 4        | 
| 72          | 35    | 5   | 0.93000000000000004884981308350688777863979339599609375 | 0.94000000000000005773159728050814010202884674072265625 | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 7.17999999999999971578290569595992565155029296875     | 0      | 0         | 36.340000000000003410605131648480892181396484375      | 0         | 0       | 18.92999999999999971578290569595992565155029296875    | 19.080000000000001847411112976260483264923095703125 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 35.05000000000000426325641456060111522674560546875  | 53.41000000000000369482222595252096652984619140625 | 0.11000000000000000055511151231257827021181583404541015625 | 0.070000000000000006661338147750939242541790008544921875    | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.72239872000000104890204966068267822265625       | 4.666810540000000173677108250558376312255859375       |          |       |        |         | 5        | 
| 77          | 35    | 5   | 0.979999999999999982236431605997495353221893310546875   | 0.9899999999999999911182158029987476766109466552734375  | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 9.089999999999999857891452847979962825775146484375    | 0      | 0         | 2.319999999999999840127884453977458178997039794921875 | 0         | 0       | 1.890000000000000124344978758017532527446746826171875 | 27.870000000000000994759830064140260219573974609375 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 56.6099999999999994315658113919198513031005859375   | 55.25999999999999801048033987171947956085205078125 | 0.11000000000000000055511151231257827021181583404541015625 | 0.070000000000000006661338147750939242541790008544921875    | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.71672902000000249245204031467437744140625       | 3.663004790000000010508074410608969628810882568359375 |          |       |        |         | 6        | 
| 79          | 35    | 5   | 1                                                       | 1.0100000000000000088817841970012523233890533447265625  | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 36.99000000000000198951966012828052043914794921875    | 0      | 0         | 8.6699999999999999289457264239899814128875732421875   | 0         | 0       | 18.550000000000000710542735760100185871124267578125   | 9.300000000000000710542735760100185871124267578125  | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 44.2000000000000028421709430404007434844970703125   | 57.21000000000000085265128291212022304534912109375 | 0.11000000000000000055511151231257827021181583404541015625 | 0.05000000000000000277555756156289135105907917022705078125  | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.71668790999999743007720098830759525299072265625 | 3.329287359999999917903323876089416444301605224609375 |          |       |        |         | 7        | 
| 82          | 35    | 5   | 1.0300000000000000266453525910037569701671600341796875  | 1.04000000000000003552713678800500929355621337890625    | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 0                                                     | 0      | 0         | 0                                                     | 0         | 0       | 9.050000000000000710542735760100185871124267578125    | 18.519999999999999573674358543939888477325439453125 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 44.46000000000000085265128291212022304534912109375  | 50.1700000000000017053025658242404460906982421875  | 0.11000000000000000055511151231257827021181583404541015625 | 0.040000000000000000832667268468867405317723751068115234375 | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.72405789999999825568011146970093250274658203125 | 3.5001259999999998484554453170858323574066162109375   |          |       |        |         | 8        | 
| 84          | 35    | 5   | 1.0500000000000000444089209850062616169452667236328125  | 1.060000000000000053290705182007513940334320068359375   | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 0                                                     | 0      | 0         | 0                                                     | 0         | 0       | 9.2900000000000009237055564881302416324615478515625   | 16.080000000000001847411112976260483264923095703125 | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 43.52000000000000312638803734444081783294677734375  | 53.1700000000000017053025658242404460906982421875  | 0.11999999999999999555910790149937383830547332763671875    | 0.059999999999999997779553950749686919152736663818359375    | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.72964560999999861223841435275971889495849609375 | 4.017456700000000324735083268024027347564697265625    |          |       |        |         | 9        | 
| 91          | 35    | 5   | 1.12000000000000010658141036401502788066864013671875    | 1.1300000000000001154631945610162802040576934814453125  | 03511126 04130 6040 | I 35      | 0       | 0       | 0000    | 40        | 1400198400 | 1    | 53      | 0   | 0      | ASP    | FAE   | 0       | 0       | 0       | 0      | 17.050000000000000710542735760100185871124267578125   | 0      | 0         | 1.75                                                  | 0         | 0       | 27.53999999999999914734871708787977695465087890625    | 9.370000000000000994759830064140260219573974609375  | 0        | 0        | 0        | 0        | 0       | 0       | 0         | 0       | 48.25                                               | 80.0700000000000073896444519050419330596923828125  | 0.0899999999999999966693309261245303787291049957275390625  | 0.11000000000000000055511151231257827021181583404541015625  | 0    | 0       | 100150     | 1      | S       | 1731 | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 52.74267133000000029596776585094630718231201171875 | 4.9694997900000004165121936239302158355712890625      |          |       |        |         | 10       | 
```