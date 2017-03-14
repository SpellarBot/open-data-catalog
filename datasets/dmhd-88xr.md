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
| Publication Date | 2016-07-01T23:37:12Z |
| Rows Updated | 2016-07-01T23:36:51Z |

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
series e:dmhd-88xr d:2015-11-05T14:36:04.000Z t:phase_step_description="User departments and DGS identity the needs/scope/goals of project. Usually in-house. POR (Program of Requirements) produced at this stage" t:phase_step_number=1 t:phase_type=default t:phase_step_name=Planning m:row_number=1

series e:dmhd-88xr d:2015-11-05T14:36:04.000Z t:phase_step_description="Architects and engineers work from the defined scope and budget to develop the design, and  produce construction drawings, etc." t:phase_step_number=2 t:phase_type=default t:phase_step_name="Preliminary Design" m:row_number=2

series e:dmhd-88xr d:2015-11-05T14:36:04.000Z t:phase_step_description="Design complete. Construction documents complete. Ready to award contract." t:phase_step_number=3 t:phase_type=default t:phase_step_name="Final Design" m:row_number=3
```

## Meta Commands

```ls
metric m:row_number p:long l:"Row Number"

entity e:dmhd-88xr l:"Template011: Project Phase List" t:url=https://data.srcity.org/api/views/dmhd-88xr

property e:dmhd-88xr t:meta.view v:id=dmhd-88xr v:averageRating=0 v:name="Template011: Project Phase List"

property e:dmhd-88xr t:meta.view.owner v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:roleName=administrator v:displayName="Tickner, Brian"

property e:dmhd-88xr t:meta.view.tableauthor v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:roleName=administrator v:displayName="Tickner, Brian"
```