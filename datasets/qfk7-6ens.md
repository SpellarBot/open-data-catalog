# 2006-07 Class Size - School-level Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2006-07-class-size-school-level-detail-383c2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qfk7-6ens) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qfk7-6ens/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qfk7-6ens/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qfk7-6ens |
| Name | 2006-07 Class Size - School-level Detail |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-13T17:32:27Z |
| Publication Date | 2011-10-13T17:38:04Z |

## Description

Citywide Class Size Report, including Region, District, School, Program, Grade or Service Category, Average Class Size, and Pupil / Teacher Ratio (PTR) 

SOURCES: 10/31/06 Official Register (K-9) and 12/15/06 Register/Schedule (9-12)
#Grade 9 not in high schools
##Indicates how special class is delivered

For schools with students in any grades between Kindergarten and 9th grade (where 9th grade is the termination grade for the school), class size is reported by four program areas: general education, special education self-contained class, collaborative team teaching and gifted and talented self-contained class. Within each program area class size is reported by grade or service category, which indicates how a special education self-contained class is delivered. Class size is calculated by dividing the number of students in a program and grade by the number of official classes in that program and grade. 

The following data is excluded from all the reports: District 75 schools, bridge classes which span more than one grade, classes with fewer than five students (for other than special education self-contained classes) and classes with one student (for special education self-contained classes). On the summary reports programs and grades with three or fewer classes are excluded from the citywide, borough and region reports and programs and grades with one class are excluded from the district report. For schools with students in any grades between 9th and 12th grade (where 9th grade is not the termination grade for the school), class size is reported by two program areas: general education and special education. For general education students class size is reported by grade for each core subject area: English, Math, Science and Social Studies. For special education students with a self-contained program recommendation, class size is reported by service category (self-contained or mainstream) for each core subject area. Since high school classes may contain students in multiple grades and programs, class size is calculated by taking a weighted average of all the classes in a core subject area with students in a particular grade or program. For example, there are 75 ninth graders enrolled at a high school. 25 ninth graders attend a Math class with 28 students, a second group of 25 ninth graders attend a Math class with 25 students, and a third group of 25 ninth graders attend a Math class with 30 students. Average class size for ninth grade Math equals: (25x28 + 25x25 + 25x30)/75 = 27.7. 

The Pupil Teacher Ratio is also provided on the school level report. Pupil Teacher Ratio is another means to evaluate the instructional resources provided at a school. Pupil Teacher Ratio for All Students is calculated by dividing the number of students at a school by the number of full-time equivalent teachers, including both teachers in classes taught by two teachers, ?cluster? teachers providing instruction in specialized topics like art or science, and teachers providing special education instruction. Pupil Teacher Ratio Excluding Special Education is calculated by dividing the number of non-special education students at a school by the number of full-time equivalent non-special education teachers.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                      | Data Type | Render Type |
| ======== | ============== | ==================================== | ========================================= | ========= | =========== |
| Yes      | series tag     | region                               | REGION                                    | text      | number      |
| Yes      | series tag     | empowerment_school                   | Empowerment School                        | text      | text        |
| Yes      | series tag     | district                             | DISTRICT                                  | text      | number      |
| Yes      | numeric metric | school                               | SCHOOL                                    | number    | number      |
| Yes      | series tag     | name                                 | NAME                                      | text      | text        |
| Yes      | series tag     | program                              | PROGRAM                                   | text      | text        |
| Yes      | series tag     | grade_or_service_category_           | GRADE OR SERVICE CATEGORY##               | text      | text        |
| Yes      | series tag     | core_course_high_schools_only_       | CORE COURSE(High Schools only)            | text      | text        |
| Yes      | numeric metric | avg_class_size                       | AVG CLASS SIZE                            | number    | number      |
| Yes      | numeric metric | pupil_teacher_ratio_ptr_all_students | Pupil / Teacher Ratio (PTR): All Students | number    | number      |
| Yes      | numeric metric | ptr_excluding_special_ed             | PTR: Excluding Special Ed                 | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qfk7-6ens d:2006-01-01T00:00:00.000Z t:region=1 t:grade_or_service_category_=Kindergarten t:program="GENERAL EDUCATION" t:name="PS 002 MORRISANIA" t:district=9 m:avg_class_size=18 m:school=2

series e:qfk7-6ens d:2006-01-01T00:00:00.000Z t:region=1 t:grade_or_service_category_=1 t:program="GENERAL EDUCATION" t:name="PS 002 MORRISANIA" t:district=9 m:avg_class_size=17 m:school=2

series e:qfk7-6ens d:2006-01-01T00:00:00.000Z t:region=1 t:grade_or_service_category_=2 t:program="GENERAL EDUCATION" t:name="PS 002 MORRISANIA" t:district=9 m:avg_class_size=23 m:school=2
```

## Meta Commands

```ls
metric m:school p:integer l:SCHOOL t:dataTypeName=number

metric m:avg_class_size p:float l:"AVG CLASS SIZE" t:dataTypeName=number

metric m:pupil_teacher_ratio_ptr_all_students p:double l:"Pupil / Teacher Ratio (PTR): All Students" t:dataTypeName=number

metric m:ptr_excluding_special_ed p:double l:"PTR: Excluding Special Ed" t:dataTypeName=number

entity e:qfk7-6ens l:"2006-07 Class Size - School-level Detail" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qfk7-6ens

property e:qfk7-6ens t:meta.view v:id=qfk7-6ens v:category=Education v:averageRating=0 v:name="2006-07 Class Size - School-level Detail" v:attribution="Department of Education (DOE)"

property e:qfk7-6ens t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qfk7-6ens t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| region | empowerment_school | district | school | name              | program                     | grade_or_service_category_ | core_course_high_schools_only_ | avg_class_size | pupil_teacher_ratio_ptr_all_students | ptr_excluding_special_ed | 
| ====== | ================== | ======== | ====== | ================= | =========================== | ========================== | ============================== | ============== | ==================================== | ======================== | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | Kindergarten               |                                | 18.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | 1                          |                                | 17.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | 2                          |                                | 23.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | 3                          |                                | 20.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | 4                          |                                | 19.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | GENERAL EDUCATION           | 5                          |                                | 16.5           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | SPECIAL CLASS - Grades K-9# | 12:1                       |                                | 11.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | SPECIAL CLASS - Grades K-9# | 12:1:1                     |                                | 12.3           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | COLLABORATIVE TEAM TEACHING | Kindergarten               |                                | 21.0           |                                      |                          | 
| 1      |                    | 9        | 2      | PS 002 MORRISANIA | COLLABORATIVE TEAM TEACHING | 5                          |                                | 19.0           |                                      |                          | 
```