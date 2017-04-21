# English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-district-by-gender-0f5a3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/htkc-b6ea) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/htkc-b6ea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/htkc-b6ea/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | htkc-b6ea |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:35:59Z |
| Publication Date | 2011-10-11T18:06:07Z |

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
series e:htkc-b6ea d:2006-01-01T00:00:00.000Z t:category=Female t:grade=3 t:district=1 m:level_4_1=19 m:level_3_4_2=67.4 m:mean_scale_score=667 m:level_2_2=23.8 m:level_4_2=4.4 m:level_2_1=103 m:level_1_2=8.8 m:level_1_1=38 m:number_tested=432 m:level_3_2=63 m:level_3_4_1=291 m:level_3_1=272

series e:htkc-b6ea d:2006-01-01T00:00:00.000Z t:category=Male t:grade=3 t:district=1 m:level_4_1=23 m:level_3_4_2=56.8 m:mean_scale_score=658 m:level_2_2=29.9 m:level_4_2=6.1 m:level_2_1=112 m:level_1_2=13.3 m:level_1_1=50 m:number_tested=375 m:level_3_2=50.7 m:level_3_4_1=213 m:level_3_1=190

series e:htkc-b6ea d:2006-01-01T00:00:00.000Z t:category=Female t:grade=4 t:district=1 m:level_4_1=21 m:level_3_4_2=55.5 m:mean_scale_score=657 m:level_2_2=33.4 m:level_4_2=5.5 m:level_2_1=127 m:level_1_2=11.1 m:level_1_1=42 m:number_tested=380 m:level_3_2=50 m:level_3_4_1=211 m:level_3_1=190
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

entity e:htkc-b6ea l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/htkc-b6ea

property e:htkc-b6ea t:meta.view v:id=htkc-b6ea v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - District - by Gender" v:attribution="Department of Education (DOE)"

property e:htkc-b6ea t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:htkc-b6ea t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======== | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 1        | 3     | 2006 | Female   | 432           | 667              | 38        | 8.8       | 103       | 23.8      | 272       | 63.0      | 19        | 4.4       | 291         | 67.4        | 
| 1        | 3     | 2006 | Male     | 375           | 658              | 50        | 13.3      | 112       | 29.9      | 190       | 50.7      | 23        | 6.1       | 213         | 56.8        | 
| 1        | 4     | 2006 | Female   | 380           | 657              | 42        | 11.1      | 127       | 33.4      | 190       | 50.0      | 21        | 5.5       | 211         | 55.5        | 
| 1        | 4     | 2006 | Male     | 436           | 651              | 60        | 13.8      | 145       | 33.3      | 213       | 48.9      | 18        | 4.1       | 231         | 53.0        | 
| 1        | 5     | 2006 | Female   | 357           | 650              | 31        | 8.7       | 141       | 39.5      | 164       | 45.9      | 21        | 5.9       | 185         | 51.8        | 
| 1        | 5     | 2006 | Male     | 393           | 653              | 36        | 9.2       | 145       | 36.9      | 178       | 45.3      | 34        | 8.7       | 212         | 53.9        | 
| 1        | 6     | 2006 | Female   | 429           | 654              | 30        | 7.0       | 169       | 39.4      | 180       | 42.0      | 50        | 11.7      | 230         | 53.6        | 
| 1        | 6     | 2006 | Male     | 426           | 651              | 28        | 6.6       | 177       | 41.5      | 183       | 43.0      | 38        | 8.9       | 221         | 51.9        | 
| 1        | 7     | 2006 | Female   | 440           | 648              | 40        | 9.1       | 197       | 44.8      | 164       | 37.3      | 39        | 8.9       | 203         | 46.1        | 
| 1        | 7     | 2006 | Male     | 478           | 644              | 44        | 9.2       | 228       | 47.7      | 177       | 37.0      | 29        | 6.1       | 206         | 43.1        | 
```