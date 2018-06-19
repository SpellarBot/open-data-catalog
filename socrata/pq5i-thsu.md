# Derelict Vehicles Dispositions - Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/derelict-vehicles-dispositions-complaints) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pq5i-thsu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pq5i-thsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pq5i-thsu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pq5i-thsu |
| Name | Derelict Vehicles Dispositions - Complaints |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Created | 2015-05-22T20:14:47Z |
| Publication Date | 2017-04-08T19:53:13Z |

## Description

Data for removing derelict vehicle operations from city streets, Gives disposition (complaints) of derelict vehicles reported to DSNY from 311.

https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Tow/vr8p-8shw
https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Vehicles/bjuu-44hx
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Rentals/v6j6-k9uc

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | isn              | ISN              | text      | number      |
| Yes      | series tag     | dvc_loc1         | DVC_LOC1         | text      | text        |
| Yes      | series tag     | dvc_loc2         | DVC_LOC2         | text      | text        |
| Yes      | series tag     | dvc_make         | DVC_MAKE         | text      | text        |
| Yes      | series tag     | dvc_color        | DVC_COLOR        | text      | text        |
| Yes      | series tag     | dvc_type         | DVC_TYPE         | text      | text        |
| Yes      | series tag     | dvc_remarks1     | DVC_REMARKS1     | text      | text        |
| Yes      | series tag     | dvc_remarks2     | DVC_REMARKS2     | text      | text        |
| Yes      | series tag     | dvc_filler2      | DVC_FILLER2      | text      | text        |
| Yes      | series tag     | dvc_dist_cd      | DVC_DIST_CD      | text      | text        |
| Yes      | series tag     | dvc_log          | DVC_LOG          | text      | text        |
| No       |                | dvc_call_dt_time | DVC_CALL_DT_TIME | number    | number      |
| Yes      | series tag     | dvc_tag_no       | DVC_TAG_NO       | text      | text        |
| Yes      | numeric metric | dvc_timstmp_upd  | DVC_TIMSTMP_UPD  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = dvc_call_dt_time
```

## Data Commands

```ls
series e:pq5i-thsu d:2017-04-08T19:51:40.000Z t:dvc_color=WHITE t:dvc_make=CHEVY t:dvc_loc1="2310 BRIDGE PLAZA SOUTH" t:isn=540 t:dvc_dist_cd=QW02 t:dvc_log="QW 0146" t:dvc_loc2="BET 23RD AVE & 24TH AVE" t:dvc_type=2D m:dvc_timstmp_upd=199005110727

series e:pq5i-thsu d:2017-04-08T19:51:40.000Z t:dvc_color=GOLD t:dvc_make=CADY t:dvc_tag_no=409378 t:dvc_loc1="108-33 39TH AVE BET" t:isn=541 t:dvc_dist_cd=QW03 t:dvc_log="QW 0147" t:dvc_loc2="108TH ST & 111TH ST" t:dvc_type=4D m:dvc_timstmp_upd=199005110740

series e:pq5i-thsu d:2017-04-08T19:51:40.000Z t:dvc_color=BLUE t:dvc_make=CADY t:dvc_tag_no=400382 t:dvc_loc1="247TH ST BET DEPEW AVE &" t:isn=542 t:dvc_dist_cd=QN11 t:dvc_log="QN 0054" t:dvc_loc2="43RD AVE" t:dvc_type=2D m:dvc_timstmp_upd=199005101357
```

## Meta Commands

```ls
metric m:dvc_timstmp_upd p:long l:DVC_TIMSTMP_UPD t:dataTypeName=number

entity e:pq5i-thsu l:"Derelict Vehicles Dispositions - Complaints" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/pq5i-thsu

property e:pq5i-thsu t:meta.view v:id=pq5i-thsu v:category="City Government" v:averageRating=0 v:name="Derelict Vehicles Dispositions - Complaints" v:attribution="Department of Sanitation (DSNY)"

property e:pq5i-thsu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pq5i-thsu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | isn | dvc_loc1                 | dvc_loc2                | dvc_make | dvc_color | dvc_type | dvc_remarks1 | dvc_remarks2 | dvc_filler2 | dvc_dist_cd | dvc_log | dvc_call_dt_time | dvc_tag_no | dvc_timstmp_upd | 
| =========== | === | ======================== | ======================= | ======== | ========= | ======== | ============ | ============ | =========== | =========== | ======= | ================ | ========== | =============== | 
| 1491681100  | 540 | 2310 BRIDGE PLAZA SOUTH  | BET 23RD AVE & 24TH AVE | CHEVY    | WHITE     | 2D       |              |              |             | QW02        | QW 0146 | 199005081132     |            | 199005110727    | 
| 1491681100  | 541 | 108-33 39TH AVE BET      | 108TH ST & 111TH ST     | CADY     | GOLD      | 4D       |              |              |             | QW03        | QW 0147 | 199005081425     | 409378     | 199005110740    | 
| 1491681100  | 542 | 247TH ST BET DEPEW AVE & | 43RD AVE                | CADY     | BLUE      | 2D       |              |              |             | QN11        | QN 0054 | 199005081427     | 400382     | 199005101357    | 
| 1491681100  | 543 | 15-16 120TH ST BET       | 15TH AVE & 18TH AVE     | CHEVY    | BLUE      | 2D       |              |              |             | QN07        | QN 0055 | 199005081431     |            | 199005150913    | 
| 1491681100  | 544 | 206 CANNON BLVD BET      | HYLAN BLVD & CLASSON ST | PLYMO    | MAROON    | 2D       |              |              |             | SI02        | SI 0068 | 199005081434     |            | 199005101415    | 
| 1491681100  | 545 | WEBSTER AVE BET 167TH ST | 168TH ST                | CHEVY    | BLUE      | 4D       |              |              |             | BXW03       | BXW0014 | 199005081436     | 473569     | 199005101432    | 
| 1491681100  | 546 | 104-45 43RD AVE BET      | 104TH ST & 108TH ST     | BUICK    | BLUE      | 2D       |              |              |             | QW04        | QW 0148 | 199005081527     | 409773     | 199005141401    | 
| 1491681100  | 547 | 126 ST BET 13TH AVE &    | 14TH AVE                | CHEVY    | RED       | 4D       |              |              |             | QN07        | QN 0056 | 199005081529     |            | 199005150913    | 
| 1491681100  | 548 | 50TH ST BET 54TH AVE     | LONG ISLAND EXPRESSWAY  | CHEVY    | GREY      | 2D       |              |              |             | QW02        | QW 0149 | 199005081549     | 409142     | 199005101023    | 
| 1491681100  | 549 | KISSENA BLVD BET         | HOLLY AVE & JUNIPER AVE | N/A      | BLACK     | 4D       |              |              |             | QN07        | QN 0057 | 199005081625     |            | 199005241439    | 
```