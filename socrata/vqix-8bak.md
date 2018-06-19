# English Language Arts (ELA) Test Results 2006-2012 - District - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-district-ethnicity-2bf71) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vqix-8bak) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vqix-8bak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vqix-8bak/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vqix-8bak |
| Name | English Language Arts (ELA) Test Results 2006-2012 - District - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, district, lifelong learning |
| Created | 2013-02-20T22:04:42Z |
| Publication Date | 2013-02-20T22:05:31Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by district and student ethnicity.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | district          | District          | text      | text        |
| Yes      | series tag     | grade             | Grade             | text      | text        |
| Yes      | time           | year              | Year              | number    | text        |
| Yes      | series tag     | demographic       | Demographic       | text      | text        |
| Yes      | numeric metric | number_tested     | Number Tested     | number    | text        |
| Yes      | series tag     | mean_scale_score  | Mean Scale Score  | text      | text        |
| Yes      | series tag     | num_level_1       | Num Level 1       | text      | text        |
| Yes      | series tag     | pct_level_1       | Pct Level 1       | text      | text        |
| Yes      | series tag     | num_level_2       | Num Level 2       | text      | text        |
| Yes      | series tag     | pct_level_2       | Pct Level 2       | text      | text        |
| Yes      | series tag     | num_level_3       | Num Level 3       | text      | text        |
| Yes      | series tag     | pct_level_3       | Pct Level 3       | text      | text        |
| Yes      | series tag     | num_level_4       | Num Level 4       | text      | text        |
| Yes      | series tag     | pct_level_4       | Pct Level 4       | text      | text        |
| Yes      | series tag     | num_level_3_and_4 | Num Level 3 and 4 | text      | text        |
| Yes      | series tag     | pct_level_3_and_4 | Pct Level 3 and 4 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vqix-8bak d:2006-01-01T00:00:00.000Z t:mean_scale_score=690 t:pct_level_1=1.8 t:pct_level_2=12.3 t:pct_level_3=71.1 t:pct_level_4=14.9 t:demographic=Asian t:num_level_1=2 t:num_level_2=14 t:pct_level_3_and_4=86 t:num_level_3=81 t:grade=3 t:num_level_3_and_4=98 t:district=1 t:num_level_4=17 m:number_tested=114

series e:vqix-8bak d:2006-01-01T00:00:00.000Z t:mean_scale_score=649 t:pct_level_1=14.3 t:pct_level_2=33.7 t:pct_level_3=51.4 t:pct_level_4=0.6 t:demographic=Black t:num_level_1=25 t:num_level_2=59 t:pct_level_3_and_4=52 t:num_level_3=90 t:grade=3 t:num_level_3_and_4=91 t:district=1 t:num_level_4=1 m:number_tested=175

series e:vqix-8bak d:2006-01-01T00:00:00.000Z t:mean_scale_score=654 t:pct_level_1=13.6 t:pct_level_2=31.9 t:pct_level_3=52.9 t:pct_level_4=1.7 t:demographic=Hispanic t:num_level_1=57 t:num_level_2=134 t:pct_level_3_and_4=54.5 t:num_level_3=222 t:grade=3 t:num_level_3_and_4=229 t:district=1 t:num_level_4=7 m:number_tested=420
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

entity e:vqix-8bak l:"English Language Arts (ELA) Test Results 2006-2012 - District - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vqix-8bak

property e:vqix-8bak t:meta.view v:id=vqix-8bak v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/D8B559C6-A588-44B6-AECE-1108BE52BE9F/0/DistrictELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - District - Ethnicity" v:attribution="Department of Education (DOE)"

property e:vqix-8bak t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vqix-8bak t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| district | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======== | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| 1        | 3     | 2006 | Asian       | 114           | 690              | 2           | 1.8         | 14          | 12.3        | 81          | 71.1        | 17          | 14.9        | 98                | 86                | 
| 1        | 3     | 2006 | Black       | 175           | 649              | 25          | 14.3        | 59          | 33.7        | 90          | 51.4        | 1           | 0.6         | 91                | 52                | 
| 1        | 3     | 2006 | Hispanic    | 420           | 654              | 57          | 13.6        | 134         | 31.9        | 222         | 52.9        | 7           | 1.7         | 229               | 54.5              | 
| 1        | 3     | 2006 | White       | 92            | 699              | 2           | 2.2         | 6           | 6.5         | 67          | 72.8        | 17          | 18.5        | 84                | 91.3              | 
| 1        | 3     | 2007 | Asian       | 127           | 674              | 7           | 5.5         | 22          | 17.3        | 87          | 68.5        | 11          | 8.7         | 98                | 77.2              | 
| 1        | 3     | 2007 | Black       | 153           | 646              | 25          | 16.3        | 57          | 37.3        | 64          | 41.8        | 7           | 4.6         | 71                | 46.4              | 
| 1        | 3     | 2007 | Hispanic    | 438           | 652              | 57          | 13          | 151         | 34.5        | 216         | 49.3        | 14          | 3.2         | 230               | 52.5              | 
| 1        | 3     | 2007 | White       | 86            | 704              | 1           | 1.2         | 3           | 3.5         | 53          | 61.6        | 29          | 33.7        | 82                | 95.3              | 
| 1        | 3     | 2008 | Asian       | 130           | 681              | 1           | 0.8         | 20          | 15.4        | 89          | 68.5        | 20          | 15.4        | 109               | 83.8              | 
| 1        | 3     | 2008 | Black       | 154           | 652              | 18          | 11.7        | 58          | 37.7        | 72          | 46.8        | 6           | 3.9         | 78                | 50.6              | 
```