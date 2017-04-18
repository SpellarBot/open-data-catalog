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
series e:qfw2-ekmx d:2011-11-08T11:00:00.000Z t:dir_from_cross_street=S t:study_lane_code=STANDARD t:unitid2=0730 t:study_type="VOLUME COUNT" t:hpms=Y t:flowmap=Y t:stdy_title_part="12TH AVE NE, S/O NE 75TH ST" t:screenline=Y t:stdy_title_part_with_flow="12TH AVE NE, S/O NE 75TH ST; N FLOW" t:title="12TH AVE NE, S/O NE 75TH ST; N FLOW; CHD TUBE; 08Nov2011 11:00" t:unitid=00330 t:x_street="NE 73RD ST" t:study_id=304349 t:objectid=1 t:o_street="12TH AVE NE" t:stdy_label="304349, 2011-11-08, N" t:study_dirflow=N m:study_awdt=8387 m:distance=284 m:study_pmpk=1096 m:intended_days=7 m:actual_days=7 m:seg_compkey=1589 m:study_adt=7834 m:study_ampk=424 m:study_length=672 m:study_max8=5492

series e:qfw2-ekmx d:2012-05-02T12:15:00.000Z t:dir_from_cross_street=SE t:study_lane_code=STANDARD t:unitid2=0840 t:study_type="VOLUME COUNT" t:stdy_title_part="WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP" t:title="WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP; NW FLOW; CHB TUBE; 02May2012 12:15" t:stdy_title_part_with_flow="WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP; NW FLOW" t:unitid=09781 t:x_street="CLOVERDALE ST ON RP" t:study_id=307902 t:objectid=2 t:o_street="WEST MARGINAL NB WAY S" t:stdy_label="307902, 2012-05-02, NW" t:study_dirflow=NW m:study_awdt=20223 m:distance=1518.5 m:study_pmpk=1713 m:intended_days=7 m:actual_days=7 m:seg_compkey=490543 m:study_adt=17247 m:study_ampk=1665 m:study_length=672 m:study_max8=11650

series e:qfw2-ekmx d:2011-02-16T11:00:00.000Z t:dir_from_cross_street=SE t:study_lane_code="AGGREGATE ELEMENT" t:unitid2=0120 t:study_type="VOLUME COUNT" t:stdy_title_part="4TH AVE, SE/O UNIVERSITY ST" t:title="4TH AVE, SE/O UNIVERSITY ST; NW FLOW; (EL) TUBE; 16Feb2011 11:00" t:stdy_title_part_with_flow="4TH AVE, SE/O UNIVERSITY ST; NW FLOW" t:unitid=03130 t:x_street="SENECA ST" t:study_id=301830 t:objectid=3 t:o_street="4TH AVE" t:stdy_label="301830, 2011-02-16, NW" t:study_dirflow=NW m:study_awdt=17997 m:distance=153 m:study_pmpk=1432 m:intended_days=7 m:actual_days=7 m:seg_compkey=6128 m:study_adt=16714 m:study_ampk=1430 m:study_length=672 m:study_max8=9859
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
| objectid | study_id | title                                                                                | start_date | end_date   | actual_days | intended_days | study_length | study_lane_code   | study_dirflow | comments                                                                              | study_adt | study_awdt | study_max8 | study_ampk | study_pmpk | seg_compkey | unitid | unitid2 | o_street               | x_street            | dir_from_cross_street | stdy_title_part                                  | stdy_label                | distance | stdy_year | study_type   | flowmap | hpms | screenline | stdy_title_part_with_flow                                 | 
| ======== | ======== | ==================================================================================== | ========== | ========== | =========== | ============= | ============ | ================= | ============= | ===================================================================================== | ========= | ========== | ========== | ========== | ========== | =========== | ====== | ======= | ====================== | =================== | ===================== | ================================================ | ========================= | ======== | ========= | ============ | ======= | ==== | ========== | ========================================================= | 
| 1        | 304349   | 12TH AVE NE, S/O NE 75TH ST; N FLOW; CHD TUBE; 08Nov2011 11:00                       | 1320750000 | 1321354800 | 7           | 7             | 672          | STANDARD          | N             |                                                                                       | 7834      | 8387       | 5492       | 424        | 1096       | 1589        | 00330  | 0730    | 12TH AVE NE            | NE 73RD ST          | S                     | 12TH AVE NE, S/O NE 75TH ST                      | 304349, 2011-11-08, N     | 284      | 2011      | VOLUME COUNT | Y       | Y    | Y          | 12TH AVE NE, S/O NE 75TH ST; N FLOW                       | 
| 2        | 307902   | WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP; NW FLOW; CHB TUBE; 02May2012 12:15 | 1335960900 | 1336565700 | 7           | 7             | 672          | STANDARD          | NW            |                                                                                       | 17247     | 20223      | 11650      | 1665       | 1713       | 490543      | 09781  | 0840    | WEST MARGINAL NB WAY S | CLOVERDALE ST ON RP | SE                    | WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP | 307902, 2012-05-02, NW    | 1518.5   | 2012      | VOLUME COUNT |         |      |            | WEST MARGINAL NB WAY S, SE/O CLOVERDALE ST ON RP; NW FLOW | 
| 3        | 301830   | 4TH AVE, SE/O UNIVERSITY ST; NW FLOW; (EL) TUBE; 16Feb2011 11:00                     | 1297854000 | 1298458800 | 7           | 7             | 672          | AGGREGATE ELEMENT | NW            |                                                                                       | 16714     | 17997      | 9859       | 1430       | 1432       | 6128        | 03130  | 0120    | 4TH AVE                | SENECA ST           | SE                    | 4TH AVE, SE/O UNIVERSITY ST                      | 301830, 2011-02-16, NW    | 153      | 2011      | VOLUME COUNT |         |      |            | 4TH AVE, SE/O UNIVERSITY ST; NW FLOW                      | 
| 4        | 304686   | NE 75TH ST, W/O 30TH AVE NE; TOTAL FLOW; CH(AGG); 28Nov2011 12:30                    | 1322483400 | 1323088200 | 7           | 7             | 672          | STANDARD          | TOTAL         | This study is an aggregate of the following source studies: 304480, 304200            | 16039     | 16679      | 10027      | 1421       | 1484       | 17527       | 13595  | 0280    | NE 75TH ST             | 28TH AVE NE         | W                     | NE 75TH ST, W/O 30TH AVE NE                      | 304686, 2011-11-28, TOTAL | 162      | 2011      | AGGREGATE    | Y       | Y    |            | NE 75TH ST, W/O 30TH AVE NE; TOTAL FLOW                   | 
| 5        | 308813   | JAMES ST, NE/O 7TH AVE; NE FLOW; CH1; 03Feb2011 10:15                                | 1296728100 | 1297332900 | 7           | 7             | 672          | STANDARD          | NE            | This study is an aggregate of the following source studies: 218233 (2010 DATA)        | 13070     | 14671      | 7994       | 1163       | 958        | 11055       | 07885  | 0070    | JAMES ST               | 7TH AVE             | NE                    | JAMES ST, NE/O 7TH AVE                           | 308813, 2011-02-03, NE    | 161      | 2011      | AGGREGATE    |         |      |            | JAMES ST, NE/O 7TH AVE; NE FLOW                           | 
| 6        | 81993    | 17TH AVE NW, N/O NW MARKET ST; S FLOW; 31AUG2000 11:00                               | 967719600  | 968324400  | 7           | 7             | 672          | 0                 | S             | ORIGINAL TITLE: 775 110N S 0 8/31/2000 511: 0 710: 0 17 AVNWNWMARKET ST COUNTER 102 H | 0         | 1832       | 1119       | 154        | 161        | 2440        | 00775  | 0550    | 17TH AVE NW            | NW MARKET ST        | N                     | 17TH AVE NW, N/O NW MARKET ST                    | 81993, 2000-08-31, S      | 141.5    | 2000      | VOLUME COUNT |         |      |            | 17TH AVE NW, N/O NW MARKET ST; S FLOW                     | 
| 7        | 302750   | N 85TH ST, W/O ASHWORTH AVE N; W FLOW; CHA TUBE; 10May2011 12:00                     | 1305028800 | 1305633600 | 7           | 7             | 672          | STANDARD          | W             |                                                                                       | 15005     | 15045      | 7904       | 867        | 1138       | 15962       | 12500  | 0140    | N 85TH ST              | INTERLAKE E AVE N   | W                     | N 85TH ST, W/O ASHWORTH AVE N                    | 302750, 2011-05-10, W     | 134      | 2011      | VOLUME COUNT |         |      |            | N 85TH ST, W/O ASHWORTH AVE N; W FLOW                     | 
| 8        | 305278   | 9TH AVE NE, N/O NE 75TH ST; S FLOW; CHB TUBE; 31Jan2012 11:30                        | 1328009400 | 1328614200 | 7           | 7             | 672          | STANDARD          | S             |                                                                                       | 39        | 43         | 36         | 5          | 7          | 8555        | 04900  | 0750    | 9TH AVE NE             | NE 75TH ST          | N                     | 9TH AVE NE, N/O NE 75TH ST                       | 305278, 2012-01-31, S     | 328      | 2012      | VOLUME COUNT |         |      |            | 9TH AVE NE, N/O NE 75TH ST; S FLOW                        | 
| 9        | 307865   | S ROYAL BROUGHAM WAY, E/O 4TH AVE S; TOTAL FLOW; CH(AGG); 07Feb2011 11:30            | 1297078200 | 1297683000 | 7           | 7             | 672          | STANDARD          | TOTAL         | This study is an aggregate of the following source studies: 301588, 301589            | 6700      | 7865       | 4749       | 706        | 692        | 21217       | 16895  | 0040    | S ROYAL BROUGHAM WAY   | 4TH AVE S           | E                     | S ROYAL BROUGHAM WAY, E/O 4TH AVE S              | 307865, 2011-02-07, TOTAL | 204      | 2011      | AGGREGATE    |         | Y    |            | S ROYAL BROUGHAM WAY, E/O 4TH AVE S; TOTAL FLOW           | 
| 10       | 303303   | M L KING JR WAY S, N/O S ANDOVER ST; TOTAL FLOW;(ER&WR) CH(AGG); 14Oct2010 13:00     | 1287061200 | 1287666000 | 7           | 7             | 672          | STANDARD          | TOTAL         | This study is an aggregate of the following source studies: 302490, 300841            | 17426     | 18560      | 10391      | 1370       | 1557       | 352636      | 08299  | 0360    | M L KING JR ER WAY S   | RENTON N AVE S      | N                     | M L KING JR WAY S, N/O S ANDOVER ST              | 303303, 2010-10-14, TOTAL | 621      | 2010      | AGGREGATE    |         |      |            | M L KING JR WAY S, N/O S ANDOVER ST; TOTAL FLOW           | 
```