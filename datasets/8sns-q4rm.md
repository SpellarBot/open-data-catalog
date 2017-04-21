# Health & Hospitals System - Outpatient Registrations, by Month, by ZIP - Fiscal Year 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-hospitals-system-outpatient-registrations-by-month-by-zip-fiscal-year-2009-60399) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8sns-q4rm) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8sns-q4rm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8sns-q4rm/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8sns-q4rm |
| Name | Health & Hospitals System - Outpatient Registrations, by Month, by ZIP - Fiscal Year 2009 |
| Attribution | Cook County Health & Hospitals System |
| Category | Healthcare |
| Created | 2011-10-11T21:15:42Z |
| Publication Date | 2014-10-09T21:43:31Z |

## Description

Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations.

2,330 of 2009 and 3,093 of 2008 zip code registrations are not included in this data file due to privacy concerns when 10 registrations or less occurred per zip code.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | time           | year       | Year     | text      | text        |
| Yes      | series tag     | zip_code   | ZIP CODE | text      | text        |
| Yes      | numeric metric | dec        | Dec      | number    | number      |
| Yes      | numeric metric | jan        | Jan      | number    | number      |
| Yes      | numeric metric | feb        | Feb      | number    | number      |
| Yes      | numeric metric | mar        | Mar      | number    | number      |
| Yes      | numeric metric | apr        | Apr      | number    | number      |
| Yes      | numeric metric | may        | May      | number    | number      |
| Yes      | numeric metric | jun        | Jun      | number    | number      |
| Yes      | numeric metric | jul        | Jul      | number    | number      |
| Yes      | numeric metric | aug        | Aug      | number    | number      |
| Yes      | numeric metric | sep        | Sep      | number    | number      |
| Yes      | numeric metric | oct        | Oct      | number    | number      |
| Yes      | numeric metric | nov        | Nov      | number    | number      |
| Yes      | numeric metric | total      | Total    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8sns-q4rm d:2009-01-01T00:00:00.000Z m:total=4212 m:may=462 m:apr=333 m:dec=286 m:oct=238 m:feb=299 m:nov=277 m:jul=525 m:sep=237 m:jun=472 m:mar=334 m:jan=327 m:aug=422

series e:8sns-q4rm d:2009-01-01T00:00:00.000Z t:zip_code=00000 m:total=410 m:may=30 m:apr=51 m:dec=36 m:oct=31 m:feb=41 m:nov=25 m:jul=33 m:sep=21 m:jun=22 m:mar=58 m:jan=45 m:aug=17

series e:8sns-q4rm d:2009-01-01T00:00:00.000Z t:zip_code=06062 m:total=13 m:apr=3 m:oct=1 m:nov=3 m:jun=1 m:jan=1 m:aug=4
```

## Meta Commands

```ls
metric m:dec p:integer l:Dec t:dataTypeName=number

metric m:jan p:integer l:Jan t:dataTypeName=number

metric m:feb p:integer l:Feb t:dataTypeName=number

metric m:mar p:integer l:Mar t:dataTypeName=number

metric m:apr p:integer l:Apr t:dataTypeName=number

metric m:may p:integer l:May t:dataTypeName=number

metric m:jun p:integer l:Jun t:dataTypeName=number

metric m:jul p:integer l:Jul t:dataTypeName=number

metric m:aug p:integer l:Aug t:dataTypeName=number

metric m:sep p:integer l:Sep t:dataTypeName=number

metric m:oct p:integer l:Oct t:dataTypeName=number

metric m:nov p:integer l:Nov t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:8sns-q4rm l:"Health & Hospitals System - Outpatient Registrations, by Month, by ZIP - Fiscal Year 2009" t:attribution="Cook County Health & Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/8sns-q4rm

property e:8sns-q4rm t:meta.view v:id=8sns-q4rm v:category=Healthcare v:attributionLink=http://www.cookcountyhhs.org/ v:averageRating=0 v:name="Health & Hospitals System - Outpatient Registrations, by Month, by ZIP - Fiscal Year 2009" v:attribution="Cook County Health & Hospitals System"

property e:8sns-q4rm t:meta.view.license v:name="Public Domain"

property e:8sns-q4rm t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:8sns-q4rm t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | zip_code | dec | jan | feb | mar | apr | may | jun | jul | aug | sep | oct | nov | total | 
| ==== | ======== | === | === | === | === | === | === | === | === | === | === | === | === | ===== | 
| 2009 |          | 286 | 327 | 299 | 334 | 333 | 462 | 472 | 525 | 422 | 237 | 238 | 277 | 4212  | 
| 2009 | 00000    | 36  | 45  | 41  | 58  | 51  | 30  | 22  | 33  | 17  | 21  | 31  | 25  | 410   | 
| 2009 | 06062    |     | 1   |     |     | 3   |     | 1   |     | 4   |     | 1   | 3   | 13    | 
| 2009 | 06501    |     | 4   | 6   | 12  | 8   | 2   | 1   |     |     | 4   | 2   | 3   | 42    | 
| 2009 | 11209    | 2   | 6   | 3   | 1   | 4   | 3   | 1   | 1   |     |     |     |     | 21    | 
| 2009 | 22902    | 2   | 1   | 3   | 2   | 2   | 1   |     |     |     |     |     |     | 11    | 
| 2009 | 30108    |     | 1   | 2   |     |     | 2   | 1   |     |     | 2   | 2   | 2   | 12    | 
| 2009 | 46307    | 3   | 6   | 2   | 3   | 1   | 3   |     |     | 1   | 4   | 1   | 1   | 25    | 
| 2009 | 46312    | 26  | 17  | 10  | 16  | 24  | 16  | 13  | 18  | 21  | 22  | 20  | 17  | 220   | 
| 2009 | 46319    | 1   | 3   | 2   | 1   | 3   | 5   | 5   | 5   | 7   | 1   | 4   | 4   | 41    | 
```