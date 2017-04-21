# English Language Arts (ELA) Test Results 2006-2012 - Citywide - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-citywide-swd-638b6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d72n-ivax) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d72n-ivax/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d72n-ivax/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d72n-ivax |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Citywide - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, citywide, lifelong learning |
| Created | 2013-02-20T22:03:43Z |
| Publication Date | 2013-02-20T22:03:54Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated citywide and student with disabilities.

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
series e:d72n-ivax d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=668 m:pct_level_1=6.4 m:pct_level_2=25.4 m:pct_level_3=62.2 m:num_level_3_and_4=35599 m:pct_level_4=5.9 m:num_level_1=3355 m:number_tested=52245 m:num_level_2=13291 m:pct_level_3_and_4=68.1 m:num_level_4=3107 m:num_level_3=32492

series e:d72n-ivax d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=663 m:pct_level_1=7.7 m:pct_level_2=29.4 m:pct_level_3=55.7 m:num_level_3_and_4=37391 m:pct_level_4=7.1 m:num_level_1=4573 m:number_tested=59452 m:num_level_2=17488 m:pct_level_3_and_4=62.9 m:num_level_4=4248 m:num_level_3=33143

series e:d72n-ivax d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=665 m:pct_level_1=4.6 m:pct_level_2=29 m:pct_level_3=57.1 m:num_level_3_and_4=38185 m:pct_level_4=9.2 m:num_level_1=2665 m:number_tested=57545 m:num_level_2=16695 m:pct_level_3_and_4=66.4 m:num_level_4=5304 m:num_level_3=32881
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

entity e:d72n-ivax l:"English Language Arts (ELA) Test Results 2006-2012 - Citywide - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/d72n-ivax

property e:d72n-ivax t:meta.view v:id=d72n-ivax v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Citywide - SWD" v:attribution="Department of Education (DOE)"

property e:d72n-ivax t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d72n-ivax t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | Not SWD     | 52245         | 668              | 3355        | 6.4         | 13291       | 25.4        | 32492       | 62.2        | 3107        | 5.9         | 35599             | 68.1              | 
| 3     | 2007 | Not SWD     | 59452         | 663              | 4573        | 7.7         | 17488       | 29.4        | 33143       | 55.7        | 4248        | 7.1         | 37391             | 62.9              | 
| 3     | 2008 | Not SWD     | 57545         | 665              | 2665        | 4.6         | 16695       | 29          | 32881       | 57.1        | 5304        | 9.2         | 38185             | 66.4              | 
| 3     | 2009 | Not SWD     | 58009         | 670              | 1597        | 2.8         | 12088       | 20.8        | 38974       | 67.2        | 5350        | 9.2         | 44324             | 76.4              | 
| 3     | 2010 | Not SWD     | 56986         | 668              | 6548        | 11.5        | 20363       | 35.7        | 21484       | 37.7        | 8591        | 15.1        | 30075             | 52.8              | 
| 3     | 2011 | Not SWD     | 58084         | 664              | 5725        | 9.9         | 20692       | 35.6        | 29357       | 50.5        | 2310        | 4           | 31667             | 54.5              | 
| 3     | 2012 | Not SWD     | 58608         | 665              | 6224        | 10.6        | 19797       | 33.8        | 28728       | 49          | 3859        | 6.6         | 32587             | 55.6              | 
| 4     | 2006 | Not SWD     | 54339         | 665              | 3168        | 5.8         | 15266       | 28.1        | 32152       | 59.2        | 3753        | 6.9         | 35905             | 66.1              | 
| 4     | 2007 | Not SWD     | 57674         | 661              | 3335        | 5.8         | 17874       | 31          | 33089       | 57.4        | 3376        | 5.9         | 36465             | 63.2              | 
| 4     | 2008 | Not SWD     | 57053         | 664              | 2989        | 5.2         | 14737       | 25.8        | 35386       | 62          | 3941        | 6.9         | 39327             | 68.9              | 
```