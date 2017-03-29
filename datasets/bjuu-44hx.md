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
| No       |                | dvv_tag_date        | DVV_TAG_DATE        | text      | number      |
| No       |                | dvv_tag_time        | DVV_TAG_TIME        | number    | number      |
| Yes      | numeric metric | dvv_prev_463        | DVV_PREV_463        | number    | number      |
| Yes      | time           | dvv_timestmp        | DVV_TIMESTMP        | number    | number      |
| Yes      | series tag     | dvv_filler3         | DVV_FILLER3         | text      | text        |
| Yes      | numeric metric | dvv_filler4         | DVV_FILLER4         | number    | number      |
| Yes      | series tag     | dvv_print_flag      | DVV_PRINT_FLAG      | text      | text        |
| No       |                | dvv_checked_date    | DVV_CHECKED_DATE    | text      | number      |
| No       |                | dvv_timestmp_upd    | DVV_TIMESTMP_UPD    | number    | number      |
| No       |                | dvv_final_disp_date | DVV_FINAL_DISP_DATE | text      | number      |
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
Excluded Fields = dvv_tag_time,dvv_checked_date,dvv_timestmp_upd,dvv_final_disp_date,dvv_vin_timestmp,dvv_nicb_timestmp,dvv_tag_date
```

## Data Commands

```ls
series e:bjuu-44hx d:1997-07-04T22:15:21.000Z t:dvv_print_flag=F t:dvv_907_no=D40620B t:dvv_464_color=BLACK t:dvv_over48_ind=N t:dvv_tag_loc2="2 AVE - 3 AVE" t:dvv_tag_remarks=7A-7P t:isn=11 t:dvv_tag_loc1="S/S E 126 ST" t:dvv_hq_approve=X t:dvv_color=BLACK t:dvv_state=NY t:dvv_challenge_48=N t:dvv_464_make=DODGE t:dvv_type=4D t:dvv_chrge_48=N t:dvv_final_disp_cd=RTC t:dvv_make=CHRYSL t:dvv_city="NEW YORK" t:dvv_district_cd=ME11 t:dvv_lor_indic=A t:dvv_yard_resp=DVO1A t:dvv_tag_no=1072203 t:dvv_year=1985 t:dvv_464_type=4D t:dvv_se_status=V m:dvv_summons=96754947

series e:bjuu-44hx d:1997-11-24T22:36:42.000Z t:dvv_print_flag=F t:dvv_907_no=D53346B t:dvv_464_color=GREEN t:dvv_over48_ind=N t:dvv_tag_loc2="PITKIN X GLENMORE" t:dvv_tag_remarks="NO PARKING" t:isn=42 t:dvv_tag_loc1="INF 236 WYONA" t:dvv_hq_approve=X t:dvv_color=BLUE t:dvv_challenge_48=N t:dvv_464_make=HONDA t:dvv_type=4D t:dvv_chrge_48=N t:dvv_final_disp_cd=RTC t:dvv_make=HONDA t:dvv_district_cd=BKN05 t:dvv_yard_resp=DVO3A t:dvv_tag_no=3106736 t:dvv_year=1995 t:dvv_464_type=4D t:dvv_se_status=S m:dvv_yd_sub_contr=2

series e:bjuu-44hx d:1995-09-05T06:18:41.000Z t:dvv_print_flag=F t:dvv_907_no=C46564Y t:dvv_464_color=RED t:dvv_over48_ind=N t:dvv_tag_loc2="OPP.448 WEST 16" t:dvv_tag_remarks=8A/6P t:isn=44 t:dvv_tag_loc1="N/S 16 TH ST. BET. 10/9" t:dvv_hq_approve=X t:dvv_color=RED t:dvv_state=NY t:dvv_challenge_48=N t:dvv_464_make=SUBARU t:dvv_type=SW t:dvv_chrge_48=N t:dvv_final_disp_cd=RTC t:dvv_make=SUBARU t:dvv_city=BRONX t:dvv_district_cd=MW04 t:dvv_lor_indic=A t:dvv_yard_resp=DVO1A t:dvv_tag_no=1064107 t:dvv_year=1982 t:dvv_464_type=SW t:dvv_se_status=V m:dvv_summons=88644160
```

## Meta Commands

```ls
metric m:dvv_464_upd_cnt p:integer l:DVV_464_UPD_CNT t:dataTypeName=number

metric m:dvv_prev_463 p:integer l:DVV_PREV_463 t:dataTypeName=number

metric m:dvv_filler4 p:long l:DVV_FILLER4 t:dataTypeName=number

metric m:dvv_filler6 p:long l:DVV_FILLER6 t:dataTypeName=number

metric m:dvv_dot p:integer l:DVV_DOT t:dataTypeName=number

metric m:dvv_kdvo_cnt p:integer l:DVV_KDVO_CNT t:dataTypeName=number

metric m:dvv_summons p:integer l:DVV_SUMMONS t:dataTypeName=number

metric m:dvv_yd_sub_contr p:integer l:DVV_YD_SUB_CONTR t:dataTypeName=number

metric m:dvv_rotow_tagno p:integer l:DVV_ROTOW_TAGNO t:dataTypeName=number

entity e:bjuu-44hx l:"Derelict Vehicle Dispositions - Vehicles" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/bjuu-44hx

property e:bjuu-44hx t:meta.view v:id=bjuu-44hx v:category="City Government" v:averageRating=0 v:name="Derelict Vehicle Dispositions - Vehicles" v:attribution="Department of Sanitation (DSNY)"

property e:bjuu-44hx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:bjuu-44hx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```

## Top Records

```ls
| isn | dvv_yard_resp | dvv_district_cd | dvv_orig_yard | dvv_464_upd_cnt | dvv_tag_loc1              | dvv_tag_loc2             | dvv_year | dvv_make | dvv_type | dvv_color | dvv_tag_remarks      | dvv_tag_no | dvv_tag_date | dvv_tag_time | dvv_prev_463 | dvv_timestmp   | dvv_filler3 | dvv_filler4 | dvv_print_flag | dvv_checked_date | dvv_timestmp_upd | dvv_final_disp_date | dvv_final_disp_cd | dvv_464_make | dvv_464_type | dvv_464_color | dvv_907_no | dvv_hold_no | dvv_filler5 | dvv_filler6 | dvv_se_status | dvv_over48_ind | dvv_chrge_48 | dvv_challenge_48 | dvv_hq_approve | dvv_vin_timestmp | dvv_rental_find | dvv_rental_indic | dvv_city | dvv_state | dvv_stolen_indic | dvv_lor_indic | dvv_dot | dvv_kdvo_cnt | dvv_nicb_timestmp | dvv_summons | dvv_yd_sub_contr | dvv_last_upd_opid | dvv_rotow_tagno | dvv_acc_logno | 
| === | ============= | =============== | ============= | =============== | ========================= | ======================== | ======== | ======== | ======== | ========= | ==================== | ========== | ============ | ============ | ============ | ============== | =========== | =========== | ============== | ================ | ================ | =================== | ================= | ============ | ============ | ============= | ========== | =========== | =========== | =========== | ============= | ============== | ============ | ================ | ============== | ================ | =============== | ================ | ======== | ========= | ================ | ============= | ======= | ============ | ================= | =========== | ================ | ================= | =============== | ============= | 
| 1   | DVO999        | TRN01           |               |                 | AVENUE P & E 4TH ST       |                          |          | VOLVO    | 4D       | BLACK     | EMERGENCY TOW        | 1          | 19891117     | 900          |              | 19891117162634 |             |             | F              |                  | 19970606070052   | 19891117            | NOL               | VOLVO        | 4D           | BLACK         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 2   | DVO999        | TRN01           |               |                 | WOODSIDE/61ST ST          | IFO DUNKIN DONUTS        |          | DATSUN   | 2D       | BURNT     | NORTH SIDE OF STREET | 2          | 19891119     | 900          |              | 19891120113336 |             |             | F              |                  | 19900711055802   | 99999999            | AAA               | DATSUN       | 2D           | BURNT         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 3   | DVO999        | TRN01           |               |                 | LOCATION                  | STREET                   |          | OLDS     | SW       | GREEN     |                      | 5          | 19891120     | 900          |              | 19891120103827 |             |             | F              | 19891120         |                  | 19891120            | RTC               | OLDS         | SW           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 4   | DVO999        | TRN05           |               |                 | SMITH STR NR BWAY IFO     | SCHOOL YARD              |          | CHEV     | SW       | GREEN     | EMERGENCY TOW        | 6          | 19891120     | 900          |              | 19900328092426 |             |             | F              |                  |                  | 19900328            | NOL               | CHEV         | SW           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 5   | DVO999        | TRN01           |               |                 | N/E CORNER 125ST & 5TH AV |                          |          | FORD     | 4D       | BLUE      |                      | 100001     | 19891120     | 930          |              | 19891127142252 |             |             | E              |                  |                  | 99999999            | AAA               | FORD         | 4D           | BLUE          |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 6   | DVO999        | TRN01           |               |                 | 86TH ST BETW LEXINGTON    | AND PARK AVE             |          | FORD     | 4D       | GREEN     |                      | 100002     | 19891120     | 1000         |              | 19891122135609 |             |             | F              |                  |                  | 99999999            | AAA               | FORD         | 4D           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 7   | DVO999        | TRN01           |               |                 | N/S WELLINGTON DRIVE,BET  | HOBART & HASTINGS AVENUE |          | FORD     | VN       | GREEN     |                      | 100003     | 19891121     | 830          |              | 19891121095359 |             |             | E              |                  |                  | 99999999            | AAA               | FORD         | VN           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 8   | DVO999        | TRN14           |               |                 | N/S WELLINGTON DRIVE BET  | HOBART & HASTINGS AVE.   |          | FORD     | VN       | GREEN     |                      | 1400001    | 19891121     | 830          |              | 19891121113125 |             |             | E              |                  | 19900409093631   | 99999999            | AAA               | FORD         | VN           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 9   | DVO999        | TRN14           |               |                 | 351 FRESH POND AVE BET    | GRAND AVE & 31 PLACE     |          | BUICK    | 4D       | GRAY      |                      | 1400002    | 19891121     | 830          |              | 19891121095945 |             |             | F              |                  | 19900921090033   | 99999999            | AAA               | BUICK        | 4D           | GRAY          |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
| 10  | DVO999        | TRN13           |               |                 | N/S WELLINGTON DRIVE BET  | HOBART & HASTINGS        |          | FORD     | VN       | GREEN     |                      | 1300001    | 19891121     | 830          |              | 19891127112401 |             |             | F              |                  |                  | 99999999            | AAA               | FORD         | VN           | GREEN         |            |             |             |             |               |                |              |                  |                |                  |                 |                  |          |           |                  |               |         |              |                   |             |                  |                   |                 |               | 
```