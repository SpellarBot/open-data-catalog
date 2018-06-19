# Seattle Pet Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-pet-licenses) |
| Metadata | [Link](https://data.seattle.gov/api/views/jguv-t9rb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/jguv-t9rb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/jguv-t9rb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | jguv-t9rb |
| Name | Seattle Pet Licenses |
| Attribution | City of Seattle Department of Finance and Administrative Services |
| Category | Community |
| Tags | animal, shelter, pet, license, tag |
| Created | 2017-01-24T22:04:13Z |
| Publication Date | 2017-01-24T22:17:08Z |

## Description

A list of active/current Seattle pet licenses, including animal type (species), pet's name, breed and the owner's ZIP code. (List current as of Jan. 11, 2017)

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | time        | license_issue_date | License Issue Date | calendar_date | calendar_date |
| Yes      | series tag  | license_number     | License Number     | text          | number        |
| Yes      | series tag  | animal_s_name      | Animal's Name      | text          | text          |
| Yes      | series tag  | species            | Species            | text          | text          |
| Yes      | series tag  | primary_breed      | Primary Breed      | text          | text          |
| Yes      | series tag  | secondary_breed    | Secondary Breed    | text          | text          |
| Yes      | series tag  | zip_code           | ZIP Code           | text          | text          |
```

## Time Field

```ls
Value = license_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jguv-t9rb d:2005-03-29T00:00:00.000Z t:zip_code=98104 t:species=Dog t:primary_breed="Dachshund, Standard Smooth Haired" t:license_number=130651 t:animal_s_name=Ozzy m:row_number.jguv-t9rb=1

series e:jguv-t9rb d:2009-12-23T00:00:00.000Z t:zip_code=98107 t:species=Dog t:primary_breed="Schnauzer, Miniature" t:license_number=898148 t:animal_s_name=Jack t:secondary_breed="Terrier, Rat" m:row_number.jguv-t9rb=2

series e:jguv-t9rb d:2006-01-20T00:00:00.000Z t:zip_code=98117 t:species=Dog t:primary_breed="Retriever, Golden" t:license_number=29654 t:animal_s_name=Ginger t:secondary_breed="Retriever, Labrador" m:row_number.jguv-t9rb=3
```

## Meta Commands

```ls
metric m:row_number.jguv-t9rb p:long l:"Row Number"

entity e:jguv-t9rb l:"Seattle Pet Licenses" t:attribution="City of Seattle Department of Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/jguv-t9rb

property e:jguv-t9rb t:meta.view v:id=jguv-t9rb v:category=Community v:averageRating=0 v:name="Seattle Pet Licenses" v:attribution="City of Seattle Department of Finance and Administrative Services"

property e:jguv-t9rb t:meta.view.owner v:id=axtc-pgxr v:profileImageUrlMedium=/api/users/axtc-pgxr/profile_images/THUMB v:profileImageUrlLarge=/api/users/axtc-pgxr/profile_images/LARGE v:screenName="FAS - Seattle Animal Shelter" v:profileImageUrlSmall=/api/users/axtc-pgxr/profile_images/TINY v:displayName="FAS - Seattle Animal Shelter"

property e:jguv-t9rb t:meta.view.tableauthor v:id=axtc-pgxr v:profileImageUrlMedium=/api/users/axtc-pgxr/profile_images/THUMB v:profileImageUrlLarge=/api/users/axtc-pgxr/profile_images/LARGE v:screenName="FAS - Seattle Animal Shelter" v:profileImageUrlSmall=/api/users/axtc-pgxr/profile_images/TINY v:roleName=publisher v:displayName="FAS - Seattle Animal Shelter"
```

## Top Records

```ls
| license_issue_date  | license_number | animal_s_name | species | primary_breed                     | secondary_breed     | zip_code | 
| =================== | ============== | ============= | ======= | ================================= | =================== | ======== | 
| 2005-03-29T00:00:00 | 130651         | Ozzy          | Dog     | Dachshund, Standard Smooth Haired |                     | 98104    | 
| 2009-12-23T00:00:00 | 898148         | Jack          | Dog     | Schnauzer, Miniature              | Terrier, Rat        | 98107    | 
| 2006-01-20T00:00:00 | 29654          | Ginger        | Dog     | Retriever, Golden                 | Retriever, Labrador | 98117    | 
| 2006-02-07T00:00:00 | 75432          | Pepper        | Cat     | Manx                              | Mix                 | 98103    | 
| 2006-08-04T00:00:00 | 729899         | Addy          | Dog     | Retriever, Golden                 |                     | 98105    | 
| 2007-07-24T00:00:00 | 437433         | Rustie        | Dog     | Dachshund, Standard Smooth Haired |                     | 98108    | 
| 2006-12-06T00:00:00 | 959078         | Lady          | Dog     | Doberman Pinscher                 |                     | 98104    | 
| 2007-11-19T00:00:00 | 895915         | Emily         | Cat     | Domestic Medium Hair              |                     | 98103    | 
| 2007-12-04T00:00:00 | 957798         | Pancho        | Dog     | Chihuahua, Short Coat             |                     |          | 
| 2008-01-31T00:00:00 | 26600          | Sampson       | Dog     | Shepherd                          | Siberian Husky      | 98106    | 
```