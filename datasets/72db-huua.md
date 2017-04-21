# English Language Arts (ELA) Test Results 2006-2012 - Citywide - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-citywide-ell-3e046) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/72db-huua) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/72db-huua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/72db-huua/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 72db-huua |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Citywide - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, citywide, lifelong learning |
| Created | 2013-02-20T22:03:10Z |
| Publication Date | 2013-02-20T22:03:20Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by student ELL status.

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
series e:72db-huua d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=621 m:pct_level_1=43.5 m:pct_level_2=34.1 m:pct_level_3=21.9 m:num_level_3_and_4=500 m:pct_level_4=0.4 m:num_level_1=971 m:number_tested=2233 m:num_level_2=762 m:pct_level_3_and_4=22.4 m:num_level_4=10 m:num_level_3=490

series e:72db-huua d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=631 m:pct_level_1=27.8 m:pct_level_2=43.6 m:pct_level_3=28.1 m:num_level_3_and_4=3610 m:pct_level_4=0.5 m:num_level_1=3515 m:number_tested=12632 m:num_level_2=5507 m:pct_level_3_and_4=28.6 m:num_level_4=66 m:num_level_3=3544

series e:72db-huua d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic=ELL m:mean_scale_score=636 m:pct_level_1=19.7 m:pct_level_2=50 m:pct_level_3=29.5 m:num_level_3_and_4=3553 m:pct_level_4=0.8 m:num_level_1=2304 m:number_tested=11719 m:num_level_2=5862 m:pct_level_3_and_4=30.3 m:num_level_4=93 m:num_level_3=3460
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:num_level_1 p:integer l:"Num Level 1" t:dataTypeName=number

metric m:pct_level_1 p:float l:"Pct Level 1" t:dataTypeName=number

metric m:num_level_2 p:integer l:"Num Level 2" t:dataTypeName=number

metric m:pct_level_2 p:integer l:"Pct Level 2" t:dataTypeName=number

metric m:num_level_3 p:integer l:"Num Level 3" t:dataTypeName=number

metric m:pct_level_3 p:float l:"Pct Level 3" t:dataTypeName=number

metric m:num_level_4 p:integer l:"Num Level 4" t:dataTypeName=number

metric m:pct_level_4 p:float l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:72db-huua l:"English Language Arts (ELA) Test Results 2006-2012 - Citywide - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/72db-huua

property e:72db-huua t:meta.view v:id=72db-huua v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Citywide - ELL" v:attribution="Department of Education (DOE)"

property e:72db-huua t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:72db-huua t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | ELL         | 2233          | 621              | 971         | 43.5        | 762         | 34.1        | 490         | 21.9        | 10          | 0.4         | 500               | 22.4              | 
| 3     | 2007 | ELL         | 12632         | 631              | 3515        | 27.8        | 5507        | 43.6        | 3544        | 28.1        | 66          | 0.5         | 3610              | 28.6              | 
| 3     | 2008 | ELL         | 11719         | 636              | 2304        | 19.7        | 5862        | 50          | 3460        | 29.5        | 93          | 0.8         | 3553              | 30.3              | 
| 3     | 2009 | ELL         | 11980         | 645              | 1716        | 14.3        | 4660        | 38.9        | 5452        | 45.5        | 152         | 1.3         | 5604              | 46.8              | 
| 3     | 2010 | ELL         | 12106         | 649              | 4150        | 34.3        | 5086        | 42          | 2460        | 20.3        | 410         | 3.4         | 2870              | 23.7              | 
| 3     | 2011 | ELL         | 11871         | 647              | 4012        | 33.8        | 5288        | 44.5        | 2546        | 21.4        | 25          | 0.2         | 2571              | 21.7              | 
| 3     | 2012 | ELL         | 11039         | 646              | 4204        | 38.1        | 4775        | 43.3        | 2033        | 18.4        | 27          | 0.2         | 2060              | 18.7              | 
| 4     | 2006 | ELL         | 2938          | 612              | 1327        | 45.2        | 1116        | 38          | 488         | 16.6        | 7           | 0.2         | 495               | 16.8              | 
| 4     | 2007 | ELL         | 10873         | 623              | 3512        | 32.3        | 5063        | 46.6        | 2282        | 21          | 16          | 0.1         | 2298              | 21.1              | 
| 4     | 2008 | ELL         | 10271         | 628              | 2607        | 25.4        | 4649        | 45.3        | 2991        | 29.1        | 24          | 0.2         | 3015              | 29.4              | 
```