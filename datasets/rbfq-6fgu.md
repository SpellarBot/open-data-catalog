# September 2014 Austin Animal Center Live Outcome Rate Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/september-2014-austin-animal-center-live-outcome-rate-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/rbfq-6fgu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/rbfq-6fgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/rbfq-6fgu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | rbfq-6fgu |
| Name | September 2014 Austin Animal Center Live Outcome Rate Data |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2014-10-01T21:50:43Z |
| Publication Date | 2014-10-01T21:52:57Z |

## Description

cat and dog live outcome rates for the month of September 2014

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
series e:rbfq-6fgu d:2014-01-01T00:00:00.000Z t:animal_type=Cats m:live_outcome_rate=94.4

series e:rbfq-6fgu d:2014-01-01T00:00:00.000Z t:animal_type=Dogs m:live_outcome_rate=94.6

series e:rbfq-6fgu d:2014-01-01T00:00:00.000Z t:animal_type=Total m:live_outcome_rate=94.5
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:rbfq-6fgu l:"September 2014 Austin Animal Center Live Outcome Rate Data" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/rbfq-6fgu

property e:rbfq-6fgu t:meta.view v:id=rbfq-6fgu v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="September 2014 Austin Animal Center Live Outcome Rate Data" v:attribution="Austin Animal Center"

property e:rbfq-6fgu t:meta.view.license v:name="Public Domain"

property e:rbfq-6fgu t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:rbfq-6fgu t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | live_outcome_rate | 
| =========== | ================= | 
| Cats        | 94.4              | 
| Dogs        | 94.6              | 
| Total       | 94.5              | 
```