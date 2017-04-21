# May 2014 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/may-2014-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dque-zfgd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dque-zfgd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dque-zfgd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dque-zfgd |
| Name | May 2014 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2014-06-02T21:08:11Z |
| Publication Date | 2014-06-02T21:09:40Z |

## Description

cat & dog outcomes of the month of May 2014

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
series e:dque-zfgd d:2014-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cats m:animal_count=148

series e:dque-zfgd d:2014-01-01T00:00:00.000Z t:outcome_type=Deceased t:animal_type=Cats m:animal_count=8

series e:dque-zfgd d:2014-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cats m:animal_count=34
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:dque-zfgd l:"May 2014 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/dque-zfgd

property e:dque-zfgd t:meta.view v:id=dque-zfgd v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="May 2014 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:dque-zfgd t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:dque-zfgd t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cats        | Adopted             | 148          | 
| Cats        | Deceased            | 8            | 
| Cats        | Humanely Euthanized | 34           | 
| Cats        | Returned to Owner   | 18           | 
| Cats        | Transferred         | 400          | 
| Dogs        | Adopted             | 355          | 
| Dogs        | Deceased            | 4            | 
| Dogs        | Humanely Euthanized | 54           | 
| Dogs        | Missing             | 1            | 
| Dogs        | Returned to Owner   | 231          | 
```