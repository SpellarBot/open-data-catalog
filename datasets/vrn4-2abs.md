# School Progress Report 2008-2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-2008-2009-aa34c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vrn4-2abs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vrn4-2abs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vrn4-2abs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vrn4-2abs |
| Name | School Progress Report 2008-2009 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T04:37:43Z |
| Publication Date | 2013-02-21T04:38:01Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F. ?These reports focus on a school's learning environment, student performance, and student progress.? They were designed to help parents, teachers, principals, and others understand how well schools are doing?and compare them to other, similar schools.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | dbn                                 | DBN                                 | text      | text        |
| Yes      | series tag     | district                            | DISTRICT                            | text      | text        |
| Yes      | series tag     | school                              | SCHOOL                              | text      | text        |
| Yes      | series tag     | principal                           | PRINCIPAL                           | text      | text        |
| Yes      | series tag     | 2008_09_school_support_organization | 2008-09 SCHOOL SUPPORT ORGANIZATION | text      | text        |
| Yes      | series tag     | progress_report_type                | PROGRESS REPORT TYPE                | text      | text        |
| Yes      | series tag     | school_level                        | SCHOOL LEVEL*                       | text      | text        |
| Yes      | numeric metric | peer_index                          | PEER INDEX*                         | number    | text        |
| Yes      | series tag     | overall_grade                       | OVERALL GRADE                       | text      | text        |
| Yes      | numeric metric | overall_score                       | OVERALL SCORE                       | number    | text        |
| Yes      | numeric metric | environment_category_score          | ENVIRONMENT CATEGORY SCORE          | number    | text        |
| Yes      | series tag     | environment_grade                   | ENVIRONMENT GRADE                   | text      | text        |
| Yes      | numeric metric | performance_category_score          | PERFORMANCE CATEGORY SCORE          | number    | text        |
| Yes      | series tag     | performance_grade                   | PERFORMANCE GRADE                   | text      | text        |
| Yes      | numeric metric | progress_category_score             | PROGRESS CATEGORY SCORE             | number    | text        |
| Yes      | series tag     | progress_grade                      | PROGRESS GRADE                      | text      | text        |
| Yes      | numeric metric | additional_credit                   | ADDITIONAL CREDIT                   | number    | text        |
| Yes      | series tag     | 2007_08_progress_report_grade       | 2007-08 PROGRESS REPORT GRADE       | text      | text        |
| Yes      | series tag     | most_recent_quality_review_score    | MOST RECENT QUALITY REVIEW SCORE    | text      | text        |
| Yes      | series tag     | 2008_09_state_accountability_status | 2008-09 STATE ACCOUNTABILITY STATUS | text      | text        |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vrn4-2abs d:2008-01-01T00:00:00.000Z t:performance_grade=C t:school="P.S. 015 ROBERTO CLEMENTE" t:most_recent_quality_review_score="Proficient (2008-09)" t:principal="Thomas Staebell" t:dbn=01M015 t:2007_08_progress_report_grade=D t:2008_09_school_support_organization=ICI t:progress_grade=B t:progress_report_type=ESMS t:overall_grade=B t:2008_09_state_accountability_status="In Good Standing" t:district=01 t:environment_grade=B t:school_level=Elementary m:additional_credit=2.3 m:performance_category_score=11.7 m:environment_category_score=8.3 m:peer_index=63.28 m:progress_category_score=35.1 m:overall_score=57.4

series e:vrn4-2abs d:2008-01-01T00:00:00.000Z t:performance_grade=A t:school="P.S. 019 ASHER LEVY" t:most_recent_quality_review_score="Well Developed (2007-08)" t:principal="Ivan Kushner" t:dbn=01M019 t:2007_08_progress_report_grade=B t:2008_09_school_support_organization=ESO t:progress_grade=A t:progress_report_type=ESMS t:overall_grade=A t:2008_09_state_accountability_status="In Good Standing" t:district=01 t:environment_grade=B t:school_level=Elementary m:additional_credit=3 m:performance_category_score=19.7 m:environment_category_score=8.6 m:peer_index=50.39 m:progress_category_score=56.7 m:overall_score=88

series e:vrn4-2abs d:2008-01-01T00:00:00.000Z t:performance_grade=A t:school="P.S. 020 ANNA SILVER" t:most_recent_quality_review_score="Proficient (2008-09)" t:principal="James Lee" t:dbn=01M020 t:2007_08_progress_report_grade=A t:2008_09_school_support_organization=ICI t:progress_grade=A t:progress_report_type=ESMS t:overall_grade=A t:2008_09_state_accountability_status="In Good Standing" t:district=01 t:environment_grade=A t:school_level=Elementary m:additional_credit=2.3 m:performance_category_score=21.1 m:environment_category_score=11.9 m:peer_index=57.37 m:progress_category_score=54.4 m:overall_score=89.7
```

## Meta Commands

```ls
metric m:peer_index p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:overall_score p:float l:"OVERALL SCORE" t:dataTypeName=number

metric m:environment_category_score p:float l:"ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:float l:"PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:float l:"PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:float l:"ADDITIONAL CREDIT" t:dataTypeName=number

entity e:vrn4-2abs l:"School Progress Report 2008-2009" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vrn4-2abs

property e:vrn4-2abs t:meta.view v:id=vrn4-2abs v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report 2008-2009" v:attribution="Department of Education (DOE)"

property e:vrn4-2abs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vrn4-2abs t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | district | school                         | principal             | 2008_09_school_support_organization | progress_report_type | school_level | peer_index | overall_grade | overall_score | environment_category_score | environment_grade | performance_category_score | performance_grade | progress_category_score | progress_grade | additional_credit | 2007_08_progress_report_grade | most_recent_quality_review_score | 2008_09_state_accountability_status | 
| ====== | ======== | ============================== | ===================== | =================================== | ==================== | ============ | ========== | ============= | ============= | ========================== | ================= | ========================== | ================= | ======================= | ============== | ================= | ============================= | ================================ | =================================== | 
| 01M015 | 01       | P.S. 015 ROBERTO CLEMENTE      | Thomas Staebell       | ICI                                 | ESMS                 | Elementary   | 63.28      | B             | 57.4          | 8.3                        | B                 | 11.7                       | C                 | 35.1                    | B              | 2.3               | D                             | Proficient (2008-09)             | In Good Standing                    | 
| 01M019 | 01       | P.S. 019 ASHER LEVY            | Ivan Kushner          | ESO                                 | ESMS                 | Elementary   | 50.39      | A             | 88.0          | 8.6                        | B                 | 19.7                       | A                 | 56.7                    | A              | 3.0               | B                             | Well Developed (2007-08)         | In Good Standing                    | 
| 01M020 | 01       | P.S. 020 ANNA SILVER           | James Lee             | ICI                                 | ESMS                 | Elementary   | 57.37      | A             | 89.7          | 11.9                       | A                 | 21.1                       | A                 | 54.4                    | A              | 2.3               | A                             | Proficient (2008-09)             | In Good Standing                    | 
| 01M034 | 01       | P.S. 034 FRANKLIN D. ROOSEVELT | Joyce Stallings Harte | ICI                                 | ESMS                 | K-8          | 58.96      | A             | 73.3          | 7.6                        | C                 | 16.7                       | B                 | 43.0                    | A              | 6.0               | B                             | Well Developed (2007-08)         | In Good Standing                    | 
| 01M063 | 01       | P.S. 063 WILLIAM MCKINLEY      | Darlene Despeignes    | ICI                                 | ESMS                 | Elementary   | 53.00      | B             | 67.8          | 10.0                       | B                 | 14.9                       | B                 | 40.6                    | B              | 2.3               | F                             | Proficient (2008-09)             | In Good Standing                    | 
| 01M064 | 01       | P.S. 064 ROBERT SIMON          | Marlon L. Hosang      | ESO                                 | ESMS                 | Elementary   | 60.63      | A             | 96.3          | 14.0                       | A                 | 20.8                       | A                 | 60.0                    | A              | 1.5               | A                             | Proficient (2008-09)             | In Good Standing                    | 
| 01M110 | 01       | P.S. 110 FLORENCE NIGHTINGALE  | Karen Feuer           | ESO                                 | ESMS                 | Elementary   | 42.56      | B             | 65.0          | 9.0                        | B                 | 19.8                       | A                 | 34.7                    | B              | 1.5               | C                             | Well Developed (2008-09)         | In Good Standing                    | 
| 01M134 | 01       | P.S. 134 HENRIETTA SZOLD       | Loretta Caputo        | ICI                                 | ESMS                 | Elementary   | 54.03      | B             | 67.0          | 9.2                        | B                 | 16.6                       | B                 | 39.7                    | B              | 1.5               | B                             | Proficient (2007-08)             | In Good Standing                    | 
| 01M137 | 01       | P.S. 137 JOHN L. BERNSTEIN     | Melissa Rodriguez     | ICI                                 | ESMS                 | Elementary   | 61.63      | A             | 82.0          | 10.7                       | A                 | 18.0                       | A                 | 50.3                    | A              | 3.0               | B                             | Proficient (2007-08)             | In Good Standing                    | 
| 01M140 | 01       | P.S. 140 NATHAN STRAUS         | Esteban Barrientos    | ESO                                 | ESMS                 | K-8          | 62.46      | A             | 75.1          | 9.9                        | B                 | 19.1                       | A                 | 39.3                    | B              | 6.8               | B                             | Proficient (2007-08)             | Improvement (year 2) - Basic        | 
```