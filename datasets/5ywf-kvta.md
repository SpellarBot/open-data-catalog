# December 2013 Outcome Count

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/december-2013-outcome-count) |
| Metadata | [Link](https://data.austintexas.gov/api/views/5ywf-kvta) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/5ywf-kvta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/5ywf-kvta/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 5ywf-kvta |
| Name | December 2013 Outcome Count |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal center |
| Created | 2014-01-02T23:13:46Z |
| Publication Date | 2014-01-02T23:41:21Z |

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
series e:5ywf-kvta d:2013-01-01T00:00:00.000Z t:outcome_type=Adopted t:animal_type=Cat m:animal_count=278

series e:5ywf-kvta d:2013-01-01T00:00:00.000Z t:outcome_type=Died t:animal_type=Cat m:animal_count=1

series e:5ywf-kvta d:2013-01-01T00:00:00.000Z t:outcome_type="Humanely Euthanized" t:animal_type=Cat m:animal_count=21
```

## Meta Commands

```ls
metric m:animal_count p:integer l:"Animal Count" t:dataTypeName=number

entity e:5ywf-kvta l:"December 2013 Outcome Count" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/5ywf-kvta

property e:5ywf-kvta t:meta.view v:id=5ywf-kvta v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="December 2013 Outcome Count" v:attribution="Austin Animal Center"

property e:5ywf-kvta t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:5ywf-kvta t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | outcome_type        | animal_count | 
| =========== | =================== | ============ | 
| Cat         | Adopted             | 278          | 
| Cat         | Died                | 1            | 
| Cat         | Humanely Euthanized | 21           | 
| Cat         | Missing             | 1            | 
| Cat         | Returned to Owner   | 16           | 
| Cat         | Transferred         | 234          | 
| Dog         | Adopted             | 406          | 
| Dog         | Died                | 3            | 
| Dog         | Humanely Euthanized | 60           | 
| Dog         | Missing             | 1            | 
```