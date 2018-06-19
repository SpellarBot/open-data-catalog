# English Language Arts (ELA) Test Results 2006-2012 - School - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-school-all-students-b1c55) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wrhz-w8mn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wrhz-w8mn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wrhz-w8mn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wrhz-w8mn |
| Name | English Language Arts (ELA) Test Results 2006-2012 - School - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, school, lifelong learning |
| Created | 2013-02-20T22:06:24Z |
| Publication Date | 2013-02-20T22:09:21Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by school.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | dbn               | DBN               | text      | text        |
| Yes      | series tag     | grade             | Grade             | text      | text        |
| Yes      | time           | year              | Year              | number    | text        |
| Yes      | series tag     | demographic       | Demographic       | text      | text        |
| Yes      | numeric metric | number_tested     | Number Tested     | number    | text        |
| Yes      | series tag     | mean_scale_score  | Mean Scale Score  | text      | text        |
| Yes      | series tag     | num_level_1       | Num Level 1       | text      | text        |
| Yes      | series tag     | pct_level_1       | Pct Level 1       | text      | text        |
| Yes      | series tag     | num_level_2       | Num Level 2       | text      | text        |
| Yes      | series tag     | pct_level_2       | Pct Level 2       | text      | text        |
| Yes      | series tag     | num_level_3       | Num Level 3       | text      | text        |
| Yes      | series tag     | pct_level_3       | Pct Level 3       | text      | text        |
| Yes      | series tag     | num_level_4       | Num Level 4       | text      | text        |
| Yes      | series tag     | pct_level_4       | Pct Level 4       | text      | text        |
| Yes      | series tag     | num_level_3_and_4 | Num Level 3 and 4 | text      | text        |
| Yes      | series tag     | pct_level_3_and_4 | Pct Level 3 and 4 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wrhz-w8mn d:2006-01-01T00:00:00.000Z t:mean_scale_score=651 t:pct_level_1=10.8 t:pct_level_2=37.8 t:pct_level_3=51.4 t:pct_level_4=0 t:demographic="All Students" t:num_level_1=4 t:num_level_2=14 t:pct_level_3_and_4=51.4 t:num_level_3=19 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=19 t:num_level_4=0 m:number_tested=37

series e:wrhz-w8mn d:2007-01-01T00:00:00.000Z t:mean_scale_score=635 t:pct_level_1=18.2 t:pct_level_2=54.5 t:pct_level_3=27.3 t:pct_level_4=0 t:demographic="All Students" t:num_level_1=6 t:num_level_2=18 t:pct_level_3_and_4=27.3 t:num_level_3=9 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=9 t:num_level_4=0 m:number_tested=33

series e:wrhz-w8mn d:2008-01-01T00:00:00.000Z t:mean_scale_score=646 t:pct_level_1=7.7 t:pct_level_2=56.4 t:pct_level_3=35.9 t:pct_level_4=0 t:demographic="All Students" t:num_level_1=3 t:num_level_2=22 t:pct_level_3_and_4=35.9 t:num_level_3=14 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=14 t:num_level_4=0 m:number_tested=39
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:wrhz-w8mn l:"English Language Arts (ELA) Test Results 2006-2012 - School - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/wrhz-w8mn

property e:wrhz-w8mn t:meta.view v:id=wrhz-w8mn v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/66E8CC55-51E7-4DE5-8C5C-08C588701A1E/0/SchoolELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - School - All Students" v:attribution="Department of Education (DOE)"

property e:wrhz-w8mn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wrhz-w8mn t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | All Students | 37            | 651              | 4           | 10.8        | 14          | 37.8        | 19          | 51.4        | 0           | 0           | 19                | 51.4              | 
| 01M015 | 3     | 2007 | All Students | 33            | 635              | 6           | 18.2        | 18          | 54.5        | 9           | 27.3        | 0           | 0           | 9                 | 27.3              | 
| 01M015 | 3     | 2008 | All Students | 39            | 646              | 3           | 7.7         | 22          | 56.4        | 14          | 35.9        | 0           | 0           | 14                | 35.9              | 
| 01M015 | 3     | 2009 | All Students | 33            | 644              | 1           | 3           | 19          | 57.6        | 13          | 39.4        | 0           | 0           | 13                | 39.4              | 
| 01M015 | 3     | 2010 | All Students | 25            | 652              | 10          | 40          | 11          | 44          | 3           | 12          | 1           | 4           | 4                 | 16                | 
| 01M015 | 3     | 2011 | All Students | 28            | 647              | 7           | 25          | 18          | 64.3        | 3           | 10.7        | 0           | 0           | 3                 | 10.7              | 
| 01M015 | 3     | 2012 | All Students | 21            | 651              | 7           | 33.3        | 9           | 42.9        | 4           | 19          | 1           | 4.8         | 5                 | 23.8              | 
| 01M015 | 4     | 2006 | All Students | 46            | 621              | 18          | 39.1        | 20          | 43.5        | 7           | 15.2        | 1           | 2.2         | 8                 | 17.4              | 
| 01M015 | 4     | 2007 | All Students | 42            | 648              | 2           | 4.8         | 21          | 50          | 19          | 45.2        | 0           | 0           | 19                | 45.2              | 
| 01M015 | 4     | 2008 | All Students | 41            | 633              | 6           | 14.6        | 24          | 58.5        | 11          | 26.8        | 0           | 0           | 11                | 26.8              | 
```