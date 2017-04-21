# Quitline ? Services Available ? Medications - 2010 To Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quitline-a-services-available-a-medications-2010-to-present-f0269) |
| Metadata | [Link](https://data.cdc.gov/api/views/tbyb-bvjd) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/tbyb-bvjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/tbyb-bvjd/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | tbyb-bvjd |
| Name | Quitline ? Services Available ? Medications - 2010 To Present |
| Category | Quitline |
| Tags | osh, office on smoking and health, nqdw, state system, national quitline data warehouse, quitline, quit, callers, services, cessation, intervention, quit-now |
| Created | 2014-11-06T13:44:39Z |
| Publication Date | 2017-04-13T15:34:03Z |

## Description

2010-2016.  National Quitline Data Warehouse (NQDW). State Tobacco Activities Tracking and Evaluation (STATE) System.  NQDW Data.  National Quitline Data Warehouse (NQDW) assists in evaluating quitline activities and serves as a national resource for data on the use, success, and services of state quitlines.  States report data on quitline callers, quitting success, as well as the services provided by their quitlines. The NQDW consolidates this information for evaluating programs and improving quitline services.  The jurisdictions participating in this data collection effort include the 50 states, the District of Columbia, Guam and Puerto Rico.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       |             | year           | Year           | number    | number      |
| No       |             | quarter        | Quarter        | number    | number      |
| Yes      | series tag  | locationabbr   | LocationAbbr   | text      | text        |
| Yes      | series tag  | locationdesc   | LocationDesc   | text      | text        |
| Yes      | series tag  | topictype      | TopicType      | text      | text        |
| Yes      | series tag  | topicdesc      | TopicDesc      | text      | text        |
| Yes      | series tag  | measuredesc    | MeasureDesc    | text      | text        |
| Yes      | series tag  | sub_measure    | Sub-Measure    | text      | text        |
| Yes      | series tag  | variable       | Variable       | text      | text        |
| Yes      | series tag  | value          | Value          | text      | text        |
| Yes      | series tag  | criteria       | Criteria       | text      | text        |
| Yes      | series tag  | free           | Free           | text      | text        |
| Yes      | series tag  | discounted     | Discounted     | text      | text        |
| Yes      | series tag  | voucher_coupon | Voucher/Coupon | text      | text        |
| Yes      | series tag  | comments       | Comments       | text      | text        |
| Yes      | series tag  | topictypeid    | TopicTypeId    | text      | text        |
| Yes      | series tag  | topicid        | TopicId        | text      | text        |
| Yes      | series tag  | measureid      | MeasureID      | text      | text        |
| Yes      | series tag  | source         | SOURCE         | text      | text        |
| Yes      | series tag  | submeasureid   | SubMeasureID   | text      | text        |
| No       |             | displayorder   | DisplayOrder   | number    | text        |
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
series e:tbyb-bvjd d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Available Medications" t:free=Yes t:topicid=900QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:voucher_coupon=No t:discounted=No t:value=NA t:measureid=912MED t:measuredesc=Medications t:topictype=Quitline t:topicdesc="Services Available" t:variable="Nicotine Patch" t:submeasureid=QUT05 t:topictypeid=QUI m:row_number.tbyb-bvjd=1

series e:tbyb-bvjd d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Available Medications" t:free=Yes t:topicid=900QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:voucher_coupon=No t:discounted=No t:value=NA t:measureid=912MED t:measuredesc=Medications t:topictype=Quitline t:topicdesc="Services Available" t:variable="Nicotine Gum" t:submeasureid=QUT05 t:topictypeid=QUI m:row_number.tbyb-bvjd=2

series e:tbyb-bvjd d:2016-07-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:sub_measure="Available Medications" t:free=Yes t:topicid=900QUI t:source="National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH)" t:voucher_coupon=No t:discounted=No t:value=NA t:measureid=912MED t:measuredesc=Medications t:topictype=Quitline t:topicdesc="Services Available" t:variable="Nicotine Lozenge" t:submeasureid=QUT05 t:topictypeid=QUI m:row_number.tbyb-bvjd=3
```

## Meta Commands

```ls
metric m:row_number.tbyb-bvjd p:long l:"Row Number"

entity e:tbyb-bvjd l:"Quitline ? Services Available ? Medications - 2010 To Present" t:url=https://data.cdc.gov/api/views/tbyb-bvjd

property e:tbyb-bvjd t:meta.view v:id=tbyb-bvjd v:category=Quitline v:attributionLink=http://www.cdc.gov/tobacco/quit_smoking/cessation/nqdw/index.htm v:averageRating=0 v:name="Quitline ? Services Available ? Medications - 2010 To Present"

property e:tbyb-bvjd t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:tbyb-bvjd t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:tbyb-bvjd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topictype | topicdesc          | measuredesc | sub_measure                              | variable               | value | criteria | free | discounted       | voucher_coupon | comments                                                                                            | topictypeid | topicid | measureid | source                                                                   | submeasureid | displayorder | 
| ==== | ======= | ============ | ============ | ========= | ================== | =========== | ======================================== | ====================== | ===== | ======== | ==== | ================ | ============== | =================================================================================================== | =========== | ======= | ========= | ======================================================================== | ============ | ============ | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Nicotine Patch         | NA    |          | Yes  | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Nicotine Gum           | NA    |          | Yes  | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Nicotine Lozenge       | NA    |          | Yes  | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Nicotine Nasal Spray   | NA    |          | No   | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Nicotine Inhaler       | NA    |          | No   | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Bupropion (Zyban?)     | NA    |          | No   | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Available Medications                    | Varenicline (Chantix?) | NA    |          | No   | No               | No             |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT05        | 5            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Free Nicotine Gum - Amount Provided      | All Eligible Callers   | 4     |          |      | 2 times per year |                | Combo therapy (4 wks patch + 2 wks gum or lozenge) offered to those who smoke 9+ cigarettes per day | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT08        | 8            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Free Nicotine Gum - Eligibility Criteria | Resident of State      | NA    | Yes      |      |                  |                |                                                                                                     | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT09        | 9            | 
| 2016 | 3       | AK           | Alaska       | Quitline  | Services Available | Medications | Free Nicotine Gum - Eligibility Criteria | Age                    | NA    | Yes      |      |                  |                | 18 years and older                                                                                  | QUI         | 900QUI  | 912MED    | National Quitline Data Warehouse, Office on Smoking and Health(NQDW OSH) | QUT09        | 9            | 
```