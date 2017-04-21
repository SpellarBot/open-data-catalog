# English Language Arts (ELA) Test Results 2006-2012 - Borough - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/english-language-arts-ela-test-results-2006-2012-borough-swd-916ea) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vfk9-3uwk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vfk9-3uwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vfk9-3uwk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vfk9-3uwk |
| Name | English Language Arts (ELA) Test Results 2006-2012 - Borough - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | english language arts, ela test, grade, borough, lifelong learning |
| Created | 2013-02-20T22:02:29Z |
| Publication Date | 2013-02-20T22:02:41Z |

## Description

Latest available data and trends in the state assessment results of English Language Arts for grades 3 through 8. Data are disaggregated by borough and student with disabilities.

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
series e:vfk9-3uwk d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="Not SWD" m:mean_scale_score=657 m:pct_level_1=9.4 m:pct_level_2=33.7 m:pct_level_3=54 m:num_level_3_and_4=6300 m:pct_level_4=3 m:num_level_1=1040 m:number_tested=11064 m:num_level_2=3724 m:pct_level_3_and_4=56.9 m:num_level_4=329 m:num_level_3=5971

series e:vfk9-3uwk d:2006-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic=SWD m:mean_scale_score=616 m:pct_level_1=49.9 m:pct_level_2=32.8 m:pct_level_3=16.8 m:num_level_3_and_4=385 m:pct_level_4=0.4 m:num_level_1=1114 m:number_tested=2232 m:num_level_2=733 m:pct_level_3_and_4=17.2 m:num_level_4=9 m:num_level_3=376

series e:vfk9-3uwk d:2007-01-01T00:00:00.000Z t:grade=3 t:borough=BRONX t:demographic="Not SWD" m:mean_scale_score=651 m:pct_level_1=12 m:pct_level_2=37.5 m:pct_level_3=47.3 m:num_level_3_and_4=6568 m:pct_level_4=3.2 m:num_level_1=1561 m:number_tested=13001 m:num_level_2=4872 m:pct_level_3_and_4=50.5 m:num_level_4=422 m:num_level_3=6146
```

## Meta Commands

```ls
metric m:number_tested p:integer l:"Number Tested" t:dataTypeName=number

metric m:mean_scale_score p:integer l:"Mean Scale Score" t:dataTypeName=number

metric m:num_level_1 p:integer l:"Num Level 1" t:dataTypeName=number

metric m:pct_level_1 p:integer l:"Pct Level 1" t:dataTypeName=number

metric m:num_level_2 p:integer l:"Num Level 2" t:dataTypeName=number

metric m:pct_level_2 p:float l:"Pct Level 2" t:dataTypeName=number

metric m:num_level_3 p:integer l:"Num Level 3" t:dataTypeName=number

metric m:pct_level_3 p:float l:"Pct Level 3" t:dataTypeName=number

metric m:num_level_4 p:integer l:"Num Level 4" t:dataTypeName=number

metric m:pct_level_4 p:integer l:"Pct Level 4" t:dataTypeName=number

metric m:num_level_3_and_4 p:integer l:"Num Level 3 and 4" t:dataTypeName=number

metric m:pct_level_3_and_4 p:float l:"Pct Level 3 and 4" t:dataTypeName=number

entity e:vfk9-3uwk l:"English Language Arts (ELA) Test Results 2006-2012 - Borough - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vfk9-3uwk

property e:vfk9-3uwk t:meta.view v:id=vfk9-3uwk v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/B82F9971-6533-4355-B3F0-19219B74453F/0/BoroughELAResults20062012Public.xlsx v:averageRating=0 v:name="English Language Arts (ELA) Test Results 2006-2012 - Borough - SWD" v:attribution="Department of Education (DOE)"

property e:vfk9-3uwk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vfk9-3uwk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | grade | year | demographic | number_tested | mean_scale_score | num_level_1 | pct_level_1 | num_level_2 | pct_level_2 | num_level_3 | pct_level_3 | num_level_4 | pct_level_4 | num_level_3_and_4 | pct_level_3_and_4 | 
| ======= | ===== | ==== | =========== | ============= | ================ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ================= | ================= | 
| BRONX   | 3     | 2006 | Not SWD     | 11064         | 657              | 1040        | 9.4         | 3724        | 33.7        | 5971        | 54          | 329         | 3           | 6300              | 56.9              | 
| BRONX   | 3     | 2006 | SWD         | 2232          | 616              | 1114        | 49.9        | 733         | 32.8        | 376         | 16.8        | 9           | 0.4         | 385               | 17.2              | 
| BRONX   | 3     | 2007 | Not SWD     | 13001         | 651              | 1561        | 12          | 4872        | 37.5        | 6146        | 47.3        | 422         | 3.2         | 6568              | 50.5              | 
| BRONX   | 3     | 2007 | SWD         | 2870          | 614              | 1373        | 47.8        | 992         | 34.6        | 495         | 17.2        | 10          | 0.3         | 505               | 17.6              | 
| BRONX   | 3     | 2008 | Not SWD     | 12432         | 656              | 870         | 7           | 4623        | 37.2        | 6343        | 51          | 596         | 4.8         | 6939              | 55.8              | 
| BRONX   | 3     | 2008 | SWD         | 2948          | 622              | 1152        | 39.1        | 1239        | 42          | 532         | 18          | 25          | 0.8         | 557               | 18.9              | 
| BRONX   | 3     | 2009 | Not SWD     | 12433         | 661              | 515         | 4.1         | 3515        | 28.3        | 7840        | 63.1        | 563         | 4.5         | 8403              | 67.6              | 
| BRONX   | 3     | 2009 | SWD         | 3098          | 629              | 935         | 30.2        | 1322        | 42.7        | 818         | 26.4        | 23          | 0.7         | 841               | 27.1              | 
| BRONX   | 3     | 2010 | Not SWD     | 12092         | 661              | 1984        | 16.4        | 5045        | 41.7        | 3931        | 32.5        | 1132        | 9.4         | 5063              | 41.9              | 
| BRONX   | 3     | 2010 | SWD         | 3362          | 640              | 1861        | 55.4        | 1035        | 30.8        | 400         | 11.9        | 66          | 2           | 466               | 13.9              | 
```