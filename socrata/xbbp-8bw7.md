# November Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/november-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xbbp-8bw7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xbbp-8bw7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xbbp-8bw7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xbbp-8bw7 |
| Name | November Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, outcome, austin animal center |
| Created | 2013-12-02T23:15:15Z |
| Publication Date | 2013-12-02T23:16:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | animal_type  | Animal Type  | text      | text        |
| Yes      | series tag     | outcome_type | Outcome Type | text      | text        |
| Yes      | numeric metric | animal_count | Animal Count | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xbbp-8bw7 d:2013-12-02T15:15:18.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=226

series e:xbbp-8bw7 d:2013-12-02T15:15:18.000Z t:outcome_type=Died t:animal_type=Cats m:animal_count=4

series e:xbbp-8bw7 d:2013-12-02T15:15:18.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=25
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:xbbp-8bw7 l:"November Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/xbbp-8bw7

property e:xbbp-8bw7 t:meta.view v:id=xbbp-8bw7 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="November Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:xbbp-8bw7 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:xbbp-8bw7 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| :updated_at | animal_type | outcome_type        | animal_count | 
| =========== | =========== | =================== | ============ | 
| 1385997318  | Cats        | Adopted             | 226          | 
| 1385997318  | Cats        | Died                | 4            | 
| 1385997318  | Cats        | Humanely Euthanized | 25           | 
| 1385997318  | Cats        | Returned to Owner   | 27           | 
| 1385997318  | Cats        | Transferred         | 164          | 
| 1385997318  | Dogs        | Adopted             | 323          | 
| 1385997318  | Dogs        | Humanely Euthanized | 51           | 
| 1385997318  | Dogs        | Returned to Owner   | 187          | 
| 1385997318  | Dogs        | Transferred         | 223          | 
```