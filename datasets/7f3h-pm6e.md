# Jackson Capital Budget Project Phases List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-capital-budget-project-phases-list) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/7f3h-pm6e) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/7f3h-pm6e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/7f3h-pm6e/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 7f3h-pm6e |
| Name | Jackson Capital Budget Project Phases List |
| Category | Public Works |
| Created | 2016-12-22T17:10:32Z |
| Publication Date | 2016-12-22T17:21:53Z |
| Rows Updated | 2016-12-22T17:21:44Z |

## Description

Budget data that describes the Projects and Phases of the Infrastructure Master Plan.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | phase_step_name        | Phase Step Name        | text      | text        |
| Yes      | series tag  | phase_step_number      | Phase Step Number      | text      | number      |
| Yes      | series tag  | phase_step_description | Phase Step Description | text      | text        |
| Yes      | series tag  | phase_type             | Phase Type             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:7f3h-pm6e l:"Jackson Capital Budget Project Phases List" t:url=https://data.jacksonms.gov/api/views/7f3h-pm6e

property e:7f3h-pm6e t:meta.view v:id=7f3h-pm6e v:category="Public Works" v:averageRating=0 v:name="Jackson Capital Budget Project Phases List"

property e:7f3h-pm6e t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:displayName="Justin Bruce"

property e:7f3h-pm6e t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:displayName="Justin Bruce"
```