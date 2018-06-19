# School Progress Reports - All Schools - 2010-11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-reports-all-schools-2010-11-4e4e9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yig9-9zum) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yig9-9zum/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yig9-9zum/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yig9-9zum |
| Name | School Progress Reports - All Schools - 2010-11 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T20:12:51Z |
| Publication Date | 2011-10-11T18:26:33Z |

## Description

2010/11 Progress Report results for all schools (As of 9/23/2011)

Peer indexes are calculated differently depending on School Level.  Schools are only compared to other schools in the same School Level (e.g., Elementary, K-8, Middle, High, Transfer)

1) Elementary, K-8, Early Childhood - peer index is a value from 0-100.  A composite demographic statistic based on % ELL, % Students with Disabilities, % Title I free lunch, and % Black/Hispanic is used.  Higher values indicate student populations with higher need.

2) Middle - peer index is a value from 1.00-4.50.  For middle schools, the average 4th grade proficiency ratings in ELA and Math and the % Students with Disabilities is used. Lower values indicate student populations with higher need.

3) High School - peer index is a value from 1.00-4.50. For high schools, the average 8th grade proficiency, the % Students with Disabilities, the % Self-contained, and the % overage is used. Lower values indicate student populations with higher need.

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
| Yes      | series tag     | overall_grade              | 2010-2011 OVERALL GRADE              | text      | text        |
| Yes      | numeric metric | overall_score              | 2010-2011 OVERALL SCORE              | number    | number      |
| Yes      | numeric metric | environment_category_score | 2010-2011 ENVIRONMENT CATEGORY SCORE | number    | number      |
| Yes      | series tag     | environment_grade          | 2010-2011 ENVIRONMENT GRADE          | text      | text        |
| Yes      | numeric metric | performance_category_score | 2010-2011 PERFORMANCE CATEGORY SCORE | number    | number      |
| Yes      | series tag     | performance_grade          | 2010-2011 PERFORMANCE GRADE          | text      | text        |
| Yes      | numeric metric | progress_category_score    | 2010-2011 PROGRESS CATEGORY SCORE    | number    | number      |
| Yes      | series tag     | progress_grade             | 2010-2011 PROGRESS GRADE             | text      | text        |
| Yes      | numeric metric | additional_credit          | 2010-2011 ADDITIONAL CREDIT          | number    | number      |
| Yes      | series tag     | progress_report_grade      | 2009-10 PROGRESS REPORT GRADE        | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yig9-9zum d:2010-01-01T00:00:00.000Z t:performance_grade=D t:school="P.S. 015 Roberto Clemente" t:principal="Irene Sanchez" t:dbn=01M015 t:school_level_=Elementary t:progress_grade=C t:progress_report_type=EMS t:progress_report_grade=C t:overall_grade=C t:district=1 t:environment_grade=B m:additional_credit=0.5 m:performance_category_score=2.1 m:peer_index_=63.61 m:environment_category_score=6.4 m:progress_category_score=18 m:overall_score=27

series e:yig9-9zum d:2010-01-01T00:00:00.000Z t:performance_grade=D t:school="P.S. 019 Asher Levy" t:principal="Jacqueline Flanagan" t:dbn=01M019 t:school_level_=Elementary t:progress_grade=A t:progress_report_type=EMS t:progress_report_grade=C t:overall_grade=B t:district=1 t:environment_grade=B m:additional_credit=0.5 m:performance_category_score=5.2 m:peer_index_=49.48 m:environment_category_score=7.8 m:progress_category_score=35.1 m:overall_score=48.7

series e:yig9-9zum d:2010-01-01T00:00:00.000Z t:performance_grade=C t:school="P.S. 020 Anna Silver" t:principal="James Lee" t:dbn=01M020 t:school_level_=Elementary t:progress_grade=B t:progress_report_type=EMS t:progress_report_grade=A t:overall_grade=B t:district=1 t:environment_grade=B m:additional_credit=2 m:performance_category_score=7.4 m:peer_index_=56.65 m:environment_category_score=7.7 m:progress_category_score=31.1 m:overall_score=48.2
```

## Meta Commands

```ls
metric m:peer_index_ p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:overall_score p:float l:"2010-2011 OVERALL SCORE" t:dataTypeName=number

metric m:environment_category_score p:float l:"2010-2011 ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:float l:"2010-2011 PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:float l:"2010-2011 PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:float l:"2010-2011 ADDITIONAL CREDIT" t:dataTypeName=number

entity e:yig9-9zum l:"School Progress Reports - All Schools - 2010-11" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/yig9-9zum

property e:yig9-9zum t:meta.view v:id=yig9-9zum v:category=Education v:averageRating=0 v:name="School Progress Reports - All Schools - 2010-11" v:attribution="Department of Education (DOE)"

property e:yig9-9zum t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yig9-9zum t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | district | school                         | principal             | progress_report_type | school_level_ | peer_index_ | overall_grade | overall_score | environment_category_score | environment_grade | performance_category_score | performance_grade | progress_category_score | progress_grade | additional_credit | progress_report_grade | 
| ====== | ======== | ============================== | ===================== | ==================== | ============= | =========== | ============= | ============= | ========================== | ================= | ========================== | ================= | ======================= | ============== | ================= | ===================== | 
| 01M015 | 1        | P.S. 015 Roberto Clemente      | Irene Sanchez         | EMS                  | Elementary    | 63.61       | C             | 27.0          | 6.4                        | B                 | 2.1                        | D                 | 18.0                    | C              | 0.5               | C                     | 
| 01M019 | 1        | P.S. 019 Asher Levy            | Jacqueline Flanagan   | EMS                  | Elementary    | 49.48       | B             | 48.7          | 7.8                        | B                 | 5.2                        | D                 | 35.1                    | A              | 0.5               | C                     | 
| 01M020 | 1        | P.S. 020 Anna Silver           | James Lee             | EMS                  | Elementary    | 56.65       | B             | 48.2          | 7.7                        | B                 | 7.4                        | C                 | 31.1                    | B              | 2.0               | A                     | 
| 01M034 | 1        | P.S. 034 Franklin D. Roosevelt | Joyce Stallings Harte | EMS                  | K-8           | 67.97       | C             | 39.8          | 7.5                        | B                 | 11.3                       | B                 | 18.5                    | C              | 2.5               | B                     | 
| 01M063 | 1        | P.S. 063 William McKinley      | Darlene Despeignes    | EMS                  | Elementary    | 58.85       | B             | 49.0          | 8.1                        | B                 | 10.4                       | B                 | 29.0                    | B              | 1.5               | B                     | 
| 01M064 | 1        | P.S. 064 Robert Simon          | Marlon L. Hosang      | EMS                  | Elementary    | 60.73       | C             | 25.8          | 9.7                        | A                 | 4.5                        | D                 | 11.6                    | D              | 0.0               | C                     | 
| 01M110 | 1        | P.S. 110 Florence Nightingale  | Karen Feuer           | EMS                  | Elementary    | 40.85       | C             | 38.1          | 4.1                        | C                 | 10.9                       | B                 | 22.1                    | C              | 1.0               | D                     | 
| 01M134 | 1        | P.S. 134 Henrietta Szold       | Loretta Caputo        | EMS                  | Elementary    | 54.33       | C             | 34.6          | 4.2                        | C                 | 5.9                        | C                 | 24.0                    | C              | 0.5               | B                     | 
| 01M137 | 1        | P.S. 137 John L. Bernstein     | Melissa Rodriguez     | EMS                  | Elementary    | 57.88       | F             | 17.6          | 5.1                        | C                 | 4.8                        | D                 | 6.7                     | F              | 1.0               | C                     | 
| 01M140 | 1        | P.S. 140 Nathan Straus         | Esteban Barrientos    | EMS                  | K-8           | 61.28       | D             | 23.6          | 8.4                        | B                 | 5.1                        | D                 | 9.6                     | D              | 0.5               | B                     | 
```