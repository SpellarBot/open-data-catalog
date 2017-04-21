# FY2015 Budget By Line Item

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-budget-by-line-item-ef703) |
| Metadata | [Link](https://data.illinois.gov/api/views/atbf-3t6d) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/atbf-3t6d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/atbf-3t6d/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | atbf-3t6d |
| Name | FY2015 Budget By Line Item |
| Attribution | Governor's Office of Management and Budget |
| Category | Reference |
| Tags | illinois, fy2015, budget, gomb |
| Created | 2014-04-09T19:31:37Z |
| Publication Date | 2014-04-09T20:02:31Z |

## Description

This dataset contains the Fiscal Year 2015 operations budget with historical and proposed appropriations for state budgeted entities by line item. The file is provided by the Governor?s Office of Management and Budget and is available at the following websites: Budget.Illinois.gov or http://www.state.il.us/budget/).

The first twelve (12) columns contain the appropriation code, the agency number designator, the agency name, the agency division name, the appropriation name, the appropriation number, the fund from which the appropriation is made, the fund number, the fund category, the appropriation type, and whether or not the appropriation is capital expenditure.

The remaining columns contain the appropriation amounts ($ thousands) for fiscal years 2013 and 2014, and recommended and not recommended appropriations for fiscal year 2015.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | approp_code             | Approp Code             | text      | text        |
| Yes      | series tag     | agency                  | Agency                  | text      | text        |
| Yes      | series tag     | agency_name             | Agency Name             | text      | text        |
| Yes      | numeric metric | division                | Division                | number    | text        |
| Yes      | series tag     | division_name           | Division Name           | text      | text        |
| Yes      | series tag     | appropriation_name      | Appropriation Name      | text      | text        |
| Yes      | numeric metric | appropriation           | Appropriation           | number    | text        |
| Yes      | series tag     | fund_name               | Fund Name               | text      | text        |
| Yes      | numeric metric | fund                    | Fund                    | number    | text        |
| Yes      | series tag     | fund_category_name      | Fund Category Name      | text      | text        |
| Yes      | series tag     | appropriation_type      | Appropriation Type      | text      | text        |
| Yes      | series tag     | capital_line            | Capital Line            | text      | text        |
| Yes      | numeric metric | fy13_actual_approp      | FY13 Actual Approp      | number    | number      |
| Yes      | numeric metric | fy13_actual_expend      | FY13 Actual Expend      | number    | number      |
| Yes      | numeric metric | fy14_actual_approp      | FY14 Actual Approp      | number    | number      |
| Yes      | numeric metric | fy14_estimate_expend    | FY14 Estimate Expend    | number    | number      |
| Yes      | numeric metric | fy15_governors_proposed | FY15 Governors Proposed | number    | number      |
| Yes      | numeric metric | fy_15_not_recommended   | FY 15 Not Recommended   | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:atbf-3t6d d:2015-01-01T00:00:00.000Z t:fund_name="General Revenue Fund" t:approp_code=101-10-0001-19100100 t:appropriation_name="Ordinary and Contingent Expenses of Legislative Leadership and Legislative Staff Assistants: President of the Senate" t:capital_line=n t:agency=101 t:agency_name="General Assembly" t:division_name="Senate Expenses" t:fund_category_name="General Funds" t:appropriation_type="New Appropriation" m:division=10 m:fy13_actual_expend=4130133.04 m:appropriation=19100100 m:fy14_estimate_expend=4183100 m:fy15_governors_proposed=5295074 m:fund=1 m:fy_15_not_recommended=4518700 m:fy13_actual_approp=5295074 m:fy14_actual_approp=5295074

series e:atbf-3t6d d:2015-01-01T00:00:00.000Z t:fund_name="General Revenue Fund" t:approp_code=101-10-0001-19100200 t:appropriation_name="Ordinary and Contingent Expenses of Legislative Leadership and Legislative Staff Assistants: Senate Minority Leader" t:capital_line=n t:agency=101 t:agency_name="General Assembly" t:division_name="Senate Expenses" t:fund_category_name="General Funds" t:appropriation_type="New Appropriation" m:division=10 m:fy13_actual_expend=4091877.97 m:appropriation=19100200 m:fy14_estimate_expend=4130200 m:fy15_governors_proposed=5295074 m:fund=1 m:fy_15_not_recommended=4518700 m:fy13_actual_approp=5295074 m:fy14_actual_approp=5295074

series e:atbf-3t6d d:2015-01-01T00:00:00.000Z t:fund_name="General Revenue Fund" t:approp_code=101-10-0001-19100300 t:appropriation_name="Ordinary and Incidental Expenses of Committees, General Staff and Operations, Transcribing and Printing of Senate Debates" t:capital_line=n t:agency=101 t:agency_name="General Assembly" t:division_name="Senate Expenses" t:fund_category_name="General Funds" t:appropriation_type="New Appropriation" m:division=10 m:fy13_actual_expend=2720158.35 m:appropriation=19100300 m:fy14_estimate_expend=2720700 m:fy15_governors_proposed=4251082 m:fund=1 m:fy_15_not_recommended=3627800 m:fy13_actual_approp=4251082 m:fy14_actual_approp=4251082
```

## Meta Commands

```ls
metric m:division p:integer l:Division t:dataTypeName=number

metric m:appropriation p:integer l:Appropriation t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy13_actual_approp p:double l:"FY13 Actual Approp" t:dataTypeName=number

metric m:fy13_actual_expend p:double l:"FY13 Actual Expend" t:dataTypeName=number

metric m:fy14_actual_approp p:double l:"FY14 Actual Approp" t:dataTypeName=number

metric m:fy14_estimate_expend p:double l:"FY14 Estimate Expend" t:dataTypeName=number

metric m:fy15_governors_proposed p:double l:"FY15 Governors Proposed" t:dataTypeName=number

metric m:fy_15_not_recommended p:double l:"FY 15 Not Recommended" t:dataTypeName=number

entity e:atbf-3t6d l:"FY2015 Budget By Line Item" t:attribution="Governor's Office of Management and Budget" t:url=https://data.illinois.gov/api/views/atbf-3t6d

property e:atbf-3t6d t:meta.view v:id=atbf-3t6d v:category=Reference v:attributionLink=http://www.state.il.us/budget/ v:averageRating=0 v:name="FY2015 Budget By Line Item" v:attribution="Governor's Office of Management and Budget"

property e:atbf-3t6d t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:atbf-3t6d t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| approp_code          | agency | agency_name      | division | division_name   | appropriation_name                                                                                                                         | appropriation | fund_name            | fund | fund_category_name | appropriation_type | capital_line | fy13_actual_approp | fy13_actual_expend | fy14_actual_approp | fy14_estimate_expend | fy15_governors_proposed | fy_15_not_recommended | 
| ==================== | ====== | ================ | ======== | =============== | ========================================================================================================================================== | ============= | ==================== | ==== | ================== | ================== | ============ | ================== | ================== | ================== | ==================== | ======================= | ===================== | 
| 101-10-0001-19100100 | 101    | General Assembly | 10       | Senate Expenses | Ordinary and Contingent Expenses of Legislative Leadership and Legislative Staff Assistants: President of the Senate                       | 19100100      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 5295074.00         | 4130133.04         | 5295074.00         | 4183100.00           | 5295074.00              | 4518700.00            | 
| 101-10-0001-19100200 | 101    | General Assembly | 10       | Senate Expenses | Ordinary and Contingent Expenses of Legislative Leadership and Legislative Staff Assistants: Senate Minority Leader                        | 19100200      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 5295074.00         | 4091877.97         | 5295074.00         | 4130200.00           | 5295074.00              | 4518700.00            | 
| 101-10-0001-19100300 | 101    | General Assembly | 10       | Senate Expenses | Ordinary and Incidental Expenses of Committees, General Staff and Operations, Transcribing and Printing of Senate Debates                  | 19100300      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 4251082.00         | 2720158.35         | 4251082.00         | 2720700.00           | 4251082.00              | 3627800.00            | 
| 101-10-0001-19100400 | 101    | General Assembly | 10       | Senate Expenses | Construct/Reconstruct Senate Offices (to Senate Operations Commission)                                                                     | 19100400      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 113700.00          | 17580.91           | 113700.00          | 15900.00             | 113700.00               | 97000.00              | 
| 101-10-0001-19100500 | 101    | General Assembly | 10       | Senate Expenses | Ordinary and Incidental Expenses of Senate, Including Purchase of Contract Printing, Binding, and Office Supplies: President of the Senate | 19100500      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 214204.00          | 157269.32          | 214204.00          | 107100.00            | 214204.00               | 182800.00             | 
| 101-10-0001-19100600 | 101    | General Assembly | 10       | Senate Expenses | Allowances for Services of Officers of Senate: President                                                                                   | 19100600      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 83500.00           |                    | 83500.00           |                      | 83500.00                | 71300.00              | 
| 101-10-0001-19100700 | 101    | General Assembly | 10       | Senate Expenses | Allowances for Services of Officers of Senate: Minority Leader                                                                             | 19100700      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 83500.00           | 30000.00           | 83500.00           | 56800.00             | 83500.00                | 71300.00              | 
| 101-10-0001-19100800 | 101    | General Assembly | 10       | Senate Expenses | Travel, Including Expenses to Springfield for Official Business when General Assembly is not in Session: President of the Senate           | 19100800      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 57706.00           | 1296.12            | 57706.00           | 3000.00              | 57706.00                | 49200.00              | 
| 101-10-0001-19100900 | 101    | General Assembly | 10       | Senate Expenses | President of the Senate                                                                                                                    | 19100900      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 4900765.00         | 4482600.99         | 4900765.00         | 4508700.00           | 4900765.00              | 4182200.00            | 
| 101-10-0001-19101000 | 101    | General Assembly | 10       | Senate Expenses | Standing Committees for Expert Witnesses, Technical Service and Other Research Assistance: President of the Senate                         | 19101000      | General Revenue Fund | 1    | General Funds      | New Appropriation  | n            | 3038087.00         | 1980003.31         | 3038087.00         | 2187400.00           | 3038087.00              | 2592600.00            | 
```