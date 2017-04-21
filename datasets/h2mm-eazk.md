# NYS Math Test Results By Grade 2006-2011 - District - By English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-by-english-proficiency-status-09b02) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h2mm-eazk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h2mm-eazk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h2mm-eazk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h2mm-eazk |
| Name | NYS Math Test Results By Grade 2006-2011 - District - By English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:45:07Z |
| Publication Date | 2011-10-11T18:09:57Z |

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
series e:h2mm-eazk d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:district=1 m:level_4_1=38 m:level_3_4_2=67 m:mean_scale_score=667 m:level_2_2=21.8 m:level_4_2=20.2 m:level_2_1=41 m:level_1_2=11.2 m:level_1_1=21 m:number_tested=188 m:level_3_2=46.8 m:level_3_4_1=126 m:level_3_1=88

series e:h2mm-eazk d:2006-01-01T00:00:00.000Z t:category=EP t:grade=3 t:district=1 m:level_4_1=172 m:level_3_4_2=75.8 m:mean_scale_score=675 m:level_2_2=17.2 m:level_4_2=23 m:level_2_1=129 m:level_1_2=6.9 m:level_1_1=52 m:number_tested=749 m:level_3_2=52.9 m:level_3_4_1=568 m:level_3_1=396

series e:h2mm-eazk d:2007-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:district=1 m:level_4_1=18 m:level_3_4_2=72.3 m:mean_scale_score=666 m:level_2_2=20.9 m:level_4_2=12.2 m:level_2_1=31 m:level_1_2=6.8 m:level_1_1=10 m:number_tested=148 m:level_3_2=60.1 m:level_3_4_1=107 m:level_3_1=89
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

entity e:h2mm-eazk l:"NYS Math Test Results By Grade 2006-2011 - District - By English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/h2mm-eazk

property e:h2mm-eazk t:meta.view v:id=h2mm-eazk v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:h2mm-eazk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h2mm-eazk t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | ELL      | 188           | 667              | 21        | 11.2      | 41        | 21.8      | 88        | 46.8      | 38        | 20.2      | 126         | 67.0        | 
| 1        | 3     | 2006 | EP       | 749           | 675              | 52        | 6.9       | 129       | 17.2      | 396       | 52.9      | 172       | 23.0      | 568         | 75.8        | 
| 1        | 3     | 2007 | ELL      | 148           | 666              | 10        | 6.8       | 31        | 20.9      | 89        | 60.1      | 18        | 12.2      | 107         | 72.3        | 
| 1        | 3     | 2007 | EP       | 671           | 683              | 37        | 5.5       | 53        | 7.9       | 409       | 61.0      | 172       | 25.6      | 581         | 86.6        | 
| 1        | 3     | 2008 | ELL      | 120           | 676              | 4         | 3.3       | 16        | 13.3      | 84        | 70.0      | 16        | 13.3      | 100         | 83.3        | 
| 1        | 3     | 2008 | EP       | 724           | 688              | 12        | 1.7       | 73        | 10.1      | 443       | 61.2      | 196       | 27.1      | 639         | 88.3        | 
| 1        | 3     | 2009 | ELL      | 94            | 675              | 2         | 2.1       | 13        | 13.8      | 69        | 73.4      | 10        | 10.6      | 79          | 84.0        | 
| 1        | 3     | 2009 | EP       | 798           | 693              | 6         | 0.8       | 50        | 6.3       | 513       | 64.3      | 229       | 28.7      | 742         | 93.0        | 
| 1        | 3     | 2010 | ELL      | 92            | 676              | 29        | 31.5      | 34        | 37.0      | 20        | 21.7      | 9         | 9.8       | 29          | 31.5        | 
| 1        | 3     | 2010 | EP       | 774           | 699              | 60        | 7.8       | 223       | 28.8      | 259       | 33.5      | 232       | 30.0      | 491         | 63.4        | 
```