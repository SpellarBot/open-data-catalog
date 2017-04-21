# Aid to the Disabled Payments by the Department of Social Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aid-to-the-disabled-payments-by-the-department-of-social-services) |
| Metadata | [Link](https://data.ct.gov/api/views/qrnc-zkrb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qrnc-zkrb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qrnc-zkrb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qrnc-zkrb |
| Name | Aid to the Disabled Payments by the Department of Social Services |
| Attribution | CT Department of Social Services |
| Category | Health and Human Services |
| Tags | aid to the disabled, ad |
| Created | 2014-09-23T17:47:40Z |
| Publication Date | 2015-09-21T13:41:16Z |

## Description

Aid to the Disabled expenditures and caseload

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ======================================= | ============= | ============= |
| No       | time           | :updated_at                           | updated_at                              | meta_data     | meta_data     |
| No       |                | date                                  | Date                                    | calendar_date | calendar_date |
| Yes      | numeric metric | ad_boarding_homes_dds_payments        | AD Boarding Homes - DDS - payments      | money         | money         |
| Yes      | numeric metric | ad_boarding_homes_other_payments      | AD Boarding Homes - Other - payments    | money         | money         |
| Yes      | numeric metric | ad_total_boarding_homes_payments      | AD Total Boarding Homes - payments      | money         | money         |
| Yes      | numeric metric | ad_other_living_arrangements_payments | AD Other Living Arrangements - payments | money         | money         |
| Yes      | numeric metric | ad_total_maintenance_payments         | AD Total Maintenance Payments           | money         | money         |
| Yes      | numeric metric | ad_boarding_homes_dds_cases           | AD Boarding Homes - DDS - cases         | number        | number        |
| Yes      | numeric metric | ad_boarding_homes_other_cases         | AD Boarding Homes - Other - cases       | number        | number        |
| Yes      | numeric metric | ad_total_boarding_homes_cases         | AD Total Boarding Homes - cases         | number        | number        |
| Yes      | numeric metric | ad_other_living_arrangements_cases    | AD Other Living Arrangements - cases    | number        | number        |
| Yes      | numeric metric | ad_total_paid_cases                   | AD Total Paid Cases                     | number        | number        |
| Yes      | numeric metric | ad_boarding_homes_dds_c_c             | AD Boarding Homes - DDS - c/c           | money         | money         |
| Yes      | numeric metric | ad_boarding_homes_other_c_c           | AD Boarding Homes - Other - c/c         | money         | money         |
| Yes      | numeric metric | ad_total_boarding_homes_c_c           | AD Total Boarding Homes - c/c           | money         | money         |
| Yes      | numeric metric | ad_other_living_arrangements_c_c      | AD Other Living Arrangements - c/c      | money         | money         |
| Yes      | numeric metric | ad_overall_cost_per_case              | AD Overall Cost per Case                | money         | money         |
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
series e:qrnc-zkrb d:2015-09-21T06:40:04.000Z m:ad_other_living_arrangements_payments=1289946 m:ad_total_boarding_homes_c_c=858.32 m:ad_boarding_homes_dds_payments=1391307 m:ad_boarding_homes_other_c_c=1242.57 m:ad_boarding_homes_other_payments=1554449 m:ad_total_maintenance_payments=4235703 m:ad_boarding_homes_dds_c_c=637.91 m:ad_total_boarding_homes_payments=2945757 m:ad_overall_cost_per_case=348.22 m:ad_other_living_arrangements_c_c=147.72

series e:qrnc-zkrb d:2015-09-21T06:40:04.000Z m:ad_other_living_arrangements_payments=1259258 m:ad_total_boarding_homes_c_c=1033.33 m:ad_boarding_homes_dds_payments=1524837 m:ad_boarding_homes_other_c_c=1621.49 m:ad_boarding_homes_other_payments=2034974 m:ad_total_maintenance_payments=4819069 m:ad_boarding_homes_dds_c_c=696.27 m:ad_total_boarding_homes_payments=3559811 m:ad_overall_cost_per_case=396.04 m:ad_other_living_arrangements_c_c=144.36

series e:qrnc-zkrb d:2015-09-21T06:40:04.000Z m:ad_other_living_arrangements_payments=1271547 m:ad_total_boarding_homes_c_c=1020.82 m:ad_boarding_homes_dds_payments=1535724 m:ad_boarding_homes_other_c_c=1583.05 m:ad_boarding_homes_other_payments=1999392 m:ad_total_maintenance_payments=4806663 m:ad_boarding_homes_dds_c_c=698.06 m:ad_total_boarding_homes_payments=3535116 m:ad_overall_cost_per_case=396.98 m:ad_other_living_arrangements_c_c=147.08
```

## Meta Commands

```ls
metric m:ad_boarding_homes_dds_payments p:integer l:"AD Boarding Homes - DDS - payments" t:dataTypeName=money

metric m:ad_boarding_homes_other_payments p:integer l:"AD Boarding Homes - Other - payments" t:dataTypeName=money

metric m:ad_total_boarding_homes_payments p:integer l:"AD Total Boarding Homes - payments" t:dataTypeName=money

metric m:ad_other_living_arrangements_payments p:integer l:"AD Other Living Arrangements - payments" t:dataTypeName=money

metric m:ad_total_maintenance_payments p:integer l:"AD Total Maintenance Payments" t:dataTypeName=money

metric m:ad_boarding_homes_dds_cases p:long l:"AD Boarding Homes - DDS - cases" t:dataTypeName=number

metric m:ad_boarding_homes_other_cases p:long l:"AD Boarding Homes - Other - cases" t:dataTypeName=number

metric m:ad_total_boarding_homes_cases p:long l:"AD Total Boarding Homes - cases" t:dataTypeName=number

metric m:ad_other_living_arrangements_cases p:long l:"AD Other Living Arrangements - cases" t:dataTypeName=number

metric m:ad_total_paid_cases p:long l:"AD Total Paid Cases" t:dataTypeName=number

metric m:ad_boarding_homes_dds_c_c p:double l:"AD Boarding Homes - DDS - c/c" t:dataTypeName=money

metric m:ad_boarding_homes_other_c_c p:double l:"AD Boarding Homes - Other - c/c" t:dataTypeName=money

metric m:ad_total_boarding_homes_c_c p:double l:"AD Total Boarding Homes - c/c" t:dataTypeName=money

metric m:ad_other_living_arrangements_c_c p:double l:"AD Other Living Arrangements - c/c" t:dataTypeName=money

metric m:ad_overall_cost_per_case p:double l:"AD Overall Cost per Case" t:dataTypeName=money

entity e:qrnc-zkrb l:"Aid to the Disabled Payments by the Department of Social Services" t:attribution="CT Department of Social Services" t:url=https://data.ct.gov/api/views/qrnc-zkrb

property e:qrnc-zkrb t:meta.view v:id=qrnc-zkrb v:category="Health and Human Services" v:averageRating=0 v:name="Aid to the Disabled Payments by the Department of Social Services" v:attribution="CT Department of Social Services"

property e:qrnc-zkrb t:meta.view.license v:name="Public Domain"

property e:qrnc-zkrb t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:qrnc-zkrb t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| :updated_at | date | ad_boarding_homes_dds_payments | ad_boarding_homes_other_payments | ad_total_boarding_homes_payments | ad_other_living_arrangements_payments | ad_total_maintenance_payments | ad_boarding_homes_dds_cases | ad_boarding_homes_other_cases | ad_total_boarding_homes_cases | ad_other_living_arrangements_cases | ad_total_paid_cases | ad_boarding_homes_dds_c_c | ad_boarding_homes_other_c_c | ad_total_boarding_homes_c_c | ad_other_living_arrangements_c_c | ad_overall_cost_per_case | 
| =========== | ==== | ============================== | ================================ | ================================ | ===================================== | ============================= | =========================== | ============================= | ============================= | ================================== | =================== | ========================= | =========================== | =========================== | ================================ | ======================== | 
| 1442817604  |      | 1391307                        | 1554449                          | 2945757                          | 1289946                               | 4235703                       |                             |                               |                               |                                    |                     | 637.91                    | 1242.57                     | 858.32                      | 147.72                           | 348.22                   | 
| 1442817604  |      | 1524837                        | 2034974                          | 3559811                          | 1259258                               | 4819069                       |                             |                               |                               |                                    |                     | 696.27                    | 1621.49                     | 1033.33                     | 144.36                           | 396.04                   | 
| 1442817604  |      | 1535724                        | 1999392                          | 3535116                          | 1271547                               | 4806663                       |                             |                               |                               |                                    |                     | 698.06                    | 1583.05                     | 1020.82                     | 147.08                           | 396.98                   | 
| 1442817604  |      | 1411773                        | 1892808                          | 3304581                          | 1271316                               | 4575897                       |                             |                               |                               |                                    |                     | 642.88                    | 1479.91                     | 950.96                      | 147.78                           | 378.86                   | 
| 1442817604  |      | 1618869                        | 1842030                          | 3460899                          | 1255691                               | 4716590                       |                             |                               |                               |                                    |                     | 740.9                     | 1429.04                     | 996.23                      | 147.36                           | 393.21                   | 
| 1442817604  |      | 1345165                        | 1887814                          | 3232979                          | 1197469                               | 4430447                       |                             |                               |                               |                                    |                     | 613.11                    | 1432.33                     | 920.55                      | 143.03                           | 372.81                   | 
| 1442817604  |      | 1398118                        | 1974601                          | 3372719                          | 1075100                               | 4447820                       |                             |                               |                               |                                    |                     | 649.99                    | 1531.89                     | 980.44                      | 131.80                           | 383.53                   | 
| 1442817604  |      | 1330579                        | 1889884                          | 3220463                          | 1177135                               | 4397598                       |                             |                               |                               |                                    |                     | 610.91                    | 1433.9                      | 921.19                      | 144.03                           | 376.86                   | 
| 1442817604  |      | 1368714                        | 1931215                          | 3299929                          | 1113332                               | 4413261                       |                             |                               |                               |                                    |                     | 639.59                    | 1480.99                     | 958.17                      | 138.84                           | 385                      | 
| 1442817604  |      | 1398938                        | 1998661                          | 3397599                          | 1293772                               | 4691371                       |                             |                               |                               |                                    |                     | 646.16                    | 1519.89                     | 976.32                      | 161.62                           | 408.48                   | 
```