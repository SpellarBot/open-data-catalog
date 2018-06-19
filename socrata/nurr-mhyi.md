# 2010-2011 Class Size - District-level Distribution

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-district-level-distribution-c3cb0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nurr-mhyi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nurr-mhyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nurr-mhyi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nurr-mhyi |
| Name | 2010-2011 Class Size - District-level Distribution |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T18:33:11Z |
| Publication Date | 2011-10-14T18:34:39Z |

## Description

This file shows citywide average class sizes, aggregated by grade and program type. For grades 5-9 (where available) and 9-12, the data are shown by program type and core course.
Based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                                  | Data Type | Render Type |
| ======== | ============== | ============================================================= | ===================================================================== | ========= | =========== |
| Yes      | series tag     | csd                                                           | CSD                                                                   | text      | text        |
| Yes      | series tag     | borough                                                       | BOROUGH                                                               | text      | text        |
| Yes      | series tag     | grade_level                                                   | GRADE LEVEL                                                           | text      | text        |
| Yes      | series tag     | program_type                                                  | PROGRAM TYPE                                                          | text      | text        |
| Yes      | series tag     | core_subject                                                  | CORE SUBJECT                                                          | text      | text        |
| Yes      | series tag     | service_category                                              | SERVICE CATEGORY                                                      | text      | text        |
| Yes      | numeric metric | class_size                                                    | CLASS SIZE                                                            | number    | number      |
| Yes      | numeric metric | number_of_classes                                             | NUMBER OF CLASSES                                                     | number    | number      |
| Yes      | numeric metric | number_of_students                                            | NUMBER OF STUDENTS                                                    | number    | number      |
| Yes      | series tag     | percent_of_students_in_district_borough_grade_program_subject | PERCENT OF STUDENTS IN DISTRICT / BOROUGH / GRADE / PROGRAM / SUBJECT | text      | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nurr-mhyi d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:csd=01 t:service_category=- t:borough=M t:core_subject=- t:percent_of_students_in_district_borough_grade_program_subject=9.0909090909090917 t:grade_level=0K m:number_of_students=89 m:number_of_classes=7

series e:nurr-mhyi d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:csd=01 t:service_category=- t:borough=M t:core_subject=- t:percent_of_students_in_district_borough_grade_program_subject=1.5321756894790604 t:grade_level=0K m:number_of_students=15 m:class_size=15 m:number_of_classes=1

series e:nurr-mhyi d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:csd=01 t:service_category=- t:borough=M t:core_subject=- t:percent_of_students_in_district_borough_grade_program_subject=5.2093973442288046 t:grade_level=0K m:number_of_students=51 m:class_size=17 m:number_of_classes=3
```

## Meta Commands

```ls
metric m:class_size p:integer l:"CLASS SIZE" t:dataTypeName=number

metric m:number_of_classes p:integer l:"NUMBER OF CLASSES" t:dataTypeName=number

metric m:number_of_students p:integer l:"NUMBER OF STUDENTS" t:dataTypeName=number

entity e:nurr-mhyi l:"2010-2011 Class Size - District-level Distribution" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/nurr-mhyi

property e:nurr-mhyi t:meta.view v:id=nurr-mhyi v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - District-level Distribution" v:attribution="Department of Education (DOE)"

property e:nurr-mhyi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nurr-mhyi t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| csd | borough | grade_level | program_type       | core_subject | service_category | class_size | number_of_classes | number_of_students | percent_of_students_in_district_borough_grade_program_subject | 
| === | ======= | =========== | ================== | ============ | ================ | ========== | ================= | ================== | ============================================================= | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                |            | 7                 | 89                 | 9.0909090909090917                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 15         | 1                 | 15                 | 1.5321756894790604                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 17         | 3                 | 51                 | 5.2093973442288046                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 18         | 1                 | 18                 | 1.8386108273748722                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 19         | 6                 | 114                | 11.644535240040858                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 20         | 5                 | 100                | 10.214504596527069                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 21         | 4                 | 84                 | 8.5801838610827375                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 22         | 4                 | 88                 | 8.9887640449438209                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 23         | 7                 | 161                | 16.445352400408581                                            | 
| 01  | M       | 0K          | GEN ED / CTT / G&T | -            | -                | 25         | 4                 | 100                | 10.214504596527069                                            | 
```