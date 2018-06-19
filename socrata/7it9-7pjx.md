# December 2013 Live Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/december-2013-live-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7it9-7pjx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7it9-7pjx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7it9-7pjx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7it9-7pjx |
| Name | December 2013 Live Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal center, live outcome |
| Created | 2014-01-03T16:32:10Z |
| Publication Date | 2014-01-03T16:38:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | animal_type       | Animal Type       | text      | text        |
| Yes      | numeric metric | live_outcome_rate | Live Outcome Rate | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7it9-7pjx d:2013-01-01T00:00:00.000Z t:animal_type=Dogs m:live_outcome_rate=93

series e:7it9-7pjx d:2013-01-01T00:00:00.000Z t:animal_type=Total m:live_outcome_rate=94.3

series e:7it9-7pjx d:2013-01-01T00:00:00.000Z t:animal_type=Cats m:live_outcome_rate=96.2
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:7it9-7pjx l:"December 2013 Live Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/7it9-7pjx

property e:7it9-7pjx t:meta.view v:id=7it9-7pjx v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="December 2013 Live Outcomes" v:attribution="Austin Animal Center"

property e:7it9-7pjx t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:7it9-7pjx t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | live_outcome_rate | 
| =========== | ================= | 
| Dogs        | 93                | 
| Total       | 94.3              | 
| Cats        | 96.2              | 
```