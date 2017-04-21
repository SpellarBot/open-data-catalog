# School Progress Report 2007-2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-2007-2008-16883) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yayv-apxh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yayv-apxh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yayv-apxh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yayv-apxh |
| Name | School Progress Report 2007-2008 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T04:37:25Z |
| Publication Date | 2013-02-21T04:37:42Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F. ?These reports focus on a school's learning environment, student performance, and student progress.? They were designed to help parents, teachers, principals, and others understand how well schools are doing?and compare them to other, similar schools.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | dbn                                   | DBN                                   | text      | text        |
| Yes      | series tag     | district                              | DISTRICT                              | text      | text        |
| Yes      | series tag     | school                                | SCHOOL                                | text      | text        |
| Yes      | series tag     | principal                             | PRINCIPAL                             | text      | text        |
| Yes      | series tag     | 2007_08_school_support_organization   | 2007-08 SCHOOL SUPPORT ORGANIZATION   | text      | text        |
| Yes      | series tag     | progress_report_type                  | PROGRESS REPORT TYPE                  | text      | text        |
| Yes      | series tag     | school_level                          | SCHOOL LEVEL*                         | text      | text        |
| Yes      | numeric metric | peer_index                            | PEER INDEX*                           | number    | text        |
| Yes      | series tag     | overall_grade                         | OVERALL GRADE                         | text      | text        |
| Yes      | series tag     | overall_score                         | OVERALL SCORE                         | text      | text        |
| Yes      | numeric metric | environment_category_score            | ENVIRONMENT CATEGORY SCORE            | number    | text        |
| Yes      | series tag     | environment_grade                     | ENVIRONMENT GRADE                     | text      | text        |
| Yes      | numeric metric | performance_category_score            | PERFORMANCE CATEGORY SCORE            | number    | text        |
| Yes      | series tag     | performance_grade                     | PERFORMANCE GRADE                     | text      | text        |
| Yes      | numeric metric | progress_category_score               | PROGRESS CATEGORY SCORE               | number    | text        |
| Yes      | series tag     | progress_grade                        | PROGRESS GRADE                        | text      | text        |
| Yes      | numeric metric | additional_credit                     | ADDITIONAL CREDIT                     | number    | text        |
| Yes      | series tag     | 2006_07_progress_report_grade         | 2006-07 PROGRESS REPORT GRADE         | text      | text        |
| Yes      | series tag     | 2007_08_quality_review_score          | 2007-08 QUALITY REVIEW SCORE          | text      | text        |
| Yes      | series tag     | 2006_07_federal_accountability_status | 2006-07 FEDERAL ACCOUNTABILITY STATUS | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yayv-apxh d:2007-01-01T00:00:00.000Z t:2007_08_school_support_organization=ICI t:progress_report_type=ESMS t:overall_grade=D t:environment_grade=C t:2007_08_quality_review_score=Proficient t:school="P.S. 015 ROBERTO CLEMENTE" t:performance_grade=C t:principal="Thomas Staebell" t:dbn=01M015 t:progress_grade=C t:2006_07_federal_accountability_status="In Good Standing" t:2006_07_progress_report_grade=B t:district=01 t:school_level="Elementary School" t:overall_score=31.9 m:additional_credit=0 m:performance_category_score=8 m:environment_category_score=5.8 m:peer_index=63.28 m:progress_category_score=18.1

series e:yayv-apxh d:2007-01-01T00:00:00.000Z t:2007_08_school_support_organization=ESO t:progress_report_type=ESMS t:overall_grade=B t:environment_grade=B t:2007_08_quality_review_score="Well Developed" t:school="P.S. 019 ASHER LEVY" t:performance_grade=B t:principal="Ivan Kushner" t:dbn=01M019 t:progress_grade=B t:2006_07_federal_accountability_status="In Good Standing" t:2006_07_progress_report_grade=B t:district=01 t:school_level="Elementary School" t:overall_score=50.8 m:additional_credit=0 m:performance_category_score=11.4 m:environment_category_score=9 m:peer_index=50.39 m:progress_category_score=30.4

series e:yayv-apxh d:2007-01-01T00:00:00.000Z t:2007_08_school_support_organization=ICI t:progress_report_type=ESMS t:overall_grade=A t:environment_grade=A t:2007_08_quality_review_score="Well Developed" t:school="P.S. 020 ANNA SILVER" t:performance_grade=A t:principal="Felix Gil" t:dbn=01M020 t:progress_grade=A t:2006_07_federal_accountability_status="In Need of Improvement - Year 2" t:2006_07_progress_report_grade=B t:district=01 t:school_level="Elementary School" t:overall_score=69.7 m:additional_credit=2.25 m:performance_category_score=20 m:environment_category_score=9.7 m:peer_index=57.37 m:progress_category_score=37.7
```

## Meta Commands

```ls
metric m:peer_index p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:environment_category_score p:integer l:"ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:integer l:"PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:integer l:"PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:integer l:"ADDITIONAL CREDIT" t:dataTypeName=number

entity e:yayv-apxh l:"School Progress Report 2007-2008" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yayv-apxh

property e:yayv-apxh t:meta.view v:id=yayv-apxh v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report 2007-2008" v:attribution="Department of Education (DOE)"

property e:yayv-apxh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yayv-apxh t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | district | school                         | principal             | 2007_08_school_support_organization | progress_report_type | school_level      | peer_index | overall_grade | overall_score | environment_category_score | environment_grade | performance_category_score | performance_grade | progress_category_score | progress_grade | additional_credit | 2006_07_progress_report_grade | 2007_08_quality_review_score | 2006_07_federal_accountability_status | 
| ====== | ======== | ============================== | ===================== | =================================== | ==================== | ================= | ========== | ============= | ============= | ========================== | ================= | ========================== | ================= | ======================= | ============== | ================= | ============================= | ============================ | ===================================== | 
| 01M015 | 01       | P.S. 015 ROBERTO CLEMENTE      | Thomas Staebell       | ICI                                 | ESMS                 | Elementary School | 63.28      | D             | 31.9          | 5.8                        | C                 | 8                          | C                 | 18.1                    | C              | 0                 | B                             | Proficient                   | In Good Standing                      | 
| 01M019 | 01       | P.S. 019 ASHER LEVY            | Ivan Kushner          | ESO                                 | ESMS                 | Elementary School | 50.39      | B             | 50.8          | 9                          | B                 | 11.4                       | B                 | 30.4                    | B              | 0                 | B                             | Well Developed               | In Good Standing                      | 
| 01M020 | 01       | P.S. 020 ANNA SILVER           | Felix Gil             | ICI                                 | ESMS                 | Elementary School | 57.37      | A             | 69.7          | 9.7                        | A                 | 20                         | A                 | 37.7                    | A              | 2.25              | B                             | Well Developed               | In Need of Improvement - Year 2       | 
| 01M034 | 01       | P.S. 034 FRANKLIN D. ROOSEVELT | Joyce Stallings Harte | ICI                                 | ESMS                 | K-8               | 58.96      | B             | 59.8          | 4.5                        | D                 | 10.6                       | C                 | 37.9                    | A              | 6.75              | C                             | Well Developed               | In Good Standing                      | 
| 01M063 | 01       | P.S. 063 WILLIAM MCKINLEY      | Darlene Despeignes    | ICI                                 | ESMS                 | Elementary School | 53.00      | F             | 26.5          | 7.6                        | B                 | 11.3                       | C                 | 7.6                     | F              | 0                 | C                             | Proficient                   | In Good Standing                      | 
| 01M064 | 01       | P.S. 064 ROBERT SIMON          | Sandra Litrico Pappas | ESO                                 | ESMS                 | Elementary School | 60.63      | A             | 79.7          | 12.1                       | A                 | 18.9                       | A                 | 46.4                    | A              | 2.25              | C                             | Well Developed               | In Good Standing                      | 
| 01M110 | 01       | P.S. 110 FLORENCE NIGHTINGALE  | Irene Quvus           | ESO                                 | ESMS                 | Elementary School | 42.56      | C             | 41.2          | 9.4                        | A                 | 16.9                       | A                 | 13.4                    | D              | 1.5               | B                             | Well Developed               | In Good Standing                      | 
| 01M134 | 01       | P.S. 134 HENRIETTA SZOLD       | Loretta Caputo        | ICI                                 | ESMS                 | Elementary School | 54.03      | B             | 53            | 5.8                        | C                 | 14.4                       | B                 | 31.3                    | B              | 1.5               | B                             | Proficient                   | In Good Standing                      | 
| 01M137 | 01       | P.S. 137 JOHN L. BERNSTEIN     | Melissa Rodriguez     | ICI                                 | ESMS                 | Elementary School | 61.63      | B             | 55.2          | 7.8                        | B                 | 16.1                       | A                 | 29.8                    | B              | 1.5               | B                             | Proficient                   | In Good Standing                      | 
| 01M140 | 01       | P.S. 140 NATHAN STRAUS         | Esteban Barrientos    | ESO                                 | ESMS                 | K-8               | 62.46      | B             | 64.8          | 9                          | B                 | 15.3                       | B                 | 36                      | B              | 4.5               | B                             | Proficient                   | In Need of Improvement - Year 1       | 
```