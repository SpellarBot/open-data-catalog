# Traffic Count Details [arcgis_rest_services_SDOT_EXT_DSG_datasharing_MapServer_77]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-count-details) |
| Metadata | [Link](https://data.seattle.gov/api/views/qfw2-ekmx) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qfw2-ekmx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qfw2-ekmx/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qfw2-ekmx |
| Name | Traffic Count Details [arcgis_rest_services_SDOT_EXT_DSG_datasharing_MapServer_77] |
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
series e:qfw2-ekmx d:2009-11-10T11:15:00.000Z t:dir_from_cross_street=SE t:comments="This study is an aggregate of the following source studies: 217878, 217879" t:stdy_label="316946, 2009-11-10, TOTAL" t:study_id=316946 t:title="ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW; CH(AGG); 10NOV2009 11:15" t:study_dirflow=TOTAL t:stdy_title_part_with_flow="ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW; CH(AGG)" t:o_street="ALASKAN WAY" t:study_type=AGGREGATE t:x_street="LENORA ST" t:unitid=05045 t:study_lane_code=STANDARD t:stdy_title_part="ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW" t:objectid=1 t:unitid2=0210 m:study_adt=9374 m:actual_days=7 m:seg_compkey=8728 m:distance=213.5 m:intended_days=7 m:study_ampk=687 m:study_awdt=9926 m:study_max8=5949 m:study_length=672 m:study_pmpk=1210

series e:qfw2-ekmx d:2016-05-23T10:45:00.000Z t:dir_from_cross_street=E t:stdy_label="320359, 2016-05-23, W" t:study_id=320359 t:title="REPUBLICAN ST, E/O 9TH AVE N; W FLOW; CH(WB); 23May2016 10:45" t:study_dirflow=W t:stdy_title_part_with_flow="REPUBLICAN ST, E/O 9TH AVE N; W FLOW" t:o_street="REPUBLICAN ST" t:study_type="VOLUME COUNT" t:x_street="9TH AVE N" t:unitid=09455 t:study_lane_code=STANDARD t:stdy_title_part="REPUBLICAN ST, E/O 9TH AVE N" t:objectid=2 t:unitid2=0090 m:study_adt=825 m:actual_days=7 m:seg_compkey=12561 m:distance=161 m:intended_days=7 m:study_ampk=115 m:study_awdt=968 m:study_max8=621 m:study_length=672 m:study_pmpk=74

series e:qfw2-ekmx d:2017-03-28T13:00:00.000Z t:dir_from_cross_street=SW t:stdy_label="322874, 2017-03-28, NE" t:study_id=322874 t:title="S CLOVERDALE PL, SW/O GRATTAN PL S; NE FLOW; CHNEB; 28Mar2017 13:00" t:study_dirflow=NE t:stdy_title_part_with_flow="S CLOVERDALE PL, SW/O GRATTAN PL S; NE FLOW" t:o_street="S CLOVERDALE PL" t:study_type="VOLUME COUNT" t:x_street="RAINIER AVE S" t:unitid=15591 t:study_lane_code=STANDARD t:stdy_title_part="S CLOVERDALE PL, SW/O GRATTAN PL S" t:objectid=3 t:unitid2=0510 m:study_adt=929 m:actual_days=7 m:seg_compkey=9694 m:distance=339.5 m:intended_days=7 m:study_ampk=80 m:study_awdt=964 m:study_max8=579 m:study_length=672 m:study_pmpk=97
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

entity e:qfw2-ekmx l:"Traffic Count Details [arcgis_rest_services_SDOT_EXT_DSG_datasharing_MapServer_77]" t:url=https://data.seattle.gov/api/views/qfw2-ekmx

property e:qfw2-ekmx t:meta.view d:2017-09-25T07:23:20.092Z v:averageRating=0 v:name="Traffic Count Details [arcgis_rest_services_SDOT_EXT_DSG_datasharing_MapServer_77]" v:attributionLink=http://www.seattle.gov/transportation/ v:id=qfw2-ekmx v:category=Transportation

property e:qfw2-ekmx t:meta.view.license d:2017-09-25T07:23:20.092Z v:name="Public Domain"

property e:qfw2-ekmx t:meta.view.owner d:2017-09-25T07:23:20.092Z v:displayName="SDOT GIS" v:lastNotificationSeenAt=1504648993 v:id=geh9-fb2x v:screenName="SDOT GIS"

property e:qfw2-ekmx t:meta.view.tableauthor d:2017-09-25T07:23:20.092Z v:displayName="SDOT GIS" v:lastNotificationSeenAt=1504648993 v:roleName=publisher v:id=geh9-fb2x v:screenName="SDOT GIS"
```

## Top Records

```ls
| objectid | study_id | title                                                                       | start_date | end_date   | actual_days | intended_days | study_length | study_lane_code | study_dirflow | comments                                                                   | study_adt | study_awdt | study_max8 | study_ampk | study_pmpk | seg_compkey | unitid | unitid2 | o_street              | x_street      | dir_from_cross_street | stdy_title_part                            | stdy_label                | distance | stdy_year | study_type   | flowmap | hpms | screenline | stdy_title_part_with_flow                           | 
| ======== | ======== | =========================================================================== | ========== | ========== | =========== | ============= | ============ | =============== | ============= | ========================================================================== | ========= | ========== | ========== | ========== | ========== | =========== | ====== | ======= | ===================== | ============= | ===================== | ========================================== | ========================= | ======== | ========= | ============ | ======= | ==== | ========== | =================================================== | 
| 1        | 316946   | ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW; CH(AGG); 10NOV2009 11:15        | 1257851700 | 1258456500 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 217878, 217879 | 9374      | 9926       | 5949       | 687        | 1210       | 8728        | 05045  | 0210    | ALASKAN WAY           | LENORA ST     | SE                    | ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW | 316946, 2009-11-10, TOTAL | 213.5    | 2009      | AGGREGATE    |         |      |            | ALASKAN WAY, SE/O BLANCHARD ST, TOTAL FLOW; CH(AGG) | 
| 2        | 320359   | REPUBLICAN ST, E/O 9TH AVE N; W FLOW; CH(WB); 23May2016 10:45               | 1464000300 | 1464605100 | 7           | 7             | 672          | STANDARD        | W             |                                                                            | 825       | 968        | 621        | 115        | 74         | 12561       | 09455  | 0090    | REPUBLICAN ST         | 9TH AVE N     | E                     | REPUBLICAN ST, E/O 9TH AVE N               | 320359, 2016-05-23, W     | 161      | 2016      | VOLUME COUNT |         |      |            | REPUBLICAN ST, E/O 9TH AVE N; W FLOW                | 
| 3        | 322874   | S CLOVERDALE PL, SW/O GRATTAN PL S; NE FLOW; CHNEB; 28Mar2017 13:00         | 1490706000 | 1491310800 | 7           | 7             | 672          | STANDARD        | NE            |                                                                            | 929       | 964        | 579        | 80         | 97         | 9694        | 15591  | 0510    | S CLOVERDALE PL       | RAINIER AVE S | SW                    | S CLOVERDALE PL, SW/O GRATTAN PL S         | 322874, 2017-03-28, NE    | 339.5    | 2017      | VOLUME COUNT |         |      |            | S CLOVERDALE PL, SW/O GRATTAN PL S; NE FLOW         | 
| 4        | 317299   | ALASKAN WAY, SE/O BLANCHARD ST; N FLOW; CHSENSOR A; 24Jul2015 09:15         | 1437729300 | 1438334100 | 7           | 7             | 672          | STANDARD        | N             |                                                                            | 10828     | 10833      | 6056       | 813        | 948        | 8728        | 05045  | 0210    | ALASKAN WAY           | LENORA ST     | SE                    | ALASKAN WAY, SE/O BLANCHARD ST             | 317299, 2015-07-24, N     | 213.5    | 2015      | VOLUME COUNT |         |      |            | ALASKAN WAY, SE/O BLANCHARD ST; N FLOW              | 
| 5        | 319636   | S LANDER ST, W/O 6TH AVE S; W FLOW; CHSENSOR B; 06Apr2016 09:45             | 1459935900 | 1460540700 | 7           | 7             | 672          | STANDARD        | W             |                                                                            | 6529      | 7567       | 4649       | 712        | 592        | 20628       | 16420  | 0050    | S LANDER ST           | 5TH PL S      | W                     | S LANDER ST, W/O 6TH AVE S                 | 319636, 2016-04-06, W     | 95       | 2016      | VOLUME COUNT |         |      |            | S LANDER ST, W/O 6TH AVE S; W FLOW                  | 
| 6        | 318742   | NE 65TH ST, W/O 25TH AVE NE; E FLOW; CHSENSOR A; 25Jan2016 11:30            | 1453721400 | 1454326200 | 7           | 7             | 672          | STANDARD        | E             |                                                                            | 5827      | 6020       | 3457       | 415        | 545        | 17277       | 13465  | 0240    | NE 65TH ST            | 24TH AVE NE   | W                     | NE 65TH ST, W/O 25TH AVE NE                | 318742, 2016-01-25, E     | 126      | 2016      | VOLUME COUNT | Y       |      |            | NE 65TH ST, W/O 25TH AVE NE; E FLOW                 | 
| 7        | 317031   | EAST GREEN LAKE WAY N, NE/O N 57TH ST; TOTAL FLOW; CH(AGG); 10FEB2009 11:00 | 1234263600 | 1234868400 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 215861, 215862 | 15028     | 15717      | 9440       | 1106       | 1558       | 14073       | 11075  | 0570    | EAST GREEN LAKE WAY N | N 57TH ST     | NE                    | EAST GREEN LAKE WAY N, NE/O N 57TH ST      | 317031, 2009-02-10, TOTAL | 531      | 2009      | AGGREGATE    |         |      |            | EAST GREEN LAKE WAY N, NE/O N 57TH ST; TOTAL FLOW   | 
| 8        | 317935   | HOLMAN RD NW, NE/O 13TH E AVE NW; NE FLOW; CHSENSOR D; 16Jun2015 10:45      | 1434451500 | 1435056300 | 7           | 7             | 672          | STANDARD        | NE            |                                                                            | 12426     | 12862      | 7211       | 762        | 1092       | 10940       | 07360  | 0920    | HOLMAN RD NW          | 13TH E AVE NW | NE                    | HOLMAN RD NW, NE/O 13TH E AVE NW           | 317935, 2015-06-16, NE    | 195      | 2015      | VOLUME COUNT |         |      |            | HOLMAN RD NW, NE/O 13TH E AVE NW; NE FLOW           | 
| 9        | 319055   | S LANDER ST, W/O 6TH AVE S; TOTAL FLOW; CH(AGG); 30Sep2015 11:15            | 1443611700 | 1444216500 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 318102, 318103 | 11349     | 13247      | 7777       | 965        | 1113       | 20628       | 16420  | 0050    | S LANDER ST           | 5TH PL S      | W                     | S LANDER ST, W/O 6TH AVE S                 | 319055, 2015-09-30, TOTAL | 95       | 2015      | AGGREGATE    |         |      |            | S LANDER ST, W/O 6TH AVE S; TOTAL FLOW              | 
| 10       | 323555   | RAINIER AVE S, S/O S OTHELLO ST; N FLOW; CH1; 09May2017 10:45               | 1494326700 | 1494931500 | 7           | 7             | 672          | STANDARD        | N             |                                                                            | 10027     | 10555      | 5749       | 1043       | 684        | 12409       | 09345  | 0730    | RAINIER AVE S         | S OTHELLO ST  | S                     | RAINIER AVE S, S/O S OTHELLO ST            | 323555, 2017-05-09, N     | 190      | 2017      | VOLUME COUNT |         |      |            | RAINIER AVE S, S/O S OTHELLO ST; N FLOW             | 
```