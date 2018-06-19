# English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-school-level-by-disability-statu-6afaf) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zs4w-c9cd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zs4w-c9cd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zs4w-c9cd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zs4w-c9cd |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:02:42Z |
| Publication Date | 2011-10-11T18:07:59Z |

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
series e:zs4w-c9cd d:2006-01-01T00:00:00.000Z t:category="General Ed" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=64.3 m:mean_scale_score=659 m:level_2_2=32.1 m:level_4_2=0 m:level_2_1=9 m:level_1_2=3.6 m:level_1_1=1 m:number_tested=28 m:level_3_2=64.3 m:level_3_4_1=18 m:level_3_1=18

series e:zs4w-c9cd d:2006-01-01T00:00:00.000Z t:category="General Ed" t:dbn=01M015 t:grade=4 m:level_4_1=1 m:level_3_4_2=20 m:mean_scale_score=628 m:level_2_2=46.7 m:level_4_2=3.3 m:level_2_1=14 m:level_1_2=33.3 m:level_1_1=10 m:number_tested=30 m:level_3_2=16.7 m:level_3_4_1=6 m:level_3_1=5

series e:zs4w-c9cd d:2006-01-01T00:00:00.000Z t:category="General Ed" t:dbn=01M015 t:grade=5 m:level_4_1=0 m:level_3_4_2=46.7 m:mean_scale_score=643 m:level_2_2=40 m:level_4_2=0 m:level_2_1=6 m:level_1_2=13.3 m:level_1_1=2 m:number_tested=15 m:level_3_2=46.7 m:level_3_4_1=7 m:level_3_1=7
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

entity e:zs4w-c9cd l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/zs4w-c9cd

property e:zs4w-c9cd t:meta.view v:id=zs4w-c9cd v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Disability Status" v:attribution="Department of Education (DOE)"

property e:zs4w-c9cd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zs4w-c9cd t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade      | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3          | 2006 | General Ed | 28            | 659              | 1         | 3.6       | 9         | 32.1      | 18        | 64.3      | 0         | 0.0       | 18          | 64.3        | 
| 01M015 | 4          | 2006 | General Ed | 30            | 628              | 10        | 33.3      | 14        | 46.7      | 5         | 16.7      | 1         | 3.3       | 6           | 20.0        | 
| 01M015 | 5          | 2006 | General Ed | 15            | 643              | 2         | 13.3      | 6         | 40.0      | 7         | 46.7      | 0         | 0.0       | 7           | 46.7        | 
| 01M015 | 6          | 2006 | General Ed | 27            | 644              | 1         | 3.7       | 12        | 44.4      | 13        | 48.1      | 1         | 3.7       | 14          | 51.9        | 
| 01M015 | All Grades | 2006 | General Ed | 100           |                  | 14        | 14.0      | 41        | 41.0      | 43        | 43.0      | 2         | 2.0       | 45          | 45.0        | 
| 01M015 | 3          | 2006 | Special Ed | 9             | 625              | 3         | 33.3      | 5         | 55.6      | 1         | 11.1      | 0         | 0.0       | 1           | 11.1        | 
| 01M015 | 4          | 2006 | Special Ed | 16            | 606              | 8         | 50.0      | 6         | 37.5      | 2         | 12.5      | 0         | 0.0       | 2           | 12.5        | 
| 01M015 | 5          | 2006 | Special Ed | 13            | 604              | 6         | 46.2      | 7         | 53.8      | 0         | 0.0       | 0         | 0.0       | 0           | 0.0         | 
| 01M015 | 6          | 2006 | Special Ed | 9             | 624              | 1         | 11.1      | 6         | 66.7      | 2         | 22.2      | 0         | 0.0       | 2           | 22.2        | 
| 01M015 | All Grades | 2006 | Special Ed | 47            |                  | 18        | 38.3      | 24        | 51.1      | 5         | 10.6      | 0         | 0.0       | 5           | 10.6        | 
```