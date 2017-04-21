# State University Construction Fund (SUCF) Projects: Beginning 1989

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-projects-beginning-1989) |
| Metadata | [Link](https://data.ny.gov/api/views/7xmz-2ur8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7xmz-2ur8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7xmz-2ur8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7xmz-2ur8 |
| Name | State University Construction Fund (SUCF) Projects: Beginning 1989 |
| Attribution | State University Construction Fund ? IS Department |
| Category | Education |
| Tags | state university construction fund, sucf, project, education, suny construction, capital |
| Created | 2014-02-19T15:29:34Z |
| Publication Date | 2017-04-01T10:08:01Z |

## Description

Listing of Fund and Campus Managed Projects Funded through State University Construction Fund Appropriations

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | =========== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag  | project_number              | Project Number              | text          | text          |
| Yes      | series tag  | description                 | Description                 | text          | text          |
| Yes      | time        | start_date                  | Start Date                  | calendar_date | calendar_date |
| No       |             | target_date                 | Target Date                 | calendar_date | calendar_date |
| Yes      | series tag  | campus                      | Campus                      | text          | text          |
| Yes      | series tag  | economic_development_region | Economic Development Region | text          | text          |
| Yes      | series tag  | project_phase               | Project Phase               | text          | text          |
| Yes      | series tag  | purpose                     | Purpose                     | text          | text          |
| Yes      | series tag  | managed_by_sucf             | Managed by SUCF             | text          | text          |
| Yes      | series tag  | project_status              | Project Status              | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = target_date
```

## Data Commands

```ls
series e:7xmz-2ur8 d:2014-09-30T00:00:00.000Z t:project_status=Active t:description="Site Representative - (GH)" t:managed_by_sucf=N t:project_number=011000 t:purpose="Preservation of Facilities" t:project_phase="In Design" t:economic_development_region="Capital Region" t:campus="University at Albany" m:row_number.7xmz-2ur8=1

series e:7xmz-2ur8 d:2014-09-30T00:00:00.000Z t:project_status=Active t:description="Site Representative - (EB)" t:managed_by_sucf=N t:project_number=011001 t:purpose="Preservation of Facilities" t:project_phase="In Design" t:economic_development_region="Capital Region" t:campus="University at Albany" m:row_number.7xmz-2ur8=2

series e:7xmz-2ur8 d:2014-10-10T00:00:00.000Z t:project_status=Active t:description="Site Improvements Washington Avenue East Entry" t:managed_by_sucf=N t:project_number=011002 t:purpose="Health, Safety, Security" t:project_phase="In Guarantee" t:economic_development_region="Capital Region" t:campus="University at Albany" m:row_number.7xmz-2ur8=3
```

## Meta Commands

```ls
metric m:row_number.7xmz-2ur8 p:long l:"Row Number"

entity e:7xmz-2ur8 l:"State University Construction Fund (SUCF) Projects: Beginning 1989" t:attribution="State University Construction Fund ? IS Department" t:url=https://data.ny.gov/api/views/7xmz-2ur8

property e:7xmz-2ur8 t:meta.view v:id=7xmz-2ur8 v:category=Education v:attributionLink=https://www.sucf.suny.edu/ v:averageRating=0 v:name="State University Construction Fund (SUCF) Projects: Beginning 1989" v:attribution="State University Construction Fund ? IS Department"

property e:7xmz-2ur8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7xmz-2ur8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7xmz-2ur8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project_number | description                                    | start_date          | target_date         | campus               | economic_development_region | project_phase   | purpose                               | managed_by_sucf | project_status | 
| ============== | ============================================== | =================== | =================== | ==================== | =========================== | =============== | ===================================== | =============== | ============== | 
| 011000         | Site Representative - (GH)                     | 2014-09-30T00:00:00 | 2017-03-22T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | N               | Active         | 
| 011001         | Site Representative - (EB)                     | 2014-09-30T00:00:00 | 2017-03-22T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | N               | Active         | 
| 011002         | Site Improvements Washington Avenue East Entry | 2014-10-10T00:00:00 | 2017-06-07T00:00:00 | University at Albany | Capital Region              | In Guarantee    | Health, Safety, Security              | N               | Active         | 
| 011003         | Lighting Replacement Building 105              | 2015-06-01T00:00:00 | 2016-07-01T00:00:00 | University at Albany | Capital Region              | Closed          | Preservation of Facilities            | N               | Complete       | 
| 011004         | Renovate Basement Milne Hall                   | 2015-05-01T00:00:00 | 2019-01-14T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | N               | Active         | 
| 011005         | Renovate Sub-Basement Lecture Center South     | 2015-05-07T00:00:00 | 2020-03-23T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | Y               | Active         | 
| 011006         | Upgrade Central Plant - SUCF                   | 2015-05-22T00:00:00 | 2021-03-25T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | Y               | Active         | 
| 011007         | Decommission Former Data Center - Bldg 56      | 2015-05-27T00:00:00 | 2019-01-10T00:00:00 | University at Albany | Capital Region              | In Construction | Program Improvement or Program Change | Y               | Active         | 
| 011008         | Rehab Toilet Rooms for ADA - Podium            | 2015-05-27T00:00:00 | 2022-02-08T00:00:00 | University at Albany | Capital Region              | In Design       | Facilities for Physically Disabled    | Y               | Active         | 
| 011009         | Upgrade Controls Study/Pilot Campus Wide       | 2016-03-01T00:00:00 | 2017-08-30T00:00:00 | University at Albany | Capital Region              | In Design       | Preservation of Facilities            | Y               | Active         | 
```