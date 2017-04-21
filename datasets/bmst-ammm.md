# Rockford Open Tech Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rockford-open-tech-dataset-43533) |
| Metadata | [Link](https://data.illinois.gov/api/views/bmst-ammm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/bmst-ammm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/bmst-ammm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | bmst-ammm |
| Name | Rockford Open Tech Dataset |
| Category | Municipality |
| Created | 2013-11-16T17:47:18Z |
| Publication Date | 2013-11-16T17:49:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | col1        | Col1       | number    | number      |
| Yes      | series tag     | col2        | Col2       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bmst-ammm d:2013-11-16T09:48:58.000Z t:col2="Test String" m:col1=100
```

## Meta Commands

```ls
metric m:col1 p:integer l:Col1 t:dataTypeName=number

entity e:bmst-ammm l:"Rockford Open Tech Dataset" t:url=https://data.illinois.gov/api/views/bmst-ammm

property e:bmst-ammm t:meta.view v:id=bmst-ammm v:category=Municipality v:averageRating=0 v:name="Rockford Open Tech Dataset"

property e:bmst-ammm t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:bmst-ammm t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| :updated_at | col1 | col2        | 
| =========== | ==== | =========== | 
| 1384595338  | 100  | Test String | 
```