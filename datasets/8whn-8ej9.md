# Aid to the Blind Payments by the Department of Social Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aid-to-the-blind-payments-by-the-department-of-social-services) |
| Metadata | [Link](https://data.ct.gov/api/views/8whn-8ej9) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8whn-8ej9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8whn-8ej9/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8whn-8ej9 |
| Name | Aid to the Blind Payments by the Department of Social Services |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | aid to the blind, ab |
| Created | 2014-09-23T17:31:04Z |
| Publication Date | 2015-09-21T13:44:04Z |

## Description

CT Aid to the Blind

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ===================================== | ============= | ============= |
| No       | time           | :updated_at                           | updated_at                            | meta_data     | meta_data     |
| No       |                | date                                  | Date                                  | calendar_date | calendar_date |
| Yes      | numeric metric | ab_boarding_homes_dds_payments        | AB Boarding Homes - DDS Payments      | money         | money         |
| Yes      | numeric metric | ab_boarding_homes_other_payments      | AB Boarding Homes - Other Payments    | money         | money         |
| Yes      | numeric metric | ab_total_boarding_homes_payments      | AB Total Boarding Homes - Payments    | money         | money         |
| Yes      | numeric metric | ab_other_living_arrangements_payments | AB Other Living Arrangements Payments | money         | money         |
| Yes      | numeric metric | ab_total_maintenance_payments         | AB Total Maintenance Payments         | money         | money         |
| Yes      | numeric metric | ab_boarding_homes_dds_cases           | AB Boarding Homes - DDS - cases       | number        | number        |
| Yes      | numeric metric | ab_boarding_homes_other_cases         | AB Boarding Homes - Other - cases     | number        | number        |
| Yes      | numeric metric | ab_total_boarding_homes_cases         | AB Total Boarding Homes - cases       | number        | number        |
| Yes      | numeric metric | ab_other_living_arrangements_cases    | AB Other Living Arrangements - cases  | number        | number        |
| Yes      | numeric metric | ab_total_paid_cases                   | AB Total Paid Cases                   | number        | number        |
| Yes      | numeric metric | ab_boarding_homes_dds_c_c             | AB Boarding Homes - DDS - c/c         | money         | money         |
| Yes      | numeric metric | ab_boarding_homes_other_c_c           | AB Boarding Homes - Other - c/c       | money         | money         |
| Yes      | numeric metric | ab_total_boarding_homes_c_c           | AB Total Boarding Homes - c/c         | money         | money         |
| Yes      | numeric metric | ab_other_living_arrangements_c_c      | AB Other Living Arrangements - c/c    | money         | money         |
| Yes      | numeric metric | ab_overall_cost_per_case              | AB Overall Cost per Case              | money         | money         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:8whn-8ej9 d:2015-09-21T06:43:13.000Z m:ab_boarding_homes_dds_c_c=646.98 m:ab_boarding_homes_other_c_c=895.42 m:ab_total_boarding_homes_c_c=676.21 m:ab_total_boarding_homes_payments=34487 m:ab_boarding_homes_dds_payments=29114 m:ab_total_maintenance_payments=39471 m:ab_boarding_homes_other_payments=5373 m:ab_other_living_arrangements_c_c=124.6 m:ab_other_living_arrangements_payments=4984 m:ab_overall_cost_per_case=433.74

series e:8whn-8ej9 d:2015-09-21T06:43:13.000Z m:ab_boarding_homes_dds_c_c=670.83 m:ab_boarding_homes_other_c_c=1522.27 m:ab_total_boarding_homes_c_c=769.08 m:ab_total_boarding_homes_payments=39992 m:ab_boarding_homes_dds_payments=30858 m:ab_total_maintenance_payments=45328 m:ab_boarding_homes_other_payments=9134 m:ab_other_living_arrangements_c_c=133.4 m:ab_other_living_arrangements_payments=5336 m:ab_overall_cost_per_case=492.69

series e:8whn-8ej9 d:2015-09-21T06:43:13.000Z m:ab_boarding_homes_dds_c_c=818.4 m:ab_boarding_homes_other_c_c=2260.41 m:ab_total_boarding_homes_c_c=981.65 m:ab_total_boarding_homes_payments=52027 m:ab_boarding_homes_dds_payments=38465 m:ab_total_maintenance_payments=60285 m:ab_boarding_homes_other_payments=13562 m:ab_other_living_arrangements_c_c=204.4 m:ab_other_living_arrangements_payments=8257 m:ab_overall_cost_per_case=641.33
```

## Meta Commands

```ls
metric m:ab_boarding_homes_dds_payments p:integer l:"AB Boarding Homes - DDS Payments" t:dataTypeName=money

metric m:ab_boarding_homes_other_payments p:integer l:"AB Boarding Homes - Other Payments" t:dataTypeName=money

metric m:ab_total_boarding_homes_payments p:integer l:"AB Total Boarding Homes - Payments" t:dataTypeName=money

metric m:ab_other_living_arrangements_payments p:integer l:"AB Other Living Arrangements Payments" t:dataTypeName=money

metric m:ab_total_maintenance_payments p:integer l:"AB Total Maintenance Payments" t:dataTypeName=money

metric m:ab_boarding_homes_dds_cases p:long l:"AB Boarding Homes - DDS - cases" t:dataTypeName=number

metric m:ab_boarding_homes_other_cases p:long l:"AB Boarding Homes - Other - cases" t:dataTypeName=number

metric m:ab_total_boarding_homes_cases p:long l:"AB Total Boarding Homes - cases" t:dataTypeName=number

metric m:ab_other_living_arrangements_cases p:long l:"AB Other Living Arrangements - cases" t:dataTypeName=number

metric m:ab_total_paid_cases p:long l:"AB Total Paid Cases" t:dataTypeName=number

metric m:ab_boarding_homes_dds_c_c p:double l:"AB Boarding Homes - DDS - c/c" t:dataTypeName=money

metric m:ab_boarding_homes_other_c_c p:double l:"AB Boarding Homes - Other - c/c" t:dataTypeName=money

metric m:ab_total_boarding_homes_c_c p:double l:"AB Total Boarding Homes - c/c" t:dataTypeName=money

metric m:ab_other_living_arrangements_c_c p:double l:"AB Other Living Arrangements - c/c" t:dataTypeName=money

metric m:ab_overall_cost_per_case p:double l:"AB Overall Cost per Case" t:dataTypeName=money

entity e:8whn-8ej9 l:"Aid to the Blind Payments by the Department of Social Services" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/8whn-8ej9

property e:8whn-8ej9 t:meta.view v:id=8whn-8ej9 v:category="Health and Human Services" v:averageRating=0 v:name="Aid to the Blind Payments by the Department of Social Services" v:attribution="CT Department of Social Services"

property e:8whn-8ej9 t:meta.view.license v:name="Public Domain"

property e:8whn-8ej9 t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:8whn-8ej9 t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| :updated_at | date | ab_boarding_homes_dds_payments | ab_boarding_homes_other_payments | ab_total_boarding_homes_payments | ab_other_living_arrangements_payments | ab_total_maintenance_payments | ab_boarding_homes_dds_cases | ab_boarding_homes_other_cases | ab_total_boarding_homes_cases | ab_other_living_arrangements_cases | ab_total_paid_cases | ab_boarding_homes_dds_c_c | ab_boarding_homes_other_c_c | ab_total_boarding_homes_c_c | ab_other_living_arrangements_c_c | ab_overall_cost_per_case | 
| =========== | ==== | ============================== | ================================ | ================================ | ===================================== | ============================= | =========================== | ============================= | ============================= | ================================== | =================== | ========================= | =========================== | =========================== | ================================ | ======================== | 
| 1442817793  |      | 29114                          | 5373                             | 34487                            | 4984                                  | 39471                         |                             |                               |                               |                                    |                     | 646.98                    | 895.42                      | 676.21                      | 124.6                            | 433.74                   | 
| 1442817793  |      | 30858                          | 9134                             | 39992                            | 5336                                  | 45328                         |                             |                               |                               |                                    |                     | 670.83                    | 1522.27                     | 769.08                      | 133.4                            | 492.69                   | 
| 1442817793  |      | 38465                          | 13562                            | 52027                            | 8257                                  | 60285                         |                             |                               |                               |                                    |                     | 818.4                     | 2260.41                     | 981.65                      | 204.4                            | 641.33                   | 
| 1442817793  |      | 30321                          | 11080                            | 41401                            | 9955                                  | 51356                         |                             |                               |                               |                                    |                     | 673.81                    | 1846.64                     | 811.79                      | 237.02                           | 552.22                   | 
| 1442817793  |      | 33273                          | 12441                            | 45714                            | 5965                                  | 51679                         |                             |                               |                               |                                    |                     | 707.94                    | 2073.5                      | 862.53                      | 152.94                           | 561.73                   | 
| 1442817793  |      | 33651                          | 12264                            | 45916                            | 5179                                  | 51094                         |                             |                               |                               |                                    |                     | 715.99                    | 2044.03                     | 866.33                      | 136.29                           | 561.48                   | 
| 1442817793  |      | 37007                          | 13540                            | 50547                            | 4926                                  | 55473                         |                             |                               |                               |                                    |                     | 740.14                    | 2708.08                     | 919.04                      | 126.31                           | 590.14                   | 
| 1442817793  |      | 32597                          | 12352                            | 44949                            | 5701                                  | 50650                         |                             |                               |                               |                                    |                     | 679.11                    | 2058.63                     | 832.39                      | 135.74                           | 527.6                    | 
| 1442817793  |      | 23970                          | 9032                             | 33002                            | 12340                                 | 45342                         |                             |                               |                               |                                    |                     | 489.18                    | 1505.36                     | 600.04                      | 293.81                           | 467.44                   | 
| 1442817793  |      | 33096                          | 12476                            | 45571                            | 4969                                  | 50540                         |                             |                               |                               |                                    |                     | 675.42                    | 2495.11                     | 843.91                      | 115.56                           | 521.03                   | 
```