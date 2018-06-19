# Quitline ? Services Available ? Hours Of Operation And Available Languages - 2010 To Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quitline-a-services-available-a-hours-of-operation-and-available-languages-2010-to-present-c66c7) |
| Metadata | [Link](https://data.cdc.gov/api/views/vtt8-av2v) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vtt8-av2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vtt8-av2v/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vtt8-av2v |
| Name | Quitline ? Services Available ? Hours Of Operation And Available Languages - 2010 To Present |
| Category | Quitline |
| Tags | osh, office on smoking and health, nqdw, state system, national quitline data warehouse, quitline, quit, callers, services, cessation, intervention, quit-now |
| Created | 2014-11-06T13:34:24Z |
| Publication Date | 2017-04-13T15:32:31Z |

## Description

2010-2016.  National Quitline Data Warehouse (NQDW). State Tobacco Activities Tracking and Evaluation (STATE) System.  NQDW Data.  National Quitline Data Warehouse (NQDW) assists in evaluating quitline activities and serves as a national resource for data on the use, success, and services of state quitlines.  States report data on quitline callers, quitting success, as well as the services provided by their quitlines. The NQDW consolidates this information for evaluating programs and improving quitline services.  The jurisdictions participating in this data collection effort include the 50 states, the District of Columbia, Guam and Puerto Rico.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       |             | year                  | Year                  | number    | number      |
| No       |             | quarter               | Quarter               | number    | number      |
| Yes      | series tag  | locationabbr          | LocationAbbr          | text      | text        |
| Yes      | series tag  | locationdesc          | LocationDesc          | text      | text        |
| Yes      | series tag  | topictype             | TopicType             | text      | text        |
| Yes      | series tag  | topicdesc             | TopicDesc             | text      | text        |
| Yes      | series tag  | measuredesc           | MeasureDesc           | text      | text        |
| Yes      | series tag  | sub_measure           | Sub-Measure           | text      | text        |
| Yes      | series tag  | variable              | Variable              | text      | text        |
| Yes      | series tag  | availability          | Availability          | text      | text        |
| Yes      | series tag  | live_pick_up_of_calls | Live Pick-Up of Calls | text      | text        |
| Yes      | series tag  | counseling_available  | Counseling Available  | text      | text        |
| Yes      | series tag  | topictypeid           | TopicTypeId           | text      | text        |
| Yes      | series tag  | topicid               | TopicId               | text      | text        |
| Yes      | series tag  | measureid             | MeasureID             | text      | text        |
| Yes      | series tag  | source                | SOURCE                | text      | text        |
| Yes      | series tag  | submeasureid          | SubMeasureID          | text      | text        |
| No       |             | displayorder          | DisplayOrder          | number    | text        |
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
series e:vtt8-av2v d:2016-07-01T00:00:00.000Z t:sub_measure="Available Languages" t:locationdesc=Alaska t:locationabbr=AK t:topicid=900QUI t:measuredesc="Hours of Operation and Available Languages" t:measureid=910HOL t:topicdesc="Services Available" t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:topictype=Quitline t:variable=English t:submeasureid=QUT01 t:topictypeid=QUI t:availability=Yes m:row_number.vtt8-av2v=1

series e:vtt8-av2v d:2016-07-01T00:00:00.000Z t:sub_measure="Available Languages" t:locationdesc=Alaska t:locationabbr=AK t:topicid=900QUI t:measuredesc="Hours of Operation and Available Languages" t:measureid=910HOL t:topicdesc="Services Available" t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:topictype=Quitline t:variable=Spanish t:submeasureid=QUT01 t:topictypeid=QUI t:availability=Yes m:row_number.vtt8-av2v=2

series e:vtt8-av2v d:2016-07-01T00:00:00.000Z t:sub_measure="Available Languages" t:locationdesc=Alaska t:locationabbr=AK t:topicid=900QUI t:measuredesc="Hours of Operation and Available Languages" t:measureid=910HOL t:topicdesc="Services Available" t:source="National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH)" t:topictype=Quitline t:variable=French t:submeasureid=QUT01 t:topictypeid=QUI t:availability=Yes m:row_number.vtt8-av2v=3
```

## Meta Commands

```ls
metric m:row_number.vtt8-av2v p:long l:"Row Number"

entity e:vtt8-av2v l:"Quitline ? Services Available ? Hours Of Operation And Available Languages - 2010 To Present" t:url=https://data.cdc.gov/api/views/vtt8-av2v

property e:vtt8-av2v t:meta.view v:id=vtt8-av2v v:category=Quitline v:attributionLink=http://www.cdc.gov/tobacco/quit_smoking/cessation/nqdw/index.htm v:averageRating=0 v:name="Quitline ? Services Available ? Hours Of Operation And Available Languages - 2010 To Present"

property e:vtt8-av2v t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:vtt8-av2v t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vtt8-av2v t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topictype | topicdesc          | measuredesc                                | sub_measure         | variable            | availability | live_pick_up_of_calls | counseling_available | topictypeid | topicid | measureid | source                                                                    | submeasureid | displayorder | 
| ==== | ======= | ============ | ============ | ========= | ================== | ========================================== | =================== | =================== | ============ | ===================== | ==================== | =========== | ======= | ========= | ========================================================================= | ============ | ============ | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | English             | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Spanish             | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | French              | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Cantonese           | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Mandarin            | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Korean              | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Vietnamese          | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Russian             | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Greek               | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Hours of Operation and Available Languages | Available Languages | Amharic (Ethiopian) | Yes          |                       |                      | QUI         | 900QUI  | 910HOL    | National Quitline Data Warehouse, Office on Smoking and Health (NQDW OSH) | QUT01        | 1            | 
```