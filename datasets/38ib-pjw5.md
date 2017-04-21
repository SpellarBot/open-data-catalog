# Graduation Outcomes - Citywide - Classes of 2005-2011 - ELL

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-citywide-classes-of-2005-2011-ell-51439) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/38ib-pjw5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/38ib-pjw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/38ib-pjw5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 38ib-pjw5 |
| Name | Graduation Outcomes - Citywide - Classes of 2005-2011 - ELL |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, citywide, ell, lifelong learning |
| Created | 2013-02-21T02:31:54Z |
| Publication Date | 2013-02-21T02:32:06Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by English Language Learner status.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | cohort_year                        | Cohort Year                        | number    | text        |
| Yes      | series tag     | cohort_category                    | Cohort Category                    | text      | text        |
| Yes      | series tag     | demographic                        | Demographic                        | text      | text        |
| Yes      | numeric metric | total_cohort_num                   | Total Cohort Num                   | number    | text        |
| Yes      | numeric metric | total_grads_num                    | Total Grads Num                    | number    | text        |
| Yes      | numeric metric | total_grads_pct_of_cohort          | Total Grads Pct of cohort          | number    | text        |
| Yes      | numeric metric | total_regents_num                  | Total Regents Num                  | number    | text        |
| Yes      | numeric metric | total_regents_pct_of_cohort        | Total Regents Pct of cohort        | number    | text        |
| Yes      | numeric metric | total_regents_pct_of_grads         | Total Regents Pct of grads         | number    | text        |
| Yes      | series tag     | advanced_regents_num               | Advanced Regents Num               | text      | text        |
| Yes      | series tag     | advanced_regents_pct_of_cohort     | Advanced Regents Pct of cohort     | text      | text        |
| Yes      | series tag     | advanced_regents_pct_of_grads      | Advanced Regents Pct of grads      | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_num           | Regents w/o Advanced Num           | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_pct_of_cohort | Regents w/o Advanced Pct of cohort | text      | text        |
| Yes      | series tag     | regents_w_o_advanced_pct_of_grads  | Regents w/o Advanced Pct of grads  | text      | text        |
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
series e:38ib-pjw5 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=6.40% t:regents_w_o_advanced_num=677 t:cohort_category="4 Year  June" t:advanced_regents_num=315 t:demographic="English Language Learner" t:regents_w_o_advanced_pct_of_grads=24.30% t:advanced_regents_pct_of_grads=11.30% t:advanced_regents_pct_of_cohort=3.00% m:still_enrolled_num=3895 m:dropped_out_num=3220 m:total_grads_pct_of_cohort=26.5 m:dropped_out_pct_of_cohort=30.600000381469727 m:local_num=1803 m:total_grads_num=2791 m:local_pct_of_cohort=17.100000381469727 m:total_regents_pct_of_cohort=9 m:total_regents_pct_of_grads=35.5 m:total_cohort_num=10540 m:total_regents_num=992 m:still_enrolled_pct_of_cohort=37 m:local_pct_of_grads=64.5999984741211

series e:38ib-pjw5 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=8.20% t:regents_w_o_advanced_num=862 t:cohort_category="5 Year" t:advanced_regents_num=371 t:demographic="English Language Learner" t:regents_w_o_advanced_pct_of_grads=22.00% t:advanced_regents_pct_of_grads=9.50% t:advanced_regents_pct_of_cohort=3.50% m:still_enrolled_num=1516 m:dropped_out_num=4193 m:total_grads_pct_of_cohort=37.20000076293945 m:dropped_out_pct_of_cohort=39.79999923706055 m:local_num=2701 m:total_grads_num=3920 m:local_pct_of_cohort=25.600000381469727 m:total_regents_pct_of_cohort=11.699999809265137 m:total_regents_pct_of_grads=31.5 m:total_cohort_num=10540 m:total_regents_num=1233 m:still_enrolled_pct_of_cohort=14.399999618530273 m:local_pct_of_grads=68.9000015258789

series e:38ib-pjw5 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=8.60% t:regents_w_o_advanced_num=911 t:cohort_category="6 Year" t:advanced_regents_num=380 t:demographic="English Language Learner" t:regents_w_o_advanced_pct_of_grads=21.20% t:advanced_regents_pct_of_grads=8.80% t:advanced_regents_pct_of_cohort=3.60% m:still_enrolled_num=655 m:dropped_out_num=4598 m:total_grads_pct_of_cohort=40.79999923706055 m:dropped_out_pct_of_cohort=43.599998474121094 m:local_num=3028 m:total_grads_num=4296 m:local_pct_of_cohort=28.700000762939453 m:total_regents_pct_of_cohort=12.199999809265137 m:total_regents_pct_of_grads=30.100000381469727 m:total_cohort_num=10540 m:total_regents_num=1291 m:still_enrolled_pct_of_cohort=6.199999809265137 m:local_pct_of_grads=70.5
```

## Meta Commands

```ls
metric m:total_cohort_num p:long l:"Total Cohort Num" t:dataTypeName=number

metric m:total_grads_num p:long l:"Total Grads Num" t:dataTypeName=number

metric m:total_grads_pct_of_cohort p:float l:"Total Grads Pct of cohort" t:dataTypeName=number

metric m:total_regents_num p:long l:"Total Regents Num" t:dataTypeName=number

metric m:total_regents_pct_of_cohort p:float l:"Total Regents Pct of cohort" t:dataTypeName=number

metric m:total_regents_pct_of_grads p:float l:"Total Regents Pct of grads" t:dataTypeName=number

metric m:local_num p:long l:"Local Num" t:dataTypeName=number

metric m:local_pct_of_cohort p:float l:"Local Pct of cohort" t:dataTypeName=number

metric m:local_pct_of_grads p:float l:"Local Pct of grads" t:dataTypeName=number

metric m:still_enrolled_num p:long l:"Still Enrolled Num" t:dataTypeName=number

metric m:still_enrolled_pct_of_cohort p:float l:"Still Enrolled Pct of cohort" t:dataTypeName=number

metric m:dropped_out_num p:long l:"Dropped Out Num" t:dataTypeName=number

metric m:dropped_out_pct_of_cohort p:float l:"Dropped Out Pct of cohort" t:dataTypeName=number

entity e:38ib-pjw5 l:"Graduation Outcomes - Citywide - Classes of 2005-2011 - ELL" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/38ib-pjw5

property e:38ib-pjw5 t:meta.view v:id=38ib-pjw5 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/72F0AB29-A095-4C22-95A2-096958175299/0/Graduation_Rates_Public_Citywide.xls v:averageRating=0 v:name="Graduation Outcomes - Citywide - Classes of 2005-2011 - ELL" v:attribution="Department of Education (DOE)"

property e:38ib-pjw5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:38ib-pjw5 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| cohort_year | cohort_category | demographic              | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| =========== | =============== | ======================== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 2001        | 4 Year June     | English Language Learner | 10,540           | 2,791           | 26.50%                    | 992               | 9.00%                       | 35.50%                     | 315                  | 3.00%                          | 11.30%                        | 677                      | 6.40%                              | 24.30%                            | 1,803     | 17.10%              | 64.60%             | 3,895              | 37.00%                       | 3,220           | 30.60%                    | 
| 2001        | 5 Year          | English Language Learner | 10,540           | 3,920           | 37.20%                    | 1,233             | 11.70%                      | 31.50%                     | 371                  | 3.50%                          | 9.50%                         | 862                      | 8.20%                              | 22.00%                            | 2,701     | 25.60%              | 68.90%             | 1,516              | 14.40%                       | 4,193           | 39.80%                    | 
| 2001        | 6 Year          | English Language Learner | 10,540           | 4,296           | 40.80%                    | 1,291             | 12.20%                      | 30.10%                     | 380                  | 3.60%                          | 8.80%                         | 911                      | 8.60%                              | 21.20%                            | 3,028     | 28.70%              | 70.50%             | 655                | 6.20%                        | 4,598           | 43.60%                    | 
| 2002        | 4 Year June     | English Language Learner | 7,454            | 1,691           | 22.70%                    | 639               | 8.60%                       | 37.80%                     | 132                  | 1.80%                          | 7.80%                         | 507                      | 6.80%                              | 30.00%                            | 1,062     | 14.20%              | 62.80%             | 3,062              | 41.10%                       | 2,330           | 31.30%                    | 
| 2002        | 5 Year          | English Language Learner | 7,454            | 2,354           | 31.60%                    | 794               | 10.70%                      | 33.70%                     | 176                  | 2.40%                          | 7.50%                         | 618                      | 8.30%                              | 26.30%                            | 1,578     | 21.20%              | 67.00%             | 1,457              | 19.50%                       | 3,041           | 40.80%                    | 
| 2002        | 6 Year          | English Language Learner | 7,454            | 2,729           | 36.60%                    | 856               | 11.50%                      | 31.40%                     | 185                  | 2.50%                          | 6.80%                         | 671                      | 9.00%                              | 24.60%                            | 1,891     | 25.40%              | 69.30%             | 697                | 9.40%                        | 3,356           | 45.00%                    | 
| 2003        | 4 Year June     | English Language Learner | 8,163            | 2,052           | 25.10%                    | 909               | 11.10%                      | 44.30%                     | 290                  | 3.60%                          | 14.10%                        | 619                      | 7.60%                              | 30.20%                            | 1,143     | 14.00%              | 55.70%             | 3,360              | 41.20%                       | 2,394           | 29.30%                    | 
| 2003        | 5 Year          | English Language Learner | 8,163            | 3,105           | 38.00%                    | 1,159             | 14.20%                      | 37.30%                     | 358                  | 4.40%                          | 11.50%                        | 801                      | 9.80%                              | 25.80%                            | 1,946     | 23.80%              | 62.70%             | 1,327              | 16.30%                       | 3,111           | 38.10%                    | 
| 2003        | 6 Year          | English Language Learner | 8,041            | 3,394           | 42.20%                    | 1,216             | 15.10%                      | 35.80%                     | 363                  | 4.50%                          | 10.70%                        | 853                      | 10.60%                             | 25.10%                            | 2,178     | 27.10%              | 64.20%             | 570                | 7.10%                        | 3,361           | 41.80%                    | 
| 2004        | 4 Year June     | English Language Learner | 8,486            | 3,039           | 35.80%                    | 1,504             | 17.70%                      | 49.50%                     | 487                  | 5.70%                          | 16.00%                        | 1,017                    | 12.00%                             | 33.50%                            | 1,535     | 18.10%              | 50.50%             | 3,288              | 38.70%                       | 1,840           | 21.70%                    | 
```