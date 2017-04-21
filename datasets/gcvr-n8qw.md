# New York State Mathematics Exam by School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-mathematics-exam-by-school) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gcvr-n8qw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gcvr-n8qw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gcvr-n8qw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gcvr-n8qw |
| Name | New York State Mathematics Exam by School |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | education, schools, exams, doe |
| Created | 2016-03-11T20:01:53Z |
| Publication Date | 2016-03-11T20:09:41Z |

## Description

(Grades 3 - 8) 
2013 - 2015 
Notes 
Starting in 2013, the NY State Education Department (NYSED) changed the exams to be Common Core aligned. Results on earlier exams from 2006-2012 can be found at this link: http://schools.nyc.gov/NR/exeres/05289E74-2D81-4CC0-81F6-E1143E28F4C4,frameless.htm
Results presented here include all students who sat for either the Math or ELA exam. On the NYSED website, results for "matched" students can be found. To account for participation changes across years and anticipate the importance of year-to-year same-cohort comparisons for the Class of 2022, "matched" Math and ELA results were calculated to include 4th grade students who were tested in both the current and previous year and to include 5th ? 8th grade students who were tested in all three years. 
In order to comply with FERPA regulations on public reporting of education outcomes, rows with 5 or fewer students are suppressed. 
For 2013, District 75 students are represented in their home districts and boroughs. For 2014 & 2015, they are not included. 
Charter schools are not included. School level charter data can be found here: http://schools.nyc.gov/Accountability/data/TestResults/ELAandMathTestResults
In 2007, the New York State Education Department updated its testing policy for English Language Learners: ELLs in an English Language School System for more than one year are required to take the ELA exam. Previously, ELLs in an English Language School System for less than 3 years were exempt from taking the ELA exam. 
A change in State testing policy drove a decrease in eighth grade proficiency rates in 2014: to reduce double testing, most students in accelerated math courses who took the Algebra Regents exam were exempted from taking the 7th or 8th grade State math assessment. 
Former English Language Learners includes any students who were classified as English Language Learners in at least one of the previous two school years.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | dbn              | DBN              | text      | text        |
| Yes      | series tag     | school_name      | School Name      | text      | text        |
| Yes      | series tag     | grade            | Grade            | text      | text        |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | series tag     | category         | Category         | text      | text        |
| Yes      | numeric metric | number_tested    | Number Tested    | number    | number      |
| Yes      | numeric metric | mean_scale_score | Mean Scale Score | number    | number      |
| Yes      | numeric metric | level_1_1        | # Level 1        | number    | number      |
| Yes      | numeric metric | level_1_2        | % Level 1        | number    | number      |
| Yes      | numeric metric | level_2_1        | # Level 2        | number    | number      |
| Yes      | numeric metric | level_2_2        | % Level 2        | number    | number      |
| Yes      | numeric metric | level_3_1        | # Level 3        | number    | number      |
| Yes      | numeric metric | level_3_2        | % Level 3        | number    | number      |
| Yes      | numeric metric | level_4_1        | # Level 4        | number    | number      |
| Yes      | numeric metric | level_4_2        | % Level 4        | number    | number      |
| Yes      | numeric metric | level_3_4_1      | # Level 3+4      | number    | number      |
| Yes      | numeric metric | level_3_4_2      | % Level 3+4      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gcvr-n8qw d:2013-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=0 m:mean_scale_score=278 m:level_2_2=40.7 m:level_4_2=0 m:level_2_1=11 m:level_1_2=59.3 m:level_1_1=16 m:number_tested=27 m:level_3_2=0 m:level_3_4_1=0 m:level_3_1=0

series e:gcvr-n8qw d:2014-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=1 m:level_3_4_2=16.7 m:mean_scale_score=286 m:level_2_2=50 m:level_4_2=5.6 m:level_2_1=9 m:level_1_2=33.3 m:level_1_1=6 m:number_tested=18 m:level_3_2=11.1 m:level_3_4_1=3 m:level_3_1=2

series e:gcvr-n8qw d:2015-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=1 m:level_3_4_2=17.6 m:mean_scale_score=280 m:level_2_2=23.5 m:level_4_2=5.9 m:level_2_1=4 m:level_1_2=58.8 m:level_1_1=10 m:number_tested=17 m:level_3_2=11.8 m:level_3_4_1=3 m:level_3_1=2
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"# Level 1" t:dataTypeName=number

metric m:level_1_2 p:double l:"% Level 1" t:dataTypeName=number

metric m:level_2_1 p:integer l:"# Level 2" t:dataTypeName=number

metric m:level_2_2 p:double l:"% Level 2" t:dataTypeName=number

metric m:level_3_1 p:integer l:"# Level 3" t:dataTypeName=number

metric m:level_3_2 p:double l:"% Level 3" t:dataTypeName=number

metric m:level_4_1 p:integer l:"# Level 4" t:dataTypeName=number

metric m:level_4_2 p:double l:"% Level 4" t:dataTypeName=number

metric m:level_3_4_1 p:integer l:"# Level 3+4" t:dataTypeName=number

metric m:level_3_4_2 p:double l:"% Level 3+4" t:dataTypeName=number

entity e:gcvr-n8qw l:"New York State Mathematics Exam by School" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/gcvr-n8qw

property e:gcvr-n8qw t:meta.view v:id=gcvr-n8qw v:category=Education v:averageRating=0 v:name="New York State Mathematics Exam by School" v:attribution="Department of Education (DOE)"

property e:gcvr-n8qw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gcvr-n8qw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | school_name               | grade      | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========================= | ========== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2013 | All Students | 27            | 278              | 16        | 59.3      | 11        | 40.7      | 0         | 0         | 0         | 0         | 0           | 0           | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2014 | All Students | 18            | 286              | 6         | 33.3      | 9         | 50        | 2         | 11.1      | 1         | 5.6       | 3           | 16.7        | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2015 | All Students | 17            | 280              | 10        | 58.8      | 4         | 23.5      | 2         | 11.8      | 1         | 5.9       | 3           | 17.6        | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2013 | All Students | 20            | 277              | 12        | 60        | 6         | 30        | 1         | 5         | 1         | 5         | 2           | 10          | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2014 | All Students | 24            | 282              | 9         | 37.5      | 14        | 58.3      | 1         | 4.2       | 0         | 0         | 1           | 4.2         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2015 | All Students | 17            | 281              | 8         | 47.1      | 7         | 41.2      | 2         | 11.8      | 0         | 0         | 2           | 11.8        | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2013 | All Students | 24            | 274              | 17        | 70.8      | 6         | 25        | 1         | 4.2       | 0         | 0         | 1           | 4.2         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2014 | All Students | 21            | 266              | 17        | 81        | 2         | 9.5       | 1         | 4.8       | 1         | 4.8       | 2           | 9.5         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2015 | All Students | 24            | 275              | 16        | 66.7      | 6         | 25        | 2         | 8.3       | 0         | 0         | 2           | 8.3         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | All Grades | 2013 | All Students | 71            | 276              | 45        | 63.4      | 23        | 32.4      | 2         | 2.8       | 1         | 1.4       | 3           | 4.2         | 
```