# Math Test Results 2006-2012 - District - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-district-gender-0a12a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qphc-zrtc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qphc-zrtc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qphc-zrtc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qphc-zrtc |
| Name | Math Test Results 2006-2012 - District - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, district, gender, lifelong learning |
| Created | 2013-02-21T02:46:19Z |
| Publication Date | 2013-02-21T02:46:41Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by district and gender.

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
series e:qphc-zrtc d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Female m:mean_scale_score=675 m:pct_level_1=6.9 m:pct_level_2=19.4 m:pct_level_3=50.8 m:num_level_3_and_4=366 m:pct_level_4=23 m:num_level_1=34 m:number_tested=496 m:num_level_2=96 m:pct_level_3_and_4=73.8 m:num_level_4=114 m:num_level_3=252

series e:qphc-zrtc d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Male m:mean_scale_score=672 m:pct_level_1=8.8 m:pct_level_2=16.8 m:pct_level_3=52.6 m:num_level_3_and_4=328 m:pct_level_4=21.8 m:num_level_1=39 m:number_tested=441 m:num_level_2=74 m:pct_level_3_and_4=74.4 m:num_level_4=96 m:num_level_3=232

series e:qphc-zrtc d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic=Female m:mean_scale_score=681 m:pct_level_1=5.7 m:pct_level_2=8.6 m:pct_level_3=61.1 m:num_level_3_and_4=348 m:pct_level_4=24.6 m:num_level_1=23 m:number_tested=406 m:num_level_2=35 m:pct_level_3_and_4=85.7 m:num_level_4=100 m:num_level_3=248
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

entity e:qphc-zrtc l:"Math Test Results 2006-2012 - District - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qphc-zrtc

property e:qphc-zrtc t:meta.view v:id=qphc-zrtc v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/3E439D63-A14E-4B6E-B019-B634A8915D71/0/DistrictMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - District - Gender" v:attribution="Department of Education (DOE)"

property e:qphc-zrtc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qphc-zrtc t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | Female      | 496           | 675              | 34          | 6.9         | 96          | 19.4        | 252         | 50.8        | 114         | 23          | 366               | 73.8              | 
| 1        | 3     | 2006 | Male        | 441           | 672              | 39          | 8.8         | 74          | 16.8        | 232         | 52.6        | 96          | 21.8        | 328               | 74.4              | 
| 1        | 3     | 2007 | Female      | 406           | 681              | 23          | 5.7         | 35          | 8.6         | 248         | 61.1        | 100         | 24.6        | 348               | 85.7              | 
| 1        | 3     | 2007 | Male        | 413           | 678              | 24          | 5.8         | 49          | 11.9        | 250         | 60.5        | 90          | 21.8        | 340               | 82.3              | 
| 1        | 3     | 2008 | Female      | 407           | 686              | 8           | 2           | 42          | 10.3        | 256         | 62.9        | 101         | 24.8        | 357               | 87.7              | 
| 1        | 3     | 2008 | Male        | 437           | 687              | 8           | 1.8         | 47          | 10.8        | 271         | 62          | 111         | 25.4        | 382               | 87.4              | 
| 1        | 3     | 2009 | Female      | 447           | 694              | 3           | 0.7         | 24          | 5.4         | 290         | 64.9        | 130         | 29.1        | 420               | 94                | 
| 1        | 3     | 2009 | Male        | 445           | 688              | 5           | 1.1         | 39          | 8.8         | 292         | 65.6        | 109         | 24.5        | 401               | 90.1              | 
| 1        | 3     | 2010 | Female      | 417           | 698              | 36          | 8.6         | 129         | 30.9        | 135         | 32.4        | 117         | 28.1        | 252               | 60.4              | 
| 1        | 3     | 2010 | Male        | 449           | 695              | 53          | 11.8        | 128         | 28.5        | 144         | 32.1        | 124         | 27.6        | 268               | 59.7              | 
```