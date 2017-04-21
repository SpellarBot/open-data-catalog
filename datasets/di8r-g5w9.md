# Graduation Outcomes - Borough - Classes of 2005-2011 - Total Cohort

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-borough-classes-of-2005-2011-total-cohort-4fdb7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/di8r-g5w9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/di8r-g5w9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/di8r-g5w9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | di8r-g5w9 |
| Name | Graduation Outcomes - Borough - Classes of 2005-2011 - Total Cohort |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | graduation outcome, school, borough, total cohort, lifelong learning |
| Created | 2013-02-21T02:31:40Z |
| Publication Date | 2013-02-21T02:31:54Z |

## Description

Latest available data and trends in graduation and dropout outcomes disaggregated by borough.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | borough                            | Borough                            | text      | text        |
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
series e:di8r-g5w9 d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" t:borough=Bronx m:regents_w_o_advanced_pct_of_cohort=14.399999618530273 m:regents_w_o_advanced_num=1646 m:advanced_regents_num=998 m:local_pct_of_cohort=19.799999237060547 m:advanced_regents_pct_of_grads=20.299999237060547 m:regents_w_o_advanced_pct_of_grads=33.5 m:advanced_regents_pct_of_cohort=8.699999809265137 m:still_enrolled_num=3512 m:dropped_out_num=2438 m:total_grads_pct_of_cohort=42.900001525878906 m:dropped_out_pct_of_cohort=21.299999237060547 m:local_num=2271 m:total_grads_num=4913 m:total_regents_pct_of_cohort=23.100000381469727 m:total_regents_pct_of_grads=53.79999923706055 m:total_cohort_num=11453 m:total_regents_num=2644 m:still_enrolled_pct_of_cohort=30.700000762939453 m:local_pct_of_grads=46.20000076293945

series e:di8r-g5w9 d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year" t:borough=Bronx m:regents_w_o_advanced_pct_of_cohort=16 m:regents_w_o_advanced_num=1837 m:advanced_regents_num=1022 m:local_pct_of_cohort=28 m:advanced_regents_pct_of_grads=16.899999618530273 m:regents_w_o_advanced_pct_of_grads=30.299999237060547 m:advanced_regents_pct_of_cohort=8.899999618530273 m:still_enrolled_num=1412 m:dropped_out_num=3178 m:total_grads_pct_of_cohort=52.900001525878906 m:dropped_out_pct_of_cohort=27.700000762939453 m:local_num=3209 m:total_grads_num=6058 m:total_regents_pct_of_cohort=25 m:total_regents_pct_of_grads=47.20000076293945 m:total_cohort_num=11453 m:total_regents_num=2859 m:still_enrolled_pct_of_cohort=12.300000190734863 m:local_pct_of_grads=53

series e:di8r-g5w9 d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" t:borough=Bronx m:regents_w_o_advanced_pct_of_cohort=16.399999618530273 m:regents_w_o_advanced_num=1873 m:advanced_regents_num=1022 m:local_pct_of_cohort=30.600000381469727 m:advanced_regents_pct_of_grads=16.100000381469727 m:regents_w_o_advanced_pct_of_grads=29.399999618530273 m:advanced_regents_pct_of_cohort=8.899999618530273 m:still_enrolled_num=610 m:dropped_out_num=3614 m:total_grads_pct_of_cohort=55.5 m:dropped_out_pct_of_cohort=31.600000381469727 m:local_num=3501 m:total_grads_num=6360 m:total_regents_pct_of_cohort=25.299999237060547 m:total_regents_pct_of_grads=45.5 m:total_cohort_num=11453 m:total_regents_num=2895 m:still_enrolled_pct_of_cohort=5.300000190734863 m:local_pct_of_grads=55
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

entity e:di8r-g5w9 l:"Graduation Outcomes - Borough - Classes of 2005-2011 - Total Cohort" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/di8r-g5w9

property e:di8r-g5w9 t:meta.view v:id=di8r-g5w9 v:category=Education v:attributionLink=http://schools.nyc.gov/NR/rdonlyres/F04F9067-BE45-450C-9F89-FEF6DE0229E9/0/Graduation_Rates_Public_Borough.xls v:averageRating=0 v:name="Graduation Outcomes - Borough - Classes of 2005-2011 - Total Cohort" v:attribution="Department of Education (DOE)"

property e:di8r-g5w9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:di8r-g5w9 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| borough | cohort_year | cohort_category | total_cohort_num | total_grads_num | total_grads_pct_of_cohort | total_regents_num | total_regents_pct_of_cohort | total_regents_pct_of_grads | advanced_regents_num | advanced_regents_pct_of_cohort | advanced_regents_pct_of_grads | regents_w_o_advanced_num | regents_w_o_advanced_pct_of_cohort | regents_w_o_advanced_pct_of_grads | local_num | local_pct_of_cohort | local_pct_of_grads | still_enrolled_num | still_enrolled_pct_of_cohort | dropped_out_num | dropped_out_pct_of_cohort | 
| ======= | =========== | =============== | ================ | =============== | ========================= | ================= | =========================== | ========================== | ==================== | ============================== | ============================= | ======================== | ================================== | ================================= | ========= | =================== | ================== | ================== | ============================ | =============== | ========================= | 
| Bronx   | 2001        | 4 Year June     | 11,453           | 4,913           | 42.90%                    | 2,644             | 23.10%                      | 53.80%                     | 998                  | 8.70%                          | 20.30%                        | 1,646                    | 14.40%                             | 33.50%                            | 2,271     | 19.80%              | 46.20%             | 3,512              | 30.70%                       | 2,438           | 21.30%                    | 
| Bronx   | 2001        | 5 Year          | 11,453           | 6,058           | 52.90%                    | 2,859             | 25.00%                      | 47.20%                     | 1,022                | 8.90%                          | 16.90%                        | 1,837                    | 16.00%                             | 30.30%                            | 3,209     | 28.00%              | 53.00%             | 1,412              | 12.30%                       | 3,178           | 27.70%                    | 
| Bronx   | 2001        | 6 Year          | 11,453           | 6,360           | 55.50%                    | 2,895             | 25.30%                      | 45.50%                     | 1,022                | 8.90%                          | 16.10%                        | 1,873                    | 16.40%                             | 29.40%                            | 3,501     | 30.60%              | 55.00%             | 610                | 5.30%                        | 3,614           | 31.60%                    | 
| Bronx   | 2002        | 4 Year June     | 12,032           | 5,328           | 44.30%                    | 3,118             | 25.90%                      | 58.50%                     | 992                  | 8.20%                          | 18.60%                        | 2,126                    | 17.70%                             | 39.90%                            | 2,217     | 18.40%              | 41.60%             | 4,047              | 33.60%                       | 2,140           | 17.80%                    | 
| Bronx   | 2002        | 5 Year          | 12,032           | 6,582           | 54.70%                    | 3,401             | 28.30%                      | 51.70%                     | 1,013                | 8.40%                          | 15.40%                        | 2,388                    | 19.80%                             | 36.30%                            | 3,232     | 26.90%              | 49.10%             | 1,724              | 14.30%                       | 3,008           | 25.00%                    | 
| Bronx   | 2002        | 6 Year          | 12,032           | 6,964           | 57.90%                    | 3,459             | 28.70%                      | 49.70%                     | 1,014                | 8.40%                          | 14.60%                        | 2,445                    | 20.30%                             | 35.10%                            | 3,556     | 29.60%              | 51.10%             | 1,024              | 8.50%                        | 3,255           | 27.10%                    | 
| Bronx   | 2003        | 4 Year June     | 13,632           | 6,389           | 46.90%                    | 3,861             | 28.30%                      | 60.40%                     | 1,255                | 9.20%                          | 19.60%                        | 2,606                    | 19.10%                             | 40.80%                            | 2,528     | 18.50%              | 39.60%             | 4,258              | 31.20%                       | 2,472           | 18.10%                    | 
| Bronx   | 2003        | 5 Year          | 13,632           | 7,728           | 56.70%                    | 4,179             | 30.70%                      | 54.10%                     | 1,271                | 9.30%                          | 16.40%                        | 2,908                    | 21.30%                             | 37.60%                            | 3,549     | 26.00%              | 45.90%             | 1,879              | 13.80%                       | 3,211           | 23.60%                    | 
| Bronx   | 2003        | 6 Year          | 13,681           | 8,186           | 59.80%                    | 4,255             | 31.10%                      | 52.00%                     | 1,272                | 9.30%                          | 15.50%                        | 2,983                    | 21.80%                             | 36.40%                            | 3,931     | 28.70%              | 48.00%             | 1,032              | 7.50%                        | 3,481           | 25.40%                    | 
| Bronx   | 2004        | 4 Year June     | 14,364           | 7,448           | 51.90%                    | 4,625             | 32.20%                      | 62.10%                     | 1,395                | 9.70%                          | 18.70%                        | 3,230                    | 22.50%                             | 43.40%                            | 2,823     | 19.70%              | 37.90%             | 4,169              | 29.00%                       | 2,303           | 16.00%                    | 
```