# Quitline ? Service Utilization - 2010 To Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quitline-a-service-utilization-2010-to-present-b1983) |
| Metadata | [Link](https://data.cdc.gov/api/views/equ4-92qe) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/equ4-92qe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/equ4-92qe/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | equ4-92qe |
| Name | Quitline ? Service Utilization - 2010 To Present |
| Category | Quitline |
| Tags | osh, office on smoking and health, nqdw, state system, national quitline data warehouse, quitline, quit, callers, services, cessation, intervention, quit-now |
| Created | 2014-11-06T12:35:20Z |
| Publication Date | 2017-04-18T13:17:58Z |

## Description

2010-2016.  National Quitline Data Warehouse (NQDW). State Tobacco Activities Tracking and Evaluation (STATE) System.  NQDW Data.  National Quitline Data Warehouse (NQDW) assists in evaluating quitline activities and serves as a national resource for data on the use, success, and services of state quitlines.  States report data on quitline callers, quitting success, as well as the services provided by their quitlines. The NQDW consolidates this information for evaluating programs and improving quitline services.  The jurisdictions participating in this data collection effort include the 50 states, the District of Columbia, Guam and Puerto Rico.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       |                | year         | Year         | number    | number      |
| No       |                | quarter      | Quarter      | number    | number      |
| Yes      | series tag     | locationabbr | LocationAbbr | text      | text        |
| Yes      | series tag     | locationdesc | LocationDesc | text      | text        |
| Yes      | series tag     | topictype    | TopicType    | text      | text        |
| Yes      | series tag     | topicdesc    | TopicDesc    | text      | text        |
| Yes      | series tag     | measuredesc  | MeasureDesc  | text      | text        |
| Yes      | series tag     | sub_measure  | Sub-Measure  | text      | text        |
| Yes      | series tag     | variable     | Variable     | text      | text        |
| Yes      | numeric metric | value        | Value        | number    | number      |
| Yes      | series tag     | percent      | Percent      | text      | text        |
| Yes      | series tag     | topictypeid  | TopicTypeId  | text      | text        |
| Yes      | series tag     | topicid      | TopicId      | text      | text        |
| Yes      | series tag     | measureid    | MeasureID    | text      | text        |
| Yes      | series tag     | source       | SOURCE       | text      | text        |
| Yes      | series tag     | submeasureid | SubMeasureID | text      | text        |
| No       |                | displayorder | DisplayOrder | number    | text        |
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
series e:equ4-92qe d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Incoming Calls" t:topicid=901QUI t:percent=100 t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:measureid=916VOL t:measuredesc="Call Volume" t:topictype=Quitline t:topicdesc="Service Utilization" t:variable="Total Incoming Calls" t:submeasureid=QUT20 t:topictypeid=QUI m:value=1022

series e:equ4-92qe d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Incoming Calls" t:topicid=901QUI t:percent=69.3 t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:measureid=916VOL t:measuredesc="Call Volume" t:topictype=Quitline t:topicdesc="Service Utilization" t:variable="Calls Answered Live" t:submeasureid=QUT20 t:topictypeid=QUI m:value=708

series e:equ4-92qe d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Incoming Calls" t:topicid=901QUI t:percent=0.3 t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:measureid=916VOL t:measuredesc="Call Volume" t:topictype=Quitline t:topicdesc="Service Utilization" t:variable="Calls Went to Voicemail" t:submeasureid=QUT20 t:topictypeid=QUI m:value=3
```

## Meta Commands

```ls
metric m:value p:integer l:Value d:"Value of data" t:dataTypeName=number

entity e:equ4-92qe l:"Quitline ? Service Utilization - 2010 To Present" t:url=https://data.cdc.gov/api/views/equ4-92qe

property e:equ4-92qe t:meta.view v:id=equ4-92qe v:category=Quitline v:attributionLink=http://www.cdc.gov/tobacco/quit_smoking/cessation/nqdw/index.htm v:averageRating=0 v:name="Quitline ? Service Utilization - 2010 To Present"

property e:equ4-92qe t:meta.view.license v:name="Public Domain"

property e:equ4-92qe t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:equ4-92qe t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:equ4-92qe t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topictype | topicdesc           | measuredesc       | sub_measure                    | variable                                                                   | value  | percent | topictypeid | topicid | measureid | source                                                                    | submeasureid | displayorder | 
| ==== | ======= | ============ | ============ | ========= | =================== | ================= | ============================== | ========================================================================== | ====== | ======= | =========== | ======= | ========= | ========================================================================= | ============ | ============ | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Incoming Calls                 | Total Incoming Calls                                                       | 1022   | 100     | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT20        | 20           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Incoming Calls                 | Calls Answered Live                                                        | 708    | 69.3    | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT20        | 20           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Incoming Calls                 | Calls Went to Voicemail                                                    | 3      | 0.3     | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT20        | 20           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Incoming Calls                 | Other Calls                                                                | 311    | 30.3    | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT20        | 20           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Per Capita Rate and Population | Incoming Calls per 10,000 State Population                                 | 14.1   | NA      | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT21        | 21           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Per Capita Rate and Population | Callers who received counseling and/or Medications per 1,000 tobacco users | 2.5    | NA      | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT21        | 21           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Per Capita Rate and Population | State Population                                                           | 722718 | NA      | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT21        | 21           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Call Volume       | Per Capita Rate and Population | Number of Adult Tobacco Users                                              | 133887 | NA      | QUI         | 901QUI  | 916VOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT21        | 21           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Services Received | Service                        | Counseling and/or Medications                                              | 341    | NA      | QUI         | 901QUI  | 920SRC    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT22        | 22           | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Service Utilization | Services Received | Service                        | Counseling                                                                 | 157    | NA      | QUI         | 901QUI  | 920SRC    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT23        | 23           | 
```