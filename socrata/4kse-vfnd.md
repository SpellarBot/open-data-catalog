# English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-boro-all-students-87c18) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4kse-vfnd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4kse-vfnd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4kse-vfnd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4kse-vfnd |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T19:57:19Z |
| Publication Date | 2011-10-11T17:14:30Z |

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
series e:4kse-vfnd d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=338 m:level_3_4_2=50.3 m:mean_scale_score=650 m:level_2_2=33.5 m:level_4_2=2.5 m:level_2_1=4457 m:level_1_2=16.2 m:level_1_1=2154 m:number_tested=13296 m:level_3_2=47.7 m:level_3_4_1=6685 m:level_3_1=6347

series e:4kse-vfnd d:2007-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=432 m:level_3_4_2=44.6 m:mean_scale_score=645 m:level_2_2=36.9 m:level_4_2=2.7 m:level_2_1=5864 m:level_1_2=18.5 m:level_1_1=2934 m:number_tested=15871 m:level_3_2=41.8 m:level_3_4_1=7073 m:level_3_1=6641

series e:4kse-vfnd d:2008-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=621 m:level_3_4_2=48.7 m:mean_scale_score=649 m:level_2_2=38.1 m:level_4_2=4 m:level_2_1=5862 m:level_1_2=13.1 m:level_1_1=2022 m:number_tested=15380 m:level_3_2=44.7 m:level_3_4_1=7496 m:level_3_1=6875
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

entity e:4kse-vfnd l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/4kse-vfnd

property e:4kse-vfnd t:meta.view v:id=4kse-vfnd v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - All Students" v:attribution="Department of Education (DOE)"

property e:4kse-vfnd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4kse-vfnd t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | All Students | 13296         | 650              | 2154      | 16.2      | 4457      | 33.5      | 6347      | 47.7      | 338       | 2.5       | 6685        | 50.3        | 
| BRONX   | 3     | 2007 | All Students | 15871         | 645              | 2934      | 18.5      | 5864      | 36.9      | 6641      | 41.8      | 432       | 2.7       | 7073        | 44.6        | 
| BRONX   | 3     | 2008 | All Students | 15380         | 649              | 2022      | 13.1      | 5862      | 38.1      | 6875      | 44.7      | 621       | 4.0       | 7496        | 48.7        | 
| BRONX   | 3     | 2009 | All Students | 15531         | 655              | 1450      | 9.3       | 4837      | 31.1      | 8658      | 55.7      | 586       | 3.8       | 9244        | 59.5        | 
| BRONX   | 3     | 2010 | All Students | 15454         | 657              | 3845      | 24.9      | 6080      | 39.3      | 4331      | 28.0      | 1198      | 7.8       | 5529        | 35.8        | 
| BRONX   | 3     | 2011 | All Students | 15434         | 654              | 3520      | 22.8      | 6468      | 41.9      | 5242      | 34.0      | 204       | 1.3       | 5446        | 35.3        | 
| BRONX   | 4     | 2006 | All Students | 13655         | 647              | 2182      | 16.0      | 4854      | 35.5      | 6224      | 45.6      | 395       | 2.9       | 6619        | 48.5        | 
| BRONX   | 4     | 2007 | All Students | 15775         | 644              | 2471      | 15.7      | 6166      | 39.1      | 6770      | 42.9      | 368       | 2.3       | 7138        | 45.2        | 
| BRONX   | 4     | 2008 | All Students | 15434         | 645              | 2372      | 15.4      | 5467      | 35.4      | 7224      | 46.8      | 371       | 2.4       | 7595        | 49.2        | 
| BRONX   | 4     | 2009 | All Students | 15237         | 654              | 1284      | 8.4       | 4845      | 31.8      | 8780      | 57.6      | 328       | 2.2       | 9108        | 59.8        | 
```