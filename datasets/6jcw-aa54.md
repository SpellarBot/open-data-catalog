# Medical Examiner--2009 Manner Death, by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-death-by-gender-a77be) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6jcw-aa54 |
| Name | Medical Examiner--2009 Manner Death, by Gender |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:22:24Z |
| Publication Date | 2014-10-27T16:38:44Z |
| Rows Updated | 2014-10-27T16:38:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manner_of_death | MANNER OF DEATH | text      | text        |
| Yes      | series tag     | sex_            | SEX             | text      | text        |
| Yes      | numeric metric | count           | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6jcw-aa54 d:2009-01-01T00:00:00.000Z t:manner_of_death=ACCIDENT t:sex_=MALE m:count=995

series e:6jcw-aa54 d:2009-01-01T00:00:00.000Z t:manner_of_death=ACCIDENT t:sex_=FEMALE m:count=439

series e:6jcw-aa54 d:2009-01-01T00:00:00.000Z t:manner_of_death=HOMICIDE t:sex_=MALE m:count=535
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:6jcw-aa54 l:"Medical Examiner--2009 Manner Death, by Gender" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/6jcw-aa54

property e:6jcw-aa54 t:meta.view v:id=6jcw-aa54 v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Manner Death, by Gender" v:attribution="Cook County Medical Examiner"

property e:6jcw-aa54 t:meta.view.license v:name="Public Domain"

property e:6jcw-aa54 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6jcw-aa54 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```