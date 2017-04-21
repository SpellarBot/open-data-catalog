# English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-citywide-all-students-7e180) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9bmk-bbj5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9bmk-bbj5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9bmk-bbj5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9bmk-bbj5 |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T18:42:54Z |
| Publication Date | 2011-10-11T17:16:17Z |

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
series e:9bmk-bbj5 d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 m:level_4_1=3179 m:level_3_4_2=61.5 m:mean_scale_score=661 m:level_2_2=26.6 m:level_4_2=5.2 m:level_2_1=16353 m:level_1_2=11.9 m:level_1_1=7331 m:number_tested=61478 m:level_3_2=56.3 m:level_3_4_1=37794 m:level_3_1=34615

series e:9bmk-bbj5 d:2007-01-01T00:00:00.000Z t:category="All Students" t:grade=3 m:level_4_1=4375 m:level_3_4_2=56.4 m:mean_scale_score=656 m:level_2_2=30.6 m:level_4_2=6.2 m:level_2_1=21735 m:level_1_2=13 m:level_1_1=9249 m:number_tested=71045 m:level_3_2=50.2 m:level_3_4_1=40070 m:level_3_1=35695

series e:9bmk-bbj5 d:2008-01-01T00:00:00.000Z t:category="All Students" t:grade=3 m:level_4_1=5532 m:level_3_4_2=59.9 m:mean_scale_score=659 m:level_2_2=31.2 m:level_4_2=8 m:level_2_1=21504 m:level_1_2=8.9 m:level_1_1=6131 m:number_tested=68883 m:level_3_2=51.9 m:level_3_4_1=41248 m:level_3_1=35716
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

entity e:9bmk-bbj5 l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/9bmk-bbj5

property e:9bmk-bbj5 t:meta.view v:id=9bmk-bbj5 v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - All Students" v:attribution="Department of Education (DOE)"

property e:9bmk-bbj5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9bmk-bbj5 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ===== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3     | 2006 | All Students | 61478         | 661              | 7331      | 11.9      | 16353     | 26.6      | 34615     | 56.3      | 3179      | 5.2       | 37794       | 61.5        | 
| 3     | 2007 | All Students | 71045         | 656              | 9249      | 13.0      | 21735     | 30.6      | 35695     | 50.2      | 4375      | 6.2       | 40070       | 56.4        | 
| 3     | 2008 | All Students | 68883         | 659              | 6131      | 8.9       | 21504     | 31.2      | 35716     | 51.9      | 5532      | 8.0       | 41248       | 59.9        | 
| 3     | 2009 | All Students | 70074         | 664              | 4546      | 6.5       | 16906     | 24.1      | 43067     | 61.5      | 5555      | 7.9       | 48622       | 69.4        | 
| 3     | 2010 | All Students | 69629         | 663              | 12632     | 18.1      | 24590     | 35.3      | 23389     | 33.6      | 9018      | 13.0      | 32407       | 46.5        | 
| 3     | 2011 | All Students | 71060         | 660              | 11353     | 16.0      | 25520     | 35.9      | 31807     | 44.8      | 2380      | 3.3       | 34187       | 48.1        | 
| 4     | 2006 | All Students | 64467         | 657              | 7602      | 11.8      | 18876     | 29.3      | 34196     | 53.0      | 3793      | 5.9       | 37989       | 58.9        | 
| 4     | 2007 | All Students | 69933         | 654              | 8073      | 11.5      | 22693     | 32.4      | 35724     | 51.1      | 3453      | 4.9       | 39177       | 56.0        | 
| 4     | 2008 | All Students | 69364         | 657              | 7306      | 10.5      | 19545     | 28.2      | 38517     | 55.5      | 3996      | 5.8       | 42513       | 61.3        | 
| 4     | 2009 | All Students | 68555         | 663              | 4068      | 5.9       | 17252     | 25.2      | 43643     | 63.7      | 3592      | 5.2       | 47235       | 68.9        | 
```