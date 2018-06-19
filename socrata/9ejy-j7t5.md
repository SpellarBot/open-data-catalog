# February 2014 Austin Animal Center Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/february-2014-austin-animal-center-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/9ejy-j7t5) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/9ejy-j7t5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/9ejy-j7t5/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 9ejy-j7t5 |
| Name | February 2014 Austin Animal Center Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal center, data, open government |
| Created | 2014-03-04T16:18:32Z |
| Publication Date | 2014-03-04T16:21:44Z |

## Description

cat & dog intake summary for February 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | animal_type  | Animal Type  | text      | text        |
| Yes      | series tag     | intake_type  | Intake Type  | text      | text        |
| Yes      | numeric metric | animal_count | Animal Count | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9ejy-j7t5 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=79

series e:9ejy-j7t5 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=3

series e:9ejy-j7t5 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type=Stray m:animal_count=183
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:9ejy-j7t5 l:"February 2014 Austin Animal Center Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/9ejy-j7t5

property e:9ejy-j7t5 t:meta.view v:id=9ejy-j7t5 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="February 2014 Austin Animal Center Intakes" v:attribution="Austin Animal Center"

property e:9ejy-j7t5 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:9ejy-j7t5 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type                   | animal_count | 
| =========== | ============================= | ============ | 
| Cats        | Owner Surrender               | 79           | 
| Cats        | Public Assist                 | 3            | 
| Cats        | Stray                         | 183          | 
| Dogs        | Owner Surrender               | 172          | 
| Dogs        | Request for Humane Euthanasia | 6            | 
| Dogs        | Public Assist                 | 73           | 
| Dogs        | Stray                         | 527          | 
```