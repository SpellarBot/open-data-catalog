# Food Pantry List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-pantry-list) |
| Metadata | [Link](https://data.mo.gov/api/views/eb3y-vtsa) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/eb3y-vtsa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/eb3y-vtsa/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | eb3y-vtsa |
| Name | Food Pantry List |
| Category | Social Services |
| Created | 2015-05-27T19:37:07Z |
| Publication Date | 2016-10-26T16:40:37Z |
| Rows Updated | 2016-10-26T16:40:30Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                     | Data Type | Render Type |
| ======== | =========== | ======================= | ======================== | ========= | =========== |
| No       | time        | :updated_at             | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | agency_name             | Agency Name              | text      | text        |
| Yes      | series tag  | county                  | County                   | text      | text        |
| Yes      | series tag  | phone_number            | Phone Number             | text      | text        |
| Yes      | series tag  | hours_of_operation      | Hours of Operation       | text      | text        |
| Yes      | series tag  | additional_address_info | Additional Address Info. | text      | text        |
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
entity e:eb3y-vtsa l:"Food Pantry List" t:url=https://data.mo.gov/api/views/eb3y-vtsa

property e:eb3y-vtsa t:meta.view d:2017-03-10T14:36:04.424Z v:id=eb3y-vtsa v:category="Social Services" v:averageRating=0 v:name="Food Pantry List"

property e:eb3y-vtsa t:meta.view.owner d:2017-03-10T14:36:04.424Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna

property e:eb3y-vtsa t:meta.view.tableauthor d:2017-03-10T14:36:04.424Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna
```