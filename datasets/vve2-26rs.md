# Math Test Results 2006-2012 - Citywide - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-citywide-ethnicity-2c63f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vve2-26rs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vve2-26rs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vve2-26rs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vve2-26rs |
| Name | Math Test Results 2006-2012 - Citywide - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, citywide, ethnicity, lifelong learning |
| Created | 2013-02-21T02:44:20Z |
| Publication Date | 2013-02-21T02:44:33Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by ethnicity.

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
series e:vve2-26rs d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic=Asian m:mean_scale_score=700 m:pct_level_1=2.5 m:pct_level_2=5.6 m:pct_level_3=42.3 m:num_level_3_and_4=8982 m:pct_level_4=49.7 m:num_level_1=243 m:number_tested=9768 m:num_level_2=543 m:pct_level_3_and_4=92 m:num_level_4=4854 m:num_level_3=4128

series e:vve2-26rs d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic=Asian m:mean_scale_score=706 m:pct_level_1=1.6 m:pct_level_2=4.1 m:pct_level_3=39.9 m:num_level_3_and_4=9192 m:pct_level_4=54.4 m:num_level_1=156 m:number_tested=9750 m:num_level_2=402 m:pct_level_3_and_4=94.3 m:num_level_4=5306 m:num_level_3=3886

series e:vve2-26rs d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic=Asian m:mean_scale_score=707 m:pct_level_1=0.7 m:pct_level_2=2.8 m:pct_level_3=48.3 m:num_level_3_and_4=9609 m:pct_level_4=48.2 m:num_level_1=67 m:number_tested=9951 m:num_level_2=275 m:pct_level_3_and_4=96.6 m:num_level_4=4800 m:num_level_3=4809
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

entity e:vve2-26rs l:"Math Test Results 2006-2012 - Citywide - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vve2-26rs

property e:vve2-26rs t:meta.view v:id=vve2-26rs v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Citywide - Ethnicity" v:attribution="Department of Education (DOE)"

property e:vve2-26rs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vve2-26rs t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | Asian       | 9768          | 700              | 243         | 2.5         | 543         | 5.6         | 4128        | 42.3        | 4854        | 49.7        | 8982              | 92                | 
| 3     | 2007 | Asian       | 9750          | 706              | 156         | 1.6         | 402         | 4.1         | 3886        | 39.9        | 5306        | 54.4        | 9192              | 94.3              | 
| 3     | 2008 | Asian       | 9951          | 707              | 67          | 0.7         | 275         | 2.8         | 4809        | 48.3        | 4800        | 48.2        | 9609              | 96.6              | 
| 3     | 2009 | Asian       | 10984         | 711              | 43          | 0.4         | 216         | 2           | 5532        | 50.4        | 5193        | 47.3        | 10725             | 97.6              | 
| 3     | 2010 | Asian       | 10646         | 709              | 415         | 3.9         | 1823        | 17.1        | 3888        | 36.5        | 4520        | 42.5        | 8408              | 79                | 
| 3     | 2011 | Asian       | 11007         | 697              | 402         | 3.7         | 1839        | 16.7        | 5652        | 51.3        | 3114        | 28.3        | 8766              | 79.6              | 
| 3     | 2012 | Asian       | 11315         | 699              | 331         | 2.9         | 1717        | 15.2        | 6100        | 53.9        | 3167        | 28          | 9267              | 81.9              | 
| 4     | 2006 | Asian       | 9973          | 699              | 294         | 2.9         | 600         | 6           | 4245        | 42.6        | 4834        | 48.5        | 9079              | 91                | 
| 4     | 2007 | Asian       | 9881          | 704              | 209         | 2.1         | 564         | 5.7         | 3968        | 40.2        | 5140        | 52          | 9108              | 92.2              | 
| 4     | 2008 | Asian       | 9861          | 706              | 159         | 1.6         | 389         | 3.9         | 3874        | 39.3        | 5439        | 55.2        | 9313              | 94.4              | 
```