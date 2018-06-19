# Medical Examiner--2009 Manner Of Death, by Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-of-death-by-type-42b76) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kmuq-337u) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kmuq-337u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kmuq-337u/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kmuq-337u |
| Name | Medical Examiner--2009 Manner Of Death, by Type |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T16:06:50Z |
| Publication Date | 2014-10-27T16:42:08Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manner_of_death | MANNER OF DEATH | text      | text        |
| Yes      | numeric metric | count_          | COUNT           | number    | number      |
| Yes      | numeric metric | percent_        | PERCENT         | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kmuq-337u d:2009-01-01T00:00:00.000Z t:manner_of_death=ACCIDENT m:count_=1434 m:percent_=27.4

series e:kmuq-337u d:2009-01-01T00:00:00.000Z t:manner_of_death=HOMICIDE m:count_=630 m:percent_=12.04

series e:kmuq-337u d:2009-01-01T00:00:00.000Z t:manner_of_death=NATURAL m:count_=2620 m:percent_=50.06
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:kmuq-337u l:"Medical Examiner--2009 Manner Of Death, by Type" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/kmuq-337u

property e:kmuq-337u t:meta.view v:id=kmuq-337u v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Manner Of Death, by Type" v:attribution="Cook County Medical Examiner"

property e:kmuq-337u t:meta.view.license v:name="Public Domain"

property e:kmuq-337u t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:kmuq-337u t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| manner_of_death | count_ | percent_ | 
| =============== | ====== | ======== | 
| ACCIDENT        | 1434   | 27.4     | 
| HOMICIDE        | 630    | 12.04    | 
| NATURAL         | 2620   | 50.06    | 
| REMAINS         | 41     | 0.78     | 
| STILL BIRTH     | 7      | 0.13     | 
| SUICIDE         | 407    | 7.78     | 
| UNDETERMINED    | 95     | 1.82     | 
```