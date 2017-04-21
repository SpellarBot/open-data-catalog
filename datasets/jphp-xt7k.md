# Math Test Results 2006-2012 - Borough - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-borough-all-students-3378b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jphp-xt7k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jphp-xt7k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jphp-xt7k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jphp-xt7k |
| Name | Math Test Results 2006-2012 - Borough - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, borough, lifelong learning |
| Created | 2013-02-21T02:41:48Z |
| Publication Date | 2013-02-21T02:42:01Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8 disaggregated by borough.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | borough           | Borough           | text      | text        |
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
series e:jphp-xt7k d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=663 m:pct_level_1=12.5 m:pct_level_2=19.8 m:pct_level_3=52.4 m:num_level_3_and_4=11126 m:pct_level_4=15.3 m:num_level_1=2062 m:number_tested=16445 m:num_level_2=3257 m:pct_level_3_and_4=67.7 m:num_level_4=2508 m:num_level_3=8618

series e:jphp-xt7k d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=674 m:pct_level_1=7.7 m:pct_level_2=16.3 m:pct_level_3=55.6 m:num_level_3_and_4=12304 m:pct_level_4=20.4 m:num_level_1=1245 m:number_tested=16189 m:num_level_2=2640 m:pct_level_3_and_4=76 m:num_level_4=3308 m:num_level_3=8996

series e:jphp-xt7k d:2008-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="All Students" m:mean_scale_score=677 m:pct_level_1=4.3 m:pct_level_2=13.2 m:pct_level_3=66.8 m:num_level_3_and_4=12905 m:pct_level_4=15.7 m:num_level_1=670 m:number_tested=15636 m:num_level_2=2061 m:pct_level_3_and_4=82.5 m:num_level_4=2458 m:num_level_3=10447
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

entity e:jphp-xt7k l:"Math Test Results 2006-2012 - Borough - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/jphp-xt7k

property e:jphp-xt7k t:meta.view v:id=jphp-xt7k v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/9EE3AC39-71D5-4619-9F99-A850842F68DE/0/BoroughMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Borough - All Students" v:attribution="Department of Education (DOE)"

property e:jphp-xt7k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jphp-xt7k t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | All Students | 16445         | 663              | 2062        | 12.5        | 3257        | 19.8        | 8618        | 52.4        | 2508        | 15.3        | 11126             | 67.7              | 
| BRONX   | 3     | 2007 | All Students | 16189         | 674              | 1245        | 7.7         | 2640        | 16.3        | 8996        | 55.6        | 3308        | 20.4        | 12304             | 76                | 
| BRONX   | 3     | 2008 | All Students | 15636         | 677              | 670         | 4.3         | 2061        | 13.2        | 10447       | 66.8        | 2458        | 15.7        | 12905             | 82.5              | 
| BRONX   | 3     | 2009 | All Students | 15809         | 681              | 258         | 1.6         | 1566        | 9.9         | 11295       | 71.4        | 2690        | 17          | 13985             | 88.5              | 
| BRONX   | 3     | 2010 | All Students | 15866         | 683              | 2638        | 16.6        | 6337        | 39.9        | 4629        | 29.2        | 2262        | 14.3        | 6891              | 43.4              | 
| BRONX   | 3     | 2011 | All Students | 15820         | 679              | 2566        | 16.2        | 6628        | 41.9        | 5753        | 36.4        | 873         | 5.5         | 6626              | 41.9              | 
| BRONX   | 3     | 2012 | All Students | 16063         | 680              | 2691        | 16.8        | 6433        | 40          | 5971        | 37.2        | 968         | 6           | 6939              | 43.2              | 
| BRONX   | 4     | 2006 | All Students | 15798         | 658              | 2212        | 14          | 3925        | 24.8        | 7702        | 48.8        | 1959        | 12.4        | 9661              | 61.2              | 
| BRONX   | 4     | 2007 | All Students | 16066         | 662              | 1906        | 11.9        | 3775        | 23.5        | 8202        | 51.1        | 2183        | 13.6        | 10385             | 64.6              | 
| BRONX   | 4     | 2008 | All Students | 15745         | 668              | 1404        | 8.9         | 2943        | 18.7        | 9010        | 57.2        | 2388        | 15.2        | 11398             | 72.4              | 
```