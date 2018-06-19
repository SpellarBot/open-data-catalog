# NYS Math Test Results by Grade 2006-2011 - Citywide - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-citywide-all-students-fc606) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j2sr-pm3b) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j2sr-pm3b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j2sr-pm3b/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j2sr-pm3b |
| Name | NYS Math Test Results by Grade 2006-2011 - Citywide - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:37:24Z |
| Publication Date | 2011-10-11T17:10:50Z |

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
series e:j2sr-pm3b d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 m:level_4_1=17938 m:level_3_4_2=75.3 m:mean_scale_score=674 m:level_2_2=15.6 m:level_4_2=24.4 m:level_2_1=11431 m:level_1_2=9.1 m:level_1_1=6714 m:number_tested=73413 m:level_3_2=50.8 m:level_3_4_1=55268 m:level_3_1=37330

series e:j2sr-pm3b d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=4 m:level_4_1=15764 m:level_3_4_2=70.9 m:mean_scale_score=669 m:level_2_2=18.9 m:level_4_2=21.7 m:level_2_1=13668 m:level_1_2=10.3 m:level_1_1=7455 m:number_tested=72501 m:level_3_2=49.1 m:level_3_4_1=51378 m:level_3_1=35614

series e:j2sr-pm3b d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=5 m:level_4_1=12599 m:level_3_4_2=61.3 m:mean_scale_score=660 m:level_2_2=25.4 m:level_4_2=16.9 m:level_2_1=18916 m:level_1_2=13.3 m:level_1_1=9883 m:number_tested=74454 m:level_3_2=44.4 m:level_3_4_1=45655 m:level_3_1=33056
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

entity e:j2sr-pm3b l:"NYS Math Test Results by Grade 2006-2011 - Citywide - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/j2sr-pm3b

property e:j2sr-pm3b t:meta.view v:id=j2sr-pm3b v:category=Education v:averageRating=0 v:name="NYS Math Test Results by Grade 2006-2011 - Citywide - All Students" v:attribution="Department of Education (DOE)"

property e:j2sr-pm3b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j2sr-pm3b t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade      | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ========== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3          | 2006 | All Students | 73413         | 674              | 6714      | 9.1       | 11431     | 15.6      | 37330     | 50.8      | 17938     | 24.4      | 55268       | 75.3        | 
| 4          | 2006 | All Students | 72501         | 669              | 7455      | 10.3      | 13668     | 18.9      | 35614     | 49.1      | 15764     | 21.7      | 51378       | 70.9        | 
| 5          | 2006 | All Students | 74454         | 660              | 9883      | 13.3      | 18916     | 25.4      | 33056     | 44.4      | 12599     | 16.9      | 45655       | 61.3        | 
| 6          | 2006 | All Students | 74000         | 650              | 13322     | 18.0      | 21710     | 29.3      | 30329     | 41.0      | 8639      | 11.7      | 38968       | 52.7        | 
| 7          | 2006 | All Students | 75543         | 641              | 14231     | 18.8      | 28231     | 37.4      | 27189     | 36.0      | 5892      | 7.8       | 33081       | 43.8        | 
| 8          | 2006 | All Students | 76286         | 640              | 18485     | 24.2      | 28153     | 36.9      | 24043     | 31.5      | 5605      | 7.3       | 29648       | 38.9        | 
| All Grades | 2006 | All Students | 446197        | 656              | 70090     | 15.7      | 122109    | 27.4      | 187561    | 42.0      | 66437     | 14.9      | 253998      | 57.0        | 
| 3          | 2007 | All Students | 72196         | 683              | 3907      | 5.4       | 8918      | 12.4      | 38117     | 52.8      | 21254     | 29.4      | 59371       | 82.2        | 
| 4          | 2007 | All Students | 71199         | 675              | 5765      | 8.1       | 12683     | 17.8      | 35724     | 50.2      | 17027     | 23.9      | 52751       | 74.1        | 
| 5          | 2007 | All Students | 72514         | 670              | 5526      | 7.6       | 15416     | 21.3      | 36239     | 50.0      | 15333     | 21.1      | 51572       | 71.1        | 
```