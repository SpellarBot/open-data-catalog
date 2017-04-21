# 2010-2011 Class Size - Citywide Distribution

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-2011-class-size-citywide-distribution-d2c90) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4s7y-vm5x) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4s7y-vm5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4s7y-vm5x/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4s7y-vm5x |
| Name | 2010-2011 Class Size - Citywide Distribution |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-14T17:52:34Z |
| Publication Date | 2011-10-14T17:55:16Z |

## Description

This file shows the range and distribution of class sizes within a particular grade and program type. For grades 5-9 (where available) and 9-12, the data are shown by program type and core subject.
Based on January 28, 2011 data.
* Grade 9 Official Class data is included for 0K-09 schools. Core Course information for these sections is not reported.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                             | Data Type | Render Type |
| ======== | ============== | ============================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | grade_level                                  | GRADE LEVEL                                      | text      | text        |
| Yes      | series tag     | program_type                                 | PROGRAM TYPE                                     | text      | text        |
| Yes      | series tag     | core_subject                                 | CORE SUBJECT                                     | text      | text        |
| Yes      | series tag     | service_category                             | SERVICE CATEGORY                                 | text      | text        |
| Yes      | numeric metric | class_size                                   | CLASS SIZE                                       | number    | number      |
| Yes      | numeric metric | number_of_classes                            | NUMBER OF CLASSES                                | number    | number      |
| Yes      | numeric metric | number_of_students                           | NUMBER OF STUDENTS                               | number    | number      |
| Yes      | numeric metric | percent_of_students_in_program_grade_subject | PERCENT OF STUDENTS IN PROGRAM / GRADE / SUBJECT | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4s7y-vm5x d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:core_subject=- t:grade_level=0K m:number_of_students=1100 m:percent_of_students_in_program_grade_subject=1.5859742207099397 m:number_of_classes=94

series e:4s7y-vm5x d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:core_subject=- t:grade_level=0K m:number_of_students=690 m:class_size=15 m:percent_of_students_in_program_grade_subject=0.9948383748089621 m:number_of_classes=46

series e:4s7y-vm5x d:2010-01-01T00:00:00.000Z t:program_type="GEN ED / CTT / G&T" t:service_category=- t:core_subject=- t:grade_level=0K m:number_of_students=944 m:class_size=16 m:percent_of_students_in_program_grade_subject=1.3610542403183483 m:number_of_classes=59
```

## Meta Commands

```ls
metric m:class_size p:integer l:"CLASS SIZE" t:dataTypeName=number

metric m:number_of_classes p:integer l:"NUMBER OF CLASSES" t:dataTypeName=number

metric m:number_of_students p:integer l:"NUMBER OF STUDENTS" t:dataTypeName=number

metric m:percent_of_students_in_program_grade_subject p:double l:"PERCENT OF STUDENTS IN PROGRAM / GRADE / SUBJECT" t:dataTypeName=percent

entity e:4s7y-vm5x l:"2010-2011 Class Size - Citywide Distribution" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/4s7y-vm5x

property e:4s7y-vm5x t:meta.view v:id=4s7y-vm5x v:category=Education v:averageRating=0 v:name="2010-2011 Class Size - Citywide Distribution" v:attribution="Department of Education (DOE)"

property e:4s7y-vm5x t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4s7y-vm5x t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade_level | program_type       | core_subject | service_category | class_size | number_of_classes | number_of_students | percent_of_students_in_program_grade_subject | 
| =========== | ================== | ============ | ================ | ========== | ================= | ================== | ============================================ | 
| 0K          | GEN ED / CTT / G&T | -            | -                |            | 94                | 1100               | 1.5859742207099397                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 15         | 46                | 690                | 0.99483837480896209                          | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 16         | 59                | 944                | 1.3610542403183483                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 17         | 104               | 1768               | 2.5490931111047033                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 18         | 149               | 2682               | 3.8668935090400529                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 19         | 185               | 3515               | 5.067908532541308                            | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 20         | 263               | 5260               | 7.5838403644857122                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 21         | 279               | 5859               | 8.4474754173995787                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 22         | 338               | 7436               | 10.721185731999192                           | 
| 0K          | GEN ED / CTT / G&T | -            | -                | 23         | 374               | 8602               | 12.402318405951728                           | 
```