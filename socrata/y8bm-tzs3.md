# Math Test Results 2006-2012 - School - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-school-ell-f9ef8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/y8bm-tzs3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/y8bm-tzs3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/y8bm-tzs3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | y8bm-tzs3 |
| Name | Math Test Results 2006-2012 - School - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, school, ell, lifelong learning |
| Created | 2013-02-21T02:49:34Z |
| Publication Date | 2013-02-21T02:53:48Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by school and English Language Learner status.

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
series e:y8bm-tzs3 d:2006-01-01T00:00:00.000Z t:mean_scale_score=s t:pct_level_1=s t:pct_level_2=s t:pct_level_3=s t:pct_level_4=s t:demographic=ELL t:num_level_1=s t:num_level_2=s t:pct_level_3_and_4=s t:num_level_3=s t:dbn=01M015 t:grade=3 t:num_level_3_and_4=s t:num_level_4=s m:number_tested=4

series e:y8bm-tzs3 d:2006-01-01T00:00:00.000Z t:mean_scale_score=671 t:pct_level_1=0 t:pct_level_2=28.6 t:pct_level_3=54.3 t:pct_level_4=17.1 t:demographic=EP t:num_level_1=0 t:num_level_2=10 t:pct_level_3_and_4=71.4 t:num_level_3=19 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=25 t:num_level_4=6 m:number_tested=35

series e:y8bm-tzs3 d:2007-01-01T00:00:00.000Z t:mean_scale_score=668 t:pct_level_1=0 t:pct_level_2=12.5 t:pct_level_3=75 t:pct_level_4=12.5 t:demographic=ELL t:num_level_1=0 t:num_level_2=1 t:pct_level_3_and_4=87.5 t:num_level_3=6 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=7 t:num_level_4=1 m:number_tested=8
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:y8bm-tzs3 l:"Math Test Results 2006-2012 - School - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/y8bm-tzs3

property e:y8bm-tzs3 t:meta.view v:id=y8bm-tzs3 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/A77DF9C5-BD62-4171-9995-4EB41E7E4067/0/SchoolMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - School - ELL" v:attribution="Department of Education (DOE)"

property e:y8bm-tzs3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:y8bm-tzs3 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | ELL         | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2006 | EP          | 35            | 671              | 0           | 0           | 10          | 28.6        | 19          | 54.3        | 6           | 17.1        | 25                | 71.4              | 
| 01M015 | 3     | 2007 | ELL         | 8             | 668              | 0           | 0           | 1           | 12.5        | 6           | 75          | 1           | 12.5        | 7                 | 87.5              | 
| 01M015 | 3     | 2007 | EP          | 23            | 674              | 2           | 8.7         | 2           | 8.7         | 16          | 69.6        | 3           | 13          | 19                | 82.6              | 
| 01M015 | 3     | 2008 | ELL         | 6             | 670              | 0           | 0           | 0           | 0           | 6           | 100         | 0           | 0           | 6                 | 100               | 
| 01M015 | 3     | 2008 | EP          | 31            | 668              | 0           | 0           | 6           | 19.4        | 23          | 74.2        | 2           | 6.5         | 25                | 80.6              | 
| 01M015 | 3     | 2009 | ELL         | 9             | 664              | 0           | 0           | 1           | 11.1        | 8           | 88.9        | 0           | 0           | 8                 | 88.9              | 
| 01M015 | 3     | 2009 | EP          | 24            | 669              | 0           | 0           | 3           | 12.5        | 20          | 83.3        | 1           | 4.2         | 21                | 87.5              | 
| 01M015 | 3     | 2010 | ELL         | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2010 | EP          | 22            | 673              | 5           | 22.7        | 11          | 50          | 5           | 22.7        | 1           | 4.5         | 6                 | 27.3              | 
```