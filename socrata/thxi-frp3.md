# English Language Arts (ELA) Test Results 2006-2012 - School - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-school-ell-47f30) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/thxi-frp3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/thxi-frp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/thxi-frp3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | thxi-frp3 |
| Name | English Language Arts (ELA) Test Results 2006-2012 - School - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, school, lifelong learning |
| Created | 2013-02-20T22:09:22Z |
| Publication Date | 2013-02-20T22:14:37Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by school and ELL status.

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
series e:thxi-frp3 d:2006-01-01T00:00:00.000Z t:mean_scale_score=651 t:pct_level_1=10.8 t:pct_level_2=37.8 t:pct_level_3=51.4 t:pct_level_4=0 t:demographic=EP t:num_level_1=4 t:num_level_2=14 t:pct_level_3_and_4=51.4 t:num_level_3=19 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=19 t:num_level_4=0 m:number_tested=37

series e:thxi-frp3 d:2007-01-01T00:00:00.000Z t:mean_scale_score=627 t:pct_level_1=25 t:pct_level_2=75 t:pct_level_3=0 t:pct_level_4=0 t:demographic=ELL t:num_level_1=2 t:num_level_2=6 t:pct_level_3_and_4=0 t:num_level_3=0 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=0 t:num_level_4=0 m:number_tested=8

series e:thxi-frp3 d:2007-01-01T00:00:00.000Z t:mean_scale_score=637 t:pct_level_1=16 t:pct_level_2=48 t:pct_level_3=36 t:pct_level_4=0 t:demographic=EP t:num_level_1=4 t:num_level_2=12 t:pct_level_3_and_4=36 t:num_level_3=9 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=9 t:num_level_4=0 m:number_tested=25
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:thxi-frp3 l:"English Language Arts (ELA) Test Results 2006-2012 - School - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/thxi-frp3

property e:thxi-frp3 t:meta.view v:id=thxi-frp3 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/66E8CC55-51E7-4DE5-8C5C-08C588701A1E/0/SchoolELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - School - ELL" v:attribution="Department of Education (DOE)"

property e:thxi-frp3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:thxi-frp3 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | EP          | 37            | 651              | 4           | 10.8        | 14          | 37.8        | 19          | 51.4        | 0           | 0           | 19                | 51.4              | 
| 01M015 | 3     | 2007 | ELL         | 8             | 627              | 2           | 25          | 6           | 75          | 0           | 0           | 0           | 0           | 0                 | 0                 | 
| 01M015 | 3     | 2007 | EP          | 25            | 637              | 4           | 16          | 12          | 48          | 9           | 36          | 0           | 0           | 9                 | 36                | 
| 01M015 | 3     | 2008 | ELL         | 6             | 643              | 0           | 0           | 4           | 66.7        | 2           | 33.3        | 0           | 0           | 2                 | 33.3              | 
| 01M015 | 3     | 2008 | EP          | 33            | 646              | 3           | 9.1         | 18          | 54.5        | 12          | 36.4        | 0           | 0           | 12                | 36.4              | 
| 01M015 | 3     | 2009 | ELL         | 8             | 642              | 0           | 0           | 5           | 62.5        | 3           | 37.5        | 0           | 0           | 3                 | 37.5              | 
| 01M015 | 3     | 2009 | EP          | 25            | 645              | 1           | 4           | 14          | 56          | 10          | 40          | 0           | 0           | 10                | 40                | 
| 01M015 | 3     | 2010 | ELL         | 4             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2010 | EP          | 21            | 653              | 8           | 38.1        | 9           | 42.9        | 3           | 14.3        | 1           | 4.8         | 4                 | 19                | 
| 01M015 | 3     | 2011 | ELL         | 9             | 636              | 4           | 44.4        | 5           | 55.6        | 0           | 0           | 0           | 0           | 0                 | 0                 | 
```