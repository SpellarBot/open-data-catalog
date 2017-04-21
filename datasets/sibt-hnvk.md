# NYS Math Test Results By Grade 2006-2011 - School Level - By English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-school-level-by-english-proficiency-status-5106d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sibt-hnvk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sibt-hnvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sibt-hnvk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sibt-hnvk |
| Name | NYS Math Test Results By Grade 2006-2011 - School Level - By English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T17:22:43Z |
| Publication Date | 2011-10-11T18:12:37Z |

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
series e:sibt-hnvk d:2006-01-01T00:00:00.000Z t:category=ELL t:level_4_1=s t:dbn=01M015 t:level_2_1=s t:grade=3 t:level_1_1=s t:level_3_4_1=s t:level_3_1=s m:number_tested=4

series e:sibt-hnvk d:2006-01-01T00:00:00.000Z t:category=EP t:level_4_1=6 t:dbn=01M015 t:level_2_1=10 t:grade=3 t:level_1_1=0 t:level_3_4_1=25 t:level_3_1=19 m:level_3_4_2=71.4 m:mean_scale_score=671 m:level_2_2=28.6 m:level_4_2=17.1 m:level_1_2=0 m:number_tested=35 m:level_3_2=54.3

series e:sibt-hnvk d:2007-01-01T00:00:00.000Z t:category=ELL t:level_4_1=1 t:dbn=01M015 t:level_2_1=1 t:grade=3 t:level_1_1=0 t:level_3_4_1=7 t:level_3_1=6 m:level_3_4_2=87.5 m:mean_scale_score=668 m:level_2_2=12.5 m:level_4_2=12.5 m:level_1_2=0 m:number_tested=8 m:level_3_2=75
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

entity e:sibt-hnvk l:"NYS Math Test Results By Grade 2006-2011 - School Level - By English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/sibt-hnvk

property e:sibt-hnvk t:meta.view v:id=sibt-hnvk v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - School Level - By English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:sibt-hnvk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sibt-hnvk t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3     | 2006 | ELL      | 4             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2006 | EP       | 35            | 671              | 0         | 0.0       | 10        | 28.6      | 19        | 54.3      | 6         | 17.1      | 25          | 71.4        | 
| 01M015 | 3     | 2007 | ELL      | 8             | 668              | 0         | 0.0       | 1         | 12.5      | 6         | 75.0      | 1         | 12.5      | 7           | 87.5        | 
| 01M015 | 3     | 2007 | EP       | 23            | 674              | 2         | 8.7       | 2         | 8.7       | 16        | 69.6      | 3         | 13.0      | 19          | 82.6        | 
| 01M015 | 3     | 2008 | ELL      | 6             | 670              | 0         | 0.0       | 0         | 0.0       | 6         | 100.0     | 0         | 0.0       | 6           | 100.0       | 
| 01M015 | 3     | 2008 | EP       | 31            | 668              | 0         | 0.0       | 6         | 19.4      | 23        | 74.2      | 2         | 6.5       | 25          | 80.6        | 
| 01M015 | 3     | 2009 | ELL      | 9             | 664              | 0         | 0.0       | 1         | 11.1      | 8         | 88.9      | 0         | 0.0       | 8           | 88.9        | 
| 01M015 | 3     | 2009 | EP       | 24            | 669              | 0         | 0.0       | 3         | 12.5      | 20        | 83.3      | 1         | 4.2       | 21          | 87.5        | 
| 01M015 | 3     | 2010 | ELL      | 4             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3     | 2010 | EP       | 22            | 673              | 5         | 22.7      | 11        | 50.0      | 5         | 22.7      | 1         | 4.5       | 6           | 27.3        | 
```