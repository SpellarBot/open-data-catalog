# General City Budget Incremental Changes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-city-budget-incremental-changes) |
| Metadata | [Link](https://data.lacity.org/api/views/k4k6-bwwv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/k4k6-bwwv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/k4k6-bwwv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | k4k6-bwwv |
| Name | General City Budget Incremental Changes |
| Category | A Prosperous City |
| Tags | budget, expenditures, appropriations |
| Created | 2016-07-08T20:48:21Z |
| Publication Date | 2016-07-11T16:48:24Z |

## Description

Changes made from the Fiscal Year 2015-2016 budget to the current budget, FY2016-2017, based on requests from departments.

## Columns

```ls
| Included | Schema Type    | Field Name                                                      | Name                                                            | Data Type | Render Type |
| ======== | ============== | =============================================================== | =============================================================== | ========= | =========== |
| No       | time           | :updated_at                                                     | updated_at                                                      | meta_data | meta_data   |
| Yes      | series tag     | department_code                                                 | Department Code                                                 | text      | number      |
| Yes      | series tag     | department_name                                                 | Department Name                                                 | text      | text        |
| Yes      | series tag     | subdept_code                                                    | SubDept Code                                                    | text      | text        |
| Yes      | series tag     | subdepartment_name                                              | SubDepartment Name                                              | text      | text        |
| Yes      | series tag     | program_code                                                    | Program Code                                                    | text      | number      |
| Yes      | series tag     | program_name                                                    | Program Name                                                    | text      | text        |
| Yes      | series tag     | fund_code                                                       | Fund Code                                                       | text      | number      |
| Yes      | series tag     | fund_name                                                       | Fund Name                                                       | text      | text        |
| Yes      | series tag     | source_fund_code                                                | Source Fund Code                                                | text      | text        |
| Yes      | series tag     | source_fund_name                                                | Source Fund Name                                                | text      | text        |
| Yes      | series tag     | budget_request_description                                      | Budget Request Description                                      | text      | text        |
| Yes      | series tag     | budget_request_category                                         | Budget Request Category                                         | text      | text        |
| Yes      | series tag     | account_code                                                    | Account Code                                                    | text      | number      |
| Yes      | series tag     | account_name                                                    | Account Name                                                    | text      | text        |
| Yes      | series tag     | one_time_01_on_going_bb                                         | One Time (01) / On-going (BB)                                   | text      | text        |
| Yes      | numeric metric | 2016_17_proposed_budget_incremental_change_from_2015_16_adopted | 2016-17 Proposed Budget INCREMENTAL CHANGE FROM 2015-16 Adopted | money     | money       |
| Yes      | numeric metric | 2016_17_adopted_budget_incremental_change_from_2015_16_adopted  | 2016-17 Adopted Budget INCREMENTAL CHANGE FROM 2015-16 Adopted  | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k4k6-bwwv d:2016-07-08T13:48:27.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:one_time_01_on_going_bb=BB t:subdept_code=02LVL5 t:source_fund_code=100 t:program_name="Senior Services" t:account_code=1010 t:subdepartment_name=Aging t:budget_request_category="1-Obligatory Changes" t:department_code=2 t:department_name=Aging t:budget_request_description="2015-16 Employee Compensation Adjustment" t:source_fund_name="General Fund" t:account_name="Salaries General" m:2016_17_adopted_budget_incremental_change_from_2015_16_adopted=2842 m:2016_17_proposed_budget_incremental_change_from_2015_16_adopted=2842

series e:k4k6-bwwv d:2016-07-08T13:48:27.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:one_time_01_on_going_bb=BB t:subdept_code=02LVL5 t:source_fund_code=385 t:program_name="Senior Services" t:account_code=1010 t:subdepartment_name=Aging t:budget_request_category="1-Obligatory Changes" t:department_code=2 t:department_name=Aging t:budget_request_description="2015-16 Employee Compensation Adjustment" t:source_fund_name="Proposition A Local Transit Assistance Fund (Sch. 26)" t:account_name="Salaries General" m:2016_17_adopted_budget_incremental_change_from_2015_16_adopted=2471 m:2016_17_proposed_budget_incremental_change_from_2015_16_adopted=2471

series e:k4k6-bwwv d:2016-07-08T13:48:27.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:one_time_01_on_going_bb=BB t:subdept_code=02LVL5 t:source_fund_code=395 t:program_name="Senior Services" t:account_code=1010 t:subdepartment_name=Aging t:budget_request_category="1-Obligatory Changes" t:department_code=2 t:department_name=Aging t:budget_request_description="2015-16 Employee Compensation Adjustment" t:source_fund_name="Area Plan for the Aging Title 7 Fund (Sch. 21)" t:account_name="Salaries General" m:2016_17_adopted_budget_incremental_change_from_2015_16_adopted=11028 m:2016_17_proposed_budget_incremental_change_from_2015_16_adopted=11028
```

## Meta Commands

```ls
metric m:2016_17_proposed_budget_incremental_change_from_2015_16_adopted p:integer l:"2016-17 Proposed Budget INCREMENTAL CHANGE FROM 2015-16 Adopted" t:dataTypeName=money

metric m:2016_17_adopted_budget_incremental_change_from_2015_16_adopted p:integer l:"2016-17 Adopted Budget INCREMENTAL CHANGE FROM 2015-16 Adopted" t:dataTypeName=money

entity e:k4k6-bwwv l:"General City Budget Incremental Changes" t:url=https://data.lacity.org/api/views/k4k6-bwwv

property e:k4k6-bwwv t:meta.view v:id=k4k6-bwwv v:category="A Prosperous City" v:averageRating=0 v:name="General City Budget Incremental Changes"

property e:k4k6-bwwv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:k4k6-bwwv t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:k4k6-bwwv t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | department_code | department_name | subdept_code | subdepartment_name | program_code | program_name              | fund_code | fund_name    | source_fund_code | source_fund_name                                      | budget_request_description               | budget_request_category | account_code | account_name     | one_time_01_on_going_bb | 2016_17_proposed_budget_incremental_change_from_2015_16_adopted | 2016_17_adopted_budget_incremental_change_from_2015_16_adopted | 
| =========== | =============== | =============== | ============ | ================== | ============ | ========================= | ========= | ============ | ================ | ===================================================== | ======================================== | ======================= | ============ | ================ | ======================= | =============================================================== | ============================================================== | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 100              | General Fund                                          | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 2842                                                            | 2842                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 385              | Proposition A Local Transit Assistance Fund (Sch. 26) | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 2471                                                            | 2471                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 395              | Area Plan for the Aging Title 7 Fund (Sch. 21)        | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 11028                                                           | 11028                                                          | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 424              | Community Development Trust Fund (Sch. 8)             | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 2173                                                            | 2173                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 202          | Family Caregiver Services | 100       | General Fund | 395              | Area Plan for the Aging Title 7 Fund (Sch. 21)        | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 4959                                                            | 4959                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 203          | Older Workers Program     | 100       | General Fund | 395              | Area Plan for the Aging Title 7 Fund (Sch. 21)        | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 197                                                             | 197                                                            | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 203          | Older Workers Program     | 100       | General Fund | 410              | Other Programs for the Aging (Sch. 21)                | 2015-16 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 2491                                                            | 2491                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 100              | General Fund                                          | 2016-17 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 10255                                                           | 10255                                                          | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 385              | Proposition A Local Transit Assistance Fund (Sch. 26) | 2016-17 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 9081                                                            | 9081                                                           | 
| 1467985707  | 2               | Aging           | 02LVL5       | Aging              | 201          | Senior Services           | 100       | General Fund | 395              | Area Plan for the Aging Title 7 Fund (Sch. 21)        | 2016-17 Employee Compensation Adjustment | 1-Obligatory Changes    | 1010         | Salaries General | BB                      | 38792                                                           | 38792                                                          | 
```