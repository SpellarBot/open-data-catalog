# Holacracy - Circles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/holacracy-circles) |
| Metadata | [Link](https://data.wa.gov/api/views/qjnp-3r9c) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qjnp-3r9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qjnp-3r9c/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qjnp-3r9c |
| Name | Holacracy - Circles |
| Category | Demographics |
| Tags | circles, holacracy, experiment |
| Created | 2016-08-08T21:41:10Z |
| Publication Date | 2016-08-08T22:05:48Z |

## Description

Circles created in the Holacracy Experiment

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | id         | text      | text        |
| Yes      | series tag  | name        | name       | text      | text        |
| Yes      | series tag  | short_name  | short_name | text      | text        |
| Yes      | series tag  | strategy    | strategy   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:qjnp-3r9c d:2016-08-08T14:41:13.000Z t:name=Development t:short_name=Development m:row_number.qjnp-3r9c=1

series e:qjnp-3r9c d:2016-08-08T14:41:13.000Z t:name="Integration Services" t:strategy="Production Outages are number 1 priority
Priorities are set by Portfolio Managers
Metrics are reported to show success of our circle" t:short_name="Integration Services" m:row_number.qjnp-3r9c=2

series e:qjnp-3r9c d:2016-08-08T14:41:13.000Z t:name="Business Analysis" t:short_name="Business Analysis" m:row_number.qjnp-3r9c=3
```

## Meta Commands

```ls
metric m:row_number.qjnp-3r9c p:long l:"Row Number"

entity e:qjnp-3r9c l:"Holacracy - Circles" t:url=https://data.wa.gov/api/views/qjnp-3r9c

property e:qjnp-3r9c t:meta.view v:id=qjnp-3r9c v:category=Demographics v:averageRating=0 v:name="Holacracy - Circles"

property e:qjnp-3r9c t:meta.view.license v:name="Public Domain"

property e:qjnp-3r9c t:meta.view.owner v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:displayName=max.pham

property e:qjnp-3r9c t:meta.view.tableauthor v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:roleName=editor v:displayName=max.pham
```

## Top Records

```ls
| :updated_at | id    | name                                 | short_name                           | strategy                                                                                                                                                                                   | 
| =========== | ===== | ==================================== | ==================================== | ========================================================================================================================================================================================== | 
| 1470667273  | 14342 | Development                          | Development                          |                                                                                                                                                                                            | 
| 1470667273  | 11423 | Integration Services                 | Integration Services                 | Production Outages are number 1 priority Priorities are set by Portfolio Managers Metrics are reported to show success of our circle                                                       | 
| 1470667273  | 12429 | Business Analysis                    | Business Analysis                    |                                                                                                                                                                                            | 
| 1470667273  | 7135  | Web and UX                           | Web and UX                           | Focus on: - hr.wa.gov website launch - Integrating usability and accessibility into our web design and development process - Increased usability lab use - Increased customer satisfaction | 
| 1470667273  | 10576 | Human Resources                      | Human Resources                      |                                                                                                                                                                                            | 
| 1470667273  | 3714  | WaTech                               | WaTech                               |                                                                                                                                                                                            | 
| 1470667273  | 12906 | Enterprise Reporting                 | Enterprise Reporting                 |                                                                                                                                                                                            | 
| 1470667273  | 4919  | e-gov                                | e-gov                                | Focus on:
? Create new revenue sources
? Employee Value Proposition for State IT                                                                                                           | 
| 1470667273  | 10689 | Security Gateway                     | Security Gateway                     |                                                                                                                                                                                            | 
| 1470667273  | 10688 | Network Engineering and Architecture | Network Engineering and Architecture |                                                                                                                                                                                            | 
```