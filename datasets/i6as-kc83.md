# Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Total Cohort

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-school-level-classes-2010-2011-regents-based-math-ela-apm-total-cohort-c30da) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i6as-kc83) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i6as-kc83/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i6as-kc83/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i6as-kc83 |
| Name | Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Total Cohort |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, apm, total cohort, lifelong learning |
| Created | 2013-02-21T02:34:12Z |
| Publication Date | 2013-02-21T02:34:21Z |

## Description

Latest available data and trends in graduation and dropout outcomes school.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | dbn                            | DBN                            | text      | text        |
| Yes      | series tag     | school_name                    | School Name                    | text      | text        |
| Yes      | time           | cohort_year                    | Cohort Year                    | number    | text        |
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
series e:i6as-kc83 d:2006-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=9.00% t:pct_of_graduates_achieving_apm=16.30% t:num_achieving_apm=7 m:total_grads_num=43 m:total_cohort_num=78

series e:i6as-kc83 d:2007-01-01T00:00:00.000Z t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES" t:dbn=01M292 t:pct_of_cohort_achieving_apm=6.50% t:pct_of_graduates_achieving_apm=12.20% t:num_achieving_apm=5 m:total_grads_num=41 m:total_cohort_num=77

series e:i6as-kc83 d:2006-01-01T00:00:00.000Z t:school_name="UNIVERSITY NEIGHBORHOOD HIGH SCHOOL" t:dbn=01M448 t:pct_of_cohort_achieving_apm=13.70% t:pct_of_graduates_achieving_apm=32.10% t:num_achieving_apm=17 m:total_grads_num=53 m:total_cohort_num=124
```

## Meta Commands

```ls
metric m:total_cohort_num p:integer l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:integer l:"Total Grads Num" t:dataTypeName=number

entity e:i6as-kc83 l:"Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Total Cohort" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/i6as-kc83

property e:i6as-kc83 t:meta.view v:id=i6as-kc83 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/193BBD8A-5DE1-4EEE-B49B-C8C45357441B/0/Graduation_Rates_Public_School_Apm.xls v:averageRating=0 v:name="Graduation Outcomes - School Level - Classes 2010-2011 - Regents-based Math/ELA APM - Total Cohort" v:attribution="Department of Education (DOE)"

property e:i6as-kc83 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i6as-kc83 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_name                                        | cohort_year | total_cohort_num | total_grads_num | num_achieving_apm | pct_of_cohort_achieving_apm | pct_of_graduates_achieving_apm | 
| ====== | ================================================== | =========== | ================ | =============== | ================= | =========================== | ============================== | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES      | 2006        | 78               | 43              | 7                 | 9.00%                       | 16.30%                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES      | 2007        | 77               | 41              | 5                 | 6.50%                       | 12.20%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL                | 2006        | 124              | 53              | 17                | 13.70%                      | 32.10%                         | 
| 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL                | 2007        | 150              | 99              | 19                | 12.70%                      | 19.20%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                       | 2006        | 84               | 47              | 14                | 16.70%                      | 29.80%                         | 
| 01M509 | MARTA VALLE SECONDARY SCHOOL                       | 2007        | 95               | 47              | 6                 | 6.30%                       | 12.80%                         | 
| 01M515 | LOWER EAST SIDE PREPARATORY HIGH SCHOOL            | 2006        | 193              | 105             | 63                | 32.60%                      | 60.00%                         | 
| 01M515 | LOWER EAST SIDE PREPARATORY HIGH SCHOOL            | 2007        | 235              | 74              | 45                | 19.10%                      | 60.80%                         | 
| 01M539 | NEW EXPLORATIONS INTO SCIENCE,TECH AND MATH SCHOOL | 2006        | 46               | 46              | 42                | 91.30%                      | 91.30%                         | 
| 01M539 | NEW EXPLORATIONS INTO SCIENCE,TECH AND MATH SCHOOL | 2007        | 128              | 122             | 99                | 77.30%                      | 81.10%                         | 
```