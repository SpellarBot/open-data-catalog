# Graduation Outcomes - Borough - Classes of 2005-2011 - Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-borough-classes-of-2005-2011-ethnicity-9e568) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x2hp-8ukt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x2hp-8ukt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x2hp-8ukt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x2hp-8ukt |
| Name | Graduation Outcomes - Borough - Classes of 2005-2011 - Ethnicity |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, borough, ethnicity, lifelong learning |
| Created | 2013-02-21T02:30:57Z |
| Publication Date | 2013-02-21T02:31:12Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by borough and ethnicity.

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
series e:x2hp-8ukt d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" t:borough=Bronx t:demographic=Asian m:regents_w_o_advanced_pct_of_cohort=12.899999618530273 m:regents_w_o_advanced_num=82 m:advanced_regents_num=314 m:local_pct_of_cohort=13.199999809265137 m:advanced_regents_pct_of_grads=65.5999984741211 m:regents_w_o_advanced_pct_of_grads=17.100000381469727 m:advanced_regents_pct_of_cohort=49.20000076293945 m:still_enrolled_num=92 m:dropped_out_num=60 m:total_grads_pct_of_cohort=75.0999984741211 m:dropped_out_pct_of_cohort=9.399999618530273 m:local_num=84 m:total_grads_num=479 m:total_regents_pct_of_cohort=62.099998474121094 m:total_regents_pct_of_grads=82.69999694824219 m:total_cohort_num=638 m:total_regents_num=396 m:still_enrolled_pct_of_cohort=14.399999618530273 m:local_pct_of_grads=17.5

series e:x2hp-8ukt d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year" t:borough=Bronx t:demographic=Asian m:regents_w_o_advanced_pct_of_cohort=14.600000381469727 m:regents_w_o_advanced_num=93 m:advanced_regents_num=323 m:local_pct_of_cohort=17.700000762939453 m:advanced_regents_pct_of_grads=61.20000076293945 m:regents_w_o_advanced_pct_of_grads=17.600000381469727 m:advanced_regents_pct_of_cohort=50.599998474121094 m:still_enrolled_num=26 m:dropped_out_num=75 m:total_grads_pct_of_cohort=82.80000305175781 m:dropped_out_pct_of_cohort=11.800000190734863 m:local_num=113 m:total_grads_num=528 m:total_regents_pct_of_cohort=65.19999694824219 m:total_regents_pct_of_grads=78.80000305175781 m:total_cohort_num=638 m:total_regents_num=416 m:still_enrolled_pct_of_cohort=4.099999904632568 m:local_pct_of_grads=21.399999618530273

series e:x2hp-8ukt d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" t:borough=Bronx t:demographic=Asian m:regents_w_o_advanced_pct_of_cohort=14.600000381469727 m:regents_w_o_advanced_num=93 m:advanced_regents_num=323 m:local_pct_of_cohort=19 m:advanced_regents_pct_of_grads=60.5 m:regents_w_o_advanced_pct_of_grads=17.399999618530273 m:advanced_regents_pct_of_cohort=50.599998474121094 m:still_enrolled_num=14 m:dropped_out_num=81 m:total_grads_pct_of_cohort=83.69999694824219 m:dropped_out_pct_of_cohort=12.699999809265137 m:local_num=121 m:total_grads_num=534 m:total_regents_pct_of_cohort=65.19999694824219 m:total_regents_pct_of_grads=77.9000015258789 m:total_cohort_num=638 m:total_regents_num=416 m:still_enrolled_pct_of_cohort=2.200000047683716 m:local_pct_of_grads=22.700000762939453
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

entity e:x2hp-8ukt l:"Graduation Outcomes - Borough - Classes of 2005-2011 - Ethnicity" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/x2hp-8ukt

property e:x2hp-8ukt t:meta.view v:id=x2hp-8ukt v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/F04F9067-BE45-450C-9F89-FEF6DE0229E9/0/Graduation_Rates_Public_Borough.xls v:averageRating=0 v:name="Graduation Outcomes - Borough - Classes of 2005-2011 - Ethnicity" v:attribution="Department of Education (DOE)"

property e:x2hp-8ukt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x2hp-8ukt t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | cohort_year | cohort_category | demographic | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| ======= | =========== | =============== | =========== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| Bronx   | 2001        | 4 Year June     | Asian       | 638              | 479             | 75.10%                    | 396               | 62.10%                      | 82.70%                     | 314                  | 49.20%                         | 65.60%                        | 82                       | 12.90%                             | 17.10%                            | 84        | 13.20%              | 17.50%             | 92                 | 14.40%                       | 60              | 9.40%                     | 
| Bronx   | 2001        | 5 Year          | Asian       | 638              | 528             | 82.80%                    | 416               | 65.20%                      | 78.80%                     | 323                  | 50.60%                         | 61.20%                        | 93                       | 14.60%                             | 17.60%                            | 113       | 17.70%              | 21.40%             | 26                 | 4.10%                        | 75              | 11.80%                    | 
| Bronx   | 2001        | 6 Year          | Asian       | 638              | 534             | 83.70%                    | 416               | 65.20%                      | 77.90%                     | 323                  | 50.60%                         | 60.50%                        | 93                       | 14.60%                             | 17.40%                            | 121       | 19.00%              | 22.70%             | 14                 | 2.20%                        | 81              | 12.70%                    | 
| Bronx   | 2002        | 4 Year June     | Asian       | 681              | 497             | 73.00%                    | 451               | 66.20%                      | 90.70%                     | 350                  | 51.40%                         | 70.40%                        | 101                      | 14.80%                             | 20.30%                            | 46        | 6.80%               | 9.30%              | 132                | 19.40%                       | 39              | 5.70%                     | 
| Bronx   | 2002        | 5 Year          | Asian       | 681              | 564             | 82.80%                    | 473               | 69.50%                      | 83.90%                     | 353                  | 51.80%                         | 62.60%                        | 120                      | 17.60%                             | 21.30%                            | 93        | 13.70%              | 16.50%             | 36                 | 5.30%                        | 63              | 9.30%                     | 
| Bronx   | 2002        | 6 Year          | Asian       | 681              | 574             | 84.30%                    | 474               | 69.60%                      | 82.60%                     | 353                  | 51.80%                         | 61.50%                        | 121                      | 17.80%                             | 21.10%                            | 102       | 15.00%              | 17.80%             | 20                 | 2.90%                        | 68              | 10.00%                    | 
| Bronx   | 2003        | 4 Year June     | Asian       | 672              | 552             | 82.10%                    | 487               | 72.50%                      | 88.20%                     | 382                  | 56.80%                         | 69.20%                        | 105                      | 15.60%                             | 19.00%                            | 65        | 9.70%               | 11.80%             | 82                 | 12.20%                       | 35              | 5.20%                     | 
| Bronx   | 2003        | 5 Year          | Asian       | 672              | 592             | 88.10%                    | 506               | 75.30%                      | 85.50%                     | 383                  | 57.00%                         | 64.70%                        | 123                      | 18.30%                             | 20.80%                            | 86        | 12.80%              | 14.50%             | 23                 | 3.40%                        | 49              | 7.30%                     | 
| Bronx   | 2003        | 6 Year          | Asian       | 675              | 600             | 88.90%                    | 507               | 75.10%                      | 84.50%                     | 383                  | 56.70%                         | 63.80%                        | 124                      | 18.40%                             | 20.70%                            | 93        | 13.80%              | 15.50%             | 13                 | 1.90%                        | 50              | 7.40%                     | 
| Bronx   | 2004        | 4 Year June     | Asian       | 748              | 624             | 83.40%                    | 560               | 74.90%                      | 89.70%                     | 421                  | 56.30%                         | 67.50%                        | 139                      | 18.60%                             | 22.30%                            | 64        | 8.60%               | 10.30%             | 98                 | 13.10%                       | 23              | 3.10%                     | 
```