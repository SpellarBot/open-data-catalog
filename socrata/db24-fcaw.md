# 2-16 to 2-22-14 Austin Animal Center Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2-16-to-2-22-14-austin-animal-center-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/db24-fcaw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/db24-fcaw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/db24-fcaw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | db24-fcaw |
| Name | 2-16 to 2-22-14 Austin Animal Center Intakes |
| Attribution | Austin Animal Center |
| Category | Government |
| Tags | cat, dog, austin animal center, data, open government |
| Created | 2014-02-24T19:42:11Z |
| Publication Date | 2014-02-24T19:44:09Z |

## Description

All animal intakes for the week of Sunday 2-16 to Saturday 2-22-14.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | time        | intake_date      | Intake Date      | calendar_date | calendar_date |
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

## Data Commands

```ls
series e:db24-fcaw d:2014-02-16T00:00:00.000Z t:sex_upon_intake="Neutered Male" t:breed="Labrador Retriever/Pointer" t:intake_condition=Normal t:color=Black/White t:age_upon_intake="3 years" t:found_location="Austin, TX" t:animal_type=Dog t:intake_type="Owner Surrender" t:animal_id=A611152 m:row_number.db24-fcaw=1

series e:db24-fcaw d:2014-02-16T00:00:00.000Z t:sex_upon_intake="Intact Female" t:breed="Pit Bull Mix" t:intake_condition=Normal t:color="Blue Cream/White" t:age_upon_intake="2 years" t:found_location="Mlk And 183 Austin, TX" t:animal_type=Dog t:intake_type=Stray t:animal_id=A647176 m:row_number.db24-fcaw=2

series e:db24-fcaw d:2014-02-16T00:00:00.000Z t:sex_upon_intake="Neutered Male" t:breed="Labrador Retriever Mix" t:intake_condition=Normal t:color=Sable/Black t:age_upon_intake="9 months" t:found_location="Austin, TX" t:animal_type=Dog t:intake_type="Owner Surrender" t:animal_id=A663480 m:row_number.db24-fcaw=3
```

## Meta Commands

```ls
metric m:row_number.db24-fcaw p:long l:"Row Number"

entity e:db24-fcaw l:"2-16 to 2-22-14 Austin Animal Center Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/db24-fcaw

property e:db24-fcaw t:meta.view v:id=db24-fcaw v:category=Government v:attributionLink=http://austinanimalcenter.org v:averageRating=0 v:name="2-16 to 2-22-14 Austin Animal Center Intakes" v:attribution="Austin Animal Center"

property e:db24-fcaw t:meta.view.owner v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:displayName="Austin Animal Center"

property e:db24-fcaw t:meta.view.tableauthor v:id=p3dk-w2wy v:profileImageUrlMedium=/api/users/p3dk-w2wy/profile_images/THUMB v:profileImageUrlLarge=/api/users/p3dk-w2wy/profile_images/LARGE v:screenName="Austin Animal Center" v:profileImageUrlSmall=/api/users/p3dk-w2wy/profile_images/TINY v:roleName=editor v:displayName="Austin Animal Center"
```

## Top Records

```ls
| animal_id | intake_date         | found_location                | intake_type     | intake_condition | animal_type | sex_upon_intake | age_upon_intake | breed                              | color             | 
| ========= | =================== | ============================= | =============== | ================ | =========== | =============== | =============== | ================================== | ================= | 
| A611152   | 2014-02-16T00:00:00 | Austin, TX                    | Owner Surrender | Normal           | Dog         | Neutered Male   | 3 years         | Labrador Retriever/Pointer         | Black/White       | 
| A647176   | 2014-02-16T00:00:00 | Mlk And 183 Austin, TX        | Stray           | Normal           | Dog         | Intact Female   | 2 years         | Pit Bull Mix                       | Blue Cream/White  | 
| A663480   | 2014-02-16T00:00:00 | Austin, TX                    | Owner Surrender | Normal           | Dog         | Neutered Male   | 9 months        | Labrador Retriever Mix             | Sable/Black       | 
| A672714   | 2014-02-16T00:00:00 | 10801 Old Manchaca Austin, TX | Owner Surrender | Normal           | Cat         | Intact Female   | 2 years         | American Shorthair Mix             | Black/White       | 
| A672718   | 2014-02-16T00:00:00 | 1800 Linnet Austin, TX        | Stray           | Normal           | Dog         | Intact Female   | 2 months        | Labrador Retriever Mix             | Black Smoke/Black | 
| A672741   | 2014-02-16T00:00:00 | 4106 N.Lamar Austin, TX       | Stray           | Normal           | Dog         | Intact Male     | 3 months        | Rottweiler Mix                     | Black/Tan         | 
| A672742   | 2014-02-16T00:00:00 | 4106 N. Lamar Austin, TX      | Stray           | Normal           | Dog         | Intact Female   | 1 year          | Chihuahua Shorthair Mix            | Black             | 
| A672743   | 2014-02-16T00:00:00 | 4106 N.Lamar Austin, TX       | Stray           | Normal           | Dog         | Intact Female   | 2 years         | Chihuahua Shorthair Mix            | Brown/Black       | 
| A672745   | 2014-02-16T00:00:00 | Mlk And Fm 969 Austin, TX     | Stray           | Normal           | Dog         | Spayed Female   | 2 years         | American Staffordshire Terrier Mix | White/Red         | 
| A672746   | 2014-02-16T00:00:00 | Travis, TX                    | Owner Surrender | Normal           | Dog         | Neutered Male   | 9 years         | Jack Russell Terrier Mix           | White/Black       | 
```