# New York State English Language Arts (ELA) Exam

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-english-language-arts-ela-exam) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/26kp-bgdh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/26kp-bgdh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/26kp-bgdh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 26kp-bgdh |
| Name | New York State English Language Arts (ELA) Exam |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | ela, exam, english, education |
| Created | 2016-03-08T22:02:17Z |
| Publication Date | 2016-03-08T22:08:59Z |

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
series e:26kp-bgdh d:2013-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=20 m:level_3_4_2=6.9 m:mean_scale_score=276 m:level_2_2=27.9 m:level_4_2=0.2 m:level_2_1=3100 m:level_1_2=65.3 m:level_1_1=7261 m:number_tested=11123 m:level_3_2=6.7 m:level_3_4_1=762 m:level_3_1=742

series e:26kp-bgdh d:2014-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=19 m:level_3_4_2=7.1 m:mean_scale_score=270 m:level_2_2=23.2 m:level_4_2=0.2 m:level_2_1=2143 m:level_1_2=69.7 m:level_1_1=6443 m:number_tested=9241 m:level_3_2=6.9 m:level_3_4_1=655 m:level_3_1=636

series e:26kp-bgdh d:2015-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=53 m:level_3_4_2=8 m:mean_scale_score=272 m:level_2_2=24 m:level_4_2=0.6 m:level_2_1=2293 m:level_1_2=68.1 m:level_1_1=6505 m:number_tested=9559 m:level_3_2=7.4 m:level_3_4_1=761 m:level_3_1=708
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"# Level 1" t:dataTypeName=number

metric m:level_1_2 p:double l:"% Level 1" t:dataTypeName=number

metric m:level_2_1 p:integer l:"# Level 2" t:dataTypeName=number

metric m:level_2_2 p:float l:"% Level 2" t:dataTypeName=number

metric m:level_3_1 p:integer l:"# Level 3" t:dataTypeName=number

metric m:level_3_2 p:float l:"% Level 3" t:dataTypeName=number

metric m:level_4_1 p:integer l:"# Level 4" t:dataTypeName=number

metric m:level_4_2 p:float l:"% Level 4" t:dataTypeName=number

metric m:level_3_4_1 p:integer l:"# Level 3+4" t:dataTypeName=number

metric m:level_3_4_2 p:float l:"% Level 3+4" t:dataTypeName=number

entity e:26kp-bgdh l:"New York State English Language Arts (ELA) Exam" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/26kp-bgdh

property e:26kp-bgdh t:meta.view v:id=26kp-bgdh v:category=Education v:averageRating=0 v:name="New York State English Language Arts (ELA) Exam" v:attribution="Department of Education (DOE)"

property e:26kp-bgdh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:26kp-bgdh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3     | 2013 | ELL      | 11123         | 276              | 7261      | 65.3      | 3100      | 27.9      | 742       | 6.7       | 20        | 0.2       | 762         | 6.9         | 
| 3     | 2014 | ELL      | 9241          | 270              | 6443      | 69.7      | 2143      | 23.2      | 636       | 6.9       | 19        | 0.2       | 655         | 7.1         | 
| 3     | 2015 | ELL      | 9559          | 272              | 6505      | 68.1      | 2293      | 24        | 708       | 7.4       | 53        | 0.6       | 761         | 8           | 
| 4     | 2013 | ELL      | 9429          | 267              | 6441      | 68.3      | 2644      | 28        | 305       | 3.2       | 39        | 0.4       | 344         | 3.6         | 
| 4     | 2014 | ELL      | 9768          | 270              | 6505      | 66.6      | 2688      | 27.5      | 506       | 5.2       | 69        | 0.7       | 575         | 5.9         | 
| 4     | 2015 | ELL      | 8757          | 270              | 5701      | 65.1      | 2462      | 28.1      | 498       | 5.7       | 96        | 1.1       | 594         | 6.8         | 
| 5     | 2013 | ELL      | 9439          | 270              | 6673      | 70.7      | 2386      | 25.3      | 344       | 3.6       | 36        | 0.4       | 380         | 4           | 
| 5     | 2014 | ELL      | 8062          | 264              | 6195      | 76.8      | 1639      | 20.3      | 188       | 2.3       | 40        | 0.5       | 228         | 2.8         | 
| 5     | 2015 | ELL      | 7958          | 263              | 5953      | 74.8      | 1713      | 21.5      | 256       | 3.2       | 36        | 0.5       | 292         | 3.7         | 
| 6     | 2013 | ELL      | 7224          | 258              | 5823      | 80.6      | 1307      | 18.1      | 73        | 1         | 21        | 0.3       | 94          | 1.3         | 
```