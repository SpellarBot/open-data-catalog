# November Austin Animal Center Live Outcome Rate

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/november-austin-animal-center-live-outcome-rate) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8ruh-ty5d) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8ruh-ty5d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8ruh-ty5d/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8ruh-ty5d |
| Name | November Austin Animal Center Live Outcome Rate |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, live outcome, austin animal center |
| Created | 2013-12-02T23:25:41Z |
| Publication Date | 2013-12-02T23:27:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | animal_type       | Animal Type       | text      | text        |
| Yes      | numeric metric | live_outcome_rate | Live Outcome Rate | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8ruh-ty5d d:2013-12-02T15:26:56.000Z t:animal_type=Total m:live_outcome_rate=93.8

series e:8ruh-ty5d d:2013-12-02T15:27:20.000Z t:animal_type=Cats m:live_outcome_rate=94.3

series e:8ruh-ty5d d:2013-12-02T15:27:24.000Z t:animal_type=Dogs m:live_outcome_rate=93.5
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:8ruh-ty5d l:"November Austin Animal Center Live Outcome Rate" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/8ruh-ty5d

property e:8ruh-ty5d t:meta.view v:id=8ruh-ty5d v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="November Austin Animal Center Live Outcome Rate" v:attribution="Austin Animal Center"

property e:8ruh-ty5d t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:8ruh-ty5d t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| :updated_at | animal_type | live_outcome_rate | 
| =========== | =========== | ================= | 
| 1385998016  | Total       | 93.8              | 
| 1385998040  | Cats        | 94.3              | 
| 1385998044  | Dogs        | 93.5              | 
```