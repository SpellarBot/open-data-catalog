# English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by English Proficiency Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-boro-by-english-proficiency-stat-b8459) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vn2t-jh2b) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vn2t-jh2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vn2t-jh2b/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vn2t-jh2b |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by English Proficiency Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:02:26Z |
| Publication Date | 2011-10-11T17:14:09Z |

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
series e:vn2t-jh2b d:2006-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=1 m:level_3_4_2=19.3 m:mean_scale_score=618 m:level_2_2=35.6 m:level_4_2=0.1 m:level_2_1=273 m:level_1_2=45 m:level_1_1=345 m:number_tested=766 m:level_3_2=19.2 m:level_3_4_1=148 m:level_3_1=147

series e:vn2t-jh2b d:2006-01-01T00:00:00.000Z t:category=EP t:grade=3 t:borough=BRONX m:level_4_1=337 m:level_3_4_2=52.2 m:mean_scale_score=652 m:level_2_2=33.4 m:level_4_2=2.7 m:level_2_1=4184 m:level_1_2=14.4 m:level_1_1=1809 m:number_tested=12530 m:level_3_2=49.5 m:level_3_4_1=6537 m:level_3_1=6200

series e:vn2t-jh2b d:2007-01-01T00:00:00.000Z t:category=ELL t:grade=3 t:borough=BRONX m:level_4_1=5 m:level_3_4_2=22.2 m:mean_scale_score=626 m:level_2_2=45.8 m:level_4_2=0.2 m:level_2_1=1441 m:level_1_2=31.9 m:level_1_1=1004 m:number_tested=3143 m:level_3_2=22 m:level_3_4_1=698 m:level_3_1=693
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

entity e:vn2t-jh2b l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by English Proficiency Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vn2t-jh2b

property e:vn2t-jh2b t:meta.view v:id=vn2t-jh2b v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by English Proficiency Status" v:attribution="Department of Education (DOE)"

property e:vn2t-jh2b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vn2t-jh2b t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | ELL      | 766           | 618              | 345       | 45.0      | 273       | 35.6      | 147       | 19.2      | 1         | 0.1       | 148         | 19.3        | 
| BRONX   | 3     | 2006 | EP       | 12530         | 652              | 1809      | 14.4      | 4184      | 33.4      | 6200      | 49.5      | 337       | 2.7       | 6537        | 52.2        | 
| BRONX   | 3     | 2007 | ELL      | 3143          | 626              | 1004      | 31.9      | 1441      | 45.8      | 693       | 22.0      | 5         | 0.2       | 698         | 22.2        | 
| BRONX   | 3     | 2007 | EP       | 12728         | 649              | 1930      | 15.2      | 4423      | 34.8      | 5948      | 46.7      | 427       | 3.4       | 6375        | 50.1        | 
| BRONX   | 3     | 2008 | ELL      | 3092          | 631              | 764       | 24.7      | 1574      | 50.9      | 728       | 23.5      | 26        | 0.8       | 754         | 24.4        | 
| BRONX   | 3     | 2008 | EP       | 12288         | 654              | 1258      | 10.2      | 4288      | 34.9      | 6147      | 50.0      | 595       | 4.8       | 6742        | 54.9        | 
| BRONX   | 3     | 2009 | ELL      | 3136          | 639              | 596       | 19.0      | 1307      | 41.7      | 1208      | 38.5      | 25        | 0.8       | 1233        | 39.3        | 
| BRONX   | 3     | 2009 | EP       | 12395         | 659              | 854       | 6.9       | 3530      | 28.5      | 7450      | 60.1      | 561       | 4.5       | 8011        | 64.6        | 
| BRONX   | 3     | 2010 | ELL      | 3346          | 646              | 1374      | 41.1      | 1333      | 39.8      | 564       | 16.9      | 75        | 2.2       | 639         | 19.1        | 
| BRONX   | 3     | 2010 | EP       | 12108         | 659              | 2471      | 20.4      | 4747      | 39.2      | 3767      | 31.1      | 1123      | 9.3       | 4890        | 40.4        | 
```