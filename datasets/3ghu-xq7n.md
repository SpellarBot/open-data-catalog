# Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-hospitals-system-outpatient-registrations-by-zip-fiscal-year-2011-incomplete-73b93) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3ghu-xq7n |
| Name | Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Health & Hospitals System |
| Category | Healthcare |
| Created | 2011-09-19T21:13:30Z |
| Publication Date | 2014-10-09T20:54:42Z |
| Rows Updated | 2014-10-09T20:54:30Z |

## Description

Data for 2011 through June 2011. Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                       | Data Type | Render Type |
| ======== | ============== | ===================== | ========================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | zipcode               | ZIPCODE                    | text      | text        |
| Yes      | numeric metric | ytd_through_june_2011 | 2011 YTD through June 2011 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3ghu-xq7n d:2011-09-19T14:13:32.000Z t:zipcode=60600 m:ytd_through_june_2011=70

series e:3ghu-xq7n d:2011-09-19T14:13:32.000Z t:zipcode=60627 m:ytd_through_june_2011=125

series e:3ghu-xq7n d:2011-09-19T14:13:32.000Z t:zipcode=60635 m:ytd_through_june_2011=46
```

## Meta Commands

```ls
metric m:ytd_through_june_2011 p:integer l:"2011 YTD through June 2011" t:dataTypeName=number

entity e:3ghu-xq7n l:"Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete" t:attribution="Cook County Health & Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n

property e:3ghu-xq7n t:meta.view v:id=3ghu-xq7n v:category=Healthcare v:attributionLink=http://www.cookcountyhhs.org/ v:averageRating=0 v:name="Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete" v:attribution="Cook County Health & Hospitals System"

property e:3ghu-xq7n t:meta.view.license v:name="Public Domain"

property e:3ghu-xq7n t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:3ghu-xq7n t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```