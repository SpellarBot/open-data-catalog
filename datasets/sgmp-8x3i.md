# Health & Hospitals System - Outpatient Registrations, by Month and ZIP Code - Fiscal Year 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-hospitals-system-outpatient-registrations-by-month-and-zip-code-fiscal-year-2008-93bf7) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/sgmp-8x3i) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/sgmp-8x3i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/sgmp-8x3i/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | sgmp-8x3i |
| Name | Health & Hospitals System - Outpatient Registrations, by Month and ZIP Code - Fiscal Year 2008 |
| Attribution | Cook County Health & Hospitals System |
| Category | Healthcare |
| Created | 2011-10-11T21:02:24Z |
| Publication Date | 2014-10-09T22:13:02Z |

## Description

Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations.

2,330 of 2009 and 3,093 of 2008 zip code registrations are not included in this data file due to privacy concerns when 10 registrations or less occurred per zip code

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
series e:sgmp-8x3i d:2008-01-01T00:00:00.000Z t:zip_code=00676 m:total=60 m:may=3 m:apr=5 m:oct=11 m:nov=9 m:jul=9 m:sep=9 m:jun=5 m:aug=9

series e:sgmp-8x3i d:2008-01-01T00:00:00.000Z t:zip_code=60021 m:total=13 m:may=1 m:apr=1 m:oct=2 m:nov=2 m:sep=4 m:mar=2 m:aug=1

series e:sgmp-8x3i d:2008-01-01T00:00:00.000Z t:zip_code=60149 m:total=14 m:may=5 m:apr=3 m:oct=2 m:nov=1 m:jun=1 m:aug=2
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

entity e:sgmp-8x3i l:"Health & Hospitals System - Outpatient Registrations, by Month and ZIP Code - Fiscal Year 2008" t:attribution="Cook County Health & Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/sgmp-8x3i

property e:sgmp-8x3i t:meta.view v:id=sgmp-8x3i v:category=Healthcare v:attributionLink=http://www.cookcountyhhs.org/ v:averageRating=0 v:name="Health & Hospitals System - Outpatient Registrations, by Month and ZIP Code - Fiscal Year 2008" v:attribution="Cook County Health & Hospitals System"

property e:sgmp-8x3i t:meta.view.license v:name="Public Domain"

property e:sgmp-8x3i t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:sgmp-8x3i t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | zip_code | dec | jan | feb | mar | apr | may | jun | jul | aug | sep | oct | nov | total | 
| ==== | ======== | === | === | === | === | === | === | === | === | === | === | === | === | ===== | 
| 2008 | 00676    |     |     |     |     | 5   | 3   | 5   | 9   | 9   | 9   | 11  | 9   | 60    | 
| 2008 | 60021    |     |     |     | 2   | 1   | 1   |     |     | 1   | 4   | 2   | 2   | 13    | 
| 2008 | 60149    |     |     |     |     | 3   | 5   | 1   |     | 2   |     | 2   | 1   | 14    | 
| 2008 |          | 399 | 398 | 465 | 459 | 300 | 307 | 326 | 300 | 338 | 300 | 288 | 274 | 4154  | 
| 2008 | 00000    | 35  | 41  | 50  | 58  | 46  | 75  | 53  | 75  | 107 | 83  | 68  | 37  | 728   | 
| 2008 | 06052    | 2   |     |     | 2   | 1   |     |     | 3   |     |     | 1   | 2   | 11    | 
| 2008 | 10536    | 5   | 3   | 2   | 5   | 6   | 3   |     |     |     |     |     |     | 24    | 
| 2008 | 24637    | 2   | 3   | 1   | 4   | 4   | 2   | 1   |     |     |     |     |     | 17    | 
| 2008 | 30341    |     | 4   | 3   | 3   | 1   | 2   | 2   | 1   | 2   |     |     |     | 18    | 
| 2008 | 38701    |     |     |     |     | 1   | 3   | 1   | 3   | 2   | 2   |     |     | 12    | 
```