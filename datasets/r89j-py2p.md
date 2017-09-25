# Fiscal Year 2013 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2013-budget-9d416) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/r89j-py2p) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/r89j-py2p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/r89j-py2p/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | r89j-py2p |
| Name | Fiscal Year 2013 Budget |
| Category | Government |
| Tags | budget, operating budget, county budget, fiscal year |
| Created | 2012-09-11T15:58:40Z |
| Publication Date | 2012-10-05T13:57:17Z |

## Description

This dataset includes the Fiscal Year* 2013 Council-approved operating budget for Montgomery County.  The dataset does not include revenues and agency budget information; each agency, such as Montgomery County Public Schools, maintain their individual budget information.   The data can be sorted, filtered, and exported by the following elements:  Function (grouping, such as “Public Safety”), Department, Program, Cost Center (activity within a program), Fund Type , Fund Subtype, Fund Name, Subfund Name, Personnel & Operating Expenses, Object Name, and Account Name.


*The 12-month period to which the annual operating and capital budgets and their respective appropriations apply.  The Montgomery County fiscal year starts on July 1st and ends on June 30th.

Update Frequency:  Annually

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | function                           | Function                             | text      | text        |
| Yes      | series tag     | department                         | Department                           | text      | text        |
| Yes      | series tag     | program_name                       | Program Name                         | text      | text        |
| Yes      | series tag     | cost_center_name                   | Cost Center Name                     | text      | text        |
| Yes      | series tag     | fund_type                          | Fund Type                            | text      | text        |
| Yes      | series tag     | fund_subtype                       | Fund Subtype                         | text      | text        |
| Yes      | series tag     | subfund_name                       | Subfund Name                         | text      | text        |
| Yes      | series tag     | fund_name                          | Fund Name                            | text      | text        |
| Yes      | series tag     | personnel_costs_operating_expenses | Personnel Costs & Operating Expenses | text      | text        |
| Yes      | series tag     | object_name                        | Object Name                          | text      | text        |
| Yes      | series tag     | account_name                       | Account Name                         | text      | text        |
| Yes      | numeric metric | amount                             | Amount                               | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r89j-py2p d:2013-01-01T00:00:00.000Z t:fund_type="Tax Supported Funds" t:fund_subtype="General Fund" t:program_name="Pre-Trial Services" t:function="Public Safety" t:object_name=Retirement t:account_name=RSP t:personnel_costs_operating_expenses="Personnel Costs" t:fund_name="General Fund" t:subfund_name="General Fund" t:department="Correction and Rehabilitation" t:cost_center_name=ACS m:amount=4295

series e:r89j-py2p d:2013-01-01T00:00:00.000Z t:fund_type="Tax Supported Funds" t:fund_subtype="General Fund" t:program_name="Field Services" t:function="Public Safety" t:object_name=Retirement t:account_name=ERS t:personnel_costs_operating_expenses="Personnel Costs" t:fund_name="General Fund" t:subfund_name="General Fund" t:department=Police t:cost_center_name="5th District S.A.T" m:amount=193146

series e:r89j-py2p d:2013-01-01T00:00:00.000Z t:fund_type="Tax Supported Funds" t:fund_subtype="General Fund" t:program_name="Investigative Services" t:function="Public Safety" t:object_name=Retirement t:account_name=ERS t:personnel_costs_operating_expenses="Personnel Costs" t:fund_name="General Fund" t:subfund_name="General Fund" t:department=Police t:cost_center_name="C.I.D-Auto Theft" m:amount=229661
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:r89j-py2p l:"Fiscal Year 2013 Budget" t:url=https://data.montgomerycountymd.gov/api/views/r89j-py2p

property e:r89j-py2p t:meta.view d:2017-09-25T07:29:42.237Z v:averageRating=0 v:name="Fiscal Year 2013 Budget" v:id=r89j-py2p v:category=Government

property e:r89j-py2p t:meta.view.owner d:2017-09-25T07:29:42.237Z v:displayName="MC Open Data" v:id=fnci-gphj v:screenName="MC Open Data"

property e:r89j-py2p t:meta.view.tableauthor d:2017-09-25T07:29:42.237Z v:displayName="MC Open Data" v:roleName=administrator v:id=fnci-gphj v:screenName="MC Open Data"
```

## Top Records

```ls
| function           | department                    | program_name           | cost_center_name   | fund_type           | fund_subtype | subfund_name | fund_name    | personnel_costs_operating_expenses | object_name     | account_name   | amount    | 
| ================== | ============================= | ====================== | ================== | =================== | ============ | ============ | ============ | ================================== | =============== | ============== | ========= | 
| Public Safety      | Correction and Rehabilitation | Pre-Trial Services     | ACS                | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | RSP            | 4295.00   | 
| Public Safety      | Police                        | Field Services         | 5th District S.A.T | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | ERS            | 193146.00 | 
| Public Safety      | Police                        | Investigative Services | C.I.D-Auto Theft   | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | ERS            | 229661.00 | 
| General Government | Finance                       | General Accounting     | General Accounting | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | GRIP           | 6686.00   | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Group Insurance | Prescription   | 14293.00  | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Group Insurance | Vision         | 570.00    | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Group Insurance | Life Insurance | 3683.00   | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | RSP            | 37019.00  | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | ERS            | 18364.00  | 
| General Government | Finance                       | Payroll                | Payroll            | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement      | GRIP           | 14901.00  | 
```