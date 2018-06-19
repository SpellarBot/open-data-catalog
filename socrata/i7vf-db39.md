# Expenditures: ESD: Douglas: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-douglas-fiscal-year-2013-7b830) |
| Metadata | [Link](https://data.oregon.gov/api/views/i7vf-db39) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i7vf-db39/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i7vf-db39/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i7vf-db39 |
| Name | Expenditures: ESD: Douglas: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, douglas, fiscal year 2013 |
| Created | 2013-10-31T20:55:45Z |
| Publication Date | 2013-10-31T20:58:28Z |

## Description

Expenditures for Douglas ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | esd        | ESD#       | number    | number      |
| Yes      | series tag     | esd_name   | ESD Name   | text      | text        |
| Yes      | series tag     | fund       | Fund       | text      | text        |
| Yes      | numeric metric | obj        | Obj        | number    | number      |
| Yes      | series tag     | compt_desc | Compt-Desc | text      | text        |
| Yes      | series tag     | remitstate | RemitState | text      | text        |
| Yes      | series tag     | remitname  | RemitName  | text      | text        |
| Yes      | numeric metric | totalcost  | TotalCost  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i7vf-db39 d:2013-01-01T00:00:00.000Z t:esd_name="Douglas Education Service District" t:remitstate=OR t:compt_desc="Other Required Payroll Costs-Unemployment Compensation" t:fund="Unemployment Fund" t:remitname="Employment Benefits" m:totalcost=13739.62 m:esd=1980 m:obj=232

series e:i7vf-db39 d:2013-01-01T00:00:00.000Z t:esd_name="Douglas Education Service District" t:remitstate=OR t:compt_desc="Other Required Payroll Costs-Unemployment Compensation" t:fund="Unemployment Fund" t:remitname="Employment Benefits" m:totalcost=27598.38 m:esd=1980 m:obj=232

series e:i7vf-db39 d:2013-01-01T00:00:00.000Z t:esd_name="Douglas Education Service District" t:remitstate=OR t:compt_desc="Other Required Payroll Costs-Unemployment Compensation" t:fund="Unemployment Fund" t:remitname="Employment Benefits" m:totalcost=14743.96 m:esd=1980 m:obj=232
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:i7vf-db39 l:"Expenditures: ESD: Douglas: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/i7vf-db39

property e:i7vf-db39 t:meta.view v:id=i7vf-db39 v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Douglas: Fiscal Year 2013"

property e:i7vf-db39 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:i7vf-db39 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                           | fund                  | obj | compt_desc                                             | remitstate | remitname           | totalcost | 
| ==== | ================================== | ===================== | === | ====================================================== | ========== | =================== | ========= | 
| 1980 | Douglas Education Service District | Unemployment Fund     | 232 | Other Required Payroll Costs-Unemployment Compensation | OR         | Employment Benefits | 13739.62  | 
| 1980 | Douglas Education Service District | Unemployment Fund     | 232 | Other Required Payroll Costs-Unemployment Compensation | OR         | Employment Benefits | 27598.38  | 
| 1980 | Douglas Education Service District | Unemployment Fund     | 232 | Other Required Payroll Costs-Unemployment Compensation | OR         | Employment Benefits | 14743.96  | 
| 1980 | Douglas Education Service District | Unemployment Fund     | 232 | Other Required Payroll Costs-Unemployment Compensation | OR         | Employment Benefits | 12224.71  | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4781.36   | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4781.36   | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4781.36   | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4510.00   | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4510.00   | 
| 1980 | Douglas Education Service District | Early Retirement Fund | 241 | Contractual Employee Benefits-Health Insurance         | OR         | OEBB                | 4510.00   | 
```