# August 2014 Austin Animal Center Intakes Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/august-2014-austin-animal-center-intakes-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qyb8-tmu7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qyb8-tmu7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qyb8-tmu7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qyb8-tmu7 |
| Name | August 2014 Austin Animal Center Intakes Data |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, open government, data |
| Created | 2014-09-02T19:36:21Z |
| Publication Date | 2014-09-02T19:38:30Z |

## Description

all cat and dog intakes for the month of August 2014

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
series e:qyb8-tmu7 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=136

series e:qyb8-tmu7 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=7

series e:qyb8-tmu7 d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Request for Humane Euthanasia" m:animal_count=1
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:qyb8-tmu7 l:"August 2014 Austin Animal Center Intakes Data" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/qyb8-tmu7

property e:qyb8-tmu7 t:meta.view v:id=qyb8-tmu7 v:category=Government v:attributionLink=http://austinnimalcenter.org v:averageRating=0 v:name="August 2014 Austin Animal Center Intakes Data" v:attribution="Austin Animal Center"

property e:qyb8-tmu7 t:meta.view.license v:name="Public Domain"

property e:qyb8-tmu7 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:qyb8-tmu7 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type                   | animal_count | 
| =========== | ============================= | ============ | 
| Cats        | Owner Surrender               | 136          | 
| Cats        | Public Assist                 | 7            | 
| Cats        | Request for Humane Euthanasia | 1            | 
| Cats        | Stray                         | 533          | 
| Dogs        | Owner Surrender               | 167          | 
| Dogs        | Public Assist                 | 37           | 
| Dogs        | Request for Humane Euthanasia | 7            | 
| Dogs        | Stray                         | 598          | 
```