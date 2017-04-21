# 2010-2011 Class Size - Borough Distribution

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-borough-distribution-e69b6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xefy-6ent) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xefy-6ent/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xefy-6ent/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xefy-6ent |
| Name | 2010-2011 Class Size - Borough Distribution |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T16:19:05Z |
| Publication Date | 2011-10-14T16:23:19Z |

## Description

This file shows the range and distribution of class sizes within a particular grade and program type. For grades 5-9 (where available) and 9-12, the data are shown by program type and core subject.

Class size data is based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                       | Data Type | Render Type |
| ======== | ============== | ==================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | borough                                              | BOROUGH                                                    | text      | text        |
| Yes      | series tag     | grade_level                                          | GRADE LEVEL                                                | text      | text        |
| Yes      | series tag     | program_type                                         | PROGRAM TYPE                                               | text      | text        |
| Yes      | series tag     | core_subject                                         | CORE SUBJECT                                               | text      | text        |
| Yes      | series tag     | service_category                                     | SERVICE CATEGORY                                           | text      | text        |
| Yes      | numeric metric | class_size                                           | CLASS SIZE                                                 | number    | number      |
| Yes      | numeric metric | number_of_classes                                    | NUMBER OF CLASSES                                          | number    | number      |
| Yes      | numeric metric | number_of_students                                   | NUMBER OF STUDENTS                                         | number    | number      |
| Yes      | numeric metric | percent_of_students_in_borough_grade_program_subject | PERCENT OF STUDENTS IN BOROUGH / GRADE / PROGRAM / SUBJECT | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xefy-6ent d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:borough=K t:core_subject=- t:grade_level=0K m:number_of_students=329 m:percent_of_students_in_borough_grade_program_subject=1.588604538870111 m:number_of_classes=28

series e:xefy-6ent d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:borough=K t:core_subject=- t:grade_level=0K m:number_of_students=330 m:percent_of_students_in_borough_grade_program_subject=1.5934331240946402 m:class_size=15 m:number_of_classes=22

series e:xefy-6ent d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:borough=K t:core_subject=- t:grade_level=0K m:number_of_students=256 m:percent_of_students_in_borough_grade_program_subject=1.2361178174794785 m:class_size=16 m:number_of_classes=16
```

## Meta Commands

```ls
metric m:class_size p:integer l:"CLASS SIZE" t:dataTypeName=number

metric m:number_of_classes p:integer l:"NUMBER OF CLASSES" t:dataTypeName=number

metric m:number_of_students p:integer l:"NUMBER OF STUDENTS" t:dataTypeName=number

metric m:percent_of_students_in_borough_grade_program_subject p:double l:"PERCENT OF STUDENTS IN BOROUGH / GRADE / PROGRAM / SUBJECT" t:dataTypeName=percent

entity e:xefy-6ent l:"2010-2011 Class Size - Borough Distribution" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/xefy-6ent

property e:xefy-6ent t:meta.view v:id=xefy-6ent v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - Borough Distribution" v:attribution="Department of Education (DOE)"

property e:xefy-6ent t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xefy-6ent t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade_level | program_type       | core_subject | service_category | class_size | number_of_classes | number_of_students | percent_of_students_in_borough_grade_program_subject | 
| ======= | =========== | ================== | ============ | ================ | ========== | ================= | ================== | ==================================================== | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                |            | 28                | 329                | 1.5886045388701111                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 15         | 22                | 330                | 1.5934331240946402                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 16         | 16                | 256                | 1.2361178174794785                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 17         | 37                | 629                | 3.0371801062288752                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 18         | 64                | 1152               | 5.5625301786576538                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 19         | 60                | 1140               | 5.5045871559633035                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 20         | 92                | 1840               | 8.8845968131337525                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 21         | 77                | 1617               | 7.807822308063737                                    | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 22         | 121               | 2662               | 12.853693867696764                                   | 
| K       | 0K          | GEN ED / CTT / G&T | -            | -                | 23         | 100               | 2300               | 11.105746016417189                                   | 
```