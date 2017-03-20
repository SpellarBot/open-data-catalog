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
series e:qfw2-ekmx d:2005-06-13T14:00:00.000Z t:dir_from_cross_street=N t:study_lane_code=STANDARD t:unitid2=0130 t:study_type="VOLUME COUNT" t:stdy_title_part="4TH AVE S, N/O 4TH AVE NB ON RP" t:title="4TH AVE S, N/O 4TH AVE NB ON RP; S FLOW; CH1; 13JUN2005 14:00" t:stdy_title_part_with_flow="4TH AVE S, N/O 4TH AVE NB ON RP; S FLOW" t:unitid=03150 t:x_street="4TH AVE NB OFF RP" t:study_id=207138 t:objectid=1 t:o_street="4TH AVE S" t:stdy_label="207138, 2005-06-13, S" t:study_dirflow=S m:study_awdt=9743 m:distance=388 m:study_pmpk=884 m:intended_days=7 m:actual_days=7 m:seg_compkey=163343 m:study_adt=8592 m:study_ampk=687 m:study_length=672 m:study_max8=5793

series e:qfw2-ekmx d:2005-03-15T09:00:00.000Z t:dir_from_cross_street=NE t:study_lane_code=STANDARD t:unitid2=0950 t:study_type="VOLUME COUNT" t:stdy_title_part="LAKE CITY WAY NE, NE/O NE 95TH ST" t:title="LAKE CITY WAY NE, NE/O NE 95TH ST; SW FLOW; CH1; 15MAR2005 09:00" t:stdy_title_part_with_flow="LAKE CITY WAY NE, NE/O NE 95TH ST; SW FLOW" t:unitid=08015 t:x_street="NE 95TH ST" t:study_id=206368 t:objectid=2 t:o_street="LAKE CITY WAY NE" t:stdy_label="206368, 2005-03-15, SW" t:study_dirflow=SW m:study_awdt=17323 m:distance=560.5 m:study_pmpk=1028 m:intended_days=7 m:actual_days=7 m:seg_compkey=11159 m:study_adt=16114 m:study_ampk=1828 m:study_length=672 m:study_max8=9163

series e:qfw2-ekmx d:2003-04-07T11:15:00.000Z t:dir_from_cross_street=W t:study_lane_code=STANDARD t:unitid2=0129 t:study_type="VOLUME COUNT" t:stdy_title_part="S DEARBORN ST, W/O 13TH AVE S" t:title="S DEARBORN ST, W/O 13TH AVE S; W FLOW; CH1; 07APR2003 11:15" t:stdy_title_part_with_flow="S DEARBORN ST, W/O 13TH AVE S; W FLOW" t:unitid=15755 t:x_street="DEARBORN ST OFF RP" t:study_id=200454 t:objectid=3 t:o_street="S DEARBORN ST" t:stdy_label="200454, 2003-04-07, W" t:study_dirflow=W m:study_awdt=11192 m:distance=406 m:study_pmpk=827 m:intended_days=7 m:actual_days=7 m:seg_compkey=19832 m:study_adt=10452 m:study_ampk=742 m:study_length=672 m:study_max8=6070
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

property e:qfw2-ekmx t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"

property e:qfw2-ekmx t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```