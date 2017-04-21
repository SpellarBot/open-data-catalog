# NYS Math Test Results by Grade 2006-2011 - Citywide - by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-citywide-by-gender-c0461) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c5sh-m8tb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c5sh-m8tb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c5sh-m8tb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c5sh-m8tb |
| Name | NYS Math Test Results by Grade 2006-2011 - Citywide - by Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:50:00Z |
| Publication Date | 2011-10-11T17:08:38Z |

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
series e:c5sh-m8tb d:2006-01-01T00:00:00.000Z t:category=Female t:grade=3 m:level_4_1=8912 m:level_3_4_2=76.1 m:mean_scale_score=675 m:level_2_2=15.7 m:level_4_2=25 m:level_2_1=5613 m:level_1_2=8.2 m:level_1_1=2908 m:number_tested=35655 m:level_3_2=51.1 m:level_3_4_1=27134 m:level_3_1=18222

series e:c5sh-m8tb d:2006-01-01T00:00:00.000Z t:category=Female t:grade=4 m:level_4_1=7435 m:level_3_4_2=70.7 m:mean_scale_score=670 m:level_2_2=20 m:level_4_2=21.1 m:level_2_1=7069 m:level_1_2=9.3 m:level_1_1=3283 m:number_tested=35287 m:level_3_2=49.6 m:level_3_4_1=24935 m:level_3_1=17500

series e:c5sh-m8tb d:2006-01-01T00:00:00.000Z t:category=Female t:grade=5 m:level_4_1=6120 m:level_3_4_2=61.9 m:mean_scale_score=661 m:level_2_2=26.4 m:level_4_2=16.7 m:level_2_1=9697 m:level_1_2=11.7 m:level_1_1=4284 m:number_tested=36667 m:level_3_2=45.2 m:level_3_4_1=22686 m:level_3_1=16566
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

entity e:c5sh-m8tb l:"NYS Math Test Results by Grade 2006-2011 - Citywide - by Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/c5sh-m8tb

property e:c5sh-m8tb t:meta.view v:id=c5sh-m8tb v:category=Education v:averageRating=0 v:name="NYS Math Test Results by Grade 2006-2011 - Citywide - by Gender" v:attribution="Department of Education (DOE)"

property e:c5sh-m8tb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c5sh-m8tb t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade      | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ========== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3          | 2006 | Female   | 35655         | 675              | 2908      | 8.2       | 5613      | 15.7      | 18222     | 51.1      | 8912      | 25.0      | 27134       | 76.1        | 
| 4          | 2006 | Female   | 35287         | 670              | 3283      | 9.3       | 7069      | 20.0      | 17500     | 49.6      | 7435      | 21.1      | 24935       | 70.7        | 
| 5          | 2006 | Female   | 36667         | 661              | 4284      | 11.7      | 9697      | 26.4      | 16566     | 45.2      | 6120      | 16.7      | 22686       | 61.9        | 
| 6          | 2006 | Female   | 36002         | 651              | 5893      | 16.4      | 10836     | 30.1      | 15043     | 41.8      | 4230      | 11.7      | 19273       | 53.5        | 
| 7          | 2006 | Female   | 36891         | 643              | 6260      | 17.0      | 13869     | 37.6      | 13801     | 37.4      | 2961      | 8.0       | 16762       | 45.4        | 
| 8          | 2006 | Female   | 37429         | 642              | 8372      | 22.4      | 13820     | 36.9      | 12247     | 32.7      | 2990      | 8.0       | 15237       | 40.7        | 
| All Grades | 2006 | Female   | 217931        | 657              | 31000     | 14.2      | 60904     | 27.9      | 93379     | 42.8      | 32648     | 15.0      | 126027      | 57.8        | 
| 3          | 2007 | Female   | 35240         | 685              | 1602      | 4.5       | 4344      | 12.3      | 18552     | 52.6      | 10742     | 30.5      | 29294       | 83.1        | 
| 4          | 2007 | Female   | 34602         | 675              | 2476      | 7.2       | 6453      | 18.6      | 17668     | 51.1      | 8005      | 23.1      | 25673       | 74.2        | 
| 5          | 2007 | Female   | 35281         | 671              | 2284      | 6.5       | 7614      | 21.6      | 17957     | 50.9      | 7426      | 21.0      | 25383       | 71.9        | 
```