# Open Budget Application: Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-operating-budget) |
| Metadata | [Link](https://data.seattle.gov/api/views/qqa2-kmne) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qqa2-kmne/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qqa2-kmne/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qqa2-kmne |
| Name | Open Budget Application: Operating Budget |
| Attribution | City Budget Office |
| Category | Finance |
| Created | 2016-08-11T18:56:00Z |
| Publication Date | 2016-09-27T18:53:27Z |

## Description

data powering openbudget.seattle.gov

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | fiscal_year  | Fiscal Year  | number    | number      |
| Yes      | series tag     | service      | Service      | text      | text        |
| Yes      | series tag     | department   | Department   | text      | text        |
| Yes      | series tag     | program      | Program      | text      | text        |
| Yes      | series tag     | description  | Description  | text      | text        |
| Yes      | series tag     | fund         | Fund         | text      | text        |
| Yes      | series tag     | fund_type    | Fund Type    | text      | text        |
| Yes      | series tag     | expense_type | Expense Type | text      | text        |
| Yes      | numeric metric | amount       | Amount       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qqa2-kmne d:2010-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Support to Multi-Purpose Trails" t:program="Support to Multi-Purpose Trails" t:department="2008 Parks Levy" t:service="Arts, Culture & Recreation" t:fund="General Fund" m:amount=3500000

series e:qqa2-kmne d:2010-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Administrative Services - AT" t:program="Arts Account" t:department="Arts and Culture" t:service="Arts, Culture & Recreation" t:fund="General Fund" m:amount=462514.59

series e:qqa2-kmne d:2010-01-01T00:00:00.000Z t:fund_type="Tax-Supported Fund" t:expense_type="Operating Expense" t:description="Arts Account" t:program="Arts Account" t:department="Arts and Culture" t:service="Arts, Culture & Recreation" t:fund="General Fund" m:amount=1207454
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=number

entity e:qqa2-kmne l:"Open Budget Application: Operating Budget" t:attribution="City Budget Office" t:url=https://data.seattle.gov/api/views/qqa2-kmne

property e:qqa2-kmne t:meta.view v:id=qqa2-kmne v:category=Finance v:averageRating=0 v:name="Open Budget Application: Operating Budget" v:attribution="City Budget Office"

property e:qqa2-kmne t:meta.view.license v:name="Public Domain"

property e:qqa2-kmne t:meta.view.owner v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:displayName="Kirk, Daniel"

property e:qqa2-kmne t:meta.view.tableauthor v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:roleName=administrator v:displayName="Kirk, Daniel"
```

## Top Records

```ls
| fiscal_year | service                    | department       | program                         | description                             | fund         | fund_type          | expense_type      | amount     | 
| =========== | ========================== | ================ | =============================== | ======================================= | ============ | ================== | ================= | ========== | 
| 2010        | Arts, Culture & Recreation | 2008 Parks Levy  | Support to Multi-Purpose Trails | Support to Multi-Purpose Trails         | General Fund | Tax-Supported Fund | Operating Expense | 3500000.00 | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | Arts Account                    | Administrative Services - AT            | General Fund | Tax-Supported Fund | Operating Expense | 462514.59  | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | Arts Account                    | Arts Account                            | General Fund | Tax-Supported Fund | Operating Expense | 1207454.00 | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | Arts Account                    | Community Development and Outreach - AT | General Fund | Tax-Supported Fund | Operating Expense | 507296.74  | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | Arts Account                    | Cultural Partnerships - AT              | General Fund | Tax-Supported Fund | Operating Expense | 1502208.74 | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | General Subfund                 | Administrative Services - GF            | General Fund | Tax-Supported Fund | Operating Expense | 0.00       | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | General Subfund                 | Community Development and Outreach - GF | General Fund | Tax-Supported Fund | Operating Expense | 0.00       | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | General Subfund                 | Cultural Partnerships - GF              | General Fund | Tax-Supported Fund | Operating Expense | 0.00       | 
| 2010        | Arts, Culture & Recreation | Arts and Culture | Municipal Arts Fund             | Municipal Arts Fund                     | General Fund | Tax-Supported Fund | Operating Expense | 2754881.88 | 
| 2010        | Administration             | Auditor          | Office of City Auditor          | Office of City Auditor                  | General Fund | Tax-Supported Fund | Operating Expense | 1167986.61 | 
```