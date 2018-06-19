# 2-16 to 2-22-14 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2-16-to-2-22-14-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vs6n-chuq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vs6n-chuq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vs6n-chuq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vs6n-chuq |
| Name | 2-16 to 2-22-14 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | dog, cat, austin animal center, data, open government |
| Created | 2014-02-24T19:44:27Z |
| Publication Date | 2014-02-24T19:45:52Z |

## Description

All animal outcomes for the week of Sunday 2-16 to Saturday 2-22-14.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | time        | outcome_date     | Outcome Date     | calendar_date | calendar_date |
| Yes      | series tag  | found_location   | Found Location   | text          | text          |
| Yes      | series tag  | outcome_type     | Outcome Type     | text          | text          |
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

## Data Commands

```ls
series e:vs6n-chuq d:2014-02-16T00:00:00.000Z t:breed="Rottweiler Mix" t:age_upon_outcome="4 years" t:color=Black/Brown t:sex_upon_outcome="Spayed Female" t:outcome_type=Adoption t:found_location="Austin, TX" t:animal_type=Dog t:animal_id=A621010 m:row_number.vs6n-chuq=1

series e:vs6n-chuq d:2014-02-16T00:00:00.000Z t:breed="Boxer Mix" t:age_upon_outcome="2 years" t:color=Tan/White t:sex_upon_outcome="Neutered Male" t:outcome_type=Adoption t:found_location="Salt Spring Austin, TX" t:animal_type=Dog t:animal_id=A631538 m:row_number.vs6n-chuq=2

series e:vs6n-chuq d:2014-02-16T00:00:00.000Z t:breed="Rat Terrier Mix" t:age_upon_outcome="13 years" t:color=White/Black t:sex_upon_outcome="Spayed Female" t:outcome_type=Transfer t:found_location="Austin, TX" t:animal_type=Dog t:animal_id=A632022 m:row_number.vs6n-chuq=3
```

## Meta Commands

```ls
metric m:row_number.vs6n-chuq p:long l:"Row Number"

entity e:vs6n-chuq l:"2-16 to 2-22-14 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/vs6n-chuq

property e:vs6n-chuq t:meta.view v:id=vs6n-chuq v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="2-16 to 2-22-14 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:vs6n-chuq t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:vs6n-chuq t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | outcome_date        | found_location                       | outcome_type    | animal_type | sex_upon_outcome | age_upon_outcome | breed                              | color           | 
| ========= | =================== | ==================================== | =============== | =========== | ================ | ================ | ================================== | =============== | 
| A621010   | 2014-02-16T00:00:00 | Austin, TX                           | Adoption        | Dog         | Spayed Female    | 4 years          | Rottweiler Mix                     | Black/Brown     | 
| A631538   | 2014-02-16T00:00:00 | Salt Spring Austin, TX               | Adoption        | Dog         | Neutered Male    | 2 years          | Boxer Mix                          | Tan/White       | 
| A632022   | 2014-02-16T00:00:00 | Austin, TX                           | Transfer        | Dog         | Spayed Female    | 13 years         | Rat Terrier Mix                    | White/Black     | 
| A632476   | 2014-02-16T00:00:00 | 1204 Castile Rd Travis, TX           | Return to Owner | Dog         | Spayed Female    | 3 years          | Labrador Retriever Mix             | Black           | 
| A651564   | 2014-02-16T00:00:00 | Austin, TX                           | Adoption        | Dog         | Neutered Male    | 1 year           | Pit Bull Mix                       | Brown/White     | 
| A663220   | 2014-02-16T00:00:00 | 8207 Tonopa Austin, TX               | Adoption        | Dog         | Spayed Female    | 1 year           | Jack Russell Terrier Mix           | White/Brown     | 
| A664695   | 2014-02-16T00:00:00 | Austin, TX                           | Transfer        | Dog         | Neutered Male    | 9 months         | American Foxhound Mix              | Brown/White     | 
| A667777   | 2014-02-16T00:00:00 | Austin, TX                           | Adoption        | Dog         | Spayed Female    | 2 years          | American Staffordshire Terrier Mix | Chocolate/White | 
| A667920   | 2014-02-16T00:00:00 | Payton Gin And Clarkfield Austin, TX | Transfer        | Dog         | Spayed Female    | 4 years          | American Staffordshire Terrier Mix | Blue/White      | 
| A668351   | 2014-02-16T00:00:00 | Austin, TX                           | Adoption        | Dog         | Neutered Male    | 4 years          | Chihuahua Shorthair Mix            | White/Brown     | 
```