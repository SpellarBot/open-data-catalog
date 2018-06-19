# English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Race-Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-school-level-by-race-ethnicity-83606) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g8e6-y4ax) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g8e6-y4ax/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g8e6-y4ax/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g8e6-y4ax |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Race-Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:12:24Z |
| Publication Date | 2011-10-11T18:08:44Z |

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
| Yes      | series tag     | dbn              | DBN              | text      | text        |
| Yes      | series tag     | grade            | Grade            | text      | text        |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | series tag     | category         | Category         | text      | text        |
| Yes      | numeric metric | number_tested    | Number Tested    | number    | number      |
| Yes      | numeric metric | mean_scale_score | Mean Scale Score | number    | number      |
| Yes      | series tag     | level_1_1        | Level 1 #        | text      | text        |
| Yes      | numeric metric | level_1_2        | Level 1 %        | percent   | percent     |
| Yes      | series tag     | level_2_1        | Level 2 #        | text      | text        |
| Yes      | numeric metric | level_2_2        | Level 2 %        | percent   | percent     |
| Yes      | series tag     | level_3_1        | Level 3 #        | text      | text        |
| Yes      | numeric metric | level_3_2        | Level 3 %        | percent   | percent     |
| Yes      | series tag     | level_4_1        | Level 4 #        | text      | text        |
| Yes      | numeric metric | level_4_2        | Level 4 %        | percent   | percent     |
| Yes      | series tag     | level_3_4_1      | Level 3+4 #      | text      | text        |
| Yes      | numeric metric | level_3_4_2      | Level 3+4 %      | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g8e6-y4ax d:2006-01-01T00:00:00.000Z t:category=Asian t:level_4_1=s t:dbn=01M015 t:level_2_1=s t:grade=3 t:level_1_1=s t:level_3_4_1=s t:level_3_1=s m:number_tested=1

series e:g8e6-y4ax d:2006-01-01T00:00:00.000Z t:category=Asian t:level_4_1=s t:dbn=01M015 t:level_2_1=s t:grade=4 t:level_1_1=s t:level_3_4_1=s t:level_3_1=s m:number_tested=1

series e:g8e6-y4ax d:2006-01-01T00:00:00.000Z t:category=Asian t:level_4_1=s t:dbn=01M015 t:level_2_1=s t:grade=5 t:level_1_1=s t:level_3_4_1=s t:level_3_1=s m:number_tested=1
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:level_1_2 p:float l:"Level 1 %" t:dataTypeName=percent

metric m:level_2_2 p:float l:"Level 2 %" t:dataTypeName=percent

metric m:level_3_2 p:float l:"Level 3 %" t:dataTypeName=percent

metric m:level_4_2 p:float l:"Level 4 %" t:dataTypeName=percent

metric m:level_3_4_2 p:float l:"Level 3+4 %" t:dataTypeName=percent

entity e:g8e6-y4ax l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Race-Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/g8e6-y4ax

property e:g8e6-y4ax t:meta.view v:id=g8e6-y4ax v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - School level - by Race-Ethnicity" v:attribution="Department of Education (DOE)"

property e:g8e6-y4ax t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g8e6-y4ax t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | grade      | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ====== | ========== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 01M015 | 3          | 2006 | Asian    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 4          | 2006 | Asian    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 5          | 2006 | Asian    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | All Grades | 2006 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 3          | 2007 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 4          | 2007 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 5          | 2007 | Asian    | 2             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | All Grades | 2007 | Asian    | 8             |                  | 3         | 37.5      | 4         | 50.0      | 1         | 12.5      | 0         | 0.0       | 1           | 12.5        | 
| 01M015 | 3          | 2008 | Asian    | 1             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
| 01M015 | 4          | 2008 | Asian    | 3             |                  | s         |           | s         |           | s         |           | s         |           | s           |             | 
```