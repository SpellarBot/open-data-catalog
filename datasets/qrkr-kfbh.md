# General Fund Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-fund-revenue) |
| Metadata | [Link](https://data.lacity.org/api/views/qrkr-kfbh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qrkr-kfbh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qrkr-kfbh |
| Name | General Fund Revenue |
| Category | A Prosperous City |
| Tags | budget, revenue |
| Created | 2016-07-11T14:10:40Z |
| Publication Date | 2016-07-11T14:12:29Z |
| Rows Updated | 2016-07-11T14:10:54Z |

## Description

Revenue towards the City's general fund by department, program, and account.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | dept_code               | Dept Code               | text      | number      |
| Yes      | series tag     | department_name         | Department Name         | text      | text        |
| Yes      | series tag     | program_code            | Program Code            | text      | number      |
| Yes      | series tag     | program_name            | Program Name            | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | number      |
| Yes      | series tag     | fund_name               | Fund Name               | text      | text        |
| Yes      | series tag     | account_code            | Account Code            | text      | number      |
| Yes      | series tag     | account_name            | Account Name            | text      | text        |
| Yes      | numeric metric | 2014_15_actuals         | 2014-15 Actuals         | number    | number      |
| Yes      | numeric metric | 2015_16_adopted_budget  | 2015-16 Adopted Budget  | number    | number      |
| Yes      | numeric metric | 2015_16_estimates       | 2015-16 Estimates       | number    | number      |
| Yes      | numeric metric | 2016_17_proposed_budget | 2016-17 Proposed Budget | number    | number      |
| Yes      | numeric metric | 2016_17_adopted_budget  | 2016-17 Adopted Budget  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qrkr-kfbh d:2016-07-11T07:10:45.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:dept_code=2 t:program_name="Senior Services" t:account_code=5126 t:department_name=Aging t:account_name="Fire Insurance Proceeds" m:2015_16_estimates=182775

series e:qrkr-kfbh d:2016-07-11T07:10:45.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:dept_code=2 t:program_name="Senior Services" t:account_code=5169 t:department_name=Aging t:account_name="Jury Duty Reimbursement" m:2015_16_adopted_budget=40 m:2016_17_proposed_budget=133 m:2016_17_adopted_budget=133 m:2015_16_estimates=133

series e:qrkr-kfbh d:2016-07-11T07:10:45.000Z t:fund_name="General Fund" t:fund_code=100 t:program_code=201 t:dept_code=2 t:program_name="Senior Services" t:account_code=5188 t:department_name=Aging t:account_name="Miscellaneous Revenue-Others" m:2015_16_adopted_budget=200 m:2016_17_proposed_budget=330 m:2014_15_actuals=2322 m:2016_17_adopted_budget=330 m:2015_16_estimates=330
```

## Meta Commands

```ls
metric m:2014_15_actuals p:integer l:"2014-15 Actuals" t:dataTypeName=number

metric m:2015_16_adopted_budget p:integer l:"2015-16 Adopted Budget" t:dataTypeName=number

metric m:2015_16_estimates p:integer l:"2015-16 Estimates" t:dataTypeName=number

metric m:2016_17_proposed_budget p:integer l:"2016-17 Proposed Budget" t:dataTypeName=number

metric m:2016_17_adopted_budget p:integer l:"2016-17 Adopted Budget" t:dataTypeName=number

entity e:qrkr-kfbh l:"General Fund Revenue" t:url=https://data.lacity.org/api/views/qrkr-kfbh

property e:qrkr-kfbh t:meta.view v:id=qrkr-kfbh v:category="A Prosperous City" v:averageRating=0 v:name="General Fund Revenue"

property e:qrkr-kfbh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qrkr-kfbh t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU

property e:qrkr-kfbh t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```