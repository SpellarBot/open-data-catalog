# Health and Hospitals System-2009 Total Outpatient Registrations By ZIP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-and-hospitals-system-2009-total-outpatient-registrations-by-zip-59518) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/c62y-v8ri) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c62y-v8ri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c62y-v8ri/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | c62y-v8ri |
| Name | Health and Hospitals System-2009 Total Outpatient Registrations By ZIP |
| Attribution | Cook County Health and Hospitals System |
| Category | Healthcare |
| Created | 2011-10-11T20:54:35Z |
| Publication Date | 2014-10-09T21:08:53Z |

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
series e:c62y-v8ri d:2009-01-01T00:00:00.000Z t:zip_code=06501 m:total=42

series e:c62y-v8ri d:2009-01-01T00:00:00.000Z t:zip_code=60000 m:total=37

series e:c62y-v8ri d:2009-01-01T00:00:00.000Z t:zip_code=60063 m:total=11
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:c62y-v8ri l:"Health and Hospitals System-2009 Total Outpatient Registrations By ZIP" t:attribution="Cook County Health and Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/c62y-v8ri

property e:c62y-v8ri t:meta.view v:id=c62y-v8ri v:category=Healthcare v:averageRating=0 v:name="Health and Hospitals System-2009 Total Outpatient Registrations By ZIP" v:attribution="Cook County Health and Hospitals System"

property e:c62y-v8ri t:meta.view.license v:name="Public Domain"

property e:c62y-v8ri t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:c62y-v8ri t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | zip_code | total | 
| ==== | ======== | ===== | 
| 2009 | 06501    | 42    | 
| 2009 | 60000    | 37    | 
| 2009 | 60063    | 11    | 
| 2009 | 60405    | 30    | 
| 2009 | 60418    | 11    | 
| 2009 | 60427    | 18    | 
| 2009 | 60547    | 13    | 
| 2009 | 60600    | 239   | 
| 2009 | 60627    | 448   | 
| 2009 | 60635    | 129   | 
```