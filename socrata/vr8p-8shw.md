# Derelict Vehicle Dispositions - Tow

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/derelict-vehicle-dispositions-tow) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vr8p-8shw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vr8p-8shw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vr8p-8shw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vr8p-8shw |
| Name | Derelict Vehicle Dispositions - Tow |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Created | 2015-05-22T20:21:29Z |
| Publication Date | 2017-04-08T19:37:39Z |

## Description

Data for removing derelict vehicle operations from city streets, Gives disposition (complaints) of derelict vehicles reported to DSNY from 311.

https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Vehicles/bjuu-44hx
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Complaints/pq5i-thsu
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Rentals/v6j6-k9uc

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | isn                | ISN                | text      | number      |
| Yes      | numeric metric | dvt_rotow_tagno    | DVT_ROTOW_TAGNO    | number    | number      |
| Yes      | series tag     | dvt_district       | DVT_DISTRICT       | text      | text        |
| Yes      | numeric metric | dvt_tagdt          | DVT_TAGDT          | number    | text        |
| Yes      | series tag     | dvt_tagtm          | DVT_TAGTM          | text      | text        |
| Yes      | series tag     | dvt_location       | DVT_LOCATION       | text      | text        |
| Yes      | series tag     | dvt_between_1      | DVT_BETWEEN_1      | text      | text        |
| Yes      | series tag     | dvt_between_2      | DVT_BETWEEN_2      | text      | text        |
| Yes      | series tag     | dvt_make           | DVT_MAKE           | text      | text        |
| Yes      | series tag     | dvt_color          | DVT_COLOR          | text      | text        |
| Yes      | series tag     | dvt_type           | DVT_TYPE           | text      | text        |
| Yes      | series tag     | dvt_tid_e          | DVT_TID_E          | text      | text        |
| Yes      | numeric metric | dvt_timestmp_e     | DVT_TIMESTMP_E     | number    | text        |
| Yes      | series tag     | dvt_operid_e       | DVT_OPERID_E       | text      | text        |
| Yes      | numeric metric | dvt_status_cd      | DVT_STATUS_CD      | number    | text        |
| Yes      | series tag     | dvt_fill_a         | DVT_FILL_A         | text      | text        |
| Yes      | series tag     | dvt_final_disp_cd  | DVT_FINAL_DISP_CD  | text      | text        |
| Yes      | numeric metric | dvt_final_disp_dt  | DVT_FINAL_DISP_DT  | number    | text        |
| Yes      | series tag     | dvt_final_disp_tm  | DVT_FINAL_DISP_TM  | text      | text        |
| Yes      | series tag     | dvt_final_tid      | DVT_FINAL_TID      | text      | text        |
| Yes      | numeric metric | dvt_final_timestmp | DVT_FINAL_TIMESTMP | number    | text        |
| Yes      | series tag     | dvt_final_operid   | DVT_FINAL_OPERID   | text      | text        |
| Yes      | series tag     | dvt_tag_no         | DVT_TAG_NO         | text      | text        |
| Yes      | numeric metric | dvt_outstand_ind   | DVT_OUTSTAND_IND   | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vr8p-8shw d:2017-04-08T19:36:54.000Z t:isn=1 t:dvt_final_operid=BKE15C t:dvt_final_tid=Z001 t:dvt_make=MAZDA t:dvt_district=BKE15 t:dvt_operid_e=DIRDVO t:dvt_final_disp_cd=NOL t:dvt_tid_e=Z001 t:dvt_type=4D t:dvt_color=BLUE t:dvt_between_1="AVE U" t:dvt_between_2="AVE V" t:dvt_tagtm=0800 t:dvt_final_disp_tm=1002 t:dvt_location=BATCHELDER m:dvt_final_disp_dt=20021227 m:dvt_tagdt=20021211 m:dvt_timestmp_e=200301061055 m:dvt_outstand_ind=9 m:dvt_status_cd=3 m:dvt_final_timestmp=200301061311 m:dvt_rotow_tagno=17908

series e:vr8p-8shw d:2017-04-08T19:36:54.000Z t:isn=2 t:dvt_final_operid=BKW11C t:dvt_final_tid=Z001 t:dvt_make=LINCOL t:dvt_district=BKW11 t:dvt_operid_e=DIRDVO t:dvt_final_disp_cd=NOL t:dvt_tid_e=Z001 t:dvt_type=4D t:dvt_color=WHITE t:dvt_between_1="68TH ST." t:dvt_between_2="67TH ST." t:dvt_tagtm=0800 t:dvt_final_disp_tm=1001 t:dvt_location="R/S NEW UTRECHT AVE" m:dvt_final_disp_dt=20021227 m:dvt_tagdt=20021211 m:dvt_timestmp_e=200301061058 m:dvt_outstand_ind=9 m:dvt_status_cd=3 m:dvt_final_timestmp=200301061250 m:dvt_rotow_tagno=18029

series e:vr8p-8shw d:2017-04-08T19:36:54.000Z t:isn=3 t:dvt_final_operid=BKE18C t:dvt_final_tid=Z001 t:dvt_make=MITSUB t:dvt_district=BKE18 t:dvt_operid_e=DIRDVO t:dvt_final_disp_cd=NOL t:dvt_tid_e=Z001 t:dvt_type=4D t:dvt_color=BLACK t:dvt_between_1="KING HWY" t:dvt_between_2="AVE P" t:dvt_tagtm=0800 t:dvt_final_disp_tm=1001 t:dvt_location="NOSTRAND AVE" m:dvt_final_disp_dt=20021227 m:dvt_tagdt=20021212 m:dvt_timestmp_e=200301061101 m:dvt_outstand_ind=9 m:dvt_status_cd=3 m:dvt_final_timestmp=200301061251 m:dvt_rotow_tagno=17935
```

## Meta Commands

```ls
metric m:dvt_rotow_tagno p:integer l:DVT_ROTOW_TAGNO t:dataTypeName=number

metric m:dvt_tagdt p:integer l:DVT_TAGDT t:dataTypeName=number

metric m:dvt_timestmp_e p:long l:DVT_TIMESTMP_E t:dataTypeName=number

metric m:dvt_status_cd p:integer l:DVT_STATUS_CD t:dataTypeName=number

metric m:dvt_final_disp_dt p:integer l:DVT_FINAL_DISP_DT t:dataTypeName=number

metric m:dvt_final_timestmp p:long l:DVT_FINAL_TIMESTMP t:dataTypeName=number

metric m:dvt_outstand_ind p:integer l:DVT_OUTSTAND_IND t:dataTypeName=number

entity e:vr8p-8shw l:"Derelict Vehicle Dispositions - Tow" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/vr8p-8shw

property e:vr8p-8shw t:meta.view v:id=vr8p-8shw v:category="City Government" v:averageRating=0 v:name="Derelict Vehicle Dispositions - Tow" v:attribution="Department of Sanitation (DSNY)"

property e:vr8p-8shw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vr8p-8shw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | isn | dvt_rotow_tagno | dvt_district | dvt_tagdt | dvt_tagtm | dvt_location        | dvt_between_1 | dvt_between_2   | dvt_make | dvt_color | dvt_type | dvt_tid_e | dvt_timestmp_e | dvt_operid_e | dvt_status_cd | dvt_fill_a | dvt_final_disp_cd | dvt_final_disp_dt | dvt_final_disp_tm | dvt_final_tid | dvt_final_timestmp | dvt_final_operid | dvt_tag_no | dvt_outstand_ind | 
| =========== | === | =============== | ============ | ========= | ========= | =================== | ============= | =============== | ======== | ========= | ======== | ========= | ============== | ============ | ============= | ========== | ================= | ================= | ================= | ============= | ================== | ================ | ========== | ================ | 
| 1491680214  | 1   | 17908           | BKE15        | 20021211  | 0800      | BATCHELDER          | AVE U         | AVE V           | MAZDA    | BLUE      | 4D       | Z001      | 200301061055   | DIRDVO       | 3             |            | NOL               | 20021227          | 1002              | Z001          | 200301061311       | BKE15C           |            | 9                | 
| 1491680214  | 2   | 18029           | BKW11        | 20021211  | 0800      | R/S NEW UTRECHT AVE | 68TH ST.      | 67TH ST.        | LINCOL   | WHITE     | 4D       | Z001      | 200301061058   | DIRDVO       | 3             |            | NOL               | 20021227          | 1001              | Z001          | 200301061250       | BKW11C           |            | 9                | 
| 1491680214  | 3   | 17935           | BKE18        | 20021212  | 0800      | NOSTRAND AVE        | KING HWY      | AVE P           | MITSUB   | BLACK     | 4D       | Z001      | 200301061101   | DIRDVO       | 3             |            | NOL               | 20021227          | 1001              | Z001          | 200301061251       | BKE18C           |            | 9                | 
| 1491680214  | 4   | 17739           | BKE18        | 20021213  | 0800      | E34TH STREET        | FLATBUSH AVE. | AVE J           | LINCOL   | BLUE      | 4D       | Z001      | 200301061103   | DIRDVO       | 3             |            | NOL               | 20021227          | 1001              | Z001          | 200301061251       | BKE18C           |            | 9                | 
| 1491680214  | 5   | 17996           | BKW06        | 20021214  | 0800      | R/S 7TH STREET      | 3RD AVE       | 4TH AVE         | PUGEOT   | BLACK     | 4D       | Z001      | 200301061105   | DIRDVO       | 3             |            | NOL               | 20021227          | 1001              | Z001          | 200301061252       | BKW06C           |            | 9                | 
| 1491680214  | 6   | 24056           | BKE16        | 20030106  | 1040      | 2052 STRAUSS STREET | BLAKE ST      | DUMONT ST       | FORD     | GRAY      | 4D       |           |                | DIRDVO       | 3             |            | NOL               | 20030116          | 1310              | B162          | 200301161359       | BKE16C           | 0          | 9                | 
| 1491680214  | 7   | 14895           | BKE14        | 20021214  | 0800      | S/S FARRAGUT RD     | E23RD STREET  | E22ND STREET    | PONTIA   | RED       | 4D       | Z001      | 200301061107   | DIRDVO       | 3             |            | DVO               | 20030108          | 1330              | B142          | 200301090705       | BKE14C           | 3146965    | 9                | 
| 1491680214  | 8   | 18078           | BKE17        | 20021219  | 0800      | E94 TH STREET       | CLARKSON      | KING HWY        | CHEVY    | BLUE      | PT       | Z001      | 200301061109   | DIRDVO       | 3             |            | LP                | 20021227          | 1001              | Z001          | 200301061254       | BKE17C           |            | 9                | 
| 1491680214  | 9   | 24012           | BKE18        | 20021219  | 0800      | E55 TH STREET       | FARRAGUT RD   | FOSTER AVE      | FORD     | YELLOW    | 4D       | Z001      | 200301061112   | DIRDVO       | 3             |            | NOL               | 20021227          | 1001              | Z001          | 200301061251       | BKE18C           |            | 9                | 
| 1491680214  | 10  | 18031           | BKW11        | 20021219  | 0800      | R/S 68TH STREET     | 16TH AVE      | NEW UTRECHT AVE | CADDY    | WHITE     | 4D       | Z001      | 200301061113   | DIRDVO       | 3             |            | LP                | 20021227          | 1001              | Z001          | 200301061250       | BKW11C           |            | 9                | 
```