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
series e:qfw2-ekmx d:2002-10-24T15:00:00.000Z t:dir_from_cross_street=S t:study_lane_code=0 t:unitid2=1100 t:study_type="VOLUME COUNT" t:stdy_title_part="5TH AVE NE, S/O NE 112TH S ST" t:title="5TH AVE NE, S/O NE 112TH S ST; S FLOW; 24OCT2002 15:00" t:stdy_title_part_with_flow="5TH AVE NE, S/O NE 112TH S ST; S FLOW" t:unitid=03895 t:x_street="NE NORTHGATE WAY" t:study_id=102810 t:objectid=1 t:o_street="5TH AVE NE" t:comments="ORIGINAL TITLE:  3895 590S S  010/24/2002 515: 0 714: 0  5             AVNENE112 S         ST  COUNTER 116                                          H" t:stdy_label="102810, 2002-10-24, S" t:study_dirflow=S m:study_awdt=6296 m:distance=180 m:study_pmpk=515 m:intended_days=7 m:actual_days=7 m:seg_compkey=7256 m:study_adt=6092 m:study_ampk=435 m:study_length=672 m:study_max8=3566

series e:qfw2-ekmx d:2002-09-12T12:00:00.000Z t:dir_from_cross_street=S t:study_lane_code=0 t:unitid2=0390 t:study_type="VOLUME COUNT" t:stdy_title_part="M L KING JR WAY S, S/O S BRADFORD ST" t:title="M L KING JR WAY S, S/O S BRADFORD ST; S FLOW; 12SEP2002 12:00" t:stdy_title_part_with_flow="M L KING JR WAY S, S/O S BRADFORD ST; S FLOW" t:unitid=08303 t:x_street="S BRADFORD ST" t:study_id=102476 t:objectid=2 t:o_street="M L KING JR WR WAY S" t:comments="ORIGINAL TITLE:  8293 400S S  0 9/12/2002 512: 0 711: 0  M L KING JR   WYS S BRADFORD      ST  COUNTER 148                                          H" t:stdy_label="102476, 2002-09-12, S" t:study_dirflow=S m:study_awdt=13685 m:distance=185 m:study_pmpk=1277 m:intended_days=7 m:actual_days=7 m:seg_compkey=11530 m:study_adt=13110 m:study_ampk=691 m:study_length=672 m:study_max8=8048

series e:qfw2-ekmx d:2002-09-05T12:00:00.000Z t:dir_from_cross_street=W t:study_lane_code=0 t:unitid2=0110 t:study_type="VOLUME COUNT" t:stdy_title_part="SW BARTON ST, W/O 11TH AVE SW" t:title="SW BARTON ST, W/O 11TH AVE SW; TOTAL FLOW; 05SEP2002 12:00" t:stdy_title_part_with_flow="SW BARTON ST, W/O 11TH AVE SW; TOTAL FLOW" t:unitid=17400 t:x_street="11TH AVE SW" t:study_id=102410 t:objectid=3 t:o_street="SW BARTON ST" t:comments="ORIGINAL TITLE: 17400  40W    0 9/ 5/2002 512: 0 711: 0SWBARTON        ST    11            AVSWCOUNTER 162                                          H" t:stdy_label="102410, 2002-09-05, TOTAL" t:study_dirflow=TOTAL m:study_awdt=607 m:distance=169 m:study_pmpk=59 m:intended_days=7 m:actual_days=7 m:seg_compkey=21828 m:study_adt=594 m:study_ampk=39 m:study_length=672 m:study_max8=342
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
| objectid | study_id | title                                                         | start_date | end_date   | actual_days | intended_days | study_length | study_lane_code | study_dirflow | comments                                                                                                             | study_adt | study_awdt | study_max8 | study_ampk | study_pmpk | seg_compkey | unitid | unitid2 | o_street             | x_street         | dir_from_cross_street | stdy_title_part                      | stdy_label                | distance | stdy_year | study_type   | flowmap | hpms | screenline | stdy_title_part_with_flow                    | 
| ======== | ======== | ============================================================= | ========== | ========== | =========== | ============= | ============ | =============== | ============= | ==================================================================================================================== | ========= | ========== | ========== | ========== | ========== | =========== | ====== | ======= | ==================== | ================ | ===================== | ==================================== | ========================= | ======== | ========= | ============ | ======= | ==== | ========== | ============================================ | 
| 1        | 102810   | 5TH AVE NE, S/O NE 112TH S ST; S FLOW; 24OCT2002 15:00        | 1035471600 | 1036076400 | 7           | 7             | 672          | 0               | S             | ORIGINAL TITLE: 3895 590S S 010/24/2002 515: 0 714: 0 5 AVNENE112 S ST COUNTER 116 H                                 | 6092      | 6296       | 3566       | 435        | 515        | 7256        | 03895  | 1100    | 5TH AVE NE           | NE NORTHGATE WAY | S                     | 5TH AVE NE, S/O NE 112TH S ST        | 102810, 2002-10-24, S     | 180      | 2002      | VOLUME COUNT |         |      |            | 5TH AVE NE, S/O NE 112TH S ST; S FLOW        | 
| 2        | 102476   | M L KING JR WAY S, S/O S BRADFORD ST; S FLOW; 12SEP2002 12:00 | 1031832000 | 1032436800 | 7           | 7             | 672          | 0               | S             | ORIGINAL TITLE: 8293 400S S 0 9/12/2002 512: 0 711: 0 M L KING JR WYS S BRADFORD ST COUNTER 148 H                    | 13110     | 13685      | 8048       | 691        | 1277       | 11530       | 08303  | 0390    | M L KING JR WR WAY S | S BRADFORD ST    | S                     | M L KING JR WAY S, S/O S BRADFORD ST | 102476, 2002-09-12, S     | 185      | 2002      | VOLUME COUNT |         |      |            | M L KING JR WAY S, S/O S BRADFORD ST; S FLOW | 
| 3        | 102410   | SW BARTON ST, W/O 11TH AVE SW; TOTAL FLOW; 05SEP2002 12:00    | 1031227200 | 1031832000 | 7           | 7             | 672          | 0               | TOTAL         | ORIGINAL TITLE: 17400 40W 0 9/ 5/2002 512: 0 711: 0SWBARTON ST 11 AVSWCOUNTER 162 H                                  | 594       | 607        | 342        | 39         | 59         | 21828       | 17400  | 0110    | SW BARTON ST         | 11TH AVE SW      | W                     | SW BARTON ST, W/O 11TH AVE SW        | 102410, 2002-09-05, TOTAL | 169      | 2002      | VOLUME COUNT |         |      |            | SW BARTON ST, W/O 11TH AVE SW; TOTAL FLOW    | 
| 4        | 102461   | ALASKAN WAY, SE/O BLANCHARD ST; S FLOW; 11SEP2002 11:00       | 1031742000 | 1032346800 | 7           | 7             | 672          | 0               | S             | ORIGINAL TITLE: 5045 230S S 0 9/11/2002 411: 0 710: 0 ALASKAN WY BLANCHARD ST COUNTER 165 H                          | 5372      | 5329       | 3077       | 325        | 521        | 8728        | 05045  | 0210    | ALASKAN WAY          | LENORA ST        | S                     | ALASKAN WAY, SE/O BLANCHARD ST       | 102461, 2002-09-11, S     | 213.5    | 2002      | VOLUME COUNT |         |      |            | ALASKAN WAY, SE/O BLANCHARD ST; S FLOW       | 
| 5        | 102146   | S LUCILE ST, E/O 4TH AVE S; W FLOW; 08AUG2002 13:00           | 1028811600 | 1029416400 | 7           | 7             | 672          | 0               | W             | ORIGINAL TITLE: 16495 60E W 0 8/ 8/2002 513: 0 712: 0S LUCILE ST 4 AVS COUNTER 147 CH2 MINUS CH1 H                   | 2662      | 3383       | 2240       | 255        | 399        | 20693       | 16495  | 0040    | S LUCILE ST          | 4TH AVE S        | E                     | S LUCILE ST, E/O 4TH AVE S           | 102146, 2002-08-08, W     | 147.5    | 2002      | VOLUME COUNT |         |      |            | S LUCILE ST, E/O 4TH AVE S; W FLOW           | 
| 6        | 102139   | N 60TH ST, E/O PHINNEY AVE N; W FLOW; 07AUG2002 12:00         | 1028721600 | 1029326400 | 7           | 7             | 672          | 0               | W             | ORIGINAL TITLE: 12300 40E W 0 8/ 7/2002 412: 0 711: 0N 60 ST PHINNEY AVN COUNTER 114 H                               | 313       | 317        | 215        | 19         | 45         | 15734       | 12300  | 0040    | N 60TH ST            | PHINNEY AVE N    | E                     | N 60TH ST, E/O PHINNEY AVE N         | 102139, 2002-08-07, W     | 185      | 2002      | VOLUME COUNT |         |      |            | N 60TH ST, E/O PHINNEY AVE N; W FLOW         | 
| 7        | 101846   | 3RD AVE, SE/O UNION ST; N FLOW; 10JUL2002 09:30               | 1026293400 | 1026898200 | 7           | 7             | 672          | 0               | N             | ORIGINAL TITLE: 2080 100S N 0 7/10/2002 4 9:41 7 9:15 3 AV UNION ST COUNTER 131 H                                    | 6765      | 7293       | 3789       | 453        | 675        | 4382        | 02080  | 0130    | 3RD AVE              | UNIVERSITY ST    | S                     | 3RD AVE, SE/O UNION ST               | 101846, 2002-07-10, N     | 213      | 2002      | VOLUME COUNT |         |      |            | 3RD AVE, SE/O UNION ST; N FLOW               | 
| 8        | 101842   | E MADISON ST, SW/O 17TH AVE; W FLOW; 10JUL2002 11:00          | 1026298800 | 1026903600 | 7           | 7             | 672          | 0               | W             | ORIGINAL TITLE: 11275 115W W 0 7/10/2002 411: 0 710: 0E MADISON ST 17 AV COUNTER 109 H                               | 10810     | 11782      | 5926       | 939        | 785        | 14348       | 11275  | 0169    | E MADISON ST         | E PINE ST        | W                     | E MADISON ST, SW/O 17TH AVE          | 101842, 2002-07-10, W     | 147      | 2002      | VOLUME COUNT |         |      |            | E MADISON ST, SW/O 17TH AVE; W FLOW          | 
| 9        | 101839   | S DAKOTA ST, W/O 2ND AVE S; E FLOW; 11JUL2002 11:00           | 1026385200 | 1026990000 | 7           | 7             | 672          | 6               | E             | ORIGINAL TITLE: 15695 10W E 6 7/11/2002 511: 0 710: 0S DAKOTA ST 1 AVS VI COUNTER 121 HIGH, MARGINAL TUBE LOCATION H | 274       | 362        | 296        | 36         | 77         | 19746       | 15695  | 0010    | S DAKOTA ST          | 1ST AV S VI      | W                     | S DAKOTA ST, W/O 2ND AVE S           | 101839, 2002-07-11, E     | 274.5    | 2002      | VOLUME COUNT |         |      |            | S DAKOTA ST, W/O 2ND AVE S; E FLOW           | 
| 10       | 102798   | 35TH AVE NE, N/O NE 75TH ST; N FLOW; 23OCT2002 15:00          | 1035385200 | 1035990000 | 7           | 7             | 672          | 0               | N             | ORIGINAL TITLE: 2705 130N N 010/23/2002 415: 0 714: 0 35 AVNENE75 ST COUNTER 159 H                                   | 7278      | 7798       | 5003       | 454        | 873        | 5363        | 02705  | 0750    | 35TH AVE NE          | NE 75TH ST       | N                     | 35TH AVE NE, N/O NE 75TH ST          | 102798, 2002-10-23, N     | 330      | 2002      | VOLUME COUNT |         |      |            | 35TH AVE NE, N/O NE 75TH ST; N FLOW          | 
```