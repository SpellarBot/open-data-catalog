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
series e:qfw2-ekmx d:2014-09-23T12:00:00.000Z t:dir_from_cross_street=E t:study_lane_code=STANDARD t:unitid2=0070 t:study_type=AGGREGATE t:stdy_title_part="NW 58TH ST, E/O 8TH AVE NW" t:title="NW 58TH ST, E/O 8TH AVE NW; TOTAL FLOW; CH(AGG); 23Sep2014 12:00" t:stdy_title_part_with_flow="NW 58TH ST, E/O 8TH AVE NW; TOTAL FLOW" t:unitid=14565 t:x_street="7TH AVE NW" t:study_id=321580 t:objectid=1 t:o_street="NW 58TH ST" t:comments="This study is an aggregate of the following source studies: 321527, 321528" t:stdy_label="321580, 2014-09-23, TOTAL" t:study_dirflow=TOTAL m:study_awdt=396 m:distance=133.5 m:actual_days=7 m:intended_days=7 m:study_pmpk=55 m:study_adt=371 m:seg_compkey=18491 m:study_length=672 m:study_ampk=62 m:study_max8=298

series e:qfw2-ekmx d:2015-03-19T10:15:00.000Z t:dir_from_cross_street=S t:study_lane_code=STANDARD t:unitid2=0730 t:study_type="VOLUME COUNT" t:stdy_title_part="RAINIER AVE S, S/O S OTHELLO ST" t:title="RAINIER AVE S, S/O S OTHELLO ST; S FLOW; CHSENSOR A; 19Mar2015 10:15" t:stdy_title_part_with_flow="RAINIER AVE S, S/O S OTHELLO ST; S FLOW" t:unitid=09345 t:x_street="S OTHELLO ST" t:study_id=315485 t:objectid=2 t:o_street="RAINIER AVE S" t:stdy_label="315485, 2015-03-19, S" t:study_dirflow=S m:study_awdt=12281 m:distance=190 m:actual_days=7 m:intended_days=7 m:study_pmpk=841 m:study_adt=11694 m:seg_compkey=12409 m:study_length=672 m:study_ampk=1128 m:study_max8=6774

series e:qfw2-ekmx d:2014-09-18T11:00:00.000Z t:dir_from_cross_street=N t:study_lane_code=STANDARD t:unitid2=0841 t:study_type="VOLUME COUNT" t:stdy_title_part="RENTON AVE S, N/O S CLOVERDALE ST" t:title="RENTON AVE S, N/O S CLOVERDALE ST; N FLOW; CHSENSOR A; 18Sep2014 11:00" t:stdy_title_part_with_flow="RENTON AVE S, N/O S CLOVERDALE ST; N FLOW" t:unitid=09425 t:x_street="S CAMANO PL" t:study_id=314417 t:objectid=3 t:o_street="RENTON AVE S" t:stdy_label="314417, 2014-09-18, N" t:study_dirflow=N m:study_awdt=4447 m:distance=249 m:actual_days=7 m:intended_days=7 m:study_pmpk=335 m:study_adt=4400 m:seg_compkey=12522 m:study_length=672 m:study_ampk=401 m:study_max8=2450
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

property e:qfw2-ekmx t:meta.view d:2017-06-09T13:52:00.895Z v:id=qfw2-ekmx v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="Traffic Count Details [arcgis_rest_services_SDOT_EXT_DSG_datasharing_MapServer_77]"

property e:qfw2-ekmx t:meta.view.license d:2017-06-09T13:52:00.895Z v:name="Public Domain"

property e:qfw2-ekmx t:meta.view.owner d:2017-06-09T13:52:00.895Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:qfw2-ekmx t:meta.view.tableauthor d:2017-06-09T13:52:00.895Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | study_id | title                                                                      | start_date | end_date   | actual_days | intended_days | study_length | study_lane_code | study_dirflow | comments                                                                   | study_adt | study_awdt | study_max8 | study_ampk | study_pmpk | seg_compkey | unitid | unitid2 | o_street            | x_street      | dir_from_cross_street | stdy_title_part                      | stdy_label                | distance | stdy_year | study_type   | flowmap | hpms | screenline | stdy_title_part_with_flow                        | 
| ======== | ======== | ========================================================================== | ========== | ========== | =========== | ============= | ============ | =============== | ============= | ========================================================================== | ========= | ========== | ========== | ========== | ========== | =========== | ====== | ======= | =================== | ============= | ===================== | ==================================== | ========================= | ======== | ========= | ============ | ======= | ==== | ========== | ================================================ | 
| 1        | 321580   | NW 58TH ST, E/O 8TH AVE NW; TOTAL FLOW; CH(AGG); 23Sep2014 12:00           | 1411473600 | 1412078400 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 321527, 321528 | 371       | 396        | 298        | 62         | 55         | 18491       | 14565  | 0070    | NW 58TH ST          | 7TH AVE NW    | E                     | NW 58TH ST, E/O 8TH AVE NW           | 321580, 2014-09-23, TOTAL | 133.5    | 2014      | AGGREGATE    |         |      |            | NW 58TH ST, E/O 8TH AVE NW; TOTAL FLOW           | 
| 2        | 315485   | RAINIER AVE S, S/O S OTHELLO ST; S FLOW; CHSENSOR A; 19Mar2015 10:15       | 1426760100 | 1427364900 | 7           | 7             | 672          | STANDARD        | S             |                                                                            | 11694     | 12281      | 6774       | 1128       | 841        | 12409       | 09345  | 0730    | RAINIER AVE S       | S OTHELLO ST  | S                     | RAINIER AVE S, S/O S OTHELLO ST      | 315485, 2015-03-19, S     | 190      | 2015      | VOLUME COUNT |         |      |            | RAINIER AVE S, S/O S OTHELLO ST; S FLOW          | 
| 3        | 314417   | RENTON AVE S, N/O S CLOVERDALE ST; N FLOW; CHSENSOR A; 18Sep2014 11:00     | 1411038000 | 1411642800 | 7           | 7             | 672          | STANDARD        | N             |                                                                            | 4400      | 4447       | 2450       | 401        | 335        | 12522       | 09425  | 0841    | RENTON AVE S        | S CAMANO PL   | N                     | RENTON AVE S, N/O S CLOVERDALE ST    | 314417, 2014-09-18, N     | 249      | 2014      | VOLUME COUNT |         |      |            | RENTON AVE S, N/O S CLOVERDALE ST; N FLOW        | 
| 4        | 318658   | EAST MARGINAL WAY S, S/O S ALASKA ST; S FLOW; CHSENSOR B; 12Jan2016 12:00  | 1452600000 | 1453204800 | 7           | 7             | 672          | STANDARD        | S             |                                                                            | 22352     | 26139      | 15004      | 1599       | 2469       | 14395       | 11300  | 0480    | EAST MARGINAL WAY S | S ALASKA ST   | S                     | EAST MARGINAL WAY S, S/O S ALASKA ST | 318658, 2016-01-12, S     | 140      | 2016      | VOLUME COUNT |         |      |            | EAST MARGINAL WAY S, S/O S ALASKA ST; S FLOW     | 
| 5        | 317271   | UNIVERSITY BR, SW/O POINT A; TOTAL FLOW; CH(AGG); 10MAR2009 11:30          | 1236684600 | 1237289400 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 216071, 216072 | 25798     | 28508      | 17484      | 2419       | 2931       | 13189       | 10110  | 0330    | UNIVERSITY BR       | FUHRMAN AVE E | SW                    | UNIVERSITY BR, SW/O POINT A          | 317271, 2009-03-10, TOTAL | 185      | 2009      | AGGREGATE    |         |      |            | UNIVERSITY BR, SW/O POINT A; TOTAL FLOW          | 
| 6        | 316287   | M L KING JR WAY, N/O E YESLER WAY; S FLOW; CHSENSOR A; 12May2015 08:45     | 1431420300 | 1432025100 | 7           | 7             | 672          | STANDARD        | S             |                                                                            | 7404      | 8109       | 4999       | 517        | 842        | 11481       | 08291  | 0010    | M L KING JR WAY     | E YESLER WAY  | N                     | M L KING JR WAY, N/O E YESLER WAY    | 316287, 2015-05-12, S     | 182.5    | 2015      | VOLUME COUNT |         |      |            | M L KING JR WAY, N/O E YESLER WAY; S FLOW        | 
| 7        | 319136   | EAST MARGINAL WAY S, S/O S ALASKA ST; TOTAL FLOW; CH(AGG); 14Jul2015 11:45 | 1436874300 | 1437479100 | 7           | 7             | 672          | STANDARD        | TOTAL         | This study is an aggregate of the following source studies: 316841, 316842 | 55520     | 62154      | 33351      | 4425       | 4875       | 14395       | 11300  | 0480    | EAST MARGINAL WAY S | S ALASKA ST   | S                     | EAST MARGINAL WAY S, S/O S ALASKA ST | 319136, 2015-07-14, TOTAL | 140      | 2015      | AGGREGATE    |         |      |            | EAST MARGINAL WAY S, S/O S ALASKA ST; TOTAL FLOW | 
| 8        | 321300   | GREEN LAKE DR N, SE/O STONE AVE N; SE FLOW; CHSEB; 22Sep2016 12:45         | 1474548300 | 1475153100 | 7           | 7             | 672          | STANDARD        | SE            |                                                                            | 1505      | 1569       | 948        | 142        | 121        | 10682       | 07090  | 0800    | GREEN LAKE DR N     | N 80TH ST     | SE                    | GREEN LAKE DR N, SE/O STONE AVE N    | 321300, 2016-09-22, SE    | 213      | 2016      | VOLUME COUNT |         |      |            | GREEN LAKE DR N, SE/O STONE AVE N; SE FLOW       | 
| 9        | 317995   | AURORA AVE N, S/O N 112TH ST; S FLOW; CH4; 31Aug2015 11:30                 | 1441020600 | 1441625400 | 7           | 7             | 672          | STANDARD        | S             |                                                                            | 15410     | 16549      | 9339       | 1206       | 1278       | 8988        | 05250  | 1090    | AURORA AVE N        | N 109TH ST    | S                     | AURORA AVE N, S/O N 112TH ST         | 317995, 2015-08-31, S     | 371      | 2015      | VOLUME COUNT |         |      |            | AURORA AVE N, S/O N 112TH ST; S FLOW             | 
| 10       | 320874   | RAINIER AVE S, S/O S OTHELLO ST; S FLOW; CHSENSOR A; 03Aug2016 11:45       | 1470224700 | 1470829500 | 7           | 7             | 672          | STANDARD        | S             |                                                                            | 12406     | 12760      | 7332       | 645        | 1193       | 12409       | 09345  | 0730    | RAINIER AVE S       | S OTHELLO ST  | S                     | RAINIER AVE S, S/O S OTHELLO ST      | 320874, 2016-08-03, S     | 190      | 2016      | VOLUME COUNT |         |      |            | RAINIER AVE S, S/O S OTHELLO ST; S FLOW          | 
```