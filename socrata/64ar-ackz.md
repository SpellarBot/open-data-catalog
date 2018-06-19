# State University of New York (SUNY) - NYS High School Attended by First Time Undergraduate Students: Beginning Fall 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-of-new-york-suny-nys-high-school-attended-by-first-time-undergraduate-stu) |
| Metadata | [Link](https://data.ny.gov/api/views/64ar-ackz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/64ar-ackz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/64ar-ackz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 64ar-ackz |
| Name | State University of New York (SUNY) - NYS High School Attended by First Time Undergraduate Students: Beginning Fall 2010 |
| Attribution | SUNY System Administration, Office of Institutional Research and Data Analytics |
| Category | Education |
| Tags | suny institutions, first time undergraduates, higher education |
| Created | 2015-06-12T19:37:32Z |
| Publication Date | 2016-09-09T20:15:43Z |

## Description

Report by NYS High School of the number of SUNY First Time Undergraduates entering in the Term, who reported attending that High School.  The total number of First Time Undergraduates at SUNY from each High School is provided. The total is sub-divided by the SUNY Sector of the Institution the student is attending; Doctoral, Comprehensive, Technology and Community College.  The report also provides a total count by NYS County, which is an aggregate of all the high schools in that County.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | term                                  | Term                                  | text      | text        |
| Yes      | series tag     | high_school_name                      | High School Name                      | text      | text        |
| Yes      | numeric metric | high_school_ceeb                      | High School CEEB                      | number    | number      |
| Yes      | series tag     | city                                  | City                                  | text      | text        |
| Yes      | series tag     | county                                | County                                | text      | text        |
| Yes      | series tag     | zip_code                              | Zip Code                              | text      | text        |
| Yes      | numeric metric | total_attending_suny_institutions     | Total Attending SUNY Institutions     | number    | number      |
| Yes      | series tag     | attending_suny_doctoral_institutions  | Attending SUNY Doctoral Institutions  | text      | text        |
| Yes      | series tag     | attending_suny_comprehensive_colleges | Attending SUNY Comprehensive Colleges | text      | text        |
| Yes      | series tag     | attending_suny_technology_colleges    | Attending SUNY Technology Colleges    | text      | text        |
| Yes      | series tag     | attending_suny_community_colleges     | Attending SUNY Community Colleges     | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:64ar-ackz d:2010-01-01T00:00:00.000Z t:attending_suny_technology_colleges=33 t:county=Herkimer t:term="Fall 2015" t:attending_suny_comprehensive_colleges=26 t:attending_suny_community_colleges=260 t:attending_suny_doctoral_institutions=27 m:total_attending_suny_institutions=346

series e:64ar-ackz d:2010-01-01T00:00:00.000Z t:attending_suny_technology_colleges=31 t:county=Herkimer t:term="Fall 2014" t:attending_suny_comprehensive_colleges=27 t:attending_suny_community_colleges=266 t:attending_suny_doctoral_institutions=31 m:total_attending_suny_institutions=355

series e:64ar-ackz d:2010-01-01T00:00:00.000Z t:high_school_name="Spackenkill High School" t:attending_suny_technology_colleges=<4 t:zip_code=126035099 t:county=Dutchess t:term="Fall 2014" t:attending_suny_comprehensive_colleges=11 t:attending_suny_community_colleges=51 t:attending_suny_doctoral_institutions=5 t:city=Poughkeepsie m:high_school_ceeb=334632 m:total_attending_suny_institutions=68
```

## Meta Commands

```ls
metric m:high_school_ceeb p:integer l:"High School CEEB" d:"Code assigned to institution by College Entrance Examination Board" t:dataTypeName=number

metric m:total_attending_suny_institutions p:integer l:"Total Attending SUNY Institutions" d:"Total number of First Time Undergraduates entering a SUNY Institution in the Term by the NYS High School attended." t:dataTypeName=number

entity e:64ar-ackz l:"State University of New York (SUNY) - NYS High School Attended by First Time Undergraduate Students: Beginning Fall 2010" t:attribution="SUNY System Administration, Office of Institutional Research and Data Analytics" t:url=https://data.ny.gov/api/views/64ar-ackz

property e:64ar-ackz t:meta.view v:id=64ar-ackz v:category=Education v:averageRating=0 v:name="State University of New York (SUNY) - NYS High School Attended by First Time Undergraduate Students: Beginning Fall 2010" v:attribution="SUNY System Administration, Office of Institutional Research and Data Analytics"

property e:64ar-ackz t:meta.view.license v:name="Public Domain"

property e:64ar-ackz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:64ar-ackz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:64ar-ackz t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| term      | high_school_name               | high_school_ceeb | city         | county   | zip_code  | total_attending_suny_institutions | attending_suny_doctoral_institutions | attending_suny_comprehensive_colleges | attending_suny_technology_colleges | attending_suny_community_colleges | 
| ========= | ============================== | ================ | ============ | ======== | ========= | ================================= | ==================================== | ===================================== | ================================== | ================================= | 
| Fall 2015 |                                |                  |              | Herkimer |           | 346                               | 27                                   | 26                                    | 33                                 | 260                               | 
| Fall 2014 |                                |                  |              | Herkimer |           | 355                               | 31                                   | 27                                    | 31                                 | 266                               | 
| Fall 2014 | Spackenkill High School        | 334632           | Poughkeepsie | Dutchess | 126035099 | 68                                | 5                                    | 11                                    | <4                                 | 51                                | 
| Fall 2015 | Spackenkill High School        | 334632           | Poughkeepsie | Dutchess | 126035099 | 58                                | 12                                   | 10                                    | 0                                  | 36                                | 
| Fall 2012 | Poughkeepsie High School       | 334630           | Poughkeepsie | Dutchess | 12603     | 120                               | <4                                   | <4                                    | 7                                  | 107                               | 
| Fall 2012 | Tabernacle Christian Academy   | 334633           | Poughkeepsie | Dutchess | 12601     |                                   | <4                                   | 0                                     | 0                                  | <4                                | 
| Fall 2014 | Tabernacle Christian Academy   | 334633           | Poughkeepsie | Dutchess | 12601     | 4                                 | 0                                    | 0                                     | 0                                  | 4                                 | 
| Fall 2010 | Red Hook High School           | 334685           | Red Hook     | Dutchess | 12571     | 96                                | 6                                    | 24                                    | <4                                 | 63                                | 
| Fall 2011 | Poughkeepsie High School       | 334630           | Poughkeepsie | Dutchess | 12603     | 117                               | <4                                   | <4                                    | 7                                  | 105                               | 
| Fall 2013 | Academy Conservation / Environ | 331056           | Brooklyn     | Kings    | 112363525 | 4                                 | 0                                    | 0                                     | <4                                 | <4                                | 
```