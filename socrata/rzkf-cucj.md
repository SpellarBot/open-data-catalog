# Health & Hospitals - Outpatient Registrations, by Zip Code - 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-hospitals-outpatient-registrations-by-zip-code-2011-322b4) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/rzkf-cucj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rzkf-cucj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rzkf-cucj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | rzkf-cucj |
| Name | Health & Hospitals - Outpatient Registrations, by Zip Code - 2011 |
| Attribution | Cook County Health & Hospitals System |
| Category | Healthcare |
| Created | 2012-08-30T17:27:34Z |
| Publication Date | 2014-10-09T22:29:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                       | Data Type | Render Type |
| ======== | ============== | ===================== | ========================== | ========= | =========== |
| Yes      | series tag     | zipcode               | ZIPCODE                    | text      | text        |
| Yes      | numeric metric | ytd_through_june_2011 | 2011 YTD through June 2011 | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rzkf-cucj d:2011-01-01T00:00:00.000Z t:zipcode=60600 m:ytd_through_june_2011=70

series e:rzkf-cucj d:2011-01-01T00:00:00.000Z t:zipcode=60627 m:ytd_through_june_2011=163

series e:rzkf-cucj d:2011-01-01T00:00:00.000Z t:zipcode=60635 m:ytd_through_june_2011=58
```

## Meta Commands

```ls
metric m:ytd_through_june_2011 p:integer l:"2011 YTD through June 2011" t:dataTypeName=number

entity e:rzkf-cucj l:"Health & Hospitals - Outpatient Registrations, by Zip Code - 2011" t:attribution="Cook County Health & Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/rzkf-cucj

property e:rzkf-cucj t:meta.view v:id=rzkf-cucj v:category=Healthcare v:attributionLink=http://www.cookcountyhhs.org/ v:averageRating=0 v:name="Health & Hospitals - Outpatient Registrations, by Zip Code - 2011" v:attribution="Cook County Health & Hospitals System"

property e:rzkf-cucj t:meta.view.license v:name="Public Domain"

property e:rzkf-cucj t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:rzkf-cucj t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| zipcode | ytd_through_june_2011 | 
| ======= | ===================== | 
| 60600   | 70                    | 
| 60627   | 163                   | 
| 60635   | 58                    | 
| 60648   | 25                    | 
| 60650   | 64                    | 
| 60658   | 28                    | 
| 60663   | 16                    | 
| 60781   | 17                    | 
| 60171   | 592                   | 
| 60501   | 930                   | 
```