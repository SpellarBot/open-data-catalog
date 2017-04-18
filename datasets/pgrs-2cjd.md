# NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-by-race-ethnicity-0058b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pgrs-2cjd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pgrs-2cjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pgrs-2cjd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pgrs-2cjd |
| Name | NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:55:29Z |
| Publication Date | 2011-10-11T18:11:37Z |

## Description

New York City Results on the New York State Mathematics Tests, Grades 3 - 8
Notes:
As of 2006, the New York State Education Department expanded the ELA and mathematics testing programs to Grades 3-8. Previously, state tests were administered in Grades 4 and 8 and citywide tests were administered in Grades 3, 5, 6, and 7.
In 2006, NYSED treated District 75 students as a distinct geographic district. For 2007-2011, District 75 students are represented in their home districts and boroughs. Spreadsheets for District and Borough do not include District 75 students in 2006.
Starting in 2010, NYSED changed the scale score required to meet each of the proficiency levels, increasing the number of questions students needed to answer correctly to meet proficiency.

Rows are suppressed (noted with ‘s’) if the number of tested students was 5 or fewer.

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
series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 t:district=1 m:level_4_1=79 m:level_3_4_2=94.8 m:mean_scale_score=704 m:level_2_2=2.6 m:level_4_2=51 m:level_2_1=4 m:level_1_2=2.6 m:level_1_1=4 m:number_tested=155 m:level_3_2=43.9 m:level_3_4_1=147 m:level_3_1=68

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 t:district=1 m:level_4_1=13 m:level_3_4_2=63.2 m:mean_scale_score=659 m:level_2_2=25.4 m:level_4_2=7 m:level_2_1=47 m:level_1_2=11.4 m:level_1_1=21 m:number_tested=185 m:level_3_2=56.2 m:level_3_4_1=117 m:level_3_1=104

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 t:district=1 m:level_4_1=73 m:level_3_4_2=68.2 m:mean_scale_score=664 m:level_2_2=22.5 m:level_4_2=14.8 m:level_2_1=111 m:level_1_2=9.3 m:level_1_1=46 m:number_tested=494 m:level_3_2=53.4 m:level_3_4_1=337 m:level_3_1=264
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

entity e:pgrs-2cjd l:"NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pgrs-2cjd

property e:pgrs-2cjd t:meta.view v:id=pgrs-2cjd v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" v:attribution="Department of Education (DOE)"

property e:pgrs-2cjd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pgrs-2cjd t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | Asian    | 155           | 704              | 4         | 2.6       | 4         | 2.6       | 68        | 43.9      | 79        | 51.0      | 147         | 94.8        | 
| 1        | 3     | 2006 | Black    | 185           | 659              | 21        | 11.4      | 47        | 25.4      | 104       | 56.2      | 13        | 7.0       | 117         | 63.2        | 
| 1        | 3     | 2006 | Hispanic | 494           | 664              | 46        | 9.3       | 111       | 22.5      | 264       | 53.4      | 73        | 14.8      | 337         | 68.2        | 
| 1        | 3     | 2006 | White    | 94            | 702              | 1         | 1.1       | 5         | 5.3       | 45        | 47.9      | 43        | 45.7      | 88          | 93.6        | 
| 1        | 3     | 2007 | Asian    | 131           | 703              | 2         | 1.5       | 4         | 3.1       | 58        | 44.3      | 67        | 51.1      | 125         | 95.4        | 
| 1        | 3     | 2007 | Black    | 150           | 668              | 17        | 11.3      | 24        | 16.0      | 85        | 56.7      | 24        | 16.0      | 109         | 72.7        | 
| 1        | 3     | 2007 | Hispanic | 440           | 672              | 28        | 6.4       | 53        | 12.0      | 301       | 68.4      | 58        | 13.2      | 359         | 81.6        | 
| 1        | 3     | 2007 | White    | 89            | 702              | 0         | 0.0       | 2         | 2.2       | 49        | 55.1      | 38        | 42.7      | 87          | 97.8        | 
| 1        | 3     | 2008 | Asian    | 137           | 713              | 0         | 0.0       | 3         | 2.2       | 54        | 39.4      | 80        | 58.4      | 134         | 97.8        | 
| 1        | 3     | 2008 | Black    | 150           | 675              | 4         | 2.7       | 22        | 14.7      | 99        | 66.0      | 25        | 16.7      | 124         | 82.7        | 
```