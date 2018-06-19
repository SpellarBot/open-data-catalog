# English Language Arts (ELA) Test Results 2006-2012 - Citywide - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-citywide-gender-441d3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cs9m-cz6f) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cs9m-cz6f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cs9m-cz6f/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cs9m-cz6f |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Citywide - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, citywide, lifelong learning |
| Created | 2013-02-20T22:03:32Z |
| Publication Date | 2013-02-20T22:03:42Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by student gender.

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
series e:cs9m-cz6f d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=667 m:pct_level_1=8.7 m:pct_level_2=24.6 m:pct_level_3=60.5 m:num_level_3_and_4=20093 m:pct_level_4=6.3 m:num_level_1=2616 m:number_tested=30109 m:num_level_2=7400 m:pct_level_3_and_4=66.7 m:num_level_4=1882 m:num_level_3=18211

series e:cs9m-cz6f d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=661 m:pct_level_1=10 m:pct_level_2=29.2 m:pct_level_3=53.7 m:num_level_3_and_4=21089 m:pct_level_4=7.1 m:num_level_1=3460 m:number_tested=34691 m:num_level_2=10142 m:pct_level_3_and_4=60.8 m:num_level_4=2452 m:num_level_3=18637

series e:cs9m-cz6f d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=663 m:pct_level_1=6.5 m:pct_level_2=29.8 m:pct_level_3=54.9 m:num_level_3_and_4=21285 m:pct_level_4=8.9 m:num_level_1=2163 m:number_tested=33390 m:num_level_2=9942 m:pct_level_3_and_4=63.7 m:num_level_4=2970 m:num_level_3=18315
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

entity e:cs9m-cz6f l:"English Language Arts (ELA) Test Results 2006-2012 - Citywide - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/cs9m-cz6f

property e:cs9m-cz6f t:meta.view v:id=cs9m-cz6f v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Citywide - Gender" v:attribution="Department of Education (DOE)"

property e:cs9m-cz6f t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cs9m-cz6f t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | Female      | 30109         | 667              | 2616        | 8.7         | 7400        | 24.6        | 18211       | 60.5        | 1882        | 6.3         | 20093             | 66.7              | 
| 3     | 2007 | Female      | 34691         | 661              | 3460        | 10          | 10142       | 29.2        | 18637       | 53.7        | 2452        | 7.1         | 21089             | 60.8              | 
| 3     | 2008 | Female      | 33390         | 663              | 2163        | 6.5         | 9942        | 29.8        | 18315       | 54.9        | 2970        | 8.9         | 21285             | 63.7              | 
| 3     | 2009 | Female      | 34209         | 668              | 1502        | 4.4         | 7197        | 21          | 22245       | 65          | 3265        | 9.5         | 25510             | 74.6              | 
| 3     | 2010 | Female      | 33810         | 666              | 5156        | 15.2        | 11845       | 35          | 11901       | 35.2        | 4908        | 14.5        | 16809             | 49.7              | 
| 3     | 2011 | Female      | 34725         | 663              | 4305        | 12.4        | 11863       | 34.2        | 17065       | 49.1        | 1492        | 4.3         | 18557             | 53.4              | 
| 3     | 2012 | Female      | 35015         | 664              | 4494        | 12.8        | 11768       | 33.6        | 16414       | 46.9        | 2339        | 6.7         | 18753             | 53.6              | 
| 4     | 2006 | Female      | 31750         | 661              | 2844        | 9           | 9053        | 28.5        | 17632       | 55.5        | 2221        | 7           | 19853             | 62.5              | 
| 4     | 2007 | Female      | 33987         | 659              | 2949        | 8.7         | 10530       | 31          | 18424       | 54.2        | 2084        | 6.1         | 20508             | 60.3              | 
| 4     | 2008 | Female      | 33970         | 662              | 2585        | 7.6         | 8876        | 26.1        | 20040       | 59          | 2469        | 7.3         | 22509             | 66.3              | 
```