# Graduation Outcomes - Citywide - Classes of 2005-2011 - SWD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-citywide-classes-of-2005-2011-swd-8434e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jkiz-wt49) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jkiz-wt49/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jkiz-wt49/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jkiz-wt49 |
| Name | Graduation Outcomes - Citywide - Classes of 2005-2011 - SWD |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, citywide, swd, lifelong learning |
| Created | 2013-02-21T02:32:31Z |
| Publication Date | 2013-02-21T02:32:43Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by students with disabilities

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
series e:jkiz-wt49 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=19.70% t:regents_w_o_advanced_num=12,730 t:cohort_category="4 Year  June" t:advanced_regents_num=9,211 t:demographic="Not Student with Disability" t:regents_w_o_advanced_pct_of_grads=38.70% t:advanced_regents_pct_of_grads=28.00% t:advanced_regents_pct_of_cohort=14.30% m:still_enrolled_num=18305 m:dropped_out_num=13062 m:total_grads_pct_of_cohort=50.900001525878906 m:dropped_out_pct_of_cohort=20.200000762939453 m:local_num=10937 m:total_grads_num=32863 m:local_pct_of_cohort=16.899999618530273 m:total_regents_pct_of_cohort=34 m:total_regents_pct_of_grads=66.80000305175781 m:total_cohort_num=64593 m:total_regents_num=21941 m:still_enrolled_pct_of_cohort=28.299999237060547 m:local_pct_of_grads=33.29999923706055

series e:jkiz-wt49 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=22.00% t:regents_w_o_advanced_num=14,236 t:cohort_category="5 Year" t:advanced_regents_num=9,411 t:demographic="Not Student with Disability" t:regents_w_o_advanced_pct_of_grads=36.20% t:advanced_regents_pct_of_grads=23.90% t:advanced_regents_pct_of_cohort=14.60% m:still_enrolled_num=7386 m:dropped_out_num=17426 m:total_grads_pct_of_cohort=60.900001525878906 m:dropped_out_pct_of_cohort=27 m:local_num=15777 m:total_grads_num=39364 m:local_pct_of_cohort=24.399999618530273 m:total_regents_pct_of_cohort=36.599998474121094 m:total_regents_pct_of_grads=60.099998474121094 m:total_cohort_num=64593 m:total_regents_num=23647 m:still_enrolled_pct_of_cohort=11.399999618530273 m:local_pct_of_grads=40.099998474121094

series e:jkiz-wt49 d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=22.60% t:regents_w_o_advanced_num=14,620 t:cohort_category="6 Year" t:advanced_regents_num=9,433 t:demographic="Not Student with Disability" t:regents_w_o_advanced_pct_of_grads=35.40% t:advanced_regents_pct_of_grads=22.80% t:advanced_regents_pct_of_cohort=14.60% m:still_enrolled_num=3287 m:dropped_out_num=19482 m:total_grads_pct_of_cohort=63.900001525878906 m:dropped_out_pct_of_cohort=30.200000762939453 m:local_num=17392 m:total_grads_num=41293 m:local_pct_of_cohort=26.899999618530273 m:total_regents_pct_of_cohort=37.20000076293945 m:total_regents_pct_of_grads=58.20000076293945 m:total_cohort_num=64593 m:total_regents_num=24053 m:still_enrolled_pct_of_cohort=5.099999904632568 m:local_pct_of_grads=42.099998474121094
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

entity e:jkiz-wt49 l:"Graduation Outcomes - Citywide - Classes of 2005-2011 - SWD" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/jkiz-wt49

property e:jkiz-wt49 t:meta.view v:id=jkiz-wt49 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/72F0AB29-A095-4C22-95A2-096958175299/0/Graduation_Rates_Public_Citywide.xls v:averageRating=0 v:name="Graduation Outcomes - Citywide - Classes of 2005-2011 - SWD" v:attribution="Department of Education (DOE)"

property e:jkiz-wt49 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jkiz-wt49 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| cohort_year | cohort_category | demographic                 | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| =========== | =============== | =========================== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 2001        | 4 Year June     | Not Student with Disability | 64,593           | 32,863          | 50.90%                    | 21,941            | 34.00%                      | 66.80%                     | 9,211                | 14.30%                         | 28.00%                        | 12,730                   | 19.70%                             | 38.70%                            | 10,937    | 16.90%              | 33.30%             | 18,305             | 28.30%                       | 13,062          | 20.20%                    | 
| 2001        | 5 Year          | Not Student with Disability | 64,593           | 39,364          | 60.90%                    | 23,647            | 36.60%                      | 60.10%                     | 9,411                | 14.60%                         | 23.90%                        | 14,236                   | 22.00%                             | 36.20%                            | 15,777    | 24.40%              | 40.10%             | 7,386              | 11.40%                       | 17,426          | 27.00%                    | 
| 2001        | 6 Year          | Not Student with Disability | 64,593           | 41,293          | 63.90%                    | 24,053            | 37.20%                      | 58.20%                     | 9,433                | 14.60%                         | 22.80%                        | 14,620                   | 22.60%                             | 35.40%                            | 17,392    | 26.90%              | 42.10%             | 3,287              | 5.10%                        | 19,482          | 30.20%                    | 
| 2002        | 4 Year June     | Not Student with Disability | 67,537           | 35,265          | 52.20%                    | 24,798            | 36.70%                      | 70.30%                     | 9,400                | 13.90%                         | 26.70%                        | 15,398                   | 22.80%                             | 43.70%                            | 10,501    | 15.50%              | 29.80%             | 18,972             | 28.10%                       | 11,832          | 17.50%                    | 
| 2002        | 5 Year          | Not Student with Disability | 67,537           | 42,249          | 62.60%                    | 27,152            | 40.20%                      | 64.30%                     | 9,708                | 14.40%                         | 23.00%                        | 17,444                   | 25.80%                             | 41.30%                            | 15,360    | 22.70%              | 36.40%             | 7,313              | 10.80%                       | 16,253          | 24.10%                    | 
| 2002        | 6 Year          | Not Student with Disability | 67,537           | 44,169          | 65.40%                    | 27,589            | 40.90%                      | 62.50%                     | 9,731                | 14.40%                         | 22.00%                        | 17,858                   | 26.40%                             | 40.40%                            | 16,843    | 24.90%              | 38.10%             | 4,045              | 6.00%                        | 17,572          | 26.00%                    | 
| 2003        | 4 Year June     | Not Student with Disability | 64,766           | 37,324          | 57.60%                    | 27,046            | 41.80%                      | 72.50%                     | 11,284               | 17.40%                         | 30.20%                        | 15,762                   | 24.30%                             | 42.20%                            | 10,278    | 15.90%              | 27.50%             | 16,946             | 26.20%                       | 9,614           | 14.80%                    | 
| 2003        | 5 Year          | Not Student with Disability | 64,766           | 43,826          | 67.70%                    | 29,392            | 45.40%                      | 67.10%                     | 11,520               | 17.80%                         | 26.30%                        | 17,872                   | 27.60%                             | 40.80%                            | 14,434    | 22.30%              | 32.90%             | 6,880              | 10.60%                       | 13,058          | 20.20%                    | 
| 2003        | 6 Year          | Not Student with Disability | 65,187           | 45,871          | 70.40%                    | 29,957            | 46.00%                      | 65.30%                     | 11,533               | 17.70%                         | 25.10%                        | 18,424                   | 28.30%                             | 40.20%                            | 15,914    | 24.40%              | 34.70%             | 3,324              | 5.10%                        | 14,361          | 22.00%                    | 
| 2004        | 4 Year June     | Not Student with Disability | 64,874           | 40,021          | 61.70%                    | 29,933            | 46.10%                      | 74.80%                     | 12,481               | 19.20%                         | 31.20%                        | 17,452                   | 26.90%                             | 43.60%                            | 10,088    | 15.60%              | 25.20%             | 16,642             | 25.70%                       | 7,942           | 12.20%                    | 
```