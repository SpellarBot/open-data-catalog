# English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Disability Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-by-grade-2006-2011-boro-by-disability-status-9938b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hcf7-jp2y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hcf7-jp2y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hcf7-jp2y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hcf7-jp2y |
| Name | English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Disability Status |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-05T20:08:33Z |
| Publication Date | 2011-10-11T17:13:45Z |

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
series e:hcf7-jp2y d:2006-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:borough=BRONX m:level_4_1=329 m:level_3_4_2=56.9 m:mean_scale_score=657 m:level_2_2=33.7 m:level_4_2=3 m:level_2_1=3724 m:level_1_2=9.4 m:level_1_1=1040 m:number_tested=11064 m:level_3_2=54 m:level_3_4_1=6300 m:level_3_1=5971

series e:hcf7-jp2y d:2006-01-01T00:00:00.000Z t:category="Special Ed" t:grade=3 t:borough=BRONX m:level_4_1=9 m:level_3_4_2=17.2 m:mean_scale_score=616 m:level_2_2=32.8 m:level_4_2=0.4 m:level_2_1=733 m:level_1_2=49.9 m:level_1_1=1114 m:number_tested=2232 m:level_3_2=16.8 m:level_3_4_1=385 m:level_3_1=376

series e:hcf7-jp2y d:2007-01-01T00:00:00.000Z t:category="General Ed" t:grade=3 t:borough=BRONX m:level_4_1=422 m:level_3_4_2=50.5 m:mean_scale_score=651 m:level_2_2=37.5 m:level_4_2=3.2 m:level_2_1=4872 m:level_1_2=12 m:level_1_1=1561 m:number_tested=13001 m:level_3_2=47.3 m:level_3_4_1=6568 m:level_3_1=6146
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

entity e:hcf7-jp2y l:"English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Disability Status" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/hcf7-jp2y

property e:hcf7-jp2y t:meta.view v:id=hcf7-jp2y v:category=Education v:averageRating=0 v:name="English Language Arts (ELA) Test Results by Grade 2006-2011 - Boro - by Disability Status" v:attribution="Department of Education (DOE)"

property e:hcf7-jp2y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hcf7-jp2y t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| borough | grade | year | category   | number_tested | mean_scale_score | level_1_1 | level_1_2 | level_2_1 | level_2_2 | level_3_1 | level_3_2 | level_4_1 | level_4_2 | level_3_4_1 | level_3_4_2 | 
| ======= | ===== | ==== | ========== | ============= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =========== | =========== | 
| BRONX   | 3     | 2006 | General Ed | 11064         | 657              | 1040      | 9.4       | 3724      | 33.7      | 5971      | 54.0      | 329       | 3.0       | 6300        | 56.9        | 
| BRONX   | 3     | 2006 | Special Ed | 2232          | 616              | 1114      | 49.9      | 733       | 32.8      | 376       | 16.8      | 9         | 0.4       | 385         | 17.2        | 
| BRONX   | 3     | 2007 | General Ed | 13001         | 651              | 1561      | 12.0      | 4872      | 37.5      | 6146      | 47.3      | 422       | 3.2       | 6568        | 50.5        | 
| BRONX   | 3     | 2007 | Special Ed | 2870          | 614              | 1373      | 47.8      | 992       | 34.6      | 495       | 17.2      | 10        | 0.3       | 505         | 17.6        | 
| BRONX   | 3     | 2008 | General Ed | 12432         | 656              | 870       | 7.0       | 4623      | 37.2      | 6343      | 51.0      | 596       | 4.8       | 6939        | 55.8        | 
| BRONX   | 3     | 2008 | Special Ed | 2948          | 622              | 1152      | 39.1      | 1239      | 42.0      | 532       | 18.0      | 25        | 0.8       | 557         | 18.9        | 
| BRONX   | 3     | 2009 | General Ed | 12433         | 661              | 515       | 4.1       | 3515      | 28.3      | 7840      | 63.1      | 563       | 4.5       | 8403        | 67.6        | 
| BRONX   | 3     | 2009 | Special Ed | 3098          | 629              | 935       | 30.2      | 1322      | 42.7      | 818       | 26.4      | 23        | 0.7       | 841         | 27.1        | 
| BRONX   | 3     | 2010 | General Ed | 12092         | 661              | 1984      | 16.4      | 5045      | 41.7      | 3931      | 32.5      | 1132      | 9.4       | 5063        | 41.9        | 
| BRONX   | 3     | 2010 | Special Ed | 3362          | 640              | 1861      | 55.4      | 1035      | 30.8      | 400       | 11.9      | 66        | 2.0       | 466         | 13.9        | 
```