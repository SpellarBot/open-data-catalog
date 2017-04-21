# FY18 REC CIP Budget Montgomery Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy18-rec-cip-budget-montgomery-data) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/urxh-76aw) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/urxh-76aw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/urxh-76aw/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | urxh-76aw |
| Name | FY18 REC CIP Budget Montgomery Data |
| Tags | cip, budget |
| Created | 2017-01-18T20:49:08Z |
| Publication Date | 2017-01-19T13:15:19Z |

## Description

FY18 REC CIP Budget Montgomery Data

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | datasetfy    | DataSetFY    | number    | number      |
| Yes      | time           | fiscal_year  | Fiscal_Year  | number    | number      |
| Yes      | series tag     | service      | Service      | text      | text        |
| Yes      | series tag     | category     | Category     | text      | text        |
| Yes      | series tag     | project      | Project      | text      | text        |
| Yes      | series tag     | project_id   | Project_id   | text      | text        |
| Yes      | series tag     | fund         | Fund         | text      | text        |
| Yes      | series tag     | fund_type    | Fund_Type    | text      | text        |
| Yes      | numeric metric | recommended  | Recommended  | number    | number      |
| Yes      | numeric metric | approved_amt | Approved_amt | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:urxh-76aw d:2016-01-01T00:00:00.000Z t:fund_type=Local t:project="Indoor Air Quality Improvements:  MCPS (P006503)" t:category=Countywide t:project_id=P006503 t:service="Montgomery County Public Schools" t:fund="G.O. Bonds" m:approved_amt=0 m:datasetfy=2018 m:recommended=22073000

series e:urxh-76aw d:2016-01-01T00:00:00.000Z t:fund_type=Local t:project="Ballfield Improvements (P008720)" t:category=Development t:project_id=P008720 t:service=M-NCPPC t:fund="G.O. Bonds" m:approved_amt=0 m:datasetfy=2018 m:recommended=552000

series e:urxh-76aw d:2016-01-01T00:00:00.000Z t:fund_type=External t:project="Ballfield Improvements (P008720)" t:category=Development t:project_id=P008720 t:service=M-NCPPC t:fund=Intergovernmental m:approved_amt=0 m:datasetfy=2018 m:recommended=0
```

## Meta Commands

```ls
metric m:datasetfy p:integer l:DataSetFY t:dataTypeName=number

metric m:recommended p:integer l:Recommended t:dataTypeName=number

metric m:approved_amt p:integer l:Approved_amt t:dataTypeName=number

entity e:urxh-76aw l:"FY18 REC CIP Budget Montgomery Data" t:url=https://data.montgomerycountymd.gov/api/views/urxh-76aw

property e:urxh-76aw t:meta.view v:id=urxh-76aw v:averageRating=0 v:name="FY18 REC CIP Budget Montgomery Data"

property e:urxh-76aw t:meta.view.owner v:id=y8as-9hmt v:screenName=Rekha v:displayName=Rekha

property e:urxh-76aw t:meta.view.tableauthor v:id=y8as-9hmt v:screenName=Rekha v:roleName=editor v:displayName=Rekha
```

## Top Records

```ls
| datasetfy | fiscal_year | service                          | category                              | project                                         | project_id | fund                              | fund_type | recommended | approved_amt | 
| ========= | =========== | ================================ | ===================================== | =============================================== | ========== | ================================= | ========= | =========== | ============ | 
| 2018      | 2016        | Montgomery County Public Schools | Countywide                            | Indoor Air Quality Improvements: MCPS (P006503) | P006503    | G.O. Bonds                        | Local     | 22073000    | 0            | 
| 2018      | 2016        | M-NCPPC                          | Development                           | Ballfield Improvements (P008720)                | P008720    | G.O. Bonds                        | Local     | 552000      | 0            | 
| 2018      | 2016        | M-NCPPC                          | Development                           | Ballfield Improvements (P008720)                | P008720    | Intergovernmental                 | External  | 0           | 0            | 
| 2018      | 2016        | M-NCPPC                          | Development                           | Ballfield Improvements (P008720)                | P008720    | PAYGO                             | Local     | 521000      | 0            | 
| 2018      | 2016        | General Government               | County Offices and Other Improvements | Council Office Building Renovations (P010100)   | P010100    | Cable TV                          | Local     | 900000      | 0            | 
| 2018      | 2016        | General Government               | County Offices and Other Improvements | Council Office Building Renovations (P010100)   | P010100    | G.O. Bonds                        | Local     | 3518000     | 0            | 
| 2018      | 2016        | General Government               | County Offices and Other Improvements | Council Office Building Renovations (P010100)   | P010100    | Long-Term Financing               | Local     | 0           | 0            | 
| 2018      | 2016        | General Government               | County Offices and Other Improvements | Council Office Building Renovations (P010100)   | P010100    | PAYGO                             | Local     | 164000      | 0            | 
| 2018      | 2016        | General Government               | County Offices and Other Improvements | Council Office Building Garage (P011601)        | P011601    | G.O. Bonds                        | Local     | 159000      | 0            | 
| 2018      | 2016        | WSSC                             | Water Montgomery County               | Newcut Road Water Main, Part 2 (P013802)        | P013802    | Contributions - Other (WSSC only) | Local     | 1417000     | 0            | 
```