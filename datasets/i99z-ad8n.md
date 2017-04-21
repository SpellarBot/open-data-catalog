# Math Test Results 2006-2012 - School - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-school-swd-73a4c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i99z-ad8n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i99z-ad8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i99z-ad8n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i99z-ad8n |
| Name | Math Test Results 2006-2012 - School - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, school, swd, lifelong learning |
| Created | 2013-02-21T03:05:27Z |
| Publication Date | 2013-02-21T03:09:29Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by school and disability status.

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
series e:i99z-ad8n d:2006-01-01T00:00:00.000Z t:mean_scale_score=675 t:pct_level_1=3.4 t:pct_level_2=17.2 t:pct_level_3=58.6 t:pct_level_4=20.7 t:demographic="Not SWD" t:num_level_1=1 t:num_level_2=5 t:pct_level_3_and_4=79.3 t:num_level_3=17 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=23 t:num_level_4=6 m:number_tested=29

series e:i99z-ad8n d:2006-01-01T00:00:00.000Z t:mean_scale_score=644 t:pct_level_1=10 t:pct_level_2=60 t:pct_level_3=30 t:pct_level_4=0 t:demographic=SWD t:num_level_1=1 t:num_level_2=6 t:pct_level_3_and_4=30 t:num_level_3=3 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=3 t:num_level_4=0 m:number_tested=10

series e:i99z-ad8n d:2007-01-01T00:00:00.000Z t:mean_scale_score=675 t:pct_level_1=3.8 t:pct_level_2=11.5 t:pct_level_3=69.2 t:pct_level_4=15.4 t:demographic="Not SWD" t:num_level_1=1 t:num_level_2=3 t:pct_level_3_and_4=84.6 t:num_level_3=18 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=22 t:num_level_4=4 m:number_tested=26
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:i99z-ad8n l:"Math Test Results 2006-2012 - School - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/i99z-ad8n

property e:i99z-ad8n t:meta.view v:id=i99z-ad8n v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/A77DF9C5-BD62-4171-9995-4EB41E7E4067/0/SchoolMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - School - SWD" v:attribution="Department of Education (DOE)"

property e:i99z-ad8n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i99z-ad8n t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | Not SWD     | 29            | 675              | 1           | 3.4         | 5           | 17.2        | 17          | 58.6        | 6           | 20.7        | 23                | 79.3              | 
| 01M015 | 3     | 2006 | SWD         | 10            | 644              | 1           | 10          | 6           | 60          | 3           | 30          | 0           | 0           | 3                 | 30                | 
| 01M015 | 3     | 2007 | Not SWD     | 26            | 675              | 1           | 3.8         | 3           | 11.5        | 18          | 69.2        | 4           | 15.4        | 22                | 84.6              | 
| 01M015 | 3     | 2007 | SWD         | 5             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Not SWD     | 30            | 669              | 0           | 0           | 4           | 13.3        | 24          | 80          | 2           | 6.7         | 26                | 86.7              | 
| 01M015 | 3     | 2008 | SWD         | 7             | 663              | 0           | 0           | 2           | 28.6        | 5           | 71.4        | 0           | 0           | 5                 | 71.4              | 
| 01M015 | 3     | 2009 | Not SWD     | 30            | 668              | 0           | 0           | 4           | 13.3        | 25          | 83.3        | 1           | 3.3         | 26                | 86.7              | 
| 01M015 | 3     | 2009 | SWD         | 3             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2010 | Not SWD     | 20            | 680              | 5           | 25          | 8           | 40          | 5           | 25          | 2           | 10          | 7                 | 35                | 
| 01M015 | 3     | 2010 | SWD         | 6             | 668              | 1           | 16.7        | 4           | 66.7        | 1           | 16.7        | 0           | 0           | 1                 | 16.7              | 
```