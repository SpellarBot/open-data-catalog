# Math Test Results 2006-2012 - School - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-school-all-students-b2468) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3mrr-8h5c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3mrr-8h5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3mrr-8h5c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3mrr-8h5c |
| Name | Math Test Results 2006-2012 - School - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, school, all student, lifelong learning |
| Created | 2013-02-21T02:47:04Z |
| Publication Date | 2013-02-21T02:49:33Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by school.

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
series e:3mrr-8h5c d:2006-01-01T00:00:00.000Z t:mean_scale_score=667 t:pct_level_1=5.1 t:pct_level_2=28.2 t:pct_level_3=51.3 t:pct_level_4=15.4 t:demographic="All Students" t:num_level_1=2 t:num_level_2=11 t:pct_level_3_and_4=66.7 t:num_level_3=20 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=26 t:num_level_4=6 m:number_tested=39

series e:3mrr-8h5c d:2007-01-01T00:00:00.000Z t:mean_scale_score=672 t:pct_level_1=6.5 t:pct_level_2=9.7 t:pct_level_3=71 t:pct_level_4=12.9 t:demographic="All Students" t:num_level_1=2 t:num_level_2=3 t:pct_level_3_and_4=83.9 t:num_level_3=22 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=26 t:num_level_4=4 m:number_tested=31

series e:3mrr-8h5c d:2008-01-01T00:00:00.000Z t:mean_scale_score=668 t:pct_level_1=0 t:pct_level_2=16.2 t:pct_level_3=78.4 t:pct_level_4=5.4 t:demographic="All Students" t:num_level_1=0 t:num_level_2=6 t:pct_level_3_and_4=83.8 t:num_level_3=29 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=31 t:num_level_4=2 m:number_tested=37
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:3mrr-8h5c l:"Math Test Results 2006-2012 - School - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/3mrr-8h5c

property e:3mrr-8h5c t:meta.view v:id=3mrr-8h5c v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/A77DF9C5-BD62-4171-9995-4EB41E7E4067/0/SchoolMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - School - All Students" v:attribution="Department of Education (DOE)"

property e:3mrr-8h5c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3mrr-8h5c t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | All Students | 39            | 667              | 2           | 5.1         | 11          | 28.2        | 20          | 51.3        | 6           | 15.4        | 26                | 66.7              | 
| 01M015 | 3     | 2007 | All Students | 31            | 672              | 2           | 6.5         | 3           | 9.7         | 22          | 71          | 4           | 12.9        | 26                | 83.9              | 
| 01M015 | 3     | 2008 | All Students | 37            | 668              | 0           | 0           | 6           | 16.2        | 29          | 78.4        | 2           | 5.4         | 31                | 83.8              | 
| 01M015 | 3     | 2009 | All Students | 33            | 668              | 0           | 0           | 4           | 12.1        | 28          | 84.8        | 1           | 3           | 29                | 87.9              | 
| 01M015 | 3     | 2010 | All Students | 26            | 677              | 6           | 23.1        | 12          | 46.2        | 6           | 23.1        | 2           | 7.7         | 8                 | 30.8              | 
| 01M015 | 3     | 2011 | All Students | 28            | 671              | 10          | 35.7        | 13          | 46.4        | 5           | 17.9        | 0           | 0           | 5                 | 17.9              | 
| 01M015 | 3     | 2012 | All Students | 21            | 678              | 2           | 9.5         | 12          | 57.1        | 7           | 33.3        | 0           | 0           | 7                 | 33.3              | 
| 01M015 | 4     | 2006 | All Students | 49            | 629              | 20          | 40.8        | 18          | 36.7        | 10          | 20.4        | 1           | 2           | 11                | 22.4              | 
| 01M015 | 4     | 2007 | All Students | 40            | 659              | 4           | 10          | 13          | 32.5        | 18          | 45          | 5           | 12.5        | 23                | 57.5              | 
| 01M015 | 4     | 2008 | All Students | 41            | 655              | 5           | 12.2        | 15          | 36.6        | 18          | 43.9        | 3           | 7.3         | 21                | 51.2              | 
```