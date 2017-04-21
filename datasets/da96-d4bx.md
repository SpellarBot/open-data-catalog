# April 2014 Austin Animal Center Live Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/april-2014-austin-animal-center-live-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/da96-d4bx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/da96-d4bx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/da96-d4bx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | da96-d4bx |
| Name | April 2014 Austin Animal Center Live Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, open government, no kill, data |
| Created | 2014-05-02T21:54:14Z |
| Publication Date | 2014-05-02T21:57:05Z |

## Description

cat & dog live outcomes for the month of April 2014

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | cats              | Animal Type       | text      | text        |
| Yes      | numeric metric | live_outcome_rate | Live Outcome Rate | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:da96-d4bx d:2014-01-01T00:00:00.000Z t:cats=Dogs m:live_outcome_rate=95.7

series e:da96-d4bx d:2014-01-01T00:00:00.000Z t:cats=Total m:live_outcome_rate=94.5

series e:da96-d4bx d:2014-01-01T00:00:00.000Z t:cats=Cats m:live_outcome_rate=92.6
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:da96-d4bx l:"April 2014 Austin Animal Center Live Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/da96-d4bx

property e:da96-d4bx t:meta.view v:id=da96-d4bx v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="April 2014 Austin Animal Center Live Outcomes" v:attribution="Austin Animal Center"

property e:da96-d4bx t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:da96-d4bx t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| cats  | live_outcome_rate | 
| ===== | ================= | 
| Dogs  | 95.7              | 
| Total | 94.5              | 
| Cats  | 92.6              | 
```