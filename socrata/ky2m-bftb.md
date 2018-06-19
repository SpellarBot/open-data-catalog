# Old Age Assistance Payments by the Department of Social Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/old-age-assistance-payments-by-the-department-of-social-services) |
| Metadata | [Link](https://data.ct.gov/api/views/ky2m-bftb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ky2m-bftb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ky2m-bftb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ky2m-bftb |
| Name | Old Age Assistance Payments by the Department of Social Services |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | oaa |
| Created | 2014-09-23T17:02:50Z |
| Publication Date | 2015-09-21T13:53:51Z |

## Description

CT Old Age Assistance

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ====================================== | ======================================== | ============= | ============= |
| No       | time           | :updated_at                            | updated_at                               | meta_data     | meta_data     |
| No       |                | date                                   | Date                                     | calendar_date | calendar_date |
| Yes      | numeric metric | oaa_boarding_homes_dds_payments        | OAA Boarding Homes - DDS - payments      | money         | money         |
| Yes      | numeric metric | oaa_boarding_homes_other_payments      | OAA Boarding Homes - Other - payments    | money         | money         |
| Yes      | numeric metric | oaa_total_boarding_homes_payments      | OAA Total Boarding Homes - payments      | money         | money         |
| Yes      | numeric metric | oaa_other_living_arrangements_payments | OAA Other Living Arrangements - payments | money         | money         |
| Yes      | numeric metric | oaa_total_maintenance_payments         | OAA Total Maintenance Payments           | money         | money         |
| Yes      | numeric metric | oaa_boarding_homes_dds_cases           | OAA Boarding Homes - DDS - cases         | number        | number        |
| Yes      | numeric metric | oaa_boarding_homes_other_cases         | OAA Boarding Homes - Other - cases       | number        | number        |
| Yes      | numeric metric | oaa_total_boarding_homes_cases         | OAA Total Boarding Homes - cases         | number        | number        |
| Yes      | numeric metric | oaa_other_living_arrangements_cases    | OAA Other Living Arrangements - cases    | number        | number        |
| Yes      | numeric metric | oaa_total_paid_cases                   | OAA Total Paid Cases                     | number        | number        |
| Yes      | numeric metric | oaa_boarding_homes_dds_c_c             | OAA Boarding Homes - DDS - c/c           | money         | money         |
| Yes      | numeric metric | oaa_boarding_homes_other_c_c           | OAA Boarding Homes - Other c/c           | money         | money         |
| Yes      | numeric metric | oaa_total_boarding_homes_c_c           | OAA Total Boarding Homes c/c             | money         | money         |
| Yes      | numeric metric | oaa_other_living_arrangements_c_c      | OAA Other Living Arrangements c/c        | money         | money         |
| Yes      | numeric metric | oaa_overall_cost_per_case_c_c          | OAA Overall Cost per Case c/c            | money         | money         |
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
series e:ky2m-bftb d:2015-09-21T06:53:01.000Z m:oaa_total_maintenance_payments=2343445 m:oaa_overall_cost_per_case_c_c=439.09 m:oaa_boarding_homes_dds_c_c=677.06 m:oaa_other_living_arrangements_c_c=136.87 m:oaa_boarding_homes_dds_payments=178067 m:oaa_other_living_arrangements_payments=563103 m:oaa_boarding_homes_other_c_c=1669.04 m:oaa_total_boarding_homes_payments=1780342 m:oaa_boarding_homes_other_payments=1602275 m:oaa_total_boarding_homes_c_c=1455.72

series e:ky2m-bftb d:2015-09-21T06:53:01.000Z m:oaa_total_maintenance_payments=2596350 m:oaa_overall_cost_per_case_c_c=489.88 m:oaa_boarding_homes_dds_c_c=697.95 m:oaa_other_living_arrangements_c_c=131.78 m:oaa_boarding_homes_dds_payments=201011 m:oaa_other_living_arrangements_payments=524485 m:oaa_boarding_homes_other_c_c=1812.84 m:oaa_total_boarding_homes_payments=2071865 m:oaa_boarding_homes_other_payments=1870854 m:oaa_total_boarding_homes_c_c=1569.59

series e:ky2m-bftb d:2015-09-21T06:53:01.000Z m:oaa_total_maintenance_payments=2844713 m:oaa_overall_cost_per_case_c_c=533.12 m:oaa_boarding_homes_dds_c_c=790.75 m:oaa_other_living_arrangements_c_c=134.47 m:oaa_boarding_homes_dds_payments=230108 m:oaa_other_living_arrangements_payments=538705 m:oaa_boarding_homes_other_c_c=1997.98 m:oaa_total_boarding_homes_payments=2306008 m:oaa_boarding_homes_other_payments=2075900 m:oaa_total_boarding_homes_c_c=1733.84
```

## Meta Commands

```ls
metric m:oaa_boarding_homes_dds_payments p:integer l:"OAA Boarding Homes - DDS - payments" t:dataTypeName=money

metric m:oaa_boarding_homes_other_payments p:integer l:"OAA Boarding Homes - Other - payments" t:dataTypeName=money

metric m:oaa_total_boarding_homes_payments p:integer l:"OAA Total Boarding Homes - payments" t:dataTypeName=money

metric m:oaa_other_living_arrangements_payments p:integer l:"OAA Other Living Arrangements - payments" t:dataTypeName=money

metric m:oaa_total_maintenance_payments p:integer l:"OAA Total Maintenance Payments" t:dataTypeName=money

metric m:oaa_boarding_homes_dds_cases p:long l:"OAA Boarding Homes - DDS - cases" t:dataTypeName=number

metric m:oaa_boarding_homes_other_cases p:long l:"OAA Boarding Homes - Other - cases" t:dataTypeName=number

metric m:oaa_total_boarding_homes_cases p:long l:"OAA Total Boarding Homes - cases" t:dataTypeName=number

metric m:oaa_other_living_arrangements_cases p:long l:"OAA Other Living Arrangements - cases" t:dataTypeName=number

metric m:oaa_total_paid_cases p:long l:"OAA Total Paid Cases" t:dataTypeName=number

metric m:oaa_boarding_homes_dds_c_c p:double l:"OAA Boarding Homes - DDS - c/c" t:dataTypeName=money

metric m:oaa_boarding_homes_other_c_c p:double l:"OAA Boarding Homes - Other c/c" t:dataTypeName=money

metric m:oaa_total_boarding_homes_c_c p:double l:"OAA Total Boarding Homes c/c" t:dataTypeName=money

metric m:oaa_other_living_arrangements_c_c p:double l:"OAA Other Living Arrangements c/c" t:dataTypeName=money

metric m:oaa_overall_cost_per_case_c_c p:double l:"OAA Overall Cost per Case c/c" t:dataTypeName=money

entity e:ky2m-bftb l:"Old Age Assistance Payments by the Department of Social Services" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/ky2m-bftb

property e:ky2m-bftb t:meta.view v:id=ky2m-bftb v:category="Health and Human Services" v:averageRating=0 v:name="Old Age Assistance Payments by the Department of Social Services" v:attribution="CT Department of Social Services"

property e:ky2m-bftb t:meta.view.license v:name="Public Domain"

property e:ky2m-bftb t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:ky2m-bftb t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| :updated_at | date | oaa_boarding_homes_dds_payments | oaa_boarding_homes_other_payments | oaa_total_boarding_homes_payments | oaa_other_living_arrangements_payments | oaa_total_maintenance_payments | oaa_boarding_homes_dds_cases | oaa_boarding_homes_other_cases | oaa_total_boarding_homes_cases | oaa_other_living_arrangements_cases | oaa_total_paid_cases | oaa_boarding_homes_dds_c_c | oaa_boarding_homes_other_c_c | oaa_total_boarding_homes_c_c | oaa_other_living_arrangements_c_c | oaa_overall_cost_per_case_c_c | 
| =========== | ==== | =============================== | ================================= | ================================= | ====================================== | ============================== | ============================ | ============================== | ============================== | =================================== | ==================== | ========================== | ============================ | ============================ | ================================= | ============================= | 
| 1442818381  |      | 178067                          | 1602275                           | 1780342                           | 563103                                 | 2343445                        |                              |                                |                                |                                     |                      | 677.06                     | 1669.04                      | 1455.72                      | 136.87                            | 439.09                        | 
| 1442818381  |      | 201011                          | 1870854                           | 2071865                           | 524485                                 | 2596350                        |                              |                                |                                |                                     |                      | 697.95                     | 1812.84                      | 1569.59                      | 131.78                            | 489.88                        | 
| 1442818381  |      | 230108                          | 2075900                           | 2306008                           | 538705                                 | 2844713                        |                              |                                |                                |                                     |                      | 790.75                     | 1997.98                      | 1733.84                      | 134.47                            | 533.12                        | 
| 1442818381  |      | 184261                          | 1638649                           | 1822910                           | 544757                                 | 2367667                        |                              |                                |                                |                                     |                      | 626.74                     | 1581.71                      | 1370.61                      | 138.47                            | 449.78                        | 
| 1442818381  |      | 206356                          | 1796192                           | 2002548                           | 525364                                 | 2527911                        |                              |                                |                                |                                     |                      | 697.15                     | 1740.5                       | 1507.94                      | 133.31                            | 479.77                        | 
| 1442818381  |      | 191574                          | 1713613                           | 1905187                           | 507464                                 | 2412651                        |                              |                                |                                |                                     |                      | 640.72                     | 1641.39                      | 1418.61                      | 131.09                            | 462.73                        | 
| 1442818381  |      | 189540                          | 1742023                           | 1931563                           | 552901                                 | 2484464                        |                              |                                |                                |                                     |                      | 642.51                     | 1670.2                       | 1443.62                      | 145.81                            | 484.3                         | 
| 1442818381  |      | 175140                          | 1580631                           | 1755771                           | 509110                                 | 2264881                        |                              |                                |                                |                                     |                      | 599.79                     | 1540.58                      | 1332.15                      | 136.93                            | 449.74                        | 
| 1442818381  |      | 190277                          | 1705693                           | 1895970                           | 484979                                 | 2380949                        |                              |                                |                                |                                     |                      | 645.01                     | 1641.67                      | 1421.27                      | 128.88                            | 467.13                        | 
| 1442818381  |      | 196685                          | 1755710                           | 1952395                           | 492324                                 | 2444719                        |                              |                                |                                |                                     |                      | 673.58                     | 1717.92                      | 1485.84                      | 133.49                            | 488.75                        | 
```