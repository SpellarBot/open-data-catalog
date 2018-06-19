# Math Test Results 2006-2012 - Citywide - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-citywide-all-students-94989) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fxwm-3t4n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fxwm-3t4n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fxwm-3t4n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fxwm-3t4n |
| Name | Math Test Results 2006-2012 - Citywide - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, citywide, all student, lifelong learning |
| Created | 2013-02-21T02:43:59Z |
| Publication Date | 2013-02-21T02:44:09Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8.

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
series e:fxwm-3t4n d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=674 m:pct_level_1=9.1 m:pct_level_2=15.6 m:pct_level_3=50.8 m:num_level_3_and_4=55268 m:pct_level_4=24.4 m:num_level_1=6714 m:number_tested=73413 m:num_level_2=11431 m:pct_level_3_and_4=75.3 m:num_level_4=17938 m:num_level_3=37330

series e:fxwm-3t4n d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=683 m:pct_level_1=5.4 m:pct_level_2=12.4 m:pct_level_3=52.8 m:num_level_3_and_4=59371 m:pct_level_4=29.4 m:num_level_1=3907 m:number_tested=72196 m:num_level_2=8918 m:pct_level_3_and_4=82.2 m:num_level_4=21254 m:num_level_3=38117

series e:fxwm-3t4n d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=685 m:pct_level_1=3.1 m:pct_level_2=9.8 m:pct_level_3=63.3 m:num_level_3_and_4=61065 m:pct_level_4=23.8 m:num_level_1=2143 m:number_tested=70062 m:num_level_2=6854 m:pct_level_3_and_4=87.2 m:num_level_4=16695 m:num_level_3=44370
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

entity e:fxwm-3t4n l:"Math Test Results 2006-2012 - Citywide - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/fxwm-3t4n

property e:fxwm-3t4n t:meta.view v:id=fxwm-3t4n v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Citywide - All Students" v:attribution="Department of Education (DOE)"

property e:fxwm-3t4n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fxwm-3t4n t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | All Students | 73413         | 674              | 6714        | 9.1         | 11431       | 15.6        | 37330       | 50.8        | 17938       | 24.4        | 55268             | 75.3              | 
| 3     | 2007 | All Students | 72196         | 683              | 3907        | 5.4         | 8918        | 12.4        | 38117       | 52.8        | 21254       | 29.4        | 59371             | 82.2              | 
| 3     | 2008 | All Students | 70062         | 685              | 2143        | 3.1         | 6854        | 9.8         | 44370       | 63.3        | 16695       | 23.8        | 61065             | 87.2              | 
| 3     | 2009 | All Students | 71376         | 689              | 922         | 1.3         | 5196        | 7.3         | 47401       | 66.4        | 17857       | 25          | 65258             | 91.4              | 
| 3     | 2010 | All Students | 71351         | 690              | 8555        | 12          | 24086       | 33.8        | 22957       | 32.2        | 15753       | 22.1        | 38710             | 54.3              | 
| 3     | 2011 | All Students | 72477         | 685              | 8151        | 11.2        | 24613       | 34          | 30955       | 42.7        | 8758        | 12.1        | 39713             | 54.8              | 
| 3     | 2012 | All Students | 73198         | 686              | 8063        | 11          | 23396       | 32          | 32661       | 44.6        | 9078        | 12.4        | 41739             | 57                | 
| 4     | 2006 | All Students | 72501         | 669              | 7455        | 10.3        | 13668       | 18.9        | 35614       | 49.1        | 15764       | 21.7        | 51378             | 70.9              | 
| 4     | 2007 | All Students | 71199         | 675              | 5765        | 8.1         | 12683       | 17.8        | 35724       | 50.2        | 17027       | 23.9        | 52751             | 74.1              | 
| 4     | 2008 | All Students | 70606         | 679              | 4417        | 6.3         | 9953        | 14.1        | 37719       | 53.4        | 18517       | 26.2        | 56236             | 79.6              | 
```