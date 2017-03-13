# Fiscal Year 2015 County Executive Recommended Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2015-county-executive-recommended-operating-budget-b2df3) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/y7rf-xz8k) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/y7rf-xz8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/y7rf-xz8k/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | y7rf-xz8k |
| Name | Fiscal Year 2015 County Executive Recommended Operating Budget |
| Category | Government |
| Tags | fiscal year 2015, council, executives, recommended budget |
| Created | 2014-04-25T19:24:33Z |
| Publication Date | 2014-08-18T21:15:46Z |
| Rows Updated | 2014-08-18T21:13:40Z |

## Description

This dataset includes the Fiscal Year* 2015 County Executive Recommended operating budget for Montgomery County. The dataset does not include revenues and  detailed agency budget information (only includes agency budget information by fund); each agency, such as Montgomery County Public Schools, maintain their individual budget information. The data can be sorted, filtered, and exported by the following elements: Function (grouping, such as ?Public Safety?), Department, Program, Cost Center (activity within a program), Fund Type , Fund Subtype, Fund Name, Subfund Name, Personnel & Operating Expenses, Object Name, and Account Name. *The 12-month period to which the annual operating and capital budgets and their respective appropriations apply. The Montgomery County fiscal year starts on July 1st and ends on June 30th. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                 | Data Type | Render Type |
| ======== | ============== | ====================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | function                               | Function                             | text      | text        |
| Yes      | series tag     | department                             | Department                           | text      | text        |
| Yes      | series tag     | program_name                           | Program Name                         | text      | text        |
| Yes      | series tag     | cost_center_name                       | Cost Center Name                     | text      | text        |
| Yes      | series tag     | fund_type                              | Fund Type                            | text      | text        |
| Yes      | series tag     | fund_subtype                           | Fund SubType                         | text      | text        |
| Yes      | series tag     | subfund_name                           | SubFund Name                         | text      | text        |
| Yes      | series tag     | fund_name                              | Fund Name                            | text      | text        |
| Yes      | series tag     | personnel_costs_amp_operating_expenses | Personnel Costs & Operating Expenses | text      | text        |
| Yes      | series tag     | object_name                            | Object Name                          | text      | text        |
| Yes      | series tag     | account_name                           | Account Name                         | text      | text        |
| Yes      | numeric metric | recommended_amount                     | Recommended Amount                   | money     | money       |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y7rf-xz8k d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Operating Expenses" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Office Of Zoning And Admin Hearings" t:subfund_name="General Fund" t:department="Zoning and Administrative Hearings" t:program_name="Zoning and Administrative Hearings" t:object_name="Contract and Services" t:fund_subtype="General Fund" t:account_name="Preparation Of Transcripts/Recorders" t:function="General Government" m:recommended_amount=15000

series e:y7rf-xz8k d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Operating Expenses" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Office Of Zoning And Admin Hearings" t:subfund_name="General Fund" t:department="Zoning and Administrative Hearings" t:program_name="Zoning and Administrative Hearings" t:object_name=Maintenance t:fund_subtype="General Fund" t:account_name="Other Office Equip Repair / Maint" t:function="General Government" m:recommended_amount=180

series e:y7rf-xz8k d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Operating Expenses" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Office Of Zoning And Admin Hearings" t:subfund_name="General Fund" t:department="Zoning and Administrative Hearings" t:program_name="Zoning and Administrative Hearings" t:object_name="Rental Leases" t:fund_subtype="General Fund" t:account_name=Copiers t:function="General Government" m:recommended_amount=6000
```

## Meta Commands

```ls
metric m:recommended_amount p:double l:"Recommended Amount" d:"the County Executive?s recommended budget for the upcoming fiscal year, submitted to Council for review each year by March 15th." t:dataTypeName=money

entity e:y7rf-xz8k l:"Fiscal Year 2015 County Executive Recommended Operating Budget" t:url=https://data.montgomerycountymd.gov/api/views/y7rf-xz8k

property e:y7rf-xz8k t:meta.view v:id=y7rf-xz8k v:category=Government v:averageRating=0 v:name="Fiscal Year 2015 County Executive Recommended Operating Budget"

property e:y7rf-xz8k t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"

property e:y7rf-xz8k t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```