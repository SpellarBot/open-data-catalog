# Medical Examiner -- 2009 Manner of Death by Age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-of-death-by-age-e9b53) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9gbd-zx5t) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9gbd-zx5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9gbd-zx5t/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9gbd-zx5t |
| Name | Medical Examiner -- 2009 Manner of Death by Age |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:25:05Z |
| Publication Date | 2014-10-09T21:45:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name            | Data Type | Render Type |
| ======== | ============== | ================ | =============== | ========= | =========== |
| Yes      | series tag     | age_range_       | AGE RANGE       | text      | text        |
| Yes      | series tag     | manner_of_death_ | MANNER OF DEATH | text      | text        |
| Yes      | numeric metric | count            | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9gbd-zx5t d:2009-01-01T00:00:00.000Z t:manner_of_death_=ACCIDENT t:age_range_="UNDER 1" m:count=21

series e:9gbd-zx5t d:2009-01-01T00:00:00.000Z t:manner_of_death_=HOMICIDE t:age_range_="UNDER 1" m:count=11

series e:9gbd-zx5t d:2009-01-01T00:00:00.000Z t:manner_of_death_=NATURAL t:age_range_="UNDER 1" m:count=56
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:9gbd-zx5t l:"Medical Examiner -- 2009 Manner of Death by Age" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/9gbd-zx5t

property e:9gbd-zx5t t:meta.view v:id=9gbd-zx5t v:category=Healthcare v:averageRating=0 v:name="Medical Examiner -- 2009 Manner of Death by Age" v:attribution="Cook County Medical Examiner"

property e:9gbd-zx5t t:meta.view.license v:name="Public Domain"

property e:9gbd-zx5t t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:9gbd-zx5t t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| age_range_ | manner_of_death_ | count | 
| ========== | ================ | ===== | 
| UNDER 1    | ACCIDENT         | 21    | 
| UNDER 1    | HOMICIDE         | 11    | 
| UNDER 1    | NATURAL          | 56    | 
| UNDER 1    | REMAINS          | 41    | 
| UNDER 1    | STILL BIRTH      | 7     | 
| UNDER 1    | UNDETERMINED     | 34    | 
| 1 TO 4     | ACCIDENT         | 16    | 
| 1 TO 4     | HOMICIDE         | 9     | 
| 1 TO 4     | NATURAL          | 17    | 
| 1 TO 4     | UNDETERMINED     | 6     | 
```