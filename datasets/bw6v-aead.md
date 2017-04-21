# July 2014 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/july-2014-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bw6v-aead) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bw6v-aead/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bw6v-aead/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bw6v-aead |
| Name | July 2014 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2014-08-01T21:16:29Z |
| Publication Date | 2014-08-01T21:18:44Z |

## Description

all cat and dog outcomes for the month of July 2014

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
series e:bw6v-aead d:2014-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=459

series e:bw6v-aead d:2014-01-01T00:00:00.000Z t:outcome_type=Deceased t:animal_type=Cats m:animal_count=16

series e:bw6v-aead d:2014-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=45
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:bw6v-aead l:"July 2014 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/bw6v-aead

property e:bw6v-aead t:meta.view v:id=bw6v-aead v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="July 2014 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:bw6v-aead t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:bw6v-aead t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 459          | 
| Cats        | Deceased            | 16           | 
| Cats        | Humanely Euthanized | 45           | 
| Cats        | Missing             | 1            | 
| Cats        | Returned to Owner   | 17           | 
| Cats        | Transferred         | 491          | 
| Dogs        | Adopted             | 446          | 
| Dogs        | Deceased            | 1            | 
| Dogs        | Humanely Euthanized | 66           | 
| Dogs        | Returned to Owner   | 195          | 
```