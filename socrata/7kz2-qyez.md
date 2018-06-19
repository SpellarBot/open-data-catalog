# March 2014 Austin Animal Center Live Outcome Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/march-2014-austin-animal-center-live-outcome-rates) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7kz2-qyez) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7kz2-qyez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7kz2-qyez/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7kz2-qyez |
| Name | March 2014 Austin Animal Center Live Outcome Rates |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, animal, austin animal center, open government, data, no kill |
| Created | 2014-04-01T17:48:01Z |
| Publication Date | 2014-04-01T17:50:54Z |

## Description

Cat and dog live outcome rates for March 2014

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | animal_type       | Animal Type       | text      | text        |
| Yes      | numeric metric | live_outcome_rate | Live Outcome Rate | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7kz2-qyez d:2014-01-01T00:00:00.000Z t:animal_type=Cats m:live_outcome_rate=91.7

series e:7kz2-qyez d:2014-01-01T00:00:00.000Z t:animal_type=Dogs m:live_outcome_rate=93

series e:7kz2-qyez d:2014-01-01T00:00:00.000Z t:animal_type=Total m:live_outcome_rate=92.7
```

## Meta Commands

```ls
metric m:live_outcome_rate p:double l:"Live Outcome Rate" t:dataTypeName=percent

entity e:7kz2-qyez l:"March 2014 Austin Animal Center Live Outcome Rates" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/7kz2-qyez

property e:7kz2-qyez t:meta.view v:id=7kz2-qyez v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="March 2014 Austin Animal Center Live Outcome Rates" v:attribution="Austin Animal Center"

property e:7kz2-qyez t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:7kz2-qyez t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | live_outcome_rate | 
| =========== | ================= | 
| Cats        | 91.7              | 
| Dogs        | 93                | 
| Total       | 92.7              | 
```