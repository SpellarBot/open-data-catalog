# NYS Math Test Results By Grade 2006-2011 - Boro - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-all-students-fe1ad) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a2nf-cvfm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a2nf-cvfm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a2nf-cvfm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a2nf-cvfm |
| Name | NYS Math Test Results By Grade 2006-2011 - Boro - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:11:19Z |
| Publication Date | 2011-10-11T17:05:53Z |

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
series e:a2nf-cvfm d:2006-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=2508 m:level_3_4_2=67.7 m:mean_scale_score=663 m:level_2_2=19.8 m:level_4_2=15.3 m:level_2_1=3257 m:level_1_2=12.5 m:level_1_1=2062 m:number_tested=16445 m:level_3_2=52.4 m:level_3_4_1=11126 m:level_3_1=8618

series e:a2nf-cvfm d:2007-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=3308 m:level_3_4_2=76 m:mean_scale_score=674 m:level_2_2=16.3 m:level_4_2=20.4 m:level_2_1=2640 m:level_1_2=7.7 m:level_1_1=1245 m:number_tested=16189 m:level_3_2=55.6 m:level_3_4_1=12304 m:level_3_1=8996

series e:a2nf-cvfm d:2008-01-01T00:00:00.000Z t:category="All Students" t:grade=3 t:borough=BRONX m:level_4_1=2458 m:level_3_4_2=82.5 m:mean_scale_score=677 m:level_2_2=13.2 m:level_4_2=15.7 m:level_2_1=2061 m:level_1_2=4.3 m:level_1_1=670 m:number_tested=15636 m:level_3_2=66.8 m:level_3_4_1=12905 m:level_3_1=10447
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

entity e:a2nf-cvfm l:"NYS Math Test Results By Grade 2006-2011 - Boro - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/a2nf-cvfm

property e:a2nf-cvfm t:meta.view v:id=a2nf-cvfm v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - All Students" v:attribution="Department of Education (DOE)"

property e:a2nf-cvfm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a2nf-cvfm t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category     | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ============ | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | All Students | 16445         | 663              | 2062      | 12.5      | 3257      | 19.8      | 8618      | 52.4      | 2508      | 15.3      | 11126       | 67.7        | 
| BRONX   | 3     | 2007 | All Students | 16189         | 674              | 1245      | 7.7       | 2640      | 16.3      | 8996      | 55.6      | 3308      | 20.4      | 12304       | 76.0        | 
| BRONX   | 3     | 2008 | All Students | 15636         | 677              | 670       | 4.3       | 2061      | 13.2      | 10447     | 66.8      | 2458      | 15.7      | 12905       | 82.5        | 
| BRONX   | 3     | 2009 | All Students | 15809         | 681              | 258       | 1.6       | 1566      | 9.9       | 11295     | 71.4      | 2690      | 17.0      | 13985       | 88.5        | 
| BRONX   | 3     | 2010 | All Students | 15866         | 683              | 2638      | 16.6      | 6337      | 39.9      | 4629      | 29.2      | 2262      | 14.3      | 6891        | 43.4        | 
| BRONX   | 3     | 2011 | All Students | 15820         | 679              | 2566      | 16.2      | 6628      | 41.9      | 5753      | 36.4      | 873       | 5.5       | 6626        | 41.9        | 
| BRONX   | 4     | 2006 | All Students | 15798         | 658              | 2212      | 14.0      | 3925      | 24.8      | 7702      | 48.8      | 1959      | 12.4      | 9661        | 61.2        | 
| BRONX   | 4     | 2007 | All Students | 16066         | 662              | 1906      | 11.9      | 3775      | 23.5      | 8202      | 51.1      | 2183      | 13.6      | 10385       | 64.6        | 
| BRONX   | 4     | 2008 | All Students | 15745         | 668              | 1404      | 8.9       | 2943      | 18.7      | 9010      | 57.2      | 2388      | 15.2      | 11398       | 72.4        | 
| BRONX   | 4     | 2009 | All Students | 15531         | 678              | 1031      | 6.6       | 2188      | 14.1      | 8631      | 55.6      | 3681      | 23.7      | 12312       | 79.3        | 
```