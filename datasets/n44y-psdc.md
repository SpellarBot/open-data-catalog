# Medical Examiner--2009 Manner Death By Gender, Age, and Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-death-by-gender-age-and-race-5d0a0) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/n44y-psdc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/n44y-psdc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/n44y-psdc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | n44y-psdc |
| Name | Medical Examiner--2009 Manner Death By Gender, Age, and Race |
| Attribution | Cook County Medical Examiner |
| Category | Finance & Administration |
| Created | 2011-10-24T17:00:35Z |
| Publication Date | 2014-10-27T16:42:50Z |

## Description

Updated 10/24/2011. From the Medical Examiner's 2009 Annual Report, the manner of death of autopsied people, by age, race, and gender

## Columns

```ls
| Included | Schema Type    | Field Name       | Name            | Data Type | Render Type |
| ======== | ============== | ================ | =============== | ========= | =========== |
| Yes      | series tag     | manner_of_death_ | MANNER OF DEATH | text      | text        |
| Yes      | series tag     | sex_             | SEX             | text      | text        |
| Yes      | series tag     | age_             | AGE             | text      | text        |
| Yes      | series tag     | race_            | RACE            | text      | text        |
| Yes      | numeric metric | count            | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n44y-psdc d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death_=ACCIDENT t:age_="UNDER 1" t:sex_=MALE m:count=4

series e:n44y-psdc d:2009-01-01T00:00:00.000Z t:race_=BLACK t:manner_of_death_=ACCIDENT t:age_="UNDER 1" t:sex_=MALE m:count=7

series e:n44y-psdc d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death_=ACCIDENT t:age_="1 TO 4" t:sex_=MALE m:count=4
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:n44y-psdc l:"Medical Examiner--2009 Manner Death By Gender, Age, and Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/n44y-psdc

property e:n44y-psdc t:meta.view v:id=n44y-psdc v:category="Finance & Administration" v:averageRating=0 v:name="Medical Examiner--2009 Manner Death By Gender, Age, and Race" v:attribution="Cook County Medical Examiner"

property e:n44y-psdc t:meta.view.license v:name="Public Domain"

property e:n44y-psdc t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:n44y-psdc t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| manner_of_death_ | sex_ | age_     | race_ | count | 
| ================ | ==== | ======== | ===== | ===== | 
| ACCIDENT         | MALE | UNDER 1  | WHITE | 4     | 
| ACCIDENT         | MALE | UNDER 1  | BLACK | 7     | 
| ACCIDENT         | MALE | 1 TO 4   | WHITE | 4     | 
| ACCIDENT         | MALE | 1 TO 4   | BLACK | 5     | 
| ACCIDENT         | MALE | 5 TO 9   | WHITE | 2     | 
| ACCIDENT         | MALE | 5 TO 9   | BLACK | 1     | 
| ACCIDENT         | MALE | 10 TO 14 | WHITE | 1     | 
| ACCIDENT         | MALE | 10 TO 14 | BLACK | 6     | 
| ACCIDENT         | MALE | 15 TO 19 | WHITE | 16    | 
| ACCIDENT         | MALE | 15 TO 19 | BLACK | 7     | 
```