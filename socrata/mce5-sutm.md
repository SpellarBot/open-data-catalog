# Registered Saw Users

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/registered-saw-users-c7d55) |
| Metadata | [Link](https://data.wa.gov/api/views/mce5-sutm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mce5-sutm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mce5-sutm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mce5-sutm |
| Name | Registered Saw Users |
| Category | Natural Resources & Environment |
| Created | 2013-07-11T20:53:43Z |
| Publication Date | 2013-07-11T20:54:31Z |

## Description

Dept of Ecology Proof of Concept dataset for testing and filtering only. It will not have public ramifications.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | quarter     | Quarter    | text      | text        |
| Yes      | numeric metric | user_count  | User Count | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mce5-sutm d:2013-07-11T13:53:44.000Z t:quarter=Q1_2012 m:user_count=313479

series e:mce5-sutm d:2013-07-11T13:53:44.000Z t:quarter=Q2_2012 m:user_count=396492

series e:mce5-sutm d:2013-07-11T13:53:44.000Z t:quarter=Q3_2012 m:user_count=432051
```

## Meta Commands

```ls
metric m:user_count p:integer l:"User Count" t:dataTypeName=number

entity e:mce5-sutm l:"Registered Saw Users" t:url=https://data.wa.gov/api/views/mce5-sutm

property e:mce5-sutm t:meta.view v:id=mce5-sutm v:category="Natural Resources & Environment" v:averageRating=0 v:name="Registered Saw Users"

property e:mce5-sutm t:meta.view.owner v:id=ian4-3czc v:profileImageUrlMedium=/api/users/ian4-3czc/profile_images/THUMB v:profileImageUrlLarge=/api/users/ian4-3czc/profile_images/LARGE v:screenName="Miles Neale" v:profileImageUrlSmall=/api/users/ian4-3czc/profile_images/TINY v:displayName="Miles Neale"

property e:mce5-sutm t:meta.view.tableauthor v:id=ian4-3czc v:profileImageUrlMedium=/api/users/ian4-3czc/profile_images/THUMB v:profileImageUrlLarge=/api/users/ian4-3czc/profile_images/LARGE v:screenName="Miles Neale" v:profileImageUrlSmall=/api/users/ian4-3czc/profile_images/TINY v:roleName=administrator v:displayName="Miles Neale"
```

## Top Records

```ls
| :updated_at | quarter | user_count | 
| =========== | ======= | ========== | 
| 1373550824  | Q1_2012 | 313479     | 
| 1373550824  | Q2_2012 | 396492     | 
| 1373550824  | Q3_2012 | 432051     | 
| 1373550824  | Q4_2012 | 550747     | 
| 1373550824  | Q1_2013 | 700755     | 
| 1373550824  | Q2_2013 | 873962     | 
```