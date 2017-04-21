# SDOT Closed Bike Lanes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-closed-bike-lanes) |
| Metadata | [Link](https://data.seattle.gov/api/views/yn2a-j5d3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/yn2a-j5d3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/yn2a-j5d3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | yn2a-j5d3 |
| Name | SDOT Closed Bike Lanes |
| Tags | storm response |
| Created | 2016-12-09T19:25:55Z |
| Publication Date | 2016-12-14T17:50:17Z |

## Description

Displays all permits that have led or will lead to a closure of the bike lane on the given street segment.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type  | Render Type |
| ======== | ============== | ============================ | ============================ | ========== | =========== |
| Yes      | series tag     | objectid                     | OBJECTID                     | text       | number      |
| Yes      | series tag     | permit_aptype                | PERMIT_APTYPE                | text       | text        |
| Yes      | series tag     | permit_category              | PERMIT_CATEGORY              | text       | text        |
| Yes      | numeric metric | permit_no_num                | PERMIT_NO_NUM                | number     | text        |
| No       |                | permit_address_text          | PERMIT_ADDRESS_TEXT          | text       | text        |
| Yes      | series tag     | permit_stat                  | PERMIT_STAT                  | text       | text        |
| No       |                | permit_address_stno          | PERMIT_ADDRESS_STNO          | text       | text        |
| No       |                | permit_address_predir        | PERMIT_ADDRESS_PREDIR        | text       | text        |
| No       |                | permit_address_stname        | PERMIT_ADDRESS_STNAME        | text       | text        |
| No       |                | permit_address_suffix        | PERMIT_ADDRESS_SUFFIX        | text       | text        |
| No       |                | permit_address_postdir       | PERMIT_ADDRESS_POSTDIR       | text       | text        |
| No       |                | permit_address_stsub         | PERMIT_ADDRESS_STSUB         | text       | text        |
| Yes      | series tag     | applicant_name               | APPLICANT_NAME               | text       | text        |
| Yes      | series tag     | applicant_company_name       | APPLICANT_COMPANY_NAME       | text       | text        |
| Yes      | series tag     | applicant_phone_num          | APPLICANT_PHONE_NUM          | text       | text        |
| Yes      | series tag     | contact_24hour_name          | CONTACT_24HOUR_NAME          | text       | text        |
| Yes      | series tag     | contact_24hour_number        | CONTACT_24HOUR_NUMBER        | text       | text        |
| Yes      | series tag     | job_number_text              | JOB_NUMBER_TEXT              | text       | text        |
| Yes      | numeric metric | dpd_reference_num            | DPD_REFERENCE_NUM            | number     | text        |
| No       |                | address_key                  | ADDRESS_KEY                  | number     | number      |
| Yes      | numeric metric | segkey                       | SEGKEY                       | number     | number      |
| Yes      | series tag     | permit_stage_name            | PERMIT_STAGE_NAME            | text       | text        |
| Yes      | series tag     | permit_insptn_district_name  | PERMIT_INSPTN_DISTRICT_NAME  | text       | text        |
| Yes      | series tag     | permit_inspector_name        | PERMIT_INSPECTOR_NAME        | text       | text        |
| Yes      | series tag     | permit_inspector_phone_num   | PERMIT_INSPECTOR_PHONE_NUM   | text       | text        |
| Yes      | series tag     | permit_location_text         | PERMIT_LOCATION_TEXT         | text       | text        |
| Yes      | time           | permit_application_date      | PERMIT_APPLICATION_DATE      | date       | date        |
| Yes      | series tag     | impact_data_format           | IMPACT_DATA_FORMAT           | text       | text        |
| Yes      | series tag     | hub                          | HUB                          | text       | text        |
| Yes      | series tag     | primarydistrictcd            | PRIMARYDISTRICTCD            | text       | text        |
| Yes      | series tag     | secondarydistrictcd          | SECONDARYDISTRICTCD          | text       | text        |
| Yes      | series tag     | overrideyn                   | OVERRIDEYN                   | text       | text        |
| Yes      | series tag     | overridecomment              | OVERRIDECOMMENT              | text       | text        |
| Yes      | series tag     | urban_village                | URBAN_VILLAGE                | text       | text        |
| Yes      | series tag     | high_impact_area             | HIGH_IMPACT_AREA             | text       | text        |
| Yes      | series tag     | strt_closed_flag             | STRT_CLOSED_FLAG             | text       | text        |
| No       |                | strt_close_start_dt          | STRT_CLOSE_START_DT          | date       | date        |
| No       |                | strt_close_end_dt            | STRT_CLOSE_END_DT            | date       | date        |
| Yes      | series tag     | strt_part_closed_flag        | STRT_PART_CLOSED_FLAG        | text       | text        |
| No       |                | strt_part_close_start_dt     | STRT_PART_CLOSE_START_DT     | date       | date        |
| No       |                | strt_part_close_end_dt       | STRT_PART_CLOSE_END_DT       | date       | date        |
| Yes      | series tag     | strt_intrmt_closed_flag      | STRT_INTRMT_CLOSED_FLAG      | text       | text        |
| No       |                | strt_intrmt_close_start_dt   | STRT_INTRMT_CLOSE_START_DT   | date       | date        |
| No       |                | strt_intrmt_close_end_dt     | STRT_INTRMT_CLOSE_END_DT     | date       | date        |
| Yes      | series tag     | strt_reroute_flag            | STRT_REROUTE_FLAG            | text       | text        |
| No       |                | strt_reroute_start_dt        | STRT_REROUTE_START_DT        | date       | date        |
| No       |                | strt_reroute_end_dt          | STRT_REROUTE_END_DT          | date       | date        |
| Yes      | series tag     | sdwlk_closed_flag            | SDWLK_CLOSED_FLAG            | text       | text        |
| No       |                | sdwlk_close_start_dt         | SDWLK_CLOSE_START_DT         | date       | date        |
| No       |                | sdwlk_close_end_dt           | SDWLK_CLOSE_END_DT           | date       | date        |
| Yes      | series tag     | sdwlk_part_closed_flag       | SDWLK_PART_CLOSED_FLAG       | text       | text        |
| No       |                | sdwlk_part_close_start_dt    | SDWLK_PART_CLOSE_START_DT    | date       | date        |
| No       |                | sdwlk_part_cls_end_dt        | SDWLK_PART_CLS_END_DT        | date       | date        |
| Yes      | series tag     | sdwlk_intrmt_closed_flag     | SDWLK_INTRMT_CLOSED_FLAG     | text       | text        |
| No       |                | sdwlk_intrmt_close_strt_dt   | SDWLK_INTRMT_CLOSE_STRT_DT   | date       | date        |
| No       |                | sdwlk_intrmt_close_end_dt    | SDWLK_INTRMT_CLOSE_END_DT    | date       | date        |
| Yes      | series tag     | sdwlk_reroute_flag           | SDWLK_REROUTE_FLAG           | text       | text        |
| No       |                | sdwlk_reroute_start_dt       | SDWLK_REROUTE_START_DT       | date       | date        |
| No       |                | sdwlk_reroute_end_dt         | SDWLK_REROUTE_END_DT         | date       | date        |
| Yes      | series tag     | prkln_closed_flag            | PRKLN_CLOSED_FLAG            | text       | text        |
| No       |                | prkln_close_start_dt         | PRKLN_CLOSE_START_DT         | date       | date        |
| No       |                | prkln_close_end_dt           | PRKLN_CLOSE_END_DT           | date       | date        |
| Yes      | series tag     | prkln_part_clsd_flag         | PRKLN_PART_CLSD_FLAG         | text       | text        |
| No       |                | prkln_part_cls_start_dt      | PRKLN_PART_CLS_START_DT      | date       | date        |
| No       |                | prkln_part_cls_end_dt        | PRKLN_PART_CLS_END_DT        | date       | date        |
| Yes      | series tag     | prkln_intrmt_clsd_flag       | PRKLN_INTRMT_CLSD_FLAG       | text       | text        |
| No       |                | prkln_intrmt_cls_strt_dt     | PRKLN_INTRMT_CLS_STRT_DT     | date       | date        |
| No       |                | prkln_intrmt_cls_end_dt      | PRKLN_INTRMT_CLS_END_DT      | date       | date        |
| Yes      | series tag     | prkln_reroute_flag           | PRKLN_REROUTE_FLAG           | text       | text        |
| No       |                | prkln_reroute_start_dt       | PRKLN_REROUTE_START_DT       | date       | date        |
| No       |                | prkln_reroute_end_dt         | PRKLN_REROUTE_END_DT         | date       | date        |
| Yes      | series tag     | alley_closed_flag            | ALLEY_CLOSED_FLAG            | text       | text        |
| No       |                | alley_close_start_dt         | ALLEY_CLOSE_START_DT         | date       | date        |
| No       |                | alley_close_end_dt           | ALLEY_CLOSE_END_DT           | date       | date        |
| Yes      | series tag     | alley_part_closed_flag       | ALLEY_PART_CLOSED_FLAG       | text       | text        |
| No       |                | alley_part_close_start_dt    | ALLEY_PART_CLOSE_START_DT    | date       | date        |
| No       |                | alley_part_close_end_dt      | ALLEY_PART_CLOSE_END_DT      | date       | date        |
| Yes      | series tag     | alley_intrmt_closed_flag     | ALLEY_INTRMT_CLOSED_FLAG     | text       | text        |
| No       |                | alley_intrmt_close_start_dt  | ALLEY_INTRMT_CLOSE_START_DT  | date       | date        |
| No       |                | alley_intrmt_close_end_dt    | ALLEY_INTRMT_CLOSE_END_DT    | date       | date        |
| Yes      | series tag     | alley_reroute_flag           | ALLEY_REROUTE_FLAG           | text       | text        |
| No       |                | alley_reroute_start_dt       | ALLEY_REROUTE_START_DT       | date       | date        |
| No       |                | alley_reroute_end_dt         | ALLEY_REROUTE_END_DT         | date       | date        |
| Yes      | series tag     | trvl_lane_closed_flag        | TRVL_LANE_CLOSED_FLAG        | text       | text        |
| No       |                | trvl_lane_start_dt           | TRVL_LANE_START_DT           | date       | date        |
| No       |                | trvl_lane_end_dt             | TRVL_LANE_END_DT             | date       | date        |
| Yes      | series tag     | trvl_lane_part_clsd_flag     | TRVL_LANE_PART_CLSD_FLAG     | text       | text        |
| No       |                | trvl_lane_part_cls_strt_dt   | TRVL_LANE_PART_CLS_STRT_DT   | date       | date        |
| No       |                | trvl_lane_part_cls_end_dt    | TRVL_LANE_PART_CLS_END_DT    | date       | date        |
| Yes      | series tag     | trvl_lane_intrmt_clsd_flag   | TRVL_LANE_INTRMT_CLSD_FLAG   | text       | text        |
| No       |                | trvl_lane_intrmt_cls_strt_dt | TRVL_LANE_INTRMT_CLS_STRT_DT | date       | date        |
| No       |                | trvl_lane_intrmt_cls_end_dt  | TRVL_LANE_INTRMT_CLS_END_DT  | date       | date        |
| Yes      | series tag     | trvl_lane_reroute_flag       | TRVL_LANE_REROUTE_FLAG       | text       | text        |
| No       |                | trvl_lane_reroute_start_dt   | TRVL_LANE_REROUTE_START_DT   | date       | date        |
| No       |                | trvl_lane_reroute_end_dt     | TRVL_LANE_REROUTE_END_DT     | date       | date        |
| Yes      | series tag     | bike_lane_closed_flag        | BIKE_LANE_CLOSED_FLAG        | text       | text        |
| No       |                | bike_lane_start_dt           | BIKE_LANE_START_DT           | date       | date        |
| No       |                | bike_lane_end_dt             | BIKE_LANE_END_DT             | date       | date        |
| Yes      | series tag     | bike_lane_part_clsd_flag     | BIKE_LANE_PART_CLSD_FLAG     | text       | text        |
| No       |                | bike_lane_part_cls_strt_dt   | BIKE_LANE_PART_CLS_STRT_DT   | date       | date        |
| No       |                | bike_lane_part_cls_end_dt    | BIKE_LANE_PART_CLS_END_DT    | date       | date        |
| Yes      | series tag     | bike_lane_intrmt_clsd_flag   | BIKE_LANE_INTRMT_CLSD_FLAG   | text       | text        |
| No       |                | bike_lane_intrmt_cls_strt_dt | BIKE_LANE_INTRMT_CLS_STRT_DT | date       | date        |
| No       |                | bike_lane_intrmt_cls_end_dt  | BIKE_LANE_INTRMT_CLS_END_DT  | date       | date        |
| Yes      | series tag     | bike_lane_reroute_flag       | BIKE_LANE_REROUTE_FLAG       | text       | text        |
| No       |                | bike_lane_reroute_start_dt   | BIKE_LANE_REROUTE_START_DT   | date       | date        |
| No       |                | bike_lane_reroute_end_dt     | BIKE_LANE_REROUTE_END_DT     | date       | date        |
| Yes      | series tag     | filler_closed_flag           | FILLER_CLOSED_FLAG           | text       | text        |
| No       |                | filler_start_dt              | FILLER_START_DT              | date       | date        |
| No       |                | filler_end_dt                | FILLER_END_DT                | date       | date        |
| Yes      | series tag     | filler_part_closed_flag      | FILLER_PART_CLOSED_FLAG      | text       | text        |
| No       |                | filler_part_close_start_dt   | FILLER_PART_CLOSE_START_DT   | date       | date        |
| No       |                | filler_part_close_end_dt     | FILLER_PART_CLOSE_END_DT     | date       | date        |
| Yes      | series tag     | filler_intrmt_clsd_flag      | FILLER_INTRMT_CLSD_FLAG      | text       | text        |
| No       |                | filler_intrmt_cls_strt_dt    | FILLER_INTRMT_CLS_STRT_DT    | date       | date        |
| No       |                | filler_intrmt_cls_end_dt     | FILLER_INTRMT_CLS_END_DT     | date       | date        |
| Yes      | series tag     | filler_reroute_flag          | FILLER_REROUTE_FLAG          | text       | text        |
| No       |                | filler_reroute_start_dt      | FILLER_REROUTE_START_DT      | date       | date        |
| No       |                | filler_reroute_end_dt        | FILLER_REROUTE_END_DT        | date       | date        |
| Yes      | series tag     | unimp_row_closed_flag        | UNIMP_ROW_CLOSED_FLAG        | text       | text        |
| No       |                | unimp_row_start_dt           | UNIMP_ROW_START_DT           | date       | date        |
| No       |                | unimp_row_end_dt             | UNIMP_ROW_END_DT             | date       | date        |
| Yes      | series tag     | unimp_row_part_clsd_flag     | UNIMP_ROW_PART_CLSD_FLAG     | text       | text        |
| No       |                | unimp_row_part_cls_strt_dt   | UNIMP_ROW_PART_CLS_STRT_DT   | date       | date        |
| No       |                | unimp_row_part_cls_end_dt    | UNIMP_ROW_PART_CLS_END_DT    | date       | date        |
| Yes      | series tag     | unimp_row_intrmt_clsd_flag   | UNIMP_ROW_INTRMT_CLSD_FLAG   | text       | text        |
| No       |                | unimp_row_intrmt_cls_strt_dt | UNIMP_ROW_INTRMT_CLS_STRT_DT | date       | date        |
| No       |                | unimp_row_intrmt_cls_end_dt  | UNIMP_ROW_INTRMT_CLS_END_DT  | date       | date        |
| Yes      | series tag     | unimp_row_reroute_flag       | UNIMP_ROW_REROUTE_FLAG       | text       | text        |
| No       |                | unimp_row_reroute_start_dt   | UNIMP_ROW_REROUTE_START_DT   | date       | date        |
| No       |                | unimp_row_reroute_end_dt     | UNIMP_ROW_REROUTE_END_DT     | date       | date        |
| Yes      | series tag     | intersect_closed_flag        | INTERSECT_CLOSED_FLAG        | text       | text        |
| No       |                | intersect_start_dt           | INTERSECT_START_DT           | date       | date        |
| No       |                | intersect_end_dt             | INTERSECT_END_DT             | date       | date        |
| Yes      | series tag     | intersect_part_closed_flag   | INTERSECT_PART_CLOSED_FLAG   | text       | text        |
| No       |                | intersect_part_close_strt_dt | INTERSECT_PART_CLOSE_STRT_DT | date       | date        |
| No       |                | intersect_part_close_end_dt  | INTERSECT_PART_CLOSE_END_DT  | date       | date        |
| Yes      | series tag     | intersect_intrmt_clsd_flag   | INTERSECT_INTRMT_CLSD_FLAG   | text       | text        |
| No       |                | intersect_intrmt_cls_strt_dt | INTERSECT_INTRMT_CLS_STRT_DT | date       | date        |
| No       |                | intersect_intrmt_cls_end_dt  | INTERSECT_INTRMT_CLS_END_DT  | date       | date        |
| Yes      | series tag     | intersect_reroute_flag       | INTERSECT_REROUTE_FLAG       | text       | text        |
| No       |                | intersect_reroute_start_dt   | INTERSECT_REROUTE_START_DT   | date       | date        |
| No       |                | intersect_reroute_end_dt     | INTERSECT_REROUTE_END_DT     | date       | date        |
| Yes      | series tag     | plntstrp_closed_flag         | PLNTSTRP_CLOSED_FLAG         | text       | text        |
| No       |                | plntstrp_start_dt            | PLNTSTRP_START_DT            | date       | date        |
| No       |                | plntstrp_end_dt              | PLNTSTRP_END_DT              | date       | date        |
| Yes      | series tag     | plntstrp_part_clsd_flag      | PLNTSTRP_PART_CLSD_FLAG      | text       | text        |
| No       |                | plntstrp_part_cls_start_dt   | PLNTSTRP_PART_CLS_START_DT   | date       | date        |
| No       |                | plntstrp_part_cls_end_dt     | PLNTSTRP_PART_CLS_END_DT     | date       | date        |
| Yes      | series tag     | plntstrp_intrmt_clsd_flag    | PLNTSTRP_INTRMT_CLSD_FLAG    | text       | text        |
| No       |                | plntstrp_intrmt_cls_strt_dt  | PLNTSTRP_INTRMT_CLS_STRT_DT  | date       | date        |
| No       |                | plntstrp_intrmt_cls_end_dt   | PLNTSTRP_INTRMT_CLS_END_DT   | date       | date        |
| Yes      | series tag     | plntstrp_reroute_flag        | PLNTSTRP_REROUTE_FLAG        | text       | text        |
| No       |                | plntstrp_reroute_start_dt    | PLNTSTRP_REROUTE_START_DT    | date       | date        |
| No       |                | plntstrp_reroute_end_dt      | PLNTSTRP_REROUTE_END_DT      | date       | date        |
| Yes      | series tag     | am_peak_hour_ok_flag         | AM_PEAK_HOUR_OK_FLAG         | text       | text        |
| Yes      | series tag     | pm_peak_hour_ok_flag         | PM_PEAK_HOUR_OK_FLAG         | text       | text        |
| Yes      | series tag     | night_weekend_only_flag      | NIGHT_WEEKEND_ONLY_FLAG      | text       | text        |
| Yes      | series tag     | planned_project_text         | PLANNED_PROJECT_TEXT         | text       | text        |
| Yes      | series tag     | construction_waiver_text     | CONSTRUCTION_WAIVER_TEXT     | text       | text        |
| Yes      | series tag     | review_desc                  | REVIEW_DESC                  | text       | text        |
| No       |                | review_action_date           | REVIEW_ACTION_DATE           | date       | date        |
| Yes      | series tag     | review_status                | REVIEW_STATUS                | text       | text        |
| Yes      | series tag     | reviewer_name                | REVIEWER_NAME                | text       | text        |
| Yes      | series tag     | tcp_roll30_flag              | TCP_ROLL30_FLAG              | text       | text        |
| Yes      | series tag     | use_roll30_flag              | USE_ROLL30_FLAG              | text       | text        |
| No       |                | shape                        | SHAPE                        | geospatial | geospatial  |
| Yes      | numeric metric | shape_len                    | SHAPE.LEN                    | number     | number      |
| Yes      | series tag     | use_code                     | USE_CODE                     | text       | text        |
| Yes      | series tag     | use_space_code               | USE_SPACE_CODE               | text       | text        |
| Yes      | series tag     | use_desc                     | USE_DESC                     | text       | text        |
| No       |                | use_start_date               | USE_START_DATE               | date       | date        |
| No       |                | use_exp_date                 | USE_EXP_DATE                 | date       | date        |
| Yes      | numeric metric | use_sqft_nbr                 | USE_SQFT_NBR                 | number     | number      |
| Yes      | series tag     | use_mobility_impact_desc     | USE_MOBILITY_IMPACT_DESC     | text       | text        |
| Yes      | numeric metric | permit_key                   | PERMIT_KEY                   | number     | number      |
| Yes      | series tag     | restore_by                   | RESTORE_BY                   | text       | text        |
```

## Time Field

```ls
Value = permit_application_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = permit_address_text,permit_address_stno,permit_address_predir,permit_address_stname,permit_address_suffix,permit_address_postdir,permit_address_stsub,address_key,strt_close_start_dt,strt_close_end_dt,strt_part_close_start_dt,strt_part_close_end_dt,strt_intrmt_close_start_dt,strt_intrmt_close_end_dt,strt_reroute_start_dt,strt_reroute_end_dt,sdwlk_close_start_dt,sdwlk_close_end_dt,sdwlk_part_close_start_dt,sdwlk_part_cls_end_dt,sdwlk_intrmt_close_strt_dt,sdwlk_intrmt_close_end_dt,sdwlk_reroute_start_dt,sdwlk_reroute_end_dt,prkln_close_start_dt,prkln_close_end_dt,prkln_part_cls_start_dt,prkln_part_cls_end_dt,prkln_intrmt_cls_strt_dt,prkln_intrmt_cls_end_dt,prkln_reroute_start_dt,prkln_reroute_end_dt,alley_close_start_dt,alley_close_end_dt,alley_part_close_start_dt,alley_part_close_end_dt,alley_intrmt_close_start_dt,alley_intrmt_close_end_dt,alley_reroute_start_dt,alley_reroute_end_dt,trvl_lane_start_dt,trvl_lane_end_dt,trvl_lane_part_cls_strt_dt,trvl_lane_part_cls_end_dt,trvl_lane_intrmt_cls_strt_dt,trvl_lane_intrmt_cls_end_dt,trvl_lane_reroute_start_dt,trvl_lane_reroute_end_dt,bike_lane_start_dt,bike_lane_end_dt,bike_lane_part_cls_strt_dt,bike_lane_part_cls_end_dt,bike_lane_intrmt_cls_strt_dt,bike_lane_intrmt_cls_end_dt,bike_lane_reroute_start_dt,bike_lane_reroute_end_dt,filler_start_dt,filler_end_dt,filler_part_close_start_dt,filler_part_close_end_dt,filler_intrmt_cls_strt_dt,filler_intrmt_cls_end_dt,filler_reroute_start_dt,filler_reroute_end_dt,unimp_row_start_dt,unimp_row_end_dt,unimp_row_part_cls_strt_dt,unimp_row_part_cls_end_dt,unimp_row_intrmt_cls_strt_dt,unimp_row_intrmt_cls_end_dt,unimp_row_reroute_start_dt,unimp_row_reroute_end_dt,intersect_start_dt,intersect_end_dt,intersect_part_close_strt_dt,intersect_part_close_end_dt,intersect_intrmt_cls_strt_dt,intersect_intrmt_cls_end_dt,intersect_reroute_start_dt,intersect_reroute_end_dt,plntstrp_start_dt,plntstrp_end_dt,plntstrp_part_cls_start_dt,plntstrp_part_cls_end_dt,plntstrp_intrmt_cls_strt_dt,plntstrp_intrmt_cls_end_dt,plntstrp_reroute_start_dt,plntstrp_reroute_end_dt,review_action_date,shape,use_start_date,use_exp_date
```

## Data Commands

```ls
series e:yn2a-j5d3 d:2016-10-06T14:03:43.000Z t:shape.longitude=-122.38213355999994 t:planned_project_text=N/A t:job_number_text="WO 1508336" t:high_impact_area=N t:permit_location_text="1 POLE WEST SIDE OF 20TH AVE NW, 30' NORTH OF NW 57TH ST; 1 POLE ON SOUTH SIDE OF NW 57TH ST, 12' WEST OF 20TH AVE NW." t:contact_24hour_name="NORTH SEATTLE CITY LIGHT" t:contact_24hour_number="(206)615-0646 x" t:hub=None t:restore_by=PERMITTEE t:applicant_name="NORTH SEATTLE CITY LIGHT" t:use_roll30_flag=Y t:permit_stage_name="License Issued" t:bike_lane_part_clsd_flag=Y t:shape.needs_recoding=false t:permit_aptype="ST ROWMGMT" t:shape.latitude=47.670180102000074 t:use_desc="51B-UTIL, ST LIGHT POLE WORK" t:strt_closed_flag=N t:applicant_company_name="SEATTLE CITY LIGHT-NORTH" t:urban_village=Ballard t:permit_category=SIGNIF t:permit_inspector_name="Kirk Calkins" t:permit_insptn_district_name=BALLARD t:impact_data_format=NEW t:applicant_phone_num="(206)615-0646 x" t:construction_waiver_text="NOT APPLICABLE" t:permit_stat=Issued t:use_code=51B t:tcp_roll30_flag=Y t:primarydistrictcd=DISTRICT6 t:overrideyn=N t:objectid=272405 t:use_space_code=F m:segkey=3020 m:permit_no_num=324411 m:use_sqft_nbr=40 m:permit_key=324410

series e:yn2a-j5d3 d:2017-02-22T14:13:04.000Z t:shape.longitude=-122.29624649099998 t:planned_project_text=N/A t:job_number_text="SDCI PERMIT #6582290" t:high_impact_area=N t:permit_location_text="ON E SIDE OF ML KING JR WAY B/T E COLUMBIA ST AND E MARION ST +/- 150' N OF C/L OF E COLUMBIA ST" t:contact_24hour_name="JIM CUNNINGHAM" t:contact_24hour_number="(206)472-7979 x" t:hub=None t:restore_by=PERMITTEE t:applicant_name="JIM CUNNINGHAM" t:use_roll30_flag=Y t:permit_stage_name="License Issued" t:bike_lane_part_clsd_flag=Y t:shape.needs_recoding=false t:permit_aptype="ST ROWMGMT" t:shape.latitude=47.609006899000065 t:use_desc="51F-SEWER/STORM SRVCS-ISSD BY DPD" t:strt_closed_flag=N t:applicant_company_name="TRUSTED PLUMBING & HEATING LLC" t:permit_category=SIGNIF t:permit_inspector_name="Salim Mayberry" t:permit_insptn_district_name="EAST CAPITOL HILL" t:impact_data_format=NEW t:applicant_phone_num="(206)472-7979 x" t:permit_inspector_phone_num="(206) 615-1256" t:construction_waiver_text="NOT APPLICABLE" t:permit_stat=Issued t:use_code=51F t:tcp_roll30_flag=Y t:primarydistrictcd=DISTRICT3 t:overrideyn=N t:objectid=282009 t:use_space_code=G m:segkey=11487 m:permit_no_num=337398 m:use_sqft_nbr=0 m:permit_key=337397

series e:yn2a-j5d3 d:2016-10-06T14:03:43.000Z t:shape.longitude=-122.38212667299996 t:planned_project_text=N/A t:job_number_text="WO 1508336" t:high_impact_area=N t:permit_location_text="1 POLE WEST SIDE OF 20TH AVE NW, 30' NORTH OF NW 57TH ST; 1 POLE ON SOUTH SIDE OF NW 57TH ST, 12' WEST OF 20TH AVE NW." t:contact_24hour_name="NORTH SEATTLE CITY LIGHT" t:contact_24hour_number="(206)615-0646 x" t:hub=None t:restore_by=PERMITTEE t:applicant_name="NORTH SEATTLE CITY LIGHT" t:use_roll30_flag=Y t:permit_stage_name="License Issued" t:bike_lane_part_clsd_flag=Y t:shape.needs_recoding=false t:permit_aptype="ST ROWMGMT" t:shape.latitude=47.669446651000044 t:use_desc="51B-UTIL, ST LIGHT POLE WORK" t:strt_closed_flag=N t:applicant_company_name="SEATTLE CITY LIGHT-NORTH" t:urban_village=Ballard t:permit_category=SIGNIF t:permit_inspector_name="Kirk Calkins" t:permit_insptn_district_name=BALLARD t:impact_data_format=NEW t:applicant_phone_num="(206)615-0646 x" t:construction_waiver_text="NOT APPLICABLE" t:permit_stat=Issued t:use_code=51B t:tcp_roll30_flag=Y t:primarydistrictcd=DISTRICT6 t:overrideyn=N t:objectid=299350 t:use_space_code=C m:segkey=3019 m:permit_no_num=324411 m:use_sqft_nbr=40 m:permit_key=324410
```

## Meta Commands

```ls
metric m:permit_no_num p:integer l:PERMIT_NO_NUM d:PERMIT_NO_NUM t:dataTypeName=number

metric m:dpd_reference_num p:integer l:DPD_REFERENCE_NUM d:DPD_REFERENCE_NUM t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:SHAPE.LEN t:dataTypeName=number

metric m:use_sqft_nbr p:integer l:USE_SQFT_NBR d:USE_SQFT_NBR t:dataTypeName=number

metric m:permit_key p:integer l:PERMIT_KEY d:PERMIT_KEY t:dataTypeName=number

entity e:yn2a-j5d3 l:"SDOT Closed Bike Lanes" t:url=https://data.seattle.gov/api/views/yn2a-j5d3

property e:yn2a-j5d3 t:meta.view v:id=yn2a-j5d3 v:averageRating=0 v:name="SDOT Closed Bike Lanes"

property e:yn2a-j5d3 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:yn2a-j5d3 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | permit_aptype | permit_category | permit_no_num | permit_address_text | permit_stat | permit_address_stno | permit_address_predir | permit_address_stname | permit_address_suffix | permit_address_postdir | permit_address_stsub | applicant_name           | applicant_company_name         | applicant_phone_num | contact_24hour_name      | contact_24hour_number | job_number_text      | dpd_reference_num | address_key | segkey | permit_stage_name | permit_insptn_district_name | permit_inspector_name | permit_inspector_phone_num | permit_location_text                                                                                                   | permit_application_date | impact_data_format | hub  | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | urban_village | high_impact_area | strt_closed_flag | strt_close_start_dt | strt_close_end_dt | strt_part_closed_flag | strt_part_close_start_dt | strt_part_close_end_dt | strt_intrmt_closed_flag | strt_intrmt_close_start_dt | strt_intrmt_close_end_dt | strt_reroute_flag | strt_reroute_start_dt | strt_reroute_end_dt | sdwlk_closed_flag | sdwlk_close_start_dt | sdwlk_close_end_dt | sdwlk_part_closed_flag | sdwlk_part_close_start_dt | sdwlk_part_cls_end_dt | sdwlk_intrmt_closed_flag | sdwlk_intrmt_close_strt_dt | sdwlk_intrmt_close_end_dt | sdwlk_reroute_flag | sdwlk_reroute_start_dt | sdwlk_reroute_end_dt | prkln_closed_flag | prkln_close_start_dt | prkln_close_end_dt | prkln_part_clsd_flag | prkln_part_cls_start_dt | prkln_part_cls_end_dt | prkln_intrmt_clsd_flag | prkln_intrmt_cls_strt_dt | prkln_intrmt_cls_end_dt | prkln_reroute_flag | prkln_reroute_start_dt | prkln_reroute_end_dt | alley_closed_flag | alley_close_start_dt | alley_close_end_dt | alley_part_closed_flag | alley_part_close_start_dt | alley_part_close_end_dt | alley_intrmt_closed_flag | alley_intrmt_close_start_dt | alley_intrmt_close_end_dt | alley_reroute_flag | alley_reroute_start_dt | alley_reroute_end_dt | trvl_lane_closed_flag | trvl_lane_start_dt | trvl_lane_end_dt | trvl_lane_part_clsd_flag | trvl_lane_part_cls_strt_dt | trvl_lane_part_cls_end_dt | trvl_lane_intrmt_clsd_flag | trvl_lane_intrmt_cls_strt_dt | trvl_lane_intrmt_cls_end_dt | trvl_lane_reroute_flag | trvl_lane_reroute_start_dt | trvl_lane_reroute_end_dt | bike_lane_closed_flag | bike_lane_start_dt | bike_lane_end_dt | bike_lane_part_clsd_flag | bike_lane_part_cls_strt_dt | bike_lane_part_cls_end_dt | bike_lane_intrmt_clsd_flag | bike_lane_intrmt_cls_strt_dt | bike_lane_intrmt_cls_end_dt | bike_lane_reroute_flag | bike_lane_reroute_start_dt | bike_lane_reroute_end_dt | filler_closed_flag | filler_start_dt | filler_end_dt | filler_part_closed_flag | filler_part_close_start_dt | filler_part_close_end_dt | filler_intrmt_clsd_flag | filler_intrmt_cls_strt_dt | filler_intrmt_cls_end_dt | filler_reroute_flag | filler_reroute_start_dt | filler_reroute_end_dt | unimp_row_closed_flag | unimp_row_start_dt | unimp_row_end_dt | unimp_row_part_clsd_flag | unimp_row_part_cls_strt_dt | unimp_row_part_cls_end_dt | unimp_row_intrmt_clsd_flag | unimp_row_intrmt_cls_strt_dt | unimp_row_intrmt_cls_end_dt | unimp_row_reroute_flag | unimp_row_reroute_start_dt | unimp_row_reroute_end_dt | intersect_closed_flag | intersect_start_dt | intersect_end_dt | intersect_part_closed_flag | intersect_part_close_strt_dt | intersect_part_close_end_dt | intersect_intrmt_clsd_flag | intersect_intrmt_cls_strt_dt | intersect_intrmt_cls_end_dt | intersect_reroute_flag | intersect_reroute_start_dt | intersect_reroute_end_dt | plntstrp_closed_flag | plntstrp_start_dt | plntstrp_end_dt | plntstrp_part_clsd_flag | plntstrp_part_cls_start_dt | plntstrp_part_cls_end_dt | plntstrp_intrmt_clsd_flag | plntstrp_intrmt_cls_strt_dt | plntstrp_intrmt_cls_end_dt | plntstrp_reroute_flag | plntstrp_reroute_start_dt | plntstrp_reroute_end_dt | am_peak_hour_ok_flag | pm_peak_hour_ok_flag | night_weekend_only_flag | planned_project_text | construction_waiver_text | review_desc | review_action_date | review_status | reviewer_name | tcp_roll30_flag | use_roll30_flag | shape                                                                                                                                                          | shape_len | use_code | use_space_code | use_desc                          | use_start_date | use_exp_date | use_sqft_nbr | use_mobility_impact_desc | permit_key | restore_by | 
| ======== | ============= | =============== | ============= | =================== | =========== | =================== | ===================== | ===================== | ===================== | ====================== | ==================== | ======================== | ============================== | =================== | ======================== | ===================== | ==================== | ================= | =========== | ====== | ================= | =========================== | ===================== | ========================== | ====================================================================================================================== | ======================= | ================== | ==== | ================= | =================== | ========== | =============== | ============= | ================ | ================ | =================== | ================= | ===================== | ======================== | ====================== | ======================= | ========================== | ======================== | ================= | ===================== | =================== | ================= | ==================== | ================== | ====================== | ========================= | ===================== | ======================== | ========================== | ========================= | ================== | ====================== | ==================== | ================= | ==================== | ================== | ==================== | ======================= | ===================== | ====================== | ======================== | ======================= | ================== | ====================== | ==================== | ================= | ==================== | ================== | ====================== | ========================= | ======================= | ======================== | =========================== | ========================= | ================== | ====================== | ==================== | ===================== | ================== | ================ | ======================== | ========================== | ========================= | ========================== | ============================ | =========================== | ====================== | ========================== | ======================== | ===================== | ================== | ================ | ======================== | ========================== | ========================= | ========================== | ============================ | =========================== | ====================== | ========================== | ======================== | ================== | =============== | ============= | ======================= | ========================== | ======================== | ======================= | ========================= | ======================== | =================== | ======================= | ===================== | ===================== | ================== | ================ | ======================== | ========================== | ========================= | ========================== | ============================ | =========================== | ====================== | ========================== | ======================== | ===================== | ================== | ================ | ========================== | ============================ | =========================== | ========================== | ============================ | =========================== | ====================== | ========================== | ======================== | ==================== | ================= | =============== | ======================= | ========================== | ======================== | ========================= | =========================== | ========================== | ===================== | ========================= | ======================= | ==================== | ==================== | ======================= | ==================== | ======================== | =========== | ================== | ============= | ============= | =============== | =============== | ============================================================================================================================================================== | ========= | ======== | ============== | ================================= | ============== | ============ | ============ | ======================== | ========== | ========== | 
| 272405   | ST ROWMGMT    | SIGNIF          | 324411        | 2003 NW 57TH ST     | Issued      | 2003                | NW                    | 57TH                  | ST                    |                        |                      | NORTH SEATTLE CITY LIGHT | SEATTLE CITY LIGHT-NORTH       | (206)615-0646 x     | NORTH SEATTLE CITY LIGHT | (206)615-0646 x       | WO 1508336           |                   | 44878       | 3020   | License Issued    | BALLARD                     | Kirk Calkins          |                            | 1 POLE WEST SIDE OF 20TH AVE NW, 30' NORTH OF NW 57TH ST; 1 POLE ON SOUTH SIDE OF NW 57TH ST, 12' WEST OF 20TH AVE NW. | 1475762623              | NEW                | None | DISTRICT6         |                     | N          |                 | Ballard       | N                | N                |                     |                   |                       |                          |                        |                         |                            |                          |                   |                       |                     |                   |                      |                    |                        |                           |                       |                          |                            |                           |                    |                        |                      |                   |                      |                    |                      |                         |                       |                        |                          |                         |                    |                        |                      |                   |                      |                    |                        |                           |                         |                          |                             |                           |                    |                        |                      |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  | Y                        | 1486684800                 | 1494460800                |                            |                              |                             |                        |                            |                          |                    |                 |               |                         |                            |                          |                         |                           |                          |                     |                         |                       |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  |                            |                              |                             |                            |                              |                             |                        |                            |                          |                      |                   |                 |                         |                            |                          |                           |                             |                            |                       |                           |                         |                      |                      |                         | N/A                  | NOT APPLICABLE           |             |                    |               |               | Y               | Y               | [null, 47.670180102000074, -122.38213355999994, null, false, {paths=[[[-122.38213355999994, 47.670180102000074], [-122.38212445999994, 47.67090898600003]]]}]  |           | 51B      | F              | 51B-UTIL, ST LIGHT POLE WORK      | 1486684800     | 1494460800   | 40           |                          | 324410     | PERMITTEE  | 
| 282009   | ST ROWMGMT    | SIGNIF          | 337398        | 810 M L KING JR WAY | Issued      | 810                 |                       | M L KING JR           | WAY                   |                        |                      | JIM CUNNINGHAM           | TRUSTED PLUMBING & HEATING LLC | (206)472-7979 x     | JIM CUNNINGHAM           | (206)472-7979 x       | SDCI PERMIT #6582290 |                   | 137247      | 11487  | License Issued    | EAST CAPITOL HILL           | Salim Mayberry        | (206) 615-1256             | ON E SIDE OF ML KING JR WAY B/T E COLUMBIA ST AND E MARION ST +/- 150' N OF C/L OF E COLUMBIA ST                       | 1487772784              | NEW                | None | DISTRICT3         |                     | N          |                 |               | N                | N                |                     |                   |                       |                          |                        |                         |                            |                          |                   |                       |                     |                   |                      |                    |                        |                           |                       |                          |                            |                           |                    |                        |                      |                   |                      |                    |                      |                         |                       |                        |                          |                         |                    |                        |                      |                   |                      |                    |                        |                           |                         |                          |                             |                           |                    |                        |                      |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  | Y                        | 1487635200                 | 1534291200                |                            |                              |                             |                        |                            |                          |                    |                 |               |                         |                            |                          |                         |                           |                          |                     |                         |                       |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  |                            |                              |                             |                            |                              |                             |                        |                            |                          |                      |                   |                 |                         |                            |                          |                           |                             |                            |                       |                           |                         |                      |                      |                         | N/A                  | NOT APPLICABLE           |             |                    |               |               | Y               | Y               | [null, 47.609006899000065, -122.29624649099998, null, false, {paths=[[[-122.29624649099998, 47.609006899000065], [-122.29623107299994, 47.61001041600008]]]}]  |           | 51F      | G              | 51F-SEWER/STORM SRVCS-ISSD BY DPD | 1487635200     | 1534291200   | 0            |                          | 337397     | PERMITTEE  | 
| 299350   | ST ROWMGMT    | SIGNIF          | 324411        | 2003 NW 57TH ST     | Issued      | 2003                | NW                    | 57TH                  | ST                    |                        |                      | NORTH SEATTLE CITY LIGHT | SEATTLE CITY LIGHT-NORTH       | (206)615-0646 x     | NORTH SEATTLE CITY LIGHT | (206)615-0646 x       | WO 1508336           |                   | 44878       | 3019   | License Issued    | BALLARD                     | Kirk Calkins          |                            | 1 POLE WEST SIDE OF 20TH AVE NW, 30' NORTH OF NW 57TH ST; 1 POLE ON SOUTH SIDE OF NW 57TH ST, 12' WEST OF 20TH AVE NW. | 1475762623              | NEW                | None | DISTRICT6         |                     | N          |                 | Ballard       | N                | N                |                     |                   |                       |                          |                        |                         |                            |                          |                   |                       |                     |                   |                      |                    |                        |                           |                       |                          |                            |                           |                    |                        |                      |                   |                      |                    |                      |                         |                       |                        |                          |                         |                    |                        |                      |                   |                      |                    |                        |                           |                         |                          |                             |                           |                    |                        |                      |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  | Y                        | 1486684800                 | 1494460800                |                            |                              |                             |                        |                            |                          |                    |                 |               |                         |                            |                          |                         |                           |                          |                     |                         |                       |                       |                    |                  |                          |                            |                           |                            |                              |                             |                        |                            |                          |                       |                    |                  |                            |                              |                             |                            |                              |                             |                        |                            |                          |                      |                   |                 |                         |                            |                          |                           |                             |                            |                       |                           |                         |                      |                      |                         | N/A                  | NOT APPLICABLE           |             |                    |               |               | Y               | Y               | [null, 47.669446651000044, -122.38212667299996, null, false, {paths=[[[-122.38212667299996, 47.669446651000044], [-122.38213355999994, 47.670180102000074]]]}] |           | 51B      | C              | 51B-UTIL, ST LIGHT POLE WORK      | 1486684800     | 1494460800   | 40           |                          | 324410     | PERMITTEE  | 
```