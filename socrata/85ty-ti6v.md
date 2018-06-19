# English Language Arts (ELA) Test Results by Grade 2006-2011 - District - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-district-all-students-a6deb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/85ty-ti6v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/85ty-ti6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/85ty-ti6v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 85ty-ti6v |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - District - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:22:53Z |
| Publication Date | 2011-10-11T18:04:43Z |

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
series e:85ty-ti6v d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:district=1 m:level_4_1=42 m:level_3_4_2=62.4 m:mean_scale_score=663 m:level_2_2=26.6 m:level_4_2=5.2 m:level_2_1=215 m:level_1_2=11 m:level_1_1=89 m:number_tested=808 m:level_3_2=57.2 m:level_3_4_1=504 m:level_3_1=462

series e:85ty-ti6v d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=4 t:district=1 m:level_4_1=39 m:level_3_4_2=54.2 m:mean_scale_score=654 m:level_2_2=33.2 m:level_4_2=4.8 m:level_2_1=272 m:level_1_2=12.6 m:level_1_1=103 m:number_tested=819 m:level_3_2=49.5 m:level_3_4_1=444 m:level_3_1=405

series e:85ty-ti6v d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=5 t:district=1 m:level_4_1=55 m:level_3_4_2=52.9 m:mean_scale_score=651 m:level_2_2=38.1 m:level_4_2=7.3 m:level_2_1=286 m:level_1_2=9.1 m:level_1_1=68 m:number_tested=751 m:level_3_2=45.5 m:level_3_4_1=397 m:level_3_1=342
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

entity e:85ty-ti6v l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - District - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/85ty-ti6v

property e:85ty-ti6v t:meta.view v:id=85ty-ti6v v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - District - All Students" v:attribution="Department of Education (DOE)"

property e:85ty-ti6v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:85ty-ti6v t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade      | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ========== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3          | 2006 | All Students | 808           | 663              | 89        | 11.0      | 215       | 26.6      | 462       | 57.2      | 42        | 5.2       | 504         | 62.4        | 
| 1        | 4          | 2006 | All Students | 819           | 654              | 103       | 12.6      | 272       | 33.2      | 405       | 49.5      | 39        | 4.8       | 444         | 54.2        | 
| 1        | 5          | 2006 | All Students | 751           | 651              | 68        | 9.1       | 286       | 38.1      | 342       | 45.5      | 55        | 7.3       | 397         | 52.9        | 
| 1        | 6          | 2006 | All Students | 855           | 653              | 58        | 6.8       | 346       | 40.5      | 363       | 42.5      | 88        | 10.3      | 451         | 52.7        | 
| 1        | 7          | 2006 | All Students | 919           | 646              | 85        | 9.2       | 425       | 46.2      | 341       | 37.1      | 68        | 7.4       | 409         | 44.5        | 
| 1        | 8          | 2006 | All Students | 829           | 641              | 91        | 11.0      | 447       | 53.9      | 263       | 31.7      | 28        | 3.4       | 291         | 35.1        | 
| 1        | All Grades | 2006 | All Students | 4981          | 651              | 494       | 9.9       | 1991      | 40.0      | 2176      | 43.7      | 320       | 6.4       | 2496        | 50.1        | 
| 2        | 3          | 2006 | All Students | 2074          | 684              | 83        | 4.0       | 275       | 13.3      | 1464      | 70.6      | 252       | 12.2      | 1716        | 82.7        | 
| 2        | 4          | 2006 | All Students | 2144          | 675              | 104       | 4.9       | 341       | 15.9      | 1473      | 68.7      | 226       | 10.5      | 1699        | 79.2        | 
| 2        | 5          | 2006 | All Students | 2176          | 678              | 69        | 3.2       | 379       | 17.4      | 1218      | 56.0      | 510       | 23.4      | 1728        | 79.4        | 
```