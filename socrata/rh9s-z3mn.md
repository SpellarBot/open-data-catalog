# Proposed FY14 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-fy14-proposed-91993) |
| Metadata | [Link](https://data.honolulu.gov/api/views/rh9s-z3mn) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/rh9s-z3mn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/rh9s-z3mn/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | rh9s-z3mn |
| Name | Proposed FY14 Budget |
| Category | Finance |
| Tags | proposed, budget, fy2014 |
| Created | 2013-03-07T20:24:57Z |
| Publication Date | 2013-11-13T01:25:55Z |

## Description

Proposed City Budget for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | number      |
| Yes      | numeric metric | fy_2011_actual           | FY 2011 Actual           | number    | number      |
| Yes      | numeric metric | fy_2012_actual           | FY 2012 Actual           | number    | number      |
| Yes      | numeric metric | fy_2013_budget           | FY 2013 Budget           | number    | number      |
| Yes      | numeric metric | fy_2014_current_services | FY 2014 Current Services | number    | number      |
| Yes      | numeric metric | fy_2014_budget_issues    | FY 2014 Budget Issues    | number    | number      |
| Yes      | numeric metric | fy_2014_proposed_budget  | FY 2014 Proposed Budget  | number    | number      |
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
series e:rh9s-z3mn d:2013-03-07T12:25:01.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name=Administration t:object_code=1101 m:fy_2014_current_services=871188 m:fy_2014_proposed_budget=871188 m:fy_2013_budget=815700 m:fy_2014_budget_issues=0 m:fund=110 m:fy_2012_actual=652845 m:fy_2011_actual=666895

series e:rh9s-z3mn d:2013-03-07T12:25:01.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Non-Holiday Overtime Pay" t:division_name=Administration t:object_code=1102 m:fy_2014_current_services=0 m:fy_2014_proposed_budget=0 m:fy_2013_budget=0 m:fy_2014_budget_issues=0 m:fund=110 m:fy_2012_actual=0 m:fy_2011_actual=-553

series e:rh9s-z3mn d:2013-03-07T12:25:01.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Accumulated Vacation Pay (Lump-Sum Pay)" t:division_name=Administration t:object_code=1106 m:fy_2014_current_services=0 m:fy_2014_proposed_budget=0 m:fy_2013_budget=0 m:fy_2014_budget_issues=0 m:fund=110 m:fy_2012_actual=14197 m:fy_2011_actual=57126
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2011_actual p:integer l:"FY 2011 Actual" t:dataTypeName=number

metric m:fy_2012_actual p:integer l:"FY 2012 Actual" t:dataTypeName=number

metric m:fy_2013_budget p:integer l:"FY 2013 Budget" t:dataTypeName=number

metric m:fy_2014_current_services p:integer l:"FY 2014 Current Services" t:dataTypeName=number

metric m:fy_2014_budget_issues p:integer l:"FY 2014 Budget Issues" t:dataTypeName=number

metric m:fy_2014_proposed_budget p:integer l:"FY 2014 Proposed Budget" t:dataTypeName=number

entity e:rh9s-z3mn l:"Proposed FY14 Budget" t:url=https://data.honolulu.gov/api/views/rh9s-z3mn

property e:rh9s-z3mn t:meta.view v:id=rh9s-z3mn v:category=Finance v:averageRating=0 v:name="Proposed FY14 Budget"

property e:rh9s-z3mn t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:rh9s-z3mn t:meta.view.owner v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"

property e:rh9s-z3mn t:meta.view.tableauthor v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"
```

## Top Records

```ls
| :updated_at | department | division | fund | object_code | fy_2011_actual | fy_2012_actual | fy_2013_budget | fy_2014_current_services | fy_2014_budget_issues | fy_2014_proposed_budget | department_name            | division_name  | fund_name    | object_code_name                        | 
| =========== | ========== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ======================= | ========================== | ============== | ============ | ======================================= | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1101        | 666895         | 652845         | 815700         | 871188                   | 0                     | 871188                  | Budget and Fiscal Services | Administration | General Fund | Regular Pay                             | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1102        | -553           | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Non-Holiday Overtime Pay                | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1106        | 57126          | 14197          | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Accumulated Vacation Pay (Lump-Sum Pay) | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1107        | 492            | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Holiday Overtime Pay                    | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1109        | 1383           | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Temporary Assignment Pay                | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1120        | 0              | 0              | -63244         | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Vacancy Cut-Back(Budget)                | 
| 1362659101  | OP_BFS     | BFS0300C | 110  |             | 0              | 0              | -15836         | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Vacancy Cut-Back (Other Adj)            | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1125        | 184309         | 153554         | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Personal Svcs-Contract Positions        | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1301        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Unemployment Compensation               | 
| 1362659101  | OP_BFS     | BFS0300C | 110  | 1401        | 0              | 0              | 0              | 0                        | 0                     | 0                       | Budget and Fiscal Services | Administration | General Fund | Retirement System Contribution          | 
```