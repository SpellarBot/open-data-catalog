# 2006-07 Class Size - Citywide Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2006-07-class-size-citywide-summary-41b98) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w49k-mmkh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w49k-mmkh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w49k-mmkh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w49k-mmkh |
| Name | 2006-07 Class Size - Citywide Summary |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-13T17:47:27Z |
| Publication Date | 2011-10-13T17:48:50Z |

## Description

Citywide Average Class Size Report Summary including Program and Grade or Service Category.

SOURCES: 10/31/06 Official Register (K-9) and 12/15/06 Register/Schedule (9-12)
#Grade 9 not in high schools
##Indicates how special class is delivered

For schools with students in any grades between Kindergarten and 9th grade (where 9th grade is the termination grade for the school), class size is reported by four program areas: general education, special education self-contained class, collaborative team teaching and gifted and talented self-contained class. Within each program area class size is reported by grade or service category, which indicates how a special education self-contained class is delivered. Class size is calculated by dividing the number of students in a program and grade by the number of official classes in that program and grade. 

The following data is excluded from all the reports: District 75 schools, bridge classes which span more than one grade, classes with fewer than five students (for other than special education self-contained classes) and classes with one student (for special education self-contained classes). On the summary reports programs and grades with three or fewer classes are excluded from the citywide, borough and region reports and programs and grades with one class are excluded from the district report. For schools with students in any grades between 9th and 12th grade (where 9th grade is not the termination grade for the school), class size is reported by two program areas: general education and special education. For general education students class size is reported by grade for each core subject area: English, Math, Science and Social Studies. For special education students with a self-contained program recommendation, class size is reported by service category (self-contained or mainstream) for each core subject area. Since high school classes may contain students in multiple grades and programs, class size is calculated by taking a weighted average of all the classes in a core subject area with students in a particular grade or program. For example, there are 75 ninth graders enrolled at a high school. 25 ninth graders attend a Math class with 28 students, a second group of 25 ninth graders attend a Math class with 25 students, and a third group of 25 ninth graders attend a Math class with 30 students. Average class size for ninth grade Math equals: (25x28 + 25x25 + 25x30)/75 = 27.7. 

The Pupil Teacher Ratio is also provided on the school level report. Pupil Teacher Ratio is another means to evaluate the instructional resources provided at a school. Pupil Teacher Ratio for All Students is calculated by dividing the number of students at a school by the number of full-time equivalent teachers, including both teachers in classes taught by two teachers, ?cluster? teachers providing instruction in specialized topics like art or science, and teachers providing special education instruction. Pupil Teacher Ratio Excluding Special Education is calculated by dividing the number of non-special education students at a school by the number of full-time equivalent non-special education teachers.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | program                        | PROGRAM                        | text      | text        |
| Yes      | series tag     | grade_or_service_category_     | GRADE OR SERVICE CATEGORY##    | text      | text        |
| Yes      | series tag     | core_course_high_schools_only_ | CORE COURSE(High Schools only) | text      | text        |
| Yes      | numeric metric | average_class_size             | AVERAGE CLASS SIZE             | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w49k-mmkh d:2006-01-01T00:00:00.000Z t:grade_or_service_category_=Kindergarten t:program="GENERAL EDUCATION" m:average_class_size=20.7

series e:w49k-mmkh d:2006-01-01T00:00:00.000Z t:grade_or_service_category_=1 t:program="GENERAL EDUCATION" m:average_class_size=21.3

series e:w49k-mmkh d:2006-01-01T00:00:00.000Z t:grade_or_service_category_=2 t:program="GENERAL EDUCATION" m:average_class_size=21
```

## Meta Commands

```ls
metric m:average_class_size p:float l:"AVERAGE CLASS SIZE" t:dataTypeName=number

entity e:w49k-mmkh l:"2006-07 Class Size - Citywide Summary" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/w49k-mmkh

property e:w49k-mmkh t:meta.view v:id=w49k-mmkh v:category=Education v:averageRating=0 v:name="2006-07 Class Size - Citywide Summary" v:attribution="Department of Education (DOE)"

property e:w49k-mmkh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w49k-mmkh t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| program           | grade_or_service_category_ | core_course_high_schools_only_ | average_class_size | 
| ================= | ========================== | ============================== | ================== | 
| GENERAL EDUCATION | Kindergarten               |                                | 20.7               | 
| GENERAL EDUCATION | 1                          |                                | 21.3               | 
| GENERAL EDUCATION | 2                          |                                | 21.0               | 
| GENERAL EDUCATION | 3                          |                                | 21.2               | 
| GENERAL EDUCATION | 4                          |                                | 23.8               | 
| GENERAL EDUCATION | 5                          |                                | 24.9               | 
| GENERAL EDUCATION | 6                          |                                | 25.7               | 
| GENERAL EDUCATION | 7                          |                                | 27.0               | 
| GENERAL EDUCATION | 8                          |                                | 27.1               | 
| GENERAL EDUCATION | 09#                        |                                | 25.8               | 
```