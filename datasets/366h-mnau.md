# City University of New York (CUNY) University Enrollment Trends: Beginning Fall 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-enrollment-trends-beginning-fall-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/366h-mnau) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/366h-mnau/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/366h-mnau/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 366h-mnau |
| Name | City University of New York (CUNY) University Enrollment Trends: Beginning Fall 1990 |
| Attribution | City University of New York |
| Category | Education |
| Tags | higher education, enrollment |
| Created | 2014-01-16T19:35:13Z |
| Publication Date | 2016-01-11T13:56:39Z |

## Description

Trends in enrollment at City University of New York (CUNY) by enrollment category (transfers, freshmen, graduates, undergraduates, total).

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type | Render Type |
| ======== | ============== | =================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | fall_term                           | Fall Term                             | text      | text        |
| Yes      | series tag     | enrollment_type_code                | Enrollment Type Code                  | text      | number      |
| Yes      | series tag     | enrollment_type_description         | Enrollment Type Description           | text      | text        |
| Yes      | numeric metric | head_count                          | Head Count                            | number    | number      |
| Yes      | numeric metric | full_time_equivalent_fte_enrollment | Full-time Equivalent (FTE) Enrollment | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:366h-mnau d:1990-01-01T00:00:00.000Z t:enrollment_type_code=1 t:enrollment_type_description=Transfer t:fall_term="Fall 1990" m:full_time_equivalent_fte_enrollment=8111 m:head_count=11466

series e:366h-mnau d:1990-01-01T00:00:00.000Z t:enrollment_type_code=2 t:enrollment_type_description="First-time Freshmen" t:fall_term="Fall 1990" m:full_time_equivalent_fte_enrollment=23864 m:head_count=27002

series e:366h-mnau d:1990-01-01T00:00:00.000Z t:enrollment_type_code=3 t:enrollment_type_description=Graduate t:fall_term="Fall 1990" m:full_time_equivalent_fte_enrollment=14614 m:head_count=26463
```

## Meta Commands

```ls
metric m:head_count p:integer l:"Head Count" t:dataTypeName=number

metric m:full_time_equivalent_fte_enrollment p:integer l:"Full-time Equivalent (FTE) Enrollment" t:dataTypeName=number

entity e:366h-mnau l:"City University of New York (CUNY) University Enrollment Trends: Beginning Fall 1990" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/366h-mnau

property e:366h-mnau t:meta.view v:id=366h-mnau v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Enrollment Trends: Beginning Fall 1990" v:attribution="City University of New York"

property e:366h-mnau t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:366h-mnau t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:366h-mnau t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fall_term | enrollment_type_code | enrollment_type_description | head_count | full_time_equivalent_fte_enrollment | 
| ========= | ==================== | =========================== | ========== | =================================== | 
| Fall 1990 | 1                    | Transfer                    | 11466      | 8111                                | 
| Fall 1990 | 2                    | First-time Freshmen         | 27002      | 23864                               | 
| Fall 1990 | 3                    | Graduate                    | 26463      | 14614                               | 
| Fall 1990 | 4                    | Undergraduate               | 174165     | 125010                              | 
| Fall 1990 | 5                    | Total                       | 200628     | 139623                              | 
| Fall 1991 | 1                    | Transfer                    | 11655      | 8557                                | 
| Fall 1991 | 2                    | First-time Freshmen         | 25574      | 22939                               | 
| Fall 1991 | 3                    | Graduate                    | 25971      | 14629                               | 
| Fall 1991 | 4                    | Undergraduate               | 174263     | 127392                              | 
| Fall 1991 | 5                    | Total                       | 200234     | 142021                              | 
```