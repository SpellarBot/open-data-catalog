# 2012 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/yrpa-wmth) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/yrpa-wmth/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/yrpa-wmth/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | yrpa-wmth |
| Name | 2012 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Tags | animals, animal services, 2012, outcome, austin animal center |
| Created | 2013-11-21T20:03:55Z |
| Publication Date | 2013-11-21T20:07:46Z |

## Description

Animal and outcome descriptions for Austin Animal Center cats and dogs in 2012.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | animal_id        | Animal ID        | text      | text        |
| No       |             | outcome_date     | Outcome Date     | text      | text        |
| Yes      | series tag  | outcome_type     | Outcome Type     | text      | text        |
| Yes      | series tag  | animal_type      | Animal Type      | text      | text        |
| Yes      | series tag  | sex_upon_outcome | Sex upon Outcome | text      | text        |
| Yes      | series tag  | age_upon_outcome | Age upon Outcome | text      | text        |
| Yes      | series tag  | primary_breed    | Primary Breed    | text      | text        |
| Yes      | series tag  | primary_color    | Primary Color    | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = outcome_date
```

## Data Commands

```ls
series e:yrpa-wmth d:2012-01-01T00:00:00.000Z t:primary_color=Buff t:age_upon_outcome="11 years" t:sex_upon_outcome="Neutered Male" t:outcome_type="Return to Owner" t:primary_breed="Golden Retriever" t:animal_type=Dog t:animal_id=A247649 m:row_number.yrpa-wmth=1

series e:yrpa-wmth d:2012-01-01T00:00:00.000Z t:primary_color=Yellow t:age_upon_outcome="7 years" t:sex_upon_outcome="Spayed Female" t:outcome_type=Transfer t:primary_breed="Labrador Retriever" t:animal_type=Dog t:animal_id=A522847 m:row_number.yrpa-wmth=2

series e:yrpa-wmth d:2012-01-01T00:00:00.000Z t:primary_color=Blue t:age_upon_outcome="7 months" t:sex_upon_outcome="Neutered Male" t:outcome_type=Transfer t:primary_breed="Pit Bull" t:animal_type=Dog t:animal_id=A607885 m:row_number.yrpa-wmth=3
```

## Meta Commands

```ls
metric m:row_number.yrpa-wmth p:long l:"Row Number"

entity e:yrpa-wmth l:"2012 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/yrpa-wmth

property e:yrpa-wmth t:meta.view v:id=yrpa-wmth v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="2012 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:yrpa-wmth t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:yrpa-wmth t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | outcome_date | outcome_type    | animal_type | sex_upon_outcome | age_upon_outcome | primary_breed      | primary_color | 
| ========= | ============ | =============== | =========== | ================ | ================ | ================== | ============= | 
| A247649   | 1/1          | Return to Owner | Dog         | Neutered Male    | 11 years         | Golden Retriever   | Buff          | 
| A522847   | 1/1          | Transfer        | Dog         | Spayed Female    | 7 years          | Labrador Retriever | Yellow        | 
| A607885   | 1/1          | Transfer        | Dog         | Neutered Male    | 7 months         | Pit Bull           | Blue          | 
| A609226   | 1/1          | Return to Owner | Dog         | Neutered Male    | 2 years          | Pit Bull           | Tan           | 
| A614441   | 1/1          | Transfer        | Dog         | Intact Female    | 11 months        | Labrador Retriever | Brown         | 
| A614768   | 1/1          | Euthanasia      | Dog         | Spayed Female    | 2 years          | Pit Bull           | White         | 
| A614969   | 1/1          | Transfer        | Dog         | Neutered Male    | 5 years          | English Pointer    | Chocolate     | 
| A615155   | 1/1          | Transfer        | Dog         | Intact Female    | 4 years          | Pit Bull           | White         | 
| A615156   | 1/1          | Transfer        | Dog         | Intact Female    | 1 month          | Pit Bull           | Chocolate     | 
| A615158   | 1/1          | Transfer        | Dog         | Intact Female    | 1 month          | Pit Bull           | Chocolate     | 
```