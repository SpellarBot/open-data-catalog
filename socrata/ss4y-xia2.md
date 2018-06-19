# Fiscal Year 2015 Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2015-budget-37edf) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ss4y-xia2) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ss4y-xia2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ss4y-xia2/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ss4y-xia2 |
| Name | Fiscal Year 2015 Budget |
| Category | Government |
| Tags | budget, operating budget, county budget |
| Created | 2014-07-11T19:34:37Z |
| Publication Date | 2014-08-18T21:25:30Z |

## Description

This dataset includes the Fiscal Year* 2015 Council-approved operating budget for Montgomery County. The dataset does not include revenues and detailed agency budget information (only includes agency budget information by fund); each agency, such as Montgomery County Public Schools, maintain their individual budget information. The data can be sorted, filtered, and exported by the following elements: Function (grouping, such as ?Public Safety?), Department, Program, Cost Center (activity within a program), Fund Type , Fund Subtype, Fund Name, Subfund Name, Personnel & Operating Expenses, Object Name, and Account Name. *The 12-month period to which the annual operating and capital budgets and their respective appropriations apply. The Montgomery County fiscal year starts on July 1st and ends on June 30th. Update Frequency: Annually

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
| Yes      | numeric metric | amount                                 | Amount                               | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ss4y-xia2 d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Operating Expenses" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Council Staff Opertions" t:subfund_name="General Fund" t:department="County Council" t:program_name="Council Staff Operations" t:object_name="Miscellaneous Operating Expenses" t:fund_subtype="General Fund" t:account_name="Other Misc Operating Expenses" t:function="General Government" m:amount=4000

series e:ss4y-xia2 d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Personnel Costs" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Board Of Appeals" t:subfund_name="General Fund" t:department="Board of Appeals" t:program_name="Zoning Related Hearings and Administrative Appeals" t:object_name="Salaries and Wages" t:fund_subtype="General Fund" t:account_name="Full Time Salaries" t:function="General Government" m:amount=223136

series e:ss4y-xia2 d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Personnel Costs" t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:cost_center_name="Board Of Appeals" t:subfund_name="General Fund" t:department="Board of Appeals" t:program_name="Zoning Related Hearings and Administrative Appeals" t:object_name="Salaries and Wages" t:fund_subtype="General Fund" t:account_name="Part Time Salaries" t:function="General Government" m:amount=71255
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount d:Money t:dataTypeName=money

entity e:ss4y-xia2 l:"Fiscal Year 2015 Budget" t:url=https://data.montgomerycountymd.gov/api/views/ss4y-xia2

property e:ss4y-xia2 t:meta.view v:id=ss4y-xia2 v:category=Government v:averageRating=0 v:name="Fiscal Year 2015 Budget"

property e:ss4y-xia2 t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:ss4y-xia2 t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| function           | department       | program_name                                       | cost_center_name        | fund_type           | fund_subtype | subfund_name | fund_name    | personnel_costs_amp_operating_expenses | object_name                      | account_name                               | amount | 
| ================== | ================ | ================================================== | ======================= | =================== | ============ | ============ | ============ | ====================================== | ================================ | ========================================== | ====== | 
| General Government | County Council   | Council Staff Operations                           | Council Staff Opertions | Tax Supported Funds | General Fund | General Fund | General Fund | Operating Expenses                     | Miscellaneous Operating Expenses | Other Misc Operating Expenses              | 4000   | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Salaries and Wages               | Full Time Salaries                         | 223136 | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Salaries and Wages               | Part Time Salaries                         | 71255  | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Salaries and Wages               | Board/Commission Stipends/Empl Supplements | 81375  | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Salaries and Wages               | Budget Adjustment (Salary)                 | 5842   | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Salaries and Wages               | Other Compensation Adj-OMB Use only        | 419    | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Social Security                  | Social Security- FICA                      | 18227  | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Social Security                  | Social Security- FICA Medicaid             | 4268   | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Social Security                  | Other Non-Workforce FICA                   | 6225   | 
| General Government | Board of Appeals | Zoning Related Hearings and Administrative Appeals | Board Of Appeals        | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                        | Group Insurance                  | Group Insurance                            | 42940  | 
```