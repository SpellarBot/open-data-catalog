# School Progress Reports - All Schools - 2007-08

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-reports-all-schools-2007-08-08392) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dj4e-3xrn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dj4e-3xrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dj4e-3xrn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dj4e-3xrn |
| Name | School Progress Reports - All Schools - 2007-08 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T20:28:33Z |
| Publication Date | 2011-10-11T18:31:05Z |

## Description

2007/08 Progress Report results for all schools (data as of 1/13/09)

Peer indices are calculated differently depending on School Level.  Schools are only compared to other schools in the same School Level (e.g., Elementary, K-8, Middle, High)

1) Elementary & K-8 - peer index is a value from 0-100.  We use a composite demographic statistic based on % ELL, % SpEd, % Title I free lunch, and % Black/Hispanic.  Higher values indicate student populations with higher need.

2) Middle & High - peer index is a value from 1.00-4.50.  For middle schools, we use the average 4th grade proficiency ratings in ELA and Math for all their students that have 4th grade test scores.  For high schools, we use the average 8th grade proficiency ratings in ELA and Math for all their students that have 8th grade test scores, % SpEd, and % Overage.  Lower values indicate student populations with higher need.

3) Schools for Transfer Students - peer index is a value from 1.00-4.50.  We use the average 8th grade proficiency ratings in ELA and Math for all their students that have 8th grade test scores and the % Overage/Under credited.  Lower values indicate student populations with higher need.  Unlike Elementary, Middle, and High School Progress Reports, the Environment Category is only composed of Survey Results.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                  | Data Type | Render Type |
| ======== | ============== | ============================= | ===================================== | ========= | =========== |
| Yes      | series tag     | dbn                           | DBN                                   | text      | text        |
| Yes      | series tag     | district                      | DISTRICT                              | text      | number      |
| Yes      | series tag     | school                        | SCHOOL                                | text      | text        |
| Yes      | series tag     | principal                     | PRINCIPAL                             | text      | text        |
| Yes      | series tag     | school_support_organization   | 2007-08 SCHOOL SUPPORT ORGANIZATION   | text      | text        |
| Yes      | series tag     | progress_report_type          | PROGRESS REPORT TYPE                  | text      | text        |
| Yes      | series tag     | school_level_                 | SCHOOL LEVEL*                         | text      | text        |
| Yes      | numeric metric | peer_index_                   | PEER INDEX*                           | number    | number      |
| Yes      | series tag     | overall_grade                 | OVERALL GRADE                         | text      | text        |
| Yes      | numeric metric | overall_score                 | OVERALL SCORE                         | number    | number      |
| Yes      | numeric metric | environment_category_score    | ENVIRONMENT CATEGORY SCORE            | number    | number      |
| Yes      | series tag     | environment_grade             | ENVIRONMENT GRADE                     | text      | text        |
| Yes      | numeric metric | performance_category_score    | PERFORMANCE CATEGORY SCORE            | number    | number      |
| Yes      | series tag     | performance_grade             | PERFORMANCE GRADE                     | text      | text        |
| Yes      | numeric metric | progress_category_score       | PROGRESS CATEGORY SCORE               | number    | number      |
| Yes      | series tag     | progress_grade                | PROGRESS GRADE                        | text      | text        |
| Yes      | numeric metric | additional_credit             | ADDITIONAL CREDIT                     | number    | number      |
| Yes      | series tag     | progress_report_grade         | 2006-07 PROGRESS REPORT GRADE         | text      | text        |
| Yes      | series tag     | quality_review_score          | 2007-08 QUALITY REVIEW SCORE          | text      | text        |
| Yes      | series tag     | federal_accountability_status | 2006-07 FEDERAL ACCOUNTABILITY STATUS | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dj4e-3xrn d:2007-01-01T00:00:00.000Z t:performance_grade=C t:school="P.S. 015 ROBERTO CLEMENTE" t:school_support_organization=ICI t:principal="Thomas Staebell" t:dbn=01M015 t:school_level_="Elementary School" t:progress_grade=C t:quality_review_score=Proficient t:progress_report_type=ESMS t:progress_report_grade=B t:overall_grade=D t:district=1 t:environment_grade=C t:federal_accountability_status="In Good Standing" m:additional_credit=0 m:peer_index_=63.28 m:performance_category_score=8 m:environment_category_score=5.8 m:progress_category_score=18.1 m:overall_score=31.9

series e:dj4e-3xrn d:2007-01-01T00:00:00.000Z t:performance_grade=B t:school="P.S. 019 ASHER LEVY" t:school_support_organization=ESO t:principal="Ivan Kushner" t:dbn=01M019 t:school_level_="Elementary School" t:progress_grade=B t:quality_review_score="Well Developed" t:progress_report_type=ESMS t:progress_report_grade=B t:overall_grade=B t:district=1 t:environment_grade=B t:federal_accountability_status="In Good Standing" m:additional_credit=0 m:peer_index_=50.39 m:performance_category_score=11.4 m:environment_category_score=9 m:progress_category_score=30.4 m:overall_score=50.8

series e:dj4e-3xrn d:2007-01-01T00:00:00.000Z t:performance_grade=A t:school="P.S. 020 ANNA SILVER" t:school_support_organization=ICI t:principal="Felix Gil" t:dbn=01M020 t:school_level_="Elementary School" t:progress_grade=A t:quality_review_score="Well Developed" t:progress_report_type=ESMS t:progress_report_grade=B t:overall_grade=A t:district=1 t:environment_grade=A t:federal_accountability_status="In Need of Improvement - Year 2" m:additional_credit=2.25 m:peer_index_=57.37 m:performance_category_score=20 m:environment_category_score=9.7 m:progress_category_score=37.7 m:overall_score=69.7
```

## Meta Commands

```ls
metric m:peer_index_ p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:overall_score p:long l:"OVERALL SCORE" t:dataTypeName=number

metric m:environment_category_score p:double l:"ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:double l:"PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:double l:"PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:double l:"ADDITIONAL CREDIT" t:dataTypeName=number

entity e:dj4e-3xrn l:"School Progress Reports - All Schools - 2007-08" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/dj4e-3xrn

property e:dj4e-3xrn t:meta.view v:id=dj4e-3xrn v:category=Education v:averageRating=0 v:name="School Progress Reports - All Schools - 2007-08" v:attribution="Department of Education (DOE)"

property e:dj4e-3xrn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dj4e-3xrn t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | district | school                         | principal             | school_support_organization | progress_report_type | school_level_     | peer_index_ | overall_grade | overall_score | environment_category_score | environment_grade | performance_category_score | performance_grade | progress_category_score | progress_grade | additional_credit | progress_report_grade | quality_review_score | federal_accountability_status   | 
| ====== | ======== | ============================== | ===================== | =========================== | ==================== | ================= | =========== | ============= | ============= | ========================== | ================= | ========================== | ================= | ======================= | ============== | ================= | ===================== | ==================== | =============================== | 
| 01M015 | 1        | P.S. 015 ROBERTO CLEMENTE      | Thomas Staebell       | ICI                         | ESMS                 | Elementary School | 63.28       | D             | 31.9          | 5.8                        | C                 | 8                          | C                 | 18.1                    | C              | 0                 | B                     | Proficient           | In Good Standing                | 
| 01M019 | 1        | P.S. 019 ASHER LEVY            | Ivan Kushner          | ESO                         | ESMS                 | Elementary School | 50.39       | B             | 50.8          | 9                          | B                 | 11.4                       | B                 | 30.4                    | B              | 0                 | B                     | Well Developed       | In Good Standing                | 
| 01M020 | 1        | P.S. 020 ANNA SILVER           | Felix Gil             | ICI                         | ESMS                 | Elementary School | 57.37       | A             | 69.7          | 9.7                        | A                 | 20                         | A                 | 37.7                    | A              | 2.25              | B                     | Well Developed       | In Need of Improvement - Year 2 | 
| 01M034 | 1        | P.S. 034 FRANKLIN D. ROOSEVELT | Joyce Stallings Harte | ICI                         | ESMS                 | K-8               | 58.96       | B             | 59.8          | 4.5                        | D                 | 10.6                       | C                 | 37.9                    | A              | 6.75              | C                     | Well Developed       | In Good Standing                | 
| 01M063 | 1        | P.S. 063 WILLIAM MCKINLEY      | Darlene Despeignes    | ICI                         | ESMS                 | Elementary School | 53.00       | F             | 26.5          | 7.6                        | B                 | 11.3                       | C                 | 7.6                     | F              | 0                 | C                     | Proficient           | In Good Standing                | 
| 01M064 | 1        | P.S. 064 ROBERT SIMON          | Sandra Litrico Pappas | ESO                         | ESMS                 | Elementary School | 60.63       | A             | 79.7          | 12.1                       | A                 | 18.9                       | A                 | 46.4                    | A              | 2.25              | C                     | Well Developed       | In Good Standing                | 
| 01M110 | 1        | P.S. 110 FLORENCE NIGHTINGALE  | Irene Quvus           | ESO                         | ESMS                 | Elementary School | 42.56       | C             | 41.2          | 9.4                        | A                 | 16.9                       | A                 | 13.4                    | D              | 1.5               | B                     | Well Developed       | In Good Standing                | 
| 01M134 | 1        | P.S. 134 HENRIETTA SZOLD       | Loretta Caputo        | ICI                         | ESMS                 | Elementary School | 54.03       | B             | 53            | 5.8                        | C                 | 14.4                       | B                 | 31.3                    | B              | 1.5               | B                     | Proficient           | In Good Standing                | 
| 01M137 | 1        | P.S. 137 JOHN L. BERNSTEIN     | Melissa Rodriguez     | ICI                         | ESMS                 | Elementary School | 61.63       | B             | 55.2          | 7.8                        | B                 | 16.1                       | A                 | 29.8                    | B              | 1.5               | B                     | Proficient           | In Good Standing                | 
| 01M140 | 1        | P.S. 140 NATHAN STRAUS         | Esteban Barrientos    | ESO                         | ESMS                 | K-8               | 62.46       | B             | 64.8          | 9                          | B                 | 15.3                       | B                 | 36                      | B              | 4.5               | B                     | Proficient           | In Need of Improvement - Year 1 | 
```