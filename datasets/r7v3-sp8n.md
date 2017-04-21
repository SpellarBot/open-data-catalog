# State University of New York (SUNY) Employees By Employment Status: Beginning Fall 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-of-new-york-suny-employees-by-employment-status-beginning-fall-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/r7v3-sp8n) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/r7v3-sp8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/r7v3-sp8n/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | r7v3-sp8n |
| Name | State University of New York (SUNY) Employees By Employment Status: Beginning Fall 2011 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, employees, faculty, higher education |
| Created | 2013-12-23T15:45:44Z |
| Publication Date | 2015-09-10T14:25:58Z |

## Description

Number of employees at SUNY Institutions (System Administration and campuses) by total employees, faculty only, professional (non-faculty) only and other (non-faculty) only by employment status (full-time, part-time).

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | time           | year                                         | Year                                         | number    | number      |
| Yes      | series tag     | suny_institution                             | SUNY Institution                             | text      | text        |
| Yes      | series tag     | sector                                       | Sector                                       | text      | text        |
| Yes      | numeric metric | all_employees_total                          | All Employees Total                          | number    | number      |
| Yes      | numeric metric | all_employees_full_time                      | All Employees Full-Time                      | number    | number      |
| Yes      | numeric metric | all_employees_part_time                      | All Employees Part-Time                      | number    | number      |
| Yes      | numeric metric | faculty_total                                | Faculty Total                                | number    | number      |
| Yes      | numeric metric | faculty_full_time                            | Faculty Full-Time                            | number    | number      |
| Yes      | numeric metric | faculty_part_time                            | Faculty Part-Time                            | number    | number      |
| Yes      | numeric metric | professional_employees_non_faculty_total     | Professional Employees Non-Faculty Total     | number    | number      |
| Yes      | numeric metric | professional_employees_non_faculty_full_time | Professional Employees Non-Faculty Full-Time | number    | number      |
| Yes      | numeric metric | professional_employees_non_faculty_part_time | Professional Employees Non-Faculty Part-Time | number    | number      |
| Yes      | numeric metric | other_employees_total                        | Other Employees Total                        | number    | number      |
| Yes      | numeric metric | other_employees_full_time                    | Other Employees Full-Time                    | number    | number      |
| Yes      | numeric metric | other_employees_part_time                    | Other Employees Part-Time                    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r7v3-sp8n d:2011-01-01T00:00:00.000Z t:sector="Community Colleges" t:suny_institution="Adirondack Community College" m:professional_employees_non_faculty_full_time=54 m:professional_employees_non_faculty_total=70 m:all_employees_full_time=202 m:other_employees_part_time=10 m:professional_employees_non_faculty_part_time=16 m:faculty_full_time=89 m:other_employees_total=69 m:all_employees_part_time=213 m:all_employees_total=415 m:faculty_total=276 m:other_employees_full_time=59 m:faculty_part_time=187

series e:r7v3-sp8n d:2011-01-01T00:00:00.000Z t:sector="Community Colleges" t:suny_institution="Broome Community College" m:professional_employees_non_faculty_full_time=97 m:professional_employees_non_faculty_total=118 m:all_employees_full_time=402 m:other_employees_part_time=66 m:professional_employees_non_faculty_part_time=21 m:faculty_full_time=170 m:other_employees_total=201 m:all_employees_part_time=374 m:all_employees_total=776 m:faculty_total=457 m:other_employees_full_time=135 m:faculty_part_time=287

series e:r7v3-sp8n d:2011-01-01T00:00:00.000Z t:sector="Community Colleges" t:suny_institution="Cayuga County Community College" m:professional_employees_non_faculty_full_time=82 m:professional_employees_non_faculty_total=121 m:all_employees_full_time=197 m:other_employees_part_time=50 m:professional_employees_non_faculty_part_time=39 m:faculty_full_time=60 m:other_employees_total=105 m:all_employees_part_time=306 m:all_employees_total=503 m:faculty_total=277 m:other_employees_full_time=55 m:faculty_part_time=217
```

## Meta Commands

```ls
metric m:all_employees_total p:integer l:"All Employees Total" t:dataTypeName=number

metric m:all_employees_full_time p:integer l:"All Employees Full-Time" t:dataTypeName=number

metric m:all_employees_part_time p:integer l:"All Employees Part-Time" t:dataTypeName=number

metric m:faculty_total p:integer l:"Faculty Total" t:dataTypeName=number

metric m:faculty_full_time p:integer l:"Faculty Full-Time" t:dataTypeName=number

metric m:faculty_part_time p:integer l:"Faculty Part-Time" t:dataTypeName=number

metric m:professional_employees_non_faculty_total p:integer l:"Professional Employees Non-Faculty Total" t:dataTypeName=number

metric m:professional_employees_non_faculty_full_time p:integer l:"Professional Employees Non-Faculty Full-Time" t:dataTypeName=number

metric m:professional_employees_non_faculty_part_time p:integer l:"Professional Employees Non-Faculty Part-Time" t:dataTypeName=number

metric m:other_employees_total p:integer l:"Other Employees Total" t:dataTypeName=number

metric m:other_employees_full_time p:integer l:"Other Employees Full-Time" t:dataTypeName=number

metric m:other_employees_part_time p:integer l:"Other Employees Part-Time" t:dataTypeName=number

entity e:r7v3-sp8n l:"State University of New York (SUNY) Employees By Employment Status: Beginning Fall 2011" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/r7v3-sp8n

property e:r7v3-sp8n t:meta.view v:id=r7v3-sp8n v:category=Education v:attributionLink=http://www.suny.edu v:averageRating=0 v:name="State University of New York (SUNY) Employees By Employment Status: Beginning Fall 2011" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:r7v3-sp8n t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:r7v3-sp8n t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:r7v3-sp8n t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | suny_institution                    | sector              | all_employees_total | all_employees_full_time | all_employees_part_time | faculty_total | faculty_full_time | faculty_part_time | professional_employees_non_faculty_total | professional_employees_non_faculty_full_time | professional_employees_non_faculty_part_time | other_employees_total | other_employees_full_time | other_employees_part_time | 
| ==== | =================================== | =================== | =================== | ======================= | ======================= | ============= | ================= | ================= | ======================================== | ============================================ | ============================================ | ===================== | ========================= | ========================= | 
| 2011 | Adirondack Community College        | Community Colleges  | 415                 | 202                     | 213                     | 276           | 89                | 187               | 70                                       | 54                                           | 16                                           | 69                    | 59                        | 10                        | 
| 2011 | Broome Community College            | Community Colleges  | 776                 | 402                     | 374                     | 457           | 170               | 287               | 118                                      | 97                                           | 21                                           | 201                   | 135                       | 66                        | 
| 2011 | Cayuga County Community College     | Community Colleges  | 503                 | 197                     | 306                     | 277           | 60                | 217               | 121                                      | 82                                           | 39                                           | 105                   | 55                        | 50                        | 
| 2011 | Clinton Community College           | Community Colleges  | 302                 | 136                     | 166                     | 179           | 53                | 126               | 40                                       | 37                                           | 3                                            | 83                    | 46                        | 37                        | 
| 2011 | College of Tech & Ag at Cobleskill  | Technology Colleges | 447                 | 362                     | 85                      | 170           | 97                | 73                | 131                                      | 128                                          | 3                                            | 146                   | 137                       | 9                         | 
| 2011 | College of Tech & Ag at Morrisville | Technology Colleges | 585                 | 416                     | 169                     | 244           | 140               | 104               | 180                                      | 118                                          | 62                                           | 161                   | 158                       | 3                         | 
| 2011 | College of Tech at Alfred           | Technology Colleges | 589                 | 521                     | 68                      | 217           | 179               | 38                | 162                                      | 144                                          | 18                                           | 210                   | 198                       | 12                        | 
| 2011 | College of Tech at Canton           | Technology Colleges | 513                 | 339                     | 174                     | 206           | 116               | 90                | 141                                      | 117                                          | 24                                           | 166                   | 106                       | 60                        | 
| 2011 | College of Tech at Delhi            | Technology Colleges | 504                 | 354                     | 150                     | 215           | 119               | 96                | 160                                      | 124                                          | 36                                           | 129                   | 111                       | 18                        | 
| 2011 | College of Tech at Farmingdale      | Technology Colleges | 1113                | 580                     | 533                     | 604           | 207               | 397               | 226                                      | 169                                          | 57                                           | 283                   | 204                       | 79                        | 
```