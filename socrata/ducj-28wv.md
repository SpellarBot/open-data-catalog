# Math Test Results 2006-2012 - District - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-district-swd-b3e14) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ducj-28wv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ducj-28wv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ducj-28wv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ducj-28wv |
| Name | Math Test Results 2006-2012 - District - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, district, swd, lifelong learning |
| Created | 2013-02-21T02:46:41Z |
| Publication Date | 2013-02-21T02:47:03Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by district and disability status.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | district          | District          | text      | text        |
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
series e:ducj-28wv d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="Not SWD" m:mean_scale_score=680 m:pct_level_1=4.1 m:pct_level_2=15.3 m:pct_level_3=54.1 m:num_level_3_and_4=605 m:pct_level_4=26.5 m:num_level_1=31 m:number_tested=751 m:num_level_2=115 m:pct_level_3_and_4=80.6 m:num_level_4=199 m:num_level_3=406

series e:ducj-28wv d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=SWD m:mean_scale_score=647 m:pct_level_1=22.6 m:pct_level_2=29.6 m:pct_level_3=41.9 m:num_level_3_and_4=89 m:pct_level_4=5.9 m:num_level_1=42 m:number_tested=186 m:num_level_2=55 m:pct_level_3_and_4=47.8 m:num_level_4=11 m:num_level_3=78

series e:ducj-28wv d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="Not SWD" m:mean_scale_score=685 m:pct_level_1=2.7 m:pct_level_2=8.2 m:pct_level_3=62.2 m:num_level_3_and_4=599 m:pct_level_4=26.9 m:num_level_1=18 m:number_tested=672 m:num_level_2=55 m:pct_level_3_and_4=89.1 m:num_level_4=181 m:num_level_3=418
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

entity e:ducj-28wv l:"Math Test Results 2006-2012 - District - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ducj-28wv

property e:ducj-28wv t:meta.view v:id=ducj-28wv v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/3E439D63-A14E-4B6E-B019-B634A8915D71/0/DistrictMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - District - SWD" v:attribution="Department of Education (DOE)"

property e:ducj-28wv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ducj-28wv t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | Not SWD     | 751           | 680              | 31          | 4.1         | 115         | 15.3        | 406         | 54.1        | 199         | 26.5        | 605               | 80.6              | 
| 1        | 3     | 2006 | SWD         | 186           | 647              | 42          | 22.6        | 55          | 29.6        | 78          | 41.9        | 11          | 5.9         | 89                | 47.8              | 
| 1        | 3     | 2007 | Not SWD     | 672           | 685              | 18          | 2.7         | 55          | 8.2         | 418         | 62.2        | 181         | 26.9        | 599               | 89.1              | 
| 1        | 3     | 2007 | SWD         | 147           | 654              | 29          | 19.7        | 29          | 19.7        | 80          | 54.4        | 9           | 6.1         | 89                | 60.5              | 
| 1        | 3     | 2008 | Not SWD     | 677           | 693              | 3           | 0.4         | 34          | 5           | 437         | 64.5        | 203         | 30          | 640               | 94.5              | 
| 1        | 3     | 2008 | SWD         | 167           | 659              | 13          | 7.8         | 55          | 32.9        | 90          | 53.9        | 9           | 5.4         | 99                | 59.3              | 
| 1        | 3     | 2009 | Not SWD     | 741           | 697              | 3           | 0.4         | 24          | 3.2         | 483         | 65.2        | 231         | 31.2        | 714               | 96.4              | 
| 1        | 3     | 2009 | SWD         | 151           | 661              | 5           | 3.3         | 39          | 25.8        | 99          | 65.6        | 8           | 5.3         | 107               | 70.9              | 
| 1        | 3     | 2010 | Not SWD     | 700           | 702              | 36          | 5.1         | 187         | 26.7        | 245         | 35          | 232         | 33.1        | 477               | 68.1              | 
| 1        | 3     | 2010 | SWD         | 166           | 671              | 53          | 31.9        | 70          | 42.2        | 34          | 20.5        | 9           | 5.4         | 43                | 25.9              | 
```