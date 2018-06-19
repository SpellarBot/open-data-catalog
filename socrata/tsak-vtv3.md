# Upcoming contracts to be awarded (CIP)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upcoming-contracts-to-be-awarded-cip-e3239) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tsak-vtv3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tsak-vtv3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tsak-vtv3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tsak-vtv3 |
| Name | Upcoming contracts to be awarded (CIP) |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, capital, improvement, project, design, complete, completion, bid, education |
| Created | 2013-08-22T19:06:52Z |
| Publication Date | 2017-03-08T21:23:25Z |

## Description

New school projects Capital Improvement Projects (CIP) that will complete design within the next 6 months and will be available for bid.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | =========== | ======================================= | ======================================= | ========= | =========== |
| No       | time        | :updated_at                             | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | upcoming_project_design_number          | Upcoming Project Design Number          | text      | text        |
| Yes      | series tag  | upcoming_project_name                   | Upcoming Project Name                   | text      | text        |
| Yes      | series tag  | upcoming_project_borough_               | Upcoming Project Borough                | text      | text        |
| Yes      | series tag  | upcoming_project_geographic_district    | Upcoming Project Geographic District    | text      | text        |
| Yes      | series tag  | upcoming_project_description            | Upcoming Project Description            | text      | text        |
| Yes      | series tag  | upcoming_project_budget_range           | Upcoming Project Budget Range           | text      | text        |
| No       |             | upcoming_project_design_completion_date | Upcoming Project Design Completion Date | text      | text        |
| Yes      | series tag  | upcoming_project_category               | Upcoming Project Category               | text      | text        |
| Yes      | series tag  | upcoming_project_status_                | Upcoming Project Status                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = upcoming_project_design_completion_date
```

## Data Commands

```ls
series e:tsak-vtv3 d:2017-03-08T21:23:18.000Z t:upcoming_project_budget_range="1 M - 4 M" t:upcoming_project_category="Ext.  Work" t:upcoming_project_name="ARCHER ELEMENTARY SCHOOL - BRO" t:upcoming_project_borough_=BRONX t:upcoming_project_description=ROOFS t:upcoming_project_status_=Design t:upcoming_project_geographic_district=12 t:upcoming_project_design_number=D016474 m:row_number.tsak-vtv3=1

series e:tsak-vtv3 d:2017-03-08T21:23:18.000Z t:upcoming_project_budget_range="4 M OVER" t:upcoming_project_category="Boilers/Heating Plant Upgrade" t:upcoming_project_name="BRONX CNTR FOR SCIENCE & MATH" t:upcoming_project_borough_=BRONX t:upcoming_project_description="PLANYC BOILER CONVERSION" t:upcoming_project_status_=Design t:upcoming_project_geographic_district=09 t:upcoming_project_design_number=D017541 m:row_number.tsak-vtv3=2

series e:tsak-vtv3 d:2017-03-08T21:23:18.000Z t:upcoming_project_budget_range="4 M OVER" t:upcoming_project_category="Building Systems" t:upcoming_project_name="BRONX CNTR FOR SCIENCE & MATH" t:upcoming_project_borough_=BRONX t:upcoming_project_description="PLANYC CLIMATE CONTROL" t:upcoming_project_status_=Design t:upcoming_project_geographic_district=09 t:upcoming_project_design_number=D017541 m:row_number.tsak-vtv3=3
```

## Meta Commands

```ls
metric m:row_number.tsak-vtv3 p:long l:"Row Number"

entity e:tsak-vtv3 l:"Upcoming contracts to be awarded (CIP)" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/tsak-vtv3

property e:tsak-vtv3 t:meta.view v:id=tsak-vtv3 v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Business/WorkingWithTheSCA/Construction/ContractAwards/Pages/CIPAwards.aspx v:averageRating=0 v:name="Upcoming contracts to be awarded (CIP)" v:attribution="School Construction Authority (SCA)"

property e:tsak-vtv3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tsak-vtv3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | upcoming_project_design_number | upcoming_project_name          | upcoming_project_borough_ | upcoming_project_geographic_district | upcoming_project_description        | upcoming_project_budget_range | upcoming_project_design_completion_date | upcoming_project_category     | upcoming_project_status_ | 
| =========== | ============================== | ============================== | ========================= | ==================================== | =================================== | ============================= | ======================================= | ============================= | ======================== | 
| 1489008198  | D016474                        | ARCHER ELEMENTARY SCHOOL - BRO | BRONX                     | 12                                   | ROOFS                               | 1 M - 4 M                     | 2017/02                                 | Ext. Work                     | Design                   | 
| 1489008198  | D017541                        | BRONX CNTR FOR SCIENCE & MATH  | BRONX                     | 09                                   | PLANYC BOILER CONVERSION            | 4 M OVER                      | 2017/05                                 | Boilers/Heating Plant Upgrade | Design                   | 
| 1489008198  | D017541                        | BRONX CNTR FOR SCIENCE & MATH  | BRONX                     | 09                                   | PLANYC CLIMATE CONTROL              | 4 M OVER                      | 2017/05                                 | Building Systems              | Design                   | 
| 1489008198  | D016468                        | BRONX HS FOR THE VISUAL ARTS - | BRONX                     | 11                                   | COMPLETION OF PHASE II MERCY COLLEG | $750-1M                       | 2017/02                                 | Electrical (Exclude RCT)      | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | FLOOD ELIMINATION                   | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | INTERIOR SPACES                     | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | ROOFS                               | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | SITE WORK                           | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | TOWER TERRA COTTA REPLACEMENT       | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
| 1489008198  | D016617                        | BRONX INTERNATIONAL - BRONX    | BRONX                     | 09                                   | WINDOWS                             | 4 M OVER                      | 2017/05                                 | Ext. Work                     | Design                   | 
```