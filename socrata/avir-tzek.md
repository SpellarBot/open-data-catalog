# Graduation Outcomes - Classes Of 2005-2010 By Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-classes-of-2005-2010-by-borough-f7bb6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/avir-tzek) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/avir-tzek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/avir-tzek/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | avir-tzek |
| Name | Graduation Outcomes - Classes Of 2005-2010 By Borough |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-18T17:29:17Z |
| Publication Date | 2011-10-18T17:30:50Z |

## Description

Graduation Outcomes - 4 Year Outcome - Cohorts of 2001 through 2006 (Classes of 2005 through 2010) 

?The New York State calculation method was first adopted for the Cohort of 2001 (Class of 2005). The cohort consists of all students who first entered 9th grade in a given school year (e.g., the Cohort of 2006 entered 9th grade in the 2006-2007 school year). Graduates are defined as those students earning either a Local or Regents diploma and exclude those earning either a special education (IEP) diploma or GED. For the most recent cohort, graduation rates as of both June and August (including summer graduates) are reported. 

?Records with cohorts of 20 students or less are suppressed. August outcomes are only reported for the most recent cohort. 

?August outcomes include all June and August graduates. 

?In school-level reporting, students who were in a school for less than 5 months are not included in the school?s cohort, but are included in citywide totals. 

?School level results are not presented for District 79 schools, but their outcomes are included in citywide totals.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                               | Data Type | Render Type |
| ======== | ============== | ============================== | ================================== | ========= | =========== |
| Yes      | series tag     | demographic                    | Demographic                        | text      | text        |
| Yes      | series tag     | borough                        | Borough                            | text      | text        |
| Yes      | series tag     | cohort                         | Cohort                             | text      | text        |
| Yes      | numeric metric | total_cohort                   | Total Cohort                       | number    | number      |
| Yes      | numeric metric | total_grads_n                  | Total Grads - n                    | number    | number      |
| Yes      | numeric metric | total_grads_of_cohort          | Total Grads - % of cohort          | percent   | percent     |
| Yes      | numeric metric | total_regents_n                | Total Regents - n                  | number    | number      |
| Yes      | numeric metric | total_regents_of_cohort        | Total Regents - % of cohort        | percent   | percent     |
| Yes      | numeric metric | total_regents_of_grads         | Total Regents - % of grads         | percent   | percent     |
| Yes      | numeric metric | advanced_regents_n             | Advanced Regents - n               | number    | number      |
| Yes      | numeric metric | advanced_regents_of_cohort     | Advanced Regents - % of cohort     | percent   | percent     |
| Yes      | numeric metric | advanced_regents_of_grads      | Advanced Regents - % of grads      | percent   | percent     |
| Yes      | numeric metric | regents_w_o_advanced_n         | Regents w/o Advanced - n           | number    | number      |
| Yes      | numeric metric | regents_w_o_advanced_of_cohort | Regents w/o Advanced - % of cohort | percent   | percent     |
| Yes      | numeric metric | regents_w_o_advanced_of_grads  | Regents w/o Advanced - % of grads  | percent   | percent     |
| Yes      | numeric metric | local_n                        | Local - n                          | number    | number      |
| Yes      | numeric metric | local_of_cohort                | Local - % of cohort                | percent   | percent     |
| Yes      | numeric metric | local_of_grads                 | Local - % of grads                 | percent   | percent     |
| Yes      | numeric metric | still_enrolled_n               | Still Enrolled - n                 | number    | number      |
| Yes      | numeric metric | still_enrolled_of_cohort       | Still Enrolled - % of cohort       | percent   | percent     |
| Yes      | numeric metric | dropped_out_n                  | Dropped Out - n                    | number    | number      |
| Yes      | numeric metric | dropped_out_of_cohort          | Dropped Out - % of cohort          | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:avir-tzek d:2005-01-01T00:00:00.000Z t:cohort=2001 t:borough=Bronx t:demographic="Borough Total" m:advanced_regents_of_grads=20.3 m:still_enrolled_n=3512 m:total_grads_of_cohort=42.9 m:still_enrolled_of_cohort=30.7 m:regents_w_o_advanced_of_grads=33.5 m:regents_w_o_advanced_of_cohort=14.4 m:local_n=2271 m:advanced_regents_of_cohort=8.7 m:local_of_grads=46.2 m:total_grads_n=4913 m:total_cohort=11453 m:total_regents_of_cohort=23.1 m:advanced_regents_n=998 m:total_regents_n=2644 m:dropped_out_of_cohort=21.3 m:regents_w_o_advanced_n=1646 m:local_of_cohort=19.8 m:total_regents_of_grads=53.8 m:dropped_out_n=2438

series e:avir-tzek d:2005-01-01T00:00:00.000Z t:cohort=2002 t:borough=Bronx t:demographic="Borough Total" m:advanced_regents_of_grads=18.6 m:still_enrolled_n=4047 m:total_grads_of_cohort=44.3 m:still_enrolled_of_cohort=33.6 m:regents_w_o_advanced_of_grads=39.9 m:regents_w_o_advanced_of_cohort=17.7 m:local_n=2217 m:advanced_regents_of_cohort=8.2 m:local_of_grads=41.6 m:total_grads_n=5328 m:total_cohort=12032 m:total_regents_of_cohort=25.9 m:advanced_regents_n=992 m:total_regents_n=3118 m:dropped_out_of_cohort=17.8 m:regents_w_o_advanced_n=2126 m:local_of_cohort=18.4 m:total_regents_of_grads=58.5 m:dropped_out_n=2140

series e:avir-tzek d:2005-01-01T00:00:00.000Z t:cohort=2003 t:borough=Bronx t:demographic="Borough Total" m:advanced_regents_of_grads=19.6 m:still_enrolled_n=4258 m:total_grads_of_cohort=46.9 m:still_enrolled_of_cohort=31.2 m:regents_w_o_advanced_of_grads=40.8 m:regents_w_o_advanced_of_cohort=19.1 m:local_n=2528 m:advanced_regents_of_cohort=9.2 m:local_of_grads=39.6 m:total_grads_n=6389 m:total_cohort=13632 m:total_regents_of_cohort=28.3 m:advanced_regents_n=1255 m:total_regents_n=3861 m:dropped_out_of_cohort=18.1 m:regents_w_o_advanced_n=2606 m:local_of_cohort=18.5 m:total_regents_of_grads=60.4 m:dropped_out_n=2472
```

## Meta Commands

```ls
metric m:total_cohort p:integer l:"Total Cohort" t:dataTypeName=number

metric m:total_grads_n p:integer l:"Total Grads - n" t:dataTypeName=number

metric m:total_grads_of_cohort p:float l:"Total Grads - % of cohort" t:dataTypeName=percent

metric m:total_regents_n p:integer l:"Total Regents - n" t:dataTypeName=number

metric m:total_regents_of_cohort p:float l:"Total Regents - % of cohort" t:dataTypeName=percent

metric m:total_regents_of_grads p:float l:"Total Regents - % of grads" t:dataTypeName=percent

metric m:advanced_regents_n p:integer l:"Advanced Regents - n" t:dataTypeName=number

metric m:advanced_regents_of_cohort p:float l:"Advanced Regents - % of cohort" t:dataTypeName=percent

metric m:advanced_regents_of_grads p:float l:"Advanced Regents - % of grads" t:dataTypeName=percent

metric m:regents_w_o_advanced_n p:integer l:"Regents w/o Advanced - n" t:dataTypeName=number

metric m:regents_w_o_advanced_of_cohort p:float l:"Regents w/o Advanced - % of cohort" t:dataTypeName=percent

metric m:regents_w_o_advanced_of_grads p:float l:"Regents w/o Advanced - % of grads" t:dataTypeName=percent

metric m:local_n p:integer l:"Local - n" t:dataTypeName=number

metric m:local_of_cohort p:float l:"Local - % of cohort" t:dataTypeName=percent

metric m:local_of_grads p:float l:"Local - % of grads" t:dataTypeName=percent

metric m:still_enrolled_n p:integer l:"Still Enrolled - n" t:dataTypeName=number

metric m:still_enrolled_of_cohort p:float l:"Still Enrolled - % of cohort" t:dataTypeName=percent

metric m:dropped_out_n p:integer l:"Dropped Out - n" t:dataTypeName=number

metric m:dropped_out_of_cohort p:float l:"Dropped Out - % of cohort" t:dataTypeName=percent

entity e:avir-tzek l:"Graduation Outcomes - Classes Of 2005-2010 By Borough" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/avir-tzek

property e:avir-tzek t:meta.view v:id=avir-tzek v:category=Education v:averageRating=0 v:name="Graduation Outcomes - Classes Of 2005-2010 By Borough" v:attribution="Department of Education (DOE)"

property e:avir-tzek t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:avir-tzek t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| demographic   | borough  | cohort   | total_cohort | total_grads_n | total_grads_of_cohort | total_regents_n | total_regents_of_cohort | total_regents_of_grads | advanced_regents_n | advanced_regents_of_cohort | advanced_regents_of_grads | regents_w_o_advanced_n | regents_w_o_advanced_of_cohort | regents_w_o_advanced_of_grads | local_n | local_of_cohort    | local_of_grads     | still_enrolled_n | still_enrolled_of_cohort | dropped_out_n | dropped_out_of_cohort | 
| ============= | ======== | ======== | ============ | ============= | ===================== | =============== | ======================= | ====================== | ================== | ========================== | ========================= | ====================== | ============================== | ============================= | ======= | ================== | ================== | ================ | ======================== | ============= | ===================== | 
| Borough Total | Bronx    | 2001     | 11453        | 4913          | 42.9                  | 2644            | 23.1                    | 53.8                   | 998                | 8.6999999999999993         | 20.3                      | 1646                   | 14.4                           | 33.5                          | 2271    | 19.8               | 46.2               | 3512             | 30.7                     | 2438          | 21.3                  | 
| Borough Total | Bronx    | 2002     | 12032        | 5328          | 44.3                  | 3118            | 25.9                    | 58.5                   | 992                | 8.1999999999999993         | 18.600000000000001        | 2126                   | 17.7                           | 39.9                          | 2217    | 18.399999999999999 | 41.6               | 4047             | 33.6                     | 2140          | 17.8                  | 
| Borough Total | Bronx    | 2003     | 13632        | 6389          | 46.9                  | 3861            | 28.3                    | 60.4                   | 1255               | 9.1999999999999993         | 19.600000000000001        | 2606                   | 19.100000000000001             | 40.799999999999997            | 2528    | 18.5               | 39.6               | 4258             | 31.2                     | 2472          | 18.100000000000001    | 
| Borough Total | Bronx    | 2004     | 14364        | 7448          | 51.9                  | 4625            | 32.200000000000003      | 62.1                   | 1395               | 9.6999999999999993         | 18.7                      | 3230                   | 22.5                           | 43.4                          | 2823    | 19.7               | 37.9               | 4169             | 29                       | 2303          | 16                    | 
| Borough Total | Bronx    | 2005     | 15175        | 8229          | 54.2                  | 5618            | 37                      | 68.3                   | 1544               | 10.199999999999999         | 18.8                      | 4074                   | 26.8                           | 49.5                          | 2611    | 17.2               | 31.7               | 3943             | 26                       | 2147          | 14.1                  | 
| Borough Total | Bronx    | 2006     | 15579        | 8524          | 54.7                  | 6312            | 40.5                    | 74                     | 1558               | 10                         | 18.3                      | 4754                   | 30.5                           | 55.8                          | 2212    | 14.2               | 26                 | 3824             | 24.5                     | 2402          | 15.4                  | 
| Borough Total | Bronx    | Aug 2006 | 15579        | 9215          | 59.2                  | 6605            | 42.4                    | 71.7                   | 1572               | 10.1                       | 17.100000000000001        | 5033                   | 32.299999999999997             | 54.6                          | 2610    | 16.8               | 28.3               | 3160             | 20.3                     | 2375          | 15.2                  | 
| Borough Total | Brooklyn | 2001     | 19961        | 9758          | 48.9                  | 6177            | 30.9                    | 63.3                   | 2829               | 14.2                       | 29                        | 3348                   | 16.8                           | 34.299999999999997            | 3591    | 18                 | 36.799999999999997 | 6101             | 30.6                     | 3547          | 17.8                  | 
| Borough Total | Brooklyn | 2002     | 20808        | 10337         | 49.7                  | 7050            | 33.9                    | 68.2                   | 2865               | 13.8                       | 27.7                      | 4185                   | 20.100000000000001             | 40.5                          | 3298    | 15.8               | 31.9               | 6368             | 30.6                     | 3369          | 16.2                  | 
| Borough Total | Brooklyn | 2003     | 21334        | 11064         | 51.9                  | 7711            | 36.1                    | 69.7                   | 3239               | 15.2                       | 29.3                      | 4472                   | 21                             | 40.4                          | 3353    | 15.7               | 30.3               | 6571             | 30.8                     | 3198          | 15                    | 
```