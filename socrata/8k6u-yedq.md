# Fiscal Year 2015 County Executive Recommended Operating Budget ? Internal Service Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2015-county-executive-recommended-operating-budget-internal-service-funds-0ba5a) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/8k6u-yedq) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/8k6u-yedq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/8k6u-yedq/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 8k6u-yedq |
| Name | Fiscal Year 2015 County Executive Recommended Operating Budget ? Internal Service Funds |
| Category | Finance/Tax/Property |
| Tags | financial budget, internal, service, funds |
| Created | 2014-05-02T19:11:11Z |
| Publication Date | 2014-05-02T19:29:30Z |

## Description

This dataset includes the Internal Service Fund data included in the annual operating budget. Internal Service Funds (ISF) are proprietary funds used to record activity (primarily goods and services) provided by one department to other departments of the County government on a cost-reimbursable basis. The County uses this type of fund to account for Motor Pool, Central Duplicating, Liability and Property Coverage Self-Insurance, and Employee Health Benefits Self-Insurance. Update Frequency: Annually

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
series e:8k6u-yedq d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Personnel Costs" t:fund_name="Motor Pool" t:fund_type="Non-Tax Supported Funds" t:cost_center_name="Division Chief/Management" t:subfund_name="Motor Pool" t:department="General Services" t:program_name="Management Services" t:object_name="Salaries and Wages" t:fund_subtype="Internal Service Funds" t:account_name="Other Budgeted Salary Adjustment" t:function="General Government" m:amount=64399

series e:8k6u-yedq d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Personnel Costs" t:fund_name="Motor Pool" t:fund_type="Non-Tax Supported Funds" t:cost_center_name="Division Chief/Management" t:subfund_name="Motor Pool" t:department="General Services" t:program_name="Management Services" t:object_name="Salaries and Wages" t:fund_subtype="Internal Service Funds" t:account_name="Other Compensation Adj-OMB Use only" t:function="General Government" m:amount=24040

series e:8k6u-yedq d:2015-01-01T00:00:00.000Z t:personnel_costs_amp_operating_expenses="Personnel Costs" t:fund_name="Motor Pool" t:fund_type="Non-Tax Supported Funds" t:cost_center_name="Division Chief/Management" t:subfund_name="Motor Pool" t:department="General Services" t:program_name="Management Services" t:object_name="Salaries and Wages" t:fund_subtype="Internal Service Funds" t:account_name=Overtime t:function="General Government" m:amount=14485
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Dollar amount allocated." t:dataTypeName=money

entity e:8k6u-yedq l:"Fiscal Year 2015 County Executive Recommended Operating Budget ? Internal Service Funds" t:url=https://data.montgomerycountymd.gov/api/views/8k6u-yedq

property e:8k6u-yedq t:meta.view v:id=8k6u-yedq v:category=Finance/Tax/Property v:averageRating=0 v:name="Fiscal Year 2015 County Executive Recommended Operating Budget ? Internal Service Funds"

property e:8k6u-yedq t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:8k6u-yedq t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| function           | department       | program_name        | cost_center_name          | fund_type               | fund_subtype           | subfund_name | fund_name  | personnel_costs_amp_operating_expenses | object_name                             | account_name                        | amount             | 
| ================== | ================ | =================== | ========================= | ======================= | ====================== | ============ | ========== | ====================================== | ======================================= | =================================== | ================== | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Personnel Costs                        | Salaries and Wages                      | Other Budgeted Salary Adjustment    | 64399              | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Personnel Costs                        | Salaries and Wages                      | Other Compensation Adj-OMB Use only | 24040              | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Personnel Costs                        | Salaries and Wages                      | Overtime                            | 14485              | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Personnel Costs                        | Social Security                         | Other Non-Workforce FICA            | 1108.0999999999999 | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Contract and Services                   | Maint - Janitorial                  | 854541             | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Contract and Services                   | Maint Agmt - Building Equip         | 335546             | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Contract and Services                   | Hazardous Waste Handling            | 1650               | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Maintenance                             | Other Equip Repair/Maint            | 25000              | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Office Supplies/Equipment(5000 or Less) | General Office Supplies             | 47320              | 
| General Government | General Services | Management Services | Division Chief/Management | Non-Tax Supported Funds | Internal Service Funds | Motor Pool   | Motor Pool | Operating Expenses                     | Medical/Health Supplies                 | Other Medical/Health Supplies       | 10000              | 
```