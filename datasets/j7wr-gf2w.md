# English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-citywide-by-gender-a554d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j7wr-gf2w) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j7wr-gf2w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j7wr-gf2w/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j7wr-gf2w |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T18:58:54Z |
| Publication Date | 2011-10-11T17:15:34Z |

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
series e:j7wr-gf2w d:2006-01-01T00:00:00.000Z t:category=Female t:grade=3 m:level_4_1=1882 m:level_3_4_2=66.7 m:mean_scale_score=667 m:level_2_2=24.6 m:level_4_2=6.3 m:level_2_1=7400 m:level_1_2=8.7 m:level_1_1=2616 m:number_tested=30109 m:level_3_2=60.5 m:level_3_4_1=20093 m:level_3_1=18211

series e:j7wr-gf2w d:2007-01-01T00:00:00.000Z t:category=Female t:grade=3 m:level_4_1=2452 m:level_3_4_2=60.8 m:mean_scale_score=661 m:level_2_2=29.2 m:level_4_2=7.1 m:level_2_1=10142 m:level_1_2=10 m:level_1_1=3460 m:number_tested=34691 m:level_3_2=53.7 m:level_3_4_1=21089 m:level_3_1=18637

series e:j7wr-gf2w d:2008-01-01T00:00:00.000Z t:category=Female t:grade=3 m:level_4_1=2970 m:level_3_4_2=63.7 m:mean_scale_score=663 m:level_2_2=29.8 m:level_4_2=8.9 m:level_2_1=9942 m:level_1_2=6.5 m:level_1_1=2163 m:number_tested=33390 m:level_3_2=54.9 m:level_3_4_1=21285 m:level_3_1=18315
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

entity e:j7wr-gf2w l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/j7wr-gf2w

property e:j7wr-gf2w t:meta.view v:id=j7wr-gf2w v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Citywide - by Gender" v:attribution="Department of Education (DOE)"

property e:j7wr-gf2w t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j7wr-gf2w t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| grade | year | category | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ===== | ==== | ======== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| 3     | 2006 | Female   | 30109         | 667              | 2616      | 8.7       | 7400      | 24.6      | 18211     | 60.5      | 1882      | 6.3       | 20093       | 66.7        | 
| 3     | 2007 | Female   | 34691         | 661              | 3460      | 10.0      | 10142     | 29.2      | 18637     | 53.7      | 2452      | 7.1       | 21089       | 60.8        | 
| 3     | 2008 | Female   | 33390         | 663              | 2163      | 6.5       | 9942      | 29.8      | 18315     | 54.9      | 2970      | 8.9       | 21285       | 63.7        | 
| 3     | 2009 | Female   | 34209         | 668              | 1502      | 4.4       | 7197      | 21.0      | 22245     | 65.0      | 3265      | 9.5       | 25510       | 74.6        | 
| 3     | 2010 | Female   | 33810         | 666              | 5156      | 15.2      | 11845     | 35.0      | 11901     | 35.2      | 4908      | 14.5      | 16809       | 49.7        | 
| 3     | 2011 | Female   | 34725         | 663              | 4305      | 12.4      | 11863     | 34.2      | 17065     | 49.1      | 1492      | 4.3       | 18557       | 53.4        | 
| 4     | 2006 | Female   | 31750         | 661              | 2844      | 9.0       | 9053      | 28.5      | 17632     | 55.5      | 2221      | 7.0       | 19853       | 62.5        | 
| 4     | 2007 | Female   | 33987         | 659              | 2949      | 8.7       | 10530     | 31.0      | 18424     | 54.2      | 2084      | 6.1       | 20508       | 60.3        | 
| 4     | 2008 | Female   | 33970         | 662              | 2585      | 7.6       | 8876      | 26.1      | 20040     | 59.0      | 2469      | 7.3       | 22509       | 66.3        | 
| 4     | 2009 | Female   | 33346         | 667              | 1341      | 4.0       | 7647      | 22.9      | 22156     | 66.4      | 2202      | 6.6       | 24358       | 73.0        | 
```