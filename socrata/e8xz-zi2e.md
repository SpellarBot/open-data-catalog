# Proposed FY17 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-fy17-budget) |
| Metadata | [Link](https://data.honolulu.gov/api/views/e8xz-zi2e) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/e8xz-zi2e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/e8xz-zi2e/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | e8xz-zi2e |
| Name | Proposed FY17 Budget |
| Category | Finance |
| Tags | proposed, budget, fy2017 |
| Created | 2016-04-28T18:54:21Z |
| Publication Date | 2016-04-28T20:04:06Z |

## Description

Proposed City Budget for Fiscal Year 2017

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | text        |
| Yes      | numeric metric | fy_2014_actual           | FY 2014 Actual           | number    | number      |
| Yes      | numeric metric | fy_2015_actual           | FY 2015 Actual           | number    | number      |
| Yes      | numeric metric | fy_2016_budget           | FY 2016 Budget           | number    | number      |
| Yes      | numeric metric | fy_2017_current_services | FY 2017 Current Services | number    | number      |
| Yes      | numeric metric | fy_2017_budget_issues    | FY 2017 Budget Issues    | number    | number      |
| Yes      | numeric metric | fy_2017_proposed_budget  | FY 2017 Proposed Budget  | number    | number      |
| Yes      | series tag     | department_name          | Department Name          | text      | text        |
| Yes      | series tag     | division_name            | Division Name            | text      | text        |
| Yes      | series tag     | fund_name                | Fund Name                | text      | text        |
| Yes      | series tag     | object_code_name         | Object Code Name         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e8xz-zi2e d:2016-04-28T11:54:26.000Z t:fund_name="Sewer Fund" t:division=ENV2114 t:department=OP_ENV t:department_name="Environmental Services" t:object_code_name="Paint Supplies, Grit Cloth/Sand Paper, Solvent" t:division_name="Collection System Maintenance" t:object_code=2513 m:fy_2015_actual=4160 m:fy_2017_current_services=10000 m:fy_2017_budget_issues=0 m:fund=170 m:fy_2014_actual=6936 m:fy_2016_budget=13500 m:fy_2017_proposed_budget=10000

series e:e8xz-zi2e d:2016-04-28T11:54:26.000Z t:fund_name="Sewer Fund" t:division=ENV2114 t:department=OP_ENV t:department_name="Environmental Services" t:object_code_name=Meals-Dinner t:division_name="Collection System Maintenance" t:object_code=2354 m:fy_2015_actual=23660 m:fy_2017_current_services=21000 m:fy_2017_budget_issues=0 m:fund=170 m:fy_2014_actual=19820 m:fy_2016_budget=21000 m:fy_2017_proposed_budget=21000

series e:e8xz-zi2e d:2016-04-28T11:54:26.000Z t:fund_name="Sewer Fund" t:division=ENV2114 t:department=OP_ENV t:department_name="Environmental Services" t:object_code_name="Other Building & Construction Materials" t:division_name="Collection System Maintenance" t:object_code=2607 m:fy_2015_actual=46822 m:fy_2017_current_services=80000 m:fy_2017_budget_issues=0 m:fund=170 m:fy_2014_actual=61024 m:fy_2016_budget=80000 m:fy_2017_proposed_budget=80000
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2014_actual p:integer l:"FY 2014 Actual" t:dataTypeName=number

metric m:fy_2015_actual p:integer l:"FY 2015 Actual" t:dataTypeName=number

metric m:fy_2016_budget p:integer l:"FY 2016 Budget" t:dataTypeName=number

metric m:fy_2017_current_services p:integer l:"FY 2017 Current Services" t:dataTypeName=number

metric m:fy_2017_budget_issues p:integer l:"FY 2017 Budget Issues" t:dataTypeName=number

metric m:fy_2017_proposed_budget p:integer l:"FY 2017 Proposed Budget" t:dataTypeName=number

entity e:e8xz-zi2e l:"Proposed FY17 Budget" t:url=https://data.honolulu.gov/api/views/e8xz-zi2e

property e:e8xz-zi2e t:meta.view v:id=e8xz-zi2e v:category=Finance v:averageRating=0 v:name="Proposed FY17 Budget"

property e:e8xz-zi2e t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:e8xz-zi2e t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2014_actual | fy_2015_actual | fy_2016_budget | fy_2017_current_services | fy_2017_budget_issues | fy_2017_proposed_budget | department_name        | division_name                 | fund_name  | object_code_name                                   | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ======================= | ====================== | ============================= | ========== | ================================================== | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2513        | 6936           | 4160           | 13500          | 10000                    | 0                     | 10000                   | Environmental Services | Collection System Maintenance | Sewer Fund | Paint Supplies, Grit Cloth/Sand Paper, Solvent     | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2354        | 19820          | 23660          | 21000          | 21000                    | 0                     | 21000                   | Environmental Services | Collection System Maintenance | Sewer Fund | Meals-Dinner                                       | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2607        | 61024          | 46822          | 80000          | 80000                    | 0                     | 80000                   | Environmental Services | Collection System Maintenance | Sewer Fund | Other Building & Construction Materials            | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2457        | 2319           | 2256           | 0              | 0                        | 0                     | 0                       | Environmental Services | Collection System Maintenance | Sewer Fund | Engine Oil                                         | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2152        | 244            | 0              | 500            | 500                      | 0                     | 500                     | Environmental Services | Collection System Maintenance | Sewer Fund | Soil                                               | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2201        | 69360          | 68             | 0              | 0                        | 0                     | 0                       | Environmental Services | Collection System Maintenance | Sewer Fund | Cleaning and Toilet Supplies                       | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2301        | 0              | 77             | 2000           | 1000                     | 0                     | 1000                    | Environmental Services | Collection System Maintenance | Sewer Fund | Medical, Dental, Hospital & Institutional Supplies | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 2802        | 28             | 0              | 0              | 0                        | 0                     | 0                       | Environmental Services | Collection System Maintenance | Sewer Fund | Light Wires And Devices                            | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 1110        | 0              | 25             | 0              | 0                        | 0                     | 0                       | Environmental Services | Collection System Maintenance | Sewer Fund | Waiting Time                                       | 
| 1461844466  | OP_ENV     | ENV2114  | 170  | 3305        | 4742           | 5124           | 6500           | 6500                     | 0                     | 6500                    | Environmental Services | Collection System Maintenance | Sewer Fund | Sewer                                              | 
```