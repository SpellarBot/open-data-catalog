# Medical Examiner--2009 Age Of Decendents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-age-of-decendents-10c5d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/frpz-jtq8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/frpz-jtq8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/frpz-jtq8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | frpz-jtq8 |
| Name | Medical Examiner--2009 Age Of Decendents |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-21T21:05:28Z |
| Publication Date | 2014-10-27T16:39:47Z |

## Description

From the 2009 Medical Examiner's Annual Report, the age of each decedent in 2009.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | age_of_decedent | AGE OF DECEDENT | text      | text        |
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
series e:frpz-jtq8 d:2009-01-01T00:00:00.000Z t:age_of_decedent="UNDER 1" m:count_=170 m:percent_=3.25

series e:frpz-jtq8 d:2009-01-01T00:00:00.000Z t:age_of_decedent="1 to 4" m:count_=48 m:percent_=0.92

series e:frpz-jtq8 d:2009-01-01T00:00:00.000Z t:age_of_decedent="5 to 9" m:count_=18 m:percent_=0.34
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:frpz-jtq8 l:"Medical Examiner--2009 Age Of Decendents" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/frpz-jtq8

property e:frpz-jtq8 t:meta.view v:id=frpz-jtq8 v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Age Of Decendents" v:attribution="Cook County Medical Examiner"

property e:frpz-jtq8 t:meta.view.license v:name="Public Domain"

property e:frpz-jtq8 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:frpz-jtq8 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| age_of_decedent | count_ | percent_ | 
| =============== | ====== | ======== | 
| UNDER 1         | 170    | 3.25     | 
| 1 to 4          | 48     | 0.92     | 
| 5 to 9          | 18     | 0.34     | 
| 10 to 14        | 28     | 0.53     | 
| 15 to 19        | 181    | 3.46     | 
| 20 to 24        | 303    | 5.79     | 
| 25 to 29        | 312    | 5.96     | 
| 30 to 34        | 268    | 5.12     | 
| 35 to 39        | 307    | 5.87     | 
| 40 to 44        | 353    | 6.74     | 
```