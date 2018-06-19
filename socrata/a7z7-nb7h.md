# Fiscal Year 2016 County Executive Recommended Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2016-county-executive-recommended-operating-budget) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/a7z7-nb7h) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/a7z7-nb7h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/a7z7-nb7h/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | a7z7-nb7h |
| Name | Fiscal Year 2016 County Executive Recommended Operating Budget |
| Category | Government |
| Tags | operating budget, fiscal year, recommended, county executive |
| Created | 2015-03-31T15:45:56Z |
| Publication Date | 2015-04-01T20:11:44Z |

## Description

This dataset includes the Fiscal Year* 2016 County Executive Recommended operating budget for Montgomery County. The dataset does not include revenues and detailed agency budget information (only includes agency budget information by fund); each agency, such as Montgomery County Public Schools, maintain their individual budget information.  *The 12-month period to which the annual operating and capital budgets and their respective appropriations apply. The Montgomery County fiscal year starts on July 1st and ends on June 30th. 
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | function                           | Function                             | text      | text        |
| Yes      | series tag     | department                         | Department                           | text      | text        |
| Yes      | series tag     | program_name                       | Program Name                         | text      | text        |
| Yes      | series tag     | cost_center_name                   | Cost Center Name                     | text      | text        |
| Yes      | series tag     | fund_type                          | Fund Type                            | text      | text        |
| Yes      | series tag     | fund_subtype                       | Fund SubType                         | text      | text        |
| Yes      | series tag     | subfund_name                       | SubFund Name                         | text      | text        |
| Yes      | series tag     | fund_name                          | Fund Name                            | text      | text        |
| Yes      | series tag     | personnel_costs_operating_expenses | Personnel Costs & Operating Expenses | text      | text        |
| Yes      | series tag     | object_name                        | Object Name                          | text      | text        |
| Yes      | series tag     | account_name                       | Account Name                         | text      | text        |
| Yes      | numeric metric | amount                             | Recommended Amount                   | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a7z7-nb7h d:2016-01-01T00:00:00.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name="Council Members" t:subfund_name="General Fund" t:department="County Council" t:program_name="Councilmember Offices" t:object_name="Salaries and Wages" t:fund_subtype="General Fund" t:account_name="Seasonal Temps" t:function="General Government" m:amount=1000

series e:a7z7-nb7h d:2016-01-01T00:00:00.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name="Council Members" t:subfund_name="General Fund" t:department="County Council" t:program_name="Councilmember Offices" t:object_name="Salaries and Wages" t:fund_subtype="General Fund" t:account_name="Budget Adjustment (Salary)" t:function="General Government" m:amount=108480

series e:a7z7-nb7h d:2016-01-01T00:00:00.000Z t:fund_name="General Fund" t:fund_type="Tax Supported Funds" t:personnel_costs_operating_expenses="Personnel Costs" t:cost_center_name="Council Members" t:subfund_name="General Fund" t:department="County Council" t:program_name="Councilmember Offices" t:object_name="Salaries and Wages" t:fund_subtype="General Fund" t:account_name="Lapse (Planning)" t:function="General Government" m:amount=-83750
```

## Meta Commands

```ls
metric m:amount p:double l:"Recommended Amount" d:"the County Executive?s recommended budget for the upcoming fiscal year, submitted to Council for review each year by March 15th." t:dataTypeName=money

entity e:a7z7-nb7h l:"Fiscal Year 2016 County Executive Recommended Operating Budget" t:url=https://data.montgomerycountymd.gov/api/views/a7z7-nb7h

property e:a7z7-nb7h t:meta.view v:id=a7z7-nb7h v:category=Government v:averageRating=0 v:name="Fiscal Year 2016 County Executive Recommended Operating Budget"

property e:a7z7-nb7h t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:a7z7-nb7h t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| function           | department     | program_name          | cost_center_name | fund_type           | fund_subtype | subfund_name | fund_name    | personnel_costs_operating_expenses | object_name                             | account_name                        | amount    | 
| ================== | ============== | ===================== | ================ | =================== | ============ | ============ | ============ | ================================== | ======================================= | =================================== | ========= | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Salaries and Wages                      | Seasonal Temps                      | 1000.00   | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Salaries and Wages                      | Budget Adjustment (Salary)          | 108480.00 | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Salaries and Wages                      | Lapse (Planning)                    | -83750.00 | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Social Security                         | Other Non-Workforce FICA            | -6330.38  | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Group Insurance                         | Other Non-Workforce Group Insurance | -12562.50 | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Personnel Costs                    | Retirement                              | Other Non-Workforce Retirement      | -10133.75 | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Operating Expenses                 | Contract and Services                   | Professional Purchase Of Service    | 100000.00 | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Operating Expenses                 | Office Supplies/Equipment(5000 or Less) | General Office Supplies             | 10000.00  | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Operating Expenses                 | Office Supplies/Equipment(5000 or Less) | Computer Equip-Non Capitalized      | 5000.00   | 
| General Government | County Council | Councilmember Offices | Council Members  | Tax Supported Funds | General Fund | General Fund | General Fund | Operating Expenses                 | Office Supplies/Equipment(5000 or Less) | Other Supplies & Equipment          | 1000.00   | 
```