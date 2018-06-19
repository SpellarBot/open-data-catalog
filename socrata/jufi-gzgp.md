# NYS Math Test Results By Grade 2006-2011 - School Level - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-school-level-all-students-7b78b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jufi-gzgp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jufi-gzgp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jufi-gzgp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jufi-gzgp |
| Name | NYS Math Test Results By Grade 2006-2011 - School Level - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T16:53:46Z |
| Publication Date | 2011-10-11T18:12:07Z |

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
series e:jufi-gzgp d:2006-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=3 m:level_4_1=6 m:level_3_4_2=66.7 m:mean_scale_score=667 m:level_2_2=28.2 m:level_4_2=15.4 m:level_2_1=11 m:level_1_2=5.1 m:level_1_1=2 m:number_tested=39 m:level_3_2=51.3 m:level_3_4_1=26 m:level_3_1=20

series e:jufi-gzgp d:2007-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=3 m:level_4_1=4 m:level_3_4_2=83.9 m:mean_scale_score=672 m:level_2_2=9.7 m:level_4_2=12.9 m:level_2_1=3 m:level_1_2=6.5 m:level_1_1=2 m:number_tested=31 m:level_3_2=71 m:level_3_4_1=26 m:level_3_1=22

series e:jufi-gzgp d:2008-01-01T00:00:00.000Z t:category="All Students" t:dbn=01M015 t:grade=3 m:level_4_1=2 m:level_3_4_2=83.8 m:mean_scale_score=668 m:level_2_2=16.2 m:level_4_2=5.4 m:level_2_1=6 m:level_1_2=0 m:level_1_1=0 m:number_tested=37 m:level_3_2=78.4 m:level_3_4_1=31 m:level_3_1=29
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

entity e:jufi-gzgp l:"NYS Math Test Results By Grade 2006-2011 - School Level - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/jufi-gzgp

property e:jufi-gzgp t:meta.view v:id=jufi-gzgp v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - School Level - All Students" v:attribution="Department of Education (DOE)"

property e:jufi-gzgp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jufi-gzgp t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ===== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3     | 2006 | All Students | 39            | 667              | 2         | 5.1       | 11        | 28.2      | 20        | 51.3      | 6         | 15.4      | 26          | 66.7        | 
| 01M015 | 3     | 2007 | All Students | 31            | 672              | 2         | 6.5       | 3         | 9.7       | 22        | 71.0      | 4         | 12.9      | 26          | 83.9        | 
| 01M015 | 3     | 2008 | All Students | 37            | 668              | 0         | 0.0       | 6         | 16.2      | 29        | 78.4      | 2         | 5.4       | 31          | 83.8        | 
| 01M015 | 3     | 2009 | All Students | 33            | 668              | 0         | 0.0       | 4         | 12.1      | 28        | 84.8      | 1         | 3.0       | 29          | 87.9        | 
| 01M015 | 3     | 2010 | All Students | 26            | 677              | 6         | 23.1      | 12        | 46.2      | 6         | 23.1      | 2         | 7.7       | 8           | 30.8        | 
| 01M015 | 3     | 2011 | All Students | 28            | 671              | 10        | 35.7      | 13        | 46.4      | 5         | 17.9      | 0         | 0.0       | 5           | 17.9        | 
| 01M015 | 4     | 2006 | All Students | 49            | 629              | 20        | 40.8      | 18        | 36.7      | 10        | 20.4      | 1         | 2.0       | 11          | 22.4        | 
| 01M015 | 4     | 2007 | All Students | 40            | 659              | 4         | 10.0      | 13        | 32.5      | 18        | 45.0      | 5         | 12.5      | 23          | 57.5        | 
| 01M015 | 4     | 2008 | All Students | 41            | 655              | 5         | 12.2      | 15        | 36.6      | 18        | 43.9      | 3         | 7.3       | 21          | 51.2        | 
| 01M015 | 4     | 2009 | All Students | 39            | 655              | 4         | 10.3      | 15        | 38.5      | 18        | 46.2      | 2         | 5.1       | 20          | 51.3        | 
```