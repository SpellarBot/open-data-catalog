# DWW Catch Basins

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dww-catch-basins-436cf) |
| Metadata | [Link](https://data.seattle.gov/api/views/r7pf-fsen) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/r7pf-fsen/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/r7pf-fsen/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | r7pf-fsen |
| Name | DWW Catch Basins |
| Category | Land Base |
| Tags | drainage, basins, spu, catch basin |
| Created | 2014-07-14T18:40:47Z |
| Publication Date | 2014-07-14T18:42:38Z |

## Description

https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/57

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | objectid               | OBJECTID               | text      | number      |
| Yes      | numeric metric | cb_fea_key             | CB_FEA_KEY             | number    | number      |
| Yes      | series tag     | cb_eqnum_id            | CB_EQNUM_ID            | text      | text        |
| Yes      | series tag     | cb_s_endpt_id          | CB_S_ENDPT_ID          | text      | text        |
| Yes      | series tag     | cb_d_endpt_id          | CB_D_ENDPT_ID          | text      | text        |
| Yes      | series tag     | cb_npdes_id            | CB_NPDES_ID            | text      | text        |
| Yes      | series tag     | cb_cb_id               | CB_CB_ID               | text      | text        |
| Yes      | series tag     | cb_map_area_id         | CB_MAP_AREA_ID         | text      | text        |
| Yes      | series tag     | cb_owner_code          | CB_OWNER_CODE          | text      | text        |
| Yes      | series tag     | cb_owner_name          | CB_OWNER_NAME          | text      | text        |
| Yes      | series tag     | cb_featype_code        | CB_FEATYPE_CODE        | text      | text        |
| Yes      | series tag     | cb_featype_text        | CB_FEATYPE_TEXT        | text      | text        |
| Yes      | series tag     | cb_lifecycle_code      | CB_LIFECYCLE_CODE      | text      | text        |
| Yes      | series tag     | cb_lifecycle_stat      | CB_LIFECYCLE_STAT      | text      | text        |
| Yes      | series tag     | cb_depth_ref_code      | CB_DEPTH_REF_CODE      | text      | text        |
| Yes      | series tag     | cb_depth_ref_text      | CB_DEPTH_REF_TEXT      | text      | text        |
| Yes      | series tag     | cb_cvr_elev_ref_code   | CB_CVR_ELEV_REF_CODE   | text      | text        |
| Yes      | series tag     | cb_cvr_elev_ref_text   | CB_CVR_ELEV_REF_TEXT   | text      | text        |
| Yes      | series tag     | cb_role_code           | CB_ROLE_CODE           | text      | text        |
| Yes      | series tag     | cb_role_type           | CB_ROLE_TYPE           | text      | text        |
| Yes      | numeric metric | cb_depth_ft_nbr        | CB_DEPTH_FT_NBR        | number    | number      |
| Yes      | numeric metric | cb_cvr_elev_ft_nbr     | CB_CVR_ELEV_FT_NBR     | number    | number      |
| Yes      | numeric metric | cb_inc_inlet_nbr       | CB_INC_INLET_NBR       | number    | number      |
| Yes      | numeric metric | cb_rotation_nbr        | CB_ROTATION_NBR        | number    | number      |
| Yes      | series tag     | cb_sym_num             | CB_SYM_NUM             | text      | number      |
| No       |                | cb_install_date        | CB_INSTALL_DATE        | date      | date        |
| No       |                | cb_retire_date         | CB_RETIRE_DATE         | date      | date        |
| Yes      | time           | cb_lst_updt_date       | CB_LST_UPDT_DATE       | date      | date        |
| Yes      | numeric metric | cb_x_coord             | CB_X_COORD             | number    | number      |
| Yes      | numeric metric | cb_y_coord             | CB_Y_COORD             | number    | number      |
| Yes      | series tag     | cb_rec_wtrbdy_name     | CB_REC_WTRBDY_NAME     | text      | text        |
| Yes      | series tag     | cb_mxm_mnt_agrmnt_text | CB_MXM_MNT_AGRMNT_TEXT | text      | text        |
| Yes      | series tag     | cb_mxm_artrl_text      | CB_MXM_ARTRL_TEXT      | text      | text        |
| Yes      | series tag     | cb_mxm_adrs_text       | CB_MXM_ADRS_TEXT       | text      | text        |
| Yes      | series tag     | cb_mxm_comments_text   | CB_MXM_COMMENTS_TEXT   | text      | text        |
| Yes      | series tag     | cb_mxm_cncrt_flag      | CB_MXM_CNCRT_FLAG      | text      | text        |
| Yes      | series tag     | cb_mxm_dstrct_code     | CB_MXM_DSTRCT_CODE     | text      | text        |
| Yes      | series tag     | cb_mxm_lndsld_flag     | CB_MXM_LNDSLD_FLAG     | text      | text        |
| Yes      | series tag     | cb_mxm_leaf_flag       | CB_MXM_LEAF_FLAG       | text      | text        |
| Yes      | series tag     | cb_mxm_snw_ice_flag    | CB_MXM_SNW_ICE_FLAG    | text      | text        |
| Yes      | series tag     | cb_mxm_storm_flag      | CB_MXM_STORM_FLAG      | text      | text        |
| Yes      | series tag     | cb_mxm_grt_slt_flag    | CB_MXM_GRT_SLT_FLAG    | text      | text        |
| Yes      | series tag     | cb_mxm_grate_type      | CB_MXM_GRATE_TYPE      | text      | text        |
| Yes      | series tag     | cb_mxm_inlet_250_flag  | CB_MXM_INLET_250_FLAG  | text      | text        |
| Yes      | series tag     | cb_mxm_material_type   | CB_MXM_MATERIAL_TYPE   | text      | text        |
| Yes      | series tag     | cb_mxm_2crw_flag       | CB_MXM_2CRW_FLAG       | text      | text        |
| Yes      | series tag     | cb_mxm_nprks_flag      | CB_MXM_NPRKS_FLAG      | text      | text        |
| Yes      | series tag     | cb_mxm_prkhd_flag      | CB_MXM_PRKHD_FLAG      | text      | text        |
| Yes      | series tag     | cb_mxm_swr_acs_text    | CB_MXM_SWR_ACS_TEXT    | text      | text        |
| Yes      | series tag     | cb_mxm_trfc_cntrl_flag | CB_MXM_TRFC_CNTRL_FLAG | text      | text        |
| Yes      | series tag     | cb_mxm_use_type        | CB_MXM_USE_TYPE        | text      | text        |
| Yes      | series tag     | cb_mxm_ovrlnd_flag     | CB_MXM_OVRLND_FLAG     | text      | text        |
| No       |                | cb_mxm_lst_mnt_date    | CB_MXM_LST_MNT_DATE    | text      | text        |
| Yes      | series tag     | cb_mxm_lst_mnt_wo_id   | CB_MXM_LST_MNT_WO_ID   | text      | text        |
| Yes      | series tag     | cb_mxm_lst_mnt_jpnum   | CB_MXM_LST_MNT_JPNUM   | text      | text        |
| Yes      | series tag     | cb_mxm_lst_mnt_clsfctn | CB_MXM_LST_MNT_CLSFCTN | text      | text        |
| Yes      | series tag     | cb_mxm_lst_mnt_stat    | CB_MXM_LST_MNT_STAT    | text      | text        |
```

## Time Field

```ls
Value = cb_lst_updt_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = cb_retire_date,cb_install_date,cb_mxm_lst_mnt_date
```

## Data Commands

```ls
series e:r7pf-fsen d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_cb_id=031-00147S t:cb_owner_name=Private t:cb_featype_text="Catch Basin" t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text="Topo 1999" t:cb_owner_code=PRI t:cb_map_area_id=031 t:cb_featype_code=CB t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=T t:cb_sym_num=17 t:objectid=1 m:cb_x_coord=1277723.57689 m:cb_rotation_nbr=141 m:cb_cvr_elev_ft_nbr=107 m:cb_y_coord=237241.69924 m:cb_fea_key=1000143

series e:r7pf-fsen d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_cb_id=031-00149S t:cb_owner_name=Private t:cb_featype_text="Catch Basin" t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text="Topo 1999" t:cb_owner_code=PRI t:cb_map_area_id=031 t:cb_featype_code=CB t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=T t:cb_sym_num=17 t:objectid=2 m:cb_x_coord=1277633.8878 m:cb_rotation_nbr=242 m:cb_cvr_elev_ft_nbr=105 m:cb_y_coord=237238.73809 m:cb_fea_key=1000244

series e:r7pf-fsen d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_owner_name=Private t:cb_featype_text="Catch Basin" t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text="Lidar 2003" t:cb_owner_code=PRI t:cb_map_area_id=031 t:cb_rec_wtrbdy_name="Lake Washington" t:cb_featype_code=CB t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=L t:cb_sym_num=69 t:objectid=3 m:cb_x_coord=1281032.69996 m:cb_rotation_nbr=0 m:cb_cvr_elev_ft_nbr=30.01 m:cb_y_coord=237220.49988 m:cb_fea_key=1000869
```

## Meta Commands

```ls
metric m:cb_fea_key p:integer l:CB_FEA_KEY d:FEA_KEY t:dataTypeName=number

metric m:cb_depth_ft_nbr p:double l:CB_DEPTH_FT_NBR d:DEPTH_FT t:dataTypeName=number

metric m:cb_cvr_elev_ft_nbr p:decimal l:CB_CVR_ELEV_FT_NBR d:CVR_ELEV_FT t:dataTypeName=number

metric m:cb_inc_inlet_nbr p:integer l:CB_INC_INLET_NBR d:INC_INLET t:dataTypeName=number

metric m:cb_rotation_nbr p:integer l:CB_ROTATION_NBR d:ROTATION t:dataTypeName=number

metric m:cb_x_coord p:decimal l:CB_X_COORD d:X_COORD t:dataTypeName=number

metric m:cb_y_coord p:decimal l:CB_Y_COORD d:Y_COORD t:dataTypeName=number

entity e:r7pf-fsen l:"DWW Catch Basins" t:url=https://data.seattle.gov/api/views/r7pf-fsen

property e:r7pf-fsen t:meta.view v:id=r7pf-fsen v:category="Land Base" v:averageRating=0 v:name="DWW Catch Basins"

property e:r7pf-fsen t:meta.view.license v:name="Public Domain"

property e:r7pf-fsen t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:r7pf-fsen t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | cb_fea_key | cb_eqnum_id | cb_s_endpt_id | cb_d_endpt_id | cb_npdes_id | cb_cb_id    | cb_map_area_id | cb_owner_code | cb_owner_name            | cb_featype_code | cb_featype_text          | cb_lifecycle_code | cb_lifecycle_stat | cb_depth_ref_code | cb_depth_ref_text | cb_cvr_elev_ref_code | cb_cvr_elev_ref_text | cb_role_code | cb_role_type       | cb_depth_ft_nbr | cb_cvr_elev_ft_nbr                                  | cb_inc_inlet_nbr | cb_rotation_nbr | cb_sym_num | cb_install_date | cb_retire_date | cb_lst_updt_date | cb_x_coord                               | cb_y_coord                                 | cb_rec_wtrbdy_name    | cb_mxm_mnt_agrmnt_text | cb_mxm_artrl_text | cb_mxm_adrs_text                      | cb_mxm_comments_text | cb_mxm_cncrt_flag | cb_mxm_dstrct_code | cb_mxm_lndsld_flag | cb_mxm_leaf_flag | cb_mxm_snw_ice_flag | cb_mxm_storm_flag | cb_mxm_grt_slt_flag | cb_mxm_grate_type | cb_mxm_inlet_250_flag | cb_mxm_material_type | cb_mxm_2crw_flag | cb_mxm_nprks_flag | cb_mxm_prkhd_flag | cb_mxm_swr_acs_text | cb_mxm_trfc_cntrl_flag | cb_mxm_use_type | cb_mxm_ovrlnd_flag | cb_mxm_lst_mnt_date | cb_mxm_lst_mnt_wo_id | cb_mxm_lst_mnt_jpnum | cb_mxm_lst_mnt_clsfctn          | cb_mxm_lst_mnt_stat | 
| ======== | ========== | =========== | ============= | ============= | =========== | =========== | ============== | ============= | ======================== | =============== | ======================== | ================= | ================= | ================= | ================= | ==================== | ==================== | ============ | ================== | =============== | =================================================== | ================ | =============== | ========== | =============== | ============== | ================ | ======================================== | ========================================== | ===================== | ====================== | ================= | ===================================== | ==================== | ================= | ================== | ================== | ================ | =================== | ================= | =================== | ================= | ===================== | ==================== | ================ | ================= | ================= | =================== | ====================== | =============== | ================== | =================== | ==================== | ==================== | =============================== | =================== | 
| 1        | 1000143    |             |               |               |             | 031-00147S  | 031            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 107                                                 |                  | 141             | 17         |                 |                | 1343347200       | 1277723.57688999990932643413543701171875 | 237241.699239999987185001373291015625      |                       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 2        | 1000244    |             |               |               |             | 031-00149S  | 031            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 105                                                 |                  | 242             | 17         |                 |                | 1343347200       | 1277633.88779999990947544574737548828125 | 237238.738089999998919665813446044921875   |                       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 3        | 1000869    |             |               |               |             |             | 031            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | L                    | Lidar 2003           | NONMAIN      | Non Mainline Point |                 | 30.010000000000001563194018672220408916473388671875 |                  | 0               | 69         |                 |                | 1343347200       | 1281032.69996000011451542377471923828125 | 237220.49987999998847953975200653076171875 | Lake Washington       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 4        | 1001132    | 787149      |               |               |             |             | 029            | SPU           | Seattle Public Utilities | CBL             | Catch Basin ? Grated Top | C                 | Connected         |                   |                   | L                    | Lidar 2003           | NONMAIN      | Non Mainline Point |                 | 30.699999999999999289457264239899814128875732421875 |                  | 0               | 0          |                 |                | 1463443200       | 1268459.50007999991066753864288330078125 | 237214.19996999998693354427814483642578125 | Lake Union/Ship Canal |                        |                   | W/S WESTLAKE AVE N 269'N OF MCGRAW ST |                      | N                 |                    | N                  | N                | N                   | N                 | Y                   |                   | N                     | CON                  | N                | N                 | N                 | ARTERIAL            | N                      | DRAIN           |                    | 20161214            | 7286725              | 2388                 | STRUCTURE CLEAN                 | COMP                | 
| 5        | 1001323    | 558402      |               |               |             | 027-00218NE | 027            | SPU           | Seattle Public Utilities | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 261                                                 |                  | 248             | 17         |                 |                | 1343347200       | 1255657.6443199999630451202392578125     | 237208.7927400000044144690036773681640625  | Puget Sound           |                        |                   | NEC 29TH AVE W/W MCGRAW ST            |                      | N                 |                    | N                  | N                | N                   | N                 | Y                   |                   | Y                     | CON                  | N                | N                 | N                 | ARTERIAL            | N                      | DRAIN           |                    | 20110407            | 2715849              | 2414                 | COVER INSP/INVEST/RESET/REPLACE | CLOSE               | 
| 6        | 100214     |             |               |               |             |             | 222            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         |                   |                   | L                    | Lidar 2003           | NONMAIN      | Non Mainline Point |                 | 118.43999999999999772626324556767940521240234375    |                  | 0               | 17         |                 |                | 1343347200       | 1283627.89996999991126358509063720703125 | 266976.6000099999946542084217071533203125  | Lake Washington       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 7        | 1002925    | 558433      |               |               |             | 026-00259S  | 026            | SPU           | Seattle Public Utilities | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 256                                                 |                  | 346             | 17         |                 |                | 1343347200       | 1252147.432479999959468841552734375      | 237159.844010000000707805156707763671875   | Puget Sound           |                        |                   | 2345 W VIEWMONT WAY W                 |                      | N                 |                    | N                  | N                | N                   | N                 | N                   |                   | N                     | CON                  | N                | N                 | N                 | ARTERIAL            | N                      | DRAIN           |                    | 20130822            | 3876523              | 2388                 | STRUCTURE CLEAN                 | CLOSE               | 
| 8        | 100300     |             |               |               |             |             | 221            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         |                   |                   | L                    | Lidar 2003           | NONMAIN      | Non Mainline Point |                 | 201.23000000000001818989403545856475830078125       |                  | 0               | 69         |                 |                | 1343347200       | 1280178.10003000008873641490936279296875 | 266967.9999400000087916851043701171875     | Lake Washington       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 9        | 1003237    |             |               |               |             |             | 030            | PRI           | Private                  | CB              | Catch Basin              | C                 | Connected         |                   |                   | L                    | Lidar 2003           | NONMAIN      | Non Mainline Point | 4.5             | 224.080000000000012505552149377763271331787109375   |                  | 0               | 69         |                 |                | 1343347200       | 1273658.599990000016987323760986328125   | 237151.4999400000087916851043701171875     |                       |                        |                   |                                       |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                                 |                     | 
| 10       | 1003564    | 558439      |               |               |             | 030-00206E  | 030            | SPU           | Seattle Public Utilities | CB              | Catch Basin              | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 36                                                  |                  | 225             | 17         |                 |                | 1343347200       | 1275770.7663900000043213367462158203125  | 237141.68593000000691972672939300537109375 | Lake Union/Ship Canal |                        |                   | 2350 BOYER AVE E                      |                      | N                 |                    | N                  | N                | N                   | N                 | Y                   |                   | N                     | CON                  | N                | N                 | N                 | ARTERIAL            | N                      | DRAIN           |                    | 20141002            | 4964433              | 2388                 | STRUCTURE CLEAN                 | CLOSE               | 
```