# Derelict Vehicle Dispositions - Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/derelict-vehicle-dispositions-vehicles) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bjuu-44hx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bjuu-44hx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bjuu-44hx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bjuu-44hx |
| Name | Derelict Vehicle Dispositions - Vehicles |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Created | 2015-05-22T20:26:01Z |
| Publication Date | 2017-03-08T23:05:16Z |
| Rows Updated | 2017-03-08T23:05:12Z |

## Description

Data for removing derelict vehicle operations from city streets, Gives disposition (complaints) of derelict vehicles reported to DSNY from 311.

https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Tow/vr8p-8shw
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Complaints/pq5i-thsu
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Rentals/v6j6-k9uc

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | isn                 | ISN                 | text      | number      |
| Yes      | series tag     | dvv_yard_resp       | DVV_YARD_RESP       | text      | text        |
| Yes      | series tag     | dvv_district_cd     | DVV_DISTRICT_CD     | text      | text        |
| Yes      | series tag     | dvv_orig_yard       | DVV_ORIG_YARD       | text      | text        |
| Yes      | numeric metric | dvv_464_upd_cnt     | DVV_464_UPD_CNT     | number    | number      |
| Yes      | series tag     | dvv_tag_loc1        | DVV_TAG_LOC1        | text      | text        |
| Yes      | series tag     | dvv_tag_loc2        | DVV_TAG_LOC2        | text      | text        |
| Yes      | series tag     | dvv_year            | DVV_YEAR            | text      | number      |
| Yes      | series tag     | dvv_make            | DVV_MAKE            | text      | text        |
| Yes      | series tag     | dvv_type            | DVV_TYPE            | text      | text        |
| Yes      | series tag     | dvv_color           | DVV_COLOR           | text      | text        |
| Yes      | series tag     | dvv_tag_remarks     | DVV_TAG_REMARKS     | text      | text        |
| Yes      | series tag     | dvv_tag_no          | DVV_TAG_NO          | text      | number      |
| Yes      | numeric metric | dvv_tag_date        | DVV_TAG_DATE        | number    | number      |
| Yes      | numeric metric | dvv_tag_time        | DVV_TAG_TIME        | number    | number      |
| Yes      | numeric metric | dvv_prev_463        | DVV_PREV_463        | number    | number      |
| Yes      | time           | dvv_timestmp        | DVV_TIMESTMP        | number    | number      |
| Yes      | series tag     | dvv_filler3         | DVV_FILLER3         | text      | text        |
| Yes      | numeric metric | dvv_filler4         | DVV_FILLER4         | number    | number      |
| Yes      | series tag     | dvv_print_flag      | DVV_PRINT_FLAG      | text      | text        |
| Yes      | numeric metric | dvv_checked_date    | DVV_CHECKED_DATE    | number    | number      |
| Yes      | numeric metric | dvv_timestmp_upd    | DVV_TIMESTMP_UPD    | number    | number      |
| Yes      | numeric metric | dvv_final_disp_date | DVV_FINAL_DISP_DATE | number    | number      |
| Yes      | series tag     | dvv_final_disp_cd   | DVV_FINAL_DISP_CD   | text      | text        |
| Yes      | series tag     | dvv_464_make        | DVV_464_MAKE        | text      | text        |
| Yes      | series tag     | dvv_464_type        | DVV_464_TYPE        | text      | text        |
| Yes      | series tag     | dvv_464_color       | DVV_464_COLOR       | text      | text        |
| Yes      | series tag     | dvv_907_no          | DVV_907_NO          | text      | text        |
| Yes      | series tag     | dvv_hold_no         | DVV_HOLD_NO         | text      | text        |
| Yes      | series tag     | dvv_filler5         | DVV_FILLER5         | text      | text        |
| Yes      | numeric metric | dvv_filler6         | DVV_FILLER6         | number    | number      |
| Yes      | series tag     | dvv_se_status       | DVV_SE_STATUS       | text      | text        |
| Yes      | series tag     | dvv_over48_ind      | DVV_OVER48_IND      | text      | text        |
| Yes      | series tag     | dvv_chrge_48        | DVV_CHRGE_48        | text      | text        |
| Yes      | series tag     | dvv_challenge_48    | DVV_CHALLENGE_48    | text      | text        |
| Yes      | series tag     | dvv_hq_approve      | DVV_HQ_APPROVE      | text      | text        |
| No       |                | dvv_vin_timestmp    | DVV_VIN_TIMESTMP    | number    | number      |
| Yes      | series tag     | dvv_rental_find     | DVV_RENTAL_FIND     | text      | text        |
| Yes      | series tag     | dvv_rental_indic    | DVV_RENTAL_INDIC    | text      | text        |
| Yes      | series tag     | dvv_city            | DVV_CITY            | text      | text        |
| Yes      | series tag     | dvv_state           | DVV_STATE           | text      | text        |
| Yes      | series tag     | dvv_stolen_indic    | DVV_STOLEN_INDIC    | text      | text        |
| Yes      | series tag     | dvv_lor_indic       | DVV_LOR_INDIC       | text      | text        |
| Yes      | numeric metric | dvv_dot             | DVV_DOT             | number    | number      |
| Yes      | numeric metric | dvv_kdvo_cnt        | DVV_KDVO_CNT        | number    | number      |
| No       |                | dvv_nicb_timestmp   | DVV_NICB_TIMESTMP   | number    | number      |
| Yes      | numeric metric | dvv_summons         | DVV_SUMMONS         | number    | number      |
| Yes      | numeric metric | dvv_yd_sub_contr    | DVV_YD_SUB_CONTR    | number    | text        |
| Yes      | series tag     | dvv_last_upd_opid   | DVV_LAST_UPD_OPID   | text      | text        |
| Yes      | numeric metric | dvv_rotow_tagno     | DVV_ROTOW_TAGNO     | number    | number      |
| Yes      | series tag     | dvv_acc_logno       | DVV_ACC_LOGNO       | text      | text        |
```

## Time Field

```ls
Value = dvv_timestmp
Format & Zone = yyyyMMddHHmmss
```

## Series Fields

```ls
Excluded Fields = dvv_vin_timestmp,dvv_nicb_timestmp
```

## Data Commands

```ls
series e:bjuu-44hx d:1989-11-17T16:26:34.000Z t:dvv_print_flag=F t:dvv_464_color=BLACK t:dvv_tag_remarks="EMERGENCY TOW" t:isn=1 t:dvv_tag_loc1="AVENUE P & E 4TH ST" t:dvv_color=BLACK t:dvv_464_make=VOLVO t:dvv_type=4D t:dvv_final_disp_cd=NOL t:dvv_make=VOLVO t:dvv_district_cd=TRN01 t:dvv_yard_resp=DVO999 t:dvv_tag_no=1 t:dvv_464_type=4D m:dvv_tag_time=900 m:dvv_tag_date=19891117 m:dvv_final_disp_date=19891117 m:dvv_timestmp_upd=19970606070052

series e:bjuu-44hx d:1989-11-20T11:33:36.000Z t:dvv_print_flag=F t:dvv_464_color=BURNT t:dvv_tag_loc2="IFO DUNKIN DONUTS" t:dvv_tag_remarks="NORTH SIDE OF STREET" t:isn=2 t:dvv_tag_loc1="WOODSIDE/61ST ST" t:dvv_color=BURNT t:dvv_464_make=DATSUN t:dvv_type=2D t:dvv_final_disp_cd=AAA t:dvv_make=DATSUN t:dvv_district_cd=TRN01 t:dvv_yard_resp=DVO999 t:dvv_tag_no=2 t:dvv_464_type=2D m:dvv_tag_time=900 m:dvv_tag_date=19891119 m:dvv_final_disp_date=99999999 m:dvv_timestmp_upd=19900711055802

series e:bjuu-44hx d:1989-11-20T10:38:27.000Z t:dvv_print_flag=F t:dvv_464_color=GREEN t:dvv_tag_loc2=STREET t:isn=3 t:dvv_tag_loc1=LOCATION t:dvv_color=GREEN t:dvv_464_make=OLDS t:dvv_type=SW t:dvv_final_disp_cd=RTC t:dvv_make=OLDS t:dvv_district_cd=TRN01 t:dvv_yard_resp=DVO999 t:dvv_tag_no=5 t:dvv_464_type=SW m:dvv_tag_time=900 m:dvv_tag_date=19891120 m:dvv_final_disp_date=19891120 m:dvv_checked_date=19891120
```

## Meta Commands

```ls
metric m:dvv_464_upd_cnt p:integer l:DVV_464_UPD_CNT t:dataTypeName=number

metric m:dvv_tag_date p:integer l:DVV_TAG_DATE t:dataTypeName=number

metric m:dvv_tag_time p:integer l:DVV_TAG_TIME t:dataTypeName=number

metric m:dvv_prev_463 p:integer l:DVV_PREV_463 t:dataTypeName=number

metric m:dvv_filler4 p:long l:DVV_FILLER4 t:dataTypeName=number

metric m:dvv_checked_date p:integer l:DVV_CHECKED_DATE t:dataTypeName=number

metric m:dvv_timestmp_upd p:long l:DVV_TIMESTMP_UPD t:dataTypeName=number

metric m:dvv_final_disp_date p:integer l:DVV_FINAL_DISP_DATE t:dataTypeName=number

metric m:dvv_filler6 p:long l:DVV_FILLER6 t:dataTypeName=number

metric m:dvv_dot p:integer l:DVV_DOT t:dataTypeName=number

metric m:dvv_kdvo_cnt p:integer l:DVV_KDVO_CNT t:dataTypeName=number

metric m:dvv_summons p:integer l:DVV_SUMMONS t:dataTypeName=number

metric m:dvv_yd_sub_contr p:integer l:DVV_YD_SUB_CONTR t:dataTypeName=number

metric m:dvv_rotow_tagno p:integer l:DVV_ROTOW_TAGNO t:dataTypeName=number

entity e:bjuu-44hx l:"Derelict Vehicle Dispositions - Vehicles" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/bjuu-44hx

property e:bjuu-44hx t:meta.view v:id=bjuu-44hx v:category="City Government" v:averageRating=0 v:name="Derelict Vehicle Dispositions - Vehicles" v:attribution="Department of Sanitation (DSNY)"

property e:bjuu-44hx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:bjuu-44hx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```