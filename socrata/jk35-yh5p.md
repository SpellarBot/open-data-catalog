# New York State English Language Arts (ELA) Exam by School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-english-language-arts-ela-exam-by-school) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jk35-yh5p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jk35-yh5p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jk35-yh5p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jk35-yh5p |
| Name | New York State English Language Arts (ELA) Exam by School |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | ela, education, schools, exams, doe |
| Created | 2016-03-11T19:53:32Z |
| Publication Date | 2016-03-11T20:02:05Z |

## Description

NEW YORK CITY Results on the NEW YORK STATE English Language Arts (ELA) & Mathematics Exams
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
series e:jk35-yh5p d:2013-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=7.4 m:mean_scale_score=289 m:level_2_2=40.7 m:level_4_2=0 m:level_2_1=11 m:level_1_2=51.9 m:level_1_1=14 m:number_tested=27 m:level_3_2=7.4 m:level_3_4_1=2 m:level_3_1=2

series e:jk35-yh5p d:2014-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=0 m:mean_scale_score=285 m:level_2_2=44.4 m:level_4_2=0 m:level_2_1=8 m:level_1_2=55.6 m:level_1_1=10 m:number_tested=18 m:level_3_2=0 m:level_3_4_1=0 m:level_3_1=0

series e:jk35-yh5p d:2015-01-01T00:00:00.000Z t:category="All Students" t:school_name="P.S. 015 ROBERTO CLEMENTE" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=12.5 m:mean_scale_score=282 m:level_2_2=31.3 m:level_4_2=0 m:level_2_1=5 m:level_1_2=56.3 m:level_1_1=9 m:number_tested=16 m:level_3_2=12.5 m:level_3_4_1=2 m:level_3_1=2
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

entity e:jk35-yh5p l:"New York State English Language Arts (ELA) Exam by School" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/jk35-yh5p

property e:jk35-yh5p t:meta.view v:id=jk35-yh5p v:category=Education v:averageRating=0 v:name="New York State English Language Arts (ELA) Exam by School" v:attribution="Department of Education (DOE)"

property e:jk35-yh5p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jk35-yh5p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | school_name               | grade      | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========================= | ========== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2013 | All Students | 27            | 289              | 14        | 51.9      | 11        | 40.7      | 2         | 7.4       | 0         | 0         | 2           | 7.4         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2014 | All Students | 18            | 285              | 10        | 55.6      | 8         | 44.4      | 0         | 0         | 0         | 0         | 0           | 0           | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 3          | 2015 | All Students | 16            | 282              | 9         | 56.3      | 5         | 31.3      | 2         | 12.5      | 0         | 0         | 2           | 12.5        | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2013 | All Students | 20            | 278              | 8         | 40        | 11        | 55        | 1         | 5         | 0         | 0         | 1           | 5           | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2014 | All Students | 24            | 284              | 13        | 54.2      | 10        | 41.7      | 1         | 4.2       | 0         | 0         | 1           | 4.2         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 4          | 2015 | All Students | 16            | 288              | 5         | 31.3      | 11        | 68.8      | 0         | 0         | 0         | 0         | 0           | 0           | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2013 | All Students | 24            | 284              | 12        | 50        | 11        | 45.8      | 1         | 4.2       | 0         | 0         | 1           | 4.2         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2014 | All Students | 21            | 268              | 15        | 71.4      | 5         | 23.8      | 0         | 0         | 1         | 4.8       | 1           | 4.8         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | 5          | 2015 | All Students | 24            | 281              | 14        | 58.3      | 9         | 37.5      | 1         | 4.2       | 0         | 0         | 1           | 4.2         | 
| 01M015 | P.S. 015 ROBERTO CLEMENTE | All Grades | 2013 | All Students | 71            | 284              | 34        | 47.9      | 33        | 46.5      | 4         | 5.6       | 0         | 0         | 4           | 5.6         | 
```