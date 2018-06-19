# English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Race-Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-district-by-race-ethnicity-dcb72) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cz36-mpdq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cz36-mpdq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cz36-mpdq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cz36-mpdq |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Race-Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:39:31Z |
| Publication Date | 2011-10-11T18:06:35Z |

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
series e:cz36-mpdq d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 t:district=1 m:level_4_1=17 m:level_3_4_2=86 m:mean_scale_score=690 m:level_2_2=12.3 m:level_4_2=14.9 m:level_2_1=14 m:level_1_2=1.8 m:level_1_1=2 m:number_tested=114 m:level_3_2=71.1 m:level_3_4_1=98 m:level_3_1=81

series e:cz36-mpdq d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 t:district=1 m:level_4_1=1 m:level_3_4_2=52 m:mean_scale_score=649 m:level_2_2=33.7 m:level_4_2=0.6 m:level_2_1=59 m:level_1_2=14.3 m:level_1_1=25 m:number_tested=175 m:level_3_2=51.4 m:level_3_4_1=91 m:level_3_1=90

series e:cz36-mpdq d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 t:district=1 m:level_4_1=7 m:level_3_4_2=54.5 m:mean_scale_score=654 m:level_2_2=31.9 m:level_4_2=1.7 m:level_2_1=134 m:level_1_2=13.6 m:level_1_1=57 m:number_tested=420 m:level_3_2=52.9 m:level_3_4_1=229 m:level_3_1=222
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

entity e:cz36-mpdq l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Race-Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/cz36-mpdq

property e:cz36-mpdq t:meta.view v:id=cz36-mpdq v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Race-Ethnicity" v:attribution="Department of Education (DOE)"

property e:cz36-mpdq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cz36-mpdq t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | Asian    | 114           | 690              | 2         | 1.8       | 14        | 12.3      | 81        | 71.1      | 17        | 14.9      | 98          | 86.0        | 
| 1        | 3     | 2006 | Black    | 175           | 649              | 25        | 14.3      | 59        | 33.7      | 90        | 51.4      | 1         | 0.6       | 91          | 52.0        | 
| 1        | 3     | 2006 | Hispanic | 420           | 654              | 57        | 13.6      | 134       | 31.9      | 222       | 52.9      | 7         | 1.7       | 229         | 54.5        | 
| 1        | 3     | 2006 | White    | 92            | 699              | 2         | 2.2       | 6         | 6.5       | 67        | 72.8      | 17        | 18.5      | 84          | 91.3        | 
| 1        | 4     | 2006 | Asian    | 134           | 673              | 7         | 5.2       | 24        | 17.9      | 90        | 67.2      | 13        | 9.7       | 103         | 76.9        | 
| 1        | 4     | 2006 | Black    | 160           | 645              | 23        | 14.4      | 68        | 42.5      | 65        | 40.6      | 4         | 2.5       | 69          | 43.1        | 
| 1        | 4     | 2006 | Hispanic | 432           | 645              | 70        | 16.2      | 172       | 39.8      | 181       | 41.9      | 9         | 2.1       | 190         | 44.0        | 
| 1        | 4     | 2006 | White    | 82            | 684              | 2         | 2.4       | 6         | 7.3       | 63        | 76.8      | 11        | 13.4      | 74          | 90.2        | 
| 1        | 5     | 2006 | Asian    | 112           | 675              | 2         | 1.8       | 21        | 18.8      | 70        | 62.5      | 19        | 17.0      | 89          | 79.5        | 
| 1        | 5     | 2006 | Black    | 149           | 643              | 17        | 11.4      | 67        | 45.0      | 61        | 40.9      | 4         | 2.7       | 65          | 43.6        | 
```