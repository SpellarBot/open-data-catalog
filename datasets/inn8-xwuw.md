# Medical Examiner--2009 Manner Death, by Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-manner-death-by-race-44a00) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/inn8-xwuw) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/inn8-xwuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/inn8-xwuw/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | inn8-xwuw |
| Name | Medical Examiner--2009 Manner Death, by Race |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:09:04Z |
| Publication Date | 2014-10-27T16:43:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | manner_of_death | MANNER OF DEATH | text      | text        |
| Yes      | series tag     | race_           | RACE            | text      | text        |
| Yes      | numeric metric | count           | COUNT           | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:inn8-xwuw d:2009-01-01T00:00:00.000Z t:race_=WHITE t:manner_of_death=ACCIDENT m:count=916

series e:inn8-xwuw d:2009-01-01T00:00:00.000Z t:race_=BLACK t:manner_of_death=ACCIDENT m:count=493

series e:inn8-xwuw d:2009-01-01T00:00:00.000Z t:race_=OTHER t:manner_of_death=ACCIDENT m:count=25
```

## Meta Commands

```ls
metric m:count p:integer l:COUNT t:dataTypeName=number

entity e:inn8-xwuw l:"Medical Examiner--2009 Manner Death, by Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/inn8-xwuw

property e:inn8-xwuw t:meta.view v:id=inn8-xwuw v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Manner Death, by Race" v:attribution="Cook County Medical Examiner"

property e:inn8-xwuw t:meta.view.license v:name="Public Domain"

property e:inn8-xwuw t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:inn8-xwuw t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| manner_of_death | race_ | count | 
| =============== | ===== | ===== | 
| ACCIDENT        | WHITE | 916   | 
| ACCIDENT        | BLACK | 493   | 
| ACCIDENT        | OTHER | 25    | 
| HOMICIDE        | WHITE | 176   | 
| HOMICIDE        | BLACK | 450   | 
| HOMICIDE        | OTHER | 4     | 
| NATURAL         | WHITE | 1475  | 
| NATURAL         | BLACK | 1123  | 
| NATURAL         | OTHER | 22    | 
| REMAINS         | WHITE | 1     | 
```