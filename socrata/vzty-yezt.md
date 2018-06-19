# Sep 2013 Austin Animal Center Live Outcome Rate

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sep-2013-austin-animal-center-live-outcome-rate) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vzty-yezt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vzty-yezt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vzty-yezt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vzty-yezt |
| Name | Sep 2013 Austin Animal Center Live Outcome Rate |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | animals, animal services, september, 2013, austin animal center |
| Created | 2013-11-21T17:20:50Z |
| Publication Date | 2013-11-21T17:21:37Z |

## Description

Percentages of live outcomes for cats and dogs from Austin Animal Center in September 2013.

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
series e:vzty-yezt d:2013-01-01T00:00:00.000Z t:animal_type=Cats m:live_outcome_rate=93.4

series e:vzty-yezt d:2013-01-01T00:00:00.000Z t:animal_type=Dogs m:live_outcome_rate=92.7

series e:vzty-yezt d:2013-01-01T00:00:00.000Z t:animal_type=Total m:live_outcome_rate=93
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:vzty-yezt l:"Sep 2013 Austin Animal Center Live Outcome Rate" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/vzty-yezt

property e:vzty-yezt t:meta.view v:id=vzty-yezt v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Sep 2013 Austin Animal Center Live Outcome Rate" v:attribution="Austin Animal Center"

property e:vzty-yezt t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:vzty-yezt t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | live_outcome_rate | 
| =========== | ================= | 
| Cats        | 93.4              | 
| Dogs        | 92.7              | 
| Total       | 93                | 
```