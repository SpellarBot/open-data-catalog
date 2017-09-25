# Template011: Project Phase List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/template011-project-phase-list) |
| Metadata | [Link](https://data.srcity.org/api/views/dmhd-88xr) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/dmhd-88xr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/dmhd-88xr/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | dmhd-88xr |
| Name | Template011: Project Phase List |
| Created | 2015-11-05T22:36:00Z |
| Publication Date | 2017-07-05T18:12:18Z |

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | phase_type             | Phase Type             | text      | text        |
| Yes      | series tag  | phase_step_number      | Phase Step Number      | text      | number      |
| Yes      | series tag  | phase_step_name        | Phase Step Name        | text      | text        |
| Yes      | series tag  | phase_step_description | Phase Step Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dmhd-88xr d:2017-07-05T18:11:32.000Z t:phase_step_name="Preliminary Design" t:phase_type=default t:phase_step_description="Architects and engineers work from the defined scope and budget to develop the design, and  produce construction drawings, etc." t:phase_step_number=2 m:row_number.dmhd-88xr=1

series e:dmhd-88xr d:2017-07-05T18:11:32.000Z t:phase_step_name="Final Design" t:phase_type=default t:phase_step_description="Design complete. Construction documents complete. Ready to award contract." t:phase_step_number=3 m:row_number.dmhd-88xr=2

series e:dmhd-88xr d:2017-07-05T18:11:32.000Z t:phase_step_name="Bids Let" t:phase_type=default t:phase_step_description="Contractor is selected based on several procurement criteria" t:phase_step_number=4 m:row_number.dmhd-88xr=3
```

## Meta Commands

```ls
metric m:row_number.dmhd-88xr p:long l:"Row Number"

entity e:dmhd-88xr l:"Template011: Project Phase List" t:url=https://data.srcity.org/api/views/dmhd-88xr

property e:dmhd-88xr t:meta.view d:2017-09-25T07:26:12.244Z v:averageRating=0 v:name="Template011: Project Phase List" v:id=dmhd-88xr

property e:dmhd-88xr t:meta.view.owner d:2017-09-25T07:26:12.244Z v:displayName="Tickner, Brian" v:lastNotificationSeenAt=1504743279 v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:id=4jau-mr7g v:screenName="Tickner, Brian" v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB

property e:dmhd-88xr t:meta.view.tableauthor d:2017-09-25T07:26:12.244Z v:displayName="Tickner, Brian" v:lastNotificationSeenAt=1504743279 v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:id=4jau-mr7g v:screenName="Tickner, Brian" v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | phase_type | phase_step_number | phase_step_name    | phase_step_description                                                                                                         | 
| =========== | ========== | ================= | ================== | ============================================================================================================================== | 
| 1499278292  | default    | 2                 | Preliminary Design | Architects and engineers work from the defined scope and budget to develop the design, and produce construction drawings, etc. | 
| 1499278292  | default    | 3                 | Final Design       | Design complete. Construction documents complete. Ready to award contract.                                                     | 
| 1499278292  | default    | 4                 | Bids Let           | Contractor is selected based on several procurement criteria                                                                   | 
| 1499278292  | default    | 5                 | Under Construction | Contractors work from the instructions contained in design documents to complete facility.                                     | 
| 1499278292  | default    | 6                 | Ongoing            | Refers to level of effort projects or projects that occur each year (i.e., roof replacement)                                   | 
| 1499278292  | default    | 7                 | Completed          | All project activities have been completed and paid for.                                                                       | 
| 1499278292  | N/A        | 1                 | N/A                | CIP                                                                                                                            | 
| 1499278292  | 2010-11    | 1                 | 2010-11            | CIP                                                                                                                            | 
| 1499278292  | 2011-12    | 1                 | 2011-12            | CIP                                                                                                                            | 
| 1499278292  | 2012-13    | 1                 | 2012-13            | CIP                                                                                                                            | 
```