# Health & Hospitals System - Outpatient Registrations, by Facility, Zip Code, Month - Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-hospitals-system-outpatient-registrations-by-facility-zip-code-month-fiscal-year-20-96b55) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wege-aen9) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wege-aen9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wege-aen9/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wege-aen9 |
| Name | Health & Hospitals System - Outpatient Registrations, by Facility, Zip Code, Month - Fiscal Year 2011 |
| Attribution | Cook County Health & Hospitals System |
| Category | Healthcare |
| Created | 2012-01-26T17:25:31Z |
| Publication Date | 2014-10-09T21:21:01Z |

## Description

Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | facility   | FACILITY  | text      | text        |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | total      | TOTAL     | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wege-aen9 d:2011-01-01T00:00:00.000Z t:facility="John H. Stroger Hospital" m:total=13 m:december=2 m:may=1 m:november=0 m:march=4 m:april=3 m:february=2 m:june=0 m:january=0 m:august=0 m:july=0 m:october=0 m:september=1

series e:wege-aen9 d:2011-01-01T00:00:00.000Z t:facility="John H. Stroger Hospital" m:total=91 m:december=12 m:may=19 m:november=0 m:march=10 m:april=22 m:february=5 m:june=2 m:january=18 m:august=2 m:july=0 m:october=1 m:september=0

series e:wege-aen9 d:2011-01-01T00:00:00.000Z t:facility="John H. Stroger Hospital" m:total=20 m:december=2 m:may=2 m:november=0 m:march=7 m:april=4 m:february=2 m:june=0 m:january=1 m:august=0 m:july=0 m:october=1 m:september=1
```

## Meta Commands

```ls
metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:total p:integer l:TOTAL t:dataTypeName=number

entity e:wege-aen9 l:"Health & Hospitals System - Outpatient Registrations, by Facility, Zip Code, Month - Fiscal Year 2011" t:attribution="Cook County Health & Hospitals System" t:url=https://datacatalog.cookcountyil.gov/api/views/wege-aen9

property e:wege-aen9 t:meta.view v:id=wege-aen9 v:category=Healthcare v:averageRating=0 v:name="Health & Hospitals System - Outpatient Registrations, by Facility, Zip Code, Month - Fiscal Year 2011" v:attribution="Cook County Health & Hospitals System"

property e:wege-aen9 t:meta.view.license v:name="Public Domain"

property e:wege-aen9 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:wege-aen9 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| facility                 | december | january | february | march | april | may | june | july | august | september | october | november | total | 
| ======================== | ======== | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ===== | 
| John H. Stroger Hospital | 2        | 0       | 2        | 4     | 3     | 1   | 0    | 0    | 0      | 1         | 0       | 0        | 13    | 
| John H. Stroger Hospital | 12       | 18      | 5        | 10    | 22    | 19  | 2    | 0    | 2      | 0         | 1       | 0        | 91    | 
| John H. Stroger Hospital | 2        | 1       | 2        | 7     | 4     | 2   | 0    | 0    | 0      | 1         | 1       | 0        | 20    | 
| Provident Hospital       | 3        | 8       | 3        | 2     | 1     | 6   | 1    | 1    | 1      | 0         | 0       | 0        | 26    | 
| John H. Stroger Hospital | 29       | 25      | 15       | 23    | 23    | 38  | 2    | 2    | 3      | 1         | 4       | 2        | 167   | 
| John H. Stroger Hospital | 1        | 4       | 1        | 1     | 5     | 2   | 0    | 0    | 0      | 0         | 0       | 0        | 14    | 
| John H. Stroger Hospital | 7        | 11      | 11       | 13    | 8     | 8   | 2    | 0    | 1      | 0         | 2       | 1        | 64    | 
| John H. Stroger Hospital | 4        | 7       | 3        | 2     | 3     | 11  | 0    | 0    | 0      | 0         | 0       | 0        | 30    | 
| John H. Stroger Hospital | 18       | 16      | 16       | 18    | 10    | 10  | 0    | 1    | 0      | 0         | 3       | 3        | 95    | 
| John H. Stroger Hospital | 4        | 2       | 12       | 6     | 4     | 4   | 0    | 0    | 0      | 0         | 0       | 0        | 32    | 
```