# NYS Math Test Results By Grade 2006-2011 - District - By Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-by-disability-status-e05e1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vza7-n6vi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vza7-n6vi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vza7-n6vi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vza7-n6vi |
| Name | NYS Math Test Results By Grade 2006-2011 - District - By Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:52:18Z |
| Publication Date | 2011-10-11T18:11:07Z |

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
series e:vza7-n6vi d:2006-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:district=1 m:level_4_1=199 m:level_3_4_2=80.6 m:mean_scale_score=680 m:level_2_2=15.3 m:level_4_2=26.5 m:level_2_1=115 m:level_1_2=4.1 m:level_1_1=31 m:number_tested=751 m:level_3_2=54.1 m:level_3_4_1=605 m:level_3_1=406

series e:vza7-n6vi d:2006-01-01T00:00:00.000Z t:category="Special Ed" t:grade=3 t:district=1 m:level_4_1=11 m:level_3_4_2=47.8 m:mean_scale_score=647 m:level_2_2=29.6 m:level_4_2=5.9 m:level_2_1=55 m:level_1_2=22.6 m:level_1_1=42 m:number_tested=186 m:level_3_2=41.9 m:level_3_4_1=89 m:level_3_1=78

series e:vza7-n6vi d:2007-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:district=1 m:level_4_1=181 m:level_3_4_2=89.1 m:mean_scale_score=685 m:level_2_2=8.2 m:level_4_2=26.9 m:level_2_1=55 m:level_1_2=2.7 m:level_1_1=18 m:number_tested=672 m:level_3_2=62.2 m:level_3_4_1=599 m:level_3_1=418
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

entity e:vza7-n6vi l:"NYS Math Test Results By Grade 2006-2011 - District - By Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vza7-n6vi

property e:vza7-n6vi t:meta.view v:id=vza7-n6vi v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By Disability Status" v:attribution="Department of Education (DOE)"

property e:vza7-n6vi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vza7-n6vi t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | General Ed | 751           | 680              | 31        | 4.1       | 115       | 15.3      | 406       | 54.1      | 199       | 26.5      | 605         | 80.6        | 
| 1        | 3     | 2006 | Special Ed | 186           | 647              | 42        | 22.6      | 55        | 29.6      | 78        | 41.9      | 11        | 5.9       | 89          | 47.8        | 
| 1        | 3     | 2007 | General Ed | 672           | 685              | 18        | 2.7       | 55        | 8.2       | 418       | 62.2      | 181       | 26.9      | 599         | 89.1        | 
| 1        | 3     | 2007 | Special Ed | 147           | 654              | 29        | 19.7      | 29        | 19.7      | 80        | 54.4      | 9         | 6.1       | 89          | 60.5        | 
| 1        | 3     | 2008 | General Ed | 677           | 693              | 3         | 0.4       | 34        | 5.0       | 437       | 64.5      | 203       | 30.0      | 640         | 94.5        | 
| 1        | 3     | 2008 | Special Ed | 167           | 659              | 13        | 7.8       | 55        | 32.9      | 90        | 53.9      | 9         | 5.4       | 99          | 59.3        | 
| 1        | 3     | 2009 | General Ed | 741           | 697              | 3         | 0.4       | 24        | 3.2       | 483       | 65.2      | 231       | 31.2      | 714         | 96.4        | 
| 1        | 3     | 2009 | Special Ed | 151           | 661              | 5         | 3.3       | 39        | 25.8      | 99        | 65.6      | 8         | 5.3       | 107         | 70.9        | 
| 1        | 3     | 2010 | General Ed | 700           | 702              | 36        | 5.1       | 187       | 26.7      | 245       | 35.0      | 232       | 33.1      | 477         | 68.1        | 
| 1        | 3     | 2010 | Special Ed | 166           | 671              | 53        | 31.9      | 70        | 42.2      | 34        | 20.5      | 9         | 5.4       | 43          | 25.9        | 
```