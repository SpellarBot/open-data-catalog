# Graduation Outcomes - Citywide - Classes of 2005-2011 - Total Cohort

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-citywide-classes-of-2005-2011-total-cohort-c6282) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ubv8-6n5w) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ubv8-6n5w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ubv8-6n5w/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ubv8-6n5w |
| Name | Graduation Outcomes - Citywide - Classes of 2005-2011 - Total Cohort |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, citywide, total cohort, lifelong learning |
| Created | 2013-02-21T02:32:44Z |
| Publication Date | 2013-02-21T02:33:02Z |

## Description

Latest available data and trends in graduation and dropout outcomes.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | cohort_year                        | Cohort Year                        | number    | text        |
| Yes      | series tag     | cohort_category                    | Cohort Category                    | text      | text        |
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
series e:ubv8-6n5w d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" m:regents_w_o_advanced_pct_of_cohort=17.5 m:regents_w_o_advanced_num=12948 m:advanced_regents_num=9249 m:local_pct_of_cohort=16.600000381469727 m:advanced_regents_pct_of_grads=26.799999237060547 m:regents_w_o_advanced_pct_of_grads=37.5 m:advanced_regents_pct_of_cohort=12.5 m:still_enrolled_num=21094 m:dropped_out_num=16337 m:total_grads_pct_of_cohort=46.5 m:dropped_out_pct_of_cohort=22 m:local_num=12333 m:total_grads_num=34503 m:total_regents_pct_of_cohort=30 m:total_regents_pct_of_grads=64 m:total_cohort_num=74143 m:total_regents_num=22197 m:still_enrolled_pct_of_cohort=28.5 m:local_pct_of_grads=36

series e:ubv8-6n5w d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year" m:regents_w_o_advanced_pct_of_cohort=19.5 m:regents_w_o_advanced_num=14476 m:advanced_regents_num=9449 m:local_pct_of_cohort=23.600000381469727 m:advanced_regents_pct_of_grads=22.899999618530273 m:regents_w_o_advanced_pct_of_grads=35 m:advanced_regents_pct_of_cohort=12.699999809265137 m:still_enrolled_num=8335 m:dropped_out_num=21382 m:total_grads_pct_of_cohort=55.70000076293945 m:dropped_out_pct_of_cohort=28.799999237060547 m:local_num=17465 m:total_grads_num=41317 m:total_regents_pct_of_cohort=32.29999923706055 m:total_regents_pct_of_grads=57.900001525878906 m:total_cohort_num=74143 m:total_regents_num=23925 m:still_enrolled_pct_of_cohort=11.199999809265137 m:local_pct_of_grads=42.29999923706055

series e:ubv8-6n5w d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" m:regents_w_o_advanced_pct_of_cohort=20 m:regents_w_o_advanced_num=14865 m:advanced_regents_num=9473 m:local_pct_of_cohort=25.899999618530273 m:advanced_regents_pct_of_grads=21.899999618530273 m:regents_w_o_advanced_pct_of_grads=34.29999923706055 m:advanced_regents_pct_of_cohort=12.800000190734863 m:still_enrolled_num=3896 m:dropped_out_num=23538 m:total_grads_pct_of_cohort=58.5 m:dropped_out_pct_of_cohort=31.700000762939453 m:local_num=19180 m:total_grads_num=43351 m:total_regents_pct_of_cohort=32.79999923706055 m:total_regents_pct_of_grads=56.099998474121094 m:total_cohort_num=74143 m:total_regents_num=24338 m:still_enrolled_pct_of_cohort=5.300000190734863 m:local_pct_of_grads=44.20000076293945
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

entity e:ubv8-6n5w l:"Graduation Outcomes - Citywide - Classes of 2005-2011 - Total Cohort" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ubv8-6n5w

property e:ubv8-6n5w t:meta.view v:id=ubv8-6n5w v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/72F0AB29-A095-4C22-95A2-096958175299/0/Graduation_Rates_Public_Citywide.xls v:averageRating=0 v:name="Graduation Outcomes - Citywide - Classes of 2005-2011 - Total Cohort" v:attribution="Department of Education (DOE)"

property e:ubv8-6n5w t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ubv8-6n5w t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| cohort_year | cohort_category | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| =========== | =============== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| 2001        | 4 Year June     | 74,143           | 34,503          | 46.50%                    | 22,197            | 30.00%                      | 64.00%                     | 9,249                | 12.50%                         | 26.80%                        | 12,948                   | 17.50%                             | 37.50%                            | 12,333    | 16.60%              | 36.00%             | 21,094             | 28.50%                       | 16,337          | 22.00%                    | 
| 2001        | 5 Year          | 74,143           | 41,317          | 55.70%                    | 23,925            | 32.30%                      | 57.90%                     | 9,449                | 12.70%                         | 22.90%                        | 14,476                   | 19.50%                             | 35.00%                            | 17,465    | 23.60%              | 42.30%             | 8,335              | 11.20%                       | 21,382          | 28.80%                    | 
| 2001        | 6 Year          | 74,143           | 43,351          | 58.50%                    | 24,338            | 32.80%                      | 56.10%                     | 9,473                | 12.80%                         | 21.90%                        | 14,865                   | 20.00%                             | 34.30%                            | 19,180    | 25.90%              | 44.20%             | 3,896              | 5.30%                        | 23,538          | 31.70%                    | 
| 2002        | 4 Year June     | 74,511           | 36,552          | 49.10%                    | 25,098            | 33.70%                      | 68.60%                     | 9,435                | 12.70%                         | 25.80%                        | 15,663                   | 21.00%                             | 42.80%                            | 11,489    | 15.40%              | 31.40%             | 21,721             | 29.20%                       | 13,758          | 18.50%                    | 
| 2002        | 5 Year          | 74,511           | 43,835          | 58.80%                    | 27,478            | 36.90%                      | 62.70%                     | 9,745                | 13.10%                         | 22.20%                        | 17,733                   | 23.80%                             | 40.50%                            | 16,625    | 22.30%              | 37.90%             | 8,927              | 12.00%                       | 18,434          | 24.70%                    | 
| 2002        | 6 Year          | 74,511           | 46,067          | 61.80%                    | 27,937            | 37.50%                      | 60.60%                     | 9,768                | 13.10%                         | 21.20%                        | 18,169                   | 24.40%                             | 39.40%                            | 18,398    | 24.70%              | 39.90%             | 4,729              | 6.30%                        | 20,140          | 27.00%                    | 
| 2003        | 4 Year June     | 73,888           | 38,990          | 52.80%                    | 27,445            | 37.10%                      | 70.40%                     | 11,356               | 15.40%                         | 29.10%                        | 16,089                   | 21.80%                             | 41.30%                            | 11,545    | 15.60%              | 29.60%             | 21,353             | 28.90%                       | 11,704          | 15.80%                    | 
| 2003        | 5 Year          | 73,888           | 46,265          | 62.60%                    | 29,887            | 40.40%                      | 64.60%                     | 11,594               | 15.70%                         | 25.10%                        | 18,293                   | 24.80%                             | 39.50%                            | 16,378    | 22.20%              | 35.40%             | 8,520              | 11.50%                       | 16,095          | 21.80%                    | 
| 2003        | 6 Year          | 74,027           | 48,586          | 65.60%                    | 30,483            | 41.20%                      | 62.70%                     | 11,607               | 15.70%                         | 23.90%                        | 18,876                   | 25.50%                             | 38.90%                            | 18,103    | 24.50%              | 37.30%             | 4,120              | 5.60%                        | 17,517          | 23.70%                    | 
| 2004        | 4 Year June     | 75,009           | 42,313          | 56.40%                    | 30,652            | 40.90%                      | 72.50%                     | 12,592               | 16.80%                         | 29.80%                        | 18,060                   | 24.10%                             | 42.70%                            | 11,661    | 15.50%              | 27.60%             | 20,844             | 27.80%                       | 10,127          | 13.50%                    | 
```