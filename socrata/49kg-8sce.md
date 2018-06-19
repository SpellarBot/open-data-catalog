# English Language Arts (ELA) Test Results 2006-2012 - District - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-district-gender-78692) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/49kg-8sce) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/49kg-8sce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/49kg-8sce/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 49kg-8sce |
| Name | English Language Arts (ELA) Test Results 2006-2012 - District - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, district, lifelong learning |
| Created | 2013-02-20T22:05:32Z |
| Publication Date | 2013-02-20T22:05:57Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by district and gender.

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
series e:49kg-8sce d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Female m:mean_scale_score=667 m:pct_level_1=8.8 m:pct_level_2=23.8 m:pct_level_3=63 m:num_level_3_and_4=291 m:pct_level_4=4.4 m:num_level_1=38 m:number_tested=432 m:num_level_2=103 m:pct_level_3_and_4=67.4 m:num_level_4=19 m:num_level_3=272

series e:49kg-8sce d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Male m:mean_scale_score=658 m:pct_level_1=13.3 m:pct_level_2=29.9 m:pct_level_3=50.7 m:num_level_3_and_4=213 m:pct_level_4=6.1 m:num_level_1=50 m:number_tested=375 m:num_level_2=112 m:pct_level_3_and_4=56.8 m:num_level_4=23 m:num_level_3=190

series e:49kg-8sce d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Female m:mean_scale_score=665 m:pct_level_1=6.2 m:pct_level_2=29.2 m:pct_level_3=56.6 m:num_level_3_and_4=259 m:pct_level_4=8 m:num_level_1=25 m:number_tested=401 m:num_level_2=117 m:pct_level_3_and_4=64.6 m:num_level_4=32 m:num_level_3=227
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

entity e:49kg-8sce l:"English Language Arts (ELA) Test Results 2006-2012 - District - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/49kg-8sce

property e:49kg-8sce t:meta.view v:id=49kg-8sce v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/D8B559C6-A588-44B6-AECE-1108BE52BE9F/0/DistrictELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - District - Gender" v:attribution="Department of Education (DOE)"

property e:49kg-8sce t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:49kg-8sce t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | Female      | 432           | 667              | 38          | 8.8         | 103         | 23.8        | 272         | 63          | 19          | 4.4         | 291               | 67.4              | 
| 1        | 3     | 2006 | Male        | 375           | 658              | 50          | 13.3        | 112         | 29.9        | 190         | 50.7        | 23          | 6.1         | 213               | 56.8              | 
| 1        | 3     | 2007 | Female      | 401           | 665              | 25          | 6.2         | 117         | 29.2        | 227         | 56.6        | 32          | 8           | 259               | 64.6              | 
| 1        | 3     | 2007 | Male        | 410           | 655              | 66          | 16.1        | 117         | 28.5        | 197         | 48          | 30          | 7.3         | 227               | 55.4              | 
| 1        | 3     | 2008 | Female      | 398           | 666              | 26          | 6.5         | 107         | 26.9        | 221         | 55.5        | 44          | 11.1        | 265               | 66.6              | 
| 1        | 3     | 2008 | Male        | 436           | 660              | 28          | 6.4         | 155         | 35.6        | 224         | 51.4        | 29          | 6.7         | 253               | 58                | 
| 1        | 3     | 2009 | Female      | 445           | 673              | 11          | 2.5         | 89          | 20          | 290         | 65.2        | 55          | 12.4        | 345               | 77.5              | 
| 1        | 3     | 2009 | Male        | 435           | 661              | 32          | 7.4         | 124         | 28.5        | 252         | 57.9        | 27          | 6.2         | 279               | 64.1              | 
| 1        | 3     | 2010 | Female      | 410           | 672              | 56          | 13.7        | 128         | 31.2        | 138         | 33.7        | 88          | 21.5        | 226               | 55.1              | 
| 1        | 3     | 2010 | Male        | 438           | 666              | 81          | 18.5        | 148         | 33.8        | 134         | 30.6        | 75          | 17.1        | 209               | 47.7              | 
```