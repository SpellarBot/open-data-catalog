# Graduation Outcomes - Classes Of 2005-2010 - School Level

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/graduation-outcomes-classes-of-2005-2010-school-level-f864c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vh2h-md7a) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vh2h-md7a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vh2h-md7a/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vh2h-md7a |
| Name | Graduation Outcomes - Classes Of 2005-2010 - School Level |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-18T20:28:07Z |
| Publication Date | 2011-10-18T20:29:57Z |

## Description

Graduation Outcomes - Cohorts of 2001 through 2006 (Classes of 2005 through 2010) 
???The New York State calculation method was first adopted for the Cohort of 2001 (Class of 2005). The cohort consists of all students who first entered 9th grade in a given school year (e.g., the Cohort of 2006 entered 9th grade in the 2006-2007 school year). Graduates are defined as those students earning either a Local or Regents diploma and exclude those earning either a special education (IEP) diploma or GED. For the most recent cohort, graduation rates as of both June and August (including summer graduates) are reported. 
???Records with cohorts of 20 students or less are suppressed. August outcomes are only reported for the most recent cohort. 
???August outcomes include all June and August graduates. In school-level reporting, students who were in a school for less than 5 months are not included in the school?s cohort, but are included in citywide totals. 
???School level results are not presented for District 79 schools, but their outcomes are included in citywide totals. 
???Schools are listed by their current DBN's.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                               | Data Type | Render Type |
| ======== | ============== | ============================== | ================================== | ========= | =========== |
| Yes      | series tag     | demographic                    | Demographic                        | text      | text        |
| Yes      | series tag     | dbn                            | DBN                                | text      | text        |
| Yes      | series tag     | school_name                    | School Name                        | text      | text        |
| Yes      | series tag     | cohort                         | Cohort                             | text      | text        |
| Yes      | numeric metric | total_cohort                   | Total Cohort                       | number    | number      |
| Yes      | series tag     | total_grads_n                  | Total Grads - n                    | text      | text        |
| Yes      | numeric metric | total_grads_of_cohort          | Total Grads - % of cohort          | percent   | percent     |
| Yes      | series tag     | total_regents_n                | Total Regents - n                  | text      | text        |
| Yes      | numeric metric | total_regents_of_cohort        | Total Regents - % of cohort        | percent   | percent     |
| Yes      | numeric metric | total_regents_of_grads         | Total Regents - % of grads         | percent   | percent     |
| Yes      | series tag     | advanced_regents_n             | Advanced Regents - n               | text      | text        |
| Yes      | numeric metric | advanced_regents_of_cohort     | Advanced Regents - % of cohort     | percent   | percent     |
| Yes      | numeric metric | advanced_regents_of_grads      | Advanced Regents - % of grads      | percent   | percent     |
| Yes      | series tag     | regents_w_o_advanced_n         | Regents w/o Advanced - n           | text      | text        |
| Yes      | numeric metric | regents_w_o_advanced_of_cohort | Regents w/o Advanced - % of cohort | percent   | percent     |
| Yes      | numeric metric | regents_w_o_advanced_of_grads  | Regents w/o Advanced - % of grads  | percent   | percent     |
| Yes      | series tag     | local_n                        | Local - n                          | text      | text        |
| Yes      | numeric metric | local_of_cohort                | Local - % of cohort                | percent   | percent     |
| Yes      | numeric metric | local_of_grads                 | Local - % of grads                 | percent   | percent     |
| Yes      | series tag     | still_enrolled_n               | Still Enrolled - n                 | text      | text        |
| Yes      | numeric metric | still_enrolled_of_cohort       | Still Enrolled - % of cohort       | percent   | percent     |
| Yes      | series tag     | dropped_out_n                  | Dropped Out - n                    | text      | text        |
| Yes      | numeric metric | dropped_out_of_cohort          | Dropped Out - % of cohort          | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vh2h-md7a d:2005-01-01T00:00:00.000Z t:cohort=2003 t:still_enrolled_n=s t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL" t:dbn=01M292 t:advanced_regents_n=s t:total_regents_n=s t:regents_w_o_advanced_n=s t:local_n=s t:demographic="Total Cohort" t:dropped_out_n=s t:total_grads_n=s m:total_cohort=5

series e:vh2h-md7a d:2005-01-01T00:00:00.000Z t:cohort=2004 t:still_enrolled_n=15 t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL" t:dbn=01M292 t:advanced_regents_n=0 t:total_regents_n=17 t:regents_w_o_advanced_n=17 t:local_n=20 t:demographic="Total Cohort" t:dropped_out_n=3 t:total_grads_n=37 m:advanced_regents_of_grads=0 m:total_cohort=55 m:total_grads_of_cohort=67.3 m:total_regents_of_cohort=30.9 m:still_enrolled_of_cohort=27.3 m:regents_w_o_advanced_of_grads=45.9 m:dropped_out_of_cohort=5.5 m:regents_w_o_advanced_of_cohort=30.9 m:local_of_cohort=36.4 m:advanced_regents_of_cohort=0 m:local_of_grads=54.1 m:total_regents_of_grads=45.9

series e:vh2h-md7a d:2005-01-01T00:00:00.000Z t:cohort=2005 t:still_enrolled_n=9 t:school_name="HENRY STREET SCHOOL FOR INTERNATIONAL" t:dbn=01M292 t:advanced_regents_n=0 t:total_regents_n=27 t:regents_w_o_advanced_n=27 t:local_n=16 t:demographic="Total Cohort" t:dropped_out_n=9 t:total_grads_n=43 m:advanced_regents_of_grads=0 m:total_cohort=64 m:total_grads_of_cohort=67.2 m:total_regents_of_cohort=42.2 m:still_enrolled_of_cohort=14.1 m:regents_w_o_advanced_of_grads=62.8 m:dropped_out_of_cohort=14.1 m:regents_w_o_advanced_of_cohort=42.2 m:local_of_cohort=25 m:advanced_regents_of_cohort=0 m:local_of_grads=37.2 m:total_regents_of_grads=62.8
```

## Meta Commands

```ls
metric m:total_cohort p:integer l:"Total Cohort" t:dataTypeName=number

metric m:total_grads_of_cohort p:double l:"Total Grads - % of cohort" t:dataTypeName=percent

metric m:total_regents_of_cohort p:double l:"Total Regents - % of cohort" t:dataTypeName=percent

metric m:total_regents_of_grads p:double l:"Total Regents - % of grads" t:dataTypeName=percent

metric m:advanced_regents_of_cohort p:double l:"Advanced Regents - % of cohort" t:dataTypeName=percent

metric m:advanced_regents_of_grads p:double l:"Advanced Regents - % of grads" t:dataTypeName=percent

metric m:regents_w_o_advanced_of_cohort p:float l:"Regents w/o Advanced - % of cohort" t:dataTypeName=percent

metric m:regents_w_o_advanced_of_grads p:double l:"Regents w/o Advanced - % of grads" t:dataTypeName=percent

metric m:local_of_cohort p:float l:"Local - % of cohort" t:dataTypeName=percent

metric m:local_of_grads p:double l:"Local - % of grads" t:dataTypeName=percent

metric m:still_enrolled_of_cohort p:double l:"Still Enrolled - % of cohort" t:dataTypeName=percent

metric m:dropped_out_of_cohort p:float l:"Dropped Out - % of cohort" t:dataTypeName=percent

entity e:vh2h-md7a l:"Graduation Outcomes - Classes Of 2005-2010 - School Level" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vh2h-md7a

property e:vh2h-md7a t:meta.view v:id=vh2h-md7a v:category=Education v:averageRating=0 v:name="Graduation Outcomes - Classes Of 2005-2010 - School Level" v:attribution="Department of Education (DOE)"

property e:vh2h-md7a t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vh2h-md7a t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| demographic  | dbn    | school_name                           | cohort   | total_cohort | total_grads_n | total_grads_of_cohort | total_regents_n | total_regents_of_cohort | total_regents_of_grads | advanced_regents_n | advanced_regents_of_cohort | advanced_regents_of_grads | regents_w_o_advanced_n | regents_w_o_advanced_of_cohort | regents_w_o_advanced_of_grads | local_n | local_of_cohort    | local_of_grads     | still_enrolled_n | still_enrolled_of_cohort | dropped_out_n | dropped_out_of_cohort | 
| ============ | ====== | ===================================== | ======== | ============ | ============= | ===================== | =============== | ======================= | ====================== | ================== | ========================== | ========================= | ====================== | ============================== | ============================= | ======= | ================== | ================== | ================ | ======================== | ============= | ===================== | 
| Total Cohort | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL | 2003     | 5            | s             |                       | s               |                         |                        | s                  |                            |                           | s                      |                                |                               | s       |                    |                    | s                |                          | s             |                       | 
| Total Cohort | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL | 2004     | 55           | 37            | 67.3                  | 17              | 30.9                    | 45.9                   | 0                  | 0                          | 0                         | 17                     | 30.9                           | 45.9                          | 20      | 36.4               | 54.1               | 15               | 27.3                     | 3             | 5.5                   | 
| Total Cohort | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL | 2005     | 64           | 43            | 67.2                  | 27              | 42.2                    | 62.8                   | 0                  | 0                          | 0                         | 27                     | 42.2                           | 62.8                          | 16      | 25                 | 37.200000000000003 | 9                | 14.1                     | 9             | 14.1                  | 
| Total Cohort | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL | 2006     | 78           | 43            | 55.1                  | 36              | 46.2                    | 83.7                   | 0                  | 0                          | 0                         | 36                     | 46.2                           | 83.7                          | 7       | 9                  | 16.3               | 16               | 20.5                     | 11            | 14.1                  | 
| Total Cohort | 01M292 | HENRY STREET SCHOOL FOR INTERNATIONAL | 2006 Aug | 78           | 44            | 56.4                  | 37              | 47.4                    | 84.1                   | 0                  | 0                          | 0                         | 37                     | 47.4                           | 84.1                          | 7       | 9                  | 15.9               | 15               | 19.2                     | 11            | 14.1                  | 
| Total Cohort | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL   | 2001     | 64           | 46            | 71.900000000000006    | 32              | 50                      | 69.599999999999994     | 7                  | 10.9                       | 15.2                      | 25                     | 39.1                           | 54.3                          | 14      | 21.9               | 30.4               | 10               | 15.6                     | 6             | 9.4                   | 
| Total Cohort | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL   | 2002     | 52           | 33            | 63.5                  | 19              | 36.5                    | 57.6                   | 8                  | 15.4                       | 24.2                      | 11                     | 21.2                           | 33.299999999999997            | 14      | 26.9               | 42.4               | 16               | 30.8                     | 1             | 1.9                   | 
| Total Cohort | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL   | 2003     | 87           | 67            | 77                    | 39              | 44.8                    | 58.2                   | 11                 | 12.6                       | 16.399999999999999        | 28                     | 32.200000000000003             | 41.8                          | 28      | 32.200000000000003 | 41.8               | 9                | 10.3                     | 11            | 12.6                  | 
| Total Cohort | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL   | 2004     | 112          | 75            | 67                    | 36              | 32.1                    | 48                     | 6                  | 5.4                        | 8                         | 30                     | 26.8                           | 40                            | 39      | 34.799999999999997 | 52                 | 33               | 29.5                     | 4             | 3.6                   | 
| Total Cohort | 01M448 | UNIVERSITY NEIGHBORHOOD HIGH SCHOOL   | 2005     | 121          | 64            | 52.9                  | 35              | 28.9                    | 54.7                   | 4                  | 3.3                        | 6.3                       | 31                     | 25.6                           | 48.4                          | 29      | 24                 | 45.3               | 41               | 33.9                     | 11            | 9.1                   | 
```