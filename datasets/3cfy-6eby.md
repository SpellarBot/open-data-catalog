# Open Budget Application: Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-operating-budget-7a996) |
| Metadata | [Link](https://data.seattle.gov/api/views/3cfy-6eby) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3cfy-6eby/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3cfy-6eby/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3cfy-6eby |
| Name | Open Budget Application: Operating Budget |
| Category | Finance |
| Created | 2014-09-22T23:01:51Z |
| Publication Date | 2016-08-11T21:41:41Z |

## Description

data powering openbudget.seattle.gov

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscal_year        | Fiscal Year        | number    | number      |
| Yes      | series tag     | service            | Service            | text      | text        |
| Yes      | series tag     | department         | Department         | text      | text        |
| Yes      | series tag     | program            | Program            | text      | text        |
| Yes      | series tag     | expense_category   | Expense Category   | text      | text        |
| Yes      | series tag     | fund               | Fund               | text      | text        |
| Yes      | series tag     | fund_type          | Fund Type          | text      | text        |
| Yes      | series tag     | expense_type       | Expense Type       | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | numeric metric | recommended_amount | Recommended Amount | number    | number      |
| Yes      | numeric metric | approved_amount    | Approved Amount    | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3cfy-6eby d:2016-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Annual Certification and Inspection" t:program="Annual Certification and Inspection" t:department="Construction and Inspections" t:service="Neighborhoods & Development" t:expense_category="Annual Certification and Inspection" t:fund="General Fund" m:approved_amount=4096261

series e:3cfy-6eby d:2016-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Code Compliance" t:program="Code Compliance" t:department="Construction and Inspections" t:service="Neighborhoods & Development" t:expense_category="Code Compliance" t:fund="General Fund" m:approved_amount=5292260

series e:3cfy-6eby d:2016-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Code Development" t:program="Code Compliance" t:department="Construction and Inspections" t:service="Neighborhoods & Development" t:expense_category="Code Development" t:fund="General Fund" m:approved_amount=1043946
```

## Meta Commands

```ls
metric m:recommended_amount p:integer l:"Recommended Amount" t:dataTypeName=number

metric m:approved_amount p:decimal l:"Approved Amount" t:dataTypeName=number

entity e:3cfy-6eby l:"Open Budget Application: Operating Budget" t:url=https://data.seattle.gov/api/views/3cfy-6eby

property e:3cfy-6eby t:meta.view v:id=3cfy-6eby v:category=Finance v:averageRating=0 v:name="Open Budget Application: Operating Budget"

property e:3cfy-6eby t:meta.view.license v:name="Public Domain"

property e:3cfy-6eby t:meta.view.owner v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:displayName="Kirk, Daniel"

property e:3cfy-6eby t:meta.view.tableauthor v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:roleName=administrator v:displayName="Kirk, Daniel"
```

## Top Records

```ls
| fiscal_year | service                     | department                   | program                             | expense_category                                  | fund         | fund_type          | expense_type      | description                                       | recommended_amount | approved_amount | 
| =========== | =========================== | ============================ | =================================== | ================================================= | ============ | ================== | ================= | ================================================= | ================== | =============== | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Annual Certification and Inspection | Annual Certification and Inspection               | General Fund | Tax-Supported Fund | Operating Expense | Annual Certification and Inspection               |                    | 4096261         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Code Compliance                     | Code Compliance                                   | General Fund | Tax-Supported Fund | Operating Expense | Code Compliance                                   |                    | 5292260         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Code Compliance                     | Code Development                                  | General Fund | Tax-Supported Fund | Operating Expense | Code Development                                  |                    | 1043946         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Code Compliance                     | Rental Housing                                    | General Fund | Tax-Supported Fund | Operating Expense | Rental Housing                                    |                    | 2327256         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Inspections            | Building Inspections                              | General Fund | Tax-Supported Fund | Operating Expense | Building Inspections                              |                    | 5697741         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Inspections            | Construction Inspections Unallocated CBA          | General Fund | Tax-Supported Fund | Operating Expense | Construction Inspections Unallocated CBA          |                    | 2318752         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Inspections            | Electrical Inspections                            | General Fund | Tax-Supported Fund | Operating Expense | Electrical Inspections                            |                    | 5792546         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Inspections            | Signs and Billboards                              | General Fund | Tax-Supported Fund | Operating Expense | Signs and Billboards                              |                    | 349985          | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Inspections            | Site Review and Inspection                        | General Fund | Tax-Supported Fund | Operating Expense | Site Review and Inspection                        |                    | 4302502         | 
| 2016        | Neighborhoods & Development | Construction and Inspections | Construction Permit Services        | Construction Permit Services Overhead Allocations | General Fund | Tax-Supported Fund | Operating Expense | Construction Permit Services Overhead Allocations |                    | -2020647        | 
```