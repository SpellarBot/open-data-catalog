# 2-9 to 2-15-14 Austin Animal Center Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2-9-to-2-15-14-austin-animal-center-outcomes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ctnk-wvxm) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ctnk-wvxm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ctnk-wvxm/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ctnk-wvxm |
| Name | 2-9 to 2-15-14 Austin Animal Center Outcomes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal center, data, open government |
| Created | 2014-02-18T21:54:29Z |
| Publication Date | 2014-02-18T21:56:09Z |

## Description

All animal outcomes for the week of Sunday 2-9 to Saturday 2-15-14.

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
series e:ctnk-wvxm d:2014-02-09T00:00:00.000Z t:breed="Brittany Mix" t:age_upon_outcome="7 years" t:color=White/Red t:sex_upon_outcome="Spayed Female" t:outcome_type="Return to Owner" t:found_location="4434 Frontier Trl Austin, TX" t:animal_type=Dog t:animal_id=A587190 m:row_number.ctnk-wvxm=1

series e:ctnk-wvxm d:2014-02-09T00:00:00.000Z t:breed=Brittany t:age_upon_outcome="8 years" t:color=White/Brown t:sex_upon_outcome="Neutered Male" t:outcome_type="Return to Owner" t:found_location="4434 Frontier Trl Austin, TX" t:animal_type=Dog t:animal_id=A592428 m:row_number.ctnk-wvxm=2

series e:ctnk-wvxm d:2014-02-09T00:00:00.000Z t:breed="Australian Shepherd Mix" t:age_upon_outcome="1 year" t:color=Brown/White t:sex_upon_outcome="Spayed Female" t:outcome_type=Adoption t:found_location="Austin, TX" t:animal_type=Dog t:animal_id=A663863 m:row_number.ctnk-wvxm=3
```

## Meta Commands

```ls
metric m:row_number.ctnk-wvxm p:long l:"Row Number"

entity e:ctnk-wvxm l:"2-9 to 2-15-14 Austin Animal Center Outcomes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/ctnk-wvxm

property e:ctnk-wvxm t:meta.view v:id=ctnk-wvxm v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="2-9 to 2-15-14 Austin Animal Center Outcomes" v:attribution="Austin Animal Center"

property e:ctnk-wvxm t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:ctnk-wvxm t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | outcome_date        | found_location               | outcome_type    | animal_type | sex_upon_outcome | age_upon_outcome | breed                                   | color       | 
| ========= | =================== | ============================ | =============== | =========== | ================ | ================ | ======================================= | =========== | 
| A587190   | 2014-02-09T00:00:00 | 4434 Frontier Trl Austin, TX | Return to Owner | Dog         | Spayed Female    | 7 years          | Brittany Mix                            | White/Red   | 
| A592428   | 2014-02-09T00:00:00 | 4434 Frontier Trl Austin, TX | Return to Owner | Dog         | Neutered Male    | 8 years          | Brittany                                | White/Brown | 
| A663863   | 2014-02-09T00:00:00 | Austin, TX                   | Adoption        | Dog         | Spayed Female    | 1 year           | Australian Shepherd Mix                 | Brown/White | 
| A665123   | 2014-02-09T00:00:00 | Out Of Juris, TX             | Adoption        | Dog         | Spayed Female    | 5 years          | Redbone Hound                           | Red/White   | 
| A669812   | 2014-02-09T00:00:00 | General Williams Travis, TX  | Adoption        | Dog         | Spayed Female    | 4 years          | Anatol Shepherd/Labrador Retriever      | Black/White | 
| A669817   | 2014-02-09T00:00:00 | Tampa Cove Austin, TX        | Adoption        | Cat         | Intact Male      | 2 months         | Domestic Shorthair Mix                  | White/Black | 
| A669992   | 2014-02-09T00:00:00 | Austin, TX                   | Adoption        | Dog         | Neutered Male    | 1 year           | Labrador Retriever/Jack Russell Terrier | White/Brown | 
| A670436   | 2014-02-09T00:00:00 | Austin, TX                   | Adoption        | Cat         | Spayed Female    | 1 year           | Japanese Bobtail Mix                    | Black       | 
| A670563   | 2014-02-09T00:00:00 | 5209 Cameron Rd Austin, TX   | Adoption        | Dog         | Spayed Female    | 1 year           | Pit Bull Mix                            | Blue/White  | 
| A670635   | 2014-02-09T00:00:00 | 7605 Fm 1625 Rd Travis, TX   | Transfer        | Dog         | Spayed Female    | 5 months         | Plott Hound Mix                         | Sable       | 
```