# FY 2016 Proposed Operating Budget Expenditures ? Line Item Detail

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/c9gq-k8de/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/fy-2016-proposed-operating-budget-expenditures-line-item-detail)
* Id = c9gq-k8de
* Name = FY 2016 Proposed Operating Budget Expenditures ? Line Item Detail
* Attribution = City of Austin
* Category = Government
* Tags = [proposed budget]
* Created = 2015-08-14T21:37:06Z
* Publication Date = 2015-08-14T21:52:16Z
* Rows Updated = 2015-08-14T21:44:36Z

## Description

City of Austin FY 2016 Proposed operating budget showing expenditures by line item detail. The Proposed Budget is at the Fund, Department, Program, Activity, Unit and Expense Code level. The information contained in this data set is for informational purposes for viewing and downloading and includes personnel, contractual and commodities. Certain Austin Energy budget items have been excluded as competitive matters under Texas Government Code Section 552.133 and City Council Resolution 20051201-002.

## Columns

```ls
| Name                 | Field Name           | Data Type | Render Type | Schema Type    | Included | 
| ==================== | ==================== | ========= | =========== | ============== | ======== | 
| PROPOSED_FISCAL_YEAR | proposed_fiscal_year | number    | number      | time           | Yes      | 
| DEPT_ROLLUP          | dept_rollup          | number    | number      | numeric metric | Yes      | 
| DEPT_ROLLUP_NAME     | dept_rollup_name     | text      | text        | series tag     | Yes      | 
| DEPARTMENT_CODE      | department_code      | text      | number      | series tag     | Yes      | 
| DEPARTMENT_NAME      | department_name      | text      | text        | series tag     | Yes      | 
| FUND_CODE            | fund_code            | text      | number      | series tag     | Yes      | 
| FUND_NAME            | fund_name            | text      | text        | series tag     | Yes      | 
| PROGRAM_CODE         | program_code         | text      | text        | series tag     | Yes      | 
| PROGRAM_NAME         | program_name         | text      | text        | series tag     | Yes      | 
| ACTIVITY_CODE        | activity_code        | text      | text        | series tag     | Yes      | 
| ACTIVITY_NAME        | activity_name        | text      | text        | series tag     | Yes      | 
| UNIT_CODE            | unit_code            | text      | number      | series tag     | Yes      | 
| UNIT_NAME            | unit_name            | text      | text        | series tag     | Yes      | 
| EXPENSE_CODE         | expense_code         | text      | number      | series tag     | Yes      | 
| EXPENSE_NAME         | expense_name         | text      | text        | series tag     | Yes      | 
| PROPOSED_BUDGET      | proposed_budget      | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = proposed_fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:fund_code=1000 t:expense_name="Regular wages - full-time" t:program_code=2ANL t:program_name="Animal Services" t:dept_rollup_name="Animal Services" t:expense_code=5001 t:activity_name="Field Services" t:activity_code=2FDS t:fund_name="General Fund" t:department_code=9200 t:department_name="Animal Services" t:unit_name="Animal Protection" t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=806489

series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:fund_code=1000 t:expense_name="Regular wages - part-time" t:program_code=2ANL t:program_name="Animal Services" t:dept_rollup_name="Animal Services" t:expense_code=5002 t:activity_name="Field Services" t:activity_code=2FDS t:fund_name="General Fund" t:department_code=9200 t:department_name="Animal Services" t:unit_name="Animal Protection" t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=17879

series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:fund_code=1000 t:expense_name=Overtime t:program_code=2ANL t:program_name="Animal Services" t:dept_rollup_name="Animal Services" t:expense_code=5005 t:activity_name="Field Services" t:activity_code=2FDS t:fund_name="General Fund" t:department_code=9200 t:department_name="Animal Services" t:unit_name="Animal Protection" t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=45664
```

## Meta Commands

```ls
metric m:dept_rollup p:integer l:DEPT_ROLLUP t:dataTypeName=number

metric m:proposed_budget l:PROPOSED_BUDGET t:dataTypeName=number

entity e:c9gq-k8de l:"FY 2016 Proposed Operating Budget Expenditures ? Line Item Detail" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/c9gq-k8de

property e:c9gq-k8de t:meta.view d:2017-03-03T13:54:44.904Z v:id=c9gq-k8de v:category=Government v:averageRating=0 v:name="FY 2016 Proposed Operating Budget Expenditures ? Line Item Detail" v:attribution="City of Austin"

property e:c9gq-k8de t:meta.view.license d:2017-03-03T13:54:44.904Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:c9gq-k8de t:meta.view.owner d:2017-03-03T13:54:44.904Z v:id=mx9i-sxdu v:screenName="FSD - Controller's Office" v:roleName=publisher v:displayName="FSD - Controller's Office"

property e:c9gq-k8de t:meta.view.tableauthor d:2017-03-03T13:54:44.904Z v:id=mx9i-sxdu v:screenName="FSD - Controller's Office" v:roleName=publisher v:displayName="FSD - Controller's Office"
```