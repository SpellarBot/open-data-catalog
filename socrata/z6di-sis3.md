# Medical Examiner--2009 Manner By Gender, and Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-by-gender-and-race-fe0a7) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/z6di-sis3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z6di-sis3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z6di-sis3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | z6di-sis3 |
| Name | Medical Examiner--2009 Manner By Gender, and Race |
| Attribution | Cook County Medical Examiner |
| Category | Finance & Administration |
| Created | 2011-10-24T17:08:05Z |
| Publication Date | 2014-10-27T16:04:22Z |

## Description

Updated 10/24/2011. From the 2009 Medical Examiner's Annual Report, the manner of of death of autopsied people by gender and race.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name            | Data Type | Render Type |
| ======== | ============== | ================ | =============== | ========= | =========== |
| Yes      | series tag     | race_            | RACE            | text      | text        |
| Yes      | series tag     | sex_             | SEX             | text      | text        |
| Yes      | series tag     | manner_of_death_ | MANNER OF DEATH | text      | text        |
| Yes      | numeric metric | count_           | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:z6di-sis3 d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death_=ACCIDENT t:sex_=MALE m:count_=642

series e:z6di-sis3 d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death_=HOMICIDE t:sex_=MALE m:count_=141

series e:z6di-sis3 d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death_=NATURAL t:sex_=MALE m:count_=1040
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

entity e:z6di-sis3 l:"Medical Examiner--2009 Manner By Gender, and Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/z6di-sis3

property e:z6di-sis3 t:meta.view v:id=z6di-sis3 v:category="Finance & Administration" v:averageRating=0 v:name="Medical Examiner--2009 Manner By Gender, and Race" v:attribution="Cook County Medical Examiner"

property e:z6di-sis3 t:meta.view.license v:name="Public Domain"

property e:z6di-sis3 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:z6di-sis3 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| race_ | sex_   | manner_of_death_ | count_ | 
| ===== | ====== | ================ | ====== | 
| WHITE | MALE   | ACCIDENT         | 642    | 
| WHITE | MALE   | HOMICIDE         | 141    | 
| WHITE | MALE   | NATURAL          | 1040   | 
| WHITE | MALE   | STILL BIRTH      | 1      | 
| WHITE | MALE   | SUICIDE          | 257    | 
| WHITE | MALE   | UNDETERMINED     | 35     | 
| WHITE | FEMALE | ACCIDENT         | 274    | 
| WHITE | FEMALE | HOMICIDE         | 35     | 
| WHITE | FEMALE | NATURAL          | 435    | 
| WHITE | FEMALE | STILL BIRTH      | 1      | 
```