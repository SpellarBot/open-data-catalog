# DWW Inlets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dww-inlets-35afd) |
| Metadata | [Link](https://data.seattle.gov/api/views/ejn9-f8zr) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ejn9-f8zr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ejn9-f8zr/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ejn9-f8zr |
| Name | DWW Inlets |
| Category | Land Base |
| Tags | dww, drainage, waste water, spu, inlets |
| Created | 2014-07-14T21:10:29Z |
| Publication Date | 2014-07-14T21:17:05Z |

## Description

https://gisrevprxy.seattle.gov/ArcGIS/rest/services/ext/WM_CityGISLayers/MapServer/60

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
| Yes      | numeric metric | cb_mxm_lst_mnt_jpnum   | CB_MXM_LST_MNT_JPNUM   | number    | text        |
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
series e:ejn9-f8zr d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_owner_name="Seattle Public Utilities" t:cb_featype_text=Inlet t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text=Unknown t:cb_owner_code=SPU t:cb_map_area_id=027 t:cb_rec_wtrbdy_name="Puget Sound" t:cb_featype_code=INL t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=UNK t:cb_sym_num=0 t:objectid=1 m:cb_x_coord=1255299.28093 m:cb_rotation_nbr=0 m:cb_cvr_elev_ft_nbr=210.29 m:cb_y_coord=237243.50097 m:cb_fea_key=1000093

series e:ejn9-f8zr d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_owner_name="Seattle Public Utilities" t:cb_featype_text=Inlet t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text=Unknown t:cb_owner_code=SPU t:cb_map_area_id=027 t:cb_rec_wtrbdy_name="Puget Sound" t:cb_featype_code=INL t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=UNK t:cb_sym_num=0 t:objectid=2 m:cb_x_coord=1255923.2433 m:cb_rotation_nbr=0 m:cb_cvr_elev_ft_nbr=290 m:cb_y_coord=237224.08644 m:cb_fea_key=1000780

series e:ejn9-f8zr d:2012-07-27T00:00:00.000Z t:cb_role_type="Non Mainline Point" t:cb_lifecycle_code=C t:cb_owner_name="Seattle Public Utilities" t:cb_featype_text=Inlet t:cb_lifecycle_stat=Connected t:cb_cvr_elev_ref_text=Unknown t:cb_owner_code=SPU t:cb_map_area_id=026 t:cb_rec_wtrbdy_name="Puget Sound" t:cb_featype_code=INL t:cb_depth_ref_text=Unknown t:cb_depth_ref_code=UNK t:cb_role_code=NONMAIN t:cb_cvr_elev_ref_code=UNK t:cb_sym_num=0 t:objectid=3 m:cb_x_coord=1254272.62493 m:cb_rotation_nbr=0 m:cb_cvr_elev_ft_nbr=159.66 m:cb_y_coord=237198.14058 m:cb_fea_key=1001673
```

## Meta Commands

```ls
metric m:cb_fea_key p:long l:CB_FEA_KEY d:FEA_KEY t:dataTypeName=number

metric m:cb_depth_ft_nbr p:decimal l:CB_DEPTH_FT_NBR d:DEPTH_FT t:dataTypeName=number

metric m:cb_cvr_elev_ft_nbr p:double l:CB_CVR_ELEV_FT_NBR d:CVR_ELEV_FT t:dataTypeName=number

metric m:cb_inc_inlet_nbr p:long l:CB_INC_INLET_NBR d:INC_INLET t:dataTypeName=number

metric m:cb_rotation_nbr p:integer l:CB_ROTATION_NBR d:ROTATION t:dataTypeName=number

metric m:cb_x_coord p:long l:CB_X_COORD d:X_COORD t:dataTypeName=number

metric m:cb_y_coord p:long l:CB_Y_COORD d:Y_COORD t:dataTypeName=number

metric m:cb_mxm_lst_mnt_jpnum p:integer l:CB_MXM_LST_MNT_JPNUM d:MXM_LAST_WO_JPNUM t:dataTypeName=number

entity e:ejn9-f8zr l:"DWW Inlets" t:url=https://data.seattle.gov/api/views/ejn9-f8zr

property e:ejn9-f8zr t:meta.view v:id=ejn9-f8zr v:category="Land Base" v:averageRating=0 v:name="DWW Inlets"

property e:ejn9-f8zr t:meta.view.license v:name="Public Domain"

property e:ejn9-f8zr t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:ejn9-f8zr t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | cb_fea_key | cb_eqnum_id | cb_s_endpt_id | cb_d_endpt_id | cb_npdes_id | cb_cb_id | cb_map_area_id | cb_owner_code | cb_owner_name            | cb_featype_code | cb_featype_text | cb_lifecycle_code | cb_lifecycle_stat | cb_depth_ref_code | cb_depth_ref_text | cb_cvr_elev_ref_code | cb_cvr_elev_ref_text | cb_role_code | cb_role_type       | cb_depth_ft_nbr | cb_cvr_elev_ft_nbr                                | cb_inc_inlet_nbr | cb_rotation_nbr | cb_sym_num | cb_install_date | cb_retire_date | cb_lst_updt_date | cb_x_coord                               | cb_y_coord                                 | cb_rec_wtrbdy_name | cb_mxm_mnt_agrmnt_text | cb_mxm_artrl_text | cb_mxm_adrs_text | cb_mxm_comments_text | cb_mxm_cncrt_flag | cb_mxm_dstrct_code | cb_mxm_lndsld_flag | cb_mxm_leaf_flag | cb_mxm_snw_ice_flag | cb_mxm_storm_flag | cb_mxm_grt_slt_flag | cb_mxm_grate_type | cb_mxm_inlet_250_flag | cb_mxm_material_type | cb_mxm_2crw_flag | cb_mxm_nprks_flag | cb_mxm_prkhd_flag | cb_mxm_swr_acs_text | cb_mxm_trfc_cntrl_flag | cb_mxm_use_type | cb_mxm_ovrlnd_flag | cb_mxm_lst_mnt_date | cb_mxm_lst_mnt_wo_id | cb_mxm_lst_mnt_jpnum | cb_mxm_lst_mnt_clsfctn | cb_mxm_lst_mnt_stat | 
| ======== | ========== | =========== | ============= | ============= | =========== | ======== | ============== | ============= | ======================== | =============== | =============== | ================= | ================= | ================= | ================= | ==================== | ==================== | ============ | ================== | =============== | ================================================= | ================ | =============== | ========== | =============== | ============== | ================ | ======================================== | ========================================== | ================== | ====================== | ================= | ================ | ==================== | ================= | ================== | ================== | ================ | =================== | ================= | =================== | ================= | ===================== | ==================== | ================ | ================= | ================= | =================== | ====================== | =============== | ================== | =================== | ==================== | ==================== | ====================== | =================== | 
| 1        | 1000093    |             |               |               |             |          | 027            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 210.289999999999992041921359486877918243408203125 |                  | 0               | 0          |                 |                | 1343347200       | 1255299.2809299998916685581207275390625  | 237243.5009699999936856329441070556640625  | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 2        | 1000780    |             |               |               |             |          | 027            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 290                                               |                  | 0               | 0          |                 |                | 1343347200       | 1255923.24329999997280538082122802734375 | 237224.08644000001368112862110137939453125 | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 3        | 1001673    |             |               |               |             |          | 026            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 159.659999999999996589394868351519107818603515625 |                  | 0               | 0          |                 |                | 1343347200       | 1254272.62492999993264675140380859375    | 237198.140580000006593763828277587890625   | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 4        | 1001818    |             |               |               |             |          | 026            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 153.270000000000010231815394945442676544189453125 |                  | 0               | 0          |                 |                | 1343347200       | 1254540.53098000003956258296966552734375 | 237193.13015000001178123056888580322265625 | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 5        | 1001984    |             |               |               |             |          | 027            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 153.479999999999989768184605054557323455810546875 |                  | 0               | 0          |                 |                | 1343347200       | 1254662.79631999996490776538848876953125 | 237188.8142499999958090484142303466796875  | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 6        | 1002118    |             |               |               |             |          | 027            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 208.93000000000000682121026329696178436279296875  |                  | 0               | 0          |                 |                | 1343347200       | 1255315.5919699999503791332244873046875  | 237185.40304999999352730810642242431640625 | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 7        | 1002894    |             |               |               |             |          | 032            | PRI           | Private                  | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | T                    | Topo 1999            | NONMAIN      | Non Mainline Point |                 | 39                                                |                  | 114             | 31         |                 |                | 1343347200       | 1282287.16729000001214444637298583984375 | 237160.45303000000421889126300811767578125 | Lake Washington    |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 8        | 1003734    |             |               |               |             |          | 026            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 179.710000000000007958078640513122081756591796875 |                  | 0               | 0          |                 |                | 1343347200       | 1253923.374880000017583370208740234375   | 237136.95324999999138526618480682373046875 | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 9        | 1005136    |             |               |               |             |          | 029            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 0                                                 |                  | 0               | 0          |                 |                | 1343347200       | 1265755.43018999998457729816436767578125 | 237100.85956000001169741153717041015625    |                    |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
| 10       | 1005564    |             |               |               |             |          | 026            | SPU           | Seattle Public Utilities | INL             | Inlet           | C                 | Connected         | UNK               | Unknown           | UNK                  | Unknown              | NONMAIN      | Non Mainline Point |                 | 158.5                                             |                  | 0               | 0          |                 |                | 1343347200       | 1254281.89263999997638165950775146484375 | 237088.7927400000044144690036773681640625  | Puget Sound        |                        |                   |                  |                      |                   |                    |                    |                  |                     |                   |                     |                   |                       |                      |                  |                   |                   |                     |                        |                 |                    |                     |                      |                      |                        |                     | 
```