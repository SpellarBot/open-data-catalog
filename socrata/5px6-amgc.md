# Medical Examiner--2009 Deaths, by Gender, Age, and Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-deaths-by-gender-age-and-race-d7551) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/5px6-amgc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5px6-amgc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5px6-amgc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 5px6-amgc |
| Name | Medical Examiner--2009 Deaths, by Gender, Age, and Race |
| Attribution | Cook County Medical Examiner |
| Category | Finance & Administration |
| Created | 2011-10-24T17:13:07Z |
| Publication Date | 2014-10-27T16:40:15Z |

## Description

Updated 10/24/2011. From the Medical Examiner's 2009 Annual Report, deaths of autopsied people by gender, age range and race.

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | series tag     | sex_       | SEX   | text      | text        |
| Yes      | series tag     | age_       | AGE   | text      | text        |
| Yes      | series tag     | race_      | RACE  | text      | text        |
| Yes      | numeric metric | count      | COUNT | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5px6-amgc d:2009-01-01T00:00:00.000Z t:race_=WHITE t:age_="UNDER 1" t:sex_=MALE m:count=27

series e:5px6-amgc d:2009-01-01T00:00:00.000Z t:race_=BLACK t:age_="UNDER 1" t:sex_=MALE m:count=45

series e:5px6-amgc d:2009-01-01T00:00:00.000Z t:race_=UNKNOWN t:age_="UNDER 1" t:sex_=MALE m:count=1
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:5px6-amgc l:"Medical Examiner--2009 Deaths, by Gender, Age, and Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/5px6-amgc

property e:5px6-amgc t:meta.view v:id=5px6-amgc v:category="Finance & Administration" v:averageRating=0 v:name="Medical Examiner--2009 Deaths, by Gender, Age, and Race" v:attribution="Cook County Medical Examiner"

property e:5px6-amgc t:meta.view.license v:name="Public Domain"

property e:5px6-amgc t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:5px6-amgc t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| sex_ | age_     | race_   | count | 
| ==== | ======== | ======= | ===== | 
| MALE | UNDER 1  | WHITE   | 27    | 
| MALE | UNDER 1  | BLACK   | 45    | 
| MALE | UNDER 1  | UNKNOWN | 1     | 
| MALE | 1 TO 4   | WHITE   | 10    | 
| MALE | 1 TO 4   | BLACK   | 14    | 
| MALE | 1 TO 4   | ASIAN   | 1     | 
| MALE | 5 TO 9   | WHITE   | 3     | 
| MALE | 5 TO 9   | BLACK   | 4     | 
| MALE | 10 TO 14 | WHITE   | 7     | 
| MALE | 10 TO 14 | BLACK   | 13    | 
```