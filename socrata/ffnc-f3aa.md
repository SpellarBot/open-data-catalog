# School Progress Reports - All Schools - 2009-10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-reports-all-schools-2009-10-76b5c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ffnc-f3aa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ffnc-f3aa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ffnc-f3aa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ffnc-f3aa |
| Name | School Progress Reports - All Schools - 2009-10 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T20:20:00Z |
| Publication Date | 2011-10-11T18:29:04Z |

## Description

2009/10 Progress Report results for all schools (data as of 2/2/2011)

Peer indexes are calculated differently depending on School Level.  Schools are only compared to other schools in the same School Level (e.g., Elementary, K-8, Middle, High, Transfer)

1) Elementary, K-8, K-3, K-2 - peer index is a value from 0-100.  We use a composite demographic statistic based on % ELL, % SpEd, % Title I free lunch, and % Black/Hispanic.  Higher values indicate student populations with higher need.

2) Middle - peer index is a value from 1.00-4.50.  For middle schools, we use the average 4th grade proficiency ratings in ELA and Math and the % SpEd. Lower values indicate student populations with higher need.

3) High School - peer index is a value from 1.00-4.50. For high schools, we use the average 8th grade proficiency, the % SpEd, the % Self-contained, and the % overage. Lower values indicate student populations with higher need.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                                 | Data Type | Render Type |
| ======== | ============== | ========================== | ==================================== | ========= | =========== |
| Yes      | series tag     | dbn                        | DBN                                  | text      | text        |
| Yes      | series tag     | district                   | DISTRICT                             | text      | number      |
| Yes      | series tag     | school                     | SCHOOL                               | text      | text        |
| Yes      | series tag     | principal                  | PRINCIPAL                            | text      | text        |
| Yes      | series tag     | progress_report_type       | PROGRESS REPORT TYPE                 | text      | text        |
| Yes      | series tag     | school_level_              | SCHOOL LEVEL*                        | text      | text        |
| Yes      | numeric metric | peer_index_                | PEER INDEX*                          | number    | number      |
| Yes      | series tag     | overall_grade              | 2009-2010 OVERALL GRADE              | text      | text        |
| Yes      | numeric metric | overall_score              | 2009-2010 OVERALL SCORE              | number    | number      |
| Yes      | numeric metric | environment_category_score | 2009-2010 ENVIRONMENT CATEGORY SCORE | number    | number      |
| Yes      | series tag     | environment_grade          | 2009-2010 ENVIRONMENT GRADE          | text      | text        |
| Yes      | numeric metric | performance_category_score | 2009-2010 PERFORMANCE CATEGORY SCORE | number    | number      |
| Yes      | series tag     | performance_grade          | 2009-2010 PERFORMANCE GRADE          | text      | text        |
| Yes      | numeric metric | progress_category_score    | 2009-2010 PROGRESS CATEGORY SCORE    | number    | number      |
| Yes      | series tag     | progress_grade             | 2009-2010 PROGRESS GRADE             | text      | text        |
| Yes      | numeric metric | additional_credit          | 2009-2010 ADDITIONAL CREDIT          | number    | number      |
| Yes      | series tag     | progress_report_grade      | 2008-09 PROGRESS REPORT GRADE        | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ffnc-f3aa d:2009-01-01T00:00:00.000Z t:performance_grade=D t:school="P.S. 015 Roberto Clemente" t:principal="Thomas Staebell" t:dbn=01M015 t:school_level_=Elementary t:progress_grade=B t:progress_report_type=EMS t:progress_report_grade=B t:overall_grade=C t:district=1 t:environment_grade=B m:additional_credit=0 m:performance_category_score=3 m:peer_index_=62.65 m:environment_category_score=7.2 m:progress_category_score=27.4 m:overall_score=37.6

series e:ffnc-f3aa d:2009-01-01T00:00:00.000Z t:performance_grade=D t:school="P.S. 019 Asher Levy" t:principal="Jacqueline Flanagan" t:dbn=01M019 t:school_level_=Elementary t:progress_grade=B t:progress_report_type=EMS t:progress_report_grade=A t:overall_grade=C t:district=1 t:environment_grade=B m:additional_credit=0 m:performance_category_score=4.9 m:peer_index_=48.94 m:environment_category_score=6.4 m:progress_category_score=24.4 m:overall_score=35.7

series e:ffnc-f3aa d:2009-01-01T00:00:00.000Z t:performance_grade=C t:school="P.S. 020 Anna Silver" t:principal="James Lee" t:dbn=01M020 t:school_level_=Elementary t:progress_grade=A t:progress_report_type=EMS t:progress_report_grade=A t:overall_grade=A t:district=1 t:environment_grade=A m:additional_credit=9 m:performance_category_score=7.9 m:peer_index_=57.68 m:environment_category_score=9.3 m:progress_category_score=44.1 m:overall_score=70.3
```

## Meta Commands

```ls
metric m:peer_index_ p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:overall_score p:float l:"2009-2010 OVERALL SCORE" t:dataTypeName=number

metric m:environment_category_score p:float l:"2009-2010 ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:float l:"2009-2010 PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:float l:"2009-2010 PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:float l:"2009-2010 ADDITIONAL CREDIT" t:dataTypeName=number

entity e:ffnc-f3aa l:"School Progress Reports - All Schools - 2009-10" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ffnc-f3aa

property e:ffnc-f3aa t:meta.view v:id=ffnc-f3aa v:category=Education v:averageRating=0 v:name="School Progress Reports - All Schools - 2009-10" v:attribution="Department of Education (DOE)"

property e:ffnc-f3aa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ffnc-f3aa t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | district | school                         | principal             | progress_report_type | school_level_ | peer_index_ | overall_grade | overall_score | environment_category_score | environment_grade | performance_category_score | performance_grade | progress_category_score | progress_grade | additional_credit | progress_report_grade | 
| ====== | ======== | ============================== | ===================== | ==================== | ============= | =========== | ============= | ============= | ========================== | ================= | ========================== | ================= | ======================= | ============== | ================= | ===================== | 
| 01M015 | 1        | P.S. 015 Roberto Clemente      | Thomas Staebell       | EMS                  | Elementary    | 62.65       | C             | 37.6          | 7.2                        | B                 | 3.0                        | D                 | 27.4                    | B              | 0.0               | B                     | 
| 01M019 | 1        | P.S. 019 Asher Levy            | Jacqueline Flanagan   | EMS                  | Elementary    | 48.94       | C             | 35.7          | 6.4                        | B                 | 4.9                        | D                 | 24.4                    | B              | 0.0               | A                     | 
| 01M020 | 1        | P.S. 020 Anna Silver           | James Lee             | EMS                  | Elementary    | 57.68       | A             | 70.3          | 9.3                        | A                 | 7.9                        | C                 | 44.1                    | A              | 9.0               | A                     | 
| 01M034 | 1        | P.S. 034 Franklin D. Roosevelt | Joyce Stallings Harte | EMS                  | K-8           | 66.75       | B             | 53.0          | 6.8                        | B                 | 7.4                        | C                 | 33.0                    | B              | 5.8               | A                     | 
| 01M063 | 1        | P.S. 063 William McKinley      | Darlene Despeignes    | EMS                  | Elementary    | 57.55       | B             | 54.0          | 7.8                        | B                 | 7.1                        | C                 | 35.8                    | A              | 3.3               | B                     | 
| 01M064 | 1        | P.S. 064 Robert Simon          | Marlon L. Hosang      | EMS                  | Elementary    | 61.50       | C             | 31.0          | 10.3                       | A                 | 5.4                        | D                 | 15.3                    | D              | 0.0               | A                     | 
| 01M110 | 1        | P.S. 110 Florence Nightingale  | Karen Feuer           | EMS                  | Elementary    | 42.47       | D             | 25.4          | 5.2                        | C                 | 8.8                        | C                 | 11.4                    | D              | 0.0               | B                     | 
| 01M134 | 1        | P.S. 134 Henrietta Szold       | Loretta Caputo        | EMS                  | Elementary    | 53.05       | B             | 54.2          | 4.9                        | C                 | 4.1                        | D                 | 41.4                    | A              | 3.8               | B                     | 
| 01M137 | 1        | P.S. 137 John L. Bernstein     | Melissa Rodriguez     | EMS                  | Elementary    | 58.66       | C             | 20.1          | 6.8                        | B                 | 5.5                        | D                 | 7.8                     | F              | 0.0               | A                     | 
| 01M140 | 1        | P.S. 140 Nathan Straus         | Esteban Barrientos    | EMS                  | K-8           | 61.90       | B             | 43.0          | 8.5                        | A                 | 7.2                        | C                 | 26.5                    | B              | 0.8               | A                     | 
```