# English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-district-by-english-proficiency--93c56) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/87y3-sqsx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/87y3-sqsx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/87y3-sqsx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 87y3-sqsx |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:28:29Z |
| Publication Date | 2011-10-11T18:05:15Z |

## Description

New York City Results on the New York State English Language Arts (ELA) Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.
In 2007, the New York State Education Department updated its testing policy for English Language Learners: ELLs in an English Language School System for more than one year are required to take the ELA exam. Previously, ELLs in an English Language School System for less than 3 years were exempt from taking the ELA exam.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | district         | District         | text      | text        |
| Yes      | series tag     | grade            | Grade            | text      | text        |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | series tag     | category         | Category         | text      | text        |
| Yes      | numeric metric | number_tested    | Number Tested    | number    | number      |
| Yes      | numeric metric | mean_scale_score | Mean Scale Score | number    | number      |
| Yes      | numeric metric | level_1_1        | Level 1 #        | number    | number      |
| Yes      | numeric metric | level_1_2        | Level 1 %        | percent   | percent     |
| Yes      | numeric metric | level_2_1        | Level 2 #        | number    | number      |
| Yes      | numeric metric | level_2_2        | Level 2 %        | percent   | percent     |
| Yes      | numeric metric | level_3_1        | Level 3 #        | number    | number      |
| Yes      | numeric metric | level_3_2        | Level 3 %        | percent   | percent     |
| Yes      | numeric metric | level_4_1        | Level 4 #        | number    | number      |
| Yes      | numeric metric | level_4_2        | Level 4 %        | percent   | percent     |
| Yes      | numeric metric | level_3_4_1      | Level 3+4 #      | number    | number      |
| Yes      | numeric metric | level_3_4_2      | Level 3+4 %      | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:87y3-sqsx d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:district=1 m:level_4_1=4 m:level_3_4_2=60 m:mean_scale_score=660 m:level_2_2=25 m:level_4_2=6.7 m:level_2_1=15 m:level_1_2=15 m:level_1_1=9 m:number_tested=60 m:level_3_2=53.3 m:level_3_4_1=36 m:level_3_1=32

series e:87y3-sqsx d:2006-01-01T00:00:00.000Z t:category=EP t:grade=3 t:district=1 m:level_4_1=38 m:level_3_4_2=62.7 m:mean_scale_score=663 m:level_2_2=26.8 m:level_4_2=5.1 m:level_2_1=200 m:level_1_2=10.6 m:level_1_1=79 m:number_tested=747 m:level_3_2=57.6 m:level_3_4_1=468 m:level_3_1=430

series e:87y3-sqsx d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=4 t:district=1 m:level_4_1=2 m:level_3_4_2=58.8 m:mean_scale_score=650 m:level_2_2=19.1 m:level_4_2=2.9 m:level_2_1=13 m:level_1_2=22.1 m:level_1_1=15 m:number_tested=68 m:level_3_2=55.9 m:level_3_4_1=40 m:level_3_1=38
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"Level 1 #" t:dataTypeName=number

metric m:level_1_2 p:float l:"Level 1 %" t:dataTypeName=percent

metric m:level_2_1 p:integer l:"Level 2 #" t:dataTypeName=number

metric m:level_2_2 p:float l:"Level 2 %" t:dataTypeName=percent

metric m:level_3_1 p:integer l:"Level 3 #" t:dataTypeName=number

metric m:level_3_2 p:float l:"Level 3 %" t:dataTypeName=percent

metric m:level_4_1 p:integer l:"Level 4 #" t:dataTypeName=number

metric m:level_4_2 p:float l:"Level 4 %" t:dataTypeName=percent

metric m:level_3_4_1 p:integer l:"Level 3+4 #" t:dataTypeName=number

metric m:level_3_4_2 p:float l:"Level 3+4 %" t:dataTypeName=percent

entity e:87y3-sqsx l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/87y3-sqsx

property e:87y3-sqsx t:meta.view v:id=87y3-sqsx v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:87y3-sqsx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:87y3-sqsx t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | ELL      | 60            | 660              | 9         | 15.0      | 15        | 25.0      | 32        | 53.3      | 4         | 6.7       | 36          | 60.0        | 
| 1        | 3     | 2006 | EP       | 747           | 663              | 79        | 10.6      | 200       | 26.8      | 430       | 57.6      | 38        | 5.1       | 468         | 62.7        | 
| 1        | 4     | 2006 | ELL      | 68            | 650              | 15        | 22.1      | 13        | 19.1      | 38        | 55.9      | 2         | 2.9       | 40          | 58.8        | 
| 1        | 4     | 2006 | EP       | 748           | 654              | 87        | 11.6      | 259       | 34.6      | 365       | 48.8      | 37        | 4.9       | 402         | 53.7        | 
| 1        | 5     | 2006 | ELL      | 71            | 633              | 16        | 22.5      | 31        | 43.7      | 20        | 28.2      | 4         | 5.6       | 24          | 33.8        | 
| 1        | 5     | 2006 | EP       | 679           | 653              | 51        | 7.5       | 255       | 37.6      | 322       | 47.4      | 51        | 7.5       | 373         | 54.9        | 
| 1        | 6     | 2006 | ELL      | 64            | 632              | 13        | 20.3      | 22        | 34.4      | 25        | 39.1      | 4         | 6.3       | 29          | 45.3        | 
| 1        | 6     | 2006 | EP       | 791           | 654              | 45        | 5.7       | 324       | 41.0      | 338       | 42.7      | 84        | 10.6      | 422         | 53.4        | 
| 1        | 7     | 2006 | ELL      | 66            | 615              | 14        | 21.2      | 41        | 62.1      | 11        | 16.7      | 0         | 0.0       | 11          | 16.7        | 
| 1        | 7     | 2006 | EP       | 852           | 648              | 70        | 8.2       | 384       | 45.1      | 330       | 38.7      | 68        | 8.0       | 398         | 46.7        | 
```