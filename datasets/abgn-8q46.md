# 2010-2011 Class Size - Citywide Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-citywide-summary-18776) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/abgn-8q46) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/abgn-8q46/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/abgn-8q46/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | abgn-8q46 |
| Name | 2010-2011 Class Size - Citywide Summary |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T18:16:53Z |
| Publication Date | 2011-10-14T18:18:06Z |

## Description

This file shows citywide average class sizes, aggregated by grade and program type. For grades 5-9 (where available) and 9-12, the data are shown by program type and core course.
Based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
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
series e:abgn-8q46 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K m:number_of_sections=2616 m:average_class_size=22.3 m:number_of_students_seats_filled=58325

series e:abgn-8q46 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=CTT t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K m:number_of_sections=469 m:average_class_size=20.8 m:number_of_students_seats_filled=9751

series e:abgn-8q46 d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=G&T t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K m:number_of_sections=63 m:average_class_size=20.3 m:number_of_students_seats_filled=1282
```

## Meta Commands

```ls
metric m:number_of_students_seats_filled p:integer l:"NUMBER OF STUDENTS / SEATS FILLED" t:dataTypeName=number

metric m:number_of_sections p:integer l:"NUMBER OF SECTIONS" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

entity e:abgn-8q46 l:"2010-2011 Class Size - Citywide Summary" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/abgn-8q46

property e:abgn-8q46 t:meta.view v:id=abgn-8q46 v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - Citywide Summary" v:attribution="Department of Education (DOE)"

property e:abgn-8q46 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:abgn-8q46 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade_ | program_type | core_subject_ms_core_and_9_12_only_ | core_course_ms_core_and_9_12_only_ | service_category_k_9_only_ | number_of_students_seats_filled | number_of_sections | average_class_size | 
| ====== | ============ | =================================== | ================================== | ========================== | =============================== | ================== | ================== | 
| 0K     | GEN ED       | -                                   | -                                  | -                          | 58325                           | 2616               | 22.3               | 
| 0K     | CTT          | -                                   | -                                  | -                          | 9751                            | 469                | 20.8               | 
| 0K     | G&T          | -                                   | -                                  | -                          | 1282                            | 63                 | 20.3               | 
| 01     | GEN ED       | -                                   | -                                  | -                          | 60917                           | 2651               | 23.0               | 
| 01     | CTT          | -                                   | -                                  | -                          | 9276                            | 416                | 22.3               | 
| 01     | G&T          | -                                   | -                                  | -                          | 1647                            | 70                 | 23.5               | 
| 02     | GEN ED       | -                                   | -                                  | -                          | 58163                           | 2497               | 23.3               | 
| 02     | CTT          | -                                   | -                                  | -                          | 9833                            | 432                | 22.8               | 
| 02     | G&T          | -                                   | -                                  | -                          | 1324                            | 57                 | 23.2               | 
| 03     | GEN ED       | -                                   | -                                  | -                          | 56094                           | 2360               | 23.8               | 
```