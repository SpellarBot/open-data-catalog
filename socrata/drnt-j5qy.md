# Sep 2013 Austin Animal Center Outcome Count

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sep-2013-austin-animal-center-outcome-count) |
| Metadata | [Link](https://data.austintexas.gov/api/views/drnt-j5qy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/drnt-j5qy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/drnt-j5qy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | drnt-j5qy |
| Name | Sep 2013 Austin Animal Center Outcome Count |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | animals, animal services, september, 2013, austin animal center |
| Created | 2013-11-21T17:12:24Z |
| Publication Date | 2013-11-21T17:14:20Z |

## Description

Count of outcomes for cats and dogs from Austin Animal Center in September 2013.

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:drnt-j5qy d:2013-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=215

series e:drnt-j5qy d:2013-01-01T00:00:00.000Z t:outcome_type=Deceased t:animal_type=Cats m:animal_count=4

series e:drnt-j5qy d:2013-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=42
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:drnt-j5qy l:"Sep 2013 Austin Animal Center Outcome Count" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/drnt-j5qy

property e:drnt-j5qy t:meta.view v:id=drnt-j5qy v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Sep 2013 Austin Animal Center Outcome Count" v:attribution="Austin Animal Center"

property e:drnt-j5qy t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:drnt-j5qy t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 215          | 
| Cats        | Deceased            | 4            | 
| Cats        | Humanely Euthanized | 42           | 
| Cats        | Returned to Owner   | 33           | 
| Cats        | Transferred         | 344          | 
| Dogs        | Adopted             | 317          | 
| Dogs        | Deceased            | 3            | 
| Dogs        | Humanely Euthanized | 66           | 
| Dogs        | Returned to Owner   | 258          | 
| Dogs        | Transferred         | 257          | 
```