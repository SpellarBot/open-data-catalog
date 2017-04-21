# NYS Math Test Results By Grade 2006-2011 - Boro - By Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-by-disability-status-79e22) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rhtj-vttz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rhtj-vttz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rhtj-vttz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rhtj-vttz |
| Name | NYS Math Test Results By Grade 2006-2011 - Boro - By Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:16:47Z |
| Publication Date | 2011-10-11T16:54:15Z |

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
series e:rhtj-vttz d:2006-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:borough=BRONX m:level_4_1=2374 m:level_3_4_2=73.3 m:mean_scale_score=669 m:level_2_2=18.3 m:level_4_2=17.4 m:level_2_1=2498 m:level_1_2=8.4 m:level_1_1=1143 m:number_tested=13647 m:level_3_2=55.9 m:level_3_4_1=10006 m:level_3_1=7632

series e:rhtj-vttz d:2006-01-01T00:00:00.000Z t:category="Special Ed" t:grade=3 t:borough=BRONX m:level_4_1=134 m:level_3_4_2=40 m:mean_scale_score=638 m:level_2_2=27.1 m:level_4_2=4.8 m:level_2_1=759 m:level_1_2=32.8 m:level_1_1=919 m:number_tested=2798 m:level_3_2=35.2 m:level_3_4_1=1120 m:level_3_1=986

series e:rhtj-vttz d:2007-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:borough=BRONX m:level_4_1=3084 m:level_3_4_2=82.4 m:mean_scale_score=680 m:level_2_2=13.8 m:level_4_2=23.4 m:level_2_1=1815 m:level_1_2=3.9 m:level_1_1=512 m:number_tested=13194 m:level_3_2=59 m:level_3_4_1=10867 m:level_3_1=7783
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

entity e:rhtj-vttz l:"NYS Math Test Results By Grade 2006-2011 - Boro - By Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rhtj-vttz

property e:rhtj-vttz t:meta.view v:id=rhtj-vttz v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - By Disability Status" v:attribution="Department of Education (DOE)"

property e:rhtj-vttz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rhtj-vttz t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | General Ed | 13647         | 669              | 1143      | 8.4       | 2498      | 18.3      | 7632      | 55.9      | 2374      | 17.4      | 10006       | 73.3        | 
| BRONX   | 3     | 2006 | Special Ed | 2798          | 638              | 919       | 32.8      | 759       | 27.1      | 986       | 35.2      | 134       | 4.8       | 1120        | 40.0        | 
| BRONX   | 3     | 2007 | General Ed | 13194         | 680              | 512       | 3.9       | 1815      | 13.8      | 7783      | 59.0      | 3084      | 23.4      | 10867       | 82.4        | 
| BRONX   | 3     | 2007 | Special Ed | 2995          | 647              | 733       | 24.5      | 825       | 27.5      | 1213      | 40.5      | 224       | 7.5       | 1437        | 48.0        | 
| BRONX   | 3     | 2008 | General Ed | 12603         | 682              | 223       | 1.8       | 1219      | 9.7       | 8837      | 70.1      | 2324      | 18.4      | 11161       | 88.6        | 
| BRONX   | 3     | 2008 | Special Ed | 3033          | 654              | 447       | 14.7      | 842       | 27.8      | 1610      | 53.1      | 134       | 4.4       | 1744        | 57.5        | 
| BRONX   | 3     | 2009 | General Ed | 12665         | 686              | 73        | 0.6       | 814       | 6.4       | 9286      | 73.3      | 2492      | 19.7      | 11778       | 93.0        | 
| BRONX   | 3     | 2009 | Special Ed | 3144          | 663              | 185       | 5.9       | 752       | 23.9      | 2009      | 63.9      | 198       | 6.3       | 2207        | 70.2        | 
| BRONX   | 3     | 2010 | General Ed | 12458         | 687              | 1400      | 11.2      | 4953      | 39.8      | 4013      | 32.2      | 2092      | 16.8      | 6105        | 49.0        | 
| BRONX   | 3     | 2010 | Special Ed | 3408          | 669              | 1238      | 36.3      | 1384      | 40.6      | 616       | 18.1      | 170       | 5.0       | 786         | 23.1        | 
```