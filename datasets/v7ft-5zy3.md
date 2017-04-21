# January 2014 Austin Animal Center Live Outcome Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/january-2014-austin-animal-center-live-outcome-rates) |
| Metadata | [Link](https://data.austintexas.gov/api/views/v7ft-5zy3) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/v7ft-5zy3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/v7ft-5zy3/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | v7ft-5zy3 |
| Name | January 2014 Austin Animal Center Live Outcome Rates |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal, open government, data |
| Created | 2014-02-03T20:53:45Z |
| Publication Date | 2014-02-03T21:04:32Z |

## Description

Live outcome rates for all cats and dogs in January 2014.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | type              | Type              | text      | text        |
| Yes      | numeric metric | live_outcome_rate | Live Outcome Rate | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v7ft-5zy3 d:2014-01-01T00:00:00.000Z t:type=Total m:live_outcome_rate=93.3

series e:v7ft-5zy3 d:2014-01-01T00:00:00.000Z t:type=Cats m:live_outcome_rate=90.7

series e:v7ft-5zy3 d:2014-01-01T00:00:00.000Z t:type=Dogs m:live_outcome_rate=94.4
```

## Meta Commands

```ls
metric m:live_outcome_rate p:float l:"Live Outcome Rate" t:dataTypeName=percent

entity e:v7ft-5zy3 l:"January 2014 Austin Animal Center Live Outcome Rates" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/v7ft-5zy3

property e:v7ft-5zy3 t:meta.view v:id=v7ft-5zy3 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="January 2014 Austin Animal Center Live Outcome Rates" v:attribution="Austin Animal Center"

property e:v7ft-5zy3 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:v7ft-5zy3 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| type  | live_outcome_rate | 
| ===== | ================= | 
| Total | 93.3              | 
| Cats  | 90.7              | 
| Dogs  | 94.4              | 
```