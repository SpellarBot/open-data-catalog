# English Language Arts (ELA) Test Results 2006-2012 - Borough - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-borough-all-students-ef64b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k5ws-xbkn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k5ws-xbkn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k5ws-xbkn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k5ws-xbkn |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Borough - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, borough, lifelong learning |
| Created | 2013-02-20T22:01:26Z |
| Publication Date | 2013-02-20T22:01:38Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by borough.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | borough           | Borough           | text      | text        |
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
series e:k5ws-xbkn d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=650 m:pct_level_1=16.2 m:pct_level_2=33.5 m:pct_level_3=47.7 m:num_level_3_and_4=6685 m:pct_level_4=2.5 m:num_level_1=2154 m:number_tested=13296 m:num_level_2=4457 m:pct_level_3_and_4=50.3 m:num_level_4=338 m:num_level_3=6347

series e:k5ws-xbkn d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=645 m:pct_level_1=18.5 m:pct_level_2=36.9 m:pct_level_3=41.8 m:num_level_3_and_4=7073 m:pct_level_4=2.7 m:num_level_1=2934 m:number_tested=15871 m:num_level_2=5864 m:pct_level_3_and_4=44.6 m:num_level_4=432 m:num_level_3=6641

series e:k5ws-xbkn d:2008-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=649 m:pct_level_1=13.1 m:pct_level_2=38.1 m:pct_level_3=44.7 m:num_level_3_and_4=7496 m:pct_level_4=4 m:num_level_1=2022 m:number_tested=15380 m:num_level_2=5862 m:pct_level_3_and_4=48.7 m:num_level_4=621 m:num_level_3=6875
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

entity e:k5ws-xbkn l:"English Language Arts (ELA) Test Results 2006-2012 - Borough - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/k5ws-xbkn

property e:k5ws-xbkn t:meta.view v:id=k5ws-xbkn v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/B82F9971-6533-4355-B3F0-19219B74453F/0/BoroughELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Borough - All Students" v:attribution="Department of Education (DOE)"

property e:k5ws-xbkn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k5ws-xbkn t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | All Students | 13296         | 650              | 2154        | 16.2        | 4457        | 33.5        | 6347        | 47.7        | 338         | 2.5         | 6685              | 50.3              | 
| BRONX   | 3     | 2007 | All Students | 15871         | 645              | 2934        | 18.5        | 5864        | 36.9        | 6641        | 41.8        | 432         | 2.7         | 7073              | 44.6              | 
| BRONX   | 3     | 2008 | All Students | 15380         | 649              | 2022        | 13.1        | 5862        | 38.1        | 6875        | 44.7        | 621         | 4           | 7496              | 48.7              | 
| BRONX   | 3     | 2009 | All Students | 15531         | 655              | 1450        | 9.3         | 4837        | 31.1        | 8658        | 55.7        | 586         | 3.8         | 9244              | 59.5              | 
| BRONX   | 3     | 2010 | All Students | 15454         | 657              | 3845        | 24.9        | 6080        | 39.3        | 4331        | 28          | 1198        | 7.8         | 5529              | 35.8              | 
| BRONX   | 3     | 2011 | All Students | 15434         | 654              | 3520        | 22.8        | 6468        | 41.9        | 5242        | 34          | 204         | 1.3         | 5446              | 35.3              | 
| BRONX   | 3     | 2012 | All Students | 15601         | 655              | 3834        | 24.6        | 6315        | 40.5        | 5138        | 32.9        | 314         | 2           | 5452              | 34.9              | 
| BRONX   | 4     | 2006 | All Students | 13655         | 647              | 2182        | 16          | 4854        | 35.5        | 6224        | 45.6        | 395         | 2.9         | 6619              | 48.5              | 
| BRONX   | 4     | 2007 | All Students | 15775         | 644              | 2471        | 15.7        | 6166        | 39.1        | 6770        | 42.9        | 368         | 2.3         | 7138              | 45.2              | 
| BRONX   | 4     | 2008 | All Students | 15434         | 645              | 2372        | 15.4        | 5467        | 35.4        | 7224        | 46.8        | 371         | 2.4         | 7595              | 49.2              | 
```