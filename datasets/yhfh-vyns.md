# English Language Arts (ELA) Test Results 2006-2012 - District - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-district-all-students-05f54) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yhfh-vyns) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yhfh-vyns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yhfh-vyns/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yhfh-vyns |
| Name | English Language Arts (ELA) Test Results 2006-2012 - District - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, district, lifelong learning |
| Created | 2013-02-20T22:03:55Z |
| Publication Date | 2013-02-20T22:04:16Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by district.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | district          | District          | text      | text        |
| Yes      | series tag     | grade             | Grade             | text      | text        |
| Yes      | time           | year              | Year              | number    | text        |
| Yes      | series tag     | demographic       | Demographic       | text      | text        |
| Yes      | numeric metric | number_tested     | Number Tested     | number    | text        |
| Yes      | numeric metric | mean_scale_score  | Mean Scale Score  | number    | text        |
| Yes      | numeric metric | num_level_1       | Num Level 1       | number    | text        |
| Yes      | numeric metric | pct_level_1       | Pct Level 1       | number    | text        |
| Yes      | numeric metric | num_level_2       | Num Level 2       | number    | text        |
| Yes      | numeric metric | pct_level_2       | Pct Level 2       | number    | text        |
| Yes      | numeric metric | num_level_3       | Num Level 3       | number    | text        |
| Yes      | numeric metric | pct_level_3       | Pct Level 3       | number    | text        |
| Yes      | numeric metric | num_level_4       | Num Level 4       | number    | text        |
| Yes      | numeric metric | pct_level_4       | Pct Level 4       | number    | text        |
| Yes      | numeric metric | num_level_3_and_4 | Num Level 3 and 4 | number    | text        |
| Yes      | numeric metric | pct_level_3_and_4 | Pct Level 3 and 4 | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yhfh-vyns d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=663 m:pct_level_1=11 m:pct_level_2=26.6 m:pct_level_3=57.2 m:num_level_3_and_4=504 m:pct_level_4=5.2 m:num_level_1=89 m:number_tested=808 m:num_level_2=215 m:pct_level_3_and_4=62.4 m:num_level_4=42 m:num_level_3=462

series e:yhfh-vyns d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=659 m:pct_level_1=11.4 m:pct_level_2=29.3 m:pct_level_3=51.7 m:num_level_3_and_4=490 m:pct_level_4=7.6 m:num_level_1=94 m:number_tested=826 m:num_level_2=242 m:pct_level_3_and_4=59.3 m:num_level_4=63 m:num_level_3=427

series e:yhfh-vyns d:2008-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=662 m:pct_level_1=7 m:pct_level_2=31.7 m:pct_level_3=52.7 m:num_level_3_and_4=522 m:pct_level_4=8.6 m:num_level_1=60 m:number_tested=852 m:num_level_2=270 m:pct_level_3_and_4=61.3 m:num_level_4=73 m:num_level_3=449
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:num_level_1 p:integer l:"Num Level 1" t:dataTypeName=number

metric m:pct_level_1 p:float l:"Pct Level 1" t:dataTypeName=number

metric m:num_level_2 p:integer l:"Num Level 2" t:dataTypeName=number

metric m:pct_level_2 p:float l:"Pct Level 2" t:dataTypeName=number

metric m:num_level_3 p:integer l:"Num Level 3" t:dataTypeName=number

metric m:pct_level_3 p:float l:"Pct Level 3" t:dataTypeName=number

metric m:num_level_4 p:integer l:"Num Level 4" t:dataTypeName=number

metric m:pct_level_4 p:float l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:yhfh-vyns l:"English Language Arts (ELA) Test Results 2006-2012 - District - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yhfh-vyns

property e:yhfh-vyns t:meta.view v:id=yhfh-vyns v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/D8B559C6-A588-44B6-AECE-1108BE52BE9F/0/DistrictELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - District - All Students" v:attribution="Department of Education (DOE)"

property e:yhfh-vyns t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yhfh-vyns t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | All Students | 808           | 663              | 89          | 11          | 215         | 26.6        | 462         | 57.2        | 42          | 5.2         | 504               | 62.4              | 
| 1        | 3     | 2007 | All Students | 826           | 659              | 94          | 11.4        | 242         | 29.3        | 427         | 51.7        | 63          | 7.6         | 490               | 59.3              | 
| 1        | 3     | 2008 | All Students | 852           | 662              | 60          | 7           | 270         | 31.7        | 449         | 52.7        | 73          | 8.6         | 522               | 61.3              | 
| 1        | 3     | 2009 | All Students | 901           | 667              | 45          | 5           | 221         | 24.5        | 553         | 61.4        | 82          | 9.1         | 635               | 70.5              | 
| 1        | 3     | 2010 | All Students | 848           | 669              | 137         | 16.2        | 276         | 32.5        | 272         | 32.1        | 163         | 19.2        | 435               | 51.3              | 
| 1        | 3     | 2011 | All Students | 813           | 665              | 103         | 12.7        | 265         | 32.6        | 371         | 45.6        | 74          | 9.1         | 445               | 54.7              | 
| 1        | 3     | 2012 | All Students | 856           | 663              | 123         | 14.4        | 294         | 34.3        | 379         | 44.3        | 60          | 7           | 439               | 51.3              | 
| 1        | 4     | 2006 | All Students | 819           | 654              | 103         | 12.6        | 272         | 33.2        | 405         | 49.5        | 39          | 4.8         | 444               | 54.2              | 
| 1        | 4     | 2007 | All Students | 860           | 655              | 70          | 8.1         | 286         | 33.3        | 469         | 54.5        | 35          | 4.1         | 504               | 58.6              | 
| 1        | 4     | 2008 | All Students | 843           | 657              | 74          | 8.8         | 251         | 29.8        | 480         | 56.9        | 38          | 4.5         | 518               | 61.4              | 
```