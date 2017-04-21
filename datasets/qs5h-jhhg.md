# Graduation Outcomes - Borough - Classes of 2005-2011 - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-borough-classes-of-2005-2011-ell-7271a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qs5h-jhhg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qs5h-jhhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qs5h-jhhg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qs5h-jhhg |
| Name | Graduation Outcomes - Borough - Classes of 2005-2011 - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, borough, ell, lifelong learning |
| Created | 2013-02-21T02:30:42Z |
| Publication Date | 2013-02-21T02:30:56Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by borough and ELL status.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | borough                            | Borough                            | text      | text        |
| Yes      | time           | cohort_year                        | Cohort Year                        | number    | text        |
| Yes      | series tag     | cohort_category                    | Cohort Category                    | text      | text        |
| Yes      | series tag     | demographic                        | Demographic                        | text      | text        |
| Yes      | numeric metric | total_cohort_num                   | Total Cohort Num                   | number    | text        |
| Yes      | numeric metric | total_grads_num                    | Total Grads Num                    | number    | text        |
| Yes      | numeric metric | total_grads_pct_of_cohort          | Total Grads Pct of cohort          | number    | text        |
| Yes      | numeric metric | total_regents_num                  | Total Regents Num                  | number    | text        |
| Yes      | numeric metric | total_regents_pct_of_cohort        | Total Regents Pct of cohort        | number    | text        |
| Yes      | numeric metric | total_regents_pct_of_grads         | Total Regents Pct of grads         | number    | text        |
| Yes      | numeric metric | advanced_regents_num               | Advanced Regents Num               | number    | text        |
| Yes      | numeric metric | advanced_regents_pct_of_cohort     | Advanced Regents Pct of cohort     | number    | text        |
| Yes      | numeric metric | advanced_regents_pct_of_grads      | Advanced Regents Pct of grads      | number    | text        |
| Yes      | numeric metric | regents_w_o_advanced_num           | Regents w/o Advanced Num           | number    | text        |
| Yes      | numeric metric | regents_w_o_advanced_pct_of_cohort | Regents w/o Advanced Pct of cohort | number    | text        |
| Yes      | numeric metric | regents_w_o_advanced_pct_of_grads  | Regents w/o Advanced Pct of grads  | number    | text        |
| Yes      | numeric metric | local_num                          | Local Num                          | number    | text        |
| Yes      | numeric metric | local_pct_of_cohort                | Local Pct of cohort                | number    | text        |
| Yes      | numeric metric | local_pct_of_grads                 | Local Pct of grads                 | number    | text        |
| Yes      | numeric metric | still_enrolled_num                 | Still Enrolled Num                 | number    | text        |
| Yes      | numeric metric | still_enrolled_pct_of_cohort       | Still Enrolled Pct of cohort       | number    | text        |
| Yes      | numeric metric | dropped_out_num                    | Dropped Out Num                    | number    | text        |
| Yes      | numeric metric | dropped_out_pct_of_cohort          | Dropped Out Pct of cohort          | number    | text        |
```

## Time Field

```ls
Value = cohort_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qs5h-jhhg d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" t:borough=Bronx t:demographic="English Language Learner" m:regents_w_o_advanced_pct_of_cohort=3.4000000953674316 m:regents_w_o_advanced_num=68 m:advanced_regents_num=10 m:local_pct_of_cohort=15.699999809265137 m:advanced_regents_pct_of_grads=2.5999999046325684 m:regents_w_o_advanced_pct_of_grads=17.5 m:advanced_regents_pct_of_cohort=0.5 m:still_enrolled_num=799 m:dropped_out_num=592 m:total_grads_pct_of_cohort=19.600000381469727 m:dropped_out_pct_of_cohort=29.799999237060547 m:local_num=311 m:total_grads_num=388 m:total_regents_pct_of_cohort=3.9000000953674316 m:total_regents_pct_of_grads=20.100000381469727 m:total_cohort_num=1984 m:total_regents_num=78 m:still_enrolled_pct_of_cohort=40.29999923706055 m:local_pct_of_grads=80.19999694824219

series e:qs5h-jhhg d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year" t:borough=Bronx t:demographic="English Language Learner" m:regents_w_o_advanced_pct_of_cohort=5 m:regents_w_o_advanced_num=99 m:advanced_regents_num=11 m:local_pct_of_cohort=25.399999618530273 m:advanced_regents_pct_of_grads=1.7999999523162842 m:regents_w_o_advanced_pct_of_grads=16.200000762939453 m:advanced_regents_pct_of_cohort=0.6000000238418579 m:still_enrolled_num=333 m:dropped_out_num=758 m:total_grads_pct_of_cohort=30.799999237060547 m:dropped_out_pct_of_cohort=38.20000076293945 m:local_num=503 m:total_grads_num=612 m:total_regents_pct_of_cohort=5.5 m:total_regents_pct_of_grads=18 m:total_cohort_num=1984 m:total_regents_num=110 m:still_enrolled_pct_of_cohort=16.799999237060547 m:local_pct_of_grads=82.19999694824219

series e:qs5h-jhhg d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" t:borough=Bronx t:demographic="English Language Learner" m:regents_w_o_advanced_pct_of_cohort=5 m:regents_w_o_advanced_num=100 m:advanced_regents_num=11 m:local_pct_of_cohort=29.399999618530273 m:advanced_regents_pct_of_grads=1.600000023841858 m:regents_w_o_advanced_pct_of_grads=14.5 m:advanced_regents_pct_of_cohort=0.6000000238418579 m:still_enrolled_num=143 m:dropped_out_num=843 m:total_grads_pct_of_cohort=34.70000076293945 m:dropped_out_pct_of_cohort=42.5 m:local_num=583 m:total_grads_num=689 m:total_regents_pct_of_cohort=5.599999904632568 m:total_regents_pct_of_grads=16.100000381469727 m:total_cohort_num=1984 m:total_regents_num=111 m:still_enrolled_pct_of_cohort=7.199999809265137 m:local_pct_of_grads=84.5999984741211
```

## Meta Commands

```ls
metric m:total_cohort_num p:long l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:long l:"Total Grads Num" t:dataTypeName=number

metric m:total_grads_pct_of_cohort p:float l:"Total Grads Pct of cohort" t:dataTypeName=number

metric m:total_regents_num p:long l:"Total Regents Num" t:dataTypeName=number

metric m:total_regents_pct_of_cohort p:float l:"Total Regents Pct of cohort" t:dataTypeName=number

metric m:total_regents_pct_of_grads p:float l:"Total Regents Pct of grads" t:dataTypeName=number

metric m:advanced_regents_num p:long l:"Advanced Regents Num" t:dataTypeName=number

metric m:advanced_regents_pct_of_cohort p:float l:"Advanced Regents Pct of cohort" t:dataTypeName=number

metric m:advanced_regents_pct_of_grads p:float l:"Advanced Regents Pct of grads" t:dataTypeName=number

metric m:regents_w_o_advanced_num p:long l:"Regents w/o Advanced Num" t:dataTypeName=number

metric m:regents_w_o_advanced_pct_of_cohort p:float l:"Regents w/o Advanced Pct of cohort" t:dataTypeName=number

metric m:regents_w_o_advanced_pct_of_grads p:float l:"Regents w/o Advanced Pct of grads" t:dataTypeName=number

metric m:local_num p:long l:"Local Num" t:dataTypeName=number

metric m:local_pct_of_cohort p:float l:"Local Pct of cohort" t:dataTypeName=number

metric m:local_pct_of_grads p:float l:"Local Pct of grads" t:dataTypeName=number

metric m:still_enrolled_num p:long l:"Still Enrolled Num" t:dataTypeName=number

metric m:still_enrolled_pct_of_cohort p:float l:"Still Enrolled Pct of cohort" t:dataTypeName=number

metric m:dropped_out_num p:long l:"Dropped Out Num" t:dataTypeName=number

metric m:dropped_out_pct_of_cohort p:float l:"Dropped Out Pct of cohort" t:dataTypeName=number

entity e:qs5h-jhhg l:"Graduation Outcomes - Borough - Classes of 2005-2011 - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qs5h-jhhg

property e:qs5h-jhhg t:meta.view v:id=qs5h-jhhg v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/F04F9067-BE45-450C-9F89-FEF6DE0229E9/0/Graduation_Rates_Public_Borough.xls v:averageRating=0 v:name="Graduation Outcomes - Borough - Classes of 2005-2011 - ELL" v:attribution="Department of Education (DOE)"

property e:qs5h-jhhg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qs5h-jhhg t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | cohort_year | cohort_category | demographic              | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| ======= | =========== | =============== | ======================== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| Bronx   | 2001        | 4 Year June     | English Language Learner | 1,984            | 388             | 19.60%                    | 78                | 3.90%                       | 20.10%                     | 10                   | 0.50%                          | 2.60%                         | 68                       | 3.40%                              | 17.50%                            | 311       | 15.70%              | 80.20%             | 799                | 40.30%                       | 592             | 29.80%                    | 
| Bronx   | 2001        | 5 Year          | English Language Learner | 1,984            | 612             | 30.80%                    | 110               | 5.50%                       | 18.00%                     | 11                   | 0.60%                          | 1.80%                         | 99                       | 5.00%                              | 16.20%                            | 503       | 25.40%              | 82.20%             | 333                | 16.80%                       | 758             | 38.20%                    | 
| Bronx   | 2001        | 6 Year          | English Language Learner | 1,984            | 689             | 34.70%                    | 111               | 5.60%                       | 16.10%                     | 11                   | 0.60%                          | 1.60%                         | 100                      | 5.00%                              | 14.50%                            | 583       | 29.40%              | 84.60%             | 143                | 7.20%                        | 843             | 42.50%                    | 
| Bronx   | 2002        | 4 Year June     | English Language Learner | 1,693            | 333             | 19.70%                    | 77                | 4.50%                       | 23.10%                     | 7                    | 0.40%                          | 2.10%                         | 70                       | 4.10%                              | 21.00%                            | 257       | 15.20%              | 77.20%             | 725                | 42.80%                       | 509             | 30.10%                    | 
| Bronx   | 2002        | 5 Year          | English Language Learner | 1,693            | 474             | 28.00%                    | 89                | 5.30%                       | 18.80%                     | 8                    | 0.50%                          | 1.70%                         | 81                       | 4.80%                              | 17.10%                            | 388       | 22.90%              | 81.90%             | 352                | 20.80%                       | 678             | 40.00%                    | 
| Bronx   | 2002        | 6 Year          | English Language Learner | 1,693            | 563             | 33.30%                    | 94                | 5.60%                       | 16.70%                     | 8                    | 0.50%                          | 1.40%                         | 86                       | 5.10%                              | 15.30%                            | 472       | 27.90%              | 83.80%             | 191                | 11.30%                       | 724             | 42.80%                    | 
| Bronx   | 2003        | 4 Year June     | English Language Learner | 1,905            | 391             | 20.50%                    | 95                | 5.00%                       | 24.30%                     | 12                   | 0.60%                          | 3.10%                         | 83                       | 4.40%                              | 21.20%                            | 296       | 15.50%              | 75.70%             | 790                | 41.50%                       | 586             | 30.80%                    | 
| Bronx   | 2003        | 5 Year          | English Language Learner | 1,905            | 610             | 32.00%                    | 112               | 5.90%                       | 18.40%                     | 13                   | 0.70%                          | 2.10%                         | 99                       | 5.20%                              | 16.20%                            | 498       | 26.10%              | 81.60%             | 339                | 17.80%                       | 718             | 37.70%                    | 
| Bronx   | 2003        | 6 Year          | English Language Learner | 1,890            | 674             | 35.70%                    | 118               | 6.20%                       | 17.50%                     | 13                   | 0.70%                          | 1.90%                         | 105                      | 5.60%                              | 15.60%                            | 556       | 29.40%              | 82.50%             | 176                | 9.30%                        | 771             | 40.80%                    | 
| Bronx   | 2004        | 4 Year June     | English Language Learner | 1,894            | 640             | 33.80%                    | 214               | 11.30%                      | 33.40%                     | 27                   | 1.40%                          | 4.20%                         | 187                      | 9.90%                              | 29.20%                            | 426       | 22.50%              | 66.60%             | 711                | 37.50%                       | 437             | 23.10%                    | 
```