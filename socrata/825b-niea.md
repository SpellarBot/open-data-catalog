# NYS Math Test Results by Grade 2006-2011 - Citywide - by Race-Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-math-test-results-by-grade-2006-2011-citywide-by-race-ethnicity-d52ff) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/825b-niea) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/825b-niea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/825b-niea/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 825b-niea |
| Name | NYS Math Test Results by Grade 2006-2011 - Citywide - by Race-Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T21:53:38Z |
| Publication Date | 2011-10-11T17:06:33Z |

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
series e:825b-niea d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=3 m:level_4_1=4854 m:level_3_4_2=92 m:mean_scale_score=700 m:level_2_2=5.6 m:level_4_2=49.7 m:level_2_1=543 m:level_1_2=2.5 m:level_1_1=243 m:number_tested=9768 m:level_3_2=42.3 m:level_3_4_1=8982 m:level_3_1=4128

series e:825b-niea d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=4 m:level_4_1=4834 m:level_3_4_2=91 m:mean_scale_score=699 m:level_2_2=6 m:level_4_2=48.5 m:level_2_1=600 m:level_1_2=2.9 m:level_1_1=294 m:number_tested=9973 m:level_3_2=42.6 m:level_3_4_1=9079 m:level_3_1=4245

series e:825b-niea d:2006-01-01T00:00:00.000Z t:category=Asian t:grade=5 m:level_4_1=4197 m:level_3_4_2=87 m:mean_scale_score=691 m:level_2_2=9.2 m:level_4_2=42.6 m:level_2_1=907 m:level_1_2=3.7 m:level_1_1=369 m:number_tested=9852 m:level_3_2=44.4 m:level_3_4_1=8576 m:level_3_1=4379
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

entity e:825b-niea l:"NYS Math Test Results by Grade 2006-2011 - Citywide - by Race-Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/825b-niea

property e:825b-niea t:meta.view v:id=825b-niea v:category=Education v:averageRating=0 v:name="NYS Math Test Results by Grade 2006-2011 - Citywide - by Race-Ethnicity" v:attribution="Department of Education (DOE)"

property e:825b-niea t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:825b-niea t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade      | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ========== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3          | 2006 | Asian    | 9768          | 700              | 243       | 2.5       | 543       | 5.6       | 4128      | 42.3      | 4854      | 49.7      | 8982        | 92.0        | 
| 4          | 2006 | Asian    | 9973          | 699              | 294       | 2.9       | 600       | 6.0       | 4245      | 42.6      | 4834      | 48.5      | 9079        | 91.0        | 
| 5          | 2006 | Asian    | 9852          | 691              | 369       | 3.7       | 907       | 9.2       | 4379      | 44.4      | 4197      | 42.6      | 8576        | 87.0        | 
| 6          | 2006 | Asian    | 9606          | 682              | 452       | 4.7       | 1176      | 12.2      | 4646      | 48.4      | 3332      | 34.7      | 7978        | 83.1        | 
| 7          | 2006 | Asian    | 9433          | 671              | 521       | 5.5       | 1698      | 18.0      | 4690      | 49.7      | 2524      | 26.8      | 7214        | 76.5        | 
| 8          | 2006 | Asian    | 9593          | 675              | 671       | 7.0       | 1847      | 19.3      | 4403      | 45.9      | 2672      | 27.9      | 7075        | 73.8        | 
| All Grades | 2006 | Asian    | 58225         | 687              | 2550      | 4.4       | 6771      | 11.6      | 26491     | 45.5      | 22413     | 38.5      | 48904       | 84.0        | 
| 3          | 2007 | Asian    | 9750          | 706              | 156       | 1.6       | 402       | 4.1       | 3886      | 39.9      | 5306      | 54.4      | 9192        | 94.3        | 
| 4          | 2007 | Asian    | 9881          | 704              | 209       | 2.1       | 564       | 5.7       | 3968      | 40.2      | 5140      | 52.0      | 9108        | 92.2        | 
| 5          | 2007 | Asian    | 10111         | 700              | 211       | 2.1       | 626       | 6.2       | 4257      | 42.1      | 5017      | 49.6      | 9274        | 91.7        | 
```