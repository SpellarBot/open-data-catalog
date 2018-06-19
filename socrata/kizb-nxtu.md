# Metropolitan Transportation Authority (MTA) Capital Dashboard Agencies Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/metropolitan-transportation-authority-mta-capital-dashboard-agencies-detail) |
| Metadata | [Link](https://data.ny.gov/api/views/kizb-nxtu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kizb-nxtu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kizb-nxtu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kizb-nxtu |
| Name | Metropolitan Transportation Authority (MTA) Capital Dashboard Agencies Detail |
| Attribution | MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels |
| Category | Transportation |
| Tags | capital program, mta capital plan |
| Created | 2013-05-02T15:15:27Z |
| Publication Date | 2017-01-06T23:06:26Z |

## Description

The Capital Dashboard data provides information about the projects in the MTA?s 2010 to 2014 and 2005 ? 2009 Capital Programs.  The data describes the planned projects and provide information about the status of Project Budgets, Scopes and Schedules. This dataset organizes information at the agency level

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                          | Data Type | Render Type |
| ======== | ============== | =========================== | ============================= | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | project_number              | Project Number                | text      | text        |
| Yes      | series tag     | capital_plan                | Capital Plan                  | text      | text        |
| Yes      | series tag     | agency_name                 | Agency Name                   | text      | text        |
| Yes      | numeric metric | plan_revision               | Plan Revision                 | number    | number      |
| No       |                | budget_submission_date      | Budget Submission Date        | text      | text        |
| Yes      | series tag     | project_descrition          | Project Description           | text      | text        |
| Yes      | series tag     | change_narrative            | Change Narrative              | text      | text        |
| Yes      | numeric metric | plan_year_year_1_allocation | Plan Year - Year 1 Allocation | money     | money       |
| Yes      | numeric metric | plan_year_year_2_allocation | Plan Year - Year 2 Allocation | money     | money       |
| Yes      | numeric metric | plan_year_year_3_allocation | Plan Year - Year 3 Allocation | money     | money       |
| Yes      | numeric metric | plan_year_year_4_allocation | Plan Year - Year 4 Allocation | money     | money       |
| Yes      | numeric metric | plan_year_year_5_allocation | Plan Year - Year 5 Allocation | money     | money       |
| Yes      | numeric metric | out_years_allocation        | Out Years Allocation          | money     | money       |
| Yes      | numeric metric | total_allocation            | Total Allocation              | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = budget_submission_date
```

## Data Commands

```ls
series e:kizb-nxtu d:2017-01-06T23:06:10.000Z t:project_descrition="Deck and Structural Rehabilitation - Cross Bay Bridge" t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D501CB08 t:agency_name="Bridges and Tunnels" m:plan_revision=200504 m:total_allocation=48845 m:plan_year_year_2_allocation=48845

series e:kizb-nxtu d:2017-01-06T23:06:10.000Z t:project_descrition="Deck and Structural Rehabilitation - Cross Bay Bridge" t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D501CB08 t:change_narrative="Revised estimate to include CCTV and fiber optic work" t:agency_name="Bridges and Tunnels" m:plan_revision=200512 m:total_allocation=49845 m:plan_year_year_2_allocation=49845

series e:kizb-nxtu d:2017-01-06T23:06:10.000Z t:project_descrition="Deck and Structural Rehabilitation - Cross Bay Bridge" t:capital_plan="Capital Plan 2005 - 2009" t:project_number=D501CB08 t:change_narrative="Budget was revised based on costs of construction and support requirements at time of award" t:agency_name="Bridges and Tunnels" m:plan_revision=200612 m:total_allocation=67917 m:plan_year_year_2_allocation=5023 m:plan_year_year_3_allocation=62894
```

## Meta Commands

```ls
metric m:plan_revision p:integer l:"Plan Revision" d:"This is the Plan Amendment Key that is used to link to the Capital Dashboard Summary data. See information on PLAN_REV_KEYS above. The key is in an YYYYMM format. A value of 999999 indicates the most current detail record with in the current Plan Amendment." t:dataTypeName=number

metric m:plan_year_year_1_allocation p:integer l:"Plan Year - Year 1 Allocation" d:"The Plan Year allocation is defined as a series of monetary commitments the MTA will make in various years in order to implement a project." t:dataTypeName=money

metric m:plan_year_year_2_allocation p:integer l:"Plan Year - Year 2 Allocation" d:"The Plan Year allocation is defined as a series of monetary commitments the MTA will make in various years in order to implement a project." t:dataTypeName=money

metric m:plan_year_year_3_allocation p:integer l:"Plan Year - Year 3 Allocation" d:"The Plan Year allocation is defined as a series of monetary commitments the MTA will make in various years in order to implement a project." t:dataTypeName=money

metric m:plan_year_year_4_allocation p:integer l:"Plan Year - Year 4 Allocation" d:"The Plan Year allocation is defined as a series of monetary commitments the MTA will make in various years in order to implement a project." t:dataTypeName=money

metric m:plan_year_year_5_allocation p:integer l:"Plan Year - Year 5 Allocation" d:"The Plan Year allocation is defined as a series of monetary commitments the MTA will make in various years in order to implement a project." t:dataTypeName=money

metric m:out_years_allocation p:integer l:"Out Years Allocation" d:"This field captures budget allocations for projects which are committed after the 5th year of a Capital Plan." t:dataTypeName=money

metric m:total_allocation p:integer l:"Total Allocation" d:"This is the sum of the budgetary commitments that the MTA plans to make in order to fully implement a project." t:dataTypeName=money

entity e:kizb-nxtu l:"Metropolitan Transportation Authority (MTA) Capital Dashboard Agencies Detail" t:attribution="MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels" t:url=https://data.ny.gov/api/views/kizb-nxtu

property e:kizb-nxtu t:meta.view v:id=kizb-nxtu v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Metropolitan Transportation Authority (MTA) Capital Dashboard Agencies Detail" v:attribution="MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels"

property e:kizb-nxtu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kizb-nxtu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | project_number | capital_plan             | agency_name         | plan_revision | budget_submission_date | project_descrition                                     | change_narrative                                                                            | plan_year_year_1_allocation | plan_year_year_2_allocation | plan_year_year_3_allocation | plan_year_year_4_allocation | plan_year_year_5_allocation | out_years_allocation | total_allocation | 
| =========== | ============== | ======================== | =================== | ============= | ====================== | ====================================================== | =========================================================================================== | =========================== | =========================== | =========================== | =========================== | =========================== | ==================== | ================ | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200504        | 2005 Apr.              | Deck and Structural Rehabilitation - Cross Bay Bridge  |                                                                                             |                             | 48845                       |                             |                             |                             |                      | 48845            | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200512        | 2005 Dec.              | Deck and Structural Rehabilitation - Cross Bay Bridge  | Revised estimate to include CCTV and fiber optic work                                       |                             | 49845                       |                             |                             |                             |                      | 49845            | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200612        | 2006 Dec.              | Deck and Structural Rehabilitation - Cross Bay Bridge  | Budget was revised based on costs of construction and support requirements at time of award |                             | 5023                        | 62894                       |                             |                             |                      | 67917            | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200807        | 2008 Jul.              | Deck and Structural Rehabilitation - Cross Bay Bridge  | Reflects addition of Variable Speed Limit Signs                                             |                             | 5625                        | 63717                       |                             |                             |                      | 69342            | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200907        | 2009 Jul.              | Deck and Structural Rehabilitation - Cross Bay Bridge  |                                                                                             |                             | 5625                        | 63717                       |                             |                             |                      | 69342            | 
| 1483743970  | D501CB08       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 999999        | Current                | Deck and structural rehabilitation - Cross Bay Bridge. | Budget revised to reflect estimate at completion.                                           |                             | 4699                        | 58368                       |                             |                             |                      | 63066            | 
| 1483743970  | D501TN85       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200504        | 2005 Apr.              | Suspended Span Cable Rewrap.                           |                                                                                             | 1491                        | 7189                        |                             |                             |                             |                      | 8680             | 
| 1483743970  | D501TN85       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200512        | 2005 Dec.              | Suspended Span Cable Rewrap.                           | Scope change to add catwalk work formerly part of another project (TN-47).                  | 904                         | 15349                       |                             |                             |                             |                      | 16253            | 
| 1483743970  | D501TN85       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200612        | 2006 Dec.              | Suspended Span Cable Rewrap.                           | Budget reflects favorable construction bid (Phase B).                                       | 904                         | 14650                       |                             |                             |                             |                      | 15554            | 
| 1483743970  | D501TN85       | Capital Plan 2005 - 2009 | Bridges and Tunnels | 200807        | 2008 Jul.              | Suspended Span Cable Rewrap                            | Reflects estimate to complete (Phase B).                                                    | 975                         | 14650                       |                             |                             |                             |                      | 15625            | 
```