# NYS Math Test Results By Grade 2006-2011 - District - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-district-all-students-714d7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gyaz-82xj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gyaz-82xj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gyaz-82xj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gyaz-82xj |
| Name | NYS Math Test Results By Grade 2006-2011 - District - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:42:04Z |
| Publication Date | 2011-10-11T18:09:28Z |

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
series e:gyaz-82xj d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:district=1 m:level_4_1=209 m:level_3_4_2=74 m:mean_scale_score=673 m:level_2_2=18.2 m:level_4_2=22.3 m:level_2_1=170 m:level_1_2=7.8 m:level_1_1=73 m:number_tested=936 m:level_3_2=51.7 m:level_3_4_1=693 m:level_3_1=484

series e:gyaz-82xj d:2007-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:district=1 m:level_4_1=191 m:level_3_4_2=84 m:mean_scale_score=679 m:level_2_2=10.3 m:level_4_2=22.8 m:level_2_1=86 m:level_1_2=5.7 m:level_1_1=48 m:number_tested=836 m:level_3_2=61.1 m:level_3_4_1=702 m:level_3_1=511

series e:gyaz-82xj d:2008-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:district=1 m:level_4_1=214 m:level_3_4_2=87.1 m:mean_scale_score=686 m:level_2_2=10.9 m:level_4_2=24.8 m:level_2_1=94 m:level_1_2=2 m:level_1_1=17 m:number_tested=862 m:level_3_2=62.3 m:level_3_4_1=751 m:level_3_1=537
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

entity e:gyaz-82xj l:"NYS Math Test Results By Grade 2006-2011 - District - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/gyaz-82xj

property e:gyaz-82xj t:meta.view v:id=gyaz-82xj v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - District - All Students" v:attribution="Department of Education (DOE)"

property e:gyaz-82xj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gyaz-82xj t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | All Students | 936           | 673              | 73        | 7.8       | 170       | 18.2      | 484       | 51.7      | 209       | 22.3      | 693         | 74.0        | 
| 1        | 3     | 2007 | All Students | 836           | 679              | 48        | 5.7       | 86        | 10.3      | 511       | 61.1      | 191       | 22.8      | 702         | 84.0        | 
| 1        | 3     | 2008 | All Students | 862           | 686              | 17        | 2.0       | 94        | 10.9      | 537       | 62.3      | 214       | 24.8      | 751         | 87.1        | 
| 1        | 3     | 2009 | All Students | 914           | 691              | 8         | 0.9       | 66        | 7.2       | 598       | 65.4      | 242       | 26.5      | 840         | 91.9        | 
| 1        | 3     | 2010 | All Students | 866           | 697              | 89        | 10.3      | 257       | 29.7      | 279       | 32.2      | 241       | 27.8      | 520         | 60.0        | 
| 1        | 3     | 2011 | All Students | 826           | 689              | 78        | 9.4       | 247       | 29.9      | 319       | 38.6      | 182       | 22.0      | 501         | 60.7        | 
| 1        | 4     | 2006 | All Students | 895           | 670              | 80        | 8.9       | 188       | 21.0      | 422       | 47.2      | 205       | 22.9      | 627         | 70.1        | 
| 1        | 4     | 2007 | All Students | 868           | 673              | 68        | 7.8       | 167       | 19.2      | 440       | 50.7      | 193       | 22.2      | 633         | 72.9        | 
| 1        | 4     | 2008 | All Students | 848           | 677              | 44        | 5.2       | 149       | 17.6      | 454       | 53.5      | 201       | 23.7      | 655         | 77.2        | 
| 1        | 4     | 2009 | All Students | 846           | 685              | 55        | 6.5       | 90        | 10.6      | 413       | 48.8      | 288       | 34.0      | 701         | 82.9        | 
```