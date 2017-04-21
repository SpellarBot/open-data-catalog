# Graduation Outcomes - School Level - Classes of 2005-2011 - Total Cohort

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-school-level-classes-of-2005-2011-total-cohort-7f58c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cma4-zi8m) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cma4-zi8m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cma4-zi8m/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cma4-zi8m |
| Name | Graduation Outcomes - School Level - Classes of 2005-2011 - Total Cohort |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, total cohort, lifelong learning |
| Created | 2013-02-21T02:39:42Z |
| Publication Date | 2013-02-21T02:40:26Z |

## Description

Latest available data and trends in graduation and dropout outcomes by school.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | dbn                                | DBN                                | text      | text        |
| Yes      | series tag     | school_name                        | School Name                        | text      | text        |
| Yes      | time           | cohort_year                        | Cohort Year                        | number    | text        |
| Yes      | series tag     | cohort_category                    | Cohort Category                    | text      | text        |
| Yes      | numeric metric | total_cohort_num                   | Total Cohort Num                   | number    | text        |
| Yes      | series tag     | total_grads_num                    | Total Grads Num                    | text      | text        |
| Yes      | series tag     | total_grads_pct_of_cohort          | Total Grads Pct of cohort          | text      | text        |
| Yes      | series tag     | total_regents_num                  | Total Regents Num                  | text      | text        |
| Yes      | series tag     | total_regents_pct_of_cohort        | Total Regents Pct of cohort        | text      | text        |
| Yes      | series tag     | total_regents_pct_of_grads         | Total Regents Pct of grads         | text      | text        |
| Yes      | series tag     | advanced_regents_num               | Advanced Regents Num               | text      | text        |
| Yes      | series tag     | advanced_regents_pct_of_cohort     | Advanced Regents Pct of cohort     | text      | text        |
| Yes      | series tag     | advanced_regents_pct_of_grads      | Advanced Regents Pct of grads      | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_num           | Regents w/o Advanced Num           | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_pct_of_cohort | Regents w/o Advanced Pct of cohort | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_pct_of_grads  | Regents w/o Advanced Pct of grads  | text      | text        |
| Yes      | series tag     | local_num                          | Local Num                          | text      | text        |
| Yes      | series tag     | local_pct_of_cohort                | Local Pct of cohort                | text      | text        |
| Yes      | series tag     | local_pct_of_grads                 | Local Pct of grads                 | text      | text        |
| Yes      | series tag     | still_enrolled_num                 | Still Enrolled Num                 | text      | text        |
| Yes      | series tag     | still_enrolled_pct_of_cohort       | Still Enrolled Pct of cohort       | text      | text        |
| Yes      | series tag     | dropped_out_num                    | Dropped Out Num                    | text      | text        |
| Yes      | series tag     | dropped_out_pct_of_cohort          | Dropped Out Pct of cohort          | text      | text        |
```

## Time Field

```ls
Value = cohort_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cma4-zi8m d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=s t:school_name="CORLEARS SCHOOL" t:regents_w_o_advanced_num=s t:advanced_regents_num=s t:cohort_category="4 Year  June" t:local_pct_of_cohort=s t:advanced_regents_pct_of_grads=s t:regents_w_o_advanced_pct_of_grads=s t:advanced_regents_pct_of_cohort=s t:still_enrolled_num=s t:dropped_out_num=s t:dbn=01M056 t:dropped_out_pct_of_cohort=s t:total_grads_pct_of_cohort=s t:local_num=s t:total_grads_num=s t:total_regents_pct_of_cohort=s t:total_regents_pct_of_grads=s t:total_regents_num=s t:still_enrolled_pct_of_cohort=s t:local_pct_of_grads=s m:total_cohort_num=1

series e:cma4-zi8m d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=s t:school_name="CORLEARS SCHOOL" t:regents_w_o_advanced_num=s t:advanced_regents_num=s t:cohort_category="5 Year" t:local_pct_of_cohort=s t:advanced_regents_pct_of_grads=s t:regents_w_o_advanced_pct_of_grads=s t:advanced_regents_pct_of_cohort=s t:still_enrolled_num=s t:dropped_out_num=s t:dbn=01M056 t:dropped_out_pct_of_cohort=s t:total_grads_pct_of_cohort=s t:local_num=s t:total_grads_num=s t:total_regents_pct_of_cohort=s t:total_regents_pct_of_grads=s t:total_regents_num=s t:still_enrolled_pct_of_cohort=s t:local_pct_of_grads=s m:total_cohort_num=1

series e:cma4-zi8m d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=s t:school_name="CORLEARS SCHOOL" t:regents_w_o_advanced_num=s t:advanced_regents_num=s t:cohort_category="6 Year" t:local_pct_of_cohort=s t:advanced_regents_pct_of_grads=s t:regents_w_o_advanced_pct_of_grads=s t:advanced_regents_pct_of_cohort=s t:still_enrolled_num=s t:dropped_out_num=s t:dbn=01M056 t:dropped_out_pct_of_cohort=s t:total_grads_pct_of_cohort=s t:local_num=s t:total_grads_num=s t:total_regents_pct_of_cohort=s t:total_regents_pct_of_grads=s t:total_regents_num=s t:still_enrolled_pct_of_cohort=s t:local_pct_of_grads=s m:total_cohort_num=1
```

## Meta Commands

```ls
metric m:total_cohort_num p:integer l:"Total Cohort Num" t:dataTypeName=number

entity e:cma4-zi8m l:"Graduation Outcomes - School Level - Classes of 2005-2011 - Total Cohort" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/cma4-zi8m

property e:cma4-zi8m t:meta.view v:id=cma4-zi8m v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/7F2B22CA-B920-4F47-8BEF-876A568933A6/0/Graduation_Rates_Public_School.xls v:averageRating=0 v:name="Graduation Outcomes - School Level - Classes of 2005-2011 - Total Cohort" v:attribution="Department of Education (DOE)"

property e:cma4-zi8m t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cma4-zi8m t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | school_name                                   | cohort_year | cohort_category | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| ====== | ============================================= | =========== | =============== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 01M056 | CORLEARS SCHOOL                               | 2001        | 4 Year June     | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M056 | CORLEARS SCHOOL                               | 2001        | 5 Year          | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M056 | CORLEARS SCHOOL                               | 2001        | 6 Year          | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M056 | CORLEARS SCHOOL                               | 2003        | 4 Year June     | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M056 | CORLEARS SCHOOL                               | 2003        | 5 Year          | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M056 | CORLEARS SCHOOL                               | 2003        | 6 Year          | 1                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2003        | 4 Year June     | 5                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2003        | 5 Year          | 5                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2003        | 6 Year          | 5                | s               | s                         | s                 | s                           | s                          | s                    | s                              | s                             | s                        | s                                  | s                                 | s         | s                   | s                  | s                  | s                            | s               | s                         | 
| 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL STUDIES | 2004        | 4 Year June     | 55               | 37              | 67.30%                    | 17                | 30.90%                      | 45.90%                     | 0                    | 0.00%                          | 0.00%                         | 17                       | 30.90%                             | 45.90%                            | 20        | 36.40%              | 54.10%             | 15                 | 27.30%                       | 3               | 5.50%                     | 
```