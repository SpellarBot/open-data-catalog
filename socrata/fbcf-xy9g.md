# Illinois Guardianship and Advocacy Commission LAS Public Accounting Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-guardianship-and-advocacy-commission-las-public-accounting-report-a1908) |
| Metadata | [Link](https://data.illinois.gov/api/views/fbcf-xy9g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fbcf-xy9g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fbcf-xy9g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fbcf-xy9g |
| Name | Illinois Guardianship and Advocacy Commission LAS Public Accounting Report |
| Category | Social/Healthcare |
| Tags | igac, disabilities, wards, caseload, guardian, guardianship |
| Created | 2013-03-01T16:36:42Z |
| Publication Date | 2013-03-11T22:32:40Z |

## Description

Legal Advocacy Service annual public accounting report.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | las_public_accounting_report | LAS Public Accounting Report | text      | text        |
| Yes      | numeric metric | fy_2010_actual               | FY 2010 Actual               | number    | number      |
| Yes      | numeric metric | fy_2011_actual               | FY 2011 Actual               | number    | number      |
| Yes      | numeric metric | fy_2012_target_projected     | FY 2012 Target/ Projected    | number    | number      |
| Yes      | numeric metric | fy_2012_actual               | FY 2012 Actual               | number    | number      |
| Yes      | numeric metric | fy_2013_target_projected     | FY 2013 Target/ Projected    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fbcf-xy9g d:2013-03-01T08:36:45.000Z t:las_public_accounting_report="Total expenditures - all sources (in thousands) $" m:fy_2012_target_projected=940 m:fy_2013_target_projected=994.5 m:fy_2010_actual=882.4 m:fy_2012_actual=927.3 m:fy_2011_actual=903.3

series e:fbcf-xy9g d:2013-03-01T08:36:45.000Z t:las_public_accounting_report="Total expenditures - state appropriated funds (in thousands)  $" m:fy_2012_target_projected=940 m:fy_2013_target_projected=994.5 m:fy_2010_actual=882.4 m:fy_2012_actual=927.3 m:fy_2011_actual=903.3

series e:fbcf-xy9g d:2013-03-01T08:36:45.000Z t:las_public_accounting_report="Average monthly full-time equivalents" m:fy_2012_target_projected=12 m:fy_2013_target_projected=12 m:fy_2010_actual=11 m:fy_2012_actual=12 m:fy_2011_actual=12
```

## Meta Commands

```ls
metric m:fy_2010_actual p:double l:"FY 2010 Actual" t:dataTypeName=number

metric m:fy_2011_actual p:double l:"FY 2011 Actual" t:dataTypeName=number

metric m:fy_2012_target_projected p:double l:"FY 2012 Target/ Projected" t:dataTypeName=number

metric m:fy_2012_actual p:double l:"FY 2012 Actual" t:dataTypeName=number

metric m:fy_2013_target_projected p:double l:"FY 2013 Target/ Projected" t:dataTypeName=number

entity e:fbcf-xy9g l:"Illinois Guardianship and Advocacy Commission LAS Public Accounting Report" t:url=https://data.illinois.gov/api/views/fbcf-xy9g

property e:fbcf-xy9g t:meta.view v:id=fbcf-xy9g v:category=Social/Healthcare v:averageRating=0 v:name="Illinois Guardianship and Advocacy Commission LAS Public Accounting Report"

property e:fbcf-xy9g t:meta.view.owner v:id=vtpq-vdyg v:screenName=rdixo4 v:displayName=rdixo4

property e:fbcf-xy9g t:meta.view.tableauthor v:id=vtpq-vdyg v:screenName=rdixo4 v:roleName=publisher v:displayName=rdixo4
```

## Top Records

```ls
| :updated_at | las_public_accounting_report                                       | fy_2010_actual | fy_2011_actual | fy_2012_target_projected | fy_2012_actual | fy_2013_target_projected | 
| =========== | ================================================================== | ============== | ============== | ======================== | ============== | ======================== | 
| 1362127005  | Total expenditures - all sources (in thousands) $                  | 882.4          | 903.3          | 940.0                    | 927.3          | 994.5                    | 
| 1362127005  | Total expenditures - state appropriated funds (in thousands) $     | 882.4          | 903.3          | 940.0                    | 927.3          | 994.5                    | 
| 1362127005  | Average monthly full-time equivalents                              | 11.0           | 12.0           | 12.0                     | 12.0           | 12.0                     | 
| 1362127005  | Total LAS cases handled                                            | 5286           | 5292           | 5000                     | 5484           | 5200                     | 
| 1362127005  | Total clients served                                               | 9241           | 9333           | 8500                     | 8817           | 8500                     | 
| 1362127005  | Requests for information, referrals or assistance                  | 1620           | 1697           | 1600                     | 1506           | 1600                     | 
| 1362127005  | Percentage of cases referred to higher courts %                    | 86             | 82.2           | 85                       | 75             | 75                       | 
| 1362127005  | Percentage of program staff involved in direct service provision % | 100            | 100            | 100                      | 100            | 100                      | 
| 1362127005  | Cost per case handled (in dollars) $                               | 167.00         | 171.00         | 188.00                   | 169.00         | 191.00                   | 
| 1362127005  | Cost per client served (in dollars) $                              | 95.00          | 97.00          | 111.00                   | 105.00         | 117.00                   | 
```