# 2010-2011 Class Size - School-level detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-school-level-detail-3a3f5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/urz7-pzb3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/urz7-pzb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/urz7-pzb3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | urz7-pzb3 |
| Name | 2010-2011 Class Size - School-level detail |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-13T16:26:44Z |
| Publication Date | 2011-10-13T16:32:37Z |

## Description

Average class sizes for each school, by grade and program type (General Education, Self-Contained Special Education, Collaborative Team Teaching (CTT)) for grades K-9 (where grade 9 is not reported by subject area), and for grades 5-9 (where available) and 9-12, aggregated by program type (General Education, CTT, and Self-Contained Special Education) and core course (e.g. English 9, Integrated Algebra, US History, etc.).

Class size data is based on January 28, 2011 data.

*Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
| Yes      | numeric metric | csd                                 | CSD                                  | number    | number      |
| Yes      | series tag     | borough                             | BOROUGH                              | text      | text        |
| Yes      | series tag     | school_code                         | SCHOOL CODE                          | text      | text        |
| Yes      | series tag     | school_name                         | SCHOOL NAME                          | text      | text        |
| Yes      | series tag     | grade_                              | GRADE                                | text      | text        |
| Yes      | series tag     | program_type                        | PROGRAM TYPE                         | text      | text        |
| Yes      | series tag     | core_subject_ms_core_and_9_12_only_ | CORE SUBJECT (MS CORE and 9-12 ONLY) | text      | text        |
| Yes      | series tag     | core_course_ms_core_and_9_12_only_  | CORE COURSE (MS CORE and 9-12 ONLY)  | text      | text        |
| Yes      | series tag     | service_category_k_9_only_          | SERVICE CATEGORY(K-9* ONLY)          | text      | text        |
| Yes      | numeric metric | number_of_students_seats_filled     | NUMBER OF STUDENTS / SEATS FILLED    | number    | number      |
| Yes      | numeric metric | number_of_sections                  | NUMBER OF SECTIONS                   | number    | number      |
| Yes      | numeric metric | average_class_size                  | AVERAGE CLASS SIZE                   | number    | number      |
| Yes      | numeric metric | size_of_smallest_class              | SIZE OF SMALLEST CLASS               | number    | number      |
| Yes      | numeric metric | size_of_largest_class               | SIZE OF LARGEST CLASS                | number    | number      |
| Yes      | series tag     | data_source                         | DATA SOURCE                          | text      | text        |
| Yes      | numeric metric | schoolwide_pupil_teacher_ratio      | SCHOOLWIDE PUPIL-TEACHER RATIO       | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:urz7-pzb3 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:school_name="P.S. 015 Roberto Clemente" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=0K t:borough=M t:school_code=M015 m:csd=1 m:number_of_sections=1 m:average_class_size=19 m:size_of_largest_class=19 m:size_of_smallest_class=19 m:number_of_students_seats_filled=19

series e:urz7-pzb3 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=CTT t:school_name="P.S. 015 Roberto Clemente" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=0K t:borough=M t:school_code=M015 m:csd=1 m:number_of_sections=1 m:average_class_size=21 m:size_of_largest_class=21 m:size_of_smallest_class=21 m:number_of_students_seats_filled=21

series e:urz7-pzb3 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:school_name="P.S. 015 Roberto Clemente" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=01 t:borough=M t:school_code=M015 m:csd=1 m:number_of_sections=1 m:average_class_size=17 m:size_of_largest_class=17 m:size_of_smallest_class=17 m:number_of_students_seats_filled=17
```

## Meta Commands

```ls
metric m:csd p:integer l:CSD t:dataTypeName=number

metric m:number_of_students_seats_filled p:integer l:"NUMBER OF STUDENTS / SEATS FILLED" t:dataTypeName=number

metric m:number_of_sections p:integer l:"NUMBER OF SECTIONS" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

metric m:size_of_smallest_class p:integer l:"SIZE OF SMALLEST CLASS" t:dataTypeName=number

metric m:size_of_largest_class p:integer l:"SIZE OF LARGEST CLASS" t:dataTypeName=number

metric m:schoolwide_pupil_teacher_ratio p:float l:"SCHOOLWIDE PUPIL-TEACHER RATIO" t:dataTypeName=number

entity e:urz7-pzb3 l:"2010-2011 Class Size - School-level detail" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/urz7-pzb3

property e:urz7-pzb3 t:meta.view v:id=urz7-pzb3 v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - School-level detail" v:attribution="Department of Education (DOE)"

property e:urz7-pzb3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:urz7-pzb3 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| csd | borough | school_code | school_name               | grade_ | program_type | core_subject_ms_core_and_9_12_only_ | core_course_ms_core_and_9_12_only_ | service_category_k_9_only_ | number_of_students_seats_filled | number_of_sections | average_class_size | size_of_smallest_class | size_of_largest_class | data_source | schoolwide_pupil_teacher_ratio | 
| === | ======= | =========== | ========================= | ====== | ============ | =================================== | ================================== | ========================== | =============================== | ================== | ================== | ====================== | ===================== | =========== | ============================== | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 0K     | GEN ED       | -                                   | -                                  | -                          | 19                              | 1                  | 19.0               | 19                     | 19                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 0K     | CTT          | -                                   | -                                  | -                          | 21                              | 1                  | 21.0               | 21                     | 21                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 01     | GEN ED       | -                                   | -                                  | -                          | 17                              | 1                  | 17.0               | 17                     | 17                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 01     | CTT          | -                                   | -                                  | -                          | 17                              | 1                  | 17.0               | 17                     | 17                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 02     | GEN ED       | -                                   | -                                  | -                          | 15                              | 1                  | 15.0               | 15                     | 15                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 02     | CTT          | -                                   | -                                  | -                          | 17                              | 1                  | 17.0               | 17                     | 17                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 03     | GEN ED       | -                                   | -                                  | -                          | 12                              | 1                  | 12.0               | 12                     | 12                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 03     | CTT          | -                                   | -                                  | -                          | 15                              | 1                  | 15.0               | 15                     | 15                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 04     | GEN ED       | -                                   | -                                  | -                          | 26                              | 2                  | 13.0               | 12                     | 14                    | ATS         |                                | 
| 1   | M       | M015        | P.S. 015 Roberto Clemente | 05     | GEN ED       | -                                   | -                                  | -                          | 27                              | 1                  | 27.0               | 27                     | 27                    | ATS         |                                | 
```