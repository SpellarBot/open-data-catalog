# English Language Arts (ELA) Test Results 2006-2012 - School - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-school-swd-314d5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/phth-xf25) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/phth-xf25/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/phth-xf25/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | phth-xf25 |
| Name | English Language Arts (ELA) Test Results 2006-2012 - School - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, school, lifelong learning |
| Created | 2013-02-20T22:28:36Z |
| Publication Date | 2013-02-20T22:33:32Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by school and student with disabilities status.

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
series e:phth-xf25 d:2006-01-01T00:00:00.000Z t:mean_scale_score=659 t:pct_level_1=3.6 t:pct_level_2=32.1 t:pct_level_3=64.3 t:pct_level_4=0 t:demographic="Not SWD" t:num_level_1=1 t:num_level_2=9 t:pct_level_3_and_4=64.3 t:num_level_3=18 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=18 t:num_level_4=0 m:number_tested=28

series e:phth-xf25 d:2006-01-01T00:00:00.000Z t:mean_scale_score=625 t:pct_level_1=33.3 t:pct_level_2=55.6 t:pct_level_3=11.1 t:pct_level_4=0 t:demographic=SWD t:num_level_1=3 t:num_level_2=5 t:pct_level_3_and_4=11.1 t:num_level_3=1 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=1 t:num_level_4=0 m:number_tested=9

series e:phth-xf25 d:2007-01-01T00:00:00.000Z t:mean_scale_score=637 t:pct_level_1=13.8 t:pct_level_2=62.1 t:pct_level_3=24.1 t:pct_level_4=0 t:demographic="Not SWD" t:num_level_1=4 t:num_level_2=18 t:pct_level_3_and_4=24.1 t:num_level_3=7 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=7 t:num_level_4=0 m:number_tested=29
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:phth-xf25 l:"English Language Arts (ELA) Test Results 2006-2012 - School - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/phth-xf25

property e:phth-xf25 t:meta.view v:id=phth-xf25 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/66E8CC55-51E7-4DE5-8C5C-08C588701A1E/0/SchoolELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - School - SWD" v:attribution="Department of Education (DOE)"

property e:phth-xf25 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:phth-xf25 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | Not SWD     | 28            | 659              | 1           | 3.6         | 9           | 32.1        | 18          | 64.3        | 0           | 0           | 18                | 64.3              | 
| 01M015 | 3     | 2006 | SWD         | 9             | 625              | 3           | 33.3        | 5           | 55.6        | 1           | 11.1        | 0           | 0           | 1                 | 11.1              | 
| 01M015 | 3     | 2007 | Not SWD     | 29            | 637              | 4           | 13.8        | 18          | 62.1        | 7           | 24.1        | 0           | 0           | 7                 | 24.1              | 
| 01M015 | 3     | 2007 | SWD         | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Not SWD     | 32            | 647              | 1           | 3.1         | 19          | 59.4        | 12          | 37.5        | 0           | 0           | 12                | 37.5              | 
| 01M015 | 3     | 2008 | SWD         | 7             | 638              | 2           | 28.6        | 3           | 42.9        | 2           | 28.6        | 0           | 0           | 2                 | 28.6              | 
| 01M015 | 3     | 2009 | Not SWD     | 29            | 645              | 1           | 3.4         | 15          | 51.7        | 13          | 44.8        | 0           | 0           | 13                | 44.8              | 
| 01M015 | 3     | 2009 | SWD         | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2010 | Not SWD     | 19            | 659              | 5           | 26.3        | 10          | 52.6        | 3           | 15.8        | 1           | 5.3         | 4                 | 21.1              | 
| 01M015 | 3     | 2010 | SWD         | 6             | 629              | 5           | 83.3        | 1           | 16.7        | 0           | 0           | 0           | 0           | 0                 | 0                 | 
```