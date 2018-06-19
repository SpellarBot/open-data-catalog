# Math Test Results 2006-2012 - Citywide - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-citywide-swd-318e1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ufu7-zp25) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ufu7-zp25/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ufu7-zp25/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ufu7-zp25 |
| Name | Math Test Results 2006-2012 - Citywide - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, citywide, swd, lifelong learning |
| Created | 2013-02-21T02:44:49Z |
| Publication Date | 2013-02-21T02:45:00Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by disability status.

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
series e:ufu7-zp25 d:2006-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=680 m:pct_level_1=5.5 m:pct_level_2=13.7 m:pct_level_3=53.1 m:num_level_3_and_4=50138 m:pct_level_4=27.7 m:num_level_1=3419 m:number_tested=62092 m:num_level_2=8535 m:pct_level_3_and_4=80.7 m:num_level_4=17192 m:num_level_3=32946

series e:ufu7-zp25 d:2007-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=689 m:pct_level_1=2.7 m:pct_level_2=9.8 m:pct_level_3=54.1 m:num_level_3_and_4=52977 m:pct_level_4=33.4 m:num_level_1=1631 m:number_tested=60525 m:num_level_2=5917 m:pct_level_3_and_4=87.5 m:num_level_4=20219 m:num_level_3=32758

series e:ufu7-zp25 d:2008-01-01T00:00:00.000Z t:grade=3 t:demographic="Not SWD" m:mean_scale_score=690 m:pct_level_1=1.3 m:pct_level_2=7 m:pct_level_3=64.5 m:num_level_3_and_4=53513 m:pct_level_4=27.1 m:num_level_1=757 m:number_tested=58364 m:num_level_2=4094 m:pct_level_3_and_4=91.7 m:num_level_4=15841 m:num_level_3=37672
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

entity e:ufu7-zp25 l:"Math Test Results 2006-2012 - Citywide - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ufu7-zp25

property e:ufu7-zp25 t:meta.view v:id=ufu7-zp25 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7C17840D-BB62-41C9-919D-AACABAA92E04/0/CitywideMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Citywide - SWD" v:attribution="Department of Education (DOE)"

property e:ufu7-zp25 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ufu7-zp25 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 3     | 2006 | Not SWD     | 62092         | 680              | 3419        | 5.5         | 8535        | 13.7        | 32946       | 53.1        | 17192       | 27.7        | 50138             | 80.7              | 
| 3     | 2007 | Not SWD     | 60525         | 689              | 1631        | 2.7         | 5917        | 9.8         | 32758       | 54.1        | 20219       | 33.4        | 52977             | 87.5              | 
| 3     | 2008 | Not SWD     | 58364         | 690              | 757         | 1.3         | 4094        | 7           | 37672       | 64.5        | 15841       | 27.1        | 53513             | 91.7              | 
| 3     | 2009 | Not SWD     | 59155         | 694              | 301         | 0.5         | 2620        | 4.4         | 39383       | 66.6        | 16851       | 28.5        | 56234             | 95.1              | 
| 3     | 2010 | Not SWD     | 58565         | 694              | 4619        | 7.9         | 18859       | 32.2        | 20295       | 34.7        | 14792       | 25.3        | 35087             | 59.9              | 
| 3     | 2011 | Not SWD     | 59507         | 687              | 4596        | 7.7         | 19119       | 32.1        | 27532       | 46.3        | 8260        | 13.9        | 35792             | 60.1              | 
| 3     | 2012 | Not SWD     | 59839         | 689              | 4477        | 7.5         | 17856       | 29.8        | 28911       | 48.3        | 8595        | 14.4        | 37506             | 62.7              | 
| 4     | 2006 | Not SWD     | 60736         | 677              | 3421        | 5.6         | 10388       | 17.1        | 31706       | 52.2        | 15221       | 25.1        | 46927             | 77.3              | 
| 4     | 2007 | Not SWD     | 58906         | 681              | 2369        | 4           | 9037        | 15.3        | 31165       | 52.9        | 16335       | 27.7        | 47500             | 80.6              | 
| 4     | 2008 | Not SWD     | 57984         | 685              | 1662        | 2.9         | 6531        | 11.3        | 32111       | 55.4        | 17680       | 30.5        | 49791             | 85.9              | 
```