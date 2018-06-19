# March 2014 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/march-2014-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/krsq-4num) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/krsq-4num/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/krsq-4num/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | krsq-4num |
| Name | March 2014 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, animal, austin animal center, open government, data, no kill |
| Created | 2014-04-01T17:43:58Z |
| Publication Date | 2014-04-01T17:45:48Z |

## Description

All cat and dogs outcomes for March 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | animal_type  | Animal Type  | text      | text        |
| Yes      | series tag     | outcome_type | Outcome Type | text      | text        |
| Yes      | numeric metric | animal_count | Animal Count | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:krsq-4num d:2014-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=86

series e:krsq-4num d:2014-01-01T00:00:00.000Z t:outcome_type=Died t:animal_type=Cats m:animal_count=6

series e:krsq-4num d:2014-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=27
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:krsq-4num l:"March 2014 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/krsq-4num

property e:krsq-4num t:meta.view v:id=krsq-4num v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="March 2014 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:krsq-4num t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:krsq-4num t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 86           | 
| Cats        | Died                | 6            | 
| Cats        | Humanely Euthanized | 27           | 
| Cats        | Returned to Owner   | 25           | 
| Cats        | Transferred         | 187          | 
| Dogs        | Adopted             | 389          | 
| Dogs        | Died                | 2            | 
| Dogs        | Humanely Euthanized | 61           | 
| Dogs        | Returned to Owner   | 223          | 
| Dogs        | Transferred         | 204          | 
```