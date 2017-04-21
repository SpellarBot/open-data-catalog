# Math Test Results 2006-2012 - District - All Students

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-district-all-students-89ba3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7yig-nj52) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7yig-nj52/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7yig-nj52/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7yig-nj52 |
| Name | Math Test Results 2006-2012 - District - All Students |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, district, all student, lifelong learning |
| Created | 2013-02-21T02:45:01Z |
| Publication Date | 2013-02-21T02:45:18Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by district.

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
series e:7yig-nj52 d:2006-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=673 m:pct_level_1=7.8 m:pct_level_2=18.2 m:pct_level_3=51.7 m:num_level_3_and_4=693 m:pct_level_4=22.3 m:num_level_1=73 m:number_tested=936 m:num_level_2=170 m:pct_level_3_and_4=74 m:num_level_4=209 m:num_level_3=484

series e:7yig-nj52 d:2007-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=679 m:pct_level_1=5.7 m:pct_level_2=10.3 m:pct_level_3=61.1 m:num_level_3_and_4=702 m:pct_level_4=22.8 m:num_level_1=48 m:number_tested=836 m:num_level_2=86 m:pct_level_3_and_4=84 m:num_level_4=191 m:num_level_3=511

series e:7yig-nj52 d:2008-01-01T00:00:00.000Z t:grade=3 t:district=1 t:demographic="All Students" m:mean_scale_score=686 m:pct_level_1=2 m:pct_level_2=10.9 m:pct_level_3=62.3 m:num_level_3_and_4=751 m:pct_level_4=24.8 m:num_level_1=17 m:number_tested=862 m:num_level_2=94 m:pct_level_3_and_4=87.1 m:num_level_4=214 m:num_level_3=537
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

entity e:7yig-nj52 l:"Math Test Results 2006-2012 - District - All Students" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/7yig-nj52

property e:7yig-nj52 t:meta.view v:id=7yig-nj52 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/3E439D63-A14E-4B6E-B019-B634A8915D71/0/DistrictMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - District - All Students" v:attribution="Department of Education (DOE)"

property e:7yig-nj52 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7yig-nj52 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic  | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | ============ | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | All Students | 936           | 673              | 73          | 7.8         | 170         | 18.2        | 484         | 51.7        | 209         | 22.3        | 693               | 74                | 
| 1        | 3     | 2007 | All Students | 836           | 679              | 48          | 5.7         | 86          | 10.3        | 511         | 61.1        | 191         | 22.8        | 702               | 84                | 
| 1        | 3     | 2008 | All Students | 862           | 686              | 17          | 2           | 94          | 10.9        | 537         | 62.3        | 214         | 24.8        | 751               | 87.1              | 
| 1        | 3     | 2009 | All Students | 914           | 691              | 8           | 0.9         | 66          | 7.2         | 598         | 65.4        | 242         | 26.5        | 840               | 91.9              | 
| 1        | 3     | 2010 | All Students | 866           | 697              | 89          | 10.3        | 257         | 29.7        | 279         | 32.2        | 241         | 27.8        | 520               | 60                | 
| 1        | 3     | 2011 | All Students | 826           | 689              | 78          | 9.4         | 247         | 29.9        | 319         | 38.6        | 182         | 22          | 501               | 60.7              | 
| 1        | 3     | 2012 | All Students | 861           | 690              | 70          | 8.1         | 270         | 31.4        | 371         | 43.1        | 150         | 17.4        | 521               | 60.5              | 
| 1        | 4     | 2006 | All Students | 895           | 670              | 80          | 8.9         | 188         | 21          | 422         | 47.2        | 205         | 22.9        | 627               | 70.1              | 
| 1        | 4     | 2007 | All Students | 868           | 673              | 68          | 7.8         | 167         | 19.2        | 440         | 50.7        | 193         | 22.2        | 633               | 72.9              | 
| 1        | 4     | 2008 | All Students | 848           | 677              | 44          | 5.2         | 149         | 17.6        | 454         | 53.5        | 201         | 23.7        | 655               | 77.2              | 
```