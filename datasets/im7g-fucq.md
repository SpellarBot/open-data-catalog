# Missouri Zip Codes by County/City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-zip-codes-by-county-city-a85bf) |
| Metadata | [Link](https://data.mo.gov/api/views/im7g-fucq) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/im7g-fucq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/im7g-fucq/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | im7g-fucq |
| Name | Missouri Zip Codes by County/City |
| Category | Geography |
| Created | 2012-02-15T18:41:53Z |
| Publication Date | 2013-06-27T15:17:49Z |
| Rows Updated | 2013-06-27T15:17:40Z |

## Description

List of cities, zip codes and counties in Missouri

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | county      | county     | text      | text        |
| Yes      | series tag  | zip_code    | zip code   | text      | text        |
| Yes      | series tag  | city        | city       | text      | text        |
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
entity e:im7g-fucq l:"Missouri Zip Codes by County/City" t:url=https://data.mo.gov/api/views/im7g-fucq

property e:im7g-fucq t:meta.view d:2017-03-10T16:03:29.787Z v:id=im7g-fucq v:category=Geography v:averageRating=0 v:name="Missouri Zip Codes by County/City"

property e:im7g-fucq t:meta.view.owner d:2017-03-10T16:03:29.787Z v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"

property e:im7g-fucq t:meta.view.tableauthor d:2017-03-10T16:03:29.787Z v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"
```