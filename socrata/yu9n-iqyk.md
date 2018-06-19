# English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-school-level-all-students-3b46b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yu9n-iqyk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yu9n-iqyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yu9n-iqyk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yu9n-iqyk |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:50:06Z |
| Publication Date | 2011-10-11T18:07:06Z |

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
| Yes      | series tag     | dbn              | DBN              | text      | text        |
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
series e:yu9n-iqyk d:2006-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=51.4 m:mean_scale_score=651 m:level_2_2=37.8 m:level_4_2=0 m:level_2_1=14 m:level_1_2=10.8 m:level_1_1=4 m:number_tested=37 m:level_3_2=51.4 m:level_3_4_1=19 m:level_3_1=19

series e:yu9n-iqyk d:2006-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=4 m:level_4_1=1 m:level_3_4_2=17.4 m:mean_scale_score=621 m:level_2_2=43.5 m:level_4_2=2.2 m:level_2_1=20 m:level_1_2=39.1 m:level_1_1=18 m:number_tested=46 m:level_3_2=15.2 m:level_3_4_1=8 m:level_3_1=7

series e:yu9n-iqyk d:2006-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=5 m:level_4_1=0 m:level_3_4_2=25 m:mean_scale_score=625 m:level_2_2=46.4 m:level_4_2=0 m:level_2_1=13 m:level_1_2=28.6 m:level_1_1=8 m:number_tested=28 m:level_3_2=25 m:level_3_4_1=7 m:level_3_1=7
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

entity e:yu9n-iqyk l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yu9n-iqyk

property e:yu9n-iqyk t:meta.view v:id=yu9n-iqyk v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - All Students" v:attribution="Department of Education (DOE)"

property e:yu9n-iqyk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yu9n-iqyk t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade      | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3          | 2006 | All Students | 37            | 651              | 4         | 10.8      | 14        | 37.8      | 19        | 51.4      | 0         | 0.0       | 19          | 51.4        | 
| 01M015 | 4          | 2006 | All Students | 46            | 621              | 18        | 39.1      | 20        | 43.5      | 7         | 15.2      | 1         | 2.2       | 8           | 17.4        | 
| 01M015 | 5          | 2006 | All Students | 28            | 625              | 8         | 28.6      | 13        | 46.4      | 7         | 25.0      | 0         | 0.0       | 7           | 25.0        | 
| 01M015 | 6          | 2006 | All Students | 36            | 639              | 2         | 5.6       | 18        | 50.0      | 15        | 41.7      | 1         | 2.8       | 16          | 44.4        | 
| 01M015 | All Grades | 2006 | All Students | 147           |                  | 32        | 21.8      | 65        | 44.2      | 48        | 32.7      | 2         | 1.4       | 50          | 34.0        | 
| 01M015 | 3          | 2007 | All Students | 33            | 635              | 6         | 18.2      | 18        | 54.5      | 9         | 27.3      | 0         | 0.0       | 9           | 27.3        | 
| 01M015 | 4          | 2007 | All Students | 42            | 648              | 2         | 4.8       | 21        | 50.0      | 19        | 45.2      | 0         | 0.0       | 19          | 45.2        | 
| 01M015 | 5          | 2007 | All Students | 48            | 637              | 5         | 10.4      | 28        | 58.3      | 15        | 31.3      | 0         | 0.0       | 15          | 31.3        | 
| 01M015 | All Grades | 2007 | All Students | 123           |                  | 13        | 10.6      | 67        | 54.5      | 43        | 35.0      | 0         | 0.0       | 43          | 35.0        | 
| 01M015 | 3          | 2008 | All Students | 39            | 646              | 3         | 7.7       | 22        | 56.4      | 14        | 35.9      | 0         | 0.0       | 14          | 35.9        | 
```