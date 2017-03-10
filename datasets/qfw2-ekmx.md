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
| Yes      | numeric metric | unitid2                   | UNITID2                   | number    | text        |
| Yes      | series tag     | o_street                  | O_STREET                  | text      | text        |
| Yes      | series tag     | x_street                  | X_STREET                  | text      | text        |
| Yes      | series tag     | dir_from_cross_street     | DIR_FROM_CROSS_STREET     | text      | text        |
| Yes      | series tag     | stdy_title_part           | STDY_TITLE_PART           | text      | text        |
| Yes      | series tag     | stdy_label                | STDY_LABEL                | text      | text        |
| Yes      | numeric metric | distance                  | DISTANCE                  | number    | number      |
| No       |                | stdy_year                 | STDY_YEAR                 | number    | number      |
| Yes      | series tag     | study_type                | STUDY_TYPE                | text      | text        |
| Yes      | numeric metric | flowmap                   | FLOWMAP                   | number    | text        |
| Yes      | numeric metric | hpms                      | HPMS                      | number    | text        |
| Yes      | numeric metric | screenline                | SCREENLINE                | number    | text        |
| Yes      | series tag     | stdy_title_part_with_flow | STDY_TITLE_PART_WITH_FLOW | text      | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = stdy_year,end_date
```

## Data Commands

```ls
series e:qfw2-ekmx d:2004-03-30T10:45:00.000Z t:dir_from_cross_street=E t:study_lane_code=STANDARD t:study_type="VOLUME COUNT" t:hpms=Y t:flowmap=Y t:stdy_title_part="NE 75TH ST, E/O 12TH AVE NE" t:title="NE 75TH ST, E/O 12TH AVE NE; W FLOW; CH1; 30MAR2004 10:45*+" t:stdy_title_part_with_flow="NE 75TH ST, E/O 12TH AVE NE; W FLOW" t:unitid=13595 t:x_street="12TH AVE NE" t:study_id=203497 t:objectid=1 t:o_street="NE 75TH ST" t:stdy_label="203497, 2004-03-30, W" t:study_dirflow=W m:study_awdt=10653 m:distance=130 m:study_pmpk=825 m:intended_days=7 m:actual_days=7 m:unitid2=120 m:seg_compkey=17510 m:study_adt=10117 m:study_ampk=885 m:study_length=672 m:study_max8=5633

series e:qfw2-ekmx d:2007-06-13T10:30:00.000Z t:dir_from_cross_street=SE t:stdy_title_part="3RD AVE, SE/O UNION ST" t:stdy_title_part_with_flow="3RD AVE, SE/O UNION ST; SE FLOW" t:title="3RD AVE, SE/O UNION ST; SE FLOW; CH1; 13JUN2007 10:30" t:unitid=02080 t:study_lane_code=STANDARD t:x_street="UNIVERSITY ST" t:study_id=212183 t:study_type="VOLUME COUNT" t:objectid=2 t:o_street="3RD AVE" t:stdy_label="212183, 2007-06-13, SE" t:study_dirflow=SE m:study_awdt=4713 m:distance=213 m:study_pmpk=358 m:intended_days=7 m:actual_days=7 m:unitid2=130 m:seg_compkey=4382 m:study_adt=4459 m:study_ampk=320 m:study_length=672 m:study_max8=2385

series e:qfw2-ekmx d:2007-04-02T10:15:00.000Z t:dir_from_cross_street=E t:study_lane_code=STANDARD t:study_type=AGGREGATE t:stdy_title_part="S HOLGATE BR, E/O S HOLGATE ST" t:screenline=Y t:title="S HOLGATE BR, E/O S HOLGATE ST; W FLOW;AGG; 02APR2007 10:15#" t:stdy_title_part_with_flow="S HOLGATE BR, E/O S HOLGATE ST; W FLOW" t:unitid=16195 t:x_street="S HOLGATE ST" t:study_id=211647 t:objectid=3 t:o_street="S HOLGATE BR" t:comments="This study is an aggregate of the following source studies: 211646, 211645" t:stdy_label="211647, 2007-04-02, W" t:study_dirflow=W m:study_awdt=3826 m:distance=567 m:study_pmpk=293 m:intended_days=7 m:actual_days=7 m:unitid2=197 m:seg_compkey=20314 m:study_adt=3347 m:study_ampk=347 m:study_length=672 m:study_max8=2173
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

metric m:unitid2 p:integer l:UNITID2 d:UNITID2 t:dataTypeName=number

metric m:distance l:DISTANCE d:DISTANCE t:dataTypeName=number

entity e:qfw2-ekmx l:"SDOT Traffic Count Details" t:url=https://data.seattle.gov/api/views/qfw2-ekmx

property e:qfw2-ekmx t:meta.view d:2017-03-10T16:26:07.114Z v:id=qfw2-ekmx v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Traffic Count Details"

property e:qfw2-ekmx t:meta.view.license d:2017-03-10T16:26:07.114Z v:name="Public Domain"

property e:qfw2-ekmx t:meta.view.owner d:2017-03-10T16:26:07.114Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"

property e:qfw2-ekmx t:meta.view.tableauthor d:2017-03-10T16:26:07.114Z v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```