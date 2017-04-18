# NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-by-english-proficiency-status-fdef8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zpd4-gad8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zpd4-gad8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zpd4-gad8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zpd4-gad8 |
| Name | NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:14:31Z |
| Publication Date | 2011-10-11T16:57:18Z |

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | borough          | Borough          | text      | text        |
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
series e:zpd4-gad8 d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=202 m:level_3_4_2=49 m:mean_scale_score=645 m:level_2_2=27.6 m:level_4_2=5.4 m:level_2_1=1037 m:level_1_2=23.3 m:level_1_1=876 m:number_tested=3754 m:level_3_2=43.7 m:level_3_4_1=1841 m:level_3_1=1639

series e:zpd4-gad8 d:2006-01-01T00:00:00.000Z t:category=EP t:grade=3 t:borough=BRONX m:level_4_1=2306 m:level_3_4_2=73.2 m:mean_scale_score=669 m:level_2_2=17.5 m:level_4_2=18.2 m:level_2_1=2220 m:level_1_2=9.3 m:level_1_1=1186 m:number_tested=12691 m:level_3_2=55 m:level_3_4_1=9285 m:level_3_1=6979

series e:zpd4-gad8 d:2007-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=376 m:level_3_4_2=62.5 m:mean_scale_score=659 m:level_2_2=24.4 m:level_4_2=10.1 m:level_2_1=908 m:level_1_2=13.1 m:level_1_1=489 m:number_tested=3726 m:level_3_2=52.4 m:level_3_4_1=2329 m:level_3_1=1953
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

entity e:zpd4-gad8 l:"NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/zpd4-gad8

property e:zpd4-gad8 t:meta.view v:id=zpd4-gad8 v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - By English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:zpd4-gad8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zpd4-gad8 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | ELL      | 3754          | 645              | 876       | 23.3      | 1037      | 27.6      | 1639      | 43.7      | 202       | 5.4       | 1841        | 49.0        | 
| BRONX   | 3     | 2006 | EP       | 12691         | 669              | 1186      | 9.3       | 2220      | 17.5      | 6979      | 55.0      | 2306      | 18.2      | 9285        | 73.2        | 
| BRONX   | 3     | 2007 | ELL      | 3726          | 659              | 489       | 13.1      | 908       | 24.4      | 1953      | 52.4      | 376       | 10.1      | 2329        | 62.5        | 
| BRONX   | 3     | 2007 | EP       | 12463         | 678              | 756       | 6.1       | 1732      | 13.9      | 7043      | 56.5      | 2932      | 23.5      | 9975        | 80.0        | 
| BRONX   | 3     | 2008 | ELL      | 3311          | 666              | 205       | 6.2       | 620       | 18.7      | 2242      | 67.7      | 244       | 7.4       | 2486        | 75.1        | 
| BRONX   | 3     | 2008 | EP       | 12325         | 680              | 465       | 3.8       | 1441      | 11.7      | 8205      | 66.6      | 2214      | 18.0      | 10419       | 84.5        | 
| BRONX   | 3     | 2009 | ELL      | 3370          | 672              | 95        | 2.8       | 523       | 15.5      | 2417      | 71.7      | 335       | 9.9       | 2752        | 81.7        | 
| BRONX   | 3     | 2009 | EP       | 12439         | 684              | 163       | 1.3       | 1043      | 8.4       | 8878      | 71.4      | 2355      | 18.9      | 11233       | 90.3        | 
| BRONX   | 3     | 2010 | ELL      | 3696          | 673              | 975       | 26.4      | 1642      | 44.4      | 839       | 22.7      | 240       | 6.5       | 1079        | 29.2        | 
| BRONX   | 3     | 2010 | EP       | 12170         | 686              | 1663      | 13.7      | 4695      | 38.6      | 3790      | 31.1      | 2022      | 16.6      | 5812        | 47.8        | 
```