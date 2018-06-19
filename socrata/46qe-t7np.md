# Positions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/positions) |
| Metadata | [Link](https://data.lacity.org/api/views/46qe-t7np) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/46qe-t7np/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/46qe-t7np/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 46qe-t7np |
| Name | Positions |
| Attribution | City of LA |
| Category | A Well Run City |
| Tags | positions, budget, departments, employees, personnel |
| Created | 2016-04-25T16:53:43Z |
| Publication Date | 2017-04-20T23:21:04Z |

## Description

This dataset lists all employee positions (civilian regular authority, commissioners, as-needed, etc) by budgetary department, program, and fund, dating back to Fiscal Year 2012.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | department_code           | Department Code           | text      | number      |
| Yes      | series tag     | department_name           | Department Name           | text      | text        |
| Yes      | series tag     | program_code              | Program Code              | text      | number      |
| Yes      | series tag     | program_name              | Program Name              | text      | text        |
| Yes      | series tag     | source_fund_code          | Fund Code                 | text      | number      |
| Yes      | series tag     | fund_code                 | Source Fund Code          | text      | text        |
| Yes      | series tag     | source_fund_name          | Source Fund Name          | text      | text        |
| Yes      | series tag     | account_code              | Account Code              | text      | text        |
| Yes      | series tag     | account_name              | Account Name              | text      | text        |
| Yes      | numeric metric | 2011_12_adopted_budget    | 2011-12 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2012_13_adopted_budget    | 2012-13 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2013_14_adopted_budget    | 2013-14 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2014_15_adopted_budget    | 2014-15 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2015_16_adopted_budget    | 2015-16 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2016_17_adopted_budget    | 2016-17 Adopted Budget    | number    | number      |
| Yes      | numeric metric | 2017_2018_proposed_budget | 2017-2018 Proposed Budget | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:46qe-t7np d:2017-04-20T23:20:39.000Z t:fund_code=100 t:program_code=201 t:source_fund_code=100 t:program_name="Senior Services" t:account_code=POSAN t:department_code=2 t:department_name=Aging t:source_fund_name="General Fund" t:account_name="As Needed Positions" m:2015_16_adopted_budget=6 m:2014_15_adopted_budget=3 m:2012_13_adopted_budget=3 m:2016_17_adopted_budget=6 m:2013_14_adopted_budget=3 m:2017_2018_proposed_budget=5.82

series e:46qe-t7np d:2017-04-20T23:20:39.000Z t:fund_code=100 t:program_code=201 t:source_fund_code=100 t:program_name="Senior Services" t:account_code=POSSG t:department_code=2 t:department_name=Aging t:source_fund_name="General Fund" t:account_name="Civilian Regular Authority Positions" m:2015_16_adopted_budget=5.82 m:2011_12_adopted_budget=34 m:2014_15_adopted_budget=5.85 m:2012_13_adopted_budget=31 m:2016_17_adopted_budget=5.82 m:2013_14_adopted_budget=31 m:2017_2018_proposed_budget=0

series e:46qe-t7np d:2017-04-20T23:20:39.000Z t:fund_code=100 t:program_code=201 t:source_fund_code=100 t:program_name="Senior Services" t:account_code=RESSG t:department_code=2 t:department_name=Aging t:source_fund_name="General Fund" t:account_name="Civilian Resolution Authority Positions" m:2011_12_adopted_budget=2 m:2012_13_adopted_budget=3 m:2016_17_adopted_budget=4 m:2013_14_adopted_budget=2 m:2017_2018_proposed_budget=5.12
```

## Meta Commands

```ls
metric m:2011_12_adopted_budget p:long l:"2011-12 Adopted Budget" t:dataTypeName=number

metric m:2012_13_adopted_budget p:long l:"2012-13 Adopted Budget" t:dataTypeName=number

metric m:2013_14_adopted_budget p:long l:"2013-14 Adopted Budget" t:dataTypeName=number

metric m:2014_15_adopted_budget p:long l:"2014-15 Adopted Budget" t:dataTypeName=number

metric m:2015_16_adopted_budget p:long l:"2015-16 Adopted Budget" t:dataTypeName=number

metric m:2016_17_adopted_budget p:long l:"2016-17 Adopted Budget" t:dataTypeName=number

metric m:2017_2018_proposed_budget p:long l:"2017-2018 Proposed Budget" t:dataTypeName=number

entity e:46qe-t7np l:Positions t:attribution="City of LA" t:url=https://data.lacity.org/api/views/46qe-t7np

property e:46qe-t7np t:meta.view v:id=46qe-t7np v:category="A Well Run City" v:attributionLink=http://lacity.org v:averageRating=0 v:name=Positions v:attribution="City of LA"

property e:46qe-t7np t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:46qe-t7np t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:46qe-t7np t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | department_code | department_name | program_code | program_name              | source_fund_code | fund_code | source_fund_name                                      | account_code | account_name                            | 2011_12_adopted_budget | 2012_13_adopted_budget | 2013_14_adopted_budget | 2014_15_adopted_budget | 2015_16_adopted_budget | 2016_17_adopted_budget | 2017_2018_proposed_budget | 
| =========== | =============== | =============== | ============ | ========================= | ================ | ========= | ===================================================== | ============ | ======================================= | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ========================= | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 100       | General Fund                                          | POSAN        | As Needed Positions                     |                        | 3                      | 3                      | 3                      | 6                      | 6                      | 5.82                      | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 100       | General Fund                                          | POSSG        | Civilian Regular Authority Positions    | 34                     | 31                     | 31                     | 5.85                   | 5.82                   | 5.82                   | 0                         | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 100       | General Fund                                          | RESSG        | Civilian Resolution Authority Positions | 2                      | 3                      | 2                      |                        |                        | 4                      | 5.12                      | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 385       | Proposition A Local Transit Assistance Fund (Sch. 26) | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        |                        | 5.12                   | 5.12                   | 17.46                     | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 395       | Area Plan for the Aging Title 7 Fund (Sch. 21)        | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        |                        |                        | 17.46                  | 3.6                       | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 424       | Community Development Trust Fund (Sch. 8)             | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        |                        | 3.6                    | 3.6                    |                           | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | 564       | Title VII Older Americans Act Fund (Sch. 21)          | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        |                        | 17.46                  |                        |                           | 
| 1492730439  | 2               | Aging           | 201          | Senior Services           | 100              | XXX       | DEFAULT SPECIAL FUND                                  | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        | 26.15                  |                        |                        | 0.23                      | 
| 1492730439  | 2               | Aging           | 202          | Family Caregiver Services | 100              | 100       | General Fund                                          | POSSG        | Civilian Regular Authority Positions    |                        |                        |                        |                        | 0.23                   | 0.23                   |                           | 
| 1492730439  | 2               | Aging           | 202          | Family Caregiver Services | 100              | 100       | General Fund                                          | RESSG        | Civilian Resolution Authority Positions | 9                      | 8                      | 8                      |                        |                        |                        | 7.77                      | 
```