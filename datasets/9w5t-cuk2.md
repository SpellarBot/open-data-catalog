# Austin Animal Center FY15 Q1 Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-fy15-q1-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/9w5t-cuk2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/9w5t-cuk2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/9w5t-cuk2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 9w5t-cuk2 |
| Name | Austin Animal Center FY15 Q1 Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2015-01-09T20:28:45Z |
| Publication Date | 2015-01-09T20:41:18Z |

## Description

cat and dog intakes for the months of October to December 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | animal_type  | Animal Type  | text      | text        |
| Yes      | series tag     | intake_type  | Intake Type  | text      | text        |
| Yes      | numeric metric | animal_count | Animal Count | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9w5t-cuk2 d:2015-01-09T12:29:12.000Z t:animal_type=Cats t:intake_type="Owner Surrender" m:animal_count=307

series e:9w5t-cuk2 d:2015-01-09T12:29:12.000Z t:animal_type=Cats t:intake_type="Public Assist" m:animal_count=23

series e:9w5t-cuk2 d:2015-01-09T12:29:12.000Z t:animal_type=Cats t:intake_type="Request for Humane Euthanasia" m:animal_count=6
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:9w5t-cuk2 l:"Austin Animal Center FY15 Q1 Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/9w5t-cuk2

property e:9w5t-cuk2 t:meta.view v:id=9w5t-cuk2 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Austin Animal Center FY15 Q1 Intakes" v:attribution="Austin Animal Center"

property e:9w5t-cuk2 t:meta.view.license v:name="Public Domain"

property e:9w5t-cuk2 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:9w5t-cuk2 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| :updated_at | animal_type | intake_type                   | animal_count | 
| =========== | =========== | ============================= | ============ | 
| 1420806552  | Cats        | Owner Surrender               | 307          | 
| 1420806552  | Cats        | Public Assist                 | 23           | 
| 1420806552  | Cats        | Request for Humane Euthanasia | 6            | 
| 1420806552  | Cats        | Stray                         | 1092         | 
| 1420806773  | Dogs        | Born in                       | 24           | 
| 1420806956  | Dogs        | Owner Surrender               | 493          | 
| 1420806960  | Dogs        | Public Assist                 | 196          | 
| 1420806962  | Dogs        | Request for Humane Euthanasia | 32           | 
| 1420807273  | Dogs        | Stray                         | 1848         | 
```