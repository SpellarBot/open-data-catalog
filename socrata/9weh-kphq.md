# Holacracy - People Participating

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/holacracy-people-participating) |
| Metadata | [Link](https://data.wa.gov/api/views/9weh-kphq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9weh-kphq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9weh-kphq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9weh-kphq |
| Name | Holacracy - People Participating |
| Created | 2016-08-08T20:38:28Z |
| Publication Date | 2016-08-08T22:11:46Z |

## Description

Unique people participating in the Holacracy experiment at WaTech.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | id         | text      | text        |
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
series e:9weh-kphq d:2016-08-08T13:38:31.000Z m:row_number.9weh-kphq=1

series e:9weh-kphq d:2016-08-08T13:38:31.000Z m:row_number.9weh-kphq=2

series e:9weh-kphq d:2016-08-08T13:38:31.000Z m:row_number.9weh-kphq=3
```

## Meta Commands

```ls
metric m:row_number.9weh-kphq p:long l:"Row Number"

entity e:9weh-kphq l:"Holacracy - People Participating" t:url=https://data.wa.gov/api/views/9weh-kphq

property e:9weh-kphq t:meta.view v:id=9weh-kphq v:averageRating=0 v:name="Holacracy - People Participating"

property e:9weh-kphq t:meta.view.owner v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:displayName=max.pham

property e:9weh-kphq t:meta.view.tableauthor v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:roleName=editor v:displayName=max.pham
```

## Top Records

```ls
| :updated_at | id    | 
| =========== | ===== | 
| 1470663511  | 33650 | 
| 1470663511  | 16826 | 
| 1470663511  | 26058 | 
| 1470663511  | 33704 | 
| 1470663511  | 33594 | 
| 1470663511  | 33652 | 
| 1470663511  | 33690 | 
| 1470663511  | 33596 | 
| 1470663511  | 33721 | 
| 1470663511  | 33617 | 
```