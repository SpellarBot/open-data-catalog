# 2012 Austin Animal Center Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-austin-animal-center-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3ghn-wv5a) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3ghn-wv5a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3ghn-wv5a/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3ghn-wv5a |
| Name | 2012 Austin Animal Center Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | animals, animal services, 2012, intake, austin animal center |
| Created | 2013-11-21T19:57:44Z |
| Publication Date | 2013-11-21T20:02:45Z |

## Description

Animal and intake descriptions for Austin Animal Center cats and dogs in 2012.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | animal_id        | Animal ID        | text      | text        |
| No       |             | intake_date      | Intake Date      | text      | text        |
| Yes      | series tag  | intake_type      | Intake Type      | text      | text        |
| Yes      | series tag  | intake_condition | Intake Condition | text      | text        |
| Yes      | series tag  | animal_type      | Animal Type      | text      | text        |
| Yes      | series tag  | sex_upon_intake  | Sex upon Intake  | text      | text        |
| Yes      | series tag  | age_upon_intake  | Age upon Intake  | text      | text        |
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
Excluded Fields = intake_date
```

## Data Commands

```ls
series e:3ghn-wv5a d:2012-01-01T00:00:00.000Z t:sex_upon_intake="Neutered Male" t:primary_color=Buff t:intake_condition=Normal t:primary_breed="Golden Retriever" t:age_upon_intake="11 years" t:animal_type=Dog t:intake_type=Stray t:animal_id=A247649 m:row_number.3ghn-wv5a=1

series e:3ghn-wv5a d:2012-01-01T00:00:00.000Z t:sex_upon_intake="Intact Male" t:primary_color=Black t:intake_condition=Normal t:primary_breed="Labrador Retriever" t:age_upon_intake="8 years" t:animal_type=Dog t:intake_type=Stray t:animal_id=A351576 m:row_number.3ghn-wv5a=2

series e:3ghn-wv5a d:2012-01-01T00:00:00.000Z t:sex_upon_intake="Intact Male" t:primary_color=Tan t:intake_condition=Normal t:primary_breed="Labrador Retriever" t:age_upon_intake="7 years" t:animal_type=Dog t:intake_type=Stray t:animal_id=A351577 m:row_number.3ghn-wv5a=3
```

## Meta Commands

```ls
metric m:row_number.3ghn-wv5a p:long l:"Row Number"

entity e:3ghn-wv5a l:"2012 Austin Animal Center Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/3ghn-wv5a

property e:3ghn-wv5a t:meta.view v:id=3ghn-wv5a v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="2012 Austin Animal Center Intakes" v:attribution="Austin Animal Center"

property e:3ghn-wv5a t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:3ghn-wv5a t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | intake_date | intake_type | intake_condition | animal_type | sex_upon_intake | age_upon_intake | primary_breed      | primary_color | 
| ========= | =========== | =========== | ================ | =========== | =============== | =============== | ================== | ============= | 
| A247649   | 1/1         | Stray       | Normal           | Dog         | Neutered Male   | 11 years        | Golden Retriever   | Buff          | 
| A351576   | 1/1         | Stray       | Normal           | Dog         | Intact Male     | 8 years         | Labrador Retriever | Black         | 
| A351577   | 1/1         | Stray       | Normal           | Dog         | Intact Male     | 7 years         | Labrador Retriever | Tan           | 
| A595699   | 1/1         | Stray       | Normal           | Dog         | Neutered Male   | 8 years         | Labrador Retriever | Yellow        | 
| A609226   | 1/1         | Stray       | Normal           | Dog         | Neutered Male   | 2 years         | Pit Bull           | Tan           | 
| A609734   | 1/1         | Stray       | Normal           | Cat         | Spayed Female   | 5 months        | Domestic Shorthair | Black         | 
| A614014   | 1/1         | Stray       | Injured          | Dog         | Intact Female   | 1 year          | Beagle             | Tricolor      | 
| A616907   | 1/1         | Stray       | Injured          | Dog         | Intact Female   | 6 years         | Pug                | Fawn          | 
| A616908   | 1/1         | Stray       | Normal           | Dog         | Neutered Male   | NULL            | German Shepherd    | Black         | 
| A616909   | 1/1         | Stray       | Normal           | Cat         | Intact Female   | 8 months        | Domestic Shorthair | Blue Cream    | 
```