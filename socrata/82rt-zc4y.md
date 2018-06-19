# 2010-2011 Class Size - District-level Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-district-level-summary-f0000) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/82rt-zc4y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/82rt-zc4y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/82rt-zc4y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 82rt-zc4y |
| Name | 2010-2011 Class Size - District-level Summary |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T21:12:51Z |
| Publication Date | 2011-10-14T21:17:12Z |

## Description

This file shows average class size for each district, broken out by program type (General Education, Self-Contained Special Education, Collaborative Team Teaching (CTT)) for grades K-9 (where grade 9 is not reported by subject area), and for grades 5-9 (where available) and 9-12, aggregated by program type (General Education, CTT, and Self-Contained Special Education) and core course (e.g. English 9, Integrated Algebra, US History, etc.).
Based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
| Yes      | numeric metric | csd                                 | CSD                                  | number    | number      |
| Yes      | series tag     | boro                                | BORO                                 | text      | text        |
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
series e:82rt-zc4y d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:boro=M t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K m:csd=1 m:number_of_sections=39 m:average_class_size=20.3 m:number_of_students_seats_filled=792

series e:82rt-zc4y d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type=CTT t:boro=M t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=0K m:csd=1 m:number_of_sections=9 m:average_class_size=20.8 m:number_of_students_seats_filled=187

series e:82rt-zc4y d:2010-01-01T00:00:00.000Z t:core_subject_ms_core_and_9_12_only_=- t:program_type="GEN ED" t:boro=M t:service_category_k_9_only_=- t:core_course_ms_core_and_9_12_only_=- t:grade_=01 m:csd=1 m:number_of_sections=33 m:average_class_size=20.1 m:number_of_students_seats_filled=662
```

## Meta Commands

```ls
metric m:csd p:integer l:CSD t:dataTypeName=number

metric m:number_of_students_seats_filled p:integer l:"NUMBER OF STUDENTS / SEATS FILLED" t:dataTypeName=number

metric m:number_of_sections p:integer l:"NUMBER OF SECTIONS" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

entity e:82rt-zc4y l:"2010-2011 Class Size - District-level Summary" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/82rt-zc4y

property e:82rt-zc4y t:meta.view v:id=82rt-zc4y v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - District-level Summary" v:attribution="Department of Education (DOE)"

property e:82rt-zc4y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:82rt-zc4y t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| csd | boro | grade_ | program_type | core_subject_ms_core_and_9_12_only_ | core_course_ms_core_and_9_12_only_ | service_category_k_9_only_ | number_of_students_seats_filled | number_of_sections | average_class_size | 
| === | ==== | ====== | ============ | =================================== | ================================== | ========================== | =============================== | ================== | ================== | 
| 1   | M    | 0K     | GEN ED       | -                                   | -                                  | -                          | 792                             | 39                 | 20.3               | 
| 1   | M    | 0K     | CTT          | -                                   | -                                  | -                          | 187                             | 9                  | 20.8               | 
| 1   | M    | 01     | GEN ED       | -                                   | -                                  | -                          | 662                             | 33                 | 20.1               | 
| 1   | M    | 01     | CTT          | -                                   | -                                  | -                          | 208                             | 11                 | 18.9               | 
| 1   | M    | 01     | G&T          | -                                   | -                                  | -                          | 25                              | 1                  | 25.0               | 
| 1   | M    | 02     | GEN ED       | -                                   | -                                  | -                          | 560                             | 28                 | 20.0               | 
| 1   | M    | 02     | CTT          | -                                   | -                                  | -                          | 225                             | 12                 | 18.8               | 
| 1   | M    | 03     | GEN ED       | -                                   | -                                  | -                          | 678                             | 36                 | 18.8               | 
| 1   | M    | 03     | CTT          | -                                   | -                                  | -                          | 131                             | 8                  | 16.4               | 
| 1   | M    | 04     | GEN ED       | -                                   | -                                  | -                          | 548                             | 29                 | 18.9               | 
```