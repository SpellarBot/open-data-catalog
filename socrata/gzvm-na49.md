# Contractor / Sub Contractor Change Order Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contractor-sub-contractor-change-order-report-027b5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gzvm-na49) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gzvm-na49/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gzvm-na49/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gzvm-na49 |
| Name | Contractor / Sub Contractor Change Order Report |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, capital, improvement, project, contractor, subcontractor, change order |
| Created | 2013-07-02T19:00:59Z |
| Publication Date | 2017-04-08T19:14:38Z |

## Description

The Contractor / Sub Contractor Change Order Report is a monthly Multi-Project SCA Change Management Report that lists who is currently responsible for Change Management Issues and the last stage/document of the Change Process.

## Columns

```ls
| Included | Schema Type | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | =========== | ============================================ | ============================================ | ========= | =========== |
| No       | time        | :updated_at                                  | updated_at                                   | meta_data | meta_data   |
| No       |             | data_as_of_date                              | Data as of Date                              | text      | text        |
| Yes      | series tag  | change_order_project_sca_contract_identifier | Change Order Project SCA Contract Identifier | text      | text        |
| Yes      | series tag  | change_order_boro_identifier                 | Change Order Boro Identifier                 | text      | text        |
| Yes      | series tag  | change_order_project_district_identifier     | Change Order Project District Identifier     | text      | text        |
| Yes      | series tag  | change_order_project_identifier              | Change Order Project Identifier              | text      | text        |
| Yes      | series tag  | change_management_number                     | Change Management Number                     | text      | text        |
| No       |             | change_order_document_date                   | Change Order Document Date                   | text      | text        |
| Yes      | series tag  | change_order_project_ball_in_court_code      | Change Order Project Ball In Court Code      | text      | text        |
| Yes      | series tag  | change_order_project_title                   | Change Order Project Title                   | text      | text        |
| Yes      | series tag  | change_order_document_type                   | Change Order Document Type                   | text      | text        |
| No       |             | change_order_project_stage_date              | Change Order Project Stage Date              | text      | text        |
| Yes      | series tag  | change_order_number                          | Change Order Number                          | text      | text        |
| Yes      | series tag  | change_order_project_to_status_name          | Change Order Project To Status Name          | text      | text        |
| Yes      | series tag  | change_order_project_to_vendor_              | Change Order Project To Vendor               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = data_as_of_date,change_order_document_date,change_order_project_stage_date
```

## Data Commands

```ls
series e:gzvm-na49 d:2017-04-08T19:14:26.000Z t:change_order_document_type=EST t:change_order_project_sca_contract_identifier=C000013857 t:change_order_project_identifier=PS052R03 t:change_order_project_to_vendor_=SCA-PM t:change_management_number=00021 t:change_order_boro_identifier=R t:change_order_number=00021 t:change_order_project_district_identifier=31 t:change_order_project_to_status_name=CLO t:change_order_project_ball_in_court_code=POSITIVE t:change_order_project_title="PS052R Sandy-Htg Plnt Upgr,Flood" m:row_number.gzvm-na49=1

series e:gzvm-na49 d:2017-04-08T19:14:26.000Z t:change_order_document_type=FRE t:change_order_project_sca_contract_identifier=C000013708 t:change_order_project_identifier=PS356X01 t:change_order_project_to_vendor_=SCA-PM t:change_management_number=00003 t:change_order_boro_identifier=X t:change_order_number=00003 t:change_order_project_district_identifier=07 t:change_order_project_to_status_name=CLO t:change_order_project_ball_in_court_code=INNOVAX t:change_order_project_title="PS356X Pre K" m:row_number.gzvm-na49=2

series e:gzvm-na49 d:2017-04-08T19:14:26.000Z t:change_order_document_type=PCO t:change_order_project_sca_contract_identifier=C000013112 t:change_order_project_identifier=PS320Q02 t:change_order_project_to_vendor_=SCA-PM t:change_management_number=00080 t:change_order_boro_identifier=Q t:change_order_number=00080 t:change_order_project_district_identifier=24 t:change_order_project_to_status_name=CLO t:change_order_project_ball_in_court_code=PAVARINI t:change_order_project_title="PS320Q New School" m:row_number.gzvm-na49=3
```

## Meta Commands

```ls
metric m:row_number.gzvm-na49 p:long l:"Row Number"

entity e:gzvm-na49 l:"Contractor / Sub Contractor Change Order Report" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/gzvm-na49

property e:gzvm-na49 t:meta.view v:id=gzvm-na49 v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Business/WorkingWithTheSCA/Construction/ChangeOrders/Pages/ExpeditionReportChangeOrderStatus.aspx v:averageRating=0 v:name="Contractor / Sub Contractor Change Order Report" v:attribution="School Construction Authority (SCA)"

property e:gzvm-na49 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gzvm-na49 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | data_as_of_date                | change_order_project_sca_contract_identifier | change_order_boro_identifier | change_order_project_district_identifier | change_order_project_identifier | change_management_number | change_order_document_date | change_order_project_ball_in_court_code | change_order_project_title           | change_order_document_type | change_order_project_stage_date | change_order_number | change_order_project_to_status_name | change_order_project_to_vendor_ | 
| =========== | ============================== | ============================================ | ============================ | ======================================== | =============================== | ======================== | ========================== | ======================================= | ==================================== | ========================== | =============================== | =================== | =================================== | =============================== | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013857                                   | R                            | 31                                       | PS052R03                        | 00021                    | 2016-08-11                 | POSITIVE                                | PS052R Sandy-Htg Plnt Upgr,Flood     | EST                        | 2016-08-11                      | 00021               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013708                                   | X                            | 07                                       | PS356X01                        | 00003                    | 2015-02-04                 | INNOVAX                                 | PS356X Pre K                         | FRE                        | 2015-11-20                      | 00003               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013112                                   | Q                            | 24                                       | PS320Q02                        | 00080                    | 2015-04-21                 | PAVARINI                                | PS320Q New School                    | PCO                        | 2015-10-05                      | 00080               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013796                                   | M                            | 02                                       | IS323M01                        | 00039                    | 2016-05-17                 | LDD                                     | IS323M Reno Exist to New 7 Story Sch | FRE                        | 2016-08-19                      | 00039               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000012869                                   | M                            | 02                                       | PS343M02                        | 00228                    | 2015-10-30                 | EWHOWELL                                | PS343M Reno & Three Story Add        | PCO                        | 2015-10-30                      | 00228               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013709                                   | Q                            | 28                                       | PS383Q01                        | 00011                    | 2015-09-22                 | NESCO                                   | PS383Q Pre K                         | FRE                        | 2015-10-27                      | 00011               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013925                                   | R                            | 31                                       | PS045R06                        | 00004                    | 2016-08-10                 | HILT                                    | PS045R Ext Mas,Prpts,Roofs,Fld Elim  | EST                        | 2016-08-10                      | 00004               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013282                                   | Q                            | 29                                       | PS176Q03                        | 00054                    | 2015-11-16                 | LDD                                     | PS176Q03 New Add & Reno to Existing  | EST                        | 2015-11-16                      | 00054               | NEW                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000013119                                   | Q                            | 24                                       | IS311Q01                        | 00182                    | 2016-02-19                 | LDD                                     | IS311Q New Five Story School         | EST                        | 2016-02-19                      | 00182               | CLO                                 | SCA-PM                          | 
| 1491678866  | 2017-04-03T09:00:03.8865512-04 | C000012944                                   | Q                            | 29                                       | PS892Q01                        | 00100                    | 2014-08-28                 | WDF                                     | PS892Q School Renovation             | PCO                        | 2015-11-04                      | 00100               | CLO                                 | SCA-PM                          | 
```