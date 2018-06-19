# 2011-13 Tax Expenditure Report - List of Tax Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-13-tax-expenditure-report-list-of-tax-expenditures-28e16) |
| Metadata | [Link](https://data.oregon.gov/api/views/cjmm-9sxs) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cjmm-9sxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cjmm-9sxs/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cjmm-9sxs |
| Name | 2011-13 Tax Expenditure Report - List of Tax Expenditures |
| Category | Revenue & Expense |
| Tags | revenue, expense, tax, expenditures, oregon, data, data.oregon.gov |
| Created | 2011-03-03T16:48:05Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

The 1995 Budget Accountability Act (the Act) requires the governor, with the assistance of the Department of Revenue and the Department of Administrative Services, to produce a tax expenditure report every biennium, along with the Governor?s Recommended Budget. The report was first prepared in 1996 for the 1997?99 biennium. This report covers tax expenditures for the 2011?13 biennium.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | type                | Type                | text      | text        |
| Yes      | numeric metric | number              | Number              | number    | number      |
| Yes      | series tag     | tax_expenditure     | Tax Expenditure     | text      | text        |
| Yes      | series tag     | program_or_function | Program or Function | text      | text        |
| Yes      | numeric metric | enacted             | Enacted             | number    | number      |
| Yes      | series tag     | oregon_statute      | Oregon Statute      | text      | text        |
| Yes      | series tag     | 2009_11             | 2009-11             | text      | text        |
| Yes      | series tag     | 2011_13             | 2011-13             | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cjmm-9sxs d:2011-01-01T00:00:00.000Z t:program_or_function=Education t:oregon_statute=316.048 t:2011_13=$15,800.00 t:tax_expenditure="Scholarship and Fellowship Income" t:type="Income Tax: Federal Exclusions" t:2009_11=$14,300.00 m:number=1.001 m:enacted=1954

series e:cjmm-9sxs d:2011-01-01T00:00:00.000Z t:program_or_function=Education t:oregon_statute=316.048 t:2011_13=$100.00 t:tax_expenditure="Interest on Education Savings Bonds" t:type="Income Tax: Federal Exclusions" t:2009_11=$100.00 m:number=1.002 m:enacted=1988

series e:cjmm-9sxs d:2011-01-01T00:00:00.000Z t:program_or_function=Education t:oregon_statute=316.048 t:2011_13=$1,400.00 t:tax_expenditure="Earnings on Education Savings Accounts" t:type="Income Tax: Federal Exclusions" t:2009_11=$700.00 m:number=1.003 m:enacted=1997
```

## Meta Commands

```ls
metric m:number p:float l:Number t:dataTypeName=number

metric m:enacted p:integer l:Enacted t:dataTypeName=number

entity e:cjmm-9sxs l:"2011-13 Tax Expenditure Report - List of Tax Expenditures" t:url=https://data.oregon.gov/api/views/cjmm-9sxs

property e:cjmm-9sxs t:meta.view v:id=cjmm-9sxs v:category="Revenue & Expense" v:averageRating=100 v:name="2011-13 Tax Expenditure Report - List of Tax Expenditures"

property e:cjmm-9sxs t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cjmm-9sxs t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| type                           | number | tax_expenditure                                  | program_or_function | enacted | oregon_statute | 2009_11       | 2011_13       | 
| ============================== | ====== | ================================================ | =================== | ======= | ============== | ============= | ============= | 
| Income Tax: Federal Exclusions | 1.001  | Scholarship and Fellowship Income                | Education           | 1954    | 316.048        | $14,300.00    | $15,800.00    | 
| Income Tax: Federal Exclusions | 1.002  | Interest on Education Savings Bonds              | Education           | 1988    | 316.048        | $100.00       | $100.00       | 
| Income Tax: Federal Exclusions | 1.003  | Earnings on Education Savings Accounts           | Education           | 1997    | 316.048        | $700.00       | $1,400.00     | 
| Income Tax: Federal Exclusions | 1.004  | Qualified Tuition Programs (Federal)             | Education           | 1996    | 316.048        | $3,800.00     | $6,600.00     | 
| Income Tax: Federal Exclusions | 1.005  | Exclusion of Employer Provided Tuition Reduction | Education           | 1984    | 316.048        | $1,500.00     | $1,500.00     | 
| Income Tax: Federal Exclusions | 1.007  | Certain Foster Care Payments                     | Human Services      | 1982    | 316.048        | $6,000.00     | $6,700.00     | 
| Income Tax: Federal Exclusions | 1.008  | Employee Adoption Benefits                       | Human Services      | 1996    | 316.048        | Less than 100 | Less than 100 | 
| Income Tax: Federal Exclusions | 1.009  | Cafeteria Plan Benefits                          | Human Services      | 1974    | 316.048        | $266,100.00   | $316,700.00   | 
| Income Tax: Federal Exclusions | 1.010  | Employer Paid Medical Benefits                   | Human Services      | 1918    | 316.048        | $890,400.00   | $1,022,900.00 | 
| Income Tax: Federal Exclusions | 1.012  | Prescription Drug Insurance (Part D)             | Human Services      | 2003    | 316.048        | $46,300.00    | $53,400.00    | 
```