# Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-school-level-classes-2010-2011-regents-based-math-ela-apm-swd-9a515) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5gxs-yzxw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5gxs-yzxw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5gxs-yzxw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5gxs-yzxw |
| Name | Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, apm, swd, lifelong learning |
| Created | 2013-02-21T02:33:58Z |
| Publication Date | 2013-02-21T02:34:11Z |

## Description

Latest available data and trends in NYSED's Regents-based Aspirational Performance Measure (APM) by school and disability status

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | dbn                            | DBN                            | text      | text        |
| Yes      | series tag     | school_name                    | School Name                    | text      | text        |
| Yes      | time           | cohort_year                    | Cohort Year                    | number    | text        |
| Yes      | series tag     | demographic                    | Demographic                    | text      | text        |
| Yes      | numeric metric | total_cohort_num               | Total Cohort Num               | number    | text        |
| Yes      | numeric metric | total_grads_num                | Total Grads Num                | number    | text        |
| Yes      | series tag     | num_achieving_apm              | Num achieving APM              | text      | text        |
| Yes      | series tag     | pct_of_cohort_achieving_apm    | Pct of cohort achieving APM    | text      | text        |
| Yes      | series tag     | pct_of_graduates_achieving_apm | Pct of graduates achieving APM | text      | text        |
```

## Time Field

```ls
Value = cohort_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5gxs-yzxw d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=11.70% t:pct_of_graduates_achieving_apm=18.40% t:demographic="Not Student with Disability" t:num_achieving_apm=7 m:total_grads_num=38 m:total_cohort_num=60

series e:5gxs-yzxw d:2007-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=7.10% t:pct_of_graduates_achieving_apm=12.90% t:demographic="Not Student with Disability" t:num_achieving_apm=4 m:total_grads_num=31 m:total_cohort_num=56

series e:5gxs-yzxw d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=s t:pct_of_graduates_achieving_apm=s t:demographic="Student with Disability" t:num_achieving_apm=s m:total_grads_num=5 m:total_cohort_num=18
```

## Meta Commands

```ls
metric m:total_cohort_num p:integer l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:integer l:"Total Grads Num" t:dataTypeName=number

entity e:5gxs-yzxw l:"Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/5gxs-yzxw

property e:5gxs-yzxw t:meta.view v:id=5gxs-yzxw v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/193BBD8A-5DE1-4EEE-B49B-C8C45357441B/0/Graduation_Rates_Public_School_Apm.xls v:averageRating=0 v:name="Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - SWD" v:attribution="Department of Education (DOE)"

property e:5gxs-yzxw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5gxs-yzxw t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_name                                   | cohort_year | demographic                 | total_cohort_num | total_grads_num | num_achieving_apm | pct_of_cohort_achieving_apm | pct_of_graduates_achieving_apm | 
| ====== | ============================================= | =========== | =========================== | ================ | =============== | ================= | =========================== | ============================== | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | Not Student with Disability | 60               | 38              | 7                 | 11.70%                      | 18.40%                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | Not Student with Disability | 56               | 31              | 4                 | 7.10%                       | 12.90%                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | Student with Disability     | 18               | 5               | s                 | s                           | s                              | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | Student with Disability     | 21               | 10              | s                 | s                           | s                              | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | Not Student with Disability | 99               | 48              | 16                | 16.20%                      | 33.30%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | Not Student with Disability | 108              | 83              | 19                | 17.60%                      | 22.90%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | Student with Disability     | 25               | 5               | s                 | s                           | s                              | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | Student with Disability     | 42               | 16              | s                 | s                           | s                              | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2006        | Not Student with Disability | 71               | 43              | 14                | 19.70%                      | 32.60%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2007        | Not Student with Disability | 79               | 41              | 6                 | 7.60%                       | 14.60%                         | 
```