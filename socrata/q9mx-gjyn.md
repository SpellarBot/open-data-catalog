# Math Test Results 2006-2012 - Borough - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/math-test-results-2006-2012-borough-gender-332aa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q9mx-gjyn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q9mx-gjyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q9mx-gjyn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q9mx-gjyn |
| Name | Math Test Results 2006-2012 - Borough - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | math test result, grade, borough, gender, lifelong learning |
| Created | 2013-02-21T02:42:28Z |
| Publication Date | 2013-02-21T02:43:25Z |

## Description

Latest available data and trends in the state assessment results of math for grades 3 through 8. Data are disaggregated by borough and gender.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | borough           | Borough           | text      | text        |
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
series e:q9mx-gjyn d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Female m:mean_scale_score=664 m:pct_level_1=11.4 m:pct_level_2=20.5 m:pct_level_3=53 m:num_level_3_and_4=5438 m:pct_level_4=15.1 m:num_level_1=911 m:number_tested=7984 m:num_level_2=1635 m:pct_level_3_and_4=68.1 m:num_level_4=1206 m:num_level_3=4232

series e:q9mx-gjyn d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Male m:mean_scale_score=663 m:pct_level_1=13.6 m:pct_level_2=19.2 m:pct_level_3=51.8 m:num_level_3_and_4=5688 m:pct_level_4=15.4 m:num_level_1=1151 m:number_tested=8461 m:num_level_2=1622 m:pct_level_3_and_4=67.2 m:num_level_4=1302 m:num_level_3=4386

series e:q9mx-gjyn d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=Female m:mean_scale_score=675 m:pct_level_1=6.2 m:pct_level_2=16.6 m:pct_level_3=56.5 m:num_level_3_and_4=6023 m:pct_level_4=20.7 m:num_level_1=484 m:number_tested=7803 m:num_level_2=1296 m:pct_level_3_and_4=77.2 m:num_level_4=1613 m:num_level_3=4410
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

entity e:q9mx-gjyn l:"Math Test Results 2006-2012 - Borough - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/q9mx-gjyn

property e:q9mx-gjyn t:meta.view v:id=q9mx-gjyn v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/9EE3AC39-71D5-4619-9F99-A850842F68DE/0/BoroughMathResults20062012Public.xlsx v:averageRating=0 v:name="Math Test Results 2006-2012 - Borough - Gender" v:attribution="Department of Education (DOE)"

property e:q9mx-gjyn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q9mx-gjyn t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | Female      | 7984          | 664              | 911         | 11.4        | 1635        | 20.5        | 4232        | 53          | 1206        | 15.1        | 5438              | 68.1              | 
| BRONX   | 3     | 2006 | Male        | 8461          | 663              | 1151        | 13.6        | 1622        | 19.2        | 4386        | 51.8        | 1302        | 15.4        | 5688              | 67.2              | 
| BRONX   | 3     | 2007 | Female      | 7803          | 675              | 484         | 6.2         | 1296        | 16.6        | 4410        | 56.5        | 1613        | 20.7        | 6023              | 77.2              | 
| BRONX   | 3     | 2007 | Male        | 8386          | 673              | 761         | 9.1         | 1344        | 16          | 4586        | 54.7        | 1695        | 20.2        | 6281              | 74.9              | 
| BRONX   | 3     | 2008 | Female      | 7556          | 678              | 249         | 3.3         | 958         | 12.7        | 5123        | 67.8        | 1226        | 16.2        | 6349              | 84                | 
| BRONX   | 3     | 2008 | Male        | 8080          | 676              | 421         | 5.2         | 1103        | 13.7        | 5324        | 65.9        | 1232        | 15.2        | 6556              | 81.1              | 
| BRONX   | 3     | 2009 | Female      | 7659          | 683              | 84          | 1.1         | 683         | 8.9         | 5519        | 72.1        | 1373        | 17.9        | 6892              | 90                | 
| BRONX   | 3     | 2009 | Male        | 8150          | 680              | 174         | 2.1         | 883         | 10.8        | 5776        | 70.9        | 1317        | 16.2        | 7093              | 87                | 
| BRONX   | 3     | 2010 | Female      | 7653          | 683              | 1200        | 15.7        | 3109        | 40.6        | 2274        | 29.7        | 1070        | 14          | 3344              | 43.7              | 
| BRONX   | 3     | 2010 | Male        | 8213          | 683              | 1438        | 17.5        | 3228        | 39.3        | 2355        | 28.7        | 1192        | 14.5        | 3547              | 43.2              | 
```