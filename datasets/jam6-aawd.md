# Austin Animal Center FY14 Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-fy14-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jam6-aawd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jam6-aawd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jam6-aawd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jam6-aawd |
| Name | Austin Animal Center FY14 Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, pet, austin animal center, no kill, data, open government |
| Created | 2015-01-14T16:49:30Z |
| Publication Date | 2015-01-14T16:53:15Z |

## Description

all animal intakes for Fiscal Year 2014 (October 1st 2013 to September 30th 2014)

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | series tag  | name             | Name             | text          | text          |
| Yes      | time        | intake_date      | Intake Date      | calendar_date | calendar_date |
| No       |             | intake_time      | Intake Time      | text          | text          |
| Yes      | series tag  | found_location   | Found Location   | text          | text          |
| Yes      | series tag  | intake_type      | Intake Type      | text          | text          |
| Yes      | series tag  | intake_condition | Intake Condition | text          | text          |
| Yes      | series tag  | animal_type      | Animal Type      | text          | text          |
| Yes      | series tag  | sex_upon_intake  | Sex upon Intake  | text          | text          |
| Yes      | series tag  | age_upon_intake  | Age upon Intake  | text          | text          |
| Yes      | series tag  | breed            | Breed            | text          | text          |
| Yes      | series tag  | color            | Color            | text          | text          |
```

## Time Field

```ls
Value = intake_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = intake_time
```

## Data Commands

```ls
series e:jam6-aawd d:2013-10-01T00:00:00.000Z t:sex_upon_intake="Spayed Female" t:breed="Border Terrier/Border Collie" t:intake_condition=Normal t:color=White/Tan t:name=Nina t:age_upon_intake="7 years" t:found_location="Norht Ec in Austin (TX)" t:animal_type=Dog t:intake_type=Stray t:animal_id=A521520 m:row_number.jam6-aawd=1

series e:jam6-aawd d:2013-10-01T00:00:00.000Z t:sex_upon_intake=Unknown t:breed="Domestic Shorthair Mix" t:intake_condition=Normal t:color=Orange/White t:age_upon_intake="1 week" t:found_location="Abia in Austin (TX)" t:animal_type=Cat t:intake_type=Stray t:animal_id=A664235 m:row_number.jam6-aawd=2

series e:jam6-aawd d:2013-10-01T00:00:00.000Z t:sex_upon_intake=Unknown t:breed="Domestic Shorthair Mix" t:intake_condition=Normal t:color=Orange/White t:age_upon_intake="1 week" t:found_location="Abia in Austin (TX)" t:animal_type=Cat t:intake_type=Stray t:animal_id=A664236 m:row_number.jam6-aawd=3
```

## Meta Commands

```ls
metric m:row_number.jam6-aawd p:long l:"Row Number"

entity e:jam6-aawd l:"Austin Animal Center FY14 Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/jam6-aawd

property e:jam6-aawd t:meta.view v:id=jam6-aawd v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="Austin Animal Center FY14 Intakes" v:attribution="Austin Animal Center"

property e:jam6-aawd t:meta.view.license v:name="Public Domain"

property e:jam6-aawd t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:jam6-aawd t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | name    | intake_date         | intake_time | found_location                 | intake_type     | intake_condition | animal_type | sex_upon_intake | age_upon_intake | breed                        | color             | 
| ========= | ======= | =================== | =========== | ============================== | =============== | ================ | =========== | =============== | =============== | ============================ | ================= | 
| A521520   | Nina    | 2013-10-01T00:00:00 | 7:51AM      | Norht Ec in Austin (TX)        | Stray           | Normal           | Dog         | Spayed Female   | 7 years         | Border Terrier/Border Collie | White/Tan         | 
| A664235   |         | 2013-10-01T00:00:00 | 8:33AM      | Abia in Austin (TX)            | Stray           | Normal           | Cat         | Unknown         | 1 week          | Domestic Shorthair Mix       | Orange/White      | 
| A664236   |         | 2013-10-01T00:00:00 | 8:33AM      | Abia in Austin (TX)            | Stray           | Normal           | Cat         | Unknown         | 1 week          | Domestic Shorthair Mix       | Orange/White      | 
| A664237   |         | 2013-10-01T00:00:00 | 8:33AM      | Abia in Austin (TX)            | Stray           | Normal           | Cat         | Unknown         | 1 week          | Domestic Shorthair Mix       | Orange/White      | 
| A664233   | Stevie  | 2013-10-01T00:00:00 | 8:53AM      | 7405 Springtime in Austin (TX) | Stray           | Injured          | Dog         | Intact Female   | 3 years         | Pit Bull Mix                 | Blue/White        | 
| A664238   |         | 2013-10-01T00:00:00 | 9:33AM      | Outside Jurisdiction           | Stray           | Normal           | Cat         | Unknown         | 4 months        | American Shorthair Mix       | Black/White       | 
| A664234   |         | 2013-10-01T00:00:00 | 10:37AM     | 5400 Jimmy Clay in Austin (TX) | Stray           | Injured          | Dog         | Intact Male     | 8 years         | Border Collie Mix            | Black/White       | 
| A664256   | *Donnie | 2013-10-01T00:00:00 | 10:59AM     | Austin (TX)                    | Owner Surrender | Normal           | Cat         | Neutered Male   | 17 years        | Domestic Shorthair Mix       | Brown Tabby/White | 
| A664257   | Pippin  | 2013-10-01T00:00:00 | 11:01AM     | Burleson in Travis (TX)        | Stray           | Normal           | Dog         | Intact Female   | 4 years         | Podengo Pequeno Mix          | Black             | 
| A664266   |         | 2013-10-01T00:00:00 | 11:09AM     | Payton And 183 in Austin (TX)  | Stray           | Normal           | Dog         | Intact Female   | 1 year          | Chihuahua Shorthair Mix      | Buff              | 
```