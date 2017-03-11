# Derelict Vehicle Dispositions - Vehicles

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/bjuu-44hx/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/derelict-vehicle-dispositions-vehicles)
* Id = bjuu-44hx
* Name = Derelict Vehicle Dispositions - Vehicles
* Attribution = Department of Sanitation (DSNY)
* Category = City Government
* Created = 2015-05-22T20:26:01Z
* Publication Date = 2017-02-08T22:38:03Z
* Rows Updated = 2017-02-08T22:37:59Z

## Description

Data for removing derelict vehicle operations from city streets, Gives disposition (complaints) of derelict vehicles reported to DSNY from 311.

https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Tow/vr8p-8shw
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Complaints/pq5i-thsu
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Rentals/v6j6-k9uc

## Columns

```ls
| Name                | Field Name          | Data Type | Render Type | Schema Type    | Included | 
| =================== | =================== | ========= | =========== | ============== | ======== | 
| ISN                 | isn                 | number    | number      | numeric metric | Yes      | 
| DVV_YARD_RESP       | dvv_yard_resp       | text      | text        | series tag     | Yes      | 
| DVV_DISTRICT_CD     | dvv_district_cd     | text      | text        | series tag     | Yes      | 
| DVV_ORIG_YARD       | dvv_orig_yard       | text      | text        | series tag     | Yes      | 
| DVV_464_UPD_CNT     | dvv_464_upd_cnt     | number    | number      | numeric metric | Yes      | 
| DVV_TAG_LOC1        | dvv_tag_loc1        | text      | text        | series tag     | Yes      | 
| DVV_TAG_LOC2        | dvv_tag_loc2        | text      | text        | series tag     | Yes      | 
| DVV_YEAR            | dvv_year            | number    | number      | time           | Yes      | 
| DVV_MAKE            | dvv_make            | text      | text        | series tag     | Yes      | 
| DVV_TYPE            | dvv_type            | text      | text        | series tag     | Yes      | 
| DVV_COLOR           | dvv_color           | text      | text        | series tag     | Yes      | 
| DVV_TAG_REMARKS     | dvv_tag_remarks     | text      | text        | series tag     | Yes      | 
| DVV_TAG_NO          | dvv_tag_no          | number    | number      | numeric metric | Yes      | 
| DVV_TAG_DATE        | dvv_tag_date        | number    | number      | numeric metric | Yes      | 
| DVV_TAG_TIME        | dvv_tag_time        | number    | number      | numeric metric | Yes      | 
| DVV_PREV_463        | dvv_prev_463        | number    | number      | numeric metric | Yes      | 
| DVV_TIMESTMP        | dvv_timestmp        | number    | number      | numeric metric | Yes      | 
| DVV_FILLER3         | dvv_filler3         | text      | text        | series tag     | Yes      | 
| DVV_FILLER4         | dvv_filler4         | number    | number      | numeric metric | Yes      | 
| DVV_PRINT_FLAG      | dvv_print_flag      | number    | text        | numeric metric | Yes      | 
| DVV_CHECKED_DATE    | dvv_checked_date    | number    | number      | numeric metric | Yes      | 
| DVV_TIMESTMP_UPD    | dvv_timestmp_upd    | number    | number      | numeric metric | Yes      | 
| DVV_FINAL_DISP_DATE | dvv_final_disp_date | number    | number      | numeric metric | Yes      | 
| DVV_FINAL_DISP_CD   | dvv_final_disp_cd   | text      | text        | series tag     | Yes      | 
| DVV_464_MAKE        | dvv_464_make        | text      | text        | series tag     | Yes      | 
| DVV_464_TYPE        | dvv_464_type        | text      | text        | series tag     | Yes      | 
| DVV_464_COLOR       | dvv_464_color       | text      | text        | series tag     | Yes      | 
| DVV_907_NO          | dvv_907_no          | text      | text        | series tag     | Yes      | 
| DVV_HOLD_NO         | dvv_hold_no         | text      | text        | series tag     | Yes      | 
| DVV_FILLER5         | dvv_filler5         | text      | text        | series tag     | Yes      | 
| DVV_FILLER6         | dvv_filler6         | number    | number      | numeric metric | Yes      | 
| DVV_SE_STATUS       | dvv_se_status       | number    | text        | numeric metric | Yes      | 
| DVV_OVER48_IND      | dvv_over48_ind      | number    | text        | numeric metric | Yes      | 
| DVV_CHRGE_48        | dvv_chrge_48        | number    | text        | numeric metric | Yes      | 
| DVV_CHALLENGE_48    | dvv_challenge_48    | number    | text        | numeric metric | Yes      | 
| DVV_HQ_APPROVE      | dvv_hq_approve      | number    | text        | numeric metric | Yes      | 
| DVV_VIN_TIMESTMP    | dvv_vin_timestmp    | number    | number      | numeric metric | Yes      | 
| DVV_RENTAL_FIND     | dvv_rental_find     | number    | text        | numeric metric | Yes      | 
| DVV_RENTAL_INDIC    | dvv_rental_indic    | number    | text        | numeric metric | Yes      | 
| DVV_CITY            | dvv_city            | text      | text        | series tag     | Yes      | 
| DVV_STATE           | dvv_state           | text      | text        | series tag     | Yes      | 
| DVV_STOLEN_INDIC    | dvv_stolen_indic    | number    | text        | numeric metric | Yes      | 
| DVV_LOR_INDIC       | dvv_lor_indic       | number    | text        | numeric metric | Yes      | 
| DVV_DOT             | dvv_dot             | number    | number      | numeric metric | Yes      | 
| DVV_KDVO_CNT        | dvv_kdvo_cnt        | number    | number      | numeric metric | Yes      | 
| DVV_NICB_TIMESTMP   | dvv_nicb_timestmp   | number    | number      | numeric metric | Yes      | 
| DVV_SUMMONS         | dvv_summons         | number    | number      | numeric metric | Yes      | 
| DVV_YD_SUB_CONTR    | dvv_yd_sub_contr    | number    | text        | numeric metric | Yes      | 
| DVV_LAST_UPD_OPID   | dvv_last_upd_opid   | text      | text        | series tag     | Yes      | 
| DVV_ROTOW_TAGNO     | dvv_rotow_tagno     | number    | number      | numeric metric | Yes      | 
| DVV_ACC_LOGNO       | dvv_acc_logno       | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = dvv_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:bjuu-44hx d:2017-03-03T14:01:20.036Z t:dvv_print_flag=F t:dvv_type=4D t:dvv_464_color=BLACK t:dvv_final_disp_cd=NOL t:dvv_tag_remarks="EMERGENCY TOW" t:dvv_tag_loc1="AVENUE P & E 4TH ST" t:dvv_make=VOLVO t:dvv_district_cd=TRN01 t:dvv_color=BLACK t:dvv_464_make=VOLVO t:dvv_yard_resp=DVO999 t:dvv_464_type=4D m:dvv_tag_time=900 m:dvv_timestmp=19891117162634 m:isn=1 m:dvv_tag_date=19891117 m:dvv_final_disp_date=19891117 m:dvv_timestmp_upd=19970606070052 m:dvv_tag_no=1

series e:bjuu-44hx d:2017-03-03T14:01:20.036Z t:dvv_print_flag=F t:dvv_464_color=BURNT t:dvv_tag_loc2="IFO DUNKIN DONUTS" t:dvv_tag_remarks="NORTH SIDE OF STREET" t:dvv_tag_loc1="WOODSIDE/61ST ST" t:dvv_color=BURNT t:dvv_464_make=DATSUN t:dvv_type=2D t:dvv_final_disp_cd=AAA t:dvv_make=DATSUN t:dvv_district_cd=TRN01 t:dvv_yard_resp=DVO999 t:dvv_464_type=2D m:dvv_tag_time=900 m:dvv_timestmp=19891120113336 m:isn=2 m:dvv_tag_date=19891119 m:dvv_final_disp_date=99999999 m:dvv_timestmp_upd=19900711055802 m:dvv_tag_no=2

series e:bjuu-44hx d:2017-03-03T14:01:20.036Z t:dvv_print_flag=F t:dvv_type=SW t:dvv_464_color=GREEN t:dvv_tag_loc2=STREET t:dvv_final_disp_cd=RTC t:dvv_tag_loc1=LOCATION t:dvv_make=OLDS t:dvv_district_cd=TRN01 t:dvv_color=GREEN t:dvv_464_make=OLDS t:dvv_yard_resp=DVO999 t:dvv_464_type=SW m:dvv_tag_time=900 m:dvv_timestmp=19891120103827 m:isn=3 m:dvv_tag_date=19891120 m:dvv_final_disp_date=19891120 m:dvv_checked_date=19891120 m:dvv_tag_no=5
```

## Meta Commands

```ls
metric m:isn p:integer l:ISN t:dataTypeName=number

metric m:dvv_464_upd_cnt p:integer l:DVV_464_UPD_CNT t:dataTypeName=number

metric m:dvv_tag_no p:integer l:DVV_TAG_NO t:dataTypeName=number

metric m:dvv_tag_date p:integer l:DVV_TAG_DATE t:dataTypeName=number

metric m:dvv_tag_time p:integer l:DVV_TAG_TIME t:dataTypeName=number

metric m:dvv_prev_463 p:integer l:DVV_PREV_463 t:dataTypeName=number

metric m:dvv_timestmp p:long l:DVV_TIMESTMP t:dataTypeName=number

metric m:dvv_filler4 l:DVV_FILLER4 t:dataTypeName=number

metric m:dvv_checked_date p:integer l:DVV_CHECKED_DATE t:dataTypeName=number

metric m:dvv_timestmp_upd p:long l:DVV_TIMESTMP_UPD t:dataTypeName=number

metric m:dvv_final_disp_date p:integer l:DVV_FINAL_DISP_DATE t:dataTypeName=number

metric m:dvv_filler6 l:DVV_FILLER6 t:dataTypeName=number

metric m:dvv_vin_timestmp p:long l:DVV_VIN_TIMESTMP t:dataTypeName=number

metric m:dvv_rental_find l:DVV_RENTAL_FIND t:dataTypeName=number

metric m:dvv_rental_indic l:DVV_RENTAL_INDIC t:dataTypeName=number

metric m:dvv_dot p:integer l:DVV_DOT t:dataTypeName=number

metric m:dvv_kdvo_cnt p:integer l:DVV_KDVO_CNT t:dataTypeName=number

metric m:dvv_nicb_timestmp p:long l:DVV_NICB_TIMESTMP t:dataTypeName=number

metric m:dvv_summons l:DVV_SUMMONS t:dataTypeName=number

metric m:dvv_yd_sub_contr p:integer l:DVV_YD_SUB_CONTR t:dataTypeName=number

metric m:dvv_rotow_tagno p:integer l:DVV_ROTOW_TAGNO t:dataTypeName=number

entity e:bjuu-44hx l:"Derelict Vehicle Dispositions - Vehicles" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/bjuu-44hx

property e:bjuu-44hx t:meta.view d:2017-03-03T14:01:20.036Z v:id=bjuu-44hx v:category="City Government" v:averageRating=0 v:name="Derelict Vehicle Dispositions - Vehicles" v:attribution="Department of Sanitation (DSNY)"

property e:bjuu-44hx t:meta.view.owner d:2017-03-03T14:01:20.036Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:bjuu-44hx t:meta.view.tableauthor d:2017-03-03T14:01:20.036Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```