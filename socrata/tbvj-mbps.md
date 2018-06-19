# English Language Arts (ELA) Test Results 2006-2012 - District - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-district-ell-97246) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tbvj-mbps) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tbvj-mbps/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tbvj-mbps/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tbvj-mbps |
| Name | English Language Arts (ELA) Test Results 2006-2012 - District - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, district, lifelong learning |
| Created | 2013-02-20T22:04:16Z |
| Publication Date | 2013-02-20T22:04:41Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by district and ELL status.

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
series e:tbvj-mbps d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=ELL m:mean_scale_score=660 m:pct_level_1=15 m:pct_level_2=25 m:pct_level_3=53.3 m:num_level_3_and_4=36 m:pct_level_4=6.7 m:num_level_1=9 m:number_tested=60 m:num_level_2=15 m:pct_level_3_and_4=60 m:num_level_4=4 m:num_level_3=32

series e:tbvj-mbps d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=EP m:mean_scale_score=663 m:pct_level_1=10.6 m:pct_level_2=26.8 m:pct_level_3=57.6 m:num_level_3_and_4=468 m:pct_level_4=5.1 m:num_level_1=79 m:number_tested=747 m:num_level_2=200 m:pct_level_3_and_4=62.7 m:num_level_4=38 m:num_level_3=430

series e:tbvj-mbps d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=ELL m:mean_scale_score=643 m:pct_level_1=17.1 m:pct_level_2=41.9 m:pct_level_3=41.1 m:num_level_3_and_4=53 m:pct_level_4=0 m:num_level_1=22 m:number_tested=129 m:num_level_2=54 m:pct_level_3_and_4=41.1 m:num_level_4=0 m:num_level_3=53
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

entity e:tbvj-mbps l:"English Language Arts (ELA) Test Results 2006-2012 - District - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/tbvj-mbps

property e:tbvj-mbps t:meta.view v:id=tbvj-mbps v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/D8B559C6-A588-44B6-AECE-1108BE52BE9F/0/DistrictELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - District - ELL" v:attribution="Department of Education (DOE)"

property e:tbvj-mbps t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tbvj-mbps t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | ELL         | 60            | 660              | 9           | 15          | 15          | 25          | 32          | 53.3        | 4           | 6.7         | 36                | 60                | 
| 1        | 3     | 2006 | EP          | 747           | 663              | 79          | 10.6        | 200         | 26.8        | 430         | 57.6        | 38          | 5.1         | 468               | 62.7              | 
| 1        | 3     | 2007 | ELL         | 129           | 643              | 22          | 17.1        | 54          | 41.9        | 53          | 41.1        | 0           | 0           | 53                | 41.1              | 
| 1        | 3     | 2007 | EP          | 682           | 663              | 69          | 10.1        | 180         | 26.4        | 371         | 54.4        | 62          | 9.1         | 433               | 63.5              | 
| 1        | 3     | 2008 | ELL         | 111           | 646              | 11          | 9.9         | 49          | 44.1        | 51          | 45.9        | 0           | 0           | 51                | 45.9              | 
| 1        | 3     | 2008 | EP          | 723           | 665              | 43          | 5.9         | 213         | 29.5        | 394         | 54.5        | 73          | 10.1        | 467               | 64.6              | 
| 1        | 3     | 2009 | ELL         | 89            | 648              | 6           | 6.7         | 40          | 44.9        | 42          | 47.2        | 1           | 1.1         | 43                | 48.3              | 
| 1        | 3     | 2009 | EP          | 791           | 669              | 37          | 4.7         | 173         | 21.9        | 500         | 63.2        | 81          | 10.2        | 581               | 73.5              | 
| 1        | 3     | 2010 | ELL         | 78            | 641              | 34          | 43.6        | 36          | 46.2        | 8           | 10.3        | 0           | 0           | 8                 | 10.3              | 
| 1        | 3     | 2010 | EP          | 770           | 671              | 103         | 13.4        | 240         | 31.2        | 264         | 34.3        | 163         | 21.2        | 427               | 55.5              | 
```