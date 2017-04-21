# School Progress Report 2009-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-2009-2010-8c402) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4n2j-ut8i) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4n2j-ut8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4n2j-ut8i/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4n2j-ut8i |
| Name | School Progress Report 2009-2010 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T04:38:01Z |
| Publication Date | 2013-02-21T04:38:18Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F. ?These reports focus on a school's learning environment, student performance, and student progress.? They were designed to help parents, teachers, principals, and others understand how well schools are doing?and compare them to other, similar schools.

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
| Yes      | series tag     | 2009_2010_overall_grade              | 2009-2010 OVERALL GRADE              | text      | text        |
| Yes      | numeric metric | 2009_2010_overall_score              | 2009-2010 OVERALL SCORE              | number    | text        |
| Yes      | numeric metric | 2009_2010_environment_category_score | 2009-2010 ENVIRONMENT CATEGORY SCORE | number    | text        |
| Yes      | series tag     | 2009_2010_environment_grade          | 2009-2010 ENVIRONMENT GRADE          | text      | text        |
| Yes      | numeric metric | 2009_2010_performance_category_score | 2009-2010 PERFORMANCE CATEGORY SCORE | number    | text        |
| Yes      | series tag     | 2009_2010_performance_grade          | 2009-2010 PERFORMANCE GRADE          | text      | text        |
| Yes      | numeric metric | 2009_2010_progress_category_score    | 2009-2010 PROGRESS CATEGORY SCORE    | number    | text        |
| Yes      | series tag     | 2009_2010_progress_grade             | 2009-2010 PROGRESS GRADE             | text      | text        |
| Yes      | numeric metric | 2009_2010_additional_credit          | 2009-2010 ADDITIONAL CREDIT          | number    | text        |
| Yes      | series tag     | 2008_09_progress_report_grade        | 2008-09 PROGRESS REPORT GRADE        | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4n2j-ut8i d:2009-01-01T00:00:00.000Z t:school="P.S. 015 Roberto Clemente" t:principal="Thomas Staebell" t:dbn=01M015 t:2008_09_progress_report_grade=B t:2009_2010_overall_grade=C t:progress_report_type=EMS t:2009_2010_progress_grade=B t:2009_2010_performance_grade=D t:district=1 t:school_level=Elementary t:2009_2010_environment_grade=B m:2009_2010_environment_category_score=7.2 m:2009_2010_progress_category_score=27.4 m:2009_2010_overall_score=37.6 m:peer_index=62.65 m:2009_2010_performance_category_score=3 m:2009_2010_additional_credit=0

series e:4n2j-ut8i d:2009-01-01T00:00:00.000Z t:school="P.S. 019 Asher Levy" t:principal="Jacqueline Flanagan" t:dbn=01M019 t:2008_09_progress_report_grade=A t:2009_2010_overall_grade=C t:progress_report_type=EMS t:2009_2010_progress_grade=B t:2009_2010_performance_grade=D t:district=1 t:school_level=Elementary t:2009_2010_environment_grade=B m:2009_2010_environment_category_score=6.4 m:2009_2010_progress_category_score=24.4 m:2009_2010_overall_score=35.7 m:peer_index=48.94 m:2009_2010_performance_category_score=4.9 m:2009_2010_additional_credit=0

series e:4n2j-ut8i d:2009-01-01T00:00:00.000Z t:school="P.S. 020 Anna Silver" t:principal="James Lee" t:dbn=01M020 t:2008_09_progress_report_grade=A t:2009_2010_overall_grade=A t:progress_report_type=EMS t:2009_2010_progress_grade=A t:2009_2010_performance_grade=C t:district=1 t:school_level=Elementary t:2009_2010_environment_grade=A m:2009_2010_environment_category_score=9.3 m:2009_2010_progress_category_score=44.1 m:2009_2010_overall_score=70.3 m:peer_index=57.68 m:2009_2010_performance_category_score=7.9 m:2009_2010_additional_credit=9
```

## Meta Commands

```ls
metric m:peer_index p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:2009_2010_overall_score p:float l:"2009-2010 OVERALL SCORE" t:dataTypeName=number

metric m:2009_2010_environment_category_score p:float l:"2009-2010 ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:2009_2010_performance_category_score p:float l:"2009-2010 PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:2009_2010_progress_category_score p:float l:"2009-2010 PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:2009_2010_additional_credit p:float l:"2009-2010 ADDITIONAL CREDIT" t:dataTypeName=number

entity e:4n2j-ut8i l:"School Progress Report 2009-2010" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/4n2j-ut8i

property e:4n2j-ut8i t:meta.view v:id=4n2j-ut8i v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report 2009-2010" v:attribution="Department of Education (DOE)"

property e:4n2j-ut8i t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4n2j-ut8i t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | district | school                         | principal             | progress_report_type | school_level | peer_index | 2009_2010_overall_grade | 2009_2010_overall_score | 2009_2010_environment_category_score | 2009_2010_environment_grade | 2009_2010_performance_category_score | 2009_2010_performance_grade | 2009_2010_progress_category_score | 2009_2010_progress_grade | 2009_2010_additional_credit | 2008_09_progress_report_grade | 
| ====== | ======== | ============================== | ===================== | ==================== | ============ | ========== | ======================= | ======================= | ==================================== | =========================== | ==================================== | =========================== | ================================= | ======================== | =========================== | ============================= | 
| 01M015 | 1        | P.S. 015 Roberto Clemente      | Thomas Staebell       | EMS                  | Elementary   | 62.65      | C                       | 37.6                    | 7.2                                  | B                           | 3.0                                  | D                           | 27.4                              | B                        | 0.0                         | B                             | 
| 01M019 | 1        | P.S. 019 Asher Levy            | Jacqueline Flanagan   | EMS                  | Elementary   | 48.94      | C                       | 35.7                    | 6.4                                  | B                           | 4.9                                  | D                           | 24.4                              | B                        | 0.0                         | A                             | 
| 01M020 | 1        | P.S. 020 Anna Silver           | James Lee             | EMS                  | Elementary   | 57.68      | A                       | 70.3                    | 9.3                                  | A                           | 7.9                                  | C                           | 44.1                              | A                        | 9.0                         | A                             | 
| 01M034 | 1        | P.S. 034 Franklin D. Roosevelt | Joyce Stallings Harte | EMS                  | K-8          | 66.75      | B                       | 53.0                    | 6.8                                  | B                           | 7.4                                  | C                           | 33.0                              | B                        | 5.8                         | A                             | 
| 01M063 | 1        | P.S. 063 William McKinley      | Darlene Despeignes    | EMS                  | Elementary   | 57.55      | B                       | 54.0                    | 7.8                                  | B                           | 7.1                                  | C                           | 35.8                              | A                        | 3.3                         | B                             | 
| 01M064 | 1        | P.S. 064 Robert Simon          | Marlon L. Hosang      | EMS                  | Elementary   | 61.50      | C                       | 31.0                    | 10.3                                 | A                           | 5.4                                  | D                           | 15.3                              | D                        | 0.0                         | A                             | 
| 01M110 | 1        | P.S. 110 Florence Nightingale  | Karen Feuer           | EMS                  | Elementary   | 42.47      | D                       | 25.4                    | 5.2                                  | C                           | 8.8                                  | C                           | 11.4                              | D                        | 0.0                         | B                             | 
| 01M134 | 1        | P.S. 134 Henrietta Szold       | Loretta Caputo        | EMS                  | Elementary   | 53.05      | B                       | 54.2                    | 4.9                                  | C                           | 4.1                                  | D                           | 41.4                              | A                        | 3.8                         | B                             | 
| 01M137 | 1        | P.S. 137 John L. Bernstein     | Melissa Rodriguez     | EMS                  | Elementary   | 58.66      | C                       | 20.1                    | 6.8                                  | B                           | 5.5                                  | D                           | 7.8                               | F                        | 0.0                         | A                             | 
| 01M140 | 1        | P.S. 140 Nathan Straus         | Esteban Barrientos    | EMS                  | K-8          | 61.90      | B                       | 43.0                    | 8.5                                  | A                           | 7.2                                  | C                           | 26.5                              | B                        | 0.8                         | A                             | 
```