# Graduation Outcomes - Borough - Classes of 2005-2011 - Gender

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-borough-classes-of-2005-2011-gender-fa665) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sqb7-p8nz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sqb7-p8nz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sqb7-p8nz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sqb7-p8nz |
| Name | Graduation Outcomes - Borough - Classes of 2005-2011 - Gender |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, borough, gender, lifelong learning |
| Created | 2013-02-21T02:31:13Z |
| Publication Date | 2013-02-21T02:31:26Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by borough and gender

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
series e:sqb7-p8nz d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" t:borough=Bronx t:demographic=Female m:regents_w_o_advanced_pct_of_cohort=16.100000381469727 m:regents_w_o_advanced_num=890 m:advanced_regents_num=519 m:local_pct_of_cohort=23.600000381469727 m:advanced_regents_pct_of_grads=19.100000381469727 m:regents_w_o_advanced_pct_of_grads=32.79999923706055 m:advanced_regents_pct_of_cohort=9.399999618530273 m:still_enrolled_num=1547 m:dropped_out_num=1052 m:total_grads_pct_of_cohort=49 m:dropped_out_pct_of_cohort=19 m:local_num=1305 m:total_grads_num=2711 m:total_regents_pct_of_cohort=25.5 m:total_regents_pct_of_grads=52 m:total_cohort_num=5532 m:total_regents_num=1409 m:still_enrolled_pct_of_cohort=28 m:local_pct_of_grads=48.099998474121094

series e:sqb7-p8nz d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year" t:borough=Bronx t:demographic=Female m:regents_w_o_advanced_pct_of_cohort=17.5 m:regents_w_o_advanced_num=969 m:advanced_regents_num=528 m:local_pct_of_cohort=31.700000762939453 m:advanced_regents_pct_of_grads=16.299999237060547 m:regents_w_o_advanced_pct_of_grads=29.799999237060547 m:advanced_regents_pct_of_cohort=9.5 m:still_enrolled_num=605 m:dropped_out_num=1378 m:total_grads_pct_of_cohort=58.70000076293945 m:dropped_out_pct_of_cohort=24.899999618530273 m:local_num=1756 m:total_grads_num=3249 m:total_regents_pct_of_cohort=27.100000381469727 m:total_regents_pct_of_grads=46.099998474121094 m:total_cohort_num=5532 m:total_regents_num=1497 m:still_enrolled_pct_of_cohort=10.899999618530273 m:local_pct_of_grads=54

series e:sqb7-p8nz d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" t:borough=Bronx t:demographic=Female m:regents_w_o_advanced_pct_of_cohort=17.799999237060547 m:regents_w_o_advanced_num=987 m:advanced_regents_num=528 m:local_pct_of_cohort=34.20000076293945 m:advanced_regents_pct_of_grads=15.600000381469727 m:regents_w_o_advanced_pct_of_grads=29.100000381469727 m:advanced_regents_pct_of_cohort=9.5 m:still_enrolled_num=249 m:dropped_out_num=1574 m:total_grads_pct_of_cohort=61.29999923706055 m:dropped_out_pct_of_cohort=28.5 m:local_num=1891 m:total_grads_num=3391 m:total_regents_pct_of_cohort=27.399999618530273 m:total_regents_pct_of_grads=44.70000076293945 m:total_cohort_num=5532 m:total_regents_num=1515 m:still_enrolled_pct_of_cohort=4.5 m:local_pct_of_grads=55.79999923706055
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

entity e:sqb7-p8nz l:"Graduation Outcomes - Borough - Classes of 2005-2011 - Gender" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/sqb7-p8nz

property e:sqb7-p8nz t:meta.view v:id=sqb7-p8nz v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/F04F9067-BE45-450C-9F89-FEF6DE0229E9/0/Graduation_Rates_Public_Borough.xls v:averageRating=0 v:name="Graduation Outcomes - Borough - Classes of 2005-2011 - Gender" v:attribution="Department of Education (DOE)"

property e:sqb7-p8nz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sqb7-p8nz t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | cohort_year | cohort_category | demographic | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| ======= | =========== | =============== | =========== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| Bronx   | 2001        | 4 Year June     | Female      | 5,532            | 2,711           | 49.00%                    | 1,409             | 25.50%                      | 52.00%                     | 519                  | 9.40%                          | 19.10%                        | 890                      | 16.10%                             | 32.80%                            | 1,305     | 23.60%              | 48.10%             | 1,547              | 28.00%                       | 1,052           | 19.00%                    | 
| Bronx   | 2001        | 5 Year          | Female      | 5,532            | 3,249           | 58.70%                    | 1,497             | 27.10%                      | 46.10%                     | 528                  | 9.50%                          | 16.30%                        | 969                      | 17.50%                             | 29.80%                            | 1,756     | 31.70%              | 54.00%             | 605                | 10.90%                       | 1,378           | 24.90%                    | 
| Bronx   | 2001        | 6 Year          | Female      | 5,532            | 3,391           | 61.30%                    | 1,515             | 27.40%                      | 44.70%                     | 528                  | 9.50%                          | 15.60%                        | 987                      | 17.80%                             | 29.10%                            | 1,891     | 34.20%              | 55.80%             | 249                | 4.50%                        | 1,574           | 28.50%                    | 
| Bronx   | 2002        | 4 Year June     | Female      | 5,835            | 2,921           | 50.10%                    | 1,652             | 28.30%                      | 56.60%                     | 474                  | 8.10%                          | 16.20%                        | 1,178                    | 20.20%                             | 40.30%                            | 1,273     | 21.80%              | 43.60%             | 1,832              | 31.40%                       | 880             | 15.10%                    | 
| Bronx   | 2002        | 5 Year          | Female      | 5,835            | 3,527           | 60.40%                    | 1,789             | 30.70%                      | 50.70%                     | 486                  | 8.30%                          | 13.80%                        | 1,303                    | 22.30%                             | 36.90%                            | 1,764     | 30.20%              | 50.00%             | 770                | 13.20%                       | 1,265           | 21.70%                    | 
| Bronx   | 2002        | 6 Year          | Female      | 5,835            | 3,695           | 63.30%                    | 1,808             | 31.00%                      | 48.90%                     | 486                  | 8.30%                          | 13.20%                        | 1,322                    | 22.70%                             | 35.80%                            | 1,913     | 32.80%              | 51.80%             | 453                | 7.80%                        | 1,389           | 23.80%                    | 
| Bronx   | 2003        | 4 Year June     | Female      | 6,688            | 3,498           | 52.30%                    | 2,081             | 31.10%                      | 59.50%                     | 649                  | 9.70%                          | 18.60%                        | 1,432                    | 21.40%                             | 40.90%                            | 1,417     | 21.20%              | 40.50%             | 1,969              | 29.40%                       | 1,015           | 15.20%                    | 
| Bronx   | 2003        | 5 Year          | Female      | 6,688            | 4,148           | 62.00%                    | 2,213             | 33.10%                      | 53.40%                     | 655                  | 9.80%                          | 15.80%                        | 1,558                    | 23.30%                             | 37.60%                            | 1,935     | 28.90%              | 46.60%             | 863                | 12.90%                       | 1,354           | 20.20%                    | 
| Bronx   | 2003        | 6 Year          | Female      | 6,723            | 4,359           | 64.80%                    | 2,238             | 33.30%                      | 51.30%                     | 656                  | 9.80%                          | 15.00%                        | 1,582                    | 23.50%                             | 36.30%                            | 2,121     | 31.50%              | 48.70%             | 488                | 7.30%                        | 1,472           | 21.90%                    | 
| Bronx   | 2004        | 4 Year June     | Female      | 7,085            | 4,091           | 57.70%                    | 2,552             | 36.00%                      | 62.40%                     | 731                  | 10.30%                         | 17.90%                        | 1,821                    | 25.70%                             | 44.50%                            | 1,539     | 21.70%              | 37.60%             | 1,853              | 26.20%                       | 980             | 13.80%                    | 
```