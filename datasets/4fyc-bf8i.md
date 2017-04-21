# Headcount Enrollment by Student Level and Student Load by Institutions of the State University of New York: Beginning Fall 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/headcount-enrollment-by-student-level-and-student-load-by-institutions-of-the-state-univer) |
| Metadata | [Link](https://data.ny.gov/api/views/4fyc-bf8i) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4fyc-bf8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4fyc-bf8i/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4fyc-bf8i |
| Name | Headcount Enrollment by Student Level and Student Load by Institutions of the State University of New York: Beginning Fall 2011 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, student enrollment |
| Created | 2013-03-05T22:57:59Z |
| Publication Date | 2016-09-09T21:07:23Z |

## Description

Number of home institution students attending a SUNY campus by level (Undergraduate/Graduate) and load status (full-time, part-time) by institution based on Fall term enrollment.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | number      |
| Yes      | series tag     | term                        | Term                        | text      | text        |
| Yes      | series tag     | college_or_institution_type | College or Institution Type | text      | text        |
| Yes      | series tag     | college_or_institution_name | College or Institution Name | text      | text        |
| Yes      | numeric metric | undergraduate_full_time     | Undergraduate Full-Time     | number    | number      |
| Yes      | numeric metric | undergraduate_part_time     | Undergraduate Part-Time     | number    | number      |
| Yes      | numeric metric | graduate_full_time          | Graduate Full-Time          | number    | number      |
| Yes      | numeric metric | graduate_part_time          | Graduate Part-Time          | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4fyc-bf8i d:2011-01-01T00:00:00.000Z t:college_or_institution_name=Albany t:term=Fall t:college_or_institution_type="Doctoral Degree Granting Institutions" m:graduate_full_time=2117 m:undergraduate_full_time=11925 m:undergraduate_part_time=830 m:graduate_part_time=2242

series e:4fyc-bf8i d:2011-01-01T00:00:00.000Z t:college_or_institution_name=Alfred-Ceramics t:term=Fall t:college_or_institution_type="Doctoral Degree Granting Institutions" m:graduate_full_time=71 m:undergraduate_full_time=629 m:undergraduate_part_time=17 m:graduate_part_time=14

series e:4fyc-bf8i d:2011-01-01T00:00:00.000Z t:college_or_institution_name=Binghamton t:term=Fall t:college_or_institution_type="Doctoral Degree Granting Institutions" m:graduate_full_time=1566 m:undergraduate_full_time=11464 m:undergraduate_part_time=397 m:graduate_part_time=1319
```

## Meta Commands

```ls
metric m:undergraduate_full_time p:integer l:"Undergraduate Full-Time" t:dataTypeName=number

metric m:undergraduate_part_time p:integer l:"Undergraduate Part-Time" t:dataTypeName=number

metric m:graduate_full_time p:integer l:"Graduate Full-Time" t:dataTypeName=number

metric m:graduate_part_time p:integer l:"Graduate Part-Time" t:dataTypeName=number

entity e:4fyc-bf8i l:"Headcount Enrollment by Student Level and Student Load by Institutions of the State University of New York: Beginning Fall 2011" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/4fyc-bf8i

property e:4fyc-bf8i t:meta.view v:id=4fyc-bf8i v:category=Education v:attributionLink=http://www.suny.edu/ v:averageRating=0 v:name="Headcount Enrollment by Student Level and Student Load by Institutions of the State University of New York: Beginning Fall 2011" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:4fyc-bf8i t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4fyc-bf8i t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4fyc-bf8i t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | term | college_or_institution_type           | college_or_institution_name | undergraduate_full_time | undergraduate_part_time | graduate_full_time | graduate_part_time | 
| ==== | ==== | ===================================== | =========================== | ======================= | ======================= | ================== | ================== | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Albany                      | 11925                   | 830                     | 2117               | 2242               | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Alfred-Ceramics             | 629                     | 17                      | 71                 | 14                 | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Binghamton                  | 11464                   | 397                     | 1566               | 1319               | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Buffalo Univ                | 17664                   | 1670                    | 6048               | 3478               | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Cornell Stat                | 5608                    |                         | 1840               |                    | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Downstate Medical           | 184                     | 165                     | 1037               | 365                | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Envir Sci & Forestry        | 1628                    | 539                     | 319                | 194                | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Optometry                   |                         |                         | 315                | 2                  | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Stony Brook                 | 14485                   | 1300                    | 5137               | 2998               | 
| 2011 | Fall | Doctoral Degree Granting Institutions | Upstate Medical             | 213                     | 83                      | 1040               | 253                | 
```