# English Language Arts (ELA) Test Results 2006-2012 - Borough - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-borough-ell-b323f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h3zm-ta5h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h3zm-ta5h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h3zm-ta5h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h3zm-ta5h |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Borough - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, borough, ell, lifelong learning |
| Created | 2013-02-20T22:01:38Z |
| Publication Date | 2013-02-20T22:01:55Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by borough and ELL status.

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
series e:h3zm-ta5h d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=ELL m:mean_scale_score=618 m:pct_level_1=45 m:pct_level_2=35.6 m:pct_level_3=19.2 m:num_level_3_and_4=148 m:pct_level_4=0.1 m:num_level_1=345 m:number_tested=766 m:num_level_2=273 m:pct_level_3_and_4=19.3 m:num_level_4=1 m:num_level_3=147

series e:h3zm-ta5h d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=EP m:mean_scale_score=652 m:pct_level_1=14.4 m:pct_level_2=33.4 m:pct_level_3=49.5 m:num_level_3_and_4=6537 m:pct_level_4=2.7 m:num_level_1=1809 m:number_tested=12530 m:num_level_2=4184 m:pct_level_3_and_4=52.2 m:num_level_4=337 m:num_level_3=6200

series e:h3zm-ta5h d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=ELL m:mean_scale_score=626 m:pct_level_1=31.9 m:pct_level_2=45.8 m:pct_level_3=22 m:num_level_3_and_4=698 m:pct_level_4=0.2 m:num_level_1=1004 m:number_tested=3143 m:num_level_2=1441 m:pct_level_3_and_4=22.2 m:num_level_4=5 m:num_level_3=693
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:num_level_1 p:integer l:"Num Level 1" t:dataTypeName=number

metric m:pct_level_1 p:integer l:"Pct Level 1" t:dataTypeName=number

metric m:num_level_2 p:integer l:"Num Level 2" t:dataTypeName=number

metric m:pct_level_2 p:integer l:"Pct Level 2" t:dataTypeName=number

metric m:num_level_3 p:integer l:"Num Level 3" t:dataTypeName=number

metric m:pct_level_3 p:integer l:"Pct Level 3" t:dataTypeName=number

metric m:num_level_4 p:integer l:"Num Level 4" t:dataTypeName=number

metric m:pct_level_4 p:float l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:h3zm-ta5h l:"English Language Arts (ELA) Test Results 2006-2012 - Borough - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/h3zm-ta5h

property e:h3zm-ta5h t:meta.view v:id=h3zm-ta5h v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/B82F9971-6533-4355-B3F0-19219B74453F/0/BoroughELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Borough - ELL" v:attribution="Department of Education (DOE)"

property e:h3zm-ta5h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h3zm-ta5h t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | ELL         | 766           | 618              | 345         | 45          | 273         | 35.6        | 147         | 19.2        | 1           | 0.1         | 148               | 19.3              | 
| BRONX   | 3     | 2006 | EP          | 12530         | 652              | 1809        | 14.4        | 4184        | 33.4        | 6200        | 49.5        | 337         | 2.7         | 6537              | 52.2              | 
| BRONX   | 3     | 2007 | ELL         | 3143          | 626              | 1004        | 31.9        | 1441        | 45.8        | 693         | 22          | 5           | 0.2         | 698               | 22.2              | 
| BRONX   | 3     | 2007 | EP          | 12728         | 649              | 1930        | 15.2        | 4423        | 34.8        | 5948        | 46.7        | 427         | 3.4         | 6375              | 50.1              | 
| BRONX   | 3     | 2008 | ELL         | 3092          | 631              | 764         | 24.7        | 1574        | 50.9        | 728         | 23.5        | 26          | 0.8         | 754               | 24.4              | 
| BRONX   | 3     | 2008 | EP          | 12288         | 654              | 1258        | 10.2        | 4288        | 34.9        | 6147        | 50          | 595         | 4.8         | 6742              | 54.9              | 
| BRONX   | 3     | 2009 | ELL         | 3136          | 639              | 596         | 19          | 1307        | 41.7        | 1208        | 38.5        | 25          | 0.8         | 1233              | 39.3              | 
| BRONX   | 3     | 2009 | EP          | 12395         | 659              | 854         | 6.9         | 3530        | 28.5        | 7450        | 60.1        | 561         | 4.5         | 8011              | 64.6              | 
| BRONX   | 3     | 2010 | ELL         | 3346          | 646              | 1374        | 41.1        | 1333        | 39.8        | 564         | 16.9        | 75          | 2.2         | 639               | 19.1              | 
| BRONX   | 3     | 2010 | EP          | 12108         | 659              | 2471        | 20.4        | 4747        | 39.2        | 3767        | 31.1        | 1123        | 9.3         | 4890              | 40.4              | 
```