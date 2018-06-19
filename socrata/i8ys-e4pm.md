# 2007-08 Class Size - School-level Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2007-08-class-size-school-level-detail-a0bf8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i8ys-e4pm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i8ys-e4pm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i8ys-e4pm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i8ys-e4pm |
| Name | 2007-08 Class Size - School-level Detail |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-13T20:39:36Z |
| Publication Date | 2011-10-13T20:48:07Z |

## Description

This file shows average class sizes and the size of the smallest and largest class for each school, by grade and program type (General Education, Self-Contained Special Education, Collaborative Team Teaching (CTT)) for grades K-9 (where grade 9 is not reported by subject area), and for grades 9-12, aggregated by program type (General Education, CTT, and Self-Contained Special Education) and core course (e.g. English 9, Math A, US History, etc.).
Data as of January 23, 2008
*Where ninth grade data is not reported by grade

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | boro                                  | BORO                                  | text      | text        |
| Yes      | numeric metric | csd                                   | CSD                                   | number    | number      |
| Yes      | series tag     | school_code                           | SCHOOL CODE                           | text      | text        |
| Yes      | series tag     | school_name                           | SCHOOL NAME                           | text      | text        |
| Yes      | series tag     | grade                                 | GRADE                                 | text      | text        |
| Yes      | series tag     | program_type                          | PROGRAM TYPE                          | text      | text        |
| Yes      | series tag     | core_subject_9_12_only_               | CORE SUBJECT(9-12 ONLY)               | text      | text        |
| Yes      | series tag     | core_course_9_12_only_                | CORE COURSE(9-12 ONLY)                | text      | text        |
| Yes      | series tag     | service_category_k_9_only_            | SERVICE CATEGORY(K-9 ONLY)            | text      | text        |
| Yes      | numeric metric | number_of_classes                     | NUMBER OF CLASSES                     | number    | number      |
| Yes      | numeric metric | total_register_as_of_1_23_08_         | TOTAL REGISTER(as of 1-23-08)         | number    | number      |
| Yes      | numeric metric | average_class_size                    | AVERAGE CLASS SIZE                    | number    | number      |
| Yes      | numeric metric | size_of_smallest_class_as_of_1_23_08_ | SIZE OF SMALLEST CLASS(as of 1-23-08) | number    | number      |
| Yes      | numeric metric | size_of_largest_class_as_of_1_23_08_  | SIZE OF LARGEST CLASS(as of 1-23-08)  | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i8ys-e4pm d:2007-01-01T00:00:00.000Z t:program_type="GEN ED" t:core_course_9_12_only_=- t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:grade=0K t:core_subject_9_12_only_=- t:school_code=M015 m:size_of_largest_class_as_of_1_23_08_=21 m:csd=1 m:average_class_size=21 m:total_register_as_of_1_23_08_=21 m:size_of_smallest_class_as_of_1_23_08_=21 m:number_of_classes=1

series e:i8ys-e4pm d:2007-01-01T00:00:00.000Z t:program_type=CTT t:core_course_9_12_only_=- t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:grade=0K t:core_subject_9_12_only_=- t:school_code=M015 m:size_of_largest_class_as_of_1_23_08_=24 m:csd=1 m:average_class_size=24 m:total_register_as_of_1_23_08_=24 m:size_of_smallest_class_as_of_1_23_08_=24 m:number_of_classes=1

series e:i8ys-e4pm d:2007-01-01T00:00:00.000Z t:program_type="GEN ED" t:core_course_9_12_only_=- t:boro=M t:school_name="P.S. 015 ROBERTO CLEMENTE" t:service_category_k_9_only_=- t:grade=01 t:core_subject_9_12_only_=- t:school_code=M015 m:size_of_largest_class_as_of_1_23_08_=19 m:csd=1 m:average_class_size=18.5 m:total_register_as_of_1_23_08_=37 m:size_of_smallest_class_as_of_1_23_08_=18 m:number_of_classes=2
```

## Meta Commands

```ls
metric m:csd p:integer l:CSD t:dataTypeName=number

metric m:number_of_classes p:integer l:"NUMBER OF CLASSES" t:dataTypeName=number

metric m:total_register_as_of_1_23_08_ p:integer l:"TOTAL REGISTER(as of 1-23-08)" t:dataTypeName=number

metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

metric m:size_of_smallest_class_as_of_1_23_08_ p:integer l:"SIZE OF SMALLEST CLASS(as of 1-23-08)" t:dataTypeName=number

metric m:size_of_largest_class_as_of_1_23_08_ p:integer l:"SIZE OF LARGEST CLASS(as of 1-23-08)" t:dataTypeName=number

entity e:i8ys-e4pm l:"2007-08 Class Size - School-level Detail" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/i8ys-e4pm

property e:i8ys-e4pm t:meta.view v:id=i8ys-e4pm v:category=Education v:averageRating=0 v:name="2007-08 Class Size - School-level Detail" v:attribution="Department of Education (DOE)"

property e:i8ys-e4pm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i8ys-e4pm t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| boro | csd | school_code | school_name               | grade | program_type | core_subject_9_12_only_ | core_course_9_12_only_ | service_category_k_9_only_ | number_of_classes | total_register_as_of_1_23_08_ | average_class_size | size_of_smallest_class_as_of_1_23_08_ | size_of_largest_class_as_of_1_23_08_ | 
| ==== | === | =========== | ========================= | ===== | ============ | ======================= | ====================== | ========================== | ================= | ============================= | ================== | ===================================== | ==================================== | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K    | GEN ED       | -                       | -                      | -                          | 1                 | 21                            | 21.0               | 21                                    | 21                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K    | CTT          | -                       | -                      | -                          | 1                 | 24                            | 24.0               | 24                                    | 24                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 01    | GEN ED       | -                       | -                      | -                          | 2                 | 37                            | 18.5               | 18                                    | 19                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 02    | GEN ED       | -                       | -                      | -                          | 2                 | 36                            | 18.0               | 17                                    | 19                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 03    | GEN ED       | -                       | -                      | -                          | 2                 | 38                            | 19.0               | 19                                    | 19                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 04    | GEN ED       | -                       | -                      | -                          | 2                 | 40                            | 20.0               | 19                                    | 21                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 05    | GEN ED       | -                       | -                      | -                          | 1                 | 12                            | 12.0               | 12                                    | 12                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 05    | CTT          | -                       | -                      | -                          | 1                 | 23                            | 23.0               | 23                                    | 23                                   | 
| M    | 1   | M015        | P.S. 015 ROBERTO CLEMENTE | 0K-09 | SPEC ED      | -                       | -                      | 12:1:1                     | 1                 | 12                            | 12.0               | 12                                    | 12                                   | 
| M    | 1   | M019        | P.S. 019 ASHER LEVY       | 0K    | GEN ED       | -                       | -                      | -                          | 2                 | 39                            | 19.5               | 17                                    | 22                                   | 
```