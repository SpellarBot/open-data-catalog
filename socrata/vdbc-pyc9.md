# NYS Math Test Results By Grade 2006-2011 - School Level - By Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-school-level-by-disability-status-e2917) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vdbc-pyc9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vdbc-pyc9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vdbc-pyc9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vdbc-pyc9 |
| Name | NYS Math Test Results By Grade 2006-2011 - School Level - By Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning, nys math test results by grade 2006-2011 - school level - by disability status, math, grades |
| Created | 2011-10-06T17:25:48Z |
| Publication Date | 2011-10-11T18:13:10Z |

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
series e:vdbc-pyc9 d:2006-01-01T00:00:00.000Z t:category="General Ed" t:dbn=01M015 t:grade=3 m:level_4_1=6 m:level_3_4_2=79.3 m:mean_scale_score=675 m:level_2_2=17.2 m:level_4_2=20.7 m:level_2_1=5 m:level_1_2=3.4 m:level_1_1=1 m:number_tested=29 m:level_3_2=58.6 m:level_3_4_1=23 m:level_3_1=17

series e:vdbc-pyc9 d:2006-01-01T00:00:00.000Z t:category="Special Ed" t:dbn=01M015 t:grade=3 m:level_4_1=0 m:level_3_4_2=30 m:mean_scale_score=644 m:level_2_2=60 m:level_4_2=0 m:level_2_1=6 m:level_1_2=10 m:level_1_1=1 m:number_tested=10 m:level_3_2=30 m:level_3_4_1=3 m:level_3_1=3

series e:vdbc-pyc9 d:2007-01-01T00:00:00.000Z t:category="General Ed" t:dbn=01M015 t:grade=3 m:level_4_1=4 m:level_3_4_2=84.6 m:mean_scale_score=675 m:level_2_2=11.5 m:level_4_2=15.4 m:level_2_1=3 m:level_1_2=3.8 m:level_1_1=1 m:number_tested=26 m:level_3_2=69.2 m:level_3_4_1=22 m:level_3_1=18
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

entity e:vdbc-pyc9 l:"NYS Math Test Results By Grade 2006-2011 - School Level - By Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vdbc-pyc9

property e:vdbc-pyc9 t:meta.view v:id=vdbc-pyc9 v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - School Level - By Disability Status" v:attribution="Department of Education (DOE)"

property e:vdbc-pyc9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vdbc-pyc9 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ===== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3     | 2006 | General Ed | 29            | 675              | 1         | 3.4       | 5         | 17.2      | 17        | 58.6      | 6         | 20.7      | 23          | 79.3        | 
| 01M015 | 3     | 2006 | Special Ed | 10            | 644              | 1         | 10.0      | 6         | 60.0      | 3         | 30.0      | 0         | 0.0       | 3           | 30.0        | 
| 01M015 | 3     | 2007 | General Ed | 26            | 675              | 1         | 3.8       | 3         | 11.5      | 18        | 69.2      | 4         | 15.4      | 22          | 84.6        | 
| 01M015 | 3     | 2007 | Special Ed | 5             |                  |           |           |           |           |           |           |           |           |             |             | 
| 01M015 | 3     | 2008 | General Ed | 30            | 669              | 0         | 0.0       | 4         | 13.3      | 24        | 80.0      | 2         | 6.7       | 26          | 86.7        | 
| 01M015 | 3     | 2008 | Special Ed | 7             | 663              | 0         | 0.0       | 2         | 28.6      | 5         | 71.4      | 0         | 0.0       | 5           | 71.4        | 
| 01M015 | 3     | 2009 | General Ed | 30            | 668              | 0         | 0.0       | 4         | 13.3      | 25        | 83.3      | 1         | 3.3       | 26          | 86.7        | 
| 01M015 | 3     | 2009 | Special Ed | 3             |                  |           |           |           |           |           |           |           |           |             |             | 
| 01M015 | 3     | 2010 | General Ed | 20            | 680              | 5         | 25.0      | 8         | 40.0      | 5         | 25.0      | 2         | 10.0      | 7           | 35.0        | 
| 01M015 | 3     | 2010 | Special Ed | 6             | 668              | 1         | 16.7      | 4         | 66.7      | 1         | 16.7      | 0         | 0.0       | 1           | 16.7        | 
```