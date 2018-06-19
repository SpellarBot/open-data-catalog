# English Language Arts (ELA) Test Results 2006-2012 - Citywide - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-citywide-all-students-3e502) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/89di-hi4s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/89di-hi4s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/89di-hi4s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 89di-hi4s |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Citywide - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, citywide, lifelong learning |
| Created | 2013-02-20T22:02:59Z |
| Publication Date | 2013-02-20T22:03:09Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8.

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
series e:89di-hi4s d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=661 m:pct_level_1=11.9 m:pct_level_2=26.6 m:pct_level_3=56.3 m:num_level_3_and_4=37794 m:pct_level_4=5.2 m:num_level_1=7331 m:number_tested=61478 m:num_level_2=16353 m:pct_level_3_and_4=61.5 m:num_level_4=3179 m:num_level_3=34615

series e:89di-hi4s d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=656 m:pct_level_1=13 m:pct_level_2=30.6 m:pct_level_3=50.2 m:num_level_3_and_4=40070 m:pct_level_4=6.2 m:num_level_1=9249 m:number_tested=71045 m:num_level_2=21735 m:pct_level_3_and_4=56.4 m:num_level_4=4375 m:num_level_3=35695

series e:89di-hi4s d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic="All Students" m:mean_scale_score=659 m:pct_level_1=8.9 m:pct_level_2=31.2 m:pct_level_3=51.9 m:num_level_3_and_4=41248 m:pct_level_4=8 m:num_level_1=6131 m:number_tested=68883 m:num_level_2=21504 m:pct_level_3_and_4=59.9 m:num_level_4=5532 m:num_level_3=35716
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

entity e:89di-hi4s l:"English Language Arts (ELA) Test Results 2006-2012 - Citywide - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/89di-hi4s

property e:89di-hi4s t:meta.view v:id=89di-hi4s v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Citywide - All Students" v:attribution="Department of Education (DOE)"

property e:89di-hi4s t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:89di-hi4s t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | All Students | 61478         | 661              | 7331        | 11.9        | 16353       | 26.6        | 34615       | 56.3        | 3179        | 5.2         | 37794             | 61.5              | 
| 3     | 2007 | All Students | 71045         | 656              | 9249        | 13          | 21735       | 30.6        | 35695       | 50.2        | 4375        | 6.2         | 40070             | 56.4              | 
| 3     | 2008 | All Students | 68883         | 659              | 6131        | 8.9         | 21504       | 31.2        | 35716       | 51.9        | 5532        | 8           | 41248             | 59.9              | 
| 3     | 2009 | All Students | 70074         | 664              | 4546        | 6.5         | 16906       | 24.1        | 43067       | 61.5        | 5555        | 7.9         | 48622             | 69.4              | 
| 3     | 2010 | All Students | 69629         | 663              | 12632       | 18.1        | 24590       | 35.3        | 23389       | 33.6        | 9018        | 13          | 32407             | 46.5              | 
| 3     | 2011 | All Students | 71060         | 660              | 11353       | 16          | 25520       | 35.9        | 31807       | 44.8        | 2380        | 3.3         | 34187             | 48.1              | 
| 3     | 2012 | All Students | 71861         | 661              | 11871       | 16.5        | 24810       | 34.5        | 31198       | 43.4        | 3982        | 5.5         | 35180             | 49                | 
| 4     | 2006 | All Students | 64467         | 657              | 7602        | 11.8        | 18876       | 29.3        | 34196       | 53          | 3793        | 5.9         | 37989             | 58.9              | 
| 4     | 2007 | All Students | 69933         | 654              | 8073        | 11.5        | 22693       | 32.4        | 35724       | 51.1        | 3453        | 4.9         | 39177             | 56                | 
| 4     | 2008 | All Students | 69364         | 657              | 7306        | 10.5        | 19545       | 28.2        | 38517       | 55.5        | 3996        | 5.8         | 42513             | 61.3              | 
```