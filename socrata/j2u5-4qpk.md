# WA State Accessibility Coordinators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-state-accessibility-coordinators) |
| Metadata | [Link](https://data.wa.gov/api/views/j2u5-4qpk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/j2u5-4qpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/j2u5-4qpk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | j2u5-4qpk |
| Name | WA State Accessibility Coordinators |
| Attribution | WA State Accessibility Champion |
| Tags | policy 188, accessibility, ada, section 508 |
| Created | 2016-11-22T21:43:29Z |
| Publication Date | 2017-01-20T19:55:21Z |

## Description

WA State Office of the Chief Information Officer Accessibility Policy #188 requires agencies and other groups required to follow OCIO Policy to identify an Accessibility Coordinator. Having a central list will help the public contact coordinators to resolve issues and assist Agencies with resources. http://ocio.wa.gov/policy/accessibility

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | =========== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag  | agency_number                    | AGENCY NUMBER                    | text          | number        |
| Yes      | series tag  | agency_title                     | AGENCY TITLE                     | text          | text          |
| Yes      | series tag  | abbreviation                     | Abbreviation                     | text          | text          |
| Yes      | series tag  | agency_accessibility_coordinator | Agency Accessibility Coordinator | text          | text          |
| Yes      | series tag  | agency_coordinator_email         | Agency Coordinator Email         | email         | email         |
| Yes      | time        | last_change_date                 | Last change date                 | calendar_date | calendar_date |
| Yes      | series tag  | url_of_accessibility_info        | URL of Accessibility Info        | url           | url           |
```

## Time Field

```ls
Value = last_change_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:j2u5-4qpk d:2016-11-22T21:43:42.000Z t:agency_number=10 t:agency_title="State Revenue for Distribution (SRD)" t:abbreviation=SRD m:row_number.j2u5-4qpk=1

series e:j2u5-4qpk d:2016-11-22T21:43:42.000Z t:agency_number=50 t:agency_title="Federal Revenue for Distribution (FRD)" t:abbreviation=FRD m:row_number.j2u5-4qpk=2

series e:j2u5-4qpk d:2016-11-22T21:43:42.000Z t:agency_number=100 t:agency_title="Bond Retirement and Interest (BRI)" t:abbreviation=BRI m:row_number.j2u5-4qpk=3
```

## Meta Commands

```ls
metric m:row_number.j2u5-4qpk p:long l:"Row Number"

entity e:j2u5-4qpk l:"WA State Accessibility Coordinators" t:attribution="WA State Accessibility Champion" t:url=https://data.wa.gov/api/views/j2u5-4qpk

property e:j2u5-4qpk t:meta.view d:2017-09-25T07:28:00.830Z v:averageRating=0 v:name="WA State Accessibility Coordinators" v:attribution="WA State Accessibility Champion" v:attributionLink=http://ocio.wa.gov/policy/accessibility v:id=j2u5-4qpk

property e:j2u5-4qpk t:meta.view.license d:2017-09-25T07:28:00.830Z v:name="Public Domain"

property e:j2u5-4qpk t:meta.view.owner d:2017-09-25T07:28:00.830Z v:displayName=ryan.leisinger v:lastNotificationSeenAt=1500917366 v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:id=2iur-ynm8 v:screenName=ryan.leisinger v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB

property e:j2u5-4qpk t:meta.view.tableauthor d:2017-09-25T07:28:00.830Z v:displayName=ryan.leisinger v:lastNotificationSeenAt=1500917366 v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:id=2iur-ynm8 v:screenName=ryan.leisinger v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB
```

## Top Records

```ls
| agency_number | agency_title                                                       | abbreviation | agency_accessibility_coordinator | agency_coordinator_email | last_change_date | url_of_accessibility_info | 
| ============= | ================================================================== | ============ | ================================ | ======================== | ================ | ========================= | 
| 10            | State Revenue for Distribution (SRD)                               | SRD          |                                  |                          |                  | [null, null]              | 
| 50            | Federal Revenue for Distribution (FRD)                             | FRD          |                                  |                          |                  | [null, null]              | 
| 100           | Bond Retirement and Interest (BRI)                                 | BRI          |                                  |                          |                  | [null, null]              | 
| 110           | House of Representatives (REP)                                     | REP          |                                  |                          |                  | [null, null]              | 
| 120           | Senate (SEN)                                                       | SEN          |                                  |                          |                  | [null, null]              | 
| 130           | Joint Transportation Committee (JTC)                               | JTC          |                                  |                          |                  | [null, null]              | 
| 140           | Joint Legislative Audit and Review Committee (JLARC)               | ARC          |                                  |                          |                  | [null, null]              | 
| 200           | Legislative Evaluation and Accountability Program Committee (LEAP) | EAP          |                                  |                          |                  | [null, null]              | 
| 350           | Office of the State Actuary (OSA)                                  | OSA          |                                  |                          |                  | [null, null]              | 
| 370           | Office of Legislative Support Services (LSS)                       | LSS          |                                  |                          |                  | [null, null]              | 
```