# Active Projects Under Construction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-projects-under-construction-5a4b0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2xh6-psuq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2xh6-psuq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2xh6-psuq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2xh6-psuq |
| Name | Active Projects Under Construction |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, capital, improvement, project, current, education |
| Created | 2013-08-22T19:00:41Z |
| Publication Date | 2016-02-09T08:04:14Z |

## Description

New school projects (Capacity) and Capital Improvement Projects (CIP) currently under Construction.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                                | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | project_geographic_district_                               | Project Geographic District                                | text      | text        |
| Yes      | series tag     | project_building_identifier                                | Project Building Identifier                                | text      | text        |
| Yes      | series tag     | project_school_name                                        | Project School Name                                        | text      | text        |
| Yes      | series tag     | project_type_                                              | Project Type                                               | text      | text        |
| Yes      | series tag     | project_description                                        | Project Description                                        | text      | text        |
| Yes      | series tag     | project_phase_name                                         | Project Phase Name                                         | text      | text        |
| Yes      | series tag     | project_status_name                                        | Project Status Name                                        | text      | text        |
| No       |                | project_phase_actual_start_date                            | Project Phase Actual Start Date                            | text      | text        |
| No       |                | project_phase_planned_end_date                             | Project Phase Planned End Date                             | text      | text        |
| No       |                | project_phase_actual_end_date                              | Project Phase Actual End Date                              | text      | text        |
| Yes      | series tag     | project_budget_amount                                      | Project Budget Amount                                      | text      | text        |
| Yes      | series tag     | final_estimate_of_actual_costs_through_end_of_phase_amount | Final Estimate of Actual Costs Through End of Phase Amount | text      | text        |
| Yes      | numeric metric | total_phase_actual_spending_amount                         | Total Phase Actual Spending Amount                         | money     | money       |
| Yes      | series tag     | dsf_number_s_                                              | DSF Number(s)                                              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = project_phase_actual_start_date,project_phase_planned_end_date,project_phase_actual_end_date
```

## Data Commands

```ls
series e:2xh6-psuq d:2016-02-09T00:03:33.000Z t:dsf_number_s_="DSF: 0000022397, 0000774535, 0000774536" t:project_budget_amount=9444095 t:project_geographic_district_=08 t:project_building_identifier=X650 t:project_school_name="JANE ADDAMS VOC HS - X" t:project_status_name=Complete t:project_phase_name=Construction t:final_estimate_of_actual_costs_through_end_of_phase_amount=8890977 t:project_description="DAMAGED EXTERIOR WALLS/ROOFS/PARAPETS" t:project_type_="SCA CIP" m:total_phase_actual_spending_amount=8504318

series e:2xh6-psuq d:2016-02-09T00:03:33.000Z t:dsf_number_s_="DSF: 0000022397, 0000774535, 0000774536" t:project_budget_amount=887721 t:project_geographic_district_=08 t:project_building_identifier=X650 t:project_school_name="JANE ADDAMS VOC HS - X" t:project_status_name=Complete t:project_phase_name="CM, F&E" t:final_estimate_of_actual_costs_through_end_of_phase_amount=479580 t:project_description="DAMAGED EXTERIOR WALLS/ROOFS/PARAPETS" t:project_type_="SCA CIP" m:total_phase_actual_spending_amount=470508

series e:2xh6-psuq d:2016-02-09T00:03:33.000Z t:dsf_number_s_="DSF: 0000797270" t:project_budget_amount=11611 t:project_geographic_district_=08 t:project_building_identifier=X650 t:project_school_name="JANE ADDAMS VOC HS - X" t:project_status_name=Complete t:project_phase_name=Scope t:final_estimate_of_actual_costs_through_end_of_phase_amount=491 t:project_description="ELECTRICAL LIGHTING FIXTURES" t:project_type_="RCT CIP" m:total_phase_actual_spending_amount=491
```

## Meta Commands

```ls
metric m:total_phase_actual_spending_amount p:double l:"Total Phase Actual Spending Amount" d:"Actual cumulative expenditures by phase" t:dataTypeName=money

entity e:2xh6-psuq l:"Active Projects Under Construction" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/2xh6-psuq

property e:2xh6-psuq t:meta.view v:id=2xh6-psuq v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Community/CapitalPlanManagementReportsData/QuarterlyStatus/cc_qr04_by_geodist.pdf v:averageRating=0 v:name="Active Projects Under Construction" v:attribution="School Construction Authority (SCA)"

property e:2xh6-psuq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2xh6-psuq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | project_geographic_district_ | project_building_identifier | project_school_name    | project_type_ | project_description                   | project_phase_name | project_status_name | project_phase_actual_start_date | project_phase_planned_end_date | project_phase_actual_end_date | project_budget_amount | final_estimate_of_actual_costs_through_end_of_phase_amount | total_phase_actual_spending_amount | dsf_number_s_                           | 
| =========== | ============================ | =========================== | ====================== | ============= | ===================================== | ================== | =================== | =============================== | ============================== | ============================= | ===================== | ========================================================== | ================================== | ======================================= | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | SCA CIP       | DAMAGED EXTERIOR WALLS/ROOFS/PARAPETS | Construction       | Complete            | 07/22/2013                      | 07/21/2015                     | 09/10/2015                    | 9444095               | 8890977                                                    | 8504318.00                         | DSF: 0000022397, 0000774535, 0000774536 | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | SCA CIP       | DAMAGED EXTERIOR WALLS/ROOFS/PARAPETS | CM, F&E            | Complete            | 07/22/2013                      | 07/21/2015                     | 09/10/2015                    | 887721                | 479580                                                     | 470508.00                          | DSF: 0000022397, 0000774535, 0000774536 | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | RCT CIP       | ELECTRICAL LIGHTING FIXTURES          | Scope              | Complete            | 08/10/2015                      | 08/10/2015                     | 08/10/2015                    | 11611                 | 491                                                        | 491.00                             | DSF: 0000797270                         | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | RCT CIP       | ELECTRICAL LIGHTING FIXTURES          | Design             | Complete            | 08/10/2015                      | 12/10/2015                     | 10/08/2015                    | 32897                 | 1963                                                       | 1963.00                            | DSF: 0000797270                         | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | RCT CIP       | ELECTRICAL LIGHTING FIXTURES          | Construction       | PNS                 | PNS                             | PNS                            | PNS                           | 443146                | 443146                                                     | 1826.00                            | DSF: 0000797270                         | 
| 1454976213  | 08                           | X650                        | JANE ADDAMS VOC HS - X | RCT CIP       | ELECTRICAL LIGHTING FIXTURES          | CM, F&E            | PNS                 | PNS                             | PNS                            | PNS                           | 85146                 | 85146                                                      | 2242.00                            | DSF: 0000797270                         | 
| 1454976213  | 08                           | X650                        | H.S. 559 - BRONX       | SCA CIP RESOA | FY16 RESO A ROOM CONVERSIONS / PART   | Scope              | PNS                 | PNS                             | PNS                            | PNS                           | 0                     | 0                                                          | 0.00                               | DSF: 0000822711                         | 
| 1454976213  | 08                           | X650                        | H.S. 559 - BRONX       | SCA CIP RESOA | FY16 RESO A ROOM CONVERSIONS / PART   | Design             | PNS                 | PNS                             | PNS                            | PNS                           | 30000                 | 30000                                                      | 0.00                               | DSF: 0000822711                         | 
| 1454976213  | 08                           | X650                        | H.S. 559 - BRONX       | SCA CIP RESOA | FY16 RESO A ROOM CONVERSIONS / PART   | Construction       | PNS                 | PNS                             | PNS                            | PNS                           | 440000                | 440000                                                     | 0.00                               | DSF: 0000822711                         | 
| 1454976213  | 08                           | X650                        | H.S. 559 - BRONX       | SCA CIP RESOA | FY16 RESO A ROOM CONVERSIONS / PART   | CM, F&E            | PNS                 | PNS                             | PNS                            | PNS                           | 30000                 | 30000                                                      | 0.00                               | DSF: 0000822711                         | 
```