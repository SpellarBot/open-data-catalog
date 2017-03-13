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
| Rows Updated | 2011-10-05T22:55:51Z |

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
series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 t:district=1 m:level_4_1=79 m:level_3_4_2=94.8 m:mean_scale_score=704 m:level_2_2=2.6 m:level_4_2=51 m:level_2_1=4 m:level_1_2=2.6 m:level_1_1=4 m:number_tested=155 m:level_3_2=43.9 m:level_3_4_1=147 m:level_3_1=68

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 t:district=1 m:level_4_1=13 m:level_3_4_2=63.2 m:mean_scale_score=659 m:level_2_2=25.4 m:level_4_2=7 m:level_2_1=47 m:level_1_2=11.4 m:level_1_1=21 m:number_tested=185 m:level_3_2=56.2 m:level_3_4_1=117 m:level_3_1=104

series e:pgrs-2cjd d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 t:district=1 m:level_4_1=73 m:level_3_4_2=68.2 m:mean_scale_score=664 m:level_2_2=22.5 m:level_4_2=14.8 m:level_2_1=111 m:level_1_2=9.3 m:level_1_1=46 m:number_tested=494 m:level_3_2=53.4 m:level_3_4_1=337 m:level_3_1=264
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_1 p:integer l:"Level 1 #" t:dataTypeName=number

metric m:level_2_1 p:integer l:"Level 2 #" t:dataTypeName=number

metric m:level_3_1 p:integer l:"Level 3 #" t:dataTypeName=number

metric m:level_4_1 p:integer l:"Level 4 #" t:dataTypeName=number

metric m:level_3_4_1 p:integer l:"Level 3+4 #" t:dataTypeName=number

entity e:pgrs-2cjd l:"NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pgrs-2cjd

property e:pgrs-2cjd t:meta.view v:id=pgrs-2cjd v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - By Race- Ethnicity" v:attribution="Department of Education (DOE)"

property e:pgrs-2cjd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:pgrs-2cjd t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```