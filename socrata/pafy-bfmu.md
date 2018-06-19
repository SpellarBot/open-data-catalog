# OPA Complaint Tracker

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/opa-complaint-tracker) |
| Metadata | [Link](https://data.seattle.gov/api/views/pafy-bfmu) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/pafy-bfmu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/pafy-bfmu/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | pafy-bfmu |
| Name | OPA Complaint Tracker |
| Attribution | OPA |
| Category | City Business |
| Tags | opa |
| Created | 2015-03-25T20:41:24Z |
| Publication Date | 2017-04-20T17:18:30Z |

## Description

Office of Professional Accountability Complaint Tracker Status.
Making the work of the OPA transparent promotes the confidence of both the public and the employees of the department. OPA provides data status of complaints filed and issues of community concern.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | opa_case_number      | OPA Case Number      | text      | text        |
| Yes      | series tag  | status_description   | Status Description   | text      | text        |
| Yes      | series tag  | external_case_number | External Case Number | text      | text        |
| No       |             | due_date_2           | Due_Date             | text      | text        |
| No       |             | completed_date_2     | Completed_Date       | text      | text        |
| No       |             | task_creation_date_2 | Task_Creation_Date   | text      | text        |
| Yes      | series tag  | currentstatus        | CurrentStatus        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = due_date_2,completed_date_2,task_creation_date_2
```

## Data Commands

```ls
series e:pafy-bfmu d:2017-04-20T17:14:33.000Z t:status_description="OPA Close CL" t:opa_case_number=2015OPA-0433 t:currentstatus=Done m:row_number.pafy-bfmu=1

series e:pafy-bfmu d:2017-04-20T17:14:33.000Z t:status_description="OPA Close Case" t:external_case_number=2015-191974 t:opa_case_number=2015OPA-0826 t:currentstatus=Done m:row_number.pafy-bfmu=2

series e:pafy-bfmu d:2017-04-20T17:14:33.000Z t:status_description="OPA Director SA Review" t:opa_case_number=2015OPA-0514 t:currentstatus=Done m:row_number.pafy-bfmu=3
```

## Meta Commands

```ls
metric m:row_number.pafy-bfmu p:long l:"Row Number"

entity e:pafy-bfmu l:"OPA Complaint Tracker" t:attribution=OPA t:url=https://data.seattle.gov/api/views/pafy-bfmu

property e:pafy-bfmu t:meta.view v:id=pafy-bfmu v:category="City Business" v:averageRating=0 v:name="OPA Complaint Tracker" v:attribution=OPA

property e:pafy-bfmu t:meta.view.license v:name="Public Domain"

property e:pafy-bfmu t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:pafy-bfmu t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | opa_case_number | status_description     | external_case_number | due_date_2 | completed_date_2 | task_creation_date_2 | currentstatus | 
| =========== | =============== | ====================== | ==================== | ========== | ================ | ==================== | ============= | 
| 1492708473  | 2015OPA-0433    | OPA Close CL           |                      |            | 3/31/15          | 10/20/15             | Done          | 
| 1492708473  | 2015OPA-0826    | OPA Close Case         | 2015-191974          |            | 12/23/15         | 12/4/15              | Done          | 
| 1492708473  | 2015OPA-0514    | OPA Director SA Review |                      | 5/17/15    | 5/20/15          | 5/12/15              | Done          | 
| 1492708473  | 2016OPA-0842    | OPA Close CL           |                      | 8/10/16    | 8/8/16           | 8/5/16               | Done          | 
| 1492708473  | 2015OPA-0752    | OPA Close CL           |                      |            | 6/15/15          | 10/19/15             | Done          | 
| 1492708473  | 2015OPA-1777    | OPA Close CL           |                      | 11/28/15   | 11/30/15         | 11/23/15             | Done          | 
| 1492708473  | 2016OPA-0636    | OPA Close Case         |                      | 12/9/16    | 12/9/16          | 12/2/16              | Done          | 
| 1492708473  | 2016OPA-0599    | OPA Close CL           |                      | 7/2/16     | 6/30/16          | 6/27/16              | Done          | 
| 1492708473  | 2015OPA-0079    | OPA Close CL           |                      |            | 1/26/15          | 10/23/15             | Done          | 
| 1492708473  | 2016OPA-1236    | OPA Close CL           |                      | 11/14/16   | 10/17/16         | 10/10/16             | Done          | 
```