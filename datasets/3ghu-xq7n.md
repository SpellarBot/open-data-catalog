# Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/health-hospitals-system-outpatient-registrations-by-zip-fiscal-year-2011-incomplete-73b93)
* [Metadata URL](https://datacatalog.cookcountyil.gov/api/views/3ghu-xq7n)
* Id = 3ghu-xq7n
* Name = Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete
* Attribution = Cook County Health & Hospitals System
* [Attribution Link](http://www.cookcountyhhs.org/)
* Category = Healthcare
* Created = 2011-09-19T21:13:30Z
* Publication Date = 2014-10-09T20:54:42Z
* Rows Updated = 2014-10-09T20:54:30Z

## Description

Data for 2011 through June 2011. Enclosed data represents outpatient registrations including hospital ancillary services (e.g. laboratory, radiology, physical therapy, dialysis), primary and speciality care clinics (Fantus, Stroger Speciality Clinic, Ambulatory Screening Center, Prieto, Austin, Logan Square, Cicero, Vista, Child Advocacy Center, Woodlawn Adult Clinic, Englewood, Morton East, Near South, Sengstacke, Southside Pediatrics, Southside OB, Cottage Grove, Lincoln Robbins, Woody Winston, and OFH Speciality Clinic) same day surgery, CORE center and emergency department registrations

## Columns

```ls
| Name                       | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ===================== | ========= | =========== | ============== | ======== | 
| updated_at                 | :updated_at           | meta_data | meta_data   | time           | No       | 
| ZIPCODE                    | zipcode               | text      | text        | series tag     | Yes      | 
| 2011 YTD through June 2011 | ytd_through_june_2011 | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:3ghu-xq7n t:meta.view d:2017-03-07T16:57:30.972Z v:id=3ghu-xq7n v:category=Healthcare v:attributionLink=http://www.cookcountyhhs.org/ v:averageRating=0 v:name="Health & Hospitals System - Outpatient Registrations, by ZIP - Fiscal Year 2011 Incomplete" v:attribution="Cook County Health & Hospitals System"

property e:3ghu-xq7n t:meta.view.license d:2017-03-07T16:57:30.972Z v:name="Public Domain"

property e:3ghu-xq7n t:meta.view.owner d:2017-03-07T16:57:30.972Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:3ghu-xq7n t:meta.view.tableauthor d:2017-03-07T16:57:30.972Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```