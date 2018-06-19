# Math Test Results 2006-2012 - District - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-district-ell-1dfe5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/siju-6isf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/siju-6isf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/siju-6isf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | siju-6isf |
| Name | Math Test Results 2006-2012 - District - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, district, ell, lifelong learning |
| Created | 2013-02-21T02:45:19Z |
| Publication Date | 2013-02-21T02:45:42Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by district and English Language Learner status.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | district          | District          | text      | text        |
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
series e:siju-6isf d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=ELL m:mean_scale_score=667 m:pct_level_1=11.2 m:pct_level_2=21.8 m:pct_level_3=46.8 m:num_level_3_and_4=126 m:pct_level_4=20.2 m:num_level_1=21 m:number_tested=188 m:num_level_2=41 m:pct_level_3_and_4=67 m:num_level_4=38 m:num_level_3=88

series e:siju-6isf d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=EP m:mean_scale_score=675 m:pct_level_1=6.9 m:pct_level_2=17.2 m:pct_level_3=52.9 m:num_level_3_and_4=568 m:pct_level_4=23 m:num_level_1=52 m:number_tested=749 m:num_level_2=129 m:pct_level_3_and_4=75.8 m:num_level_4=172 m:num_level_3=396

series e:siju-6isf d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=ELL m:mean_scale_score=666 m:pct_level_1=6.8 m:pct_level_2=20.9 m:pct_level_3=60.1 m:num_level_3_and_4=107 m:pct_level_4=12.2 m:num_level_1=10 m:number_tested=148 m:num_level_2=31 m:pct_level_3_and_4=72.3 m:num_level_4=18 m:num_level_3=89
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

metric m:pct_level_4 p:integer l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:siju-6isf l:"Math Test Results 2006-2012 - District - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/siju-6isf

property e:siju-6isf t:meta.view v:id=siju-6isf v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/3E439D63-A14E-4B6E-B019-B634A8915D71/0/DistrictMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - District - ELL" v:attribution="Department of Education (DOE)"

property e:siju-6isf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:siju-6isf t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | ELL         | 188           | 667              | 21          | 11.2        | 41          | 21.8        | 88          | 46.8        | 38          | 20.2        | 126               | 67                | 
| 1        | 3     | 2006 | EP          | 749           | 675              | 52          | 6.9         | 129         | 17.2        | 396         | 52.9        | 172         | 23          | 568               | 75.8              | 
| 1        | 3     | 2007 | ELL         | 148           | 666              | 10          | 6.8         | 31          | 20.9        | 89          | 60.1        | 18          | 12.2        | 107               | 72.3              | 
| 1        | 3     | 2007 | EP          | 671           | 683              | 37          | 5.5         | 53          | 7.9         | 409         | 61          | 172         | 25.6        | 581               | 86.6              | 
| 1        | 3     | 2008 | ELL         | 120           | 676              | 4           | 3.3         | 16          | 13.3        | 84          | 70          | 16          | 13.3        | 100               | 83.3              | 
| 1        | 3     | 2008 | EP          | 724           | 688              | 12          | 1.7         | 73          | 10.1        | 443         | 61.2        | 196         | 27.1        | 639               | 88.3              | 
| 1        | 3     | 2009 | ELL         | 94            | 675              | 2           | 2.1         | 13          | 13.8        | 69          | 73.4        | 10          | 10.6        | 79                | 84                | 
| 1        | 3     | 2009 | EP          | 798           | 693              | 6           | 0.8         | 50          | 6.3         | 513         | 64.3        | 229         | 28.7        | 742               | 93                | 
| 1        | 3     | 2010 | ELL         | 92            | 676              | 29          | 31.5        | 34          | 37          | 20          | 21.7        | 9           | 9.8         | 29                | 31.5              | 
| 1        | 3     | 2010 | EP          | 774           | 699              | 60          | 7.8         | 223         | 28.8        | 259         | 33.5        | 232         | 30          | 491               | 63.4              | 
```