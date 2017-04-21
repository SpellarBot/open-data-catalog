# Austin Animal Center FY14 Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-fy14-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/azsy-zee6) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/azsy-zee6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/azsy-zee6/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | azsy-zee6 |
| Name | Austin Animal Center FY14 Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2015-01-14T16:54:01Z |
| Publication Date | 2015-01-14T16:56:34Z |

## Description

all animal outcomes for Fiscal Year 2014 (October 1st 2013 to September 30th 2014)

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | series tag  | name             | Name             | text          | text          |
| Yes      | time        | outcome_date     | Outcome Date     | calendar_date | calendar_date |
| No       |             | outcome_time     | Outcome Time     | text          | text          |
| Yes      | series tag  | outcome_type     | Outcome Type     | text          | text          |
| Yes      | series tag  | outcome_subtype  | Outcome Subtype  | text          | text          |
| Yes      | series tag  | animal_type      | Animal Type      | text          | text          |
| Yes      | series tag  | sex_upon_outcome | Sex upon Outcome | text          | text          |
| Yes      | series tag  | age_upon_outcome | Age upon Outcome | text          | text          |
| Yes      | series tag  | breed            | Breed            | text          | text          |
| Yes      | series tag  | color            | Color            | text          | text          |
```

## Time Field

```ls
Value = outcome_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = outcome_time
```

## Data Commands

```ls
series e:azsy-zee6 d:2013-10-01T00:00:00.000Z t:breed="Labrador Retriever Mix" t:age_upon_outcome="2 months" t:color=Black t:sex_upon_outcome="Neutered Male" t:outcome_type=Adoption t:name=*Dudley t:outcome_subtype=Foster t:animal_type=Dog t:animal_id=A659834 m:row_number.azsy-zee6=1

series e:azsy-zee6 d:2013-10-01T00:00:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="1 week" t:color=Orange/White t:sex_upon_outcome=Unknown t:outcome_type=Transfer t:outcome_subtype=Partner t:animal_type=Cat t:animal_id=A664235 m:row_number.azsy-zee6=2

series e:azsy-zee6 d:2013-10-01T00:00:00.000Z t:breed="Domestic Shorthair Mix" t:age_upon_outcome="1 week" t:color=Orange/White t:sex_upon_outcome=Unknown t:outcome_type=Transfer t:outcome_subtype=Partner t:animal_type=Cat t:animal_id=A664236 m:row_number.azsy-zee6=3
```

## Meta Commands

```ls
metric m:row_number.azsy-zee6 p:long l:"Row Number"

entity e:azsy-zee6 l:"Austin Animal Center FY14 Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/azsy-zee6

property e:azsy-zee6 t:meta.view v:id=azsy-zee6 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Austin Animal Center FY14 Outcomes" v:attribution="Austin Animal Center"

property e:azsy-zee6 t:meta.view.license v:name="Public Domain"

property e:azsy-zee6 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:azsy-zee6 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | name      | outcome_date        | outcome_time | outcome_type    | outcome_subtype | animal_type | sex_upon_outcome | age_upon_outcome | breed                  | color        | 
| ========= | ========= | =================== | ============ | =============== | =============== | =========== | ================ | ================ | ====================== | ============ | 
| A659834   | *Dudley   | 2013-10-01T00:00:00 | 9:31AM       | Adoption        | Foster          | Dog         | Neutered Male    | 2 months         | Labrador Retriever Mix | Black        | 
| A664235   |           | 2013-10-01T00:00:00 | 10:39AM      | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664236   |           | 2013-10-01T00:00:00 | 10:44AM      | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664237   |           | 2013-10-01T00:00:00 | 10:44AM      | Transfer        | Partner         | Cat         | Unknown          | 1 week           | Domestic Shorthair Mix | Orange/White | 
| A664223   | Moby      | 2013-10-01T00:00:00 | 11:03AM      | Return to Owner |                 | Dog         | Neutered Male    | 4 years          | Bulldog Mix            | White        | 
| A663646   |           | 2013-10-01T00:00:00 | 11:12AM      | Transfer        | Partner         | Dog         | Neutered Male    | 3 years          | Toy Poodle Mix         | White        | 
| A663888   |           | 2013-10-01T00:00:00 | 11:13AM      | Transfer        | Partner         | Dog         | Spayed Female    | 2 years          | Boxer Mix              | Red/White    | 
| A663572   | *Starla   | 2013-10-01T00:00:00 | 11:42AM      | Adoption        |                 | Dog         | Spayed Female    | 3 years          | Anatol Shepherd Mix    | White/Brown  | 
| A663833   | Baby Girl | 2013-10-01T00:00:00 | 11:50AM      | Return to Owner |                 | Dog         | Spayed Female    | 9 years          | Labrador Retriever Mix | Black        | 
| A661795   | Blakie    | 2013-10-01T00:00:00 | 11:53AM      | Adoption        |                 | Cat         | Spayed Female    | 6 months         | Domestic Shorthair Mix | Tortie       | 
```