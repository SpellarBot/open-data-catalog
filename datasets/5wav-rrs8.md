# Fiscal Year 2017 IT Spend By Functional Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-it-spend-by-functional-group) |
| Metadata | [Link](https://data.wa.gov/api/views/5wav-rrs8) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5wav-rrs8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5wav-rrs8/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5wav-rrs8 |
| Name | Fiscal Year 2017 IT Spend By Functional Group |
| Attribution | OCIO |
| Category | Economics |
| Tags | it spend |
| Created | 2017-01-10T17:49:25Z |
| Publication Date | 2017-01-10T17:59:46Z |

## Description

Spend numbers are reflected as of the most recently closed fiscal month.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | functional_group           | Functional Group           | text      | text        |
| Yes      | numeric metric | it_acquisitions_ytd        | IT Acquisitions YTD        | money     | money       |
| Yes      | numeric metric | it_maintenance_and_ops_ytd | IT Maintenance and Ops YTD | money     | money       |
| Yes      | numeric metric | total                      | Total                      | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5wav-rrs8 d:2017-01-01T00:00:00.000Z t:functional_group="Higher Education" m:total=221441010 m:it_acquisitions_ytd=206519889 m:it_maintenance_and_ops_ytd=14921121

series e:5wav-rrs8 d:2017-01-01T00:00:00.000Z t:functional_group="Human Services - Other" m:total=74965554 m:it_acquisitions_ytd=19674618 m:it_maintenance_and_ops_ytd=55290936

series e:5wav-rrs8 d:2017-01-01T00:00:00.000Z t:functional_group="Human Services - Department of Social and Health Services" m:total=64422752 m:it_acquisitions_ytd=14403928 m:it_maintenance_and_ops_ytd=50018824
```

## Meta Commands

```ls
metric m:it_acquisitions_ytd p:integer l:"IT Acquisitions YTD" t:dataTypeName=money

metric m:it_maintenance_and_ops_ytd p:integer l:"IT Maintenance and Ops YTD" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:5wav-rrs8 l:"Fiscal Year 2017 IT Spend By Functional Group" t:attribution=OCIO t:url=https://data.wa.gov/api/views/5wav-rrs8

property e:5wav-rrs8 t:meta.view v:id=5wav-rrs8 v:category=Economics v:averageRating=0 v:name="Fiscal Year 2017 IT Spend By Functional Group" v:attribution=OCIO

property e:5wav-rrs8 t:meta.view.owner v:id=x4yv-cfu9 v:screenName="Derek Puckett" v:displayName="Derek Puckett"

property e:5wav-rrs8 t:meta.view.tableauthor v:id=x4yv-cfu9 v:screenName="Derek Puckett" v:roleName=administrator v:displayName="Derek Puckett"
```

## Top Records

```ls
| functional_group                                          | it_acquisitions_ytd | it_maintenance_and_ops_ytd | total     | 
| ========================================================= | =================== | ========================== | ========= | 
| Higher Education                                          | 206519889           | 14921121                   | 221441010 | 
| Human Services - Other                                    | 19674618            | 55290936                   | 74965554  | 
| Human Services - Department of Social and Health Services | 14403928            | 50018824                   | 64422752  | 
| Governmental Operations                                   | 10862369            | 92966568                   | 103828936 | 
| Transportation                                            | 8450219             | 35949886                   | 44400105  | 
| Judicial                                                  | 5582308             | 5999520                    | 11581828  | 
| Natural Resources and Recreation                          | 2568190             | 18582039                   | 21150229  | 
| Kindergarten Through Grade 12 Education                   | 1027701             | 1555897                    | 2583598   | 
| Education - Other                                         | 537920              | 3142163                    | 3680083   | 
| Legislative                                               | 485476              | 2444653                    | 2930129   | 
```