# Sep 2013 Austin Animal Center Intake Count

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sep-2013-austin-animal-center-intake-count) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ba4t-mrbm) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ba4t-mrbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ba4t-mrbm/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ba4t-mrbm |
| Name | Sep 2013 Austin Animal Center Intake Count |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | animals, animal services, september, 2013, austin animal center |
| Created | 2013-11-21T17:08:16Z |
| Publication Date | 2013-11-21T17:10:59Z |

## Description

Count of intakes for cats and dogs from Austin Animal Center in September 2013.

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ba4t-mrbm d:2013-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=124

series e:ba4t-mrbm d:2013-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=14

series e:ba4t-mrbm d:2013-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type=Stray m:animal_count=486
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:ba4t-mrbm l:"Sep 2013 Austin Animal Center Intake Count" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/ba4t-mrbm

property e:ba4t-mrbm t:meta.view v:id=ba4t-mrbm v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Sep 2013 Austin Animal Center Intake Count" v:attribution="Austin Animal Center"

property e:ba4t-mrbm t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:ba4t-mrbm t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type                   | animal_count | 
| =========== | ============================= | ============ | 
| Cats        | Owner Surrender               | 124          | 
| Cats        | Public Assist                 | 14           | 
| Cats        | Stray                         | 486          | 
| Dogs        | Owner Surrender               | 189          | 
| Dogs        | Public Assist                 | 89           | 
| Dogs        | Request for Humane Euthanasia | 6            | 
| Dogs        | Stray                         | 649          | 
```