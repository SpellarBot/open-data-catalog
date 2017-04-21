# English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-citywide-by-english-proficiency--b8573) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yjsf-89ae) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yjsf-89ae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yjsf-89ae/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yjsf-89ae |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T18:51:54Z |
| Publication Date | 2011-10-11T17:15:55Z |

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
series e:yjsf-89ae d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=10 m:level_3_4_2=22.4 m:mean_scale_score=621 m:level_2_2=34.1 m:level_4_2=0.4 m:level_2_1=762 m:level_1_2=43.5 m:level_1_1=971 m:number_tested=2233 m:level_3_2=21.9 m:level_3_4_1=500 m:level_3_1=490

series e:yjsf-89ae d:2007-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=66 m:level_3_4_2=28.6 m:mean_scale_score=631 m:level_2_2=43.6 m:level_4_2=0.5 m:level_2_1=5507 m:level_1_2=27.8 m:level_1_1=3515 m:number_tested=12632 m:level_3_2=28.1 m:level_3_4_1=3610 m:level_3_1=3544

series e:yjsf-89ae d:2008-01-01T00:00:00.000Z t:category=ELL t:grade=3 m:level_4_1=93 m:level_3_4_2=30.3 m:mean_scale_score=636 m:level_2_2=50 m:level_4_2=0.8 m:level_2_1=5862 m:level_1_2=19.7 m:level_1_1=2304 m:number_tested=11719 m:level_3_2=29.5 m:level_3_4_1=3553 m:level_3_1=3460
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

entity e:yjsf-89ae l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yjsf-89ae

property e:yjsf-89ae t:meta.view v:id=yjsf-89ae v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:yjsf-89ae t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yjsf-89ae t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3     | 2006 | ELL      | 2233          | 621              | 971       | 43.5      | 762       | 34.1      | 490       | 21.9      | 10        | 0.4       | 500         | 22.4        | 
| 3     | 2007 | ELL      | 12632         | 631              | 3515      | 27.8      | 5507      | 43.6      | 3544      | 28.1      | 66        | 0.5       | 3610        | 28.6        | 
| 3     | 2008 | ELL      | 11719         | 636              | 2304      | 19.7      | 5862      | 50.0      | 3460      | 29.5      | 93        | 0.8       | 3553        | 30.3        | 
| 3     | 2009 | ELL      | 11980         | 645              | 1716      | 14.3      | 4660      | 38.9      | 5452      | 45.5      | 152       | 1.3       | 5604        | 46.8        | 
| 3     | 2010 | ELL      | 12106         | 649              | 4150      | 34.3      | 5086      | 42.0      | 2460      | 20.3      | 410       | 3.4       | 2870        | 23.7        | 
| 3     | 2011 | ELL      | 11871         | 647              | 4012      | 33.8      | 5288      | 44.5      | 2546      | 21.4      | 25        | 0.2       | 2571        | 21.7        | 
| 4     | 2006 | ELL      | 2938          | 612              | 1327      | 45.2      | 1116      | 38.0      | 488       | 16.6      | 7         | 0.2       | 495         | 16.8        | 
| 4     | 2007 | ELL      | 10873         | 623              | 3512      | 32.3      | 5063      | 46.6      | 2282      | 21.0      | 16        | 0.1       | 2298        | 21.1        | 
| 4     | 2008 | ELL      | 10271         | 628              | 2607      | 25.4      | 4649      | 45.3      | 2991      | 29.1      | 24        | 0.2       | 3015        | 29.4        | 
| 4     | 2009 | ELL      | 10012         | 638              | 1495      | 14.9      | 4636      | 46.3      | 3863      | 38.6      | 18        | 0.2       | 3881        | 38.8        | 
```