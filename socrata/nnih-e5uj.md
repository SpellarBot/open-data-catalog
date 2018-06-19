# Medical Examiner--2009 Decedents, by Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-2009-decedents-by-race-493fd) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nnih-e5uj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nnih-e5uj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nnih-e5uj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nnih-e5uj |
| Name | Medical Examiner--2009 Decedents, by Race |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2011-09-22T15:59:26Z |
| Publication Date | 2014-10-27T16:04:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | race_      | RACE    | text      | text        |
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
series e:nnih-e5uj d:2009-01-01T00:00:00.000Z t:race_=WHITE m:count_=2965 m:percent_=56.65

series e:nnih-e5uj d:2009-01-01T00:00:00.000Z t:race_=BLACK m:count_=2169 m:percent_=41.44

series e:nnih-e5uj d:2009-01-01T00:00:00.000Z t:race_=OTHER m:count_=100 m:percent_=1.91
```

## Meta Commands

```ls
metric m:count_ p:integer l:COUNT t:dataTypeName=number

metric m:percent_ p:float l:PERCENT t:dataTypeName=percent

entity e:nnih-e5uj l:"Medical Examiner--2009 Decedents, by Race" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/nnih-e5uj

property e:nnih-e5uj t:meta.view v:id=nnih-e5uj v:category=Healthcare v:averageRating=0 v:name="Medical Examiner--2009 Decedents, by Race" v:attribution="Cook County Medical Examiner"

property e:nnih-e5uj t:meta.view.license v:name="Public Domain"

property e:nnih-e5uj t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nnih-e5uj t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| race_ | count_ | percent_ | 
| ===== | ====== | ======== | 
| WHITE | 2965   | 56.65    | 
| BLACK | 2169   | 41.44    | 
| OTHER | 100    | 1.91     | 
```