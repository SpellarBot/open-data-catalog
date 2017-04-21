# English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-citywide-by-disability-status-81683) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pcgw-s47c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pcgw-s47c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pcgw-s47c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pcgw-s47c |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T18:56:06Z |
| Publication Date | 2011-10-11T17:14:53Z |

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
series e:pcgw-s47c d:2006-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 m:level_4_1=3107 m:level_3_4_2=68.1 m:mean_scale_score=668 m:level_2_2=25.4 m:level_4_2=5.9 m:level_2_1=13291 m:level_1_2=6.4 m:level_1_1=3355 m:number_tested=52245 m:level_3_2=62.2 m:level_3_4_1=35599 m:level_3_1=32492

series e:pcgw-s47c d:2007-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 m:level_4_1=4248 m:level_3_4_2=62.9 m:mean_scale_score=663 m:level_2_2=29.4 m:level_4_2=7.1 m:level_2_1=17488 m:level_1_2=7.7 m:level_1_1=4573 m:number_tested=59452 m:level_3_2=55.7 m:level_3_4_1=37391 m:level_3_1=33143

series e:pcgw-s47c d:2008-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 m:level_4_1=5304 m:level_3_4_2=66.4 m:mean_scale_score=665 m:level_2_2=29 m:level_4_2=9.2 m:level_2_1=16695 m:level_1_2=4.6 m:level_1_1=2665 m:number_tested=57545 m:level_3_2=57.1 m:level_3_4_1=38185 m:level_3_1=32881
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

entity e:pcgw-s47c l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pcgw-s47c

property e:pcgw-s47c t:meta.view v:id=pcgw-s47c v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Disability Status" v:attribution="Department of Education (DOE)"

property e:pcgw-s47c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pcgw-s47c t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ===== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3     | 2006 | General Ed | 52245         | 668              | 3355      | 6.4       | 13291     | 25.4      | 32492     | 62.2      | 3107      | 5.9       | 35599       | 68.1        | 
| 3     | 2007 | General Ed | 59452         | 663              | 4573      | 7.7       | 17488     | 29.4      | 33143     | 55.7      | 4248      | 7.1       | 37391       | 62.9        | 
| 3     | 2008 | General Ed | 57545         | 665              | 2665      | 4.6       | 16695     | 29.0      | 32881     | 57.1      | 5304      | 9.2       | 38185       | 66.4        | 
| 3     | 2009 | General Ed | 58009         | 670              | 1597      | 2.8       | 12088     | 20.8      | 38974     | 67.2      | 5350      | 9.2       | 44324       | 76.4        | 
| 3     | 2010 | General Ed | 56986         | 668              | 6548      | 11.5      | 20363     | 35.7      | 21484     | 37.7      | 8591      | 15.1      | 30075       | 52.8        | 
| 3     | 2011 | General Ed | 58084         | 664              | 5725      | 9.9       | 20692     | 35.6      | 29357     | 50.5      | 2310      | 4.0       | 31667       | 54.5        | 
| 4     | 2006 | General Ed | 54339         | 665              | 3168      | 5.8       | 15266     | 28.1      | 32152     | 59.2      | 3753      | 6.9       | 35905       | 66.1        | 
| 4     | 2007 | General Ed | 57674         | 661              | 3335      | 5.8       | 17874     | 31.0      | 33089     | 57.4      | 3376      | 5.9       | 36465       | 63.2        | 
| 4     | 2008 | General Ed | 57053         | 664              | 2989      | 5.2       | 14737     | 25.8      | 35386     | 62.0      | 3941      | 6.9       | 39327       | 68.9        | 
| 4     | 2009 | General Ed | 55657         | 670              | 1129      | 2.0       | 11774     | 21.2      | 39230     | 70.5      | 3524      | 6.3       | 42754       | 76.8        | 
```