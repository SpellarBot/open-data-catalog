# Proposed FY16 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-fy16-budget) |
| Metadata | [Link](https://data.honolulu.gov/api/views/rkqa-i8sr) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/rkqa-i8sr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/rkqa-i8sr/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | rkqa-i8sr |
| Name | Proposed FY16 Budget |
| Category | Finance |
| Tags | proposed, budget, fy2016 |
| Created | 2015-03-06T01:35:29Z |
| Publication Date | 2015-03-06T01:39:08Z |
| Rows Updated | 2015-03-06T01:36:52Z |

## Description

Proposed City Budget for Fiscal Year 2016

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department               | Department               | text      | text        |
| Yes      | series tag     | division                 | Division                 | text      | text        |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | text        |
| Yes      | numeric metric | fy_2013_actual           | FY 2013 Actual           | money     | money       |
| Yes      | numeric metric | fy_2014_actual           | FY 2014 Actual           | money     | money       |
| Yes      | numeric metric | fy_2015_budget           | FY 2015 Budget           | money     | money       |
| Yes      | numeric metric | fy_2016_current_services | FY 2016 Current Services | money     | money       |
| Yes      | numeric metric | fy_2016_budget_issues    | FY 2016 Budget Issues    | money     | money       |
| Yes      | numeric metric | fy_2016_proposed_budget  | FY 2016 Proposed Budget  | money     | money       |
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
series e:rkqa-i8sr d:2015-03-05T17:35:57.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Regular Pay" t:division_name=Administration t:object_code=1101 m:fy_2013_actual=648445 m:fy_2016_proposed_budget=896328 m:fy_2015_budget=854868 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=749381 m:fy_2016_current_services=896328

series e:rkqa-i8sr d:2015-03-05T17:35:57.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Adjustment for Deactivated Positions" t:division_name=Administration t:object_code=1101D m:fy_2013_actual=0 m:fy_2016_proposed_budget=0 m:fy_2015_budget=0 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=0 m:fy_2016_current_services=0

series e:rkqa-i8sr d:2015-03-05T17:35:57.000Z t:fund_name="General Fund" t:division=BFS0300C t:department=OP_BFS t:department_name="Budget and Fiscal Services" t:object_code_name="Transfer to Prov for Vacant Positions" t:division_name=Administration t:object_code=1101T m:fy_2013_actual=0 m:fy_2016_budget_issues=0 m:fund=110 m:fy_2014_actual=0
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

entity e:rkqa-i8sr l:"Proposed FY16 Budget" t:url=https://data.honolulu.gov/api/views/rkqa-i8sr

property e:rkqa-i8sr t:meta.view v:id=rkqa-i8sr v:category=Finance v:averageRating=0 v:name="Proposed FY16 Budget"

property e:rkqa-i8sr t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"

property e:rkqa-i8sr t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```