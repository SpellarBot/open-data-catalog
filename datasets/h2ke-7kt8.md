# Health and Hosptials--2008 Total Outpatient Registrations By ZIP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-and-hosptials-2008-total-outpatient-registrations-by-zip-74b79) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/h2ke-7kt8) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/h2ke-7kt8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/h2ke-7kt8/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | h2ke-7kt8 |
| Name | Health and Hosptials--2008 Total Outpatient Registrations By ZIP |
| Attribution | Cook County Health and Hospitals System |
| Category | Healthcare |
| Created | 2011-10-11T20:41:04Z |
| Publication Date | 2014-10-09T21:27:55Z |

## Description

Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations.

2,330 of 2009 and 3,093 of 2008 zip code registrations are not included in this data file due to privacy concerns when 10 registrations or less occurred per zip code

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | time           | year       | Year     | text      | text        |
| Yes      | series tag     | zip_code   | ZIP Code | text      | text        |
| Yes      | numeric metric | total      | Total    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h2ke-7kt8 d:2008-01-01T00:00:00.000Z t:zip_code=60000 m:total=66

series e:h2ke-7kt8 d:2008-01-01T00:00:00.000Z t:zip_code=60149 m:total=14

series e:h2ke-7kt8 d:2008-01-01T00:00:00.000Z t:zip_code=60405 m:total=12
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:h2ke-7kt8 l:"Health and Hosptials--2008 Total Outpatient Registrations By ZIP" t:attribution="Cook County Health and Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/h2ke-7kt8

property e:h2ke-7kt8 t:meta.view v:id=h2ke-7kt8 v:category=Healthcare v:averageRating=0 v:name="Health and Hosptials--2008 Total Outpatient Registrations By ZIP" v:attribution="Cook County Health and Hospitals System"

property e:h2ke-7kt8 t:meta.view.license v:name="Public Domain"

property e:h2ke-7kt8 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:h2ke-7kt8 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | zip_code | total | 
| ==== | ======== | ===== | 
| 2008 | 60000    | 66    | 
| 2008 | 60149    | 14    | 
| 2008 | 60405    | 12    | 
| 2008 | 60427    | 46    | 
| 2008 | 60493    | 11    | 
| 2008 | 60508    | 13    | 
| 2008 | 60600    | 607   | 
| 2008 | 60627    | 617   | 
| 2008 | 60635    | 221   | 
| 2008 | 60648    | 73    | 
```