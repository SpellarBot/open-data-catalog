# Quitline ? 7-Month Follow-Up (Not Comparable Across States) ? 2010-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quitline-7-month-follow-up-not-comparable-across-states-2010-2011-9464d) |
| Metadata | [Link](https://data.cdc.gov/api/views/7dvv-y64a) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/7dvv-y64a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/7dvv-y64a/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 7dvv-y64a |
| Name | Quitline ? 7-Month Follow-Up (Not Comparable Across States) ? 2010-2011 |
| Category | Quitline |
| Tags | osh, office on smoking and health, nqdw, state system, national quitline data warehouse, quitline, quit, callers, services, cessation, intervention, quit-now |
| Created | 2014-11-06T12:25:10Z |
| Publication Date | 2017-02-01T19:22:52Z |

## Description

2010-2011.  National Quitline Data Warehouse (NQDW). State Tobacco Activities Tracking and Evaluation (STATE) System.  NQDW Data.  National Quitline Data Warehouse (NQDW) assists in evaluating quitline activities and serves as a national resource for data on the use, success, and services of state quitlines.  States report data on quitline callers, quitting success, as well as the services provided by their quitlines. The NQDW consolidates this information for evaluating programs and improving quitline services.  The jurisdictions participating in this data collection effort include the 50 states, the District of Columbia, Guam and Puerto Rico.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       |             | year         | Year         | number    | number      |
| No       |             | quarter      | Quarter      | number    | number      |
| Yes      | series tag  | locationabbr | LocationAbbr | text      | text        |
| Yes      | series tag  | locationdesc | LocationDesc | text      | text        |
| Yes      | series tag  | topictype    | TopicType    | text      | text        |
| Yes      | series tag  | topicdesc    | TopicDesc    | text      | text        |
| Yes      | series tag  | measuredesc  | MeasureDesc  | text      | text        |
| Yes      | series tag  | sub_measure  | Sub-Measure  | text      | text        |
| Yes      | series tag  | variable     | Variable     | text      | text        |
| Yes      | series tag  | sub_variable | Sub-Variable | text      | text        |
| Yes      | series tag  | value        | Value        | text      | text        |
| Yes      | series tag  | topictypeid  | TopicTypeId  | text      | text        |
| Yes      | series tag  | topicid      | TopicId      | text      | text        |
| Yes      | series tag  | measureid    | MeasureID    | text      | text        |
| Yes      | series tag  | source       | SOURCE       | text      | text        |
| Yes      | series tag  | submeasureid | SubMeasureID | text      | text        |
| No       |             | displayorder | DisplayOrder | number    | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = displayorder,year,quarter
```

## Data Commands

```ls
series e:7dvv-y64a d:2011-10-01T00:00:00.000Z t:sub_variable="Intent to Treat Rate (%)" t:locationabbr=AL t:locationdesc=Alabama t:sub_measure="Cessation Outcomes" t:topicid=902QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:value=38 t:measureid=926FUP t:measuredesc="7 Month Follow-Up Evaluation" t:topictype=Quitline t:topicdesc=Follow-Up t:variable="24 Hour Quit Attempt" t:submeasureid=QUT51 t:topictypeid=QUI m:row_number.7dvv-y64a=1

series e:7dvv-y64a d:2011-10-01T00:00:00.000Z t:sub_variable="Responder Rate (%)" t:locationabbr=AL t:locationdesc=Alabama t:sub_measure="Cessation Outcomes" t:topicid=902QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:value=79.8 t:measureid=926FUP t:measuredesc="7 Month Follow-Up Evaluation" t:topictype=Quitline t:topicdesc=Follow-Up t:variable="24 Hour Quit Attempt" t:submeasureid=QUT51 t:topictypeid=QUI m:row_number.7dvv-y64a=2

series e:7dvv-y64a d:2011-10-01T00:00:00.000Z t:sub_variable="Intent to Treat Rate (%)" t:locationabbr=AL t:locationdesc=Alabama t:sub_measure="Cessation Outcomes" t:topicid=902QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:value=20.3 t:measureid=926FUP t:measuredesc="7 Month Follow-Up Evaluation" t:topictype=Quitline t:topicdesc=Follow-Up t:variable="Quit for 30 Days or More" t:submeasureid=QUT51 t:topictypeid=QUI m:row_number.7dvv-y64a=3
```

## Meta Commands

```ls
metric m:row_number.7dvv-y64a p:long l:"Row Number"

entity e:7dvv-y64a l:"Quitline ? 7-Month Follow-Up (Not Comparable Across States) ? 2010-2011" t:url=https://data.cdc.gov/api/views/7dvv-y64a

property e:7dvv-y64a t:meta.view v:id=7dvv-y64a v:category=Quitline v:attributionLink=http://www.cdc.gov/tobacco/quit_smoking/cessation/nqdw/index.htm v:averageRating=0 v:name="Quitline ? 7-Month Follow-Up (Not Comparable Across States) ? 2010-2011"

property e:7dvv-y64a t:meta.view.license v:name="Public Domain"

property e:7dvv-y64a t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:7dvv-y64a t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:7dvv-y64a t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topictype | topicdesc | measuredesc                  | sub_measure                   | variable                           | sub_variable             | value | topictypeid | topicid | measureid | source                                                                   | submeasureid | displayorder | 
| ==== | ======= | ============ | ============ | ========= | ========= | ============================ | ============================= | ================================== | ======================== | ===== | =========== | ======= | ========= | ======================================================================== | ============ | ============ | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | 24 Hour Quit Attempt               | Intent to Treat Rate (%) | 38    | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | 24 Hour Quit Attempt               | Responder Rate (%)       | 79.8  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | Quit for 30 Days or More           | Intent to Treat Rate (%) | 20.3  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | Quit for 30 Days or More           | Responder Rate (%)       | 42.7  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Sample Size and Response Rate | Number of Respondents              |                          | 1052  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT52        | 52           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Sample Size and Response Rate | Response Rate (%)                  |                          | 47.6  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT52        | 52           | 
| 2011 | 4       | AL           | Alabama      | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Sample Size and Response Rate | Sample Size Selected for Follow-Up |                          | 2212  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT52        | 52           | 
| 2011 | 4       | AK           | Alaska       | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | 24 Hour Quit Attempt               | Intent to Treat Rate (%) | NA    | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AK           | Alaska       | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | 24 Hour Quit Attempt               | Responder Rate (%)       | NA    | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
| 2011 | 4       | AK           | Alaska       | Quitline  | Follow-Up | 7 Month Follow-Up Evaluation | Cessation Outcomes            | Quit for 30 Days or More           | Intent to Treat Rate (%) | 11.1  | QUI         | 902QUI  | 926FUP    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT51        | 51           | 
```