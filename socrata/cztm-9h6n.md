# Medical Examiner--2009 Decedents, by Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-decedents-by-race-83b99) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cztm-9h6n) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cztm-9h6n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cztm-9h6n/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cztm-9h6n |
| Name | Medical Examiner--2009 Decedents, by Race |
| Attribution | Cook County Medical Examiner |
| Category | Finance & Administration |
| Created | 2011-10-24T17:51:46Z |
| Publication Date | 2014-10-27T16:41:31Z |

## Description

Updated 10/24/2011. From the 2009 Medical Examiner's Annual Report. Race of autopsied people.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | race_      | RACE    | text      | text        |
| Yes      | numeric metric | count_     | COUNT   | number    | number      |
| Yes      | numeric metric | percent_   | PERCENT | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cztm-9h6n d:2009-01-01T00:00:00.000Z t:race_=WHITE m:count_=2965 m:percent_=56.65

series e:cztm-9h6n d:2009-01-01T00:00:00.000Z t:race_=BLACK m:count_=2169 m:percent_=41.44

series e:cztm-9h6n d:2009-01-01T00:00:00.000Z t:race_="AMER. IND" m:count_=6 m:percent_=0.11
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=number

entity e:cztm-9h6n l:"Medical Examiner--2009 Decedents, by Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/cztm-9h6n

property e:cztm-9h6n t:meta.view v:id=cztm-9h6n v:category="Finance & Administration" v:averageRating=0 v:name="Medical Examiner--2009 Decedents, by Race" v:attribution="Cook County Medical Examiner"

property e:cztm-9h6n t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:cztm-9h6n t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| race_     | count_ | percent_ | 
| ========= | ====== | ======== | 
| WHITE     | 2965   | 56.65    | 
| BLACK     | 2169   | 41.44    | 
| AMER. IND | 6      | 0.11     | 
| FILIPINO  | 17     | 0.32     | 
| INDIAN    | 4      | 0.08     | 
| ORIENTAL  | 31     | 0.59     | 
| UNKNOWN   | 42     | 0.8      | 
```