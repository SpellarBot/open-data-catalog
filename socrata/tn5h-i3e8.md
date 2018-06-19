# English Language Arts (ELA) Test Results 2006-2012 - School - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-school-ethnicity-47af1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tn5h-i3e8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tn5h-i3e8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tn5h-i3e8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tn5h-i3e8 |
| Name | English Language Arts (ELA) Test Results 2006-2012 - School - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, school, lifelong learning |
| Created | 2013-02-20T22:14:38Z |
| Publication Date | 2013-02-20T22:23:37Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by school and student ethnicity.

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
series e:tn5h-i3e8 d:2006-01-01T00:00:00.000Z t:mean_scale_score=s t:pct_level_1=s t:pct_level_2=s t:pct_level_3=s t:pct_level_4=s t:demographic=Asian t:num_level_1=s t:num_level_2=s t:pct_level_3_and_4=s t:num_level_3=s t:dbn=01M015 t:grade=3 t:num_level_3_and_4=s t:num_level_4=s m:number_tested=1

series e:tn5h-i3e8 d:2006-01-01T00:00:00.000Z t:mean_scale_score=646 t:pct_level_1=18.2 t:pct_level_2=36.4 t:pct_level_3=45.5 t:pct_level_4=0 t:demographic=Black t:num_level_1=2 t:num_level_2=4 t:pct_level_3_and_4=45.5 t:num_level_3=5 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=5 t:num_level_4=0 m:number_tested=11

series e:tn5h-i3e8 d:2006-01-01T00:00:00.000Z t:mean_scale_score=652 t:pct_level_1=8.7 t:pct_level_2=34.8 t:pct_level_3=56.5 t:pct_level_4=0 t:demographic=Hispanic t:num_level_1=2 t:num_level_2=8 t:pct_level_3_and_4=56.5 t:num_level_3=13 t:dbn=01M015 t:grade=3 t:num_level_3_and_4=13 t:num_level_4=0 m:number_tested=23
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:tn5h-i3e8 l:"English Language Arts (ELA) Test Results 2006-2012 - School - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/tn5h-i3e8

property e:tn5h-i3e8 t:meta.view v:id=tn5h-i3e8 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/66E8CC55-51E7-4DE5-8C5C-08C588701A1E/0/SchoolELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - School - Ethnicity" v:attribution="Department of Education (DOE)"

property e:tn5h-i3e8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tn5h-i3e8 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ====== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 01M015 | 3     | 2006 | Asian       | 1             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2006 | Black       | 11            | 646              | 2           | 18.2        | 4           | 36.4        | 5           | 45.5        | 0           | 0           | 5                 | 45.5              | 
| 01M015 | 3     | 2006 | Hispanic    | 23            | 652              | 2           | 8.7         | 8           | 34.8        | 13          | 56.5        | 0           | 0           | 13                | 56.5              | 
| 01M015 | 3     | 2006 | White       | 2             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2007 | Asian       | 3             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2007 | Black       | 5             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2007 | Hispanic    | 24            | 642              | 3           | 12.5        | 12          | 50          | 9           | 37.5        | 0           | 0           | 9                 | 37.5              | 
| 01M015 | 3     | 2007 | White       | 1             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Asian       | 1             | s                | s           | s           | s           | s           | s           | s           | s           | s           | s                 | s                 | 
| 01M015 | 3     | 2008 | Black       | 11            | 632              | 3           | 27.3        | 7           | 63.6        | 1           | 9.1         | 0           | 0           | 1                 | 9.1               | 
```