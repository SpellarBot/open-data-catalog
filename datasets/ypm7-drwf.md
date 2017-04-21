# NYS Math Test Results By Grade 2006-2011 - Boro - By Race- Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-boro-by-race-ethnicity-7b037) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ypm7-drwf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ypm7-drwf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ypm7-drwf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ypm7-drwf |
| Name | NYS Math Test Results By Grade 2006-2011 - Boro - By Race- Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T22:26:39Z |
| Publication Date | 2011-10-11T17:11:58Z |

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
series e:ypm7-drwf d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 t:borough=BRONX m:level_4_1=227 m:level_3_4_2=82.9 m:mean_scale_score=689 m:level_2_2=11 m:level_4_2=39.7 m:level_2_1=63 m:level_1_2=6.1 m:level_1_1=35 m:number_tested=572 m:level_3_2=43.2 m:level_3_4_1=474 m:level_3_1=247

series e:ypm7-drwf d:2006-01-01T00:00:00.000Z t:category=Black t:grade=3 t:borough=BRONX m:level_4_1=737 m:level_3_4_2=67.3 m:mean_scale_score=662 m:level_2_2=20.5 m:level_4_2=13.9 m:level_2_1=1088 m:level_1_2=12.2 m:level_1_1=645 m:number_tested=5296 m:level_3_2=53.4 m:level_3_4_1=3563 m:level_3_1=2826

series e:ypm7-drwf d:2006-01-01T00:00:00.000Z t:category=Hispanic t:grade=3 t:borough=BRONX m:level_4_1=1307 m:level_3_4_2=65.8 m:mean_scale_score=661 m:level_2_2=20.7 m:level_4_2=13.2 m:level_2_1=2044 m:level_1_2=13.5 m:level_1_1=1336 m:number_tested=9875 m:level_3_2=52.5 m:level_3_4_1=6495 m:level_3_1=5188
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

entity e:ypm7-drwf l:"NYS Math Test Results By Grade 2006-2011 - Boro - By Race- Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ypm7-drwf

property e:ypm7-drwf t:meta.view v:id=ypm7-drwf v:category=Education v:averageRating=0 v:name="NYS Math Test Results By Grade 2006-2011 - Boro - By Race- Ethnicity" v:attribution="Department of Education (DOE)"

property e:ypm7-drwf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ypm7-drwf t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | Asian    | 572           | 689              | 35        | 6.1       | 63        | 11.0      | 247       | 43.2      | 227       | 39.7      | 474         | 82.9        | 
| BRONX   | 3     | 2006 | Black    | 5296          | 662              | 645       | 12.2      | 1088      | 20.5      | 2826      | 53.4      | 737       | 13.9      | 3563        | 67.3        | 
| BRONX   | 3     | 2006 | Hispanic | 9875          | 661              | 1336      | 13.5      | 2044      | 20.7      | 5188      | 52.5      | 1307      | 13.2      | 6495        | 65.8        | 
| BRONX   | 3     | 2006 | White    | 636           | 686              | 37        | 5.8       | 43        | 6.8       | 333       | 52.4      | 223       | 35.1      | 556         | 87.4        | 
| BRONX   | 3     | 2007 | Asian    | 555           | 697              | 14        | 2.5       | 41        | 7.4       | 253       | 45.6      | 247       | 44.5      | 500         | 90.1        | 
| BRONX   | 3     | 2007 | Black    | 5066          | 671              | 450       | 8.9       | 843       | 16.6      | 2844      | 56.1      | 929       | 18.3      | 3773        | 74.5        | 
| BRONX   | 3     | 2007 | Hispanic | 9817          | 672              | 756       | 7.7       | 1708      | 17.4      | 5495      | 56.0      | 1858      | 18.9      | 7353        | 74.9        | 
| BRONX   | 3     | 2007 | White    | 630           | 695              | 16        | 2.5       | 36        | 5.7       | 330       | 52.4      | 248       | 39.4      | 578         | 91.7        | 
| BRONX   | 3     | 2008 | Asian    | 523           | 704              | 7         | 1.3       | 14        | 2.7       | 268       | 51.2      | 234       | 44.7      | 502         | 96.0        | 
| BRONX   | 3     | 2008 | Black    | 4804          | 674              | 231       | 4.8       | 701       | 14.6      | 3223      | 67.1      | 649       | 13.5      | 3872        | 80.6        | 
```