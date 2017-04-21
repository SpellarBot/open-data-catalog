# Quality Review 2005-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quality-review-2005-2012-0bdea) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/piri-jns7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/piri-jns7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/piri-jns7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | piri-jns7 |
| Name | Quality Review 2005-2012 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | quaility review score, school, lifelong learning |
| Created | 2013-02-21T05:16:58Z |
| Publication Date | 2013-02-21T05:17:15Z |

## Description

The Quality Review is a two- or three-day school visit by experienced educators to each New York City school. During the review, the external evaluator visits classrooms, talks with school leaders, and uses a rubric to evaluate how well the school is organized to support student achievement. This dataset includes all of the Quality Review scores from 2005-2011.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | dbn            | DBN            | text      | text        |
| Yes      | series tag  | school_year    | School Year    | text      | text        |
| Yes      | series tag  | overall_rating | Overall Rating | text      | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:piri-jns7 d:2005-01-01T00:00:00.000Z t:dbn=20K062 t:school_year=SY05-06 t:overall_rating=WD m:row_number.piri-jns7=1

series e:piri-jns7 d:2005-01-01T00:00:00.000Z t:dbn=21K101 t:school_year=SY05-06 t:overall_rating=WD m:row_number.piri-jns7=2

series e:piri-jns7 d:2005-01-01T00:00:00.000Z t:dbn=18K115 t:school_year=SY05-06 t:overall_rating=WD m:row_number.piri-jns7=3
```

## Meta Commands

```ls
metric m:row_number.piri-jns7 p:long l:"Row Number"

entity e:piri-jns7 l:"Quality Review 2005-2012" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/piri-jns7

property e:piri-jns7 t:meta.view v:id=piri-jns7 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/E3367F73-5021-4113-97CC-A131848E46FD/0/Updated20052010QRScoresforthewebsitesheet1.xlsx v:averageRating=0 v:name="Quality Review 2005-2012" v:attribution="Department of Education (DOE)"

property e:piri-jns7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:piri-jns7 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_year | overall_rating | 
| ====== | =========== | ============== | 
| 20K062 | SY05-06     | WD             | 
| 21K101 | SY05-06     | WD             | 
| 18K115 | SY05-06     | WD             | 
| 22K152 | SY05-06     | WD             | 
| 22K315 | SY05-06     | WD             | 
| 14K330 | SY05-06     | P              | 
| 15K027 | SY06-07     | U              | 
| 21K337 | SY05-06     | P              | 
| 13K350 | SY05-06     | P              | 
| 15K027 | SY07-08     | P              | 
```