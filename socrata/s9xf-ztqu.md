# Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-school-level-classes-2010-2011-regents-based-math-ela-apm-ell-d9b74) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s9xf-ztqu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s9xf-ztqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s9xf-ztqu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s9xf-ztqu |
| Name | Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, apm, ell, lifelong learning |
| Created | 2013-02-21T02:33:02Z |
| Publication Date | 2013-02-21T02:33:26Z |

## Description

Latest available data and trends in NYSED's Regents-based Aspirational Performance Measure (APM) by school and ELL status.

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
series e:s9xf-ztqu d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=s t:pct_of_graduates_achieving_apm=s t:demographic="English Language Learner" t:num_achieving_apm=s m:total_grads_num=3 m:total_cohort_num=5

series e:s9xf-ztqu d:2007-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=s t:pct_of_graduates_achieving_apm=s t:demographic="English Language Learner" t:num_achieving_apm=s m:total_grads_num=2 m:total_cohort_num=9

series e:s9xf-ztqu d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=8.20% t:pct_of_graduates_achieving_apm=15.00% t:demographic="English Language Proficient" t:num_achieving_apm=6 m:total_grads_num=40 m:total_cohort_num=73
```

## Meta Commands

```ls
metric m:total_cohort_num p:integer l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:integer l:"Total Grads Num" t:dataTypeName=number

entity e:s9xf-ztqu l:"Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/s9xf-ztqu

property e:s9xf-ztqu t:meta.view v:id=s9xf-ztqu v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/193BBD8A-5DE1-4EEE-B49B-C8C45357441B/0/Graduation_Rates_Public_School_Apm.xls v:averageRating=0 v:name="Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - ELL" v:attribution="Department of Education (DOE)"

property e:s9xf-ztqu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s9xf-ztqu t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_name                                   | cohort_year | demographic                 | total_cohort_num | total_grads_num | num_achieving_apm | pct_of_cohort_achieving_apm | pct_of_graduates_achieving_apm | 
| ====== | ============================================= | =========== | =========================== | ================ | =============== | ================= | =========================== | ============================== | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | English Language Learner    | 5                | 3               | s                 | s                           | s                              | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | English Language Learner    | 9                | 2               | s                 | s                           | s                              | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | English Language Proficient | 73               | 40              | 6                 | 8.20%                       | 15.00%                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | English Language Proficient | 68               | 39              | 5                 | 7.40%                       | 12.80%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | English Language Learner    | 3                | 1               | s                 | s                           | s                              | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | English Language Learner    | 11               | 6               | s                 | s                           | s                              | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | English Language Proficient | 121              | 52              | 16                | 13.20%                      | 30.80%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | English Language Proficient | 139              | 93              | 19                | 13.70%                      | 20.40%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2006        | English Language Learner    | 12               | 3               | s                 | s                           | s                              | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2007        | English Language Learner    | 13               | 2               | s                 | s                           | s                              | 
```