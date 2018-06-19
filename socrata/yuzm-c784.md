# English Language Arts (ELA) Test Results 2006-2012 - School - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-school-gender-db64a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yuzm-c784) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yuzm-c784/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yuzm-c784/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yuzm-c784 |
| Name | English Language Arts (ELA) Test Results 2006-2012 - School - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, school, lifelong learning |
| Created | 2013-02-20T22:23:38Z |
| Publication Date | 2013-02-20T22:28:35Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by school and student gender.

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
series e:yuzm-c784 d:2006-01-01T00:00:00.000Z t:mean_scale_score=655 t:pct_level_1=8.7 t:pct_level_2=34.8 t:pct_level_3=56.5 t:pct_level_4=0 t:demographic=Female t:num_level_1=2 t:num_level_2=8 t:pct_level_3_and_4=56.5 t:num_level_3=13 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=13 t:num_level_4=0 m:number_tested=23

series e:yuzm-c784 d:2006-01-01T00:00:00.000Z t:mean_scale_score=643 t:pct_level_1=14.3 t:pct_level_2=42.9 t:pct_level_3=42.9 t:pct_level_4=0 t:demographic=Male t:num_level_1=2 t:num_level_2=6 t:pct_level_3_and_4=42.9 t:num_level_3=6 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=6 t:num_level_4=0 m:number_tested=14

series e:yuzm-c784 d:2007-01-01T00:00:00.000Z t:mean_scale_score=633 t:pct_level_1=9.1 t:pct_level_2=63.6 t:pct_level_3=27.3 t:pct_level_4=0 t:demographic=Female t:num_level_1=1 t:num_level_2=7 t:pct_level_3_and_4=27.3 t:num_level_3=3 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=3 t:num_level_4=0 m:number_tested=11
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:yuzm-c784 l:"English Language Arts (ELA) Test Results 2006-2012 - School - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yuzm-c784

property e:yuzm-c784 t:meta.view v:id=yuzm-c784 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/66E8CC55-51E7-4DE5-8C5C-08C588701A1E/0/SchoolELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - School - Gender" v:attribution="Department of Education (DOE)"

property e:yuzm-c784 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yuzm-c784 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | Female      | 23            | 655              | 2           | 8.7         | 8           | 34.8        | 13          | 56.5        | 0           | 0           | 13                | 56.5              | 
| 01M015 | 3     | 2006 | Male        | 14            | 643              | 2           | 14.3        | 6           | 42.9        | 6           | 42.9        | 0           | 0           | 6                 | 42.9              | 
| 01M015 | 3     | 2007 | Female      | 11            | 633              | 1           | 9.1         | 7           | 63.6        | 3           | 27.3        | 0           | 0           | 3                 | 27.3              | 
| 01M015 | 3     | 2007 | Male        | 22            | 636              | 5           | 22.7        | 11          | 50          | 6           | 27.3        | 0           | 0           | 6                 | 27.3              | 
| 01M015 | 3     | 2008 | Female      | 17            | 640              | 3           | 17.6        | 9           | 52.9        | 5           | 29.4        | 0           | 0           | 5                 | 29.4              | 
| 01M015 | 3     | 2008 | Male        | 22            | 650              | 0           | 0           | 13          | 59.1        | 9           | 40.9        | 0           | 0           | 9                 | 40.9              | 
| 01M015 | 3     | 2009 | Female      | 12            | 649              | 0           | 0           | 7           | 58.3        | 5           | 41.7        | 0           | 0           | 5                 | 41.7              | 
| 01M015 | 3     | 2009 | Male        | 21            | 642              | 1           | 4.8         | 12          | 57.1        | 8           | 38.1        | 0           | 0           | 8                 | 38.1              | 
| 01M015 | 3     | 2010 | Female      | 13            | 648              | 6           | 46.2        | 5           | 38.5        | 2           | 15.4        | 0           | 0           | 2                 | 15.4              | 
| 01M015 | 3     | 2010 | Male        | 12            | 655              | 4           | 33.3        | 6           | 50          | 1           | 8.3         | 1           | 8.3         | 2                 | 16.7              | 
```