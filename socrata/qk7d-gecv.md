# Regents Exam Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regents-exam-results) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qk7d-gecv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qk7d-gecv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qk7d-gecv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qk7d-gecv |
| Name | Regents Exam Results |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | regents, exams, schools, graduation |
| Created | 2016-03-08T21:53:08Z |
| Publication Date | 2016-03-08T21:58:07Z |

## Description

Regents results by School for all subjects, by year.

Cohorts of 2001 through 2011 (Classes of 2005 through 2015)
Graduation Outcomes as Calculated by the New York State Education Department
The New York State calculation method was first adopted for the Cohort of 2001 (Class of 2005).  The cohort consists of all students who first entered 9th grade in a given school year (e.g., the Cohort of 2006 entered 9th grade in the 2006-2007 school year).  Graduates are defined as those students earning either a Local or Regents diploma and exclude those earning either a special education (IEP) diploma or GED. 

In order to comply with FERPA regulations on public reporting of education outcomes, rows with a cohort of 20 or fewer students are suppressed.
Due to the small number of students identified as Native American or Multi-Racial, these ethnicities are not reported on the Ethnicity tab; however, these students are included in the counts on all other tabs.
4 Year August outcomes are available for the 2004-2011 cohorts at the citywide level and for the 2005-2011 cohorts at the borough, district and school level. 5 Year August outcomes are available for the 2006-2010 cohorts. Cells are blank when data is not available.
Charter schools are not included in the NYSED calculation of graduation rates for NYC.
School level results are not presented for District 79 and District 75 schools, but their outcomes are included in citywide totals.
Starting with the 2009 cohort (Class of 2013), students with IEPs could use the compensatory score option (CSO) to meet graduation requirements, which contributed to an increase in the graduation rate. 
Students are considered English Language Learners by NY State if classified as an ELL as of graduation.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                             | Data Type | Render Type |
| ======== | ============== | =============================== | ================================ | ========= | =========== |
| Yes      | time           | cohort_year                     | Cohort Year                      | number    | number      |
| Yes      | series tag     | cohort_category                 | Cohort Category                  | text      | text        |
| Yes      | series tag     | demographic                     | Demographic                      | text      | text        |
| Yes      | numeric metric | total_cohort                    | # Total Cohort                   | number    | number      |
| Yes      | numeric metric | total_grads                     | # Total Grads                    | number    | number      |
| Yes      | numeric metric | of_cohort_total_grads_1         | % of cohort Total Grads          | percent   | percent     |
| Yes      | numeric metric | of_cohort_total_grads_2         | # of cohort Total Grads          | number    | number      |
| Yes      | numeric metric | of_cohort_total_regents         | % of cohort Total Regents        | percent   | percent     |
| Yes      | numeric metric | of_grads_total_regents_1        | % of grads Total Regents         | percent   | percent     |
| Yes      | numeric metric | of_grads_total_regents_2        | # of grads Total Regents         | number    | number      |
| Yes      | numeric metric | of_cohort_advanced_regents      | % of cohort Advanced Regents     | percent   | percent     |
| Yes      | numeric metric | of_grads_advanced_regents_1     | % of grads Advanced Regents      | percent   | percent     |
| Yes      | numeric metric | of_grads_advanced_regents_2     | # of grads Advanced Regents      | number    | number      |
| Yes      | numeric metric | of_cohort_regents_w_o_advanced  | % of cohort Regents w/o Advanced | percent   | percent     |
| Yes      | numeric metric | of_grads_regents_w_o_advanced_1 | % of grads Regents w/o Advanced  | percent   | percent     |
| Yes      | numeric metric | of_grads_regents_w_o_advanced_2 | # of grads Regents w/o Advanced  | number    | number      |
| Yes      | numeric metric | of_cohort_local                 | % of cohort Local                | percent   | percent     |
| Yes      | numeric metric | of_grads_local                  | % of grads Local                 | percent   | percent     |
| Yes      | numeric metric | still_enrolled                  | # Still Enrolled                 | number    | number      |
| Yes      | numeric metric | of_cohort_still_enrolled        | % of cohort Still Enrolled       | percent   | percent     |
| Yes      | numeric metric | dropped_out                     | # Dropped Out                    | number    | number      |
| Yes      | numeric metric | of_cohort_dropped_out           | % of cohort Dropped Out          | percent   | percent     |
```

## Time Field

```ls
Value = cohort_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qk7d-gecv d:2001-01-01T00:00:00.000Z t:cohort_category="4 Year  June" t:demographic="English Language Learner" m:of_cohort_regents_w_o_advanced=6.4 m:of_grads_total_regents_1=35.5 m:of_grads_total_regents_2=315 m:total_grads=2791 m:of_grads_local=64.6 m:of_cohort_advanced_regents=3 m:of_cohort_still_enrolled=37 m:dropped_out=3220 m:total_cohort=10540 m:of_grads_advanced_regents_1=11.3 m:of_grads_advanced_regents_2=677 m:of_grads_regents_w_o_advanced_1=24.3 m:of_cohort_total_grads_1=26.5 m:of_cohort_total_grads_2=992 m:of_cohort_local=17.1 m:still_enrolled=3895 m:of_grads_regents_w_o_advanced_2=1803 m:of_cohort_total_regents=9 m:of_cohort_dropped_out=30.6

series e:qk7d-gecv d:2001-01-01T00:00:00.000Z t:cohort_category="5 Year  June" t:demographic="English Language Learner" m:of_cohort_regents_w_o_advanced=8.2 m:of_grads_total_regents_1=31.5 m:of_grads_total_regents_2=371 m:total_grads=3920 m:of_grads_local=68.9 m:of_cohort_advanced_regents=3.5 m:of_cohort_still_enrolled=14.4 m:dropped_out=4193 m:total_cohort=10540 m:of_grads_advanced_regents_1=9.5 m:of_grads_advanced_regents_2=862 m:of_grads_regents_w_o_advanced_1=22 m:of_cohort_total_grads_1=37.2 m:of_cohort_total_grads_2=1233 m:of_cohort_local=25.6 m:still_enrolled=1516 m:of_grads_regents_w_o_advanced_2=2701 m:of_cohort_total_regents=11.7 m:of_cohort_dropped_out=39.8

series e:qk7d-gecv d:2001-01-01T00:00:00.000Z t:cohort_category="6 Year" t:demographic="English Language Learner" m:of_cohort_regents_w_o_advanced=8.6 m:of_grads_total_regents_1=30.1 m:of_grads_total_regents_2=380 m:total_grads=4296 m:of_grads_local=70.5 m:of_cohort_advanced_regents=3.6 m:of_cohort_still_enrolled=6.2 m:dropped_out=4598 m:total_cohort=10540 m:of_grads_advanced_regents_1=8.8 m:of_grads_advanced_regents_2=911 m:of_grads_regents_w_o_advanced_1=21.2 m:of_cohort_total_grads_1=40.8 m:of_cohort_total_grads_2=1291 m:of_cohort_local=28.7 m:still_enrolled=655 m:of_grads_regents_w_o_advanced_2=3028 m:of_cohort_total_regents=12.2 m:of_cohort_dropped_out=43.6
```

## Meta Commands

```ls
metric m:total_cohort p:integer l:"# Total Cohort" t:dataTypeName=number

metric m:total_grads p:integer l:"# Total Grads" t:dataTypeName=number

metric m:of_cohort_total_grads_1 p:float l:"% of cohort Total Grads" t:dataTypeName=percent

metric m:of_cohort_total_grads_2 p:integer l:"# of cohort Total Grads" t:dataTypeName=number

metric m:of_cohort_total_regents p:float l:"% of cohort Total Regents" t:dataTypeName=percent

metric m:of_grads_total_regents_1 p:float l:"% of grads Total Regents" t:dataTypeName=percent

metric m:of_grads_total_regents_2 p:integer l:"# of grads Total Regents" t:dataTypeName=number

metric m:of_cohort_advanced_regents p:float l:"% of cohort Advanced Regents" t:dataTypeName=percent

metric m:of_grads_advanced_regents_1 p:float l:"% of grads Advanced Regents" t:dataTypeName=percent

metric m:of_grads_advanced_regents_2 p:integer l:"# of grads Advanced Regents" t:dataTypeName=number

metric m:of_cohort_regents_w_o_advanced p:float l:"% of cohort Regents w/o Advanced" t:dataTypeName=percent

metric m:of_grads_regents_w_o_advanced_1 p:float l:"% of grads Regents w/o Advanced" t:dataTypeName=percent

metric m:of_grads_regents_w_o_advanced_2 p:integer l:"# of grads Regents w/o Advanced" t:dataTypeName=number

metric m:of_cohort_local p:float l:"% of cohort Local" t:dataTypeName=percent

metric m:of_grads_local p:float l:"% of grads Local" t:dataTypeName=percent

metric m:still_enrolled p:integer l:"# Still Enrolled" t:dataTypeName=number

metric m:of_cohort_still_enrolled p:float l:"% of cohort Still Enrolled" t:dataTypeName=percent

metric m:dropped_out p:integer l:"# Dropped Out" t:dataTypeName=number

metric m:of_cohort_dropped_out p:float l:"% of cohort Dropped Out" t:dataTypeName=percent

entity e:qk7d-gecv l:"Regents Exam Results" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qk7d-gecv

property e:qk7d-gecv t:meta.view v:id=qk7d-gecv v:category=Education v:averageRating=0 v:name="Regents Exam Results" v:attribution="Department of Education (DOE)"

property e:qk7d-gecv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qk7d-gecv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| cohort_year | cohort_category | demographic              | total_cohort | total_grads | of_cohort_total_grads_1 | of_cohort_total_grads_2 | of_cohort_total_regents | of_grads_total_regents_1 | of_grads_total_regents_2 | of_cohort_advanced_regents | of_grads_advanced_regents_1 | of_grads_advanced_regents_2 | of_cohort_regents_w_o_advanced | of_grads_regents_w_o_advanced_1 | of_grads_regents_w_o_advanced_2 | of_cohort_local | of_grads_local | still_enrolled | of_cohort_still_enrolled | dropped_out | of_cohort_dropped_out | 
| =========== | =============== | ======================== | ============ | =========== | ======================= | ======================= | ======================= | ======================== | ======================== | ========================== | =========================== | =========================== | ============================== | =============================== | =============================== | =============== | ============== | ============== | ======================== | =========== | ===================== | 
| 2001        | 4 Year June     | English Language Learner | 10540        | 2791        | 26.50                   | 992                     | 9.00                    | 35.50                    | 315                      | 3.00                       | 11.30                       | 677                         | 6.40                           | 24.30                           | 1803                            | 17.10           | 64.60          | 3895           | 37.00                    | 3220        | 30.60                 | 
| 2001        | 5 Year June     | English Language Learner | 10540        | 3920        | 37.20                   | 1233                    | 11.70                   | 31.50                    | 371                      | 3.50                       | 9.50                        | 862                         | 8.20                           | 22.00                           | 2701                            | 25.60           | 68.90          | 1516           | 14.40                    | 4193        | 39.80                 | 
| 2001        | 6 Year          | English Language Learner | 10540        | 4296        | 40.80                   | 1291                    | 12.20                   | 30.10                    | 380                      | 3.60                       | 8.80                        | 911                         | 8.60                           | 21.20                           | 3028                            | 28.70           | 70.50          | 655            | 6.20                     | 4598        | 43.60                 | 
| 2002        | 4 Year June     | English Language Learner | 7454         | 1691        | 22.70                   | 639                     | 8.60                    | 37.80                    | 132                      | 1.80                       | 7.80                        | 507                         | 6.80                           | 30.00                           | 1062                            | 14.20           | 62.80          | 3062           | 41.10                    | 2330        | 31.30                 | 
| 2002        | 5 Year June     | English Language Learner | 7454         | 2354        | 31.60                   | 794                     | 10.70                   | 33.70                    | 176                      | 2.40                       | 7.50                        | 618                         | 8.30                           | 26.30                           | 1578                            | 21.20           | 67.00          | 1457           | 19.50                    | 3041        | 40.80                 | 
| 2002        | 6 Year          | English Language Learner | 7454         | 2729        | 36.60                   | 856                     | 11.50                   | 31.40                    | 185                      | 2.50                       | 6.80                        | 671                         | 9.00                           | 24.60                           | 1891                            | 25.40           | 69.30          | 697            | 9.40                     | 3356        | 45.00                 | 
| 2003        | 4 Year June     | English Language Learner | 8163         | 2052        | 25.10                   | 909                     | 11.10                   | 44.30                    | 290                      | 3.60                       | 14.10                       | 619                         | 7.60                           | 30.20                           | 1143                            | 14.00           | 55.70          | 3360           | 41.20                    | 2394        | 29.30                 | 
| 2003        | 5 Year June     | English Language Learner | 8163         | 3105        | 38.00                   | 1159                    | 14.20                   | 37.30                    | 358                      | 4.40                       | 11.50                       | 801                         | 9.80                           | 25.80                           | 1946                            | 23.80           | 62.70          | 1327           | 16.30                    | 3111        | 38.10                 | 
| 2003        | 6 Year          | English Language Learner | 8041         | 3394        | 42.20                   | 1216                    | 15.10                   | 35.80                    | 363                      | 4.50                       | 10.70                       | 853                         | 10.60                          | 25.10                           | 2178                            | 27.10           | 64.20          | 570            | 7.10                     | 3361        | 41.80                 | 
| 2004        | 4 Year June     | English Language Learner | 8486         | 3039        | 35.80                   | 1504                    | 17.70                   | 49.50                    | 487                      | 5.70                       | 16.00                       | 1017                        | 12.00                          | 33.50                           | 1535                            | 18.10           | 50.50          | 3288           | 38.70                    | 1840        | 21.70                 | 
```