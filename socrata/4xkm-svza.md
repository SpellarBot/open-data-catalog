# WFRS Archive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wfrs-archive) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/4xkm-svza) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/4xkm-svza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/4xkm-svza/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 4xkm-svza |
| Name | WFRS Archive |
| Category | Oral Health |
| Tags | doh, oral health, wfrs |
| Created | 2016-11-07T13:37:01Z |
| Publication Date | 2016-11-07T13:39:45Z |

## Description

This will be used for the annual archive of data

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| No       |                | id                         | ID                         | text          | number        |
| No       |                | year                       | Year                       | number        | number        |
| Yes      | time           | datetime                   | DateTime                   | calendar_date | calendar_date |
| Yes      | series tag     | stateabbr                  | StateAbbr                  | text          | text          |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text          | text          |
| Yes      | series tag     | locationdesc               | LocationDesc               | text          | text          |
| Yes      | series tag     | category                   | Category                   | text          | text          |
| Yes      | series tag     | indicator                  | Indicator                  | text          | text          |
| Yes      | series tag     | datasource                 | DataSource                 | text          | text          |
| No       |                | data_value_unit            | Data_Value_Unit            | text          | text          |
| No       |                | data_value_type            | Data_Value_Type            | text          | text          |
| Yes      | numeric metric | data_value                 | Data_Value                 | number        | number        |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text          | text          |
| No       |                | data_value_footnote_text   | Data_Value_Footnote_Text   | text          | text          |
| Yes      | series tag     | indicatorid                | IndicatorID                | text          | text          |
| Yes      | series tag     | locationid                 | LocationID                 | text          | text          |
```

## Time Field

```ls
Value = datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote_text,year
```

## Data Commands

```ls
series e:4xkm-svza d:2016-12-31T00:00:00.000Z t:locationabbr=Pickaway t:locationdesc=Pickaway t:indicator="PWS population (dampened)" t:category=Fluoridation t:locationid=39129 t:stateabbr=OH t:indicatorid=FLR1_8 t:datasource=WFRS m:data_value=-1

series e:4xkm-svza d:2016-12-31T00:00:00.000Z t:locationabbr=Brewster t:locationdesc=Brewster t:indicator="Number of PWS providing fluoridated water (not dampened)" t:category=Fluoridation t:locationid=48043 t:stateabbr=TX t:indicatorid=FLR1_2 t:datasource=WFRS m:data_value=8

series e:4xkm-svza d:2016-12-31T00:00:00.000Z t:locationabbr=Camden t:locationdesc=Camden t:indicator="Percentage of total population receiving fluoridated water from PWS with added (adjusted, consecutive) fluoride (dampened)" t:category=Fluoridation t:locationid=37029 t:stateabbr=NC t:indicatorid=FLR1_24 t:datasource=WFRS m:data_value=-1
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value t:dataTypeName=number

entity e:4xkm-svza l:"WFRS Archive" t:url=https://chronicdata.cdc.gov/api/views/4xkm-svza

property e:4xkm-svza t:meta.view v:id=4xkm-svza v:category="Oral Health" v:averageRating=0 v:name="WFRS Archive"

property e:4xkm-svza t:meta.view.license v:name="Public Domain"

property e:4xkm-svza t:meta.view.owner v:id=vdma-hns2 v:screenName=Tayo v:displayName=Tayo

property e:4xkm-svza t:meta.view.tableauthor v:id=vdma-hns2 v:screenName=Tayo v:displayName=Tayo

property e:4xkm-svza t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| id     | year | datetime            | stateabbr | locationabbr | locationdesc  | category     | indicator                                                                                                                                | datasource | data_value_unit  | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote_text         | indicatorid | locationid | 
| ====== | ==== | =================== | ========= | ============ | ============= | ============ | ======================================================================================================================================== | ========== | ================ | =============== | ========== | ========================== | ================================ | =========== | ========== | 
| 416900 | 2012 | 2016-12-31T00:00:00 | OH        | Pickaway     | Pickaway      | Fluoridation | PWS population (dampened)                                                                                                                | WFRS       | Number of People | Population      | -1         | ?                          | Data are not currently available | FLR1_8      | 39129      | 
| 429186 | 2012 | 2016-12-31T00:00:00 | TX        | Brewster     | Brewster      | Fluoridation | Number of PWS providing fluoridated water (not dampened)                                                                                 | WFRS       | Number of PWS    | Count           | 8          |                            |                                  | FLR1_2      | 48043      | 
| 143468 | 2015 | 2016-12-31T00:00:00 | NC        | Camden       | Camden        | Fluoridation | Percentage of total population receiving fluoridated water from PWS with added (adjusted, consecutive) fluoride (dampened)               | WFRS       | %                | Percent         | -1         | ?                          | Data are not currently available | FLR1_24     | 37029      | 
| 23547  | 2016 | 2016-12-31T00:00:00 | IA        | Grundy       | Grundy        | Fluoridation | Percentage of total population receiving water from PWS with less than the recommended level (not dampened)                              | WFRS       | %                | Percent         | 0          |                            |                                  | FLR1_27     | 19075      | 
| 407102 | 2012 | 2016-12-31T00:00:00 | NH        | NH           | New Hampshire | Fluoridation | Population on fluoridated drinking water systems (dampened)                                                                              | WFRS       | Number of People | Population      | -1         | ?                          | Data are not currently available | FLR1_10     | 33         | 
| 407701 | 2012 | 2016-12-31T00:00:00 | NJ        | Hunterdon    | Hunterdon     | Fluoridation | Percentage of PWS population receiving fluoridated water from PWS with natural fluoride at or above the recommended level (not dampened) | WFRS       | %                | Percent         | 0          |                            |                                  | FLR1_21     | 34019      | 
| 113577 | 2015 | 2016-12-31T00:00:00 | IA        | Monona       | Monona        | Fluoridation | Population on fluoridated drinking water systems (not dampened)                                                                          | WFRS       | Number of People | Population      | 3001       |                            |                                  | FLR1_9      | 19133      | 
| 197475 | 2014 | 2016-12-31T00:00:00 | IL        | Peoria       | Peoria        | Fluoridation | Percentage of total population receiving fluoridated water (dampened)                                                                    | WFRS       | %                | Percent         | -1         | ?                          | Data are not currently available | FLR1_19     | 17143      | 
| 123052 | 2015 | 2016-12-31T00:00:00 | ME        | Somerset     | Somerset      | Fluoridation | Percentage of PWS population receiving fluoridated water from PWS with added (adjusted, consecutive) fluoride (not dampened)             | WFRS       | %                | Percent         | 69.75      |                            |                                  | FLR1_20     | 23025      | 
| 55095  | 2016 | 2016-12-31T00:00:00 | NC        | Hertford     | Hertford      | Fluoridation | Percentage of total population receiving fluoridated water (dampened)                                                                    | WFRS       | %                | Percent         | -1         | ?                          | Data are not currently available | FLR1_19     | 37091      | 
```