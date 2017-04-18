# School Progress Report 2010-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-2010-2011-72582) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/upwt-zvh3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/upwt-zvh3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/upwt-zvh3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | upwt-zvh3 |
| Name | School Progress Report 2010-2011 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T04:38:19Z |
| Publication Date | 2013-02-21T04:38:53Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F.  These reports focus on a school's learning environment, student performance, and student progress.  They were designed to help parents, teachers, principals, and others understand how well schools are doing—and compare them to other, similar schools.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | dbn                                  | DBN                                  | text      | text        |
| Yes      | series tag     | district                             | DISTRICT                             | text      | text        |
| Yes      | series tag     | school                               | SCHOOL                               | text      | text        |
| Yes      | series tag     | principal                            | PRINCIPAL                            | text      | text        |
| Yes      | series tag     | progress_report_type                 | PROGRESS REPORT TYPE                 | text      | text        |
| Yes      | series tag     | school_level                         | SCHOOL LEVEL*                        | text      | text        |
| Yes      | numeric metric | peer_index                           | PEER INDEX*                          | number    | text        |
| Yes      | series tag     | 2010_2011_overall_grade              | 2010-2011 OVERALL GRADE              | text      | text        |
| Yes      | numeric metric | 2010_2011_overall_score              | 2010-2011 OVERALL SCORE              | number    | text        |
| Yes      | numeric metric | 2010_2011_environment_category_score | 2010-2011 ENVIRONMENT CATEGORY SCORE | number    | text        |
| Yes      | series tag     | 2010_2011_environment_grade          | 2010-2011 ENVIRONMENT GRADE          | text      | text        |
| Yes      | numeric metric | 2010_2011_performance_category_score | 2010-2011 PERFORMANCE CATEGORY SCORE | number    | text        |
| Yes      | series tag     | 2010_2011_performance_grade          | 2010-2011 PERFORMANCE GRADE          | text      | text        |
| Yes      | numeric metric | 2010_2011_progress_category_score    | 2010-2011 PROGRESS CATEGORY SCORE    | number    | text        |
| Yes      | series tag     | 2010_2011_progress_grade             | 2010-2011 PROGRESS GRADE             | text      | text        |
| Yes      | numeric metric | 2010_2011_additional_credit          | 2010-2011 ADDITIONAL CREDIT          | number    | text        |
| Yes      | series tag     | 2009_10_progress_report_grade        | 2009-10 PROGRESS REPORT GRADE        | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:upwt-zvh3 d:2010-01-01T00:00:00.000Z t:school="P.S. 015 Roberto Clemente" t:2010_2011_overall_grade=C t:principal="Irene Sanchez" t:dbn=01M015 t:progress_report_type=EMS t:2010_2011_performance_grade=D t:2010_2011_progress_grade=C t:district=1 t:2009_10_progress_report_grade=C t:2010_2011_environment_grade=B t:school_level=Elementary m:2010_2011_overall_score=27 m:2010_2011_performance_category_score=2.1 m:2010_2011_environment_category_score=6.4 m:2010_2011_additional_credit=0.5 m:peer_index=63.61 m:2010_2011_progress_category_score=18

series e:upwt-zvh3 d:2010-01-01T00:00:00.000Z t:school="P.S. 019 Asher Levy" t:2010_2011_overall_grade=B t:principal="Jacqueline Flanagan" t:dbn=01M019 t:progress_report_type=EMS t:2010_2011_performance_grade=D t:2010_2011_progress_grade=A t:district=1 t:2009_10_progress_report_grade=C t:2010_2011_environment_grade=B t:school_level=Elementary m:2010_2011_overall_score=48.7 m:2010_2011_performance_category_score=5.2 m:2010_2011_environment_category_score=7.8 m:2010_2011_additional_credit=0.5 m:peer_index=49.48 m:2010_2011_progress_category_score=35.1

series e:upwt-zvh3 d:2010-01-01T00:00:00.000Z t:school="P.S. 020 Anna Silver" t:2010_2011_overall_grade=B t:principal="James Lee" t:dbn=01M020 t:progress_report_type=EMS t:2010_2011_performance_grade=C t:2010_2011_progress_grade=B t:district=1 t:2009_10_progress_report_grade=A t:2010_2011_environment_grade=B t:school_level=Elementary m:2010_2011_overall_score=48.2 m:2010_2011_performance_category_score=7.4 m:2010_2011_environment_category_score=7.7 m:2010_2011_additional_credit=2 m:peer_index=56.65 m:2010_2011_progress_category_score=31.1
```

## Meta Commands

```ls
metric m:peer_index p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:2010_2011_overall_score p:float l:"2010-2011 OVERALL SCORE" t:dataTypeName=number

metric m:2010_2011_environment_category_score p:float l:"2010-2011 ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:2010_2011_performance_category_score p:float l:"2010-2011 PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:2010_2011_progress_category_score p:float l:"2010-2011 PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:2010_2011_additional_credit p:float l:"2010-2011 ADDITIONAL CREDIT" t:dataTypeName=number

entity e:upwt-zvh3 l:"School Progress Report 2010-2011" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/upwt-zvh3

property e:upwt-zvh3 t:meta.view v:id=upwt-zvh3 v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report 2010-2011" v:attribution="Department of Education (DOE)"

property e:upwt-zvh3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:upwt-zvh3 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | district | school                         | principal             | progress_report_type | school_level | peer_index | 2010_2011_overall_grade | 2010_2011_overall_score | 2010_2011_environment_category_score | 2010_2011_environment_grade | 2010_2011_performance_category_score | 2010_2011_performance_grade | 2010_2011_progress_category_score | 2010_2011_progress_grade | 2010_2011_additional_credit | 2009_10_progress_report_grade | 
| ====== | ======== | ============================== | ===================== | ==================== | ============ | ========== | ======================= | ======================= | ==================================== | =========================== | ==================================== | =========================== | ================================= | ======================== | =========================== | ============================= | 
| 01M015 | 1        | P.S. 015 Roberto Clemente      | Irene Sanchez         | EMS                  | Elementary   | 63.61      | C                       | 27.0                    | 6.4                                  | B                           | 2.1                                  | D                           | 18.0                              | C                        | 0.5                         | C                             | 
| 01M019 | 1        | P.S. 019 Asher Levy            | Jacqueline Flanagan   | EMS                  | Elementary   | 49.48      | B                       | 48.7                    | 7.8                                  | B                           | 5.2                                  | D                           | 35.1                              | A                        | 0.5                         | C                             | 
| 01M020 | 1        | P.S. 020 Anna Silver           | James Lee             | EMS                  | Elementary   | 56.65      | B                       | 48.2                    | 7.7                                  | B                           | 7.4                                  | C                           | 31.1                              | B                        | 2.0                         | A                             | 
| 01M034 | 1        | P.S. 034 Franklin D. Roosevelt | Joyce Stallings Harte | EMS                  | K-8          | 67.97      | C                       | 39.8                    | 7.5                                  | B                           | 11.3                                 | B                           | 18.5                              | C                        | 2.5                         | B                             | 
| 01M063 | 1        | P.S. 063 William McKinley      | Darlene Despeignes    | EMS                  | Elementary   | 58.85      | B                       | 49.0                    | 8.1                                  | B                           | 10.4                                 | B                           | 29.0                              | B                        | 1.5                         | B                             | 
| 01M064 | 1        | P.S. 064 Robert Simon          | Marlon L. Hosang      | EMS                  | Elementary   | 60.73      | C                       | 25.8                    | 9.7                                  | A                           | 4.5                                  | D                           | 11.6                              | D                        | 0.0                         | C                             | 
| 01M110 | 1        | P.S. 110 Florence Nightingale  | Karen Feuer           | EMS                  | Elementary   | 40.85      | C                       | 38.1                    | 4.1                                  | C                           | 10.9                                 | B                           | 22.1                              | C                        | 1.0                         | D                             | 
| 01M134 | 1        | P.S. 134 Henrietta Szold       | Loretta Caputo        | EMS                  | Elementary   | 54.33      | C                       | 34.6                    | 4.2                                  | C                           | 5.9                                  | C                           | 24.0                              | C                        | 0.5                         | B                             | 
| 01M137 | 1        | P.S. 137 John L. Bernstein     | Melissa Rodriguez     | EMS                  | Elementary   | 57.88      | F                       | 17.6                    | 5.1                                  | C                           | 4.8                                  | D                           | 6.7                               | F                        | 1.0                         | C                             | 
| 01M140 | 1        | P.S. 140 Nathan Straus         | Esteban Barrientos    | EMS                  | K-8          | 61.28      | D                       | 23.6                    | 8.4                                  | B                           | 5.1                                  | D                           | 9.6                               | D                        | 0.5                         | B                             | 
```