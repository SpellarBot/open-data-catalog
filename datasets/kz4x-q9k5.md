# Austin Animal Center Stray Map

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-stray-map) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kz4x-q9k5) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kz4x-q9k5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kz4x-q9k5/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kz4x-q9k5 |
| Name | Austin Animal Center Stray Map |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, stray, austin animal center, no kill, data, open government |
| Created | 2014-06-24T20:53:10Z |
| Publication Date | 2015-12-17T22:53:01Z |

## Description

This map shows all stray cats and dogs that are currently listed in AAC's database for no longer than a week. Most will be located at AAC, but some will be held by citizens, which will be indicated on the "At AAC" column. AAC will post an image as soon as possible, which can be accessed by clicking the link in the "Image Link" column. Please also check http://www.austintexas.gov/department/lost-found-pet for more information.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | animal_id   | Animal ID   | text          | text          |
| Yes      | series tag  | at_aac      | At AAC      | text          | text          |
| Yes      | time        | intake_date | Intake Date | calendar_date | calendar_date |
| Yes      | series tag  | type        | Type        | text          | text          |
| Yes      | series tag  | looks_like  | Looks Like  | text          | text          |
| Yes      | series tag  | color       | Color       | text          | text          |
| Yes      | series tag  | sex         | Sex         | text          | text          |
| Yes      | series tag  | age         | Age         | text          | text          |
| Yes      | series tag  | image       | Image Link  | url           | url           |
```

## Time Field

```ls
Value = intake_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kz4x-q9k5 d:2017-04-10T00:00:00.000Z t:sex="Intact Female" t:looks_like="Golden Retriever Mix" t:color=Cream t:age="11 months" t:image="http://www.petharbor.com/pet.asp?uaid=ASTN.A746876" t:at_aac="Yes (come to the shelter)" t:type=Dog t:animal_id=A746876 m:row_number.kz4x-q9k5=1

series e:kz4x-q9k5 d:2017-04-10T00:00:00.000Z t:sex="Intact Female" t:looks_like="Domestic Shorthair Mix" t:color="Brown Tabby" t:age="4 weeks" t:image="http://www.petharbor.com/pet.asp?uaid=ASTN.A746868" t:at_aac="No (contact for more info)" t:type=Cat t:animal_id=A746868 m:row_number.kz4x-q9k5=2

series e:kz4x-q9k5 d:2017-04-10T00:00:00.000Z t:sex="Intact Male" t:looks_like="Domestic Shorthair Mix" t:color="Brown Tabby" t:age="4 weeks" t:image="http://www.petharbor.com/pet.asp?uaid=ASTN.A746867" t:at_aac="No (contact for more info)" t:type=Cat t:animal_id=A746867 m:row_number.kz4x-q9k5=3
```

## Meta Commands

```ls
metric m:row_number.kz4x-q9k5 p:long l:"Row Number"

entity e:kz4x-q9k5 l:"Austin Animal Center Stray Map" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/kz4x-q9k5

property e:kz4x-q9k5 t:meta.view v:id=kz4x-q9k5 v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Austin Animal Center Stray Map" v:attribution="Austin Animal Center"

property e:kz4x-q9k5 t:meta.view.license v:name="Public Domain"

property e:kz4x-q9k5 t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:kz4x-q9k5 t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | at_aac                     | intake_date         | type | looks_like               | color             | sex           | age       | image                                                      | 
| ========= | ========================== | =================== | ==== | ======================== | ================= | ============= | ========= | ========================================================== | 
| A746876   | Yes (come to the shelter)  | 2017-04-10T00:00:00 | Dog  | Golden Retriever Mix     | Cream             | Intact Female | 11 months | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746876, null] | 
| A746868   | No (contact for more info) | 2017-04-10T00:00:00 | Cat  | Domestic Shorthair Mix   | Brown Tabby       | Intact Female | 4 weeks   | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746868, null] | 
| A746867   | No (contact for more info) | 2017-04-10T00:00:00 | Cat  | Domestic Shorthair Mix   | Brown Tabby       | Intact Male   | 4 weeks   | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746867, null] | 
| A746893   | No (contact for more info) | 2017-04-10T00:00:00 | Dog  | Labrador Retriever Mix   | Black/White       | Intact Female | 3 months  | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746893, null] | 
| A746896   | No (contact for more info) | 2017-04-10T00:00:00 | Cat  | Domestic Medium Hair Mix | Torbie/White      | Intact Female | 1 year    | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746896, null] | 
| A746900   | No (contact for more info) | 2017-04-10T00:00:00 | Dog  | Pit Bull Mix             | Tan/White         | Intact Female | 2 years   | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746900, null] | 
| A746898   | No (contact for more info) | 2017-04-10T00:00:00 | Dog  | Chihuahua Shorthair Mix  | Black/Tan         | Spayed Female | 7 years   | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746898, null] | 
| A746897   | No (contact for more info) | 2017-04-10T00:00:00 | Dog  | Chihuahua Shorthair Mix  | Brown             | Neutered Male | 9 months  | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746897, null] | 
| A746907   | Yes (come to the shelter)  | 2017-04-11T00:00:00 | Cat  | Domestic Shorthair Mix   | Black/White       | Intact Male   | 1 year    | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746907, null] | 
| A746909   | Yes (come to the shelter)  | 2017-04-11T00:00:00 | Cat  | Domestic Shorthair Mix   | Brown Tabby/White | Intact Female | 1 year    | [http://www.petharbor.com/pet.asp?uaid=ASTN.A746909, null] | 
```