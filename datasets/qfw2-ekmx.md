# SDOT Traffic Count Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-count-details) |
| Metadata | [Link](https://data.seattle.gov/api/views/qfw2-ekmx) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qfw2-ekmx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qfw2-ekmx/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qfw2-ekmx |
| Name | SDOT Traffic Count Details |
| Category | Transportation |
| Tags | traffic, counts, sdot, adt, awdt, am, pm, peak, hour, seattle, vision zero |
| Created | 2015-03-19T15:17:18Z |
| Publication Date | 2015-03-19T15:18:33Z |

## Description

Vehicle traffic volumes collected from 7-day counts. Used to provide traffic count data that includes ADT, AWDT, AM and PM peak hour volumes along with study dates.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | series tag     | study_id                  | STUDY_ID                  | text      | number      |
| Yes      | series tag     | title                     | TITLE                     | text      | text        |
| Yes      | time           | start_date                | START_DATE                | date      | date        |
| No       |                | end_date                  | END_DATE                  | date      | date        |
| Yes      | numeric metric | actual_days               | ACTUAL_DAYS               | number    | number      |
| Yes      | numeric metric | intended_days             | INTENDED_DAYS             | number    | number      |
| Yes      | numeric metric | study_length              | STUDY_LENGTH              | number    | number      |
| Yes      | series tag     | study_lane_code           | STUDY_LANE_CODE           | text      | text        |
| Yes      | series tag     | study_dirflow             | STUDY_DIRFLOW             | text      | text        |
| Yes      | series tag     | comments                  | COMMENTS                  | text      | text        |
| Yes      | numeric metric | study_adt                 | STUDY_ADT                 | number    | number      |
| Yes      | numeric metric | study_awdt                | STUDY_AWDT                | number    | number      |
| Yes      | numeric metric | study_max8                | STUDY_MAX8                | number    | number      |
| Yes      | numeric metric | study_ampk                | STUDY_AMPK                | number    | number      |
| Yes      | numeric metric | study_pmpk                | STUDY_PMPK                | number    | number      |
| Yes      | numeric metric | seg_compkey               | SEG_COMPKEY               | number    | number      |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | unitid2                   | UNITID2                   | text      | text        |
| Yes      | series tag     | o_street                  | O_STREET                  | text      | text        |
| Yes      | series tag     | x_street                  | X_STREET                  | text      | text        |
| Yes      | series tag     | dir_from_cross_street     | DIR_FROM_CROSS_STREET     | text      | text        |
| Yes      | series tag     | stdy_title_part           | STDY_TITLE_PART           | text      | text        |
| Yes      | series tag     | stdy_label                | STDY_LABEL                | text      | text        |
| Yes      | numeric metric | distance                  | DISTANCE                  | number    | number      |
| No       |                | stdy_year                 | STDY_YEAR                 | number    | number      |
| Yes      | series tag     | study_type                | STUDY_TYPE                | text      | text        |
| Yes      | series tag     | flowmap                   | FLOWMAP                   | text      | text        |
| Yes      | series tag     | hpms                      | HPMS                      | text      | text        |
| Yes      | series tag     | screenline                | SCREENLINE                | text      | text        |
| Yes      | series tag     | stdy_title_part_with_flow | STDY_TITLE_PART_WITH_FLOW | text      | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_date,stdy_year
```

## Data Commands

```ls
series e:qfw2-ekmx d:2002-04-08T12:00:00.000Z t:dir_from_cross_street=N t:study_lane_code=0 t:unitid2=0153 t:study_type="VOLUME COUNT" t:stdy_title_part="RAINIER AVE S, NW/O S MASSACHUSETTS ST" t:title="RAINIER AVE S, NW/O S MASSACHUSETTS ST; N FLOW; 08APR2002 12:00" t:stdy_title_part_with_flow="RAINIER AVE S, NW/O S MASSACHUSETTS ST; N FLOW" t:unitid=09345 t:x_street="RAINIER NB I90 EB ON RP" t:study_id=100914 t:objectid=1 t:o_street="RAINIER AVE S" t:comments="ORIGINAL TITLE:  9345 135N N  0 4/ 8/2002 212: 0 711: 0  RAINIER       AVS S MASSACHUSETTS ST  COUNTER 150                                          H" t:stdy_label="100914, 2002-04-08, N" t:study_dirflow=N m:study_awdt=22662 m:distance=33 m:study_pmpk=1529 m:intended_days=7 m:actual_days=7 m:seg_compkey=12352 m:study_adt=21066 m:study_ampk=2012 m:study_length=672 m:study_max8=12107

series e:qfw2-ekmx d:2005-10-04T11:15:00.000Z t:dir_from_cross_street=SE t:study_lane_code=STANDARD t:unitid2=0322 t:study_type="VOLUME COUNT" t:stdy_title_part="FUHRMAN AVE E, SE/O EASTLAKE AVE E" t:screenline=Y t:title="FUHRMAN AVE E, SE/O EASTLAKE AVE E; SE FLOW; CH1; 04OCT2005 11:15#" t:stdy_title_part_with_flow="FUHRMAN AVE E, SE/O EASTLAKE AVE E; SE FLOW" t:unitid=06910 t:x_street="FRANKLIN AVE E" t:study_id=207947 t:objectid=2 t:o_street="FUHRMAN AVE E" t:stdy_label="207947, 2005-10-04, SE" t:study_dirflow=SE m:study_awdt=4511 m:distance=181 m:study_pmpk=453 m:intended_days=7 m:actual_days=7 m:seg_compkey=10578 m:study_adt=4089 m:study_ampk=525 m:study_length=672 m:study_max8=2500

series e:qfw2-ekmx d:2002-04-02T09:45:00.000Z t:dir_from_cross_street=W t:study_lane_code=0 t:unitid2=0300 t:study_type="VOLUME COUNT" t:stdy_title_part="WEST SEATTLE BR WB, W/O 4TH AV S OFF RP" t:title="WEST SEATTLE BR WB, W/O 4TH AV S OFF RP; W FLOW; 02APR2002 09:45" t:stdy_title_part_with_flow="WEST SEATTLE BR WB, W/O 4TH AV S OFF RP; W FLOW" t:unitid=10273 t:x_street="4TH AV S OFF RP" t:study_id=100913 t:objectid=3 t:o_street="WEST SEATTLE BR WB" t:comments="ORIGINAL TITLE: 10273  70W W  0 4/ 2/2002 3 9:45 7 9:30  W SEATTLE WB  BR    4 AVS OFF     RP  AGGREGATE                                            H" t:stdy_label="100913, 2002-04-02, W" t:study_dirflow=W m:study_awdt=34137 m:distance=428.5 m:study_pmpk=2431 m:intended_days=7 m:actual_days=7 m:seg_compkey=13338 m:study_adt=32097 m:study_ampk=1983 m:study_length=672 m:study_max8=16982
```

## Meta Commands

```ls
metric m:actual_days p:integer l:ACTUAL_DAYS d:ACTUAL_DAYS t:dataTypeName=number

metric m:intended_days p:integer l:INTENDED_DAYS d:INTENDED_DAYS t:dataTypeName=number

metric m:study_length p:integer l:STUDY_LENGTH d:STUDY_LENGTH t:dataTypeName=number

metric m:study_adt p:integer l:STUDY_ADT d:STUDY_ADT t:dataTypeName=number

metric m:study_awdt p:integer l:STUDY_AWDT d:STUDY_AWDT t:dataTypeName=number

metric m:study_max8 p:integer l:STUDY_MAX8 d:STUDY_MAX8 t:dataTypeName=number

metric m:study_ampk p:integer l:STUDY_AMPK d:STUDY_AMPK t:dataTypeName=number

metric m:study_pmpk p:integer l:STUDY_PMPK d:STUDY_PMPK t:dataTypeName=number

metric m:seg_compkey p:integer l:SEG_COMPKEY d:SEG_COMPKEY t:dataTypeName=number

metric m:distance p:float l:DISTANCE d:DISTANCE t:dataTypeName=number

entity e:qfw2-ekmx l:"SDOT Traffic Count Details" t:url=https://data.seattle.gov/api/views/qfw2-ekmx

property e:qfw2-ekmx t:meta.view v:id=qfw2-ekmx v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Traffic Count Details"

property e:qfw2-ekmx t:meta.view.license v:name="Public Domain"

property e:qfw2-ekmx t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:qfw2-ekmx t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | study_id | title                                                              | start_date | end_date   | actual_days | intended_days | study_length | study_lane_code | study_dirflow | comments                                                                                           | study_adt | study_awdt | study_max8 | study_ampk | study_pmpk | seg_compkey | unitid | unitid2 | o_street           | x_street                | dir_from_cross_street | stdy_title_part                         | stdy_label             | distance | stdy_year | study_type   | flowmap | hpms | screenline | stdy_title_part_with_flow                       | 
| ======== | ======== | ================================================================== | ========== | ========== | =========== | ============= | ============ | =============== | ============= | ================================================================================================== | ========= | ========== | ========== | ========== | ========== | =========== | ====== | ======= | ================== | ======================= | ===================== | ======================================= | ====================== | ======== | ========= | ============ | ======= | ==== | ========== | =============================================== | 
| 1        | 100914   | RAINIER AVE S, NW/O S MASSACHUSETTS ST; N FLOW; 08APR2002 12:00    | 1018267200 | 1018872000 | 7           | 7             | 672          | 0               | N             | ORIGINAL TITLE: 9345 135N N 0 4/ 8/2002 212: 0 711: 0 RAINIER AVS S MASSACHUSETTS ST COUNTER 150 H | 21066     | 22662      | 12107      | 2012       | 1529       | 12352       | 09345  | 0153    | RAINIER AVE S      | RAINIER NB I90 EB ON RP | N                     | RAINIER AVE S, NW/O S MASSACHUSETTS ST  | 100914, 2002-04-08, N  | 33       | 2002      | VOLUME COUNT |         |      |            | RAINIER AVE S, NW/O S MASSACHUSETTS ST; N FLOW  | 
| 2        | 207947   | FUHRMAN AVE E, SE/O EASTLAKE AVE E; SE FLOW; CH1; 04OCT2005 11:15# | 1128424500 | 1129029300 | 7           | 7             | 672          | STANDARD        | SE            |                                                                                                    | 4089      | 4511       | 2500       | 525        | 453        | 10578       | 06910  | 0322    | FUHRMAN AVE E      | FRANKLIN AVE E          | SE                    | FUHRMAN AVE E, SE/O EASTLAKE AVE E      | 207947, 2005-10-04, SE | 181      | 2005      | VOLUME COUNT |         |      | Y          | FUHRMAN AVE E, SE/O EASTLAKE AVE E; SE FLOW     | 
| 3        | 100913   | WEST SEATTLE BR WB, W/O 4TH AV S OFF RP; W FLOW; 02APR2002 09:45   | 1017740700 | 1018345500 | 7           | 7             | 672          | 0               | W             | ORIGINAL TITLE: 10273 70W W 0 4/ 2/2002 3 9:45 7 9:30 W SEATTLE WB BR 4 AVS OFF RP AGGREGATE H     | 32097     | 34137      | 16982      | 1983       | 2431       | 13338       | 10273  | 0300    | WEST SEATTLE BR WB | 4TH AV S OFF RP         | W                     | WEST SEATTLE BR WB, W/O 4TH AV S OFF RP | 100913, 2002-04-02, W  | 428.5    | 2002      | VOLUME COUNT |         |      |            | WEST SEATTLE BR WB, W/O 4TH AV S OFF RP; W FLOW | 
| 4        | 207946   | FUHRMAN AVE E, SE/O EASTLAKE AVE E; NW FLOW; CH1; 04OCT2005 11:15# | 1128424500 | 1129029300 | 7           | 7             | 672          | STANDARD        | NW            |                                                                                                    | 2998      | 3261       | 1857       | 314        | 318        | 10578       | 06910  | 0322    | FUHRMAN AVE E      | FRANKLIN AVE E          | SE                    | FUHRMAN AVE E, SE/O EASTLAKE AVE E      | 207946, 2005-10-04, NW | 181      | 2005      | VOLUME COUNT |         |      | Y          | FUHRMAN AVE E, SE/O EASTLAKE AVE E; NW FLOW     | 
| 5        | 212597   | AURORA AVE N, N/O GREEN LAKE DR N; S FLOW; CH1; 20AUG2007 14:00    | 1187618400 | 1188223200 | 7           | 7             | 672          | STANDARD        | S             |                                                                                                    | 19852     | 21005      | 10733      | 1815       | 1450       | 8961        | 05250  | 0830    | AURORA AVE N       | GREEN LAKE DR N         | N                     | AURORA AVE N, N/O GREEN LAKE DR N       | 212597, 2007-08-20, S  | 132      | 2007      | VOLUME COUNT |         |      |            | AURORA AVE N, N/O GREEN LAKE DR N; S FLOW       | 
| 6        | 215354   | 1ST AVE NE, S/O NE 80TH ST; S FLOW; AGG; 04NOV2008 11:45#          | 1225799100 | 1226403900 | 7           | 7             | 672          | STANDARD        | S             | This study is an aggregate of the following source studies: 215353, 215352                         | 905       | 947        | 527        | 119        | 86         | 1086        | 00020  | 0770    | 1ST AVE NE         | NE 77TH ST              | S                     | 1ST AVE NE, S/O NE 80TH ST              | 215354, 2008-11-04, S  | 329      | 2008      | AGGREGATE    |         |      | Y          | 1ST AVE NE, S/O NE 80TH ST; S FLOW              | 
| 7        | 203309   | STEWART ST, NE/O 4TH AVE; SW FLOW; CH1; 10MAR2004 10:15            | 1078913700 | 1079518500 | 7           | 7             | 672          | STANDARD        | SW            |                                                                                                    | 10412     | 10987      | 5454       | 941        | 789        | 12900       | 09800  | 0040    | STEWART ST         | 4TH AVE                 | NE                    | STEWART ST, NE/O 4TH AVE                | 203309, 2004-03-10, SW | 161      | 2004      | VOLUME COUNT |         |      |            | STEWART ST, NE/O 4TH AVE; SW FLOW               | 
| 8        | 212596   | AURORA AVE N, S/O GREEN LAKE DR N; N FLOW; CH1; 20AUG2007 12:45    | 1187613900 | 1188218700 | 5           | 7             | 480          | STANDARD        | N             |                                                                                                    | 0         | 20916      | 12310      | 1097       | 1974       | 8960        | 05250  | 0820    | AURORA AVE N       | N 82ND ST               | S                     | AURORA AVE N, S/O GREEN LAKE DR N       | 212596, 2007-08-20, N  | 132      | 2007      | VOLUME COUNT |         |      |            | AURORA AVE N, S/O GREEN LAKE DR N; N FLOW       | 
| 9        | 214488   | VINE ST, NE/O ALASKAN WAY; SW FLOW; AGG; 19JUN2008 09:45           | 1213868700 | 1214473500 | 7           | 7             | 672          | STANDARD        | SW            | This study is an aggregate of the following source studies: 214486, 214485                         | 321       | 302        | 179        | 22         | 34         | 13299       | 10240  | 0002    | VINE ST            | ALASKAN WAY             | NE                    | VINE ST, NE/O ALASKAN WAY               | 214488, 2008-06-19, SW | 143      | 2008      | AGGREGATE    |         |      |            | VINE ST, NE/O ALASKAN WAY; SW FLOW              | 
| 10       | 203307   | ALASKAN WAY, SE/O BLANCHARD ST; SE FLOW; CH1; 10MAR2004 10:00#     | 1078912800 | 1079517600 | 7           | 7             | 672          | STANDARD        | SE            |                                                                                                    | 5075      | 5232       | 3059       | 385        | 568        | 8728        | 05045  | 0210    | ALASKAN WAY        | LENORA ST               | SE                    | ALASKAN WAY, SE/O BLANCHARD ST          | 203307, 2004-03-10, SE | 213.5    | 2004      | VOLUME COUNT |         |      | Y          | ALASKAN WAY, SE/O BLANCHARD ST; SE FLOW         | 
```