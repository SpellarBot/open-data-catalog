# Graduation Outcomes - Citywide - Classes of 2005-2011 - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-citywide-classes-of-2005-2011-ethnicity-98de8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mbym-vp3s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mbym-vp3s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mbym-vp3s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mbym-vp3s |
| Name | Graduation Outcomes - Citywide - Classes of 2005-2011 - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, citywide, ethnicity, lifelong learning |
| Created | 2013-02-21T02:32:07Z |
| Publication Date | 2013-02-21T02:32:19Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by ethnicity.

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
series e:mbym-vp3s d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=20.20% t:regents_w_o_advanced_num=1,984 t:cohort_category="4 Year  June" t:advanced_regents_num=3,277 t:demographic=Asian t:regents_w_o_advanced_pct_of_grads=30.50% t:advanced_regents_pct_of_grads=50.40% t:advanced_regents_pct_of_cohort=33.40% m:still_enrolled_num=1934 m:dropped_out_num=1281 m:total_grads_pct_of_cohort=66.30000305175781 m:dropped_out_pct_of_cohort=13.100000381469727 m:local_num=1245 m:total_grads_num=6501 m:local_pct_of_cohort=12.699999809265137 m:total_regents_pct_of_cohort=53.599998474121094 m:total_regents_pct_of_grads=80.9000015258789 m:total_cohort_num=9807 m:total_regents_num=5261 m:still_enrolled_pct_of_cohort=19.700000762939453 m:local_pct_of_grads=19.200000762939453

series e:mbym-vp3s d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=22.90% t:regents_w_o_advanced_num=2,249 t:cohort_category="5 Year" t:advanced_regents_num=3,369 t:demographic=Asian t:regents_w_o_advanced_pct_of_grads=30.50% t:advanced_regents_pct_of_grads=45.70% t:advanced_regents_pct_of_cohort=34.40% m:still_enrolled_num=582 m:dropped_out_num=1705 m:total_grads_pct_of_cohort=75.19999694824219 m:dropped_out_pct_of_cohort=17.399999618530273 m:local_num=1767 m:total_grads_num=7377 m:local_pct_of_cohort=18 m:total_regents_pct_of_cohort=57.29999923706055 m:total_regents_pct_of_grads=76.19999694824219 m:total_cohort_num=9807 m:total_regents_num=5618 m:still_enrolled_pct_of_cohort=5.900000095367432 m:local_pct_of_grads=24

series e:mbym-vp3s d:2001-01-01T00:00:00.000Z t:regents_w_o_advanced_pct_of_cohort=23.60% t:regents_w_o_advanced_num=2,311 t:cohort_category="6 Year" t:advanced_regents_num=3,380 t:demographic=Asian t:regents_w_o_advanced_pct_of_grads=30.40% t:advanced_regents_pct_of_grads=44.50% t:advanced_regents_pct_of_cohort=34.50% m:still_enrolled_num=202 m:dropped_out_num=1856 m:total_grads_pct_of_cohort=77.5 m:dropped_out_pct_of_cohort=18.899999618530273 m:local_num=1921 m:total_grads_num=7599 m:local_pct_of_cohort=19.600000381469727 m:total_regents_pct_of_cohort=58 m:total_regents_pct_of_grads=74.9000015258789 m:total_cohort_num=9807 m:total_regents_num=5691 m:still_enrolled_pct_of_cohort=2.0999999046325684 m:local_pct_of_grads=25.299999237060547
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

entity e:mbym-vp3s l:"Graduation Outcomes - Citywide - Classes of 2005-2011 - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/mbym-vp3s

property e:mbym-vp3s t:meta.view v:id=mbym-vp3s v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/72F0AB29-A095-4C22-95A2-096958175299/0/Graduation_Rates_Public_Citywide.xls v:averageRating=0 v:name="Graduation Outcomes - Citywide - Classes of 2005-2011 - Ethnicity" v:attribution="Department of Education (DOE)"

property e:mbym-vp3s t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mbym-vp3s t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| cohort_year | cohort_category | demographic | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| =========== | =============== | =========== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 2001        | 4 Year June     | Asian       | 9,807            | 6,501           | 66.30%                    | 5,261             | 53.60%                      | 80.90%                     | 3,277                | 33.40%                         | 50.40%                        | 1,984                    | 20.20%                             | 30.50%                            | 1,245     | 12.70%              | 19.20%             | 1,934              | 19.70%                       | 1,281           | 13.10%                    | 
| 2001        | 5 Year          | Asian       | 9,807            | 7,377           | 75.20%                    | 5,618             | 57.30%                      | 76.20%                     | 3,369                | 34.40%                         | 45.70%                        | 2,249                    | 22.90%                             | 30.50%                            | 1,767     | 18.00%              | 24.00%             | 582                | 5.90%                        | 1,705           | 17.40%                    | 
| 2001        | 6 Year          | Asian       | 9,807            | 7,599           | 77.50%                    | 5,691             | 58.00%                      | 74.90%                     | 3,380                | 34.50%                         | 44.50%                        | 2,311                    | 23.60%                             | 30.40%                            | 1,921     | 19.60%              | 25.30%             | 202                | 2.10%                        | 1,856           | 18.90%                    | 
| 2002        | 4 Year June     | Asian       | 10,554           | 7,082           | 67.10%                    | 6,062             | 57.40%                      | 85.60%                     | 3,601                | 34.10%                         | 50.80%                        | 2,461                    | 23.30%                             | 34.80%                            | 1,025     | 9.70%               | 14.50%             | 2,014              | 19.10%                       | 1,257           | 11.90%                    | 
| 2002        | 5 Year          | Asian       | 10,554           | 8,054           | 76.30%                    | 6,554             | 62.10%                      | 81.40%                     | 3,743                | 35.50%                         | 46.50%                        | 2,811                    | 26.60%                             | 34.90%                            | 1,521     | 14.40%              | 18.90%             | 627                | 5.90%                        | 1,633           | 15.50%                    | 
| 2002        | 6 Year          | Asian       | 10,554           | 8,260           | 78.30%                    | 6,632             | 62.80%                      | 80.30%                     | 3,754                | 35.60%                         | 45.40%                        | 2,878                    | 27.30%                             | 34.80%                            | 1,649     | 15.60%              | 20.00%             | 278                | 2.60%                        | 1,765           | 16.70%                    | 
| 2003        | 4 Year June     | Asian       | 10,403           | 7,467           | 71.80%                    | 6,568             | 63.10%                      | 88.00%                     | 4,274                | 41.10%                         | 57.20%                        | 2,294                    | 22.10%                             | 30.70%                            | 899       | 8.60%               | 12.00%             | 1,867              | 17.90%                       | 999             | 9.60%                     | 
| 2003        | 5 Year          | Asian       | 10,403           | 8,372           | 80.50%                    | 7,062             | 67.90%                      | 84.40%                     | 4,410                | 42.40%                         | 52.70%                        | 2,652                    | 25.50%                             | 31.70%                            | 1,310     | 12.60%              | 15.60%             | 562                | 5.40%                        | 1,340           | 12.90%                    | 
| 2003        | 6 Year          | Asian       | 10,408           | 8,569           | 82.30%                    | 7,150             | 68.70%                      | 83.40%                     | 4,420                | 42.50%                         | 51.60%                        | 2,730                    | 26.20%                             | 31.90%                            | 1,419     | 13.60%              | 16.60%             | 223                | 2.10%                        | 1,434           | 13.80%                    | 
| 2004        | 4 Year June     | Asian       | 10,897           | 8,075           | 74.10%                    | 7,188             | 66.00%                      | 89.00%                     | 4,729                | 43.40%                         | 58.60%                        | 2,459                    | 22.60%                             | 30.50%                            | 887       | 8.10%               | 11.00%             | 1,946              | 17.90%                       | 808             | 7.40%                     | 
```