# Messages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/messages-dbe66) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gb78-jhh6) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gb78-jhh6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gb78-jhh6/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gb78-jhh6 |
| Name | Messages |
| Created | 2013-11-20T04:40:56Z |
| Publication Date | 2013-11-20T20:01:50Z |

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
series e:gb78-jhh6 d:2013-11-19T20:40:58.000Z t:text="Build something with public data." t:title="Developer Message" m:row_number.gb78-jhh6=1

series e:gb78-jhh6 d:2013-11-20T11:55:42.000Z t:text="Using Open Data for Campaign Spending. Track and analyze contributions and expenses of candidates running for state or county office." t:title="Explorer Message" m:row_number.gb78-jhh6=2
```

## Meta Commands

```ls
metric m:row_number.gb78-jhh6 p:long l:"Row Number"

entity e:gb78-jhh6 l:Messages t:url=https://data.hawaii.gov/api/views/gb78-jhh6

property e:gb78-jhh6 t:meta.view v:id=gb78-jhh6 v:averageRating=0 v:name=Messages

property e:gb78-jhh6 t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:gb78-jhh6 t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | title             | text                                                                                                                                  | 
| =========== | ================= | ===================================================================================================================================== | 
| 1384893658  | Developer Message | Build something with public data.                                                                                                     | 
| 1384948542  | Explorer Message  | Using Open Data for Campaign Spending. Track and analyze contributions and expenses of candidates running for state or county office. | 
```