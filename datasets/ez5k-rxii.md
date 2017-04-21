# Medical Examiner--2009 Decedents, by Cause Of Death

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-decedents-by-cause-of-death-da5b3) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ez5k-rxii) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ez5k-rxii/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ez5k-rxii/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ez5k-rxii |
| Name | Medical Examiner--2009 Decedents, by Cause Of Death |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T18:48:37Z |
| Publication Date | 2014-10-27T16:43:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name           | Data Type | Render Type |
| ======== | ============== | =============== | ============== | ========= | =========== |
| Yes      | series tag     | cause_of_death_ | CAUSE OF DEATH | text      | text        |
| Yes      | numeric metric | count_          | COUNT          | number    | number      |
| Yes      | numeric metric | percent         | PERCENT        | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ez5k-rxii d:2009-01-01T00:00:00.000Z t:cause_of_death_=UNKNOWN m:percent=0.73 m:count_=38

series e:ez5k-rxii d:2009-01-01T00:00:00.000Z t:cause_of_death_="TRAUMATIC INJURY" m:percent=22.35 m:count_=1170

series e:ez5k-rxii d:2009-01-01T00:00:00.000Z t:cause_of_death_="POISONING AND TOXIC EFFECTS" m:percent=10.97 m:count_=574
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent p:float l:PERCENT t:dataTypeName=percent

entity e:ez5k-rxii l:"Medical Examiner--2009 Decedents, by Cause Of Death" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/ez5k-rxii

property e:ez5k-rxii t:meta.view v:id=ez5k-rxii v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Decedents, by Cause Of Death" v:attribution="Cook County Medical Examiner"

property e:ez5k-rxii t:meta.view.license v:name="Public Domain"

property e:ez5k-rxii t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ez5k-rxii t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| cause_of_death_               | count_ | percent | 
| ============================= | ====== | ======= | 
| UNKNOWN                       | 38     | 0.73    | 
| TRAUMATIC INJURY              | 1170   | 22.35   | 
| POISONING AND TOXIC EFFECTS   | 574    | 10.97   | 
| ASPHYXIATION                  | 257    | 4.91    | 
| BURNS                         | 13     | 0.25    | 
| ELECTROCUTION                 | 3      | 0.06    | 
| EXPOSURE AND NEGLECT          | 21     | 0.4     | 
| ALLERGY AND ADVERSE REACTIONS | 2      | 0.04    | 
| INFECTIOUS DISEASES           | 138    | 2.64    | 
| NEOPLASMS; MALIGNANT (CANCER) | 31     | 0.59    | 
```