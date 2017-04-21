# English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Race-Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-boro-by-race-ethnicity-96731) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xjcm-e5uy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xjcm-e5uy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xjcm-e5uy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xjcm-e5uy |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Race-Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:14:46Z |
| Publication Date | 2011-10-11T17:12:53Z |

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
series e:xjcm-e5uy d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 t:borough=BRONX m:level_4_1=33 m:level_3_4_2=69.8 m:mean_scale_score=668 m:level_2_2=21.8 m:level_4_2=7.3 m:level_2_1=98 m:level_1_2=8.4 m:level_1_1=38 m:number_tested=450 m:level_3_2=62.4 m:level_3_4_1=314 m:level_3_1=281

series e:xjcm-e5uy d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 t:borough=BRONX m:level_4_1=96 m:level_3_4_2=46.4 m:mean_scale_score=647 m:level_2_2=35.8 m:level_4_2=1.9 m:level_2_1=1816 m:level_1_2=17.8 m:level_1_1=904 m:number_tested=5075 m:level_3_2=44.5 m:level_3_4_1=2355 m:level_3_1=2259

series e:xjcm-e5uy d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 t:borough=BRONX m:level_4_1=155 m:level_3_4_2=50 m:mean_scale_score=650 m:level_2_2=33.8 m:level_4_2=2.2 m:level_2_1=2393 m:level_1_2=16.2 m:level_1_1=1146 m:number_tested=7077 m:level_3_2=47.8 m:level_3_4_1=3538 m:level_3_1=3383
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

entity e:xjcm-e5uy l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Race-Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/xjcm-e5uy

property e:xjcm-e5uy t:meta.view v:id=xjcm-e5uy v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Race-Ethnicity" v:attribution="Department of Education (DOE)"

property e:xjcm-e5uy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xjcm-e5uy t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | Asian    | 450           | 668              | 38        | 8.4       | 98        | 21.8      | 281       | 62.4      | 33        | 7.3       | 314         | 69.8        | 
| BRONX   | 3     | 2006 | Black    | 5075          | 647              | 904       | 17.8      | 1816      | 35.8      | 2259      | 44.5      | 96        | 1.9       | 2355        | 46.4        | 
| BRONX   | 3     | 2006 | Hispanic | 7077          | 650              | 1146      | 16.2      | 2393      | 33.8      | 3383      | 47.8      | 155       | 2.2       | 3538        | 50.0        | 
| BRONX   | 3     | 2006 | White    | 626           | 673              | 47        | 7.5       | 125       | 20.0      | 401       | 64.1      | 53        | 8.5       | 454         | 72.5        | 
| BRONX   | 3     | 2007 | Asian    | 537           | 664              | 47        | 8.8       | 129       | 24.0      | 321       | 59.8      | 40        | 7.4       | 361         | 67.2        | 
| BRONX   | 3     | 2007 | Black    | 5021          | 644              | 890       | 17.7      | 1895      | 37.7      | 2129      | 42.4      | 107       | 2.1       | 2236        | 44.5        | 
| BRONX   | 3     | 2007 | Hispanic | 9574          | 642              | 1927      | 20.1      | 3661      | 38.2      | 3765      | 39.3      | 221       | 2.3       | 3986        | 41.6        | 
| BRONX   | 3     | 2007 | White    | 613           | 668              | 50        | 8.2       | 137       | 22.3      | 370       | 60.4      | 56        | 9.1       | 426         | 69.5        | 
| BRONX   | 3     | 2008 | Asian    | 513           | 669              | 20        | 3.9       | 127       | 24.8      | 311       | 60.6      | 55        | 10.7      | 366         | 71.3        | 
| BRONX   | 3     | 2008 | Black    | 4793          | 650              | 602       | 12.6      | 1808      | 37.7      | 2204      | 46.0      | 179       | 3.7       | 2383        | 49.7        | 
```