# Fiscal Year 2013 Budget - Internal Service Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2013-budget-internal-service-funds-7af88) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qgb4-jpr6) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qgb4-jpr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qgb4-jpr6/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qgb4-jpr6 |
| Name | Fiscal Year 2013 Budget - Internal Service Funds |
| Category | Government |
| Tags | budget, internal, service, funds, internal service funds |
| Created | 2012-10-23T15:07:31Z |
| Publication Date | 2012-10-24T17:30:30Z |

## Description

This dataset includes the Internal Service Fund data included in the annual operating budget.  Internal Service Funds (ISF) are proprietary funds used to record activity (primarily goods and services) provided by one department to other departments of the County government on a cost-reimbursable basis.  The County uses this type of fund to account for Motor Pool, Central Duplicating, Liability and Property Coverage Self-Insurance, and Employee Health Benefits Self-Insurance.

Update Frequency:  Annual

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| Yes      | series tag     | function                     | Function                       | text      | text        |
| Yes      | series tag     | department                   | Department                     | text      | text        |
| Yes      | series tag     | program_name                 | Program Name                   | text      | text        |
| Yes      | series tag     | cost_center_name             | Cost Center Name               | text      | text        |
| Yes      | series tag     | fund_type                    | Fund Type                      | text      | text        |
| Yes      | series tag     | fund_subtype                 | Fund Subtype                   | text      | text        |
| Yes      | series tag     | fund_subfund                 | Fund Subfund                   | text      | text        |
| Yes      | series tag     | fund                         | Fund                           | text      | text        |
| Yes      | series tag     | personnel_operating_expenses | Personnel & Operating Expenses | text      | text        |
| Yes      | series tag     | object_name                  | Object Name                    | text      | text        |
| Yes      | numeric metric | amount                       | Amount                         | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qgb4-jpr6 d:2013-01-01T00:00:00.000Z t:fund_type="Non-Tax Supported Funds" t:fund_subfund="Central Duplicating" t:cost_center_name="Central Dup - Section Chief" t:department="General Services" t:program_name="Central Duplicating, Imaging, Archiving, & Mail Sv" t:object_name="Contract and Services" t:fund="Central Duplicating" t:fund_subtype="Internal Service Funds" t:personnel_operating_expenses="Operating Expenses" t:function="General Government" m:amount=10000

series e:qgb4-jpr6 d:2013-01-01T00:00:00.000Z t:fund_type="Non-Tax Supported Funds" t:fund_subfund="Central Duplicating" t:cost_center_name="Central Dup - Section Chief" t:department="General Services" t:program_name="Central Duplicating, Imaging, Archiving, & Mail Sv" t:object_name="Insurance (Non-Fringe Benefits)" t:fund="Central Duplicating" t:fund_subtype="Internal Service Funds" t:personnel_operating_expenses="Operating Expenses" t:function="General Government" m:amount=42160

series e:qgb4-jpr6 d:2013-01-01T00:00:00.000Z t:fund_type="Non-Tax Supported Funds" t:fund_subfund="Central Duplicating" t:cost_center_name="Central Dup - Section Chief" t:department="General Services" t:program_name="Central Duplicating, Imaging, Archiving, & Mail Sv" t:object_name="Miscellaneous Operating Expenses" t:fund="Central Duplicating" t:fund_subtype="Internal Service Funds" t:personnel_operating_expenses="Operating Expenses" t:function="General Government" m:amount=140280
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:qgb4-jpr6 l:"Fiscal Year 2013 Budget - Internal Service Funds" t:url=https://data.montgomerycountymd.gov/api/views/qgb4-jpr6

property e:qgb4-jpr6 t:meta.view v:id=qgb4-jpr6 v:category=Government v:averageRating=0 v:name="Fiscal Year 2013 Budget - Internal Service Funds"

property e:qgb4-jpr6 t:meta.view.owner v:id=fnci-gphj v:screenName="MC Open Data" v:displayName="MC Open Data"

property e:qgb4-jpr6 t:meta.view.tableauthor v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```

## Top Records

```ls
| function           | department       | program_name                                       | cost_center_name            | fund_type               | fund_subtype           | fund_subfund        | fund                | personnel_operating_expenses | object_name                             | amount    | 
| ================== | ================ | ================================================== | =========================== | ======================= | ====================== | =================== | =================== | ============================ | ======================================= | ========= | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Contract and Services                   | 10000.00  | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Insurance (Non-Fringe Benefits)         | 42160.00  | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Miscellaneous Operating Expenses        | 140280.00 | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Motor Pool                              | 250.00    | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Office Supplies/Equipment(5000 or Less) | 1000.00   | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Operating Expenses           | Phones/Telecommunication Services       | 2840.00   | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Personnel Costs              | Group Insurance                         | 24240.00  | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Personnel Costs              | Retirement                              | 24847.00  | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Personnel Costs              | Salaries and Wages                      | 163264.00 | 
| General Government | General Services | Central Duplicating, Imaging, Archiving, & Mail Sv | Central Dup - Section Chief | Non-Tax Supported Funds | Internal Service Funds | Central Duplicating | Central Duplicating | Personnel Costs              | Social Security                         | 11526.00  | 
```