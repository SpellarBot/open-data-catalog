# Math Test Results 2006-2012 - Borough - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-borough-swd-a0f16) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7vy4-ats6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7vy4-ats6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7vy4-ats6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7vy4-ats6 |
| Name | Math Test Results 2006-2012 - Borough - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, borough, swd, lifelong learning |
| Created | 2013-02-21T02:43:26Z |
| Publication Date | 2013-02-21T02:43:42Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by borough and disability status.

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
series e:7vy4-ats6 d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="Not SWD" m:mean_scale_score=669 m:pct_level_1=8.4 m:pct_level_2=18.3 m:pct_level_3=55.9 m:num_level_3_and_4=10006 m:pct_level_4=17.4 m:num_level_1=1143 m:number_tested=13647 m:num_level_2=2498 m:pct_level_3_and_4=73.3 m:num_level_4=2374 m:num_level_3=7632

series e:7vy4-ats6 d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=SWD m:mean_scale_score=638 m:pct_level_1=32.8 m:pct_level_2=27.1 m:pct_level_3=35.2 m:num_level_3_and_4=1120 m:pct_level_4=4.8 m:num_level_1=919 m:number_tested=2798 m:num_level_2=759 m:pct_level_3_and_4=40 m:num_level_4=134 m:num_level_3=986

series e:7vy4-ats6 d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="Not SWD" m:mean_scale_score=680 m:pct_level_1=3.9 m:pct_level_2=13.8 m:pct_level_3=59 m:num_level_3_and_4=10867 m:pct_level_4=23.4 m:num_level_1=512 m:number_tested=13194 m:num_level_2=1815 m:pct_level_3_and_4=82.4 m:num_level_4=3084 m:num_level_3=7783
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

entity e:7vy4-ats6 l:"Math Test Results 2006-2012 - Borough - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/7vy4-ats6

property e:7vy4-ats6 t:meta.view v:id=7vy4-ats6 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/9EE3AC39-71D5-4619-9F99-A850842F68DE/0/BoroughMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Borough - SWD" v:attribution="Department of Education (DOE)"

property e:7vy4-ats6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7vy4-ats6 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | Not SWD     | 13647         | 669              | 1143        | 8.4         | 2498        | 18.3        | 7632        | 55.9        | 2374        | 17.4        | 10006             | 73.3              | 
| BRONX   | 3     | 2006 | SWD         | 2798          | 638              | 919         | 32.8        | 759         | 27.1        | 986         | 35.2        | 134         | 4.8         | 1120              | 40                | 
| BRONX   | 3     | 2007 | Not SWD     | 13194         | 680              | 512         | 3.9         | 1815        | 13.8        | 7783        | 59          | 3084        | 23.4        | 10867             | 82.4              | 
| BRONX   | 3     | 2007 | SWD         | 2995          | 647              | 733         | 24.5        | 825         | 27.5        | 1213        | 40.5        | 224         | 7.5         | 1437              | 48                | 
| BRONX   | 3     | 2008 | Not SWD     | 12603         | 682              | 223         | 1.8         | 1219        | 9.7         | 8837        | 70.1        | 2324        | 18.4        | 11161             | 88.6              | 
| BRONX   | 3     | 2008 | SWD         | 3033          | 654              | 447         | 14.7        | 842         | 27.8        | 1610        | 53.1        | 134         | 4.4         | 1744              | 57.5              | 
| BRONX   | 3     | 2009 | Not SWD     | 12665         | 686              | 73          | 0.6         | 814         | 6.4         | 9286        | 73.3        | 2492        | 19.7        | 11778             | 93                | 
| BRONX   | 3     | 2009 | SWD         | 3144          | 663              | 185         | 5.9         | 752         | 23.9        | 2009        | 63.9        | 198         | 6.3         | 2207              | 70.2              | 
| BRONX   | 3     | 2010 | Not SWD     | 12458         | 687              | 1400        | 11.2        | 4953        | 39.8        | 4013        | 32.2        | 2092        | 16.8        | 6105              | 49                | 
| BRONX   | 3     | 2010 | SWD         | 3408          | 669              | 1238        | 36.3        | 1384        | 40.6        | 616         | 18.1        | 170         | 5           | 786               | 23.1              | 
```