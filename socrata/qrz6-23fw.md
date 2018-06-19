# Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-school-level-classes-2010-2011-regents-based-math-ela-apm-gender-b9e76) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qrz6-23fw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qrz6-23fw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qrz6-23fw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qrz6-23fw |
| Name | Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, apm, gender, lifelong learning |
| Created | 2013-02-21T02:33:43Z |
| Publication Date | 2013-02-21T02:33:57Z |

## Description

Latest available data and trends in NYSED's Regents-based Aspirational Performance Measure (APM) by school and Gender

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
series e:qrz6-23fw d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=s t:pct_of_graduates_achieving_apm=s t:demographic=Female t:num_achieving_apm=s m:total_grads_num=17 m:total_cohort_num=34

series e:qrz6-23fw d:2007-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=s t:pct_of_graduates_achieving_apm=s t:demographic=Female t:num_achieving_apm=s m:total_grads_num=18 m:total_cohort_num=30

series e:qrz6-23fw d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=11.40% t:pct_of_graduates_achieving_apm=19.20% t:demographic=Male t:num_achieving_apm=5 m:total_grads_num=26 m:total_cohort_num=44
```

## Meta Commands

```ls
metric m:total_cohort_num p:integer l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:integer l:"Total Grads Num" t:dataTypeName=number

entity e:qrz6-23fw l:"Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qrz6-23fw

property e:qrz6-23fw t:meta.view v:id=qrz6-23fw v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/193BBD8A-5DE1-4EEE-B49B-C8C45357441B/0/Graduation_Rates_Public_School_Apm.xls v:averageRating=0 v:name="Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Gender" v:attribution="Department of Education (DOE)"

property e:qrz6-23fw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qrz6-23fw t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_name                                   | cohort_year | demographic | total_cohort_num | total_grads_num | num_achieving_apm | pct_of_cohort_achieving_apm | pct_of_graduates_achieving_apm | 
| ====== | ============================================= | =========== | =========== | ================ | =============== | ================= | =========================== | ============================== | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | Female      | 34               | 17              | s                 | s                           | s                              | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | Female      | 30               | 18              | s                 | s                           | s                              | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2006        | Male        | 44               | 26              | 5                 | 11.40%                      | 19.20%                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2007        | Male        | 47               | 23              | 4                 | 8.50%                       | 17.40%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | Female      | 65               | 34              | 11                | 16.90%                      | 32.40%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | Female      | 62               | 42              | 7                 | 11.30%                      | 16.70%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2006        | Male        | 59               | 19              | s                 | s                           | s                              | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL           | 2007        | Male        | 88               | 57              | 12                | 13.60%                      | 21.10%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2006        | Female      | 45               | 31              | 11                | 24.40%                      | 35.50%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                  | 2007        | Female      | 36               | 20              | s                 | s                           | s                              | 
```