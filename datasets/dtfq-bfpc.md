# NYS Math Test Results By Grade 2006-2011 - Boro - By Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-by-gender-f1c13) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dtfq-bfpc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dtfq-bfpc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dtfq-bfpc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dtfq-bfpc |
| Name | NYS Math Test Results By Grade 2006-2011 - Boro - By Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:24:31Z |
| Publication Date | 2011-10-11T17:11:19Z |

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
series e:dtfq-bfpc d:2006-01-01T00:00:00.000Z t:category=Female t:grade=3 t:borough=BRONX m:level_4_1=1206 m:level_3_4_2=68.1 m:mean_scale_score=664 m:level_2_2=20.5 m:level_4_2=15.1 m:level_2_1=1635 m:level_1_2=11.4 m:level_1_1=911 m:number_tested=7984 m:level_3_2=53 m:level_3_4_1=5438 m:level_3_1=4232

series e:dtfq-bfpc d:2006-01-01T00:00:00.000Z t:category=Male t:grade=3 t:borough=BRONX m:level_4_1=1302 m:level_3_4_2=67.2 m:mean_scale_score=663 m:level_2_2=19.2 m:level_4_2=15.4 m:level_2_1=1622 m:level_1_2=13.6 m:level_1_1=1151 m:number_tested=8461 m:level_3_2=51.8 m:level_3_4_1=5688 m:level_3_1=4386

series e:dtfq-bfpc d:2007-01-01T00:00:00.000Z t:category=Female t:grade=3 t:borough=BRONX m:level_4_1=1613 m:level_3_4_2=77.2 m:mean_scale_score=675 m:level_2_2=16.6 m:level_4_2=20.7 m:level_2_1=1296 m:level_1_2=6.2 m:level_1_1=484 m:number_tested=7803 m:level_3_2=56.5 m:level_3_4_1=6023 m:level_3_1=4410
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

entity e:dtfq-bfpc l:"NYS Math Test Results By Grade 2006-2011 - Boro - By Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/dtfq-bfpc

property e:dtfq-bfpc t:meta.view v:id=dtfq-bfpc v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - By Gender" v:attribution="Department of Education (DOE)"

property e:dtfq-bfpc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dtfq-bfpc t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | Female   | 7984          | 664              | 911       | 11.4      | 1635      | 20.5      | 4232      | 53.0      | 1206      | 15.1      | 5438        | 68.1        | 
| BRONX   | 3     | 2006 | Male     | 8461          | 663              | 1151      | 13.6      | 1622      | 19.2      | 4386      | 51.8      | 1302      | 15.4      | 5688        | 67.2        | 
| BRONX   | 3     | 2007 | Female   | 7803          | 675              | 484       | 6.2       | 1296      | 16.6      | 4410      | 56.5      | 1613      | 20.7      | 6023        | 77.2        | 
| BRONX   | 3     | 2007 | Male     | 8386          | 673              | 761       | 9.1       | 1344      | 16.0      | 4586      | 54.7      | 1695      | 20.2      | 6281        | 74.9        | 
| BRONX   | 3     | 2008 | Female   | 7556          | 678              | 249       | 3.3       | 958       | 12.7      | 5123      | 67.8      | 1226      | 16.2      | 6349        | 84.0        | 
| BRONX   | 3     | 2008 | Male     | 8080          | 676              | 421       | 5.2       | 1103      | 13.7      | 5324      | 65.9      | 1232      | 15.2      | 6556        | 81.1        | 
| BRONX   | 3     | 2009 | Female   | 7659          | 683              | 84        | 1.1       | 683       | 8.9       | 5519      | 72.1      | 1373      | 17.9      | 6892        | 90.0        | 
| BRONX   | 3     | 2009 | Male     | 8150          | 680              | 174       | 2.1       | 883       | 10.8      | 5776      | 70.9      | 1317      | 16.2      | 7093        | 87.0        | 
| BRONX   | 3     | 2010 | Female   | 7653          | 683              | 1200      | 15.7      | 3109      | 40.6      | 2274      | 29.7      | 1070      | 14.0      | 3344        | 43.7        | 
| BRONX   | 3     | 2010 | Male     | 8213          | 683              | 1438      | 17.5      | 3228      | 39.3      | 2355      | 28.7      | 1192      | 14.5      | 3547        | 43.2        | 
```