# NYS Math Test Results By Grade 2006-2011 - District - By Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-by-gender-d3a53) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yz7z-iupz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yz7z-iupz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yz7z-iupz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yz7z-iupz |
| Name | NYS Math Test Results By Grade 2006-2011 - District - By Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:48:10Z |
| Publication Date | 2011-10-11T18:10:33Z |

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

Rows are suppressed (noted with ?s?) if the number of tested students was 5 or fewer.

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
series e:yz7z-iupz d:2006-01-01T00:00:00.000Z t:category=Female t:grade=3 t:district=1 m:level_4_1=114 m:level_3_4_2=73.8 m:mean_scale_score=675 m:level_2_2=19.4 m:level_4_2=23 m:level_2_1=96 m:level_1_2=6.9 m:level_1_1=34 m:number_tested=496 m:level_3_2=50.8 m:level_3_4_1=366 m:level_3_1=252

series e:yz7z-iupz d:2006-01-01T00:00:00.000Z t:category=Male t:grade=3 t:district=1 m:level_4_1=96 m:level_3_4_2=74.4 m:mean_scale_score=672 m:level_2_2=16.8 m:level_4_2=21.8 m:level_2_1=74 m:level_1_2=8.8 m:level_1_1=39 m:number_tested=441 m:level_3_2=52.6 m:level_3_4_1=328 m:level_3_1=232

series e:yz7z-iupz d:2007-01-01T00:00:00.000Z t:category=Female t:grade=3 t:district=1 m:level_4_1=100 m:level_3_4_2=85.7 m:mean_scale_score=681 m:level_2_2=8.6 m:level_4_2=24.6 m:level_2_1=35 m:level_1_2=5.7 m:level_1_1=23 m:number_tested=406 m:level_3_2=61.1 m:level_3_4_1=348 m:level_3_1=248
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

entity e:yz7z-iupz l:"NYS Math Test Results By Grade 2006-2011 - District - By Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yz7z-iupz

property e:yz7z-iupz t:meta.view v:id=yz7z-iupz v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By Gender" v:attribution="Department of Education (DOE)"

property e:yz7z-iupz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yz7z-iupz t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | Female   | 496           | 675              | 34        | 6.9       | 96        | 19.4      | 252       | 50.8      | 114       | 23.0      | 366         | 73.8        | 
| 1        | 3     | 2006 | Male     | 441           | 672              | 39        | 8.8       | 74        | 16.8      | 232       | 52.6      | 96        | 21.8      | 328         | 74.4        | 
| 1        | 3     | 2007 | Female   | 406           | 681              | 23        | 5.7       | 35        | 8.6       | 248       | 61.1      | 100       | 24.6      | 348         | 85.7        | 
| 1        | 3     | 2007 | Male     | 413           | 678              | 24        | 5.8       | 49        | 11.9      | 250       | 60.5      | 90        | 21.8      | 340         | 82.3        | 
| 1        | 3     | 2008 | Female   | 407           | 686              | 8         | 2.0       | 42        | 10.3      | 256       | 62.9      | 101       | 24.8      | 357         | 87.7        | 
| 1        | 3     | 2008 | Male     | 437           | 687              | 8         | 1.8       | 47        | 10.8      | 271       | 62.0      | 111       | 25.4      | 382         | 87.4        | 
| 1        | 3     | 2009 | Female   | 447           | 694              | 3         | 0.7       | 24        | 5.4       | 290       | 64.9      | 130       | 29.1      | 420         | 94.0        | 
| 1        | 3     | 2009 | Male     | 445           | 688              | 5         | 1.1       | 39        | 8.8       | 292       | 65.6      | 109       | 24.5      | 401         | 90.1        | 
| 1        | 3     | 2010 | Female   | 417           | 698              | 36        | 8.6       | 129       | 30.9      | 135       | 32.4      | 117       | 28.1      | 252         | 60.4        | 
| 1        | 3     | 2010 | Male     | 449           | 695              | 53        | 11.8      | 128       | 28.5      | 144       | 32.1      | 124       | 27.6      | 268         | 59.7        | 
```