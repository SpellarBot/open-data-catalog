# January 2014 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/january-2014-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/up99-pfez) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/up99-pfez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/up99-pfez/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | up99-pfez |
| Name | January 2014 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, animal center, data, open government |
| Created | 2014-02-03T20:11:19Z |
| Publication Date | 2014-02-03T20:13:19Z |

## Description

A count of all cat and dogs outcomes for the month of January 2014.

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
series e:up99-pfez d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type=Adopted m:animal_count=159

series e:up99-pfez d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type=Died m:animal_count=1

series e:up99-pfez d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Humanely Euthanized" m:animal_count=34
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:up99-pfez l:"January 2014 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/up99-pfez

property e:up99-pfez t:meta.view v:id=up99-pfez v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="January 2014 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:up99-pfez t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:up99-pfez t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type         | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 159          | 
| Cats        | Died                | 1            | 
| Cats        | Humanely Euthanized | 34           | 
| Cats        | Returned to Owner   | 37           | 
| Cats        | Transferred         | 136          | 
| Dogs        | Adopted             | 359          | 
| Dogs        | Died                | 3            | 
| Dogs        | Humanely Euthanized | 46           | 
| Dogs        | Missing             | 1            | 
| Dogs        | Returned to Owner   | 218          | 
```