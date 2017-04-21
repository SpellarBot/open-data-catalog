# English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-school-level-by-gender-5c4db) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c72z-kzbi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c72z-kzbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c72z-kzbi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c72z-kzbi |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:07:12Z |
| Publication Date | 2011-10-11T18:08:22Z |

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
series e:c72z-kzbi d:2006-01-01T00:00:00.000Z t:category=Female t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=56.5 m:mean_scale_score=655 m:level_2_2=34.8 m:level_4_2=0 m:level_2_1=8 m:level_1_2=8.7 m:level_1_1=2 m:number_tested=23 m:level_3_2=56.5 m:level_3_4_1=13 m:level_3_1=13

series e:c72z-kzbi d:2006-01-01T00:00:00.000Z t:category=Female t:dbn=01M015 t:grade=4 m:level_4_1=0 m:level_3_4_2=11.8 m:mean_scale_score=620 m:level_2_2=47.1 m:level_4_2=0 m:level_2_1=8 m:level_1_2=41.2 m:level_1_1=7 m:number_tested=17 m:level_3_2=11.8 m:level_3_4_1=2 m:level_3_1=2

series e:c72z-kzbi d:2006-01-01T00:00:00.000Z t:category=Female t:dbn=01M015 t:grade=5 m:level_4_1=0 m:level_3_4_2=30.8 m:mean_scale_score=627 m:level_2_2=61.5 m:level_4_2=0 m:level_2_1=8 m:level_1_2=7.7 m:level_1_1=1 m:number_tested=13 m:level_3_2=30.8 m:level_3_4_1=4 m:level_3_1=4
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

entity e:c72z-kzbi l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/c72z-kzbi

property e:c72z-kzbi t:meta.view v:id=c72z-kzbi v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Gender" v:attribution="Department of Education (DOE)"

property e:c72z-kzbi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c72z-kzbi t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade      | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3          | 2006 | Female   | 23            | 655              | 2         | 8.7       | 8         | 34.8      | 13        | 56.5      | 0         | 0.0       | 13          | 56.5        | 
| 01M015 | 4          | 2006 | Female   | 17            | 620              | 7         | 41.2      | 8         | 47.1      | 2         | 11.8      | 0         | 0.0       | 2           | 11.8        | 
| 01M015 | 5          | 2006 | Female   | 13            | 627              | 1         | 7.7       | 8         | 61.5      | 4         | 30.8      | 0         | 0.0       | 4           | 30.8        | 
| 01M015 | 6          | 2006 | Female   | 20            | 638              | 1         | 5.0       | 12        | 60.0      | 6         | 30.0      | 1         | 5.0       | 7           | 35.0        | 
| 01M015 | All Grades | 2006 | Female   | 73            |                  | 11        | 15.1      | 36        | 49.3      | 25        | 34.2      | 1         | 1.4       | 26          | 35.6        | 
| 01M015 | 3          | 2006 | Male     | 14            | 643              | 2         | 14.3      | 6         | 42.9      | 6         | 42.9      | 0         | 0.0       | 6           | 42.9        | 
| 01M015 | 4          | 2006 | Male     | 29            | 621              | 11        | 37.9      | 12        | 41.4      | 5         | 17.2      | 1         | 3.4       | 6           | 20.7        | 
| 01M015 | 5          | 2006 | Male     | 15            | 623              | 7         | 46.7      | 5         | 33.3      | 3         | 20.0      | 0         | 0.0       | 3           | 20.0        | 
| 01M015 | 6          | 2006 | Male     | 16            | 640              | 1         | 6.3       | 6         | 37.5      | 9         | 56.3      | 0         | 0.0       | 9           | 56.3        | 
| 01M015 | All Grades | 2006 | Male     | 74            |                  | 21        | 28.4      | 29        | 39.2      | 23        | 31.1      | 1         | 1.4       | 24          | 32.4        | 
```