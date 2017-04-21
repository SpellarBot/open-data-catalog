# Math Test Results 2006-2012 - Borough - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-borough-ethnicity-a6fe6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ihup-vdhf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ihup-vdhf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ihup-vdhf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ihup-vdhf |
| Name | Math Test Results 2006-2012 - Borough - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, borough, ethnicity, lifelong learning |
| Created | 2013-02-21T02:42:14Z |
| Publication Date | 2013-02-21T02:42:27Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by borough and ethnicity.

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
series e:ihup-vdhf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Asian m:mean_scale_score=689 m:pct_level_1=6.1 m:pct_level_2=11 m:pct_level_3=43.2 m:num_level_3_and_4=474 m:pct_level_4=39.7 m:num_level_1=35 m:number_tested=572 m:num_level_2=63 m:pct_level_3_and_4=82.9 m:num_level_4=227 m:num_level_3=247

series e:ihup-vdhf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Black m:mean_scale_score=662 m:pct_level_1=12.2 m:pct_level_2=20.5 m:pct_level_3=53.4 m:num_level_3_and_4=3563 m:pct_level_4=13.9 m:num_level_1=645 m:number_tested=5296 m:num_level_2=1088 m:pct_level_3_and_4=67.3 m:num_level_4=737 m:num_level_3=2826

series e:ihup-vdhf d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Hispanic m:mean_scale_score=661 m:pct_level_1=13.5 m:pct_level_2=20.7 m:pct_level_3=52.5 m:num_level_3_and_4=6495 m:pct_level_4=13.2 m:num_level_1=1336 m:number_tested=9875 m:num_level_2=2044 m:pct_level_3_and_4=65.8 m:num_level_4=1307 m:num_level_3=5188
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:num_level_1 p:integer l:"Num Level 1" t:dataTypeName=number

metric m:pct_level_1 p:integer l:"Pct Level 1" t:dataTypeName=number

metric m:num_level_2 p:integer l:"Num Level 2" t:dataTypeName=number

metric m:pct_level_2 p:float l:"Pct Level 2" t:dataTypeName=number

metric m:num_level_3 p:integer l:"Num Level 3" t:dataTypeName=number

metric m:pct_level_3 p:float l:"Pct Level 3" t:dataTypeName=number

metric m:num_level_4 p:integer l:"Num Level 4" t:dataTypeName=number

metric m:pct_level_4 p:float l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:ihup-vdhf l:"Math Test Results 2006-2012 - Borough - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ihup-vdhf

property e:ihup-vdhf t:meta.view v:id=ihup-vdhf v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/9EE3AC39-71D5-4619-9F99-A850842F68DE/0/BoroughMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Borough - Ethnicity" v:attribution="Department of Education (DOE)"

property e:ihup-vdhf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ihup-vdhf t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | Asian       | 572           | 689              | 35          | 6.1         | 63          | 11          | 247         | 43.2        | 227         | 39.7        | 474               | 82.9              | 
| BRONX   | 3     | 2006 | Black       | 5296          | 662              | 645         | 12.2        | 1088        | 20.5        | 2826        | 53.4        | 737         | 13.9        | 3563              | 67.3              | 
| BRONX   | 3     | 2006 | Hispanic    | 9875          | 661              | 1336        | 13.5        | 2044        | 20.7        | 5188        | 52.5        | 1307        | 13.2        | 6495              | 65.8              | 
| BRONX   | 3     | 2006 | White       | 636           | 686              | 37          | 5.8         | 43          | 6.8         | 333         | 52.4        | 223         | 35.1        | 556               | 87.4              | 
| BRONX   | 3     | 2007 | Asian       | 555           | 697              | 14          | 2.5         | 41          | 7.4         | 253         | 45.6        | 247         | 44.5        | 500               | 90.1              | 
| BRONX   | 3     | 2007 | Black       | 5066          | 671              | 450         | 8.9         | 843         | 16.6        | 2844        | 56.1        | 929         | 18.3        | 3773              | 74.5              | 
| BRONX   | 3     | 2007 | Hispanic    | 9817          | 672              | 756         | 7.7         | 1708        | 17.4        | 5495        | 56          | 1858        | 18.9        | 7353              | 74.9              | 
| BRONX   | 3     | 2007 | White       | 630           | 695              | 16          | 2.5         | 36          | 5.7         | 330         | 52.4        | 248         | 39.4        | 578               | 91.7              | 
| BRONX   | 3     | 2008 | Asian       | 523           | 704              | 7           | 1.3         | 14          | 2.7         | 268         | 51.2        | 234         | 44.7        | 502               | 96                | 
| BRONX   | 3     | 2008 | Black       | 4804          | 674              | 231         | 4.8         | 701         | 14.6        | 3223        | 67.1        | 649         | 13.5        | 3872              | 80.6              | 
```