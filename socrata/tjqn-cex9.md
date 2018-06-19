# Choose Maryland: Compare States - Business Support

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-business-support) |
| Metadata | [Link](https://data.maryland.gov/api/views/tjqn-cex9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/tjqn-cex9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/tjqn-cex9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | tjqn-cex9 |
| Name | Choose Maryland: Compare States - Business Support |
| Attribution | Maryland Department of Commerce |
| Category | Business and Economy |
| Tags | federal, contracts, grants |
| Created | 2014-11-10T15:02:42Z |
| Publication Date | 2016-07-20T16:55:21Z |

## Description

Federal and DOD contracts and grants to states - total and per capita.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                        | Data Type | Render Type |
| ======== | ============== | ================================================== | =========================================================== | ========= | =========== |
| No       | time           | :updated_at                                        | updated_at                                                  | meta_data | meta_data   |
| Yes      | numeric metric | federal_government_expenditures_total_millions     | Federal Grants to State Governments, Total ($ Millions)     | money     | money       |
| Yes      | numeric metric | federal_government_expenditures_per_capita_dollars | Federal Grants to State Governments, per Capita ($ Dollars) | money     | money       |
| Yes      | numeric metric | federal_government_procurement_total_millions      | Federal Contracts, Total ($ Millions)                       | money     | money       |
| Yes      | numeric metric | federal_government_procurement_per_capita_dollars  | Federal Contracts, per Capita ($ Dollars)                   | money     | money       |
| Yes      | series tag     | defense_department_expenditures_total_millions     | Department of Defense Contracts, Total ($ Millions)         | text      | money       |
| Yes      | series tag     | defense_department_expenditures_per_capita_dollars | Department of Defense Contracts, per Capita ($ Dollars)     | text      | money       |
| Yes      | series tag     | state                                              | State                                                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tjqn-cex9 d:2016-07-20T09:54:11.000Z t:state=Alabama t:defense_department_expenditures_per_capita_dollars=1822 t:defense_department_expenditures_total_millions=8837.65 m:federal_government_procurement_total_millions=10564.19 m:federal_government_procurement_per_capita_dollars=2178 m:federal_government_expenditures_total_millions=8005.06 m:federal_government_expenditures_per_capita_dollars=1651

series e:tjqn-cex9 d:2016-07-20T09:54:11.000Z t:state=Alaska t:defense_department_expenditures_per_capita_dollars=2044 t:defense_department_expenditures_total_millions=1505.67 m:federal_government_procurement_total_millions=1922.53 m:federal_government_procurement_per_capita_dollars=2610 m:federal_government_expenditures_total_millions=2803.12 m:federal_government_expenditures_per_capita_dollars=3805

series e:tjqn-cex9 d:2016-07-20T09:54:11.000Z t:state=Arizona t:defense_department_expenditures_per_capita_dollars=1277 t:defense_department_expenditures_total_millions=8599.15 m:federal_government_procurement_total_millions=9956.53 m:federal_government_procurement_per_capita_dollars=1479 m:federal_government_expenditures_total_millions=10549.1 m:federal_government_expenditures_per_capita_dollars=1567
```

## Meta Commands

```ls
metric m:federal_government_expenditures_total_millions p:double l:"Federal Grants to State Governments, Total ($ Millions)" t:dataTypeName=money

metric m:federal_government_expenditures_per_capita_dollars p:integer l:"Federal Grants to State Governments, per Capita ($ Dollars)" t:dataTypeName=money

metric m:federal_government_procurement_total_millions p:double l:"Federal Contracts, Total ($ Millions)" t:dataTypeName=money

metric m:federal_government_procurement_per_capita_dollars p:integer l:"Federal Contracts, per Capita ($ Dollars)" t:dataTypeName=money

entity e:tjqn-cex9 l:"Choose Maryland:  Compare States - Business Support" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/tjqn-cex9

property e:tjqn-cex9 t:meta.view v:id=tjqn-cex9 v:category="Business and Economy" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Business Support" v:attribution="Maryland Department of Commerce"

property e:tjqn-cex9 t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:tjqn-cex9 t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | federal_government_expenditures_total_millions | federal_government_expenditures_per_capita_dollars | federal_government_procurement_total_millions | federal_government_procurement_per_capita_dollars | defense_department_expenditures_total_millions | defense_department_expenditures_per_capita_dollars | state       | 
| =========== | ============================================== | ================================================== | ============================================= | ================================================= | ============================================== | ================================================== | =========== | 
| 1469008451  | 8005.06                                        | 1651                                               | 10564.19                                      | 2178                                              | 8837.65                                        | 1822                                               | Alabama     | 
| 1469008451  | 2803.12                                        | 3805                                               | 1922.53                                       | 2610                                              | 1505.67                                        | 2044                                               | Alaska      | 
| 1469008451  | 10549.10                                       | 1567                                               | 9956.53                                       | 1479                                              | 8599.15                                        | 1277                                               | Arizona     | 
| 1469008451  | 6055.47                                        | 2041                                               | 1153.38                                       | 389                                               | 602.71                                         | 203                                                | Arkansas    | 
| 1469008451  | 59925.65                                       | 1544                                               | 46063.55                                      | 1187                                              | 30897.54                                       | 796                                                | California  | 
| 1469008451  | 7187.57                                        | 1342                                               | 9832.31                                       | 1836                                              | 5789.83                                        | 1081                                               | Colorado    | 
| 1469008451  | 6349.94                                        | 1766                                               | 13694.94                                      | 3808                                              | 13207.71                                       | 3672                                               | Connecticut | 
| 1469008451  | 2031.22                                        | 2171                                               | 514.69                                        | 550                                               | 405.16                                         | 433                                                | Delaware    | 
| 1469008451  | 25468.80                                       | 1280                                               | 13574.13                                      | 682                                               | 9777.12                                        | 491                                                | Florida     | 
| 1469008451  | 14327.48                                       | 1419                                               | 8749.01                                       | 866                                               | 6302.14                                        | 624                                                | Georgia     | 
```