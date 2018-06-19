# Building Plan Review Projects Submitted for Review In FY16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-plan-review-projects-submitted-for-review-in-fy16) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kccz-7kam) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kccz-7kam/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kccz-7kam/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kccz-7kam |
| Name | Building Plan Review Projects Submitted for Review In FY16 |
| Attribution | Development Services Department |
| Category | Permitting |
| Created | 2016-09-27T14:12:50Z |
| Publication Date | 2016-09-27T17:26:47Z |

## Description

All Building Plan Review projects submitted for review in FY2016.  

Here is a rundown of the criteria behind this dataset:
1)	Does not include ?Express? 
2)	Does include ?Quick Turnaround?
3)	Submitted/distributed for review within the Fiscal Year date range (October 01, 2015 through September 30, 2016)
4)	Does not include Total Demolitions or Relocations

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | review_cycle_start_fy         | REVIEW_CYCLE_START_FY         | text      | text        |
| Yes      | series tag     | folder_id                     | FOLDER_ID                     | text      | number      |
| Yes      | series tag     | project_name                  | PROJECT_NAME                  | text      | text        |
| Yes      | series tag     | sub_type                      | SUB_TYPE                      | text      | text        |
| Yes      | series tag     | work_type                     | WORK_TYPE                     | text      | text        |
| Yes      | series tag     | status                        | STATUS                        | text      | text        |
| Yes      | numeric metric | total_newaddition_bldg_sqft   | TOTAL_NEWADDITION_BLDG_SQFT   | number    | number      |
| Yes      | numeric metric | total_remodelrepair_bldg_sqft | TOTAL_REMODELREPAIR_BLDG_SQFT | number    | number      |
| Yes      | numeric metric | building_sqft_reviewed        | BUILDING_SQFT_REVIEWED        | number    | number      |
| Yes      | numeric metric | total_remodel_valuation       | TOTAL_REMODEL_VALUATION       | money     | money       |
| Yes      | numeric metric | total_job_valuation           | TOTAL_JOB_VALUATION           | money     | money       |
| Yes      | series tag     | quick_turnaround              | Quick Turnaround?             | text      | text        |
| Yes      | series tag     | link                          | LINK                          | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kccz-7kam d:2016-09-27T17:26:02.000Z t:folder_id=11410827 t:project_name="1115 W 11TH ST" t:status=Expired t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11410827" t:quick_turnaround="Non-Quick Turnaround" t:work_type=New t:sub_type="C- 101 Single Family Houses" t:review_cycle_start_fy=FY2016 m:building_sqft_reviewed=0 m:total_newaddition_bldg_sqft=0 m:total_job_valuation=2575000

series e:kccz-7kam d:2016-09-27T17:26:02.000Z t:folder_id=11385963 t:project_name="4711 E RIVERSIDE DR BLDG 1" t:status=Approved t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11385963" t:quick_turnaround="Non-Quick Turnaround" t:work_type=New t:sub_type="C- 104 Three & Four Family Bldgs" t:review_cycle_start_fy=FY2016 m:building_sqft_reviewed=280571 m:total_newaddition_bldg_sqft=281790 m:total_job_valuation=23143944

series e:kccz-7kam d:2016-09-27T17:26:02.000Z t:folder_id=11500313 t:project_name="110 ACADEMY DR" t:status="In Review" t:link="https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11500313" t:quick_turnaround="Non-Quick Turnaround" t:work_type=New t:sub_type="C- 104 Three & Four Family Bldgs" t:review_cycle_start_fy=FY2016 m:building_sqft_reviewed=0 m:total_newaddition_bldg_sqft=0 m:total_job_valuation=27500000
```

## Meta Commands

```ls
metric m:total_newaddition_bldg_sqft p:integer l:TOTAL_NEWADDITION_BLDG_SQFT t:dataTypeName=number

metric m:total_remodelrepair_bldg_sqft p:integer l:TOTAL_REMODELREPAIR_BLDG_SQFT t:dataTypeName=number

metric m:building_sqft_reviewed p:integer l:BUILDING_SQFT_REVIEWED t:dataTypeName=number

metric m:total_remodel_valuation p:integer l:TOTAL_REMODEL_VALUATION t:dataTypeName=money

metric m:total_job_valuation p:integer l:TOTAL_JOB_VALUATION t:dataTypeName=money

entity e:kccz-7kam l:"Building Plan Review Projects Submitted for Review In FY16" t:attribution="Development Services Department" t:url=https://data.austintexas.gov/api/views/kccz-7kam

property e:kccz-7kam t:meta.view v:id=kccz-7kam v:category=Permitting v:averageRating=0 v:name="Building Plan Review Projects Submitted for Review In FY16" v:attribution="Development Services Department"

property e:kccz-7kam t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:kccz-7kam t:meta.view.owner v:id=g2b7-fzfu v:screenName=Julia v:displayName=Julia

property e:kccz-7kam t:meta.view.tableauthor v:id=g2b7-fzfu v:screenName=Julia v:roleName=publisher v:displayName=Julia
```

## Top Records

```ls
| :updated_at | review_cycle_start_fy | folder_id | project_name                 | sub_type                         | work_type | status             | total_newaddition_bldg_sqft | total_remodelrepair_bldg_sqft | building_sqft_reviewed | total_remodel_valuation | total_job_valuation | quick_turnaround     | link                                                                                                 | 
| =========== | ===================== | ========= | ============================ | ================================ | ========= | ================== | =========================== | ============================= | ====================== | ======================= | =================== | ==================== | ==================================================================================================== | 
| 1474997162  | FY2016                | 11410827  | 1115 W 11TH ST               | C- 101 Single Family Houses      | New       | Expired            | 0                           |                               | 0                      |                         | 2575000             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11410827, null] | 
| 1474997162  | FY2016                | 11385963  | 4711 E RIVERSIDE DR BLDG 1   | C- 104 Three & Four Family Bldgs | New       | Approved           | 281790                      |                               | 280571                 |                         | 23143944            | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11385963, null] | 
| 1474997162  | FY2016                | 11500313  | 110 ACADEMY DR               | C- 104 Three & Four Family Bldgs | New       | In Review          | 0                           |                               | 0                      |                         | 27500000            | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11500313, null] | 
| 1474997162  | FY2016                | 11521083  | 1101 E PARMER LN             | C- 104 Three & Four Family Bldgs | New       | Withdrawn          | 0                           |                               | 0                      |                         | 2145000             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11521083, null] | 
| 1474997162  | FY2016                | 11549602  | 9009 GREAT HILLS TRL BLDG 10 | C- 104 Three & Four Family Bldgs | New       | In Review          | 0                           |                               | 14799                  |                         | 1331910             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11549602, null] | 
| 1474997162  | FY2016                | 11577878  | 1411 TOWN CREEK DR UNIT 4    | C- 104 Three & Four Family Bldgs | New       | Awaiting Update    | 0                           |                               | 0                      |                         | 5137230             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11577878, null] | 
| 1474997162  | FY2016                | 11259600  | 1306 WEST AVE                | C- 105 Five or More Family Bldgs | New       | Approved           | 18821                       |                               | 39624                  |                         | 2282734             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11259600, null] | 
| 1474997162  | FY2016                | 11261693  | 10727 DOMAIN DR              | C- 105 Five or More Family Bldgs | New       | Approved           | 579525                      |                               | 579525                 |                         | 39920897            | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11261693, null] | 
| 1474997162  | FY2016                | 11281568  | 211 W JOHANNA ST             | C- 105 Five or More Family Bldgs | New       | Approved           | 43694                       |                               | 43694                  |                         | 3495520             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11281568, null] | 
| 1474997162  | FY2016                | 11293945  | 908 NUECES ST                | C- 105 Five or More Family Bldgs | New       | Revision In Review | 57004                       |                               | 57004                  |                         | 4800000             | Non-Quick Turnaround | [https://www.austintexas.gov/devreview/b_showpublicpermitfolderdetails.jsp?FolderRSN=11293945, null] | 
```