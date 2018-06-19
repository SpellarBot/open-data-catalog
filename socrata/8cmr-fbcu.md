# Animal Services Intake Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-services-intake-data-57f73) |
| Metadata | [Link](https://data.lacity.org/api/views/8cmr-fbcu) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/8cmr-fbcu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/8cmr-fbcu/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 8cmr-fbcu |
| Name | Animal Services Intake Data |
| Attribution | City of Los Angeles, Department of Animal Services |
| Category | A Well Run City |
| Tags | animal shelter, city pound, dog, cat, rabbit |
| Created | 2014-05-27T23:02:34Z |
| Publication Date | 2014-05-29T20:24:24Z |

## Description

Dept of Animal Services animal intake data for 2011, 2012 and 2013

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | shelter          | Shelter          | text          | text          |
| Yes      | series tag  | animal_id        | Animal ID#       | text          | text          |
| Yes      | time        | intake_date      | Intake Date      | calendar_date | calendar_date |
| Yes      | series tag  | intake_type      | Intake Type      | text          | text          |
| Yes      | series tag  | intake_condition | Intake Condition | text          | text          |
| Yes      | series tag  | animal_type      | Animal Type      | text          | text          |
| Yes      | series tag  | group            | Group            | text          | text          |
| Yes      | series tag  | breed_1          | Breed 1          | text          | text          |
| Yes      | series tag  | breed_2          | Breed 2          | text          | text          |
```

## Time Field

```ls
Value = intake_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8cmr-fbcu d:2011-11-11T00:00:00.000Z t:breed_1="AMERICAN STAFF" t:intake_condition=DEAD t:breed_2=MIX t:shelter="W VALLEY" t:group=MASTIFF t:animal_type=DOG t:intake_type="OWNER SUR" t:animal_id=A0041356 m:row_number.8cmr-fbcu=1

series e:8cmr-fbcu d:2011-08-07T00:00:00.000Z t:breed_1="CHOW CHOW" t:intake_condition=ALIVE t:shelter="N CENTRA" t:group=SPITZ t:animal_type=DOG t:intake_type="OWNER SUR" t:animal_id=A0163185 m:row_number.8cmr-fbcu=2

series e:8cmr-fbcu d:2011-12-18T00:00:00.000Z t:breed_1="TERRIER X" t:intake_condition=DEAD t:breed_2=MIX t:shelter="E VALLEY" t:animal_type=DOG t:intake_type="OWNER SUR" t:animal_id=A0163432 m:row_number.8cmr-fbcu=3
```

## Meta Commands

```ls
metric m:row_number.8cmr-fbcu p:long l:"Row Number"

entity e:8cmr-fbcu l:"Animal Services Intake Data" t:attribution="City of Los Angeles, Department of Animal Services" t:url=https://data.lacity.org/api/views/8cmr-fbcu

property e:8cmr-fbcu t:meta.view v:id=8cmr-fbcu v:category="A Well Run City" v:averageRating=0 v:name="Animal Services Intake Data" v:attribution="City of Los Angeles, Department of Animal Services"

property e:8cmr-fbcu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8cmr-fbcu t:meta.view.owner v:id=s8gh-rehm v:profileImageUrlMedium=/api/users/s8gh-rehm/profile_images/THUMB v:profileImageUrlLarge=/api/users/s8gh-rehm/profile_images/LARGE v:screenName="Animal Services OpenData" v:profileImageUrlSmall=/api/users/s8gh-rehm/profile_images/TINY v:displayName="Animal Services OpenData"

property e:8cmr-fbcu t:meta.view.tableauthor v:id=s8gh-rehm v:profileImageUrlMedium=/api/users/s8gh-rehm/profile_images/THUMB v:profileImageUrlLarge=/api/users/s8gh-rehm/profile_images/LARGE v:screenName="Animal Services OpenData" v:profileImageUrlSmall=/api/users/s8gh-rehm/profile_images/TINY v:roleName=publisher v:displayName="Animal Services OpenData"
```

## Top Records

```ls
| shelter  | animal_id | intake_date         | intake_type | intake_condition | animal_type | group    | breed_1         | breed_2     | 
| ======== | ========= | =================== | =========== | ================ | =========== | ======== | =============== | =========== | 
| W VALLEY | A0041356  | 2011-11-11T00:00:00 | OWNER SUR   | DEAD             | DOG         | MASTIFF  | AMERICAN STAFF  | MIX         | 
| N CENTRA | A0163185  | 2011-08-07T00:00:00 | OWNER SUR   | ALIVE            | DOG         | SPITZ    | CHOW CHOW       |             | 
| E VALLEY | A0163432  | 2011-12-18T00:00:00 | OWNER SUR   | DEAD             | DOG         |          | TERRIER X       | MIX         | 
| S LA     | A0164458  | 2013-01-06T00:00:00 | OWNER SUR   | DEAD             | DOG         | MASTIFF  | AMERICAN STAFF  | MIX         | 
| W LA     | A0166070  | 2011-09-03T00:00:00 | OWNER SUR   | DEAD             | DOG         | SPITZ    | AKITA           | MIX         | 
| S LA     | A0168340  | 2011-01-12T00:00:00 | OWNER SUR   | ALIVE            | DOG         | SHEPHERD | GERM SHEPHERD   |             | 
| S LA     | A0168479  | 2011-01-05T00:00:00 | OWNER SUR   | ALIVE            | DOG         | SHEPHERD | GERM SHEPHERD   | MIX         | 
| N CENTRA | A0215777  | 2013-03-13T00:00:00 | POS OWNER   | ALIVE            | DOG         | COLLIE   | AUST CATTLE DOG |             | 
| W LA     | A0216724  | 2013-06-25T00:00:00 | OWNER SUR   | ALIVE            | DOG         | COLLIE   | COLLIE SMOOTH   | GOLDEN RETR | 
| W LA     | A0216873  | 2012-07-24T00:00:00 | POS OWNER   | ALIVE            | DOG         | COLLIE   | BORDER COLLIE   | MIX         | 
```