# Graduation Outcomes - Citywide - Classes of 2005-2011 - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-citywide-classes-of-2005-2011-gender-1ec0e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rn5p-vhac) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rn5p-vhac/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rn5p-vhac/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rn5p-vhac |
| Name | Graduation Outcomes - Citywide - Classes of 2005-2011 - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, citywide, gender, lifelong learning |
| Created | 2013-02-21T02:32:20Z |
| Publication Date | 2013-02-21T02:32:31Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by gender.

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
series e:rn5p-vhac d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=20.30% t:regents_w_o_advanced_num=7,308 t:cohort_category="4 Year  June" t:advanced_regents_num=5,147 t:demographic=Female t:regents_w_o_advanced_pct_of_grads=37.60% t:advanced_regents_pct_of_grads=26.50% t:advanced_regents_pct_of_cohort=14.30% m:still_enrolled_num=9075 m:dropped_out_num=6699 m:total_grads_pct_of_cohort=53.900001525878906 m:dropped_out_pct_of_cohort=18.600000381469727 m:local_num=6985 m:total_grads_num=19424 m:local_pct_of_cohort=19.399999618530273 m:total_regents_pct_of_cohort=34.5 m:total_regents_pct_of_grads=64.0999984741211 m:total_cohort_num=36069 m:total_regents_num=12455 m:still_enrolled_pct_of_cohort=25.200000762939453 m:local_pct_of_grads=36

series e:rn5p-vhac d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=22.10% t:regents_w_o_advanced_num=7,967 t:cohort_category="5 Year" t:advanced_regents_num=5,243 t:demographic=Female t:regents_w_o_advanced_pct_of_grads=35.10% t:advanced_regents_pct_of_grads=23.10% t:advanced_regents_pct_of_cohort=14.50% m:still_enrolled_num=3265 m:dropped_out_num=8931 m:total_grads_pct_of_cohort=62.900001525878906 m:dropped_out_pct_of_cohort=24.799999237060547 m:local_num=9501 m:total_grads_num=22680 m:local_pct_of_cohort=26.299999237060547 m:total_regents_pct_of_cohort=36.599998474121094 m:total_regents_pct_of_grads=58.20000076293945 m:total_cohort_num=36069 m:total_regents_num=13210 m:still_enrolled_pct_of_cohort=9.100000381469727 m:local_pct_of_grads=41.900001525878906

series e:rn5p-vhac d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=22.50% t:regents_w_o_advanced_num=8,116 t:cohort_category="6 Year" t:advanced_regents_num=5,249 t:demographic=Female t:regents_w_o_advanced_pct_of_grads=34.40% t:advanced_regents_pct_of_grads=22.20% t:advanced_regents_pct_of_cohort=14.60% m:still_enrolled_num=1302 m:dropped_out_num=9893 m:total_grads_pct_of_cohort=65.4000015258789 m:dropped_out_pct_of_cohort=27.399999618530273 m:local_num=10292 m:total_grads_num=23594 m:local_pct_of_cohort=28.5 m:total_regents_pct_of_cohort=37.099998474121094 m:total_regents_pct_of_grads=56.599998474121094 m:total_cohort_num=36069 m:total_regents_num=13365 m:still_enrolled_pct_of_cohort=3.5999999046325684 m:local_pct_of_grads=43.599998474121094
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

entity e:rn5p-vhac l:"Graduation Outcomes - Citywide - Classes of 2005-2011 - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rn5p-vhac

property e:rn5p-vhac t:meta.view v:id=rn5p-vhac v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/72F0AB29-A095-4C22-95A2-096958175299/0/Graduation_Rates_Public_Citywide.xls v:averageRating=0 v:name="Graduation Outcomes - Citywide - Classes of 2005-2011 - Gender" v:attribution="Department of Education (DOE)"

property e:rn5p-vhac t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rn5p-vhac t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| cohort_year | cohort_category | demographic | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| =========== | =============== | =========== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 2001        | 4 Year June     | Female      | 36,069           | 19,424          | 53.90%                    | 12,455            | 34.50%                      | 64.10%                     | 5,147                | 14.30%                         | 26.50%                        | 7,308                    | 20.30%                             | 37.60%                            | 6,985     | 19.40%              | 36.00%             | 9,075              | 25.20%                       | 6,699           | 18.60%                    | 
| 2001        | 5 Year          | Female      | 36,069           | 22,680          | 62.90%                    | 13,210            | 36.60%                      | 58.20%                     | 5,243                | 14.50%                         | 23.10%                        | 7,967                    | 22.10%                             | 35.10%                            | 9,501     | 26.30%              | 41.90%             | 3,265              | 9.10%                        | 8,931           | 24.80%                    | 
| 2001        | 6 Year          | Female      | 36,069           | 23,594          | 65.40%                    | 13,365            | 37.10%                      | 56.60%                     | 5,249                | 14.60%                         | 22.20%                        | 8,116                    | 22.50%                             | 34.40%                            | 10,292    | 28.50%              | 43.60%             | 1,302              | 3.60%                        | 9,893           | 27.40%                    | 
| 2002        | 4 Year June     | Female      | 37,040           | 20,565          | 55.50%                    | 13,986            | 37.80%                      | 68.00%                     | 5,155                | 13.90%                         | 25.10%                        | 8,831                    | 23.80%                             | 42.90%                            | 6,601     | 17.80%              | 32.10%             | 9,628              | 26.00%                       | 5,810           | 15.70%                    | 
| 2002        | 5 Year          | Female      | 37,040           | 24,040          | 64.90%                    | 15,053            | 40.60%                      | 62.60%                     | 5,283                | 14.30%                         | 22.00%                        | 9,770                    | 26.40%                             | 40.60%                            | 9,116     | 24.60%              | 37.90%             | 3,818              | 10.30%                       | 7,845           | 21.20%                    | 
| 2002        | 6 Year          | Female      | 37,040           | 25,053          | 67.60%                    | 15,231            | 41.10%                      | 60.80%                     | 5,290                | 14.30%                         | 21.10%                        | 9,941                    | 26.80%                             | 39.70%                            | 9,951     | 26.90%              | 39.70%             | 1,958              | 5.30%                        | 8,590           | 23.20%                    | 
| 2003        | 4 Year June     | Female      | 36,829           | 21,942          | 59.60%                    | 15,381            | 41.80%                      | 70.10%                     | 6,375                | 17.30%                         | 29.10%                        | 9,006                    | 24.50%                             | 41.00%                            | 6,561     | 17.80%              | 29.90%             | 9,253              | 25.10%                       | 4,862           | 13.20%                    | 
| 2003        | 5 Year          | Female      | 36,829           | 25,263          | 68.60%                    | 16,371            | 44.50%                      | 64.80%                     | 6,465                | 17.60%                         | 25.60%                        | 9,906                    | 26.90%                             | 39.20%                            | 8,892     | 24.10%              | 35.20%             | 3,597              | 9.80%                        | 6,782           | 18.40%                    | 
| 2003        | 6 Year          | Female      | 36,893           | 26,309          | 71.30%                    | 16,590            | 45.00%                      | 63.10%                     | 6,471                | 17.50%                         | 24.60%                        | 10,119                   | 27.40%                             | 38.50%                            | 9,719     | 26.30%              | 36.90%             | 1,665              | 4.50%                        | 7,383           | 20.00%                    | 
| 2004        | 4 Year June     | Female      | 37,275           | 23,485          | 63.00%                    | 16,970            | 45.50%                      | 72.30%                     | 6,910                | 18.50%                         | 29.40%                        | 10,060                   | 27.00%                             | 42.80%                            | 6,515     | 17.50%              | 27.70%             | 9,040              | 24.30%                       | 4,145           | 11.10%                    | 
```