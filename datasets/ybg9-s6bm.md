# Annual Youth Detention Admissions by County: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-youth-detention-admissions-by-county-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/ybg9-s6bm) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ybg9-s6bm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ybg9-s6bm/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ybg9-s6bm |
| Name | Annual Youth Detention Admissions by County: Beginning 2006 |
| Attribution | Office of Children and Family Services |
| Category | Human Services |
| Tags | juvenile justice, detention, admissions, unique youth |
| Created | 2014-03-10T12:06:20Z |
| Publication Date | 2016-06-07T14:44:43Z |

## Description

This data set from the Office of Children and Family Services (OCFS) provides information, by county, on detention admissions and unique youth admitted to detention from 2006 to 2012

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | county_district                | County/District                | text      | text        |
| Yes      | time           | year                           | Year                           | number    | number      |
| Yes      | numeric metric | secure_non_secure_admissions   | Secure Non Secure Admissions   | number    | number      |
| Yes      | numeric metric | non_secure_admissions          | Non Secure Admissions          | number    | number      |
| Yes      | numeric metric | secure_non_secure_unique_youth | Secure Non Secure Unique Youth | number    | number      |
| Yes      | numeric metric | non_secure_unique_youth        | Non Secure Unique Youth        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ybg9-s6bm d:2006-01-01T00:00:00.000Z t:county_district=Albany m:secure_non_secure_admissions=145 m:non_secure_admissions=209 m:non_secure_unique_youth=130 m:secure_non_secure_unique_youth=108

series e:ybg9-s6bm d:2006-01-01T00:00:00.000Z t:county_district=Allegany m:secure_non_secure_admissions=0 m:non_secure_admissions=18 m:non_secure_unique_youth=17 m:secure_non_secure_unique_youth=0

series e:ybg9-s6bm d:2006-01-01T00:00:00.000Z t:county_district=Broome m:secure_non_secure_admissions=15 m:non_secure_admissions=108 m:non_secure_unique_youth=83 m:secure_non_secure_unique_youth=12
```

## Meta Commands

```ls
metric m:secure_non_secure_admissions p:integer l:"Secure Non Secure Admissions" d:"Number of admissions to secure or mixed (youth was in secure and non-secure) facilities in a year." t:dataTypeName=number

metric m:non_secure_admissions p:integer l:"Non Secure Admissions" d:"Number of admissions to non secure facilities in year." t:dataTypeName=number

metric m:secure_non_secure_unique_youth p:integer l:"Secure Non Secure Unique Youth" d:"Number of unique youth admitted to secure or mixed (youth was in secure and non-secure) facilities in a year." t:dataTypeName=number

metric m:non_secure_unique_youth p:integer l:"Non Secure Unique Youth" d:"Number of unique youth admitted to non secure facilities in a year." t:dataTypeName=number

entity e:ybg9-s6bm l:"Annual Youth Detention Admissions by County: Beginning 2006" t:attribution="Office of Children and Family Services" t:url=https://data.ny.gov/api/views/ybg9-s6bm

property e:ybg9-s6bm t:meta.view v:id=ybg9-s6bm v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/rehab/ v:averageRating=0 v:name="Annual Youth Detention Admissions by County: Beginning 2006" v:attribution="Office of Children and Family Services"

property e:ybg9-s6bm t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ybg9-s6bm t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ybg9-s6bm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county_district | year | secure_non_secure_admissions | non_secure_admissions | secure_non_secure_unique_youth | non_secure_unique_youth | 
| =============== | ==== | ============================ | ===================== | ============================== | ======================= | 
| Albany          | 2006 | 145                          | 209                   | 108                            | 130                     | 
| Allegany        | 2006 | 0                            | 18                    | 0                              | 17                      | 
| Broome          | 2006 | 15                           | 108                   | 12                             | 83                      | 
| Cattaraugus     | 2006 | 3                            | 42                    | 2                              | 33                      | 
| Cayuga          | 2006 | 6                            | 26                    | 5                              | 17                      | 
| Chautauqua      | 2006 | 5                            | 19                    | 4                              | 18                      | 
| Chemung         | 2006 | 22                           | 109                   | 15                             | 73                      | 
| Chenango        | 2006 | 3                            | 12                    | 2                              | 10                      | 
| Clinton         | 2006 | 1                            | 2                     | 1                              | 2                       | 
| Columbia        | 2006 | 5                            | 32                    | 3                              | 26                      | 
```