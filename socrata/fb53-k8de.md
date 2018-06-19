# Austin Animal Center FY15 Outcomes *Updated Hourly*

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-fy15-outcomes-updated-hourly) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fb53-k8de) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fb53-k8de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fb53-k8de/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fb53-k8de |
| Name | Austin Animal Center FY15 Outcomes *Updated Hourly* |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2015-01-14T17:14:19Z |
| Publication Date | 2015-01-14T17:19:47Z |

## Description

all animal outcomes for Fiscal Year 2015 (October 1st 2014 to September 30th 2015)

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | animal_id        | Animal ID        | text      | text        |
| Yes      | series tag  | name             | Name             | text      | text        |
| Yes      | time        | outcome_date     | Outcome Date     | text      | text        |
| No       |             | outcome_time     | Outcome Time     | text      | text        |
| Yes      | series tag  | outcome_type     | Outcome Type     | text      | text        |
| Yes      | series tag  | outcome_subtype  | Outcome Subtype  | text      | text        |
| Yes      | series tag  | animal_type      | Animal Type      | text      | text        |
| Yes      | series tag  | sex_upon_outcome | Sex upon Outcome | text      | text        |
| Yes      | series tag  | age_upon_outcome | Age upon Outcome | text      | text        |
| Yes      | series tag  | breed            | Breed            | text      | text        |
| Yes      | series tag  | color            | Color            | text      | text        |
```

## Time Field

```ls
Value = outcome_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = outcome_time
```

## Data Commands

```ls
series e:fb53-k8de d:2014-10-01T00:00:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="1 month" t:color=Tortie/Calico t:sex_upon_outcome="Intact Female" t:outcome_type=Euthanasia t:outcome_subtype="Rabies Risk" t:animal_type=Cat t:animal_id=A689146 m:row_number.fb53-k8de=1

series e:fb53-k8de d:2014-10-01T00:00:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="2 years" t:color="White/Brown Tabby" t:sex_upon_outcome="Neutered Male" t:outcome_type=Euthanasia t:outcome_subtype=Suffering t:animal_type=Cat t:animal_id=A689208 m:row_number.fb53-k8de=2

series e:fb53-k8de d:2014-10-01T00:00:00.000Z t:breed="Domestic Medium Hair Mix" t:age_upon_outcome="6 years" t:color="Brown Tabby" t:sex_upon_outcome="Intact Female" t:outcome_type=Transfer t:outcome_subtype=SCRP t:animal_type=Cat t:animal_id=A689225 m:row_number.fb53-k8de=3
```

## Meta Commands

```ls
metric m:row_number.fb53-k8de p:long l:"Row Number"

entity e:fb53-k8de l:"Austin Animal Center FY15 Outcomes *Updated Hourly*" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/fb53-k8de

property e:fb53-k8de t:meta.view v:id=fb53-k8de v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Austin Animal Center FY15 Outcomes *Updated Hourly*" v:attribution="Austin Animal Center"

property e:fb53-k8de t:meta.view.license v:name="Public Domain"

property e:fb53-k8de t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:fb53-k8de t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | name      | outcome_date | outcome_time | outcome_type    | outcome_subtype | animal_type | sex_upon_outcome | age_upon_outcome | breed                           | color             | 
| ========= | ========= | ============ | ============ | =============== | =============== | =========== | ================ | ================ | =============================== | ================= | 
| A689146   |           | 10/01/14     | 7:54AM       | Euthanasia      | Rabies Risk     | Cat         | Intact Female    | 1 month          | Domestic Shorthair Mix          | Tortie/Calico     | 
| A689208   |           | 10/01/14     | 7:56AM       | Euthanasia      | Suffering       | Cat         | Neutered Male    | 2 years          | Domestic Shorthair Mix          | White/Brown Tabby | 
| A689225   |           | 10/01/14     | 9:00AM       | Transfer        | SCRP            | Cat         | Intact Female    | 6 years          | Domestic Medium Hair Mix        | Brown Tabby       | 
| A689202   |           | 10/01/14     | 11:30AM      | Euthanasia      | Rabies Risk     | Other       | Unknown          | 6 months         | Bat Mix                         | Gray              | 
| A684326   | Kelvi     | 10/01/14     | 11:37AM      | Adoption        |                 | Dog         | Spayed Female    | 5 years          | Border Collie Mix               | Black/White       | 
| A574935   | Blue      | 10/01/14     | 12:11PM      | Transfer        | Partner         | Dog         | Neutered Male    | 10 years         | Australian Cattle Dog Mix       | Blue Merle/Black  | 
| A575129   | Brandi    | 10/01/14     | 12:11PM      | Transfer        | Partner         | Dog         | Spayed Female    | 10 years         | Australian Cattle Dog Mix       | Red Merle         | 
| A688991   | Shades    | 10/01/14     | 12:25PM      | Transfer        | Partner         | Dog         | Intact Male      | 3 years          | Shih Tzu                        | Sable/White       | 
| A689108   | Andromeda | 10/01/14     | 12:30PM      | Adoption        |                 | Cat         | Spayed Female    | 5 years          | Himalayan Mix                   | Flame Point       | 
| A689241   | Lady      | 10/01/14     | 12:53PM      | Return to Owner |                 | Dog         | Spayed Female    | 2 years          | Labrador Retriever/Basset Hound | Black/White       | 
```