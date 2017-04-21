# 2009-10 Class Size - School-level Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2009-10-class-size-school-level-detail-6bf33) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d3ge-anaz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d3ge-anaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d3ge-anaz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d3ge-anaz |
| Name | 2009-10 Class Size - School-level Detail |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-13T21:50:21Z |
| Publication Date | 2011-10-13T21:51:48Z |

## Description

This file shows average class sizes, pupil-teacher ratio, and size of largest and smallest classes for each school, broken out by grade and program type (General Education, Self-Contained Special Education, Collaborative Team Teaching (CTT)) for grades K-9 (where grade 9 is not reported by subject area), and for grades 5-9 (where available) and 9-12, aggregated by program type (General Education, CTT, and Self-Contained Special Education) and core course (e.g. English 9, Math A, US History, etc.)

Based on January 27, 2010 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | boro                                | BORO                                 | text      | text        |
| Yes      | numeric metric | csd                                 | CSD                                  | number    | number      |
| Yes      | series tag     | school_code                         | SCHOOL CODE                          | text      | text        |
| Yes      | series tag     | school_name                         | SCHOOL NAME                          | text      | text        |
| Yes      | series tag     | grade_                              | GRADE                                | text      | text        |
| Yes      | series tag     | program_type                        | PROGRAM TYPE                         | text      | text        |
| Yes      | series tag     | core_subject_ms_core_and_9_12_only_ | CORE SUBJECT (MS CORE and 9-12 ONLY) | text      | text        |
| Yes      | series tag     | core_course_ms_core_and_9_12_only_  | CORE COURSE (MS CORE and 9-12 ONLY)  | text      | text        |
| Yes      | series tag     | service_category_k_9_only_          | SERVICE CATEGORY(K-9* ONLY)          | text      | text        |
| Yes      | numeric metric | number_of_classes                   | NUMBER OF CLASSES                    | number    | number      |
| Yes      | numeric metric | total_register                      | TOTAL REGISTER                       | number    | number      |
| Yes      | numeric metric | average_class_size                  | AVERAGE CLASS SIZE                   | number    | number      |
| Yes      | numeric metric | size_of_smallest_class              | SIZE OF SMALLEST CLASS               | number    | number      |
| Yes      | numeric metric | size_of_largest_class               | SIZE OF LARGEST CLASS                | number    | number      |
| Yes      | series tag     | data_source                         | DATA SOURCE                          | text      | text        |
| Yes      | numeric metric | schoolwide_pupil_teacher_ratio      | SCHOOLWIDE PUPIL-TEACHER RATIO       | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d3ge-anaz d:2009-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=0K t:school_code=M015 m:csd=1 m:average_class_size=21 m:size_of_largest_class=21 m:size_of_smallest_class=21 m:total_register=21 m:number_of_classes=1

series e:d3ge-anaz d:2009-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=CTT t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=0K t:school_code=M015 m:csd=1 m:average_class_size=21 m:size_of_largest_class=21 m:size_of_smallest_class=21 m:total_register=21 m:number_of_classes=1

series e:d3ge-anaz d:2009-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:data_source=ATS t:grade_=01 t:school_code=M015 m:csd=1 m:average_class_size=11 m:size_of_largest_class=11 m:size_of_smallest_class=11 m:total_register=11 m:number_of_classes=1
```

## Meta Commands

```ls
metric m:csd p:integer l:CSD t:dataTypeName=number

metric m:number_of_classes p:integer l:"NUMBER OF CLASSES" t:dataTypeName=number

metric m:total_register p:integer l:"TOTAL REGISTER" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

metric m:size_of_smallest_class p:integer l:"SIZE OF SMALLEST CLASS" t:dataTypeName=number

metric m:size_of_largest_class p:integer l:"SIZE OF LARGEST CLASS" t:dataTypeName=number

metric m:schoolwide_pupil_teacher_ratio p:float l:"SCHOOLWIDE PUPIL-TEACHER RATIO" t:dataTypeName=number

entity e:d3ge-anaz l:"2009-10 Class Size - School-level Detail" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/d3ge-anaz

property e:d3ge-anaz t:meta.view v:id=d3ge-anaz v:category=Education v:averageRating=0 v:name="2009-10 Class Size - School-level Detail" v:attribution="Department of Education (DOE)"

property e:d3ge-anaz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d3ge-anaz t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| boro | csd | school_code | school_name               | grade_ | program_type | core_subject_ms_core_and_9_12_only_ | core_course_ms_core_and_9_12_only_ | service_category_k_9_only_ | number_of_classes | total_register | average_class_size | size_of_smallest_class | size_of_largest_class | data_source | schoolwide_pupil_teacher_ratio | 
| ==== | === | =========== | ========================= | ====== | ============ | =================================== | ================================== | ========================== | ================= | ============== | ================== | ====================== | ===================== | =========== | ============================== | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K     | GEN ED       | -                                   | -                                  | -                          | 1                 | 21             | 21.0               | 21                     | 21                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K     | CTT          | -                                   | -                                  | -                          | 1                 | 21             | 21.0               | 21                     | 21                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 01     | GEN ED       | -                                   | -                                  | -                          | 1                 | 11             | 11.0               | 11                     | 11                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 01     | CTT          | -                                   | -                                  | -                          | 1                 | 17             | 17.0               | 17                     | 17                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 02     | GEN ED       | -                                   | -                                  | -                          | 1                 | 16             | 16.0               | 16                     | 16                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 02     | CTT          | -                                   | -                                  | -                          | 1                 | 17             | 17.0               | 17                     | 17                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 03     | GEN ED       | -                                   | -                                  | -                          | 2                 | 23             | 11.5               | 11                     | 12                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 04     | GEN ED       | -                                   | -                                  | -                          | 2                 | 26             | 13.0               | 12                     | 14                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 05     | GEN ED       | -                                   | -                                  | -                          | 2                 | 29             | 14.5               | 14                     | 15                    | ATS         |                                | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K-09  | SPEC ED      | -                                   | -                                  | 12:1:1                     | 1                 | 12             | 12.0               | 12                     | 12                    | ATS         |                                | 
```