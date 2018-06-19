# NYS Math Test Results By Grade 2006-2011 - School Level - By Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-school-level-by-gender-6b1eb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pxfd-dpcz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pxfd-dpcz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pxfd-dpcz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pxfd-dpcz |
| Name | NYS Math Test Results By Grade 2006-2011 - School Level - By Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T17:29:55Z |
| Publication Date | 2011-10-11T18:13:24Z |

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
series e:pxfd-dpcz d:2006-01-01T00:00:00.000Z t:category=Female t:dbn=01M015 t:grade=3 m:level_4_1=4 m:level_3_4_2=69.6 m:mean_scale_score=675 m:level_2_2=30.4 m:level_4_2=17.4 m:level_2_1=7 m:level_1_2=0 m:level_1_1=0 m:number_tested=23 m:level_3_2=52.2 m:level_3_4_1=16 m:level_3_1=12

series e:pxfd-dpcz d:2006-01-01T00:00:00.000Z t:category=Male t:dbn=01M015 t:grade=3 m:level_4_1=2 m:level_3_4_2=62.5 m:mean_scale_score=657 m:level_2_2=25 m:level_4_2=12.5 m:level_2_1=4 m:level_1_2=12.5 m:level_1_1=2 m:number_tested=16 m:level_3_2=50 m:level_3_4_1=10 m:level_3_1=8

series e:pxfd-dpcz d:2007-01-01T00:00:00.000Z t:category=Female t:dbn=01M015 t:grade=3 m:level_4_1=3 m:level_3_4_2=81.8 m:mean_scale_score=679 m:level_2_2=0 m:level_4_2=27.3 m:level_2_1=0 m:level_1_2=18.2 m:level_1_1=2 m:number_tested=11 m:level_3_2=54.5 m:level_3_4_1=9 m:level_3_1=6
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

entity e:pxfd-dpcz l:"NYS Math Test Results By Grade 2006-2011 - School Level - By Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pxfd-dpcz

property e:pxfd-dpcz t:meta.view v:id=pxfd-dpcz v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - School Level - By Gender" v:attribution="Department of Education (DOE)"

property e:pxfd-dpcz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pxfd-dpcz t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3     | 2006 | Female   | 23            | 675              | 0         | 0.0       | 7         | 30.4      | 12        | 52.2      | 4         | 17.4      | 16          | 69.6        | 
| 01M015 | 3     | 2006 | Male     | 16            | 657              | 2         | 12.5      | 4         | 25.0      | 8         | 50.0      | 2         | 12.5      | 10          | 62.5        | 
| 01M015 | 3     | 2007 | Female   | 11            | 679              | 2         | 18.2      | 0         | 0.0       | 6         | 54.5      | 3         | 27.3      | 9           | 81.8        | 
| 01M015 | 3     | 2007 | Male     | 20            | 668              | 0         | 0.0       | 3         | 15.0      | 16        | 80.0      | 1         | 5.0       | 17          | 85.0        | 
| 01M015 | 3     | 2008 | Female   | 17            | 661              | 0         | 0.0       | 5         | 29.4      | 12        | 70.6      | 0         | 0.0       | 12          | 70.6        | 
| 01M015 | 3     | 2008 | Male     | 20            | 674              | 0         | 0.0       | 1         | 5.0       | 17        | 85.0      | 2         | 10.0      | 19          | 95.0        | 
| 01M015 | 3     | 2009 | Female   | 13            | 667              | 0         | 0.0       | 1         | 7.7       | 11        | 84.6      | 1         | 7.7       | 12          | 92.3        | 
| 01M015 | 3     | 2009 | Male     | 20            | 668              | 0         | 0.0       | 3         | 15.0      | 17        | 85.0      | 0         | 0.0       | 17          | 85.0        | 
| 01M015 | 3     | 2010 | Female   | 13            | 681              | 2         | 15.4      | 7         | 53.8      | 3         | 23.1      | 1         | 7.7       | 4           | 30.8        | 
| 01M015 | 3     | 2010 | Male     | 13            | 673              | 4         | 30.8      | 5         | 38.5      | 3         | 23.1      | 1         | 7.7       | 4           | 30.8        | 
```