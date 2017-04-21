# Medical Examiner -- 2009 Deaths by Gender of Decedent

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-deaths-by-gender-of-decedent-dffd1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xbrr-cj6t) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xbrr-cj6t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xbrr-cj6t/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xbrr-cj6t |
| Name | Medical Examiner -- 2009 Deaths by Gender of Decedent |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T17:34:25Z |
| Publication Date | 2014-10-09T22:32:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | sex_       | SEX     | text      | text        |
| Yes      | numeric metric | count_     | COUNT   | number    | number      |
| Yes      | numeric metric | percent_   | PERCENT | percent   | percent     |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xbrr-cj6t d:2009-01-01T00:00:00.000Z t:sex_=MALE m:count_=3700 m:percent_=70.69

series e:xbrr-cj6t d:2009-01-01T00:00:00.000Z t:sex_=FEMALE m:count_=1492 m:percent_=28.51

series e:xbrr-cj6t d:2009-01-01T00:00:00.000Z t:sex_=UNKNOWN m:count_=42 m:percent_=0.8
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:xbrr-cj6t l:"Medical Examiner -- 2009 Deaths by Gender of Decedent" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/xbrr-cj6t

property e:xbrr-cj6t t:meta.view v:id=xbrr-cj6t v:category=Healthcare v:averageRating=0 v:name="Medical Examiner -- 2009 Deaths by Gender of Decedent" v:attribution="Cook County Medical Examiner"

property e:xbrr-cj6t t:meta.view.license v:name="Public Domain"

property e:xbrr-cj6t t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:xbrr-cj6t t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| sex_    | count_ | percent_ | 
| ======= | ====== | ======== | 
| MALE    | 3700   | 70.69    | 
| FEMALE  | 1492   | 28.51    | 
| UNKNOWN | 42     | 0.8      | 
```