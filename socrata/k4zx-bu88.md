# January 2014 Austin Animal Center Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/january-2014-austin-animal-center-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/k4zx-bu88) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/k4zx-bu88/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/k4zx-bu88/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | k4zx-bu88 |
| Name | January 2014 Austin Animal Center Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal, data, open government |
| Created | 2014-02-03T18:41:15Z |
| Publication Date | 2014-02-03T18:45:12Z |

## Description

A count of all cat and dogs intakes for the month of January 2014.

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
series e:k4zx-bu88 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=102

series e:k4zx-bu88 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=13

series e:k4zx-bu88 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Request for Humane Euthanasia" m:animal_count=3
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:k4zx-bu88 l:"January 2014 Austin Animal Center Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/k4zx-bu88

property e:k4zx-bu88 t:meta.view v:id=k4zx-bu88 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="January 2014 Austin Animal Center Intakes" v:attribution="Austin Animal Center"

property e:k4zx-bu88 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:k4zx-bu88 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type                   | animal_count | 
| =========== | ============================= | ============ | 
| Cats        | Owner Surrender               | 102          | 
| Cats        | Public Assist                 | 13           | 
| Cats        | Request for Humane Euthanasia | 3            | 
| Cats        | Stray                         | 222          | 
| Dogs        | Owner Surrender               | 177          | 
| Dogs        | Public Assist                 | 32           | 
| Dogs        | Request for Humane Euthanasia | 6            | 
| Dogs        | Stray                         | 632          | 
```