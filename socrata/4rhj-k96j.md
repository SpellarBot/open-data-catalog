# FY16 YTD IT Spend By Functional Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy16-ytd-it-spend-by-functional-group) |
| Metadata | [Link](https://data.wa.gov/api/views/4rhj-k96j) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/4rhj-k96j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/4rhj-k96j/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 4rhj-k96j |
| Name | FY16 YTD IT Spend By Functional Group |
| Attribution | OCIO |
| Category | Economics |
| Tags | it spend |
| Created | 2017-01-10T18:00:47Z |
| Publication Date | 2017-01-10T18:03:31Z |

## Description

Year to date IT Spend numbers for fiscal year 2016

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | functional_group           | Functional Group           | text      | text        |
| Yes      | numeric metric | it_acquisitions_ytd        | IT Acquisitions YTD        | money     | money       |
| Yes      | numeric metric | it_maintenance_and_ops_ytd | IT Maintenance and Ops YTD | money     | money       |
| Yes      | numeric metric | total                      | Total                      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4rhj-k96j d:2017-01-10T18:01:04.000Z t:functional_group="Higher Education" m:total=479972395 m:it_acquisitions_ytd=447038395 m:it_maintenance_and_ops_ytd=32934000

series e:4rhj-k96j d:2017-01-10T18:01:04.000Z t:functional_group="Human Services - Other" m:total=202180196 m:it_acquisitions_ytd=60404805 m:it_maintenance_and_ops_ytd=141775391

series e:4rhj-k96j d:2017-01-10T18:01:04.000Z t:functional_group=Transportation m:total=115132845 m:it_acquisitions_ytd=33828154 m:it_maintenance_and_ops_ytd=81304691
```

## Meta Commands

```ls
metric m:it_acquisitions_ytd p:integer l:"IT Acquisitions YTD" t:dataTypeName=money

metric m:it_maintenance_and_ops_ytd p:integer l:"IT Maintenance and Ops YTD" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:4rhj-k96j l:"FY16 YTD IT Spend By Functional Group" t:attribution=OCIO t:url=https://data.wa.gov/api/views/4rhj-k96j

property e:4rhj-k96j t:meta.view v:id=4rhj-k96j v:category=Economics v:averageRating=0 v:name="FY16 YTD IT Spend By Functional Group" v:attribution=OCIO

property e:4rhj-k96j t:meta.view.owner v:id=x4yv-cfu9 v:screenName="Derek Puckett" v:displayName="Derek Puckett"

property e:4rhj-k96j t:meta.view.tableauthor v:id=x4yv-cfu9 v:screenName="Derek Puckett" v:roleName=administrator v:displayName="Derek Puckett"
```

## Top Records

```ls
| :updated_at | functional_group                                          | it_acquisitions_ytd | it_maintenance_and_ops_ytd | total     | 
| =========== | ========================================================= | =================== | ========================== | ========= | 
| 1484071264  | Higher Education                                          | 447038395           | 32934000                   | 479972395 | 
| 1484071264  | Human Services - Other                                    | 60404805            | 141775391                  | 202180196 | 
| 1484071264  | Transportation                                            | 33828154            | 81304691                   | 115132845 | 
| 1484071264  | Human Services - Department of Social and Health Services | 31224989            | 133483138                  | 164708128 | 
| 1484071264  | Governmental Operations                                   | 18011423            | 242309021                  | 260320443 | 
| 1484071264  | Judicial                                                  | 12224499            | 10505718                   | 22730216  | 
| 1484071264  | Natural Resources and Recreation                          | 8063171             | 40074278                   | 48137449  | 
| 1484071264  | Kindergarten Through Grade 12 Education                   | 2155359             | 4767953                    | 6923312   | 
| 1484071264  | Legislative                                               | 1219223             | 6143914                    | 7363137   | 
| 1484071264  | Education - Other                                         | 1019612             | 4445183                    | 5464795   | 
```