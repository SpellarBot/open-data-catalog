# June 2014 Austin Animal Center Live Outcome Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/june-2014-austin-animal-center-live-outcome-rates) |
| Metadata | [Link](https://data.austintexas.gov/api/views/tb3x-mddn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/tb3x-mddn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/tb3x-mddn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | tb3x-mddn |
| Name | June 2014 Austin Animal Center Live Outcome Rates |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, open government, data, live outcome |
| Created | 2014-07-02T16:43:34Z |
| Publication Date | 2014-07-02T16:45:40Z |

## Description

cat and dog live outcome rates for the month of June 2014

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | animal_type | Animal Type | text      | text        |
| Yes      | numeric metric | percentage  | Percentage  | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tb3x-mddn d:2014-01-01T00:00:00.000Z t:animal_type=Cats m:percentage=93.9

series e:tb3x-mddn d:2014-01-01T00:00:00.000Z t:animal_type=Dogs m:percentage=93.8

series e:tb3x-mddn d:2014-01-01T00:00:00.000Z t:animal_type=Total m:percentage=93.8
```

## Meta Commands

```ls
metric m:percentage p:float l:Percentage t:dataTypeName=percent

entity e:tb3x-mddn l:"June 2014 Austin Animal Center Live Outcome Rates" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/tb3x-mddn

property e:tb3x-mddn t:meta.view v:id=tb3x-mddn v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="June 2014 Austin Animal Center Live Outcome Rates" v:attribution="Austin Animal Center"

property e:tb3x-mddn t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:tb3x-mddn t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_type | percentage | 
| =========== | ========== | 
| Cats        | 93.9       | 
| Dogs        | 93.8       | 
| Total       | 93.8       | 
```