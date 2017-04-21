# Messages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/messages) |
| Metadata | [Link](https://data.wa.gov/api/views/6bpk-s36s) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/6bpk-s36s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/6bpk-s36s/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 6bpk-s36s |
| Name | Messages |
| Tags | administration |
| Created | 2016-05-20T22:58:56Z |
| Publication Date | 2016-05-20T23:00:01Z |

## Description

Messages to be displayed on the data.wa.gov web page. This is one of several datasets used to configure the appearance of the site.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | title       | title      | text      | text        |
| Yes      | series tag  | text        | text       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6bpk-s36s d:2016-05-20T15:58:59.000Z t:text="Welcome to Data.WA.gov - the general purpose open data portal for the State of Washington." t:title="Opening Statement" m:row_number.6bpk-s36s=1
```

## Meta Commands

```ls
metric m:row_number.6bpk-s36s p:long l:"Row Number"

entity e:6bpk-s36s l:Messages t:url=https://data.wa.gov/api/views/6bpk-s36s

property e:6bpk-s36s t:meta.view v:id=6bpk-s36s v:averageRating=0 v:name=Messages

property e:6bpk-s36s t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:6bpk-s36s t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | title             | text                                                                                       | 
| =========== | ================= | ========================================================================================== | 
| 1463759939  | Opening Statement | Welcome to Data.WA.gov - the general purpose open data portal for the State of Washington. | 
```