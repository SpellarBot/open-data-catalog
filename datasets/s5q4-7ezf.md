# English Language Arts (ELA) Test Results 2006-2012 - Borough - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-borough-ethnicity-4e7df) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s5q4-7ezf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s5q4-7ezf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s5q4-7ezf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s5q4-7ezf |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Borough - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, borough, ethnicity, lifelong learning |
| Created | 2013-02-20T22:01:55Z |
| Publication Date | 2013-02-20T22:02:15Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by borough and student ethnicity.

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
series e:s5q4-7ezf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Asian m:mean_scale_score=668 m:pct_level_1=8.4 m:pct_level_2=21.8 m:pct_level_3=62.4 m:num_level_3_and_4=314 m:pct_level_4=7.3 m:num_level_1=38 m:number_tested=450 m:num_level_2=98 m:pct_level_3_and_4=69.8 m:num_level_4=33 m:num_level_3=281

series e:s5q4-7ezf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Black m:mean_scale_score=647 m:pct_level_1=17.8 m:pct_level_2=35.8 m:pct_level_3=44.5 m:num_level_3_and_4=2355 m:pct_level_4=1.9 m:num_level_1=904 m:number_tested=5075 m:num_level_2=1816 m:pct_level_3_and_4=46.4 m:num_level_4=96 m:num_level_3=2259

series e:s5q4-7ezf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Hispanic m:mean_scale_score=650 m:pct_level_1=16.2 m:pct_level_2=33.8 m:pct_level_3=47.8 m:num_level_3_and_4=3538 m:pct_level_4=2.2 m:num_level_1=1146 m:number_tested=7077 m:num_level_2=2393 m:pct_level_3_and_4=50 m:num_level_4=155 m:num_level_3=3383
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

entity e:s5q4-7ezf l:"English Language Arts (ELA) Test Results 2006-2012 - Borough - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/s5q4-7ezf

property e:s5q4-7ezf t:meta.view v:id=s5q4-7ezf v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/B82F9971-6533-4355-B3F0-19219B74453F/0/BoroughELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Borough - Ethnicity" v:attribution="Department of Education (DOE)"

property e:s5q4-7ezf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s5q4-7ezf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | Asian       | 450           | 668              | 38          | 8.4         | 98          | 21.8        | 281         | 62.4        | 33          | 7.3         | 314               | 69.8              | 
| BRONX   | 3     | 2006 | Black       | 5075          | 647              | 904         | 17.8        | 1816        | 35.8        | 2259        | 44.5        | 96          | 1.9         | 2355              | 46.4              | 
| BRONX   | 3     | 2006 | Hispanic    | 7077          | 650              | 1146        | 16.2        | 2393        | 33.8        | 3383        | 47.8        | 155         | 2.2         | 3538              | 50                | 
| BRONX   | 3     | 2006 | White       | 626           | 673              | 47          | 7.5         | 125         | 20          | 401         | 64.1        | 53          | 8.5         | 454               | 72.5              | 
| BRONX   | 3     | 2007 | Asian       | 537           | 664              | 47          | 8.8         | 129         | 24          | 321         | 59.8        | 40          | 7.4         | 361               | 67.2              | 
| BRONX   | 3     | 2007 | Black       | 5021          | 644              | 890         | 17.7        | 1895        | 37.7        | 2129        | 42.4        | 107         | 2.1         | 2236              | 44.5              | 
| BRONX   | 3     | 2007 | Hispanic    | 9574          | 642              | 1927        | 20.1        | 3661        | 38.2        | 3765        | 39.3        | 221         | 2.3         | 3986              | 41.6              | 
| BRONX   | 3     | 2007 | White       | 613           | 668              | 50          | 8.2         | 137         | 22.3        | 370         | 60.4        | 56          | 9.1         | 426               | 69.5              | 
| BRONX   | 3     | 2008 | Asian       | 513           | 669              | 20          | 3.9         | 127         | 24.8        | 311         | 60.6        | 55          | 10.7        | 366               | 71.3              | 
| BRONX   | 3     | 2008 | Black       | 4793          | 650              | 602         | 12.6        | 1808        | 37.7        | 2204        | 46          | 179         | 3.7         | 2383              | 49.7              | 
```