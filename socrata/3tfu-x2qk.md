# Math Test Results 2006-2012 - School - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-school-ethnicity-3a32c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3tfu-x2qk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3tfu-x2qk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3tfu-x2qk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3tfu-x2qk |
| Name | Math Test Results 2006-2012 - School - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, school, ethnicity, lifelong learning |
| Created | 2013-02-21T02:53:49Z |
| Publication Date | 2013-02-21T03:00:51Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by school and ethnicity.

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
series e:3tfu-x2qk d:2006-01-01T00:00:00.000Z t:mean_scale_score=s t:pct_level_1=s t:pct_level_2=s t:pct_level_3=s t:pct_level_4=s t:demographic=Asian t:num_level_1=s t:num_level_2=s t:pct_level_3_and_4=s t:num_level_3=s t:dbn=01M015 t:grade=3 t:num_level_3_and_4=s t:num_level_4=s m:number_tested=3

series e:3tfu-x2qk d:2006-01-01T00:00:00.000Z t:mean_scale_score=662 t:pct_level_1=0 t:pct_level_2=25 t:pct_level_3=75 t:pct_level_4=0 t:demographic=Black t:num_level_1=0 t:num_level_2=3 t:pct_level_3_and_4=75 t:num_level_3=9 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=9 t:num_level_4=0 m:number_tested=12

series e:3tfu-x2qk d:2006-01-01T00:00:00.000Z t:mean_scale_score=670 t:pct_level_1=4.2 t:pct_level_2=33.3 t:pct_level_3=41.7 t:pct_level_4=20.8 t:demographic=Hispanic t:num_level_1=1 t:num_level_2=8 t:pct_level_3_and_4=62.5 t:num_level_3=10 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=15 t:num_level_4=5 m:number_tested=24
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:3tfu-x2qk l:"Math Test Results 2006-2012 - School - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/3tfu-x2qk

property e:3tfu-x2qk t:meta.view v:id=3tfu-x2qk v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/A77DF9C5-BD62-4171-9995-4EB41E7E4067/0/SchoolMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - School - Ethnicity" v:attribution="Department of Education (DOE)"

property e:3tfu-x2qk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3tfu-x2qk t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | Asian       | 3             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2006 | Black       | 12            | 662              | 0           | 0           | 3           | 25          | 9           | 75          | 0           | 0           | 9                 | 75                | 
| 01M015 | 3     | 2006 | Hispanic    | 24            | 670              | 1           | 4.2         | 8           | 33.3        | 10          | 41.7        | 5           | 20.8        | 15                | 62.5              | 
| 01M015 | 3     | 2007 | Asian       | 3             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2007 | Black       | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2007 | Hispanic    | 23            | 678              | 0           | 0           | 1           | 4.3         | 19          | 82.6        | 3           | 13          | 22                | 95.7              | 
| 01M015 | 3     | 2007 | White       | 1             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Asian       | 1             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Black       | 8             | 652              | 0           | 0           | 3           | 37.5        | 5           | 62.5        | 0           | 0           | 5                 | 62.5              | 
| 01M015 | 3     | 2008 | Hispanic    | 27            | 671              | 0           | 0           | 3           | 11.1        | 23          | 85.2        | 1           | 3.7         | 24                | 88.9              | 
```