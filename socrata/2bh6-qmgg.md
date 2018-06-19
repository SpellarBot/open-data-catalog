# Math Test Results 2006-2012 - Citywide - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-citywide-gender-d9147) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2bh6-qmgg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2bh6-qmgg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2bh6-qmgg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2bh6-qmgg |
| Name | Math Test Results 2006-2012 - Citywide - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, citywide, gender, lifelong learning |
| Created | 2013-02-21T02:44:34Z |
| Publication Date | 2013-02-21T02:44:48Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by gender.

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
series e:2bh6-qmgg d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=675 m:pct_level_1=8.2 m:pct_level_2=15.7 m:pct_level_3=51.1 m:num_level_3_and_4=27134 m:pct_level_4=25 m:num_level_1=2908 m:number_tested=35655 m:num_level_2=5613 m:pct_level_3_and_4=76.1 m:num_level_4=8912 m:num_level_3=18222

series e:2bh6-qmgg d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=685 m:pct_level_1=4.5 m:pct_level_2=12.3 m:pct_level_3=52.6 m:num_level_3_and_4=29294 m:pct_level_4=30.5 m:num_level_1=1602 m:number_tested=35240 m:num_level_2=4344 m:pct_level_3_and_4=83.1 m:num_level_4=10742 m:num_level_3=18552

series e:2bh6-qmgg d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic=Female m:mean_scale_score=686 m:pct_level_1=2.4 m:pct_level_2=9.1 m:pct_level_3=64.1 m:num_level_3_and_4=30039 m:pct_level_4=24.4 m:num_level_1=807 m:number_tested=33950 m:num_level_2=3104 m:pct_level_3_and_4=88.5 m:num_level_4=8282 m:num_level_3=21757
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

entity e:2bh6-qmgg l:"Math Test Results 2006-2012 - Citywide - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/2bh6-qmgg

property e:2bh6-qmgg t:meta.view v:id=2bh6-qmgg v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Citywide - Gender" v:attribution="Department of Education (DOE)"

property e:2bh6-qmgg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2bh6-qmgg t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | Female      | 35655         | 675              | 2908        | 8.2         | 5613        | 15.7        | 18222       | 51.1        | 8912        | 25          | 27134             | 76.1              | 
| 3     | 2007 | Female      | 35240         | 685              | 1602        | 4.5         | 4344        | 12.3        | 18552       | 52.6        | 10742       | 30.5        | 29294             | 83.1              | 
| 3     | 2008 | Female      | 33950         | 686              | 807         | 2.4         | 3104        | 9.1         | 21757       | 64.1        | 8282        | 24.4        | 30039             | 88.5              | 
| 3     | 2009 | Female      | 34802         | 691              | 314         | 0.9         | 2310        | 6.6         | 23026       | 66.2        | 9152        | 26.3        | 32178             | 92.5              | 
| 3     | 2010 | Female      | 34588         | 691              | 3814        | 11          | 11905       | 34.4        | 11189       | 32.3        | 7680        | 22.2        | 18869             | 54.6              | 
| 3     | 2011 | Female      | 35432         | 685              | 3721        | 10.5        | 12252       | 34.6        | 15354       | 43.3        | 4105        | 11.6        | 19459             | 54.9              | 
| 3     | 2012 | Female      | 35621         | 687              | 3550        | 10          | 11595       | 32.6        | 16125       | 45.3        | 4351        | 12.2        | 20476             | 57.5              | 
| 4     | 2006 | Female      | 35287         | 670              | 3283        | 9.3         | 7069        | 20          | 17500       | 49.6        | 7435        | 21.1        | 24935             | 70.7              | 
| 4     | 2007 | Female      | 34602         | 675              | 2476        | 7.2         | 6453        | 18.6        | 17668       | 51.1        | 8005        | 23.1        | 25673             | 74.2              | 
| 4     | 2008 | Female      | 34592         | 679              | 1865        | 5.4         | 4910        | 14.2        | 18870       | 54.6        | 8947        | 25.9        | 27817             | 80.4              | 
```