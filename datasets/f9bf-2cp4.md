# SAT Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sat-results-e88d7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/f9bf-2cp4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/f9bf-2cp4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/f9bf-2cp4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | f9bf-2cp4 |
| Name | SAT Results |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | sat result, nyc, school, lifelong learning |
| Created | 2013-02-21T03:28:53Z |
| Publication Date | 2013-02-21T03:29:02Z |

## Description

The most recent school level results for New York City on the SAT. Results are available at the school level for the graduating seniors of 2012. Records contain 2012 College-bound seniors mean SAT scores taken during SY 2012.

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                            | Data Type | Render Type |
| ======== | =========== | ============================== | =============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                      | meta_data | meta_data   |
| Yes      | series tag  | dbn                            | DBN                             | text      | text        |
| Yes      | series tag  | school_name                    | SCHOOL NAME                     | text      | text        |
| Yes      | series tag  | num_of_sat_test_takers         | Num of SAT Test Takers          | text      | text        |
| Yes      | series tag  | sat_critical_reading_avg_score | SAT Critical Reading Avg. Score | text      | text        |
| Yes      | series tag  | sat_math_avg_score             | SAT Math Avg. Score             | text      | text        |
| Yes      | series tag  | sat_writing_avg_score          | SAT Writing Avg. Score          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f9bf-2cp4 d:2013-02-20T19:29:00.000Z t:sat_math_avg_score=404 t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:num_of_sat_test_takers=29 t:sat_writing_avg_score=363 t:sat_critical_reading_avg_score=355 m:row_number.f9bf-2cp4=1

series e:f9bf-2cp4 d:2013-02-20T19:29:00.000Z t:sat_math_avg_score=423 t:school_name="UNIVERSITY NEIGHBORHOOD HIGH SCHOOL" t:dbn=01M448 t:num_of_sat_test_takers=91 t:sat_writing_avg_score=366 t:sat_critical_reading_avg_score=383 m:row_number.f9bf-2cp4=2

series e:f9bf-2cp4 d:2013-02-20T19:29:00.000Z t:sat_math_avg_score=402 t:school_name="EAST SIDE COMMUNITY SCHOOL" t:dbn=01M450 t:num_of_sat_test_takers=70 t:sat_writing_avg_score=370 t:sat_critical_reading_avg_score=377 m:row_number.f9bf-2cp4=3
```

## Meta Commands

```ls
metric m:row_number.f9bf-2cp4 p:long l:"Row Number"

entity e:f9bf-2cp4 l:"SAT Results" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/f9bf-2cp4

property e:f9bf-2cp4 t:meta.view v:id=f9bf-2cp4 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/E1C5E5DD-AA7E-4C60-A9FA-53E185AECB1C/0/2012SATPUBLICWEBSITE.xlsx v:averageRating=0 v:name="SAT Results" v:attribution="Department of Education (DOE)"

property e:f9bf-2cp4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:f9bf-2cp4 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | dbn    | school_name                                                    | num_of_sat_test_takers | sat_critical_reading_avg_score | sat_math_avg_score | sat_writing_avg_score | 
| =========== | ====== | ============================================================== | ====================== | ============================== | ================== | ===================== | 
| 1361388540  | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES                  | 29                     | 355                            | 404                | 363                   | 
| 1361388540  | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL                            | 91                     | 383                            | 423                | 366                   | 
| 1361388540  | 01M450 | EAST SIDE COMMUNITY SCHOOL                                     | 70                     | 377                            | 402                | 370                   | 
| 1361388540  | 01M458 | FORSYTH SATELLITE ACADEMY                                      | 7                      | 414                            | 401                | 359                   | 
| 1361388540  | 01M509 | MARTA VALLE HIGH SCHOOL                                        | 44                     | 390                            | 433                | 384                   | 
| 1361388540  | 01M515 | LOWER EAST SIDE PREPARATORY HIGH SCHOOL                        | 112                    | 332                            | 557                | 316                   | 
| 1361388540  | 01M539 | NEW EXPLORATIONS INTO SCIENCE, TECHNOLOGY AND MATH HIGH SCHOOL | 159                    | 522                            | 574                | 525                   | 
| 1361388540  | 01M650 | CASCADES HIGH SCHOOL                                           | 18                     | 417                            | 418                | 411                   | 
| 1361388540  | 01M696 | BARD HIGH SCHOOL EARLY COLLEGE                                 | 130                    | 624                            | 604                | 628                   | 
| 1361388540  | 02M047 | 47 THE AMERICAN SIGN LANGUAGE AND ENGLISH SECONDARY SCHOOL     | 16                     | 395                            | 400                | 387                   | 
```