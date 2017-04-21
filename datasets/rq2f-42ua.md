# English Language Arts (ELA) Test Results 2006-2012 - District - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-district-swd-7273c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rq2f-42ua) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rq2f-42ua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rq2f-42ua/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rq2f-42ua |
| Name | English Language Arts (ELA) Test Results 2006-2012 - District - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, district, lifelong learning |
| Created | 2013-02-20T22:05:58Z |
| Publication Date | 2013-02-20T22:06:24Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by district and disability status.

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
series e:rq2f-42ua d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="Not SWD" m:mean_scale_score=669 m:pct_level_1=5.6 m:pct_level_2=25.2 m:pct_level_3=63.7 m:num_level_3_and_4=453 m:pct_level_4=5.5 m:num_level_1=37 m:number_tested=655 m:num_level_2=165 m:pct_level_3_and_4=69.2 m:num_level_4=36 m:num_level_3=417

series e:rq2f-42ua d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=SWD m:mean_scale_score=636 m:pct_level_1=33.6 m:pct_level_2=32.9 m:pct_level_3=29.6 m:num_level_3_and_4=51 m:pct_level_4=3.9 m:num_level_1=51 m:number_tested=152 m:num_level_2=50 m:pct_level_3_and_4=33.6 m:num_level_4=6 m:num_level_3=45

series e:rq2f-42ua d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="Not SWD" m:mean_scale_score=666 m:pct_level_1=6.1 m:pct_level_2=28.4 m:pct_level_3=56.7 m:num_level_3_and_4=444 m:pct_level_4=8.9 m:num_level_1=41 m:number_tested=677 m:num_level_2=192 m:pct_level_3_and_4=65.6 m:num_level_4=60 m:num_level_3=384
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

entity e:rq2f-42ua l:"English Language Arts (ELA) Test Results 2006-2012 - District - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rq2f-42ua

property e:rq2f-42ua t:meta.view v:id=rq2f-42ua v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/D8B559C6-A588-44B6-AECE-1108BE52BE9F/0/DistrictELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - District - SWD" v:attribution="Department of Education (DOE)"

property e:rq2f-42ua t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rq2f-42ua t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | Not SWD     | 655           | 669              | 37          | 5.6         | 165         | 25.2        | 417         | 63.7        | 36          | 5.5         | 453               | 69.2              | 
| 1        | 3     | 2006 | SWD         | 152           | 636              | 51          | 33.6        | 50          | 32.9        | 45          | 29.6        | 6           | 3.9         | 51                | 33.6              | 
| 1        | 3     | 2007 | Not SWD     | 677           | 666              | 41          | 6.1         | 192         | 28.4        | 384         | 56.7        | 60          | 8.9         | 444               | 65.6              | 
| 1        | 3     | 2007 | SWD         | 134           | 627              | 50          | 37.3        | 42          | 31.3        | 40          | 29.9        | 2           | 1.5         | 42                | 31.3              | 
| 1        | 3     | 2008 | Not SWD     | 678           | 669              | 15          | 2.2         | 193         | 28.5        | 400         | 59          | 70          | 10.3        | 470               | 69.3              | 
| 1        | 3     | 2008 | SWD         | 156           | 634              | 39          | 25          | 69          | 44.2        | 45          | 28.8        | 3           | 1.9         | 48                | 30.8              | 
| 1        | 3     | 2009 | Not SWD     | 734           | 673              | 10          | 1.4         | 146         | 19.9        | 497         | 67.7        | 81          | 11          | 578               | 78.7              | 
| 1        | 3     | 2009 | SWD         | 146           | 638              | 33          | 22.6        | 67          | 45.9        | 45          | 30.8        | 1           | 0.7         | 46                | 31.5              | 
| 1        | 3     | 2010 | Not SWD     | 684           | 675              | 57          | 8.3         | 221         | 32.3        | 251         | 36.7        | 155         | 22.7        | 406               | 59.4              | 
| 1        | 3     | 2010 | SWD         | 164           | 642              | 80          | 48.8        | 55          | 33.5        | 21          | 12.8        | 8           | 4.9         | 29                | 17.7              | 
```