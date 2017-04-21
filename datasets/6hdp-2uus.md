# King County data categories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-data-categories-df387) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/6hdp-2uus) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/6hdp-2uus/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/6hdp-2uus/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 6hdp-2uus |
| Name | King County data categories |
| Attribution | King County |
| Category | Website content |
| Tags | data, category, classification |
| Created | 2013-10-14T21:43:31Z |
| Publication Date | 2013-10-14T21:46:06Z |

## Description

Categories used to classify datasets on data.kingcounty.gov

## Columns

```ls
| Included | Schema Type | Field Name     | Name            | Data Type | Render Type |
| ======== | =========== | ============== | =============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | category       | Category        | text      | text        |
| Yes      | series tag  | subcategory_of | Parent category | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6hdp-2uus d:2013-10-14T14:43:34.000Z t:category=Budget t:subcategory_of="Government administration" m:row_number.6hdp-2uus=1

series e:6hdp-2uus d:2013-10-14T14:43:34.000Z t:category=Business m:row_number.6hdp-2uus=2

series e:6hdp-2uus d:2013-10-14T14:43:34.000Z t:category=Census t:subcategory_of=Government m:row_number.6hdp-2uus=3
```

## Meta Commands

```ls
metric m:row_number.6hdp-2uus p:long l:"Row Number"

entity e:6hdp-2uus l:"King County data categories" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/6hdp-2uus

property e:6hdp-2uus t:meta.view v:id=6hdp-2uus v:category="Website content" v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="King County data categories" v:attribution="King County"

property e:6hdp-2uus t:meta.view.license v:name="Public Domain"

property e:6hdp-2uus t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:6hdp-2uus t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | category             | subcategory_of            | 
| =========== | ==================== | ========================= | 
| 1381761814  | Budget               | Government administration | 
| 1381761814  | Business             |                           | 
| 1381761814  | Census               | Government                | 
| 1381761814  | Economic Development |                           | 
| 1381761814  | Education            |                           | 
| 1381761814  | Election operations  | Elections                 | 
| 1381761814  | Election results     | Elections                 | 
| 1381761814  | Elections            |                           | 
| 1381761814  | Employees            | Government administration | 
| 1381761814  | Environment          |                           | 
```