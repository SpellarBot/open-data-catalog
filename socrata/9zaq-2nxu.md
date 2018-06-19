# Captial Planning - Clean Steam Piping Replacement - Milestones Report 11 October 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/captial-planning-clean-steam-piping-replacement-milestones-report-11-october-2011-454ed) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9zaq-2nxu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9zaq-2nxu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9zaq-2nxu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9zaq-2nxu |
| Name | Captial Planning - Clean Steam Piping Replacement - Milestones Report 11 October 2011 |
| Attribution | Cook County Department of Captial Planning and Policy |
| Category | Economic Development |
| Created | 2011-10-11T15:43:53Z |
| Publication Date | 2014-10-09T22:22:20Z |

## Description

Click the "About" button to access a pdf with a full description of this project.

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type | Render Type |
| ======== | =========== | ================ | ================= | ========= | =========== |
| Yes      | series tag  | company_name     | Company Name      | text      | text        |
| Yes      | series tag  | project          | Project           | text      | text        |
| Yes      | series tag  | milestone        | Milestone         | text      | text        |
| Yes      | series tag  | status           | Status            | text      | text        |
| Yes      | time        | due_date         | Due Date          | date      | date        |
| Yes      | series tag  | overdue_by_days_ | Overdue By (days) | text      | text        |
| No       |             | date_completed   | Date Completed    | text      | text        |
```

## Time Field

```ls
Value = due_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_completed
```

## Data Commands

```ls
series e:9zaq-2nxu d:2011-11-04T07:00:00.000Z t:milestone="95% CDs (contingent on IDPH review being complete)" t:project="Clean Steam Piping Replacement" t:status=new t:company_name="CC Health & Hospitals System" m:row_number.9zaq-2nxu=1

series e:9zaq-2nxu d:2011-11-16T08:00:00.000Z t:milestone="95% County CD Review" t:project="Clean Steam Piping Replacement" t:status=new t:company_name="CC Health & Hospitals System" m:row_number.9zaq-2nxu=2

series e:9zaq-2nxu d:2011-11-22T08:00:00.000Z t:milestone="Advertise for Bid (contingent on Purchasing Approval)" t:project="Clean Steam Piping Replacement" t:status=new t:company_name="CC Health & Hospitals System" m:row_number.9zaq-2nxu=3
```

## Meta Commands

```ls
metric m:row_number.9zaq-2nxu p:long l:"Row Number"

entity e:9zaq-2nxu l:"Captial Planning - Clean Steam Piping Replacement - Milestones Report 11 October 2011" t:attribution="Cook County Department of Captial Planning and Policy" t:url=https://datacatalog.cookcountyil.gov/api/views/9zaq-2nxu

property e:9zaq-2nxu t:meta.view v:id=9zaq-2nxu v:category="Economic Development" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/capital_planning_and_policy%2C_office_of/254/capital_planning_and_policy%2C_office_oflicy%2C_office_of v:averageRating=0 v:name="Captial Planning - Clean Steam Piping Replacement - Milestones Report 11 October 2011" v:attribution="Cook County Department of Captial Planning and Policy"

property e:9zaq-2nxu t:meta.view.license v:name="Public Domain"

property e:9zaq-2nxu t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:9zaq-2nxu t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| company_name                 | project                        | milestone                                                                             | status   | due_date   | overdue_by_days_ | date_completed | 
| ============================ | ============================== | ===================================================================================== | ======== | ========== | ================ | ============== | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | 95% CDs (contingent on IDPH review being complete)                                    | new      | 1320390000 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | 95% County CD Review                                                                  | new      | 1321430400 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Advertise for Bid (contingent on Purchasing Approval)                                 | new      | 1321948800 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | PreBid Conference & Site Inspection                                                   | new      | 1323936000 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Bid Opening (contingent on 2012 Bid Opening Dates being confirmed)                    | new      | 1326268800 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Bid Review, Award & Execution of Contract for Work                                    | new      | 1328601600 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Start Project: GC obtain Hosp IDs and Permits                                         | new      | 1333695600 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Issue Notice to Proceed                                                               | new      | 1334041200 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Project Substantial Completion (Contingent on JSH ability to conform to phasing plan) | new      | 1365577200 |                  |                | 
| CC Health & Hospitals System | Clean Steam Piping Replacement | Punch list, Final Completion & Closeout                                               | reopened | 1372489200 |                  |                | 
```