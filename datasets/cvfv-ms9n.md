# Illinois Guardianship and Advocacy Commission HRA Public Accounting Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-guardianship-and-advocacy-commission-hra-public-accounting-report-c2fdf) |
| Metadata | [Link](https://data.illinois.gov/api/views/cvfv-ms9n) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cvfv-ms9n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cvfv-ms9n/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cvfv-ms9n |
| Name | Illinois Guardianship and Advocacy Commission HRA Public Accounting Report |
| Category | Social/Healthcare |
| Tags | igac, disabilities, wards, caseload, guardian, guardianship |
| Created | 2013-03-01T16:28:14Z |
| Publication Date | 2013-03-11T22:31:31Z |

## Description

Human Rights Authority annual public accounting report.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | hra_public_accounting_report | HRA Public Accounting Report | text      | text        |
| Yes      | numeric metric | fy_10_actual                 | FY 10 Actual                 | number    | number      |
| Yes      | numeric metric | fy_11_actual                 | FY 11 Actual                 | number    | number      |
| Yes      | numeric metric | fy_12_target_projected       | FY 12 Target/Projected       | number    | number      |
| Yes      | numeric metric | fy_12_actual                 | FY 12 Actual                 | number    | number      |
| Yes      | numeric metric | fy_13_target_projected       | FY 13 Target/Projected       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cvfv-ms9n d:2013-03-01T08:28:15.000Z t:hra_public_accounting_report="Total expenditures - all sources (in thousands)                                     $" m:fy_12_target_projected=658 m:fy_10_actual=617.7 m:fy_12_actual=649.1 m:fy_13_target_projected=696.1 m:fy_11_actual=632.3

series e:cvfv-ms9n d:2013-03-01T08:28:15.000Z t:hra_public_accounting_report="Total expenditures - state appropriated funds (in thousands)       $" m:fy_12_target_projected=658 m:fy_10_actual=617.7 m:fy_12_actual=649.1 m:fy_13_target_projected=696.1 m:fy_11_actual=632.3

series e:cvfv-ms9n d:2013-03-01T08:28:15.000Z t:hra_public_accounting_report="Average monthly full-time equivalents" m:fy_12_target_projected=8 m:fy_10_actual=9 m:fy_12_actual=8 m:fy_13_target_projected=9 m:fy_11_actual=9
```

## Meta Commands

```ls
metric m:fy_10_actual p:double l:"FY 10 Actual" t:dataTypeName=number

metric m:fy_11_actual p:double l:"FY 11 Actual" t:dataTypeName=number

metric m:fy_12_target_projected p:double l:"FY 12 Target/Projected" t:dataTypeName=number

metric m:fy_12_actual p:double l:"FY 12 Actual" t:dataTypeName=number

metric m:fy_13_target_projected p:double l:"FY 13 Target/Projected" t:dataTypeName=number

entity e:cvfv-ms9n l:"Illinois Guardianship and Advocacy Commission HRA Public Accounting Report" t:url=https://data.illinois.gov/api/views/cvfv-ms9n

property e:cvfv-ms9n t:meta.view v:id=cvfv-ms9n v:category=Social/Healthcare v:averageRating=0 v:name="Illinois Guardianship and Advocacy Commission HRA Public Accounting Report"

property e:cvfv-ms9n t:meta.view.owner v:id=vtpq-vdyg v:screenName=rdixo4 v:displayName=rdixo4

property e:cvfv-ms9n t:meta.view.tableauthor v:id=vtpq-vdyg v:screenName=rdixo4 v:roleName=publisher v:displayName=rdixo4
```

## Top Records

```ls
| :updated_at | hra_public_accounting_report                                                                     | fy_10_actual | fy_11_actual | fy_12_target_projected | fy_12_actual | fy_13_target_projected | 
| =========== | ================================================================================================ | ============ | ============ | ====================== | ============ | ====================== | 
| 1362126495  | Total expenditures - all sources (in thousands) $                                                | 617.7        | 632.3        | 658.0                  | 649.1        | 696.1                  | 
| 1362126495  | Total expenditures - state appropriated funds (in thousands) $                                   | 617.7        | 632.3        | 658.0                  | 649.1        | 696.1                  | 
| 1362126495  | Average monthly full-time equivalents                                                            | 9.0          | 9.0          | 8.0                    | 8.0          | 9.0                    | 
| 1362126495  | Number of volunteer hours HRA members contribute to the HRA                                      | 5368         | 2789         | 3000                   | 2812         | 3000                   | 
| 1362126495  | Number of information and referral inquiries the HRA handled                                     | 248.0        | 211.0        | 250.0                  | 198.0        | 200.0                  | 
| 1362126495  | Number of HRA cases handled                                                                      | 337.0        | 327.0        | 330.0                  | 285.0        | 300.0                  | 
| 1362126495  | Number of recommendations for improvement issued to service providers for substantiated findings | 139.0        | 158.0        | 150.0                  | 123.0        | 150.0                  | 
| 1362126495  | Number of recommendations accepted and implemented by service providers                          | 136.0        | 134.0        | 127.0                  | 110.0        | 134.0                  | 
| 1362126495  | Percentage of HRA recommendations accepted and implemented by service providers investigated %   | 98           | 85           | 85                     | 89           | 89                     | 
| 1362126495  | Number of persons with disabilities benefiting from HRA recommendations                          | 15925        | 32932        | 21000                  | 25382        | 25000                  | 
```