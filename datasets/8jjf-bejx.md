# September 2014 Austin Animal Center Intake Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/september-2014-austin-animal-center-intake-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8jjf-bejx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8jjf-bejx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8jjf-bejx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8jjf-bejx |
| Name | September 2014 Austin Animal Center Intake Data |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data |
| Created | 2014-10-01T20:26:41Z |
| Publication Date | 2014-10-01T20:48:07Z |

## Description

all cat and dog intakes for the month of September 2014

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
series e:8jjf-bejx d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=107

series e:8jjf-bejx d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=5

series e:8jjf-bejx d:2014-01-01T00:00:00.000Z t:animal_type=Cats t:intake_type="Request for Humane Euthanasia" m:animal_count=3
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:8jjf-bejx l:"September 2014 Austin Animal Center Intake Data" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/8jjf-bejx

property e:8jjf-bejx t:meta.view v:id=8jjf-bejx v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="September 2014 Austin Animal Center Intake Data" v:attribution="Austin Animal Center"

property e:8jjf-bejx t:meta.view.license v:name="Public Domain"

property e:8jjf-bejx t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:8jjf-bejx t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | intake_type                   | animal_count | 
| =========== | ============================= | ============ | 
| Cats        | Owner Surrender               | 107          | 
| Cats        | Public Assist                 | 5            | 
| Cats        | Request for Humane Euthanasia | 3            | 
| Cats        | Stray                         | 584          | 
| Dogs        | Owner Surrender               | 202          | 
| Dogs        | Public Assist                 | 36           | 
| Dogs        | Request for Humane Euthanasia | 6            | 
| Dogs        | Stray                         | 639          | 
```