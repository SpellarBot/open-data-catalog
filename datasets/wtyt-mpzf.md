# April 2014 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/april-2014-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wtyt-mpzf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wtyt-mpzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wtyt-mpzf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wtyt-mpzf |
| Name | April 2014 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, open government, data, no kill |
| Created | 2014-05-02T21:43:48Z |
| Publication Date | 2014-05-02T21:46:39Z |

## Description

cat & dog outcomes for the month of April 2014

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
series e:wtyt-mpzf d:2014-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=105

series e:wtyt-mpzf d:2014-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=33

series e:wtyt-mpzf d:2014-01-01T00:00:00.000Z t:outcome_type=Missing t:animal_type=Cats m:animal_count=1
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:wtyt-mpzf l:"April 2014 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/wtyt-mpzf

property e:wtyt-mpzf t:meta.view v:id=wtyt-mpzf v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="April 2014 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:wtyt-mpzf t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:wtyt-mpzf t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 105          | 
| Cats        | Humanely Euthanized | 33           | 
| Cats        | Missing             | 1            | 
| Cats        | Returned to Owner   | 27           | 
| Cats        | Transferred         | 281          | 
| Dogs        | Adopted             | 332          | 
| Dogs        | Humanely Euthanized | 34           | 
| Dogs        | Returned to Owner   | 225          | 
| Dogs        | Transferred         | 191          | 
| Cats        | Deceased            | 1            | 
```