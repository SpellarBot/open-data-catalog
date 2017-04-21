# State of Iowa Budget Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-budget-dispositions-by-fiscal-year-and-budget-org-unit) |
| Metadata | [Link](https://data.iowa.gov/api/views/hqz2-xt9r) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hqz2-xt9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hqz2-xt9r/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hqz2-xt9r |
| Name | State of Iowa Budget Expenditures |
| Attribution | Iowa Department of Management, I3 Budget System |
| Category | Government |
| Tags | financial, budget, expenditures |
| Created | 2014-11-13T20:22:40Z |
| Publication Date | 2017-01-17T20:56:01Z |

## Description

This dataset provides information on budgeted expenditures by fiscal year starting in FY 2010. The data provides granular detail down to the budget organizational unit and and object class for the department request, the Governor's recommendation, and the adopted budget.

The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends. The State of Iowa operates on a modified accrual basis which provides that encumbrances on June 30 must be paid within 60 days after year end. The Legislature may enact exceptions to this statute and usually do so for capital items which may run for several years.

Department names and budget units for FY 2010 - 2015 are based on names used in FY 2016.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                       | Data Type | Render Type |
| ======== | ============== | ================== | ========================== | ========= | =========== |
| Yes      | series tag     | budget_line_code   | Budget Line Code           | text      | text        |
| Yes      | time           | fiscal_year        | Fiscal Year                | number    | number      |
| Yes      | series tag     | function           | Function                   | text      | text        |
| Yes      | series tag     | dept_name          | Department Name            | text      | text        |
| Yes      | series tag     | fund               | Fund                       | text      | text        |
| Yes      | series tag     | appropriation      | Appropriation              | text      | text        |
| Yes      | series tag     | budget_unit_code   | Budget Unit Code           | text      | text        |
| Yes      | series tag     | budget_unit        | Budget Unit                | text      | text        |
| Yes      | series tag     | object_class       | Object Class               | text      | text        |
| Yes      | numeric metric | gov_recommendation | Governor's Recommendations | money     | money       |
| Yes      | numeric metric | dept_request       | Department Request         | money     | money       |
| Yes      | numeric metric | adopted_budget     | Adopted Budget             | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hqz2-xt9r d:2010-01-01T00:00:00.000Z t:budget_line_code=2010-0001-0C85-0051000-101 t:appropriation="0C85 - Administrative Services, Dept." t:budget_unit_code=0051000 t:object_class="101 - Personal Services-Salaries" t:budget_unit=Leadership t:fund="0001 - General Fund" t:dept_name="Administrative Services, Department of" t:function="Administration and Regulation" m:gov_recommendation=657795 m:dept_request=657795 m:adopted_budget=472119

series e:hqz2-xt9r d:2010-01-01T00:00:00.000Z t:budget_line_code=2010-0001-0C85-0051000-202 t:appropriation="0C85 - Administrative Services, Dept." t:budget_unit_code=0051000 t:object_class="202 - Personal Travel In State" t:budget_unit=Leadership t:fund="0001 - General Fund" t:dept_name="Administrative Services, Department of" t:function="Administration and Regulation" m:gov_recommendation=1921 m:dept_request=1921 m:adopted_budget=1921

series e:hqz2-xt9r d:2010-01-01T00:00:00.000Z t:budget_line_code=2010-0001-0C85-0051000-205 t:appropriation="0C85 - Administrative Services, Dept." t:budget_unit_code=0051000 t:object_class="205 - Personal Travel Out of State" t:budget_unit=Leadership t:fund="0001 - General Fund" t:dept_name="Administrative Services, Department of" t:function="Administration and Regulation" m:gov_recommendation=9500 m:dept_request=9500 m:adopted_budget=2000
```

## Meta Commands

```ls
metric m:gov_recommendation p:long l:"Governor's Recommendations" d:"Governor's budget recommendations submitted to the Legislature." t:dataTypeName=money

metric m:dept_request p:long l:"Department Request" d:"Department request submitted to the Department of Management." t:dataTypeName=money

metric m:adopted_budget p:long l:"Adopted Budget" d:"Budget which has been updated and made ready for the financial system for monitoring purposes" t:dataTypeName=money

entity e:hqz2-xt9r l:"State of Iowa Budget Expenditures" t:attribution="Iowa Department of Management, I3 Budget System" t:url=https://data.iowa.gov/api/views/hqz2-xt9r

property e:hqz2-xt9r t:meta.view v:id=hqz2-xt9r v:category=Government v:averageRating=0 v:name="State of Iowa Budget Expenditures" v:attribution="Iowa Department of Management, I3 Budget System"

property e:hqz2-xt9r t:meta.view.license v:name="Public Domain"

property e:hqz2-xt9r t:meta.view.owner v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:displayName="IDOM, State Budget"

property e:hqz2-xt9r t:meta.view.tableauthor v:id=bnfb-vany v:profileImageUrlMedium=/api/users/bnfb-vany/profile_images/THUMB v:profileImageUrlLarge=/api/users/bnfb-vany/profile_images/LARGE v:screenName="IDOM, State Budget" v:profileImageUrlSmall=/api/users/bnfb-vany/profile_images/TINY v:roleName=editor v:displayName="IDOM, State Budget"
```

## Top Records

```ls
| budget_line_code           | fiscal_year | function                      | dept_name                              | fund                | appropriation                         | budget_unit_code | budget_unit | object_class                             | gov_recommendation | dept_request | adopted_budget | 
| ========================== | =========== | ============================= | ====================================== | =================== | ===================================== | ================ | =========== | ======================================== | ================== | ============ | ============== | 
| 2010-0001-0C85-0051000-101 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 101 - Personal Services-Salaries         | 657795             | 657795       | 472119         | 
| 2010-0001-0C85-0051000-202 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 202 - Personal Travel In State           | 1921               | 1921         | 1921           | 
| 2010-0001-0C85-0051000-205 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 205 - Personal Travel Out of State       | 9500               | 9500         | 2000           | 
| 2010-0001-0C85-0051000-301 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 301 - Office Supplies                    | 5100               | 5100         | 4500           | 
| 2010-0001-0C85-0051000-309 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 309 - Printing & Binding                 | 2143               | 2143         | 50             | 
| 2010-0001-0C85-0051000-313 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 313 - Postage                            | 227                | 227          | 229            | 
| 2010-0001-0C85-0051000-401 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 401 - Communications                     | 13655              | 13655        | 8460           | 
| 2010-0001-0C85-0051000-402 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 402 - Rentals                            | 7000               | 7000         | 0              | 
| 2010-0001-0C85-0051000-405 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 405 - Professional & Scientific Services | 47901              | 47901        | 35000          | 
| 2010-0001-0C85-0051000-406 | 2010        | Administration and Regulation | Administrative Services, Department of | 0001 - General Fund | 0C85 - Administrative Services, Dept. | 0051000          | Leadership  | 406 - Outside Services                   | 8517               | 8517         | 7200           | 
```