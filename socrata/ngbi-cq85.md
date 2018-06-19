# Math Test Results 2006-2012 - Citywide - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-citywide-ell-1aefe) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ngbi-cq85) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ngbi-cq85/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ngbi-cq85/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ngbi-cq85 |
| Name | Math Test Results 2006-2012 - Citywide - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, citywide, ell, lifelong learning |
| Created | 2013-02-21T02:44:10Z |
| Publication Date | 2013-02-21T02:44:20Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by ELL status

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
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
series e:ngbi-cq85 d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=653 m:pct_level_1=17.6 m:pct_level_2=24.8 m:pct_level_3=48.7 m:num_level_3_and_4=7969 m:pct_level_4=8.9 m:num_level_1=2436 m:number_tested=13842 m:num_level_2=3437 m:pct_level_3_and_4=57.6 m:num_level_4=1234 m:num_level_3=6735

series e:ngbi-cq85 d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=666 m:pct_level_1=10.6 m:pct_level_2=20.3 m:pct_level_3=55 m:num_level_3_and_4=9523 m:pct_level_4=14.1 m:num_level_1=1454 m:number_tested=13781 m:num_level_2=2804 m:pct_level_3_and_4=69.1 m:num_level_4=1947 m:num_level_3=7576

series e:ngbi-cq85 d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=672 m:pct_level_1=5 m:pct_level_2=15.8 m:pct_level_3=68 m:num_level_3_and_4=10052 m:pct_level_4=11.2 m:num_level_1=630 m:number_tested=12689 m:num_level_2=2007 m:pct_level_3_and_4=79.2 m:num_level_4=1422 m:num_level_3=8630
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

entity e:ngbi-cq85 l:"Math Test Results 2006-2012 - Citywide - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ngbi-cq85

property e:ngbi-cq85 t:meta.view v:id=ngbi-cq85 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Citywide - ELL" v:attribution="Department of Education (DOE)"

property e:ngbi-cq85 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ngbi-cq85 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | ELL         | 13842         | 653              | 2436        | 17.6        | 3437        | 24.8        | 6735        | 48.7        | 1234        | 8.9         | 7969              | 57.6              | 
| 3     | 2007 | ELL         | 13781         | 666              | 1454        | 10.6        | 2804        | 20.3        | 7576        | 55          | 1947        | 14.1        | 9523              | 69.1              | 
| 3     | 2008 | ELL         | 12689         | 672              | 630         | 5           | 2007        | 15.8        | 8630        | 68          | 1422        | 11.2        | 10052             | 79.2              | 
| 3     | 2009 | ELL         | 13114         | 676              | 314         | 2.4         | 1640        | 12.5        | 9508        | 72.5        | 1652        | 12.6        | 11160             | 85.1              | 
| 3     | 2010 | ELL         | 13599         | 678              | 2843        | 20.9        | 5685        | 41.8        | 3628        | 26.7        | 1443        | 10.6        | 5071              | 37.3              | 
| 3     | 2011 | ELL         | 13193         | 675              | 2777        | 21          | 5844        | 44.3        | 4137        | 31.4        | 435         | 3.3         | 4572              | 34.7              | 
| 3     | 2012 | ELL         | 12238         | 676              | 2669        | 21.8        | 5052        | 41.3        | 4048        | 33.1        | 469         | 3.8         | 4517              | 36.9              | 
| 4     | 2006 | ELL         | 10435         | 643              | 2600        | 24.9        | 3013        | 28.9        | 4192        | 40.2        | 630         | 6           | 4822              | 46.2              | 
| 4     | 2007 | ELL         | 12051         | 651              | 2174        | 18          | 3440        | 28.5        | 5551        | 46.1        | 886         | 7.4         | 6437              | 53.4              | 
| 4     | 2008 | ELL         | 11319         | 659              | 1397        | 12.3        | 2694        | 23.8        | 6226        | 55          | 1002        | 8.9         | 7228              | 63.9              | 
```