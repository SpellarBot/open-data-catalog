# 2010-2011 Class Size - Borough Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-borough-summary-15572) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7yds-6i8e) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7yds-6i8e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7yds-6i8e/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7yds-6i8e |
| Name | 2010-2011 Class Size - Borough Summary |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T17:29:10Z |
| Publication Date | 2011-10-14T17:30:06Z |

## Description

This file shows average class size for each borough, aggregated by grade and program type. For grades 5-9 (where available) and 9-12, the data are shown by program type and core course.
Based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | borough                             | BOROUGH                              | text      | text        |
| Yes      | series tag     | grade_                              | GRADE                                | text      | text        |
| Yes      | series tag     | program_type                        | PROGRAM TYPE                         | text      | text        |
| Yes      | series tag     | core_subject_ms_core_and_9_12_only_ | CORE SUBJECT (MS CORE and 9-12 ONLY) | text      | text        |
| Yes      | series tag     | core_course_ms_core_and_9_12_only_  | CORE COURSE (MS CORE and 9-12 ONLY)  | text      | text        |
| Yes      | series tag     | service_category_k_9_only_          | SERVICE CATEGORY(K-9* ONLY)          | text      | text        |
| Yes      | numeric metric | number_of_students_seats_filled     | NUMBER OF STUDENTS / SEATS FILLED    | number    | number      |
| Yes      | numeric metric | number_of_sections                  | NUMBER OF SECTIONS                   | number    | number      |
| Yes      | numeric metric | average_class_size                  | AVERAGE CLASS SIZE                   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7yds-6i8e d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K t:borough=Brooklyn m:number_of_sections=783 m:average_class_size=22 m:number_of_students_seats_filled=17264

series e:7yds-6i8e d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=CTT t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K t:borough=Brooklyn m:number_of_sections=149 m:average_class_size=20.5 m:number_of_students_seats_filled=3056

series e:7yds-6i8e d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=G&T t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K t:borough=Brooklyn m:number_of_sections=21 m:average_class_size=18.6 m:number_of_students_seats_filled=390
```

## Meta Commands

```ls
metric m:number_of_students_seats_filled p:integer l:"NUMBER OF STUDENTS / SEATS FILLED" t:dataTypeName=number

metric m:number_of_sections p:integer l:"NUMBER OF SECTIONS" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

entity e:7yds-6i8e l:"2010-2011 Class Size - Borough Summary" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/7yds-6i8e

property e:7yds-6i8e t:meta.view v:id=7yds-6i8e v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - Borough Summary" v:attribution="Department of Education (DOE)"

property e:7yds-6i8e t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7yds-6i8e t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough  | grade_ | program_type | core_subject_ms_core_and_9_12_only_ | core_course_ms_core_and_9_12_only_ | service_category_k_9_only_ | number_of_students_seats_filled | number_of_sections | average_class_size | 
| ======== | ====== | ============ | =================================== | ================================== | ========================== | =============================== | ================== | ================== | 
| Brooklyn | 0K     | GEN ED       | -                                   | -                                  | -                          | 17264                           | 783                | 22.0               | 
| Brooklyn | 0K     | CTT          | -                                   | -                                  | -                          | 3056                            | 149                | 20.5               | 
| Brooklyn | 0K     | G&T          | -                                   | -                                  | -                          | 390                             | 21                 | 18.6               | 
| Brooklyn | 01     | GEN ED       | -                                   | -                                  | -                          | 18658                           | 823                | 22.7               | 
| Brooklyn | 01     | CTT          | -                                   | -                                  | -                          | 2783                            | 126                | 22.1               | 
| Brooklyn | 01     | G&T          | -                                   | -                                  | -                          | 512                             | 22                 | 23.3               | 
| Brooklyn | 02     | GEN ED       | -                                   | -                                  | -                          | 18083                           | 784                | 23.1               | 
| Brooklyn | 02     | CTT          | -                                   | -                                  | -                          | 2775                            | 123                | 22.6               | 
| Brooklyn | 02     | G&T          | -                                   | -                                  | -                          | 370                             | 17                 | 21.8               | 
| Brooklyn | 03     | GEN ED       | -                                   | -                                  | -                          | 17201                           | 737                | 23.3               | 
```