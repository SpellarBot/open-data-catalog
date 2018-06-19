# NYS Math Test Results By Grade 2006-2011 - School Level - By Race- Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-school-level-by-race-ethnicity-2f01b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ty7c-8rmq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ty7c-8rmq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ty7c-8rmq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ty7c-8rmq |
| Name | NYS Math Test Results By Grade 2006-2011 - School Level - By Race- Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T17:33:06Z |
| Publication Date | 2011-10-11T18:13:50Z |

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

Rows are suppressed (noted with ?s?) if the number of tested students was 5 or fewer. 
Prior to 2011, the mean scale scores for ?All Grades? were not calculated.

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
| Yes      | series tag     | level_1_1        | Level 1 #        | text      | text        |
| Yes      | numeric metric | level_1_2        | Level 1 %        | percent   | percent     |
| Yes      | series tag     | level_2_1        | Level 2 #        | text      | text        |
| Yes      | numeric metric | level_2_2        | Level 2 %        | percent   | percent     |
| Yes      | series tag     | level_3_1        | Level 3 #        | text      | text        |
| Yes      | numeric metric | level_3_2        | Level 3 %        | percent   | percent     |
| Yes      | series tag     | level_4_1        | Level 4 #        | text      | text        |
| Yes      | numeric metric | level_4_2        | Level 4 %        | percent   | percent     |
| Yes      | series tag     | level_3_4_1      | Level 3+4 #      | text      | text        |
| Yes      | numeric metric | level_3_4_2      | Level 3+4 %      | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ty7c-8rmq d:2006-01-01T00:00:00.000Z t:category=Asian t:level_4_1=s t:dbn=01M015 t:level_2_1=s t:grade=3 t:level_1_1=s t:level_3_4_1=s t:level_3_1=s m:number_tested=3

series e:ty7c-8rmq d:2006-01-01T00:00:00.000Z t:category=Black t:level_4_1=0 t:dbn=01M015 t:level_2_1=3 t:grade=3 t:level_1_1=0 t:level_3_4_1=9 t:level_3_1=9 m:level_3_4_2=75 m:mean_scale_score=662 m:level_2_2=25 m:level_4_2=0 m:level_1_2=0 m:number_tested=12 m:level_3_2=75

series e:ty7c-8rmq d:2006-01-01T00:00:00.000Z t:category=Hispanic t:level_4_1=5 t:dbn=01M015 t:level_2_1=8 t:grade=3 t:level_1_1=1 t:level_3_4_1=15 t:level_3_1=10 m:level_3_4_2=62.5 m:mean_scale_score=670 m:level_2_2=33.3 m:level_4_2=20.8 m:level_1_2=4.2 m:number_tested=24 m:level_3_2=41.7
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_2 p:float l:"Level 1 %" t:dataTypeName=percent

metric m:level_2_2 p:float l:"Level 2 %" t:dataTypeName=percent

metric m:level_3_2 p:float l:"Level 3 %" t:dataTypeName=percent

metric m:level_4_2 p:float l:"Level 4 %" t:dataTypeName=percent

metric m:level_3_4_2 p:float l:"Level 3+4 %" t:dataTypeName=percent

entity e:ty7c-8rmq l:"NYS Math Test Results By Grade 2006-2011 - School Level - By Race- Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ty7c-8rmq

property e:ty7c-8rmq t:meta.view v:id=ty7c-8rmq v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - School Level - By Race- Ethnicity" v:attribution="Department of Education (DOE)"

property e:ty7c-8rmq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ty7c-8rmq t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3     | 2006 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2006 | Black    | 12            | 662              | 0         | 0.0       | 3         | 25.0      | 9         | 75.0      | 0         | 0.0       | 9           | 75.0        | 
| 01M015 | 3     | 2006 | Hispanic | 24            | 670              | 1         | 4.2       | 8         | 33.3      | 10        | 41.7      | 5         | 20.8      | 15          | 62.5        | 
| 01M015 | 3     | 2007 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2007 | Black    | 4             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2007 | Hispanic | 23            | 678              | 0         | 0.0       | 1         | 4.3       | 19        | 82.6      | 3         | 13.0      | 22          | 95.7        | 
| 01M015 | 3     | 2007 | White    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2008 | Asian    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2008 | Black    | 8             | 652              | 0         | 0.0       | 3         | 37.5      | 5         | 62.5      | 0         | 0.0       | 5           | 62.5        | 
| 01M015 | 3     | 2008 | Hispanic | 27            | 671              | 0         | 0.0       | 3         | 11.1      | 23        | 85.2      | 1         | 3.7       | 24          | 88.9        | 
```