# Program Budget Operating Budget Vs Expense Raw Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/program-budget-operating-budget-vs-expense-raw-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/g5k8-8sud) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/g5k8-8sud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/g5k8-8sud/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | g5k8-8sud |
| Name | Program Budget Operating Budget Vs Expense Raw Data |
| Attribution | Communication and Technology Management |
| Category | Financial |
| Tags | budget, operating, proposed, actual, expenditures, finance, financial, reports, financial services, budget office, city of austin, austin, austin finance online, raw budget data, budget documents,... |
| Created | 2013-06-13T18:29:22Z |
| Publication Date | 2014-10-09T12:36:29Z |

## Description

City of Austin current budget fiscal year Operating Budget showing budget versus expenditures.  This budget is at the Fund, Department, Unit level.  This data set includes a build date and will be updated on a quarterly basis.  The data contained in this data set is for informational purposes. Certain Austin Energy budget items have been excluded as competitive matters under Texas Government Code Section 552.133 and City Council Resolution 20051201-002.

The comparison of actual expenditures to budget may appear inconsistent. That is because base wages for personnel are fully budgeted in the expense categories regular wages?full-time, regular wages?part-time or regular wages?civil service. The budget does not assume expenditure levels for the various leave categories, such as sick pay, vacation pay, or jury leave. However, actual expenses for various leave categories are recorded based on timesheet coding. The result is that actual expenditures for regular wages are spread across multiple expense categories while the budget is shown in one expense category.

Personnel savings is budgeted to account for the likely savings in personnel costs generated through attrition. However, the savings is realized in the expense categories regular wages?full-time, regular wages?part-time and regular wages?civil service. Therefore, the actual expenditures in the personnel savings expense category will always be zero.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | budget_fiscal_year | BUDGET_FISCAL_YEAR | number    | number      |
| No       |                | thru_quarter       | THRU_QUARTER       | number    | text        |
| Yes      | numeric metric | dept_rollup        | DEPT_ROLLUP        | number    | number      |
| Yes      | series tag     | dept_rollup_name   | DEPT_ROLLUP_NAME   | text      | text        |
| Yes      | series tag     | department_code    | DEPARTMENT_CODE    | text      | number      |
| Yes      | series tag     | department_name    | DEPARTMENT_NAME    | text      | text        |
| Yes      | series tag     | fund_code          | FUND_CODE          | text      | text        |
| Yes      | series tag     | fund_name          | FUND_NAME          | text      | text        |
| Yes      | series tag     | program_code       | PROGRAM_CODE       | text      | text        |
| Yes      | series tag     | program_name       | PROGRAM_NAME       | text      | text        |
| Yes      | series tag     | activity_code      | ACTIVITY_CODE      | text      | text        |
| Yes      | series tag     | activity_name      | ACTIVITY_NAME      | text      | text        |
| Yes      | series tag     | unit_code          | UNIT_CODE          | text      | text        |
| Yes      | series tag     | unit_name          | UNIT_NAME          | text      | text        |
| Yes      | series tag     | expense_code       | EXPENSE_CODE       | text      | text        |
| Yes      | series tag     | expense_name       | EXPENSE_NAME       | text      | text        |
| Yes      | numeric metric | budget             | BUDGET             | money     | money       |
| Yes      | numeric metric | expenditures       | EXPENDITURES       | money     | money       |
| Yes      | series tag     | key                | KEY                | text      | text        |
```

## Time Field

```ls
Value = budget_fiscal_year-thru_quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = budget_fiscal_year,thru_quarter
```

## Data Commands

```ls
series e:g5k8-8sud d:2017-04-01T00:00:00.000Z t:fund_code=5010 t:expense_name=Services-engineering t:program_code=1PSM t:program_name="Power Generation, Market Operations & Resource Planning" t:dept_rollup_name="Austin Energy" t:expense_code=5590 t:activity_name="Power Generation" t:activity_code=1GEN t:fund_name="Austin Energy Fund" t:department_code=1100 t:department_name="Austin Energy" t:unit_name="Environmental Projects" t:key=2017211110050101PSM1GEN13075590 t:unit_code=1307 m:dept_rollup=11 m:budget=210000 m:expenditures=31018.89

series e:g5k8-8sud d:2017-04-01T00:00:00.000Z t:fund_code=5010 t:expense_name="Services-hazardous mat disp" t:program_code=1PSM t:program_name="Power Generation, Market Operations & Resource Planning" t:dept_rollup_name="Austin Energy" t:expense_code=5600 t:activity_name="Power Generation" t:activity_code=1GEN t:fund_name="Austin Energy Fund" t:department_code=1100 t:department_name="Austin Energy" t:unit_name="Environmental Projects" t:key=2017211110050101PSM1GEN13075600 t:unit_code=1307 m:dept_rollup=11 m:budget=395000 m:expenditures=128177.58

series e:g5k8-8sud d:2017-04-01T00:00:00.000Z t:fund_code=5010 t:expense_name=Services-testing t:program_code=1PSM t:program_name="Power Generation, Market Operations & Resource Planning" t:dept_rollup_name="Austin Energy" t:expense_code=5730 t:activity_name="Power Generation" t:activity_code=1GEN t:fund_name="Austin Energy Fund" t:department_code=1100 t:department_name="Austin Energy" t:unit_name="Environmental Projects" t:key=2017211110050101PSM1GEN13075730 t:unit_code=1307 m:dept_rollup=11 m:budget=2000 m:expenditures=150.01
```

## Meta Commands

```ls
metric m:dept_rollup p:integer l:DEPT_ROLLUP d:"A department is a primary organizational unit used by the City of Austin. Examples of various departments are Parks and Recreation and Austin Police Department." t:dataTypeName=number

metric m:budget p:integer l:BUDGET t:dataTypeName=money

metric m:expenditures p:double l:EXPENDITURES t:dataTypeName=money

entity e:g5k8-8sud l:"Program Budget Operating Budget Vs Expense Raw Data" t:attribution="Communication and Technology Management" t:url=https://data.austintexas.gov/api/views/g5k8-8sud

property e:g5k8-8sud t:meta.view v:id=g5k8-8sud v:category=Financial v:averageRating=0 v:name="Program Budget Operating Budget Vs Expense Raw Data" v:attribution="Communication and Technology Management"

property e:g5k8-8sud t:meta.view.license v:name="Public Domain"

property e:g5k8-8sud t:meta.view.owner v:id=t5rb-t58r v:screenName=Chris v:displayName=Chris

property e:g5k8-8sud t:meta.view.tableauthor v:id=t5rb-t58r v:screenName=Chris v:roleName=publisher v:displayName=Chris
```

## Top Records

```ls
| budget_fiscal_year | thru_quarter | dept_rollup | dept_rollup_name | department_code | department_name | fund_code | fund_name          | program_code | program_name                                            | activity_code | activity_name    | unit_code | unit_name                      | expense_code | expense_name                | budget | expenditures | key                             | 
| ================== | ============ | =========== | ================ | =============== | =============== | ========= | ================== | ============ | ======================================================= | ============= | ================ | ========= | ============================== | ============ | =========================== | ====== | ============ | =============================== | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 5590         | Services-engineering        | 210000 | 31018.89     | 2017211110050101PSM1GEN13075590 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 5600         | Services-hazardous mat disp | 395000 | 128177.58    | 2017211110050101PSM1GEN13075600 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 5730         | Services-testing            | 2000   | 150.01       | 2017211110050101PSM1GEN13075730 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 5860         | Services-other              | 90000  | 1800         | 2017211110050101PSM1GEN13075860 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 6236         | Interdeptl-PW CPM charges   | 0      | 0            | 2017211110050101PSM1GEN13076236 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 6383         | Maintenance-buildings       | 20000  | 0            | 2017211110050101PSM1GEN13076383 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 6633         | Subscriptions               | 40000  | 29550        | 2017211110050101PSM1GEN13076633 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1307      | Environmental Projects         | 6843         | Government permits and fees | 2000   | 1126         | 2017211110050101PSM1GEN13076843 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1330      | Reliability Compliance Program | 5005         | Overtime                    | 0      | 200.03       | 2017211110050101PSM1GEN13305005 | 
| 2017               | 2            | 11          | Austin Energy    | 1100            | Austin Energy   | 5010      | Austin Energy Fund | 1PSM         | Power Generation, Market Operations & Resource Planning | 1GEN          | Power Generation | 1330      | Reliability Compliance Program | 5018         | Holidays worked             | 0      | 683.92       | 2017211110050101PSM1GEN13305018 | 
```